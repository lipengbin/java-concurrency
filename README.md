# java-concurrency
Java Concurrency Code Demo and Some Code Guide。 

## Java线程内存模型

<div align=center>
<img width="150" height="150" src="https://github.com/lipengbin/java-concurrency/master/javaMemeoryModel.png"/></div>
## 线程安全
原子性
- 提供了互斥访问，一个时间只允许一个线程来对其进行操作

可见性
- 一个线程对主内存的修改可以及时被其他线程观察到

有序性
- 一个线程观察其他线程中的指令的执行顺序，由于指令重拍的存在，该观察结果一般是杂乱无序的
