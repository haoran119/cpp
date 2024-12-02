# 面试总结之C / C++

* [c-cpp/学习笔记之C-C++ at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C%2B%2B)
* [学习笔记之IKM C++ 11 - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/8465745.html)
* [学习笔记之100 TOP Ikm C++ Online Test Questions - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/8533582.html)
* [面试总结之指针 - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/5581823.html)
* [[ZZ]软件工程师 C/C++笔试题 - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/archive/2010/10/05/1842918.html)

## RESOURCES

* [Solve C++ | HackerRank](https://www.hackerrank.com/domains/cpp)
* [C++ Programming Language - GeeksforGeeks](https://www.geeksforgeeks.org/c-plus-plus/?ref=shm#C++inCompetitiveProgramming)
    * [C++ Interview Questions (2023)](https://www.geeksforgeeks.org/cpp-interview-questions/)
    * [Commonly Asked C++ Interview Questions | Set 1 - GeeksforGeeks](https://www.geeksforgeeks.org/commonly-asked-c-interview-questions-set-1/)
    * [Commonly Asked C++ Interview Questions | Set 2 - GeeksforGeeks](https://www.geeksforgeeks.org/commonly-asked-c-interview-questions-set-2/?ref=lbp)    
    * [Commonly Asked OOP Interview Questions | Set 1 - GeeksforGeeks](https://www.geeksforgeeks.org/commonly-asked-oop-interview-questions/)
    * [C/C++ Programs - GeeksforGeeks](https://www.geeksforgeeks.org/cc-programs/)	
* [Containers library - cppreference.com](https://en.cppreference.com/w/cpp/container)
    * The Containers library is a generic collection of class templates and algorithms that allow programmers to easily implement common data structures like queues, lists and stacks. There are two (until C++11)three (since C++11) classes of containers:
        * sequence containers,
        * associative containers, and
        * unordered associative containers, (since C++11)
    * each of which is designed to support a different set of operations.
    * The container manages the storage space that is allocated for its elements and provides member functions to access them, either directly or through iterators (objects with properties similar to pointers).
    * Most containers have at least several member functions in common, and share functionalities. Which container is the best for the particular application depends not only on the offered functionality, but also on its efficiency for different workloads.
* [STL Containers - C++ Reference](http://www.cplusplus.com/reference/stl/)
* [C++ Data Structures and Algorithms Cheat Sheet](https://github.com/gibsjose/cpp-cheat-sheet/blob/master/Data%20Structures%20and%20Algorithms.md)

### [huihut/interview: 📚 C/C++ 技术面试基础知识总结](https://github.com/huihut/interview)

* [C 语言与 C++ 面试知识总结 (qq.com)](https://mp.weixin.qq.com/s/x6DMkh54NQBOlDMqNxvf7w)
* [STL](https://github.com/huihut/interview#-stl)
* [Effective C++](https://github.com/huihut/interview#effective-c)
    * 为多态基类声明 virtual 析构函数（如果 class 带有任何 virtual 函数，它就应该拥有一个 virtual 析构函数）
    * 别让异常逃离析构函数（析构函数应该吞下不传播异常，或者结束程序，而不是吐出异常；如果要处理异常应该在非析构的普通函数处理）
    * 绝不在构造和析构过程中调用 virtual 函数（因为这类调用从不下降至 derived class）
    * 令 operator= 返回一个 reference to *this （用于连锁赋值）
    * 在 operator= 中处理 “自我赋值”
    * 赋值对象时应确保复制 “对象内的所有成员变量” 及 “所有 base class 成分”（调用基类复制构造函数）
    * 在资源管理类中小心 copying 行为（普遍的 RAII class copying 行为是：抑制 copying、引用计数、深度拷贝、转移底部资源拥有权（类似 auto_ptr））
    * 以独立语句将 newed 对象存储于（置入）智能指针（如果不这样做，可能会因为编译器优化，导致难以察觉的资源泄漏）
    * 宁以 pass-by-reference-to-const 替换 pass-by-value （前者通常更高效、避免切割问题（slicing problem），但不适用于内置类型、STL迭代器、函数对象）
    * 必须返回对象时，别妄想返回其 reference（绝不返回 pointer 或 reference 指向一个 local stack 对象，或返回 reference 指向一个 heap-allocated 对象，或返回 pointer 或 reference 指向一个 local static 对象而有可能同时需要多个这样的对象。）
    * 避免使用 handles（包括 引用、指针、迭代器）指向对象内部（以增加封装性、使 const 成员函数的行为更像 const、降低 “虚吊号码牌”（dangling handles，如悬空指针等）的可能性）
    * 将文件间的编译依存关系降至最低（如果使用 object references 或 object pointers 可以完成任务，就不要使用 objects；如果能够，尽量以 class 声明式替换 class 定义式；为声明式和定义式提供不同的头文件）
    * 绝不重新定义继承而来的 non-virtual 函数
    * 绝不重新定义继承而来的缺省参数值，因为缺省参数值是静态绑定（statically bound），而 virtual 函数却是动态绑定（dynamically bound）
    * 明智而审慎地使用多重继承（多继承比单一继承复杂，可能导致新的歧义性，以及对 virtual 继承的需要，但确有正当用途，如 “public 继承某个 interface class” 和 “private 继承某个协助实现的 class”；virtual 继承可解决多继承下菱形继承的二义性问题，但会增加大小、速度、初始化及赋值的复杂度等等成本）
    * 了解隐式接口和编译期多态（class 和 templates 都支持接口（interfaces）和多态（polymorphism）；class 的接口是以签名为中心的显式的（explicit），多态则是通过 virtual 函数发生于运行期；template 的接口是奠基于有效表达式的隐式的（implicit），多态则是通过 template 具现化和函数重载解析（function overloading resolution）发生于编译期）
* [More Effective c++](https://github.com/huihut/interview#more-effective-c)
    * 仔细区别 pointers 和 references（当你知道你需要指向某个东西，而且绝不会改变指向其他东西，或是当你实现一个操作符而其语法需求无法由 pointers 达成，你就应该选择 references；任何其他时候，请采用 pointers）
    * 区别 increment/decrement 操作符的前置（prefix）和后置（postfix）形式（前置式累加后取出，返回一个 reference；后置式取出后累加，返回一个 const 对象；处理用户定制类型时，应该尽可能使用前置式 increment；后置式的实现应以其前置式兄弟为基础）
    * 千万不要重载 &&，|| 和 , 操作符（&& 与 || 的重载会用 “函数调用语义” 取代 “骤死式语义”；, 的重载导致不能保证左侧表达式一定比右侧表达式更早被评估）
    * 在 constructors 内阻止资源泄漏（由于 C++ 只会析构已构造完成的对象，因此在构造函数可以使用 try...catch 或者 auto_ptr（以及与之相似的 classes） 处理异常时资源泄露问题）
    * 禁止异常流出 destructors 之外（原因：一、避免 terminate 函数在 exception 传播过程的栈展开（stack-unwinding）机制种被调用；二、协助确保 destructors 完成其应该完成的所有事情）
    * 了解 “抛出一个 exception” 与 “传递一个参数” 或 “调用一个虚函数” 之间的差异（第一，exception objects 总是会被复制（by pointer 除外），如果以 by value 方式捕捉甚至被复制两次，而传递给函数参数的对象则不一定得复制；第二，“被抛出成为 exceptions” 的对象，其被允许的类型转换动作比 “被传递到函数去” 的对象少；第三，catch 子句以其 “出现于源代码的顺序” 被编译器检验对比，其中第一个匹配成功者便执行，而调用一个虚函数，被选中执行的是那个 “与对象类型最佳吻合” 的函数）
    * 以 by reference 方式捕获 exceptions（可避免对象删除问题、exception objects 的切割问题，可保留捕捉标准 exceptions 的能力，可约束 exception object 需要复制的次数）
    * 了解异常处理的成本（粗略估计，如果使用 try 语句块，代码大约整体膨胀 5%-10%，执行速度亦大约下降这个数；因此请将你对 try 语句块和 exception specifications 的使用限制于非用不可的地点，并且在真正异常的情况下才抛出 exceptions）
* 英文：[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
* 中文：[C++ 风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-cpp-styleguide/contents/)
* [Bjarne Stroustrup 的常见问题](http://www.stroustrup.com/bs_faq.html)
* [Bjarne Stroustrup 的 C++ 风格和技巧常见问题](http://www.stroustrup.com/bs_faq2.html)

### [C++ 面试突击 - LeetBook - 力扣（LeetCode）全球极客挚爱的技术成长平台](https://leetcode-cn.com/leetbook/detail/cpp-interview-highlights/)

* [2021 秋招 100 道 C++ 面试高频题汇总](https://mp.weixin.qq.com/s/wPq-fJFua0xt5zfJf0fLJA)
* [C++ 面试突击 - 知乎](https://zhuanlan.zhihu.com/p/519582300)
* 编译内存相关
1. C++ 程序编译过程
2. C++ 内存管理
3. 栈和堆的区别
4. 变量的区别
5. 全局变量定义在头文件中有什么问题？
6. 对象创建限制在堆或栈
7. 内存对齐
8. 类的大小
9. 什么是内存泄露
10. 怎么防止内存泄漏？内存泄漏检测工具的原理？
11. 智能指针有哪几种？智能指针的实现原理？
12. 一个 unique_ptr 怎么赋值给另一个 unique_ptr 对象？
13. 使用智能指针会出现什么问题？怎么解决？
* 语言对比
1. C++ 11 新特性
2. C 和 C++ 的区别
3. Java 和 C++ 的区别
4. Python 和 C++ 的区别
* 面向对象
1. 什么是面向对象？面向对象的三大特性
2. 重载、重写、隐藏的区别
3. 如何理解 C++ 是面向对象编程
4. 什么是多态？多态如何实现？
* 关键字库函数
1. sizeof 和 strlen 的区别
2. lambda 表达式（匿名函数）的具体应用和使用场景
3. explicit 的作用（如何避免编译器进行隐式类型转换）
4. C 和 C++ static 的区别
5. static 的作用
6. static 在类中使用的注意事项（定义、初始化和使用）
7. static 全局变量和普通全局变量的异同
8. const 作用及用法
9. define 和 const 的区别
10. define 和 typedef 的区别
11. 用宏实现比较大小，以及两个数中的最小值
12. inline 作用及使用方法
13. inline 函数工作原理
14. 宏定义（define）和内联函数（inline）的区别
15. new 的作用？
16. new 和 malloc 如何判断是否申请到内存？
17. delete 实现原理？delete 和 delete[] 的区别？
18. new 和 malloc 的区别，delete 和 free 的区别
19. malloc 的原理？malloc 的底层实现？
20. C 和 C++ struct 的区别？
21. 为什么有了 class 还保留 struct？
22. struct 和 union 的区别
23. class 和 struct 的异同
24. volatile 的作用？是否具有原子性，对编译器有什么影响？
25. 什么情况下一定要用 volatile， 能否和 const 一起使用？
26. 返回函数中静态变量的地址会发生什么？
27. extern C 的作用？
28. sizeof(1==1) 在 C 和 C++ 中分别是什么结果？
29. memcpy 函数的底层原理？
30. strcpy 函数有什么缺陷？
31. auto 类型推导的原理
* 类相关
1. 什么是虚函数？什么是纯虚函数？
2. 虚函数和纯虚函数的区别？
3. 虚函数的实现机制
4. 单继承和多继承的虚函数表结构
5. 如何禁止构造函数的使用？
6. 什么是类的默认构造函数？
7. 构造函数、析构函数是否需要定义成虚函数？为什么？
8. 如何避免拷贝？
9. 如何减少构造函数开销？
10. 多重继承时会出现什么状况？如何解决？
11. 空类占多少字节？C++ 编译器会给一个空类自动生成哪些函数？
12. 为什么拷贝构造函数必须为引用？
13. C++ 类对象的初始化顺序
14. 如何禁止一个类被实例化？
15. 为什么用成员初始化列表会快一些？
16. 实例化一个对象需要哪几个阶段
17. 友元函数的作用及使用场景
18. 静态绑定和动态绑定是怎么实现的？
19. 深拷贝和浅拷贝的区别
20. 编译时多态和运行时多态的区别
21. 实现一个类成员函数，要求不允许修改类的成员变量？
22. 如何让类不能被继承？
* 语言特性相关
1. 左值和右值的区别？左值引用和右值引用的区别，如何将左值转换成右值？
2. std::move() 函数的实现原理
3. 什么是指针？指针的大小及用法？
4. 什么是野指针和悬空指针？
5. C++ 11 nullptr 比 NULL 优势
6. 指针和引用的区别？
7. 常量指针和指针常量的区别
8. 函数指针和指针函数的区别
9. 强制类型转换有哪几种？
10. 如何判断结构体是否相等？能否用 memcmp 函数判断结构体相等？
11. 参数传递时，值传递、引用传递、指针传递的区别？
12. 什么是模板？如何实现？
13. 函数模板和类模板的区别？
14. 什么是可变参数模板？
15. 什么是模板特化？为什么特化？
16. include " " 和 <> 的区别
17. switch 的 case 里为何不能定义变量
18. 迭代器的作用？
19. 泛型编程如何实现？
20. 什么是类型萃取？
* 设计模式
1. 了解哪些设计模式？
2. 什么是单例模式？如何实现？应用场景？
3. 什么是工厂模式？如何实现？应用场景？
4. 什么是观察者模式？如何实现？应用场景？

### MISC

* [这些C++工程师面试题你都会了吗？](https://mp.weixin.qq.com/s/JA3ZrRwS_KllNdJxVMQRdA)
    * [你们要的C++面试题答案来了--基础篇](https://mp.weixin.qq.com/s/YRo5Lm9pbbZnjY1DQfW6yw)
* [2021 年 C++ 岗就业如何？附学习路线图 (qq.com)](https://mp.weixin.qq.com/s/g6dHxYN7jhw_bLXqnFdEyA)
* [C++ 八股文（一）](https://mp.weixin.qq.com/s/qVSdP0hXbC7le5DC3vJHKw)
* [C/C++ 八股文（二）](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247497197&idx=1&sn=eda5b49d1abaa48cdfa948744efba95a&chksm=9f8a90d3a8fd19c51ad9071de207ade8929d45071c7b9191acfea3d65cd3ff01b009aec303dd&scene=178&cur_album_id=1511180677537464321#rd)
* [C++来了，详细知识点思维导图！](https://mp.weixin.qq.com/s/0x_mWC7M0WhqJ03y1w6w2Q)
* [腾讯C++后台开发面试笔试知识点参考笔记](https://mp.weixin.qq.com/s/kdZVU4W7mEVGQKQgP64elw)
* [腾讯 C++ 笔试/面试题及答案](https://mp.weixin.qq.com/s/lX9mmmRecu2gw84xkInsww)
* [面试必备 | 常见C++笔试面试题整理](https://mp.weixin.qq.com/s/tpQTBlwAJTqxMe6krw9C_Q)
* [面试常问的 C/C++ 问题，你能答上来几个？](https://mp.weixin.qq.com/s/7hcT6HV7vx58PWHVO9Zmqw)
	* https://www.cnblogs.com/hjhgogo/p/9953506.html
* [重磅干货 | 五万字长文总结 C/C++ 知识（上）](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247492098&idx=1&sn=e250dd4483b7d784ca91975b93fb25f3&chksm=9f8a873ca8fd0e2a53cc6b3f90f81198af01d4b8481b449f36387b7e798bef75e22d23608dce&scene=178&cur_album_id=1511180677537464321#rd)
* [重磅干货 | 五万字长文总结 C/C++ 知识（下）](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247492170&idx=1&sn=c03b00547fbaee0da0217d8c4ec9a71d&chksm=9f8a8774a8fd0e62a4382eba643f8f60c6062b29a0f3add36f782e71177120ffac84e3b40337&scene=178&cur_album_id=1511180677537464321#rd)
* [C/C++ 易错点 56 条，干货收藏！](https://mp.weixin.qq.com/s/gO2fk25_TK4YDcNdcl676g)

## 编译内存相关

* `#include “filename.h”`和`#include <filename.h>`的区别
    * `#include “filename.h”`是指编译器将从当前工作目录上开始查找此文件
    * `#include <filename.h>`是指编译器将从标准库目录中开始查找此文件
* C++ 内存管理
    * C++ 内存分区：栈、堆、全局/静态存储区、常量存储区、代码区。
    * 栈：存放函数的局部变量、函数参数、返回地址等，由编译器自动分配和释放。
    * 堆：动态申请的内存空间，就是由 malloc 分配的内存块，由程序员控制它的分配和释放，如果程序执行结束还没有释放，操作系统会自动回收。
    * 全局区/静态存储区（.bss 段和 .data 段）：存放全局变量和静态变量，程序运行结束操作系统自动释放，在 C 语言中，未初始化的放在 .bss 段中，初始化的放在 .data 段中，C++ 中不再区分了。
    * 常量存储区（.rodata 段）：存放的是常量，不允许修改，程序运行结束自动释放。
    * 代码区（.text 段）：存放代码，不允许修改，但可以执行。编译后的二进制文件存放在这里。
    * 说明：
        * 从操作系统的本身来讲，以上存储区在内存中的分布是如下形式(从低地址到高地址)：.text 段 --> .data 段 --> .bss 段 --> 堆 --> unused --> 栈 --> env
* 变量的内存分区
    * [C/C++的四大内存分区 - CSDN博客](https://blog.csdn.net/K346K346/article/details/45592329)
* 对象创建限制在堆或栈
	* [如何定义一个只能在堆上（栈上）生成对象的类？](https://github.com/huihut/interview#%E5%A6%82%E4%BD%95%E5%AE%9A%E4%B9%89%E4%B8%80%E4%B8%AA%E5%8F%AA%E8%83%BD%E5%9C%A8%E5%A0%86%E4%B8%8A%E6%A0%88%E4%B8%8A%E7%94%9F%E6%88%90%E5%AF%B9%E8%B1%A1%E7%9A%84%E7%B1%BB)
	* 只能在堆上
		* 方法：将析构函数设置为私有
		* 原因：C++ 是静态绑定语言，编译器管理栈上对象的生命周期，编译器在为类对象分配栈空间时，会先检查类的析构函数的访问性。若析构函数不可访问，则不能在栈上创建对象。
	* 只能在栈上
		* 方法：将 new 和 delete 重载为私有
		* 原因：在堆上生成对象，使用 new 关键词操作，其过程分为两阶段：第一阶段，使用 new 在堆上寻找可用内存，分配给对象；第二阶段，调用构造函数生成对象。将 new 操作设置为私有，那么第一阶段就无法完成，就不能够在堆上生成对象。
* C structure，数据结构里有inter,char,float时，数据的内存布局会是怎样
    * 数据会以4位或是8位，16位等等方式对齐
* 为什么会有这种对齐
    * 这是因为机器寻址就是按照这种方式进行的，这样可以一次而不是多次读取一定数据
* [面试常考，项目易错！C/C++中的字节对齐 (qq.com)](https://mp.weixin.qq.com/s/F0QIjH-fMe7KP-CtlQVbHA)
* C pointer,指向数据结构与指向char的指针有区别吗
    * 它们正做+1运算时产生的位移不同
* delete数组指针，只delete第一个后果
    * 内存泄漏 

### [smart pointers](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#smart-pointers)

* [Move Semantics and Smart Pointers](https://www.learncpp.com/)
	* [M.1 — Intro to smart pointers and move semantics – Learn C++](https://www.learncpp.com/cpp-tutorial/intro-to-smart-pointers-move-semantics/)
	* [M.6 — std::unique_ptr – Learn C++](https://www.learncpp.com/cpp-tutorial/stdunique_ptr/)
	* [M.7 — std::shared_ptr – Learn C++](https://www.learncpp.com/cpp-tutorial/stdshared_ptr/)
	* [M.8 — Circular dependency issues with std::shared_ptr, and std::weak_ptr – Learn C++](https://www.learncpp.com/cpp-tutorial/circular-dependency-issues-with-stdshared_ptr-and-stdweak_ptr/)
	* [M.x — Chapter M comprehensive review – Learn C++](https://www.learncpp.com/cpp-tutorial/chapter-m-comprehensive-review/)
* 智能指针是为了解决动态内存分配时带来的内存泄漏以及多次释放同一块内存空间而提出的。C++11 中封装在了 \<memory\> 头文件中。
* C++11 中智能指针包括以下三种：
	* 共享指针（shared_ptr）：资源可以被多个指针共享，使用计数机制表明资源被几个指针共享。通过 use_count() 查看资源的所有者的个数，可以通过 unique_ptr、weak_ptr 来构造，调用 release() 释放资源的所有权，计数减一，当计数减为 0 时，会自动释放内存空间，从而避免了内存泄漏。
	* 独占指针（unique_ptr）：独享所有权的智能指针，资源只能被一个指针占有，该指针不能拷贝构造和赋值。但可以进行移动构造和移动赋值构造（调用 move() 函数），即一个 unique_ptr 对象赋值给另一个 unique_ptr 对象，可以通过该方法进行赋值。
	* 弱指针（weak_ptr）：指向 share_ptr 指向的对象，能够解决由shared_ptr带来的循环引用问题。
* 智能指针的实现原理： 计数原理。
* [智能指针_百度百科](http://baike.baidu.com/link?url=-4Fxt6pJdzfT54y9W-fRgMxlSYiedMOkLOxNlQf67rz_wHTOhIvtESgw6s8sEdgGMy2PxyNj0VUNe_IpaSBnbK)
	* 当类中有指针成员时，一般有两种方式来管理指针成员：一是采用值型的方式管理，每个类对象都保留一份指针指向的对象的拷贝；另一种更优雅的方式是使用智能指针，从而实现指针指向的对象的共享。
	* 智能指针(smart pointer)的一种通用实现技术是使用引用计数(reference count)。智能指针类将一个计数器与类指向的对象相关联，引用计数跟踪该类有多少个对象的指针指向同一对象。
	* 每次创建类的新对象时，初始化指针并将引用计数置为1；当对象作为另一对象的副本而创建时，拷贝构造函数拷贝指针并增加与之相应的引用计数；对一个对象进行赋值时，赋值操作符减少左操作数所指对象的引用计数（如果引用计数为减至0，则删除对象），并增加右操作数所指对象的引用计数；调用析构函数时，析构函数减少引用计数（如果引用计数减至0，则删除基础对象）。
	* 实现引用计数有两种经典策略：一是引入辅助类，二是使用句柄类。
	* 为了避免方案一中每个使用指针的类自己去控制引用计数，可以用一个类把指针封装起来。封装好后，这个类对象可以出现在用户类使用指针的任何地方，表现为一个指针的行为。我们可以像指针一样使用它，而不用担心普通成员指针所带来的问题，我们把这样的类叫句柄类。在封装句柄类时，需要申请一个动态分配的引用计数空间，指针与引用计数分开存储。
	* 智能指针是存储指向动态分配（堆）对象指针的类。除了能够在适当的时间自动删除指向的对象外，他们的工作机制很像C++的内置指针。智能指针在面对异常的时候格外有用，因为他们能够确保正确的销毁动态分配的对象。他们也可以用于跟踪被多用户共享的动态分配对象。
	* 事实上，智能指针能够做的还有很多事情，例如处理线程安全，提供写时复制，确保协议，并且提供远程交互服务。有能够为这些ESP (Extremely Smart Pointers)创建一般智能指针的方法，但是并没有涵盖进来。
	* 智能指针的大部分使用是用于生存期控制，阶段控制。它们使用operator->和operator*来生成原始指针，这样智能指针看上去就像一个普通指针。
	* 这样的一个类来自标准库：std::auto_ptr。它是为解决资源所有权问题设计的，但是缺少对引用数和数组的支持。并且，std::auto_ptr在被复制的时候会传输所有权。在大多数情况下，你需要更多的和/或者是不同的功能。这时就需要加入smart_ptr类。
* [c++ - Does C++11 unique_ptr and shared_ptr able to convert to each other's type? - Stack Overflow](https://stackoverflow.com/questions/37884728/does-c11-unique-ptr-and-shared-ptr-able-to-convert-to-each-others-type)
    * In short, you can easily and efficiently convert a std::unique_ptr to std::shared_ptr but you cannot convert std::shared_ptr to std::unique_ptr.
```c++
std::unique_ptr<std::string> unique = std::make_unique<std::string>("test");
std::shared_ptr<std::string> shared = std::move(unique);
// or:
std::shared_ptr<std::string> shared = std::make_unique<std::string>("test");
```

#### [std::weak_ptr](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#stdweak_ptr)

* An instance of `std::weak_ptr` must be initialized by either an object of `std::share_ptr` or another `std::weak_ptr` object, otherwise it is an empty weak_ptr constructed by the default constructor. 
    * Because it holds a non-owning ("weak") reference to an object that is managed by `std::shared_ptr`. 
    * It must be converted to `std::shared_ptr` in order to access the referenced object.
* An `std::weak_ptr` instance can `not` transfer ownership of its contained pointer because it holds a non-owning ("weak") reference to an object that is managed by `std::shared_ptr`. 
    * Since it is non-owning, it does not have the ownership of the contained pointer and therefore it can't transfer the ownership. 
    * To transfer ownership from a `std::weak_ptr` to a `std::unique_ptr` you need to first lock the `std::weak_ptr` which will return a `std::shared_ptr` and then use `std::move` to transfer the ownership to the `std::unique_ptr`.
* Each `std::weak_ptr` instance does `not` increase the reference count of the pointer object being shared
    * it only holds a non-owning reference to the object, meaning it can access the object while it is still in scope, but it does not affect the object's lifetime.
    * The reference count is maintained by the `std::shared_ptr` instances that own the object, and when all `std::shared_ptr` instances go out of scope, the object will be deleted.
    * Because `std::weak_ptr` does not affect the reference count, it is useful in situations where you need to access an object but do not want to prolong its lifetime, such as in a `circular reference` scenario.
* Access to `std::weak_ptr` contained pointer is `not` done via `operator->()`
    * The `operator->()` is used to access the members of the object pointed by the pointer, but since `std::weak_ptr` only holds a non-owning reference to an object managed by a `std::shared_ptr`, it does not guarantee that the object will still be alive when the `std::weak_ptr` is accessed.
    * To access the object, you need to first use the `lock()` function, which will return a `std::shared_ptr` that points to the same object.
    * Once you have a `std::shared_ptr`, you can use the `operator->()` to access the members of the object, or `get()` to get a raw pointer.
* The object being referenced by the `std::weak_ptr` instance must be checked to see if it still exists before it can be accessed
    * Since a `std::weak_ptr` instance holds a non-owning reference to an object managed by a `std::shared_ptr`, it does not guarantee that the object will still be alive when the `std::weak_ptr` is accessed.
    * You must use the `lock()` function to check if the object still exists before accessing it. The `lock()` function returns a `std::shared_ptr` that points to the same object, if the object is still alive, otherwise it returns an empty `std::shared_ptr`.
    * You can then use the shared_ptr to access the object, if it is not expired.

## 语言对比

* C++如何实现JAVA接口
    * [java接口_百度百科](http://baike.baidu.com/link?url=hoPdmBnxPUNPpyCRPD80NQVbOPS0qT5IoI1jezWUDT4Dz0MdgaVrPEurjtacqy6rJRZxO0CrQCNqDn5czUriNK)
    * [C++中的抽象类以及接口的区别联系_Linux编程_Linux公社-Linux系统门户网站](http://www.linuxidc.com/Linux/2012-10/73243.htm)

### modern C++

* [B.1 — Introduction to C++11 – Learn C++](https://www.learncpp.com/cpp-tutorial/b-1-introduction-to-c11/)
* [B.2 — Introduction to C++14 – Learn C++](https://www.learncpp.com/cpp-tutorial/b-2-introduction-to-c14/)
* [B.3 — Introduction to C++17 – Learn C++](https://www.learncpp.com/cpp-tutorial/b-3-introduction-to-c17/)
* [B.4 — Introduction to C++20 – Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-c20/)
* [每个开发者都应该了解的一些C++特性](https://mp.weixin.qq.com/s/Hpn7KqYlBKz0JdryiozqyQ)
    * https://www.freecodecamp.org/news/some-awesome-modern-c-features-that-every-developer-should-know-5e3bf6f79a3c/
    * C++ 是一种强大的编程语言，但也因为其复杂性一直让用户望而却步。后来，C++ 决定做出改变，然后发展至今，成了编程社区最受欢迎的语言之一。C++ 有一些新特性非常好用，本文对此进行了介绍，比如 auto、lambda、constexpr、tuple、智能指针等。
    * auto 概念
    * lambda 表达式
    * if 或 switch 语句里的初始状态
    * 编译时执行 constexpr
    * tuple
    * 类模版参数推断
    * 智能指针
* [C++ 中的各种特性](https://mp.weixin.qq.com/s?__biz=MzA4MjI3NzQ1Nw==&mid=2247502245&idx=1&sn=9e472ebac369ffc5219ebd9e5cf67b9f&chksm=9f8aac9ba8fd258db6d136449963bbe2669fb65183a58822824314995faad442f5e5211444cc&scene=178&cur_album_id=1511180677537464321#rd)
	* https://blog.csdn.net/a15920804211/article/details/90691525
* [C++ 11 新特性梳理](https://mp.weixin.qq.com/s/c6BCvqbmwU6jCOhjL7qQPQ)
    * https://www.jianshu.com/p/78c700c8d72d
    * 在面试中，经常被问的一个问题就是：你了解C++11哪些新特性？一般而言，回答以下四个方面就够了：
        * “语法糖”：nullptr, auto自动类型推导，范围for循环，初始化列表, lambda表达式等
        * 右值引用和移动语义
        * 智能指针
        * C++11多线程编程：thread库及其相配套的同步原语mutex, lock_guard, condition_variable, 以及异步std::furture
* [【C++面试知识】C++11新特性](https://mp.weixin.qq.com/s/jZRnb8WxNoJvdbiHrSuFlQ)
	* https://blog.csdn.net/a15920804211/article/details/90691525
* [C++17 在业务代码中最好用的十个特性](https://mp.weixin.qq.com/s/jlM1NWRNpoOvW2qrBtxflQ)
	* 自从步入现代 C++时代开始，C++语言标准形成了三年一个版本的惯例：C++11 标志着现代 C++的开端，C++14 在 11 的基础上查缺补漏，并未加入许多新特性，而 C++17 作为 C++11 后的第一个大版本，标志着现代 C++逐渐走向成熟。WXG 编译器升级到 gcc7.5 已有一段时间，笔者所在项目组也已经将全部代码升级到 C++17。在使用了 C++17 一年多之后，笔者总结了 C++17 在业务代码中最好用的十个特性。
	* 笔者将这些特性大体上分为三类：语法糖、性能提升和类型系统。
	* 语法糖
		* 结构化绑定
		* std::tuple 的隐式推导
		* if constexpr
		* if 初始化语句
	* 性能提升
		* std::shared_mutex
		* std::string_view
		* std::map/unordered_map try_emplace
	* 类型系统
		* std::any
		* std::optional
		* std::variant
		* 总结一下，c++17 新增的三种类型给 c++带来了更现代更安全的类型系统，它们对应的使用场景是：
			* std::any适用于之前使用void*作为通用类型的场景。
			* std::optional适用于之前使用nullptr代表失败状态的场景。
			* std::variant适用于之前使用union的场景。
	* 总结
		* 以上是笔者在生产环境中最常用的 c++17 特性，除了本文描述的十个特性外，c++17 还添加了如lambda 值捕获*this, 钳夹函数 std::clamp(), 强制检查返回值[[nodiscard]]等非常易用的特性，本文篇幅有限不做赘述，欢迎有兴趣的读者自行探索。
* [解读C++即将迎来的重大更新（一）：C++20的四大新特性](https://mp.weixin.qq.com/s/QpqvZ3a7nFdHGjIBiKX67g)
    * https://www.modernescpp.com/index.php/thebigfour
* [Google “战败”后，C++20 用微软的提案进入协程时代！](https://mp.weixin.qq.com/s/SlTObQQeDXvLLXuoxbO1yg)

#### Differences between C++17,20,23？

* C++17, C++20, and C++23 are the three most recent iterations of the C++ language, each introducing new features, enhancements, and fixes. Here's a breakdown of the key differences and additions between these versions.

# 
**C++17**

C++17 brought many significant language and library features that improved developer productivity, simplicity, and compile-time operations. Some highlights include:

# 
**Key Language Features:**

1. **Structured Bindings**:
   - Allows decomposing tuple-like objects into individual names.
   ```cpp
   auto [x, y] = std::pair{1, 2}; // x = 1, y = 2
   ```

2. **If and Switch Statements with Initializers**:
   - You can now declare variables directly inside `if` and `switch` statements.
   ```cpp
   if (int x = foo(); x > 0) { /* use x here */ }
   ```

3. **constexpr if**:
   - Enables compile-time conditional code, reducing the need for SFINAE.
   ```cpp
   if constexpr (condition) { /* code */ }
   ```

4. **Fold Expressions**:
   - Simplifies variadic template argument processing.
   ```cpp
   template<typename... Args> void print(Args... args) {
       (std::cout << ... << args); // prints all args
   }
   ```

5. **Inline Variables**:
   - Variables declared `inline` can be defined in headers without violating the one-definition rule.
   ```cpp
   inline int global = 42;
   ```

6. **constexpr lambdas**:
   - Lambdas can now be declared `constexpr`, enabling them to be evaluated at compile time.

7. **Template Argument Deduction for Class Templates**:
   - Deduction guides make it easier to instantiate class templates without specifying template parameters.
   ```cpp
   std::pair p(1, 2);  // Deduction of std::pair<int, int>
   ```

# 
**Library Features:**

1. **std::optional**:
   - Encapsulates an optional value, replacing null pointers or error codes.
   ```cpp
   std::optional<int> maybeInt = 42;
   ```

2. **std::variant**:
   - A type-safe union-like feature to store one of multiple types.
   ```cpp
   std::variant<int, float> var = 42;
   ```

3. **std::any**:
   - A type-safe container for single values of any type.
   ```cpp
   std::any anything = 42;
   ```

4. **std::string_view**:
   - Provides a non-owning view of a string to avoid unnecessary copying.
   ```cpp
   std::string_view sv = "Hello, World!";
   ```

5. **Parallel Algorithms**:
   - Introduced parallel execution policies for standard algorithms.
   ```cpp
   std::sort(std::execution::par, v.begin(), v.end());
   ```

---

# 
**C++20**

C++20 introduced one of the largest overhauls in C++ history since C++11. It includes major features that enhance metaprogramming, concurrency, and modularization.

# 
**Key Language Features:**

1. **Concepts**:
   - Concepts constrain template parameters with predicates that must be satisfied. They provide cleaner, more readable template code.
   ```cpp
   template<typename T> requires std::integral<T>
   T add(T a, T b) { return a + b; }
   ```

2. **Ranges**:
   - Ranges simplify the use of algorithms by decoupling them from iterators, working directly with ranges.
   ```cpp
   auto result = v | std::views::filter([](int i){ return i > 10; });
   ```

3. **Coroutines**:
   - Introduced support for coroutines, allowing functions to be suspended and resumed, ideal for asynchronous tasks.
   ```cpp
   generator<int> foo() { co_yield 1; co_yield 2; }
   ```

4. **Modules**:
   - A long-awaited feature, modules break up code into well-defined components, improving compile times and the stability of large codebases.
   ```cpp
   export module MyModule;
   ```

5. **Three-way Comparison (`<=>`) - The "Spaceship Operator"**:
   - Simplifies comparison between objects by automatically generating comparison operators.
   ```cpp
   bool result = a <=> b == 0;  // Equivalent to (a == b)
   ```

6. **Constexpr Improvements**:
   - More functions (including the standard library) can be marked `constexpr`, allowing more compile-time evaluations.
   ```cpp
   constexpr int factorial(int n) {
       if (n <= 1) return 1;
       else return n * factorial(n - 1);
   }
   ```

7. **`[[likely]]` and `[[unlikely]]` Attributes**:
   - These attributes allow you to give hints to the compiler about which branches are more likely to be taken.
   ```cpp
   if ([[likely]] x > 0) { /* ... */ }
   ```

8. **Designated Initializers**:
   - You can now initialize specific members of a struct.
   ```cpp
   Point p = {.x = 1, .y = 2};
   ```

# 
**Library Features:**

1. **Calendar and Time Zones**:
   - New `std::chrono` features for calendrical and time zone manipulation.
   ```cpp
   using namespace std::chrono;
   auto today = year{2023} / January / 1d;
   ```

2. **std::span**:
   - A lightweight view over a contiguous array of elements.
   ```cpp
   std::span<int> s(arr, 5);
   ```

3. **Enhanced Concurrency**:
   - C++20 improves concurrency primitives with new features like atomic `wait` and `notify`.
   ```cpp
   atomic<int> counter;
   counter.wait(0);  // Wait for counter to change
   ```

4. **`std::format`**:
   - Provides Python-style string formatting.
   ```cpp
   std::string s = std::format("Hello, {}!", "World");
   ```

---

# 
**C++23**

C++23, the latest finalized standard, builds upon C++20 with further refinements and some notable additions, particularly focusing on fixing inconsistencies, improving usability, and expanding on earlier features.

# 
**Key Language Features:**

1. **Deduction Guides for `std::pair` and `std::tuple`**:
   - Simplifies instantiations by inferring types automatically.
   ```cpp
   std::pair p{1, 2};  // Automatic deduction
   ```

2. **Multidimensional `std::views::cartesian_product`**:
   - Provides easier handling of Cartesian products in ranges.
   ```cpp
   auto v = std::views::cartesian_product(v1, v2);
   ```

3. **`constexpr` for `std::vector` and `std::string`**:
   - `std::vector` and `std::string` can now be used in constant expressions.
   ```cpp
   constexpr std::vector<int> vec = {1, 2, 3};
   ```

4. **`std::optional` Improvements**:
   - You can now access the value of an `optional` or a default value with `value_or`.
   ```cpp
   std::optional<int> opt = std::nullopt;
   int value = opt.value_or(10);  // value = 10
   ```

5. **if consteval**:
   - Refines compile-time vs run-time decision-making.
   ```cpp
   if consteval {
       // Compile-time only code
   } else {
       // Run-time only code
   }
   ```

# 
**Library Features:**

1. **`std::expected`**:
   - A way to represent values that may either contain a value or an error, improving error handling.
   ```cpp
   std::expected<int, std::string> divide(int a, int b) {
       if (b == 0) return std::unexpected("Division by zero");
       return a / b;
   }
   ```

2. **`std::flat_map` and `std::flat_set`**:
   - Sorted associative containers that store data in contiguous memory, improving cache locality and lookup performance in some scenarios.

3. **std::views::zip**:
   - A way to iterate over multiple ranges simultaneously.
   ```cpp
   auto zipped = std::views::zip(v1, v2);
   ```

4. **Improved `std::format`**:
   - Additional formatting options and custom formatters, making `std::format` even more powerful.

5. **Range Adaptors like `std::views::chunk`**:
   - Provides utilities for working with ranges in more intuitive ways.
   ```cpp
   auto chunks = std::views::chunk(v, 2); // Chunk the range into subranges of 2
   ```

---

# 
**Summary of Key Differences**:

| Feature                           | C++17                        | C++20                               | C++23                              |
|------------------------------------|------------------------------|-------------------------------------|------------------------------------|
| **Structured Bindings**            | Yes                          | Yes                                 | Yes                                |
| **Concepts**                       | No                           | Yes                                 | Yes                                |
| **Ranges**                         | No                           | Yes                                 | Yes (improvements

## 关键字库函数

### [std::size_t](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#stdsize_t)

* unsigned integer type returned by the sizeof operator (typedef)

### [lambda](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#lambda-expressions)

* Using `[]` will not capture any variables outside of the lambda definition and can only access its own local variables.

### [explicit](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#explicit-specifier)

* explicit 的作用（如何避免编译器进行隐式类型转换）?
    * 作用：用来声明类构造函数是显示调用的，而非隐式调用，可以阻止调用构造函数时进行隐式转换。只可用于修饰单参构造函数，因为无参构造函数和多参构造函数本身就是显示调用的，再加上 explicit 关键字也没有什么意义。
    * 隐式转换：
    ```c++
    #include <iostream>
    #include <cstring>

    using namespace std;

    class A
    {
    public:
        int var;
        A(int tmp)
        {
            var = tmp;
        }
    };

    int main()
    {
        A ex = 10; // 发生了隐式转换
        return 0;
    }
    ```
    * 上述代码中，A ex = 10; 在编译时，进行了`隐式转换，将 10 转换成 A 类型的对象，然后将该对象赋值给 ex`
    * 为了避免隐式转换，可用 explicit 关键字进行声明：
    ```c++
    #include <iostream>
    #include <cstring>

    using namespace std;

    class A
    {
    public:
        int var;
        explicit A(int tmp)
        {
            var = tmp;
            cout << var << endl;  
        }
    };

    int main()
    {
        A ex(100);
        A ex1 = 10; // error: conversion from 'int' to non-scalar type 'A' requested
        return 0;
    }
    ```

### [friend](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#friend-declaration)

* The friend declaration appears in a class body and grants a function or another class access to `all` members of the class where the friend declaration appears.

### static

* `static`关键字至少有下列n个作用：
    * 保持变量内容持久
        * 函数体内`static变量`的作用范围为该函数体，不同于auto变量，该变量的内存只被分配一次，因此其值在下次调用时仍维持上次的值；
    * 隐藏
        * 在模块内的`static全局变量`可以被模块内所用函数访问，但不能被模块外其它函数访问；
        * 在模块内的`static函数`只可被这一模块内的其它函数调用，这个函数的使用范围被限制在声明它的模块内；
        * 注：普通全局变量和函数具有全局可见性，即其他的源文件也可以使用。
    * 类
        * 在类中的`static成员变量`属于整个类所拥有，对类的所有对象只有一份拷贝；
        * 在类中的`static成员函数`属于整个类所拥有，这个函数不接收`this指针`，因而只能访问类的`static成员变量`。
```c++
#include<iostream>
using namespace std;

class A
{
    private:
    int var;
    static int s_var; // 静态成员变量
public:
    void show()
    {
        cout << s_var++ << endl;
    }

    static void s_show()
    {
        cout << s_var << endl;
        // cout << var << endl; // error: invalid use of member 'A::a' in static member function. 静态成员函数不能调用非静态成员变量。无法使用 this.var
        // show();  // error: cannot call member function 'void A::show()' without object. 静态成员函数不能调用非静态成员函数。无法使用 this.show()
    }
};

int A::s_var = 1;  // 静态成员变量在类外进行初始化赋值，默认初始化为 0

int main()
{
 // cout << A::sa << endl;    // error: 'int A::sa' is private within this context
    A ex;
    ex.show();
    A::s_show();
}
```

### const

* `const`关键字至少有下列n个作用：
    * 欲阻止一个变量被改变，可以使用`const`关键字。在定义该`const变量`时，通常需要对它进行初始化，因为以后就没有机会再去改变它了；相较于`宏常量`，可进行类型检查，节省内存空间，提高了效率。
    * 对指针来说，可以指定指针本身为`const`，也可以指定指针所指的数据为`const`，或二者同时指定为`const`；
    * 在一个函数声明中，`const`可以修饰形参，表明它是一个输入参数，在函数内部不能改变其值；
    * 对于类的成员函数，若指定其为`const`类型，则表明其是一个`const成员函数`，不能修改类的成员变量；也不能调用`非const成员函数`，因为`非const成员函数`可能会修改成员变量。
    * 对于类的成员函数，有时候必须指定其返回值为`const`类型，以使得其返回值不为“左值”。

### inline

* 短小而被频繁调用的程序如何处理？
    * C语言用`macro` `宏`代替。
    * C++用`inline`，内联函数机制。
    * 内联函数可以得到宏的替换功能，所有可预见的状态和常规函数的类型检查。

### new

* malloc / new operator / operator new的区别？
	* [malloc() vs new - GeeksforGeeks](https://www.geeksforgeeks.org/malloc-vs-new/)
	* [new vs operator new in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/new-vs-operator-new-in-cpp/)
	* [Difference between "new operator" and "operator new" in C++?](https://www.tutorialspoint.com/difference-between-new-operator-and-operator-new-in-cplusplus)

Item | malloc | new operator | operator new
-|-|-|-
Type|C function|operator and C++ keyword|C++ function to overload the new operator
Call constructor?|No|Yes|No but after returning the pointer from this overloaded method, the compiler calls the constructor
Return type|void*|exact data type|exact data type
Exception handling on failure|return NULL|throws bad_alloc exception|throws bad_alloc exception
Required size of memory|calculated manually|caculated by compiler|caculated by compiler

### struct

* [struct v.s. union](http://blog.csdn.net/firefly_2002/article/details/7954458)
    * 在存储多个成员信息时，编译器会自动给struct第个成员分配存储空间，struct可以存储多个成员信息，而union每个成员会用同一个存储空间，只能存储最后一个成员的信息。
    * 都是由多个不同的数据类型成员组成，但在任何同一时刻，Union只存放了一个被先选中的成员，而结构体的所有成员都存在。
    * 对于Union的不同成员赋值，将会对其他成员重写，原来成员的值就不存在了，而对于struct的不同成员赋值是互不影响的。
* [struct v.s. class](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#classes)
    * [Structure vs class in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/structure-vs-class-in-cpp/)
    * [Access Control and Constraints of Structures, Classes and Unions](https://msdn.microsoft.com/en-us/library/4a1hcx0y.aspx)

|Structures|Classes|Unions|
| - | - | - |
|class key is struct|class key is class|class key is union|
|Default access is public|	Default access is private|	Default access is public
|No usage constraints|	No usage constraints|	Use only one member at a time
|Default inheritance is public	|Default inheritance is private	|-
|[not type-parameter-key in Template](https://stackoverflow.com/questions/2520130/why-are-structs-not-allowed-in-template-definitions)	|type-parameter-key in Template	|-

### [volatile](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#cv-const-and-volatile-type-qualifiers)

* [volatile_百度百科](http://baike.baidu.com/link?url=gPm-SmXKapujjcPjO3COGYDPSvH4VPOMabuV61XG7kM1kMhwX1AnNxF5_VZDiq7fizEaEfpYKLRBVgRt99BxOK)
    * volatile是一个特征修饰符（type specifier）.volatile的作用是作为指令关键字，确保本条指令不会因编译器的优化而省略，且要求每次直接读值。
    * volatile的变量是说这变量可能会被意想不到地改变，这样，编译器就不会去假设这个变量的值了。
    * 简单地说就是防止编译器对代码进行优化。
    * 精确地说就是，编译器在用到这个变量时必须每次都小心地重新读取这个变量的值，而不是使用保存在寄存器里的备份。
* volatile 的作用？是否具有原子性，对编译器有什么影响？
    * volatile 的作用：当对象的值可能在程序的控制或检测之外被改变时，应该将该对象声明为 violatile，告知编译器不应对这样的对象进行优化。
    * volatile不具有原子性。
    * volatile 对编译器的影响：使用该关键字后，编译器不会对相应的对象进行优化，即不会将变量从内存缓存到寄存器中，防止多个线程有可能使用内存中的变量，有可能使用寄存器中的变量，从而导致程序错误。
* 什么情况下一定要用 volatile， 能否和 const 一起使用？
    * 使用 volatile 关键字的场景：
        * 当多个线程都会用到某一变量，并且该变量的值有可能发生改变时，需要用 volatile 关键字对该变量进行修饰；
        * 中断服务程序中访问的变量或并行设备的硬件寄存器的变量，最好用 volatile 关键字修饰。
        * volatile 关键字和 const 关键字可以同时使用，某种类型可以既是 volatile 又是 const ，同时具有二者的属性。

### [mutable](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#mutable-specifier)

* mutable - permits modification of the class member declared mutable even if the containing object is declared const.
* May appear in the declaration of a non-static class members of non-reference non-const type
* Mutable is used to specify that the member does not affect the externally visible state of the class (as often used for mutexes, memo caches, lazy evaluation, and access instrumentation).
* [C++ mutable keyword - GeeksforGeeks](https://www.geeksforgeeks.org/c-mutable-keyword/)
    * What is the need of mutable? 
        * Sometimes there is requirement to modify one or more data members of class / struct through `const function` even though you don’t want the function to update other members of class / struct. This task can be easily performed by using `mutable` keyword.
        * The keyword `mutable` is mainly used to allow a particular data member of `const` object to be modified. When we declare a function as `const`, the this pointer passed to function becomes `const`. Adding `mutable` to a variable allows a `const pointer` to change members. 
        * `mutable` is particularly useful if most of the members should be constant but a few need to be updatable. Data members declared as `mutable` can be modified even though they are the part of object declared as `const`. You cannot use the `mutable` specifier with names declared as `static` or `const`, or `reference`.
```c++
#include <iostream>

class Test {
public:
    int x;
    mutable int y;
    Test() { x = 4; y = 10; }
};

int main()
{
    const Test t1;

    // t1.x = 8;   // error: assignment of member 'Test::x' in read-only object

    t1.y = 20;
    std::cout << t1.y;   // 20

    return 0;
}
```

## 面向对象

* 面向对象的三大特性：
    * `封装(Encapsulation)`：将具体的实现过程和数据封装成一个函数，只能通过接口进行访问，降低耦合性。
    * `继承(Inheritance)`：子类继承父类的特征和行为，子类有父类的非 private 方法或成员变量，子类可以对父类的方法进行重写，增强了类之间的耦合性，但是当父类中的成员变量、成员函数或者类本身被 final 关键字修饰时，修饰的类不能继承，修饰的成员不能重写或修改。
    * `多态(Polymorphism)`：多态就是不同继承类的对象，对同一消息做出不同的响应，基类的指针指向或绑定到派生类的对象，使得基类指针呈现不同的表现方式。
* C++虚拟机制
    * 用来实现多态
* 重载、重写、隐藏的区别
    * `重载(Overload)`：是指同一可访问区内被声明几个具有不同参数列（`参数的类型`、`个数`、`顺序`）的`同名函数`，根据`参数列表`确定调用哪个函数，重载不关心`函数返回类型`。
    * `隐藏(Overwrite / Hide)`：是指派生类的函数屏蔽了与其同名的基类函数，主要只要`同名函数`，不管`参数列表`是否相同，基类函数都会被隐藏。
    * `重写(覆盖)(Override)`：是指派生类中存在重新定义的函数。`函数名`、`参数列表`、`返回值类型`都必须同基类中被重写的函数一致，只有函数体不同。派生类调用时会调用派生类的重写函数，不会调用被重写函数。重写的基类中被重写的函数必须有`virtual`修饰。
    * `重写`和`重载`的区别：
        * 范围区别：对于类中函数的重载或者重写而言，重载发生在同一个类的内部，重写发生在不同的类之间（子类和父类之间）。
        * 参数区别：重载的函数需要与原函数有相同的函数名、不同的参数列表，不关注函数的返回值类型；重写的函数的函数名、参数列表和返回值类型都需要和原函数相同，父类中被重写的函数需要有 virtual 修饰。
    * `virtual` 关键字：重写的函数基类中必须有 virtual关键字的修饰，重载的函数可以有 virtual 关键字的修饰也可以没有。
    * `隐藏`和`重写`，`重载`的区别：
        * 范围区别：隐藏与重载范围不同，隐藏发生在不同类中。
        * 参数区别：隐藏函数和被隐藏函数参数列表可以相同，也可以不同，但函数名一定相同；当参数不同时，无论基类中的函数是否被 virtual 修饰，基类函数都是被隐藏，而不是重写。
* [C++ Public, Protected and Private Inheritance](https://www.programiz.com/cpp-programming/public-protected-private-inheritance)
    * `public` inheritance makes `public` members of the base class `public` in the derived class, and the `protected` members of the base class remain `protected` in the derived class.
    * `protected` inheritance makes the `public` and `protected` members of the base class `protected` in the derived class.
    * `private` inheritance makes the `public` and `protected` members of the base class `private` in the derived class.
    * Note: `private` members of the base class are `inaccessible` to the derived class.
```c++
class Base {
  public:
    int x;
  protected:
    int y;
  private:
    int z;
};

class PublicDerived: public Base {
  // x is public
  // y is protected
  // z is not accessible from PublicDerived
};

class ProtectedDerived: protected Base {
  // x is protected
  // y is protected
  // z is not accessible from ProtectedDerived
};

class PrivateDerived: private Base {
  // x is private
  // y is private
  // z is not accessible from PrivateDerived
};
```

### multiple inheritance

* 可以为一个派生类指定多个基类，这样的继承结构称为`多重继承`或`多继承`
* Java/C#中没有多继承，C++中也应避免使用
* 当两个父类有同样的成员时会带来模糊性，这样导致了名称冲突(name collision)，在编译时将予以拒绝，也称之为`菱形继承`
* 可以在`方法前说明基类`，或者用`虚继承`来解决`菱形继承问题`
* [多重继承 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E5%A4%9A%E9%87%8D%E7%BB%A7%E6%89%BF)
	* 多重继承可以导致某些令人混淆的情况，所以关于它的好处与风险之间孰轻孰重常常受人争论。Java使用了一个折衷的办法：Java允许一个类别继承自多于一个父接口（可以指定某一个类别，它继承了所有父类的类型，并必须拥有所有父类接口的外部可见方法的具体实现，并允许编译器强制以上要求），但只可以从一个父类继承实现（方法与数据）。微软的.NET编程语言，例如C#和Visual Basic .NET也使用了这种接口的做法。
* [Multiple inheritance - Wikipedia](https://en.wikipedia.org/wiki/Multiple_inheritance)
	* Multiple inheritance has been a controversial issue for many years, with opponents pointing to its increased complexity and ambiguity in situations such as the "diamond problem", where it may be ambiguous as to which parent class a particular feature is inherited from if more than one parent class implements same feature. This can be addressed in various ways, including using virtual inheritance. Alternate methods of object composition not based on inheritance such as mixins and traits have also been proposed to address the ambiguity.
	* The "diamond problem" (sometimes referred to as the "Deadly Diamond of Death") is an ambiguity that arises when two classes B and C inherit from A, and class D inherits from both B and C. If there is a method in A that B and C have overridden, and D does not override it, then which version of the method does D inherit: that of B, or that of C?
	* For example, in the context of GUI software development, a class Button may inherit from both classes Rectangle (for appearance) and Clickable (for functionality/input handling), and classes Rectangle and Clickable both inherit from the Object class. Now if the equals method is called for a Button object and there is no such method in the Button class but there is an overridden equals method in Rectangle or Clickable (or both), which method should be eventually called?
	* It is called the "diamond problem" because of the shape of the class inheritance diagram in this situation. In this case, class A is at the top, both B and C separately beneath it, and D joins the two together at the bottom to form a diamond shape.
	* Languages have different ways of dealing with these problems of repeated inheritance.
		* C++ by default follows each inheritance path separately, so a D object would actually contain two separate A objects, and uses of A's members have to be properly qualified. If the inheritance from A to B and the inheritance from A to C are both marked "virtual" (for example, "class B : virtual public A"), C++ takes special care to only create one A object, and uses of A's members work correctly. If virtual inheritance and nonvirtual inheritance are mixed, there is a single virtual A, and a nonvirtual A for each nonvirtual inheritance path to A. C++ requires stating explicitly which parent class the feature to be used is invoked from i.e. Worker::Human.Age. C++ does not support explicit repeated inheritance since there would be no way to qualify which superclass to use (i.e. having a class appear more than once in a single derivation list [class Dog : public Animal, Animal]). C++ also allows a single instance of the multiple class to be created via the virtual inheritance mechanism (i.e. Worker::Human and Musician::Human will reference the same object).
		* Java 8 introduces default methods on interfaces. If A,B,C are interfaces, B,C can each provide a different implementation to an abstract method of A, causing the diamond problem. Either class D must reimplement the method (the body of which can simply forward the call to one of the super implementations), or the ambiguity will be rejected as a compile error. Prior to Java 8, Java was not subject to the Diamond problem risk, because it did not support multiple inheritance and interface default methods were not available.
		* Python has the same structure as Perl, but, unlike Perl, includes it in the syntax of the language. The order of inheritance affects the class semantics. Python had to deal with this upon the introduction of new-style classes, all of which have a common ancestor, object. Python creates a list of classes using the C3 linearization (or Method Resolution Order (MRO)) algorithm. That algorithm enforces two constraints: children precede their parents and if a class inherits from multiple classes, they are kept in the order specified in the tuple of base classes (however in this case, some classes high in the inheritance graph may precede classes lower in the graph). Thus, the method resolution order is: D, B, C, A.
	* Nevertheless, even when several interfaces declare the same method signature, as soon as that method is implemented (defined) anywhere in the inheritance chain, it overrides any implementation of that method in the chain above it (in its superclasses). Hence, at any given level in the inheritance chain, there can be at most one implementation of any method. Thus, single-inheritance method implementation does not exhibit the Diamond Problem even with multiple-inheritance of interfaces. With the introduction of default implementation for interfaces in Java 8 and C# 8, it is still possible to generate a Diamond Problem, although this will only appear as a compile-time error.

### virtual inheritance

* [虚继承 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E8%99%9A%E7%BB%A7%E6%89%BF)
	* `虚继承` 是面向对象编程中的一种技术，是指一个指定的基类，在继承体系结构中，将其成员数据实例共享给也从这个基类型直接或间接派生的其它类。
	* 举例来说：假如类A和类B各自从类X派生（非虚继承且假设类X包含一些数据成员），且类C同时多继承自类A和B，那么C的对象就会拥有两套X的实例数据（可分别独立访问，一般要用适当的消歧义限定符）。但是如果类A与B各自虚继承了类X，那么C的对象就只包含一套类X的实例数据。对于这一概念典型实现的编程语言是C++。
	* 这一特性在多重继承应用中非常有用，可以使得虚基类对于由它直接或间接派生的类来说，拥有一个共同的基类对象实例。避免由于带有歧义的组合而产生的问题（如“菱形继承问题”）。其原理是，间接派生类（C）穿透了其父类（上面例子中的A与B），实质上直接继承了虚基类X。
	* 这一概念一般用于“继承”在表现为一个整体，而非几个部分的组合时。在C++中，基类可以通过使用关键字`virtual`来声明虚继承关系。
	* `虚基类的初始化`
		* 由于虚基类是多个派生类共享的基类，因此由谁来初始化虚基类必须明确。C++标准规定，由最派生类直接初始化虚基类。因此，对间接继承了虚基类的类，也必须能直接访问其虚继承来的祖先类，也即应知道其虚继承来的祖先类的地址偏移值。
		* 例如，常见的“菱形”虚继承例子中，两个派生类、一个最派生类的构造函数的初始化列表中都可以给出虚基类的初始化；但只由最派生类的构造函数实际执行虚基类的初始化。
	* 虚继承的应用：不可派生的finally类
		* 一个类如果不希望被继承，类似于Java中的具有finally性质的类，这在C++中可以用虚继承来实现：
    ```c++
    template<typename T> class MakeFinally{
        private:
            MakeFinally(){};//只有MakeFinally的友类才可以构造MakeFinally
            ~MakeFinally(){};
        friend T;
    };

    class MyClass:public virtual  MakeFinally<MyClass>{};//MyClass是不可派生类

    //由于虚继承，所以D要直接负责构造MakeFinally类，从而导致编译报错，所以D作为派生类是不合法的。
    class D: public MyClass{};
    //另外，如果D类没有实例化对象，即没有被使用，实际上D类是被编译器忽略掉而不报错

    int main()
    {
        MyClass var1;
        // D var2;  //这一行编译将导致错误，因为D类的默认构造函数不合法
    }
    ```
* [Virtual inheritance - Wikipedia](https://en.wikipedia.org/wiki/Virtual_inheritance)
	* This example to illustrates a case where base class A has a constructor variable msg and an additional ancestor E is derived from grandchild class D.
	* Here, A must be constructed in both D and E. Further, inspection of the variable msg illustrates the how class A becomes a direct base class of its deriving class, as opposed to a base class of any intermediate deriving classed between A and the final deriving class.
    ```c++
    #include <string>
    #include <iostream>

    class A {
        private:
            std::string _msg;
        public:
            A(std::string x): _msg(x) {}
            void test(){ std::cout<<"hello from A: "<<_msg <<"\n"; }
    };

    // B,C inherit A virtually
    class B: virtual public A   { public: B(std::string x):A("b"){}  };
    class C: virtual public A   { public: C(std::string x):A("c"){}  };

    // since B,C inherit A virtually, A must be constructed in each child
    class D: public         B,C { public: D(std::string x):A("d_a"),B("d_b"),C("d_c"){}  };
    class E: public         D   { public: E(std::string x):A("e_a"),D("e_d"){}  };

    // breaks without constructing A
    // class D: public         B,C { public: D(std::string x):B(x),C(x){}  };

    // breaks without constructing A
    //class E: public         D   { public: E(std::string x):D(x){}  };

    int main(int argc, char ** argv)
    {
        D d("d");
        d.test(); // hello from A: d_a

        E e("e");
        e.test(); // hello from A: e_a
    }    
    ```
* `虚继承`用于解决`多继承`条件下的`菱形继承`问题（浪费存储空间、存在二义性）。
* 底层实现原理与编译器相关，一般通过`虚基类指针`和`虚基类表`实现，每个虚继承的子类都有一个虚基类指针（占用一个指针的存储空间，4字节）和虚基类表（不占用类对象的存储空间）（需要强调的是，虚基类依旧会在子类里面存在拷贝，只是仅仅最多存在一份而已，并不是不在子类里面了）；当虚继承的子类被当做父类继承时，虚基类指针也会被继承。
* 实际上，vbptr 指的是`虚基类表指针（virtual base table pointer）`，该指针指向了一个`虚基类表（virtual table）`，虚表中记录了虚基类与本类的偏移地址；通过偏移地址，这样就找到了虚基类成员，而虚继承也不用像普通多继承那样维持着公共基类（虚基类）的两份同样的拷贝，节省了存储空间。

### diamond problem

* The `diamond problem` (sometimes referred to as the "Deadly Diamond of Death") is an ambiguity that arises when two classes B and C inherit from A, and class D inherits from both B and C. If there is a method in A that B and C have overridden, and D does not override it, then which version of the method does D inherit: that of B, or that of C?
* [关于C++中菱形继承的解释和处理](https://mp.weixin.qq.com/s/OBSTK3kvjvqEpbmj8vXzpQ)
	* 派生类继承父类，同时也会继承父类中的所有成员副本，但如果在继承时一个基类同时被两个子类继承，然后一个新类又分别由上面的两个子类派生出来。这样从某种程度来说就形成了C++中的菱形继承，也可以叫做钻石继承
```c++
#include <iostream>
using namespace std;

class A
{
public:
    virtual void fun() { cout << "A::fun()" << endl; }
};

class B : public A
{
public:
    virtual void fun() { cout << "B::fun()" << endl; }
};

class C : public A
{
public:
    virtual void fun() { cout << "C::fun()" << endl; }
};

// Two classes virtually inheriting A
class BB : virtual public A
{
public:
    virtual void fun() { cout << "BB::fun()" << endl; }
};

class CC : virtual public A
{
public:
    virtual void fun() { cout << "CC::fun()" << endl; }
};

class D : public B, public C
{
public:
    void fun() { cout << "D::fun()" << endl; }
};

// class DD : public BB, public CC // Compile error : virtual function 'A::fun' has more than one final overrider in 'DD'
// {
// };

class DDD : public BB, public CC
{
public:
    void fun() { cout << "DDD::fun()" << endl; }
};

int main()
{
    // A *p1 = new D(); // Compile error : ambiguous conversion from derived class 'D' to base class 'A'

    // A *pDD = new DD(); // Compile error : cannot initialize a variable of type 'A *' with an rvalue of type 'DD *'

    A *pDDD = new DDD();
    pDDD->fun();  // DDD::fun() 调用派生类中的虚函数

    DDD ddd;
    A &a = ddd;
    a.fun();    // DDD::fun() 调用派生类中的虚函数

    return 0;
}
```

### polymorphism

* [多态 (计算机科学) - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E5%A4%9A%E6%80%81_(%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A7%91%E5%AD%A6))
* [Polymorphism (computer science) - Wikipedia](https://en.wikipedia.org/wiki/Polymorphism_(computer_science))
	* 在编程语言和类型论中，多态（英语：polymorphism）指为不同数据类型的实体提供统一的接口，或使用一个单一的符号来表示多个不同的类型。
	* 多态的最常见主要类别有：
		* 特设多态(Ad hoc polymorphism)：为个体的特定类型的任意集合定义一个共同接口。
		* 参数多态(Parametric polymorphism)：指定一个或多个类型不靠名字而是靠可以标识任何类型的抽象符号。
		* 子类型(Subtyping)（也叫做子类型多态或包含多态）：一个名字指称很多不同的类的实例，这些类有某个共同的超类。
	* “特设多态”来指称一个多态函数可以应用于有不同类型的实际参数上，但是以来它们所应用到的实际参数类型而有不同的表现（也叫做为函数重载或运算符重载）
	* 参数多态允许函数或数据类型被一般性的书写，从而它可以“统一”的处理值而不用依赖于它们的类型。参数多态是使语言更加有表现力而仍维持完全的静态类型安全的一种方式。这种函数和数据类型被分别称为“泛化函数”和“泛化数据类型”从而形成了泛型编程的基础。
	* 子类型
		* 在面向对象程序设计中，计算机程序运行时，相同的消息可能会送给多个不同的类别之对象，而系统可依据对象所属类别，引发对应类别的方法，而有不同的行为。简单来说，所谓多态意指相同的消息给予不同的对象会引发不同的动作。比如有动物之类别，而且由动物继承出类别猫和类别狗，并对同一源自类别动物（父类）之一消息有不同的响应，如类别动物有“叫”之动作，而类别猫会“喵喵”，类别狗则会“汪汪”，则称之为多态。
		* 多态可分为变量多态与函数多态。变量多态是指：基类型的变量（对于C++是引用或指针）可以被赋值基类型对象，也可以被赋值派生类型的对象。函数多态是指，相同的函数调用界面（函数名与实参表），传送给一个对象变量，可以有不同的行为，这视该对象变量所指向的对象类型而定。多态也可定义为“一种将不同的特殊行为和单个泛化记号相关联的能力”，变量多态是函数多态的基础。
	* 依据实现时做出的选择，多态可分为：
		* `动态多态（dynamic polymorphism）`:生效于运行期。
		* `静态多态（static polymorphism）`：将不同的特殊行为和单个泛化记号相关联，由于这种关联处理于编译期而非运行期，因此被称为“静态”。可以用来实现类型安全、运行高效的同质对象集合操作。C++ STL不采用动态多态来实现就是个例子。
	* 对于C++语言，带变量的宏和函数重载机制也允许将不同的特殊行为和单个泛化记号相关联。然而，习惯上并不将这种函数多态、宏多态展现出来的行为称为多态（或静态多态），否则就连C语言也具有宏多态了。谈及多态时，默认就是指动态多态，而静态多态则是指基于模板的多态。
* 什么是多态？多态如何实现？
	* `多态`：多态就是不同继承类的对象，对同一消息做出不同的响应，基类的指针指向或绑定到派生类的对象，使得基类指针呈现不同的表现方式。在基类的函数前加上`virtual`关键字，在派生类中重写该函数，运行时将会根据对象的实际类型来调用相应的函数。如果对象类型是派生类，就调用派生类的函数；如果对象类型是基类，就调用基类的函数。
	* 实现方法：多态是通过`虚函数`实现的，虚函数的地址保存在`虚函数表`中，虚函数表的地址保存在含有虚函数的类的实例对象的内存空间中。
	* 实现过程：
		* 在类中用 virtual 关键字声明的函数叫做虚函数；
		* 存在虚函数的类都有一个虚函数表，当创建一个该类的对象时，该对象有一个指向虚函数表的虚表指针（虚函数表和类对应的，虚表指针是和对象对应）；
		* 当基类指针指向派生类对象，基类指针调用虚函数时，基类指针指向派生类的虚表指针，由于该虚表指针指向派生类虚函数表，通过遍历虚表，寻找相应的虚函数。
* [C++编译期多态与运行期多态](https://mp.weixin.qq.com/s/Xyo97HNDaelUy6F8aiMwIA)
	* https://www.cnblogs.com/QG-whz/p/5132745.html
	* 在面向对象C++编程中，`多态`是OO三大特性之一，这种多态称为`运行期多态`，也称为`动态多态`；在泛型编程中，多态基于template(模板)的具现化与函数的重载解析，这种多态在编译期进行，因此称为`编译期多态`或`静态多态`。
	* 运行期多态
	    * 运行期多态的设计思想要归结到类继承体系的设计上去。对于有相关功能的对象集合，我们总希望能够抽象出它们共有的功能集合，在基类中将这些功能声明为虚接口（虚函数），然后由子类继承基类去重写这些虚接口，以实现子类特有的具体功能。典型的我们会举下面这个例子：
	    * 运行期多态通过虚函数发生于运行期
        ```c++
        class Animal
        {
        public :
            virtual void shout() = 0;
        };
        class Dog :public Animal
        {
        public:
            virtual void shout(){ cout << "汪汪！"<<endl; }
        };
        class Cat :public Animal
        {
        public:
            virtual void shout(){ cout << "喵喵~"<<endl; }
        };
        class Bird : public Animal
        {
        public:
            virtual void shout(){ cout << "叽喳!"<<endl; }
        };

        int main()
        {
            Animal * anim1 = new Dog;
            Animal * anim2 = new Cat;
            Animal * anim3 = new Bird;

           //藉由指针（或引用）调用的接口，在运行期确定指针（或引用）所指对象的真正类型，调用该类型对应的接口
            anim1->shout();
            anim2->shout();
            anim3->shout();

            //delete 对象
            ...
           return 0;
        }
        ```
    * 编译期多态
        * 对模板参数而言，多态是通过模板具现化和函数重载解析实现的。以不同的模板参数具现化导致调用不同的函数，这就是所谓的编译期多态。
        * 相比较于运行期多态，实现编译期多态的类之间并不需要成为一个继承体系，它们之间可以没有什么关系，但约束是它们都有相同的隐式接口。我们将上面的例子改写为:
        * 在编译之前，函数模板中t.shout()调用的是哪个接口并不确定。在编译期间，编译器推断出模板参数，因此确定调用的shout是哪个具体类型的接口。不同的推断结果调用不同的函数，这就是编译器多态。这类似于重载函数在编译器进行推导，以确定哪一个函数被调用。
        ```c++
        class Animal
        {
        public :
            void shout() { cout << "发出动物的叫声" << endl; };
        };
        class Dog
        {
        public:
            void shout(){ cout << "汪汪！"<<endl; }
        };
        class Cat
        {
        public:
            void shout(){ cout << "喵喵~"<<endl; }
        };
        class Bird
        {
        public:
            void shout(){ cout << "叽喳!"<<endl; }
        };
        template <typename T>
        void  animalShout(T & t)
        {
            t.shout();
        }
        int main()
        {
            Animal anim;
            Dog dog;
            Cat cat;
            Bird bird;

            animalShout(anim);
            animalShout(dog);
            animalShout(cat);
            animalShout(bird);

            getchar();
        }
        ```
    * 运行期多态与编译期多态优缺点分析
        * 运行期多态优点
            * OO设计中重要的特性，对客观世界直觉认识。
            * 能够处理同一个继承体系下的异质类集合。
        * 运行期多态缺点
            * 运行期间进行虚函数绑定，提高了程序运行开销。
            * 庞大的类继承层次，对接口的修改易影响类继承层次。
            * 由于虚函数在运行期在确定，所以编译器无法对虚函数进行优化。
            * 虚表指针增大了对象体积，类也多了一张虚函数表，当然，这是理所应当值得付出的资源消耗，列为缺点有点勉强。
        * 编译期多态优点
            * 它带来了泛型编程的概念，使得C++拥有泛型编程与STL这样的强大武器。
            * 在编译器完成多态，提高运行期效率。
            * 具有很强的适配性与松耦合性，对于特殊类型可由模板偏特化、全特化来处理。
        * 编译期多态缺点
            * 程序可读性降低，代码调试带来困难。
            * 无法实现模板的分离编译，当工程很大时，编译时间不可小觑。
            * 无法处理异质对象集合。
    * 关于显式接口与隐式接口
        * 所谓的显式接口是指类继承层次中定义的接口或是某个具体类提供的接口，总而言之，我们能够在源代码中找到这个接口.显式接口以函数签名为中心，例如
            ```c++
            void AnimalShot(Animal & anim)
            {
                anim.shout();
            }
            ```
        * 我们称shout为一个显式接口。在运行期多态中的接口皆为显式接口。
        * 而对模板参数而言，接口是隐式的，奠基于有效表达式。例如：
            ```c++
            template <typename T>
            void AnimalShot(T & anim)
            {
                anim.shout();
            }
            ```
        * 对于anim来说，必须支持哪一种接口，要由模板参数执行于anim身上的操作来决定，在上面这个例子中，T必须支持shout()操作，那么shout就是T的一个隐式接口。

## [类相关](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#classes)

### [virtual function](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#virtual-member-functions)

* [虚函数 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E8%99%9A%E5%87%BD%E6%95%B0)
    * 在面向对象程序设计领域，C++、Object Pascal 等语言中有`虚函数（英语：virtual function）`或虚方法（英语：virtual method）的概念。这种函数或方法可以被子类继承和覆盖，通常使用动态分派实现。这一概念是面向对象程序设计中（运行时）多态的重要组成部分。简言之，虚函数可以给出目标函数的定义，但该目标的具体指向在编译期可能无法确定。
    * 虚函数在设计模式方面扮演重要角色。例如，《设计模式》一书中提到的23种设计模式中，仅5个对象创建模式就有4个用到了虚函数（抽象工厂、工厂方法、生成器、原型），只有单例没有用到。
    * 虚函数概念的引入可以解决这样的问题：
    * 在面向对象程序设计中，派生类继承自基类。使用指针或引用访问派生类对象时，指针或引用本身所指向的类型是基类而不是派生类。如果派生类覆盖了基类中的方法，通过上述指针或引用调用该方法时，可以有两种结果：
        * 调用到基类的方法：编译器根据指针或引用的类型决定，称作“早绑定”；
        * 调用到派生类的方法：语言的运行时系统根据对象的实际类型决定，称作“迟绑定”。
    * 虚函数的效果属于后者。如果问题中基类的函数是“虚”的，则调用到的都是最终派生类（英语：most-derived class）中的函数实现，与指针或引用的类型无关。反之，如果函数非“虚”，调用到的函数就在编译期根据指针或者引用所指向的类型决定。
    * 有了虚函数，程序甚至能够调用编译期还不存在的函数。
    * 在 C++ 中，在基类的成员函数声明前加上关键字 virtual 即可让该函数成为 虚函数，派生类中对此函数的不同实现都会继承这一修饰符，允许后续派生类覆盖，达到迟绑定的效果。即便是基类中的成员函数调用虚函数，也会调用到派生类中的版本。
    ```c++
    # include <iostream>
    # include <vector>

    using namespace std;
    class Animal
    {
    public:
      // void eat() const { cout << "I eat like a generic Animal." << endl; }
      // ~Animal() {}
      virtual void eat() const { cout << "I eat like a generic Animal." << endl; }
      virtual ~Animal() {}
    };

    class Wolf : public Animal
    {
    public:
      void eat() const { cout << "I eat like a wolf!" << endl; }
    };

    class Fish : public Animal
    {
    public:
      void eat() const { cout << "I eat like a fish!" << endl; }
    };

    class GoldFish : public Fish
    {
    public:
      void eat() const { cout << "I eat like a goldfish!" << endl; }
    };


    class OtherAnimal : public Animal
    {
    };

    int main()
    {
      std::vector<Animal*> animals;
      animals.push_back( new Animal() );
      animals.push_back( new Wolf() );
      animals.push_back( new Fish() );
      animals.push_back( new GoldFish() );
      animals.push_back( new OtherAnimal() );

      /*
      以下是虚函数 Animal::eat() 的输出：
      I eat like a generic Animal.
      I eat like a wolf!
      I eat like a fish!
      I eat like a goldfish!
      I eat like a generic Animal.

      当 Animal::eat() 不是被宣告为虚函数时，输出如下所示：
      I eat like a generic Animal.
      I eat like a generic Animal.
      I eat like a generic Animal.
      I eat like a generic Animal.
      I eat like a generic Animal.
      */
      for( std::vector<Animal*>::const_iterator it = animals.begin();
         it != animals.end(); ++it)
      {
          (*it)->eat();
          delete *it;
      }

     return 0;
    }   
    ```
    * 在Java语言中, 所有的方法默认都是"虚函数". 只有以关键字 final 标记的方法才是非虚函数.
    * 在 C# 语言中, 对基类中的任何虚方法必须用 virtual 修饰, 而派生类中由基类继承而来的重载方法必须用 override 修饰.
    * 抽象类和纯虚函数
        * `纯虚函数`或`纯虚方法`是一个需要被非抽象的派生类覆盖（override）的虚函数. 包含纯虚方法的类被称作`抽象类`; 抽象类不能被直接`实例化`。 一个抽象基类的一个子类只有在所有的纯虚函数在该类(或其父类)内给出实现时, 才能直接实例化. 纯虚方法通常只有声明(签名)而没有定义(实现)，但有特例情形要求纯虚函数必须给出函数体定义.
        * 虽然纯虚方法通常在定义它的类中没有实现, 在 C++ 语言中, 允许纯虚函数在定义它的类中包含其实现, 这为派生类提供了备用或默认的行为. C++的虚基类的虚析构函数必须提供函数体定义，否则链接时（linking）在析构该抽象类的派生实例对象的语句处会报错。
        * 在C++语言中, 纯虚函数用一种特别的语法[=0]定义（但 VS 也支持 abstract 关键字：virtual ReturnType Function()abstract;）
        * 纯虚函数的定义仅提供方法的原型. 虽然在抽象类中通常不提供纯虚函数的实现, 但是抽象类中可以包含其实现, 而且可以不在声明的同时给出定义[2]. 每个非抽象子类仍然需要重载该方法, 抽象类中实现的调用可以采用以下这种形式:
    ```c++
    class Abstract {
    public:
      virtual void pure_virtual() = 0;
    };

    void Abstract::pure_virtual() {
      // do something
    }

    class Child : public Abstract {
       virtual void pure_virtual(); // no longer abstract, this class may be instantiated.
    };

    void Child::pure_virtual() {
       Abstract::pure_virtual(); // the implementation in the abstract class is executed
    }   
    ```
* [Virtual function - Wikipedia](https://en.wikipedia.org/wiki/Virtual_function)
    * Behavior during construction and destruction
        * Languages differ in their behavior while the constructor or destructor of an object is running. For this reason, calling virtual functions in constructors is generally discouraged.
        * In C++, the "base" function is called. Specifically, the most derived function that is not more derived than the current constructor's class is called. If that function is a pure virtual function, then undefined behavior occurs. This is true even if the class contains an implementation for that pure virtual function. A conforming C++ implementation is not required (and generally not able) to detect indirect calls to pure virtual functions at compile time or link time. Some runtime systems will issue a pure virtual function call error when encountering a call to a pure virtual function at run time.
        * In Java and C#, the derived implementation is called, but some fields are not yet initialized by the derived constructor (although they are initialized to their default zero values). Some design patterns, such as the Abstract Factory Pattern, actively promote this usage in languages supporting this ability.
    * Virtual destructors
        * Object-oriented languages typically manage memory allocation and de-allocation automatically when objects are created and destroyed. However, some object-oriented languages allow a custom destructor method to be implemented, if desired. If the language in question uses automatic memory management, the custom destructor (generally called a finalizer in this context) that is called is certain to be the appropriate one for the object in question. For example, if an object of type Wolf that inherits Animal is created, and both have custom destructors, the one called will be the one declared in Wolf.
        * In manual memory management contexts, the situation can be more complex, particularly in relation to static dispatch. If an object of type Wolf is created but pointed to by an Animal pointer, and it is this Animal pointer type that is deleted, the destructor called may actually be the one defined for Animal and not the one for Wolf, unless the destructor is virtual. This is particularly the case with C++, where the behavior is a common source of programming errors if destructors are not virtual.
* `如果使用虚函数，父类指针指向子类对象并调用对象方法时，使用的是子类的方法`
* `如果未使用虚函数，则是普通的重写，则父类指针指向子类对象时，使用的是父类的方法（与指针类型看齐）`
* `可以将派生类的对象赋值给基类的指针或引用，反之不可`
* 普通函数（非类成员函数）不能是虚函数
* 静态函数（static）不能是虚函数
* 构造函数不能是虚函数（因为在调用构造函数时，虚表指针并没有在对象的内存空间中，必须要构造函数调用完成后才会形成虚表指针）
* 内联函数不能是表现多态性时的虚函数，解释见：[虚函数（virtual）可以是内联函数（inline）吗？](https://github.com/huihut/interview#%E8%99%9A%E5%87%BD%E6%95%B0virtual%E5%8F%AF%E4%BB%A5%E6%98%AF%E5%86%85%E8%81%94%E5%87%BD%E6%95%B0inline%E5%90%97)

### [virtual destructor](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#virtual-destructor)

* [虚析构函数_百度百科](https://baike.baidu.com/item/虚析构函数)
    * `虚析构函数`是为了解决基类的指针指向派生类对象，并用基类的指针删除派生类对象。
    * 如果某个类不包含虚函数，那一般是表示它将不作为一个基类来使用。当一个类不准备作为基类使用时，使析构函数为虚一般是个坏主意。因为它会为类增加一个虚函数表，使得对象的体积翻倍，还有可能降低其可移植性
    * 所以基本的一条是：`无故的声明虚析构函数和永远不去声明一样是错误的`。实际上，很多人这样总结：当且仅当类里包含至少一个虚函数的时候才去声明虚析构函数。抽象类是准备被用做基类的，基类必须要有一个虚析构函数，纯虚函数会产生抽象类，所以方法很简单：在想要成为抽象类的类里声明一个纯虚析构函数。
    * 析构函数定义成虚函数是为了防止内存泄漏，因为当基类的指针或者引用指向或绑定到派生类的对象时，如果未将基类的析构函数定义成虚函数，会调用基类的析构函数，那么只能将基类的成员所占的空间释放掉，派生类中特有的就会无法释放内存空间导致内存泄漏。
* Why C++ destructor should be declared `virtual` in a base class ?
    * A C++ destructor must be declared `virtual` in a base class to ensure that the correct derived class destructor is called when an object of a derived class is deleted through a `pointer to the base class`. If a base class destructor is not declared virtual, the base class destructor will be called when an object of a derived class is deleted through a pointer to the base class, rather than the derived class destructor. This can lead to `resource leaks` or other problems because the derived class may have additional resources that need to be cleaned up.
    * To ensure that a derived class destructor is executed when the derived class is destroyed through a base class pointer.
* How to avoid memory leak if without virtual destructor ?
    * use smart pointer
        * `std::shared_ptr<Base> p_s = std::make_shared<Derived>(2);`

### [abstract class](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#pure-virtual-functions-and-abstract-classes)

* `虚函数`：派生类可以覆盖掉的函数，
* `纯虚函数`：只是个空函数，没有函数实现体。The definition of a `pure virtual function` may be provided (and `must` be provided if the pure virtual is the `destructor`)
* `抽象类`：含有纯虚函数的类
* `接口类`：仅含有纯虚函数的抽象类
* 抽象类能被实例化吗 ?
    * 不能，只能继承抽象类，实现抽象类的函数

### [copy constructor](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#copy-constructors)

* 什么是拷贝构造函数 ?
    * 它是单个参数的构造函数，其参数是与它同属一类的对象的(常)引用；类定义中，如果未提供自己的拷贝构造函数，C++提供一个默认拷贝构造函数，该默认拷贝构造函数完成一个成员到一个成员的拷贝
* 要在C++防止对象被复制，有什么方法 ?
    * [Explicitly Defaulted and Deleted Functions | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/explicitly-defaulted-and-deleted-functions?view=msvc-160)
    * Pre-C++11 定义一个基类，将其中的拷贝构造函数和赋值构造函数声明为私有`private`
    * C++11则可以对拷贝构造函数和赋值构造函数声明为`delete`
    * 派生类以私有`private`的方式继承基类

### deep copy / shallow copy

* 什么是深浅拷贝 ?
    * `浅拷贝`是创建了一个对象用一个现成的对象初始化它的时候只是复制了成员(简单赋值)而没有拷贝分配给成员的资源(如给其指针变量成员分配了动态内存)
    * `深拷贝`是当一个对象创建时，如果分配了资源，就需要定义自己的拷贝构造函数，使之不但拷贝成员也拷贝分配给它的资源
* [Shallow Copy and Deep Copy in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/shallow-copy-and-deep-copy-in-c/)
    * In general, creating a copy of an object means to create an exact replica of the object having the same literal value, data type, and resources.
        * [Copy Constructor](https://www.geeksforgeeks.org/copy-constructor-in-cpp/)
        * [Default assignment operator](https://www.geeksforgeeks.org/default-assignment-operator-and-references/)
        ```c++
        // Copy Constructor
        Geeks Obj1(Obj);
        or
        Geeks Obj1 = Obj;

        // Default assignment operator
        Geeks Obj2;
        Obj2 = Obj1;
        ```
    * Depending upon the resources like `dynamic memory` held by the object, either we need to perform `Shallow Copy` or `Deep Copy` in order to create a replica of the object. In general, if the variables of an object have been dynamically allocated, then it is required to do a `Deep Copy` in order to create a copy of the object.
    * Shallow Copy
        * In `shallow copy`, an object is created by simply `copying the data of all variables of the original object`. This works well if none of the variables of the object are defined in the [heap section of memory](https://www.geeksforgeeks.org/stack-vs-heap-memory-allocation/). If some variables are dynamically allocated memory from heap section, then the copied object variable will also reference the same memory location.
        * This will create `ambiguity and run-time errors, dangling pointer`. Since both objects will reference to the same memory location, then change made by one will reflect those change in another object as well. Since we wanted to create a replica of the object, this purpose will not be filled by Shallow copy. 
        * Note: C++ compiler `implicitly` creates a [copy constructor](https://www.geeksforgeeks.org/copy-constructor-in-cpp/) and [overloads assignment operator](https://www.geeksforgeeks.org/assignment-operator-overloading-in-c/) in order to `perform shallow copy at compile time`.
        ```c++
        // C++ program for the above approach
        #include <iostream>
        using namespace std;

        // Box Class
        class box {
        private:
            int length;
            int breadth;
            int height;

        public:
            // Function that sets the dimensions
            void set_dimensions(int length1, int breadth1,
                                int height1)
            {
                length = length1;
                breadth = breadth1;
                height = height1;
            }

            // Function to display the dimensions
            // of the Box object
            void show_data()
            {
                cout << " Length = " << length
                    << "\n Breadth = " << breadth
                    << "\n Height = " << height
                    << endl;
            }
        };

        // Driver Code
        int main()
        {
            // Object of class Box
            box B1, B3;

            // Set dimensions of Box B1
            B1.set_dimensions(14, 12, 16);
            B1.show_data();

            // When copying the data of object
            // at the time of initialization
            // then copy is made through
            // COPY CONSTRUCTOR
            box B2 = B1;
            B2.show_data();

            // When copying the data of object
            // after initialization then the
            // copy is done through DEFAULT
            // ASSIGNMENT OPERATOR
            B3 = B1;
            B3.show_data();

            return 0;
        }
        /*
        Length = 14
        Breadth = 12
        Height = 16
        Length = 14
        Breadth = 12
        Height = 16
        Length = 14
        Breadth = 12
        Height = 16
        */
        ```
    * Deep Copy
        * In `Deep copy`, an object is created by `copying data of all variables`, and it also `allocates similar memory resources with the same value to the object`. In order to perform Deep copy, we need to `explicitly define the copy constructor and assign dynamic memory` as well, if required. Also, it is required to `dynamically allocate memory to the variables in the other constructors`, as well.
        ```c++
        // C++ program to implement the
        // deep copy
        #include <iostream>
        using namespace std;

        // Box Class
        class box {
        private:
            int length;
            int* breadth;
            int height;

        public:
            // Constructor
            box()
            {
                breadth = new int;
            }

            // Function to set the dimensions
            // of the Box
            void set_dimension(int len, int brea,
                            int heig)
            {
                length = len;
                *breadth = brea;
                height = heig;
            }

            // Function to show the dimensions
            // of the Box
            void show_data()
            {
                cout << " Length = " << length
                    << "\n Breadth = " << *breadth
                    << "\n Height = " << height
                    << endl;
            }

            // Parameterized Constructors for
            // for implementing deep copy
            box(box& sample)
            {
                length = sample.length;
                breadth = new int;
                *breadth = *(sample.breadth);
                height = sample.height;
            }

            // Destructors
            ~box()
            {
                delete breadth;
            }
        };

        // Driver Code
        int main()
        {
            // Object of class first
            box first;

            // Set the dimensions
            first.set_dimension(12, 14, 16);

            // Display the dimensions
            first.show_data();

            // When the data will be copied then
            // all the resources will also get
            // allocated to the new object
            box second = first;

            // Display the dimensions
            second.show_data();

            return 0;
        }
        /*
        Length = 12
        Breadth = 14
        Height = 16
        Length = 12
        Breadth = 14
        Height = 16
        */
        ```

| - | Shallow Copy | Deep copy |
| - | - | - |
1.| When we create a copy of object by copying data of all member variables as it is, then it is called shallow copy | When we create an object by copying data of another object along with the values of memory resources that reside outside the object, then it is called a deep copy
2.|	A shallow copy of an object copies all of the member field values. | Deep copy is performed by implementing our own copy constructor.
3.| In shallow copy, the two objects are not independent | It copies all fields, and makes copies of dynamically allocated memory pointed to by the fields
4.|	It also creates a copy of the dynamically allocated objects	| If we do not create the deep copy in a rightful way then the copy will point to the original, with disastrous consequences.
      
* [Polymorphic clones in modern C++ - Fluent C++](https://www.fluentcpp.com/2017/09/08/make-polymorphic-copy-modern-cpp/)
    * How to copy an object that is accessible only by an interface that it implements?
    * The classical problem
        * Let’s take the example of the following interface:
        * With one the classes implementing this interface:
        * How to make a copy of the Implementation object?
        ```c++
        class Interface
        {
        public:
            virtual void doSomething() const = 0;
            virtual ~Interface() = default;
        };

        class Implementation : public Interface
        {
        public:
            virtual void doSomething() const override
            {
                /* ... */
            }
        };
        ```
    * The classical solution
        * The classical solution is to “virtualize” the constructor, as Scott Meyers puts it. That is to say add a clone method in the interface, that delegates the object construction to the implementation itself.
        ```c++
        #include <iostream>

        class Interface
        {
        public:
            virtual ~Interface() = default;
            virtual Interface* clone() const = 0;
            virtual void doSomething() const = 0;
        };

        class Implementation : public Interface
        {
        public:
            virtual Implementation* clone() const override
            {
                return new Implementation(*this);
            }

            virtual void doSomething() const override
            {
                std::cout << "Implementation::doSomething()" << '\n';
            }
        };

        int main()
        {
            Interface* x = new Implementation();
            Interface* y = x->clone();

            return 0;
        }
        ```
        * Notice that the return type of the clone method differ between the interface in the implementation. It is because C++ allows overriding a virtual method with one that has a different return type, provided this return type is a pointer (resp. reference) to a class convertible to the one pointed to (resp. referenced by) the return type of the base class. This is called covariance.
        * This technique allows the desired copy, but exhibits another classical problem: the call site receives the responsibility to delete the cloned object, but nothing ensures that it will do it. Particularly if there is an early return or an exception thrown further down the code, the object has a risk to leak.
    * A modern solution
        * The tool cut out for solving this problem are smart pointers, and in particular std::unique_ptr.
        * The idea is to make the clone function return a unique_ptr, that will take care about deleting the new object in all situations. Here is how to adapt the code with this:
        ```c++
        #include <iostream>
        #include <memory>

        class Interface
        {
        public:
            virtual std::unique_ptr<Interface> clone() const = 0;

            virtual void doSomething() const = 0;
            virtual ~Interface() = default;
        };

        class Implementation : public Interface
        {
        public:
            virtual std::unique_ptr<Interface> clone() const override
            {
                return std::make_unique<Implementation>(*this);
            }

            virtual void doSomething() const override
            {
                /* ... */
            }
        };

        int main()
        {
            std::unique_ptr<Interface> z = std::make_unique<Implementation>();
            Interface* x = z.get();
            std::unique_ptr<Interface> y = x->clone();

            return 0;
        }
        ```
        * Let’s look at this solution more closely.
            * First, your compiler may not have std::make_unique since it arrived in C++14 while std::unique_ptr only came in C++11 (I believe this was just an oversight). If so, you can use this implementation proposed by cppreference.com:
            ```c++
            // note: this implementation does not disable this overload for array types
            template<typename T, typename... Args>
            std::unique_ptr<T> make_unique(Args&&... args)
            {
                return std::unique_ptr<T>(new T(std::forward<Args>(args)...));
            }
            ```
            * Second, and much more annoyingly, the covariance doesn’t hold any more, because the clone method is no longer returning pointers. It now has to return an std::unique_ptr\<Interface> in the interface AND in the implementation.
        * In the above case it doesn’t cause any practical problem, given that Implementation already depends on Interface anyway. But let’s consider the case where an implementation inherits from several interfaces. The solution without smart pointers scales effortlessly because the clone method is independent from the interface:
        ```c++
        class Interface1
        {
        public:
            virtual Interface1* clone() const = 0;
            virtual void doSomething() const = 0;
            virtual ~Interface1() = default;
        };

        class Interface2
        {
        public:
            virtual Interface2* clone() const = 0;
            virtual void doSomethingElse() const = 0;
            virtual ~Interface2() = default;
        };

        class Implementation : public Interface1, public Interface2
        {
        public:
            virtual Implementation* clone() const override
            {
                return new Implementation(*this);
            }
            virtual void doSomething() const override
            {
                /* ... */
            }
            virtual void doSomethingElse() const override
            {
                /* ... */
            }
        };
        ```
        * But with smart pointers, the situation is different: the clone method, bound to Interface1, cannot be used for Interface2! And since the clone method doesn’t take any argument, there is no way to add a new overload returning a unique_ptr to Interface2.
        * One solution that comes to mind is to use template methods. But there is no such such thing as a template virtual method so this solution is off the table.
        * Another idea would be to isolate the clone method in a clonable interface. But this would force the call site to dynamic_cast back and forth from the real interface to the clonable interface. Not good either.
    * Clearing the ambiguity
        * The alternative I would suggest is to use different names for the clone methods in the interfaces.
        ```c++
        class Interface1
        {
        public:
            virtual std::unique_ptr<Interface1> cloneInterface1() const = 0;
            virtual void doSomething() const = 0;
            virtual ~Interface1() = default;
        };

        class Interface2
        {
        public:
            virtual std::unique_ptr<Interface2> cloneInterface2() const = 0;
            virtual void doSomethingElse() const = 0;
            virtual ~Interface2() = default;
        };

        class Implementation : public Interface1, public Interface2
        {
        public:
            virtual std::unique_ptr<Interface1> cloneInterface1() const override
            {
                return make_unique<Implementation>(*this);
            }
            virtual std::unique_ptr<Interface2> cloneInterface2() const override
            {
                return make_unique<Implementation>(*this);
            }
            virtual void doSomething() const override
            {

            }
            virtual void doSomethingElse() const override
            {

            }
        };
        ```
        * But to be viable, this solution has to rely on a guideline for interface designers: if you choose to implement a clone method that returns a smart pointer, then don’t call it just clone.
        * Rather, use a specific name, like cloneInterfaceX, that won’t conflict with the copy functions coming from the other interfaces.
        * This way, you allow implementers to use your interface even if they already use others.

## 语言特性相关

### [namespaces](https://en.cppreference.com/w/cpp/language/namespace)

* [namespace in C++ | Set 2 (Extending namespace and Unnamed namespace) - GeeksforGeeks](https://www.geeksforgeeks.org/namespace-in-c-set-2-extending-namespace-and-unnamed-namespace/)
    * Unnamed Namespaces
        * They are directly usable in the same program and are used for declaring unique identifiers.
        * In unnamed namespaces, name of the namespace in not mentioned in the declaration of namespace.
        * The name of the namespace is uniquely generated by the compiler.
        * The unnamed namespaces you have created will only be accessible within the file you created it in.
        * Unnamed namespaces are the replacement for the static declaration of variables.
```c++
// C++ program to demonstrate working of unnamed
// namespaces
#include <iostream>
using namespace std;

// unnamed namespace declaration
namespace
{
int rel = 300;
}

int main()
{
cout << rel << "\n"; // prints 300
return 0;
}
```

### [constexpr if](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#constexpr-if)

* It can simplify template functions that previously used std::enable_if_t
    * [constexpr if - 7 Features of C++17 that will simplify your code](https://www.codingame.com/playgrounds/2205/7-features-of-c17-that-will-simplify-your-code/constexpr-if)
    * [Simplify Code with if constexpr and Concepts in C++17/C++20 - C++ Stories](https://www.cppstories.com/2018/03/ifconstexpr/)

### [operator overloading](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#operator-overloading)

* `operator=`, `operator()`, `operator[]`, `operator->` cannot be non-member function

### [function overloading](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C%2B%2B/README.md#functions)

* Type `void` is an overloaded type. 
    * `function(void); function(); function(int);`
* `typedef` can `not` create different overloadable types.
    * `typedef int A; typedef int B; function(A); function(B);`
* The return types from the overloaded functions do `not` have to be different
* The names of overloaded functions do `not` have to be different. The function name is not considered when determining whether a function is overloaded or not.
* Overloaded functions do `not` have to be scoped inside a namespace. They can be defined in any scope, such as in the global scope or inside a class or struct. However, it is possible to define overloaded functions inside a namespace, and this can be useful in certain situations. For example, if you are working on a large project with multiple teams, namespacing can be used to prevent naming conflicts between different teams' functions.
* The argument types and/or number of arguments to the overloaded functions must be different.
    * When defining overloaded functions, the function signature, which consists of the function name and the number and types of arguments, must be different for each function.
    * This means that you can have multiple functions with the same name, but with different number or types of arguments. This is known as `function overloading`.

### [prvalue v.s. xvalue v.s. lvalue](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#value-categories-lvalue-rvalue-xvalue)

* `An lvalue has an address that your program can access`. Examples of lvalue expressions include variable names, including const variables, array elements, function calls that return an lvalue reference, bit-fields, unions, and class members.
* `A prvalue expression has no address that is accessible by your program`. Examples of prvalue expressions include literals, function calls that return a non-reference type, and temporary objects that are created during expression evaluation but accessible only by the compiler.
* `An xvalue expression has an address that no longer accessible by your program but can be used to initialize an rvalue reference, which provides access to the expression`. Examples include function calls that return an rvalue reference, and the array subscript, member and pointer to member expressions where the array or object is an rvalue reference.
* [左值和右值的区别？左值引用和右值引用的区别，如何将左值转换成右值？](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#value-categories)
    * 左值：指表达式结束后依然存在的持久对象。
    * 右值：表达式结束就不再存在的临时对象。
    * 左值和右值的区别：左值持久，右值短暂
    * 右值引用和左值引用的区别：
    * 左值引用不能绑定到要转换的表达式、字面常量或返回右值的表达式。右值引用恰好相反，可以绑定到这类表达式，但不能绑定到一个左值上。
    * 右值引用必须绑定到右值的引用，通过 && 获得。右值引用只能绑定到一个将要销毁的对象上，因此可以自由地移动其资源。
    * std::move 可以将一个左值强制转化为右值，继而可以通过右值引用使用该值，以用于移动语义。
* [Rvalue Reference Quick Look](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2006/n2027.html#Move_Semantics)
    * Rvalue references is a small technical extension to the C++ language. Rvalue references allow programmers to avoid logically unnecessary copying and to provide perfect forwarding functions. They are primarily meant to aid in the design of higer performance and more robust libraries.
    * The rvalue reference      
        * An rvalue reference is a compound type very similar to C++'s traditional reference. To better distinguish these two types, we refer to a traditional C++ reference as an lvalue reference. When the term reference is used, it refers to both kinds of reference: lvalue reference and rvalue reference.
        * It turns out that the combination of rvalue references and lvalue references is just what is needed to easily code move semantics. The rvalue reference can also be used to achieve perfect forwarding, a heretofore unsolved problem in C++. From a casual programmer's perspective, what we get from rvalue references is more general and better performing libraries.
    * Move Semantics
        * Eliminating spurious copies
            * Copying can be expensive. 
            * The first task of rvalue references is to allow us to implement move() without verbosity, or rutime overhead.
            * move
                * The move function really does very little work. All move does is accept either an lvalue or rvalue argument, and return it as an rvalue without triggering a copy construction:
                               
### [std::move()](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#swap-and-type-operations)

* [c++ - What is std::move(), and when should it be used? - Stack Overflow](https://stackoverflow.com/questions/3413470/what-is-stdmove-and-when-should-it-be-used)
    * In C++11, in addition to copy constructors, objects can have move constructors.(And in addition to copy assignment operators, they have move assignment operators.)
    * The move constructor is used instead of the copy constructor, if the object has type "rvalue-reference" (Type &&).
    * std::move() is a cast that produces an rvalue-reference to an object, to enable moving from it.
    * It's a new C++ way to avoid copies. For example, using a move constructor, a std::vector could just copy its internal pointer to data to the new object, leaving the moved object in an moved from state, therefore not copying all the data.  
* std::move() 函数的实现原理 ?
    * std::move() 函数原型：
        ```c++
        template <typename T>
        typename remove_reference<T>::type&& move(T&& t)
        {
         return static_cast<typename remove_reference<T>::type &&>(t);
        }
        ```
        * 说明：引用折叠原理
            * 右值传递给上述函数的形参 T&& 依然是右值，即 T&& && 相当于 T&&。
            * 左值传递给上述函数的形参 T&& 依然是左值，即 T&& & 相当于 T&。
        * 小结：通过引用折叠原理可以知道，move() 函数的形参既可以是左值也可以是右值。
    * std::move() 实现原理：
        * 利用引用折叠原理将右值经过 T&& 传递类型保持不变还是右值，而左值经过 T&& 变为普通的左值引用，以保证模板可以传递任意实参，且保持类型不变；
        * 然后通过 remove_refrence 移除引用，得到具体的类型 T；
        * 最后通过 static_cast\<> 进行强制类型转换，返回 T&& 右值引用。
    
### pointer v.s. reference

* [Pointers vs References in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/pointers-vs-references-cpp/)
	* [Pointers](https://www.geeksforgeeks.org/pointers-in-c-and-c-set-1-introduction-arithmetic-and-array/)
		* A pointer is a variable that holds memory address of another variable. A pointer needs to be dereferenced with * operator to access the memory location it points to. 
	* [References](https://www.geeksforgeeks.org/references-in-c/)
		* A reference variable is an alias, that is, another name for an already existing variable. A reference, like a pointer, is also implemented by storing the address of an object. 
		* A reference can be thought of as a constant pointer (not to be confused with a pointer to a constant value!) with automatic indirection, i.e the compiler will apply the * operator for you. 
	* Differences

		Features|Pointers|References
		-|-|-
		Initialization|we can declare and initialize pointer at same step or in multiple line.|we should declare and initialize references at single step.
		Reassignment|Pointer can be re-assigned. This property is useful for implementation of data structures like linked list, tree, etc.|Reference cannot be re-assigned, and must be assigned at initialization.
		Memory Address|Pointer has its own memory address and size on the stack|Reference shares the same memory address (with the original variable) but also takes up some space on the stack
		NULL value|Pointer can be assigned NULL directly|Reference cannot. The constraints associated with references (no NULL, no reassignment) ensure that the underlying operations do not run into exception situation.
		Indirection|You can have pointers to pointers offering extra levels of indirection|References only offer one level of indirection
		Arithmetic operations|Various arithmetic operations can be performed on pointers|There is no such thing called Reference Arithmetic.(but you can take the address of an object pointed by a reference and do pointer arithmetics on it as in &obj + 5).) 

	* When to use What
		* The performances are exactly the same, as references are implemented internally as pointers. But still you can keep some points in your mind to decide when to use what :
			* Use references 
				* In function parameters and return types.
			* Use pointers: 
				* Use pointers if pointer arithmetic or passing NULL-pointer is needed. For example for arrays (Note that array access is implemented using pointer arithmetic).
				* To implement data structures like linked list, tree, etc and their algorithms because to point different cell, we have to use the concept of pointers.
* 指针和引用的初始化区别
  * 引用被创建的同时必须被初始化（指针则可以在任何时候被初始化）。
  * 不能有NULL 引用，引用必须与合法的存储单元关联（指针则可以是NULL）。
  * 一旦引用被初始化，就不能改变引用的关系（指针则可以随时改变所指的对象）。
* [Passing By Pointer Vs Passing By Reference in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/passing-by-pointer-vs-passing-by-reference-in-c/)
	* 1) Passing by Pointer: Here, the memory location of the variables is passed to the parameters in the function, and then the operations are performed.
	* 2) Passing by Reference: It allows a function to modify a variable without having to create a copy of it. We have to declare reference variables. The memory location of the passed variable and parameter is the same and therefore, any change to the parameter reflects in the variable as well.
	* Difference Between Reference Variable and Pointer Variable:
		* A reference is the same object, just with a different name and a reference must refer to an object. Since references can’t be NULL, they are safer to use. 
		* A pointer can be re-assigned while a reference cannot, and must be assigned at initialization only.
		* The pointer can be assigned NULL directly, whereas the reference cannot.
		* Pointers can iterate over an array, we can use increment/decrement operators to go to the next/previous item that a pointer is pointing to.
		* A pointer is a variable that holds a memory address. A reference has the same memory address as the item it references.
		* A pointer to a class/struct uses ‘->’ (arrow operator) to access its members whereas a reference uses a ‘.’ (dot operator)
		* A pointer needs to be dereferenced with * to access the memory location it points to, whereas a reference can be used directly.
	* Which is preferred in Passing by Pointer Vs Passing by Reference in C++? 
		* References are usually preferred over pointers whenever we don’t need “reseating”.
		* Overall, Use references when you can, and pointers when you have to. But if we want to write C code that compiles with both C and a C++ compiler, you’ll have to restrict yourself to using pointers.	

### function pointer

* C++语言有几种callable objects：函数、函数指针、lambda表达式、bind创建的对象以及重载了函数调用运算符()的类。
* 函数指针,什么是函数指针，有什么用处
    * 函数指针是指向函数的指针，最大的用处是做回调函数，可以做接口函数，就像系统中断中的中断处理函数
* 设计一个函数，函数中有一段功能是对相关数据的结理，但具体的处理方式是不定的。
    * 将不定的处理方式设定成一个外部传来函数指针。(可以设计成这样 func(int a,int b，某种函数指针) )
* 如何对消息实现同步响应
    * 使用CALLBACK，回调函数
    * [CALLBACK_百度百科](https://baike.baidu.com/item/CALLBACK/813549?fr=aladdin)
* 函数对象功能
    * 可以用作类似C里的回调函数，也可以用作函数功能的组合
  
### [Type alias, alias template](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#type-alias-alias-template)  

* Valid methods of creating an alias of a type
```c++
using MyAlias1 = char;
typedef int MyAlias2;
```

### [type casting](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#conversions)

* [强制类型转换运算符](https://github.com/huihut/interview#%E5%BC%BA%E5%88%B6%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2%E8%BF%90%E7%AE%97%E7%AC%A6)
	* static_cast
		* 用于非多态类型的转换
		* 不执行运行时类型检查（转换安全性不如 dynamic_cast）
		* 通常用于转换数值数据类型（如 float -> int）
		* 可以在整个类层次结构中移动指针，子类转化为父类安全（向上转换），父类转化为子类不安全（因为子类可能有不在父类的字段或方法）
		* 向上转换是一种隐式转换。
	* dynamic_cast
		* 用于多态类型的转换
		* 执行行运行时类型检查
		* 只适用于指针或引用
		* 对不明确的指针的转换将失败（返回 nullptr），但不引发异常
		* 可以在整个类层次结构中移动指针，包括向上转换、向下转换
	* const_cast
		* 用于删除 const、volatile 和 __unaligned 特性（如将 const int 类型转换为 int 类型 ）
	* reinterpret_cast
		* 用于位的简单重新解释
		* 滥用 reinterpret_cast 运算符可能很容易带来风险。 除非所需转换本身是低级别的，否则应使用其他强制转换运算符之一。
		* 允许将任何指针转换为任何其他指针类型（如 char* 到 int* 或 One_class* 到 Unrelated_class* 之类的转换，但其本身并不安全）
		* 也允许将任何整数类型转换为任何指针类型以及反向转换。
		* reinterpret_cast 运算符不能丢掉 const、volatile 或 __unaligned 特性。
		* reinterpret_cast 的一个实际用途是在哈希函数中，即，通过让两个不同的值几乎不以相同的索引结尾的方式将值映射到索引。
	* bad_cast
		* 由于强制转换为引用类型失败，dynamic_cast 运算符引发 bad_cast 异常。
```c++
int i = 5;
int *pi = &i;

double *pd = reinterpret_cast<double*>(pi); // only this compiles
// double *pd1 = const_cast<double*>(pi);
// double *pd2 = dynamic_cast<double*>(pi);
// double *pd3 = static_cast<double*>(pi);
// int **pp = &&i;
```

### [templates](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#templates)

* 简化对类似函数的设计，比如要设计两个函数 abs(int a), abs(float a),就可以用模板去设计一个函数就可以了
* How to defind a [template alias](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#type-alias-alias-template) ?
    * `template<class T> using UP = std::unique_ptr<T, std::function<void (T*)> >;`
* What's [non-type template parameter](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#non-type-template-parameter) / [type template parameter](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#type-template-parameter) / [template template parameter](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#template-template-parameter)?
    * A `template type parameter` is a placeholder type that is substituted for a type passed in as an argument.
        ```c++
        std::vector<int> myVec;
        std::map<std::string, int> myMap;
        std::lock_guard<std::mutex> myLockGuard;
        ```
    * A `template non-type parameter` is a template parameter where the type of the parameter is predefined and is substituted for a constexpr value passed in as an argument.
        * Non-types can be a
            * lvalue reference
            * nullptr
            * pointer
            * enumerator
            * integral type
        * Integrals are the most used non-types. std::array is the typical example because you have to specify at compile time the size of a std::array:
            * `std::array<int, 3> myArray{1, 2, 3};`
    * A `template template parameter` is a template parameter where the name of this parameter is a template-name (and needs arguments to be instantiated).
        * The container adaptors std::stack, std::queue, and std::priority_queue use per default a std::deque to hold their arguments, but you can use a different container. Their usage is straightforward.
        ```c++
        std::stack<int> stack1;
        stack1.push(5);

        std::stack<double, std::vector<double>> stack2;
        stack2.push(10.5);
        ```
        * Their definition may look a little bit weird.
        ```c++
        // templateTemplateParameters.cpp

        #include <iostream>
        #include <list>
        #include <vector>
        #include <string>

        template <typename T, template <typename, typename> class Cont >   // (1)
        class Matrix{
        public:
          explicit Matrix(std::initializer_list<T> inList): data(inList){  // (2)
            for (auto d: data) std::cout << d << " ";
          }
          int getSize() const{
            return data.size();
          }

        private:
          Cont<T, std::allocator<T>> data;                                 // (3)                               

        };

        int main(){

          std::cout << std::endl;

                                                                            // (4)
          Matrix<int, std::vector> myIntVec{1, 2, 3, 4, 5, 6, 7, 8, 9, 10}; 
          std::cout << std::endl;
          std::cout << "myIntVec.getSize(): " << myIntVec.getSize() << std::endl;

          std::cout << std::endl;

          Matrix<double, std::vector> myDoubleVec{1.1, 2.2, 3.3, 4.4, 5.5}; // (5)
          std::cout << std::endl;
          std::cout << "myDoubleVec.getSize(): "  << myDoubleVec.getSize() << std::endl;

          std::cout << std::endl;
                                                                            // (6)
          Matrix<std::string, std::list> myStringList{"one", "two", "three", "four"};  
          std::cout << std::endl;
          std::cout << "myStringList.getSize(): " << myStringList.getSize() << std::endl;

          std::cout << std::endl;

        }
        ```
    * [19.2 — Template non-type parameters – Learn C++](https://www.learncpp.com/cpp-tutorial/template-non-type-parameters/)
    * [Types-, Non-Types, and Templates as Template Parameters - ModernesCpp.com](https://www.modernescpp.com/index.php/types-non-types-and-templates-as-template-parameters)
* What's [Parameter pack](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#parameter-pack) ?
    * A `template parameter pack` is a template parameter that accepts zero or more template arguments (non-types, types, or templates). A `function parameter pack` is a function parameter that accepts zero or more function arguments.
    * A template with at least one parameter pack is called a `variadic template`.

### [Pairs and tuples](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#pairs-and-tuples)

* A `std::pair` can be assigned to `std::tuple`, but not vice versa
* `std::tie` may be used to unpack a `std::pair` as well as `std::tuple` because `std::tuple` has a converting assignment from pairs
* Both `std::pair` and `std::tuple` can be initialized via an initializer list (e.g. {0, 1} )

### [STL](https://github.com/huihut/interview#-stl)

* [Containers library](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#containers-library)
* [STL 容器](https://github.com/huihut/interview#stl-%E5%AE%B9%E5%99%A8)

容器 | 底层数据结构 | 时间复杂度 | 有无序 | 可不可重复 | 其他
---|---|---|---|---|---
[array](https://github.com/huihut/interview/tree/master/STL#array)|数组|随机读改 O(1)|无序|可重复|支持随机访问
[vector](https://github.com/huihut/interview/tree/master/STL#vector)|数组|随机读改、尾部插入、尾部删除 O(1)<br/>头部插入、头部删除 O(n)|无序|可重复|支持随机访问; [Iterators/References may become invalid after insertion or erasure](https://en.cppreference.com/w/cpp/container); May have a default size
[deque](https://github.com/huihut/interview/tree/master/STL#deque)|双端队列|头尾插入、头尾删除 O(1)|无序|可重复|一个中央控制器 + 多个缓冲区，支持首尾快速增删，支持随机访问
[forward_list](https://github.com/huihut/interview/tree/master/STL#forward_list)|单向链表|插入、删除 O(1)|无序|可重复|不支持随机访问
[list](https://github.com/huihut/interview/tree/master/STL#list)|双向链表|插入、删除 O(1)|无序|可重复|不支持随机访问; Iterators/References remain valid after insertion or erasure except the corresponding element is deleted.
[stack](https://github.com/huihut/interview/tree/master/STL#stack)|deque / list|顶部插入、顶部删除 O(1)|无序|可重复|deque 或 list 封闭头端开口，不用 vector 的原因应该是容量大小有限制，扩容耗时
[queue](https://github.com/huihut/interview/tree/master/STL#queue)|deque / list|尾部插入、头部删除 O(1)|无序|可重复|deque 或 list 封闭头端开口，不用 vector 的原因应该是容量大小有限制，扩容耗时
[priority_queue](https://github.com/huihut/interview/tree/master/STL#priority_queue)|vector + max-heap|插入、删除 O(log<sub>2</sub>n)|有序|可重复|vector容器+heap处理规则
[set](https://github.com/huihut/interview/tree/master/STL#set)|[红黑树](https://github.com/huihut/interview#%E7%BA%A2%E9%BB%91%E6%A0%91)|插入、删除、查找 O(log<sub>2</sub>n)|有序|不可重复|
[multiset](https://github.com/huihut/interview/tree/master/STL#multiset)|红黑树|插入、删除、查找 O(log<sub>2</sub>n)|有序|可重复|
[map](https://github.com/huihut/interview/tree/master/STL#map)|红黑树|插入、删除、查找 O(log<sub>2</sub>n)|有序|不可重复|
[multimap](https://github.com/huihut/interview/tree/master/STL#multimap)|红黑树|插入、删除、查找 O(log<sub>2</sub>n)|有序|可重复|
[unordered_set](https://github.com/huihut/interview/tree/master/STL#unordered_set)|哈希表|插入、删除、查找 O(1) 最差 O(n)|无序|不可重复|
[unordered_multiset](https://github.com/huihut/interview/tree/master/STL#unordered_multiset)|哈希表|插入、删除、查找 O(1) 最差 O(n)|无序|可重复|
[unordered_map](https://github.com/huihut/interview/tree/master/STL#unordered_map)|哈希表|插入、删除、查找 O(1) 最差 O(n)|无序|不可重复|
[unordered_multimap](https://github.com/huihut/interview/tree/master/STL#unordered_multimap)|哈希表|插入、删除、查找 O(1) 最差 O(n)|无序|可重复|

* [STL 算法](https://github.com/huihut/interview#stl-%E7%AE%97%E6%B3%95)

算法 | 底层算法 | 时间复杂度 | 可不可重复
---|---|---|---
[find](http://www.cplusplus.com/reference/algorithm/find/)|顺序查找|O(n)|可重复
[sort](https://github.com/gcc-mirror/gcc/blob/master/libstdc++-v3/include/bits/stl_algo.h#L4808)|[内省排序](https://en.wikipedia.org/wiki/Introsort)|O(n*log<sub>2</sub>n)|可重复

* [算法（algorithms）](https://github.com/huihut/interview/tree/master/STL#%E7%AE%97%E6%B3%95algorithms)
```cpp
// 简单查找算法，要求输入迭代器（input iterator）
find(beg, end, val); // 返回一个迭代器，指向输入序列中第一个等于 val 的元素，未找到返回 end
find_if(beg, end, unaryPred); // 返回一个迭代器，指向第一个满足 unaryPred 的元素，未找到返回 end
find_if_not(beg, end, unaryPred); // 返回一个迭代器，指向第一个令 unaryPred 为 false 的元素，未找到返回 end
count(beg, end, val); // 返回一个计数器，指出 val 出现了多少次
count_if(beg, end, unaryPred); // 统计有多少个元素满足 unaryPred
all_of(beg, end, unaryPred); // 返回一个 bool 值，判断是否所有元素都满足 unaryPred
any_of(beg, end, unaryPred); // 返回一个 bool 值，判断是否任意（存在）一个元素满足 unaryPred
none_of(beg, end, unaryPred); // 返回一个 bool 值，判断是否所有元素都不满足 unaryPred

// 查找重复值的算法，传入向前迭代器（forward iterator）
adjacent_find(beg, end); // 返回指向第一对相邻重复元素的迭代器，无相邻元素则返回 end
adjacent_find(beg, end, binaryPred); // 返回指向第一对相邻重复元素的迭代器，无相邻元素则返回 end
search_n(beg, end, count, val); // 返回一个迭代器，从此位置开始有 count 个相等元素，不存在则返回 end
search_n(beg, end, count, val, binaryPred); // 返回一个迭代器，从此位置开始有 count 个相等元素，不存在则返回 end

// 查找子序列算法，除 find_first_of（前两个输入迭代器，后两个前向迭代器） 外，都要求两个前向迭代器
search(beg1, end1, beg2, end2); // 返回第二个输入范围（子序列）在爹一个输入范围中第一次出现的位置，未找到则返回 end1
search(beg1, end1, beg2, end2, binaryPred); // 返回第二个输入范围（子序列）在爹一个输入范围中第一次出现的位置，未找到则返回 end1
find_first_of(beg1, end1, beg2, end2); // 返回一个迭代器，指向第二个输入范围中任意元素在第一个范围中首次出现的位置，未找到则返回end1
find_first_of(beg1, end1, beg2, end2, binaryPred); // 返回一个迭代器，指向第二个输入范围中任意元素在第一个范围中首次出现的位置，未找到则返回end1
find_end(beg1, end1, beg2, end2); // 类似 search，但返回的最后一次出现的位置。如果第二个输入范围为空，或者在第一个输入范围为空，或者在第一个输入范围中未找到它，则返回 end1
find_end(beg1, end1, beg2, end2, binaryPred); // 类似 search，但返回的最后一次出现的位置。如果第二个输入范围为空，或者在第一个输入范围为空，或者在第一个输入范围中未找到它，则返回 end1

// 其他只读算法，传入输入迭代器
for_each(beg, end, unaryOp); // 对输入序列中的每个元素应用可调用对象 unaryOp，unaryOp 的返回值被忽略
mismatch(beg1, end1, beg2); // 比较两个序列中的元素。返回一个迭代器的 pair，表示两个序列中第一个不匹配的元素
mismatch(beg1, end1, beg2, binaryPred); // 比较两个序列中的元素。返回一个迭代器的 pair，表示两个序列中第一个不匹配的元素
equal(beg1, end1, beg2); // 比较每个元素，确定两个序列是否相等。
equal(beg1, end1, beg2, binaryPred); // 比较每个元素，确定两个序列是否相等。

// 二分搜索算法，传入前向迭代器或随机访问迭代器（random-access iterator），要求序列中的元素已经是有序的。通过小于运算符（<）或 comp 比较操作实现比较。
lower_bound(beg, end, val); // 返回一个非递减序列 [beg, end) 中的第一个大于等于值 val 的位置的迭代器，不存在则返回 end
lower_bound(beg, end, val, comp); // 返回一个非递减序列 [beg, end) 中的第一个大于等于值 val 的位置的迭代器，不存在则返回 end
upper_bound(beg, end, val); // 返回一个非递减序列 [beg, end) 中第一个大于 val 的位置的迭代器，不存在则返回 end
upper_bound(beg, end, val, comp); // 返回一个非递减序列 [beg, end) 中第一个大于 val 的位置的迭代器，不存在则返回 end
equal_range(beg, end, val); // 返回一个 pair，其 first 成员是 lower_bound 返回的迭代器，其 second 成员是 upper_bound 返回的迭代器
binary_search(beg, end, val); // 返回一个 bool 值，指出序列中是否包含等于 val 的元素。对于两个值 x 和 y，当 x 不小于 y 且 y 也不小于 x 时，认为它们相等。

// 只写不读算法，要求输出迭代器（output iterator）
fill(beg, end, val); // 将 val 赋予每个元素，返回 void
fill_n(beg, cnt, val); // 将 val 赋予 cnt 个元素，返回指向写入到输出序列最有一个元素之后位置的迭代器
genetate(beg, end, Gen); // 每次调用 Gen() 生成不同的值赋予每个序列，返回 void
genetate_n(beg, cnt, Gen); // 每次调用 Gen() 生成不同的值赋予 cnt 个序列，返回指向写入到输出序列最有一个元素之后位置的迭代器

// 使用输入迭代器的写算法，读取一个输入序列，将值写入到一个输出序列（dest）中
copy(beg, end, dest); // 从输入范围将元素拷贝所有元素到 dest 指定定的目的序列
copy_if(beg, end, dest, unaryPred); // 从输入范围将元素拷贝满足 unaryPred 的元素到 dest 指定定的目的序列
copy_n(beg, n, dest); // 从输入范围将元素拷贝前 n 个元素到 dest 指定定的目的序列
move(beg, end, dest); // 对输入序列中的每个元素调用 std::move，将其移动到迭代器 dest 开始始的序列中
transform(beg, end, dest, unaryOp); // 调用给定操作（一元操作），并将结果写到dest中
transform(beg, end, beg2, dest, binaryOp); // 调用给定操作（二元操作），并将结果写到dest中
replace_copy(beg, end, dest, old_val, new_val); // 将每个元素拷贝到 dest，将等于 old_val 的的元素替换为 new_val
replace_copy_if(beg, end, dest, unaryPred, new_val); // 将每个元素拷贝到 dest，将满足 unaryPred 的的元素替换为 new_val
merge(beg1, end1, beg2, end2, dest); // 两个输入序列必须都是有序的，用 < 运算符将合并后的序列写入到 dest 中
merge(beg1, end1, beg2, end2, dest, comp); // 两个输入序列必须都是有序的，使用给定的比较操作（comp）将合并后的序列写入到 dest 中

// 使用前向迭代器的写算法，要求前向迭代器
iter_swap(iter1, iter2); // 交换 iter1 和 iter2 所表示的元素，返回 void
swap_ranges(beg1, end1, beg2); // 将输入范围中所有元素与 beg2 开始的第二个序列中所有元素进行交换。返回递增后的的 beg2，指向最后一个交换元素之后的位置。
replace(beg, end, old_val, new_val); // 用 new_val 替换等于 old_val 的每个匹配元素
replace_if(beg, end, unaryPred, new_val); // 用 new_val 替换满足 unaryPred 的每个匹配元素

// 使用双向迭代器的写算法，要求双向选代器（bidirectional iterator）
copy_backward(beg, end, dest); // 从输入范围中拷贝元素到指定目的位置。如果范围为空,则返回值为 dest；否则，返回值表示从 *beg 中拷贝或移动的元素。
move_backward(beg, end, dest);  // 从输入范围中移动元素到指定目的位置。如果范围为空,则返回值为 dest；否则,返回值表示从 *beg 中拷贝或移动的元素。
inplace_merge(beg, mid, end); // 将同一个序列中的两个有序子序列合并为单一的有序序列。beg 到 mid 间的子序列和 mid 到 end 间的子序列被合并，并被写入到原序列中。使用 < 比较元素。
inplace_merge(beg, mid, end, comp); // 将同一个序列中的两个有序子序列合并为单一的有序序列。beg 到 mid 间的子序列和 mid 到 end 间的子序列被合并，并被写入到原序列中。使用给定的 comp 操作。

// 划分算法，要求双向选代器（bidirectional iterator）
is_partitioned(beg, end, unaryPred); // 如果所有满足谓词 unaryPred 的元素都在不满足 unarypred 的元素之前，则返回 true。若序列为空，也返回 true
partition_copy(beg, end, dest1, dest2, unaryPred); // 将满足 unaryPred 的元素拷贝到到 dest1，并将不满足 unaryPred 的元素拷贝到到 dest2。返回一个迭代器 pair，其 first 成员表示拷贝到 dest1 的的元素的末尾，second 表示拷贝到 dest2 的元素的末尾。
partitioned_point(beg, end, unaryPred); // 输入序列必须是已经用 unaryPred 划分过的。返回满足  unaryPred 的范围的尾后迭代器。如果返回的迭代器不是 end，则它指向的元素及其后的元素必须都不满足 unaryPred
stable_partition(beg, end, unaryPred); // 使用 unaryPred 划分输入序列。满足 unaryPred 的元素放置在序列开始，不满足的元素放在序列尾部。返回一个迭代器，指向最后一个满足 unaryPred 的元素之后的位置如果所有元素都不满足 unaryPred，则返回 beg
partition(beg, end, unaryPred); // 使用 unaryPred 划分输入序列。满足 unaryPred 的元素放置在序列开始，不满足的元素放在序列尾部。返回一个迭代器，指向最后一个满足 unaryPred 的元素之后的位置如果所有元素都不满足 unaryPred，则返回 beg

// 排序算法，要求随机访问迭代器（random-access iterator）
sort(beg, end); // 排序整个范围
stable_sort(beg, end); // 排序整个范围（稳定排序）
sort(beg, end, comp); // 排序整个范围
stable_sort(beg, end, comp); // 排序整个范围（稳定排序）
is_sorted(beg, end); // 返回一个 bool 值，指出整个输入序列是否有序
is_sorted(beg, end, comp); // 返回一个 bool 值，指出整个输入序列是否有序
is_sorted_until(beg, end); // 在输入序列中査找最长初始有序子序列，并返回子序列的尾后迭代器
is_sorted_until(beg, end, comp); // 在输入序列中査找最长初始有序子序列，并返回子序列的尾后迭代器
partial_sort(beg, mid, end); // 排序 mid-beg 个元素。即，如果 mid-beg 等于 42，则此函数将值最小的 42 个元素有序放在序列前 42 个位置
partial_sort(beg, mid, end, comp); // 排序 mid-beg 个元素。即，如果 mid-beg 等于 42，则此函数将值最小的 42 个元素有序放在序列前 42 个位置
partial_sort_copy(beg, end, destBeg, destEnd); // 排序输入范围中的元素，并将足够多的已排序元素放到 destBeg 和 destEnd 所指示的序列中
partial_sort_copy(beg, end, destBeg, destEnd, comp); // 排序输入范围中的元素，并将足够多的已排序元素放到 destBeg 和 destEnd 所指示的序列中
nth_element(beg, nth, end); // nth 是一个迭代器，指向输入序列中第 n 大的元素。nth 之前的元素都小于等于它，而之后的元素都大于等于它
nth_element(beg, nth, end, comp); // nth 是一个迭代器，指向输入序列中第 n 大的元素。nth 之前的元素都小于等于它，而之后的元素都大于等于它

// 使用前向迭代器的重排算法。普通版本在输入序列自身内部重拍元素，_copy 版本完成重拍后写入到指定目的序列中，而不改变输入序列
remove(beg, end, val); // 通过用保留的元素覆盖要删除的元素实现删除 ==val 的元素，返回一个指向最后一个删除元素的尾后位置的迭代器
remove_if(beg, end, unaryPred); // 通过用保留的元素覆盖要删除的元素实现删除满足 unaryPred 的元素，返回一个指向最后一个删除元素的尾后位置的迭代器
remove_copy(beg, end, dest, val); // 通过用保留的元素覆盖要删除的元素实现删除 ==val 的元素，返回一个指向最后一个删除元素的尾后位置的迭代器
remove_copy_if(beg, end, dest, unaryPred); // 通过用保留的元素覆盖要删除的元素实现删除满足 unaryPred 的元素，返回一个指向最后一个删除元素的尾后位置的迭代器
unique(beg, end); // 通过对覆盖相邻的重复元素（用 == 确定是否相同）实现重排序列。返回一个迭代器，指向不重复元素的尾后位置
unique (beg, end, binaryPred); // 通过对覆盖相邻的重复元素（用 binaryPred 确定是否相同）实现重排序列。返回一个迭代器，指向不重复元素的尾后位置
unique_copy(beg, end, dest); // 通过对覆盖相邻的重复元素（用 == 确定是否相同）实现重排序列。返回一个迭代器，指向不重复元素的尾后位置
unique_copy_if(beg, end, dest, binaryPred); // 通过对覆盖相邻的重复元素（用 binaryPred 确定是否相同）实现重排序列。返回一个迭代器，指向不重复元素的尾后位置
rotate(beg, mid, end); // 围绕 mid 指向的元素进行元素转动。元素 mid 成为为首元素，随后是 mid+1 到到 end 之前的元素，再接着是 beg 到 mid 之前的元素。返回一个迭代器，指向原来在 beg 位置的元素
rotate_copy(beg, mid, end, dest); // 围绕 mid 指向的元素进行元素转动。元素 mid 成为为首元素，随后是 mid+1 到到 end 之前的元素，再接着是 beg 到 mid 之前的元素。返回一个迭代器，指向原来在 beg 位置的元素

// 使用双向迭代器的重排算法
reverse(beg, end); // 翻转序列中的元素，返回 void
reverse_copy(beg, end, dest);; // 翻转序列中的元素，返回一个迭代器，指向拷贝到目的序列的元素的尾后位置

// 使用随机访问迭代器的重排算法
random_shuffle(beg, end); // 混洗输入序列中的元素，返回 void
random_shuffle(beg, end, rand); // 混洗输入序列中的元素，rand 接受一个正整数的随机对象，返回 void
shuffle(beg, end, Uniform_rand); // 混洗输入序列中的元素，Uniform_rand 必须满足均匀分布随机数生成器的要求，返回 void

// 最小值和最大值，使用 < 运算符或给定的比较操作 comp 进行比较
min(val1, va12); // 返回 val1 和 val2 中的最小值，两个实参的类型必须完全一致。参数和返回类型都是 const的引引用，意味着对象不会被拷贝。下略
min(val1, val2, comp);
min(init_list);
min(init_list, comp);
max(val1, val2);
max(val1, val2, comp);
max(init_list);
max(init_list, comp);
minmax(val1, val2); // 返回一个 pair，其 first 成员为提供的值中的较小者，second 成员为较大者。下略
minmax(vall, val2, comp);
minmax(init_list);
minmax(init_list, comp);
min_element(beg, end); // 返回指向输入序列中最小元素的迭代器
min_element(beg, end, comp); // 返回指向输入序列中最小元素的迭代器
max_element(beg, end); // 返回指向输入序列中最大元素的迭代器
max_element(beg, end, comp); // 返回指向输入序列中最大元素的迭代器
minmax_element(beg, end); // 返回一个 pair，其中 first 成员为最小元素，second 成员为最大元素
minmax_element(beg, end, comp); // 返回一个 pair，其中 first 成员为最小元素，second 成员为最大元素

// 字典序比较，根据第一对不相等的元素的相对大小来返回结果。如果第一个序列在字典序中小于第二个序列，则返回 true。否则，返回 fa1se。如果个序列比另一个短，且所有元素都与较长序列的对应元素相等，则较短序列在字典序中更小。如果序列长度相等，且对应元素都相等，则在字典序中任何一个都不大于另外一个。
lexicographical_compare(beg1, end1, beg2, end2);
lexicographical_compare(beg1, end1, beg2, end2, comp);
```

* [C++之旅-vector](https://mp.weixin.qq.com/s/Pizq2-UcJi7rJLTwwxtRlw)
* Is Vector allocated on stack or heap ?
	* Heap
	* [c++ - When vectors are allocated, do they use memory on the heap or the stack? - Stack Overflow](https://stackoverflow.com/questions/8036474/when-vectors-are-allocated-do-they-use-memory-on-the-heap-or-the-stack#:~:text=So%20no%20matter%20how%20you,always%20allocated%20on%20the%20heap%20.)
		* vector\<Type> vect;
			* will allocate the vector, i.e. the header info, on the stack, but the elements on the free store ("heap").
		* vector\<Type> *vect = new vector\<Type>;
			* allocates everything on the free store.
		* vector\<Type*> vect;
			* will allocate the vector on the stack and a bunch of pointers on the free store, but where these point is determined by how you use them (you could point element 0 to the free store and element 1 to the stack, say).
* [Difference Between Vector and List - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-vector-and-list/)
	* Vector: Vector is a type of dynamic array which has the ability to resize automatically after insertion or deletion of elements. The elements in vector are placed in contiguous storage so that they can be accessed and traversed using iterators. Element is inserted at the end of the vector.
	* List: List is a double linked sequence that supports both forward and backward traversal. The time taken in the insertion and deletion in the beginning, end and middle is constant. It has the non-contiguous memory and there is no pre-allocated memory.

| Vector | List | 
| - | - | 
| It has contiguous memory.	| While it has non-contiguous memory. | 
| It is synchronized. | ??? While it is not synchronized. | 
| Vector may have a default size. | List does not have default size. | 
| In vector, each element only requires the space for itself only. | In list, each element requires extra space for the node which holds the element, including pointers to the next and previous elements in the list. | 
| Insertion at the end requires constant time but insertion elsewhere is costly. | Insertion is cheap no matter where in the list it occurs. | 
| Vector is thread safe. | ??? List is not thread safe. | 
| Deletion at the end of the vector needs constant time but for the rest it is O(n). | Deletion is cheap no matter where in the list it occurs. | 
| Random access of elements is possible. | Random access of elements is not possible. | 
| Iterators become invalid if elements are added to or removed from the vector. | Iterators are valid if elements are added to or removed from the list. | 

* [map vs unordered_map in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/map-vs-unordered_map-c/)
    * Use std::map when
        * You need ordered data.
        * You would have to print/access the data (in sorted order).
        * You need predecessor/successor of elements.
        * See advantages of BST over Hash Table for more cases.
    * Use std::unordered_map when
        * You need to keep count of some data (Example – strings) and no ordering is required.
        * You need single element access i.e. no traversal.

| - | map | unordered_map |
| - | - | - |
Ordering        | increasing order (by default)  | no ordering
Implementation  | Self balancing BST like Red-Black Tree | Hash Table
search time     | log(n)              | O(1) -> Average / O(n) -> Worst Case
Insertion time  | log(n) + Rebalance  | Same as search
Deletion time   | log(n) + Rebalance  | Same as search

* [How to use unordered_map efficiently in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/how-to-use-unordered_map-efficiently-in-c/)
    * C++ provides std::unordered_set and std::unordered_map to be used as a hash set and hash map respectively. They perform insertion/deletion/access in constant average time. 
    * However, the worst-case complexity is O(n2).
    * The reason is that the unordered_map store’s key-value pair by taking the modulo of input value by a prime number and then stores it in a hash table.
    * When the input data is big and input values are multiples of this prime number a lot of collisions take place and may cause the complexity of O(n2).
    * Depending on the compiler the prime number maybe 107897 or 126271.
    * Example 1: If we insert multiples of the above two prime numbers and compute execution time. One of the prime numbers takes a much longer time than the other.
        * The standard inbuilt hash function on which unordered_map works is similar to this:
        ```c++
        struct hash {
            size_t operator()(uint64_t x)
                const { return x; }
        };
        ```
        * The above function can produce numerous collisions. The keys inserted in HashMap are not evenly distributed, and after inserting numerous prime multiples, further insertion causes the hash function to reallocate all previous keys to new slots hence making it slow. So, the idea is that we have to randomize the hash function.
        * The idea is to use a method so that the keys in our hashmap are evenly distributed. This will prevent collisions to take place. For this, we use Fibonacci numbers. The golden ratio related to the Fibonacci sequence (Phi = 1.618) has a property that it can subdivide any range evenly without looping back to the starting position.
        * We can create our own simple hash function. Below is the hash function: 
        * Basically, the above hashing function generates random hash values to store keys. To know more about this please refer to this article Fibonacci hashing.
    * Example 2: Using the above hashing function, the program runs very quickly.
    ```c++
    // C++ program to determine worst case
    // time complexity of an unordered_map
    // using modified hash function

    #include <bits/stdc++.h>
    using namespace std;
    using namespace std::chrono;

    struct modified_hash {

        static uint64_t splitmix64(uint64_t x)
        {
            x += 0x9e3779b97f4a7c15;
            x = (x ^ (x >> 30))
                * 0xbf58476d1ce4e5b9;
            x = (x ^ (x >> 27))
                * 0x94d049bb133111eb;
            return x ^ (x >> 31);
        }

        int operator()(uint64_t x) const
        {
            static const uint64_t random
                = steady_clock::now()
                    .time_since_epoch()
                    .count();
            return splitmix64(x + random);
        }
    };

    int N = 55000;
    int prime1 = 107897;
    int prime2 = 126271;

    // Function to insert in the hashMap
    void insert(int prime)
    {
        auto start = high_resolution_clock::now();

        // Third argument in initialisation
        // of unordered_map ensures that
        // the map uses the hash function
        unordered_map<int, int, modified_hash>
            umap;

        // Inserting multiples of prime
        // number as key in the map
        for (int i = 1; i <= N; i++)
            umap[i * prime] = i;

        auto stop
            = high_resolution_clock::now();

        auto duration
            = duration_cast<milliseconds>(
                stop - start);

        cout << "for " << prime << " : "
            << duration.count() / 1000.0
            << " seconds "
            << endl;
    }

    // Driver Code
    int main()
    {
        // Function call for prime 1
        insert(prime1);

        // Function call for prime 2
        insert(prime2);
    }
    /*
    for 107897 : 0.025 seconds 
    for 126271 : 0.024 seconds
    */
    ```
    * Reserving space before hand 
        * By default, the capacity of unordered_map is 16 and a hash table is created for this. But every time, when threshold is reached, the capacity of the unordered_map is doubled and all the values are rehashed according to new hash table.
        * So, we can reserve the capacity beforehand according to our input size by using .reserve() method.
    * Setting max_load_factor
        * max_load_factor of unordered_map determines the probability of collision. Default value is set to 1.
        * By setting it to a lower value like 0.25 can decrease the probability of collisions by great extent.
    * Example : Using above two method can make umap faster : 
    ```c++
    #include <bits/stdc++.h>
    using namespace std;
    using namespace std::chrono;
    int N = 55000;
    int prime1 = 107897;
    int prime2 = 126271;

    void insert(int prime)
    {

        // Starting the clock
        auto start
            = high_resolution_clock::now();

        unordered_map<int, int> umap;
        umap.reserve(1024); // RESERVING SPACE BEFOREHAND
        umap.max_load_factor(0.25); // DECREASING MAX_LOAD_FACTOR
        // Inserting multiples of prime
        // number as key in the map
        for (int i = 1; i <= N; i++)
            umap[i * prime] = i;

        // Stopping the clock
        auto stop
            = high_resolution_clock::now();

        // Typecasting the time to
        // milliseconds
        auto duration
            = duration_cast<milliseconds>(
                stop - start);

        // Time in seconds
        cout << "for " << prime << " : "
            << duration.count() / 1000.0
            << " seconds "
            << endl;
    }

    // Driver code
    int main()
    {
        // Function call for prime 1
        insert(prime1);

        // Function call for prime 2
        insert(prime2);
    }
    /*
    for 107897 : 0.029 seconds
    for 126271 : 0.026 seconds
    */
    ```
* BST v.s. Hash Table
    * [Advantages of BST over Hash Table - GeeksforGeeks](https://www.geeksforgeeks.org/advantages-of-bst-over-hash-table/)
        * Following are some important points in favor of BSTs.
            * We can get all keys in sorted order by just doing Inorder Traversal of BST. This is not a natural operation in Hash Tables and requires extra efforts.
            * Doing order statistics, finding closest lower and greater elements, doing range queries are easy to do with BSTs. Like sorting, these operations are not a natural operation with Hash Tables.
            * BSTs are easy to implement compared to hashing, we can easily implement our own customized BST. To implement Hashing, we generally rely on libraries provided by programming languages.
            * With Self-Balancing BSTs, all operations are guaranteed to work in O(Logn) time. But with Hashing, Θ(1) is average time and some particular operations may be costly i.e, O(n2 ), especially when table resizing happens.
            * In BST we can do range searches efficiently but in Hash Table we cannot do range search efficienly.
            * BST are memory efficient but Hash table is not.
    * [What are Hash Functions and How to choose a good Hash Function? - GeeksforGeeks](https://www.geeksforgeeks.org/what-are-hash-functions-and-how-to-choose-a-good-hash-function/)
        * What is a Hash Function?
            * A function that converts a given big phone number to a small practical integer value. The mapped integer value is used as an index in the hash table. In simple terms, a hash function maps a big number or string to a small integer that can be used as the index in the hash table. 
        * What is meant by Good Hash Function? 
            * A good hash function should have the following properties: 
                * Efficiently computable.
                * Should uniformly distribute the keys (Each table position equally likely for each key)
        * In practice, we can often employ heuristic techniques to create a hash function that performs well. 
        * The two heuristic methods are hashing by division and hashing by multiplication which are as follows: 
            * The `mod` method: 
                * In this method for creating hash functions, we map a key into one of the slots of table by taking the remainder of key divided by table_size.
                * That is, the hash function is
                    * `h(key) = key mod table_size`
                    * `i.e. key % table_size`
                * Hence it can be seen that by this hash function, many keys can have the same hash. This is called `Collision`.
            * The `multiplication` method: 
                * In multiplication method, we multiply the key k by a constant real number c in the range 0 < c < 1 and extract the fractional part of k * c.
                * Then we multiply this value by table_size m and take the floor of the result. It can be represented as
                    * `h(k) = floor (m * (k * c mod 1))`
                    * or `h(k) = floor (m * frac (k * c))`
* class std::string
  * [string - C++ Reference](https://www.cplusplus.com/reference/string/string/)
  * [C++之旅-string](https://mp.weixin.qq.com/s/P2nd-9fmhpn20bB45hBioQ)

### [object slicing](https://en.wikipedia.org/wiki/Object_slicing)

* In C++ programming, `object slicing` occurs when an object of a `subclass` type is copied to an object of `superclass` type: the `superclass copy` will not have any of the member variables defined in the `subclass`. These variables have, in effect, been `sliced off`.) More subtly, object slicing can also occur when an object of a subclass type is copied to an object of the same type by the superclass's assignment operator, in which case some of the target object's member variables will retain their original values instead of being copied from the source object.
* This issue is not inherently unique to C++, but it does not occur naturally in most other object-oriented languages — even C++'s relatives such as D, Java, and C# — because copying of objects is not a basic operation in those languages. (Instead, those languages prefer to manipulate objects via implicit references, such that only copying the reference is a basic operation.) In C++, by contrast, objects are copied automatically whenever a function takes an object argument by value or returns an object by value. Additionally, due to the lack of garbage collection in C++, programs will frequently copy an object whenever the ownership and lifetime of a single shared object would be unclear; for example, inserting an object into a standard-library collection, such as a std::vector, actually involves inserting a copy into the collection.
* [c++对象切割 - CSDN博客](https://blog.csdn.net/weiwangchao_/article/details/4702241)

### [Exceptions](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#exceptions)

* 异常,异常的功能
    * 保证异常的健壮性，结构化处理出错信息
```c++
#include <iostream>

template<typename T>
double SafeDivide(T n, T d)
{
    if (0 == d) {
        throw ("Division by 0");
    }

    return static_cast<double>(n) / d;
}

int main()
{
    try {
        SafeDivide(3, 0);
    } catch (const char* err) {
        std::cout << err << '\n';   // Division by 0
    }

    return 0;
}
```

* Exception safety
    * After the error condition is reported by a function, additional guarantees may be provided with regards to the state of the program. The following four levels of exception guarantee are generally recognized[4][5][6], which are strict supersets of each other:
        * `Nothrow (or nofail) exception guarantee` -- the function never throws exceptions. Nothrow (errors are reported by other means or concealed) is expected of destructors and other functions that may be called during stack unwinding. The destructors are noexcept by default. (since C++11) Nofail (the function always succeeds) is expected of swaps, move constructors, and other functions used by those that provide strong exception guarantee.
        * `Strong exception guarantee` -- If the function throws an exception, the state of the program is rolled back to the state just before the function call. (for example, std::vector::push_back)
        * `Basic exception guarantee` -- If the function throws an exception, the program is in a valid state. No resources are leaked, and all objects' invariants are intact.
        * `No exception guarantee` -- If the function throws an exception, the program may not be in a valid state: resource leaks, memory corruption, or other invariant-destroying errors may have occurred.
    * Generic components may, in addition, offer exception-neutral guarantee: if an exception is thrown from a template parameter (e.g. from the Compare function object of std::sort or from the constructor of T in std::make_shared), it is propagated, unchanged, to the caller.
	* [Exception safety - Wikipedia](https://en.wikipedia.org/wiki/Exception_safety)
		* The C++ standard library provides several levels of exception safety (in decreasing order of safety):[6]
			* No-throw guarantee, also known as failure transparency: Operations are guaranteed to succeed and satisfy all requirements even in exceptional situations. If an exception occurs, it will be handled internally and not observed by clients.
			* Strong exception safety, also known as commit or rollback semantics: Operations can fail, but failed operations are guaranteed to have no side effects, leaving the original values intact.[7]
			* Basic exception safety: Partial execution of failed operations can result in side effects, but all invariants are preserved. Any stored data will contain valid values which may differ from the original values. Resource leaks (including memory leaks) are commonly ruled out by an invariant stating that all resources are accounted for and managed.
			* No exception safety: No guarantees are made.
	* [How to: Design for exception safety | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/how-to-design-for-exception-safety?view=msvc-170#:~:text=A%20basic%20axiom%20of%20C%2B%2B,on%20all%20destructors%20it%20defines.)
		* Typically, exception safety is discussed in terms of the three exception guarantees that a function can provide: the no-fail guarantee, the strong guarantee, and the basic guarantee.
		* No-fail guarantee
			* The no-fail (or, "no-throw") guarantee is the strongest guarantee that a function can provide. It states that the function will not throw an exception or allow one to propagate. However, you cannot reliably provide such a guarantee unless (a) you know that all the functions that this function calls are also no-fail, or (b) you know that any exceptions that are thrown are caught before they reach this function, or (c) you know how to catch and correctly handle all exceptions that might reach this function.
			* Both the strong guarantee and the basic guarantee rely on the assumption that the destructors are no-fail. All containers and types in the Standard Library guarantee that their destructors do not throw. There is also a converse requirement: The Standard Library requires that user-defined types that are given to it—for example, as template arguments—must have non-throwing destructors.
		* Strong guarantee
			* The strong guarantee states that if a function goes out of scope because of an exception, it will not leak memory and program state will not be modified. A function that provides a strong guarantee is essentially a transaction that has commit or rollback semantics: either it completely succeeds or it has no effect.
		* Basic guarantee
			* The basic guarantee is the weakest of the three. However, it might be the best choice when a strong guarantee is too expensive in memory consumption or in performance. The basic guarantee states that if an exception occurs, no memory is leaked and the object is still in a usable state even though the data might have been modified.

#### [noexcept](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#noexcept-specifier)

* There may be exception handling necessary in a `noexcept` function
    * [C++ static code analysis: Exceptions should not be thrown in "noexcept" functions](https://rules.sonarsource.com/cpp/RSPEC-3743)
    * noexcept is a specifier that can be applied to a function declaration to state whether or not this function might throw an exception.
    * This specifier is a crucial information for the compiler as it enables it to perform automatic optimizations. It is also used by the noexcept operator, so that a developer can know whether an expression can throw, and adapt the code accordingly (for instance, to decide to move or copy an object).
    * When a function is specified noexcept, the compiler does not generate any code to throw exceptions and any uncaught exception will result in a call to std::terminate. This means that writing a noexcept function is an implicit agreement to the statement : "my program will terminate if any exception is thrown inside this function".
    * It is a very strong commitment as there are so many ways to get an exception including any dynamic allocation.
    * This rule raises an issue when an exception is thrown, directly or indirectly, from a function declared noexcept.
    * Noncompliant Code Example
    ```c++
    #include <exception>
    #include <memory>

    using namespace std;

    class SafetyException {};
    class Engine {};
    unique_ptr<Engine> engine;

    bool safety_check() noexcept;
    void other_checks();

    void critical_checks() {
      if (!safety_check()) {
        throw SafetyException{};
      }
    }

    void do_checks() {
      critical_checks(); // can throw
      other_checks(); // can throw
    }

    void init() noexcept(true) { // noncompliant because...
      do_checks(); // can throw
      engine = std::make_unique<Engine>(); // can throw
    }
    ```
    * Compliant Solution
    ```c++
    #include <exception>
    #include <memory>

    using namespace std;

    class SafetyException {};
    class Engine {};
    unique_ptr<Engine> engine;

    bool safety_check();
    void other_checks();

    void critical_checks() {
      if (!safety_check()) {
        throw SafetyException{};
      }
    }

    void do_checks() {
      critical_checks();
      other_checks();
    }

    void init() noexcept(true) { // compliant because ...
      try {
        do_checks(); // exception caught
        engine = std::make_unique<Engine>(); // exception caught
      } catch(std::exception e) {
        std::terminate();
      }
    }
    ```
    * Exceptions
        * Destructors are not handled by this rule because there is a specific rule about exceptions in destructors (see ExceptionInDestructor).

## Idioms

* [Curiously Recurring Template Pattern](https://github.com/haoran119/c-cpp/blob/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC-C++/README.md#curiously-recurring-template-pattern-crtp)
	* The Curiously Recurring Template Pattern is an idiom in which a class X derives from a class template Y, taking a template parameter Z, where Y is instantiated with Z=X.
	* CRTP may be used to implement "compile-time polymorphism", when a base class exposes an interface, and derived classes implement such interface.
* [DRY - Don't repeat yourself - Wikipedia](https://en.wikipedia.org/wiki/Don't_repeat_yourself)
    * "Don't repeat yourself" (DRY, or sometimes "do not repeat yourself") is a principle of software development aimed at reducing repetition of software patterns,[1] replacing it with abstractions or using data normalization to avoid redundancy.
    * The DRY principle is stated as "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system". The principle has been formulated by Andy Hunt and Dave Thomas in their book The Pragmatic Programmer.[2] They apply it quite broadly to include "database schemas, test plans, the build system, even documentation".[3] When the DRY principle is applied successfully, a modification of any single element of a system does not require a change in other logically unrelated elements. Additionally, elements that are logically related all change predictably and uniformly, and are thus kept in sync. Besides using methods and subroutines in their code, Thomas and Hunt rely on code generators, automatic build systems, and scripting languages to observe the DRY principle across layers.
* [PImpl - cppreference.com](https://en.cppreference.com/w/cpp/language/pimpl)
	* "Pointer to implementation" or "pImpl" is a C++ programming technique[1] that removes implementation details of a class from its object representation by placing them in a separate class, accessed through an opaque pointer
	* This technique is used to construct C++ library interfaces with stable ABI and to reduce compile-time dependencies.
	* [Application binary interface - Wikipedia](https://en.wikipedia.org/wiki/Application_binary_interface)
	    * In computer software, an `application binary interface (ABI)` is an `interface between two binary program modules`. Often, one of these modules is a `library or operating system facility`, and the other is a `program that is being run by a user`.
	    * An `ABI` defines how data structures or computational routines are accessed in `machine code`, which is a `low-level, hardware-dependent format`. In contrast, an `API` defines this access in `source code`, which is a relatively `high-level, hardware-independent, often human-readable format`. A common aspect of an ABI is the [calling convention](https://en.wikipedia.org/wiki/Calling_convention), which determines how data is provided as input to, or read as output from, computational routines. Examples of this are the x86 calling conventions.
	    * Adhering to an ABI (which may or may not be officially standardized) is usually the job of a compiler, operating system, or library author. However, an application programmer may have to deal with an ABI directly when writing a program in a mix of programming languages, or even compiling a program written in the same language with different compilers.
* [Race condition](https://en.wikipedia.org/wiki/Race_condition)
	* A race condition or race hazard is the condition of an electronics, software, or other system where the system's substantive behavior is dependent on the sequence or timing of other uncontrollable events. It becomes a bug when one or more of the possible behaviors is undesirable.
	* [multithreading - What is a race condition? - Stack Overflow](https://stackoverflow.com/questions/34510/what-is-a-race-condition)
		* A race condition occurs when two or more threads can access shared data and they try to change it at the same time. Because the thread scheduling algorithm can swap between threads at any time, you don't know the order in which the threads will attempt to access the shared data. Therefore, the result of the change in data is dependent on the thread scheduling algorithm, i.e. both threads are "racing" to access/change the data.
* [RAII - cppreference.com](https://en.cppreference.com/w/cpp/language/raii)
	* Resource Acquisition Is Initialization or RAII, is a C++ programming technique[1][2] which binds the life cycle of a resource that must be acquired before use (allocated heap memory, thread of execution, open socket, open file, locked mutex, disk space, database connection—anything that exists in limited supply) to the lifetime of an object.
	* RAII can be summarized as follows:
		* encapsulate each resource into a class, where
			* the constructor acquires the resource and establishes all class invariants or throws an exception if that cannot be done,
			* the destructor releases the resource and never throws exceptions;
		* always use the resource via an instance of a RAII-class that either
			* has automatic storage duration or temporary lifetime itself, or
			* has lifetime that is bounded by the lifetime of an automatic or temporary object
	* Move semantics make it possible to safely transfer resource ownership between objects, across scopes, and in and out of threads, while maintaining resource safety.
	* Classes with open()/close(), lock()/unlock(), or init()/copyFrom()/destroy() member functions are typical examples of non-RAII classes
    * [RAII - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/RAII)
        * RAII全称为Resource Acquisition Is Initialization，它是在一些面向对象语言中的一种惯用法。RAII源于C++，在Java，C#，D，Ada，Vala和Rust中也有应用。1984-1989年期间，比雅尼·斯特劳斯特鲁普和安德鲁·柯尼希在设计C++异常时，为解决资源管理时的异常安全性而使用了该用法，后来比雅尼·斯特劳斯特鲁普将其称为RAII。
        * RAII要求，资源的有效期与持有资源的对象的生命期严格绑定，即由对象的构造函数完成资源的分配(获取)，同时由析构函数完成资源的释放。在这种要求下，只要对象能正确地析构，就不会出现资源泄露问题。
    * [RAII_百度百科](http://baike.baidu.com/link?url=cZ_EqWVrbxk9AIOFJ-9IrYDMRVaeEtubQlI-JKvquwrTkm9clZshXDLN9WM1Kth0W98ADgTckgMMEAwmQ3gZDq)
        * RAII，也称为“资源获取就是初始化”，是c++等编程语言常用的管理资源、避免内存泄露的方法。它保证在任何情况下，使用对象时先构造对象，最后析构对象。
        * [对象所有资源 (RAII)](https://msdn.microsoft.com/zh-cn/library/hh438480.aspx)
* RTTI
    * RTTI事指运行时类型识别（Run-time type identification）在只有一个指向基类的指针或引用时确定一个对象的准确类型。
* [SOLID - Wikipedia](https://en.wikipedia.org/wiki/SOLID)
    * In software engineering, SOLID is a mnemonic acronym for five design principles intended to make software designs more understandable, flexible, and maintainable. The principles are a subset of many principles promoted by American software engineer and instructor Robert C. Martin,[1][2][3] first introduced in his 2000 paper Design Principles and Design Patterns.[2][4]
    * The `SOLID` concepts are
        * The `Single-responsibility principle`: "There should never be more than one reason for a class to change."[5] In other words, every class should have only one responsibility.[6]
        * The `Open–closed principle`: "Software entities ... should be open for extension, but closed for modification."[7]
        * The `Liskov substitution principle`: "Functions that use pointers or references to base classes must be able to use objects of derived classes without knowing it."[8] See also design by contract.[8]
        * The `Interface segregation principle`: "Many client-specific interfaces are better than one general-purpose interface."[9][4]
        * The `Dependency inversion principle`: "Depend upon abstractions, [not] concretions."[10][4]
* [The rule of three/five/zero - cppreference.com](https://en.cppreference.com/w/cpp/language/rule_of_three)
	* `Rule of three`
		* If a class requires a user-defined destructor, a user-defined copy constructor, or a user-defined copy assignment operator, it almost certainly requires all three.
		* Because C++ copies and copy-assigns objects of user-defined types in various situations (passing/returning by value, manipulating a container, etc), these special member functions will be called, if accessible, and if they are not user-defined, they are implicitly-defined by the compiler.
		* The implicitly-defined special member functions are typically incorrect if the class manages a resource whose handle is an object of non-class type (raw pointer, POSIX file descriptor, etc), whose destructor does nothing and copy constructor/assignment operator performs a "shallow copy" (copy the value of the handle, without duplicating the underlying resource).
		* Classes that manage non-copyable resources through copyable handles may have to declare copy assignment and copy constructor private and not provide their definitions or define them as deleted. This is another application of the rule of three: deleting one and leaving the other to be implicitly-defined will most likely result in errors.
	* `Rule of five`
		* Because the presence of a user-defined (or = default or = delete declared) destructor, copy-constructor, or copy-assignment operator prevents implicit definition of the move constructor and the move assignment operator, any class for which move semantics are desirable, has to declare all five special member functions
		* Unlike Rule of Three, failing to provide move constructor and move assignment is usually not an error, but a missed optimization opportunity.
		* [C.21: If you define or =delete any copy, move, or destructor function, define or =delete them all](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c21-if-you-define-or-delete-any-copy-move-or-destructor-function-define-or-delete-them-all)
		    * `Reason` `The semantics of copy, move, and destruction are closely related, so if one needs to be declared, the odds are that others need consideration too.`
		    * Declaring any copy/move/destructor function, even as `=default` or `=delete`, will suppress the implicit declaration of a move constructor and move assignment operator. Declaring a move constructor or move assignment operator, even as `=default` or `=delete`, will cause an implicitly generated copy constructor or implicitly generated copy assignment operator to be defined as deleted. So as soon as any of these are declared, the others should all be declared to avoid unwanted effects like turning all potential moves into more expensive copies, or making a class move-only.
		    * `Example, bad`
            ```c++
            struct M2 {   // bad: incomplete set of copy/move/destructor operations
            public:
                // ...
                // ... no copy or move operations ...
                ~M2() { delete[] rep; }
            private:
                pair<int, int>* rep;  // zero-terminated set of pairs
            };

            void use()
            {
                M2 x;
                M2 y;
                // ...
                x = y;   // the default assignment
                // ...
            }
            ```
            * Given that “special attention” was needed for the destructor (here, to deallocate), the likelihood that the implicitly-defined copy and move assignment operators will be correct is low (here, we would get `double deletion`).
            * `Note` This is known as `the rule of five.`
            * `Note` If you want a default implementation (while defining another), write `=default` to show you’re doing so intentionally for that function. If you don’t want a generated default function, suppress it with `=delete`.
            * `Example, good` When a destructor needs to be declared just to make it virtual, it can be defined as defaulted.
            ```c++
            class AbstractBase {
            public:
                virtual ~AbstractBase() = default;
                // ...
            };
            ```
            * To prevent slicing as per [C.67](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rc-copy-virtual), make the copy and move operations protected or `=delete`d, and add a `clone`:
            ```c++
            class ClonableBase {
            public:
                virtual unique_ptr<ClonableBase> clone() const;
                virtual ~ClonableBase() = default;
                CloneableBase() = default;
                ClonableBase(const ClonableBase&) = delete;
                ClonableBase& operator=(const ClonableBase&) = delete;
                ClonableBase(ClonableBase&&) = delete;
                ClonableBase& operator=(ClonableBase&&) = delete;
                // ... other constructors and functions ...
            };
            ```
            * Defining only the move operations or only the copy operations would have the same effect here, but stating the intent explicitly for each special member makes it more obvious to the reader.
            * `Note` Compilers enforce much of this rule and ideally warn about any violation.
            * `Note` Relying on an implicitly generated copy operation in a class with a destructor is deprecated.
            * `Note` Writing these functions can be error-prone. Note their argument types:
            ```c++
            class X {
            public:
                // ...
                virtual ~X() = default;            // destructor (virtual if X is meant to be a base class)
                X(const X&) = default;             // copy constructor
                X& operator=(const X&) = default;  // copy assignment
                X(X&&) = default;                  // move constructor
                X& operator=(X&&) = default;       // move assignment
            };
            ```
            * A minor mistake (such as a misspelling, leaving out a `const`, using `&` instead of `&&`, or leaving out a special function) can lead to errors or warnings. To avoid the tedium and the possibility of errors, try to follow the [rule of zero](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rc-zero).
            * `Enforcement` (Simple) A class should have a declaration (even a `=delete` one) for either `all` or `none` of the `copy/move/destructor functions`.
	* `Rule of zero`
		* Classes that have custom destructors, copy/move constructors or copy/move assignment operators should deal exclusively with ownership (which follows from the Single Responsibility Principle). Other classes should not have custom destructors, copy/move constructors or copy/move assignment operators[1].
		* This rule also appears in the C++ Core Guidelines as [C.20: If you can avoid defining default operations, do](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c20-if-you-can-avoid-defining-default-operations-do).
		    * `Reason` It’s the simplest and gives the cleanest semantics.
		    * `Example`
            ```c++
            struct Named_map {
            public:
                // ... no default operations declared ...
            private:
                string name;
                map<int, int> rep;
            };

            Named_map nm;        // default construct
            Named_map nm2 {nm};  // copy construct
            ```
            * Since std::map and string have all the special functions, no further work is needed.
            * `Note` This is known as `the rule of zero`.
            * `Enforcement` (Not enforceable) While not enforceable, a good static analyzer can detect patterns that indicate a possible improvement to meet this rule. For example, a class with a (pointer, size) pair of members and a destructor that `delete`s the pointer could probably be converted to a `vector`.
		* When a base class is intended for polymorphic use, its destructor may have to be declared public and virtual. This blocks implicit moves (and deprecates implicit copies), and so the special member functions have to be declared as defaulted[2].
		* however, this makes the class prone to slicing, which is why polymorphic classes often define copy as deleted (see [C.67: A polymorphic class should suppress copying](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c67-a-polymorphic-class-should-suppress-public-copymove) in C++ Core Guidelines), which leads to the following generic wording for the `Rule of Five`: [C.21: If you define or =delete any default operation, define or =delete them all](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c21-if-you-define-or-delete-any-copy-move-or-destructor-function-define-or-delete-them-all)
		* [C.67: A polymorphic class should suppress copying](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c67-a-polymorphic-class-should-suppress-public-copymove)
		    * `Reason` A `polymorphic class` is a class that `defines or inherits at least one virtual function`. It is likely that it will be used as a base class for other derived classes with polymorphic behavior. If it is accidentally passed by value, with the implicitly generated copy constructor and assignment, we risk `slicing`: only the base portion of a derived object will be copied, and the polymorphic behavior will be corrupted.
		    * If the class has no data, `=delete` the `copy/move` functions. Otherwise, make them `protected`.
		    * `Example, bad`
            ```c++
            class B { // BAD: polymorphic base class doesn't suppress copying
            public:
                virtual char m() { return 'B'; }
                // ... nothing about copy operations, so uses default ...
            };

            class D : public B {
            public:
                char m() override { return 'D'; }
                // ...
            };

            void f(B& b)
            {
                auto b2 = b; // oops, slices the object; b2.m() will return 'B'
            }

            D d;
            f(d);
            ```
            * `Example`
            ```c++
            class B { // GOOD: polymorphic class suppresses copying
            public:
                B() = default;
                B(const B&) = delete;
                B& operator=(const B&) = delete;
                virtual char m() { return 'B'; }
                // ...
            };

            class D : public B {
            public:
                char m() override { return 'D'; }
                // ...
            };

            void f(B& b)
            {
                auto b2 = b; // ok, compiler will detect inadvertent copying, and protest
            }

            D d;
            f(d);
            ```
            * `Note` If you need to create deep copies of polymorphic objects, use clone() functions: see [C.130](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rh-copy).
            * `Exception` Classes that represent exception objects need both to be polymorphic and copy-constructible.
            * `Enforcement`
                * Flag a polymorphic class with a public copy operation.
                * Flag an assignment of polymorphic class objects.
	* [Rule of three (C++ programming) - Wikipedia](https://en.wikipedia.org/wiki/Rule_of_three_(C%2B%2B_programming))
* [Zero-overhead principle - cppreference.com](https://en.cppreference.com/w/cpp/language/Zero-overhead_principle)
	* The `zero-overhead principle` is a C++ design principle that states:
		* You don't pay for what you don't use.
		* What you do use is just as efficient as what you could reasonably write by hand.
	* In general, this means that no feature should be added to C++ that would impose any overhead, whether in time or space, greater than a programmer would introduce without using the feature.
	* The only two features in the language that do not follow the zero-overhead principle are [runtime type identification](https://en.cppreference.com/w/cpp/language/typeid) and [exceptions](https://en.cppreference.com/w/cpp/language/exceptions), and are why most compilers include a switch to turn them off.

## CODE

* [c-cpp/面试总结之C-C++ at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E9%9D%A2%E8%AF%95%E6%80%BB%E7%BB%93%E4%B9%8BC-C%2B%2B)
* [C/C++ 10 大常见基础算法](https://mp.weixin.qq.com/s/tGGNGpaRcWwKiNoQyo-TXw)
* 用C语言，将一个数字乘以7倍的效率最快的方法是什么？ 
    * 先左移三位（*8）然后再减去原值：X << 3 – X

### Const

```c++
/*
What's wrong, and how to fix?

Const variable aaa should be initialized when being defined.
To fix it, we could take any one action as below.
1) Initialize aaa in construct function
2) Assign a value in this statement const int aaa;
3) Remove keyword const
*/

class TryConst
{
public:
    TryConst () {}
private:
    const int aaa;
};
```
```c++
/*
How to fix it to successfully compile ?

Change Process() as (1) or (2)
*/

class MyClass {
    int i;
public:
    constexpr MyClass() : i(0) {}
    void ChangeVar(int tmp) { i = tmp; }
};

void Process(const MyClass& m) {
// void Process(MyClass& m) {   // (1)
    m.ChangeVar(10);    // error: passing 'const MyClass' as 'this' argument discards qualifiers
    // const_cast<MyClass&>(m).ChangeVar(10);   // (2)
}
```
```c++
#include <iostream>

struct A {
    int x{0};
    int get() { std::cout << "get()" << '\n'; return x ++; }
    int get() const { std::cout << "get() const" << '\n'; return x; }
};

int main() 
{
    A a;
    std::cout << a.x << '\n';   // 0

    auto x = a.get();           // get()
    std::cout << x << '\n';     // 0
    std::cout << a.x << '\n';   // 1

    auto y = a.get();           // get()
    std::cout << y << '\n';     // 1
    std::cout << a.x << '\n' << '\n';   // 2

    const auto &b = a;          
    std::cout << b.x << '\n';   // 2

    auto x_ = b.get();          // get() const
    std::cout << x_ << '\n';    // 2
    std::cout << b.x << '\n';   // 2

    auto y_ = b.get();          // get() const
    std::cout << y_ << '\n';    // 2
    std::cout << b.x << '\n';   // 2

    return 0;
}
```

### Static

```c++
/*
What's wrong, and how to fix?

Static variable could not be initialized inside the class.
To fix it, we could initialize it outside the class, e.g. int aa = 0.
*/

class TryStatic
{
public:
    TryStatic () : aa (0) {}
private:
    static int aa;
};

// int TryStatic::aa = 1;
```

### Double

```c++
// What is the output of the following program
// Will the output change if x and y are declared as constexpr / No

#include <iostream>
#include <limits>

void F1() {
    double x = 1.2 / 8.0;
    double y = (32 / 256.0) * 1.2;
    std::cout << x << '\n' << y << '\n';
    if (x == y) {
        std::cout << "F1: Yes they are equal" << std::endl;
    } else {
        std::cout << "F1: No they are not" << std::endl;
    }
}

void F2() {
    double x = 1.2 / 7;
    double y = (21.0 / 147) * 1.2;
    std::cout << x << '\n' << y << '\n';
    if (x == y) {
        std::cout << "F2: Yes they are equal" << std::endl;
    } else {
        std::cout << "F2: No they are not" << std::endl;
    }
}

void F3() {
    double x = 1.2 / 7;
    double y = (32.0 / 224) * 1.2;
    std::cout << x << '\n' << y << '\n';
    if (x == y) {
        std::cout << "F3: Yes they are equal" << std::endl;
    } else {
        std::cout << "F3: No they are not" << std::endl;
    }
}

void F1_() {
    constexpr double x = 1.2 / 8.0;
    constexpr double y = (32 / 256.0) * 1.2;
    std::cout << x << '\n' << y << '\n';
    if (x == y) {
        std::cout << "F1: Yes they are equal" << std::endl;
    } else {
        std::cout << "F1: No they are not" << std::endl;
    }
}

void F2_() {
    constexpr double x = 1.2 / 7;
    constexpr double y = (21.0 / 147) * 1.2;
    std::cout << x << '\n' << y << '\n';
    if (x == y) {
        std::cout << "F2: Yes they are equal" << std::endl;
    } else {
        std::cout << "F2: No they are not" << std::endl;
    }
}

void F3_() {
    constexpr double x = 1.2 / 7;
    constexpr double y = (32.0 / 224) * 1.2;
    std::cout << x << '\n' << y << '\n';
    if (x == y) {
        std::cout << "F3: Yes they are equal" << std::endl;
    } else {
        std::cout << "F3: No they are not" << std::endl;
    }
}

int main() {
  std::cout << std::numeric_limits<double>::epsilon() << '\n';

  F1();
  F2();
  F3();

  F1_();
  F2_();
  F3_();

  return 0;
}

/*
2.22045e-16
0.15
0.15
F1: Yes they are equal
0.171429
0.171429
F2: No they are not
0.171429
0.171429
F3: No they are not
0.15
0.15
F1: Yes they are equal
0.171429
0.171429
F2: No they are not
0.171429
0.171429
F3: No they are not
*/
```

### String

```c++
#include <iostream>
using namespace std;

void compare_str()
{
    string s1 = "Abc";
    string s2 = "A";

    s1 = s1 + s2;
    s2 = s2 + s1;

    cout << s1 << endl;  // AbcA
    cout << s2 << endl;  // AAbcA
    cout << s1.length() << endl; // 4
    cout << s2.length() << endl; // 5
    cout << (s1.compare(s2) > 0) << endl; // 1
}

int main()
{
    compare_str();

    return 0;
}
```
```c++
#include <iostream>
using namespace std;

void f(string x, string& y)
{
    x += "x";
    y += "y";

    cout << x << " " << y << " ";
}

int main()
{
    string x = "x";
    string y = "y";

    f(x, y);
    cout << x << " " << y << "\n";

    return 0;
}

// xx yy x yy
```

### Pointer

* [一道C语言指针的题目](https://mp.weixin.qq.com/s/KqbMSR_rYD7ziWt-YsrYRQ)
```c++
#include <iostream>
using namespace std;

int foo(int &p)
{
    ++ p;

    return p ++;
}

int main()
{
    int a = 1, b, d;
    int * const c = &d;
    b = foo(a);
    *c = 10;

    cout << a << endl;  // 3
    cout << b << endl;  // 2
    cout << *c << endl; // 10
    cout << d << endl;  // 10

    return 0;
}
```
```c++
#include <cstdio>
#include <cstring>

int atoi(char* s)
{
    if (s == nullptr) {         // remember to check
        return 0;
    }

    int result = 0;

    bool is_negative = false;   // remember to check
    if (*s == '-') {
        is_negative = true;
        ++ s;
    }

    while (*s) {
        result = result * 10 + *s - '0';
        ++ s;
    }

    return is_negative ? -result : result;  // remember for negative
}

int main()
{
    char* s = new char[4];      // remember to new and one more place for '\0'

    strcpy(s, "123");
    printf("%d\n", atoi(s));

    strcpy(s, "-23");
    printf("%d\n", atoi(s));

    delete [] s;                // remember to delete

    return 0;
}
```
```c++
/*
What's the result ?
*/

#include <iostream>
#include <vector>
#include <memory>

class MyClass {
public:
    ~MyClass() { std::cout << "Goodbye" << '\n'; }
    void Hello() { std::cout << "Hello" << '\n'; }
};

int main()
{
    // Hello
    // std::vector<MyClass*> v { new MyClass, new MyClass, new MyClass };

    /*
    Hello
    Goodbye
    Goodbye
    Goodbye    
    */
    std::vector<std::shared_ptr<MyClass> > v {
        std::shared_ptr<MyClass>(new MyClass),
        std::shared_ptr<MyClass>(new MyClass),
        std::shared_ptr<MyClass>(new MyClass)
    };

    // error: static assertion failed: result type must be constructible from input type
    // std::vector<std::unique_ptr<MyClass> > v {
    //     std::unique_ptr<MyClass>(new MyClass),
    //     std::unique_ptr<MyClass>(new MyClass),
    //     std::unique_ptr<MyClass>(new MyClass)
    // };

    // error: no matching function for call to 
    // 'std::vector<std::weak_ptr<MyClass> >::vector(<brace-enclosed initializer list>)'
    // std::vector<std::weak_ptr<MyClass> > v { new MyClass, new MyClass, new MyClass };

    v[0]->Hello();   // Hello

    {
        // auto v1 = std::unique_ptr<MyClass>(new MyClass);
        // v1->Hello();  // Hello
        // auto v2 = std::unique_ptr<MyClass>(new MyClass);
        // v2->Hello();  // Hello
        // Goodbye
        // Goodbye
    }

    return 0;
}
```

### Reference

```c++
/*
What's wrong ?

* The reference to the temporary variable c can fall out of scope when returned
* Returning a value instead of a reference will prevent issues for callers

*/

const double PI = 3.14159265;
double& calculateCircumreference(double r)
{
    double c = 2 * PI * r;
    return c;
}
```

### Lambda

```c++
/*
How to substitute *** to correctly capture the normalization_factor ?

* [&]
* [=]
    * warning: implicit capture of 'this' via '[=]' is deprecated in C++20 [-Wdeprecated]
*/

#include <iostream>
#include <algorithm>
#include <vector>

class FFT {
public:
    using SampleData = std::vector<double>;

    void normalize()
    {
        std::for_each(samples.begin(), samples.end(), 
                        *** (double& elem) {
                            elem *= normalization_factor;
                        });
    }

private:
    SampleData samples;
    double  normalization_factor;
};
```

### Class

#### constructor / destructor

```c++
/*
What will be printed, and why?

data=1.
Because class B inherits class A, it would call constructor of A and B when constructing b. 
When calling the constructor of A, A::SetData() was called, so data was set to 1.
*/

class A
{
public:
    A () : data (0) { SetData (); printf ("data=%d", data); }
    virtual void SetData () { data = 1; }
protected:
    int data;
};

class B : public A
{
public:
    B () {}
    virtual void SetData () { data = 2; }
};

int main(int argc, char* argv[])
{
    B b;
    return 0;
}
```
```c++
#include <iostream>

class A
{
public:
    A() { std::cout << "A()\n"; }
    ~A() { std::cout << "~A()\n"; }
};

class B : public A
{
public:
    B() { std::cout << "B()\n"; }
    ~B() { std::cout << "~B()\n"; }
};

int main()
{
    B b;    // A() B()
    A* p = new B;   // A() B()
    delete p;   // ~A()

    return 0;
}   // ~B() ~A()
```
```c++
#include <iostream>

class Base
{
public:
    Base() { std::cout << "Base()\n"; }
    ~Base() { std::cout << "~Base()\n"; }
};

class Base2
{
public:
    Base2() { std::cout << "Base2()\n"; }
    ~Base2() { std::cout << "~Base2()\n"; }
};

class Derive : public Base, Base2
{
public:
    Derive() { std::cout << "Derive()\n"; }
    ~Derive() { std::cout << "~Derive()\n"; }
};

int main()
{
    Derive b;    // Base() Base2() Derive()
    Base* p = new Derive;   // Base() Base2() Derive()
    delete p;   // ~Base()

    return 0;
}   // ~Derive() ~Base2() ~Base()
```
```c++
#include<iostream>

struct A {
    A(int value) : m_value(value)
    {
        std::cout << "A(" << m_value << ")" << std::endl;
    }

    ~A()
    {
        std::cout << "~A(" << m_value << ")" << std::endl;
    }

    A(const A& other) : m_value(other.m_value)
    {
        std::cout << "copy constructor" << std::endl;
    }

    A& operator=(const A& other)
    {
        std::cout << "copy assignment" << std::endl;
        this->m_value = other.m_value;
        return *this;
    }

    int m_value;
};

int main()
{
    A a(1);         // A(1)

    {
        A aa(a);   // copy constructor
    }               // ~A(1)

    {
        A aaa = a;   // copy constructor
    }               // ~A(1)

    {
        A b(2);     // A(2)
        b = a;      // copy assignment
    }               // ~A(1)

    return 0;
}                   // ~A(1)
```
```c++
/*
What's wrong and how to fix ?

1. Memory leak. To fix it, define a destructor to release namePtr.
2. Shallow copy. The namePtr member in both president and chairman will point to the same memory location. 
To fix it, define a copy constructor and copy assignment operator.
*/

#include <iostream>

class Person {
    std::string *namePtr;

public:
    Person() { namePtr = new std::string; }
    void setName(std::string s) { *namePtr = s; }
    std::string getName() const { return *namePtr; }
};

int main()
{
    Person president;
    Person chairman;

    president.setName("Tom");
    chairman = president;
    president.setName("Janet");

    std::cout << president.getName() << '\n';
    std::cout << chairman.getName() << '\n';

    return 0;
}

/*
Janet
Janet
*/
```
```c++
/*
What's the result ?
*/

#include <iostream>

class Vehicle {
public:
    Vehicle() { std::cout << "Vehicle" << '\n'; }
    ~Vehicle() { std::cout << "~Vehicle" << '\n'; }
};

class Engine {
public:
    Engine() { std::cout << "Engine" << '\n'; }
    ~Engine() { std::cout << "~Engine" << '\n'; }
};

class Truck : public Vehicle {
private:
    Engine theEngine;
public:
    Truck() { std::cout << "Truck" << '\n'; }
    ~Truck() { std::cout << "~Truck" << '\n'; }
};


int main()
{
    Truck theTruck;

    return 0;
}

/*
Vehicle
Engine
Truck
~Truck
~Engine
~Vehicle
*/
```

##### virtual destructor

```c++
/*
What's wrong, and how to fix?

~P2 would not be executed, which would cause memory leak.
To fix it, define ~P1() as virtual ~P1().
*/

class P1
{
public:
    P1 () { p = new char [10]; }
    ~P1 () { delete [] p; }
private:
    char * p;
};
class P2 : public P1
{
public:
    P2 () { q = new char [20]; }
    ~P2 () { delete [] q; }
private:
    char * q;
};

int main(int argc, char* argv[])
{
    P1 * pp = new P2;
    ...
    delete pp;
    return 0;
}
```
```c++
#include <iostream>
#include <memory>

class Base
{
public:
    virtual void print() = 0;
    // virtual ~Base() = default; // to fix it, uncomment this and get "~Derived() : 1"
};

class Derived : public Base
{
public:
    Derived(int value) 
    {
        m_data = new int;
        *m_data = value;
        std::cout << "Derived(" << value << ")" << '\n';
    }

    ~Derived() 
    { 
        std::cout << "~Derived() : " << *m_data << '\n'; 
    }

    void print() override
    {
        std::cout << "print() : " << *m_data << '\n';
    }

private:
    int* m_data = nullptr;
};

int main()
{
    {
        Base* p = new Derived(1); // Derived(1)
        p->print(); // print() : 1
        delete p;
    }

    {
        std::shared_ptr<Base> p_s = std::make_shared<Derived>(2); // Derived(2)
        p_s->print();   // print() : 2
    }   // ~Derived() : 2

    return 0;
}
```

#### virtual

```c++
/*
which class methods will additionally be made virtual in the base class Polygon ?

* The methods Area() and Perimeter() should be made virtual in the base class Polygon.
* The reason for this is that these methods will likely have different implementations 
for different derived classes of Polygon, such as Triangle, Rectangle, and Circle.
* When a virtual method is called through a base class pointer or reference, 
the program will determine at runtime which version of the method to call, 
based on the actual type of the object pointed to or referred to.
* Making these methods virtual in the base class allows for polymorphism, 
where a pointer or reference to a Polygon object can be used to call the correct version 
of Area() or Perimeter() for the actual type of the object.
*/

class Polygon {

protected:
    std::string name;
    int num_sides;

public:
    Polygon(const std::string& shapeName, const int sides)
        : name(shapeName), num_sides(sides) {}
    virtual ~Polygon();

    const std::string& DisplayName() { return name; }
    int NumSides() { return num_sides; }
    double Area() { return 0; }
    double Perimeter() { return 0; }
};
```

#### MISC

```c++
/*
What's wrong, and how to fix ?

To fix it, change to class C : public Point {}
*/
#include <iostream>

struct Point {
    int x;
    int y;
    int z;
};

class C : Point {
};

int main()
{
    C c;            
    c.x = 5; c.y = 3; c.z = 1;  // error: 'int Point::x' is inaccessible within this context

    return 0;
}
```
```c++
/*
What should replace *** to allow the constructor to execute correctly ?

MyClass / MyClass&
*/

#include <iostream>

class MyClass{
public:
    int* my_ptr;

    MyClass(int i) : my_ptr(new int)
    {
        *my_ptr = i;
    }

    ~MyClass() 
    {
        std::cout << __func__ << ':' << (my_ptr ? *my_ptr : -1) << '\n';
        
        if (my_ptr) {
            // double deletion
            // free(): double free detected in tcache 2
            // delete my_ptr;
            // my_ptr = nullptr;
        }  
    }

    void operator=(*** rhs)
    {
        delete my_ptr;
        my_ptr = rhs.my_ptr;
        rhs.my_ptr = nullptr;
    }

    int* get_my_ptr() const { return my_ptr; }
};

int main()
{
    MyClass my_class(1);
    std::cout << *my_class.get_my_ptr() << '\n';

    MyClass my_class_2(2);
    std::cout << *my_class_2.get_my_ptr() << '\n';

    my_class = my_class_2;

    std::cout << my_class.get_my_ptr() << '\n';
    if (my_class.get_my_ptr()) std::cout << *my_class.get_my_ptr() << '\n';
    std::cout << my_class_2.get_my_ptr() << '\n';
    if (my_class_2.get_my_ptr()) std::cout << *my_class_2.get_my_ptr() << '\n';

    return 0;
}

/*
void operator=(MyClass rhs)

1
2
~MyClass:-1
0x205fee0
2
0x205fee0
2
~MyClass:2
~MyClass:2
----------------------------
void operator=(MyClass& rhs)

1
2
0x12abee0
2
0
~MyClass:-1
~MyClass:2
*/
```
```c++
/*
What will be printed, and why?

In 32-bit environment, size of TestSize2 = 12.
12 = TestSize2 virtual table pointer(4) + TestSize2::b(4) + TestSize1::a(4)
*/

class TestSize1
{
public:
    TestSize1 () : a (0) {}
    virtual void F () = 0;
private:
    int a;
};
class TestSize2 : public TestSize1
{
public:
    TestSize2 () : b (1) {}
    virtual void F () { b = 3; }
private:
    int b;
};
int main(int argc, char* argv[])
{
    printf ("size of TestSize2 = %d", sizeof (TestSize2));
    return 0;
}
```
```c++
/*
What's wrong, and how to fix?

When multiple access, the Next function will make the current pointer behave unexpected. 
E.g. A is calling doSomething(), and B issues Next(). When A issues Next(), 
actually the current node is not current->next but current->next->next.
To fix it, add a parameter for Next() => Next(Thing *currentNode) 
so that it could make sure that the next node would not be changed by others.
*/

#include <iostream>
using namespace std;

class Thing {
public:
    void    doSomething() { cout << __func__ << endl; }
    Thing*    next;
};

class Things {
public:
    Things(Thing *myThing) : head(myThing), current(myThing) {}

    Thing*  First() {
        return head;
    }

    Thing*  Next() {
        current = current->next;
        return current;
    }

    bool OK() {
        if (current != nullptr)
            return true;
        else
            return false;
    }

private:
    Thing *head, *current;
};

int main()
{
    Thing*   myThing = new Thing;
    Things myThings(myThing);

    // This is how we do with class Things
    /*
        doSomething
        */
    for (Thing *ptr = myThings.First(); myThings.OK(); myThings.Next()) {
        ptr->doSomething();
    }

    return 0;
}
```
```c++
/*
What's the result ?
*/

#include <iostream>

class Store {
    unsigned int SqFootage;
    unsigned int value;

public:
    Store(unsigned int size, unsigned int cost) : SqFootage(size), value(cost) {}
    unsigned int GetSize() { return SqFootage; }
    unsigned int GetVal() { return value; }
};

class Restaurant : protected Store {
public:
    enum FoodType { fast, casual, sit_down };
    Restaurant(FoodType ft, unsigned int size, unsigned int cost) 
        : Store(size, cost), speed(ft) {}
    FoodType GetType() { return speed; }

private:
    FoodType speed;
};

int main()
{
    Restaurant wings(Restaurant::sit_down, 1500, 120000);

    // error: 'unsigned int Store::GetSize()' is inaccessible within this context
    // wings.GetSize();

    std::cout << wings.GetType() << '\n';   // 2

    // error: 'casual' was not declared in this scope
    // Restaurant thai(casual, 1000, 80000);

    // error: 'unsigned int Store::GetVal()' is inaccessible within this context
    // wings.GetVal();

    // error: 'Restaurant::FoodType Restaurant::speed' is private within this context
    // wings.speed = Restaurant::casual;

    return 0;
}
```

### STL

```c++
#include <iostream>
using namespace std;

int main()
{
    int a[] = {4, 5, 6};

    cout << *a << endl; // 4

    return 0;
}
```
```c++
#include <iostream>
#include <vector>
using namespace std;

int main()
{
    vector<int> v = {1, 2, 3};
    auto it = v.begin();
    cout << *it << endl;    // 1
    v.push_back(4);
    cout << *it << endl;    // undefined behavior

    return 0;
}
```
```c++
#include <iostream>
#include <set>
using namespace std;

int main()
{
    set<int> s;
    s.insert(3);
    s.insert(3);
    s.insert(2);

    // 2 3
    for (auto it = s.begin(); it != s.end(); ++ it) {
        cout << *it << endl;
    }

    return 0;
}
```
```c++
/*
Which code snippet could combine the first and last name in FirstLast into a single list of names in FullName ?
*/

#include <iostream>
#include <algorithm>
#include <map>
#include <vector>

int main()
{
    std::vector<std::string> FirstLast = {"John", "Jane", "Jim", "Sally",
                                            "Smith", "Doe", "Jones", "Adams"};
    std::vector<std::string> FullName(4);
    auto concat = [](const std::string& s1, const std::string& s2) {
        return s1 + " " + s2;
    };

    // error: no match for 'operator[]'
    // std::vector<std::string>::iterator it = FirstLast.begin();
    // while (*it != "Smith") {
    //     FullName[it] = concat(*it, *(it + 4));
    //     ++ it;
    // }

    // error: no matching function for call to
    // std::for_each(FirstLast.begin(), FirstLast.end(), FullName.begin(), concat);

    /*
    John Smith
    Jane Doe
    Jim Jones
    Sally Adams
    */
    std::vector<std::string>::iterator it = FirstLast.begin() + 4;
    std::transform(FirstLast.begin(), it, it, FullName.begin(), concat);

    /*




    Smith John
    Doe Jane
    Jones Jim
    Adams Sally
    */
    // for (std::vector<std::string>::iterator it = FirstLast.begin(); *it != "Smith"; ++ it) {
    //     FullName.push_back(concat(*(it + 4), *it));
    // }

    // error: no match for call to
    // std::vector<std::string>::iterator it = FirstLast.begin() + 4;
    // std::transform(FirstLast.begin(), it, FullName.begin(), concat);

    for (auto it : FullName) {
        std::cout << it << '\n';
    }

    return 0;
}
```

### Regular expressions

```c++
/*
What C++ regular expressions will correctly convert a number in the form 123-45-6789 to
 XXX-XX-6789 when substituted for *** in this function ?
*/

#include <iostream>
#include <regex>

std::string SSHide(const std::string& SSNum)
{
    std::regex rx("***");
    // std::regex rx("[[:digit:]]{3}-[[:digit:]]{2}");
    return regex_replace(SSNum, rx, "XXX-XX");
}

int main()
{
    auto s = SSHide("123-45-6789");
    std::cout << s << '\n';

    return 0;
}
```

### Concurrency

* Implement thread safety for SomeClass
```c++
#include <iostream>
#include <atomic>
#include <mutex>
#include <thread>
#include <vector>

// SomeClass
class SomeClass {
    static int instance_count;

public:
    SomeClass() { ++ instance_count; }
    int GetCount() const { return instance_count; }
};

int SomeClass::instance_count{0};

// SomeClass1
class SomeClass1 {
    static std::atomic<int> instance_count;

public:
    SomeClass1() { ++ instance_count; }
    int GetCount() const { return instance_count; }
};

std::atomic<int> SomeClass1::instance_count{0};

// SomeClass2
std::mutex mtx;

class SomeClass2 {
    static int instance_count;

public:
    SomeClass2() 
    {
        std::lock_guard<std::mutex> lock(mtx);
        ++ instance_count; 
    }
    int GetCount() const { return instance_count; }
};

int SomeClass2::instance_count{0};

// ??? SomeClass3
class SomeClass3 {
    static std::atomic<int> instance_count;

public:
    SomeClass3() { instance_count.fetch_add(1); }
    int GetCount() const { return instance_count; }
};

std::atomic<int> SomeClass3::instance_count{0};

auto n = 10;
std::vector<int> return_values(n * n);
 
void do_work(int thread_num)
{
    for (auto i = 0; i < n; ++ i) {
        SomeClass obj;    
        return_values[thread_num] = obj.GetCount();

        // SomeClass1 obj1;    
        // return_values[thread_num] = obj1.GetCount();

        // SomeClass2 obj2;    
        // return_values[thread_num] = obj2.GetCount();

        // SomeClass3 obj3;    
        // return_values[thread_num] = obj3.GetCount();
    }
}
 
int main()
{
    {
        std::vector<std::thread> threads;
        threads.reserve(n);

        for (auto i = 0; i < n; ++ i) {
            threads.emplace_back(std::thread(do_work, i));
            // std::jthread th0{do_work, i};
        }

        for (auto& th : threads) {
            th.join();
        }
    }
 
    // for (auto val : return_values) {
    //     std::cout << "Seen return value : " << val << std::endl;
    // }

    SomeClass obj;    
    std::cout << obj.GetCount() << '\n';

    SomeClass1 obj1;    
    std::cout << obj1.GetCount() << '\n';

    SomeClass2 obj2;    
    std::cout << obj2.GetCount() << '\n';

    SomeClass3 obj3;    
    std::cout << obj3.GetCount() << '\n';

    return 0;
}
```
```c++
/*
1. The code will not crash when locking mx1.
2. The lock_guard class is being used correctly in this code, as it provides a convenient 
RAII wrapper for managing the lifetime of a mutex lock.
3. The global mutex variables do not require the static keyword. 
    * The global mutex variables are accessible throughout the program and their lifetime 
    lasts for the entire duration of the program. Adding the static keyword would limit 
    their visibility to the translation unit where they are defined, but in this case they 
    are already globally visible without the static keyword.
4. The code may potentially deadlock in the right circumstances. 
    * Deadlocks can occur when two or more threads are waiting for each other to release 
    a resource, leading to a permanent blockage. In this case, if func1 and func2 are 
    executed concurrently, they may each try to lock mx1 and mx2 in different orders, 
    resulting in a deadlock. For example, if func1 locks mx1 and then tries to lock mx2 
    while func2 has already locked mx2 and is waiting to lock mx1, both functions will be 
    stuck waiting for the other to release its lock, leading to a deadlock. 
    * To prevent deadlocks, it's important to ensure that the locking order of mutexes is 
    always the same in all functions that use them.
5. It is legal to use two different mutexes within the same function.
*/

#include <mutex>

std::mutex mx1;
std::mutex mx2;

void func1()
{
    std::lock_guard<std::mutex> lg1(mx1);
    // do time-consuming work

    std::lock_guard<std::mutex> lg2(mx2);
    // do time-consuming work
}

void func2()
{
    std::lock_guard<std::mutex> lg1(mx2);
    // do time-consuming work

    std::lock_guard<std::mutex> lg2(mx1);
    // do time-consuming work
}
```
```c++
/* What are the possible outputs of the following program?
The possible outputs of the program are:
    Caught in main:Exception in ThreadA
    Caught in main:Exception in ThreadB
    terminate called after throwing an instance of ‘std::runtime_error’ what(): Exception in ThreadA Aborted (core dumped)
    terminate called after throwing an instance of ‘std::runtime_error’ what(): Exception in ThreadB Aborted (core dumped)
    
The explanation is:
    The program creates two threads, t1 and t2, that execute ThreadA and ThreadB functions respectively.
    Each thread tries to lock two mutexes, mutex1 and mutex2, but in reverse order. This creates a potential 
deadlock situation if both threads lock one mutex each and wait for the other one to release it.
    However, before locking both mutexes, each thread throws a runtime_error exception. This exception is not 
caught within the thread function, so it propagates to the main function where it is caught by a try-catch block.
    The catch block prints out the message “Caught in main:” followed by the exception’s what() method that 
returns a string with the error message.
    The output depends on which thread throws the exception first and whether it is caught by the main function 
or not. If one thread throws the exception before locking any mutex, then it will be caught by the main function 
and printed out. If both threads throw the exception after locking one mutex each, then they will deadlock and 
neither of them will be caught by the main function. In this case, the program will terminate abnormally with 
a message indicating that an uncaught exception was thrown
*/

#include <iostream>
#include <thread>
#include <mutex>
#include <unistd.h>
#include <exception>

std::mutex mutex1, mutex2;

void ThreadA()
{
    mutex2.lock();
    throw std::runtime_error("Exception in ThreadA");
    mutex1.lock();
    mutex2.unlock();
    mutex1.unlock();
}
void ThreadB()
{
    mutex1.lock();
    throw std::runtime_error("Exception in ThreadB");
    mutex2.lock();
    mutex1.unlock();
    mutex2.unlock();
}
int main()
{
  try {
    std::thread t1( ThreadA );
    std::thread t2( ThreadB );
    t1.join();
    t2.join();
  } catch (const std::exception& ex) {
    std::cout << "Caught in main:" << ex.what() << "\n";
  }
  return 0;
}
```
* `std::async` call
```c++
/*

* threaded_func is not guaranteed to start immediately in another thread
    * Even if you pass std::launch::async as a launch policy to std::async, it is not guaranteed
    that threaded_func will start immediately in another thread. The implementation is still free 
    to decide whether to run the function in the current thread or in a new thread, based on 
    various factors such as the number of available hardware threads, the workload of the system, 
    and other implementation-specific considerations. The std::async with std::launch::async 
    guarantees that the function will be run asynchronously, but does not guarantee that the 
    function will start immediately in another thread.
* If an exception is thrown in threaded_func, it will not be handled in main(). 
    * The exception will propagate through the thread, but it will not be caught in the main 
    function. To handle exceptions thrown in threaded_func, you can use a try-catch block in main() 
    and call the .get() method on the future object, which will wait for the function to complete 
    and will propagate any exception thrown by the function.
    * Alternatively, you can use a std::future<T>::wait() function which will wait for the function 
    to complete and will propagate any exception thrown by the function.
    * Note that the .get() and .wait() method may re-throw the exception that was thrown in the 
    threaded_func so you can use try-catch block around them as well.
* Adding a call to future_result.get() after the std::async call will not launch threaded_func in a 
separate thread. 
    * The std::async call is responsible for launching the function in a separate thread, and the 
    call to future_result.get() simply waits for the function to complete and retrieves the result. 
    The .get() method will block the main thread until the function execution is finished, 
    regardless of whether the function is run in a separate thread or not.
    * It's worth noting that, there is no launch policy passed to std::async, so the behavior of 
    the function execution is not guaranteed to run async. So, adding .get() method will wait for 
    the completion of the task only.
* It is possible that threaded_func may be started synchronously at a future time, if the 
implementation chooses to do so. The std::async call is responsible for launching the function, but 
no launch policy is passed to it, so the implementation is free to decide whether to run the 
function synchronously or asynchronously.
    * The while loop will continue to execute until the future_result is valid. This means that the 
    main thread will be blocked until the future_result is ready. When the future_result is ready, 
    it means that the threaded_func has completed and the main thread will exit the loop and print 
    "Done!". Depending on the implementation, this could mean that the function was run 
    synchronously, in which case the main thread would be blocked until the function completed.
    * It's worth noting that, there is no launch policy passed to std::async, so the behavior of 
    the function execution is not guaranteed to run async or sync.

*/

#include <iostream>
#include <future>

void threaded_func() {}

int main()
{
    auto future_result = std::async(threaded_func);

    while (1) {
        if (future_result.valid()) {
            std::cout << "Done!" << '\n';   // Done!
            break;
        }
    }

    return 0;
}
```

### Template

```c++
/*
Which call will successfully compile ?
*/

#include <iostream>

template<class N> auto TriangleArea(N base, N height) {
    static_assert(std::is_arithmetic<N>::value && sizeof(N) > 1,
                    "Cannot compute with non-numeric type!");
    return static_cast<double>(0.5) * base * height;
}

int main()
{
    // error: no matching function for call to 'TriangleArea(float, double)'
    // TriangleArea(static_cast<float>(5.93), static_cast<double>(3.33));

    // error: static assertion failed: Cannot compute with non-numeric type!
    // TriangleArea(static_cast<char>(10), static_cast<char>(5));

    // error: static assertion failed: Cannot compute with non-numeric type!
    // TriangleArea('a', 'c');

    // error: no matching function for call to 'TriangleArea(int, double)'
    // TriangleArea(10, 3.1415);

    TriangleArea(10.0, 3.1415);

    return 0;
}
```
```c++
/*
It will not result in an infinite loop. The function findTotal uses recursion to add the arguments passed 
to it together, with the base case being when there is only one argument left. 

The template function findTotal(T head, P ...tail) can take any number of parameters
*/

#include <iostream>

template <typename T>
T findTotal(T lastOne)
{
    std::cout << __func__ << "(T lastOne): " << lastOne << '\n';
    return (lastOne);
}

template <typename T, typename ...P>
T findTotal(T head, P ...tail)
{
    std::cout << __func__ << "(T head, P ...tail): " << head << '\n';
    if (sizeof...(tail))
        head += findTotal(tail...);

    return (head);        
}

int main()
{
    double total = findTotal(2.1, 3.0, 4.15, 3.14, 0, 9.9);
    
    total = findTotal(-1.1);

    return 0;
}

/*
findTotal(T head, P ...tail): 2.1
findTotal(T head, P ...tail): 3
findTotal(T head, P ...tail): 4.15
findTotal(T head, P ...tail): 3.14
findTotal(T head, P ...tail): 0
findTotal(T lastOne): 9.9
findTotal(T lastOne): -1.1
*/
```
```c++
/*
Implement a C++ function to support multiplying a variable number of arguments 
for a generic calculator application.
*/

#include <iostream>
#include <vector>

// 1
template <typename T>
double multiply(T val)
{
    return val;
}

template <typename T, typename... O>
double multiply(T val, O... other)
{
    return val * multiply(other...);
}

// 2
template <typename T>
double multiply_(std::vector<T> vec)
{
    double product = 1.0;
    for (T elem : vec) {
        product *= elem;
    }

    return product;
}

int main()
{
    auto result = multiply(1, 2, 3, 4, 5);
    std::cout << result << '\n';

    auto result_ = multiply_(std::vector<int>{1, 2, 3, 4, 5});
    std::cout << result_ << '\n';

    return 0;
}
```
```c++
/*
Implement template to get minimum and/or maximum of numbers
*/

#include <cstdint>
#include <cstdlib>
#include <ctime>
#include <utility>
#include <vector>

enum class minmax_t : uint8_t{ MIN, MAX};

// Get the minimum or maximum of the vectors based on the template parameter
template <minmax_t M, typename T>
constexpr T get(const std::vector<T>& v1, const std::vector<T>& v2, const std::vector<T>& v3);

// Get both the minimum and the maximum of the vectors
template <typename T> constexpr std::pair<T, T> get(
        const std::vector<T>& v1, const std::vector<T>& v2, const std::vector<T>& v3);

#include <algorithm>
#include <iostream>
#include <sstream>
#include <string>

// Implement your templates here

// Get the minimum or maximum of the vectors based on the template parameter
template <minmax_t M, typename T>
constexpr T get(const std::vector<T>& v1, const std::vector<T>& v2, const std::vector<T>& v3)
{
    if constexpr (M == minmax_t::MIN) {
        return std::min({*std::min_element(v1.begin(), v1.end()), 
                            *std::min_element(v2.begin(), v2.end()),
                            *std::min_element(v3.begin(), v3.end())});
    }
    else {
        return std::max({*std::max_element(v1.begin(), v1.end()), 
                            *std::max_element(v2.begin(), v2.end()),
                            *std::max_element(v3.begin(), v3.end())});
    }
}

// Get both the minimum and the maximum of the vectors
template <typename T> constexpr std::pair<T, T> get(
        const std::vector<T>& v1, const std::vector<T>& v2, const std::vector<T>& v3)
{
    return std::make_pair(get<minmax_t::MIN, T>(v1, v2, v3),
                            get<minmax_t::MAX, T>(v1, v2, v3));
}

// Write your driver function
template<typename T>
void test_types()
{
    std::vector<std::vector<T> >    v(3);
    // for (auto i = 0; i < 3; ++ i) {
    //     std::string s{};
    //     std::getline(std::cin, s);
    //     std::stringstream ss{s};
    //     T value{};
    //     while (ss >> value) {
    //         v.at(i).emplace_back(value);
    //     }            
    // }

    std::srand(std::time(0));
    for (auto i = 0; i < 3; ++ i) {
        auto n = std::rand() % 10;
        for (auto j = 0; j < n; ++ j) {
            auto value = std::rand() % 100;
            std::cout << value << ' ';
            v.at(i).emplace_back(value);
        }        
        std::cout << '\n';
    }
    
    auto min_result = get<minmax_t::MIN, T>(v.at(0), v.at(1), v.at(2));    
    auto max_result = get<minmax_t::MAX, T>(v.at(0), v.at(1), v.at(2));    
    std::cout << min_result << " " << max_result << '\n';
    
    auto [min_pair_result, max_pair_result] = get<T>(v.at(0), v.at(1), v.at(2));
    std::cout << min_pair_result << " " << max_pair_result << '\n';    
}

int main() {
    // unit test of type int
    test_types<int>();
    
    // unit test of type double
    // test_types<double>();
    
    return 0;
}
```

### MISC

```c++
/*
Which of the following potential improvements that can be made to the C++ code below ? 
1. Use char buffers instead of std::string.
    * This can be a potential improvement if the size of the string objects can be determined beforehand and the 
memory usage is a concern. 
    * However, it would make the code more complicated and less readable.
2. Use a container class like std::vector instead of manually creating arrays.
    * This would be a good improvement as vectors handle memory allocation and deallocation for you, 
making the code cleaner and less error-prone.
3. Use a C++ standard library pointer like std::unique_ptr instead of a raw pointer.
    * This would be a good improvement as smart pointers handle memory management for you and provide automatic 
memory deallocation.
4. Explicitly declare the arrays using their actual types(double *, std::string*) instead of using auto.
    * This can make the code more readable and explicit, but is not necessary.
5. Use malloc() instead of new[] for performance improvement
    * malloc() is faster than new[] in some cases, but new[] provides better type-safety and exception handling. 
    * Whether to use malloc() or new[] depends on the specific requirements and trade-offs of your code.

* Memory leak: The allocated memory is never freed, causing a potential memory leak.
* Unnecessarily large arrays: The arrays might be larger than necessary, consider using a smaller size.
* Exception handling: No exception handling is in place, which could result in a crash.
* Use of raw pointers: Raw pointers can be error-prone and should be replaced with smart pointers such as unique_ptr 
or shared_ptr.
* Names of variables: The names of the variables could be more descriptive to make the code easier to read and 
understand.
*/

int main()
{
    auto darr = new double[20];
    auto strarr = new std::string[20];
}
```
```c++
/*
What's the result ?

1. The definition of function func5() claims to never throw an exception because the 
definition of function func3() claims to never throw an exception.
    * ??? False. The definition of function func5() claims to never throw an exception 
    because the expression noexcept(func3()) returns false, indicating that the function 
    func3() may throw an exception. However, the definition of func3() contains a throw 
    expression, which means that it actually throws an exception, despite being declared 
    with the noexcept specifier.
2. The definition of function func3() causes a compile error because the function throws 
an exception, while its definition claims that it never does.
    * The definition of function func3() contains a throw expression, which means that it 
    throws an exception, while its definition claims that it never throws an exception 
    with the noexcept specifier. This causes a compile error because the function 
    definition contradicts the noexcept specification.
3. The expression noexcept(func3()) does not evaluate function func3() to see if it 
throws an exception. It returns true if the definition of function func3() claims (via 
noexcept) that it never throws an exception.
    * ??? The expression noexcept(func3()) returns false, indicating that the 
    function func3() may throw an exception, based on its definition. This expression does 
    not actually evaluate the function, it only examines its definition.
4. Declaring a function to be noexcept is NOT primarily for documentation purpose.
    * Declaring a function to be noexcept has practical implications for exception safety 
    and performance. The noexcept specifier allows the compiler to make certain 
    optimizations, such as avoiding the need to generate code for stack unwinding in the 
    case of an exception. It also communicates to the caller that the function does not 
    throw exceptions, allowing the caller to make decisions based on this information.
5. A program that calls func3() should handle the exception.
    * The function func3() throws an exception, as indicated by its definition, so a    
    program that calls func3() should be prepared to handle the exception. If a program 
    does not handle the exception, it will propagate up the call stack until it is caught 
    by a suitable handler or results in a call to std::terminate().
*/

#include <iostream>

void func2() noexcept {}
void func3() noexcept { throw 1; }  // warning: 'throw' will always call 'terminate'
void func5() noexcept(noexcept(func3())) {}

int main()
{
    std::cout << std::boolalpha << noexcept(func2()) << '\n';   // true
    std::cout << std::boolalpha << noexcept(func3()) << '\n';   // true
    std::cout << std::boolalpha << noexcept(func5()) << '\n';   // true
    std::cout << std::boolalpha << noexcept(noexcept(func3())) << '\n';   // true

    // func3();    // terminate called after throwing an instance of 'int'

    return 0;
}
```

# END
