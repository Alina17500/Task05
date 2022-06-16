# Task05
Task05_num3

Задача 5.	Деревья


В некоторых вариантах данной задачи требуется реализовать дерево с количеством потомков больше 2-х. В этом случае для хранения в узле всех его потомков следует воспользоваться списком, можно стандартной реализаций (например, ArrayList<TreeNode<T>>), а еще лучше своей собственной реализацией связного списка (MyList<TreeNode<T>>). Ввод данных (построение дерева) имеет смысл сделать в виде разбора строки, описывающей дерево в скобочной нотации (разбиралась на лекции), но реализацию разбора потребуется чуть-чуть поправить для поддержки произвольного кол-ва потомков в узле. В этих задачах, вместо рисования дерева на форме можно распечатывать дерево (также может быть на форме - см. примеры) в следующем виде (слева представление дерева, справа пояснение, что это за дерево):

  A
  
  AB1
  
    AB1C1
  
    AB1C2
  
  AB2
  
    AB2C1
  
      AB2C1D1
  
  AB3	

Для остальных задач (двоичных деревьев) самым правильным подходом будет доработка демонстрационного проекта к лекциям TreeSamples (данных пример уже содержит реализацию различных двоичных деревьев, а также поддерживает возможность ввода дерева в виде скобочной последовательности и отрисовку дерева). Для задач, в которых это возможно, допускается использование в решении уже реализованных методов обхода деревьев (реализованы в виде default-методов интерфейса DefaultBinaryTree) с применением функций обратного вызова.
Естественно, при желании вы можете выполнить свою собственную реализацию дерева и демонстрационного проекта (также допускается воспользоваться реализациями деревьев, которые вы можете найти в сети Интернет).
В любом из этих случаев в вашем проекте должно присутствовать дерево, описанное в виде класса (Tree<T> / SimpleTree<T>), а для реализации дерева нужен будет класс узла дерева (TreeNode). Последний имеет смысл описывать в виде внутреннего класса дерева (в примерах к лекциям именно так и сделано). Непосредственно решение вашего варианта должно быть описано, как метод в класса дерева.
Если в условии задачи что-то непонятно – попросить пояснить преподавателя.
  
Варианты:
  
  3.	Реализовать функцию, которая изменить двоичное дерево следующим образом:	
Удалит все листья, которые не находятся на самом нижнем уровне двоичного дерева.
