# interview
阿里内推一面
##笔试
####选择题：
快速排序  
二叉树遍历  
UML类图  

####问答题：
1.Java中final，finally，finalize的区别  
2.hashmap的特性是什么，和hashtable的区别   
3.java线程中sleep和wait方法区别   
4.谈谈常用容器类的原理和应用场景   

##面试
1.一个文件中有100万个整数，由空格分开，在程序中判断用户输入的整数是否在此文件中。说出最优的方法
位方法

#金山一面
1.arraylist与vector的区别  
这两类都实现List接口，而List接口一共有三个实现类，分别是ArrayList、Vector和LinkedList。List用于存放多个元素，能够维护元素的次序，并且允许元素的重复。3个具体实现类的相关区别如下：
ArrayList是最常用的List实现类，内部是通过数组实现的，它允许对元素进行快速随机访问。数组的缺点是每个元素之间不能有间隔，当数组大小不满足时需要增加存储能力，就要讲已经有数组的数据复制到新的存储空间中。当从ArrayList的中间位置插入或者删除元素时，需要对数组进行复制、移动、代价比较高。因此，它适合随机查找和遍历，不适合插入和删除。
Vector与ArrayList一样，也是通过数组实现的，不同的是它支持线程的同步，即某一时刻只有一个线程能够写Vector，避免多线程同时写而引起的不一致性，但实现同步需要很高的花费，因此，访问它比访问ArrayList慢。
LinkedList是用链表结构存储数据的，很适合数据的动态插入和删除，随机访问和遍历速度比较慢。另外，他还提供了List接口中没有定义的方法，专门用于操作表头和表尾元素，可以当作堆栈、队列和双向队列使用。   

2.优化view   
3.线程安全  
4.实现树  
5.内存限制  
6.枚举  
7.安卓性能优化工具  
