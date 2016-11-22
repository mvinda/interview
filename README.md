# interview
2017届春招秋招公司的面试题目
#阿里内推（Android开发）
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


#金山一面（Android开发）
1.arraylist与vector的区别  
2.优化view    
3.线程安全  
4.实现树  
5.内存限制  
6.枚举  
7.安卓性能优化工具  

#阿里面试（JAVA研发）
###一面
1.写出知道的所有单例模式的写法  
2.整数的二进制找出有几个1，效率要求最高   
3.会场安排问题   
4.如何用两个栈模拟一个队列   
（前面四道考了快40分钟了）  
5.TCP三次握手的过程   
6.http了解吗？（这道我直接说没有深入研究web开发）   
7.java集合类，哪些线程安全，哪些线程不安全   
8.线程安全问题（如何保证线程安全，哪些地方要使用线程安全；lock和synchronized区别，用哪个更好，为什么？）   
9.用过volatile吗，说一下？   
10.有看过JDK源码吗？（这个我说没有深入了解过）  
11.数据库隔离级别哪几种？（这道直接说忘了，可以提示一下吗）   
12.其他问题忘了   
（没问项目，全问基础题，算法题最重要，答不好估计进不了）   

###二面   
1.详细问了项目的整个架构和一些具体功能，关键技术的实现？（谈了估计快半个钟）   
2.TCP三次握手，以及一些具体问题如”为什么要有第三次握手？客户端发给服务器的报文段丢失了怎么办？这时客户端还没收到服务器的确认包，那它会继续发吗？服务器收到之后重传的确认号应该是多少？”等等（两轮都问了TCP，总的来说就是要精通TCP，滑动窗口，确认重传都要很清楚）   
3.线程安全问题（同一面）   
4.平衡二叉树（说一下原理？开发实践中哪些地方要用到它？）  
5.一个字符串中找出给定字符串，要求效率最高？（字符串匹配的KMP算法）   
6.如果HashMap的大小超过了负载因子定义的容量,怎么办？   
7.说一下hashcode？（自己关联了equals和==回答）  
8.知道Unicode编码吗？（这道我直接说没有深入研究，怕被问深）   
9.其他细节题，如char a=‘海’；float a=1.1； short a=1；分别问了这几个正确吗？   
10.想问一道概率论的题目（我直接跟面试官说没修这门课，广外之前把概率论当选修课了…面试官也说那算了）   
11.学习理论和做项目你是怎么看的？   
12.问了我的职业规划是什么？   
13.考不考研，为什么？   
（能过估计是TCP，线程安全和hashcode与equals这几道题我答的比较好，面试官一直在点头）   

###hr面   
1.看到我的实践经历，问我怎么在学习中能抽出时间做这些实践？   
2.看到我之前被内推过安卓，问为什么从安卓转做java？（我给了很多原因，面试官都表示不理解。。）   
3.说一下职业规划？怎么学习自己这个方向？  
4.详细介绍一个自己的项目？   
5.自己扩展过的网络通信框架有测试过性能吗,比原框架好在哪里？从几个指标来回答？  
6.实习去哪个城市都行吗？   
（hr面表现不太好，没有事先准备）  

#腾讯内推电面（Android开发）
1.一次完整的http访问流程    
2.图片内存缓存LRUCache怎么实现  
3.App点击桌面图标的启动流程    
4.如何进程间通信?     
5.看过Binder源码吗，底层怎么实现  
6.Android新版本的特性，如何实现的  

#CVTE校招（Android开发）
###一面
（两个面试官轮流问...）     
1.项目介绍，画架构图     
2.手写代码实现一个栈   
3.TCP握手过程  
4.说一下内存溢出     
5.遇过内存泄漏吗    
6.设计模式，说一下抽象工厂      
7.线程模型是怎样的(难倒我了，没复习操作系统...)        
8.如何进程间通信?   
9.AIDL如何实现？      
10.说一下事件分发机制（这里还是没理解透）        

###二面
1.项目介绍，画架构图    
2.实习的工作内容       
3.手写快速排序       
4.一道挺有意思的软件架构设计题，要求设计具有扩展性     
5.后面几乎都在自我展现技术了（说了binder机制的内部实现）      

###三面
1.家庭情况,性格，缺点各种...  
2.什么情况下你会拒绝cvte的offer?     


#滴滴校招（软件研发）  
###一面（考的很全也真的很难）  
1.先做算法题         
二叉搜索树与双向链表     
输入一棵二叉搜索树，将该二叉搜索树转换成一个排序的双向链表。要求不能创建任何新的结点，只能调整树中结点指针的指向。    
2.TCP三次握手和四次挥手的过程，timewait，closewait状态分别在哪  
3.osi分层   
4.进程间通信方式    
5.分页与分段的区别，各自有什么优缺点     
6.HashMap、HashTable区别，concurrentHashmap     
7.B树    
8.java中软引用，虚引用，弱引用区别    
9.classLoader     
10.gc垃圾回收，分代回收     
11.深拷贝 浅拷贝   
12.静态内部类，内部类，匿名内部类     
13.反射机制   
14.sleep()和wait()区别，在同步方法中哪个可以释放锁？   

###二面
算法题：     
给定文件格式如下   
1.1.1.2 1.1.1.200 100  
3.2.2.1 3.2.2.144 102  
..   
每一行代表： 起始IP 结束IP  省份编号   
求指定IP的所在省份   
int searchProv(char *ip)   
可写伪代码 时间10分钟。  
（题意都看错，所以被刷了T T）

#百度校招（Android开发）
###一面
（项目上问了编译器，给一条语句让我画出语法树）         
1.说一下final的意义     
2.java集合类都问了一遍（基础）  
3.如何设计StringBuffer（没答好）    
4.死锁的定义，哪4个条件？    
5.单例模式      
6.手写二分查找，冒泡排序（面试官注重代码细节）      
7.activity生命周期，启动模式（问的比较细，singleInstance的activity开启一个新activity，任务栈是怎样状态）   
8.handler底层实现？消息队列为空会怎样？（会发生空闲等待，其实就是利用了管道机制）   

###二面  
（面试官也是先问编译器，大公司对这个感兴趣）  
1.hashmap的内部实现   
2.说一下堆栈的内存结构  
3.设计一个栈（不用list，set或map）  
4.Asynctask内部实现  
5.设计一个线程池?(之前阿里还考过，然而还是不会...)  
6.sleep()和wait()使用过程要注意什么？    
7.如何设计一个阻塞队列 ？    
8.斐波那契数列的实现（手写递归和非递归）  
9.字符串第一个出现一次的字符（遍历一遍，时间o(n),用数组int[256]或hashmap存储）  
10.什么是满二叉树，下个定义？（我说了当深度为n时，叶子节点数为2^(n-1)的树...）  
11.堆排序，如何初建大根堆?  
12.又问了Activity启动模式  
13.如何实现AIDL？    

###三面
1.有一个数列有10万个数，另一个数列是1亿个数，找出这两个数列共同拥有的数      
2.TCP     
3.画HTTP报文     
4.短连接和长连接   
5.两台服务器不同地方，传输一个文件需要考虑什么因素    
6.数据库索引    
7.B树,B+树  
8.平时怎么学习，学习方法？  
9.意向工作地点，工作业务？  

#携程校招（后台开发）
一面是电话面试，然后通知到公司面试，先写做一份笔试，后面三轮面试
###电面
java基础,排序算法之类  
###现场面     
算法题，设计数据结构，手写代码     
机票路线，从A地到B地不能直达，要中转1个站，求需要中转1个站的路线占所有路线比例,

