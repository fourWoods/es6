###Welcome to use MarkDown
Iterator的遍历过程：
1.创建一个指针对象，指向当前数据结构的起始位置，即Iterator遍历器本质上就是一个指针对象
2.第一次调用指针对象的next方法，可以将指针对象指向数据结构的第一个成员。
3.第二次调用指针对象的next方法，可以将指针对象指向数据结构的第二个成员。
4.依此类推，直到数据结构结束位置。
*.每次调用next方法会返回当前成员信息，即返回一个对象，包含value和done两个属性，
  value是当前成员的值，done是一个布尔值，用来判断遍历是否完成。
  
凡是具备Iterator的数据结构，都可以
1.进行解构赋值 2。扩展运算符（...） 3.for...of 循环

对象{} 不具备Iterator接口

