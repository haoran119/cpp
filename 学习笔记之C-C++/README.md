# 学习笔记之C / C++

* [cppreference.com](https://en.cppreference.com/w/)
* [C++ Language Reference | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/cpp-language-reference?view=msvc-160)
    * [Welcome back to C++ - Modern C++ | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/welcome-back-to-cpp-modern-cpp?view=msvc-160)
* [cplusplus.com - The C++ Resources Network](http://www.cplusplus.com/)
* [Learn C++ – Skill up with our free tutorials](https://www.learncpp.com/)
* [C++ Tutorial](https://www.tutorialspoint.com/cplusplus/index.htm)
  * [The C++ Standard Library Tutorial](https://www.tutorialspoint.com/cpp_standard_library/index.htm)
* [C++ Programming Language - GeeksforGeeks](https://www.geeksforgeeks.org/c-plus-plus/?ref=shm)
* [Fluent C++ - Jonathan Boccara's blog](https://www.fluentcpp.com/)
* [Modernes C++](https://www.modernescpp.com/index.php)
* [Standard C++](https://isocpp.org/)
    * 标准委员会官方站点，近期的会议、行程、活动、计划。
* [Open Standards](https://www.open-std.org/)
    * 官方开放文档，各种论文文献。
* [Bjarne Stroustrup's Homepage](https://www.stroustrup.com/index.html)
    * C++之父的主页
* [C++ Team Blog](https://devblogs.microsoft.com/cppblog/)
    * 微软C++团队的博客
* [fffaraz/awesome-cpp: A curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things.](https://github.com/fffaraz/awesome-cpp)
* [Clean Code - Uncle Bob / Lesson 1 - YouTube](https://www.youtube.com/watch?v=7EmboKQH8lM)
* [Cᐩᐩ Weekly With Jason Turner - YouTube](https://www.youtube.com/channel/UCxHAlbZQNFU2LgEtiqd2Maw)

#

* [Compiler Explorer](https://godbolt.org/)
* [Coliru - Compile, link and run](http://coliru.stacked-crooked.com/)
* [C++ Insights](https://cppinsights.io/)
* [Quick C++ Benchmarks](https://quick-bench.com/q/c_YexN92u816kGfoAjBp6L4okII)
* [C++ Build Benchmarks](https://build-bench.com/b/sOF8ezVagBs7xNlWevoBvyOYXwk)

#

* [c-cpp/面试总结之C-C++ at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E9%9D%A2%E8%AF%95%E6%80%BB%E7%BB%93%E4%B9%8BC-C%2B%2B)
* [c-cpp/学习笔记之C++入门到精通 at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BC%2B%2B%E5%85%A5%E9%97%A8%E5%88%B0%E7%B2%BE%E9%80%9A)
* [c-cpp/学习笔记之Windows Programming at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BWindows%20Programming)
* [学习笔记之C++ How to Program(part) - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/archive/2010/10/26/1860906.html)
* [学习笔记之C++ Primer中文版（第五版） - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/7071876.html)
* [学习笔记之高质量C++/C编程指南 - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/5577934.html)
* [学习笔记之Linux开发(C语言) - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/5122821.html)
* [学习笔记之C/C++指针使用常见的坑 - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/8464520.html)
* [学习笔记之C++入门到精通（名师教学·手把手教会）【职坐标】_腾讯课堂 - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/p/7904482.html)

## Resources

### C++ Core Guidelines

* [PPP Style Guide](https://www.stroustrup.com/Programming/PPP-style.pdf)
* [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)
  * This document is a set of guidelines for using C++ well. The aim of this document is to help people to use modern C++ effectively. By “modern C++” we mean effective use of the ISO C++ standard (currently C++17, but almost all of our recommendations also apply to C++14 and C++11).
  * [In: Introduction](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-introduction)
  * [P: Philosophy](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-philosophy)
    * P.1: Express ideas directly in code
    * P.2: Write in ISO Standard C++
    * P.3: Express intent
    * P.4: Ideally, a program should be statically type safe
    * P.5: Prefer compile-time checking to run-time checking
    * P.6: What cannot be checked at compile time should be checkable at run time
    * P.7: Catch run-time errors early
    * P.8: Don’t leak any resources
    * P.9: Don’t waste time or space
    * P.10: Prefer immutable data to mutable data
    * P.11: Encapsulate messy constructs, rather than spreading through the code
    * P.12: Use supporting tools as appropriate
    * P.13: Use support libraries as appropriate
  * [I: Interfaces](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-interfaces)
    * I.1: Make interfaces explicit
    * I.2: Avoid non-const global variables
    * I.3: Avoid singletons
    * I.4: Make interfaces precisely and strongly typed
    * I.5: State preconditions (if any)
    * I.6: Prefer Expects() for expressing preconditions
    * I.7: State postconditions
    * I.8: Prefer Ensures() for expressing postconditions
    * I.9: If an interface is a template, document its parameters using concepts
    * I.10: Use exceptions to signal a failure to perform a required task
    * I.11: Never transfer ownership by a raw pointer (T*) or reference (T&)
    * I.12: Declare a pointer that must not be null as not_null
    * I.13: Do not pass an array as a single pointer
    * I.22: Avoid complex initialization of global objects
    * I.23: Keep the number of function arguments low
    * I.24: Avoid adjacent parameters that can be invoked by the same arguments in either order with different meaning
    * I.25: Prefer empty abstract classes as interfaces to class hierarchies
    * I.26: If you want a cross-compiler ABI, use a C-style subset
    * I.27: For stable library ABI, consider the Pimpl idiom
    * I.30: Encapsulate rule violations
  * [F: Functions](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-functions)
  * [C: Classes and class hierarchies](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-class)
  * [Enum: Enumerations](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-enum)
  * [R: Resource management](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-resource)
  * [ES: Expressions and statements](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-expr)
  * [Per: Performance](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-performance)
  	* Per.1: Don’t optimize without reason
  	* Per.2: Don’t optimize prematurely
  	* Per.3: Don’t optimize something that’s not performance critical
  	* Per.4: Don’t assume that complicated code is necessarily faster than simple code
  	* Per.5: Don’t assume that low-level code is necessarily faster than high-level code
  	* Per.6: Don’t make claims about performance without measurements
  	* Per.7: Design to enable optimization
  	* Per.10: Rely on the static type system
  	* Per.11: Move computation from run time to compile time
  	* Per.12: Eliminate redundant aliases
  	* Per.13: Eliminate redundant indirections
  	* Per.14: Minimize the number of allocations and deallocations
  	* Per.15: Do not allocate on a critical branch
  	* Per.16: Use compact data structures
  	* Per.17: Declare the most used member of a time-critical struct first
  	* Per.18: Space is time
  	* Per.19: Access memory predictably
  	* Per.30: Avoid context switches on the critical path
  * [CP: Concurrency and parallelism](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-concurrency)
  	* CP.1: Assume that your code will run as part of a multi-threaded program
  	* CP.2: Avoid data races
  	* CP.3: Minimize explicit sharing of writable data
  	* CP.4: Think in terms of tasks, rather than threads
  	* CP.8: Don’t try to use volatile for synchronization
  	* CP.9: Whenever feasible use tools to validate your concurrent code
  	* See also:
  	* CP.con: Concurrency
  		* CP.20: Use RAII, never plain lock()/unlock()
  		* CP.21: Use std::lock() or std::scoped_lock to acquire multiple mutexes
  		* CP.22: Never call unknown code while holding a lock (e.g., a callback)
  		* CP.23: Think of a joining thread as a scoped container
  		* CP.24: Think of a thread as a global container
  		* CP.25: Prefer gsl::joining_thread over std::thread
  		* CP.26: Don’t detach() a thread
  		* CP.31: Pass small amounts of data between threads by value, rather than by reference or pointer
  		* CP.32: To share ownership between unrelated threads use shared_ptr
  		* CP.40: Minimize context switching
  		* CP.41: Minimize thread creation and destruction
  		* CP.42: Don’t wait without a condition
  		* CP.43: Minimize time spent in a critical section
  		* CP.44: Remember to name your lock_guards and unique_locks
  		* CP.50: Define a mutex together with the data it guards. Use synchronized_value\<T> where possible
  	* CP.coro: Coroutines
  	* CP.par: Parallelism
  	* CP.mess: Message passing
  	* CP.vec: Vectorization
  	* CP.free: Lock-free programming
  	* CP.etc: Etc. concurrency rules
  * [E: Error handling](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-errors)
  * [Con: Constants and immutability](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-const)
  * [T: Templates and generic programming](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-templates)
  * [CPL: C-style programming](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-cpl)
  * [SF: Source files](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-source)
  * [SL: The Standard Library](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-stdlib)
	* Supporting sections:
		* A: Architectural ideas
		* NR: Non-Rules and myths
		* RF: References
		* Pro: Profiles
		* GSL: Guidelines support library
		* NL: Naming and layout rules
		* FAQ: Answers to frequently asked questions
		* Appendix A: Libraries
		* Appendix B: Modernizing code
		* Appendix C: Discussion
		* Appendix D: Supporting tools
		* Glossary
		* To-do: Unclassified proto-rules
	* You can sample rules for specific language features:
		* assignment: regular types – prefer initialization – copy – move – other operations – default
		* class: data – invariant – members – helpers – concrete types – ctors, =, and dtors – hierarchy – operators
		* concept: rules – in generic programming – template arguments – semantics
		* constructor: invariant – establish invariant – throw – default – not needed – explicit – delegating – virtual
		* derived class: when to use – as interface – destructors – copy – getters and setters – multiple inheritance – overloading – slicing – dynamic_cast
		* destructor: and constructors – when needed? – must not fail
		* exception: errors – throw – for errors only – noexcept – minimize try – what if no exceptions?
		* for: range-for and for – for and while – for-initializer – empty body – loop variable – loop variable type ???
		* function: naming – single operation – no throw – arguments – argument passing – multiple return values – pointers – lambdas
		* inline: small functions – in headers
		* initialization: always – prefer {} – lambdas – in-class initializers – class members – factory functions
		* lambda expression: when to use
		* operator: conventional – avoid conversion operators – and lambdas
		* public, private, and protected: information hiding – consistency – protected
		* static_assert: compile-time checking – and concepts
		* struct: for organizing data – use if no invariant – no private members
		* template: abstraction – containers – concepts
		* unsigned: and signed – bit manipulation
		* virtual: interfaces – not virtual – destructor – never fail

### [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

### Effective C++

* [学习笔记之Effective C++ 2nd Edition - 浩然119 - 博客园 (cnblogs.com)](https://www.cnblogs.com/pegasus923/archive/2011/04/24/1930631.html)
* [Effective C++学习笔记](https://mp.weixin.qq.com/s/Sn-AeA41-ZjLzCMtmNnx_A)

### More Effective C++

* [35 个 More Effective C++ 改善编程与设计的最佳方法 | 原力计划](https://mp.weixin.qq.com/s/PQbkpjUScbYIywo4tsIdqw)

### [C++ Best Practices](https://lefticus.gitbooks.io/cpp-best-practices/content/)

* [cpp-best-practices/cppbestpractices: Collaborative Collection of C++ Best Practices. This online resource is part of Jason Turner's collection of C++ Best Practices resources. See README.md for more information.](https://github.com/cpp-best-practices/cppbestpractices)
* [C++最佳实践 | 1. 工具](https://mp.weixin.qq.com/s/_ZC1t0wMu8fjTq-1HgKrrA)
* [C++最佳实践 | 2. 代码风格](https://mp.weixin.qq.com/s/aFY3cBIsucd5J0034pzRAg)
* [C++最佳实践 | 3. 安全性](https://mp.weixin.qq.com/s/rR8rWYHZ9GFkCvxJe8bb7Q)
* [C++最佳实践 | 4. 可维护性](https://mp.weixin.qq.com/s/vs3ZbAhgKhV-VSCYUC8W3w)
* [C++最佳实践 | 5. 可移植性及多线程](https://mp.weixin.qq.com/s/Y5O9__wNp5FjsIuMJ66gZQ)
* [C++最佳实践 | 6. 性能](https://mp.weixin.qq.com/s/5SnQhjrzJ2ZLoNmyPznoZg)
	* 性能
		* 尽量使用前置声明
		* 避免不必要的模板实例化
		* 避免递归模板实例化
		* 分析构建
		* 隔离频繁更改的头文件
			* 不要包含不需要的头文件
			* 减少预处理器的工作
		* 考虑使用预编译头文件
		* 考虑使用工具
		* 将tmp放在Ramdisk上
		* 使用gold链接器
	* 运行时
		* 分析代码
		* 简化代码
		* 使用初始化列表
		* 减少临时对象
		* 启用移动(move)操作
		* 避免shared_ptr拷贝
		* 尽可能减少拷贝和重分配
		* 避免多余的异常
		* 抛弃new
		* 优先选择unique_ptr而不是shared_ptr
		* 抛弃std::endl
		* 限制变量作用域
		* 优先选择double类型而不是float类型，但需要先测试
		* 优先选择++i而不是i++
		* char是char, string是string
		* 永远不要用std::bind
		* 了解标准库
		* in_place_t及相关内容

## [C reference](https://en.cppreference.com/w/c)

* [在C语言中如何高效地复制和连接字符串？](https://mp.weixin.qq.com/s/qhbIb_Th1RyOyYBDfef1BQ)
    * https://developers.redhat.com/blog/2019/08/12/efficient-string-copying-and-concatenation-in-c/
* [const 并不能加快 C 代码的运行速度？](https://mp.weixin.qq.com/s/coeuXmY81c4WH_cJ3nsxCg)
    * https://theartofmachinery.com/2019/08/12/c_const_isnt_for_performance.html
* [C 语言结构体成员赋值的深拷贝和浅拷贝 (qq.com)](https://mp.weixin.qq.com/s/ItjirJ4SrMX2H22ig_laaQ)
* [C 语言未初始化的局部变量是多少？ (qq.com)](https://mp.weixin.qq.com/s/_JljAFBK_1UlnPgIGkKsjg)
* [C 语言发展史的点点滴滴 (qq.com)](https://mp.weixin.qq.com/s/NInTU_CagWlCEfhWhgYeOA)
* [这几道 C/C++ 题涉及你的知识盲区？](https://mp.weixin.qq.com/s/0lWx9M8J5Xa2Mo9jLRdG-g)
    * 8个C语言面试题，涉及指针、运算、函数、内存，看看你能做出几个
* [C语言中的“三字母词”坑了工程师](https://mp.weixin.qq.com/s/dsV2rYG6cEJI7IlLNSwwcg)
    * https://blog.csdn.net/daheiantian/article/details/6095507
    * "??/"会被编译器当作 /，变成C语言的换行符（多行代码连接符）。于是这段代码等同于// 注释语句 a = b+c ;就会被注释掉。

## C++ Compiler

* [C++17 - Wikipedia](https://en.wikipedia.org/wiki/C%2B%2B17)
	* Compiler support
		* GCC has had complete support for C++17 language features since version 8.[48]
		* Clang 5 and later supports all C++17 language features.[49]
		* Visual Studio 2017 15.8 (MSVC 19.15) and later supports all C++17 language features.[50][51]

### [GCC](https://gcc.gnu.org/)

* GCC, the GNU Compiler Collection - GNU Project
* [[ZZ]C++编译器—gcc的用法 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2010/10/08/1845888.html)
* [C++ Standards Support in GCC - GNU Project](https://gcc.gnu.org/projects/cxx-status.html#cxx17)
	* C++17 Support in GCC
		* GCC has almost full support for the previous revision of the C++ standard, which was published in 2017. Some library features are missing or incomplete, as described in the library documentation.
		* C++17 features are available since GCC 5. This mode is the default in GCC 11; it can be explicitly selected with the -std=c++17 command-line flag, or -std=gnu++17 to enable GNU extensions as well.
* [gcc(1): GNU project C/C++ compiler - Linux man page](https://linux.die.net/man/1/gcc)
* [Top (Using the GNU Compiler Collection (GCC))](https://gcc.gnu.org/onlinedocs/gcc/index.html#SEC_Contents)
	* [3.3 Compiling C++ Programs](https://gcc.gnu.org/onlinedocs/gcc/Invoking-G_002b_002b.html#Invoking-G_002b_002b)
		* C++ source files conventionally use one of the suffixes ‘.C’, ‘.cc’, ‘.cpp’, ‘.CPP’, ‘.c++’, ‘.cp’, or ‘.cxx’; C++ header files often use ‘.hh’, ‘.hpp’, ‘.H’, or (for shared template code) ‘.tcc’; and preprocessed C++ files use the suffix ‘.ii’. GCC recognizes files with these names and compiles them as C++ programs even if you call the compiler the same way as for compiling C programs (usually with the name gcc).
		* However, the use of gcc does not add the C++ library. g++ is a program that calls GCC and automatically specifies linking against the C++ library. It treats ‘.c’, ‘.h’ and ‘.i’ files as C++ source files instead of C source files unless -x is used. This program is also useful when precompiling a C header file with a ‘.h’ extension for use in C++ compilations. On many systems, g++ is also installed with the name c++.
		* When you compile C++ programs, you may specify many of the same command-line options that you use for compiling programs in any language; or command-line options meaningful for C and related languages; or options that are meaningful only for C++ programs. See Options Controlling C Dialect, for explanations of options for languages related to C. See [Options Controlling C++ Dialect](https://gcc.gnu.org/onlinedocs/gcc/C_002b_002b-Dialect-Options.html#C_002b_002b-Dialect-Options), for explanations of options that are meaningful only for C++ programs.
	* [3.5 Options Controlling C++ Dialect](https://gcc.gnu.org/onlinedocs/gcc/C_002b_002b-Dialect-Options.html#C_002b_002b-Dialect-Options)
	* [3.8 Options to Request or Suppress Warnings](https://gcc.gnu.org/onlinedocs/gcc/Warning-Options.html#Warning-Options)
		* -Wpedantic
		* -pedantic
			* Issue all the warnings demanded by strict ISO C and ISO C++; reject all programs that use forbidden extensions, and some other programs that do not follow ISO C and ISO C++. For ISO C, follows the version of the ISO C standard specified by any -std option used.
			* Valid ISO C and ISO C++ programs should compile properly with or without this option (though a rare few require -ansi or a -std option specifying the required version of ISO C). However, without this option, certain GNU extensions and traditional C and C++ features are supported as well. With this option, they are rejected.
			* -Wpedantic does not cause warning messages for use of the alternate keywords whose names begin and end with ‘__’. This alternate format can also be used to disable warnings for non-ISO ‘__intN’ types, i.e. ‘__intN__’. Pedantic warnings are also disabled in the expression that follows __extension__. However, only system header files should use these escape routes; application programs should avoid them. See Alternate Keywords.
			* Some users try to use -Wpedantic to check programs for strict ISO C conformance. They soon find that it does not do quite what they want: it finds some non-ISO practices, but not all—only those for which ISO C requires a diagnostic, and some others for which diagnostics have been added.
			* A feature to report any failure to conform to ISO C might be useful in some instances, but would require considerable additional work and would be quite different from -Wpedantic. We don’t have plans to support such a feature in the near future.
			* Where the standard specified with -std represents a GNU extended dialect of C, such as ‘gnu90’ or ‘gnu99’, there is a corresponding base standard, the version of ISO C on which the GNU extended dialect is based. Warnings from -Wpedantic are given where they are required by the base standard. (It does not make sense for such warnings to be given only for features not in the specified GNU C dialect, since by definition the GNU dialects of C include all features the compiler supports with the given option, and there would be nothing to warn about.)
		* -Wall
			* This enables all the warnings about constructions that some users consider questionable, and that are easy to avoid (or modify to prevent the warning), even in conjunction with macros. This also enables some language-specific warnings described in C++ Dialect Options and Objective-C and Objective-C++ Dialect Options.
		* -Wunused-variable
			* Warn whenever a local or static variable is unused aside from its declaration. This option implies -Wunused-const-variable=1 for C, but not for C++. This warning is enabled by -Wall.
			* To suppress this warning use the unused attribute (see Variable Attributes).
	* [3.11 Options That Control Optimization](https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html)
		* These options control various sorts of optimizations.
		* Without any optimization option, the compiler’s goal is to reduce the cost of compilation and to make debugging produce the expected results. Statements are independent: if you stop the program with a breakpoint between statements, you can then assign a new value to any variable or change the program counter to any other statement in the function and get exactly the results you expect from the source code.
		* Turning on optimization flags makes the compiler attempt to improve the performance and/or code size at the expense of compilation time and possibly the ability to debug the program.
		* The compiler performs optimization based on the knowledge it has of the program. Compiling multiple files at once to a single output file mode allows the compiler to use information gained from all of the files when compiling each of them.
		* Not all optimizations are controlled directly by a flag. Only optimizations that have a flag are listed in this section.
		* Most optimizations are completely disabled at -O0 or if an -O level is not set on the command line, even if individual optimization flags are specified. Similarly, -Og suppresses many optimization passes.
		* Depending on the target and how GCC was configured, a slightly different set of optimizations may be enabled at each -O level than those listed here. You can invoke GCC with -Q --help=optimizers to find out the exact set of optimizations that are enabled at each level. See Overall Options, for examples.
		* -O
		* -O1
			* Optimize. Optimizing compilation takes somewhat more time, and a lot more memory for a large function.
			* With -O, the compiler tries to reduce code size and execution time, without performing any optimizations that take a great deal of compilation time.
		* -O2
			* Optimize even more. GCC performs nearly all supported optimizations that do not involve a space-speed tradeoff. As compared to -O, this option increases both compilation time and the performance of the generated code.
			* -O2 turns on all optimization flags specified by -O1. It also turns on the following optimization flags
		* -O3
			* Optimize yet more. -O3 turns on all optimizations specified by -O2 and also turns on the following optimization flags
		* -O0
			* Reduce compilation time and make debugging produce the expected results. This is the default.
		* -Os
			* Optimize for size. -Os enables all -O2 optimizations except those that often increase code size
			* It also enables -finline-functions, causes the compiler to tune for code size rather than execution speed, and performs further optimizations designed to reduce code size.
		* -Ofast
			* Disregard strict standards compliance. -Ofast enables all -O3 optimizations. It also enables optimizations that are not valid for all standard-compliant programs. It turns on -ffast-math, -fallow-store-data-races and the Fortran-specific -fstack-arrays, unless -fmax-stack-var-size is specified, and -fno-protect-parens. It turns off -fsemantic-interposition.
		* -Og
			* Optimize debugging experience. -Og should be the optimization level of choice for the standard edit-compile-debug cycle, offering a reasonable level of optimization while maintaining fast compilation and a good debugging experience. It is a better choice than -O0 for producing debuggable code because some compiler passes that collect debug information are disabled at -O0.
			* Like -O0, -Og completely disables a number of optimization passes so that individual options controlling them have no effect. Otherwise -Og enables all -O1 optimization flags except for those that may interfere with debugging
		* -Oz
			* Optimize aggressively for size rather than speed. This may increase the number of instructions executed if those instructions require fewer bytes to encode. -Oz behaves similarly to -Os including enabling most -O2 optimizations.
		* If you use multiple -O options, with or without level numbers, the last such option is the one that is effective.
	* [3.13 Options Controlling the Preprocessor](https://gcc.gnu.org/onlinedocs/gcc/Preprocessor-Options.html#Preprocessor-Options)
		* These options control the C preprocessor, which is run on each C source file before actual compilation.
		* -D name
			* Predefine name as a macro, with definition 1.
		* -D name=definition
			* The contents of definition are tokenized and processed as if they appeared during translation phase three in a ‘#define’ directive. In particular, the definition is truncated by embedded newline characters.
			* If you are invoking the preprocessor from a shell or shell-like program you may need to use the shell’s quoting syntax to protect characters such as spaces that have a meaning in the shell syntax.
			* If you wish to define a function-like macro on the command line, write its argument list with surrounding parentheses before the equals sign (if any). Parentheses are meaningful to most shells, so you should quote the option. With sh and csh, -D'name(args…)=definition' works.
			* -D and -U options are processed in the order they are given on the command line. All -imacros file and -include file options are processed after all -D and -U options.
		* -U name
			* Cancel any previous definition of name, either built in or provided with a -D option.
	* [6.34 Specifying Attributes of Variables](https://gcc.gnu.org/onlinedocs/gcc/Variable-Attributes.html#Variable-Attributes)
		* [6.34.1 Common Variable Attributes](https://gcc.gnu.org/onlinedocs/gcc/Common-Variable-Attributes.html#Common-Variable-Attributes)
			* unused
				* This attribute, attached to a variable or structure field, means that the variable or field is meant to be possibly unused. GCC does not produce a warning for this variable or field.
* [c - How many GCC optimization levels are there? - Stack Overflow](https://stackoverflow.com/questions/1778538/how-many-gcc-optimization-levels-are-there)
* [c++ - Is optimisation level -O3 dangerous in g++? - Stack Overflow](https://stackoverflow.com/questions/11546075/is-optimisation-level-o3-dangerous-in-g)
* [gcc - How to pass values during compilation with g++ using -DN flag - Stack Overflow](https://stackoverflow.com/questions/15338289/how-to-pass-values-during-compilation-with-g-using-dn-flag)
	* -DXXX flag is just like adding #define XXX. So -DN=2 is just like #define N  2.
	* And you can pass values during compilation using this flag.
* [Linux 程序编译过程详解](https://mp.weixin.qq.com/s/W4_509c5TXV7XvL9pyqAOw)
	* https://blog.csdn.net/qq_39221436/article/details/125638972
	* 本文将介绍如何将高层的C/C++语言编写的程序转换成为处理器能够执行的二进制代码的过程，包括四个步骤：
		* 预处理（Preprocessing）
		* 编译（Compilation）
		* 汇编（Assembly）
		* 链接（Linking）

#### [GDB](https://en.wikipedia.org/wiki/GNU_Debugger)

* [GDB (Step by Step Introduction) - GeeksforGeeks](https://www.geeksforgeeks.org/gdb-step-by-step-introduction/)
* How to debug Core Dumps with GDB in linux ?
	* [GDB - Core Dumps — Debugging documentation](https://www.cse.unsw.edu.au/~learn/debugging/modules/gdb_coredumps/)
		* Core Dump Settings
			* To enable core dumps, first check the maximum core dump size:
				* `$ ulimit -c`
			* If the result of this is zero (i.e. no core dump will be produced), set the limit to the maximum:
				* `$ ulimit -c unlimited`
		* Generating a Core Dump
			* Compile the code for use with GDB.
				* `$ gcc -g <any other flags> -o file_name file_name.c`
			* Run the program as normal
				* `$ ./<file_name>` Segmentation fault (core dumped)
				* An error message like the one above should appear if the program crashes.
		* Starting a GDB session
			* Start a GDB session with the program binary and coredump file
				* `$ gdb <binary-file> <core-dump-file>`
				* GDB is helpful to inspect the stack frame and the state of variables and registers when the program crashed. Commands such as where, up, down, print, info locals, info args, info registers and list can be helpful in this situation.
				* It is useful to remember that, while debugging core dumps, the program is not actually running, so commands related to the execution of the program such as step, next and continue are unavailable.
	* [C++ Tutorial - Debugging: Core/Memory Dump - 2020](https://www.bogotobogo.com/cplusplus/debugging_core_memory_dump_segmentation_fault_gdb.php)
		* We can use backtrace to list the call stacks that had been made when the program crashed:
			* `(gdb) backtrace`
* How to debug inline functions ?
	* [c++ - Possible to call inline functions in gdb and/or emit them using GCC? - Stack Overflow](https://stackoverflow.com/questions/22029834/possible-to-call-inline-functions-in-gdb-and-or-emit-them-using-gcc)
	* [c++ - Cannot evaluate function -- may be inlined - Stack Overflow](https://stackoverflow.com/questions/22163730/cannot-evaluate-function-may-be-inlined)
	* [Inline Functions - Debugging with GDB](https://www.zeuthen.desy.de/dv/documentation/unixguide/infohtml/gdb/Inline-Functions.html#:~:text=gdb%20displays%20inlined%20functions%20just,using%20the%20info%20frame%20command.)
	* [Debugging with GDB](https://docs.adacore.com/gdb-docs/html/gdb.html#Commands)
* How to attach to process to debug with gdb on linux ?
    * To attach to a running process and debug it with GDB (the GNU Debugger) on Linux, you need to follow several steps. This is a common technique used to diagnose issues with processes that are already running, particularly when you can't start the process from within GDB due to it being a service or a daemon. Here’s a step-by-step guide on how to do it:
    * Step 1: Install GDB
        * First, make sure that GDB is installed on your Linux system. If it's not installed, you can easily install it using your distribution's package manager:
        * For Debian/Ubuntu:
            * `sudo apt-get install gdb`
        * For Fedora/Red Hat:
            * `sudo dnf install gdb`
    * Step 2: Locate the Process ID
        * You need the process ID (PID) of the application you want to attach to. You can find this by using the ps command along with grep to filter out the specific process. For example, if your application's name includes "myapp", you might use:
            * `ps aux | grep myapp`
            * This command will list processes that include "myapp" in their command line. Look for the PID in the output, which is typically the second column.
    * Step 3: Give Permission to Attach to the Process
        * Modern Linux systems have a security feature that might prevent GDB from attaching to a process. You may need to change a setting to allow this:
        * Temporarily allow attaching (safer option):
            * `echo 0 | sudo tee /proc/sys/kernel/yama/ptrace_scope`
            * This change is temporary and resets upon reboot. It's safer because it doesn't permanently reduce system security.
        * Permanently allow attaching (not recommended for most users):
            * Modify the file /etc/sysctl.d/10-ptrace.conf or similar, changing the line to kernel.yama.ptrace_scope = 0 and then run:
                * `sudo sysctl -p /etc/sysctl.d/10-ptrace.conf`
    * Step 4: Attach GDB to the Process
        * Now that you have the PID and have permitted debugging, you can attach GDB to the process. Replace 12345 with the actual PID:
            * `sudo gdb -p 12345`
            * You need to use sudo if the process is running under a different user from your own or requires higher privileges.
    * Step 5: Debug the Process
        * Once attached, GDB will halt the process. You can now perform any typical debugging tasks, such as:
            * Setting breakpoints
            * Stepping through code
            * Inspecting variables
            * Changing values
        * Use the GDB command interface to navigate and manipulate the program state. Here are a few useful commands:
            * c or continue: Continue running the process.
            * bt or backtrace: Show the call stack.
            * print var_name: Print the current value of a variable var_name.
            * set var var_name = value: Set the variable var_name to a new value.
            * break filename.c:lineno: Set a breakpoint at line number lineno in the file filename.c.
    * Step 6: Detach and Resume
        * When you're done debugging, you can detach GDB from the process and let it continue running:
            * `detach`
        * Then, exit GDB:
            * `quit`
    * These steps allow you to debug a live process on Linux using GDB effectively, providing powerful insights into runtime behavior and facilitating the diagnosis of complex issues.

#### make

* [Makefile相关资料 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2010/10/08/1846067.html)
* [[ZZ]make命令与makefile文件的写法 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2010/10/08/1846070.html)
* [CMake - Wikipedia](https://en.wikipedia.org/wiki/CMake)
	* [CMake Tutorial — CMake 3.23.0-rc2 Documentation](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
	* [Examples | CMake](https://cmake.org/examples/)
* [Top (GNU make)](https://www.gnu.org/software/make/manual/html_node/index.html#SEC_Contents)
	* [Cleanup (GNU make)](https://www.gnu.org/software/make/manual/html_node/Cleanup.html)
		* Compiling a program is not the only thing you might want to write rules for. Makefiles commonly tell how to do a few other things besides compiling a program: for example, how to delete all the object files and executables so that the directory is ‘clean’.
		* Since clean is not a prerequisite of edit, this rule will not run at all if we give the command ‘make’ with no arguments. In order to make the rule run, we have to type ‘make clean’. See [How to Run make](https://www.gnu.org/software/make/manual/html_node/Running.html#Running).
* [makefile - How to clean executable using make clean? - Ask Ubuntu](https://askubuntu.com/questions/433943/how-to-clean-executable-using-make-clean)
* [Makefiles](https://web.eecs.umich.edu/~sugih/pointers/make.html)
	* In this handout, we will take apart an example makefile and see how the pieces contribute to a working whole.
	* The Cleanup Rule
    ```sh
    clean:
        rm *.o prog3
    ```
	* This is an optional rule. It allows you to type 'make clean' at the command line to get rid of your object and executable files. Sometimes the compiler will link or compile files incorrectly and the only way to get a fresh start is to remove all the object and executable files.
* How to clean up and rebuild in cmake ?
    * When working with CMake, cleaning up the build directory and rebuilding the project are common tasks, especially when you want to ensure that old build artifacts don't affect your current build. Here’s how you can effectively clean up and rebuild a project managed by CMake.
    * Cleaning Up a CMake Build
        * To clean up a CMake build, you typically need to remove the build directory and all its contents. CMake does not have a built-in clean command like Make, so you have to do it manually or script it. Here are some methods:
            * Method 1: Delete the Build Directory
                * This is the most straightforward method. Simply delete the entire build directory and recreate it. This ensures that all previous configurations, caches, and build artifacts are removed.
                * Using Command Line:
                ```bash
                rm -rf /path/to/build-directory
                mkdir /path/to/build-directory
                cd /path/to/build-directory
                cmake ..
                make
                ```
            * Method 2: Using a Makefile Target
                * If you are using the Unix Makefiles generator with CMake, you can use the make clean command to clean up most build artifacts, but this will not remove CMake-specific files (like CMakeCache.txt).
                * Using Command Line:
                ```bash
                cd /path/to/build-directory
                make clean
                ```
                * To remove CMake-specific files and ensure a completely clean start:
                    * `rm -rf /path/to/build-directory/*`
    * Rebuilding a CMake Project
        * To rebuild a project from scratch, follow these steps:
            * Clean the Build Directory: Use one of the methods above to clean your build directory.
            * Re-run CMake: Navigate to your clean build directory and re-run the CMake configuration commands to generate fresh makefiles.
            * Build the Project: Run your build command (like make, ninja, etc.) to compile the project.
            * Example Sequence:
            ```bash
            # Assuming the build directory is `build` located in the project root
            rm -rf build/
            mkdir build
            cd build
            cmake ..
            make
            ```
    * Automating Clean and Rebuild
        * You can create a script to automate these steps, which can be helpful if you frequently need to rebuild from scratch. Here’s a simple Bash script example:
        ```bash
        #!/bin/bash
        # Rebuild script for a CMake project
        
        # Define the build directory
        BUILD_DIR="./build"
        
        # Check if the build directory exists, and clean it
        if [ -d "$BUILD_DIR" ]; then
            echo "Cleaning build directory..."
            rm -rf "$BUILD_DIR/*"
        else
            echo "Creating build directory..."
            mkdir "$BUILD_DIR"
        fi
        
        # Navigate to the build directory
        cd "$BUILD_DIR"
        
        # Run CMake configuration
        echo "Configuring project..."
        cmake ..
        
        # Build the project
        echo "Building project..."
        make
        
        echo "Build completed."
        ```
    * Considerations
        * Platform Differences: The way you delete files and directories can vary by operating system. The examples above are for Unix-like systems (Linux, macOS). For Windows, you might use PowerShell or Command Prompt specific commands.
        * CMake Generators: Depending on which generator you are using (Unix Makefiles, Ninja, Visual Studio, etc.), the build command might differ (make, ninja, msbuild).
    * Cleaning up and rebuilding a project in CMake helps ensure that you are working with the most recent changes to your source code and build scripts, avoiding issues related to stale files and configurations.

### [CMAKE](https://cmake.org/)

* CMake: A Powerful Software Build System
* CMake is the de-facto standard for building C++ code, with over 2 million downloads a month. It’s a powerful, comprehensive solution for managing the software build process. Get everything you need to successfully leverage CMake by visiting our resources section.
* [Getting Started with CMake](https://cmake.org/getting-started/)
* [CMake Documentation and Community](https://cmake.org/documentation/)
* CMake ?
    * CMake is a powerful cross-platform build system used to manage the build process in a compiler-independent manner. It generates native makefiles and workspaces that can be used in the compiler environment of your choice. The primary goal of CMake is to allow developers to build their applications across different platforms without needing to change the build process setup for each platform.
    * Key Features of CMake
        * Cross-platform: CMake can generate build systems for various platforms, including Linux, Windows, macOS, and more.
        * Out-of-source builds: CMake supports building outside the source directory to keep source directories clean and support multiple builds from a single source tree.
        * Configurable: CMake allows conditional builds, where parts of the software can be included or excluded based on configuration parameters.
        * Find packages: CMake can automatically find libraries and packages required for your project, handling include paths and linking settings.
        * Language support: While primarily used for C and C++, CMake supports languages like Fortran, Java, and others, making it versatile for multi-language projects.
    * Basic Components
        * CMakeLists.txt: This is the main file where you define the build process using CMake commands. It specifies project name, version, required libraries, source files, and other metadata.
        * cmake_minimum_required: Specifies the minimum version of CMake required.
        * project(): Sets the name and version of the project.
        * add_executable() or add_library(): Commands to specify which targets (executables or libraries) CMake should generate.
        * target_link_libraries(): Defines which libraries to link against when building your executables or libraries.
        * include_directories(): Specifies directories where the compiler should look for header files.
    * Example CMakeLists.txt
        * Here’s a simple example of a CMakeLists.txt for a project that creates an executable from two source files:
        ```cmake
        cmake_minimum_required(VERSION 3.10)
        
        # Set the project name and version
        project(MyProject VERSION 1.0)
        
        # Add an executable with the above sources
        add_executable(myapp main.cpp utility.cpp)
        
        # Specify C++ standard
        set_target_properties(myapp PROPERTIES
          CXX_STANDARD 11
          CXX_STANDARD_REQUIRED YES
          CXX_EXTENSIONS NO
        )
        
        # Add directory containing Header Files
        include_directories(include)
        ```
    * How to Use CMake
        * Writing CMakeLists.txt: Define your project and its dependencies in CMakeLists.txt.
        * Configuring the Project:
            * Create a build directory (mkdir build && cd build).
            * Run CMake configuration (cmake .. or cmake -G "Your Generator" ..) to generate makefiles or other build system files specific to your platform.
        * Building the Project:
            * Build the project using CMake-generated files (cmake --build . or use your build system directly like make, ninja, etc.).
        * Running the Executable:
            * Run your built executable directly from the build directory.
    * Advanced Features
        * CPack for Packaging: CMake includes CPack, which can be used to generate installers for your software.
        * CTest for Testing: Integrated testing support with CTest, which allows you to add tests and perform automated testing as part of your build process.
        * Compiler and Linker Options: Customize compiler and linker flags based on the needs and optimizations specific to your project.
    * Conclusion
        * CMake is an essential tool for modern software development, particularly for projects that need to support multiple platforms. It simplifies the build process by managing the differences in environments internally, allowing developers to focus more on development rather than the build system.
* specify Unix / Windows / Debug / Release in CMakeLists.txt ?
    * When developing cross-platform applications with CMake, it's common to need different settings based on the operating system (Unix or Windows) and the build type (Debug or Release). CMake provides mechanisms to handle these distinctions efficiently in your CMakeLists.txt file. Below, I'll show you how to specify settings for different platforms and build types.
    * Distinguishing Between Unix and Windows
        * You can use CMake's built-in variables to conditionally compile code or set compiler options depending on the operating system.
        * Example:
        ```cmake
        cmake_minimum_required(VERSION 3.10)
        project(MyProject)
        
        # Set sources
        set(SOURCES main.cpp)
        
        # Check if compiling on Windows
        if(WIN32)
            # Windows-specific code
            set(SOURCES ${SOURCES} win_specific.cpp)
            add_definitions(-DWINDOWS=1)
        else()
            # Unix/Linux-specific code
            set(SOURCES ${SOURCES} unix_specific.cpp)
            add_definitions(-DUNIX=1)
        endif()
        
        add_executable(MyProject ${SOURCES})
        ```
    * Specifying Debug and Release Settings
        * You can specify different settings for Debug and Release builds using the CMAKE_BUILD_TYPE variable and related commands.
        * Example:
        ```cmake
        cmake_minimum_required(VERSION 3.10)
        project(MyProject)
        
        # Set the default build type if not specified
        if(NOT CMAKE_BUILD_TYPE)
          set(CMAKE_BUILD_TYPE Release)
        endif()
        
        # Set compiler flags
        set(CMAKE_CXX_FLAGS "-Wall -Wextra")
        set(CMAKE_CXX_FLAGS_DEBUG "-g")
        set(CMAKE_CXX_FLAGS_RELEASE "-O3")
        
        # Add definitions for debug mode
        if(CMAKE_BUILD_TYPE STREQUAL "Debug")
            add_definitions(-DDEBUG_MODE=1)
        endif()
        
        add_executable(MyProject main.cpp)
        ```
    * Advanced Conditional Settings
        * For more complex scenarios, especially when dealing with multiple platforms and specific compiler options, you might want to refine your settings further.
        * Example:
        ```cmake
        cmake_minimum_required(VERSION 3.10)
        project(MyProject)
        
        # Check operating system and set files and compiler flags
        if(WIN32)
            set(PLATFORM_SOURCES win_main.cpp)
            if(MSVC)
                set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} /W4")
            else()
                set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra")
            endif()
        elseif(UNIX)
            set(PLATFORM_SOURCES unix_main.cpp)
            set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra")
        endif()
        
        # Different source files and definitions based on Debug or Release
        if(CMAKE_BUILD_TYPE STREQUAL "Debug")
            set(SOURCES ${PLATFORM_SOURCES} debug_additional.cpp)
            add_definitions(-DDEBUG)
        else()
            set(SOURCES ${PLATFORM_SOURCES} release_additional.cpp)
            add_definitions(-DNDEBUG)
        endif()
        
        add_executable(MyProject ${SOURCES})
        ```
    * Summary
        * In CMake, using conditions for platform-specific code and different build types helps create robust and portable build systems. By checking the environment with if statements and using appropriate variables (CMAKE_BUILD_TYPE, WIN32, UNIX, MSVC), you can tailor the build process to match the needs of each platform or configuration:
            * Use `WIN32`, `UNIX`, and `APPLE` for platform-specific settings.
            * Use `MSVC`, `GCC`, etc., to check for specific compilers.
            * Control build behavior with `CMAKE_BUILD_TYPE` and flags like `CMAKE_CXX_FLAGS_DEBUG` and `CMAKE_CXX_FLAGS_RELEASE`.
        * This method ensures that your project can be built in various environments without changing the source code, just by adjusting the build scripts.
* target_link_directories / target_link_libraries in CMakeLists.txt ?
    * In CMake, target_link_directories and target_link_libraries are commands used to specify where to find libraries and which libraries to link against when building a target (like an executable or library). Understanding how to use these commands correctly is crucial for properly configuring the build process of your CMake projects.
    * target_link_directories
        * Introduced in CMake 3.13, the target_link_directories command specifies the directories where the linker should look for libraries to link against a target. This command is used to add link directories to a target.
        * Syntax
            ```cmake
            target_link_directories(<target>
                [BEFORE|AFTER]
                [PUBLIC|PRIVATE|INTERFACE]
                <directories>...
            )
            ```
            * `<target>`: The target (executable or library) that the link directories apply to.
            * `[BEFORE|AFTER]`: Optional. Specifies whether the directories should be added before or after the existing directories in the linker search path.
            * `[PUBLIC|PRIVATE|INTERFACE]`: Specifies the scope of the directories.
               * `PUBLIC`: The directories are added to the link directories for the target and will also be used in the link step of any targets that link to this target.
               * `PRIVATE`: The directories are used only in the link step for this target.
               * `INTERFACE`: The directories are not used for this target but are used for targets linking to this target.
            * `<directories>`: One or more directories to add to the linker search path.
        * Example
            ```cmake
            add_executable(MyApp main.cpp)
            target_link_directories(MyApp PRIVATE ${CMAKE_SOURCE_DIR}/libs)
            ```
    * target_link_libraries
        * The target_link_libraries command is used to specify which libraries a target should be linked against. This is one of the most commonly used commands in CMake for managing library dependencies.
        * Syntax
            ```cmake
            target_link_libraries(<target>
                <item>...
                [<PRIVATE|PUBLIC|INTERFACE> <item>...]...
            )
            ```
            * `<target>`: The target that needs to link against the specified libraries.
            * `<item>`: Specifies a library to link against. This can be a target name or a library file.
            * `[PRIVATE|PUBLIC|INTERFACE]`: Specifies the scope similar to target_link_directories.
                * `PRIVATE`: Libraries are linked only to the specified target.
                * `PUBLIC`: Libraries are linked to the specified target and also to targets that link this target.
                * `INTERFACE`: Libraries are linked not to the specified target but to targets that link this target.
        * Example
            ```cmake
            add_library(MyLibrary STATIC IMPORTED)
            set_property(TARGET MyLibrary PROPERTY IMPORTED_LOCATION ${CMAKE_SOURCE_DIR}/libs/mylibrary.lib)
            
            add_executable(MyApp main.cpp)
            target_link_libraries(MyApp PRIVATE MyLibrary)
            ```
    * Best Practices
        * Prefer target-specific commands: Using target_link_directories and target_link_libraries allows for more precise and maintainable handling of library dependencies compared to using directory-based commands like link_directories, which apply globally.
        * Scope specification: Always specify the scope (PRIVATE, PUBLIC, INTERFACE) explicitly to make your CMake files clearer and to ensure proper encapsulation of dependencies.
        * Use absolute paths: When possible, specify absolute paths to libraries and link directories to avoid relative path issues, especially when the build directory structure may vary.
    * Using these commands correctly helps ensure that your project's build configuration is robust, portable, and easy to maintain. This makes it easier to manage complex projects with multiple dependencies across different platforms and build environments.

## [C++ language](https://en.cppreference.com/w/cpp/language)

* This is a reference of the core C++ language constructs.
* [最好的 5 个 C++ 网站](https://mp.weixin.qq.com/s/v3PoPBYI3uJAsQeqQQQlfA)
    * [cppreference](https://en.cppreference.com/w/)
        * cppreference 即 C++ 参考手册，这个网站始终是我的首选，因为它非常简洁，可读性也很强，不但更新及时（已经到 C++20 了），还提供了很好的示例。
    * [LearnCpp](http://www.learncpp.com/)
        * 这可以说是最好的 C++ 教程网站了，组织结构非常好，而且内容丰富、易于理解（涵盖面很广，讲解也很细致），会进行定期更新，并增加一些新的主题。毫不夸张的说，它就像一本 C++ 在线书籍。
    * [Cplusplus](http://www.cplusplus.com/)
        * 这也是一个学习 C++ 的优秀网站，除了提供相应的教程之外，还有一个很棒的论坛。和其它网站相比，它的价值更多体现在参考上，因为里面解释了许多编程概念，如果对某个特定的东西感到困惑，那么这些概念将会很有帮助。（吐槽一下，更新不及时！）
    * [TutorialsPoint](https://www.tutorialspoint.com/cplusplus/index.htm)
        * Tutorialspoint 是一个顶级网站，之所以这么说，是因为你想学的任何技术（包括 C++），它几乎都提供了详细的教程。保存好就对了，超级有用。（顺便再介绍一个 GeeksForGeeks）
    * [Awesome C++](https://github.com/fffaraz/awesome-cpp)
        * 想必很多人都知道 GitHub 上的 Awesome-XXX 系列的资源整理，awesome-cpp 就是 fffaraz 发起维护的 C++ 资源列表，内容包括：标准库、Web 应用框架、人工智能、数据库、图片处理、机器学习、日志、代码分析等。这个嘛，可以用到老 O(∩_∩)O哈哈~！
* [C/C++ PK 各大编程语言](https://mp.weixin.qq.com/s/zTuPyQRkjkVWp_KIjMh_Kw)
* [C++ 后端开发路线](https://mp.weixin.qq.com/s/QvFQEjUPEw_2zexaZi6GNQ)
* [这不就是你要的C++后台开发学习路线吗？](https://mp.weixin.qq.com/s/1FRSTcUnGf6e8HvJ3sdwLg)
* [45天，入门C++](https://mp.weixin.qq.com/s/GEUChOAu8wKZ-mazyKaMow)

### [Basic concepts](https://en.cppreference.com/w/cpp/language/basic_concepts)

* [<bits/stdc++.h> in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/bitsstdc-h-c/)
  * It is basically a header file that includes every standard library. In programming contests, using this file is a good idea, when you want to reduce the time wasted in doing chores; especially when your rank is time sensitive.
In programming contests, people do focus more on finding the algorithm to solve a problem than on software engineering. From, software engineering perspective, it is a good idea to minimize the include. If you use it actually includes a lot of files, which your program may not need, thus increases both compile time and program size unnecessarily.
* [一个合格的ACMer的代码当中，都藏着哪些秘密？ (qq.com)](https://mp.weixin.qq.com/s/0_qWix8jARKulLFKUR5UNg)
* [万字长文解析C++ 基础知识！初学者必看的一篇 (qq.com)](https://mp.weixin.qq.com/s/w7sKDO-YkfR2ZRwKyam4Pw)
  * C++ 注释
  * C++ 数据类型
    * 基本的内置类型
    * typedef 声明
    * 枚举类型
  * C++ 变量作用域
    * 局部变量
    * 全局变量
    * 初始化局部变量和全局变量
  * C++ 常量
    * 整数常量
    * 浮点常量
    * 布尔常量
    * 字符常量
    * 字符串常量
    * 定义常量
      * #define 预处理器
      * const 关键字
  * C++ 修饰符类型
  * C++ 中的类型限定符
  * C++ 存储类
    * auto 存储类
    * register 存储类
    * static 存储类
    * extern 存储类
    * mutable 存储类
  * C++ 运算符
    * 算术运算符
    * 关系运算符
    * 逻辑运算符
    * 位运算符
    * 赋值运算符
    * 杂项运算符
    * C++ 中的运算符优先级

#### [ASCII Chart](https://en.cppreference.com/w/cpp/language/ascii)

* The following chart contains all 128 ASCII decimal (dec), octal (oct), hexadecimal (hex) and character (ch) codes.
* Example
```c++
#include <iostream>
int main()
{
    std::cout << "Printable ASCII [32..126]:\n";
    for (char c{' '}; c <= '~'; c++) {
        std::cout << c << ((c+1) % 32 ? ' ' : '\n');
    }
}
/*
Printable ASCII [32..126]:
  ! " # $ % & ' ( ) * + , - . / 0 1 2 3 4 5 6 7 8 9 : ; < = > ?
@ A B C D E F G H I J K L M N O P Q R S T U V W X Y Z [ \ ] ^ _
` a b c d e f g h i j k l m n o p q r s t u v w x y z { | } ~
```

#### [Types](https://en.cppreference.com/w/cpp/language/type) – [Fundamental types](https://en.cppreference.com/w/cpp/language/types)

* Objects, references, functions including function template specializations, and expressions have a property called type, which both restricts the operations that are permitted for those entities and provides semantic meaning to the otherwise generic sequences of bits.
* [Data Type Ranges | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/data-type-ranges?view=msvc-170)
* [Modifier Types](https://www.tutorialspoint.com/cplusplus/cpp_modifier_types.htm)
* [Difference between float and double in C/C++ - GeeksforGeeks](https://www.geeksforgeeks.org/difference-float-double-c-cpp/)
* [Wide character - Wikipedia](https://en.wikipedia.org/wiki/Wide_character)
  * A wide character is a computer character datatype that generally has a size greater than the traditional 8-bit character. The increased datatype size allows for the use of larger coded character sets.
  * Programming specifics
    * The C and C++ standard libraries include a number of facilities for dealing with wide characters and strings composed of them. The wide characters are defined using datatype wchar_t, which in the original C90 standard was defined as
    * "an integral type whose range of values can represent distinct codes for all members of the largest extended character set specified among the supported locales" (ISO 9899:1990 §4.1.5)
    * Both C and C++ introduced fixed-size character types char16_t and char32_t in the 2011 revisions of their respective standards to provide unambiguous representation of 16-bit and 32-bit Unicode transformation formats, leaving wchar_t implementation-defined. The ISO/IEC 10646:2003 Unicode standard 4.0 says that:
    * "The width of wchar_t is compiler-specific and can be as small as 8 bits. Consequently, programs that need to be portable across any C or C++ compiler should not use wchar_t for storing Unicode text. The wchar_t type is intended for storing compiler-defined wide characters, which may be Unicode characters in some compilers."[3]
  * [wchar_t - C++ Reference](https://www.cplusplus.com/reference/cwchar/wchar_t)
    * Wide character
    * Type whose range of values can represent distinct codes for all members of the largest extended character set specified among the supported locales.
    * In C++, wchar_t is a distinct fundamental type (and thus it is not defined in /<cwchar/> nor any other header).
    * In C, this is a typedef of an integral type.
  * [Fundamental types - cppreference.com](https://en.cppreference.com/w/cpp/language/types)
    * wchar_t - type for wide character representation (see wide strings). Required to be large enough to represent any supported character code point (32 bits on systems that support Unicode. A notable exception is Windows, where wchar_t is 16 bits and holds UTF-16 code units) It has the same size, signedness, and alignment as one of the integer types, but is a distinct type.
  * [char, wchar_t, char8_t, char16_t, char32_t | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/char-wchar-t-char16-t-char32-t?view=msvc-160)
    * The types char, wchar_t, char8_t, char16_t, and char32_t are built-in types that represent alphanumeric characters, non-alphanumeric glyphs, and non-printing characters.
    * The wchar_t type is an implementation-defined wide character type. In the Microsoft compiler, it represents a 16-bit wide character used to store Unicode encoded as UTF-16LE, the native character type on Windows operating systems. The wide character versions of the Universal C Runtime (UCRT) library functions use wchar_t and its pointer and array types as parameters and return values, as do the wide character versions of the native Windows API.
	* [c++ - how to convert char array to wchar_t array? - Stack Overflow](https://stackoverflow.com/questions/3074776/how-to-convert-char-array-to-wchar-t-array)
		* [mbstowcs_s, _mbstowcs_s_l | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/c-runtime-library/reference/mbstowcs-s-mbstowcs-s-l?view=msvc-170)
    ```c++
    #include <iostream>
    #include <stdlib.h>
    #include <string>

    using namespace std;
    using namespace System;

    int main()
    {
        char *orig = "Hello, World!";
        cout << orig << " (char *)" << endl;

        // Convert to a wchar_t*
        size_t origsize = strlen(orig) + 1;
        const size_t newsize = 100;
        size_t convertedChars = 0;
        wchar_t wcstring[newsize];
        mbstowcs_s(&convertedChars, wcstring, origsize, orig, _TRUNCATE);
        wcscat_s(wcstring, L" (wchar_t *)");
        wcout << wcstring << endl;
    }
    ```
  * [Predefined macros | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/predefined-macros?view=msvc-160)
    * _NATIVE_WCHAR_T_DEFINED Defined as 1 when the /Zc:wchar_t compiler option is set. Otherwise, undefined.
    * [/Zc:wchar_t (wchar_t Is Native Type) | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/build/reference/zc-wchar-t-wchar-t-is-native-type?view=msvc-160)
      * Parse wchar_t as a built-in type according to the C++ standard.
* [谈一谈 C++ 中的值的类型 (qq.com)](https://mp.weixin.qq.com/s/MQNIkeS3eMUmaezyUL8ZkQ)
* [对 int 变量赋值的操作是原子的吗？为什么？](https://mp.weixin.qq.com/s/l5Ybey63USoM-OZvGsByEg)
	* https://www.windsings.com/posts/2a85d31f/
	* 原问题：什么指令集支持原子操作？其原理是什么？ 如果考虑到全部的指令集，问题太大了，这里简化下。以X86和ARM为例。
	* 原子操作是不可分割的操作，在执行完毕时它不会被任何事件中断。在单处理器系统(UniProcessor，简称 UP)中，能够在单条指令中完成的操作都可以认为是原子操作，因为中断只能发生在指令与指令之间。

#### [Object](https://en.cppreference.com/w/cpp/language/object)

* C++ programs create, destroy, refer to, access, and manipulate objects.
* An object, in C++, has
    * size (can be determined with sizeof);
    * alignment requirement (can be determined with alignof);
    * storage duration (automatic, static, dynamic, thread-local);
    * lifetime (bounded by storage duration or temporary);
    * type;
    * value (which may be indeterminate, e.g. for default-initialized non-class types);
    * optionally, a name.
* The following entities are not objects: value, reference, function, enumerator, type, non-static class member, template, class or function template specialization, namespace, parameter pack, and this.
* A variable is an object or a reference that is not a non-static data member, that is introduced by a declaration.

##### [Alignment](https://en.cppreference.com/w/cpp/language/object#Alignment)

* Every object type has the property called alignment requirement, which is an integer value (of type std::size_t, always a power of 2) representing the number of bytes between successive addresses at which objects of this type can be allocated.
* The alignment requirement of a type can be queried with alignof or std::alignment_of. The pointer alignment function std::align can be used to obtain a suitably-aligned pointer within some buffer, and std::aligned_storage can be used to obtain suitably-aligned storage. (since C++11)
* Each object type imposes its alignment requirement on every object of that type; stricter alignment (with larger alignment requirement) can be requested using alignas (since C++11).
* In order to satisfy alignment requirements of all non-static members of a class, padding bits may be inserted after some of its members.
```c++
#include <iostream>
 
// objects of type S can be allocated at any address
// because both S.a and S.b can be allocated at any address
struct S
{
    char a; // size: 1, alignment: 1
    char b; // size: 1, alignment: 1
}; // size: 2, alignment: 1
 
// objects of type X must be allocated at 4-byte boundaries
// because X.n must be allocated at 4-byte boundaries
// because int's alignment requirement is (usually) 4
struct X
{
    int n;  // size: 4, alignment: 4
    char c; // size: 1, alignment: 1
    // three bytes of padding bits
}; // size: 8, alignment: 4 
 
int main()
{
    std::cout << "sizeof(S) = " << sizeof(S)
              << " alignof(S) = " << alignof(S) << '\n';
    std::cout << "sizeof(X) = " << sizeof(X)
              << " alignof(X) = " << alignof(X) << '\n';
}
/*
sizeof(S) = 2 alignof(S) = 1
sizeof(X) = 8 alignof(X) = 4
*/
```

#### [Name lookup](https://en.cppreference.com/w/cpp/language/lookup)

* `Name lookup` is the procedure by which a [name](https://en.cppreference.com/w/cpp/language/name), when encountered in a program, is associated with the declaration that introduced it.
* For example, to compile std::cout << std::endl;, the compiler performs:
    * unqualified name lookup for the name std, which finds the declaration of namespace std in the header \<iostream>
    * qualified name lookup for the name cout, which finds a variable declaration in the namespace std
    * qualified name lookup for the name endl, which finds a function template declaration in the namespace std
    * both [argument-dependent lookup](https://en.cppreference.com/w/cpp/language/adl) for the name operator<<, which finds multiple function template declarations in the namespace std, and qualified name lookup for the name `std::ostream::operator<<`, which finds multiple member function declarations in class std::ostream.
* For function and function template names, name lookup can associate multiple declarations with the same name, and may obtain additional declarations from [argument-dependent lookup](https://en.cppreference.com/w/cpp/language/adl). [Template argument deduction](https://en.cppreference.com/w/cpp/language/function_template) may also apply, and the set of declarations is passed to [overload resolution](https://en.cppreference.com/w/cpp/language/overload_resolution), which selects the declaration that will be used. [Member access](https://en.cppreference.com/w/cpp/language/access) rules, if applicable, are considered only after name lookup and overload resolution.
* For all other names (variables, namespaces, classes, etc), name lookup can associate multiple declarations only if they declare the same entity, otherwise it must produce a single declaration in order for the program to compile. Lookup for a name in a scope finds all declarations of that name, with one exception, known as the "struct hack" or "type/non-type hiding": Within the same scope, some occurrences of a name may refer to a declaration of a class/struct/union/enum that is not a typedef, while all other occurrences of the same name either all refer to the same variable, non-static data member, or enumerator, or they all refer to possibly overloaded function or function template names. In this case, there is no error, but the type name is hidden from lookup (the code must use [elaborated type specifier](https://en.cppreference.com/w/cpp/language/elaborated_type_specifier) to access it).

##### Types of lookup

* If the name appears immediately to the right of the scope resolution operator :: or possibly after :: followed by the disambiguating keyword template, see
    * [Qualified name lookup](https://en.cppreference.com/w/cpp/language/qualified_lookup)
* Otherwise, see
    * [Unqualified name lookup](https://en.cppreference.com/w/cpp/language/unqualified_lookup)
        * (which, for function names, includes [Argument-dependent lookup](https://en.cppreference.com/w/cpp/language/adl))

### [Keywords](https://en.cppreference.com/w/cpp/keyword)

#### [C++ keywords: auto](https://en.cppreference.com/w/cpp/keyword/auto)

* [automatic storage duration specifier (until C++11)](https://en.cppreference.com/w/cpp/language/storage_duration)
* [auto placeholder type specifier (since C++11)](https://en.cppreference.com/w/cpp/language/auto)
* [function declaration with trailing return type (since C++11)](https://en.cppreference.com/w/cpp/language/function)
* [structured binding declaration (since C++17)](https://en.cppreference.com/w/cpp/language/structured_binding)
* [现代C++编程实践(七)—auto的前世今生](https://mp.weixin.qq.com/s/MMynpJruZ11JykWYY0UoOg)
	* 1 C++98 auto出现
		* 在c++98中，auto仅仅是作为一个关键字用来修饰变量，表示一个自动变量，它在作用域内生效，就像定义在栈上的变量一样，一旦超出其作用域，该变量会被自动释放回收。像极了变量。因此在随后的C++版本中，auto被赋予了新的含义，老的含义自然也被弃用，但是无论如何作为C++发展的一个过程，很多C++开发人员也对它非常推崇，
	* 2 C++11 全新的auto
		* C++11后，auto被赋予了新的含义，可以自动推导出变量的类型，在编译阶段就可以计算出变量的类型。主要用法如下：
			* 用来定义一个变量
			* 减少代码复杂度
				* 在STL编程时，经常会使用大迭代器，使用后会导致代码类型较长，使用auto后会对变量自动进行推导。
			* 模板函数返回值
				* 在C++11中，auto还不能够直接当作函数返回值返回，需要和decltyp搭配使用
		* 当然，在C++11中，开发带来便利的同时也需要遵循一定的约束，如：
			* auto变量不能有二义性
			* 不能将auto直接作为函数的参数
				* 在后面我们会介绍，这种用法在C++14中是支持的，C++11中还没有支持。
			* auto声明变量后需要立即进行初始化
			* auto变量赋值为数组，这个时候推导出来的类型为指针，如果想要推导出来的类型为数组，需要在前面加上&符号。
	* 3 C++14 一点点地改进
		* 2014年C++14版本发布，相对C++11来说，C++14对auto特性也进行了提升，比如说前面的auto不能作为函数返回值，在这个版本中明确已经支持了。
		* 需要明确的是在使用auto作为函数返回类型的时候依旧需要遵守避免函数返回结果的二义性
		* 除此之后，C++14版本还可以使用decltype(auto)作为类型占位符。推导出的类型为推导出的类型是 decltype(expr)。其中expr为初始化器。
		* decltype(auto)还可以被用于函数或者模板返回参数
		* 当然，除了上面的使用场景外，auto还可用在lambda表达式中，关于这一点后面会进行介绍，本文不再赘述。
	* 4 C++17 又一个大版本
		* C++14版本发布三年后，C++17版本横空出世，在这个版本中又新增了许多新的特性，auto也不例外，这一次它又一次对模板进行了革命，令人惊奇的是这一次它是作为非类型模板形参进入的，也就是说C++17后可以根据实参自动推导出形参的类型。
	* 5 关于C++20和C++23版本
		* C++20和C++23版本，本文不做详细的说明，因为后续会有专门的推文进行介绍，如果大家想要继续了解，欢迎关注收藏。现在对这两个版本关于auto的改动做一个预告。C++20和C++23版本中，auto的改动主要如下：
			* 类型约束(C++20版本): 这个和C++20中的概念一起了解比较合适。主要是限定入参类型，这样就可以针对传入参数的不同类型给出不同的反馈。关于C++20可以关注此专集详细了解：C++20新特新
			* 简写函数模板（C++20版本):这样就可以像写普通函数一样编写模板函数了。
			* 通过表达式推导类型(C++23版本):auto 说明符也可以在显式类型转换的简单类型说明符中出现：auto(expr) 与 auto{expr} 。从表达式推导它的类型。

#### [C++ keywords: struct](https://en.cppreference.com/w/cpp/keyword/struct)

* [declaration of a compound type](https://en.cppreference.com/w/cpp/language/class)
* [declaration of a scoped enumeration type (since C++11)](https://en.cppreference.com/w/cpp/language/enum)
* If a function or a variable exists in scope with the name identical to the name of a non-union class type, struct can be prepended to the name for disambiguation, resulting in an [elaborated type specifier](https://en.cppreference.com/w/cpp/language/elaborated_type_specifier)
* [Struct declaration - cppreference.com](https://en.cppreference.com/w/c/language/struct)
	* A struct is a type consisting of a sequence of members whose storage is allocated in an ordered sequence (as opposed to union, which is a type consisting of a sequence of members whose storage overlaps).
* [Struct and union initialization - cppreference.com](https://en.cppreference.com/w/c/language/struct_initialization)
```c++
#include <stdio.h>
#include <time.h>
 
int main(void)
{
    char buff[70];
    // designated initializers simplify the use of structs whose
    // order of members is unspecified
    struct tm my_time = { .tm_year=2012-1900, .tm_mon=9, .tm_mday=9,
                          .tm_hour=8, .tm_min=10, .tm_sec=20 };
    strftime(buff, sizeof buff, "%A %c", &my_time);
    puts(buff);
}
```
* [C/C++ 结构体就这样被攻克了！](https://mp.weixin.qq.com/s/-RoBZ9Gge-6HtYH8tUS8xw)
  * 结构体的声明与定义
    * 声明
    * 定义
    * 访问结构体成员
    * 初始化结构体
    * 对齐
  * 结构体嵌套
  * 结构体数组
  * 结构体指针
  * 传递结构体信息
    * 传递结构体变量
    * 传递指向结构体变量的指针
  * 动态申请结构体
  * 实战：建立一个图书馆数据库
  * 单链表
    * 在单链表中插入元素
    * 搜索单链表
    * 插入结点到指定位置
    * 删除结点
  * 内存池
  * typedef
    * 给数据类型起别名
    * 结构体的搭档
    * 进阶
  * 共用体
    * 声明
    * 初始化
  * 枚举
  * 位域
* [Attending Workshops | HackerRank](https://www.hackerrank.com/challenges/attending-workshops/problem)
```c++
// #include<bits/stdc++.h>
#include<algorithm>
#include<iostream>
#include<vector>
using namespace std;

//Define the structs Workshops and Available_Workshops.
//Implement the functions initialize and CalculateMaxWorkshops
struct Workshop {
    int start, duration, end;
};

struct Available_Workshops {
    Available_Workshops(int n) : m_n(n) {}

    int m_n;
    vector<Workshop> m_vWorkshop;
};

Available_Workshops* initialize(int* start_time, int* duration, int n)
{
    Available_Workshops* pAW = new Available_Workshops(n);
    Workshop temp;

    for (auto i = 0; i < n; ++ i) {
        temp.start = start_time[i];
        temp.duration = duration[i];
        temp.end = start_time[i] + duration[i];
        pAW->m_vWorkshop.push_back(temp);
    }

    sort(pAW->m_vWorkshop.begin(),
        pAW->m_vWorkshop.end(),
        [](const Workshop& w1, const Workshop& w2) {
            return w1.end < w2.end;
        });

    return pAW;
}

int CalculateMaxWorkshops(Available_Workshops* ptr)
{
    auto maxWorkshops = 0;
    auto currentEnd = 0;

    for (auto i = 0; i < ptr->m_n; ++ i) {
        if (ptr->m_vWorkshop.at(i).start >= currentEnd) {
            currentEnd = ptr->m_vWorkshop.at(i).end;
            ++ maxWorkshops;
        }
    }

    return maxWorkshops;
}

int main(int argc, char *argv[]) {
    // freopen("input.txt", "r", stdin);

    int n; // number of workshops
    cin >> n;
    // create arrays of unknown size n
    int* start_time = new int[n];
    int* duration = new int[n];

    for(int i = 0; i < n; i ++) {
        cin >> start_time[i];
    }

    for(int i = 0; i < n; i ++) {
        cin >> duration[i];
    }

    Available_Workshops * ptr;
    ptr = initialize(start_time,duration, n);
    cout << CalculateMaxWorkshops(ptr) << endl;
    return 0;
}

```

#### [C++ keywords: typename](https://en.cppreference.com/w/cpp/keyword/typename)

* In the template parameter list of a template declaration, typename can be used as an alternative to class to declare type template parameters` and template template parameters (since C++17)`.
* Inside a declaration or a definition of a template, typename can be used to declare that a dependent qualified name is a type.
* typename can be used before a non-dependent qualified type name. It has no effect in this case.
* Inside a requirements for type requirements (since C++20)

### [Preprocessor](https://en.cppreference.com/w/cpp/preprocessor)

* The preprocessor is executed at [translation phase 4](https://en.cppreference.com/w/cpp/language/translation_phases#Phase_4), before the compilation. The result of preprocessing is a single file which is then passed to the actual compiler.
* [Preprocessor directives - C++ Tutorials](http://www.cplusplus.com/doc/tutorial/preprocessor/)
* [Preprocessor Solution | HackerRank](https://www.hackerrank.com/challenges/preprocessor-solution/problem)
```c++
#define toStr(args) #args
#define foreach(v, i) for (auto i = 0; i < v.size(); ++ i)
#define io(v) cin >> v
#define FUNCTION(func, op) inline void func(int& left, int right) { left = (left op right) ? left : right; }
#define INF (int)((1 << 31) - 1)

#include <iostream>
#include <vector>
using namespace std;

#if !defined toStr || !defined io || !defined FUNCTION || !defined INF
#error Missing preprocessor definitions
#endif

FUNCTION(minimum, <)
FUNCTION(maximum, >)

int main(){
    int n; cin >> n;
    vector<int> v(n);
    foreach(v, i) {
        io(v)[i];
    }
    int mn = INF;
    int mx = -INF;
    foreach(v, i) {
        minimum(mn, v[i]);
        maximum(mx, v[i]);
    }
    int ans = mx - mn;
    cout << toStr(Result =) << ' '<< ans;

 return 0;
}
```

#### macro definitions (#define, #undef)

* [#undef directive (C/C++) | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/hash-undef-directive-c-cpp?view=msvc-160)
    * Removes (undefines) a name previously created with #define.
    * #undef identifier

#### [Conditional inclusions (#ifdef, #ifndef, #if, #endif, #else and #elif)](https://en.cppreference.com/w/cpp/preprocessor/conditional)

#### Line control (#line)

#### Error directive (#error)

#### Source file inclusion (#include)

* C++ `include<>` v.s. `include ""` ?
    * In C++, the use of angle brackets (<>) and double quotes ("") with the #include directive serves to instruct the preprocessor on where to look for the included files, but they do so in slightly different ways. Understanding these differences can help you organize your project's include files more effectively and avoid common problems related to file inclusion.
    * `#include with Angle Brackets <>`
        * When you use angle brackets with the #include directive, you're telling the preprocessor to search for the included file in the system directories that the compiler uses for standard libraries, along with any directories you've specified with the -I option (or its equivalent) when invoking the compiler.
        * Syntax Example:
        ```cpp
        #include <iostream>
        #include <vector>
        ```
        * Usage:
            * Typically used for including standard library headers or third-party library headers that are located in standard system directories.
            * The search path for these headers does not normally include the directory containing the current file unless explicitly added as part of the compiler's include path settings.
    * `#include with Double Quotes ""`
        * When you use double quotes with the #include directive, the preprocessor searches for the included file starting in the directory containing the current file. If it doesn't find the file there, it then searches the paths that it would normally search for files included with angle brackets.
        * Syntax Example:
        ```cpp
        #include "my_header.h"
        #include "utils/my_utility.h"
        ```
        * Usage:
            * Typically used for including project-specific headers or local headers that are not part of the system directories.
            * Starts searching in the current directory of the source file which contains the #include statement, which makes it useful for project-specific or local headers.
        * Why the Distinction Matters
            * `Compilation Dependence`: Using double quotes can make your project easier to compile on different systems because it doesn't rely on specific configurations of the system's include paths. It's especially useful for project-specific headers that are not intended to be installed in the system's include directories.
            * `Encapsulation and Project Structure`: By using double quotes for your own headers and angle brackets for external libraries, you clearly distinguish between external dependencies and internal modules. This can help maintain a clean and well-organized code structure.
            * `Performance`: In large projects or projects with many directories, correctly using the include style can slightly improve compilation speed, as the preprocessor may find local headers faster with double quotes.
            * `Portability and Best Practices`: Using angle brackets for standard and third-party libraries reduces the risk of a name conflict with local headers, and using double quotes for local headers reinforces their locality and potential non-reusability.
    * Summary
        * Choose `#include "header.h"` when the header is part of your project or closely related code that you manage. Choose `#include <header.h>` for external libraries and the C++ Standard Library to leverage the standard paths set up in your development environment. This practice helps in maintaining clarity in code dependencies and in managing large codebases efficiently.

#### Pragma directive (#pragma)

* [once pragma | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/once?view=msvc-160)
    * Specifies that the compiler includes the header file only once, when compiling a source code file.
    * Syntax
        * `#pragma once`
    * Remarks
        * The use of #pragma once can reduce build times, as the compiler won't open and read the file again after the first #include of the file in the translation unit. It's called the multiple-include optimization. It has an effect similar to the include guard idiom, which uses preprocessor macro definitions to prevent multiple inclusions of the contents of the file. It also helps to prevent violations of the one definition rule: the requirement that all templates, types, functions, and objects have no more than one definition in your code.
        * We recommend the include guard idiom when code must be portable to compilers that don't implement the #pragma once directive, to maintain consistency with existing code, or when the multiple-include optimization is impossible. It can occur in complex projects when file system aliasing or aliased include paths prevent the compiler from identifying identical include files by canonical path.
    * [Header files (C++) | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/header-files-cpp?view=msvc-160#include-guards)
        * Typically, header files have an include guard or a #pragma once directive to ensure that they are not inserted multiple times into a single .cpp file.
    * [pragma once - Wikipedia](https://en.wikipedia.org/wiki/Pragma_once)
        * In the C and C++ programming languages, pragma once is a non-standard but widely supported preprocessor directive designed to cause the current source file to be included only once in a single compilation.[1] Thus, #pragma once serves the same purpose as include guards, but with several advantages, including: less code, avoidance of name clashes, and sometimes improvement in compilation speed.[2] On the other hand, #pragma once is not necessarily available in all compilers and its implementation is tricky and might not always be reliable.
    * [include guard - Wikipedia](https://en.wikipedia.org/wiki/Include_guard)
        * In the C and C++ programming languages, an #include guard, sometimes called a macro guard, header guard or file guard, is a particular construct used to avoid the problem of double inclusion when dealing with the include directive.
        * The C preprocessor processes directives of the form #include \<file> in a source file by locating the associated file on disk and transcluding ("including") its contents into a copy of the source file known as the translation unit, replacing the include directive in the process. The files included in this regard are generally header files, which typically contain declarations of functions and classes or structs. If certain C or C++ language constructs are defined twice, the resulting translation unit is invalid. #include guards prevent this erroneous construct from arising by the double inclusion mechanism.
        * The addition of #include guards to a header file is one way to make that file idempotent. Another construct to combat double inclusion is #pragma once, which is non-standard but nearly universally supported among C and C++ compilers.
    * [c++ - Is #pragma once a safe include guard? - Stack Overflow](https://stackoverflow.com/questions/787533/is-pragma-once-a-safe-include-guard)
* C++ `#pragma once` ?
    * The `#pragma once` directive is a preprocessor directive used in C++ to ensure that a header file is included only once in a single compilation, thus preventing multiple inclusions. This directive serves as an alternative to traditional include guards and helps to avoid problems associated with duplicate definitions and linking errors.
    * How `#pragma once` Works
        * When you place `#pragma once` at the top of a header file, it tells the compiler to include that file only once in the compilation process, no matter how many times it is included via #include statements in different parts of your code.
    * Example
        * Here's a simple example of how #pragma once is used in a header file:
        ```cpp
        // my_header.h
        #pragma once
        
        class MyClass {
        public:
            void doSomething();
        };
        ```
        * And then you might include this header file in multiple source files:
        ```cpp
        // main.cpp
        #include "my_header.h"
        #include "another_file.h"
        
        int main() {
            MyClass obj;
            obj.doSomething();
            return 0;
        }
        
        // another_file.h
        #include "my_header.h"
        ```
        * In this scenario, my_header.h is included in main.cpp directly and indirectly via another_file.h. The #pragma once directive ensures that the compiler processes the contents of my_header.h only once, thereby avoiding multiple definition errors and reducing compilation overhead.
    * Benefits of `#pragma once`
        * Simplicity: It is simpler to write and read as compared to traditional include guards. There is no need to come up with unique macro names for include guards.
        * Reduced Errors: Eliminates the possibility of mistakenly writing non-unique include guard names, which can lead to difficult-to-diagnose bugs.
        * Efficiency: Potentially increases compilation speed, as the compiler might optimize the inclusion check more effectively than with include guards.
    * Drawbacks
        * Portability: #pragma once is widely supported by most modern compilers (like GCC, Clang, MSVC), but it is not officially part of the C++ standard, which means theoretically it might not be supported by all compilers.
        * Filesystem Dependency: Some argue that its behavior can be problematic in complex build environments with symbolic links and multiple file systems, where the same physical file might be accessible through different paths.
    * Comparing `#pragma once` and Include Guards
        * Include guards are another way to prevent multiple inclusions, using `#ifndef, #define, and #endif` preprocessor commands:
        ```cpp
        // my_header.h
        #ifndef MY_HEADER_H
        #define MY_HEADER_H
        
        class MyClass {
        public:
            void doSomething();
        };
        
        #endif // MY_HEADER_H
        ```
        * Include guards have the advantage of being part of the standard C++ preprocessor specifications, ensuring compatibility with all standards-compliant C++ compilers. However, they can be more cumbersome to maintain and slightly slower in comparison to #pragma once, depending on the compiler's optimization capabilities.
    * Conclusion
        * While `#pragma once` offers a clean and efficient solution for preventing multiple inclusions of header files, it's important to be aware of its non-standard status and potential issues in complex build setups. For most modern development environments, however, `#pragma once` is a popular choice due to its simplicity and effectiveness.
* [SF.8: Use #include guards for all header files](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#sf8-use-include-guards-for-all-header-files)
    * `Reason` To avoid files being #included several times.
        * In order to avoid include guard collisions, do not just name the guard after the filename. Be sure to also include a key and good differentiator, such as the name of library or component the header file is part of.
    * `Example`
        ```c++
        // file foobar.h:
        #ifndef LIBRARY_FOOBAR_H
        #define LIBRARY_FOOBAR_H
        // ... declarations ...
        #endif // LIBRARY_FOOBAR_H
        ```
    * `Enforcement` Flag .h files without #include guards.
    * `Note` Some implementations offer vendor extensions like `#pragma once` as alternative to include guards. `It is not standard and it is not portable`. It injects the hosting machine’s filesystem semantics into your program, in addition to locking you down to a vendor. `Our recommendation is to write in ISO C++`: See [rule P.2](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rp-Cplusplus).

#### Predefined macro names

* [Predefined macros | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/predefined-macros?view=msvc-160)
* [SUCCEEDED macro (winerror.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/winerror/nf-winerror-succeeded)
    * Provides a generic test for success on any status value.
    * void SUCCEEDED(hr);
    * #define SUCCEEDED(hr) (((HRESULT)(hr)) &gt;= 0)
* [inject_statement import attribute | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/inject-statement?view=msvc-160)
    * Inserts its argument as source text into the type-library header.
    * #import type-library inject_statement( "source-text" )
* [named_guids import attribute | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/named-guids?view=msvc-160)
    * Tells the compiler to define and initialize GUID variables in the old style, of the form LIBID_MyLib, CLSID_MyCoClass, IID_MyInterface, and DIID_MyDispInterface.
    * #import type-library named_guids
* [rename_namespace import attribute | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/preprocessor/rename-namespace?view=msvc-160)
    * Renames the namespace that contains the contents of the type library.
    * #import type-library rename_namespace( "NewName" )

### [Expressions](https://en.cppreference.com/w/cpp/language/expressions)

* An expression is a sequence of operators and their operands, that specifies a computation.
* Expression evaluation may produce a result (e.g., evaluation of 2 + 2 produces the result 4) and may generate side-effects (e.g. evaluation of std::printf("%d",4) prints the character '4' on the standard output).
* Each C++ expression is characterized by two independent properties: A type and a value category.

#### General

##### [Value categories (lvalue, rvalue, xvalue)](https://en.cppreference.com/w/cpp/language/value_category)

* Each C++ expression (an operator with its operands, a literal, a variable name, etc.) is characterized by two independent properties: `a type and a value category`. Each expression has some non-reference type, and each expression belongs to exactly one of the `three primary value categories: prvalue, xvalue, and lvalue`.
* a glvalue (“generalized” lvalue) is an expression whose evaluation determines the identity of an object or function;
* a prvalue (“pure” rvalue) is an expression whose evaluation
    * computes the value of an operand of a built-in operator (such prvalue has no result object), or
    * initializes an object (such prvalue is said to have a result object).
    * The result object may be a variable, an object created by new-expression, a temporary created by temporary materialization, or a member thereof. Note that non-void discarded expressions have a result object (the materialized temporary). Also, every class and array prvalue has a result object except when it is the operand of decltype;
* an xvalue (an “eXpiring” value) is a glvalue that denotes an object whose resources can be reused;
* an lvalue (so-called, historically, because lvalues could appear on the left-hand side of an assignment expression) is a glvalue that is not an xvalue;
* an rvalue (so-called, historically, because rvalues could appear on the right-hand side of an assignment expression) is a prvalue or an xvalue.
* [Value Categories: Lvalues and Rvalues (C++) | Microsoft Learn](https://learn.microsoft.com/en-us/cpp/cpp/lvalues-and-rvalues-visual-cpp?view=msvc-170)
    * The C++17 standard defines expression value categories as follows:
        * A glvalue is an expression whose evaluation determines the identity of an object, bit-field, or function.
        * A prvalue is an expression whose evaluation initializes an object or a bit-field, or computes the value of the operand of an operator, as specified by the context in which it appears.
        * An xvalue is a glvalue that denotes an object or bit-field whose resources can be reused (usually because it is near the end of its lifetime). Example: Certain kinds of expressions involving rvalue references (8.3.2) yield xvalues, such as a call to a function whose return type is an rvalue reference or a cast to an rvalue reference type.
        * An lvalue is a glvalue that is not an xvalue.
        * An rvalue is a prvalue or an xvalue.
    * The following diagram illustrates the relationships between the categories:
    * ![image](https://user-images.githubusercontent.com/34557994/205634478-11d7da0d-53b8-46d9-8b62-4b97c0fa3e30.png)
    * `An lvalue has an address that your program can access.` Examples of lvalue expressions include variable names, including const variables, array elements, function calls that return an lvalue reference, bit-fields, unions, and class members.
    * `A prvalue expression has no address that is accessible by your program.` Examples of prvalue expressions include literals, function calls that return a non-reference type, and temporary objects that are created during expression evaluation but accessible only by the compiler.
    * `An xvalue expression has an address that no longer accessible by your program but can be used to initialize an rvalue reference, which provides access to the expression.` Examples include function calls that return an rvalue reference, and the array subscript, member and pointer to member expressions where the array or object is an rvalue reference.

#### Literals

* Literals are the tokens of a C++ program that represent constant values embedded in the source code.
	
##### [integer literals](https://en.cppreference.com/w/cpp/language/integer_literal) 

* integer literals are decimal, octal, hexadecimal or binary numbers of integer type.
* Allows values of integer type to be used in expressions directly.
* (no suffix)	
    * int
    * long int
    * long long int (since C++11)
* u or U	
    * unsigned int
    * unsigned long int
    * unsigned long long int (since C++11)
* l or L	
    * long int
    * long long int (since C++11)
* both l/L and u/U	
    * unsigned long int
    * unsigned long long int (since C++11)
* ll or LL	
    * long long int (since C++11)
* both ll/LL and u/U	
    * unsigned long long int (since C++11)
* z or Z	
    * the signed version of std::size_t (since C++23)
* both z/Z and u/U	
    * std::size_t (since C++23)

##### [character literals](https://en.cppreference.com/w/cpp/language/character_literal) 

* character literals are individual characters of type
* char or wchar_t
* char16_t or char32_t(since C++11)
* char8_t(since C++20)

###### [Escape sequences](https://en.cppreference.com/w/cpp/language/escape)

* Escape sequences are used to represent certain special characters within string literals and character literals.
* <img width="758" alt="截屏2022-12-30 下午10 33 42" src="https://user-images.githubusercontent.com/34557994/210066019-927ccd7a-35d9-4041-b441-867f91cfe921.png">

##### [floating-point literals](https://en.cppreference.com/w/cpp/language/floating_literal) 

* floating-point literals are values of type float, double, or long double
* suffix, if present, is one of f, F, l, or L. The suffix determines the type of the floating-point literal:
    * (no suffix) defines double
    * f F defines float
    * l L defines long double
    * Optional single quotes (') may be inserted between the digits as a separator; they are ignored during compilation.(since C++14)
* [为什么将 0.1f 改为 0 会使性能降低 10 倍？](https://mp.weixin.qq.com/s/bMacxnC_JBuqFDz8k2fp3w)
    * http://cenalulu.github.io/linux/about-denormalized-float-number/
	
##### [string literals](https://en.cppreference.com/w/cpp/language/string_literal)

* string literals are sequences of characters of type
* const char[] or const wchar_t[]
* const char16_t[] or const char32_t[](since C++11)
* const char8_t[](since C++20)

##### [boolean literals](https://en.cppreference.com/w/cpp/language/bool_literal)

* boolean literals are values of type bool, that is true and false

##### [nullptr](https://en.cppreference.com/w/cpp/language/nullptr)

* nullptr is the pointer literal which specifies a null pointer value

##### [user-defined literals](https://en.cppreference.com/w/cpp/language/user_literal)

* user-defined literals are constant values of user-specified type

##### MISC

* [NL.11: Make literals readable](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#nl11-make-literals-readable)
    * Reason Readability.
    * Example Use digit separators to avoid long strings of digits
    ```c++
    auto c = 299'792'458; // m/s2
    auto q2 = 0b0000'1111'0000'0000;
    auto ss_number = 123'456'7890;
    ```
    * Example Use literal suffixes where clarification is needed
    ```c++
    auto hello = "Hello!"s; // a std::string
    auto world = "world";   // a C-style string
    auto interval = 100ms;  // using <chrono>
    ```
    * Note Literals should not be sprinkled all over the code as “magic constants”, but it is still a good idea to make them readable where they are defined. It is easy to make a typo in a long string of integers.
    * Enforcement Flag long digit sequences. The trouble is to define “long”; maybe 7.
* [SF.7: Don’t write using namespace at global scope in a header file](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#sf7-dont-write-using-namespace-at-global-scope-in-a-header-file)
    * `Reason` Doing so takes away an #includer’s ability to effectively disambiguate and to use alternatives. It also makes #included headers order-dependent as they might have different meaning when included in different orders.
    * `Note` An exception is using namespace std::literals;. This is necessary to use string literals in header files and given the rules - users are required to name their own UDLs operator""_x - they will not collide with the standard library.
* [Constants/Literals](https://www.tutorialspoint.com/cplusplus/cpp_constants_literals.htm)

#### [Operators](https://en.cppreference.com/w/cpp/language/expressions#Operators)

* [五分钟小知识：为什么说 ++i 的效率比 i++ 高？](https://mp.weixin.qq.com/s/___R-0mc7zezAEVG-1-b5w)
  * 对于内置类型，前置和后置自增或者自减在编译器优化的情况下，两者并无多大差别，而对于自定义类型，如无特别需要，人们似乎更加偏爱前置自增或自减，因为后置自增常常会产生临时对象。
* [Modulo Operator (%) in C/C++ with Examples - GeeksforGeeks](https://www.geeksforgeeks.org/modulo-operator-in-c-cpp-with-examples/)
	* Restrictions of the modulo operator: 
		* 1. The % operator cannot be applied to floating-point numbers i.e float or double. If you try to use the modulo operator with floating-point constants or variables, the compiler will produce a error
		* 2. The sign of the result for modulo operator is machine-dependent for negative operands, as the action takes as a result of underflow or overflow. 
			* -3 % 4 = -3
			* 4 % -2 = 0
			* -3 % -4 = -3

##### [new expression](https://en.cppreference.com/w/cpp/language/new)

* Creates and initializes objects with dynamic storage duration, that is, objects whose lifetime is not necessarily limited by the scope in which they were created.
* Placement new
    * If placement-params are provided, they are passed to the allocation function as additional arguments. Such allocation functions are known as "placement new", after the standard allocation function void* operator new(std::size_t, void*), which simply returns its second argument unchanged. This is used to construct objects in allocated storage:
    ```c++
    // within any block scope...
    {
        // Statically allocate the storage with automatic storage duration
        // which is large enough for any object of type `T`.
        alignas(T) unsigned char buf[sizeof(T)];

        T* tptr = new(buf) T; // Construct a `T` object, placing it directly into your 
                              // pre-allocated storage at memory address `buf`.

        tptr->~T();           // You must **manually** call the object's destructor
                              // if its side effects is depended by the program.
    }                         // Leaving this block scope automatically deallocates `buf`.
    ```
    * Note: this functionality is encapsulated by the member functions of the Allocator classes.
* Memory leaks
    * The objects created by new-expressions (objects with dynamic storage duration) persist until the pointer returned by the new-expression is used in a matching delete-expression. If the original value of pointer is lost, the object becomes unreachable and cannot be deallocated: a memory leak occurs.
    * To simplify management of dynamically-allocated objects, the result of a new-expression is often stored in a smart pointer: std::auto_ptr (until C++17)std::unique_ptr, or std::shared_ptr (since C++11). These pointers guarantee that the delete expression is executed in the situations shown above.
* [Placement new operator in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/placement-new-operator-cpp/)
	* Advantages of placement new operator over new operator
		* The address of memory allocation is known before hand.
		* Useful when building a memory pool, a garbage collector or simply when performance and exception safety are paramount.
		* There’s no danger of allocation failure since the memory has already been allocated, and constructing an object on a pre-allocated buffer takes less time.
		* This feature becomes useful while working in an environment with limited resources.

##### [alignof operator](https://en.cppreference.com/w/cpp/language/alignof)

* Queries alignment requirements of a type.
* Syntax
    * `alignof( type-id )`
    * Returns a value of type std::size_t.
* Explanation
    * Returns the alignment, in bytes, required for any instance of the type indicated by type-id, which is either complete object type, an array type whose element type is complete, or a reference type to one of those types.
    * If the type is reference type, the operator returns the alignment of referenced type; if the type is array type, alignment requirement of the element type is returned.
```c++
#include <iostream>
 
struct Foo
{
    int   i;
    float f;
    char  c;
};
 
// Note: `alignas(alignof(long double))` below can be simplified to simply 
// `alignas(long double)` if desired.
struct alignas(alignof(long double)) Foo2
{
    // put your definition here
}; 
 
struct Empty {};
 
struct alignas(64) Empty64 {};
 
int main()
{
    std::cout << "Alignment of"  "\n"
        "- char            : " << alignof(char)    << "\n"
        "- pointer         : " << alignof(int*)    << "\n"
        "- class Foo       : " << alignof(Foo)     << "\n"
        "- class Foo2      : " << alignof(Foo2)    << "\n"
        "- empty class     : " << alignof(Empty)   << "\n"
        "- empty class\n"
        "  with alignas(64): " << alignof(Empty64) << "\n";
}
/*
Alignment of
- char            : 1
- pointer         : 8
- class Foo       : 4
- class Foo2      : 16
- empty class     : 1
- empty class
  with alignas(64): 64
*/
```

##### [typeid operator](https://en.cppreference.com/w/cpp/language/typeid)

* Queries information of a type.
* Used where the dynamic type of a polymorphic object must be known and for static type identification.
* There is no guarantee that the same std::type_info instance will be referred to by all evaluations of the typeid expression on the same type, although they would compare equal, std::type_info::hash_code of those type_info objects would be identical, as would be their std::type_index.

##### [operator overloading](https://en.cppreference.com/w/cpp/language/operators)

* Customizes the C++ operators for operands of user-defined types.
* Special operators
    * `static_cast` converts one type to another related type
    * `dynamic_cast` converts within inheritance hierarchies
    * `const_cast` adds or removes cv-qualifiers
    * `reinterpret_cast` converts type to unrelated type
    * `C-style cast` converts one type to another by a mix of static_cast, const_cast, and reinterpret_cast
    * `new` creates objects with dynamic storage duration
    * `delete` destructs objects previously created by the new expression and releases obtained memory area
    * `sizeof` queries the size of a type
    * `sizeof...` queries the size of a parameter pack (since C++11)
    * `typeid` queries the type information of a type
    * `noexcept` checks if an expression can throw an exception (since C++11)
    * `alignof` queries alignment requirements of a type (since C++11)
* Example
```c++
#include <iostream>
 
class Fraction
{
    // or C++17's std::gcd
    constexpr int gcd(int a, int b) { return b == 0 ? a : gcd(b, a % b); }
 
    int n, d;
public:
    constexpr Fraction(int n, int d = 1) : n(n/gcd(n, d)), d(d/gcd(n, d)) {}
 
    constexpr int num() const { return n; }
    constexpr int den() const { return d; }
 
    constexpr Fraction& operator*=(const Fraction& rhs)
    {
        int new_n = n * rhs.n / gcd(n * rhs.n, d * rhs.d);
        d = d * rhs.d / gcd(n * rhs.n, d * rhs.d);
        n = new_n;
        return *this;
    }
};
 
std::ostream& operator<<(std::ostream& out, const Fraction& f)
{
   return out << f.num() << '/' << f.den() ;
}
 
constexpr bool operator==(const Fraction& lhs, const Fraction& rhs)
{
    return lhs.num() == rhs.num() && lhs.den() == rhs.den();
}
 
constexpr bool operator!=(const Fraction& lhs, const Fraction& rhs)
{
    return !(lhs == rhs);
}
 
constexpr Fraction operator*(Fraction lhs, const Fraction& rhs)
{
    return lhs *= rhs;
}
 
int main()
{
    constexpr Fraction f1{3, 8}, f2{1, 2}, f3{10, 2};
    std::cout << f1 << " * " << f2 << " = " << f1 * f2 << '\n'
              << f2 << " * " << f3 << " = " << f2 * f3 << '\n'
              <<  2 << " * " << f1 << " = " <<  2 * f1 << '\n';
    static_assert(f3 == f2 * 10);
}
/*
3/8 * 1/2 = 3/16
1/2 * 5/1 = 5/2
2 * 3/8 = 3/4
*/
```

###### Syntax

* `Overloaded operators are functions with special function names`:
    * operator op	(1)	
    * operator type	(2)	
    * operator new  (3)	
    * operator new []	
    * operator delete   (4)	
    * operator delete []	
    * operator "" suffix-identifier	(5)	(since C++11)
    * operator co_await	(6)	(since C++20)
    * op	-	any of the following operators:`+ - * / % ^ & | ~ ! = < > += -= *= /= %= ^= &= |= << >> >>= <<= == != <= >= <=> (since C++20) && || ++ -- , ->* -> ( ) [ ]`
    * 1) overloaded operator;
    * 2) user-defined conversion function;
    * 3) allocation function;
    * 4) deallocation function;
    * 5) user-defined literal;
    * 6) overloaded co_await operator for use in co_await expressions.

###### Overloaded operators

* When an operator appears in an expression, and at least one of its operands has a class type or an enumeration type, then overload resolution is used to determine the user-defined function to be called among all the functions whose signatures match the following:
* ...

###### Canonical implementations

* Besides the restrictions above, the language puts no other constraints on what the overloaded operators do, or on the return type (it does not participate in overload resolution), but in general, overloaded operators are expected to behave as similar as possible to the built-in operators: operator+ is expected to add, rather than multiply its arguments, operator= is expected to assign, etc. The related operators are expected to behave similarly (operator+ and operator+= do the same addition-like operation). The return types are limited by the expressions in which the operator is expected to be used: for example, assignment operators return by reference to make it possible to write a = b = c = d, because the built-in operators allow that.
* Commonly overloaded operators have the following typical, canonical forms:[1]

# 
Assignment operator

* The assignment operator (operator=) has special properties: see copy assignment and move assignment for details.
* The canonical copy-assignment operator is expected to [perform no action on self-assignment](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#c62-make-copy-assignment-safe-for-self-assignment), and to return the lhs by reference:
```c++
// copy assignment
T& operator=(const T& other)
{
    // Guard self assignment
    if (this == &other)
        return *this;

    // assume *this manages a reusable resource, such as a heap-allocated buffer mArray
    if (size != other.size)           // resource in *this cannot be reused
    {
        delete[] mArray;              // release resource in *this
        mArray = nullptr;
        size = 0;                     // preserve invariants in case next line throws
        mArray = new int[other.size]; // allocate resource in *this
        size = other.size;
    } 

    std::copy(other.mArray, other.mArray + other.size, mArray);
    return *this;
}
```
* The canonical move assignment is expected to [leave the moved-from object in valid state](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#c64-a-move-operation-should-move-and-leave-its-source-in-a-valid-state) (that is, a state with class invariants intact), and either [do nothing](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#c65-make-move-assignment-safe-for-self-assignment) or at least leave the object in a valid state on self-assignment, and return the lhs by reference to non-const, and be noexcept:
```c++
// move assignment
T& operator=(T&& other) noexcept
{
    // Guard self assignment
    if (this == &other)
        return *this; // delete[]/size=0 would also be ok

    delete[] mArray;                               // release resource in *this
    mArray = std::exchange(other.mArray, nullptr); // leave other in valid state
    size = std::exchange(other.size, 0);
    return *this;
}
```
* In those situations where copy assignment `cannot benefit from resource reuse` (it does not manage a heap-allocated array and does not have a (possibly transitive) member that does, such as a member std::vector or std::string), there is a popular convenient shorthand: `the copy-and-swap assignment operator`, which takes its parameter by value (thus working as both copy- and move-assignment depending on the value category of the argument), swaps with the parameter, and lets the destructor clean it up.
```c++
// copy assignment (copy-and-swap idiom)
T& T::operator=(T other) noexcept // call copy or move constructor to construct other
{
    std::swap(size, other.size); // exchange resources between *this and other
    std::swap(mArray, other.mArray);
    return *this;
} // destructor of other is called to release the resources formerly managed by *this
```
* This form automatically provides [strong exception guarantee](https://en.cppreference.com/w/cpp/language/exceptions#Exception_safety), but prohibits resource reuse.

###### MISC

* [Operator Overloading in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/operator-overloading-c/)
    * What is the difference between operator functions and normal functions? 
        * Operator functions are the same as normal functions. The only differences are, that the name of an operator function is always the operator keyword followed by the symbol of the operator and operator functions are called when the corresponding operator is used. 
    * Can we overload all operators? 
        * Almost all operators can be overloaded except a few. Following is the list of operators that cannot be overloaded. 
            * sizeof
            * typeid
            * Scope resolution (::)
            * Class member access operators (.(dot), .* (pointer to member operator))
            * Ternary or conditional (?:)
    * Important points about operator overloading 
        * 1) For operator overloading to work, at least `one` of the operands must be a `user-defined class object`.
        * 2) Assignment Operator: Compiler automatically creates a `default assignment operator` with every class. The default assignment operator does assign all members of the right side to the left side and works fine in most cases (this behaviour is the same as the `copy constructor`). See [this](https://www.geeksforgeeks.org/assignment-operator-overloading-in-c/) for more details. 
        * 3) Conversion Operator: We can also write conversion operators that can be used to convert one type to another type. 
            * Overloaded conversion operators must be a member method. Other operators can either be the member method or the global method.
        ```c++
        #include <iostream>
        using namespace std;
        class Fraction
        {
        private:
            int num, den;
        public:
            Fraction(int n, int d) { num = n; den = d; }

            // Conversion operator: return float value of fraction
            operator float() const {
                return float(num) / float(den);
            }
        };

        int main() {
            Fraction f(2, 5);
            float val = f;
            cout << val << '\n';    // 0.4
            return 0;
        }
        ```
        * 4) Any constructor that can be called with a single argument works as a conversion constructor, which means it can also be used for implicit conversion to the class being constructed.  

#### [Conversions](https://en.cppreference.com/w/cpp/language/expressions#Conversions)

* Type casting
    * Unrestricted explicit type-casting allows to convert any pointer into any other pointer type, independently of the types they point to. The subsequent call to member result will produce either a run-time error or some other unexpected results.
    * In order to control these types of conversions between classes, we have four specific casting operators: dynamic_cast, reinterpret_cast, static_cast and const_cast. Their format is to follow the new type enclosed between angle-brackets (<>) and immediately after, the expression to be converted between parentheses.
        * dynamic_cast <new_type> (expression)
        * reinterpret_cast <new_type> (expression)
        * static_cast <new_type> (expression)
        * const_cast <new_type> (expression)
    * The traditional type-casting equivalents to these expressions would be:
        * (new_type) expression
        * new_type (expression)
* but each one with its own special characteristics
* [如何攻克 C++ 中复杂的类型转换？](https://mp.weixin.qq.com/s/lJiva3BUJXUV0cpX1dOe2Q)
    * https://github.com/yingyulou
* [详解 C++ 的隐式类型转换与函数重载！](https://mp.weixin.qq.com/s/S_1KPn_GWJ7hmLH19Dajfg)
    * https://github.com/yingyulou
* [谁说 C++ 的强制类型转换很难懂？](https://mp.weixin.qq.com/s/q3iwtvqMSp6lNC_ZR_SP6A)
    * https://github.com/yingyulou

##### [Implicit conversion](https://en.cppreference.com/w/cpp/language/implicit_conversion)

* [C.164: Avoid implicit conversion operators](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c164-avoid-implicit-conversion-operators)
    * Reason 
        * Implicit conversions can be essential (e.g., double to int) but often cause surprises (e.g., String to C-style string).
    * Note 
        * Prefer explicitly named conversions until a serious need is demonstrated. By “serious need” we mean a reason that is fundamental in the application domain (such as an integer to complex number conversion) and frequently needed. Do not introduce implicit conversions (through conversion operators or non-explicit constructors) just to gain a minor convenience.

##### [const_cast conversion](https://en.cppreference.com/w/cpp/language/const_cast)

* `adds or removes cv-qualifiers`
* Converts between types with different cv-qualification.
* Syntax
    * `const_cast < new_type > ( expression )`
* Returns a value of type new_type.
* Explanation
    * Only the following conversions can be done with const_cast. In particular, only const_cast may be used to cast away (remove) constness or volatility.
        1) Two possibly multilevel pointers to the same type may be converted between each other, regardless of cv-qualifiers at each level.
        2) lvalue of any type T may be converted to a lvalue or rvalue reference to the same type T, more or less cv-qualified. Likewise, a prvalue of class type or an xvalue of any type may be converted to a more or less cv-qualified rvalue reference. The result of a reference const_cast refers to the original object if expression is a glvalue and to the materialized temporary otherwise (since C++17).
        3) Same rules apply to possibly multilevel pointers to data members and possibly multilevel pointers to arrays of known and unknown bound (arrays to cv-qualified elements are considered to be cv-qualified themselves) (since C++17)
        4) null pointer value may be converted to the null pointer value of new_type
    * As with all cast expressions, the result is:
        * an lvalue if new_type is an lvalue reference type or an rvalue reference to function type;
        * an xvalue if new_type is an rvalue reference to 
        type;
        * a prvalue otherwise.
```c++
#include <iostream>
 
struct type
{
    int i;
 
    type(): i(3) {}
 
    void f(int v) const
    {
        // this->i = v;                 // compile error: this is a pointer to const
        const_cast<type*>(this)->i = v; // OK as long as the type object isn't const
    }
};
 
int main() 
{
    int i = 3;                 // i is not declared const
    const int& rci = i; 
    const_cast<int&>(rci) = 4; // OK: modifies i
    std::cout << "i = " << i << '\n';
 
    type t; // if this was const type t, then t.f(4) would be undefined behavior
    t.f(4);
    std::cout << "type::i = " << t.i << '\n';
 
    const int j = 3; // j is declared const
    [[maybe_unused]]
    int* pj = const_cast<int*>(&j);
    // *pj = 4;      // undefined behavior
 
    [[maybe_unused]]
    void (type::* pmf)(int) const = &type::f; // pointer to member function
    // const_cast<void(type::*)(int)>(pmf);   // compile error: const_cast does
                                              // not work on function pointers
}
/*
i = 4
type::i = 4
*/
```
* [const_cast examples](https://www.geeksforgeeks.org/const_cast-in-c-type-casting-operators/)
    * C++ supports following 4 types of casting operators:
        1. const_cast
        2. static_cast
        3. dynamic_cast
        4. reinterpret_cast
* [c++ - Is const_cast<const Type*> ever useful? - Stack Overflow](https://stackoverflow.com/questions/5324256/is-const-castconst-type-ever-useful)
    * const_cast, despite its name, is not specific to const; it works with cv-qualifiers which effectively comprises both const and volatile.
    * While adding such a qualifier is allowed transparently, removing any requires a const_cast.
    * Therefore, in the example you give:
    ```c++
    char* p = /**/;
    char const* q = const_cast<char const*>(p);
    ```
    * the presence of the const_cast is spurious (I personally think it obscures the syntax).
    * But you can wish to remove volatile, in which case you'll need it:
    ```c++
    char const volatile* p = /**/;
    char const* q = const_cast<char const*>(p);
    ```
    * This could appear, for example, in driver code.
* [types - casting non const to const in c++ - Stack Overflow](https://stackoverflow.com/questions/5853833/casting-non-const-to-const-in-c)
    * const_cast can be used in order remove or add constness to an object. This can be useful when you want to call a specific overload.
    ```c++
    #include <iostream>

    class foo {
        int i;
    public:
        foo(int i) : i(i) { }

        int bar() const {
            return i;    
        }

        int bar() { // not const
            i++;
            return const_cast<const foo*>(this)->bar(); 
        }
    };

    int main() 
    {
        foo my_foo(10);

        std::cout << my_foo.bar() << '\n';  // 11
        std::cout << my_foo.bar() << '\n';  // 12
    }
    ```

##### [static_cast conversion](https://en.cppreference.com/w/cpp/language/static_cast)

* converts one type to another related type
* Converts between types using a combination of implicit and user-defined conversions.

##### [reinterpret_cast conversion](https://en.cppreference.com/w/cpp/language/reinterpret_cast)

* converts type to unrelated type
* Converts between types by reinterpreting the underlying bit pattern.
* Unlike `static_cast`, but like `const_cast`, the `reinterpret_cast` expression does not compile to any CPU instructions (except when converting between integers and pointers or on obscure architectures where pointer representation depends on its type). It is purely a compile-time directive which instructs the compiler to treat expression as if it had the type new-type.
* Example
    * Demonstrates some uses of reinterpret_cast:
```c++
#include <cstdint>
#include <cassert>
#include <iostream>
 
int f() { return 42; }
 
int main()
{
    int i = 7;
 
    // pointer to integer and back
    std::uintptr_t v1 = reinterpret_cast<std::uintptr_t>(&i); // static_cast is an error
    std::cout << "The value of &i is " << std::showbase << std::hex << v1 << '\n';
    int* p1 = reinterpret_cast<int*>(v1);
    assert(p1 == &i);
 
    // pointer to function to another and back
    void(*fp1)() = reinterpret_cast<void(*)()>(f);
    // fp1(); undefined behavior
    int(*fp2)() = reinterpret_cast<int(*)()>(fp1);
    std::cout << std::dec << fp2() << '\n'; // safe
 
    // type aliasing through pointer
    char* p2 = reinterpret_cast<char*>(&i);
    std::cout << (p2[0] == '\x7' ? "This system is little-endian\n"
                                 : "This system is big-endian\n");
 
    // type aliasing through reference
    reinterpret_cast<unsigned int&>(i) = 42;
    std::cout << i << '\n';
 
    [[maybe_unused]] const int &const_iref = i;
    // int &iref = reinterpret_cast<int&>(
    //     const_iref); // compiler error - can't get rid of const
    // Must use const_cast instead: int &iref = const_cast<int&>(const_iref);
}
/*
The value of &i is 0x7fff352c3580
42
This system is little-endian
42
*/
```

###### MISC

* How to convert little-endian binary encoded integer to integer ?
    * [Little and Big Endian Mystery - GeeksforGeeks](https://www.geeksforgeeks.org/little-and-big-endian-mystery/)
    * ![image](https://user-images.githubusercontent.com/34557994/210064770-2b7af10d-1875-4520-af69-d7927dde9f8f.png)
    * [turn array of HEX into one number - Using Arduino / Programming Questions - Arduino Forum](https://forum.arduino.cc/t/turn-array-of-hex-into-one-number/688986)
    * [How to convert a 4-byte hexadecimal sequence in a little-endian architecture into decimal – Today I Learned… in Code](https://www.tilcode.com/how-to-convert-a-4-byte-hexadecimal-sequence-in-a-little-endian-architecture-into-decimal/)
```c++
#include <iostream>

uint32_t get_uint32_from_char_buffer(const char* buffer)
{
    return *(uint32_t*)buffer;
}

uint32_t _get_uint32_from_char_buffer(const char* buffer)
{
    return *reinterpret_cast<const uint32_t*>(buffer);
}

// uint32_t _get_uint32_from_char_buffer(const char* buffer)
// {
//     // error: invalid 'static_cast' from type 'const char*' to type 'const uint32_t*' {aka 'const unsigned int*'}
//     return *static_cast<const uint32_t*>(buffer);
// }

int main()
{
    // unsigned little-endian binary encoded integer
    char s[5] = {'\x01', '\x01', '\x00', '\x00'};

    // 257
    std::cout << get_uint32_from_char_buffer(s) << '\n';
    std::cout << _get_uint32_from_char_buffer(s) << '\n';

    return 0;
}
```
* How to convert char* to struct ?
```c++
#include <iostream>
#include <sstream>

struct message_header
{
    char type;
    char symbol[3];

    std::string get_symbol() const
    {
        return std::string(symbol, 3);
    }

    std::string to_string() const
    {
        std::stringstream ss{};
        ss << "type=" << type << "|symbol=" << get_symbol();
        return ss.str();
    }
};

void decode_message(const char* message)
{
    auto header = reinterpret_cast<const message_header*>(message);
    std::cout << header->to_string() << '\n';
}

int main()
{
    char s[5] = {'\x41', '\x41', '\x42', '\x30'};

    decode_message(s);  // type=A|symbol=AB0

    return 0;
}
```

##### [dynamic_cast conversion](https://en.cppreference.com/w/cpp/language/dynamic_cast)

* converts within inheritance hierarchies
* Safely converts pointers and references to classes up, down, and sideways along the inheritance hierarchy.
* If the cast is successful, dynamic_cast returns a value of type new-type. If the cast fails and new-type is a pointer type, it returns a null pointer of that type. If the cast fails and new-type is a reference type, it throws an exception that matches a handler of type std::bad_cast.
```c++
#include <iostream>
#include <vector>
#include <string>
using namespace std;

class Spell {
private:
    string scrollName;
public:
    Spell(): scrollName("") { }
    Spell(string name): scrollName(name) { }
    virtual ~Spell() { }
    string revealScrollName() {
        return scrollName;
    }
};

class Fireball : public Spell {
private: int power;
public:
    Fireball(int power): power(power) { }
    void revealFirepower(){
        cout << "Fireball: " << power << endl;
    }
};

class Frostbite : public Spell {
private: int power;
public:
    Frostbite(int power): power(power) { }
    void revealFrostpower(){
        cout << "Frostbite: " << power << endl;
    }
};

class Thunderstorm : public Spell {
private: int power;
public:
    Thunderstorm(int power): power(power) { }
    void revealThunderpower(){
        cout << "Thunderstorm: " << power << endl;
    }
};

class Waterbolt : public Spell {
private: int power;
public:
    Waterbolt(int power): power(power) { }
    void revealWaterpower(){
        cout << "Waterbolt: " << power << endl;
    }
};

class SpellJournal {
public:
    static string journal;
    static string read() {
        return journal;
    }
};
string SpellJournal::journal = "";

void counterspell(Spell *spell)
{
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    if (auto* fb = dynamic_cast<Fireball*>(spell)) {
        fb->revealFirepower();
    }
    else if (auto* fb = dynamic_cast<Frostbite*>(spell)) {
        fb->revealFrostpower();
    }
    else if (auto* ts = dynamic_cast<Thunderstorm*>(spell)) {
        ts->revealThunderpower();
    }
    else if (auto* wb = dynamic_cast<Waterbolt*>(spell)) {
        wb->revealWaterpower();
    }
    else {
        const auto spellN = spell->revealScrollName();
        const auto spellJ = SpellJournal::read();
        const auto nSpellN = spellN.length();
        const auto nSpellJ = spellJ.length();
        // pay attention to the size of vector
        vector<vector<int> > vResult(nSpellN + 1, vector<int>(nSpellJ + 1, 0));

        for (auto i = 1; i <= nSpellN; ++ i) {
            for (auto j = 1; j <= nSpellJ; ++ j) {
                if (spellN.at(i - 1) == spellJ.at(j - 1)) {
                    vResult[i][j] = vResult[i - 1][j - 1] + 1;
                }
                else {
                    vResult[i][j] = max(vResult[i - 1][j], vResult[i][j - 1]);
                }
            }
        }

        cout << vResult[nSpellN][nSpellJ] << endl;
    }
}

class Wizard {
public:
    Spell *cast()
    {
        Spell *spell;
        string s; cin >> s;
        int power; cin >> power;
        if(s == "fire") {
            spell = new Fireball(power);
        }
        else if(s == "frost") {
            spell = new Frostbite(power);
        }
        else if(s == "water") {
            spell = new Waterbolt(power);
        }
        else if(s == "thunder") {
            spell = new Thunderstorm(power);
        }
        else {
            spell = new Spell(s);
            cin >> SpellJournal::journal;
        }
        return spell;
    }
};

int main() {
    int T;
    cin >> T;
    Wizard Arawn;
    while(T--) {
        Spell *spell = Arawn.cast();
        counterspell(spell);
    }
    return 0;
}
```
* [C++ equivalent of instanceof](https://www.tutorialspoint.com/cplusplus-equivalent-of-instanceof)
    * C++ has no direct method to check one object is an instance of some class type or not. In Java, we can get this kind of facility.
    * In C++11, we can find one item called `is_base_of<Base, T>`. This will check if the given class is a base of the given object or not. But, this does not verify whether the given class instance uses that function. 
    * The nearest possible functionality similar to "instanceof" can be achieved using `dynamic_cast <new-type>(expression)`. This tries to covert the given value into the specified type and returns the result. if the cast is unsuccessful this returns a null pointer. This works only for polymorphic pointers and when compiler RTTI is enabled.
```c++
#include <iostream>
using namespace std;

template<typename Base, typename T>
inline bool instanceof(const T *ptr) 
{
   return dynamic_cast<const Base*>(ptr) != nullptr;
}

class Parent 
{
public:
   virtual ~Parent() {}
   virtual void foo () { std::cout << "Parent"; }
};

class Child : public Parent 
{
public:
   virtual void foo() { std::cout << "Child"; }
};

class AnotherClass{};

int main() 
{
   Parent p;
   Child c;
   AnotherClass a;

   Parent *ptr1 = &p;
   Child *ptr2 = &c;
   AnotherClass *ptr3 = &a;

   if(instanceof<Parent>(ptr1)) {
      cout << "p is an instance of the class Parent" << endl;
   } else {
      cout << "p is not an instance of the class Parent" << endl;
   }

   if(instanceof<Parent>(ptr2)) {
      cout << "c is an instance of the class Parent" << endl;
   } else {
      cout << "c is not an instance of the class Parent" << endl;
   }

   if(instanceof<Child>(ptr2)) {
      cout << "c is an instance of the class Child" << endl;
   } else {
      cout << "c is not an instance of the class Child" << endl;
   }

   if(instanceof<Child>(ptr1)) {
      cout << "p is an instance of the class Child" << endl;
   } else {
      cout << "p is not an instance of the class Child" << endl;
   }

   if(instanceof<AnotherClass>(ptr2)) {
      cout << "c is an instance of AnotherClass class" << endl;
   } else {
      cout << "c is not an instance of AnotherClass class" << endl;
   }
}
/*
p is an instance of the class Parent
c is an instance of the class Parent
c is an instance of the class Child
p is not an instance of the class Child
c is not an instance of AnotherClass class
*/
```

##### [Explicit conversions (T)a, T(a)](https://en.cppreference.com/w/cpp/language/explicit_cast)

* C-style cast converts one type to another by a mix of static_cast, const_cast, and reinterpret_cast
* Converts between types using a combination of explicit and implicit conversions.
* Syntax
    * `( new-type ) expression`	(1)	
    * `new-type ( expression-list(optional) )`	(2)	
    * `new-type { expression-list(optional) }`	(3)	(since C++11)
    * `template-name ( expression-list(optional) )`	(4)	(since C++17)
    * `template-name { expression-list(optional) }`	(5)	(since C++17)
    * `auto ( expression )`	(6)	(since C++23)
    * `auto { expression }`	(7)	(since C++23)
    * Returns a value of type new-type.
* Example
```c++
#include <cassert>
#include <iostream>
 
double f = 3.14;
unsigned int n1 = (unsigned int)f; // C-style cast
unsigned int n2 = unsigned(f);     // function-style cast
 
class C1;
class C2;
C2* foo(C1* p)
{
    return (C2*)p; // casts incomplete type to incomplete type
}
 
void cpp23_decay_copy_demo()
{
    auto inc_print = [](int& x, const int& y)
    {
        ++x;
        std::cout << "x:" << x << ", y:" << y << '\n';
    };
 
    int p{1};
    inc_print(p, p); // prints x:2 y:2, because param y here is an alias of p
    int q{1};
    inc_print(q, auto{q}); // prints x:2 y:1, auto{q} (C++23) casts to prvalue,
                           // so the param y is a copy of q (not an alias of q)
}
 
// In this example, C-style cast is interpreted as static_cast
// even though it would work as reinterpret_cast
struct A {};
struct I1 : A {};
struct I2 : A {};
struct D : I1, I2 {};
 
int main()
{
    D* d = nullptr;
//  A* a = (A*)d;                   // compile-time error
    A* a = reinterpret_cast<A*>(d); // this compiles
    assert(a == nullptr);
 
    cpp23_decay_copy_demo();
}
/*
x:2 y:2
x:2 y:1
*/
```

### [Declarations](https://en.cppreference.com/w/cpp/language/declarations)

* Declarations are how names are introduced (or re-introduced) into the C++ program. Not all declarations actually declare anything, and each kind of entity is declared differently. Definitions are declarations that are sufficient to use the entity identified by the name.

#### Simple declaration

##### [Structured binding declaration](https://en.cppreference.com/w/cpp/language/structured_binding)

* Binds the specified names to subobjects or elements of the initializer.
* Like a reference, a structured binding is an alias to an existing object. Unlike a reference, a structured binding does not have to be of a reference type.
* Case 1: binding an array
* Case 2: binding a tuple-like type
* Case 3: binding to data members
```c++
#include <set>
#include <string>
#include <iomanip>
#include <iostream>
 
int main()
{
    std::set<std::string> myset{"hello"};
 
    for (int i{2}; i; --i)
    {
        if (auto [iter, success] = myset.insert("Hello"); success) 
            std::cout << "Insert is successful. The value is "
                      << std::quoted(*iter) << ".\n";
        else
            std::cout << "The value " << std::quoted(*iter)
                      << " already exists in the set.\n";
    }
 
    struct BitFields
    {
        // C++20: default member initializer for bit-fields
        int b : 4 {1}, d : 4 {2}, p : 4 {3}, q : 4 {4};
    };
 
    {
        const auto [b, d, p, q] = BitFields{};
        std::cout << b << ' ' << d << ' ' << p << ' ' << q << '\n';
    }
 
    {
        const auto [b, d, p, q] = []{ return BitFields{4, 3, 2, 1}; }();
        std::cout << b << ' ' << d << ' ' << p << ' ' << q << '\n';
    }
 
    {
        BitFields s;
 
        auto& [b, d, p, q] = s;
        std::cout << b << ' ' << d << ' ' << p << ' ' << q << '\n';
 
        b = 4, d = 3, p = 2, q = 1;
        std::cout << s.b << ' ' << s.d << ' ' << s.p << ' ' << s.q << '\n';
    }

    {
        BitFields s;
 
        auto [b, d, p, q] = s;
        std::cout << b << ' ' << d << ' ' << p << ' ' << q << '\n';
 
        b = 4, d = 3, p = 2, q = 1;
        std::cout << s.b << ' ' << s.d << ' ' << s.p << ' ' << s.q << '\n';
    }    
}
/*
Insert is successful. The value is "Hello".
The value "Hello" already exists in the set.
1 2 3 4
4 3 2 1
1 2 3 4
4 3 2 1
1 2 3 4
1 2 3 4
*/
```
* !!! Be careful of `auto& [b, d, p, q] = s;` if s is deleted, b will be invalidated as well. In this case, use `auto` rather than `auto&`
* [C++17常用新特性(三)---结构化绑定](https://mp.weixin.qq.com/s?__biz=MjM5ODg5MDIzOQ==&mid=2650491856&idx=1&sn=d676113480a097e2b3fd156c5096e0fd&chksm=becc344089bbbd56b357e949b694534a4a8146c548114c9d20f8612b7fe9b1f4297948018fc7&scene=21#wechat_redirect)
	* 1 结构化绑定概述
	* 2 细品结构化绑定
	* 3 哪些场景可以使用结构体绑定
		* 3.1 结构体和类
		* 3.2 原生数组
			* 对原生数组使用结构化绑定时需要注意的是只有在数组的长度一定的情况下才能使用结构化绑定，且声明的对象个数要和数组长度保持一致。数组作为按值传入的参数时是不能使用结构化绑定的，这个时候数组会退化为相应的指针。
		* 3.3 std::pair, std::tuple 和 std::array
	* 4 总结
* [C++17结构化绑定](https://mp.weixin.qq.com/s/YCxM0kmCmpkfnOwe7XNvaQ)
* [Structured binding in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/structured-binding-c/)
* [Structured binding may be the new hotness, but we'll always have std::tie - The Old New Thing](https://devblogs.microsoft.com/oldnewthing/20200925-00/?p=104297)
	* C++17 introduced structured binding, which lets you assign an expression to multiple variables.
	* However, this is for creating new variables to hold the result. If you want to assign the result to existing variables, then you can use the old standby std::tie.

##### [Type alias, alias template](https://en.cppreference.com/w/cpp/language/type_alias)

* Type alias is a name that refers to a previously defined type (similar to typedef).
* Alias template is a name that refers to a family of types.

###### Syntax

* Alias declarations are declarations with the following syntax:
    * `using identifier attr(optional) = type-id ;`	(1)	
    * `template < template-parameter-list > using identifier attr(optional) = type-id ;`(2)	
    * attr	-	optional sequence of any number of attributes
    * identifier	-	the name that is introduced by this declaration, which becomes either a type name (1) or a template name (2)
    * template-parameter-list	-	template parameter list, as in template declaration
    * type-id	-	abstract declarator or any other valid type-id (which may introduce a new type, as noted in type-id). The type-id cannot directly or indirectly refer to identifier. Note that the point of declaration of the identifier is at the semicolon following type-id.

###### Explanation

* Example
```c++
#include <iostream>
#include <string>
#include <typeinfo>
#include <type_traits>
 
// type alias, identical to
// typedef std::ios_base::fmtflags flags;
using flags = std::ios_base::fmtflags;
// the name 'flags' now denotes a type:
flags fl = std::ios_base::dec;
 
// type alias, identical to
// typedef void (*func)(int, int);
using func = void (*) (int, int);
// the name 'func' now denotes a pointer to function:
void example(int, int) {}
func f = example;
 
// alias template
template<class T>
using ptr = T*;
// the name 'ptr<T>' is now an alias for pointer to T
ptr<int> x;
 
// type alias used to hide a template parameter
template<class CharT>
using mystring = std::basic_string<CharT, std::char_traits<CharT>>;
mystring<char> str;
 
// type alias can introduce a member typedef name
template<typename T>
struct Container { using value_type = T; };
// which can be used in generic programming
template<typename ContainerT>
void info(const ContainerT& c)
{
    typename ContainerT::value_type T;
    std::cout << "ContainerT is `" << typeid(decltype(c)).name() << "`\n"
                 "value_type is `" << typeid(T).name() << "`\n";
}
 
// type alias used to simplify the syntax of std::enable_if
template<typename T>
using Invoke = typename T::type;
template<typename Condition>
using EnableIf = Invoke<std::enable_if<Condition::value>>;
template<typename T, typename = EnableIf<std::is_polymorphic<T>>>
int fpoly_only(T) { return 1; }
 
struct S { virtual ~S() {} };
 
int main()
{
    Container<int> c;
    info(c); // Container::value_type will be int in this function
//  fpoly_only(c); // error: enable_if prohibits this
    S s;
    fpoly_only(s); // okay: enable_if allows this
}
/*
ContainerT is `struct Container<int>`
value_type is `int`
*/
```

##### [static_assert declaration](https://en.cppreference.com/w/cpp/language/static_assert)

* Performs compile-time assertion checking.
* Example
```c++
#include <type_traits>
 
static_assert(03301 == 1729); // since C++17 the message string is optional
 
template <class T>
void swap(T& a, T& b) noexcept
{
    static_assert(std::is_copy_constructible_v<T>,
                  "Swap requires copying");
    static_assert(std::is_nothrow_copy_constructible_v<T> &&
                  std::is_nothrow_copy_assignable_v<T>,
                  "Swap requires nothrow copy/assign");
    auto c = b;
    b = a;
    a = c;
}
 
template <class T>
struct data_structure
{
    static_assert(std::is_default_constructible_v<T>,
                  "Data structure requires default-constructible elements");
};
 
struct no_copy
{
    no_copy ( const no_copy& ) = delete;
    no_copy () = default;
};
 
struct no_default
{
    no_default () = delete;
};
 
int main()
{
    int a, b;
    swap(a, b);
 
    no_copy nc_a, nc_b;
    swap(nc_a, nc_b); // 1
 
    [[maybe_unused]] data_structure<int> ds_ok;
    [[maybe_unused]] data_structure<no_default> ds_error; // 2
}
/*
1: error: static assertion failed: Swap requires copying
2: error: static assertion failed: Data structure requires default-constructible elements
*/
```

#### Specifiers

##### [typedef specifier](https://en.cppreference.com/w/cpp/language/typedef)

* typedef - creates an alias that can be used anywhere in place of a (possibly complex) type name.
* Notes
    * type aliases provide the same functionality as typedefs using a different syntax, and are also applicable to template names.
* Example
```c++
// simple typedef
typedef unsigned long ulong;
 
// the following two objects have the same type
unsigned long l1;
ulong l2;
 
// more complicated typedef
typedef int int_t, *intp_t, (&fp)(int, ulong), arr_t[10];
 
// the following two objects have the same type
int a1[10];
arr_t a2;
 
// beware: the following two objects do not have the same type
const intp_t p1 = 0; // int *const p1 = 0
const int *p2;
 
// common C idiom to avoid having to write "struct S"
typedef struct {int a; int b;} S, *pS;
 
// the following two objects have the same type
pS ps1;
S* ps2;
 
// error: storage-class-specifier cannot appear in a typedef declaration
// typedef static unsigned int uint;
 
// typedef can be used anywhere in the decl-specifier-seq
long unsigned typedef int long ullong;
// more conventionally spelled "typedef unsigned long long int ullong;"
 
// std::add_const, like many other metafunctions, use member typedefs
template<class T>
struct add_const
{
    typedef const T type;
};
 
typedef struct Node
{
    struct listNode* next; // declares a new (incomplete) struct type named listNode
} listNode; // error: conflicts with the previously declared struct name
 
// C++20 error: "struct with typedef name for linkage" has member functions
typedef struct { void f() {} } C_Incompatible;
```

##### [inline specifier](https://en.cppreference.com/w/cpp/language/inline)

* The inline specifier, when used in a function's decl-specifier-seq, declares the function to be an inline function.
* A function defined entirely inside a class/struct/union definition, whether it's a member function or a non-member friend function, is implicitly an inline function if it is attached to the global module (since C++20).
* A function declared constexpr is implicitly an inline function.
* A deleted function is implicitly an inline function: its (deleted) definition can appear in more than one translation unit.(since C++11)
* The inline specifier, when used in a decl-specifier-seq of a variable with static storage duration (static class member or namespace-scope variable), declares the variable to be an inline variable.
* A static member variable (but not a namespace-scope variable) declared constexpr is implicitly an inline variable.(since C++17)
* [F.5: If a function is very small and time-critical, declare it inline](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f5-if-a-function-is-very-small-and-time-critical-declare-it-inline)
	* `Reason` Some optimizers are good at inlining without hints from the programmer, but don’t rely on it. Measure! Over the last 40 years or so, we have been promised compilers that can inline better than humans without hints from humans. We are still waiting. Specifying inline (explicitly, or implicitly when writing member functions inside a class definition) encourages the compiler to do a better job.
	* `Example`
		* `inline string cat(const string& s, const string& s2) { return s + s2; }`
	* `Exception` Do not put an inline function in what is meant to be a stable interface unless you are certain that it will not change. An inline function is part of the ABI.
	* `Note` constexpr implies inline.
	* `Note` Member functions defined in-class are inline by default.
	* `Exception` Function templates (including member functions of class templates A\<T>::function() and member function templates A::function\<T>()) are normally defined in headers and therefore inline.
* [SF.2: A .h file must not contain object definitions or non-inline function definitions](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#sf2-a-h-file-must-not-contain-object-definitions-or-non-inline-function-definitions)
	* Reason: Including entities subject to the one-definition rule leads to linkage errors.
	* Example
		* Linking file1.cpp and file2.cpp will give two linker errors.
    ```c++
    // file.h:
    namespace Foo {
        int x = 7;
        int xx() { return x+x; }
    }

    // file1.cpp:
    #include <file.h>
    // ... more ...

     // file2.cpp:
    #include <file.h>
    // ... more ...
    ```
	* Alternative formulation: A .h file must contain only:
		* #includes of other .h files (possibly with include guards)
		* templates
		* class definitions
		* function declarations
		* extern declarations
		* inline function definitions
		* constexpr definitions
		* const definitions
		* using alias definitions
* [Inline Functions - Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html#Inline_Functions)
	* Define functions inline only when they are small, say, 10 lines or fewer.
	* Definition
		* You can declare functions in a way that allows the compiler to expand them inline rather than calling them through the usual function call mechanism.
	* Pros
		* Inlining a function can generate more efficient object code, as long as the inlined function is small. Feel free to inline accessors and mutators, and other short, performance-critical functions.
	* Cons
		* Overuse of inlining can actually make programs slower. Depending on a function's size, inlining it can cause the code size to increase or decrease. Inlining a very small accessor function will usually decrease code size while inlining a very large function can dramatically increase code size. On modern processors smaller code usually runs faster due to better use of the instruction cache.
	* Decision
		* A decent rule of thumb is to not inline a function if it is more than 10 lines long. Beware of destructors, which are often longer than they appear because of implicit member- and base-destructor calls!
		* Another useful rule of thumb: it's typically not cost effective to inline functions with loops or switch statements (unless, in the common case, the loop or switch statement is never executed).
		* It is important to know that functions are not always inlined even if they are declared as such; for example, virtual and recursive functions are not normally inlined. Usually recursive functions should not be inline. The main reason for making a virtual function inline is to place its definition in the class, either for convenience or to document its behavior, e.g., for accessors and mutators.
* [Self-contained Headers - Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html#Self_contained_Headers)
	* When a header declares inline functions or templates that clients of the header will instantiate, `the inline functions and templates must also have definitions in the header, either directly or in files it includes`. Do not move these definitions to separately included header (-inl.h) files; this practice was common in the past, but is no longer allowed. When all instantiations of a template occur in one .cc file, either because they're explicit or because the definition is accessible to only the .cc file, the template definition can be kept in that file.
* [Inline Functions in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/inline-functions-cpp/)
	* Compiler may not perform inlining in such circumstances like:
		* 1) If a function contains a loop. (for, while, do-while)
		* 2) If a function contains static variables.
		* 3) If a function is recursive.
		* 4) If a function return type is other than void, and the return statement doesn’t exist in function body.
		* 5) If a function contains switch or goto statement.
	* Inline functions provide following advantages:
	* Inline function disadvantages:
	* Inline function and classes:
	* What is wrong with macro?
* [C++ inline 函数简介](https://mp.weixin.qq.com/s/hWIKfl2-aXH0Uamt0LS_RA)
	* https://dablelv.blog.csdn.net/article/details/52065524
* [Why are C++ inline functions in the header? - Stack Overflow](https://stackoverflow.com/questions/5057021/why-are-c-inline-functions-in-the-header#:~:text=The%20definition%20of%20an%20inline,definition%20in%20a%20header%20file.)
	* The definition of an inline function doesn't have to be in a header file but, because of the one definition rule [(ODR)](https://en.cppreference.com/w/cpp/language/definition) for inline functions, an identical definition for the function must exist in every translation unit that uses it.
	* The easiest way to achieve this is by putting the definition in a header file.
* How to fix compile error "multiple definition of 'utils::var' ... first defined here" ?
	* declare var as `inline var` in namespace utils
	* [c - "Multiple definition", "first defined here" errors - Stack Overflow](https://stackoverflow.com/questions/30821356/multiple-definition-first-defined-here-errors)
	* [c++ - How do inline variables work? - Stack Overflow](https://stackoverflow.com/questions/38043442/how-do-inline-variables-work)

##### [constexpr specifier](https://en.cppreference.com/w/cpp/language/constexpr)

* constexpr - specifies that the value of a variable or function can appear in constant expressions
* The constexpr specifier declares that it is possible to evaluate the value of the function or variable at compile time. Such variables and functions can then be used where only compile time constant expressions are allowed (provided that appropriate function arguments are given).
* A constexpr specifier used in an object declaration or non-static member function (until C++14) implies const. A constexpr specifier used in a function or static data member (since C++17) declaration implies `inline`. If any declaration of a function or function template has a constexpr specifier, then every declaration must contain that specifier.
* Example
    * Definition of a C++11 constexpr function which computes factorials and a literal type that extends string literals:
```c++
#include <iostream>
#include <stdexcept>
 
// C++11 constexpr functions use recursion rather than iteration
constexpr int factorial(int n)
{
    return n <= 1 ? 1 : (n * factorial(n - 1));
}
 
// C++14 constexpr functions may use local variables and loops
#if __cplusplus >= 201402L
constexpr int factorial_cxx14(int n)
{
    int res = 1;
    while (n > 1)
        res *= n--;
    return res;
}
#endif // C++14
 
// literal class
class conststr
{
    const char* p;
    std::size_t sz;
public:
    template<std::size_t N>
    constexpr conststr(const char(&a)[N]): p(a), sz(N - 1) {}
 
    // constexpr functions signal errors by throwing exceptions
    // in C++11, they must do so from the conditional operator ?:
    constexpr char operator[](std::size_t n) const
    {
        return n < sz ? p[n] : throw std::out_of_range("");
    }
 
    constexpr std::size_t size() const { return sz; }
};
 
// C++11 constexpr functions had to put everything in a single return statement
// (C++14 doesn't have that requirement)
constexpr std::size_t countlower(conststr s, std::size_t n = 0,
                                             std::size_t c = 0)
{
    return n == s.size() ? c :
        'a' <= s[n] && s[n] <= 'z' ? countlower(s, n + 1, c + 1) :
                                     countlower(s, n + 1, c);
}
 
// output function that requires a compile-time constant, for testing
template<int n>
struct constN
{
    constN() { std::cout << n << '\n'; }
};
 
int main()
{
    std::cout << "4! = " ;
    constN<factorial(4)> out1; // computed at compile time
 
    volatile int k = 8; // disallow optimization using volatile
    std::cout << k << "! = " << factorial(k) << '\n'; // computed at run time
 
    std::cout << "the number of lowercase letters in \"Hello, world!\" is ";
    constN<countlower("Hello, world!")> out2; // implicitly converted to conststr
 
    constexpr int a[12] = {0, 1, 2, 3, 4, 5, 6, 7, 8};
    constexpr int length_a = sizeof(a)/sizeof(int); // std::size(a) in C++17,
                                                    // std::ssize(a) in C++20
    std::cout << "array of length " << length_a << " has elements: ";
    for (int i = 0; i < length_a; ++i)
        std::cout << a[i] << " ";
}
/*
4! = 24
8! = 40320
the number of lowercase letters in "Hello, world!" is 9
array of length 12 has elements: 0 1 2 3 4 5 6 7 8 0 0 0
*/
```
* [Constant expressions - cppreference.com](https://en.cppreference.com/w/cpp/language/constant_expression)
	* Defines an expression that can be evaluated at compile time.
	* Such expressions can be used as non-type template arguments, array sizes, and in other contexts that require constant expressions
* [constexpr (C++) | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/constexpr-cpp?view=msvc-160)
  * The keyword constexpr was introduced in C++11 and improved in C++14. It means constant expression. Like const, it can be applied to variables: A compiler error is raised when any code attempts to modify the value. Unlike const, constexpr can also be applied to functions and class constructors. constexpr indicates that the value, or return value, is constant and, where possible, is computed at compile time.
  * A constexpr integral value can be used wherever a const integer is required, such as in template arguments and array declarations. And when a value is computed at compile time instead of run time, it helps your program run faster and use less memory.
  * To limit the complexity of compile-time constant computations, and their potential impacts on compilation time, the C++14 standard requires the types in constant expressions to be literal types.
* [Understanding constexpr specifier in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/understanding-constexper-specifier-in-c/)
	* constexpr is a feature added in C++ 11. The main idea is performance improvement of programs by doing computations at compile time rather than run time. Note that once a program is compiled and finalized by developer, it is run multiple times by users. The idea is to spend time in compilation and save time at run time (similar to template metaprogramming)
	* constexpr vs inline functions
	* constexpr with constructors
	* constexpr vs const
* [c++ - Difference between constexpr and const - Stack Overflow](https://stackoverflow.com/questions/14116003/difference-between-constexpr-and-const?rq=1)
* [c++ - constexpr const vs constexpr variables? - Stack Overflow](https://stackoverflow.com/questions/28845058/constexpr-const-vs-constexpr-variables)
* [c++ - Is it possible to use std::string in a constexpr? - Stack Overflow](https://stackoverflow.com/questions/27123306/is-it-possible-to-use-stdstring-in-a-constexpr)
	* No. error: the type ‘const string {aka const std::basic_string}’ of constexpr variable ‘constString’ is not literal... because... ‘std::basic_string’ has a non-trivial destructor
	* However, as of C++17, you can use string_view or char[]
* [现代C++之constexpr](https://mp.weixin.qq.com/s/Shg1L_nUfLY18QzgVF_8aA)
	* constexpr在 C++11 引入、在 C++14 得到大幅改进。
		* （1）C++11中的constexpr指定的函数返回值和参数必须要保证是字面值，而且必须只有一行return代码，这给函数的设计者带来了更多的限制，比如通常只能通过return 三目运算符+递归来计算返回的字面值。
		* （2）C++14中只要保证返回值和参数是字面值就行了，函数体中可以加入更多的语句，方便了更灵活的计算。
	* 它的字面意思是 constant expression，常量表达式。
	* 1.变量
		* const与constexpr可以应用到变量和函数。尽管它们彼此相似，但实际上它们是非常不同的概念。
		* const与constexpr意味着他们的值不能在初始化后改变。
		* const和constexpr之间的主要区别是初始化值的时间(求值)。尽管const变量的值可以在编译时和运行时，但constexpr始终在编译时进行求值。
		* 因此，const变量既可以定义编译时常量(比如size1)来指定数组大小，也可以定义运行时常量(比如size2)来定义数组大小。另一方面，constexpr总是定义可以指定数组大小的编译时常量。
	* 2.函数
		* const和constexpr也可以应用于函数。const函数必须是成员函数（方法，运算符），其中const关键字的应用意味着该方法无法更改其成员（非静态）字段的值。
		* constexpr是一个不同的概念。如果将编译时常量作为参数传递，则它将一个函数（成员或非成员）标记为可以在编译时求值的函数。
		* 顺便说一下，这些constexpr函数是常规C ++函数，即使传递了非常量参数也可以调用它们。但是在这种情况下，您将获得非constexpr值。
	* 3.类方法
		* constexpr也可应用于所述成员函数（方法），操作者和甚至构造函数。
	* 4.建议
		* Tips from the book Effective Modern C++ by Scott Meyers about constexpr:
			* constexpr 对象是const，在编译期间使用已知的值初始化;
			* constexpr 函数当使用在编译期间已知值的参数调用时，constexpr函数产生编译时结果;
			* 与非constexpr对象和函数相比，constexpr对象和函数可以在更广泛的上下文中使用;
			* constexpr 是对象或函数接口的一部分。
	* 5.补充
		* 内联变量C++17 引入了内联（inline）变量的概念，允许在头文件中定义内联变量，然后像内联函数一样，只要所有的定义都相同，那变量的定义出现多次也没有关系。对于类的静态数据成员，const 缺省是不内联的，而 constexpr 缺省就是内联的。这种区别在你用 & 去取一个 const int 值的地址、或将其传到一个形参类型为 const int& 的函数去的时候（这在 C++ 文档里的行话叫 ODR-use），就会体现出来。
		* 程序在链接时就会报错了，说找不到 magic::number。这是因为 ODR(下面的one definition rule)-use 的类静态常量也需要有一个定义，在没有内联变量之前需要在某一个源代码文件（非头文件）中这样写：
		* `constint magic::number = 42;`
		* 必须正正好好一个，多了少了都不行，所以叫 one definition rule。
		* 内联函数，现在又有了内联变量，以及模板，则不受这条规则限制。修正这个问题的简单方法是把 magic 里的 static const 改成 static constexpr 或 static inline const。前者可行的原因是，类的静态 constexpr 成员变量默认就是内联的。const 常量和类外面的 constexpr 变量不默认内联，需要手工加 inline 关键字才会变成内联。
	* 6.学习资料
* [现代C++编程实践(六)—一招简化模板编程](https://mp.weixin.qq.com/s/jstBtimXLjxB_1pJyVy2NQ)
	* 实现一个模板类，实现类中的加法运算，支持泛型。
	* 从上面的代码可以看出，如果要实现这两个相似的功能需要对add方法进行不同的实现，也就是说：在实现这个功能时需要根据模板特化的类型分别编写出不同的特化代码。问题来了，能不能只提供一个模板函数从而实现上述两种特化的方法呢？
	* 答案是：有的。一种是使用传统的宏定义的方法，但是同时只能支持一种。另外一种是现代C++提供的constexpr关键字，它应用在if表达式中，使用方法和if-else类似。不同的是它是在编译阶段就确认好的，通过对后面的表达式进行计算，从而判断出使用哪个分支。在本文中，它需要和is_same_v搭配使用，在编译结算就计算出传入参数的类型，从而实现不同传入参数的数据运算。本文中示例的实现代码如下：
	* 如上代码所示，通过constexpr可以对不同的参数类型进行模板的实例化，在main函数中，同时传入容器和普通数据类型时都能够正确进行计算。
```c++
#include <iostream>
#include <vector>
using namespace std;
template<typename T>
class AddInterface{
public:
    AddInterface(T value):value(value){}
    template<typename U>
    T add(U x) const{
        if constexpr (std::is_same_v<T,std::vector<U>>){
            auto tmp(value);
            for(auto &ele:tmp){
                ele+=x;
            }
            return tmp;
        }else{
            return (value+x);
        }
    }
private:
    T value;
};
int main(){
    std::vector<int> vRes{1,2,3,4};
    auto res{AddInterface<std::vector<int>>{vRes}.add(20)};
    for(auto v:res){
        std::cout<<v<<",";
    }
    cout<<endl;
    std::cout<<AddInterface<float>{3.5}.add(20)<<std::endl;
    return 0;
}
```

##### [Storage class specifiers](https://en.cppreference.com/w/cpp/language/storage_duration)

* [Storage Classes](https://www.tutorialspoint.com/cplusplus/cpp_storage_classes.htm)
* A storage class defines the scope (visibility) and life-time of variables and/or functions within a C++ Program. These specifiers precede the type that they modify. There are following storage classes, which can be used in a C++ Program
	* auto
	* register
	* static
		* avoid static class members variables (race conditions, almost-global variables)
		* [SF.22: Use an unnamed (anonymous) namespace for all internal/non-exported entities](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#sf22-use-an-unnamed-anonymous-namespace-for-all-internalnon-exported-entities)
			* Reason 
				* Nothing external can depend on an entity in a nested unnamed namespace. Consider putting every definition in an implementation source file in an unnamed namespace unless that is defining an “external/exported” entity.
			* Example; bad
			```c++
			static int f();
			int g();
			static bool h();
			int k();
			```
			* Example; good
			```c++
			namespace {
				int f();
				bool h();
			}
			int g();
			int k();
			```
			* Example 
				* An API class and its members can’t live in an unnamed namespace; but any “helper” class or function that is defined in an implementation source file should be at an unnamed namespace scope.
	* extern
	* mutable
* [C++ keywords: mutable - cppreference.com](https://en.cppreference.com/w/cpp/keyword/mutable)
  * [mutable type specifier](https://en.cppreference.com/w/cpp/language/cv)
    * mutable - permits modification of the class member declared mutable even if the containing object is declared const.
  * [lambda-declarator](https://en.cppreference.com/w/cpp/language/lambda) that removes const qualification from parameters captured by copy (since C++11)
    * mutable: allows body to modify the objects captured by copy, and to call their non-const member functions
  * [C++ mutable keyword - GeeksforGeeks](https://www.geeksforgeeks.org/c-mutable-keyword/)

##### [Enumeration declaration](https://en.cppreference.com/w/cpp/language/enum)

* An enumeration is a distinct type whose value is restricted to a range of values (see below for details), which may include several explicitly named constants ("enumerators"). The values of the constants are values of an integral type known as the underlying type of the enumeration.
* Unscoped enumerations
	* `enum Color { red, green, blue };`
* Scoped enumerations
	* `enum class Color { red, green = 20, blue };`
* How to iterate over enum ?
	* [C++ Tutorial => Iteration over an enum](https://riptutorial.com/cplusplus/example/13085/iteration-over-an-enum)
	* [c++ - How can I iterate over an enum? - Stack Overflow](https://stackoverflow.com/questions/261963/how-can-i-iterate-over-an-enum)
	* [c - Number of elements in an enum - Stack Overflow](https://stackoverflow.com/questions/712463/number-of-elements-in-an-enum)
```c++
#include <iostream>

enum color
{
    red,
    yellow,
    green,
    blue,
    ColorCount
};

std::ostream& operator<<(std::ostream& os, color c)
{
    switch(c) {
        case red   : os << "red";    break;
        case yellow: os << "yellow"; break;
        case green : os << "green";  break;
        case blue  : os << "blue";   break;
        default    : os.setstate(std::ios_base::failbit);
    }
    
    return os;
}
int main()
{
    for (auto i = 0; i < color::ColorCount; ++ i)
        std::cout << static_cast<color>(i) << "\n";

    return 0;
}
/*
red
yellow
green
blue
*/
```

##### [decltype specifier](https://en.cppreference.com/w/cpp/language/decltype)

* Inspects the declared type of an entity or the type and value category of an expression.
* Keywords decltype
	* [decltype specifier](https://en.cppreference.com/w/cpp/language/decltype) (since C++11)
	* [decltype(auto)](https://en.cppreference.com/w/cpp/language/auto) (since C++14)

##### [auto placeholder type specifier](https://en.cppreference.com/w/cpp/language/auto)

* For variables, specifies that the type of the variable that is being declared will be automatically deduced from its initializer.
* For functions, specifies that the return type will be deduced from its return statements. (since C++14)
* For non-type template parameters, specifies that the type will be deduced from the argument. (since C++17)

##### [alignas specifier](https://en.cppreference.com/w/cpp/language/alignas)

* Specifies the [alignment requirement](https://en.cppreference.com/w/cpp/language/object#Alignment) of a type or an object.
* Syntax
    * `alignas( expression )`
    * `alignas( type-id )`
    * `alignas( pack ... )`
    * 1) expression must be an integral constant expression that evaluates to zero, or to a valid value for an alignment or extended alignment.
    * 2) Equivalent to alignas(alignof(type-id))
    * 3) Equivalent to multiple alignas specifiers applied to the same declaration, one for each member of the parameter pack, which can be either type or non-type parameter pack.
```c++
// every object of type struct_float will be aligned to alignof(float) boundary
// (usually 4):
struct alignas(float) struct_float
{
    // your definition here
};
 
// every object of type sse_t will be aligned to 32-byte boundary:
struct alignas(32) sse_t
{
    float sse_data[4];
};
 
// the array "cacheline" will be aligned to 64-byte boundary:
alignas(64) char cacheline[64];
 
 
#include <iostream>
int main()
{
    struct default_aligned { float data[4]; } a, b, c;
    sse_t x, y, z;
 
    std::cout
        << "alignof(struct_float) = " << alignof(struct_float) << '\n'
        << "sizeof(sse_t) = " << sizeof(sse_t) << '\n'
        << "alignof(sse_t) = " << alignof(sse_t) << '\n'
        << "alignof(cacheline) = " << alignof(alignas(64) char[64]) << '\n'
        << std::hex << std::showbase
        << "&a: " << &a << '\n'
        << "&b: " << &b << '\n'
        << "&c: " << &c << '\n'
        << "&x: " << &x << '\n'
        << "&y: " << &y << '\n'
        << "&z: " << &z << '\n';
}
/*
alignof(struct_float) = 4
sizeof(sse_t) = 32
alignof(sse_t) = 32
alignof(cacheline) = 64
&a: 0x7fffcec89930
&b: 0x7fffcec89940
&c: 0x7fffcec89950
&x: 0x7fffcec89960
&y: 0x7fffcec89980
&z: 0x7fffcec899a0
*/
```

##### [cv (const and volatile) type qualifiers](https://en.cppreference.com/w/cpp/language/cv)

* Appear in any type specifier, including decl-specifier-seq of declaration grammar, to specify constness or volatility of the object being declared or of the type being named.
    * `const` - defines that the type is constant.
    * `volatile` - defines that the type is volatile.
* Example
```c++
#include <cstdlib>
 
int main()
{
    int n1 = 0;          // non-const object
    const int n2 = 0;    // const object
    int const n3 = 0;    // const object (same as n2)
    volatile int n4 = 0; // volatile object
 
    const struct
    {
        int n1;
        mutable int n2;
    } x = {0, 0};        // const object with mutable member
 
    n1 = 1;   // ok, modifiable object
//  n2 = 2;   // error: non-modifiable object
    n4 = 3;   // ok, treated as a side-effect
//  x.n1 = 4; // error: member of a const object is const
    x.n2 = 4; // ok, mutable member of a const object isn't const
 
    const int& r1 = n1; // reference to const bound to non-const object
//  r1 = 2; // error: attempt to modify through reference to const
    const_cast<int&>(r1) = 2; // ok, modifies non-const object n1
 
    const int& r2 = n2; // reference to const bound to const object
//  r2 = 2; // error: attempt to modify through reference to const
//  const_cast<int&>(r2) = 2; // undefined behavior: attempt to modify const object n2
 
    [](...){}(n3, n4, x, r2); // see also: [[maybe_unused]]
 
    std::system("g++ -O3 -Wa,-adhln ./main.cpp"); // may issue asm on POSIX systems
}
/*
# typical machine code produced on an x86_64 platform
# (only the code that contributes to observable side-effects is emitted)
main:
    movl    $0, -4(%rsp) # volatile int n4 = 0;
    movl    $3, -4(%rsp) # n4 = 3;
    xorl    %eax, %eax   # return 0 (implicit)
    ret
*/
```

###### Explanation

* `const object` - an object whose type is const-qualified, or a non-mutable subobject of a const object. Such object cannot be modified: attempt to do so directly is a compile-time error, and attempt to do so indirectly (e.g., by modifying the const object through a reference or pointer to non-const type) results in undefined behavior.
* `volatile object` - an object whose type is volatile-qualified, or a subobject of a volatile object, or a mutable subobject of a const-volatile object. Every access (read or write operation, member function call, etc.) made through a glvalue expression of volatile-qualified type is treated as a visible side-effect for the purposes of optimization (that is, within a single thread of execution, volatile accesses cannot be optimized out or reordered with another visible side effect that is sequenced-before or sequenced-after the volatile access. This makes volatile objects suitable for communication with a signal handler, but not with another thread of execution, see std::memory_order). Any attempt to access a volatile object through a glvalue of non-volatile type (e.g. through a reference or pointer to non-volatile type) results in undefined behavior.
* `const volatile object` - an object whose type is const-volatile-qualified, a non-mutable subobject of a const volatile object, a const subobject of a volatile object, or a non-mutable volatile subobject of a const object. Behaves as both a const object and as a volatile object.
* Each cv-qualifier (`const` and `volatile`) can appear `at most once` in any cv-qualifier sequence. For example, `const const` and `volatile const volatile` are not valid cv-qualifier sequences.

###### mutable specifier

* `mutable` - permits modification of the class member declared mutable even if the containing object is declared const.
* May appear in the declaration of a non-static class members of non-reference non-const type
```c++
class X
{
    mutable const int* p; // OK
    mutable int* const q; // ill-formed
    mutable int&       r; // ill-formed
};
```
* Mutable is used to specify that the member does not affect the externally visible state of the class (as often used for mutexes, memo caches, lazy evaluation, and access instrumentation).
```c++
class ThreadsafeCounter
{
    mutable std::mutex m; // The "M&M rule": mutable and mutex go together
    int data = 0;
public:
    int get() const
    {
        std::lock_guard<std::mutex> lk(m);
        return data;
    }
 
    void inc()
    {
        std::lock_guard<std::mutex> lk(m);
        ++data;
    }
};
```

###### MISC

* [P.3: Express intent](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#p3-express-intent)
	* `Reason` Unless the intent of some code is stated (e.g., in names or comments), it is impossible to tell whether the code does what it is supposed to do.
	* `Example`
    ```c++
    gsl::index i = 0;
    while (i < v.size()) {
        // ... do something with v[i] ...
    }
    ```
	* The intent of “just” looping over the elements of v is not expressed here. The implementation detail of an index is exposed (so that it might be misused), and i outlives the scope of the loop, which might or might not be intended. The reader cannot know from just this section of code.
	* Better:
		* `for (const auto& x : v) { /* do something with the value of x */ }`
	* Now, there is no explicit mention of the iteration mechanism, and the loop operates on a reference to const elements so that accidental modification cannot happen. If modification is desired, say so:
		* `for (auto& x : v) { /* modify x */ }`
	* For more details about for-statements, see ES.71. Sometimes better still, use a named algorithm. This example uses the for_each from the Ranges TS because it directly expresses the intent:
		* `for_each(v, [](int x) { /* do something with the value of x */ });`
		* `for_each(par, v, [](int x) { /* do something with the value of x */ });`
	* The last variant makes it clear that we are not interested in the order in which the elements of v are handled.
	* A programmer should be familiar with
		* The guidelines support library
		* The ISO C++ Standard Library
		* Whatever foundation libraries are used for the current project(s)
	* `Note` Alternative formulation: Say what should be done, rather than just how it should be done.Note Some language constructs express intent better than others.Example If two ints are meant to be the coordinates of a 2D point, say so:
		* `draw_line(int, int, int, int);  // obscure`
		* `draw_line(Point, Point);        // clearer`
	* `Enforcement` Look for common patterns for which there are better alternatives
		* simple for loops vs. range-for loops
		* f(T*, int) interfaces vs. f(span\<T>) interfaces
		* loop variables in too large a scope
		* naked new and delete
		* functions with many parameters of built-in types
	* There is a huge scope for cleverness and semi-automated program transformation.
* [Con: Constants and immutability](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#con-constants-and-immutability)
	* You can’t have a race condition on a constant. It is easier to reason about a program when many of the objects cannot change their values. Interfaces that promises “no change” of objects passed as arguments greatly increase readability.
	* Constant rule summary:
		* Con.1: By default, make objects immutable
		* Con.2: By default, make member functions const
		* Con.3: By default, pass pointers and references to consts
		* Con.4: Use const to define objects with values that do not change after construction
		* Con.5: Use constexpr for values that can be computed at compile time
* [Con.2: By default, make member functions const](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#con2-by-default-make-member-functions-const)
	* `Reason` A member function should be marked const unless it changes the object’s observable state. This gives a more precise statement of design intent, better readability, more errors caught by the compiler, and sometimes more optimization opportunities.
	* `Example, bad`
    ```c++
    class Point {
        int x, y;
    public:
        int getx() { return x; }    // BAD, should be const as it doesn't modify the object's state
        // ...
    };

    void f(const Point& pt)
    {
        int x = pt.getx();          // ERROR, doesn't compile because getx was not marked const
    }
    ```
	* `Note` It is not inherently bad to pass a pointer or reference to non-const, but that should be done only when the called function is supposed to modify the object. A reader of code must assume that a function that takes a “plain” T* or T& will modify the object referred to. If it doesn’t now, it might do so later without forcing recompilation.
	* `Note` There are code/libraries that offer functions that declare a T* even though those functions do not modify that T. This is a problem for people modernizing code. You can
		* update the library to be const-correct; preferred long-term solution
		* “cast away const”; best avoided
		* provide a wrapper function
	* Example:
    ```c++
    void f(int* p);   // old code: f() does not modify `*p`
    void f(const int* p) { f(const_cast<int*>(p)); } // wrapper
    ```
	* Note that this wrapper solution is a patch that should be used only when the declaration of f() cannot be modified, e.g. because it is in a library that you cannot modify.
	* `Note` A const member function can modify the value of an object that is mutable or accessed through a pointer member. A common use is to maintain a cache rather than repeatedly do a complicated computation. For example, here is a Date that caches (memoizes) its string representation to simplify repeated uses:
    ```c++
    class Date {
    public:
        // ...
        const string& string_ref() const
        {
            if (string_val == "") compute_string_rep();
            return string_val;
        }
        // ...
    private:
        void compute_string_rep() const;    // compute string representation and place it in string_val
        mutable string string_val;
        // ...
    };
    ```
	* Another way of saying this is that constness is not transitive. It is possible for a const member function to change the value of mutable members and the value of objects accessed through non-const pointers. It is the job of the class to ensure such mutation is done only when it makes sense according to the semantics (invariants) it offers to its users.
	* See also: [Pimpl](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Ri-pimpl)
	* `Enforcement` 
		* Flag a member function that is not marked const, but that does not perform a non-const operation on any member variable.
* [C++ - Why static member function can't be created with 'const' qualifier - Stack Overflow](https://stackoverflow.com/questions/7035356/c-why-static-member-function-cant-be-created-with-const-qualifier)
	* When you apply the const qualifier to a nonstatic member function, it affects the this pointer. For a const-qualified member function of class C, the this pointer is of type C const*, whereas for a member function that is not const-qualified, the this pointer is of type C*.
	* A static member function does not have a this pointer (such a function is not called on a particular instance of a class), so const qualification of a static member function doesn't make any sense.

##### [Attribute specifier sequence](https://en.cppreference.com/w/cpp/language/attributes)

* Introduces implementation-defined attributes for types, objects, code, etc.
* `[[attr]] [[attr1, attr2, attr3(args)]] [[namespace::attr(args)]] alignas-specifier`
```c++
[[gnu::always_inline]] [[gnu::hot]] [[gnu::const]] [[nodiscard]]
inline int f(); // declare f with four attributes
 
[[gnu::always_inline, gnu::const, gnu::hot, nodiscard]]
int f(); // same as above, but uses a single attr specifier that contains four attributes
 
// C++17:
[[using gnu : const, always_inline, hot]] [[nodiscard]]
int f[[gnu::always_inline]](); // an attribute may appear in multiple specifiers
 
int f() { return 0; }
 
int main() {}
```

###### [C++ attribute: maybe_unused (since C++17)](https://en.cppreference.com/w/cpp/language/attributes/maybe_unused)

* Suppresses warnings on unused entities.
```c++
#include <cassert>
 
[[maybe_unused]] void f([[maybe_unused]] bool thing1,
                        [[maybe_unused]] bool thing2)
{
    [[maybe_unused]] bool b = thing1 && thing2;
    assert(b); // in release mode, assert is compiled out, and b is unused
               // no warning because it is declared [[maybe_unused]]
} // parameters thing1 and thing2 are not used, no warning
 
int main() {}
```

#### Declarators

##### [Pointer declaration](https://en.cppreference.com/w/cpp/language/pointer)

* Declares a variable of a pointer or pointer-to-member type.
* Should I store pointers or objects in containers ?
	* [dictionary - Map of Pointers versus Map of Structures/Containers (C++) - Stack Overflow](https://stackoverflow.com/questions/12451980/map-of-pointers-versus-map-of-structures-containers-c)
		* As I see it, there are a number of factors involved in deciding whether to use pointers vs. objects:
			* 1. Do you or don't you need polymorphism?
			* 2. The size of the objects you store and their suitability for copy operations
			* 3. Other operations you perform on the container and its contents
		* So clearly, it all depends on the type and size of objects you store, and the type and frequency of the operations you carry out. If the objects you are dealing with are various types of windows, buttons and menus of a GUI application, you will most likely want to use pointers and take advantage of polymorphism. If, on the other hand, you are dealing with huge structures of compact elements, all identical in size and shape, and the operations you perform involve frequent iteration or bulk copying, storing objects directly is perferrable. There may also be situations where the decision is hard to make without trying both and deciding based on the results of memory and time benchmarks.
	* [c++ - Should I store entire objects, or pointers to objects in containers? - Stack Overflow](https://stackoverflow.com/questions/141337/should-i-store-entire-objects-or-pointers-to-objects-in-containers)
* [c++ - Is it good practice to NULL a pointer after deleting it? - Stack Overflow](https://stackoverflow.com/questions/1931126/is-it-good-practice-to-null-a-pointer-after-deleting-it#:~:text=Setting%20pointers%20to%20NULL%20following,%2C%20it%20can%27t%20hurt.)
	* Setting a pointer to 0 (which is "null" in standard C++, the NULL define from C is somewhat different) avoids crashes on double deletes.
* [c++ - When should I use raw pointers over smart pointers? - Stack Overflow](https://stackoverflow.com/questions/6675651/when-should-i-use-raw-pointers-over-smart-pointers)
* [F.7: For general use, take T* or T& arguments rather than smart pointers](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f7-for-general-use-take-t-or-t-arguments-rather-than-smart-pointers)
* [I.11: Never transfer ownership by a raw pointer (T*) or reference (T&)](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#i11-never-transfer-ownership-by-a-raw-pointer-t-or-reference-t)
* [I.12: Declare a pointer that must not be null as not_null](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#i12-declare-a-pointer-that-must-not-be-null-as-not_null)
* [I.13: Do not pass an array as a single pointer](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#i13-do-not-pass-an-array-as-a-single-pointer)
* [I.27: For stable library ABI, consider the Pimpl idiom](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#i27-for-stable-library-abi-consider-the-pimpl-idiom)
    * `Reason` Because private data members participate in class layout and private member functions participate in overload resolution, changes to those implementation details require recompilation of all users of a class that uses them. A non-polymorphic interface class holding a pointer to implementation (`Pimpl`) can isolate the users of a class from changes in its implementation at the cost of an indirection.
    * `Example` interface (widget.h)
    ```c++
    class widget {
        class impl;
        std::unique_ptr<impl> pimpl;
    public:
        void draw(); // public API that will be forwarded to the implementation
        widget(int); // defined in the implementation file
        ~widget();   // defined in the implementation file, where impl is a complete type
        widget(widget&&) noexcept; // defined in the implementation file
        widget(const widget&) = delete;
        widget& operator=(widget&&) noexcept; // defined in the implementation file
        widget& operator=(const widget&) = delete;
    };
    ```
    * implementation (widget.cpp)
    ```c++
    class widget::impl {
        int n; // private data
    public:
        void draw(const widget& w) { /* ... */ }
        impl(int n) : n(n) {}
    };
    void widget::draw() { pimpl->draw(*this); }
    widget::widget(int n) : pimpl{std::make_unique<impl>(n)} {}
    widget::widget(widget&&) noexcept = default;
    widget::~widget() = default;
    widget& widget::operator=(widget&&) noexcept = default;
    ```
    * `Notes` See [GOTW #100](https://herbsutter.com/gotw/_100/) and [cppreference](http://en.cppreference.com/w/cpp/language/pimpl) for the trade-offs and additional implementation details associated with this idiom.
    * `Enforcement` (Not enforceable) It is difficult to reliably identify where an interface forms part of an ABI.

### [Initialization](https://en.cppreference.com/w/cpp/language/initialization)

* Initialization of a variable provides its initial value at the time of construction.
* The initial value may be provided in the initializer section of a declarator or a new expression. It also takes place during function calls: function parameters and the function return values are also initialized.
* For each declarator, the initializer may be one of the following:
    * ( expression-list )	(1)	
    * = expression	(2)	
    * { initializer-list }	(3)	
    * 1) comma-separated list of arbitrary expressions and braced-init-lists in parentheses
    * 2) the equals sign followed by an expression
    * 3) braced-init-list: possibly empty, comma-separated list of expressions and other braced-init-lists
* Depending on context, the initializer may invoke:
    * Value initialization, e.g. std::string s{};
    * Direct initialization, e.g. std::string s("hello");
    * Copy initialization, e.g. std::string s = "hello";
    * List initialization, e.g. std::string s{'a', 'b', 'c'};
    * Aggregate initialization, e.g. char a[3] = {'a', 'b'};
    * Reference initialization, e.g. char& c = a[0];
* If no initializer is provided, the rules of default initialization apply.
* Initialization includes the evaluation of all subexpressions within the initializer and the creation of any temporary objects for function arguments or return values.
* [【ZZ】C++11之统一初始化语法 | 桃子的博客志 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/8674208.html)

#### [Initializer](https://en.cppreference.com/w/cpp/language/initialization)

##### [Copy elision](https://en.cppreference.com/w/cpp/language/copy_elision)

* Omits copy and move (since C++11) constructors, resulting in zero-copy pass-by-value semantics.
* Mandatory elision of copy/move operations
    * Under the following circumstances, the compilers are required to omit the copy and move construction of class objects, even if the copy/move constructor and the destructor have observable side-effects. The objects are constructed directly into the storage where they would otherwise be copied/moved to. The copy/move constructors need not be present or accessible:
* Non-mandatory elision of copy/move (since C++11) operations
    * Under the following circumstances, the compilers are permitted, but not required to omit the copy and move (since C++11) construction of class objects even if the copy/move (since C++11) constructor and the destructor have observable side-effects. The objects are constructed directly into the storage where they would otherwise be copied/moved to. This is an optimization: even when it takes place and the copy/move (since C++11) constructor is not called, it still must be present and accessible (as if no optimization happened at all), otherwise the program is ill-formed:
* Notes
    * Copy elision is `one of the two allowed forms of optimization, alongside allocation elision and extension, (since C++14)` that can change the observable side-effects. Because some compilers do not perform copy elision in every situation where it is allowed (e.g., in debug mode), programs that rely on the side-effects of copy/move constructors and destructors are not portable.
    * In a return statement or a throw-expression, if the compiler cannot perform copy elision but the conditions for copy elision are met or would be met, except that the source is a function parameter, the compiler will attempt to use the move constructor even if the object is designated by an lvalue; see return statement for details. (since C++11)
```c++
#include <iostream>
 
struct Noisy
{
    Noisy() { std::cout << "constructed at " << this << '\n'; }
    Noisy(const Noisy&) { std::cout << "copy-constructed\n"; }
    Noisy(Noisy&&) { std::cout << "move-constructed\n"; }
    ~Noisy() { std::cout << "destructed at " << this << '\n'; }
};
 
Noisy f()
{
    Noisy v = Noisy(); // copy elision when initializing v
                       // from a temporary (until C++17) / prvalue (since C++17)
    return v; // NRVO from v to the result object (not guaranteed, even in C++17)
}             // if optimization is disabled, the move constructor is called
 
void g(Noisy arg)
{
    std::cout << "&arg = " << &arg << '\n';
}
 
int main()
{
    Noisy v = f(); // copy elision in initialization of v
                   // from the temporary returned by f() (until C++17)
                   // from the prvalue f() (since C++17)
 
    std::cout << "&v = " << &v << '\n';
 
    g(f()); // copy elision in initialization of the parameter of g()
            // from the temporary returned by f() (until C++17)
            // from the prvalue f() (since C++17)
}
/*
constructed at 0x7fffd635fd4e
&v = 0x7fffd635fd4e
constructed at 0x7fffd635fd4f
&arg = 0x7fffd635fd4f
destructed at 0x7fffd635fd4f
destructed at 0x7fffd635fd4e
*/
```

### [Functions](https://en.cppreference.com/w/cpp/language/functions)

* [Functions](https://www.tutorialspoint.com/cplusplus/cpp_functions.htm)
* [Functions - C++ Tutorials](http://www.cplusplus.com/doc/tutorial/functions/)
* [Function Signature](https://redirect.cs.umbc.edu/~chang/cs202/Lectures/modules/m04-overload/slides.php?print#:~:text=Function%20Signature,part%20of%20a%20function%27s%20signature.)
	* A function's signature includes the function's name and the number, order and type of its formal parameters.
	* Two overloaded functions must not have the same signature.
	* The return value is not part of a function's signature.
	* These two functions have the same signature:
		* `int Divide (int n, int m) ; `
		* `double Divide (int n, int m) ;`
* [进入编译器后，一个函数经历了什么？](https://mp.weixin.qq.com/s/kYilpl4K_XpVDF3gaKoRAQ)
* [C/C++ 中的 argc，argv 到底是什么？](https://mp.weixin.qq.com/s/Mik2n9oLP-PuFNU3lP48Zw)
* [exit(0) vs exit(1) in C/C++ with Examples - GeeksforGeeks](https://www.geeksforgeeks.org/exit0-vs-exit1-in-c-c-with-examples/)
	* Exit Success: Exit Success is indicated by exit(0) statement which means successful termination of the program, i.e. program has been executed without any error or interrupt.
	* Exit Failure: Exit Failure is indicated by exit(1) which means the abnormal termination of the program, i.e. some error or interrupt has occurred. We can use different integer other than 1 to indicate different types of errors.
* [现代C++编程实践(二)—函数返回值的处理](https://mp.weixin.qq.com/s/DJB9Axdh9toIBQIUZsujcA)
	* 先说一种类C的方式，可以通过使用函数出参的方式获取所求复数的实部和虚部。
	* 除此之外使用C++的方式可以通过std::pair<double,double>这种数据结构结果保存结果值。
	* std::tie的实现方式相对于std::tuple来讲可读性变强了，返回值可以直接通过std::tie中的定义获取。除此之外，还有一个优势就是，可以忽略不想要的值，这个在std::tuple中是不可能做到的。
	* C++17版本中提供了结构化绑定

#### [Default arguments](https://en.cppreference.com/w/cpp/language/default_arguments)

* Allows a function to be called without providing one or more trailing arguments.
* Indicated by using the following syntax for a parameter in the `parameter-list` of a [function declaration](https://en.cppreference.com/w/cpp/language/function).

#### [Lambda expressions](https://en.cppreference.com/w/cpp/language/lambda)

* Constructs a [closure](https://en.wikipedia.org/wiki/Closure_(computer_programming)): an unnamed function object capable of capturing variables in scope.
* If auto is used as a type of a parameter or an explicit template parameter list is provided (since C++20), the lambda is a generic lambda. (since C++14)
```c++
#include <vector>
#include <iostream>
#include <algorithm>
#include <functional>
 
int main()
{
    std::vector<int> c = {1, 2, 3, 4, 5, 6, 7};
    int x = 5;
    c.erase(std::remove_if(c.begin(), c.end(), [x](int n) { return n < x; }), c.end());
 
    std::cout << "c: ";
    std::for_each(c.begin(), c.end(), [](int i){ std::cout << i << ' '; });
    std::cout << '\n';
 
    // the type of a closure cannot be named, but can be inferred with auto
    // since C++14, lambda could own default arguments
    auto func1 = [](int i = 6) { return i + 4; };
    std::cout << "func1: " << func1() << '\n';
 
    // like all callable objects, closures can be captured in std::function
    // (this may incur unnecessary overhead)
    std::function<int(int)> func2 = [](int i) { return i + 4; };
    std::cout << "func2: " << func2(6) << '\n';
 
    constexpr int fib_max {8};
    std::cout << "Emulate `recursive lambda` calls:\nFibonacci numbers: ";
    auto nth_fibonacci = [](int n)
    {
        std::function<int(int, int, int)> fib = [&](int n, int a, int b)
        {
            return n ? fib(n - 1, a + b, a) : b;
        };
        return fib(n, 0, 1);
    };
 
    for (int i{1}; i <= fib_max; ++i)
    {
        std::cout << nth_fibonacci(i) << (i < fib_max ? ", " : "\n");
    }
 
    std::cout << "Alternative approach to lambda recursion:\nFibonacci numbers: ";
    auto nth_fibonacci2 = [](auto self, int n, int a = 0, int b = 1) -> int
    {
        return n ? self(self, n - 1, a + b, a) : b;
    };
 
    for (int i{1}; i <= fib_max; ++i)
    {
        std::cout << nth_fibonacci2(nth_fibonacci2, i) << (i < fib_max ? ", " : "\n");
    }
 
#ifdef __cpp_explicit_this_parameter
    std::cout << "C++23 approach to lambda recursion:\n";
    auto nth_fibonacci3 = [](this auto self, int n, int a = 0, int b = 1)
    {
         return n ? self(n - 1, a + b, a) : b;
    };
 
    for (int i{1}; i <= fib_max; ++i)
    {
        std::cout << nth_fibonacci3(i) << (i < fib_max ? ", " : "\n");
    }
#endif
}
```
* [Lambda expressions in C++ | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/lambda-expressions-in-cpp?view=msvc-160)
    * In C++11 and later, a lambda expression—often called a lambda—is a convenient way of defining an anonymous function object (a closure) right at the location where it's invoked or passed as an argument to a function. Typically lambdas are used to encapsulate a few lines of code that are passed to algorithms or asynchronous functions. This article defines what lambdas are, and compares them to other programming techniques. It describes their advantages, and provides some basic examples.
* [Lambda expression in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/lambda-expression-in-c/)
* [贯穿 C++ 11 与 C++ 17 的 Lambda 到底是个什么？](https://mp.weixin.qq.com/s/ok5xND2q4kPqBguhcvU42g)
    * https://hackernoon.com/all-about-Lambda-functions-in-cfrom-c11-to-c17-2t1j32qw
* [【C++11】让程序更简洁—lambda表达式](https://mp.weixin.qq.com/s/56cH0IK1DbnZX6ZZKVJRwQ)
	* C++11中，Lambda表达式是最常用的特性之一，有过java、python以及C#开发经验的人对lambda功能都不会陌生。lambda表达式来源于函数式编程，具备以下优点：
		* 代码简洁、避免代码膨胀和功能分散，也利于功能维护
		* 功能就近实现，程序更加灵活
		* 函数式编程，可读性强
	* lambda表达式概念和语法
	* 如何修改按值捕获的变量？
	* lambda表达式和std::function配合使用
* [C++11 Lambda : How to capture local variables inside Lambda ? – thisPointer](https://thispointer.com/c11-lambda-how-to-capture-local-variables-inside-lambda/)
    * Capturing Local Variables by value inside Lambda Function
    * Capturing Local Variables by Reference inside Lambda
    * Capture All Local Variables from outer scope by Value
    * Capture all local variables from outer scope by Reference
    * Mixing capturing by value and Reference
    * Be-aware of capturing local variables by Reference in Lambda
* [c++ - an enclosing-function local variable cannot be referenced in a lambda body unless if it is in capture list - Stack Overflow](https://stackoverflow.com/questions/26903602/an-enclosing-function-local-variable-cannot-be-referenced-in-a-lambda-body-unles)
* [C++ Tutorial => Generic lambdas](https://riptutorial.com/cplusplus/example/1969/generic-lambdas)
	* [c++ - How to use lambda auto parameters in C++11 - Stack Overflow](https://stackoverflow.com/questions/30071453/how-to-use-lambda-auto-parameters-in-c11)
	* [c++ - How does generic lambda work in C++14? - Stack Overflow](https://stackoverflow.com/questions/17233547/how-does-generic-lambda-work-in-c14)
* [Lambda Expressions - Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html#Formatting_Lambda_Expressions)
	* Short lambdas may be written inline as function arguments.
```c++
std::set<int> to_remove = {7, 8, 9};
std::vector<int> digits = {3, 9, 1, 8, 4, 7, 1};
digits.erase(std::remove_if(digits.begin(), digits.end(), [&to_remove](int i) {
               return to_remove.find(i) != to_remove.end();
             }),
             digits.end());
```

##### Lambda capture

* The captures is a comma-separated list of zero or more captures, optionally beginning with the capture-default. The capture list defines the outside variables that are accessible from within the lambda function body. The only capture defaults are
	* & (implicitly capture the used automatic variables by reference) and
	* = (implicitly capture the used automatic variables by copy).
* The syntax of an individual capture in captures is

| identifier | (1) |
| - | - |
| identifier ...	| (2)	 |
| identifier initializer	| (3)	(since C++14) |
| & identifier	| (4)	 |
| & identifier ...	| (5) |	
| & identifier initializer	| (6)	(since C++14) |
| this	| (7)	 |
| * this	| (8)	(since C++17) |
| ... identifier initializer	| (9)	(since C++20) |
| & ... identifier initializer	| (10)	(since C++20) |

* 1) simple by-copy capture
* 2) simple by-copy capture that is a pack expansion
* 3) by-copy capture with an initializer
* 4) simple by-reference capture
* 5) simple by-reference capture that is a pack expansion
* 6) by-reference capture with an initializer
* 7) simple by-reference capture of the current object
* 8) simple by-copy capture of the current object
* 9) by-copy capture with an initializer that is a pack expansion
* 10) by-reference capture with an initializer that is a pack expansion

* If the capture-default is &, subsequent simple captures must not begin with &.
```c++
struct S2 { void f(int i); };
void S2::f(int i)
{
    [&]{};          // OK: by-reference capture default
    [&, i]{};       // OK: by-reference capture, except i is captured by copy
    [&, &i] {};     // Error: by-reference capture when by-reference is the default
    [&, this] {};   // OK, equivalent to [&]
    [&, this, i]{}; // OK, equivalent to [&, i]
}
```
* If the capture-default is =, subsequent simple captures must begin with & or be *this (since C++17) or this (since C++20).
```c++
struct S2 { void f(int i); };
void S2::f(int i)
{
    [=]{};        // OK: by-copy capture default
    [=, &i]{};    // OK: by-copy capture, except i is captured by reference
    [=, *this]{}; // until C++17: Error: invalid syntax
                  // since C++17: OK: captures the enclosing S2 by copy
    [=, this] {}; // until C++20: Error: this when = is the default
                  // since C++20: OK, same as [=]
}
```
* Any capture may appear only once, and its name must be different from any parameter name:
```c++
struct S2 { void f(int i); };
void S2::f(int i)
{
    [i, i] {};        // Error: i repeated
    [this, *this] {}; // Error: "this" repeated (C++17)
 
    [i] (int i) {};   // Error: parameter and capture have the same name
}
```
* [F.50: Use a lambda when a function won’t do (to capture local variables, or to write a local function)](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f50-use-a-lambda-when-a-function-wont-do-to-capture-local-variables-or-to-write-a-local-function)
	* `Reason` Functions can’t capture local variables or be defined at local scope; if you need those things, prefer a lambda where possible, and a handwritten function object where not. On the other hand, lambdas and function objects don’t overload; if you need to overload, prefer a function (the workarounds to make lambdas overload are ornate). If either will work, prefer writing a function; use the simplest tool necessary.
	* `Exception` Generic lambdas offer a concise way to write function templates and so can be useful even when a normal function template would do equally well with a little more syntax. This advantage will probably disappear in the future once all functions gain the ability to have Concept parameters.
	* `Enforcement` Warn on use of a named non-generic lambda (e.g., auto x = [](int i) { /*...*/; };) that captures nothing and appears at global scope. Write an ordinary function instead.
* [F.52: Prefer capturing by reference in lambdas that will be used locally, including passed to algorithms](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f52-prefer-capturing-by-reference-in-lambdas-that-will-be-used-locally-including-passed-to-algorithms)
	* Reason 
		* For efficiency and correctness, you nearly always want to capture by reference when using the lambda locally. This includes when writing or calling parallel algorithms that are local because they join before returning.
	* Discussion 
		* The efficiency consideration is that most types are cheaper to pass by reference than by value.
		* The correctness consideration is that many calls want to perform side effects on the original object at the call site (see example below). Passing by value prevents this.
	* Note 
		* Unfortunately, there is no simple way to capture by reference to const to get the efficiency for a local call but also prevent side effects.
	* Example 
		* Here, a large object (a network message) is passed to an iterative algorithm, and it is not efficient or correct to copy the message (which might not be copyable):
    ```c++
    std::for_each(begin(sockets), end(sockets), [&message](auto& socket)
    {
        socket.send(message);
    });
    ```
	* Example 
		* This is a simple three-stage parallel pipeline. Each stage object encapsulates a worker thread and a queue, has a process function to enqueue work, and in its destructor automatically blocks waiting for the queue to empty before ending the thread.
    ```c++
    void send_packets(buffers& bufs)
    {
        stage encryptor([](buffer& b) { encrypt(b); });
        stage compressor([&](buffer& b) { compress(b); encryptor.process(b); });
        stage decorator([&](buffer& b) { decorate(b); compressor.process(b); });
        for (auto& b : bufs) { decorator.process(b); }
    }  // automatically blocks waiting for pipeline to finish
    ```
	* Enforcement 
		* Flag a lambda that captures by reference, but is used other than locally within the function scope or passed to a function by reference. (Note: This rule is an approximation, but does flag passing by pointer as those are more likely to be stored by the callee, writing to a heap location accessed via a parameter, returning the lambda, etc. The Lifetime rules will also provide general rules that flag escaping pointers and references including via lambdas.)
* [F.53: Avoid capturing by reference in lambdas that will be used non-locally, including returned, stored on the heap, or passed to another thread](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f53-avoid-capturing-by-reference-in-lambdas-that-will-be-used-non-locally-including-returned-stored-on-the-heap-or-passed-to-another-thread)
	* Reason 
		* Pointers and references to locals shouldn’t outlive their scope. Lambdas that capture by reference are just another place to store a reference to a local object, and shouldn’t do so if they (or a copy) outlive the scope.
	* Example, bad
    ```c++
    int local = 42;

    // Want a reference to local.
    // Note, that after program exits this scope,
    // local no longer exists, therefore
    // process() call will have undefined behavior!
    thread_pool.queue_work([&] { process(local); });
    ```
	* Example, good
    ```c++
    int local = 42;
    // Want a copy of local.
    // Since a copy of local is made, it will
    // always be available for the call.
    thread_pool.queue_work([=] { process(local); });
    ```
	* Enforcement
		* (Simple) Warn when capture-list contains a reference to a locally declared variable
		* (Complex) Flag when capture-list contains a reference to a locally declared variable and the lambda is passed to a non-const and non-local context
* How to fix compile error `capture of variable with non-automatic storage duration` ?
	* [c++ - Capturing a static variable by reference in a C++11 lambda - Stack Overflow](https://stackoverflow.com/questions/13827855/capturing-a-static-variable-by-reference-in-a-c11-lambda)
		* Why are you even trying to capture bar? It's static. You don't need to capture it at all. Only automatic variables need capturing. Clang throws a hard error on your code, not just a warning. And if you simply remove the &bar from your lambda capture, then the code works perfectly.

#### [Coroutines (C++20)](https://en.cppreference.com/w/cpp/language/coroutines)

* A coroutine is a function that can suspend execution to be resumed later. Coroutines are stackless: they suspend execution by returning to the caller and the data that is required to resume execution is stored separately from the stack. This allows for sequential code that executes asynchronously (e.g. to handle non-blocking I/O without explicit callbacks), and also supports algorithms on lazy-computed infinite sequences and other uses.

#### Callback

* [Callbacks in C - GeeksforGeeks](https://www.geeksforgeeks.org/callbacks-in-c/)
* [Callback functions in C++ - Stack Overflow](https://stackoverflow.com/questions/2298242/callback-functions-in-c)
* [众说纷纭的 C 语言回调函数到底是什么鬼？这里有最好的解答！](https://mp.weixin.qq.com/s/GYnKGqdS0Jj4Seh0HlB9Ug)
* [回调函数 callback 的实现原理是什么？](https://mp.weixin.qq.com/s?__biz=Mzg4OTYzODM4Mw==&mid=2247486528&idx=1&sn=8fdb163df962fb69b9efa72d69a7ca65&chksm=cfe990c0f89e19d67c31bc2a049189d0d6835dd26daa129b7dd22fdaf15a481289fcd0dc2422&scene=21#wechat_redirect)
	* [10张图让你彻底理解回调函数](https://mp.weixin.qq.com/s?__biz=Mzg4OTYzODM4Mw==&mid=2247485712&idx=1&sn=3d2750dfb693f41b2483b51b60a4f44c&chksm=cfe99590f89e1c860277fe1b22c3731ec4e3b61dbb5cd2a6d9548efbc709104a38d6da812517&scene=21#wechat_redirect)
	* [高并发高性能服务器是如何实现的](https://mp.weixin.qq.com/s?__biz=Mzg4OTYzODM4Mw==&mid=2247485713&idx=1&sn=369203957fb922371535df891920dbc1&chksm=cfe99591f89e1c87c68a4e931492d86c1d31e9d83a9b500893106c1d0d5959a56d59f11de7d2&scene=21#wechat_redirect)

### [Statements](https://en.cppreference.com/w/cpp/language/statements)

* [if-else和switch-case哪个效率更高？看这四张图。](https://mp.weixin.qq.com/s/zZ2O1tamQ6NDMneu9kKZRQ)
  * 只有在case中的条件是连续数字或相隔不大时，编译器会使用表结构做优化，性能优于if-else。
  * 其他情况下，switch-case其实就是逐个分支判断，性能与if-else无异。
  * switch-case中的case只能是常量，而if-else用途更广一些，本文仅讨论分支是常量的情况。
* [while(1) 和 for(;;)有什么区别？](https://mp.weixin.qq.com/s/a9g9PAwgc3oXoQXBvT49bA)
	* 你会发现，除了文件名不同，其余都相同。
	* 当然，这里额外说一下，不同代码、不同编译器，以及不同优化等级，可能最终结果有所差异。

#### [if statement](https://en.cppreference.com/w/cpp/language/if)

* Conditionally executes another statement.
* Used where code needs to be executed based on a run-time or compile-time (since C++17) condition, or whether the if statement is evaluated in a manifestly constant-evaluated context (since C++23).
* [ES.87: Don’t add redundant == or != to conditions](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#es87-dont-add-redundant--or--to-conditions)
	* `Reason` Doing so avoids verbosity and eliminates some opportunities for mistakes. Helps make style consistent and conventional.
	* `Example` By definition, a condition in an if-statement, while-statement, or a for-statement selects between true and false. A numeric value is compared to 0 and a pointer value to nullptr.
    ```c++
    // These all mean "if p is not nullptr"
    if (p) { ... }            // good
    if (p != 0) { ... }       // redundant !=0, bad: don't use 0 for pointers
    if (p != nullptr) { ... } // redundant !=nullptr, not recommended
    ```
    * Often, if (p) is read as “if p is valid” which is a direct expression of the programmers intent, whereas if (p != nullptr) would be a long-winded workaround.
    * `Example` This rule is especially useful when a declaration is used as a condition
    ```c++
    if (auto pc = dynamic_cast<Circle>(ps)) { ... } // execute if ps points to a kind of Circle, good
    if (auto pc = dynamic_cast<Circle>(ps); pc != nullptr) { ... } // not recommended
    ```
    * `Example` Note that implicit conversions to bool are applied in conditions. For example:
    * `for (string s; cin >> s; ) v.push_back(s);`
    * This invokes istream’s operator bool().
    * `Note` Explicit comparison of an integer to 0 is in general not redundant. The reason is that (as opposed to pointers and Booleans) an integer often has more than two reasonable values. Furthermore 0 (zero) is often used to indicate success. Consequently, it is best to be specific about the comparison.
    ```c++
    void f(int i)
    {
        if (i)            // suspect
        // ...
        if (i == success) // possibly better
        // ...
    }
    ```
    * Always remember that an integer can have more than two values.
    * `Example, bad` It has been noted that
    * `if(strcmp(p1, p2)) { ... }   // are the two C-style strings equal? (mistake!)`
    * is a common beginners error. If you use C-style strings, you must know the \<cstring> functions well. Being verbose and writing
    * `if(strcmp(p1, p2) != 0) { ... }   // are the two C-style strings equal? (mistake!)`
    * would not in itself save you.
    * `Note` The opposite condition is most easily expressed using a negation:
    ```c++
    // These all mean "if p is nullptr"
    if (!p) { ... }           // good
    if (p == 0) { ... }       // redundant == 0, bad: don't use 0 for pointers
    if (p == nullptr) { ... } // redundant == nullptr, not recommended
    ```
    * Enforcement Easy, just check for redundant use of != and == in conditions.

##### If statements with initializer

* [C++17 If statement with initializer](https://www.tutorialspoint.com/cplusplus17-if-statement-with-initializer#:~:text=Now%20it%20is%20possible%20to,variable%20leaking%20outside%20the%20scope.)
	* C++17 has extended existing if statement’s syntax. Now it is possible to provide initial condition within if statement itself. This new syntax is called "if statement with initializer". This enhancement simplifies common code patterns and helps users keep scopes tight. Which in turn avoids variable leaking outside the scope.
```c++
std::map<int, std::string> m;
std::mutex mx;
extern bool shared_flag; // guarded by mx
 
int demo()
{
    if (auto it = m.find(10); it != m.end()) { return it->second.size(); }
    if (char buf[10]; std::fgets(buf, 10, stdin)) { m[0] += buf; }
    if (std::lock_guard lock(mx); shared_flag) { unsafe_ping(); shared_flag = false; }
    if (int s; int count = ReadBytesWithSignal(&s)) { publish(count); raise(s); }
    if (const auto keywords = {"if", "for", "while"};
        std::ranges::any_of(keywords, [&tok](const char* kw) { return tok == kw; }))
    {
        std::cerr << "Token must not be a keyword\n";
    }
}
```

##### Constexpr if

* The statement that begins with `if constexpr` is known as the `constexpr if statement`.
* In a constexpr if statement, the value of `condition` must be `a contextually converted constant expression of type bool (until C++23)` `an expression contextually converted to bool, where the conversion is a constant expression (since C++23)`. If the value is `true`, then `statement-false` is discarded (if present), otherwise, `statement-true` is discarded.
    * `A contextually converted constant expression of type bool` is an expression, contextually converted to bool, where the converted expression is a constant expression and the conversion sequence contains only the conversions above.
* The return statements in a discarded statement do not participate in function return type deduction:
```c++
template<typename T>
auto get_value(T t)
{
    if constexpr (std::is_pointer_v<T>)
        return *t; // deduces return type to int for T = int*
    else
        return t;  // deduces return type to int for T = int
}
```
* The discarded statement can odr-use a variable that is not defined:
```c++
extern int x; // no definition of x required
 
int f()
{
    if constexpr (true)
        return 0;
    else if (x)
        return x;
    else
        return -x;
}
```
* Outside a template, a discarded statement is fully checked. if constexpr is not a substitute for the #if preprocessing directive:
```c++
void f()
{
    if constexpr(false)
    {
        int i = 0;
        int *p = i; // Error even though in discarded statement
    }
}
```
* ...

###### MISC

* [constexpr if - ModernesCpp.com](https://www.modernescpp.com/index.php/constespr-if)

#### [switch statement](https://en.cppreference.com/w/cpp/language/switch)

* Transfers control to one of several statements, depending on the value of a condition.

##### Syntax

* `attr(optional) switch ( init-statement(optional) condition ) statement`
* `attr` - any number of [attributes](https://en.cppreference.com/w/cpp/language/attributes)
* `init-statement` - (since C++17) either
    * an [expression statement](https://en.cppreference.com/w/cpp/language/statements#Expression_statements) (which may be a null statement ";")
    * a [simple declaration](https://en.cppreference.com/w/cpp/language/declarations#Simple_declaration), typically a declaration of a variable with initializer, but it may declare arbitrarily many variables or [structured bindings](https://en.cppreference.com/w/cpp/language/structured_binding) (since C++17)
    * an [alias declaration](https://en.cppreference.com/w/cpp/language/type_alias) (since C++23)
    * Note that any `init-statement` must end with a semicolon `;`, which is why it is often described informally as an expression or a declaration followed by a semicolon.
* condition	- any [expression](https://en.cppreference.com/w/cpp/language/expressions) of integral or enumeration type, or of a class type [contextually implicitly convertible](https://en.cppreference.com/w/cpp/language/implicit_conversion#Contextual_conversions) to an integral or enumeration type, or a [declaration](https://en.cppreference.com/w/cpp/language/declarations) of a single non-array variable of such type with a brace-or-equals [initializer](https://en.cppreference.com/w/cpp/language/initialization). If the (possibly converted) type is subject to [integral promotions](https://en.cppreference.com/w/cpp/language/implicit_conversion#Integral_promotion), `condition` is converted to the promoted type.
* statement	- any [statement](https://en.cppreference.com/w/cpp/language/statements) (typically a compound statement). `case:` and `default:` labels are permitted in `statement` and `break;` statement has special meaning.
* `attr(optional) case constant-expression : statement`	(1)	
* `attr(optional) default : statement`	(2)	
* `constant-expression` - a constant expression of the same type as the type of `condition` after conversions and [integral promotions](https://en.cppreference.com/w/cpp/language/implicit_conversion#Integral_promotion)

##### Explanation

* If `condition` evaluates to a value that doesn't match any of the `case:` labels, and the `default:` label is not present, then `none` of the statements in the switch body is executed.
* Example
    * The following code shows several usage cases of the switch statement
```c++
#include <iostream>
 
int main()
{
    const int i = 2;
    switch (i)
    {
        case 1:
            std::cout << "1";
        case 2:              // execution starts at this case label
            std::cout << "2";
        case 3:
            std::cout << "3";
            [[fallthrough]]; // C++17 attribute to silent the warning on fall through
        case 5:
            std::cout << "45";
            break;           // execution of subsequent statements is terminated
        case 6:
            std::cout << "6";
    }
 
    std::cout << '\n';
 
    switch (i)
    {
        case 4:
            std::cout << "a";
        default:
            std::cout << "d"; // there are no applicable constant expressions 
                              // therefore default is executed
    }
 
    std::cout << '\n';
 
    switch (i)
    {
        case 4:
            std::cout << "a"; // nothing is executed
    }
 
    // when enumerations are used in a switch statement, many compilers
    // issue warnings if one of the enumerators is not handled
    enum color { RED, GREEN, BLUE };
    switch (RED)
    {
        case RED:
            std::cout << "red\n";
            break;
        case GREEN:
            std::cout << "green\n";
            break;
        case BLUE:
            std::cout << "blue\n";
            break;
    }
 
    // the C++17 init-statement syntax can be helpful when there is
    // no implicit conversion to integral or enumeration type
    struct Device
    {
        enum State { SLEEP, READY, BAD };
        auto state() const { return m_state; }
 
        /*...*/
 
    private:
        State m_state{};
    };
 
    switch (auto dev = Device{}; dev.state())
    {
        case Device::SLEEP:
            /*...*/
            break;
        case Device::READY:
            /*...*/
            break;
        case Device::BAD:
            /*...*/
            break;
    }
 
    // pathological examples
 
    // the statement doesn't have to be a compound statement
    switch (0)
        std::cout << "this does nothing\n";
 
    // labels don't require a compound statement either
    switch (int n = 1)
    {
        case 0:
        case 1:
            std::cout << n << '\n';
    }
}
/*
2345
d
red
1
*/
```

#### [for loop](https://en.cppreference.com/w/cpp/language/for)

* as the declaration of the loop
* Executes init-statement once, then executes statement and iteration-expression repeatedly, until the value of condition becomes false. The test takes place before each iteration.
* [c++ - Is it possible to declare two variables of different types in a for loop? - Stack Overflow](https://stackoverflow.com/questions/2687392/is-it-possible-to-declare-two-variables-of-different-types-in-a-for-loop)
    * C++17: Yes! You should use a structured binding declaration. 
```c++
for (auto [i, f, s] = std::tuple{1, 1.0, std::string{"ab"}}; i < N; ++i, f += 1.5) {
    // ...
}
```

#### [range-based for loop](https://en.cppreference.com/w/cpp/language/range-for)

* as the declaration of the loop (since C++11)
* Executes a for loop over a range.
* Used as a more readable equivalent to the traditional for loop operating over a range of values, such as all elements in a container.
* range-declaration may be a structured binding declaration
	* `for (auto&& [first,second] : mymap) {}`
* [Range-based for loop in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/range-based-loop-c/)
	* C++ 17 or higher: Range-based loops can also be used with maps like this: 
```c++
for (auto& [key, value]: myMap) {
    cout << key << " has value " << value << std::endl;
}
```
* [Will range based for loop in c++ preserve the index order - Stack Overflow](https://stackoverflow.com/questions/19052026/will-range-based-for-loop-in-c-preserve-the-index-order)
	* Yes the two codes are guaranteed to do the same. Though I don't have a link to the standard you can have a look here. I quote: `You can read that as "for all x in v" going through starting with v.begin() and iterating to v.end()`.
	* [C++11 FAQ](https://www.stroustrup.com/C++11FAQ.html#for)
		* Range-for statement
			* A range for statement allows you to iterate through a "range", which is anything you can iterate through like an STL-sequence defined by a begin() and end(). All standard containers can be used as a range, as can a std::string, an initializer list, an array, and anything for which you define begin() and end(), e.g. an istream. For example:
            ```c++
            void f(vector<double>& v)
            {
                for (auto x : v) cout << x << '\n';
                for (auto& x : v) ++x;  // using a reference to allow us to change the value
            }
            ```
			* You can read that as "for all x in v" going through starting with v.begin() and iterating to v.end(). Another example:
				* `for (const auto x : { 1,2,3,5,8,13,21,34 }) cout << x << '\n';`
			* The begin() (and end()) can be a member to be called x.begin() or a free-standing function to be called begin(x). The member version takes precedence.
* [Reverse For Loops in C++ - Fluent C++](https://www.fluentcpp.com/2020/02/11/reverse-for-loops-in-cpp/)
	* It would be nice to be able to use C++11 range for loops to iterate backwards. But unfortunately, there is no such reverse range-for: range-for only works forwards.
	* Let’s see how to traverse a collection backwards by using a range for loop.
	* In C++20: the reverse range adaptor
		* C++20 will bring ranges to the language, including a range adaptor called std::ranges::views::reverse, or std::views::reverse.
		* It allows to traverse a collection in reverse order and can be used this way:
```c++
for (auto const& x : range | std::views::reverse)
{
    foo(x);
}
```
* [Reversed Range-based for loop in C++ with Examples - GeeksforGeeks](https://www.geeksforgeeks.org/reversed-range-based-for-loop-in-c-with-examples/)

### [Classes](https://en.cppreference.com/w/cpp/language/classes)

* A class is a user-defined type.
* A class type is defined by class-specifier, which appears in decl-specifier-seq of the declaration syntax. See class declaration for the syntax of the class specifier.
* A class can have the following kinds of members:
    * 1) data members:
        * a) non-static data members, including bit-fields.
        * b) static data members
    * 2) member functions:
        * a) non-static member functions
        * b) static member functions
    * 3) nested types:
        * a) nested classes and enumerations defined within the class definition
        * b) aliases of existing types, defined with typedef or type alias (since C++11)declarations
        * c) the name of the class within its own definition acts as a public member type alias of itself for the purpose of lookup (except when used to name a constructor): this is known as injected-class-name
    * 4) enumerators from all unscoped enumerations defined within the class, or introduced by using-declarations or using-enum-declarations (since C++20)
    * 5) member templates (variable templates, (since C++14)class templates or function templates) may appear in the body of any non-local class/struct/union.
* All members are defined at once in the class definition, they cannot be added to an already-defined class (unlike the members of namespaces)
* A member of a class T cannot use T as its name if the member is
    * a static data member,
    * a member function,
    * a member type,
    * a member template,
    * an enumerator of an enumeration (unless the enumeration is scoped) (since C++11), or
    * a member of a member anonymous union.
* However, a non-static data member may use the name T as long as there are no user-declared constructors.
* A class with at least one declared or inherited virtual member function is polymorphic. Objects of this type are polymorphic objects and have runtime type information stored as part of the object representation, which may be queried with dynamic_cast and typeid. Virtual member functions participate in dynamic binding.
* A class with at least one declared or inherited pure virtual member function is an abstract class. Objects of this type cannot be created.
* A class with a constexpr constructor is a LiteralType: objects of this type can be manipulated by constexpr functions at compile time. (since C++11)
* Properties of classes
    * Trivially copyable class
        * A trivially copyable class is a class that
            * has at least one eligible copy constructor, move constructor, copy assignment operator, or move assignment operator,
            * each eligible copy constructor is trivial
            * each eligible move constructor is trivial
            * each eligible copy assignment operator is trivial
            * each eligible move assignment operator is trivial, and
            * has a non-deleted trivial destructor.
    * Trivial class
        * A trivial class is a class that
            * is trivially copyable, and
            * has one or more eligible default constructors such that each is trivial.
    * Standard-layout class
        * A standard-layout class is a class that
            * has no non-static data members of type non-standard-layout class (or array of such types) or reference,
            * has no virtual functions and no virtual base classes,
            * has the same access control for all non-static data members,
            * has no non-standard-layout base classes,
            * only one class in the hierarchy has non-static data members, and
            * Informally, none of the base classes has the same type as the first non-static data member. Or, formally: given the class as S, has no element of the set M(S) of types as a base class, where M(X) for a type X is defined as:
                * If X is a non-union class type with no (possibly inherited) non-static data members, the set M(X) is empty.
                * If X is a non-union class type whose first non-static data member has type X0 (where said member may be an anonymous union), the set M(X) consists of X0 and the elements of M(X0).
                * If X is a union type, the set M(X) is the union of all M(Ui) and the set containing all Ui, where each Ui is the type of the ith non-static data member of X.
                * If X is an array type with element type Xe, the set M(X) consists of Xe and the elements of M(Xe).
                * If X is a non-class, non-array type, the set M(X) is empty.
        * A standard-layout struct is a standard-layout class defined with the class keyword struct or the class keyword class. A standard-layout union is a standard-layout class defined with the class keyword union.
* class v.s. struct
	* [C.1: Organize related data into structures (structs or classes)](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c1-organize-related-data-into-structures-structs-or-classes)
		* Reason Ease of comprehension. If data is related (for fundamental reasons), that fact should be reflected in code.
		* Example
		```c++
		void draw(int x, int y, int x2, int y2);  // BAD: unnecessary implicit relationships
		void draw(Point from, Point to);          // better
		```
		* Note A simple class without virtual functions implies no space or time overhead.
		* Note From a language perspective class and struct differ only in the default visibility of their members.
		* Enforcement Probably impossible. Maybe a heuristic looking for data items used together is possible.
	* [C.8: Use class rather than struct if any member is non-public](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c8-use-class-rather-than-struct-if-any-member-is-non-public)

#### Members

##### [Non-static data members](https://en.cppreference.com/w/cpp/language/data_members)

* Non-static data members are declared in a member specification of a class.
```c++
class S
{
    int n;              // non-static data member
    int& r;             // non-static data member of reference type
    int a[2] = {1, 2};  // non-static data member with default member initializer (C++11)
    std::string s, *ps; // two non-static data members
 
    struct NestedS
    {
        std::string s;
    } d5;               // non-static data member of nested type
 
    char bit : 2;       // two-bit bitfield
};
```
* Any simple declarations are allowed, except
    * extern and register storage class specifiers are not allowed;
    * thread_local storage class specifier is not allowed (but it is allowed for static data members); (since C++11)
    * incomplete types, abstract class types, and arrays thereof are not allowed: in particular, a class C cannot have a non-static data member of type C, although it can have a non-static data member of type C& (reference to C) or C* (pointer to C);
    * a non-static data member cannot have the same name as the name of the class if at least one user-declared constructor is present;
    * a placeholder type specifier (i.e. auto, decltype(auto) (since C++14), a class template name subject to deduction (since C++17), a constrained placeholder (since C++20)) cannot be used in a non-static data member declaration (although it is allowed for static data members that are initialized in the class definition). (since C++11)
* In addition, bit-field declarations are allowed.

##### [static members](https://en.cppreference.com/w/cpp/language/static)

* Inside a class definition, the keyword `static` declares members that are not bound to class instances.
* Outside a class definition, it has a different meaning: see storage duration.

##### [Non-static member functions](https://en.cppreference.com/w/cpp/language/member_functions)

* A non-static member function is a function that is declared in a member specification of a class without a `static` or `friend specifier`. (see static member functions and friend declaration for the effect of those keywords)
```c++
class S
{
    int mf1(); // non-static member function declaration
    void mf2() volatile, mf3() &&; // can have cv-qualifiers and/or a reference-qualifier
        // the declaration above is equivalent to two separate declarations:
        // void mf2() volatile;
        // void mf3() &&;
 
    int mf4() const { return data; } // can be defined inline
    virtual void mf5() final; // can be virtual, can use final/override
    S() : data(12) {} // constructors are member functions too
    int data;
};
 
int S::mf1() { return 7; } // if not defined inline, has to be defined at namespace
```
* Constructors, destructors, and conversion functions use special syntaxes for their declarations. The rules described in this page may not apply to these functions. See their respective pages for details.
* Any function declarations are allowed, with additional syntax elements that are only available for non-static member functions: pure-specifiers, cv-qualifiers, ref-qualifiers, final and override specifiers (since C++11), and member initialization lists.

###### member functions with cv-qualifiers

* A non-static member function can be declared with a cv-qualifier sequence (const, volatile, or a combination of const and volatile), this sequence appears after the parameter list in the function declaration. Functions with different cv-qualifier sequences (or no sequence) have different types and so may overload each other.
* In the body of a function with a cv-qualifier sequence, *this is cv-qualified, e.g. in a member function with const qualifier, only other member functions with const qualifier may be called normally. (A member function without const qualifier may still be called if const_cast is applied or through an access path that does not involve this.)
```c++
#include <vector>
 
struct Array
{
    std::vector<int> data;
    Array(int sz) : data(sz) {}
 
    // const member function
    int operator[](int idx) const
    {                     // the this pointer has type const Array*
        return data[idx]; // transformed to (*this).data[idx];
    }
 
    // non-const member function
    int& operator[](int idx)
    {                     // the this pointer has type Array*
        return data[idx]; // transformed to (*this).data[idx]
    }
};
 
int main()
{
    Array a(10);
    a[1] = 1;  // OK: the type of a[1] is int&
    const Array ca(10);
    ca[1] = 2; // Error: the type of ca[1] is int
}
```
* [c++ - Calling a const function rather than its non-const version - Stack Overflow](https://stackoverflow.com/questions/7287065/calling-a-const-function-rather-than-its-non-const-version)
    * If you have two overloads that differ only in their const-ness, then the compiler resolves the call based on whether *this is const or not. In your example code, test is not const, so the non-const overload is called.
    * If you did this:
    ```c++
    testType test;
    const testType &test2 = test;
    test2->x();
    ```
    * you should see that the other overload gets called, because test2 is const.
* [Const member functions in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/const-member-functions-c/#:~:text=To%20make%20a%20member%20function,also%20be%20declared%20as%20const.)

##### [Constructors and member initializer lists](https://en.cppreference.com/w/cpp/language/constructor)

* Constructor is a special non-static [member function](https://en.cppreference.com/w/cpp/language/member_functions) of a class that is used to initialize objects of its class type.
* In the definition of a constructor of a class, member initializer list specifies the initializers for direct and virtual bases and non-static data members. (Not to be confused with [std::initializer_list](https://en.cppreference.com/w/cpp/utility/initializer_list).)
* A constructor must not be a [coroutine](https://en.cppreference.com/w/cpp/language/coroutines). (since C++20)
* Example
```c++
#include <fstream>
#include <string>
#include <mutex>
 
struct Base
{
    int n;
};   
 
struct Class : public Base
{
    unsigned char x;
    unsigned char y;
    std::mutex m;
    std::lock_guard<std::mutex> lg;
    std::fstream f;
    std::string s;
 
    Class(int x) : Base{123}, // initialize base class
        x(x),     // x (member) is initialized with x (parameter)
        y{0},     // y initialized to 0
        f{"test.cc", std::ios::app}, // this takes place after m and lg are initialized
        s(__func__), // __func__ is available because init-list is a part of constructor
        lg(m),    // lg uses m, which is already initialized
        m{}       // m is initialized before lg even though it appears last here
    {}            // empty compound statement
 
    Class(double a) : y(a + 1),
        x(y), // x will be initialized before y, its value here is indeterminate
        lg(m)
    {} // base class initializer does not appear in the list, it is
       // default-initialized (not the same as if Base() were used, which is value-init)
 
    Class()
    try // function-try block begins before the function body, which includes init list
      : Class(0.0) // delegate constructor
    {
        // ...
    }
    catch (...)
    {
        // exception occurred on initialization
    }
};
 
int main()
{
    Class c;
    Class c1(1);
    Class c2(0.1);
}
```

##### [Default member initializer](https://en.cppreference.com/w/cpp/language/data_members#Member_initialization)

* Non-static data members may be initialized in one of two ways:
    * 1) In the member initializer list of the constructor.
    ```c++
    struct S
    {
        int n;
        std::string s;
        S() : n(7) {} // direct-initializes n, default-initializes s
    };
    ```
    * 2) Through a default member initializer, which is a brace or equals initializer included in the member declaration and is used if the member is omitted from the member initializer list of a constructor.
    ```c++
    struct S
    {
        int n = 7;
        std::string s{'a', 'b', 'c'};
        S() {} // default member initializer will copy-initialize n, list-initialize s
    };
    ```
    * If a member has a default member initializer and also appears in the member initialization list in a constructor, the default member initializer is ignored for that constructor.
    ```c++
    #include <iostream>

    int x = 0;
    struct S
    {
        int n = ++x;
        S() {}                 // uses default member initializer
        S(int arg) : n(arg) {} // uses member initializer 
    };

    int main()
    {
        std::cout << x << '\n'; // prints 0
        S s1;                   // default initializer ran
        std::cout << x << '\n'; // prints 1
        S s2(7);                // default initializer did not run
        std::cout << x << '\n'; // prints 1
    }
    ```
* How to fix error `Vector declaration "expected parameter declarator"` ?
    * [c++ - Vector declaration "expected parameter declarator" - Stack Overflow](https://stackoverflow.com/questions/39560277/vector-declaration-expected-parameter-declarator)
    * [c++ - Why can't member initializers use parentheses? - Stack Overflow](https://stackoverflow.com/questions/24836526/why-cant-member-initializers-use-parentheses)
    * You have to initialize the variable in the constructor's initializer list:
```c++
class X 
{
    private:
     vector<double> dQdt;
    public:
     X() : dQdt(3) {}
};
```

##### [Friend declaration](https://en.cppreference.com/w/cpp/language/friend)

* The friend declaration appears in a class body and grants a function or another class access to private and protected members of the class where the friend declaration appears.
* Description
    * 1) Designates a function or several functions as friends of this class:
    ```c++
    class Y
    {
        int data; // private member

        // the non-member function operator<< will have access to Y's private members
        friend std::ostream& operator<<(std::ostream& out, const Y& o);
        friend char* X::foo(int); // members of other classes can be friends too
        friend X::X(char), X::~X(); // constructors and destructors can be friends
    };

    // friend declaration does not declare a member function
    // this operator<< still needs to be defined, as a non-member
    std::ostream& operator<<(std::ostream& out, const Y& y)
    {
        return out << y.data; // can access private member Y::data
    }
    ```
    * 2) (only allowed in non-local class definitions) Defines a non-member function, and makes it a friend of this class at the same time. Such non-member function is always inline, unless it is attached to a named module (since C++20).
    ```c++
    class X
    {
        int a;

        friend void friend_set(X& p, int i)
        {
            p.a = i; // this is a non-member function
        }
    public:
        void member_set(int i)
        {
            a = i; // this is a member function
        }
    };
    ```
    * 3) Designates the class, struct, or union named by the elaborated-class-specifier (see elaborated type specifier) as a friend of this class. This means that the friend's member declarations and definitions can access private and protected members of this class and also that the friend can inherit from private and protected members of this class. The name of the class that is used in this friend declaration does not need to be previously declared.
    * 4) Designates the type named by the simple-type-specifier or typename-specifier as a friend of this class if that type is a (possibly cv-qualified) class, struct, or union; otherwise the friend declaration is ignored. This declaration will not forward declare a new type.
    ```c++
    class Y {};

    class A
    {
        int data; // private data member

        class B {}; // private nested type

        enum { a = 100 }; // private enumerator

        friend class X; // friend class forward declaration (elaborated class specifier)
        friend Y; // friend class declaration (simple type specifier) (since c++11)
    };

    class X : A::B // OK: A::B accessible to friend
    {
        A::B mx; // OK: A::B accessible to member of friend

        class Y
        {
            A::B my; // OK: A::B accessible to nested member of friend
        };

        int v[A::a]; // OK: A::a accessible to member of friend
    };
    ```
* Notes
    * Friendship is not transitive (a friend of your friend is not your friend).
    * Friendship is not inherited (your friend's children are not your friends).
    * Storage class specifiers are not allowed in friend function declarations. A function that is defined in the friend declaration has external linkage, a function that was previously defined, keeps the linkage it was defined with.
    * Access specifiers have no effect on the meaning of friend declarations (they can appear in private: or in public: sections, with no difference).
    * A friend class declaration cannot define a new class (friend class X {}; is an error).
    * When a local class declares an unqualified function or class as a friend, only functions and classes in the innermost non-class scope are looked up, not the global functions
* Template friends
    * Both function template and class template declarations may appear with the friend specifier in any non-local class or class template (although only function templates may be defined within the class or class template that is granting friendship). In this case, every specialization of the template becomes a friend, whether it is implicitly instantiated, partially specialized, or explicitly specialized.
* Template friend operators
    * A common use case for template friends is declaration of a non-member operator overload that acts on a class template, e.g. operator<<(std::ostream&, const Foo\<T>&) for some user-defined Foo\<T>.
    * Such operator can be defined in the class body, which has the effect of generating a separate non-template operator<< for each T and makes that non-template operator<< a friend of its Foo\<T>
    * or the function template has to be declared as a template before the class body, in which case the friend declaration within Foo\<T> can refer to the full specialization of operator<< for its T:
```c++
#include <iostream>
#include <sstream>
 
class MyClass
{
    int i;                   // friends have access to non-public, non-static
    static inline int id{6}; // and static (possibly inline) members
 
    friend std::ostream& operator<<(std::ostream& out, const MyClass&);
    friend std::istream& operator>>(std::istream& in, MyClass&);
    friend void change_id(int);
public:
    MyClass(int i = 0) : i(i) {}
};
 
std::ostream& operator<<(std::ostream& out, const MyClass& mc)
{
    return out << "MyClass::id = " << MyClass::id << "; i = " << mc.i;
}
 
std::istream& operator>>(std::istream& in, MyClass& mc)
{
    return in >> mc.i;
}
 
void change_id(int id) { MyClass::id = id; }
 
int main()
{
    MyClass mc(7);
    std::cout << mc << '\n';
//  mc.i = 333*2;  // error: i is a private member
    std::istringstream("100") >> mc;
    std::cout << mc << '\n';
//  MyClass::id = 222*3;  // error: id is a private member
    change_id(9);
    std::cout << mc << '\n';
}
Output:

MyClass::id = 6; i = 7
MyClass::id = 6; i = 100
MyClass::id = 9; i = 100
```
* [C++ Friend Functions](https://www.tutorialspoint.com/cplusplus/cpp_friend_functions.htm)
    * A friend function of a class is defined outside that class' scope but it has the right to access all private and protected members of the class. Even though the prototypes for friend functions appear in the class definition, friends are not member functions.
    * A friend can be a function, function template, or member function, or a class or class template, in which case the entire class and all of its members are friends.
* [Friend class and function in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/friend-class-function-cpp/)
    * Merits:
        * A friend function is able to access members without the need of inheriting the class.
        * Friend function acts as a bridge between two classes by accessing their private data.
        * It can be used to increase the versatility of overloaded operator.
        * It can be declared either in the public or private or protected part of class.
    * Demerits:
        * Friend functions have access to private members of a class from outside the class which violates the law of the data hiding.
        * Friend functions cannot do any run time polymorphism in its members.

##### [explicit specifier](https://en.cppreference.com/w/cpp/language/explicit)

* expression	-	contextually converted constant expression of type bool
    * 1) Specifies that a constructor or conversion function (since C++11) or deduction guide (since C++17) is explicit, that is, it cannot be used for implicit conversions and copy-initialization.
    * 2) The explicit specifier may be used with a constant expression. The function is explicit if and only if that constant expression evaluates to true. (since C++20)
* The explicit specifier may only appear within the decl-specifier-seq of the declaration of a constructor or conversion function (since C++11) within its class definition.
* [如何避免类构造函数中的隐式转换](https://mp.weixin.qq.com/s/VrMHxOwDkzTIfPFXVuaOJw)
    * 为了避免这种情况的发生，C++提供了explicit关键字，通过在构造函数前加上该关键字可以避免隐式类型转换。当然，explicit也有其自身的生效范围。如：
    * explicit只能对具有一个参数的构造函数有效。如果有多个可能不生效
    * 如果构造函数存在多个参数，那么需要将其余的参数以默认值参数的方式使用。这样explicit关键字将继续生效。
```c++
struct A
{
    A(int) { }      // converting constructor
    A(int, int) { } // converting constructor (C++11)
    operator bool() const { return true; }
};
 
struct B
{
    explicit B(int) { }
    explicit B(int, int) { }
    explicit operator bool() const { return true; }
};
 
int main()
{
    A a1 = 1;      // OK: copy-initialization selects A::A(int)
    A a2(2);       // OK: direct-initialization selects A::A(int)
    A a3 {4, 5};   // OK: direct-list-initialization selects A::A(int, int)
    A a4 = {4, 5}; // OK: copy-list-initialization selects A::A(int, int)
    A a5 = (A)1;   // OK: explicit cast performs static_cast
    if (a1) { }    // OK: A::operator bool()
    bool na1 = a1; // OK: copy-initialization selects A::operator bool()
    bool na2 = static_cast<bool>(a1); // OK: static_cast performs direct-initialization
 
//  B b1 = 1;      // error: copy-initialization does not consider B::B(int)
    B b2(2);       // OK: direct-initialization selects B::B(int)
    B b3 {4, 5};   // OK: direct-list-initialization selects B::B(int, int)
//  B b4 = {4, 5}; // error: copy-list-initialization does not consider B::B(int, int)
    B b5 = (B)1;   // OK: explicit cast performs static_cast
    if (b2) { }    // OK: B::operator bool()
//  bool nb1 = b2; // error: copy-initialization does not consider B::operator bool()
    bool nb2 = static_cast<bool>(b2); // OK: static_cast performs direct-initialization
 
    [a4, a5, na1, na2, b5, nb2] { }; // may suppress "unused variable" warnings
}
```

#### Special member functions

* Some member functions are special: under certain circumstances they are defined by the compiler even if not defined by the user. They are:
    * Default constructor
    * Copy constructor
    * Move constructor (since C++11)
    * Copy assignment operator
    * Move assignment operator (since C++11)
    * Destructor (until C++20)Prospective destructor (since C++20)
* Special member functions along with the comparison operators (since C++20) are the only functions that can be defaulted, that is, defined using `= default` instead of the function body (see their pages for details).
* [C++中 =defaule 和 =delete 使用](https://mp.weixin.qq.com/s/XRuLVEF1Yhsmm52t-l010w)
	* C++的类有四类特殊成员函数，它们分别是：默认构造函数、析构函数、拷贝构造函数、拷贝赋值运算符。如果实际编码时没有显示定义，那么编译器将会默认生成这四类成员函数。使用=default和=delete可以控制编译器默认函数体的使用。
	* 1 =default
		* C++11新增了=default标识，编译器看到后，会生成默认的执行效率更高的函数定义体，同时会减轻编码时的工作量。当然，这里会引入一个问题，既然编译器会默认生成构造函数，那么=default的优势在哪里呢？
		* =default就给我们提供了这样一个功能，加上之后，编译器就会给我们默认生成函数体，减轻工作量。上面的类就这可以这些写：
        ```c++
        class Test{
        public:
            Test(int a):x(a){};
            Test()=default;
        private:
            int x;
        };
        ```
		* 当然，=default不但可以在类成员内部添加也可以在类之外添加，但是使用=default时，必须遵守一个准则：default 函数特性只能用于类的特殊成员函数或者函数没有默认参数。=default写在类之外的方式如下：
        ```c++
        class Test{
        public:
            Test(int a):x(a){};
            Test()=default;
            Test(const Test& ts);
            Test& operator = (const Test& ts);
        private:
            int x;
        };
        Test::Test(const Test& ts) =default;
        Test& Test::operator = (const Test& ts) =default;
        ```
		* 上面的代码中演示了=default在类成员外部使用的场景。但是类中确没有析构函数，编码时，如果涉及到类的继承和派生，尤其是通过基类指针指向了派生类对象，当调用delete删除派生对象时，如果基类没有显示定义析构函数，编译器会为基类默认生成析构函数，基类对象会被正常释放，但是也会产生一个问题，派生类没有正确释放，可能会产生内存泄露等问题。正确解决这种问题的做法是在基类中显示定义一个虚析构函数。这种方法在C++11之前是我们解决这种问题经常使用的，但是C++11之后，可以使用=default，从而减轻我们的编码量，且编译器生成的代码效率更高。
        ```c++
        class Base{
        public:
            virtual ~Base()=default;
        private:
            int x;
        };
        class A : public Base{
        private:
            int y;
        };
        int main ()
        {
          Base *pBase = new A;
          delete pBase;
          return 0;
        }
        ```
	* 2 =delete
		* C++11之前，delete是和new配对使用的，释放程序在堆上开辟得空间，将资源返还给操作系统，C++11之后，delete又多了一个含义既：禁用成员函数的使用。使用方法为：在函数名称后面加上=delete。
		* 如果不想在传入非整型的数据时编译通过，就可以使用=delete来抑制这种问题的产生。如使用=delete解决上面的问题
        ```c++
        class Test { 
        public: 
            Test(int a):x(a) {std::cout<<x<<std::endl;} 
            Test(double)=delete;
        private:
            int x;
        }; 
        int main() { 
            Test test1(1); 
            Test test2(1.1);  
            return 0;
        ```
		* 如上可知，使用=delete后，可以使我们禁用一些不需要编译器生成的默认函数，还可以避免因为数据类型原因导致的错误的函数调用。

##### [Default constructors](https://en.cppreference.com/w/cpp/language/default_constructor)

* A default constructor is a constructor which can be called with no arguments (either defined with an empty parameter list, or with default arguments provided for every parameter). A type with a public default constructor is DefaultConstructible.
* Explanation
    1) Declaration of a default constructor inside of class definition.
    2) Definition of the constructor outside of class definition (the class must contain a declaration (1)). See constructors and member initializer lists for details on the constructor body.
    3) Deleted default constructor: if it is selected by overload resolution, the program fails to compile.
    4) Defaulted default constructor: the compiler will define the implicit default constructor even if other constructors are present.
    5) Defaulted default constructor outside of class definition (the class must contain a declaration (1)). Such constructor is treated as user-provided (see below and value initialization).
* Default constructors are called during default initializations and value initializations.
* Implicitly-declared default constructor
    * If no user-declared constructors of any kind are provided for a class type (struct, class, or union), the compiler will always declare a default constructor as an inline public member of its class.
    * If some user-declared constructors are present, the user may still force the automatic generation of a default constructor by the compiler that would be implicitly-declared otherwise with the keyword default. (since C++11)
    * The implicitly-declared (or defaulted on its first declaration) default constructor has an exception specification as described in dynamic exception specification (until C++17)exception specification (since C++17).
* Implicitly-defined default constructor
    * If the implicitly-declared default constructor is not defined as deleted, it is defined (that is, a function body is generated and compiled) by the compiler if odr-used or needed for constant evaluation (since C++11), and it has the same effect as a user-defined constructor with empty body and empty initializer list. That is, it calls the default constructors of the bases and of the non-static members of this class. Class types with an empty user-provided constructor may get treated differently than those with an implicitly-defined or defaulted default constructor during value initialization.
    * If this satisfies the requirements of a constexpr constructor (until C++23)constexpr function (since C++23), the generated constructor is constexpr.
    * If some user-defined constructors are present, the user may still force the automatic generation of a default constructor by the compiler that would be implicitly-declared otherwise with the keyword default. (since C++11)
* Deleted implicitly-declared default constructor
* Trivial default constructor
* Eligible default constructor
    * A default constructor is eligible if
        * it is not deleted, and
        * its associated constraints, if any, are satisfied, and
        * no default constructor is more constrained than it. (since C++20)
    * Triviality of eligible default constructors determines whether the class is an [implicit-lifetime type](https://en.cppreference.com/w/cpp/language/lifetime#Implicit-lifetime_types), and whether the class is a [trivial type](https://en.cppreference.com/w/cpp/named_req/TrivialType).
```c++
struct A
{
    int x;
    A(int x = 1): x(x) {} // user-defined default constructor
};
 
struct B: A
{
    // B::B() is implicitly-defined, calls A::A()
};
 
struct C
{
    A a;
    // C::C() is implicitly-defined, calls A::A()
};
 
struct D: A
{
    D(int y): A(y) {}
    // D::D() is not declared because another constructor exists
};
 
struct E: A
{
    E(int y): A(y) {}
    E() = default; // explicitly defaulted, calls A::A()
};
 
struct F
{
    int& ref; // reference member
    const int c; // const member
    // F::F() is implicitly defined as deleted
};
 
// user declared copy constructor (either user-provided, deleted or defaulted)
// prevents the implicit generation of a default constructor
 
struct G
{
    G(const G&) {}
    // G::G() is implicitly defined as deleted
};
 
struct H
{
    H(const H&) = delete;
    // H::H() is implicitly defined as deleted
};
 
struct I
{
    I(const I&) = default;
    // I::I() is implicitly defined as deleted
};
 
int main()
{
    A a;
    B b;
    C c;
//  D d; // compile error
    E e;
//  F f; // compile error
//  G g; // compile error
//  H h; // compile error
//  I i; // compile error
}
```
* [C.49: Prefer initialization to assignment in constructors](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c49-prefer-initialization-to-assignment-in-constructors)
	* `Reason` An initialization explicitly states that initialization, rather than assignment, is done and can be more elegant and efficient. Prevents “use before set” errors.
    ```c++
    class D {   // Good
        string s1;
    public:
        D(string_view v) : s1{v} { }    // GOOD: directly construct
        // ...
    };
    ```

##### [Copy constructors](https://en.cppreference.com/w/cpp/language/copy_constructor)

* A copy constructor of class T is a non-template constructor whose first parameter is T&‍, const T&‍, volatile T&‍, or const volatile T&‍, and either there are no other parameters, or the rest of the parameters all have default values.
* Notes
    * In many situations, copy constructors are optimized out even if they would produce observable side-effects, see [copy elision](https://en.cppreference.com/w/cpp/language/copy_elision).
```c++
struct A
{
    int n;
    A(int n = 1) : n(n) {}
    A(const A& a) : n(a.n) {} // user-defined copy constructor
};
 
struct B : A
{
    // implicit default constructor B::B()
    // implicit copy constructor B::B(const B&)
};
 
struct C : B
{
    C() : B() {}
private:
    C(const C&); // non-copyable, C++98 style
};
 
int main()
{
    A a1(7);
    A a2(a1); // calls the copy constructor
 
    B b;
    B b2 = b;
    A a3 = b; // conversion to A& and copy constructor
 
    volatile A va(10);
    // A a4 = va; // compile error
 
    C c;
    // C c2 = c; // compile error
}
```

##### [Move constructors](https://en.cppreference.com/w/cpp/language/move_constructor)

* A move constructor of class T is a non-template constructor whose first parameter is T&&, const T&&, volatile T&&, or const volatile T&&, and either there are no other parameters, or the rest of the parameters all have default values.
* Notes
    * To make the strong exception guarantee possible, user-defined move constructors should not throw exceptions. For example, std::vector relies on std::move_if_noexcept to choose between move and copy when the elements need to be relocated.
    * If both copy and move constructors are provided and no other constructors are viable, overload resolution selects the move constructor if the argument is an rvalue of the same type (an xvalue such as the result of std::move or a prvalue such as a nameless temporary (until C++17)), and selects the copy constructor if the argument is an lvalue (named object or a function/operator returning lvalue reference). If only the copy constructor is provided, all argument categories select it (as long as it takes a reference to const, since rvalues can bind to const references), which makes copying the fallback for moving, when moving is unavailable.
    * A constructor is called a 'move constructor' when it takes an rvalue reference as a parameter. It is not obligated to move anything, the class is not required to have a resource to be moved and a 'move constructor' may not be able to move a resource as in the allowable (but maybe not sensible) case where the parameter is a const rvalue reference (const T&&).
```c++
#include <string>
#include <iostream>
#include <iomanip>
#include <utility>
 
struct A
{
    std::string s;
    int k;
 
    A() : s("test"), k(-1) {}
    A(const A& o) : s(o.s), k(o.k) { std::cout << "move failed!\n"; }
    A(A&& o) noexcept :
        s(std::move(o.s)),       // explicit move of a member of class type
        k(std::exchange(o.k, 0)) // explicit move of a member of non-class type
    {}
};
 
A f(A a)
{
    return a;
}
 
struct B : A
{
    std::string s2;
    int n;
    // implicit move constructor B::(B&&)
    // calls A's move constructor
    // calls s2's move constructor
    // and makes a bitwise copy of n
};
 
struct C : B
{
    ~C() {} // destructor prevents implicit move constructor C::(C&&)
};
 
struct D : B
{
    D() {}
    ~D() {}           // destructor would prevent implicit move constructor D::(D&&)
    D(D&&) = default; // forces a move constructor anyway
};
 
int main()
{
    std::cout << "Trying to move A\n";
    A a1 = f(A()); // return by value move-constructs the target
                   // from the function parameter
 
    std::cout << "Before move, a1.s = " << std::quoted(a1.s)
        << " a1.k = " << a1.k << '\n';
 
    A a2 = std::move(a1); // move-constructs from xvalue
    std::cout << "After move, a1.s = " << std::quoted(a1.s)
        << " a1.k = " << a1.k << '\n';
 
 
    std::cout << "\nTrying to move B\n";
    B b1;
 
    std::cout << "Before move, b1.s = " << std::quoted(b1.s) << "\n";
 
    B b2 = std::move(b1); // calls implicit move constructor
    std::cout << "After move, b1.s = " << std::quoted(b1.s) << "\n";
 
 
    std::cout << "\nTrying to move C\n";
    C c1;
    C c2 = std::move(c1); // calls copy constructor
 
    std::cout << "\nTrying to move D\n";
    D d1;
    D d2 = std::move(d1);
}
/*
Trying to move A
Before move, a1.s = "test" a1.k = -1
After move, a1.s = "" a1.k = 0
 
Trying to move B
Before move, b1.s = "test"
After move, b1.s = ""
 
Trying to move C
move failed!
 
Trying to move D
*/
```

##### [Copy assignment operator](https://en.cppreference.com/w/cpp/language/copy_assignment)

* A copy assignment operator of class T is a non-template non-static member function with the name operator= that takes exactly one parameter of type T, T&, const T&, volatile T&, or const volatile T&. For a type to be CopyAssignable, it must have a public copy assignment operator.
* Notes
    * If both copy and move assignment operators are provided, overload resolution selects the move assignment if the argument is an rvalue (either a prvalue such as a nameless temporary or an xvalue such as the result of std::move), and selects the copy assignment if the argument is an lvalue (named object or a function/operator returning lvalue reference). If only the copy assignment is provided, all argument categories select it (as long as it takes its argument by value or as reference to const, since rvalues can bind to const references), which makes copy assignment the fallback for move assignment, when move is unavailable.
    * It is unspecified whether virtual base class subobjects that are accessible through more than one path in the inheritance lattice, are assigned more than once by the implicitly-defined copy assignment operator (same applies to move assignment).
    * See assignment operator overloading for additional detail on the expected behavior of a user-defined copy-assignment operator.
```c++
#include <iostream>
#include <memory>
#include <string>
#include <algorithm>
 
struct A
{
    int n;
    std::string s1;
 
    A() = default;
    A(A const&) = default;
 
    // user-defined copy assignment (copy-and-swap idiom)
    A& operator=(A other)
    {
        std::cout << "copy assignment of A\n";
        std::swap(n, other.n);
        std::swap(s1, other.s1);
        return *this;
    }
};
 
struct B : A
{
    std::string s2;
    // implicitly-defined copy assignment
};
 
struct C
{
    std::unique_ptr<int[]> data;
    std::size_t size;
 
    // user-defined copy assignment (non copy-and-swap idiom)
    // note: copy-and-swap would always reallocate resources
    C& operator=(const C& other)
    {
        if (this != &other) // not a self-assignment
        {
            if (size != other.size) // resource cannot be reused
            {
                data.reset(new int[other.size]);
                size = other.size;
            }
            std::copy(&other.data[0], &other.data[0] + size, &data[0]);
        }
        return *this;
    }
};
 
int main()
{
    A a1, a2;
    std::cout << "a1 = a2 calls ";
    a1 = a2; // user-defined copy assignment
 
    B b1, b2;
    b2.s1 = "foo";
    b2.s2 = "bar";
    std::cout << "b1 = b2 calls ";
    b1 = b2; // implicitly-defined copy assignment
 
    std::cout << "b1.s1 = " << b1.s1 << "; b1.s2 = " << b1.s2 << '\n';
}
/*
a1 = a2 calls copy assignment of A
b1 = b2 calls copy assignment of A
b1.s1 = foo; b1.s2 = bar
*/
```

##### [Move assignment operator](https://en.cppreference.com/w/cpp/language/move_assignment)

* A move assignment operator of class T is a non-template non-static member function with the name operator= that takes exactly one parameter of type T&&, const T&&, volatile T&&, or const volatile T&&.
* Syntax
    * class-name & class-name :: operator= ( class-name && )	(1)	(since C++11)
    * class-name & class-name :: operator= ( class-name && ) = default;	(2)	(since C++11)
    * class-name & class-name :: operator= ( class-name && ) = delete;	(3)	(since C++11)
* Explanation
    * 1) Typical declaration of a move assignment operator.
    * 2) Forcing a move assignment operator to be generated by the compiler.
    * 3) Avoiding implicit move assignment.
    * The move assignment operator is called whenever it is selected by overload resolution, e.g. when an object appears on the left-hand side of an assignment expression, where the right-hand side is an rvalue of the same or implicitly convertible type.
    * Move assignment operators typically "steal" the resources held by the argument (e.g. pointers to dynamically-allocated objects, file descriptors, TCP sockets, I/O streams, running threads, etc.), rather than make copies of them, and leave the argument in some valid but otherwise indeterminate state. For example, move-assigning from a std::string or from a std::vector may result in the argument being left empty. This is not, however, a guarantee. A move assignment is less, not more restrictively defined than ordinary assignment; where ordinary assignment must leave two copies of data at completion, move assignment is required to leave only one.
* Notes
    * If both copy and move assignment operators are provided, overload resolution selects the move assignment if the argument is an rvalue (either a prvalue such as a nameless temporary or an xvalue such as the result of std::move), and selects the copy assignment if the argument is an lvalue (named object or a function/operator returning lvalue reference). If only the copy assignment is provided, all argument categories select it (as long as it takes its argument by value or as reference to const, since rvalues can bind to const references), which makes copy assignment the fallback for move assignment, when move is unavailable.
    * It is unspecified whether virtual base class subobjects that are accessible through more than one path in the inheritance lattice, are assigned more than once by the implicitly-defined move assignment operator (same applies to copy assignment).
    * See assignment operator overloading for additional detail on the expected behavior of a user-defined move-assignment operator.
```c++
#include <string>
#include <iostream>
#include <utility>
 
struct A
{
    std::string s;
 
    A() : s("test") {}
 
    A(const A& o) : s(o.s) { std::cout << "move failed!\n"; }
 
    A(A&& o) noexcept : s(std::move(o.s)) {}
 
    A& operator=(const A& other)
    {
         s = other.s;
         std::cout << "copy assigned\n";
         return *this;
    }
 
    A& operator=(A&& other) noexcept
    {
         s = std::move(other.s);
         std::cout << "move assigned\n";
         return *this;
    }
};
 
A f(A a) { return a; }
 
struct B : A
{
    std::string s2; 
    int n;
    // implicit move assignment operator B& B::operator=(B&&)
    // calls A's move assignment operator
    // calls s2's move assignment operator
    // and makes a bitwise copy of n
};
 
struct C : B
{
    ~C() {} // destructor prevents implicit move assignment
};
 
struct D : B
{
    D() {}
    ~D() {} // destructor would prevent implicit move assignment
    D& operator=(D&&) = default; // force a move assignment anyway 
};
 
int main()
{
    A a1, a2;
    std::cout << "Trying to move-assign A from rvalue temporary\n";
    a1 = f(A()); // move-assignment from rvalue temporary
    std::cout << "Trying to move-assign A from xvalue\n";
    a2 = std::move(a1); // move-assignment from xvalue
 
    std::cout << "Trying to move-assign B\n";
    B b1, b2;
    std::cout << "Before move, b1.s = \"" << b1.s << "\"\n";
    b2 = std::move(b1); // calls implicit move assignment
    std::cout << "After move, b1.s = \"" << b1.s << "\"\n";
 
    std::cout << "Trying to move-assign C\n";
    C c1, c2;
    c2 = std::move(c1); // calls the copy assignment operator
 
    std::cout << "Trying to move-assign D\n";
    D d1, d2;
    d2 = std::move(d1);
}

/*
Output:

Trying to move-assign A from rvalue temporary
move assigned
Trying to move-assign A from xvalue
move assigned
Trying to move-assign B
Before move, b1.s = "test"
move assigned
After move, b1.s = "" 
Trying to move-assign C
copy assigned
Trying to move-assign D
move assigned
*/
```

#### Inheritance

##### [Base and derived classes](https://en.cppreference.com/w/cpp/language/derived_class)

* Any class type (whether declared with class-key class or struct) may be declared as derived from one or more base classes which, in turn, may be derived from their own base classes, forming an inheritance hierarchy.
* The list of base classes is provided in the base-clause of the class declaration syntax. The base-clause consists of the character : followed by a comma-separated list of one or more base-specifiers.
```c++
struct Base
{
    int a, b, c;
};
 
// every object of type Derived includes Base as a subobject
struct Derived : Base
{
    int b;
};
 
// every object of type Derived2 includes Derived and Base as subobjects
struct Derived2 : Derived
{
    int c;
};
```

###### Virtual base classes

* For each distinct base class that is specified `virtual`, the most derived object contains only `one base class subobject` of that type, even if the class appears many times in the inheritance hierarchy (as long as it is inherited virtual every time).
```c++
struct B { int n; };
class X : public virtual B {};
class Y : virtual public B {};
class Z : public B {};
 
// every object of type AA has one X, one Y, one Z, and two B's:
// one that is the base of Z and one that is shared by X and Y
struct AA : X, Y, Z
{
    AA()
    {
        X::n = 1; // modifies the virtual B subobject's member
        Y::n = 2; // modifies the same virtual B subobject's member
        Z::n = 3; // modifies the non-virtual B subobject's member
 
        std::cout << X::n << Y::n << Z::n << '\n'; // prints 223
    }
};
```
* An example of an inheritance hierarchy with virtual base classes is the iostreams hierarchy of the standard library: `std::istream` and `std::ostream` are derived from `std::ios` using virtual inheritance. `std::iostream` is derived from both `std::istream` and `std::ostream`, so every instance of `std::iostream` contains a `std::ostream` subobject, a `std::istream` subobject, and just one `std::ios` subobject (and, consequently, one `std::ios_base`).
* All `virtual` base subobjects are initialized before any `non-virtual` base subobject, so only the `most derived class` calls the constructors of the `virtual bases` in its member initializer list:
```c++
struct B
{
    int n;
 
    B(int x) : n(x) {}
};
 
struct X : virtual B { X() : B(1) {} };
struct Y : virtual B { Y() : B(2) {} };
struct AA : X, Y     { AA() : B(3), X(), Y() {} };
 
// the default constructor of AA calls the default constructors of X and Y
// but those constructors do not call the constructor of B because B is a virtual base
AA a; // a.n == 3
 
// the default constructor of X calls the constructor of B
X x;  // x.n == 1
```
* There are [special rules](https://en.cppreference.com/w/cpp/language/unqualified_lookup#Member_function_definition) for unqualified name lookup for class members when virtual inheritance is involved (sometimes referred to as the rules of dominance).

###### Public inheritance

* When a class uses public member access specifier to derive from a base, all public members of the base class are accessible as public members of the derived class and all protected members of the base class are accessible as protected members of the derived class (private members of the base are never accessible unless `friended`)
* Public inheritance models the `subtyping relationship of object-oriented programming`: the derived class object IS-A base class object. References and pointers to a derived object are expected to be usable by any code that expects references or pointers to any of its public bases (see LSP) or, in DbC terms, a derived class should maintain class invariants of its public bases, should not strengthen any precondition or weaken any postcondition of a member function it overrides.
```c++
#include <vector>
#include <string>
#include <iostream>
 
struct MenuOption { std::string title; };
 
// Menu is a vector of MenuOption: options can be inserted, removed, reordered...
// and has a title.
class Menu : public std::vector<MenuOption>
{
public:
    std::string title;
 
    void print() const
    {
        std::cout << title << ":\n";
        for (std::size_t i = 0, s = size(); i < s; ++i)
            std::cout << "  " << (i+1) << ". " << at(i).title << '\n';
    }
};
// Note: Menu::title is not problematic because its role is independent of the base class.
 
enum class Color { WHITE, RED, BLUE, GREEN };
 
void apply_terminal_color(Color) { /* OS-specific */ }
 
// THIS IS BAD!
// ColorMenu is a Menu where every option has a custom color.
class ColorMenu : public Menu
{
public:
    std::vector<Color> colors;
 
    void print() const
    {
        std::cout << title << ":\n";
 
        for (std::size_t i = 0, s = size(); i < s; ++i)
        {
            std::cout << "  " << (i+1) << ". ";
            apply_terminal_color(colors[i]);
            std::cout << at(i).title << '\n';
            apply_terminal_color(Color::WHITE);
        }
    }
};
// ColorMenu needs the following invariants that cannot be satisfied
// by publicly inheriting from Menu, for example:
// - ColorMenu::colors and Menu must have the same number of elements
// - To make sense, calling erase() should remove also elements from colors,
//   in order to let options keep their colors
// Basically every non-const call to a std::vector method will break the invariant
// of the ColorMenu and will need fixing from the user by correctly managing colors.
 
int main()
{
    ColorMenu color_menu;
 
    // The big problem of this class is that we must keep ColorMenu::Color
    // in sync with Menu.
    color_menu.push_back(MenuOption{"Some choice"});
 
    // color_menu.print(); // ERROR! colors[i] in print() is out of range
 
    color_menu.colors.push_back(Color::RED);
 
    color_menu.print(); // OK: colors and Menu has the same number of elements
}
```

###### Protected inheritance

* When a class uses protected member access specifier to derive from a base, all public and protected members of the base class are accessible as protected members of the derived class (private members of the base are never accessible unless friended)
* Protected inheritance may be used for `controlled polymorphism`: within the members of Derived, as well as within the members of all further-derived classes, the derived class IS-A base: references and pointers to Derived may be used where references and pointers to Base are expected.

###### Private inheritance

* When a class uses private member access specifier to derive from a base, all public and protected members of the base class are accessible as private members of the derived class (private members of the base are never accessible unless friended).
* Private inheritance is commonly used in `policy-based design`, since policies are usually empty classes, and using them as bases both enables static polymorphism and leverages empty-base optimization.
* Private inheritance can also be used to implement the `composition relationship` (the base class subobject is an implementation detail of the derived class object). Using a member offers better encapsulation and is generally preferred unless the derived class requires access to protected members (including constructors) of the base, needs to override a virtual member of the base, needs the base to be constructed before and destructed after some other base subobject, needs to share a virtual base or needs to control the construction of a virtual base. Use of members to implement composition is also not applicable in the case of multiple inheritance from a parameter pack or when the identities of the base classes are determined at compile time through template metaprogramming.
* Similar to protected inheritance, private inheritance may also be used for `controlled polymorphism`: within the members of the derived (but not within further-derived classes), derived IS-A base.
```c++
template<typename Transport>
class service : private Transport // private inheritance from the Transport policy
{
public:
    void transmit()
    {
        this->send(...); // send using whatever transport was supplied
    }
};
 
// TCP transport policy
class tcp
{
public:
    void send(...);
};
 
// UDP transport policy
class udp
{
public:
    void send(...);
};
 
service<tcp> service(host, port); 
service.transmit(...); // send over TCP
```

###### Member name lookup

* Unqualified and qualified name lookup rules for class members are detailed in [name lookup](https://en.cppreference.com/w/cpp/language/lookup).

##### [Empty base optimization (EBO)](https://en.cppreference.com/w/cpp/language/ebo)

* Allows the size of an empty base subobject to be zero.
* The size of any object or member subobject is required to be at least 1 even if the type is an empty class type (that is, a class or struct that has no non-static data members), `(unless with [[no_unique_address]], see below) (since C++20)` in order to be able to guarantee that the addresses of distinct objects of the same type are always distinct.
* However, base class subobjects are not so constrained, and can be completely optimized out from the object layout:
```c++
struct Base {}; // empty class
 
struct Derived1 : Base {
    int i;
};
 
int main()
{
    // the size of any object of empty class type is at least 1
    static_assert(sizeof(Base) >= 1);
 
    // empty base optimization applies
    static_assert(sizeof(Derived1) == sizeof(int));
}
```
* Empty base optimization is prohibited if one of the empty base classes is also the type or the base of the type of the `first non-static data member`, since the two base subobjects of the same type are required to have different addresses within the object representation of the most derived type.
* A typical example of such situation is the naive implementation of std::reverse_iterator (derived from the empty base std::iterator), which holds the underlying iterator (also derived from std::iterator) as its first non-static data member.
```c++
struct Base {}; // empty class
 
struct Derived1 : Base {
    int i;
};
 
struct Derived2 : Base {
    Base c; // Base, occupies 1 byte, followed by padding for i
    int i;
};
 
struct Derived3 : Base {
    Derived1 c; // derived from Base, occupies sizeof(int) bytes
    int i;
};
 
int main()
{
    // empty base optimization does not apply,
    // base occupies 1 byte, Base member occupies 1 byte
    // followed by 2 bytes of padding to satisfy int alignment requirements
    static_assert(sizeof(Derived2) == 2*sizeof(int));
 
    // empty base optimization does not apply,
    // base takes up at least 1 byte plus the padding
    // to satisfy alignment requirement of the first member (whose
    // alignment is the same as int)
    static_assert(sizeof(Derived3) == 3*sizeof(int));
}
```
* Notes
    * Empty base optimization is commonly used by `allocator-aware standard library classes` (std::vector, std::function, std::shared_ptr, etc) to avoid occupying any additional storage for its allocator member if the allocator is stateless. This is achieved by storing one of the required data members (e.g., begin, end, or capacity pointer for the vector) in an equivalent of boost::compressed_pair with the allocator.

##### [Virtual member functions](https://en.cppreference.com/w/cpp/language/virtual)

* The `virtual` specifier specifies that a `non-static member function` is virtual and supports dynamic dispatch. It may only appear in the decl-specifier-seq of the initial declaration of a non-static member function (i.e., when it is declared in the `class definition`).
* Virtual functions are member functions whose behavior can be `overridden` in derived classes. As opposed to non-virtual functions, the overriding behavior is preserved even if there is no compile-time information about the actual type of the class. That is to say, if a derived class is handled using pointer or reference to the base class, a call to an overridden virtual function would invoke the behavior defined in the derived class. Such a function call is known as `virtual function call` or `virtual call`. Virtual function call is suppressed if the function is selected using [qualified name lookup](https://en.cppreference.com/w/cpp/language/lookup) (that is, if the function's name appears to the right of the scope resolution operator `::`).
```c++
#include <iostream>
 
struct Base
{
    virtual void f()
    {
        std::cout << "base\n";
    }
};
 
struct Derived : Base
{
    void f() override // 'override' is optional
    {
        std::cout << "derived\n";
    }
};
 
int main()
{
    Base b;
    Derived d;
 
    // virtual function call through reference
    Base& br = b; // the type of br is Base&
    Base& dr = d; // the type of dr is Base& as well
    br.f(); // prints "base"
    dr.f(); // prints "derived"
 
    // virtual function call through pointer
    Base* bp = &b; // the type of bp is Base*
    Base* dp = &d; // the type of dp is Base* as well
    bp->f(); // prints "base"
    dp->f(); // prints "derived"
 
    // non-virtual function call
    br.Base::f(); // prints "base"
    dr.Base::f(); // prints "base"
}
```

###### In detail

* If some member function vf is declared as `virtual` in a class `Base`, and some class Derived, which is derived, directly or indirectly, from Base, has a declaration for member function with the same
    * name
    * parameter type list (but not the return type)
    * cv-qualifiers
    * ref-qualifiers
* Then this function in the class Derived is also `virtual` (`whether or not the keyword virtual is used` in its declaration) and `overrides` Base::vf (`whether or not the word override is used` in its declaration).
* Base::vf does not need to be accessible or visible to be overridden. (Base::vf can be declared private, or Base can be inherited using private inheritance. Any members with the same name in a base class of Derived which inherits Base do not matter for override determination, even if they would hide Base::vf during name lookup.)
```c++
class B
{
    virtual void do_f(); // private member
public:
    void f() { do_f(); } // public interface
};
 
struct D : public B
{
    void do_f() override; // overrides B::do_f
};
 
int main()
{
    D d;
    B* bp = &d;
    bp->f(); // internally calls D::do_f();
}
```
* For every virtual function, there is the `final overrider`, which is executed when a virtual function call is made. A virtual member function vf of a base class Base is the final overrider unless the derived class declares or inherits (through multiple inheritance) another function that overrides vf.
```c++
struct A { virtual void f(); };     // A::f is virtual
struct B : A { void f(); };         // B::f overrides A::f in B
struct C : virtual B { void f(); }; // C::f overrides A::f in C
 
struct D : virtual B {}; // D does not introduce an overrider, B::f is final in D
 
struct E : C, D          // E does not introduce an overrider, C::f is final in E
{
    using A::f; // not a function declaration, just makes A::f visible to lookup
};
 
int main()
{
    E e;
    e.f();    // virtual call calls C::f, the final overrider in e
    e.E::f(); // non-virtual call calls A::f, which is visible in E
}
```
* If a function has `more than one final overrider`, the program is ill-formed:
```c++
struct A
{
    virtual void f();
};
 
struct VB1 : virtual A
{
    void f(); // overrides A::f
};
 
struct VB2 : virtual A
{
    void f(); // overrides A::f
};
 
// struct Error : VB1, VB2
// {
//     // Error: A::f has two final overriders in Error
// };
 
struct Okay : VB1, VB2
{
    void f(); // OK: this is the final overrider for A::f
};
 
struct VB1a : virtual A {}; // does not declare an overrider
 
struct Da : VB1a, VB2
{
    // in Da, the final overrider of A::f is VB2::f
};
```
* A function with the same name but different parameter list does not override the base function of the same name, but `hides` it: when [unqualified name lookup](https://en.cppreference.com/w/cpp/language/lookup) examines the scope of the derived class, the lookup finds the declaration and does not examine the base class.
```c++
struct B
{
    virtual void f();
};
 
struct D : B
{
    void f(int); // D::f hides B::f (wrong parameter list)
};
 
struct D2 : D
{
    void f(); // D2::f overrides B::f (doesn't matter that it's not visible)
};
 
int main()
{
    B b;
    B& b_as_b = b;
 
    D d;
    B& d_as_b = d;
    D& d_as_d = d;
 
    D2 d2;
    B& d2_as_b = d2;
    D& d2_as_d = d2;
 
    b_as_b.f();  // calls B::f()
    d_as_b.f();  // calls B::f()
    d2_as_b.f(); // calls D2::f()
 
    d_as_d.f();  // Error: lookup in D finds only f(int)
    d2_as_d.f(); // Error: lookup in D finds only f(int)
}
```
* If a function is declared with the specifier `override`, but does not override a virtual function, the program is ill-formed:
```c++
struct B
{
    virtual void f(int);
};
 
struct D : B
{
    virtual void f(int) override;  // OK, D::f(int) overrides B::f(int)
    virtual void f(long) override; // Error: f(long) does not override B::f(int)
};
If a function is declared with the specifier final, and another function attempts to override it, the program is ill-formed:

struct B
{
    virtual void f() const final;
};
 
struct D : B
{
    void f() const; // Error: D::f attempts to override final B::f
};
```
* `Non-member functions` and `static member functions` cannot be virtual.
* `Function templates` cannot be declared virtual. This applies only to functions that are themselves templates - a regular member function of a `class template` can be declared virtual.
* [Default arguments](https://en.cppreference.com/w/cpp/language/default_arguments) for virtual functions are substituted at the compile time.

###### Covariant return types

* If the function Derived::f overrides a function Base::f, their return types must either be the same or be covariant. Two types are covariant if they satisfy all of the following requirements:
    * both types are pointers or references (lvalue or rvalue) to classes. Multi-level pointers or references are not allowed.
    * the referenced/pointed-to class in the return type of Base::f() must be an unambiguous and accessible direct or indirect base class of the referenced/pointed-to class of the return type of Derived::f().
    * the return type of Derived::f() must be equally or less cv-qualified than the return type of Base::f().
* The class in the return type of Derived::f must be either Derived itself, or must be a [complete type](https://en.cppreference.com/w/cpp/language/incomplete_type) at the point of declaration of Derived::f.
* When a virtual function call is made, the type returned by the final overrider is [implicitly converted](https://en.cppreference.com/w/cpp/language/implicit_cast) to the return type of the overridden function that was called:
```c++
class B {};
 
struct Base
{
    virtual void vf1();
    virtual void vf2();
    virtual void vf3();
    virtual B* vf4();
    virtual B* vf5();
};
 
class D : private B
{
    friend struct Derived; // in Derived, B is an accessible base of D
};
 
class A; // forward-declared class is an incomplete type
 
struct Derived : public Base
{
    void vf1();    // virtual, overrides Base::vf1()
    void vf2(int); // non-virtual, hides Base::vf2()
//  char vf3();    // Error: overrides Base::vf3, but has different
                   // and non-covariant return type
    D* vf4();      // overrides Base::vf4() and has covariant return type
//  A* vf5();      // Error: A is incomplete type
};
 
int main()
{
    Derived d;
    Base& br = d;
    Derived& dr = d;
 
    br.vf1(); // calls Derived::vf1()
    br.vf2(); // calls Base::vf2()
//  dr.vf2(); // Error: vf2(int) hides vf2()
 
    B* p = br.vf4(); // calls Derived::vf4() and converts the result to B*
    D* q = dr.vf4(); // calls Derived::vf4() and does not convert the result to B*
}
```

###### Virtual destructor

* Even though destructors are `not inherited`, if a base class declares its destructor `virtual`, the derived destructor always `overrides` it. This makes it possible to delete dynamically allocated objects of polymorphic type through `pointers to base`.
```c++
class Base
{
public:
    virtual ~Base() { /* releases Base's resources */ }
};
 
class Derived : public Base
{
    ~Derived() { /* releases Derived's resources */ }
};
 
int main()
{
    Base* b = new Derived;
    delete b; // Makes a virtual function call to Base::~Base()
              // since it is virtual, it calls Derived::~Derived() which can
              // release resources of the derived class, and then calls
              // Base::~Base() following the usual order of destruction
}
```
* Moreover, if the destructor of the base class is not virtual, deleting a derived class object through a pointer to the base class is undefined behavior regardless of whether there are resources that would be leaked if the derived destructor is not invoked, unless the selected deallocation function is a destroying operator delete (since C++20).
* A useful guideline is that the destructor of any base class must be `public and virtual` or `protected and non-virtual`, whenever delete expressions are involved, e.g. when implicitly used in std::unique_ptr.

###### During construction and destruction

* When a virtual function is called directly or indirectly from a constructor or from a destructor (including during the construction or destruction of the class’s non-static data members, e.g. in a member initializer list), and the object to which the call applies is the object under construction or destruction, the function called is the final overrider in the constructor’s or destructor’s class and not one overriding it in a more-derived class. In other words, during construction or destruction, the more-derived classes do not exist.
* When constructing a complex class with multiple branches, within a constructor that belongs to one branch, polymorphism is restricted to that class and its bases: if it obtains a pointer or reference to a base subobject outside this subhierarchy, and attempts to invoke a virtual function call (e.g. using explicit member access), the behavior is undefined:
```c++
struct V
{
    virtual void f();
    virtual void g();
};
 
struct A : virtual V
{
    virtual void f(); // A::f is the final overrider of V::f in A
};
 
struct B : virtual V
{
    virtual void g(); // B::g is the final overrider of V::g in B
    B(V*, A*);
};
 
struct D : A, B
{
    virtual void f(); // D::f is the final overrider of V::f in D
    virtual void g(); // D::g is the final overrider of V::g in D
 
    // note: A is initialized before B
    D() : B((A*) this, this) {}
};
 
// the constructor of B, called from the constructor of D 
B::B(V* v, A* a)
{
    f(); // virtual call to V::f (although D has the final overrider, D doesn't exist)
    g(); // virtual call to B::g, which is the final overrider in B 
 
    v->g(); // v's type V is base of B, virtual call calls B::g as before
 
    a->f(); // a’s type A is not a base of B. it belongs to a different branch of the
            // hierarchy. Attempting a virtual call through that branch causes
            // undefined behavior even though A was already fully constructed in this
            // case (it was constructed before B since it appears before B in the list
            // of the bases of D). In practice, the virtual call to A::f will be
            // attempted using B's virtual member function table, since that's what
            // is active during B's construction)
}
```

###### MISC

* [C.128: Virtual functions should specify exactly one of virtual, override, or final](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rh-override)
	* Reason
		* Readability. Detection of mistakes. Writing explicit virtual, override, or final is self-documenting and enables the compiler to catch mismatch of types and/or names between base and derived classes. However, writing more than one of these three is both redundant and a potential source of errors.
		* It’s simple and clear:
			* virtual means exactly and only “this is a new virtual function.”
			* override means exactly and only “this is a non-final overrider.”
			* final means exactly and only “this is a final overrider.”
	* Discussion
		* We want to eliminate two particular classes of errors:
			* implicit virtual: the programmer intended the function to be implicitly virtual and it is (but readers of the code can’t tell); or the programmer intended the function to be implicitly virtual but it isn’t (e.g., because of a subtle parameter list mismatch); or the programmer did not intend the function to be virtual but it is (because it happens to have the same signature as a virtual in the base class)
			* implicit override: the programmer intended the function to be implicitly an overrider and it is (but readers of the code can’t tell); or the programmer intended the function to be implicitly an overrider but it isn’t (e.g., because of a subtle parameter list mismatch); or the programmer did not intend the function to be an overrider but it is (because it happens to have the same signature as a virtual in the base class – note this problem arises whether or not the function is explicitly declared virtual, because the programmer might have intended to create either a new virtual function or a new non-virtual function)
		* Note: On a class defined as final, it doesn’t matter whether you put override or final on an individual virtual function.
		* Note: Use final on functions sparingly. It does not necessarily lead to optimization, and it precludes further overriding.
	* Enforcement
		* Compare virtual function names in base and derived classes and flag uses of the same name that does not override.
		* Flag overrides with neither override nor final.
		* Flag function declarations that use more than one of virtual, override, and final.
* [C.140: Do not provide different default arguments for a virtual function and an overrider](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rh-virtual-default-arg)
	* Reason
		* That can cause confusion: An overrider does not inherit default arguments.
	* Enforcement
		* Flag default arguments on virtual functions if they differ between base and derived declarations.
* [C++虚函数表原理浅析 (qq.com)](https://mp.weixin.qq.com/s/lKfOZUM1txbUncD6ZBSO4w)

##### [Pure virtual functions and abstract classes](https://en.cppreference.com/w/cpp/language/abstract_class)

* Defines an abstract type which cannot be instantiated, but can be used as a base class.

###### Syntax

* A `pure virtual function` is a virtual function whose declarator has the following syntax:
    * `declarator virt-specifier(optional) = 0`
* Here the sequence = 0 is known as `pure-specifier`, and appears either immediately after the declarator or after the optional virt-specifier (override or final).
* pure-specifier cannot appear in a `member function definition` or `friend declaration`.
```c++
struct Base
{
    virtual int g();
    virtual ~Base() {}
};
 
struct A : Base
{
    // OK: declares three member virtual functions, two of them pure
    virtual int f() = 0, g() override = 0, h();
 
    // OK: destructor can be pure too
    ~A() = 0;
 
    // Error: pure-specifier on a function definition
    virtual int b() = 0 {}
};
```
* An `abstract class` is a class that either `defines` or `inherits` at least one function for which the `final overrider` is `pure virtual`.

###### Explanation

* Abstract classes are used to represent general concepts (for example, Shape, Animal), which can be used as `base classes` for concrete classes (for example, Circle, Dog).
* No objects of an abstract class can be created (except for base subobjects of a class derived from it) and no non-static data members whose type is an abstract class can be declared.
* Abstract types cannot be used as parameter types, as function return types, or as the type of an explicit conversion (note this is checked at the point of definition and function call, since at the point of function declaration parameter and return type may be incomplete).
* `Pointers` and `references` to an abstract class can be declared.
```c++
struct Abstract
{
    virtual void f() = 0;  // pure virtual
}; // "Abstract" is abstract
 
struct Concrete : Abstract
{
    void f() override {}   // non-pure virtual
    virtual void g();      // non-pure virtual
}; // "Concrete" is non-abstract
 
struct Abstract2 : Concrete
{
    void g() override = 0; // pure virtual overrider
}; // "Abstract2" is abstract
 
int main()
{
    // Abstract a;   // Error: abstract class
    Concrete b;      // OK
    Abstract& a = b; // OK to reference abstract base
    a.f();           // virtual dispatch to Concrete::f()
    // Abstract2 a2; // Error: abstract class (final overrider of g() is pure)
}
```
* The definition of a pure virtual function `may` be provided (and `must` be provided if the pure virtual is the `destructor`): the member functions of the derived class are free to call the abstract base's pure virtual function using qualified function id. This definition must be provided outside of the class body (the syntax of a function declaration doesn't allow both the pure specifier `= 0` and a function body).
* Making a virtual call to a pure virtual function from a constructor or the destructor of the abstract class is `undefined behavior` (regardless of whether it has a definition or not).
```c++
struct Abstract
{
    virtual void f() = 0; // pure virtual
    virtual void g() {}   // non-pure virtual
 
    ~Abstract()
    {
        g();           // OK: calls Abstract::g()
        // f();        // undefined behavior
        Abstract::f(); // OK: non-virtual call
    }
};
 
// definition of the pure virtual function
void Abstract::f() { std::cout << "A::f()\n"; }
 
struct Concrete : Abstract
{
    void f() override
    {
        Abstract::f(); // OK: calls pure virtual function
    }
 
    void g() override {}
 
    ~Concrete()
    {
        g(); // OK: calls Concrete::g()
        f(); // OK: calls Concrete::f()
    }
};
```

###### MISC

* [Pure Virtual Functions and Abstract Classes in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/pure-virtual-functions-and-abstract-classes/?ref=lbp)
    * A `pure virtual function` (or abstract function) in C++ is a virtual function for which we can have implementation, But we must override that function in the derived class, otherwise the derived class will also become abstract class
* [Pure Virtual Destructor in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/pure-virtual-destructor-c/)
    * A `pure virtual destructor` can be declared in C++. After a destructor has been created as a pure virtual object(instance of a class), where the destructor body is provided. This is due to the fact that destructors will `not be overridden` in derived classes, but will instead be `called in reverse order`. As a result, for a pure virtual destructor, you `must` specify a destructor body.
    * Note: `Only Destructors can be Virtual`. `Constructors cannot be declared as virtual`, this is because if you try to override a constructor by declaring it in a base/super class and call it in the derived/sub class with same functionalities it will always give an error as overriding means a feature that lets us to use a method from the parent class in the child class which is not possible. 
    * ...
    * How did the above code work MAGICALLY?
        * This basically works because the destructors will be called recursively bottom to up if and only if the value is passed in the virtual destructor. So `vtable` is a table containing pointers of all virtual functions that the class defines, and the compiler provides `vptr` to the class as a `hidden pointer` that points to the ideal vtable, so the compiler makes use of an accurate or correct index, calculated at compile-time, to the vtable which will dispatch the correct virtual function at runtime.
        * It is important to note that a class becomes an `abstract class`(at least a function that has no definition) when it contains a `pure virtual destructor`.
* [Abstract Classes - Polymorphism | HackerRank](https://www.hackerrank.com/challenges/abstract-classes-polymorphism/problem)
  * [LRU Cache Implementation - GeeksforGeeks](https://www.geeksforgeeks.org/lru-cache-implementation/)
```c++
#include <bits/stdc++.h>
using namespace std;

struct Node {
    Node* next;
    Node* prev;
    int value;
    int key;
    Node(Node* p, Node* n, int k, int val):prev(p),next(n),key(k),value(val){};
    Node(int k, int val):prev(NULL),next(NULL),key(k),value(val){};
};

class Cache {
protected:
    map<int,Node*> mp; //map the key to the node in the linked list
    int cp;  //capacity
    Node* tail; // double linked list tail pointer
    Node* head; // double linked list head pointer
    virtual void set(int, int) = 0; //set function
    virtual int get(int) = 0; //get function
};

// Sometimes timeout
class LRUCache : public Cache {
    private:
        list< pair<int, int> >   lru;
        unordered_map<int, list< pair<int, int> >::iterator> mp;

    public:
        LRUCache(int);
        ~LRUCache(){};
        void set(int, int);
        int get(int);
};

LRUCache::LRUCache(int capacity)
{
    // note that member initializer does not name a non-static data member or base class
    cp = capacity;
}

void LRUCache::set(int key, int value)
{
    // not present in cache
    if (mp.find(key) == mp.end()) {
        // cache is full
        if (lru.size() == cp) {
            // delete least recently used item
            mp.erase(lru.back().first);
            lru.pop_back();
        }
    } else {
        lru.erase(mp[key]);
    }

    // update reference
    lru.push_front({key, value});
    mp[key] = lru.begin();
}

int LRUCache::get(int key)
{
    if (mp.find(key) == mp.end()) {
        return -1;
    } else {
        lru.push_front(*mp[key]);
        lru.erase(mp[key]);
        mp[key] = lru.begin();
        return mp[key]->second;
    }
}

int main() {
    int n, capacity,i;
    cin >> n >> capacity;
    LRUCache l(capacity);
    for(i=0;i<n;i++) {
        string command;
        cin >> command;
        if(command == "get") {
            int key;
            cin >> key;
            cout << l.get(key) << endl;
        }
        else if(command == "set") {
            int key, value;
            cin >> key >> value;
            l.set(key,value);
        }
    }

    return 0;
}
```

##### [override specifier](https://en.cppreference.com/w/cpp/language/override)
	
* Specifies that a `virtual function` overrides another `virtual function`.

###### Syntax

* The identifier override, if used, appears immediately after the `declarator` in the syntax of a member function declaration or a member function definition inside a class definition.
* `declarator virt-specifier-seq(optional) pure-specifier(optional)`	(1)	
* `declarator virt-specifier-seq(optional) function-body`	(2)	
* ...
* In both cases, virt-specifier-seq, if used, is either `override` or `final`, or `final override` or `override final`.

###### Explanation

* In a member function declaration or definition, override specifier ensures that the function is virtual and is overriding a virtual function from a base class. The program is ill-formed (a compile-time error is generated) if this is not true.
* `override` is an identifier with a special meaning when used after member function declarators: it's not a `reserved keyword` otherwise.
* Example
```c++
#include <iostream>
 
struct A
{
    virtual void foo();
    void bar();
    virtual ~A();
};
 
// member functions definitions of struct A:
void A::foo() { std::cout << "A::foo();\n"; }
A::~A() { std::cout << "A::~A();\n"; }
 
struct B : A
{
//  void foo() const override; // Error: B::foo does not override A::foo
                               // (signature mismatch)
    void foo() override; // OK: B::foo overrides A::foo
//  void bar() override; // Error: A::bar is not virtual
    ~B() override; // OK: `override` can also be applied to virtual
                   // special member functions, e.g. destructors
    void override(); // OK, member function name, not a reserved keyword
};
 
// member functions definitions of struct B:
void B::foo() { std::cout << "B::foo();\n"; }
B::~B() { std::cout << "B::~B();\n"; }
void B::override() { std::cout << "B::override();\n"; }
 
int main() {
    B b;
    b.foo();
    b.override(); // OK, invokes the member function `override()`
    int override{42}; // OK, defines an integer variable
    std::cout << "override: " << override << '\n';
}
/*
B::foo();
B::override();
override: 42
B::~B();
A::~A();
*/
```

##### [final specifier](https://en.cppreference.com/w/cpp/language/final)

* Specifies that a `virtual function` cannot be overridden in a derived class or that a class cannot be `derived from`.

###### Syntax

* When applied to a member function, the identifier final appears immediately after the declarator in the syntax of a member function declaration or a member function definition inside a class definition.
* When applied to a class, the identifier final appears at the beginning of the class definition, immediately after the name of the class.
* `declarator virt-specifier-seq(optional) pure-specifier(optional)`	(1)	
* `declarator virt-specifier-seq(optional) function-body`	(2)	
* `class-key attr(optional) class-head-name class-virt-specifier(optional) base-clause(optional)`	(3)	
* ...
* In the cases (1,2), `virt-specifier-seq`, if used, is either `override` or `final`, or `final override` or `override final`. In the case (3), the only allowed value of `class-virt-specifier`, if used, is `final`

###### Explanation

* When used in a virtual function declaration or definition, final specifier ensures that the function is virtual and specifies that it may not be overridden by derived classes. The program is ill-formed (a compile-time error is generated) otherwise.
* When used in a class definition, final specifies that this class may not appear in the `base-specifier-list` of another class definition (in other words, `cannot be derived from`). The program is ill-formed otherwise (a compile-time error is generated). final can also be used with a [union](https://en.cppreference.com/w/cpp/language/union) definition, in which case it has no effect `(other than on the outcome of std::is_final) (since C++14)`, since unions cannot be derived from.
* `final` is an identifier with a special meaning when used in a member function declaration or class head. In other contexts, it is not reserved and may be used to name objects and functions.
* Note
    * In a sequence of the following tokens:
        * one of class, struct and union;
        * a possibly qualified identifier;
        * final;
        * one of : and {,
    * the third token final in the sequence is always considered as a specifier instead of an identifier:
```c++
struct A;
struct A final {}; // OK, definition of struct A,
                   // not value-initialization of variable final
 
struct X
{
    struct C { constexpr operator int() { return 5; } };
    struct B final : C{}; // OK, definition of nested class B,
                          // not declaration of a bit-field member final
};
 
// Abnormal final usage.
 
struct final final // OK, definition of a struct named `final` from which
{                  // you cannot inherit
};
 
// struct final final {}; // Error: redefinition of `struct final`, NOT a
                          // definition of a variable `final` using an elaborated
                          // type specifier `struct final` followed by an
                          // aggregate initialization
 
// struct override : final {}; // Error: cannot derive from final base type;
                               // `override` in given context is a normal name
void foo()
{
    [[maybe_unused]]
    final final; // OK, declaration of a variable named `final` of type
                 // `struct final` 
}
 
struct final final; // OK, declaration of a variable named `final` of type
                    // `struct final` using an elaborated type specifier
int main()
{
}
```
* Example
```c++
struct Base
{
    virtual void foo();
};
 
struct A : Base
{
    void foo() final; // Base::foo is overridden and A::foo is the final override
    void bar() final; // Error: bar cannot be final as it is non-virtual
};
 
struct B final : A // struct B is final
{
    void foo() override; // Error: foo cannot be overridden as it is final in A
};
 
struct C : B {}; // Error: B is final
/*
main.cpp:9:10: error: 'void A::bar()' marked 'final', but is not virtual
    9 |     void bar() final; // Error: bar cannot be final as it is non-virtual
      |          ^~~
main.cpp:14:10: error: virtual function 'virtual void B::foo()' overriding final function
   14 |     void foo() override; // Error: foo cannot be overridden as it is final in A
      |          ^~~
main.cpp:8:10: note: overridden function is 'virtual void A::foo()'
    8 |     void foo() final; // Base::foo is overridden and A::foo is the final override
      |          ^~~
main.cpp:17:8: error: cannot derive from 'final' base 'B' in derived type 'C'
   17 | struct C : B // Error: B is final
      |
*/      
```      

### [Templates](https://en.cppreference.com/w/cpp/language/templates)

* A template is a C++ entity that defines one of the following:
	* a family of classes (class template), which may be nested classes
	* a family of functions (function template), which may be member functions
	* an alias to a family of types (alias template) (since C++11)
	* a family of variables (variable template) (since C++14)
	* a concept (constraints and concepts) (since C++20)
* Templates are parameterized by one or more template parameters, of three kinds: type template parameters, non-type template parameters, and template template parameters.
* When template arguments are provided, or, for function and class (since C++17) templates only, deduced, they are substituted for the template parameters to obtain a specialization of the template, that is, a specific type or a specific function lvalue. Specializations may also be provided explicitly: full specializations are allowed for class, variable (since C++14) and function templates, partial specializations are only allowed for class templates and variable templates (since C++14).
* When a class template specialization is referenced in context that requires a complete object type, or when a function template specialization is referenced in context that requires a function definition to exist, the template is instantiated (the code for it is actually compiled), unless the template was already explicitly specialized or explicitly instantiated. Instantiation of a class template doesn't instantiate any of its member functions unless they are also used. At link time, identical instantiations generated by different translation units are merged.
* The definition of a template must be visible at the point of implicit instantiation, which is why template libraries typically provide all template definitions in the headers (e.g. most boost libraries are header-only).
* [C++ Templates](https://www.tutorialspoint.com/cplusplus/cpp_templates.htm)
* [C++ 模板总结，很全面！](https://mp.weixin.qq.com/s/01yn6XsSt-WYKPmNCkTy2A)
	* https://blog.csdn.net/zhoumin4576/article/details/103602324
	* 模板（Template）指 C++ 程序设计设计语言中采用类型作为参数的程序设计，支持通用程序设计。C++ 的标准库提供许多有用的函数大多结合了模板的观念，如 STL 以及 IO Stream。模板是 C++ 支持参数化多态的工具，使用模板可以使用户为类或者函数声明一种一般模式，使得类中的某些数据成员或者成员函数的参数、返回值取得任意类型。
	* 模板是一种对类型进行参数化的工具；通常有两种形式：函数模板和类模板:
		* 函数模板 针对仅参数类型不同的函数；
		* 类模板 针对仅数据成员和成员函数类型不同的类.
	* 使用模板的目的就是能够让程序员编写与类型无关的代码.
	* 一、函数模板
	* 二、类模板
	* 三、模板的非类型形参
	* 四、类模板的默认模板类型形参
	* 五、模板的实例化
	* 六、模板的特化（具体化）和偏特化
	* 七、模板类的继承
	* 八、模板实例化问题
* [C++ templates declare in .h, define in .hpp - Stack Overflow](https://stackoverflow.com/questions/3526299/c-templates-declare-in-h-define-in-hpp)
	* Typically (in my experience, YMMV) an hpp file is an #include-ed CPP file. This is done in order to break the code up in to two physical files, a primary include and an implementation-details file that the users of your library don't need to know about. It is done like this:
	* super_lib.h (the only file your clients need to #include)
	* super_lib_implementation.hpp (your clients do not #include this directly)

#### [Template parameters and template arguments](https://en.cppreference.com/w/cpp/language/template_parameters)

* Examples
```c++
#include <array>
#include <iostream>
#include <numeric>
 
// simple non-type template parameter
template<int N>
struct S { int a[N]; };
 
template<const char*>
struct S2 {};
 
// complicated non-type example
template
<
    char c,             // integral type
    int (&ra)[5],       // lvalue reference to object (of array type)
    int (*pf)(int),     // pointer to function
    int (S<10>::*a)[10] // pointer to member object (of type int[10])
>
struct Complicated
{
    // calls the function selected at compile time
    // and stores the result in the array selected at compile time
    void foo(char base)
    {
        ra[4] = pf(c - base);
    }
};
 
//  S2<"fail"> s2;        // error: string literal cannot be used
    char okay[] = "okay"; // static object with linkage
//  S2<&okay[0]> s3;      // error: array element has no linkage
    S2<okay> s4;          // works
 
int a[5];
int f(int n) { return n; }
 
// C++20: NTTP can be a literal class type
template<std::array arr>
constexpr
auto sum() { return std::accumulate(arr.cbegin(), arr.cend(), 0); }
 
// C++20: class template arguments are deduced at the call site
static_assert(sum<std::array<double, 8>{3, 1, 4, 1, 5, 9, 2, 6}>() == 31.0);
// C++20: NTTP argument deduction and CTAD
static_assert(sum<std::array{2, 7, 1, 8, 2, 8}>() == 28);
 
int main()
{
    S<10> s; // s.a is an array of 10 int
    s.a[9] = 4;
 
    Complicated<'2', a, f, &S<10>::a> c;
    c.foo('0');
 
    std::cout << s.a[9] << a[4] << '\n';
}
/*
42
*/
```

##### Template parameters

* Every `template` is parameterized by one or more template parameters, indicated in the `parameter-list` of the template declaration syntax:
	* `template < parameter-list > declaration		`
	* Each parameter in `parameter-list` may be:
		* a non-type template parameter;
		* a type template parameter;
		* a template template parameter.

###### Non-type template parameter

* `type name(optional)	(1)	`
* `type name(optional) = default	(2)	`
* `type ... name(optional)	(3)	(since C++11)`
* `placeholder name	(4)	(since C++17)`
* 1) A non-type template parameter with an optional name.
* 2) A non-type template parameter with an optional name and a default value.
* 3) A non-type template parameter pack with an optional name.
* 4) A non-type template parameter with a placeholder type. `placeholder` may be any type that includes the placeholder `auto` (such as plain `auto`, `auto **` or `auto &`)`, a placeholder for a deduced class type (since C++20)`, or `decltype(auto)`.
* A non-type template parameter must have a `structural type`, which is one of the following types (optionally cv-qualified, the qualifiers are ignored):
    * lvalue reference type (to object or to function);
    * an integral type;
    * a pointer type (to object or to function);
    * a pointer to member type (to member object or to member function);
    * an enumeration type;
    * std::nullptr_t; (since C++11)
    * a floating-point type; (since C++20)
    * a literal class type with the following properties:
        * all base classes and non-static data members are public and non-mutable and
        * the types of all base classes and non-static data members are structural types or (possibly multi-dimensional) array thereof. 
* Array and function types may be written in a template declaration, but they are automatically replaced by pointer to object and pointer to function as appropriate.
* ...
* The type of a non-type template parameter may be deduced if it includes a placeholder type (auto`, a placeholder for a deduced class type (since C++20)`, or decltype(auto)). The deduction is performed as if by deducing the type of the variable x in the invented declaration `T x = template-argument;`, where T is the declared type of the template parameter. If the deduced type is not permitted for a non-type template parameter, the program is ill-formed.
```c++
template<auto n>
struct B { /* ... */ };
 
B<5> b1;   // OK: non-type template parameter type is int
B<'a'> b2; // OK: non-type template parameter type is char
B<2.5> b3; // error (until C++20): non-type template parameter type cannot be double
 
// C++20 deduced class type placeholder, class template arguments are deduced at the call site
template<std::array arr>
void f();
 
f<std::array<double, 8>{}>();
```
* For non-type template parameter packs whose type uses a placeholder type, the type is independently deduced for each template argument and need not match:
```c++
template<auto...>
struct C {};
 
C<'C', 0, 2L, nullptr> x; // OK
```

###### Type template parameter

* `type-parameter-key name(optional)	(1)	`
* `type-parameter-key name(optional) = default	(2)	`
* `type-parameter-key ... name(optional)	(3)	(since C++11)`
* `type-constraint name(optional)	(4)	(since C++20)`
* `type-constraint name(optional) = default	(5)	(since C++20)`
* `type-constraint ... name(optional)	(6)	(since C++20)`
* type-parameter-key	-	either `typename` or `class`. There is no difference between these keywords in a type template parameter declaration
* type-constraint	-	either the name of a concept or the name of a concept followed by a list of template arguments (in angle brackets). Either way, the concept name may be optionally qualified
* 1) A type template parameter without a default.
```c++
template<class T>
class My_vector { /* ... */ };
```
* 2) A type template parameter with a default.
```c++
template<class T = void>
struct My_op_functor { /* ... */ };
```
* 3) A type template parameter pack.
```c++
template<typename... Ts>
class My_tuple { /* ... */ };
```
* 4) A constrained type template parameter without a default.
```c++
template<My_concept T>
class My_constrained_vector { /* ... */ };
```
* 5) A constrained type template parameter with a default.
```c++
template<My_concept T = void>
class My_constrained_op_functor { /* ... */ };
```
* 6) A constrained type template parameter pack.
```c++
template<My_concept... Ts>
class My_constrained_tuple { /* ... */ };
```
* The name of the parameter is optional:
```c++
// Declarations of the templates shown above:
template<class>
class My_vector;

template<class = void>
struct My_op_functor;

template<typename...>
class My_tuple;
```
* In the body of the template declaration, the name of a type parameter is a `typedef-name which aliases the type supplied when the template is instantiated`.

###### Template template parameter

* `template < parameter-list > type-parameter-key name(optional)`	(1)	
* `template < parameter-list > type-parameter-key name(optional) = default`	(2)	
* `template < parameter-list > type-parameter-key ... name(optional)`	(3)	(since C++11)
* type-parameter-key	-	class `or typename (since C++17)`
    * 1) A template template parameter with an optional name.
    * 2) A template template parameter with an optional name and a default.
    * 3) A template template parameter pack with an optional name.
* In the body of the template declaration, the name of this parameter is a `template-name (and needs arguments to be instantiated)`.
```c++
template<typename T>
class my_array {};
 
// two type template parameters and one template template parameter:
template<typename K, typename V, template<typename> typename C = my_array>
class Map
{
    C<K> key;
    C<V> value;
};
```

###### Name resolution for template parameters

##### Template arguments

* In order for a template to be instantiated, every template parameter (`type`, `non-type`, or `template`) must be replaced by a corresponding template argument. For `class templates`, the arguments are either explicitly provided`, deduced from the initializer, (since C++17)` or defaulted. For `function templates`, the arguments are explicitly provided, deduced from the context, or defaulted.
* If an argument can be interpreted as both a `type-id` and an `expression`, it is always interpreted as a type-id, even if the corresponding template parameter is non-type:
```c++
template<class T>
void f(); // #1
 
template<int I>
void f(); // #2
 
void g()
{
    f<int()>(); // "int()" is both a type and an expression,
                // calls #1 because it is interpreted as a type
}
```

###### Template non-type arguments

* The following limitations apply when instantiating templates that have non-type template parameters:
* ...

###### Template type arguments

* A template argument for a type template parameter must be a type-id, which may name an incomplete type:
```c++
template<typename T>
class X {}; // class template
 
struct A;            // incomplete type
typedef struct {} B; // type alias to an unnamed type
 
int main()
{
    X<A> x1;  // OK: 'A' names a type
    X<A*> x2; // OK: 'A*' names a type
    X<B> x3;  // OK: 'B' names a type
}
```

###### Template template arguments

* A template argument for a template template parameter must be an `id-expression` which names a class template or a template alias.

###### Default template arguments

* Default template arguments are specified in the parameter lists after the `=` sign. Defaults can be specified for any kind of template parameter (type, non-type, or template), but not to parameter packs.
* If the default is specified for a template parameter of a primary class template`, primary variable template, (since C++14)` or alias template, each subsequent template parameter must have a default argument, except the very last one may be a template parameter pack. In a function template, there are no restrictions on the parameters that follow a default, and a parameter pack may be followed by more type parameters only if they have defaults or can be deduced from the function arguments.

###### Template argument equivalence

#### [Class template](https://en.cppreference.com/w/cpp/language/class_template)

* [C++ Class Template Specialization | HackerRank](https://www.hackerrank.com/challenges/cpp-class-template-specialization/problem) 
```c++
#include <iostream>
using namespace std;
enum class Fruit { apple, orange, pear };
enum class Color { red, green, orange };

template <typename T> struct Traits;
template<typename T> struct Traits {
    static string name(int index)
    {
        switch (index) {
            case 0:
                return ((typeid(T) == typeid(Fruit)) ? "apple" : "red");
            case 1:
                return ((typeid(T) == typeid(Fruit)) ? "orange" : "green");
            case 2:
                return ((typeid(T) == typeid(Fruit)) ? "pear" : "orange");
            default:
                return "unknown";
        }
    }
};

int main()
{
    int t = 0; std::cin >> t;

    for (int i=0; i!=t; ++i) {
        int index1; std::cin >> index1;
        int index2; std::cin >> index2;
        cout << Traits<Color>::name(index1) << " ";
        cout << Traits<Fruit>::name(index2) << "\n";
    }
    
    return 0;
}
```

##### [Curiously Recurring Template Pattern (CRTP)](https://en.cppreference.com/w/cpp/language/crtp)

* The Curiously Recurring Template Pattern is an idiom in which a class X derives from a class template Y, taking a template parameter Z, where Y is instantiated with Z=X.
```c++
template<class Z>
class Y {};

class X : public Y<X> {};
```
* CRTP may be used to implement "compile-time polymorphism", when a base class exposes an interface, and derived classes implement such interface.
```c++
#include <iostream>

template <class Derived>
struct Base { void name() { (static_cast<Derived*>(this))->impl(); } };

struct D1 : public Base<D1> { void impl() { std::cout << "D1::impl()\n"; } };
struct D2 : public Base<D2> { void impl() { std::cout << "D2::impl()\n"; } };

int main()
{
    Base<D1> b1; b1.name();
    Base<D2> b2; b2.name();

    D1 d1; d1.name();
    D2 d2; d2.name();
}
/*
D1::impl()
D2::impl()
D1::impl()
D2::impl()
*/
```
* [Curiously recurring template pattern - Wikipedia](https://en.wikipedia.org/wiki/Curiously_recurring_template_pattern)
	* The curiously recurring template pattern (CRTP) is an idiom in C++ in which a class X derives from a class template instantiation using X itself as a template argument.[1] More generally it is known as F-bound polymorphism, and it is a form of F-bounded quantification.
* [Curiously recurring template pattern (CRTP) - GeeksforGeeks](https://www.geeksforgeeks.org/curiously-recurring-template-pattern-crtp-2/)

###### [The Curiously Recurring Template Pattern (CRTP) - Fluent C++](https://www.fluentcpp.com/2017/05/12/curiously-recurring-template-pattern/)

* The CRTP, episode One: Definition
* The CRTP, episode Two: What the CRTP can bring to your code
* The CRTP, episode Three: An implementation helper for the CRTP
* What CRTP is
    * The CRTP consists in:
        * `inheriting from a template class`,
        * `use the derived class itself as a template parameter of the base class`.
    * The purpose of doing this is `using the derived class in the base class`. From the perspective of the base object, the derived object is itself, but downcasted. Therefore the base class can access the derived class by `static_casting` itself into the derived class.
    * Note that contrary to typical casts to derived class, we don’t use `dynamic_cast` here. A `dynamic_cast` is used when you want to make sure at run-time that the derived class you are casting into is the correct one. But here we don’t need this guarantee: the Base class is `designed` to be inherited from by its template parameter, and by nothing else. Therefore it takes this as an assumption, and a `static_cast` is enough.
    ```c++
    template <typename T>
    class Base
    {
    public:
        void doSomething()
        {
            T& derived = static_cast<T&>(*this);
            use derived...
        }
    };

    class Derived : public Base<Derived>
    {
        ...
    };
    ```
* What could go wrong
    * `If two classes happen to derive from the same CRTP base class we likely get to undefined behaviour when the CRTP will try to use the wrong class`:
    ```c++
    class Derived1 : public Base<Derived1>
    {
        ...
    };

    class Derived2 : public Base<Derived1> // bug in this line of code
    {
        ...
    };
    ```
    * There is a solution to prevent this. It consists in `adding a private constructor in the base class, and making the base class friend with the templated class`:
    ```c++
    template <typename T>
    class Base
    {
    public:
        // ...
    private:
        Base(){};
        friend T;
    };
    ```
    * Indeed, the constructors of the derived class have to call the constructor of the base class (even if you don’t write it explicitly in the code, the compiler will do his best to do it for you). Since the constructor in the base class is private, no one can access it except the friend classes. And the only friend class is `the template class`! `So if the derived class is different from the template class, the code doesn’t compile`.
    * Another risk with CRTP is that `methods in the derived class will hide methods from the base class with the same name`. As explained in Effective C++ Item 33, the reason for that is that these methods are not virtual. Therefore you want to be careful not to have identical names in the base and derived classes:
    ```c++
    class Derived : public Base<Derived>
    {
    public:
        void doSomething(); // oops this hides the doSomething methods from the base class !
    }
    ```

#
[What the Curiously Recurring Template Pattern can bring to your code - Fluent C++](https://www.fluentcpp.com/2017/05/16/what-the-crtp-brings-to-code/)

* But there are several ways the `CRTP` can be useful. Here I am presenting the one that I see most in code, `Adding Functionality`, and another one that is interesting but that I don’t encounter as often: creating `Static Interfaces`.
* Adding functionality
    * Some classes provide generic functionality, that can be re-used by many other classes.
    * This is where the CRTP comes into play. Here we can factor out the 3 numerical functions into a separate class:
    * and use the CRTP to allow Sensitivity to use it:
    * For this to work, the implementation of the 3 numerical methods need to access the getValue and setValue methods from the Sensitivity class:
    * This way we effectively `added functionality` to the initial Sensitivity class by using the `CRTP`. And this class can be inherited from by other classes, by using the same technique.
    ```c++
    template <typename T>
    struct NumericalFunctions
    {
        void scale(double multiplicator)
        {
            T& underlying = static_cast<T&>(*this);
            underlying.setValue(underlying.getValue() * multiplicator);
        }
        void square()
        {
            T& underlying = static_cast<T&>(*this);
            underlying.setValue(underlying.getValue() * underlying.getValue());
        }
        void setToOpposite()
        {
            scale(-1);
        };
    };

    class Sensitivity : public NumericalFunctions<Sensitivity>
    {
    public:
        double getValue() const;
        void setValue(double value);
        // rest of the sensitivity's rich interface...
    };
    ```
* Why not non-member template functions?
    * There is at least one argument for using the `CRTP` over `non-member template functions`: `the CRTP shows in the interface`.
    * With the CRTP, you can see that Sensitivity offers the interface of NumericalFunctions:
    * And with the template non-member functions you don’t. They would be hidden behind a `#include` somewhere.
    * And even if you knew the existence of these 3 non-member functions, you wouldn’t have the guarantee that they would be compatible with a particular class (maybe they call get() or getData() instead of getValue()?). Whereas with the CRTP the code binding Sensitivity has already been compiled, so you know they have a `compatible interface`.
* Who’s Your Interface Now?
    * A interesting point to note is that, although the `CRTP` uses `inheritance`, its usage of it does not have the same meaning as other cases of inheritance.
    * With the CRTP the situation is radically different. The derived class does not express the fact it `is a` base class. Rather, it `expands its interface` by inherting from the base class, in order to add more functionality. In this case it makes sense to use the derived class directly, and to never use the base class (which is true for this usage of the CRTP, but `not` the one described below on `static interfaces`).
    * Therefore the base class is not the `interface`, and the derived class is not the `implementation`. Rather, it is the other way around: the base class uses the derived class methods (such as getValue and setValue). In this regard, `the derived class offers an interface to the base class`. This illustrates again the fact that inheritance in the context of the CRTP can express quite a different thing from classical inheritance.
* Static interfaces
    * The second usage of the CRTP is, as described in this [answer on Stack Overflow](http://stackoverflow.com/a/262984), to create `static interfaces`. In this case, the base class does represent the `interface` and the derived one does represent the `implementation`, as usual with `polymorphism`. But the difference with traditional polymorphism is that there is no `virtual` involved and all calls are resolved during `compilation`.
    * Say we have two implementations for this interface: one that always returns a constant, and one whose value can be set. These two implementations inherit from the CRTP Amount base class:
    ```c++
    #include <iostream>

    template <typename T>
    class Amount
    {
    public:
        double getValue() const
        {
            return static_cast<T const&>(*this).getValue();
        }
    };

    class Constant42 : public Amount<Constant42>
    {
    public:
        double getValue() const {return 42;}
    };

    class Variable : public Amount<Variable>
    {
    public:
        explicit Variable(int value) : value_(value) {}
        double getValue() const {return value_;}
    private:
        int value_;
    };

    template<typename T>
    void print(Amount<T> const& amount)
    {
        std::cout << amount.getValue() << '\n';
    }

    int main()
    {
        Constant42 c42;
        print(c42); // 42
        Variable v(43);
        print(v);   // 43

        return 0;
    }
    ```
    * The most important thing to note is that, although the Amount class is used polymorphically, there isn’t any `virtual` in the code. This means that the `polymorphic call` has been resolved `at compile-time`, thus avoiding the `run-time cost of virtual functions`. For more about this impact on performance you can see the [study Eli Bendersky made](http://eli.thegreenplace.net/2013/12/05/the-cost-of-dynamic-virtual-calls-vs-static-crtp-dispatch-in-c) on his (great) website.
    * From a design point of view, we were able to avoid the virtual calls here because the information of which class to use was `available at compile-time`. And like we saw in the [Extract Interface refactoring at compile-time](https://www.fluentcpp.com/2017/04/28/extract-interface-cpp/), when you know the info, why wait until the last moment to use it?

#
[The cost of dynamic (virtual calls) vs. static (CRTP) dispatch in C++ - Eli Bendersky's website](https://eli.thegreenplace.net/2013/12/05/the-cost-of-dynamic-virtual-calls-vs-static-crtp-dispatch-in-c)

* Hypothesis - what makes virtual calls slower
	* The [previous article](http://eli.thegreenplace.net/2011/05/17/the-curiously-recurring-template-pattern-in-c/) listed the following components in the runtime cost of virtual calls:
        * Extra indirection (pointer dereference) for each call to a virtual method.
        * Virtual methods usually can’t be inlined, which may be a significant cost hit for some small methods.
        * Additional pointer per object. On 64-bit systems which are prevalent these days, this is 8 bytes per object. For small objects that carry little data this may be a serious overhead.
    * While the third component can definitely play a role in some scenarios (i.e. a lot of small objects where the additional memory means less of them fit into L1 data cache), I'll focus on the first two in this article, because they are easier to expose in a simple synthetic benchmark.
* The source code - what are we comparing?
    ```c++
    class DynamicInterface {
    public:
      virtual void tick(uint64_t n) = 0;
      virtual uint64_t getvalue() = 0;
    };

    class DynamicImplementation : public DynamicInterface {
      uint64_t counter;

    public:
      DynamicImplementation()
        : counter(0) {
      }

      virtual void tick(uint64_t n) {
        counter += n;
      }

      virtual uint64_t getvalue() {
        return counter;
      }
    };

    // The following code runs the actual benchmark:

    const unsigned N = 40000;

    void run_dynamic(DynamicInterface* obj) {
      for (unsigned i = 0; i < N; ++i) {
        for (unsigned j = 0; j < i; ++j) {
          obj->tick(j);
        }
      }
    }
    ```
    * What this does is simply invoke the virtual method tick on the base pointer obj in the order of O(N^2) times.
    * The alternative statically-polymorphic implementation is this [1]:
    ```c++
    template <typename Implementation>
    class CRTPInterface {
    public:
      void tick(uint64_t n) {
        impl().tick(n);
      }

      uint64_t getvalue() {
        return impl().getvalue();
      }
    private:
      Implementation& impl() {
        return *static_cast<Implementation*>(this);
      }
    };

    class CRTPImplementation : public CRTPInterface<CRTPImplementation> {
      uint64_t counter;
    public:
      CRTPImplementation()
        : counter(0) {
      }

      void tick(uint64_t n) {
        counter += n;
      }

      uint64_t getvalue() {
        return counter;
      }
    };

    template <typename Implementation>
    void run_crtp(CRTPInterface<Implementation>* obj) {
      for (unsigned i = 0; i < N; ++i) {
        for (unsigned j = 0; j < i; ++j) {
          obj->tick(j);
        }
      }
    }
    ```
* Performance numbers
    * As expected, the `CRTP approach is much faster`. The benchmark above takes 1.25 seconds on my i7-4771 CPU for run_dynamic and 0.21 seconds for run_crtp This is a huge difference, and it's much larger than I expected. I was looking for a 2x boost, not `6x` [2]. So here comes the 4th bullet of the benchmarking methodology I outlined above. Let's look more carefully at the numbers.
* Conclusions
    * Benchmarking is an art - if everything is too easy, you're either doing something trivial or wrong. Always cross-verify your assumptions and results with hard data like disassembly listings and detailed performance numbers.
    * Beware of different compilers and different targets. The above discusses gcc 4.8 for x86-64. Elsewhere, you may expect slightly or considerably different results. Ah, if only programming was easy. But then I guess programmers wouldn't get paid a lot for clicking in front of computers all day.
    * Compiler optimizations are, by definition, a multi-layered affair. Each is simple but they enable each other. Inlining enables some additional optimizations (such as moving hot code out of inner loops). Other optimizations may enable inlining (by making the leaf methods smaller).
    * CRTP, when implemented correctly, is recognized by the compiler as static dispatch and optimized accordingly.
    * CRTP can thus be significantly more efficient than virtual calls, mostly due to inlining. This also means that inlining is crucial to its performance (as it is to many performance features of C++).
* [1]	This is a degenerate use of CRTP, for sure. It's not here to be realistic - just to demonstrate the same mechanism used in a simple scenario. See the previous article for a more use-focused discussion of CRTP.
* [2]	These numbers depend on the CPU, of course. When I tried the same benchmark on a Xeon E5-2690 (Sandy Bridge) with gcc 4.6.3 (same code generated) the speed difference is just `3x` (0.46 vs 1.39 sec).

#
[An Implementation Helper For The Curiously Recurring Template Pattern - Fluent C++](https://www.fluentcpp.com/2017/05/19/crtp-helper/)

* In this final episode of the series on the `Curiously Recuring Template Pattern`, let’s see an implementation that makes it easier to write `CRTP` classes.
* Getting rid of static_cast
    * It would be nice to factor out these static_casts. This can be achieved by forwarding the underlying type to a higher hierarchy level:
    * Plus it deals with the case where the underlying object is const, which we hadn’t mentioned yet.
    ```c++
    template <typename T>
    struct crtp
    {
        T& underlying() { return static_cast<T&>(*this); }
        T const& underlying() const { return static_cast<T const&>(*this); }
    };

    template <typename T>
    struct NumericalFunctions : crtp<T>
    {
        void scale(double multiplicator)
        {
            this->underlying().setValue(this->underlying().getValue() * multiplicator);
        }
        // ...
    };
    ```
    * Note that the `static_cast` is gone and a `this->` appeared. Without it the code would not compile. Indeed, the compiler is not sure where underlying is declared. Even if it is declared in the template class crtp, in theory nothing guarantees that this template class won’t be specialized and rewritten on a particular type, that would not expose an underlying method. For that reason, names in template base classes are ignored in C++.
    * Using `this->` is a way to include them back in the scope of functions considered to resolve the call. There are other ways to do it, although they are arguably not as adapted to this situation. In any case, you can read all about this topic in Effective C++ Item 43.
    * Anyway, the above code relieves you from writing the `static_casts`, which become really cumbersome when they are several of them.
    * All this works if you class `only add one functionality` via CRTP, but it stops working if there are `more`.
* Adding several functionalities with CRTP
    * For the sake of the example let’s split our CRTP classes into two: one that scales values and one that squares them:
    * And add these two functionalities to the Sensitivity class:
    * This looks ok at first glance but does not compile as soon as we call a method of either one of the base class!
        * `error: 'crtp<Sensitivity>' is an ambiguous base of 'Sensitivity'`
    * The reason is that we have a diamond inheritance here:
    * ![image](https://user-images.githubusercontent.com/34557994/210545204-dfccecb5-8a47-4e4f-84a8-08861a6c44cc.png)
    * Another approach is to steer away from the `diamond inheritance` (which sounds like a good idea), by having every functionality (scale, square) `inherit` from its own crtp class. And this can be achieved by `CRTP`!
    * Indeed, we can add a `template parameter` to the crtp class, corresponding to the base class. Note the addition of the crtpType template parameter.
    ```c++
    template <typename T, template<typename> class crtpType>
    struct crtp
    {
        T& underlying() { return static_cast<T&>(*this); }
        T const& underlying() const { return static_cast<T const&>(*this); }
    private:
        crtp(){}
        friend crtpType<T>;
    };
    ```
    * Note that the template parameter is not just a `typename`, but rather a `template<typename> class`. This simply means that the parameter is not just a type, bu rather a template itself, templated over a type whose name is omitted. For example crtpType can be Scale.
    * This parameter is here to differentiate types only, and is not used in the implementation of crtp (except for the technical check in the friend declaration). Such an unused template parameter is called a `phantom type` (or to be more accurate here we could call it a `phantom template`).
    * The class hierarchy now looks like the following:
    * ![image](https://user-images.githubusercontent.com/34557994/210545784-c34da1b2-02c7-401c-b3b8-db82428a822e.png)

#### [Function template](https://en.cppreference.com/w/cpp/language/function_template)

* A function template defines a family of functions.

##### Syntax

* `template < parameter-list > function-declaration`	(1)	
* `template < parameter-list > requires constraint function-declaration	(2)`	(since C++20)
* `function-declaration-with-placeholders`	(3)	(since C++20)

##### Explanation

* `parameter-list`	-	a non-empty comma-separated list of the template parameters, each of which is either non-type parameter, a type parameter, a template parameter, or a parameter pack of any of those. `As with any template, parameters may be constrained (since C++20)`
* `function-declaration`	-	a function declaration. The function name declared becomes a template name.
* `constraint`	-	a constraint expression which restricts the template parameters accepted by this function template
* `function-declaration-with-placeholders`	-	a function declaration where the type of at least one parameter uses the placeholder auto or Concept auto: the template parameter list will have one invented parameter for each placeholder (see Abbreviated function templates below)

#### [Parameter pack](https://en.cppreference.com/w/cpp/language/parameter_pack)

* A template parameter pack is a template parameter that accepts `zero or more template arguments (non-types, types, or templates)`. A function parameter pack is a function parameter that accepts `zero or more function arguments`.
* A template with at least `one parameter pack` is called a `variadic template`.
* Example
    * The below example defines a function similar to std::printf, that replace each occurrence of the character % in the format string with a value.
    * The first overload is called when only the format string is passed and there is no parameter expansion.
    * The second overload contains a separate template parameter for the head of the arguments and a parameter pack, this allows the recursive call to pass only the tail of the parameters until it becomes empty.
    * Targs is the `template parameter pack` and Fargs is the `function parameter pack`.
```c++
#include <iostream>
 
void tprintf(const char* format) // base function
{
    std::cout << format;
}
 
template<typename T, typename... Targs>
void tprintf(const char* format, T value, Targs... Fargs) // recursive variadic function
{
    for (; *format != '\0'; format++)
    {
        if (*format == '%')
        {
            std::cout << value;
            tprintf(format + 1, Fargs...); // recursive call
            return;
        }
        std::cout << *format;
    }
}
 
int main()
{
    tprintf("% world% %\n", "Hello", '!', 123);
}
/*
Hello world! 123
*/
```

##### Syntax

* Template parameter pack (appears in alias template, class template`, variable template (since C++14)` and function template parameter lists)
    * `type ... pack-name(optional)`	(1)	
    * `typename|class ... pack-name(optional)`	(2)	
    * `type-constraint ... pack-name(optional)`	(3)	(since C++20)
    * `template < parameter-list > typename|class ... pack-name(optional)`	(4)	(since C++17)
    * Function parameter pack (a form of declarator, appears in a function parameter list of a variadic function template)
    * `pack-name ... pack-param-name(optional)`	(5)	
    * Parameter pack expansion (appears in a body of a variadic template)
    * `pattern ...`	(6)	
    * 1) A non-type template parameter pack with an optional name
    * 2) A type template parameter pack with an optional name
    * 3) A constrained type template parameter pack with an optional name (since C++20)
    * 4) A template template parameter pack with an optional name
    * 5) A function parameter pack with an optional name
    * 6) Parameter pack expansion: expands to comma-separated list of zero or more patterns. Pattern must include at least one parameter pack.

##### Explanation

* A variadic class template can be instantiated with any number of template arguments:
```c++
template<class... Types>
struct Tuple {};
 
Tuple<> t0;           // Types contains no arguments
Tuple<int> t1;        // Types contains one argument: int
Tuple<int, float> t2; // Types contains two arguments: int and float
Tuple<0> t3;          // error: 0 is not a type
```
* A variadic function template can be called with any number of function arguments (the template arguments are deduced through template argument deduction):
```c++
template<class... Types>
void f(Types... args);
 
f();       // OK: args contains no arguments
f(1);      // OK: args contains one argument: int
f(2, 1.0); // OK: args contains two arguments: int and double
```
* In a primary class template, the template parameter pack must be the final parameter in the template parameter list. In a function template, the template parameter pack may appear earlier in the list provided that all following parameters can be deduced from the function arguments, or have default arguments:
```c++
template<typename U, typename... Ts>    // OK: can deduce U
struct valid;
// template<typename... Ts, typename U> // Error: Ts... not at the end
// struct Invalid;
 
template<typename... Ts, typename U, typename=void>
void valid(U, Ts...);    // OK: can deduce U
// void valid(Ts..., U); // Can't be used: Ts... is a non-deduced context in this position
 
valid(1.0, 1, 2, 3);     // OK: deduces U as double, Ts as {int, int, int}
```
* If every valid specialization of a variadic template requires an empty template parameter pack, the program is ill-formed, no diagnostic required.

##### Pack expansion

* A pattern followed by an ellipsis, in which the name of at least one parameter pack appears at least once, is expanded into zero or more comma-separated instantiations of the pattern, where the name of the parameter pack is replaced by each of the elements from the pack, in order.
```c++
template<class... Us>
void f(Us... pargs) {}
 
template<class... Ts>
void g(Ts... args)
{
    f(&args...); // “&args...” is a pack expansion
                 // “&args” is its pattern
}
 
g(1, 0.2, "a"); // Ts... args expand to int E1, double E2, const char* E3
                // &args... expands to &E1, &E2, &E3
                // Us... pargs expand to int* E1, double* E2, const char** E3
```

##### Expansion loci

* Depending on where the expansion takes place, the resulting comma-separated list is a different kind of list: function parameter list, member initializer list, attribute list, etc. The following is the list of all allowed contexts:
* ...

##### [sizeof... operator](https://en.cppreference.com/w/cpp/language/sizeof...)

* Queries the number of elements in a parameter pack.
* Syntax
    * `sizeof...( parameter-pack )`
    * Returns a constant of type std::size_t.
* Example
```c++
#include <array>
#include <iostream>
#include <type_traits>
 
template<typename... Ts>
constexpr auto make_array(Ts&&... ts)
{
    using CT = std::common_type_t<Ts...>;
    return std::array<CT, sizeof...(Ts)>{std::forward<CT>(ts)...};
}
 
int main()
{
    std::array<double, 4ul> arr = make_array(1, 2.71f, 3.14, '*');
    std::cout << "arr = { ";
    for (auto s{arr.size()}; double elem : arr)
        std::cout << elem << (--s ? ", " : " ");
    std::cout << "}\n";
}
/*
arr = { 1, 2.71, 3.14, 42 }
*/
```

##### [fold expression](https://en.cppreference.com/w/cpp/language/fold)

* Reduces (folds) a parameter pack over a binary operator.

###### Syntax

* `( pack op ... )`	(1)	
* `( ... op pack )`	(2)	
* `( pack op ... op init )`	(3)	
* `( init op ... op pack )`	(4)	
* 1) unary right fold
* 2) unary left fold
* 3) binary right fold
* 4) binary left fold
* op	-	any of the following 32 binary operators: `+ - * / % ^ & | = < > << >> += -= *= /= %= ^= &= |= <<= >>= == != <= >= && || , .* ->*`. In a binary fold, both ops must be the same.
* pack	-	an expression that contains an unexpanded parameter pack and does not contain an operator with precedence lower than cast at the top level (formally, a cast-expression)
* init	-	an expression that does not contain an unexpanded parameter pack and does not contain an operator with precedence lower than cast at the top level (formally, a cast-expression)
* Note that the opening and closing parentheses are a required part of the fold expression.

###### Explanation

* The instantiation of a fold expression expands the expression e as follows:
* 1) Unary right fold (E op ...) becomes (E1 op (... op (EN-1 op EN)))
* 2) Unary left fold (... op E) becomes (((E1 op E2) op ...) op EN)
* 3) Binary right fold (E op ... op I) becomes (E1 op (... op (EN−1 op (EN op I))))
* 4) Binary left fold (I op ... op E) becomes ((((I op E1) op E2) op ...) op EN)
* (where N is the number of elements in the pack expansion)
* For example,
```c++
template<typename... Args>
bool all(Args... args) { return (... && args); }
 
bool b = all(true, true, true, false);
// within all(), the unary left fold expands as
//  return ((true && true) && true) && false;
// b is false
```
* When a unary fold is used with a pack expansion of length zero, only the following operators are allowed:
    * 1) Logical AND (&&). The value for the empty pack is true
    * 2) Logical OR (||). The value for the empty pack is false
    * 3) The comma operator (,). The value for the empty pack is void()
* Notes
    * If the expression used as init or as pack has an operator with precedence below cast at the top level, it must be parenthesized:
```c++
template<typename... Args>
int sum(Args&&... args)
{
//  return (args + ... + 1 * 2);   // Error: operator with precedence below cast
    return (args + ... + (1 * 2)); // OK
}
```
* Example
```c++
#include <climits>
#include <concepts>
#include <cstdint>
#include <iostream>
#include <type_traits>
#include <utility>
#include <vector>
 
template<typename... Args>
void printer(Args&&... args)
{
    (std::cout << ... << args) << '\n';
}
 
template<typename T, typename... Args>
void push_back_vec(std::vector<T>& v, Args&&... args)
{
    static_assert((std::is_constructible_v<T, Args&&> && ...));
    (v.push_back(std::forward<Args>(args)), ...);
}
 
template<class T, std::size_t... dummy_pack>
constexpr T bswap_impl(T i, std::index_sequence<dummy_pack...>)
{
    T low_byte_mask = (unsigned char)-1;
    T ret{};
    ([&]
    {
        (void)dummy_pack;
        ret <<= CHAR_BIT;
        ret |= i & low_byte_mask;
        i >>= CHAR_BIT;
    }(), ...);
    return ret;
}
 
constexpr auto bswap(std::unsigned_integral auto i)
{
    return bswap_impl(i, std::make_index_sequence<sizeof(i)>{});
}
 
int main()
{
    printer(1, 2, 3, "abc");
 
    std::vector<int> v;
    push_back_vec(v, 6, 2, 45, 12);
    push_back_vec(v, 1, 2, 9);
    for (int i : v) std::cout << i << ' ';
 
    static_assert(bswap<std::uint16_t>(0x1234u) == 
                                       0x3412u);
    static_assert(bswap<std::uint64_t>(0x0123456789abcdefull) ==
                                       0xefcdab8967452301ULL);
}
/*
123abc
6 2 45 12 1 2 9
*/
```

##### MISC

* [C++ Variadics | HackerRank](https://www.hackerrank.com/challenges/cpp-variadics/problem)
```c++
#include <iostream>
using namespace std;

// Enter your code for reversed_binary_value<bool...>()
template <bool a> int reversed_binary_value() { return a; }

template <bool a, bool b, bool... d> int reversed_binary_value() {
    return (reversed_binary_value<b, d...>() << 1) + a;
}

template <int n, bool...digits>
struct CheckValues {
    static void check(int x, int y)
    {
        CheckValues<n-1, 0, digits...>::check(x, y);
        CheckValues<n-1, 1, digits...>::check(x, y);
    }
};

template <bool...digits>
struct CheckValues<0, digits...> {
    static void check(int x, int y)
    {
        int z = reversed_binary_value<digits...>();
        std::cout << (z+64*y==x);
    }
};

int main()
{
    int t; std::cin >> t;

    for (int i=0; i!=t; ++i) {
        int x, y;
        cin >> x >> y;
        CheckValues<6>::check(x, y);
        cout << "\n";
    }
}
```

### [Exceptions](https://en.cppreference.com/w/cpp/language/exceptions)

* Exception handling provides a way of transferring control and information from some point in the execution of a program to a handler associated with a point previously passed by the execution (in other words, exception handling transfers control up the call stack)
* An exception can be thrown by a `throw-expression, dynamic_cast, typeid, new-expression, allocation function, and any of the standard library functions` that are specified to throw exceptions to signal certain error conditions (e.g. `std::vector::at`, `std::string::substr`, etc).
* In order for an exception to be caught, the throw-expression has to be inside a `try-block` or inside a function called from a try-block, and there has to be a `catch clause` that matches the type of the exception object.
* When declaring a function, the following specification(s) may be provided to limit the types of the exceptions a function may throw:
    * `dynamic exception specifications (until C++17)`
    * `noexcept specifications (since C++11)`
* Errors that arise during exception handling are handled by `std::terminate` and `std::unexpected (until C++17)`.
* Error handling
    * Throwing an exception is used to signal errors from functions, where "errors" are typically limited to only the following[1][2][3]:
        * Failures to meet the postconditions, such as failing to produce a valid return value object
        * Failures to meet the preconditions of another function that must be called
        * (for non-private member functions) Failures to (re)establish a class invariant
    * In particular, this implies that the failures of constructors (see also RAII) and most operators should be reported by throwing exceptions.
    * In addition, so-called wide contract functions use exceptions to indicate unacceptable inputs, for example, std::string::at has no preconditions, but throws an exception to indicate index out of range.
* Exception safety
    * After the error condition is reported by a function, additional guarantees may be provided with regards to the state of the program. The following four levels of exception guarantee are generally recognized[4][5][6], which are strict supersets of each other:
        * `Nothrow (or nofail) exception guarantee` -- the function never throws exceptions. Nothrow (errors are reported by other means or concealed) is expected of destructors and other functions that may be called during stack unwinding. `The destructors are noexcept by default. (since C++11)` Nofail (the function always succeeds) is expected of `swaps`, `move constructors`, and other functions used by those that provide strong exception guarantee.
        * `Strong exception guarantee` -- If the function throws an exception, the state of the program is rolled back to the state just before the function call. (for example, `std::vector::push_back`)
        * `Basic exception guarantee` -- If the function throws an exception, the program is in a valid state. No resources are leaked, and all objects' invariants are intact.
        * `No exception guarantee` -- If the function throws an exception, the program may not be in a valid state: resource leaks, memory corruption, or other invariant-destroying errors may have occurred.
    * Generic components may, in addition, offer exception-neutral guarantee: if an exception is thrown from a template parameter (e.g. from the Compare function object of std::sort or from the constructor of T in std::make_shared), it is propagated, unchanged, to the caller.
* Exception objects
    * While objects of any complete type and cv pointers to void may be thrown as exception objects, all standard library functions throw anonymous temporary objects by value, and the types of those objects are derived (directly or indirectly) from std::exception. User-defined exceptions usually follow this pattern.[7][8][9]
    * To avoid unnecessary copying of the exception object and object slicing, the best practice for catch clauses is to catch by reference.[10][11][12][13]

#### [throw expression](https://en.cppreference.com/w/cpp/language/throw)

* Signals an erroneous condition and executes an error handler.

##### Syntax

* `throw expression`	(1)
* `throw`	(2)	

##### Stack unwinding

* Once the exception object is constructed, the control flow works backwards (up the call stack) until it reaches the start of a try block, at which point the parameters of all associated catch blocks are compared, in order of appearance, with the type of the exception object to find a match (see try-catch for details on this process). If no match is found, the control flow continues to unwind the stack until the next try block, and so on. If a match is found, the control flow jumps to the matching catch block.
* ...
* This process is called stack unwinding.
* If any function that is called directly by the stack unwinding mechanism, after initialization of the exception object and before the start of the exception handler, exits with an exception, std::terminate is called. Such functions include destructors of objects with automatic storage duration whose scopes are exited, and the copy constructor of the exception object that is called (if not elided) to initialize catch-by-value arguments.
* If an exception is thrown and not caught, including exceptions that escape the initial function of std::thread, the main function, and the constructor or destructor of any static or thread-local objects, then std::terminate is called. It is implementation-defined whether any stack unwinding takes place for uncaught exceptions.

##### Explanation

* Notes
    * When rethrowing exceptions, the second form must be used to avoid `object slicing` in the (typical) case where exception objects use inheritance:
    ```c++
    try
    {
        std::string("abc").substr(10); // throws std::length_error
    }
    catch (const std::exception& e)
    {
        std::cout << e.what() << '\n';
    //  throw e; // copy-initializes a new exception object of type std::exception
        throw;   // rethrows the exception object of type std::length_error
    }
    ```
    * The throw-expression is classified as `prvalue expression` of type `void`. Like any other expression, it may be a sub-expression in another expression, most commonly in the `conditional operator`:
    ```c++
    double f(double d)
    {
        return d > 1e7 ? throw std::overflow_error("too big") : d;
    }

    int main()  
    {
        try
        {
            std::cout << f(1e10) << '\n';
        }
        catch (const std::overflow_error& e)
        {
            std::cout << e.what() << '\n';
        }
    }
    ```
* Example
```c++
#include <iostream>
#include <stdexcept>
 
struct A
{
    int n;
 
    A(int n = 0): n(n) { std::cout << "A(" << n << ") constructed successfully\n"; }
    ~A() { std::cout << "A(" << n << ") destroyed\n"; }
};
 
int foo()
{
    throw std::runtime_error("error");
}
 
struct B
{
    A a1, a2, a3;
 
    B() try : a1(1), a2(foo()), a3(3)
    {
        std::cout << "B constructed successfully\n";
    }
    catch(...)
    {
    	std::cout << "B::B() exiting with exception\n";
    }
 
    ~B() { std::cout << "B destroyed\n"; }
};
 
struct C : A, B
{
    C() try
    {
        std::cout << "C::C() completed successfully\n";
    }
    catch(...)
    {
        std::cout << "C::C() exiting with exception\n";
    }
 
    ~C() { std::cout << "C destroyed\n"; }
};
 
int main () try
{
    // creates the A base subobject
    // creates the a1 member of B
    // fails to create the a2 member of B
    // unwinding destroys the a1 member of B
    // unwinding destroys the A base subobject
    C c;
}
catch (const std::exception& e)
{
    std::cout << "main() failed to create C with: " << e.what();
}
/*
A(0) constructed successfully
A(1) constructed successfully
A(1) destroyed
B::B() exiting with exception
A(0) destroyed
C::C() exiting with exception
main() failed to create C with: error
*/
```

#### [Function-try-block](https://en.cppreference.com/w/cpp/language/function-try-block)

* Establishes an exception handler around the body of a function.

##### Syntax

* The function-try-block is one of the alternative syntax forms for function-body, which is a part of function definition.
* `try ctor-initializer(optional) compound-statement handler-sequence`
* ctor-initializer	-	member initializer list, only allowed in constructors
* compound-statement	-	the brace-enclosed sequence of statements that constitutes the body of a function
* handler-sequence	-	sequence of one or more catch-clauses

##### Explanation

* A `function-try-block` associates a sequence of catch clauses with the entire function body, and with the `member initializer list` (if used in a constructor) as well. Every exception thrown from any statement in the function body, or (for constructors) from any member or base constructor, or (for destructors) from any member or base destructor, transfers control to the `handler-sequence` the same way an exception thrown in a regular `try block` would.
```c++
#include <iostream>
#include <string>
 
struct S
{
    std::string m;
 
    S(const std::string& str, int idx) try : m(str, idx)
    {
        std::cout << "S(" << str << ", " << idx << ") constructed, m = " << m << '\n';
    }
    catch(const std::exception& e)
    {
        std::cout << "S(" << str << ", " << idx << ") failed: " << e.what() << '\n';
    } // implicit "throw;" here
};
 
int main()
{
    S s1{"ABC", 1}; // does not throw (index is in bounds)
 
    try
    {
        S s2{"ABC", 4}; // throws (out of bounds)
    }
    catch (std::exception& e)
    {
        std::cout << "S s2... raised an exception: " << e.what() << '\n';
    }
}
/*
Output:

S(ABC, 1) constructed, m = BC
S(ABC, 4) failed: basic_string::basic_string: __pos (which is 4) > this->size() (which is 3)
S s2... raised an exception: basic_string::basic_string: __pos (which is 4) > this->size() (which is 3)
*/
```
* Before any catch clauses of a function-try-block on a constructor are entered, all fully-constructed members and bases have already been destroyed.
* If the function-try-block is on a delegating constructor, which called a non-delegating constructor that completed successfully, but then the body of the delegating constructor throws, the destructor of this object will be completed before any catch clauses of the function-try-block are entered. (since C++11)
* Before any catch clauses of a function-try-block on a destructor are entered, all bases and non-variant members have already been destroyed.
* The behavior is undefined if the catch-clause of a function-try-block used on a constructor or a destructor accesses a base or a non-static member of the object.
* Every catch-clause in the function-try-block for a constructor must terminate by throwing an exception. If the control reaches the end of such handler, the current exception is automatically rethrown as if by `throw;`. The return statement is not allowed in any catch clause of a constructor's function-try-block.
* Reaching the end of a catch clause for a function-try-block on a destructor also automatically rethrows the current exception as if by `throw;`, but a return statement is allowed.
* For all other functions, reaching the end of a catch clause is equivalent to `return;` if the function's return type is (possibly cv-qualified) `void`, otherwise the behavior is undefined.
* Notes
    * The primary purpose of function-try-blocks is to respond to an exception thrown from the member initializer list in a constructor by logging and rethrowing, modifying the exception object and rethrowing, throwing a different exception instead, or terminating the program. They are rarely used with destructors or with regular functions.
    * Function-try-block does not catch the exceptions thrown by the copy/move constructors and the destructors of the function parameters passed by value: those exceptions are thrown in context of the caller.
    * Function-try-block of the top-level function of a thread does not catch the exceptions thrown from the constructors and destructors of thread-local objects (except for the constructors of function-scoped thread-locals).	(since C++11)
    * Likewise, function-try-block of the main() function does not catch the exceptions thrown from the constructors and destructors of static objects (except for the constructors of function-local statics).
    * The scope and lifetime of the function parameters (but not any objects declared in the function itself), extend to the end of the handler-sequence.
```c++
#include <cassert>
#include <iostream>

int f(int n = 2) try
{
    ++ n; // increments the function parameter
    throw n;
}
catch(...)
{
    ++ n; // n is in scope and still refers to the function parameter
    assert(n == 4);
    return n;
}

int main()
{
    std::cout << f();   // 4
}
```

#### [try/catch block](https://en.cppreference.com/w/cpp/language/try_catch)

* Associates one or more exception handlers (catch-clauses) with a compound statement.

##### Syntax

* `try compound-statement handler-sequence`
* where handler-sequence is a sequence of one or more handlers, which have the following syntax:
    * `catch ( attr(optional) type-specifier-seq declarator ) compound-statement`	(1)	
    * `catch ( attr(optional) type-specifier-seq abstract-declarator(optional) ) compound-statement`	(2)	
    * `catch ( ... ) compound-statement`	(3)	
    * compound-statement	-	brace-enclosed sequence of statements
    * attr	-	(since C++11) any number of attributes, applies to the formal parameter
    * type-specifier-seq	-	part of a formal parameter declaration, same as in a function parameter list
    * declarator	-	part of a formal parameter declaration, same as in a function parameter list
    * abstract-declarator	-	part of an unnamed formal parameter declaration, same as in function parameter list
    * 1) Catch-clause that declares a named formal parameter
        * `try { /* */ } catch (const std::exception& e) { /* */ }`
    * 2) Catch-clause that declares an unnamed parameter
        * `try { /* */ } catch (const std::exception&) { /* */ }`
    * 3) Catch-all handler, which is activated for any exception
        * `try { /* */ } catch (...) { /* */ }`

##### Explanation

```c++
try
{
    f();
}
catch (const std::overflow_error& e)
{} // this executes if f() throws std::overflow_error (same type rule)
catch (const std::runtime_error& e)
{} // this executes if f() throws std::underflow_error (base class rule)
catch (const std::exception& e)
{} // this executes if f() throws std::logic_error (base class rule)
catch (...)
{} // this executes if f() throws std::string or int or any other unrelated type
```
* The catch-all clause `catch (...)` matches exceptions of any type. If present, it has to be the last catch clause in the `handler-seq`. Catch-all block may be used to ensure that no uncaught exceptions can possibly escape from a function that offers `nothrow exception guarantee`.
* If no matches are found after all catch-clauses were examined, the exception propagation continues to the containing try-block, as described in `throw-expression`. If there are no containing try-blocks left, `std::terminate` is executed (in this case, it is implementation-defined whether any stack unwinding occurs at all: throwing an uncaught exception is permitted to terminate the program without invoking any destructors).
* When entering a catch clause, if its formal parameter is a base class of the exception type, it is `copy-initialized` from the base class subobject of the exception object. Otherwise, it is copy-initialized from the exception object (this copy is subject to `copy elision`).
```c++
try
{
    std::string("abc").substr(10); // throws std::length_error
}
// catch (std::exception e) // copy-initialization from the std::exception base
// {
//     std::cout << e.what(); // information from length_error is lost
// }
catch (const std::exception& e) // reference to the base of a polymorphic object
{
    std::cout << e.what(); // information from length_error printed
}
```
* Notes
    * The throw-expression throw NULL; is not guaranteed to be matched by a pointer catch clause, because the exception object type may be int, but throw nullptr; is assuredly matched by any pointer or pointer-to-member catch clause.
    * If a catch-clause for a derived class is placed after the catch-clause for a base class, the derived catch-clause will never be executed:
    ```c++
    try
    {
        f();
    }
    catch (const std::exception& e)
    {} // will be executed if f() throws std::runtime_error
    catch (const std::runtime_error& e)
    {} // dead code!
    ```
    * If goto is used to exit a try-block and if any of the destructors of block-scoped automatic variables that are executed by the goto throw exceptions, those exceptions are caught by the try blocks in which the variables are defined:
    ```c++
    label:
        try
        {
            T1 t1;
            try
            {
                T2 t2;
                if (condition)
                    goto label; // destroys t2, then destroys t1, then jumps to label
            }
            catch (...) {} // catches the exception from the destructor of t2
        }
        catch (...) {}     // catches the exception from the destructor of t1
    ```
* Example
    * The following example demonstrates several usage cases of the try-catch block
```c++
#include <iostream>
#include <vector>
 
int main()
{
    try
    {
        std::cout << "Throwing an integer exception...\n";
        throw 42;
    }
    catch (int i)
    {
        std::cout << " the integer exception was caught, with value: " << i << '\n';
    }
 
    try
    {
        std::cout << "Creating a vector of size 5... \n";
        std::vector<int> v(5);
        std::cout << "Accessing the 11th element of the vector...\n";
        std::cout << v.at(10); // vector::at() throws std::out_of_range
    }
    catch (const std::exception& e) // caught by reference to base
    {
        std::cout << " a standard exception was caught, with message '"
                  << e.what() << "'\n";
    }
}
/*
Throwing an integer exception...
 the integer exception was caught, with value: 42
Creating a vector of size 5...
Accessing the 11th element of the vector...
 a standard exception was caught, with message 'out_of_range'
*/
```

#### [noexcept specifier](https://en.cppreference.com/w/cpp/language/noexcept_spec)

* Specifies whether a function could throw exceptions.

##### Syntax

* `noexcept`	(1)	
* `noexcept(expression)`	(2)	
* `throw()`     (3)	(deprecated in C++17) (removed in C++20)
* 1) Same as `noexcept(true)`
* 2) If expression evaluates to `true`, the function is declared not to throw any exceptions. A `(` following `noexcept` is always a part of this form (it can never start an initializer).
* 3) Same as `noexcept(true)` (see [dynamic exception specification](https://en.cppreference.com/w/cpp/language/except_spec) for its semantics before C++17)
* expression	-	[contextually converted constant expression of type](https://en.cppreference.com/w/cpp/language/constant_expression#Converted_constant_expression) `bool`

##### Explanation

* The noexcept-specification is a part of the function type and may appear as part of any function declarator. (since C++17)
* Functions differing only in their exception specification cannot be overloaded `(just like the return type, exception specification is part of function type, but not part of the function signature) (since C++17)`.
```c++
void f() noexcept;
void f(); // error: different exception specification
void g() noexcept(false);
void g(); // ok, both declarations for g are potentially-throwing
```
* Pointers (including pointers to member function) to non-throwing functions `can be assigned to or used to initialize (until C++17)` `are implicitly convertible to (since C++17)` pointers to potentially-throwing functions, but not the other way around.
```c++
void ft(); // potentially-throwing
void (*fn)() noexcept = ft; // error
```
* If a virtual function is non-throwing, all declarations, including the definition, of every overrider must be non-throwing as well, unless the overrider is defined as deleted:
```c++
struct B
{
    virtual void f() noexcept;
    virtual void g();
    virtual void h() noexcept = delete;
};
 
struct D: B
{
    void f();          // ill-formed: D::f is potentially-throwing, B::f is non-throwing
    void g() noexcept; // OK
    void h() = delete; // OK
};
```
* `Non-throwing functions are permitted to call potentially-throwing functions.` Whenever an exception is thrown and the search for a handler encounters the outermost block of a non-throwing function, the function std::terminate is called:
```c++
extern void f(); // potentially-throwing
 
void g() noexcept
{
    f();      // valid, even if f throws
    throw 42; // valid, effectively a call to std::terminate
}
```
* Formal definition of potentially-throwing expression (used to determine the default exception specification of destructors, constructors, and assignment operators as described above):
    * An expression e is potentially-throwing if:
        * e is a function call to a function, pointer to function, or pointer to member function which is potentially-throwing, unless e is a core constant expression (until C++17)
        * e makes an implicit call to a potentially-throwing function (such as an overloaded operator, an allocation function in a new-expression, a constructor for a function argument, or a destructor if e is a full-expression)
        * e is a throw-expression
        * e is a dynamic_cast that casts a polymorphic reference type
        * e is a typeid expression applied to a dereferenced pointer to a polymorphic type
        * e has an immediate subexpression that is potentially-throwing
```c++
struct A
{
    A(int = (A(5), 0)) noexcept;
    A(const A&) noexcept;
    A(A&&) noexcept;
    ~A();
};
 
struct B
{
    B() throw();
    B(const B&) = default; // implicit exception specification is noexcept(true)
    B(B&&, int = (throw Y(), 0)) noexcept;
    ~B() noexcept(false);
};
 
int n = 7;
struct D : public A, public B
{
    int * p = new int[n];
    // D::D() potentially-throwing because of the new operator
    // D::D(const D&) non-throwing
    // D::D(D&&) potentially-throwing: the default argument for B’s constructor may throw
    // D::~D() potentially-throwing
 
    // note; if A::~A() were virtual, this program would be ill-formed because an overrider
    // of a non-throwing virtual cannot be potentially-throwing
};
```
* Notes
    * One of the uses of the constant expression is (along with the noexcept operator) to define function templates that declare noexcept for some types but not others.
    * Note that a noexcept specification on a function is not a compile-time check; it is merely a method for a programmer to inform the compiler whether or not a function should throw exceptions. The compiler can use this information to enable certain optimizations on non-throwing functions as well as enable the noexcept operator, which can check at compile time if a particular expression is declared to throw any exceptions. For example, containers such as std::vector will move their elements if the elements' move constructor is noexcept, and copy otherwise (unless the copy constructor is not accessible, but a potentially throwing move constructor is, in which case the strong exception guarantee is waived).
    * Deprecates
        * `noexcept` is an improved version of `throw()`, which is deprecated in C++11. Unlike pre-C++17 throw(), noexcept will not call `std::unexpected`, may or may not unwind the stack, and will call `std::terminate`, which potentially allows the compiler to implement `noexcept` without the runtime overhead of `throw()`. As of C++17, `throw()` is redefined to be an exact equivalent of `noexcept(true)`.
* Example
```c++
// whether foo is declared noexcept depends on if the expression
// T() will throw any exceptions
template<class T>
void foo() noexcept(noexcept(T())) {}
 
void bar() noexcept(true) {}
void baz() noexcept { throw 42; } // noexcept is the same as noexcept(true)
 
int main() 
{
    foo<int>(); // noexcept(noexcept(int())) => noexcept(true), so this is fine
 
    bar(); // fine
    baz(); // compiles, but at runtime this calls std::terminate
}
/*
Compiler messages:

main.cpp: In function 'void baz()':
main.cpp:7:23: warning: 'throw' will always call 'terminate' [-Wterminate]
    7 | void baz() noexcept { throw 42; } // noexcept is the same as noexcept(true)
      |                       ^~~~~~~~

Output:

terminate called after throwing an instance of 'int'
*/
```

##### MISC

* [noexcept (C++) | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/noexcept-cpp?view=msvc-160)
* [Exception specifications (throw, noexcept) (C++) | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/exception-specifications-throw-cpp?view=msvc-160)
* [Modern C++ best practices for exceptions and error handling | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/errors-and-exception-handling-modern-cpp?view=msvc-160)
* [C.37: Make destructors noexcept](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c37-make-destructors-noexcept)
    * `Reason` [A destructor must not fail](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rc-dtor-fail). If a destructor tries to exit with an exception, it’s a bad design error and the program had better terminate.
    * `Note` A destructor (either user-defined or compiler-generated) is implicitly declared `noexcept` (independently of what code is in its body) if all of the members of its class have `noexcept` destructors. By explicitly marking destructors `noexcept`, an author guards against the destructor becoming implicitly `noexcept(false)` through the addition or modification of a class member.
    * `Example` Not all destructors are noexcept by default; one throwing member poisons the whole class hierarchy
    ```c++
    struct X {
        Details x;  // happens to have a throwing destructor
        // ...
        ~X() { }    // implicitly noexcept(false); aka can throw
    };
    ```
    * So, if in doubt, declare a destructor noexcept.
    * `Note` Why not then declare all destructors noexcept? Because that would in many cases – especially simple cases – be distracting clutter.
    * `Enforcement` (Simple) A destructor should be declared `noexcept` if it could throw.
* [C.66: Make move operations noexcept](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#c66-make-move-operations-noexcept)
    * `Reason` A throwing move violates most people’s reasonable assumptions. A non-throwing move will be used more efficiently by standard-library and language facilities.
    * `Example`
    ```c++
    template<typename T>
    class Vector {
    public:
        Vector(Vector&& a) noexcept :elem{a.elem}, sz{a.sz} { a.sz = 0; a.elem = nullptr; }
        Vector& operator=(Vector&& a) noexcept { elem = a.elem; sz = a.sz; a.sz = 0; a.elem = nullptr; }
        // ...
    private:
        T* elem;
        int sz;
    };
    ```
    * These operations do not throw.
    * `Example, bad`
    ```c++
    template<typename T>
    class Vector2 {
    public:
        Vector2(Vector2&& a) { *this = a; }             // just use the copy
        Vector2& operator=(Vector2&& a) { *this = a; }  // just use the copy
        // ...
    private:
        T* elem;
        int sz;
    };
    ```
    * This `Vector2` is not just inefficient, but since a vector copy requires allocation, it can throw.
    * `Enforcement` (Simple) A move operation should be marked `noexcept`.
* [E.12: Use noexcept when exiting a function because of a throw is impossible or unacceptable](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#e12-use-noexcept-when-exiting-a-function-because-of-a-throw-is-impossible-or-unacceptable)
    * `Reason` To make error handling systematic, robust, and efficient.
    * `Example`
    ```c++
    double compute(double d) noexcept
    {
        return log(sqrt(d <= 0 ? 1 : d));
    }
    ```
    * Here, we know that `compute` will not throw because it is composed out of operations that don’t throw. By declaring `compute` to be `noexcept`, we give the compiler and human readers information that can make it easier for them to understand and manipulate `compute`.
    * `Note` Many standard-library functions are `noexcept` including all the standard-library functions “inherited” from the C Standard Library.
    * `Example`
    ```c++
    vector<double> munge(const vector<double>& v) noexcept
    {
        vector<double> v2(v.size());
        // ... do something ...
    }
    ```
    * The `noexcept` here states that I am not willing or able to handle the situation where I cannot construct the local vector. That is, I consider memory exhaustion a serious design error (on par with hardware failures) so that I’m willing to crash the program if it happens.
    * `Note` Do not use traditional [exception-specifications](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Re-specifications).
    * See also [discussion](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Sd-noexcept).
* [F.6: If your function must not throw, declare it noexcept](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f6-if-your-function-must-not-throw-declare-it-noexcept)
    * `Reason` If an exception is not supposed to be thrown, the program cannot be assumed to cope with the error and should be terminated as soon as possible. Declaring a function `noexcept` helps optimizers by reducing the number of alternative execution paths. It also speeds up the exit after failure.
    * `Example` Put `noexcept` on every function written completely in C or in any other language without exceptions. The C++ Standard Library does that implicitly for all functions in the C Standard Library.
    * `Note` `constexpr` functions can throw when evaluated at run time, so you might need conditional `noexcept` for some of those.
    * `Note` You must be aware of the execution environment that your code is running when deciding whether to tag a function `noexcept`, especially because of the issue of throwing and allocation. Code that is intended to be perfectly general (like the standard library and other utility code of that sort) needs to support environments where a bad_alloc exception could be handled meaningfully. However, most programs and execution environments cannot meaningfully handle a failure to allocate, and aborting the program is the cleanest and simplest response to an allocation failure in those cases. If you know that your application code cannot respond to an allocation failure, it could be appropriate to add `noexcept` even on functions that allocate.
    * Put another way: In most programs, most functions can throw (e.g., because they use `new`, call functions that do, or use library functions that reports failure by throwing), so don’t just sprinkle `noexcept` all over the place without considering whether the possible exceptions can be handled.
    * `noexcept` is most useful (and most clearly correct) for frequently used, low-level functions.
    * `Note` Destructors, swap functions, move operations, and default constructors should never throw. See also [C.44](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rc-default00).
    * `Enforcement`
        * Flag functions that are not `noexcept`, yet cannot throw.
        * Flag throwing `swap`, `move`, destructors, and default constructors.
* [现代C++编程实践(八)—关于noexcept修饰符和noexcept操作符](https://mp.weixin.qq.com/s/mAh7amGmNTbKqgW2GYEIog)
    * noexcept修饰符和noexcept操作符可以说是两个概念，C++标准委员会给noexcept的这两种用法的定义如下：
        * noexcept修饰符：指定函数是否抛出异常。
        * noexcept操作符：运算符进行编译时检查，最终返回一个布尔值，根据布尔值决定是否抛出异常。
    * 1 noexcept修饰符
        * 在C++11中，使用noexcept关键字抛出异常后，编译器会默认调用std::terminate()函数终止程序执行，相对throw抛出异常而言，确实会提升一些效率，毕竟减少了异常处理机器产生的一些开销。也正是因为这一特性，noexcept可以有效的避免函数在抛出异常过程中产生的堆栈展开，也可以有效的组织异常的传播与扩散。
    * 1.1 noexcept避免异常的扩散
        * 使用noexcept遇到异常会终止程序的继续执行阻止异常的扩散。
    * 2 noexcept操作符
        * noexcept操作符通常被用在模板中，可以根据noexcept表达式值的不同判断是否抛出异常。
        * noexcept关键字允许编译器直接调用std::terminate终止程序的执行，从某种程度来说是保证了程序的执行安全，当然也会引入问题。比如说，暴力终止程序执行的方法会导致析构函数不能执行，无法保证资源的释放等问题。但是在一定的业务场景中终止程序执行确实是一个有效且果断的异常处理办法。毕竟已经错误的程序继续之后后产生的后果也是无法预估的。
    * 3 总结
        * 程序异常检测、异常恢复或者说中断程序运行在实际工作中都会遇到。且不同的场景使用的方式也不一样，在众多的分布式系统中，程序异常后使用程序中断然后重新拉起的操作很多，这也是最暴力和有效的手段。当然在一些交易性的业务中，出现异常大可以使用异常恢复的方式进行处理，没有必要中断程序执行和重启。

## [C++ Standard Library](https://en.cppreference.com/w/cpp/standard_library)

* [C++ Standard Library](https://www.tutorialspoint.com/cplusplus/cpp_standard_library.htm)
* [什么是 C 和 C++ 标准库？](https://mp.weixin.qq.com/s/wErRQ3AzgJ9lzQKsNG9SzA)
  * https://www.oschina.net/translate/c-c-standard-library
  * C 和 C++ 是如何制订的
  * C 标准库
  * C++ 标准库
  * 实现 C/C++ 标准库
  * GNU/Linux 版实现
  * Mac 和 iOS 版实现
  * Windows 版实现
  * Android 版实现
  * 我能使用不同版本的实现代码来替代默认实现吗？
  * 如果我们脱离了标准库怎么办？

## [Utility library](https://en.cppreference.com/w/cpp/utility)

* C++ includes a variety of utility libraries that provide functionality ranging from bit-counting to partial function application. These libraries can be broadly divided into two groups:
	* language support libraries, and
	* general-purpose libraries.

## [Language support library](https://en.cppreference.com/w/cpp/utility#Language_support)

### [Type support (basic types, RTTI, type traits)](https://en.cppreference.com/w/cpp/types)

#### Additional basic types and macros

* Defined in header \<cstddef>

##### [std::size_t](https://en.cppreference.com/w/cpp/types/size_t)

* unsigned integer type returned by the [sizeof](https://en.cppreference.com/w/cpp/language/sizeof) operator (typedef)
* `std::size_t` is the `unsigned integer` type of the result of the sizeof operator as well as the `sizeof...` operator and the `alignof` operator.
* The bit width of std::size_t is not less than 16.
* Notes
    * std::size_t can store the maximum size of a theoretically possible object of any type (including array). A type whose size cannot be represented by std::size_t is ill-formed. On many platforms (an exception is systems with segmented addressing) std::size_t can safely store the value of any non-member pointer, in which case it is synonymous with std::uintptr_t.
    * std::size_t is commonly used for array indexing and loop counting. Programs that use other types, such as unsigned int, for array indexing may fail on, e.g. 64-bit systems when the index exceeds UINT_MAX or if it relies on 32-bit modular arithmetic.
    * When indexing C++ `containers`, such as std::string, std::vector, etc, the appropriate type is `the member typedef size_type provided by such containers`. It is usually defined as a synonym for std::size_t.
    * The integer literal suffix for std::size_t is any combination of z or Z with u or U (i.e. zu, zU, Zu, ZU, uz, uZ, Uz, or UZ). (since C++23)
* Example
```c++
#include <cstddef>
#include <iostream>
#include <array>
 
int main()
{
    std::array<std::size_t, 10> a;
 
    // Example with C++23 size_t literal
    for (auto i = 0uz; i != a.size(); ++i)
        std::cout << (a[i] = i) << ' ';
    std::cout << '\n';
 
    // Example of decrementing loop
    for (std::size_t i = a.size(); i--;)
        std::cout << a[i] << ' ';
 
    // Note the naive decrementing loop:
    //  for (std::size_t i = a.size() - 1; i >= 0; --i) ...
    // is an infinite loop, because unsigned numbers are always non-negative
}
/*
0 1 2 3 4 5 6 7 8 9 
9 8 7 6 5 4 3 2 1 0
*/
```

#### [Fixed width integer types](https://en.cppreference.com/w/cpp/types/integer)

* Types
* Defined in header \<cstdint>
* [g77-mingw32/include/stdint.h](https://www.rpi.edu/dept/cis/software/g77-mingw32/include/stdint.h)

|uint8_t/uint16_t/uint32_t/uint64_t(optional) | unsigned integer type with width of exactly 8, 16, 32 and 64 bits respectively (provided if and only if the implementation directly supports the type) (typedef) |
| - | - |

#### [Numeric limits](https://en.cppreference.com/w/cpp/types/numeric_limits)

* Defined in header \<limits>
* provides an interface to query properties of all fundamental numeric types. (class template)
* The numeric_limits class template provides a standardized way to query various properties of arithmetic types (e.g. the largest possible value for type int is std::numeric_limits\<int>::max()).
```c++
#include <limits>
#include <iostream>
 
int main() 
{
    std::cout
        << "type\t│ lowest()\t│ min()\t\t│ max()\n"
        << "bool\t│ "
        << std::numeric_limits<bool>::lowest() << "\t\t│ "
        << std::numeric_limits<bool>::min() << "\t\t│ "
        << std::numeric_limits<bool>::max() << '\n'
        << "uchar\t│ "
        << +std::numeric_limits<unsigned char>::lowest() << "\t\t│ "
        << +std::numeric_limits<unsigned char>::min() << "\t\t│ "
        << +std::numeric_limits<unsigned char>::max() << '\n'
        << "int\t│ "
        << std::numeric_limits<int>::lowest() << "\t│ "
        << std::numeric_limits<int>::min() << "\t│ "
        << std::numeric_limits<int>::max() << '\n'
        << "float\t│ "
        << std::numeric_limits<float>::lowest() << "\t│ "
        << std::numeric_limits<float>::min() << "\t│ "
        << std::numeric_limits<float>::max() << '\n'
        << "double\t│ "
        << std::numeric_limits<double>::lowest() << "\t│ "
        << std::numeric_limits<double>::min() << "\t│ "
        << std::numeric_limits<double>::max() << '\n';
}
/*
type	│ lowest()	│ min()		│ max()
bool	│ 0		│ 0		│ 1
uchar	│ 0		│ 0		│ 255
int	│ -2147483648	│ -2147483648	│ 2147483647
float	│ -3.40282e+38	│ 1.17549e-38	│ 3.40282e+38
double	│ -1.79769e+308	│ 2.22507e-308	│ 1.79769e+308
*/
```
* [std::numeric_limits\<T>::min - cppreference.com](https://en.cppreference.com/w/cpp/types/numeric_limits/min)
	* Returns the minimum finite value representable by the numeric type T.
	* For floating-point types with denormalization, min returns the minimum positive normalized value. Note that this behavior may be unexpected, especially when compared to the behavior of min for integral types. To find the value that has no values less than it, use numeric_limits::lowest.
	* min is only meaningful for bounded types and for unbounded unsigned types, that is, types that represent an infinite set of negative values have no meaningful minimum.
* [std::numeric_limits\<T>::max - cppreference.com](https://en.cppreference.com/w/cpp/types/numeric_limits/max)
	* Returns the maximum finite value representable by the numeric type T. Meaningful for all bounded types.
* [std::numeric_limits\<T>::epsilon - cppreference.com](https://en.cppreference.com/w/cpp/types/numeric_limits/epsilon)
	* returns the difference between 1.0 and the next representable value of the given floating-point type (public static member function)
	* Returns the machine epsilon, that is, the difference between 1.0 and the next value representable by the floating-point type T. It is only meaningful if std::numeric_limits\<T>::is_integer == false.
```c++
#include <cmath>
#include <limits>
#include <iomanip>
#include <iostream>
#include <type_traits>

template<class T>
typename std::enable_if<!std::numeric_limits<T>::is_integer, bool>::type
    almost_equal(T x, T y)
{
    return std::fabs(x-y) < std::numeric_limits<T>::epsilon();
}
 
int main()
{
    double d1 = 0.2;
    double d2 = 1 / std::sqrt(5) / std::sqrt(5);
    std::cout << std::fixed << std::setprecision(20) 
        << "d1=" << d1 << "\nd2=" << d2 << '\n';
 
    if(d1 == d2)
        std::cout << "d1 == d2\n";
    else
        std::cout << "d1 != d2\n";
 
    if(almost_equal(d1, d2))
        std::cout << "d1 almost equals d2\n";
    else
        std::cout << "d1 does not almost equal d2\n";
}
/*
d1=0.20000000000000001110
d2=0.19999999999999998335
d1 != d2
d1 almost equals d2
*/
```
* [std::numeric_limits\<T>::infinity - cppreference.com](https://en.cppreference.com/w/cpp/types/numeric_limits/infinity)
	* Returns the special value "positive infinity", as represented by the floating-point type T. Only meaningful if std::numeric_limits\<T>::has_infinity == true. In IEEE 754, the most common binary representation of floating-point numbers, the positive infinity is the value with all bits of the exponent set and all bits of the fraction cleared.

#### [C numeric limits interface](https://en.cppreference.com/w/cpp/types/climits)

* INT_MAX        = 2147483647
* LONG_MAX       = 9223372036854775807
* UINT_MAX       = 4294967295
* ULONG_MAX      = 18446744073709551615
* DBL_MAX          = 1.79769e+308

### [Program support utilities](https://en.cppreference.com/w/cpp/utility/program)

#### Program termination

* The following functions manage program termination and resource cleanup.
* Defined in header \<cstdlib>
* [std::abort - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/abort)
	* Causes abnormal program termination unless SIGABRT is being caught by a signal handler passed to std::signal and the handler does not return.
	* Note: it will cause Application Error in Windows Logs under Event Viewer
* [std::exit - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/exit)
	* Causes normal program termination to occur.
	* Several cleanup steps are performed
	* [Exit codes in C/C++ with Examples - GeeksforGeeks](https://www.geeksforgeeks.org/exit-codes-in-c-c-with-examples/)
		* The purpose of the exit() function is to terminate the execution of a program. The “return 0”(or EXIT_SUCCESS) implies that the code has executed successfully without any error. Exit codes other than “0”(or EXIT_FAILURE) indicate the presence of an error in the code. Among all the exit codes, the codes 1, 2, 126 – 165 and 255 have special meanings and hence these should be avoided for user-defined exit codes.
```c++
#include <iostream>
#include <cstdlib>
 
struct Static
{
    ~Static() 
    {
        std::cout << "Static destructor\n";
    }
};
 
struct Local
{
    ~Local() 
    {
        std::cout << "Local destructor\n";
    }
};
 
Static static_variable; // destructor of this object *will* be called
 
void atexit_handler()
{
    std::cout << "atexit handler\n";
}
 
int main()
{
    Local local_variable; // destructor of this object will *not* be called
    const int result = std::atexit(atexit_handler); // handler will be called
 
    if (result != 0)
    {
        std::cerr << "atexit registration failed\n";
        return EXIT_FAILURE;
    }
 
    std::cout << "test\n";
    std::exit(EXIT_FAILURE);
 
    std::cout << "this line will *not* be executed\n";
}
/*
test
atexit handler
Static destructor
*/
```
* [std::atexit - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/atexit)
	* registers a function to be called on std::exit() invocation (function)
	* Registers the function pointed to by func to be called on normal program termination (via std::exit() or returning from the main function)
	* The functions will be called during the destruction of the static objects, in reverse order: if A was registered before B, then the call to B is made before the call to A. Same applies to the ordering between static object constructors and the calls to atexit: see std::exit (until C++11)
	* The functions may be called concurrently with the destruction of the objects with static storage duration and with each other, maintaining the guarantee that if registration of A was sequenced-before the registration of B, then the call to B is sequenced-before the call to A, same applies to the sequencing between static object constructors and calls to atexit: see std::exit (since C++11)
	* The same function may be registered more than once.
	* If a function exits via an exception, std::terminate is called.
	* atexit is thread-safe: calling the function from several threads does not induce a data race.
	* The implementation is guaranteed to support the registration of at least 32 functions. The exact limit is implementation-defined.
```c++
#include <iostream>
#include <cstdlib>
 
void atexit_handler_1() 
{
    std::cout << "at exit #1\n";
}
 
void atexit_handler_2() 
{
    std::cout << "at exit #2\n";
}
 
int main() 
{
    const int result_1 = std::atexit(atexit_handler_1);
    const int result_2 = std::atexit(atexit_handler_2);
 
    if ((result_1 != 0) || (result_2 != 0)) {
        std::cerr << "Registration failed\n";
        return EXIT_FAILURE;
    }
 
    std::cout << "returning from main\n";
    return EXIT_SUCCESS;
}
/*
returning from main
at exit #2
at exit #1
*/
```
* [EXIT_SUCCESS, EXIT_FAILURE - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/EXIT_status)
	* The EXIT_SUCCESS and EXIT_FAILURE macros expand into integral expressions that can be used as arguments to the std::exit function (and, therefore, as the values to return from the main function), and indicate program execution status.
* [Different Ways To Terminate C++ Program - GeeksforGeeks](https://www.geeksforgeeks.org/different-ways-to-terminate-cpp-program/)
	* The following different methods will be discussed here to terminate a C++ program:
		* abort() function
		* terminate() function
		* exit() function

#### Communicating with the environment

* Defined in header \<cstdlib>
* [std::system - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/system)
	* Calls the host environment's command processor (e.g. /bin/sh, cmd.exe, command.com) with the parameter command. Returns an implementation-defined value (usually the value that the invoked program returns).
	* If command is a null pointer, checks if the host environment has a command processor and returns a nonzero value if and only if the command processor exists.
```c++
#include <cstdlib>
#include <fstream>
#include <iostream>
 
int main()
{
    std::system("ls -l >test.txt"); // execute the UNIX command "ls -l >test.txt"
    std::cout << std::ifstream("test.txt").rdbuf();
}
```
* [std::getenv - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/getenv)
	* access to the list of environment variables (function)
	* Defined in header \<cstdlib>
	* `char* getenv( const char* env_var );`
	* Searches the environment list provided by the host environment (the OS), for a string that matches the C string pointed to by env_var and returns a pointer to the C string that is associated with the matched environment list member.
	* This function is thread-safe (calling it from multiple threads does not introduce a data race) as long as no other function modifies the host environment. In particular, the POSIX functions [setenv()](http://pubs.opengroup.org/onlinepubs/9699919799/functions/setenv.html), [unsetenv()](http://pubs.opengroup.org/onlinepubs/9699919799/functions/unsetenv.html), and [putenv()](http://pubs.opengroup.org/onlinepubs/9699919799/functions/putenv.html) would introduce a data race if called without synchronization. (since C++11)
	* Modifying the string returned by getenv invokes undefined behavior.
```c++
#include <iostream>
#include <cstdlib>
 
int main()
{
    if(const char* env_p = std::getenv("PATH"))
        std::cout << "Your PATH is: " << env_p << '\n';
}
/*
Your PATH is: /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games
*/
```
* [command line - How to use setenv() to export a variable in c++? - Stack Overflow](https://stackoverflow.com/questions/17929414/how-to-use-setenv-to-export-a-variable-in-c)
	* `setenv("ROS_HOSTNAME","xxx",1); // does overwrite`
	* `setenv("ROS_HOSTNAME","xxx",0); // does not overwrite`

#### Signals

* Several functions and macro constants for signal management are provided.
* Defined in header \<csignal>
* [std::signal - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/signal)
	* sets a signal handler for particular signal (function)
	* Sets the handler for signal sig. The signal handler can be set so that default handling will occur, signal is ignored, or a user-defined function is called.
	* When signal handler is set to a function and a signal occurs, it is implementation defined whether std::signal(sig, SIG_DFL) will be executed immediately before the start of signal handler. Also, the implementation can prevent some implementation-defined set of signals from occurring while the signal handler runs.
	* For some of the signals, the implementation may call std::signal(sig, SIG_IGN) at the startup of the program. For the rest, the implementation must call std::signal(sig, SIG_DFL).
	* (Note: POSIX introduced sigaction to standardize these implementation-defined behaviors)
```c++
#include <csignal>
#include <iostream>
 
namespace
{
  volatile std::sig_atomic_t gSignalStatus;
}
 
void signal_handler(int signal)
{
  gSignalStatus = signal;
}
 
int main()
{
  // Install a signal handler
  std::signal(SIGINT, signal_handler);
 
  std::cout << "SignalValue: " << gSignalStatus << '\n';
  std::cout << "Sending signal: " << SIGINT << '\n';
  std::raise(SIGINT);
  std::cout << "SignalValue: " << gSignalStatus << '\n';
}
/*
SignalValue: 0
Sending signal: 2
SignalValue: 2
*/
```
* [std::raise - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/raise)
	* runs the signal handler for particular signal (function)
	* Sends signal sig to the program. The signal handler (specified using the std::signal() function) is invoked.
	* If the user-defined signal handling strategy is not set using std::signal() yet, it is implementation-defined whether the signal will be ignored or default handler will be invoked.
```c++
#include <csignal>
#include <iostream>
 
void signal_handler(int signal)
{
    std::cout << "Received signal " << signal << '\n';
}
 
int main()
{
    // Install a signal handler
    std::signal(SIGTERM, signal_handler);
 
    std::cout << "Sending signal " << SIGTERM << '\n';
    std::raise(SIGTERM);
}
/*
Sending signal 15
Received signal 15
*/
```
* [SIGTERM, SIGSEGV, SIGINT, SIGILL, SIGABRT, SIGFPE - cppreference.com](https://en.cppreference.com/w/cpp/utility/program/SIG_types)
	* Each of the above macro constants expands to an integer constant expression with distinct values, which represent different signals sent to the program.

Constant|Explanation
-|-
SIGTERM|termination request, sent to the program
SIGSEGV|invalid memory access (segmentation fault)
SIGINT|external interrupt, usually initiated by the user
SIGILL|invalid program image, such as invalid instruction
SIGABRT|abnormal termination condition, as is e.g. initiated by std::abort()
SIGFPE|erroneous arithmetic operation such as divide by zero

* [C++ Signal Handling](https://www.tutorialspoint.com/cplusplus/cpp_signal_handling.htm)
	* Signals are the interrupts delivered to a process by the operating system which can terminate a program prematurely. You can generate interrupts by pressing Ctrl+C on a UNIX, LINUX, Mac OS X or Windows system.
	* There are signals which can not be caught by the program but there is a following list of signals which you can catch in your program and can take appropriate actions based on the signal. These signals are defined in C++ header file \<csignal>.
* [Signal Handling in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/signal-handling-in-cpp/)
* [Shell Scripting - How to send Signal to a Processes - GeeksforGeeks](https://www.geeksforgeeks.org/shell-scripting-how-to-send-signal-to-a-processes/)
* [UNIX / Linux: 3 Ways to Send Signal to Processes](https://www.thegeekstuff.com/2011/02/send-signal-to-process/)

### [Initializer lists](https://en.cppreference.com/w/cpp/utility/initializer_list)

* Defined in header \<initializer_list>
* [std::initializer_list - cppreference.com](https://en.cppreference.com/w/cpp/utility/initializer_list)(C++11)
	* creates a temporary array in [list-initialization](https://en.cppreference.com/w/cpp/language/list_initialization) and then references it (class template)
	* An object of type std::initializer_list\<T> is a lightweight proxy object that provides access to an array of objects of type const T.
	* A std::initializer_list object is automatically constructed when:
		* a braced-init-list is used to list-initialize an object, where the corresponding constructor accepts an std::initializer_list parameter
		* a braced-init-list is used as the right operand of assignment or as a function call argument, and the corresponding assignment operator/function accepts an std::initializer_list parameter
		* a braced-init-list is bound to auto, including in a ranged for loop
	* Initializer lists may be implemented as a pair of pointers or pointer and length. Copying a std::initializer_list does not copy the underlying objects.
	* The underlying array is a temporary array of type const T[N], in which each element is copy-initialized (except that narrowing conversions are invalid) from the corresponding element of the original initializer list. The lifetime of the underlying array is the same as any other temporary object, except that initializing an initializer_list object from the array extends the lifetime of the array exactly like binding a reference to a temporary (with the same exceptions, such as for initializing a non-static class member). The underlying array may be allocated in read-only memory.
	* The program is ill-formed if an explicit or partial specialization of std::initializer_list is declared.
* [List-initialization (since C++11) - cppreference.com](https://en.cppreference.com/w/cpp/language/list_initialization)
	* Initializes an object from braced-init-list.
	* Syntax
		* Direct-list-initialization
			* T object { arg1, arg2, ... };	(1)	
			* T { arg1, arg2, ... }	(2)	
			* new T { arg1, arg2, ... }	(3)	
			* Class { T member { arg1, arg2, ... }; };	(4)	
			* Class::Class() : member { arg1, arg2, ... } {...	(5)	
		* Copy-list-initialization
			* T object = { arg1, arg2, ... };	(6)	
			* function ({ arg1, arg2, ... })	(7)	
			* return { arg1, arg2, ... };	(8)	
			* object [{ arg1, arg2, ... }]	(9)	
			* object = { arg1, arg2, ... }	(10)	
			* U ({ arg1, arg2, ... })	(11)	
			* Class { T member = { arg1, arg2, ... }; };	(12)	
	* Narrowing conversions
		* List-initialization limits the allowed implicit conversions by prohibiting the following:
			* conversion from a floating-point type to an integer type
			* conversion from a long double to double or to float and conversion from double to float, except where the source is a constant expression and overflow does not occur
			* conversion from an integer type to a floating-point type, except where the source is a constant expression whose value can be stored exactly in the target type
			* conversion from integer or unscoped enumeration type to integer type that cannot represent all values of the original, except where source is a constant expression whose value can be stored exactly in the target type
			* conversion from a pointer type or pointer-to-member type to bool
	* Notes
		* Every initializer clause is sequenced before any initializer clause that follows it in the braced-init-list. This is in contrast with the arguments of a function call expression, which are unsequenced (until C++17)indeterminately sequenced (since C++17).
		* A braced-init-list is not an expression and therefore has no type, e.g. decltype({1,2}) is ill-formed. Having no type implies that template type deduction cannot deduce a type that matches a braced-init-list, so given the declaration template\<class T> void f(T); the expression f({1,2,3}) is ill-formed. However, the template parameter can otherwise be deduced, as is the case for std::vector\<int> v(std::istream_iterator\<int>(std::cin), {}), where the iterator type is deduced by the first argument but also used in the second parameter position. A special exception is made for type deduction using the keyword auto , which deduces any braced-init-list as std::initializer_list in copy-list-initialization.
		* Also because a braced-init-list has no type, special rules for overload resolution apply when it is used as an argument to an overloaded function call.
		* Aggregates copy/move initialize directly from single-element braced-init-list of the same type, but non-aggregates consider initializer_list constructors first
		* Some compilers (e.g., gcc 10) only consider conversion from a pointer or a pointer-to-member to bool narrowing in C++20 mode.
```c++
#include <iostream>
#include <vector>
#include <map>
#include <string>
 
struct Foo
{
    std::vector<int> mem = {1, 2, 3}; // list-initialization of a non-static member
    std::vector<int> mem2;
 
    Foo() : mem2{-1, -2, -3} {} // list-initialization of a member in constructor
};
 
std::pair<std::string, std::string> f(std::pair<std::string, std::string> p)
{
    return {p.second, p.first}; // list-initialization in return statement
}
 
int main()
{
    int n0{};  // value-initialization (to zero)
    int n1{1}; // direct-list-initialization
 
    std::string s1{'a', 'b', 'c', 'd'}; // initializer-list constructor call
    std::string s2{s1, 2, 2};           // regular constructor call
    std::string s3{0x61, 'a'}; // initializer-list ctor is preferred to (int, char)
 
    int n2 = {1}; // copy-list-initialization
    double d = double{1.2}; // list-initialization of a prvalue, then copy-init
    auto s4 = std::string{"HelloWorld"}; // same as above, no temporary created since C++17
 
    std::map<int, std::string> m = // nested list-initialization
    {
        {1, "a"},
        {2, {'a', 'b', 'c'}},
        {3, s1}
    };
 
    std::cout << f({"hello", "world"}).first // list-initialization in function call
              << '\n';
 
    const int (&ar)[2] = {1, 2}; // binds a lvalue reference to a temporary array
    int&& r1 = {1}; // binds a rvalue reference to a temporary int
//  int& r2 = {2}; // error: cannot bind rvalue to a non-const lvalue ref
 
//  int bad{1.0}; // error: narrowing conversion
    unsigned char uc1{10}; // okay
//  unsigned char uc2{-1}; // error: narrowing conversion
 
    Foo f;
 
    std::cout << n0 << ' ' << n1 << ' ' << n2 << '\n'
              << s1 << ' ' << s2 << ' ' << s3 << '\n';
    for(auto p: m)
        std::cout << p.first << ' ' << p.second << '\n';
    for(auto n: f.mem)
        std::cout << n << ' ';
    for(auto n: f.mem2)
        std::cout << n << ' ';
}
```
* [ES.23: Prefer the {}-initializer syntax - C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#es23-prefer-the--initializer-syntax)
	* Reason Prefer {}. The rules for {} initialization are simpler, more general, less ambiguous, and safer than for other forms of initialization.
Use = only when you are sure that there can be no narrowing conversions. For built-in arithmetic types, use = only with auto.
	* Avoid () initialization, which allows parsing ambiguities.
	* Exception For containers, there is a tradition for using {...} for a list of elements and (...) for sizes
	* Note {}-initializers do not allow narrowing conversions (and that is usually a good thing) and allow explicit constructors (which is fine, we’re intentionally initializing a new variable).
	* Note {} initialization can be used for nearly all initialization; other forms of initialization can’t
	* Note Initialization of a variable declared using auto with a single value, e.g., {v}, had surprising results until C++17. The C++17 rules are somewhat less surprising
	* Use ={...} if you really want an initializer_list\<T>
	* Note ={} gives copy initialization whereas {} gives direct initialization. Like the distinction between copy-initialization and direct-initialization itself, this can lead to surprises. {} accepts explicit constructors; ={} does not.
	* Use plain {}-initialization unless you specifically want to disable explicit constructors.	

## [Metaprogramming library](https://en.cppreference.com/w/cpp/meta)

* C++ provides metaprogramming facilities, such as type traits, compile-time rational arithmetic, and compile-time integer sequences.
* [C++ 高阶操作：模板元编程](https://mp.weixin.qq.com/s/Ypit8BrJSvpx6B3Yf5GRuA)
  * 泛型编程大家应该都很熟悉了，主要就是利用模板实现“安全的宏”，而模板元编程区别于我们所知道的泛型编程，它是一种较为复杂的模板，属于C++的高阶操作了，它最主要的优点就在于把计算过程提前到编译期，能带来可观的性能提升。
  * 1.概述
    * 模板元编程（Template Meta programming，TMP）是编写生成或操纵程序的程序，也是一种复杂且功能强大的编程范式（Programming Paradigm）。
  * 6.小结
    * C++模板元编程是图灵完备的且是函数式编程，主要特点是代码在编译期执行，可用于编译期数值计算，能够获得更有效率的运行码。模板的使用，也提高了代码泛化。与此同时，模板元编程也存一定缺点，主要有
    * （1）模板元编程产生的代码较为复杂，难易阅读，可读性较差；
    * （2）大量模板的使用，编译时容易导致代码膨胀，提高了编译时间；
    * （3）对于C++来说，由于各编译器的差异，大量依赖模板元编程（特别是最新形式的）的代码可能会有移植性的问题。
    * 所以，对于模板元编程，我们需要扬其长避其短，合理使用模板元编程。

### Type property

* These type traits define compile-time template-based interfaces to query the properties of types.
* Attempting to specialize a template defined in the `<type_traits>` header and described in this section results in undefined behavior.
* A template defined in the `<type_traits>` header may be instantiated with an incomplete type unless otherwise specified, notwithstanding the general prohibition against instantiating standard library templates with incomplete types.
* Defined in header `<type_traits>`

#### Composite type categories

##### [std::is_arithmetic](https://en.cppreference.com/w/cpp/types/is_arithmetic)

* checks if a type is an arithmetic type (class template)
* Defined in header `<type_traits>`
```c++
template< class T >
struct is_arithmetic;   (since C++11)
```
* If T is an arithmetic type (that is, an integral type or a floating-point type) or a cv-qualified version thereof, provides the member constant value equal to `true`. For any other type, value is `false`.
* The behavior of a program that adds specializations for is_arithmetic `or is_arithmetic_v (since C++17)` is undefined.
* Template parameters
    * `T`	-	a type to check
* Helper variable template
```c++
template< class T >
inline constexpr bool is_arithmetic_v = is_arithmetic<T>::value;    (since C++17)
```

#### Type properties

##### [std::is_empty](https://en.cppreference.com/w/cpp/types/is_empty)

* checks if a type is a class (but not union) type and has no non-static data members (class template)
* `template< class T > struct is_empty;` (since C++11)
* If T is an empty type (that is, a non-union class type with no non-static data members other than bit-fields of size 0, no virtual functions, no virtual base classes, and no non-empty base classes), provides the member constant value equal to true. For any other type, value is false.
* If T is a non-union class type, T shall be a complete type; otherwise, the behavior is undefined.
* The behavior of a program that adds specializations for is_empty or is_empty_v (since C++17) is undefined.
* Template parameters
    * `T`	-	a type to check
* Helper variable template
    * `template< class T > inline constexpr bool is_empty_v = is_empty<T>::value;` (since C++17)
* Notes
    * Inheriting from empty base classes usually does not increase the size of a class due to [empty base optimization](https://en.cppreference.com/w/cpp/language/ebo).
    * `std::is_empty<T>` and all other type traits are empty classes.
* Example
```c++
#include <iostream>
#include <type_traits>
 
struct A {};
 
struct B {
    int m;
};
 
struct C {
    static int m;
};
 
struct D {
    virtual ~D();
};
 
union E {};
 
struct F {
    [[no_unique_address]] E e;
};
 
struct G {
    int:0;  
    // C++ standard allow "as a special case, an unnamed bit-field with a width of zero 
    // specifies alignment of the next bit-field at an allocation unit boundary.
    // Only when declaring an unnamed bit-field may the width be zero."
};
 
int main()
{
    std::cout << std::boolalpha;
    std::cout << "A " << std::is_empty<A>::value << '\n';
    std::cout << "B " << std::is_empty<B>::value << '\n';
    std::cout << "C " << std::is_empty<C>::value << '\n';
    std::cout << "D " << std::is_empty<D>::value << '\n';
    std::cout << "E " << std::is_empty<E>::value << '\n';
    std::cout << "F " << std::is_empty<F>::value << '\n'; // the result is ABI-dependent
    std::cout << "G " << std::is_empty<G>::value << '\n'; // unnamed bit-fields of width of 0
}
/*
A true
B false
C true
D false
E false
F true
G true
*/
```

#### Type relationships

##### [std::is_same](https://en.cppreference.com/w/cpp/types/is_same)

* checks if two types are the same (class template)
* If T and U name the same type (taking into account const/volatile qualifications), provides the member constant value equal to true. Otherwise value is false.
* Commutativity is satisfied, i.e. for any two types T and U, `is_same<T, U>::value == true` if and only if `is_same<U, T>::value == true`.
* The behavior of a program that adds specializations for is_same or is_same_v (since C++17) is undefined.
* Helper variable template
    * `template< class T, class U > inline constexpr bool is_same_v = is_same<T, U>::value;`
```c++
#include <iostream>
#include <type_traits>
#include <cstdint>
 
void print_separator()
{
    std::cout << "-----\n";
}
 
int main()
{
    std::cout << std::boolalpha;
 
    // some implementation-defined facts
 
    // usually true if 'int' is 32 bit
    std::cout << std::is_same<int, std::int32_t>::value << ' '; // ~ true
    // possibly true if ILP64 data model is used
    std::cout << std::is_same<int, std::int64_t>::value << ' '; // ~ false
 
    // same tests as above, except using C++17's `std::is_same_v<T, U>` format
    std::cout << std::is_same_v<int, std::int32_t> << ' ';  // ~ true
    std::cout << std::is_same_v<int, std::int64_t> << '\n'; // ~ false
 
    print_separator();
 
    // compare the types of a couple variables
    long double num1 = 1.0;
    long double num2 = 2.0;
    std::cout << std::is_same_v<decltype(num1), decltype(num2)> << '\n'; // true
 
    print_separator();
 
    // 'float' is never an integral type
    std::cout << std::is_same<float, std::int32_t>::value << '\n'; // false
 
    print_separator();
 
    // 'int' is implicitly 'signed'
    std::cout << std::is_same<int, int>::value << ' ';          // true
    std::cout << std::is_same<int, unsigned int>::value << ' '; // false
    std::cout << std::is_same<int, signed int>::value << '\n';  // true
 
    print_separator();
 
    // unlike other types, 'char' is neither 'unsigned' nor 'signed'
    std::cout << std::is_same<char, char>::value << ' ';          // true
    std::cout << std::is_same<char, unsigned char>::value << ' '; // false
    std::cout << std::is_same<char, signed char>::value << '\n';  // false
 
    // const-qualified type T is not same as non-const T
    static_assert( not std::is_same<const int, int>() );
}
/*
true false true false
-----
true
-----
false
-----
true false true
-----
true false false
*/
```
* [is_same - C++ Reference](https://www.cplusplus.com/reference/type_traits/is_same/)
	* `template <class T, class U> struct is_same;`
	* Trait class that identifies whether T is the same type as U, including having the same const and/or volatile qualification, if any.
	* Two different type names are considered to represent the same type if -and only if- one is a typedef of the other: Two names representing types with the exact same characteristics but which none is a typedef of the other are not considered the same type.
	* is_same inherits from integral_constant as being either true_type or false_type, depending on whether T and U are the same type.

##### [std::is_base_of](https://en.cppreference.com/w/cpp/types/is_base_of)

* If Derived is derived from Base or if both are the same non-union class (in both cases ignoring cv-qualification), provides the member constant value equal to true. Otherwise value is false.
* If both Base and Derived are non-union class types, and they are not the same type (ignoring cv-qualification), Derived shall be a complete type; otherwise the behavior is undefined.
* The behavior of a program that adds specializations for is_base_of or is_base_of_v (since C++17) is undefined.
```c++
#include <iostream>
#include <type_traits>
#define SHOW(...) \
    std::cout << #__VA_ARGS__ << " : " \
              << std:: __VA_ARGS__ << '\n'
int main()
{
    class A {};
    class B : A {};
    class C : B {};
    class D {};
 
    std::cout << std::boolalpha;
    SHOW( is_base_of_v<A, A> );
    SHOW( is_base_of_v<A, B> );
    SHOW( is_base_of_v<A, C> );
    SHOW( is_base_of_v<A, D> );
    SHOW( is_base_of_v<B, A> );
    SHOW( is_base_of_v<int, int> );
}
/*
is_base_of_v<A, A> : true
is_base_of_v<A, B> : true
is_base_of_v<A, C> : true
is_base_of_v<A, D> : false
is_base_of_v<B, A> : false
is_base_of_v<int, int> : false
*/
```

### Type modifications

* These type traits apply modifications on a template parameter, and declare (sometimes conditionally) the type member typedef as the resulting type.
* Attempting to specialize a template defined in the \<type_traits> header and described in this section results in undefined behavior, except that std::common_type and std::basic_common_reference (since C++20) may be specialized as required in description.
* A template defined in the \<type_traits> header may be instantiated with an incomplete type unless otherwise specified, notwithstanding the general prohibition against instantiating standard library templates with incomplete types.
* Defined in header \<type_traits>

### Miscellaneous transformations

* Defined in header \<type_traits>

#### [std::enable_if](https://en.cppreference.com/w/cpp/types/enable_if)

* conditionally [removes](https://en.cppreference.com/w/cpp/language/sfinae) a function overload or template specialization from overload resolution (class template)
* `template< bool B, class T = void > struct enable_if;` (since C++11)
* If B is `true`, std::enable_if has a public member typedef `type`, equal to T; otherwise, there is `no` member typedef.
* This metafunction is a convenient way to leverage SFINAE prior to C++20's concepts, in particular for conditionally removing functions from the candidate set based on type traits, allowing separate function overloads or specializations based on those different type traits.
* std::enable_if can be used in many forms, including:
    * as an additional function argument (not applicable to operator overloads)
    * as a return type (not applicable to constructors and destructors)
    * as a class template or function template parameter
* The behavior of a program that adds specializations for enable_if is undefined.
* Notes
    * A common mistake is to declare two function templates that differ only in their default template arguments. This does not work because the declarations are treated as redeclarations of the same function template (default template arguments are not accounted for in [function template equivalence](https://en.cppreference.com/w/cpp/language/function_template#Function_template_overloading)).
```c++
/* WRONG */
 
struct T {
    enum { int_t, float_t } type;
    template <typename Integer,
              typename = std::enable_if_t<std::is_integral<Integer>::value>
    >
    T(Integer) : type(int_t) {}
 
    template <typename Floating,
              typename = std::enable_if_t<std::is_floating_point<Floating>::value>
    >
    T(Floating) : type(float_t) {} // error: treated as redefinition
};
 
/* RIGHT */
 
struct T {
    enum { int_t, float_t } type;
    template <typename Integer,
              std::enable_if_t<std::is_integral<Integer>::value, bool> = true
    >
    T(Integer) : type(int_t) {}
 
    template <typename Floating,
              std::enable_if_t<std::is_floating_point<Floating>::value, bool> = true
    >
    T(Floating) : type(float_t) {} // OK
};
```

## [Diagnostics library / Error handling](https://en.cppreference.com/w/cpp/error)

### Exception handling

* The header \<exception> provides several classes and functions related to exception handling in C++ programs.
* Defined in header \<exception>
* [Exception Handling](https://www.tutorialspoint.com/cplusplus/cpp_exceptions_handling.htm)
* [std::exception - cppreference.com](https://en.cppreference.com/w/cpp/error/exception)
    * base class for exceptions thrown by the standard library components (class)
	* Provides consistent interface to handle errors through the throw expression.
	* All exceptions generated by the standard library inherit from std::exception
* [exception - C++ Reference](http://www.cplusplus.com/reference/exception/exception/)
    * [Inherited Code | HackerRank](https://www.hackerrank.com/challenges/inherited-code/problem)
    * [Exceptional Server | HackerRank](https://www.hackerrank.com/challenges/exceptional-server/problem)
    ```c++
    class BadLengthException : public exception
    {
      public:
          BadLengthException(int n) : m_n(to_string(n)) {}

          const char* what() const noexcept
          {
              return m_n.c_str();
          }

      private:
          string m_n;

    };
    ```
    ```c++
    try {
      cout << Server::compute(A, B) << endl;        
    } catch (bad_alloc& ex) {
      cout << "Not enough memory" << endl;
    } catch (exception& ex) {
      cout << "Exception: " << ex.what() << endl;
    } catch (...) {
      cout << "Other Exception" << endl;
    }
    ```
* [std::terminate - cppreference.com](https://en.cppreference.com/w/cpp/error/terminate)
	* function called when exception handling fails (function)
	* std::terminate() is called by the C++ runtime when the program cannot continue for any of the following reasons
	* std::terminate() may also be called directly from the program.
	* In any case, std::terminate calls the currently installed std::terminate_handler. The default std::terminate_handler calls std::abort.

### Exception categories

* [std::runtime_error - cppreference.com](https://en.cppreference.com/w/cpp/error/runtime_error)
  * Defines a type of object to be thrown as exception. It reports errors that are due to events beyond the scope of the program and can not be easily predicted.
  * [exception - c++: Catch runtime_error - Stack Overflow](https://stackoverflow.com/questions/7491877/c-catch-runtime-error)

### Assertions

* [assert - cppreference.com](https://en.cppreference.com/w/cpp/error/assert)
	* The definition of the macro assert depends on another macro, NDEBUG, which is not defined by the standard library.
	* If NDEBUG is defined as a macro name at the point in the source code where \<cassert> or \<assert.h> is included, then assert does nothing.
	* If NDEBUG is not defined, then assert checks if its argument (which must have scalar type) compares equal to zero. If it does, assert outputs implementation-specific diagnostic information on the standard error output and calls std::abort. The diagnostic information is required to include the text of expression, as well as the values of the predefined variable __func__ and (since C++11) the predefined macros __FILE__ and __LINE__.

### [Stacktrace](https://en.cppreference.com/w/cpp/utility/basic_stacktrace)

## [Dynamic memory management](https://en.cppreference.com/w/cpp/memory)

### Smart pointers

* Smart pointers enable automatic, exception-safe, object lifetime management.
* Defined in header \<memory>
* [智能指针（现代 C++）](https://msdn.microsoft.com/zh-cn/library/hh279674.aspx)
	* In modern C++ programming, the Standard Library includes smart pointers, which are used to help ensure that programs are free of memory and resource leaks and are exception-safe.
	* Smart pointers are defined in the std namespace in the \<memory\> header file. They are crucial to the RAII or Resource Acquisition Is Initialization programming idiom. The main goal of this idiom is to ensure that resource acquisition occurs at the same time that the object is initialized, so that all resources for the object are created and made ready in one line of code. In practical terms, the main principle of RAII is to give ownership of any heap-allocated resource—for example, dynamically-allocated memory or system object handles—to a stack-allocated object whose destructor contains the code to delete or free the resource and also any associated cleanup code.
	* In most cases, when you initialize a raw pointer or resource handle to point to an actual resource, pass the pointer to a smart pointer immediately. In modern C++, raw pointers are only used in small code blocks of limited scope, loops, or helper functions where performance is critical and there is no chance of confusion about ownership.
	* The C++ smart pointer idiom resembles object creation in languages such as C#: you create the object and then let the system take care of deleting it at the correct time. The difference is that no separate garbage collector runs in the background; memory is managed through the standard C++ scoping rules so that the runtime environment is faster and more efficient.
	* Important : Always create smart pointers on a separate line of code, never in a parameter list, so that a subtle resource leak won't occur due to certain parameter list allocation rules.
	* Use these smart pointers as a first choice for encapsulating pointers to plain old C++ objects (POCO).
	* unique_ptr
		* Allows exactly one owner of the underlying pointer. Use as the default choice for POCO unless you know for certain that you require a shared_ptr. Can be moved to a new owner, but not copied or shared. Replaces auto_ptr, which is deprecated. Compare to boost::scoped_ptr. unique_ptr is small and efficient; the size is one pointer and it supports rvalue references for fast insertion and retrieval from C++ Standard Library collections. Header file: \<memory\>. For more information, see [How to: Create and use unique_ptr instances | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/how-to-create-and-use-unique-ptr-instances?view=msvc-160) and [unique_ptr Class](https://docs.microsoft.com/en-us/cpp/standard-library/unique-ptr-class?view=msvc-160).
		* A unique_ptr does not share its pointer. It cannot be copied to another unique_ptr, passed by value to a function, or used in any C++ Standard Library algorithm that requires copies to be made. A unique_ptr can only be moved. This means that the ownership of the memory resource is transferred to another unique_ptr and the original unique_ptr no longer owns it. We recommend that you restrict an object to one owner, because multiple ownership adds complexity to the program logic. Therefore, when you need a smart pointer for a plain C++ object, use unique_ptr, and when you construct a unique_ptr, use the [make_unique](https://docs.microsoft.com/en-us/cpp/standard-library/memory-functions?view=msvc-160#make_unique) helper function.
	* shared_ptr
		* Reference-counted smart pointer. Use when you want to assign one raw pointer to multiple owners, for example, when you return a copy of a pointer from a container but want to keep the original. The raw pointer is not deleted until all shared_ptr owners have gone out of scope or have otherwise given up ownership. The size is two pointers; one for the object and one for the shared control block that contains the reference count. Header file: \<memory\>. For more information, see [How to: Create and use shared_ptr instances | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/how-to-create-and-use-shared-ptr-instances?view=msvc-160) and [shared_ptr Class](https://docs.microsoft.com/en-us/cpp/standard-library/shared-ptr-class?view=msvc-160).
			* Whenever possible, use the [make_shared](https://docs.microsoft.com/en-us/cpp/standard-library/memory-functions?view=msvc-160#make_shared) function to create a shared_ptr when the memory resource is created for the first time.
		* The shared_ptr type is a smart pointer in the C++ standard library that is designed for scenarios in which more than one owner might have to manage the lifetime of the object in memory. After you initialize a shared_ptr you can copy it, pass it by value in function arguments, and assign it to other shared_ptr instances. All the instances point to the same object, and share access to one "control block" that increments and decrements the reference count whenever a new shared_ptr is added, goes out of scope, or is reset. When the reference count reaches zero, the control block deletes the memory resource and itself.
	* weak_ptr
		* Special-case smart pointer for use in conjunction with shared_ptr. A weak_ptr provides access to an object that is owned by one or more shared_ptr instances, but does not participate in reference counting. Use when you want to observe an object, but do not require it to remain alive. Required in some cases to break circular references between shared_ptr instances. Header file: \<memory\>. For more information, see [How to: Create and use weak_ptr instances | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/how-to-create-and-use-weak-ptr-instances?view=msvc-160) and [weak_ptr Class](https://docs.microsoft.com/en-us/cpp/standard-library/weak-ptr-class?view=msvc-160).
		* Sometimes an object must store a way to access the underlying object of a shared_ptr without causing the reference count to be incremented. Typically, this situation occurs when you have cyclic references between shared_ptr instances.
		* The best design is to avoid shared ownership of pointers whenever you can. However, if you must have shared ownership of shared_ptr instances, avoid cyclic references between them. When cyclic references are unavoidable, or even preferable for some reason, use weak_ptr to give one or more of the owners a weak reference to another shared_ptr. By using a weak_ptr, you can create a shared_ptr that joins to an existing set of related instances, but only if the underlying memory resource is still valid. A weak_ptr itself does not participate in the reference counting, and therefore, it cannot prevent the reference count from going to zero. However, you can use a weak_ptr to try to obtain a new copy of the shared_ptr with which it was initialized. If the memory has already been deleted, the weak_ptr's bool operator returns false. If the memory is still valid, the new shared pointer increments the reference count and guarantees that the memory will be valid as long as the shared_ptr variable stays in scope.
* [Smart pointer - Wikipedia, the free encyclopedia](https://en.wikipedia.org/wiki/Smart_pointer)
* [Smart pointer rule summary - C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#Rr-summary-smartptrs)

#### [std::unique_ptr](https://en.cppreference.com/w/cpp/memory/unique_ptr)

* smart pointer with unique object ownership semantics (class template)
* `std::unique_ptr is a smart pointer that owns and manages another object through a pointer and disposes of that object when the unique_ptr goes out of scope`.
* The object is disposed of, using the associated deleter when either of the following happens:
    * the managing unique_ptr object is `destroyed`
    * the managing unique_ptr object is assigned another pointer via `operator=` or `reset()`.
* The object is disposed of, using a potentially user-supplied deleter by calling `get_deleter()(ptr)`. The default deleter uses the `delete` operator, which destroys the object and deallocates the memory.
* A unique_ptr may alternatively own no object, in which case it is called `empty`.
* There are two versions of std::unique_ptr:
    * Manages a single object (e.g. allocated with `new`)
    * Manages a dynamically-allocated array of objects (e.g. allocated with `new[]`)
* The class satisfies the requirements of MoveConstructible and MoveAssignable, but of neither CopyConstructible nor CopyAssignable.
* Type requirements
    * Deleter must be FunctionObject or lvalue reference to a FunctionObject or lvalue reference to function, callable with an argument of type `unique_ptr<T, Deleter>::pointer`
* Notes
    * Only non-const unique_ptr can transfer the ownership of the managed object to another unique_ptr. If an object's lifetime is managed by a `const std::unique_ptr`, it is limited to the scope in which the pointer was created.
    * std::unique_ptr is commonly used to manage the lifetime of objects, including:
        * providing exception safety to classes and functions that handle objects with dynamic lifetime, by guaranteeing deletion on both normal exit and exit through exception
        * passing ownership of uniquely-owned objects with dynamic lifetime into functions
        * acquiring ownership of uniquely-owned objects with dynamic lifetime from functions
        * as the element type in move-aware containers, such as `std::vector`, which hold pointers to dynamically-allocated objects (e.g. if polymorphic behavior is desired)
    * std::unique_ptr may be constructed for an incomplete type T, such as to facilitate the use as a handle in the [pImpl idiom](https://en.cppreference.com/w/cpp/language/pimpl). If the default deleter is used, T must be complete at the point in code where the deleter is invoked, which happens in the destructor, move assignment operator, and reset member function of `std::unique_ptr`. (Conversely, `std::shared_ptr` can't be constructed from a raw pointer to incomplete type, but can be destroyed where T is incomplete). Note that if T is a class template specialization, use of unique_ptr as an operand, e.g. `!p` requires T's parameters to be complete due to [ADL](https://en.cppreference.com/w/cpp/language/adl).
    * If T is a derived class of some base B, then `std::unique_ptr<T>` is `implicitly convertible` to `std::unique_ptr<B>`. The default deleter of the resulting `std::unique_ptr<B>` will use `operator delete` for B, leading to `undefined behavior` unless the destructor of B is virtual. Note that `std::shared_ptr` behaves differently: `std::shared_ptr<B>` will use the `operator delete` for the type T and the owned object will be deleted correctly even if the destructor of B is not virtual.
    * Unlike `std::shared_ptr`, `std::unique_ptr` may manage an object through any custom handle type that satisfies `NullablePointer`. This allows, for example, managing objects located in shared memory, by supplying a `Deleter` that defines typedef `boost::offset_ptr` pointer; or another `fancy pointer`.
* Example
```c++
#include <cassert>
#include <cstdio>
#include <fstream>
#include <iostream>
#include <memory>
#include <stdexcept>
 
// helper class for runtime polymorphism demo below
struct B
{
    virtual ~B() = default;
 
    virtual void bar() { std::cout << "B::bar\n"; }
};
 
struct D : B
{
    D() { std::cout << "D::D\n"; }
    ~D() { std::cout << "D::~D\n"; }
 
    void bar() override { std::cout << "D::bar\n"; }
};
 
// a function consuming a unique_ptr can take it by value or by rvalue reference
std::unique_ptr<D> pass_through(std::unique_ptr<D> p)
{
    p->bar();
    return p;
}
 
// helper function for the custom deleter demo below
void close_file(std::FILE* fp)
{
    std::fclose(fp);
}
 
// unique_ptr-based linked list demo
struct List
{
    struct Node
    {
        int data;
        std::unique_ptr<Node> next;
    };
 
    std::unique_ptr<Node> head;
 
    ~List()
    {
        // destroy list nodes sequentially in a loop, the default destructor
        // would have invoked its `next`'s destructor recursively, which would
        // cause stack overflow for sufficiently large lists.
        while (head)
            head = std::move(head->next);
    }
 
    void push(int data)
    {
        head = std::unique_ptr<Node>(new Node{data, std::move(head)});
    }
};
 
int main()
{
    std::cout << "1) Unique ownership semantics demo\n";
    {
        // Create a (uniquely owned) resource
        std::unique_ptr<D> p = std::make_unique<D>();
 
        // Transfer ownership to `pass_through`,
        // which in turn transfers ownership back through the return value
        std::unique_ptr<D> q = pass_through(std::move(p));
 
        // `p` is now in a moved-from 'empty' state, equal to `nullptr`
        assert(!p);
    }
 
    std::cout << "\n" "2) Runtime polymorphism demo\n";
    {
        // Create a derived resource and point to it via base type
        std::unique_ptr<B> p = std::make_unique<D>();
 
        // Dynamic dispatch works as expected
        p->bar();
    }
 
    std::cout << "\n" "3) Custom deleter demo\n";
    std::ofstream("demo.txt") << 'x'; // prepare the file to read
    {
        using unique_file_t = std::unique_ptr<std::FILE, decltype(&close_file)>;
        unique_file_t fp(std::fopen("demo.txt", "r"), &close_file);
        if (fp)
            std::cout << char(std::fgetc(fp.get())) << '\n';
    } // `close_file()` called here (if `fp` is not null)
 
    std::cout << "\n" "4) Custom lambda-expression deleter and exception safety demo\n";
    try
    {
        std::unique_ptr<D, void(*)(D*)> p(new D, [](D* ptr)
        {
            std::cout << "destroying from a custom deleter...\n";
            delete ptr;
        });
 
        throw std::runtime_error(""); // `p` would leak here if it were instead a plain pointer
    }
    catch (const std::exception&) { std::cout << "Caught exception\n"; }
 
    std::cout << "\n" "5) Array form of unique_ptr demo\n";
    {
        std::unique_ptr<D[]> p(new D[3]);
    } // `D::~D()` is called 3 times
 
    std::cout << "\n" "6) Linked list demo\n";
    {
        List wall;
        for (int beer = 0; beer != 1'000'000; ++beer)
            wall.push(beer);
 
        std::cout << "1'000'000 bottles of beer on the wall...\n";
    } // destroys all the beers
}
/*
1) Unique ownership semantics demo
D::D
D::bar
D::~D
 
2) Runtime polymorphism demo
D::D
D::bar
D::~D
 
3) Custom deleter demo
x
 
4) Custom lambda-expression deleter and exception safety demo
D::D
destroying from a custom deleter...
D::~D
Caught exception
 
5) Array form of unique_ptr demo
D::D
D::D
D::D
D::~D
D::~D
D::~D
 
6) Linked list demo
1'000'000 bottles of beer on the wall...
*/
```

##### Member functions

###### [std::unique_ptr<T,Deleter>::unique_ptr](https://en.cppreference.com/w/cpp/memory/unique_ptr/unique_ptr)

* (constructor)
* constructs a new unique_ptr (public member function)

###### [std::unique_ptr<T,Deleter>::operator=](https://en.cppreference.com/w/cpp/memory/unique_ptr/operator%3D)

* assigns the unique_ptr (public member function)
* 1) Move assignment operator. Transfers ownership from r to `*this` as if by calling `reset(r.release())` followed by an assignment of `get_deleter()` from `std::forward<Deleter>(r.get_deleter())`.
    * If Deleter is not a reference type, requires that it is `nothrow-MoveAssignable`.
    * If Deleter is a reference type, requires that `std::remove_reference<Deleter>::type` is `nothrow-CopyAssignable`.
    * The move assignment operator only participates in overload resolution if `std::is_move_assignable<Deleter>::value` is `true`.
* 2) Converting assignment operator. Behaves same as (1), except that
    * This assignment operator of the primary template only participates in overload resolution if U is not an array type and `unique_ptr<U,E>::pointer` is implicitly convertible to pointer and `std::is_assignable<Deleter&, E&&>::value` is `true`.
    * This assignment operator in the specialization for arrays, `std::unique_ptr<T[]>` behaves the same as in the primary template, except that will only participate in overload resolution if all of the following is true:
        * U is an array type
        * pointer is the same type as `element_type*`
        * `unique_ptr<U,E>::pointer` is the same type as `unique_ptr<U,E>::element_type*`
        * `unique_ptr<U,E>::element_type(*)[]` is convertible to `element_type(*)[]`
        * `std::is_assignable<Deleter&, E&&>::value` is `true`
* 3) Effectively the same as calling `reset()`.
* Note that unique_ptr's assignment operator only accepts `rvalues`, which are typically generated by std::move. (The `unique_ptr` class explicitly deletes its `lvalue` copy constructor and `lvalue` assignment operator.)
* Parameters
    * r	-	smart pointer from which ownership will be transferred
* Return value
    * `*this`
```c++
#include <iostream>
#include <memory>
 
struct Foo {
    int id;
    Foo(int id) : id(id) { std::cout << "Foo " << id << '\n'; }
    ~Foo() { std::cout << "~Foo " << id << '\n'; }
};
 
int main() 
{
    std::unique_ptr<Foo> p1( std::make_unique<Foo>(1) );
 
    {
        std::cout << "Creating new Foo...\n";
        std::unique_ptr<Foo> p2( std::make_unique<Foo>(2) );
        // p1 = p2; // Error ! can't copy unique_ptr
        p1 = std::move(p2);
        std::cout << "About to leave inner block...\n";
 
        // Foo instance will continue to live, 
        // despite p2 going out of scope
    }
 
    std::cout << "About to leave program...\n";
}
/*
Foo 1
Creating new Foo...
Foo 2
~Foo 1
About to leave inner block...
About to leave program...
~Foo 2
*/
```

###### Modifiers

* [std::unique_ptr<T,Deleter>::release](https://en.cppreference.com/w/cpp/memory/unique_ptr/release)
    * returns a pointer to the managed object and releases the ownership (public member function)
    * Releases the ownership of the managed object, if any.
    * get() returns nullptr after the call.
    * The caller is responsible for deleting the object.
```c++
#include <memory>
#include <iostream>
#include <cassert>
 
struct Foo {
    Foo() { std::cout << "Foo\n"; }
    ~Foo() { std::cout << "~Foo\n"; }
};
 
int main()
{
    std::cout << "Creating new Foo...\n";
    std::unique_ptr<Foo> up(new Foo());
 
    std::cout << "About to release Foo...\n";
    Foo* fp = up.release();
 
    assert (up.get() == nullptr);
    assert (up == nullptr);
 
    std::cout << "Foo is no longer owned by unique_ptr...\n";
 
    delete fp;
}
/*
Creating new Foo...
Foo
About to release Foo...
Foo is no longer owned by unique_ptr...
~Foo
*/
```
* [std::unique_ptr<T,Deleter>::reset](https://en.cppreference.com/w/cpp/memory/unique_ptr/reset)
    * replaces the managed object (public member function)
    * Replaces the managed object.
        * 1) Given current_ptr, the pointer that was managed by *this, performs the following actions, in this order:
            * Saves a copy of the current pointer old_ptr = current_ptr
            * Overwrites the current pointer with the argument current_ptr = ptr
            * If the old pointer was non-empty, deletes the previously managed object if(old_ptr) get_deleter()(old_ptr).
        * 2) Behaves the same as the reset member of the primary template, except that it will only participate in overload resolution if either
            * U is the same type as pointer, or
            * pointer is the same type as element_type* and U is a pointer type V* such that V(*)[] is convertible to element_type(*)[].
        * 3) Equivalent to reset(pointer())
    * Notes
        * To replace the managed object while supplying a new deleter as well, move assignment operator may be used.
        * A test for self-reset, i.e. whether ptr points to an object already managed by *this, is not performed, except where provided as a compiler extension or as a debugging assert. Note that code such as p.reset(p.release()) does not involve self-reset, only code like p.reset(p.get()) does.
```c++
#include <iostream>
#include <memory>
 
struct Foo { // object to manage
    Foo() { std::cout << "Foo...\n"; }
    ~Foo() { std::cout << "~Foo...\n"; }
};
 
struct D { // deleter
    void operator() (Foo* p) {
        std::cout << "Calling delete for Foo object... \n";
        delete p;
    }
};
 
int main()
{
    std::cout << "Creating new Foo...\n";
    std::unique_ptr<Foo, D> up(new Foo(), D());  // up owns the Foo pointer (deleter D)
 
    std::cout << "Replace owned Foo with a new Foo...\n";
    up.reset(new Foo());  // calls deleter for the old one
 
    std::cout << "Release and delete the owned Foo...\n";
    up.reset(nullptr);      
}
/*
Creating new Foo...
Foo...
Replace owned Foo with a new Foo...
Foo...
Calling delete for Foo object...
~Foo...
Release and delete the owned Foo...
Calling delete for Foo object...
~Foo...
*/
```

###### Observers

* [std::unique_ptr<T,Deleter>::get](https://en.cppreference.com/w/cpp/memory/unique_ptr/get)
    * returns a pointer to the managed object (public member function)
    * Returns a pointer to the managed object or nullptr if no object is owned.
```c++
#include <iomanip>
#include <iostream>
#include <memory>
#include <string>
#include <utility>
 
class Res {
    std::string s;
 
public:
    Res(std::string arg) : s{ std::move(arg) } {
        std::cout << "Res::Res(" << std::quoted(s) << ");\n";
    }
 
    ~Res() {
        std::cout << "Res::~Res();\n";
    }
 
private:
    friend std::ostream& operator<< (std::ostream& os, Res const& r) {
        return os << "Res { s = " << std::quoted(r.s) << "; }";
    }
};
 
int main()
{
    std::unique_ptr<Res> up(new Res{"Hello, world!"});
    Res *res = up.get();
    std::cout << *res << '\n';
}
/*
Res::Res("Hello, world!");
Res { s = "Hello, world!"; }
Res::~Res();
*/
```

###### Single-object version, `unique_ptr<T>`

* [std::unique_ptr<T,Deleter>::operator*, std::unique_ptr<T,Deleter>::operator->](https://en.cppreference.com/w/cpp/memory/unique_ptr/operator*)
    * dereferences pointer to the managed object (public member function)
    * `operator*` and `operator->` provide access to the object owned by `*this`.
    * The behavior is undefined if `get() == nullptr`.
    * These member functions are only provided for unique_ptr for the single objects i.e. the primary template.
```c++
#include <iostream>
#include <memory>
 
struct Foo {
    void bar() { std::cout << "Foo::bar\n"; }
};
 
void f(const Foo&) 
{
    std::cout << "f(const Foo&)\n";
}
 
int main() 
{
    std::unique_ptr<Foo> ptr(new Foo);
 
    ptr->bar();
    f(*ptr);
}
/*
Foo::bar
f(const Foo&)
*/
```

###### `Array version, unique_ptr<T[]>`

* [std::unique_ptr<T,Deleter>::operator[]](https://en.cppreference.com/w/cpp/memory/unique_ptr/operator_at)
    * provides indexed access to the managed array (public member function)
    * `operator[]` provides access to elements of an array managed by a unique_ptr.
    * The parameter i shall be less than the number of elements in the array; otherwise, the behavior is undefined.
    * This member function is only provided for specializations for array types.
```c++
#include <iostream>
#include <memory>
 
int main() 
{
    const int size = 10; 
    std::unique_ptr<int[]> fact(new int[size]);
 
    for (int i = 0; i < size; ++i) {
        fact[i] = (i == 0) ? 1 : i * fact[i-1];
    }
 
    for (int i = 0; i < size; ++i) {
        std::cout << i << "! = " << fact[i] << '\n';
    }
}
/*
0! = 1
1! = 1
2! = 2
3! = 6
4! = 24
5! = 120
6! = 720
7! = 5040
8! = 40320
9! = 362880
*/
```

##### Non-member functions

###### [std::make_unique, std::make_unique_for_overwrite](https://en.cppreference.com/w/cpp/memory/unique_ptr/make_unique)

* creates a unique pointer that manages a new object (function template)
* Constructs an object of type T and wraps it in a std::unique_ptr.
```c++
#include <cassert>
#include <cstdio>
#include <fstream>
#include <iostream>
#include <memory>
#include <stdexcept>
 
// helper class for runtime polymorphism demo below
struct B
{
    virtual ~B() = default;
 
    virtual void bar() { std::cout << "B::bar\n"; }
};
 
struct D : B
{
    D() { std::cout << "D::D\n"; }
    ~D() { std::cout << "D::~D\n"; }
 
    void bar() override { std::cout << "D::bar\n"; }
};
 
// a function consuming a unique_ptr can take it by value or by rvalue reference
std::unique_ptr<D> pass_through(std::unique_ptr<D> p)
{
    p->bar();
    return p;
}
 
// helper function for the custom deleter demo below
void close_file(std::FILE* fp)
{
    std::fclose(fp);
}
 
// unique_ptr-based linked list demo
struct List
{
    struct Node
    {
        int data;
        std::unique_ptr<Node> next;
    };
 
    std::unique_ptr<Node> head;
 
    ~List()
    {
        // destroy list nodes sequentially in a loop, the default destructor
        // would have invoked its `next`'s destructor recursively, which would
        // cause stack overflow for sufficiently large lists.
        while (head)
            head = std::move(head->next);
    }
 
    void push(int data)
    {
        head = std::unique_ptr<Node>(new Node{data, std::move(head)});
    }
};
 
int main()
{
    std::cout << "1) Unique ownership semantics demo\n";
    {
        // Create a (uniquely owned) resource
        std::unique_ptr<D> p = std::make_unique<D>();
 
        // Transfer ownership to `pass_through`,
        // which in turn transfers ownership back through the return value
        std::unique_ptr<D> q = pass_through(std::move(p));
 
        // `p` is now in a moved-from 'empty' state, equal to `nullptr`
        assert(!p);
    }
 
    std::cout << "\n" "2) Runtime polymorphism demo\n";
    {
        // Create a derived resource and point to it via base type
        std::unique_ptr<B> p = std::make_unique<D>();
 
        // Dynamic dispatch works as expected
        p->bar();
    }
 
    std::cout << "\n" "3) Custom deleter demo\n";
    std::ofstream("demo.txt") << 'x'; // prepare the file to read
    {
        using unique_file_t = std::unique_ptr<std::FILE, decltype(&close_file)>;
        unique_file_t fp(std::fopen("demo.txt", "r"), &close_file);
        if (fp)
            std::cout << char(std::fgetc(fp.get())) << '\n';
    } // `close_file()` called here (if `fp` is not null)
 
    std::cout << "\n" "4) Custom lambda-expression deleter and exception safety demo\n";
    try
    {
        std::unique_ptr<D, void(*)(D*)> p(new D, [](D* ptr)
        {
            std::cout << "destroying from a custom deleter...\n";
            delete ptr;
        });
 
        throw std::runtime_error(""); // `p` would leak here if it were instead a plain pointer
    }
    catch (const std::exception&) { std::cout << "Caught exception\n"; }
 
    std::cout << "\n" "5) Array form of unique_ptr demo\n";
    {
        std::unique_ptr<D[]> p(new D[3]);
    } // `D::~D()` is called 3 times
 
    std::cout << "\n" "6) Linked list demo\n";
    {
        List wall;
        for (int beer = 0; beer != 1'000'000; ++beer)
            wall.push(beer);
 
        std::cout << "1'000'000 bottles of beer on the wall...\n";
    } // destroys all the beers
}
/*
1) Unique ownership semantics demo
D::D
D::bar
D::~D
 
2) Runtime polymorphism demo
D::D
D::bar
D::~D
 
3) Custom deleter demo
x
 
4) Custom lambda-expression deleter and exception safety demo
D::D
destroying from a custom deleter...
D::~D
Caught exception
 
5) Array form of unique_ptr demo
D::D
D::D
D::D
D::~D
D::~D
D::~D
 
6) Linked list demo
1'000'000 bottles of beer on the wall...
*/
```

#### [std::shared_ptr](https://en.cppreference.com/w/cpp/memory/shared_ptr)

* smart pointer with shared object ownership semantics (class template)
* std::shared_ptr is a smart pointer that retains shared ownership of an object through a pointer. Several shared_ptr objects may own the same object. The object is destroyed and its memory deallocated when either of the following happens:
    * the last remaining shared_ptr owning the object is destroyed;
    * the last remaining shared_ptr owning the object is assigned another pointer via operator= or reset().
* The object is destroyed using delete-expression or a custom deleter that is supplied to shared_ptr during construction.
* A shared_ptr can share ownership of an object while storing a pointer to another object. This feature can be used to point to member objects while owning the object they belong to. The stored pointer is the one accessed by get(), the dereference and the comparison operators. The managed pointer is the one passed to the deleter when use count reaches zero.
* A shared_ptr may also own no objects, in which case it is called empty (an empty shared_ptr may have a non-null stored pointer if the aliasing constructor was used to create it).
* All specializations of shared_ptr meet the requirements of CopyConstructible, CopyAssignable, and LessThanComparable and are contextually convertible to bool.
* All member functions (including copy constructor and copy assignment) can be called by multiple threads on different instances of shared_ptr without additional synchronization even if these instances are copies and share ownership of the same object. If multiple threads of execution access the same instance of shared_ptr without synchronization and any of those accesses uses a non-const member function of shared_ptr then a data race will occur; the shared_ptr overloads of atomic functions can be used to prevent the data race.
* Notes
    * The ownership of an object can only be shared with another shared_ptr by copy constructing or copy assigning its value to another shared_ptr. Constructing a new shared_ptr using the raw underlying pointer owned by another shared_ptr leads to undefined behavior.
    * std::shared_ptr may be used with an incomplete type T. However, the constructor from a raw pointer (template\<class Y> shared_ptr(Y*)) and the template\<class Y> void reset(Y*) member function may only be called with a pointer to a complete type (note that std::unique_ptr may be constructed from a raw pointer to an incomplete type).
    * The T in std::shared_ptr\<T> may be a function type: in this case it manages a pointer to function, rather than an object pointer. This is sometimes used to keep a dynamic library or a plugin loaded as long as any of its functions are referenced:
```c++
void del(void(*)()) {}
void fun() {}
int main(){
  std::shared_ptr<void()> ee(fun, del);
  (*ee)();
}
```
* Implementation notes
    * In a typical implementation, shared_ptr holds only two pointers:
        * the stored pointer (one returned by get());
        * a pointer to control block.
    * The control block is a dynamically-allocated object that holds:
        * either a pointer to the managed object or the managed object itself;
        * the deleter (type-erased);
        * the allocator (type-erased);
        * the number of shared_ptrs that own the managed object;
        * the number of weak_ptrs that refer to the managed object.
    * When shared_ptr is created by calling std::make_shared or std::allocate_shared, the memory for both the control block and the managed object is created with a single allocation. The managed object is constructed in-place in a data member of the control block. When shared_ptr is created via one of the shared_ptr constructors, the managed object and the control block must be allocated separately. In this case, the control block stores a pointer to the managed object.
    * The pointer held by the shared_ptr directly is the one returned by get(), while the pointer/object held by the control block is the one that will be deleted when the number of shared owners reaches zero. These pointers are not necessarily equal.
    * The destructor of shared_ptr decrements the number of shared owners of the control block. If that counter reaches zero, the control block calls the destructor of the managed object. The control block does not deallocate itself until the std::weak_ptr counter reaches zero as well.
    * In existing implementations, the number of weak pointers is incremented ([1], [2]) if there is a shared pointer to the same control block.
    * To satisfy thread safety requirements, the reference counters are typically incremented using an equivalent of std::atomic::fetch_add with std::memory_order_relaxed (decrementing requires stronger ordering to safely destroy the control block).
```c++
#include <iostream>
#include <memory>
#include <thread>
#include <chrono>
#include <mutex>
 
struct Base
{
    Base() { std::cout << "  Base::Base()\n"; }
    // Note: non-virtual destructor is OK here
    ~Base() { std::cout << "  Base::~Base()\n"; }
};
 
struct Derived: public Base
{
    Derived() { std::cout << "  Derived::Derived()\n"; }
    ~Derived() { std::cout << "  Derived::~Derived()\n"; }
};
 
void thr(std::shared_ptr<Base> p)
{
    std::this_thread::sleep_for(std::chrono::seconds(1));
    std::shared_ptr<Base> lp = p; // thread-safe, even though the
                                  // shared use_count is incremented
    {
        static std::mutex io_mutex;
        std::lock_guard<std::mutex> lk(io_mutex);
        std::cout << "local pointer in a thread:\n"
                  << "  lp.get() = " << lp.get()
                  << ", lp.use_count() = " << lp.use_count() << '\n';
    }
}
 
int main()
{
    std::shared_ptr<Base> p = std::make_shared<Derived>();
 
    std::cout << "Created a shared Derived (as a pointer to Base)\n"
              << "  p.get() = " << p.get()
              << ", p.use_count() = " << p.use_count() << '\n';
    std::thread t1(thr, p), t2(thr, p), t3(thr, p);
    p.reset(); // release ownership from main
    std::cout << "Shared ownership between 3 threads and released\n"
              << "ownership from main:\n"
              << "  p.get() = " << p.get()
              << ", p.use_count() = " << p.use_count() << '\n';
    t1.join(); t2.join(); t3.join();
    std::cout << "All threads completed, the last one deleted Derived\n";
}
/*
Base::Base()
  Derived::Derived()
Created a shared Derived (as a pointer to Base)
  p.get() = 0x2299b30, p.use_count() = 1
Shared ownership between 3 threads and released
ownership from main:
  p.get() = 0, p.use_count() = 0
local pointer in a thread:
  lp.get() = 0x2299b30, lp.use_count() = 5
local pointer in a thread:
  lp.get() = 0x2299b30, lp.use_count() = 3
local pointer in a thread:
  lp.get() = 0x2299b30, lp.use_count() = 2
  Derived::~Derived()
  Base::~Base()
All threads completed, the last one deleted Derived
*/
```
```c++
#include <memory>
#include <iostream>
 
struct MyObj
{
    MyObj()
    {
        std::cout<<"MyObj construced" <<std::endl;
    }
 
    ~MyObj()
    {
        std::cout<<"MyObj destructed" <<std::endl;
    }
};
 
struct Container : std::enable_shared_from_this<Container> // note: public inheritance
{
    void CreateMember()
    {
        memberObj = std::make_shared<MyObj>();
    }
    std::shared_ptr<MyObj> memberObj;
 
    std::shared_ptr<MyObj> GetAsMyObj()
    {
        // Use an alias shared ptr for member
        return std::shared_ptr<MyObj>(shared_from_this(), memberObj.get());
    }
};
 
 
void test()
{
 
    std::shared_ptr<Container> cont = std::make_shared<Container>();
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
 
    std::cout << "Creating member\n\n";
    cont->CreateMember();
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
 
    std::cout << "Creating another shared container\n\n";
    std::shared_ptr<Container> cont2 = cont;
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
    std::cout << "cont2.use_count() = " << cont2.use_count() << '\n';
    std::cout << "cont2.memberObj.use_count() = " << cont2->memberObj.use_count() << '\n';
 
    std::cout << "GetAsMyObj\n\n";
    std::shared_ptr<MyObj> myobj1 = cont->GetAsMyObj();
    std::cout << "myobj1.use_count() = " << myobj1.use_count() << '\n';
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
    std::cout << "cont2.use_count() = " << cont2.use_count() << '\n';
    std::cout << "cont2.memberObj.use_count() = " << cont2->memberObj.use_count() << '\n';
 
    std::cout << "copying alias obj\n\n";
    std::shared_ptr<MyObj> myobj2 = myobj1;
    std::cout << "myobj1.use_count() = " << myobj1.use_count() << '\n';
    std::cout << "myobj2.use_count() = " << myobj2.use_count() << '\n';
 
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
    std::cout << "cont2.use_count() = " << cont2.use_count() << '\n';
    std::cout << "cont2.memberObj.use_count() = " << cont2->memberObj.use_count() << '\n';
 
    std::cout << "Resetting cont2\n\n";
    cont2.reset();
    std::cout << "myobj1.use_count() = " << myobj1.use_count() << '\n';
    std::cout << "myobj2.use_count() = " << myobj2.use_count() << '\n';
 
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
 
    std::cout << "Resetting myobj2\n\n";
    myobj2.reset();
    std::cout << "myobj1.use_count() = " << myobj1.use_count() << '\n';
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
    std::cout << "cont.memberObj.use_count() = " << cont->memberObj.use_count() << '\n';
 
    std::cout << "Resetting cont\n\n";
    cont.reset();
    std::cout << "myobj1.use_count() = " << myobj1.use_count() << '\n';
 
    std::cout << "cont.use_count() = " << cont.use_count() << '\n';
 
}
 
 
int main()
{
    test();
}
/*
cont.use_count() = 1
cont.memberObj.use_count() = 0
Creating member
 
MyObj construced
cont.use_count() = 1
cont.memberObj.use_count() = 1
Creating another shared container
 
cont.use_count() = 2
cont.memberObj.use_count() = 1
cont2.use_count() = 2
cont2.memberObj.use_count() = 1
GetAsMyObj
 
myobj1.use_count() = 3
cont.use_count() = 3
cont.memberObj.use_count() = 1
cont2.use_count() = 3
cont2.memberObj.use_count() = 1
copying alias obj
 
myobj1.use_count() = 4
myobj2.use_count() = 4
cont.use_count() = 4
cont.memberObj.use_count() = 1
cont2.use_count() = 4
cont2.memberObj.use_count() = 1
Resetting cont2
 
myobj1.use_count() = 3
myobj2.use_count() = 3
cont.use_count() = 3
cont.memberObj.use_count() = 1
Resetting myobj2
 
myobj1.use_count() = 2
cont.use_count() = 2
cont.memberObj.use_count() = 1
Resetting cont
 
myobj1.use_count() = 1
cont.use_count() = 0
MyObj destructed
*/
```
* [std::shared_ptr\<T>::use_count - cppreference.com](https://en.cppreference.com/w/cpp/memory/shared_ptr/use_count)
    * returns the number of shared_ptr objects referring to the same managed object (public member function)
    * Returns the number of different shared_ptr instances (`this` included) managing the current object. If there is no managed object, `0` is returned.
    * In multithreaded environment, the value returned by use_count is approximate (typical implementations use a memory_order_relaxed load)
```c++
#include <memory>
#include <iostream>
 
void fun(std::shared_ptr<int> sp)
{
    std::cout << "in fun(): sp.use_count() == " << sp.use_count()
              << " (object @ " << sp << ")\n";
}
 
int main()
{
    auto sp1 = std::make_shared<int>(5);
    std::cout << "in main(): sp1.use_count() == " << sp1.use_count()
              << " (object @ " << sp1 << ")\n";
 
    fun(sp1);
}
/*
in main(): sp1.use_count() == 1 (object @ 0x20eec30)
in fun(): sp.use_count() == 2 (object @ 0x20eec30)
*/
```
* [std::make_shared, std::make_shared_for_overwrite - cppreference.com](https://en.cppreference.com/w/cpp/memory/shared_ptr/make_shared)
    * creates a shared pointer that manages a new object (function template)
        * 1) Constructs an object of type T and wraps it in a std::shared_ptr using args as the parameter list for the constructor of T. The object is constructed as if by the expression ::new (pv) T(std::forward\<Args>(args)...), where pv is an internal void* pointer to storage suitable to hold an object of type T. The storage is typically larger than sizeof(T) in order to use one allocation for both the control block of the shared pointer and the T object. The std::shared_ptr constructor called by this function enables shared_from_this with a pointer to the newly constructed object of type T.
            * This overload participates in overload resolution only if T is not an array type (since C++20)
        * 2,3) Same as (1), but the object constructed is a possibly-multidimensional array whose non-array elements of type std::remove_all_extents_t\<T> are value-initialized as if by placement-new expression ::new(pv) std::remove_all_extents_t\<T>(). The overload (2) creates an array of size N along the first dimension. The array elements are initialized in ascending order of their addresses, and when their lifetime ends are destroyed in the reverse order of their original construction.
        * 4,5) Same as (2,3), but every element is initialized from the default value u. If U is not an array type, then this is performed as if by the same placement-new expression as in (1); otherwise, this is performed as if by initializing every non-array element of the (possibly multidimensional) array with the corresponding element from u with the same placement-new expression as in (1). The overload (4) creates an array of size N along the first dimension. The array elements are initialized in ascending order of their addresses, and when their lifetime ends are destroyed in the reverse order of their original construction.
        * 6) Same as (1) if T is not an array type and (3) if T is U[N], except that the created object is default-initialized.
        * 7) Same as (2), except that the individual array elements are default-initialized.
    * In each case, the object (or individual elements if T is an array type) (since C++20) will be destroyed by p->~X(), where p is a pointer to the object and X is its type.
```c++
#include <memory>
#include <vector>
#include <iostream>
#include <type_traits>
 
struct C
{
    // constructors needed (until C++20)
    C(int i) : i(i) {}
    C(int i, float f) : i(i), f(f) {}
    int i;
    float f{};
};
 
int main()
{
    // using `auto` for the type of `sp1`
    auto sp1 = std::make_shared<C>(1); // overload (1)
    static_assert(std::is_same_v<decltype(sp1), std::shared_ptr<C>>);
    std::cout << "sp1->{ i:" << sp1->i << ", f:" << sp1->f << " }\n";
 
    // being explicit with the type of `sp2`
    std::shared_ptr<C> sp2 = std::make_shared<C>(2, 3.0f); // overload (1)
    static_assert(std::is_same_v<decltype(sp2), std::shared_ptr<C>>);
    static_assert(std::is_same_v<decltype(sp1), decltype(sp2)>);
    std::cout << "sp2->{ i:" << sp2->i << ", f:" << sp2->f << " }\n";
 
    // shared_ptr to a value-initialized float[64]; overload (2):
    std::shared_ptr<float[]> sp3 = std::make_shared<float[]>(64);
 
    // shared_ptr to a value-initialized long[5][3][4]; overload (2):
    std::shared_ptr<long[][3][4]> sp4 = std::make_shared<long[][3][4]>(5);
 
    // shared_ptr to a value-initialized short[128]; overload (3):
    std::shared_ptr<short[128]> sp5 = std::make_shared<short[128]>();
 
    // shared_ptr to a value-initialized int[7][6][5]; overload (3):
    std::shared_ptr<int[7][6][5]> sp6 = std::make_shared<int[7][6][5]>();
 
    // shared_ptr to a double[256], where each element is 2.0; overload (4):
    std::shared_ptr<double[]> sp7 = std::make_shared<double[]>(256, 2.0);
 
    // shared_ptr to a double[7][2], where each double[2] element is {3.0, 4.0}; overload (4):
    std::shared_ptr<double[][2]> sp8 = std::make_shared<double[][2]>(7, {3.0, 4.0});
 
    // shared_ptr to a vector<int>[4], where each vector has contents {5, 6}; overload (4):
    std::shared_ptr<std::vector<int>[]> sp9 = std::make_shared<std::vector<int>[]>(4, {5, 6});
 
    // shared_ptr to a float[512], where each element is 1.0; overload (5):
    std::shared_ptr<float[512]> spA = std::make_shared<float[512]>(1.0);
 
    // shared_ptr to a double[6][2], where each double[2] element is {1.0, 2.0}; overload (5):
    std::shared_ptr<double[6][2]> spB = std::make_shared<double[6][2]>({1.0, 2.0});
 
    // shared_ptr to a vector<int>[4], where each vector has contents {5, 6}; overload (5):
    std::shared_ptr<std::vector<int>[4]> spC = std::make_shared<std::vector<int>[4]>({5, 6});
}
/*
sp1->{ i:1, f:0 }
sp2->{ i:2, f:3 }
*/
```

#### [std::weak_ptr](https://en.cppreference.com/w/cpp/memory/weak_ptr)

* weak reference to an object managed by std::shared_ptr (class template)
* `std::weak_ptr` is a smart pointer that holds a `non-owning ("weak") reference` to an object that is managed by `std::shared_ptr`. It must be converted to `std::shared_ptr` in order to access the referenced object.
* `std::weak_ptr` models temporary ownership: when an object needs to be accessed only if it exists, and it may be deleted at any time by someone else, `std::weak_ptr` is used to track the object, and it is converted to `std::shared_ptr` to assume temporary ownership. If the original `std::shared_ptr` is destroyed at this time, the object's lifetime is extended until the temporary `std::shared_ptr` is destroyed as well.
* Another use for `std::weak_ptr` is to `break reference cycles` formed by objects managed by `std::shared_ptr`. If such cycle is orphaned (i.e., there are no outside shared pointers into the cycle), the shared_ptr reference counts cannot reach zero and the memory is leaked. To prevent this, one of the pointers in the cycle can be made weak.
* Notes
    * Like `std::shared_ptr`, a typical implementation of weak_ptr stores two pointers:
        * a pointer to the control block; and
        * the stored pointer of the shared_ptr it was constructed from.
    * A separate stored pointer is necessary to ensure that converting a shared_ptr to weak_ptr and then back works correctly, even for aliased shared_ptrs. It is not possible to access the stored pointer in a weak_ptr without locking it into a shared_ptr.
* Example
    * Demonstrates how lock is used to ensure validity of the pointer.
```c++
#include <iostream>
#include <memory>
 
std::weak_ptr<int> gw;
 
void observe()
{
    std::cout << "gw.use_count() == " << gw.use_count() << "; ";
    // we have to make a copy of shared pointer before usage:
    if (std::shared_ptr<int> spt = gw.lock()) {
        std::cout << "*spt == " << *spt << '\n';
    }
    else {
        std::cout << "gw is expired\n";
    }
}
 
int main()
{
    {
        auto sp = std::make_shared<int>(42);
        gw = sp;
 
        observe();
    }
 
    observe();
}
/*
gw.use_count() == 1; *spt == 42
gw.use_count() == 0; gw is expired
*/
```

##### Member functions

###### [`std::weak_ptr<T>::weak_ptr`](https://en.cppreference.com/w/cpp/memory/weak_ptr/weak_ptr)

* (constructor)
* creates a new weak_ptr (public member function)
```c++
constexpr weak_ptr() noexcept;  (1)	(since C++11)
weak_ptr( const weak_ptr& r ) noexcept; (2)	(since C++11)
template< class Y >
weak_ptr( const weak_ptr<Y>& r ) noexcept;  (2)	(since C++11)
template< class Y >
weak_ptr( const std::shared_ptr<Y>& r ) noexcept;   (2)	(since C++11)
weak_ptr( weak_ptr&& r ) noexcept;  (3)	(since C++11)
template< class Y >
weak_ptr( weak_ptr<Y>&& r ) noexcept;   (3)	(since C++11)
```
* Constructs new weak_ptr that potentially shares an object with r.
    * 1) Default constructor. Constructs empty weak_ptr.
    * 2) Constructs new weak_ptr which shares an object managed by r. If r manages no object, `*this` manages no object too. The templated overloads don't participate in the overload resolution unless `Y*` is implicitly convertible to `T*``, or Y is the type "array of N U" for some type U and some number N, and T is the type "array of unknown bound of (possibly cv-qualified) U" (since C++17)`.
    * 3) Move constructors. Moves a weak_ptr instance from r into `*this`. After this, r is empty and `r.use_count()==0`. The templated overload doesn't participate in the overload resolution unless `Y*` is implicitly convertible to `T*`.
* Parameters
    * r	- a `std::shared_ptr` or `std::weak_ptr` that will be viewed by this `std::weak_ptr`.
* Notes
    * Because the default constructor is constexpr, static std::weak_ptrs are initialized as part of [static non-local initialization](https://en.cppreference.com/w/cpp/language/initialization#Non-local_variables), before any dynamic non-local initialization begins. This makes it safe to use a std::weak_ptr in a constructor of any static object.
* Example
```c++
#include <memory>
#include <iostream>
 
struct Foo {};
 
int main()
{
   std::weak_ptr<Foo> w_ptr;
 
   {
      auto ptr = std::make_shared<Foo>();
      w_ptr = ptr;
      std::cout << "w_ptr.use_count() inside scope: " << w_ptr.use_count() << '\n';
   }
 
   std::cout << "w_ptr.use_count() out of scope: " << w_ptr.use_count() << '\n';
   std::cout << "w_ptr.expired() out of scope: " << std::boolalpha << w_ptr.expired() << '\n';
}
/*
w_ptr.use_count() inside scope: 1
w_ptr.use_count() out of scope: 0
w_ptr.expired() out of scope: true
*/
```

###### [`std::weak_ptr<T>::~weak_ptr`](https://en.cppreference.com/w/cpp/memory/weak_ptr/~weak_ptr#Example)
    
* (destructor)
* destroys a weak_ptr (public member function)
* Destroys the weak_ptr object. Results in no effect to the managed object.
* Example
    * The program shows the effect of "non-breaking" the cycle of std::shared_ptrs.	
```c++
#include <iostream>
#include <memory>
#include <variant>
 
class Node {
    char id;
    std::variant<std::weak_ptr<Node>, std::shared_ptr<Node>> ptr;
  public:
    Node(char id) : id{id} {}
    ~Node() { std::cout << "  '" << id << "' reclaimed\n"; }
    /*...*/
    void assign(std::weak_ptr<Node> p) { ptr = p; }
    void assign(std::shared_ptr<Node> p) { ptr = p; }
};
 
enum class shared { all, some };
 
void test_cyclic_graph(const shared x) {
 
    auto A = std::make_shared<Node>('A');
    auto B = std::make_shared<Node>('B');
    auto C = std::make_shared<Node>('C');
 
    A->assign(B);
    B->assign(C);
 
    if (shared::all == x) {
        C->assign(A);
        std::cout << "All links are shared pointers";
    } else {
        C->assign(std::weak_ptr<Node>(A));
        std::cout << "One link is a weak_ptr";
    }
    /*...*/
    std::cout << "\nLeaving...\n";
}
 
int main() {
    test_cyclic_graph(shared::some);
    test_cyclic_graph(shared::all); // produces a memory leak
}
/*
One link is a weak_ptr
Leaving...
  'A' reclaimed
  'B' reclaimed
  'C' reclaimed
All links are shared pointers
Leaving...
*/
```

###### Observers

* [`std::weak_ptr<T>::lock`](https://en.cppreference.com/w/cpp/memory/weak_ptr/lock)
    * creates a shared_ptr that manages the referenced object (public member function)
    * `std::shared_ptr<T> lock() const noexcept;`
    * Creates a new `std::shared_ptr` that shares ownership of the managed object. If there is no managed object, i.e. `*this` is empty, then the returned shared_ptr also is empty.
    * Effectively returns `expired() ? shared_ptr<T>() : shared_ptr<T>(*this)`, executed atomically.
    * Return value
        * A shared_ptr which shares ownership of the owned object if [std::weak_ptr::expired](https://en.cppreference.com/w/cpp/memory/weak_ptr/expired) returns false. Else returns default-constructed shared_ptr of type T.
    * Notes
        * Both this function and the constructor of `std::shared_ptr` may be used to acquire temporary ownership of the managed object referred to by a `std::weak_ptr`. The difference is that the constructor of `std::shared_ptr` throws an exception when its `std::weak_ptr` argument is empty, while `std::weak_ptr<T>::lock()` constructs an empty `std::shared_ptr<T>`.
    * Example
```c++
#include <iostream>
#include <memory>
 
void observe(std::weak_ptr<int> weak) 
{
    if (auto observe = weak.lock()) {
        std::cout << "\tobserve() able to lock weak_ptr<>, value=" << *observe << "\n";
    } else {
        std::cout << "\tobserve() unable to lock weak_ptr<>\n";
    }
}
 
int main()
{
    std::weak_ptr<int> weak;
    std::cout << "weak_ptr<> not yet initialized\n";
    observe(weak);
 
    {
        auto shared = std::make_shared<int>(42);
        weak = shared;
        std::cout << "weak_ptr<> initialized with shared_ptr.\n";
        observe(weak);
    }
 
    std::cout << "shared_ptr<> has been destructed due to scope exit.\n";
    observe(weak);
}
/*
weak_ptr<> not yet initialized
        observe() unable to lock weak_ptr<>
weak_ptr<> initialized with shared_ptr.
        observe() able to lock weak_ptr<>, value=42
shared_ptr<> has been destructed due to scope exit.
        observe() unable to lock weak_ptr<>
*/       
```

#### MISC

* [智能指针：从std::auto_ptr到std::unique_ptr - hanhuili的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/hanhuili/article/details/8299912)
* [拥抱智能指针，告别内存泄露](https://mp.weixin.qq.com/s/evYOoS4_XfjkPXlDWXTnSg)
* [浅析 C++智能指针和 enable_shared_from_this 机制](https://mp.weixin.qq.com/s/a7Nl2jnbOtkfzEAK1TxVyA)
* [一文掌握 C++ 智能指针的使用](https://mp.weixin.qq.com/s/bn7BAzBSxgbrkgRMnuy8-A)
  * RAII 与引用计数
  * std::shared_ptr
  * std::unique_ptr
  * std::weak_ptr

##### Smart developers use smart pointers

###### [Smart developers use smart pointers (1/7) - Smart pointers basics - Fluent C++](https://www.fluentcpp.com/2017/08/22/smart-developers-use-smart-pointers-smart-pointers-basics/)

* Smart pointer basics
* unique_ptr, shared_ptr, weak_ptr, scoped_ptr, raw pointers: clearly stating your intentions by knowing your smart pointers
* Custom deleters and How to make them more expressive
* Changing deleters during the life of a unique_ptr
* How to implement the pimpl idiom by using unique_ptr
* How to make a polymorphic clone in modern C++
* How to Return a Smart Pointer AND Use Covariance (by Raoul Borges)
* The stack and the heap
    * Like many other languages, C++ has several types of memories, that correspond to different parts of the physical memory. They are: the static, the stack, and the heap. The static is a topic rich enough to deserve its own moment of glory, so here we focus on the stack and the heap only.
    * The stack
        * `Objects allocated on the stack are automatically destroyed when they go out of scope.`
    * The heap
        * The heap is where dynamically allocated objects are stored, that is to say `objects that are allocated with a call to new`, which returns a pointer:
        * Ok strictly speaking, the memory allocated by new is called the `free store`.
        * Contrary to the stack, objects allocated on the heap are `not destroyed automatically`. 
        * And deleting a object on the heap is no trivial task: delete has to be called `once and only once` to deallocate a heap-based object. 
* RAII: the magic four letters
    * The principle of RAII is simple: wrap a resource (a pointer for instance) into an object, and dispose of the resource in its destructor. And this is exactly what smart pointers do:
    ```c++
    template <typename T>
    class SmartPointer
    {
    public:
        explicit SmartPointer(T* p) : p_(p) {}
        ~SmartPointer() { delete p_; }

    private:
        T* p_;
    };
    ```
    * The point is that you can manipulate smart pointers as objects allocated on the stack. And the compiler will take care of automatically calling the destructor of the smart pointer because… `objects allocated on the stack are automatically destroyed when they go out of scope`. And this will therefore call delete on the wrapped pointer. Only once. In a nutshell, smart pointers behave like pointers, but when they are destroyed they delete the object they point to.
    * The above code example was only made to get a grasp of RAII. But by no means is it a complete interface of a realistic smart pointer.
    * First, a smart pointer syntactically behaves like a pointer in many way: it can be dereferenced with operator* or operator->, that is to say you can call *sp or sp->member on it. And it is also convertible to bool, so that it can be used in an if statement like a pointer:
    ```c++
    if (sp)
    {
        ...
    ```
    * which tests the nullity of the underlying pointer. And finally, the underlying pointer itself is accessible with a .get() method.
    * Second, and maybe more importantly, there is a missing aspect from the above interface: it doesn’t deal with copy! Indeed, as is, a SmartPointer copied also copies the underlying pointer, so the below code has a bug:
    ```c++
    {
        SmartPointer<int> sp1(new int(42));
        SmartPointer<int> sp2 = sp1; // now both sp1 and sp2 point to the same object
    } // sp1 and sp2 are both destroyed, the pointer is deleted twice!
    ```
    * Indeed, it deletes the underlying object twice, leading to undefined behaviour.
    * How to deal with copy then? This is a feature on which the various types of smart pointer differ. And it turns out that this lets you express your intentions in code quite precisely. Stay tuned, as this is what we see in the next episode of this series.

###### [unique_ptr, shared_ptr, weak_ptr, scoped_ptr, raw pointers - Knowing your smart pointers (2/7) - Fluent C++](https://www.fluentcpp.com/2017/08/25/knowing-your-smart-pointers/)

* std::unique_ptr
    * The semantics of std::unique_ptr is that it is the sole owner of a memory resource. A std::unique_ptr will hold a pointer and delete it in its destructor (unless you customize this, which is the topic of another post).
    * Note that std::unique_ptr is the preferred pointer to return from a factory function. Indeed, on the top of taking care of handling the memory, std::unique_ptr wraps a normal pointer and is therefore compatible with polymorphism.
    * But since you are the owner, you are allowed to safely modify the pointed to object, and the rest of the design should take this into account. If you don’t want this to happen, the way to express it is by using a unique_ptr to const:
    ```c++
    std::unique_ptr<const House> buildAHouse(); // for some reason, I don't want you
                                                // to modify the house you're being passed
    ```
    * To ensure that there is only one unique_ptr that owns a memory resource, std::unique_ptr cannot be copied. The ownership can however be transferred from one unique_ptr to another (which is how you can pass them or return them from a function) by moving a unique_ptr into another one.
    * A move can be achieved by returning an std::unique_ptr by value from a function, or explicitly in code:
    ```c++
    std::unique_ptr<int> p1 = std::make_unique(42);
    std::unique_ptr<int> p2 = move(p1); // now p2 hold the resource
                                           and p1 no longer hold anything
    ```
* Raw pointers
    * For now I only want to focus on what raw pointers and references express in code: `raw pointers and references represent access to an object, but not ownership`. In fact, this is the default way of passing objects to functions and methods:
    * `void renderHouse(House const& house);`
    * This is particularly relevant to note when you hold an object with a unique_ptr and want to pass it to an interface. You don’t pass the unique_ptr, nor a reference to it, but rather a reference to the pointed to object:
    ```c++
    std::unique_ptr<House> house = buildAHouse();
    renderHouse(*house);
    ```
* std::shared_ptr
    * `A single memory resource can be held by several std::shared_ptrs at the same time`. The shared_ptrs internally maintain a count of how many of them there are holding the same resource, and when the last one is destroyed, it deletes the memory resource.
    * Therefore std::shared_ptr allows copies, but with a reference-counting mechanism to make sure that every resource is deleted once and only once.
    * At first glance, std::shared_ptr looks like the panacea for memory management, as it can be passed around and still maintain memory safety.
    * But std::shared_ptr should not be used by default, for several reasons:
        * Having several simultaneous holders of a resource makes for a more complex system than with one unique holder, like with std::unique_ptr. Even though an std::unique_ptr doesn’t prevent from accessing and modifying its resource, it sends a message that it is the priviledged owner of a resource. For this reason you’d expect it to centralize the control of the resource, at least to some degree.
        * Having several simultaneous holders of a resource makes thread-safety harder,
        * It makes the code counter-intuitive when an object is not shared in terms of the domain and still appears as “shared” in the code for a technical reason,
        * It can incur a performance cost, both in time and memory, because of the bookkeeping related to the reference-counting.
    * One good case for using std::shared_ptr though is when objects are `shared in the domain`. Using shared pointers then reflects it in an expressive way. Typically, the nodes of a graphs are well represented as shared pointers, because several nodes can hold a reference to one other node.
* std::weak_ptr
    * std::weak_ptrs can hold a reference to a shared object along with other std::shared_ptrs, but they don’t increment the reference count. This means that if no more std::shared_ptr are holding an object, this object will be deleted even if some weak pointers still point to it.
    * For this reason, a weak pointer needs to check if the object it points to is still alive. To do this, it has to be copied into to a std::shared_ptr:
    ```c++
    void useMyWeakPointer(std::weak_ptr<int> wp)
    {
        if (std::shared_ptr<int> sp = wp.lock())
        {
            // the resource is still here and can be used
        }
        else
        {
            // the resource is no longer here
        }
    }
    ```
    * A typical use case for this is about `breaking shared_ptr circular references`. Consider the following code:
    ```c++
    struct House
    {
        std::shared_ptr<House> neighbour;
    };

    std::shared_ptr<House> house1 = std::make_shared<House>();
    std::shared_ptr<House> house2 = std::make_shared<House>();;
    house1->neighbour = house2;
    house2->neighbour = house1;
    ```
    * None of the houses ends up being destroyed at the end of this code, because the shared_ptrs points into one another. But if one is a weak_ptr instead, there is no longer a circular reference.
    * Another use case pointed out by this answer on Stack Overflow is that weak_ptr can be used to `maintain a cache`. The data may or may not have been cleared from the cache, and the weak_ptr references this data.

###### [How to implement the pimpl idiom by using unique_ptr - Fluent C++](https://www.fluentcpp.com/2017/09/22/make-pimpl-using-unique_ptr/)

* The `pimpl`, standing for `pointer to implementation` is a widespread technique to cut compilation dependencies.
* The pimpl
    * Say we have a class reprenseting a fridge (yeah why not?), that works with an engine that it contains. Here is the header of this class:
    ```c++
    #include "Engine.h"

    class Fridge
    {
    public:
       void coolDown();
    private:
       Engine engine_;
    };
    ```
    * (the contents of the Engine class are not relevant here).
    * And here is its implementation file:
    ```c++
    #include "Fridge.h"

    void Fridge::coolDown()
    {
       /* ... */
    }
    ```
    * Now there is an issue with this design (that could be serious or not, depending on how many clients Fridge has). Since Fridge.h #includes Engine.h, any client of the Fridge class will indirectly #include the Engine class. `So when the Engine class is modified, all the clients of Fridge have to recompile, even if they don’t use Engine directly`.
    * The pimpl idiom aims at solving this issue by `adding a level of indirection`, FridgeImpl, that takes on the Engine.
    * The header file becomes:
    ```c++
    class Fridge
    {
    public:
       Fridge();
       ~Fridge();

       void coolDown();
    private:
       class FridgeImpl;
       FridgeImpl* impl_;
    };
    ```
    * Note that it no longer #include Engine.h.
    * And the implementation file becomes:
    ```c++
    #include "Engine.h"
    #include "Fridge.h"

    class Fridge::FridgeImpl
    {
    public:
       void coolDown()
       {
          /* ... */
       }
    private:
       Engine engine_;
    };

    Fridge::Fridge() : impl_(new FridgeImpl) {}

    Fridge::~Fridge()
    {
       delete impl_;
    }

    void Fridge::coolDown()
    {
       impl_->coolDown();
    }
    ```
    * The class now delegates its functionalities and members to FridgeImpl, and Fridge only has to forward the calls and `manage the life cycle` of the impl_ pointer.
    * What makes it work is that `pointers only need a forward declaration to compile`. For this reason, the header file of the Fridge class doesn’t need to see the full definition of FridgeImpl, and therefore neither do Fridge‘s clients.
* Using std::unique_ptr to manage the life cycle
    * Today it’s a bit unsettling to leave a raw pointer managing its own resource in C++. A natural thing to do would be to replace it with an std::unique_ptr (or with another smart pointer). This way the Fridge destructor no longer needs to do anything, and we can leave the compiler automatically generate it for us.
    * Oops, we get the following compilation errors!
    ```c++
    use of undefined type 'FridgeImpl'
    can't delete an incomplete type
    ```
    * Can you see what’s going on here?
* Destructor visibility
    * There is a rule in C++ that says that deleting a pointer leads to undefined behaviour if:
        * this pointer has type void*, or
        * the type pointed to is incomplete, that is to say is only forward declared, like FridgeImpl in our header file.
    * std::unique_ptr happens to check in its destructor if the definition of the type is visible before calling delete. `So it refuses to compile and to call delete if the type is only forward declared`.
    * Since we removed the declaration of the destructor in the Fridge class, the compiler took over and defined it for us. But compiler-generated methods are declared `inline`, so they are implemented in the header file directly. And there, the type of FridgeImpl is incomplete. Hence the error.
    * The fix would then be to `declare the destructor and thus prevent the compiler from doing it for us`. So the header file becomes:
    ```c++
    #include <memory>

    class Fridge
    {
    public:
       Fridge();
       ~Fridge();
       void coolDown();
    private:
       class FridgeImpl;
       std::unique_ptr<FridgeImpl> impl_;
    };
    ```
    * And we can still use the default implentation for the destructor that the compiler would have generated. But we need to put it in the implementation file, after the definition of FridgeImpl:
    ```c++
    #include "Engine.h"
    #include "Fridge.h"

    class FridgeImpl
    {
    public:
       void coolDown()
       {
          /* ... */
       }
    private:
       Engine engine_;
    };

    Fridge::Fridge() : impl_(new FridgeImpl) {}

    Fridge::~Fridge() = default;
    ```
  
###### [Polymorphic clones in modern C++ - Fluent C++](https://www.fluentcpp.com/2017/09/08/make-polymorphic-copy-modern-cpp/)

* How to copy an object that is accessible only by an interface that it implements?
* https://github.com/haoran119/c-cpp/blob/main/%E9%9D%A2%E8%AF%95%E6%80%BB%E7%BB%93%E4%B9%8BC-C++/README.md#deep-copy--shallow-copy

###### [How to Return a Smart Pointer AND Use Covariance - Fluent C++](https://www.fluentcpp.com/2017/09/12/how-to-return-a-smart-pointer-and-use-covariance/)

* The original problem Jonathan proposed a solution for was how to clone a concrete class when inheriting from multiple interfaces, all declaring the clone method, and all returning a smart pointer (in order to manage life cycle and produce exception safe code).
* That solution is simple and targeted to that situation. But here I want to expand on this and tackle the more general problem: in C++, it seems that we can have covariant return, or smart pointer return, but not both. Or can we?
* The problem: Covariant return type vs. smart pointers
    * C++ has support for covariant return type. That is, you can have the following code:
    ```c++
    struct Base {};
    struct Derived : Base {};

    struct Parent
    {
       virtual Base * foo();
    } ;

    struct Child : Parent
    {
       virtual Derived * foo() override ;
    } ;
    ```
    * Here, we expect the foo method from Child to return Base * for a successful overriding (and compilation!). With the covariant return type, we can actually replace Base * by any of its derived types. For example, Derived *.
    * This works for pointers, and for references… But the moment you try to use smart pointers:
    * … the compiler generates an error.
* Use cases
    * Simple hierarchy:
    * ![image](https://user-images.githubusercontent.com/34557994/206853537-b0fdfd99-536c-4eb4-8082-647e8cff83c9.png)
    * Multiple inheritance:
    * ![image](https://user-images.githubusercontent.com/34557994/206853550-d60e9d33-c273-442c-8701-4f77a037fc13.png)
    * Deep hierarchy:
    * ![image](https://user-images.githubusercontent.com/34557994/206853563-c7201cd9-2b9e-4595-b98c-fdfbade9db1c.png)
    * Diamond inheritance:
    * ![image](https://user-images.githubusercontent.com/34557994/206853578-f88a8c5d-4bec-495a-aa0a-90d9728b13d1.png)
* Preamble: Separation of concerns + private virtual function
    * Instead of having one clone member function handling everything, we will separate it into two member functions. In the following piece of code:
    ```c++
    class some_class
    {
    public:
       std::unique_ptr<some_class> clone() const
       {
          return std::unique_ptr<some_class>(this->clone_impl());
       }

    private:
       virtual some_class * clone_impl() const
       {
          return new some_class(*this) ;
       }
    };
    ```
* Simple Hierarchy: Covariance + Name hiding
    ```c++
    #include <memory>

    class cloneable
    {
    public:
       virtual ~cloneable() {}

       std::unique_ptr<cloneable> clone() const
       {
          return std::unique_ptr<cloneable>(this->clone_impl());
       }

    private:
       virtual cloneable * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    class concrete : public cloneable
    {
    public:
       std::unique_ptr<concrete> clone() const
       {
          return std::unique_ptr<concrete>(this->clone_impl());
       }

    private:
       virtual concrete * clone_impl() const override
       {
          return new concrete(*this);
       }
    };

    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();
       std::unique_ptr<concrete> cc = c->clone();

       cloneable * p = c.get();
       std::unique_ptr<cloneable> pp = p->clone();
    }
    ```
    * By separating the concerns, we were able to use covariance at each level of the hierarchy to produce a clone_impl member function returning the exact type of pointer we wanted.
    * And using a little (usually) annoying feature in C++, name hiding (i.e. when declaring a name in a derived class, this name hides all the symbols with the same name in the base class), we hide (not override) the clone() member function to return a smart pointer of the exact type we wanted.
* Simple Hierarchy, v2: Enter the CRTP
    * We will use it to declare methods with the correct derived prototypes in the CRTP base class, methods that will then be injected through inheritance into the derived class itself:
    ```c++
    #include <memory>

    class cloneable
    {
    public:
       virtual ~cloneable() {}

       std::unique_ptr<cloneable> clone() const
       {
          return std::unique_ptr<cloneable>(this->clone_impl());
       }

    private:
       virtual cloneable * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived, typename Base>
    class clone_inherit : public Base
    {
    public:
       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(*this);
       }
    };

    class concrete
       : public clone_inherit<concrete, cloneable>
    {
    public:
        concrete() = default;   // need to add it
        concrete(const clone_inherit<concrete, cloneable>&) {}  // need to add it
    };

    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();
       std::unique_ptr<concrete> cc = c->clone();

       cloneable * p = c.get();
       std::unique_ptr<cloneable> pp = p->clone();
    }
    ```
    * clone_inherit is a CRTP that knows its derived class, but also all its direct base class. It implements the covariant clone_impl() and hiding clone() member functions as usual, but they use casts to move through the hierarchy of types.
    * As you can see, the concrete class is now free of clutter.
    * This effectively adds a polymorphic and covariant clone() to a hierarchy of class.
* Multiple Inheritance: Variadic templates to the rescue
    * ![image](https://user-images.githubusercontent.com/34557994/210284273-bbab247a-88a8-422e-bb5b-1828c53a4dc1.png)
    * In our case, how can we extend our solution to support the case where the concrete class inherits from two bases classes that both provide the same clone feature?
    * The solution first needs the two base classes, foo and bar, to offer the clone/clone_impl member functions:
    * There’s a bit of boilerplate, here, but we’ll address it later. For now, we must solve the inheritance issue, and C++11 provides us with an easy solution: Variadic templates.
    * We only need to modify the clone_inherit CRTP to support it:
    * Last, but not least, we can use our classes with both covariance and smart pointers:
    ```c++
    #include <iostream>
    #include <memory>

    class foo
    {
    public:
       virtual ~foo() = default;

       std::unique_ptr<foo> clone() const
       {
          return std::unique_ptr<foo>(this->clone_impl());
       }

    private:
       virtual foo * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    class bar
    {
    public:
       virtual ~bar() = default;

       std::unique_ptr<bar> clone() const
       {
          return std::unique_ptr<bar>(this->clone_impl());
       }

    private:
       virtual bar * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived, typename ... Bases>
    class clone_inherit : public Bases...
    {
    public:
       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    class concrete
       : public clone_inherit<concrete, foo, bar>
    {
    };

    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();

       std::unique_ptr<concrete> cc = c->clone();

       foo * f = c.get();
       std::unique_ptr<foo> ff = f->clone();

       bar * b = c.get();
       std::unique_ptr<bar> bb = b->clone();
    }
    ```
* Multiple Inheritance v2: Specialization to the rescue
    * Now, let’s address the clutter: Both foo and bar offer the same “cloneable” feature. And in our case, both should be virtually destructible.
    * The solution is to specialize clone_inherit to handle the case when no base class is desired, provide the virtual destructors, and have foo and bar inherit from it:
    ```c++
    #include <iostream>
    #include <memory>

    template <typename Derived, typename ... Bases>
    class clone_inherit : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived>
    class clone_inherit<Derived>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    class foo
       : public clone_inherit<foo>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class bar
       : public clone_inherit<bar>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class concrete
       : public clone_inherit<concrete, foo, bar>
    {
    };

    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();

       std::unique_ptr<concrete> cc = c->clone();

       foo * f = c.get();
       std::unique_ptr<foo> ff = f->clone();

       bar * b = c.get();
       std::unique_ptr<bar> bb = b->clone();
    }
    ```
* Deep Hierarchy: Abstracting
    * Another complication of OO Hierarchies is that they can go deeper than two levels:
    * ![image](https://user-images.githubusercontent.com/34557994/210350969-26600e5c-758d-43b9-88eb-7e2069d8e31a.png)
    * The thing is, as Scott Meyers advised us, non-leaf classes are not supposed to be instantiable by themselves (More Effective C++, item 33).
    * In our case, the clone_impl method in the non-leaf class must then be pure virtual.
    * Our solution must thus support the choice of declaring clone_impl pure virtual, or implemented.
    * It starts to be is a lot of code, but this will enable the user to actually use the feature with no boilerplate at all, as demonstrated by the following code:
    * Again, we succeeded in not cluttering too much the user code, and make this pattern scalable.
    ```c++
    #include <iostream>
    #include <memory>

    template <typename T>
    class abstract_method
    {
    };

    // general: inheritance + clone_impl implemented
    template <typename Derived, typename ... Bases>
    class clone_inherit : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    // specialization: inheritance + clone_impl NOT implemented
    template <typename Derived, typename ... Bases>
    class clone_inherit<abstract_method<Derived>, Bases...> : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    // specialization: NO inheritance + clone_impl implemented
    template <typename Derived>
    class clone_inherit<Derived>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    // specialization: NO inheritance + clone_impl NOT implemented
    template <typename Derived>
    class clone_inherit<abstract_method<Derived>>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    class cloneable
       : public clone_inherit<abstract_method<cloneable>>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class abstracted
       : public clone_inherit<abstract_method<abstracted>, cloneable>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class concrete
       : public clone_inherit<concrete, abstracted>
    {
    };
    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();
       std::unique_ptr<concrete> cc = c->clone();

       abstracted * a = c.get();
       std::unique_ptr<abstracted> aa = a->clone();

       cloneable * p = c.get();
       std::unique_ptr<cloneable> pp = p->clone();
    }
    ```
* Diamond Inheritance: Virtual-ing
    * Yet another complication of OO Hierarchies is that we can have a diamond inheritance:
    * ![image](https://user-images.githubusercontent.com/34557994/210352742-f9225531-f3d2-4678-85ed-d6e2096375a0.png)
    * In C++, this means we have a choice to do: Is the base class inherited virtually, or not?
    * This choice must thus be provided by clone_inherit. The thing is, declaring a virtual inheritance is much more tricky because of the template parameter pack
    * Let’s write a class that will do the indirection:
    * This class actually applies the virtual inheritance to its base class T, which is exactly what we wanted. Now, all we need is to use this class to explicit our virtual inheritance need:
    * Again, we succeeded in not cluttering too much the user code, and make this pattern scalable.
    ```c++
    #include <iostream>
    #include <memory>

    template <typename T>
    class abstract_method
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    // general: inheritance + clone_impl implemented
    template <typename Derived, typename ... Bases>
    class clone_inherit : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    // specialization: inheritance + clone_impl NOT implemented
    template <typename Derived, typename ... Bases>
    class clone_inherit<abstract_method<Derived>, Bases...> : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    // specialization: NO inheritance + clone_impl implemented
    template <typename Derived>
    class clone_inherit<Derived>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    // specialization: NO inheritance + clone_impl NOT implemented
    template <typename Derived>
    class clone_inherit<abstract_method<Derived>>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    class cloneable
       : public clone_inherit<abstract_method<cloneable>>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename T>
    class virtual_inherit_from : virtual public T
    {
       using T::T;
    };

    ///////////////////////////////////////////////////////////////////////////////

    class foo
       : public clone_inherit<abstract_method<foo>, virtual_inherit_from<cloneable>>
    {
    };

    class bar
       : public clone_inherit<abstract_method<bar>, virtual_inherit_from<cloneable>>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class concrete
       : public clone_inherit<concrete, foo, bar>
    {
    };

    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();
       std::unique_ptr<concrete> cc = c->clone();

       foo * f = c.get();
       std::unique_ptr<foo> ff = c->clone();

       bar * b = c.get();
       std::unique_ptr<bar> bb = c->clone();

       cloneable * p = c.get();
       std::unique_ptr<cloneable> pp = p->clone();
    }
    ```
* The whole package
    ```c++
    #include <iostream>
    #include <memory>

    // The whole clone-ing code

    template <typename T>
    class abstract_method
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename T>
    class virtual_inherit_from : virtual public T
    {
       using T::T;
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived, typename ... Bases>
    class clone_inherit : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    protected:
       //         desirable, but impossible in C++17
       //         see: http://cplusplus.github.io/EWG/ewg-active.html#102
       // using typename... Bases::Bases;

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived, typename ... Bases>
    class clone_inherit<abstract_method<Derived>, Bases...> : public Bases...
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    protected:
       //         desirable, but impossible in C++17
       //         see: http://cplusplus.github.io/EWG/ewg-active.html#102
       // using typename... Bases::Bases;

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived>
    class clone_inherit<Derived>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const override
       {
          return new Derived(static_cast<const Derived & >(*this));
       }
    };

    ///////////////////////////////////////////////////////////////////////////////

    template <typename Derived>
    class clone_inherit<abstract_method<Derived>>
    {
    public:
       virtual ~clone_inherit() = default;

       std::unique_ptr<Derived> clone() const
       {
          return std::unique_ptr<Derived>(static_cast<Derived *>(this->clone_impl()));
       }

    private:
       virtual clone_inherit * clone_impl() const = 0;
    };

    // user code

    class cloneable
       : public clone_inherit<abstract_method<cloneable>>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class foo
       : public clone_inherit<abstract_method<foo>, virtual_inherit_from<cloneable>>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class bar
       : public clone_inherit<abstract_method<bar>, virtual_inherit_from<cloneable>>
    {
    };

    ///////////////////////////////////////////////////////////////////////////////

    class concrete
       : public clone_inherit<concrete, foo, bar>
    {
    };

    int main()
    {
       std::unique_ptr<concrete> c = std::make_unique<concrete>();
       std::unique_ptr<concrete> cc = c->clone();

       foo * f = c.get();
       std::unique_ptr<foo> ff = c->clone();

       bar * b = c.get();
       std::unique_ptr<bar> bb = c->clone();

       cloneable * p = c.get();
       std::unique_ptr<cloneable> pp = p->clone();
    }
    ```

## [General utilities library](https://en.cppreference.com/w/cpp/utility#General-purpose_utilities)

### Swap and type operations

* Defined in header \<utility>

#### [std::exchange](https://en.cppreference.com/w/cpp/utility/exchange)
    
* replaces the argument with a new value and returns its previous value (function template)
* Replaces the value of obj with new_value and returns the old value of obj.
* Notes
    * The std::exchange can be used when implementing move assignment operators and move constructors:
    ```c++
    struct S
    {
      int n;

      S(S&& other) noexcept : n{std::exchange(other.n, 0)}
      {}

      S& operator=(S&& other) noexcept 
      {
        if(this != &other)
            n = std::exchange(other.n, 0); // move n, while leaving zero in other.n
        return *this;
      }
    };
    ```
```c++
#include <iostream>
#include <utility>
#include <vector>
#include <iterator>
 
class stream
{
  public:
 
   using flags_type = int;
 
  public:
 
    flags_type flags() const
    { return flags_; }
 
    // Replaces flags_ by newf, and returns the old value.
    flags_type flags(flags_type newf)
    { return std::exchange(flags_, newf); }
 
  private:
 
    flags_type flags_ = 0;
};
 
void f() { std::cout << "f()"; }
 
int main()
{
   stream s;
 
   std::cout << s.flags() << '\n';
   std::cout << s.flags(12) << '\n';
   std::cout << s.flags() << "\n\n";
 
   std::vector<int> v;
 
   // Since the second template parameter has a default value, it is possible
   // to use a braced-init-list as second argument. The expression below
   // is equivalent to std::exchange(v, std::vector<int>{1,2,3,4});
 
   std::exchange(v, {1,2,3,4});
 
   std::copy(begin(v),end(v), std::ostream_iterator<int>(std::cout,", "));
 
   std::cout << "\n\n";
 
   void (*fun)();
 
   // the default value of template parameter also makes possible to use a
   // normal function as second argument. The expression below is equivalent to
   // std::exchange(fun, static_cast<void(*)()>(f))
   std::exchange(fun,f);
   fun();
 
   std::cout << "\n\nFibonacci sequence: ";
   for (int a{0}, b{1}; a < 100; a = std::exchange(b, a + b))
       std::cout << a << ", ";
   std::cout << "...\n";
}
/*
0
0
12
 
1, 2, 3, 4, 
 
f()
 
Fibonacci sequence: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...
*/
```

#### [std::forward](https://en.cppreference.com/w/cpp/utility/forward)

* forwards a function argument (function template)
* 1) Forwards lvalues as either lvalues or as rvalues, depending on T
* 2) Forwards rvalues as rvalues and prohibits forwarding of rvalues as lvalues

##### MISC

* [【C++11】 改成程序性能的方法--完美转发](https://mp.weixin.qq.com/s/3TPhTa4mNy8AOLMtjbGI6A)
    *  所谓的完美转发，实际上就是指在C++函数模板中，完全按照函数模板的参数类型将参数传递给函数模板中调用的另外一个参数。通俗点解释就是，如果一个参数不管是右值引用还是左值引用，函数调用时都不会改变参数的类型。C++11给我们提供了这样一个函数std::forward,它就是专门为完美转发而生的，实际使用时它会完全按照参数本来的类型进行转发，而不是改变。

#### [std::move](https://en.cppreference.com/w/cpp/utility/move)
	
* obtains an rvalue reference (function template)
* std::move is used to indicate that an object t may be "moved from", i.e. allowing the efficient transfer of resources from t to another object.
* In particular, std::move produces an [xvalue expression](https://en.cppreference.com/w/cpp/language/value_category) that identifies its argument t. It is exactly equivalent to a static_cast to an rvalue reference type.
* Return value
    * `static_cast<typename std::remove_reference<T>::type&&>(t)`
```c++
#include <iomanip>
#include <iostream>
#include <utility>
#include <vector>
#include <string>
 
int main()
{
    std::string str = "Salut";
    std::vector<std::string> v;
 
    // uses the push_back(const T&) overload, which means 
    // we'll incur the cost of copying str
    v.push_back(str);
    std::cout << "After copy, str is " << std::quoted(str) << '\n';
 
    // uses the rvalue reference push_back(T&&) overload, 
    // which means no strings will be copied; instead, the contents
    // of str will be moved into the vector.  This is less
    // expensive, but also means str might now be empty.
    v.push_back(std::move(str));
    std::cout << "After move, str is " << std::quoted(str) << '\n';
 
    std::cout << "The contents of the vector are { " << std::quoted(v[0])
                                             << ", " << std::quoted(v[1]) << " }\n";
}
/*
After copy, str is "Salut"
After move, str is ""
The contents of the vector are { "Salut", "Salut" }
*/
```

##### MISC

* [深入理解C++中的move和forward！](https://mp.weixin.qq.com/s/Vc1sz26ACKQNonSzA-cHKQ)
	* 导语 |  在C++11标准之前，C++中默认的传值类型均为Copy语义，即：不论是指针类型还是值类型，都将会在进行函数调用时被完整的复制一份！对于非指针而言，开销极其巨大！因此在C++11以后，引入了右值和Move语义，极大地提高了效率。本文介绍了在此场景下两个常用的标准库函数：move和forward。
	* 一、特性背景
		* （一）Copy语义简述
			* C++中默认为Copy语义，因此存在大量开销。
			* 除了我们显式构造的函数之外，我们在调用函数、将对象加入vector的时候，也创建了新的对象！
			* 并且这个对象不是通过构造函数创建的，事实上是通过复制构造函数创建的！
		* （二）临时值（右值）简述
			* Copy语义虽然用起来很方便，但是很多时候我们并不想将值（尤其是一些临时变量）Copy一遍再使用！
			* 注意：上面的函数在返回时，实际上编译器会对返回值进行优化，并不会先析构v，再在str_split 函数的调用栈中对整个v进行Copy。
			* 但是之前的C++的确是这么做的，因此会出现类似于下面的代码：
			* 即：将返回值也作为一个输入参数。
			* 上面编译器的优化有一个非常学术的名字：RVO (Return Value Optimization)，返回值优化。
			* 其实这里是可以优化的：
				* 临时变量其实最终都是要被回收的，如果能把临时变量的内容直接“移入”成员变量中，此时就不需要调用复制构造函数了！
			* 对于使用过Rust的开发者来说，这里他们是非常熟悉的。因为Rust丧心病狂的将所有赋值操作都默认定义为了Move语义！
	* 二、使用move函数
		* （一）move函数的基本使用
			* 可以看到，相比于Copy，我们直接使用了move函数将变量移入了函数中，此时是没有调用复制构造函数的！
			* 实际上，C++中的move函数只是做了类型转换，并不会真正的实现值的移动！
			* 因此，对于自定义的类来说，如果要实现真正意义上的 “移动”，还是要手动重载移动构造函数和移动复制函数。
			* 即：我们需要在自己的类中实现移动语义，避免深拷贝，充分利用右值引用和std::move的语言特性。
			* 实际上，通常情况下C++编译器会默认在用户自定义的class和struct中生成移动语义函数。
			* 但前提是：用户没有主动定义该类的拷贝构造等函数！
			* 同时也要注意到：使用一个已经被move过的函数是非常危险的事情！
		* （二）move语义下的析构函数
			* 对象被move了之后，仍然会在其离开作用域之后调用他的析构函数？
			* 这是因为：
				* 虽然将obj的资源给了a_obj ，但是obj并没有立刻析构，只有在obj离开了自己的作用域的时候才会析构；因此，如果继续使用str2的m_data变量，可能会发生意想不到的错误。
				* 也正因为如此，在自己实现移动构造函数的时候，需要将原对象中的值手动置为空，以防止同一片内存区域被多次释放！
			* 此外还需要注意：
				* 如果我们没有提供移动构造函数，只提供了拷贝构造函数，std::move()会失效但是不会发生错误，因为编译器找不到移动构造函数就去寻找拷贝构造函数，这也是拷贝构造函数的参数是const T&常量左值引用的原因！
				* c++11中的所有容器都实现了move语义，move只是转移了资源的控制权，本质上是将左值强制转化为右值使用，以用于移动拷贝或赋值，避免对含有资源的对象发生无谓的拷贝。
				* move对于拥有如内存、文件句柄等资源的成员的对象有效，如果是一些基本类型，如int和char[10]数组等，如果使用move，仍会发生拷贝（因为没有对应的移动构造函数），所以说move对含有资源的对象说更有意义。
			* 这里需要注意，在移动构造函数和移动赋值函数中，我们将当前待移动对象的资源赋值为了空（str._data=nullptr），这里就是我们手动实现了资源的移动！
			* 下面我们尝试修改两个地方，来导致报错：
				* 使用资源被move后的对象。
					* 因为此时obj中的内容已经为空了！
				* 在实现移动构造函数时不赋值为nullptr。
					* 此时再执行代码，整个程序会直接崩溃，因为：我们未将已经move掉的资源设置为空值，最终会导致这里的资源被释放两次！
	* 三、什么又是foward函数
		* 有了move函数之后，我们又遇到了一个新的问题：
		* 按照上面的写法，处理临时变量用右值引用T&&，处理普通变量用const引用const T&，我们需要分别建立两个函数，然后入参使用不同的类型，每个函数都要写两遍。
		* 那么能不能避免重复，将T &&类型和const T &类型合二为一呢？
		* 答案就是：forward函数，std::forward也被称为完美转发，即：保持原来的值属性不变：
			* 如果原来的值是左值，经std::forward处理后该值还是左值。
			* 如果原来的值是右值，经std::forward处理后它还是右值。
		* 这样一来，我们就可以使用forward函数对入参进行封装，从而保证了入参的统一性，从而可以实现一个方法处理两种类型！
		* 正因为如此，forward函数被大量用在了入参值类型情况不确定的C++模板中！
	* 四、move和forward函数的区别
		* 从上面的分析我们可以看出，基本上forward可以cover所有的需要move的场景，毕竟forward函数左右值通吃。
		* 那为什么还要使用move呢？原因主要有两点：
			* 首先，forward函数常用于模板函数这种入参情况不确定的场景中，在使用的时候必须要多带一个模板参数forward\<T>，代码略复杂。
			* 此外，明确只需要move临时值的情况下如果使用了forward，会导致代码意图不清晰，其他人看着理解起来比较费劲。
		* 实际上从实现的角度上来说，他们都可以被static_cast替代。
		* 注意：为什么不用static_cast呢？也是为了阅读和使用起来更方便。
	* 五、move和forward函数的实现
		* （一）C++11后加入的一些新规则
			* 引用折叠规则
				* 如果间接的创建一个引用的引用，则这些引用就会“折叠”，在所有情况下（除了一个例外），引用折叠成一个普通的左值引用类型。
				* 一种特殊情况下，引用会折叠成右值引用，即右值引用的右值引用：T&& &&。
			* 右值引用的特殊类型推断规则
				* 当将一个左值传递给一个参数是右值引用的函数，且此右值引用指向模板类型参数(T&&)时，编译器推断模板参数类型为实参的左值引用
			* 从上述两个规则可以得出结论：如果一个函数形参是一个指向模板类型的右值引用，则该参数可以被绑定到一个左值上。
			* 可以通过static_cast显式地将一个左值转换为一个右值
		* （二）move函数解析
			* 需要注意的是：std::move函数仅仅执行到右值类型的无条件转换；就其本身而言，它没有“move”任何东西。
		* （三）forward函数解析
	* 六、总结
		* 首先，std::move和std::forward本质都是转换：
			* std::move执行强制到右值的无条件转换。
			* std::forward只有在它的参数绑定到一个右值上的时候，才转换它的参数到一个右值。
			* std::move没有move任何东西，std::forward没有转发任何东西。
		* 整个类型转变的实现是在编译期完成的，在运行期，它们没有做任何事情。
		* 它们没有为移动或者复制产生需要执行的代码，一byte都没有；（换言之，我们需要通过重载移动相关操作函数来自己处理move语义）
		* 在使用场景方面：
			* 一般在模板元编程里面，由于入参的值类型不确定，因此对于forward使用比较多。
			* 在一般的函数中，如果可以确定传入的一定是右值（临时值），可以直接使用move函数，强调使用场景。
		* https://github.com/JasonkayZK/cpp-learn/tree/value
* [Modern C++ 最核心的变化是什么？](https://mp.weixin.qq.com/s/7l6JbX_QMry0DIM9mLUFgw)
	* https://www.zhihu.com/question/22111546/answer/30801982
	* 个人觉得最核心的变化是右值引用的引入，右值引用是  C++ 走向现代化的最重要一步。建议每一位 C++ 开发者都应该深入去了解并充分使用它。
	* 右值引用是 C++11 中最重要的新特性之一，它解决了 C++ 中大量的历史遗留问题，使 C++ 标准库的实现在多种场景下消除了不必要的额外开销（如 std::vector, std::string)，也使得另外一些标准库（如 std::unique_ptr, std::function）成为可能。即使你并不直接使用右值引用，也可以通过标准库，间接从这一新特性中受益。为了更好地理解标准库结合右值引用带来的优化，我们有必要了解一下右值引用的重大意义。
	* 右值引用的意义通常解释为两大作用：移动语义和完美转发。本文主要讨论移动语义。
* [F.48: Don’t return std::move(local)](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#f48-dont-return-stdmovelocal)
	* `Reason` With guaranteed copy elision, it is now almost always a pessimization to expressly use std::move in a return statement.
	* `Example, bad`
    ```c++
    S f()
    {
      S result;
      return std::move(result);
    }
    ```
	* `Example, good`
    ```c++
    S f()
    {
      S result;
      return result;
    }
    ```
	* `Enforcement` This should be enforced by tooling by checking the return expression .
```c++
#include <iostream>
#include <vector>
  
void f(std::vector<int>& v)
{
    std::vector<int> result = {1, 2};
    v = std::move(result);
    
    return;
}

std::vector<int> f1()
{
    std::vector<int> result = {1, 2};
    return std::move(result);   
    // warning: moving a local object in a return statement prevents copy elision [-Wpessimizing-move]
    // note: remove 'std::move' call
}

int main()
{
    std::vector<int> z{};
    
    f(z);

    for (auto it : z)
        std::cout << it << " "; // 1 2     
 
    return 0;
}
```

#### [std::as_const](https://en.cppreference.com/w/cpp/utility/as_const)
    
* obtains a reference to const to its argument (function template)
* 1) Forms lvalue reference to const type of t.
* 2) const rvalue reference overload is deleted to disallow rvalue arguments.
```c++
#include <string>
#include <cassert>
#include <utility>
#include <type_traits>
 
int main()
{
    std::string mutableString = "Hello World!";
    auto&& constRef = std::as_const(mutableString);
 
//  mutableString.clear(); // OK
//  constRef.clear(); // error: 'constRef' is 'const' qualified,
                      //        but 'clear' is not marked const
 
    assert( &constRef == &mutableString );
    assert( &std::as_const( mutableString ) == &mutableString );
 
    using ExprType = std::remove_reference_t<decltype(std::as_const(mutableString))>;
 
    static_assert(std::is_same_v<std::remove_const_t<ExprType>, std::string>,
            "ExprType should be some kind of string." );
    static_assert(!std::is_same_v<ExprType, std::string>,
            "ExprType shouldn't be a mutable string." );
}
```

### Pairs and tuples

* Defined in header `<utility>`

| [pair](https://en.cppreference.com/w/cpp/utility/pair) | implements binary tuple, i.e. a pair of values(class template) |
| - | - |
| [tuple](https://en.cppreference.com/w/cpp/utility/tuple) | implements fixed size container, which holds elements of possibly different types(class template) |

#### [std::pair](https://en.cppreference.com/w/cpp/utility/pair)

* Defined in header `<utility>`
* std::pair is a class template that provides a way to store two heterogeneous objects as a single unit. A pair is a specific case of a std::tuple with two elements.
* If neither T1 nor T2 is a possibly cv-qualified class type with non-trivial destructor, or array thereof, the destructor of pair is trivial.

##### Template parameters

* T1, T2 - the types of the elements that the pair stores.

##### Member types

|Member type|Definition|
|-|-|
|first_type|T1|
|second_type|T2|

* How to implement `first_type`?
```c++
template<class T1, class T2>
struct pair {
    using first_type = T1;
    using second_type = T2;

    T1 first;
    T2 second;

    // ...
};
```

##### Member objects

|Member name|Type|
|-|-|
|first|T1|
|second|T2|

##### Non-member functions

###### [std::make_pair](https://en.cppreference.com/w/cpp/utility/pair/make_pair)

* creates a pair object of type, defined by the argument types(function template)

##### MISC

* [Pair in C++ Standard Template Library (STL) - GeeksforGeeks](https://www.geeksforgeeks.org/pair-in-cpp-stl/)
* [c++ - Check if pair is empty or uninitialized - Stack Overflow](https://stackoverflow.com/questions/57109084/check-if-pair-is-empty-or-uninitialized)
```c++
#include <optional>

std::optional<std::pair<int, int>> res;

if (res) // the pair is initialized and usable
   doStuff(*res);
else // ... it's not, hence initialize it
   res = std::make_pair(42, 43);
```

#### [std::tuple](https://en.cppreference.com/w/cpp/utility/tuple)

* Defined in header `<tuple>`
* Class template std::tuple is a `fixed-size` collection of `heterogeneous` values. It is a generalization of `std::pair`.
* If `std::is_trivially_destructible<Ti>::value` is `true` for every Ti in Types, the destructor of tuple is trivial.
* Example
```c++
#include <tuple>
#include <iostream>
#include <string>
#include <stdexcept>
 
std::tuple<double, char, std::string> get_student(int id)
{
    if (id == 0) return std::make_tuple(3.8, 'A', "Lisa Simpson");
    if (id == 1) return std::make_tuple(2.9, 'C', "Milhouse Van Houten");
    if (id == 2) return std::make_tuple(1.7, 'D', "Ralph Wiggum");
    throw std::invalid_argument("id");
}
 
int main()
{
    auto student0 = get_student(0);
    std::cout << "ID: 0, "
              << "GPA: " << std::get<0>(student0) << ", "
              << "grade: " << std::get<1>(student0) << ", "
              << "name: " << std::get<2>(student0) << '\n';
 
    double gpa1;
    char grade1;
    std::string name1;
    std::tie(gpa1, grade1, name1) = get_student(1);
    std::cout << "ID: 1, "
              << "GPA: " << gpa1 << ", "
              << "grade: " << grade1 << ", "
              << "name: " << name1 << '\n';
 
    // C++17 structured binding:
    auto [ gpa2, grade2, name2 ] = get_student(2);
    std::cout << "ID: 2, "
              << "GPA: " << gpa2 << ", "
              << "grade: " << grade2 << ", "
              << "name: " << name2 << '\n';
}
```

##### Non-member functions

###### [std::make_tuple](https://en.cppreference.com/w/cpp/utility/tuple/make_tuple)

* creates a tuple object of the type defined by the argument types(function template)

###### [std::tie](https://en.cppreference.com/w/cpp/utility/tuple/tie)

* creates a tuple of lvalue references or unpacks a tuple into individual objects (function template)
* Creates a tuple of lvalue references to its arguments or instances of std::ignore.
* Notes
    * std::tie may be used to unpack a std::pair because std::tuple has a converting assignment from pairs

###### [std::get(std::tuple)](https://en.cppreference.com/w/cpp/utility/tuple/get)

* tuple accesses specified element (function template)
* 1-4) Extracts the Ith element from the tuple. I must be an integer value in `[0, sizeof...(Types))`.
* 5-8) Extracts the element of the tuple t whose type is T. Fails to compile unless the tuple has exactly one element of that type.
* Parameters
    * t	-	tuple whose contents to extract
* Return value
    * A `reference` to the selected element of t.
* Example
```c++
#include <iostream>
#include <string>
#include <tuple>
 
int main()
{
    auto t = std::make_tuple(1, "Foo", 3.14);
    
    std::get<0>(t) = -1;
    
    // index-based access
    std::cout << "(" << std::get<0>(t) << ", " << std::get<1>(t)
              << ", " << std::get<2>(t) << ")\n";
    // type-based access (C++14 or later)
    std::cout << "(" << std::get<int>(t) << ", " << std::get<const char*>(t)
              << ", " << std::get<double>(t) << ")\n";
    // Note: std::tie and structured binding may also be used to decompose a tuple
}
/*
(-1, Foo, 3.14)
(-1, Foo, 3.14)
*/
```

##### Helper classes

* [std::ignore - cppreference.com](https://en.cppreference.com/w/cpp/utility/tuple/ignore)
    * placeholder to skip an element when unpacking a tuple using tie (constant)
    * An object of unspecified type such that any value can be assigned to it with no effect. Intended for use with std::tie when unpacking a std::tuple, as a placeholder for the arguments that are not used.
    * While the behavior of std::ignore outside of std::tie is not formally specified, some code guides recommend using std::ignore to avoid warnings from unused return values of [[nodiscard]] functions.
```c++
#include <iostream>
#include <string>
#include <set>
#include <tuple>
 
[[nodiscard]] int dontIgnoreMe()
{
    return 42;
}
 
int main()
{
    std::ignore = dontIgnoreMe();
 
    std::set<std::string> set_of_str;
    bool inserted = false;
    std::tie(std::ignore, inserted) = set_of_str.insert("Test");
    if (inserted) {
        std::cout << "Value was inserted successfully\n";
    }
}
/*
Value was inserted successfully
*/
```

##### MISC

* [Tuples in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/tuples-in-c/)
* [【C++11】让程序更简洁—tuple元组](https://mp.weixin.qq.com/s/TiU3L9vkyD-gSr5UD3jAGw)
	* tuple元组是一个泛化的std::pair，可以在一个数据结构中保存不同类型的变量，这一点和C#里面的tupe类似，由此可见，C++也在逐渐吸收其他编程语言的优良特性，加入到自己的势力范围里面来。

### Sum types and type erased wrappers

#### [std::optional](https://en.cppreference.com/w/cpp/utility/optional)

* Defined in header \<optional>
* a wrapper that may or may not hold an object (class template)
* template\< class T > class optional; (since C++17)
* The class template std::optional manages an optional contained value, i.e. a value that may or may not be present.
* A common use case for optional is the return value of a function that may fail. As opposed to other approaches, such as std::pair\<T,bool>, optional handles expensive-to-construct objects well and is more readable, as the intent is expressed explicitly.
* Any instance of optional\<T> at any given point in time either contains a value or does not contain a value.
* If an optional\<T> contains a value, the value is guaranteed to be allocated as part of the optional object footprint, i.e. no dynamic memory allocation ever takes place. Thus, an optional object models an object, not a pointer, even though operator*() and operator->() are defined.
* When an object of type optional\<T> is contextually converted to bool, the conversion returns true if the object contains a value and false if it does not contain a value.
* The optional object contains a value in the following conditions:
* The object is initialized with/assigned from a value of type T or another optional that contains a value.
* The object does not contain a value in the following conditions:
* The object is default-initialized.
* The object is initialized with/assigned from a value of type std::nullopt_t or an optional object that does not contain a value.
* The member function reset() is called.
* There are no optional references; a program is ill-formed if it instantiates an optional with a reference type. Alternatively, an optional of a std::reference_wrapper of type T may be used to hold a reference. In addition, a program is ill-formed if it instantiates an optional with the (possibly cv-qualified) tag types std::nullopt_t or std::in_place_t.
```c++
#include <string>
#include <functional>
#include <iostream>
#include <optional>
 
// optional can be used as the return type of a factory that may fail
std::optional<std::string> create(bool b) {
    if (b)
        return "Godzilla";
    return {};
}
 
// std::nullopt can be used to create any (empty) std::optional
auto create2(bool b) {
    return b ? std::optional<std::string>{"Godzilla"} : std::nullopt;
}
 
// std::reference_wrapper may be used to return a reference
auto create_ref(bool b) {
    static std::string value = "Godzilla";
    return b ? std::optional<std::reference_wrapper<std::string>>{value}
             : std::nullopt;
}
 
int main()
{
    std::cout << "create(false) returned "
              << create(false).value_or("empty") << '\n';
 
    // optional-returning factory functions are usable as conditions of while and if
    if (auto str = create2(true)) {
        std::cout << "create2(true) returned " << *str << '\n';
    }
 
    if (auto str = create_ref(true)) {
        // using get() to access the reference_wrapper's value
        std::cout << "create_ref(true) returned " << str->get() << '\n';
        str->get() = "Mothra";
        std::cout << "modifying it changed it to " << str->get() << '\n';
    }
}
```

##### Member functions

###### Observers

* [std::optional\<T>::operator->, std::optional\<T>::operator* - cppreference.com](https://en.cppreference.com/w/cpp/utility/optional/operator*)
    * accesses the contained value (public member function)
    * The behavior is undefined if *this does not contain a value.
    * Return value
        * Pointer or reference to the contained value.
    * Notes
        * This operator does not check whether the optional contains a value! You can do so manually by using has_value() or simply operator bool(). Alternatively, if checked access is needed, value() or value_or() may be used.
```c++
#include <optional>
#include <iostream>
#include <string>
 
int main()
{
    using namespace std::string_literals;
 
    std::optional<int> opt1 = 1;
    std::cout<< "opt1: "  << *opt1 << '\n';
 
    *opt1 = 2;
    std::cout<< "opt1: "  << *opt1 << '\n';
 
    std::optional<std::string> opt2 = "abc"s;
    std::cout<< "opt2: " << *opt2 << " size: " << opt2->size() << '\n';
 
    // You can "take" the contained value by calling operator* on a rvalue to optional
 
    auto taken = *std::move(opt2);
    std::cout << "taken: " << taken << " opt2: " << *opt2 << "size: " << opt2->size()  << '\n';
}
/*
opt1: 1
opt1: 2
opt2: abc size: 3
taken: abc opt2: size: 0
*/
```
* [std::optional\<T>::operator bool, std::optional\<T>::has_value - cppreference.com](https://en.cppreference.com/w/cpp/utility/optional/operator_bool)
    * checks whether the object contains a value (public member function)
    * Checks whether *this contains a value.
```c++
#include <optional>
#include <iostream>
 
int main()
{
    std::cout << std::boolalpha;
 
    std::optional<int> opt;
    std::cout << opt.has_value() << '\n';
 
    opt = 43;
    if (opt)
        std::cout << "value set to " << opt.value() << '\n';
    else
        std::cout << "value not set\n";
 
    opt.reset();
    if (opt.has_value())
        std::cout << "value still set to " << opt.value() << '\n';
    else
        std::cout << "value no longer set\n";
}
/*
false
value set to 43
value no longer set
*/
```
* [std::optional\<T>::value - cppreference.com](https://en.cppreference.com/w/cpp/utility/optional/value)
    * returns the contained value (public member function)	
    * If *this contains a value, returns a reference to the contained value.
    * Otherwise, throws a std::bad_optional_access exception.
    * Notes
        * The dereference operator operator*() does not check if this optional contains a value, which may be more efficient than value().
```c++
#include <optional>
#include <iostream>
int main()
{
    std::optional<int> opt = {};
 
    try {
        [[maybe_unused]] int n = opt.value();
    } catch(const std::bad_optional_access& e) {
        std::cout << e.what() << '\n';
    }
    try {
        opt.value() = 42;
    } catch(const std::bad_optional_access& e) {
        std::cout << e.what() << '\n';
    }
 
    opt = 43;
    std::cout << *opt << '\n';
 
    opt.value() = 44;
    std::cout << opt.value() << '\n';
}
/*
bad optional access
bad optional access
43
44
*/
```
* [std::optional\<T>::value_or - cppreference.com](https://en.cppreference.com/w/cpp/utility/optional/value_or)
    * returns the contained value if available, another value otherwise (public member function)
    * Returns the contained value if *this has a value, otherwise returns default_value.
        * 1) Equivalent to bool(*this) ? **this : static_cast\<T>(std::forward\<U>(default_value))
        * 2) Equivalent to bool(*this) ? std::move(**this) : static_cast\<T>(std::forward\<U>(default_value))
    * Return value
        * The current value if *this has a value, or default_value otherwise.
    * Exceptions
        * Any exception thrown by the selected constructor of the return value T.
```c++
#include <optional>
#include <iostream>
#include <cstdlib>
 
std::optional<const char*> maybe_getenv(const char* n)
{
    if(const char* x = std::getenv(n))
       return x;
    else
       return {};
}
int main()
{
     std::cout << maybe_getenv("MYPWD").value_or("(none)") << '\n';
}
/*
(none)
*/
```

##### Non-member functions

* [std::make_optional - cppreference.com](https://en.cppreference.com/w/cpp/utility/optional/make_optional)
    * creates an optional object
```c++
#include <optional>
#include <iostream>
#include <iomanip>
#include <vector>
#include <string>
 
int main()
{
    auto op1 = std::make_optional<std::vector<char>>({'a','b','c'});
    std::cout << "op1: ";
    for (char c: op1.value()){
        std::cout << c << ",";
    }
    auto op2 = std::make_optional<std::vector<int>>(5, 2);
    std::cout << "\nop2: ";
    for (int i: *op2){
        std::cout << i << ",";
    }
    std::string str{"hello world"};
    auto op3 = std::make_optional<std::string>(std::move(str));
    std::cout << "\nop3: " << quoted(op3.value_or("empty value")) << '\n';
    std::cout << "str: " << std::quoted(str) << '\n';
}
/*
op1: a,b,c,
op2: 2,2,2,2,2,
op3: "hello world"
str: ""
*/
```

##### Helpers

* [std::nullopt - cppreference.com](https://en.cppreference.com/w/cpp/utility/optional/nullopt)
    * an object of type nullopt_t (constant)
    * std::nullopt is a constant of type std::nullopt_t that is used to indicate optional type with uninitialized state.

##### MISC

* [optional Class | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/standard-library/optional-class?view=msvc-170)
* [std::optional: How, when, and why - C++ Team Blog](https://devblogs.microsoft.com/cppblog/stdoptional-how-when-and-why/)
	* optional is mandatory
		* optional is particularly well-suited to the delayed initialization problem because it is itself an instance of delayed initialization. The contained T may be initialized at construction, or sometime later, or never. Any contained T must be destroyed when the optional is destroyed. The designers of optional have already answered most of the questions that arise in this context.
	* Conclusions
		* Any time you need a tool to express “value-or-not-value”, or “possibly an answer”, or “object with delayed initialization”, you should reach into your toolbox for std::optional. Using a vocabulary type for these cases raises the level of abstraction, making it easier for others to understand what your code is doing. The declarations optional/<T/> f(); and void g(optional/<T/>); express intent more clearly and concisely than do pair/<T, bool> f(); or void g(T t, bool is_valid);. Just as is the case with words, adding to our vocabulary of types increases our capacity to describe complex problems simply – it makes us more efficient.
* [C++17常用新特性(十四)---std::optional](https://mp.weixin.qq.com/s/q_hSZmY4vwGBu7P-54ZdEw)
	* C++17提供了std::optional模板帮助我们解决实际编码中的问题，如实际编程时需要返回、传递或者使用一个对象，但是这个对象可能存在或者不存在值。如果要在编码过程中处理这种情况，就要写很多的代码对这些异常情况进行处理。C++17后std::optional<>提供了此类问题的一种类型安全的解决方案。

#### [std::any](https://en.cppreference.com/w/cpp/utility/any)

* Defined in header \<any>
* Objects that hold instances of any CopyConstructible type. (class)
* The class any describes a type-safe container for single values of any copy constructible type.
    * 1) An object of class any stores an instance of any type that satisfies the constructor requirements or is empty, and this is referred to as the state of the class any object. The stored instance is called the contained object. Two states are equivalent if they are either both empty or if both are not empty and if the contained objects are equivalent.
    * 2) The non-member any_cast functions provide type-safe access to the contained object.
* Implementations are encouraged to avoid dynamic allocations for small objects, but such an optimization may only be applied to types for which std::is_nothrow_move_constructible returns true.
* [C++17常用新特性(十三)---std::any](https://mp.weixin.qq.com/s/qzm_hYj7JEr0AOpxQkDm4g)

### [Function objects](https://en.cppreference.com/w/cpp/utility/functional)

* A function object is any object for which the function call operator is defined. C++ provides many built-in function objects as well as support for creation and manipulation of new function objects.

#
Function wrappers

* std::function provides support for storing arbitrary function objects.
* [std::function - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/function)
	* wraps callable object of any copy constructible type with specified function call signature (class template)
	* Class template std::function is a general-purpose polymorphic function wrapper. Instances of std::function can store, copy, and invoke any CopyConstructible Callable target -- functions, lambda expressions, bind expressions, or other function objects, as well as pointers to member functions and pointers to data members.
	* The stored callable object is called the target of std::function. If a std::function contains no target, it is called empty. Invoking the target of an empty std::function results in std::bad_function_call exception being thrown.
	* std::function satisfies the requirements of CopyConstructible and CopyAssignable.
* [function - C++ Reference](https://www.cplusplus.com/reference/functional/function/)
	* Function wrapper
		* Class that can wrap any kind of callable element (such as functions and function objects) into a copyable object, and whose type depends solely on its call signature (and not on the callable element type itself).
		* An object of a function class instantiation can wrap any of the following kinds of callable objects: a function, a function pointer, a pointer to member, or any kind of function object (i.e., an object whose class defines operator(), including closures).
		* A decay copy of the wrapped callable object is stored internally by the object, which becomes the function's target. The specific type of this target callable object is not needed in order to instantiate the function wrapper class; only its call signature.
		* The function object can be copied and moved around, and can be used to directly invoke the callable object with the specified call signature (see member operator()).
		* function objects can also be in a state with no target callable object. In this case they are known as empty functions, and calling them throws a bad_function_call exception.
* [C++ Library - \<functional>](https://www.tutorialspoint.com/cpp_standard_library/functional.htm)
* [C++ std::function技术浅谈](https://mp.weixin.qq.com/s/v1fz4YVJftuaLxYuJBRLPg)
	* https://blog.csdn.net/xiangbaohui/article/details/106741654
	* std::function是一个函数对象的包装器，std::function的实例可以存储，复制和调用任何可调用的目标，包括：
		* 函数。
		* lamada表达式。
		* 绑定表达式或其他函数对象。
		* 指向成员函数和指向数据成员的指针。
	* 当std::function对象没有初始化任何实际的可调用元素，调用std::function对象将抛出std::bad_function_call异常。
* [为什么C++中有函数指针还需要std::function？](https://mp.weixin.qq.com/s/gl47FGdsBM5lOSSJgcObPQ)
	* 我们将这个结构体命名为closure，注意看，这个结构中有两部分：
		* 一个指向代码的指针变量
		* 一个保存数据的变量
	* 即，closure既包含了一段代码也包含了这段代码使用的数据，这里的数据也被称为context，即上下文，或者environment，即环境，不管怎么称呼，其实就是函数运行依赖的数据
	* 而这也正是C++中std::function的目的所在。
	* 单纯的函数指针并没有捕捉上下文的能力，这里的上下文就是指代码依赖的数据，你不得不自己动手构造出一个结构体用来存储代码依赖的上下文。
	* 在C++中你没有办法单纯的利用函数指针指向对象的成员函数，就是因为函数指针没有办法捕捉this(指向对象的指针)这个上下文。
	* std::function的作用本质上和我们刚才定义的结构体区别不大。
	* 利用std::function你不但可以保存一段代码，同时也可以保存必要的上下文，然后在合适的地方基于上下文调用这段代码。
	* 同时std::function也更加通用，你可以用其存储任何可以被调用的对象(callable object)，只要有正确的函数签名即可。

#
Partial function application

* std::bind_front and std::bind provide support for [partial function application](https://en.wikipedia.org/wiki/Partial_application), i.e. binding arguments to functions to produce new functions.
* [std::bind - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/bind)
	* binds one or more arguments to a function object (function template)
	* The function template bind generates a forwarding call wrapper for f. Calling this wrapper is equivalent to invoking f with some of its arguments bound to args.
* [Bind Function and Placeholders in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/bind-function-placeholders-c/)
	* Sometimes we need to manipulate the operation of a function according to the need, i.e changing some arguments to default, etc. Predefining a function to have default arguments restricts the versatility of a function and forces us to use the default arguments and that too with similar values each time. From C++11 onwards, the introduction of the bind function has made this task easier. 
	* How does bind() work? 
		* Bind function with the help of placeholders helps to manipulate the position and number of values to be used by the function and modifies the function according to the desired output. 
	* What are placeholders? 
		* Placeholders are namespaces that direct the position of a value in a function. They are represented by _1, _2, _3...
```c++
// C++ code to demonstrate bind() and
// placeholders
#include <iostream>
#include <functional> // for bind()
using namespace std;

// for placeholders
using namespace std::placeholders;

// Driver function to demonstrate bind()
void func(int a, int b, int c)
{
    cout << (a - b - c) << endl;
}

int main()
{
    // for placeholders
    using namespace std::placeholders;

    // Use of bind() to bind the function
    // _1 is for first parameter and assigned
    // to 'a' in above declaration.
    // 2 is assigned to b
    // 3 is assigned to c
    auto fn1 = bind(func, _1, 2, 3);

    // 2 is assigned to a.
    // _1 is for first parameter and assigned
    // to 'b' in above declaration.
    // 3 is assigned to c.
    auto fn2 = bind(func, 2, _1, 3);

    // calling of modified functions
    fn1(10);
    fn2(10);

    return 0;
}
/*
5
-11
*/
```
* [【C++11】让程序更简洁—std::bind绑定器](https://mp.weixin.qq.com/s/z2rG7n7sViBosGuzFB3paQ)
	* 在上一期中，介绍了std::function，本节将和大家说一下bind绑定器，它可以将调用对象与调用参数一起绑定，然后将绑定的结果保存在std::function中，在后面我们需要使用的时候在执行函数功能。主要包含两个方面：
		* 将调用对象和参数绑定成一个仿函数
		* 将多元调用对象转成一元可用对象，只绑定部分参数；(多元：参数个数为n，n>1)
	* std::bind的基本用法
	* std::bind的占位符
	* std::bind和std::function配合使用
* [std::placeholders::_1, std::placeholders::_2, ..., std::placeholders::_N - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/placeholders)
	* placeholders for the unbound arguments in a std::bind expression (constant)
	* The std::placeholders namespace contains the placeholder objects [_1, ..., _N] where N is an implementation defined maximum number.
	* When used as an argument in a std::bind expression, the placeholder objects are stored in the generated function object, and when that function object is invoked with unbound arguments, each placeholder _N is replaced by the corresponding Nth unbound argument.

#
Negators

* std::not_fn creates a function object that negates the result of the callable object passed to it.
* [std::not_fn - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/not_fn)
	* Defined in header \<functional>
	* Creates a function object that returns the complement of the result of the function object it holds (function template)
	* Creates a forwarding call wrapper that returns the negation of the callable object it holds.
	* [\<functional> functions | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/standard-library/functional-functions?view=msvc-170#not_fn)
		* The not_fn function template takes a callable object and returns a callable object. When the returned callable object is later invoked with some arguments, it passes them to the original callable object, and logically negates the result. It preserves the const qualification and value category behavior of the wrapped callable object. not_fn is new in C++17, and replaces the deprecated std::not1, std::not2, std::unary_negate, and std::binary_negate.

#
Reference wrappers

* Reference wrappers allow reference arguments to be stored in copyable function objects
* [std::ref, std::cref - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/ref)
	* creates a std::reference_wrapper with a type deduced from its argument (function template)
	* Function templates ref and cref are helper functions that generate an object of type std::reference_wrapper, using template argument deduction to determine the template argument of the result.
	* T may be an incomplete type. (since C++20)
```c++
#include <functional>
#include <iostream>
 
void f(int& n1, int& n2, const int& n3)
{
    std::cout << "In function: " << n1 << ' ' << n2 << ' ' << n3 << '\n';
    ++n1; // increments the copy of n1 stored in the function object
    ++n2; // increments the main()'s n2
    // ++n3; // compile error
}
 
int main()
{
    int n1 = 1, n2 = 2, n3 = 3;
    std::function<void()> bound_f = std::bind(f, n1, std::ref(n2), std::cref(n3));
    n1 = 10;
    n2 = 11;
    n3 = 12;
    std::cout << "Before function: " << n1 << ' ' << n2 << ' ' << n3 << '\n';
    bound_f();
    std::cout << "After function: " << n1 << ' ' << n2 << ' ' << n3 << '\n';
}
/*
Before function: 10 11 12
In function: 1 11 12
After function: 10 12 12
*/
```

#
Operator function objects

* [std::multiplies - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/multiplies)
	* function object implementing x * y (class template)
	* Function object for performing multiplication. Effectively calls operator* on two instances of type T.
* [std::modulus - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/modulus)
	* function object implementing x % y (class template)
	* Function object for computing remainders of divisions. Implements operator% for type T.
* [std::greater - cppreference.com](https://en.cppreference.com/w/cpp/utility/functional/greater)
	* function object implementing x > y (class template)

## [Strings library](https://en.cppreference.com/w/cpp/string)

* The C++ strings library includes support for three general types of strings:
	* std::basic_string - a templated class designed to manipulate strings of any character type.
	* std::basic_string_view (C++17) - a lightweight non-owning read-only view into a subsequence of a string.
	* Null-terminated strings - arrays of characters terminated by a special null character.

### [std::basic_string](https://en.cppreference.com/w/cpp/string/basic_string) 

* Defined in header \<string>
```c++
template<
    class CharT,
    class Traits = std::char_traits<CharT>,
    class Allocator = std::allocator<CharT>
> class basic_string;   (1)	

namespace pmr {
    template <class CharT, class Traits = std::char_traits<CharT>>
    using basic_string = std::basic_string< CharT, Traits,
                                            std::pmr::polymorphic_allocator<CharT> >;
}   (2)	(since C++17)
```
* The class template basic_string stores and manipulates sequences of `char`-like objects, which are non-array objects of trivial standard-layout type. The class is dependent neither on the character type nor on the nature of operations on that type. The definitions of the operations are supplied via the Traits template parameter - a specialization of `std::char_traits` or a compatible traits class. Traits::char_type and CharT must name the same type; otherwise the program is ill-formed.
* The elements of a basic_string are stored contiguously, that is, for a basic_string s, `&*(s.begin() + n) == &*s.begin() + n` for any n in `[0, s.size())`, or, equivalently, a pointer to `s[0]` can be passed to functions that expect a pointer to the first element of a `null-terminated CharT[] array`.
* std::basic_string satisfies the requirements of AllocatorAwareContainer, SequenceContainer `and ContiguousContainer (since C++17)`
* `Member functions of std::basic_string are constexpr: it is possible to create and use std::string objects in the evaluation of a constant expression. (since C++20)`
* `However, std::string objects generally cannot be constexpr, because any dynamically allocated storage must be released in the same evaluation of constant expression. (since C++20)`
* Template parameters
    * `CharT`	-	character type
    * `Traits`	-	traits class specifying the operations on the character type
    * `Allocator`	-	Allocator type used to allocate internal storage
```c++
#include <iostream>
#include <string>
 
int main()
{
    using namespace std::literals;
 
    // Creating a string from const char*
    std::string str1 = "hello";
 
    // Creating a string using string literal
    auto str2 = "world"s;
 
    // Concatenating strings
    std::string str3 = str1 + " " + str2;
 
    // Print out the result
    std::cout << str3 << '\n';
 
    std::string::size_type pos = str3.find(" ");
    str1 = str3.substr(pos + 1); // the part after the space
    str2 = str3.substr(0, pos);  // the part till the space
 
    std::cout << str1 << ' ' << str2 << '\n';
 
    // Accessing an element using subscript operator[]
    std::cout << str1[0] << '\n';
    str1[0] = 'W';
    std::cout << str1 << '\n';
}
/*
hello world
world hello
w
World
*/
```

#### Member functions

##### [std::basic_string<CharT,Traits,Allocator>::basic_string](https://en.cppreference.com/w/cpp/string/basic_string/basic_string)

* constructs a basic_string (public member function)
* Constructs new string from a variety of data sources and optionally using user supplied allocator alloc.
* Notes
    * Initialization with a string literal that contains embedded '\0' characters uses the overload (5), which stops at the first null character. This can be avoided by specifying a different constructor or by using operator""s:
```c++
std::string s1 = "ab\0\0cd";   // s1 contains "ab"
std::string s2{"ab\0\0cd", 6}; // s2 contains "ab\0\0cd"
std::string s3 = "ab\0\0cd"s;  // s3 contains "ab\0\0cd"
```
* Example
```c++
#include <iostream>
#include <iomanip>
#include <cassert>
#include <iterator>
#include <string>
#include <cctype>
 
int main()
{
  {
    std::cout << "1) string(); ";
    std::string s;
    assert(s.empty() && (s.length() == 0) && (s.size() == 0));
    std::cout << "s.capacity(): " << s.capacity() << '\n'; // unspecified
  }
 
  {
    std::cout << "2) string(size_type count, charT ch): ";
    std::string s(4, '=');
    std::cout << std::quoted(s) << '\n'; // "===="
  }
 
  {
    std::cout << "3) string(const string& other, size_type pos, size_type count): ";
    std::string const other("Exemplary");
    std::string s(other, 0, other.length()-1);
    std::cout << quoted(s) << '\n'; // "Exemplar"
  }
 
  {
    std::cout << "4) string(const string& other, size_type pos): ";
    std::string const other("Mutatis Mutandis");
    std::string s(other, 8);
    std::cout << quoted(s) << '\n'; // "Mutandis", i.e. [8, 16)
  }
 
  {
    std::cout << "5) string(charT const* s, size_type count): ";
    std::string s("C-style string", 7);
    std::cout << quoted(s) << '\n'; // "C-style", i.e. [0, 7)
  }
 
  {
    std::cout << "6) string(charT const* s): ";
    std::string s("C-style\0string");
    std::cout << quoted(s) << '\n'; // "C-style"
  }
 
  {
    std::cout << "7) string(InputIt first, InputIt last): ";
    char mutable_c_str[] = "another C-style string";
    std::string s(std::begin(mutable_c_str)+8, std::end(mutable_c_str)-1);
    std::cout << quoted(s) << '\n'; // "C-style string"
  }
 
  {
    std::cout << "8) string(string&): ";
    std::string const other("Exemplar");
    std::string s(other);
    std::cout << quoted(s) << '\n'; // "Exemplar"
  }
 
  {
    std::cout << "9) string(string&&): ";
    std::string s(std::string("C++ by ") + std::string("example"));
    std::cout << quoted(s) << '\n'; // "C++ by example"
  }
 
  {
    std::cout << "α) string(std::initializer_list<charT>): ";
    std::string s({ 'C', '-', 's', 't', 'y', 'l', 'e' });
    std::cout << quoted(s) << '\n'; // "C-style"
  }
 
  {
    // before C++11, overload resolution selects string(InputIt first, InputIt last)
    // [with InputIt = int] which behaves *as if* string(size_type count, charT ch)
    // after C++11 the InputIt constructor is disabled for integral types and calls:
    std::cout << "β) string(size_type count, charT ch) is called: ";
    std::string s(3, std::toupper('a'));
    std::cout << quoted(s) << '\n'; // "AAA"
  }
 
  {
    [[maybe_unused]]
    auto zero = [] { /* ... */ return nullptr; };
//  std::string s{ zero() }; // Before C++23: throws std::logic_error
                             // Since C++23: won't compile, see overload (12)
  }
}
/*
1) string(); s.capacity(): 15
2) string(size_type count, charT ch): "===="
3) string(const string& other, size_type pos, size_type count): "Exemplar"
4) string(const string& other, size_type pos): "Mutandis"
5) string(charT const* s, size_type count): "C-style"
6) string(charT const* s): "C-style"
7) string(InputIt first, InputIt last): "C-style string"
8) string(string&): "Exemplar"
9) string(string&&): "C++ by example"
α) string(std::initializer_list<charT>): "C-style"
β) string(size_type count, charT ch) is called: "AAA"
*/
```

###### MISC

* [c++ - Converting int to String of its ASCII - Stack Overflow](https://stackoverflow.com/questions/34462964/converting-int-to-string-of-its-ascii)
	* `std::string(1, char(97))	// 'a'`
* [Convert byte array to string in C/C++ | Techie Delight](https://www.techiedelight.com/convert-byte-array-to-string-in-c-cpp/)
    * To construct a C++ string from a byte array, use the string constructor. The constructor `string (const char* b, size_t n)` copies the first n characters from array b
```c++
#include <iostream>
#include <string>
 
int main()
{
    const char bytes[] = { 72, 101, 108, 108, 111 };
 
    std::string s(bytes, sizeof(bytes));
    std::cout << s; // Hello
 
    return 0;
}
```

##### Element access

###### [std::basic_string<CharT,Traits,Allocator>::at](https://en.cppreference.com/w/cpp/string/basic_string/at)

* accesses the specified character with bounds checking (public member function)
* Returns a reference to the character at specified location pos. Bounds checking is performed, exception of type std::out_of_range will be thrown on invalid access.
* Return value
    * Reference to the requested character.
* Exceptions
    * Throws std::out_of_range if pos >= size().
* Complexity
    * Constant.

###### [std::basic_string<CharT,Traits,Allocator>::c_str](https://en.cppreference.com/w/cpp/string/basic_string/c_str)

* returns a non-modifiable standard C character array version of the string (public member function)
* Returns a pointer to a null-terminated character array with data equivalent to those stored in the string.
* The pointer is such that the range `[c_str(); c_str() + size()]` is valid and the values in it correspond to the values stored in the string with an additional null character after the last position.
* The pointer obtained from c_str() may be invalidated by:
    * Passing a non-const reference to the string to any standard library function, or
    * Calling non-const member functions on the string, excluding `operator[], at(), front(), back(), begin(), rbegin(), end() and rend()`
* Writing to the character array accessed through c_str() is undefined behavior.
* c_str() and data() perform the same function.
* Return value
    * Pointer to the underlying character storage.
    * `c_str() + i == std::addressof(operator[](i)) for every i in [0, size()].`
* Complexity
    * Constant.
* Notes
    * The pointer obtained from `c_str()` may only be treated as a pointer to a null-terminated character string if the string object does not contain other null characters.
* Example
```c++
#include <algorithm>
#include <cassert>
#include <cstring>
#include <string>
 
extern "C" {
void c_func(const char* c_str) { printf("c_func called with '%s'\n", c_str); }
}
 
int main() {
  std::string const s("Emplary");
  const char* p = s.c_str();
  assert(s.size() == std::strlen(p));
  assert(std::equal(s.begin(), s.end(), p));
  assert(std::equal(p, p + s.size(), s.begin()));
  assert('\0' == *(p + s.size()));
 
  c_func(s.c_str());
}
/*
c_func called with 'Emplary'
*/
```

##### Capacity

###### [std::basic_string<CharT,Traits,Allocator>::size, std::basic_string<CharT,Traits,Allocator>::length](https://en.cppreference.com/w/cpp/string/basic_string/size)

* returns the number of characters (public member function)
* Returns the number of CharT elements in the string, i.e. `std::distance(begin(), end())`.
* Notes
    * For std::string, the elements are bytes (objects of type char), which are not the same as characters if a multibyte encoding such as UTF-8 is used.
* Example
```c++
#include <cassert>
#include <iterator>
#include <string>
 
int main()
{
    std::string s("Exemplar");
    assert(8 == s.size());
    assert(s.size() == s.length());
    assert(s.size() == static_cast<std::string::size_type>(
        std::distance(s.begin(), s.end())));
 
    std::u32string a(U"ハロー・ワールド"); // 8 code points
    assert(8 == a.size()); // 8 code units in UTF-32
 
    std::u16string b(u"ハロー・ワールド"); // 8 code points
    assert(8 == b.size()); // 8 code units in UTF-16
 
    std::string c("ハロー・ワールド"); // 8 code points
    assert(24 == c.size()); // 24 code units in UTF-8
 
    #if __cplusplus >= 202002
    std::u8string d(u8"ハロー・ワールド"); // 8 code points
    assert(24 == d.size()); // 24 code units in UTF-8
    #endif
}
```

##### Operations

###### [std::basic_string<CharT,Traits,Allocator>::erase](https://en.cppreference.com/w/cpp/string/basic_string/erase)

* Removes specified characters from the string.
    1) Removes min(count, size() - index) characters starting at index.
    2) Removes the character at position.
    3) Removes the characters in the range \[first, last).
* [c++ - How to trim a std::string? - Stack Overflow](https://stackoverflow.com/questions/216823/how-to-trim-a-stdstring)
```c++
s.erase(s.find_last_not_of(" \n\r\t")+1);
```

###### [std::basic_string<CharT,Traits,Allocator>::append](https://en.cppreference.com/w/cpp/string/basic_string/append)

* Append to string
    * Extends the string by appending additional characters at the end of its current value:
* Complexity
    * Unspecified, but generally up to linear in the new string length.

###### [std::basic_string<CharT,Traits,Allocator>::compare](https://en.cppreference.com/w/cpp/string/basic_string/compare)

* Compare strings
    * Compares the value of the string object (or a substring) to the sequence of characters specified by its arguments.
    * The compared string is the value of the string object or -if the signature used has a pos and a len parameters- the substring that begins at its character in position pos and spans len characters.
    * This string is compared to a comparing string, which is determined by the other arguments passed to the function.
* Return value
    * Negative value if `*this` appears before the character sequence specified by the arguments, in lexicographical order.
    * `Zero` if both character sequences compare equivalent.
    * Positive value if `*this` appears after the character sequence specified by the arguments, in lexicographical order.

###### [std::basic_string<CharT,Traits,Allocator>::replace](https://en.cppreference.com/w/cpp/string/basic_string/replace)

* replaces specified portion of a string (public member function)
* Replaces the part of the string indicated by either \[pos, pos + count) or \[first, last) with a new string.
```c++
#include <cassert>
#include <cstddef>
#include <iostream>
#include <string>
#include <string_view>
 
std::size_t replace_all(std::string& inout, std::string_view what, std::string_view with);
std::size_t remove_all(std::string& inout, std::string_view what);
void test_replace_remove_all();
 
int main()
{
    std::string str{"The quick brown fox jumps over the lazy dog."};
 
    str.replace(10, 5, "red"); // (5)
 
    str.replace(str.begin(), str.begin() + 3, 1, 'A'); // (6)
 
    std::cout << str << "\n\n";
 
    test_replace_remove_all();
}
 
 
std::size_t replace_all(std::string& inout, std::string_view what, std::string_view with)
{
    std::size_t count{};
    for (std::string::size_type pos{};
         inout.npos != (pos = inout.find(what.data(), pos, what.length()));
         pos += with.length(), ++count) {
        inout.replace(pos, what.length(), with.data(), with.length());
    }
    return count;
}
 
std::size_t remove_all(std::string& inout, std::string_view what) {
    return replace_all(inout, what, "");
}
 
void test_replace_remove_all()
{
    std::string str2{"ftp: ftpftp: ftp:"};
    std::cout << "#1 " << str2 << '\n';
 
    auto count = replace_all(str2, "ftp", "http");
    assert(count == 4);
    std::cout << "#2 " << str2 << '\n';
 
    count = replace_all(str2, "ftp", "http");
    assert(count == 0);
    std::cout << "#3 " << str2 << '\n';
 
    count = remove_all(str2, "http");
    assert(count == 4);
    std::cout << "#4 " << str2 << '\n';
}
/*
A quick red fox jumps over the lazy dog.
 
#1 ftp: ftpftp: ftp:
#2 http: httphttp: http:
#3 http: httphttp: http:
#4 : : :
*/
```

###### [std::basic_string<CharT,Traits,Allocator>::substr](https://en.cppreference.com/w/cpp/string/basic_string/substr)

* returns a substring (public member function)
* Returns a substring `[pos, pos+count)`. If the requested substring extends past the end of the string, i.e. the count is greater than size() - pos (e.g. if count == npos), the returned substring is `[pos, size())`.
```c++
#include <string>
#include <iostream>
 
int main()
{
    std::string a = "0123456789abcdefghij";
 
    // count is npos, returns [pos, size())
    std::string sub1 = a.substr(10);
    std::cout << sub1 << '\n';
 
    // both pos and pos+count are within bounds, returns [pos, pos+count)
    std::string sub2 = a.substr(5, 3);
    std::cout << sub2 << '\n';
 
    // pos is within bounds, pos+count is not, returns [pos, size()) 
    std::string sub4 = a.substr(a.size()-3, 50);
    // this is effectively equivalent to
    // std::string sub4 = a.substr(17, 3);
    // since a.size() == 20, pos == a.size()-3 == 17, and a.size()-pos == 3
 
    std::cout << sub4 << '\n';
 
    try {
        // pos is out of bounds, throws
        std::string sub5 = a.substr(a.size()+3, 50);
        std::cout << sub5 << '\n';
    } catch(const std::out_of_range& e) {
        std::cout << "pos exceeds string size\n";
    }
}
/*
abcdefghij
567
hij
pos exceeds string size
*/
```

##### Search

###### [std::basic_string<CharT,Traits,Allocator>::find](https://en.cppreference.com/w/cpp/string/basic_string/find)

* Return value
    * Position of the first character of the found substring or [npos](https://en.cppreference.com/w/cpp/string/basic_string/npos) if no such substring is found.
* [string::find - C++ Reference](https://www.cplusplus.com/reference/string/string/find/)
    * Find content in string
        * Searches the string for the first occurrence of the sequence specified by its arguments.
        * When pos is specified, the search only includes characters at or after position pos, ignoring any possible occurrences that include characters before pos.
        * Notice that unlike member find_first_of, whenever more than one character is being searched for, it is not enough that just one of these characters match, but the entire sequence must match.
```c++
#include <string>
#include <iostream>
 
void print(std::string::size_type n, std::string const &s)
{
    if (n == std::string::npos) {
        std::cout << "not found\n";
    } else {
        std::cout << "found: " << s.substr(n) << '\n';
    }
}
 
int main()
{
    std::string::size_type n;
    std::string const s = "This is a string";
 
    // search from beginning of string
    n = s.find("is");
    print(n, s);
 
    // search from position 5
    n = s.find("is", 5);
    print(n, s);
 
    // find a single character
    n = s.find('a');
    print(n, s);
 
    // find a single character
    n = s.find('q');
    print(n, s);
}
/*
found: is is a string
found: is a string
found: a string
not found
*/
```

###### [std::basic_string<CharT,Traits,Allocator>::find_first_not_of - cppreference.com](https://en.cppreference.com/w/cpp/string/basic_string/find_first_not_of)

* find first absence of characters (public member function)
* Finds the first character equal to none of the characters in the given character sequence. The search considers only the interval `[pos, size())`. If the character is not present in the interval, npos will be returned.
```c++
#include <string>
#include <iostream>
 
int main() {
    std::string to_search = "Some data with %MACROS to substitute";
 
    std::cout << "Before: " << to_search << '\n';
 
    auto pos = std::string::npos;
    while ((pos = to_search.find('%')) != std::string::npos) {
        // Permit uppercase letters, lowercase letters and numbers in macro names
        const auto after = to_search.find_first_not_of("ABCDEFGHIJKLMNOPQRSTUVWXYZ"
                                                       "abcdefghijklmnopqrstuvwxyz"
                                                       "0123456789", pos + 1);
 
        // Now to_search[pos] == '%' and to_search[after] == ' ' (after the 'S')
 
        if(after != std::string::npos)
            to_search.replace(pos, after - pos, "some very nice macros");
    }
 
    std::cout << "After: " << to_search << '\n';
}
/*
Before: Some data with %MACROS to substitute
After: Some data with some very nice macros to substitute
*/
```

###### [std::basic_string<CharT,Traits,Allocator>::find_last_not_of](https://en.cppreference.com/w/cpp/string/basic_string/find_last_not_of)

* find last absence of characters (public member function)
* Finds the last character equal to none of the characters in the given character sequence. The search considers only the interval `[0, pos]`. If the character is not present in the interval, npos will be returned.
* 1) Finds the last character equal to none of characters in str.
* 2) Finds the last character equal to none of characters in the range `[s, s+count)`. This range can include null characters.
* 3) Finds the last character equal to none of characters in character string pointed to by s. The length of the string is determined by the first null character using Traits::length(s).
* 4) Finds the last character not equal to ch.
* 5) Implicitly converts t to a string view sv as if by `std::basic_string_view<CharT, Traits> sv = t;`, then finds the last character equal to none of characters in sv. This overload participates in overload resolution only if `std::is_convertible_v<const StringViewLike&, std::basic_string_view<CharT, Traits>>` is true and `std::is_convertible_v<const StringViewLike&, const CharT*>` is false.
* In all cases, equality is checked by calling Traits::eq.

###### [std::basic_string<CharT,Traits,Allocator>::substr](https://en.cppreference.com/w/cpp/string/basic_string/substr)

* Returns a substring `[pos, pos+count)`. If the requested substring extends past the end of the string, i.e. the count is greater than size() - pos (e.g. if count == npos), the returned substring is \[pos, [size()](https://en.cppreference.com/w/cpp/string/basic_string/size)).
* Exceptions
    * [std::out_of_range](https://en.cppreference.com/w/cpp/error/out_of_range) if pos > size()

#### Constants

##### [std::basic_string<CharT,Traits,Allocator>::npos](https://en.cppreference.com/w/cpp/string/basic_string/npos)

* special value. The exact meaning depends on the context (public static member constant)
* `static const size_type npos = -1;`
* This is a special value equal to the maximum value representable by the type size_type. The exact meaning depends on context, but it is generally used either as end of string indicator by the functions that expect a string index or as the error indicator by the functions that return a string index.
* Note
    * Although the definition uses -1, size_type is an unsigned integer type, and the value of npos is the largest positive value it can hold, due to signed-to-unsigned implicit conversion. This is a portable way to specify the largest value of any unsigned type.

#### Non-member functions

##### Input/output

###### [operator<<,>>(std::basic_string)](https://en.cppreference.com/w/cpp/string/basic_string/operator_ltltgtgt)

* performs stream input and output on strings (function template)

###### [std::getline](https://en.cppreference.com/w/cpp/string/basic_string/getline)
	
* read data from an I/O stream into a string (function template)
* getline reads characters from an input stream and places them into a string
* Parameters
    * `input`	-	the stream to get data from
    * `str`	-	the string to put the data into
    * `delim`	-	the delimiter character
* Return value
    * `input`
* Notes
    * When consuming whitespace-delimited input (e.g. int n; std::cin >> n;) any whitespace that follows, including a newline character, will be left on the input stream. Then when switching to line-oriented input, the first line retrieved with getline will be just that whitespace. In the likely case that this is unwanted behaviour, possible solutions include:
        * An explicit extraneous initial call to getline
        * Removing consecutive whitespace with `std::cin >> std::ws`
        * Ignoring all leftover characters on the line of input with `cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');`
* Example
    * The following example demonstrates how to use getline function to read user's input and how to process file `line by line`.
```c++
#include <string>
#include <iostream>
#include <sstream>
 
int main()
{
    // greet the user
    std::string name;
    std::cout << "What is your name? ";
    std::getline(std::cin, name);
    std::cout << "Hello " << name << ", nice to meet you.\n";
 
    // read file line by line
    std::istringstream input;
    input.str("1\n2\n3\n4\n5\n6\n7\n");
    int sum = 0;
    for (std::string line; std::getline(input, line); ) {
        sum += std::stoi(line);
    }
    std::cout << "\nThe sum is: " << sum << "\n\n";
 
    // use separator to read parts of the line
    std::istringstream input2;
    input2.str("a;b;c;d");
    for (std::string line; std::getline(input2, line, ';'); ) {
        std::cout << line << '\n';
    }
}
/*
What is your name? John Q. Public
Hello John Q. Public, nice to meet you.
 
The sum is 28.
 
a
b
c
d
*/
```
* [getline (string) - C++ Reference](https://cplusplus.com/reference/string/string/getline/)
    * Get line from stream into string
        * Extracts characters from is and stores them into str until the delimitation character delim is found (or the newline character, '\n', for (2)).
        * The extraction also stops if the end of file is reached in is or if some other error occurs during the input operation.
        * If the delimiter is found, it is extracted and discarded (i.e. it is not stored and the next input operation will begin after it).
        * Note that any content in str before the call is replaced by the newly extracted sequence.
        * Each extracted character is appended to the string as if its member push_back was called.
* [getline (string) in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/getline-string-c/)
    * The C++ getline() is a standard library function that is used to read a string or a line from an input stream. It is a part of the \<string> header. The getline() function extracts characters from the input stream and appends it to the string object until the delimiting character is encountered. While doing so the previously stored value in the string object str will be replaced by the input string if any.
* How to read data from input stream line by line and arguments ?
    * `$ cat ./input.txt | ./my_app 10`
    * Note that stream may be cut due to line seperator. Use `std::cin.rdbuf()` to read the whole input stream at once.
    * [Passing contents of file as argument into C++ program - Stack Overflow](https://stackoverflow.com/questions/48652223/passing-contents-of-file-as-argument-into-c-program)
    * [c++ - Passing text file to standard input - Stack Overflow](https://stackoverflow.com/questions/25985639/passing-text-file-to-standard-input)
```c++
#include <cstdlib>
#include <iostream>
#include <string>

int main(int argc, char* argv[])
{
    if (argc < 2) {
        std::cout << "Usage: " << argv[0] << " <depth>\n";
        return 1;
    }

    auto depth = std::atoi(argv[1]);
    std::cout << depth << '\n';

    for (std::string s_message{}; std::getline(std::cin, s_message); ) {
        std::cout << s_message << '\n';
    }

    return 0;
}
```

##### Numeric conversions

| [stoi/stol/stoll](https://en.cppreference.com/w/cpp/string/basic_string/stol) | converts a string to a signed integer |
| - | - |
| [stoul/stoull](https://en.cppreference.com/w/cpp/string/basic_string/stoul) | converts a string to an unsigned integer |
| [stof/stod/stold](https://en.cppreference.com/w/cpp/string/basic_string/stof) | converts a string to a floating point value |
| [to_string](https://en.cppreference.com/w/cpp/string/basic_string/to_string) | converts an integral or floating point value to string |
| [to_wstring](https://en.cppreference.com/w/cpp/string/basic_string/to_wstring) | converts an integral or floating point value to wstring |

###### [std::stoi, std::stol, std::stoll](https://en.cppreference.com/w/cpp/string/basic_string/stol)

* converts a string to a signed integer
```c++
#include <string>
#include <iomanip>
#include <utility>
#include <iostream>
#include <stdexcept>
 
int main()
{
    const auto data = {
        "45",
        "+45",
        " -45",
        "3.14159",
        "31337 with words",
        "words and 2",
        "12345678901",
    };
 
    for (const std::string s : data)
    {
        std::size_t pos{};
        try
        {
            std::cout << "std::stoi('" << s << "'): ";
            const int i {std::stoi(s, &pos)};
            std::cout << i << "; pos: " << pos << '\n';
        }
        catch(std::invalid_argument const& ex)
        {
            std::cout << "std::invalid_argument::what(): " << ex.what() << '\n';
        }
        catch(std::out_of_range const& ex)
        {
            std::cout << "std::out_of_range::what(): " << ex.what() << '\n';
            const long long ll {std::stoll(s, &pos)};
            std::cout << "std::stoll('" << s << "'): " << ll << "; pos: " << pos << '\n';
        }
    }
 
    std::cout << "\nCalling with different radixes:\n";
    for (const auto& [s, base]: { std::pair<const char*, int>
        {"11",  2}, {"22",  3}, {"33",  4}, {"77",  8},
        {"99", 10}, {"FF", 16}, {"jJ", 20}, {"Zz", 36}, })
    {
        const int i {std::stoi(s, nullptr, base)};
        std::cout << "std::stoi('" << s << "', " << base << "): " << i << '\n';
    }
}
/*
std::stoi('45'): 45; pos: 2
std::stoi('+45'): 45; pos: 3
std::stoi(' -45'): -45; pos: 4
std::stoi('3.14159'): 3; pos: 1
std::stoi('31337 with words'): 31337; pos: 5
std::stoi('words and 2'): std::invalid_argument::what(): stoi
std::stoi('12345678901'): std::out_of_range::what(): stoi
std::stoll('12345678901'): 12345678901; pos: 11
 
Calling with different radixes:
std::stoi('11', 2): 3
std::stoi('22', 3): 8
std::stoi('33', 4): 15
std::stoi('77', 8): 63
std::stoi('99', 10): 99
std::stoi('FF', 16): 255
std::stoi('jJ', 20): 399
std::stoi('Zz', 36): 1295
*/
```

###### [std::stoul, std::stoull](https://en.cppreference.com/w/cpp/string/basic_string/stoul) 

* converts a string to an unsigned integer
* [c++ - How to convert a string to uint32_t - Stack Overflow](https://stackoverflow.com/questions/57253837/how-to-convert-a-string-to-uint32-t)
	* `static_cast<uint32_t>(std::stoul(str))`

###### [std::stof, std::stod, std::stold](https://en.cppreference.com/w/cpp/string/basic_string/stof) 

* converts a string to a floating point value
* [C++ String to float/double and vice-versa](https://www.programiz.com/cpp-programming/string-float-conversion#:~:text=C%2B%2B%20string%20to%20float%20and,convert%20string%20to%20long%20double%20.)

###### [std::to_string](https://en.cppreference.com/w/cpp/string/basic_string/to_string)

* converts an integral or floating point value to string (function)
* Convert numerical value to string
    * Returns a string with the representation of val.
    * Discards any whitespace characters (as identified by calling std::isspace) until the first non-whitespace character is found, then takes as many characters as possible to form a valid base-n (where n=base) integer number representation and converts them to an integer value. 
* Notes
    * With floating point types std::to_string may yield unexpected results as the number of significant digits in the returned string can be zero, see the example.
    * The return value may differ significantly from what std::cout prints by default, see the example.
    * std::to_string relies on the current locale for formatting purposes, and therefore concurrent calls to std::to_string from multiple threads may result in partial serialization of calls. C++17 provides [std::to_chars](https://en.cppreference.com/w/cpp/utility/to_chars) as a higher-performance locale-independent alternative.
```c++
#include <iostream>
#include <string>
 
int main()
{
    for (const double f : {23.43, 1e-9, 1e40, 1e-40, 123456789.})
        std::cout << "std::cout: " << f << '\n'
                  << "to_string: " << std::to_string(f) << "\n\n";
}
/*
std::cout: 23.43
to_string: 23.430000
 
std::cout: 1e-09
to_string: 0.000000
 
std::cout: 1e+40
to_string: 10000000000000000303786028427003666890752.000000
 
std::cout: 1e-40
to_string: 0.000000
 
std::cout: 1.23457e+08
to_string: 123456789.000000
*/
```

#### Literals

* Defined in inline namespace `std::literals::string_literals`

##### [std::literals::string_literals::operator""s](https://en.cppreference.com/w/cpp/string/basic_string/operator%22%22s)

* Converts a character array literal to basic_string (function)
* Forms a string literal of the desired type.

#### MISC

* [How to split a string in C/C++, Python and Java? - GeeksforGeeks](https://www.geeksforgeeks.org/how-to-split-a-string-in-cc-python-and-java/)
    * Extend the method 1 with delimiter
    ```c++
    #include <iostream>
    #include <sstream>
    #include <vector>

    std::vector<std::string> get_split_string(const std::string& s, const char delimiter)
    {
        std::stringstream ss {s};
        std::string value {};
        std::vector<std::string> v_value {};

        while (std::getline(ss, value, delimiter)) {
            v_value.emplace_back(value);
        }

        return v_value;
    };

    int main(int argc, char const* argv[])
    {
        std::string a = "How,do,you,do";

        auto v_result = get_split_string(a, ',');
        for (const auto& it : v_result) {
            std::cout << it << '\n';
        }

        return 0;
    }
    ```
    * Method 1: Using stringstream API of C++
		* Stringstream object can be initialized using a string object, it automatically tokenizes strings on space char. Just like “cin” stream stringstream allows you to read a string as a stream of words.
    ```c++
    #include <bits/stdc++.h>
    using namespace std;

    // A quick way to split strings separated via spaces.
    void simple_tokenizer(string s)
    {
        stringstream ss(s);
        string word;
        while (ss >> word) {
            cout << word << endl;
        }
    }

    int main(int argc, char const* argv[])
    {
        string a = "How do you do!";
        // Takes only space separated C++ strings.
        simple_tokenizer(a);
        cout << endl;
        return 0;
    }
    ```
	* Method 2: Using C++ find() and substr() APIs.
		* This method is more robust and can parse a string with any delimiter, not just spaces(though the default behavior is to separate on spaces.) The logic is pretty simple to understand from the code below.
    ```c++
    #include <bits/stdc++.h>
    using namespace std;

    void tokenize(string s, string del = " ")
    {
        int start = 0;
        int end = s.find(del);
        while (end != -1) {
            cout << s.substr(start, end - start) << endl;
            start = end + del.size();
            end = s.find(del, start);
        }
        cout << s.substr(start, end - start);
    }
    int main(int argc, char const* argv[])
    {
        // Takes C++ string with any separator
        string a = "Hi$%do$%you$%do$%!";
        tokenize(a, "$%");
        cout << endl;

        return 0;
    }
    ```
	* Method 3: Using temporary string
		* If you are given that the length of the delimiter is 1, then you can simply use a temp string to split the string. This will save the function overhead time in the case of method 2.
    ```c++
    #include <iostream>
    using namespace std;

    void split(string str, char del){
        // declaring temp string to store the curr "word" upto del
        string temp = "";

        for(int i=0; i<(int)str.size(); i++){
            // If cur char is not del, then append it to the cur "word", otherwise
            // you have completed the word, print it, and start a new word.
            if(str[i] != del){
                temp += str[i];
            }
            else{
                cout << temp << " ";
                temp = "";
            }
        }

        cout << temp;
    }

    int main() {

        string str = "geeks_for_geeks"; // string to be split
        char del = '_'; // delimiter around which string is to be split

        split(str, del);

        return 0;
    }
    ```
* [现代C++编程实践(四)—手动撸一个泛型分割函数](https://mp.weixin.qq.com/s/rCf7qe6LmBdzngSdWsGdQQ)
	* 熟悉Java、C#以及Python的人都知道，在字符串处理时有一个split函数，非常有用，尤其在使用文件接口时，对方按照协议将内容以一定格式保存到文件中，我们要做的就是读取文件并解析文件。但是作为C/C++的我们，标准库里并没有现成的split接口可用，今天我们就使用现代C++手动实现一个C++版的分割函数。
* [string和c_str()使用时的坑](https://mp.weixin.qq.com/s/2k2fjBUB-P1PpEfP-HJz-Q)
	* 这里主要说两个问题:
		* 1、声明了一个string实例,使用c_str()进行赋值后,可以正常输出c_str()的值,但是直接输出string实例的实现,实际是空字符串
		* 2、在第一个问题后,对string实例进行字符串追加,然后对string和c_str()进行输出.原来对字符串变量被覆盖了.
	* 在使用string中的c_str()进行字符串赋值时,如果后面对string中的char*进行改变.那么c_str()中的值就不在可靠了.
* [c++ - Displaying the address of a string - Stack Overflow](https://stackoverflow.com/questions/9377407/displaying-the-address-of-a-string)
	* If you use &hello it prints the address of the pointer, not the address of the string. Cast the pointer to a void* to use the correct overload of operator<<.
	```c++
	std::cout << "String address = " << static_cast<void*>(hello) << std::endl;
	```
* [使用 C++ 的 StringBuilder 提升 4350% 的性能](https://mp.weixin.qq.com/s/YfY_c4D_kWSth5tETqnhkg)
  * 经常出现客户端打电话抱怨说：你们的程序慢如蜗牛。你开始检查可能的疑点：文件IO，数据库访问速度，甚至查看web服务。但是这些可能的疑点都很正常，一点问题都没有。
  * 你使用最顺手的性能分析工具分析，发现瓶颈在于一个小函数，这个函数的作用是将一个长的字符串链表写到一文件中。
  * 你对这个函数做了如下优化：将所有的小字符串连接成一个长的字符串，执行一次文件写入操作，避免成千上万次的小字符串写文件操作。
  * 这个优化只做对了一半。
  * 你先测试大字符串写文件的速度，发现快如闪电。然后你再测试所有字符串拼接的速度。
  * 好几年。
  * 怎么回事？你会怎么克服这个问题呢？
  * 你或许知道.net程序员可以使用StringBuilder来解决此问题。这也是本文的起点。
* [string底层实现之COW](https://mp.weixin.qq.com/s/_KhshT3h2hREpFs7gnaYRA)
	* COW
		* COW是Copy On Write的缩写，是一种很常见且很重要的优化方式。核心思想是对多个实体的资源请求进行延时处理，如果不存在资源更改行为，则多个实体共享该块资源，直到有实体需要对资源进行修改时，才真正为该实体分配私有的资源。
		* COW技术的一个经典应用在于Linux内核在进程fork时对进程地址空间的处理。由于fork产生的子进程需要一份和父进程内容相同但完全独立的地址空间，一种做法是将父进程的地址空间完全复制一份，另一种做法是将父进程地址空间中的页面标记为共享的（引用计数+1），使子进程与父进程共享地址空间，但当有一方需要对内存中某个页面进行修改时，重新分配一个新的页面（拷贝原内容），并使修改进程的虚拟地址重定向到新的页面上。
		* COW技术有哪些优点呢?
			* 1. 减少了分配（和复制）大量资源带来的瞬间延迟（注意仅仅是latency，但实际上该延迟被分摊到后续的操作中，其累积耗时很可能比一次统一处理的延迟要高，造成throughput下降是有可能的）
			* 2. 另一方面减少不必要的资源分配。（例如在fork的例子中，并不是所有的页面都需要复制，比如父进程的代码段(.code)和只读数据(.rodata)段，由于不允许修改，根本就无需复制。而如果fork后面紧跟exec的话，之前的地址空间都会废弃，花大力气的分配和复制只是徒劳无功。）
		* COW的思想在资源管理上被广泛使用，本文中分析的string中也用到了~~。
	* 结语
		* COW的核心思想就是lazy-copy，是一种常见的优化手段，通常发生在拷贝、赋值等操作上，但是如果使用不当，则会导致预期之外的结果，虽然COW在gcc的高版本实现中已经去掉了，但是，因为种种原因，仍然有许多开发人员使用的老版本gcc，那么这个优化导致的问题就不得不引起关注，正所谓知己知彼，方能百战不殆。

### [std::basic_string_view](https://en.cppreference.com/w/cpp/string/basic_string_view)

* The class template basic_string_view describes an object that can refer to a constant contiguous sequence of char-like objects with the first element of the sequence at position zero.
* [class std::string_view in C++17 - GeeksforGeeks](https://www.geeksforgeeks.org/class-stdstring_view-in-cpp-17/)
	* Drawback of std::string
	* Benefits of std::string_view
	* Parameters In std::string_view
	* Modification of std::string_view
	* Non-null Terminated Strings
	* Conversion Of std::string_view Into std::string
	* Conversion Of std::string_view To C-style String
	* Scoping Issues With std::string_view
	* Execution Of std::string_view with data() Function
```c++
// C++ program to implement
// the above approach
#include <iostream>
#include <string>
#include <string_view>
using namespace std;

void print(string s)
{
    cout << s << '\n';
}

// Driver code
int main()
{
    string_view str_1{ "Madhav" };
    str_1.remove_suffix(3);

    // compile error: won't implicitly
    // convert
    // print(str_1);

    // explicit conversion
    string str_2{ str_1 };

    print(str_2);

    // It'll work
    print(static_cast<string>(str_1));

    return 0;
}
```
* [C++17常用新特性(十五)---std::string_view和std::string差异比较](https://mp.weixin.qq.com/s/NxnPG5cVurxlcpNKdVZ-NQ)
	* 1 std::string_view和std::string内存分配的不同
	* 2 std::string_view和std::string的substr()方法性能差异10倍左右
	* 3 总结
		* 在使用 std::string_view时最好遵循以下约束：
		* 如果字符串不需要修改时使用std::string_view
		* std::string_view相对于string来说减少了内存的重新分配和内存拷贝
		* 对于std::string::substr 算法来说string的时间复杂度是线性增长，字符串越长执行时间越长，string_view时间复杂度为常数级。

#### Literals

* [std::literals::string_view_literals::operator""sv - cppreference.com](https://en.cppreference.com/w/cpp/string/basic_string_view/operator%22%22sv)
	* Defined in header \<string_view>
	* Creates a string view of a character array literal (function)

### [Null-terminated byte strings](https://en.cppreference.com/w/cpp/string/byte)

* A null-terminated byte string (NTBS) is a sequence of nonzero bytes followed by a byte with value zero (the terminating null character). Each byte in a byte string encodes one character of some character set. For example, the character array {'\x63', '\x61', '\x74', '\0'} is an NTBS holding the string "cat" in ASCII encoding.

#### Character classification

* Defined in header \<cctype>

##### [std::isalnum](https://en.cppreference.com/w/cpp/string/byte/isalnum)

* checks if a character is alphanumeric (function)
* Checks if the given character is an alphanumeric character as classified by the current C locale. In the default locale, the following characters are alphanumeric:
    * digits `0123456789`
    * uppercase letters `ABCDEFGHIJKLMNOPQRSTUVWXYZ`
    * lowercase letters `abcdefghijklmnopqrstuvwxyz`
* The behavior is undefined if the value of ch is not representable as unsigned char and is not equal to EOF.

##### [std::isalpha](https://en.cppreference.com/w/cpp/string/byte/isalpha)
	
* checks if a character is alphabetic (function)
* Checks if the given character is an alphabetic character as classified by the currently installed C locale. In the default locale, the following characters are alphabetic:
    * uppercase letters `ABCDEFGHIJKLMNOPQRSTUVWXYZ`
    * lowercase letters `abcdefghijklmnopqrstuvwxyz`
* In locales other than "C", an alphabetic character is a character for which std::isupper() or std::islower() returns non-zero or any other character considered alphabetic by the locale. In any case, std::iscntrl(), std::isdigit(), std::ispunct() and std::isspace() will return zero for this character.
* The behavior is undefined if the value of ch is not representable as unsigned char and is not equal to EOF.

##### [std::isdigit](https://en.cppreference.com/w/cpp/string/byte/isdigit)
	
* `int isdigit( int ch );`
* checks if a character is a digit (function)
* Checks if the given character is one of the 10 decimal digits: 0123456789.
* The behavior is undefined if the value of ch is not representable as unsigned char and is not equal to EOF.
* [Determine if a String Is a Number in C++ | Delft Stack](https://www.delftstack.com/howto/cpp/how-to-determine-if-a-string-is-number-cpp/#:~:text=Use%20std%3A%3Aisdigit%20Method%20to%20Determine%20if%20a%20String%20Is%20a%20Number,-The%20first%20version&text=Namely%2C%20pass%20a%20string%20as,none%20is%20found%20returns%20true.)
    * Use std::isdigit Method to Determine if a String Is a Number
    * Use std::isdigit With std::ranges::all_of to Determine if a String Is a Number
    * Use find_first_not_of Method to Determine if a String Is a Number

##### [std::isspace](https://en.cppreference.com/w/cpp/string/byte/isspace)

* `int isspace( int ch );`
* checks if a character is a space character (function)
* [c++ - std::remove_if and std::isspace - compile-time error - Stack Overflow](https://stackoverflow.com/questions/21578544/stdremove-if-and-stdisspace-compile-time-error)
    * There is another overload of std::isspace, so you need to specify which one to use. An easy way is to use a lambda (or write your own one-line function if you don't have C++11 support)

#### Character manipulation

##### [std::tolower](https://en.cppreference.com/w/cpp/string/byte/tolower)

* converts a character to lowercase (function)
* `int tolower( int ch );`
* Converts the given character to lowercase according to the character conversion rules defined by the currently installed C locale.
* In the default "C" locale, the following uppercase letters `ABCDEFGHIJKLMNOPQRSTUVWXYZ` are replaced with respective lowercase letters `abcdefghijklmnopqrstuvwxyz`.

##### [std::toupper](https://en.cppreference.com/w/cpp/string/byte/toupper)

* converts a character to uppercase (function)
* Converts the given character to uppercase according to the character conversion rules defined by the currently installed C locale.
* In the default "C" locale, the following lowercase letters `abcdefghijklmnopqrstuvwxyz` are replaced with respective uppercase letters `ABCDEFGHIJKLMNOPQRSTUVWXYZ`.

#### Conversions to numeric formats

* Defined in header `<cstdlib>`

##### [std::atoi, std::atol, std::atoll](https://en.cppreference.com/w/cpp/string/byte/atoi)
    
* converts a byte string to an integer value (function)
* `int       atoi( const char *str );`
* `long      atol( const char *str );`
* `long long atoll( const char *str );`
* Interprets an integer value in a byte string pointed to by str. The implied radix is always 10.
* Discards any whitespace characters until the first non-whitespace character is found, then takes as many characters as possible to form a valid integer number representation and converts them to an integer value. The valid integer value consists of the following parts:
    * (optional) plus or minus sign
    * numeric digits
* If the value of the result cannot be represented, i.e. the converted value falls out of range of the corresponding return type, the behavior is undefined.
* Return value
    * Integer value corresponding to the contents of str on success.
    * If no conversion can be performed, `0` is returned.    
* Example
```c++
#include <cstdlib>
#include <iostream>
 
int main()
{
    const auto data = { 
        "42",
        "0x2A", // treated as "0" and junk "x2A", not as hexadecimal
        "3.14159",
        "31337 with words",
        "words and 2",
        "-012345",
        "10000000000" // note: out of int32_t range
    };
 
    for (const char* s : data) {
        const int i {std::atoi(s)};
        std::cout << "std::atoi('" << s << "') is " << i << '\n';
        if (const long long ll {std::atoll(s)}; i != ll) {
            std::cout << "std::atoll('" << s << "') is " << ll << '\n';
        }
    }
}
/*
std::atoi('42') is 42
std::atoi('0x2A') is 0
std::atoi('3.14159') is 3
std::atoi('31337 with words') is 31337
std::atoi('words and 2') is 0
std::atoi('-012345') is -12345
std::atoi('10000000000') is 1410065408
std::atoll('10000000000') is 10000000000
*/    
```
    
###### Possible implementation
    
```c++    
template<typename T>
T atoi_impl(const char* str)
{
    while (std::isspace(static_cast<unsigned char>(*str)))
    {
        ++str;
    }
 
    bool negative = false;
 
    if (*str == '+')
    {
        ++str;
    }
    else if (*str == '-')
    {
        ++str;
        negative = true;
    }
 
    T result = 0;
    for (; std::isdigit(static_cast<unsigned char>(*str)); ++str)
    {
        int digit = *str - '0';
        result *= 10;
        result -= digit; // calculate in negatives to support INT_MIN, LONG_MIN,..
    }
 
    return negative ? result : -result;
}
 
int atoi(const char* str)
{
    return atoi_impl<int>(str);
}
 
long atol(const char* str)
{
    return atoi_impl<long>(str);
}
 
long long atoll(const char* str)
{
    return atoi_impl<long long>(str);
}
```   
    
#### String manipulation

* Defined in header `<cstring>`

##### [std::strncpy](https://en.cppreference.com/w/cpp/string/byte/strncpy)

* copies a certain amount of characters from one string to another (function)
* `char *strncpy( char *dest, const char *src, std::size_t count );`
* Copies at most count characters of the byte string pointed to by src (including the terminating null character) to character array pointed to by dest.
* If count is reached before the entire string src was copied, the resulting character array is not null-terminated.
* If, after copying the terminating null character from src, count is not reached, additional null characters are written to dest until the total of count characters have been written.
* If the strings overlap, the behavior is undefined.
* Example
```c++
#include <iostream>
#include <cstring>
 
int main()
{
    const char* src = "hi";
    char dest[6] = {'a', 'b', 'c', 'd', 'e', 'f'};
    std::strncpy(dest, src, 5);
 
    std::cout << "The contents of dest are: ";
    for (char c : dest) {
        if (c) {
            std::cout << c << ' ';
        } else {
            std::cout << "\\0" << ' ';
        }
    }
    std::cout << '\n';
}
/*
The contents of dest are: h i \0 \0 \0 f
*/
```

#### String examination

* Defined in header `<cstring>`

##### [std::strncmp](https://en.cppreference.com/w/cpp/string/byte/strncmp)

* `int strncmp( const char *lhs, const char *rhs, std::size_t count );`
* Compares at most count characters of two possibly null-terminated arrays. The comparison is done lexicographically. Characters following the null character are not compared.
* The sign of the result is the sign of the difference between the values of the first pair of characters (both interpreted as `unsigned char`) that differ in the arrays being compared.
* The behavior is undefined when access occurs past the end of either array lhs or rhs. The behavior is undefined when either lhs or rhs is the null pointer.
* Return value
    * Negative value if lhs appears before rhs in lexicographical order.
    * Zero if lhs and rhs compare equal, or if count is zero.
    * Positive value if lhs appears after rhs in lexicographical order.
* Notes
    * This function is not locale-sensitive, unlike [std::strcoll](https://en.cppreference.com/w/cpp/string/byte/strcoll) and [std::strxfrm](https://en.cppreference.com/w/cpp/string/byte/strxfrm).
* Example
```c++
#include <cstring>
#include <iostream>
 
void demo(const char* lhs, const char* rhs, int sz)
{
    int rc = std::strncmp(lhs, rhs, sz);
    if(rc == 0)
        std::cout << "First " << sz << " chars of ["
                  << lhs << "] equal [" << rhs << "]\n";
    else if(rc < 0)
        std::cout << "First " << sz << " chars of ["
                  << lhs << "] precede [" << rhs << "]\n";
    else if(rc > 0)
        std::cout << "First " << sz << " chars of ["
                  << lhs << "] follow [" << rhs << "]\n";
}
int main()
{
    demo("Hello, world!", "Hello, everybody!", 13);
    demo("Hello, everybody!", "Hello, world!", 13);
    demo("Hello, everybody!", "Hello, world!", 7);
    demo("Hello, everybody!" + 12, "Hello, somebody!" + 11, 5);
}
/*
First 13 chars of [Hello, world!] follow [Hello, everybody!]
First 13 chars of [Hello, everybody!] precede [Hello, world!]
First 7 chars of [Hello, everybody!] equal [Hello, world!]
First 5 chars of [body!] equal [body!]
*/
```

## [Containers library](https://en.cppreference.com/w/cpp/container)

* [Standard Template Library (STL)](https://www.tutorialspoint.com/cplusplus/cpp_stl_tutorial.htm)
* [STL - c-cpp/面试总结之C-C++ at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E9%9D%A2%E8%AF%95%E6%80%BB%E7%BB%93%E4%B9%8BC-C%2B%2B#stl)
* The Containers library is a generic collection of class templates and algorithms that allow programmers to easily implement common data structures like queues, lists and stacks. There are three classes of containers -- sequence containers, associative containers, and unordered associative containers -- each of which is designed to support a different set of operations.
* The container manages the storage space that is allocated for its elements and provides member functions to access them, either directly or through iterators (objects with properties similar to pointers).
* Most containers have at least several member functions in common, and share functionalities. Which container is the best for the particular application depends not only on the offered functionality, but also on its efficiency for different workloads.
* `Iterator invalidation`
	* Read-only methods never invalidate iterators or references. Methods which modify the contents of a container may invalidate iterators and/or references, as summarized in this table.
<img width="780" alt="截屏2022-12-19 下午11 13 54" src="https://user-images.githubusercontent.com/34557994/208423882-896a920a-0e64-4e3b-81a3-77520f54794d.png">

* `Thread safety`
	* All container functions can be called concurrently by different threads on different containers. More generally, the C++ standard library functions do not read objects accessible by other threads unless those objects are directly or indirectly accessible via the function arguments, including the this pointer.
	* All const member functions can be called concurrently by different threads on the same container. In addition, the member functions begin(), end(), rbegin(), rend(), front(), back(), data(), find(), lower_bound(), upper_bound(), equal_range(), at(), and, except in associative containers, operator[], behave as const for the purposes of thread safety (that is, they can also be called concurrently by different threads on the same container). More generally, the C++ standard library functions do not modify objects unless those objects are accessible, directly or indirectly, via the function's non-const arguments, including the this pointer.
	* Different elements in the same container can be modified concurrently by different threads, except for the elements of std::vector\<bool> (for example, a vector of std::future objects can be receiving values from multiple threads).
	* Iterator operations (e.g. incrementing an iterator) read, but do not modify the underlying container, and may be executed concurrently with operations on other iterators on the same container, with the const member functions, or reads from the elements. Container operations that invalidate any iterators modify the container and cannot be executed concurrently with any operations on existing iterators even if those iterators are not invalidated.
	* Elements of the same container can be modified concurrently with those member functions that are not specified to access these elements. More generally, the C++ standard library functions do not read objects indirectly accessible through their arguments (including other elements of a container) except when required by its specification.
	* In any case, container operations (as well as algorithms, or any other C++ standard library functions) may be parallelized internally as long as this does not change the user-visible results (e.g. std::transform may be parallelized, but not std::for_each which is specified to visit each element of a sequence in order)

### Sequence

* Sequence containers implement data structures which can be accessed sequentially.

| array | static contiguous array |
| - | - |
| vector | dynamic contiguous array |
| deque | double-ended queue | 
| forward_list | singly-linked list| 
| list | doubly-linked list| 

#### [std::array](https://en.cppreference.com/w/cpp/container/array)

* static contiguous array (class template)
* std::array is a container that encapsulates `fixed size arrays`.
* Defined in header `<array>`
* `template<class T, std::size_t N> struct array; (since C++11)`
* This container is an aggregate type with the same semantics as a struct holding a [C-style array](https://en.cppreference.com/w/cpp/language/array) `T[N]` as its only non-static data member. Unlike a C-style array, it doesn't decay to `T*` automatically. As an aggregate type, it can be initialized with [aggregate-initialization](https://en.cppreference.com/w/cpp/language/aggregate_initialization) given at most N initializers that are convertible to T: `std::array<int, 3> a = {1,2,3};`.
* The struct combines the performance and accessibility of a C-style array with the benefits of a standard container, such as knowing its own size, supporting assignment, random access iterators, etc.
* std::array satisfies the requirements of `Container` and `ReversibleContainer` except that default-constructed array is not empty and that the complexity of swapping is linear, `satisfies the requirements of ContiguousContainer, (since C++17)` and partially satisfies the requirements of `SequenceContainer`.
* There is a special case for a zero-length array (N == 0). In that case, `array.begin() == array.end()`, which is some unique value. The effect of calling `front()` or `back()` on a zero-sized array is undefined.
* An array can also be used as a tuple of N elements of the same type.
* Example
```c++
#include <string>
#include <iterator>
#include <iostream>
#include <algorithm>
#include <array>
 
int main()
{
    // construction uses aggregate initialization
    std::array<int, 3> a1{ {1, 2, 3} }; // double-braces required in C++11 prior to
                                        // the CWG 1270 revision (not needed in C++11
                                        // after the revision and in C++14 and beyond)
 
    std::array<int, 3> a2 = {1, 2, 3};  // double braces never required after =
 
    std::array<std::string, 2> a3 = { std::string("a"), "b" };
 
    // container operations are supported
    std::sort(a1.begin(), a1.end());
    std::reverse_copy(a2.begin(), a2.end(), 
                      std::ostream_iterator<int>(std::cout, " "));
 
    std::cout << '\n';
 
    // ranged for loop is supported
    for(const auto& s: a3)
        std::cout << s << ' ';
 
    // deduction guide for array creation (since C++17)
    [[maybe_unused]] std::array a4{3.0, 1.0, 4.0};  // -> std::array<double, 3>
}
/*
3 2 1 
a b
*/
```

##### Iterator invalidation

* As a rule, iterators to an array are `never` invalidated throughout the lifetime of the array. One should take note, however, that during [swap](https://en.cppreference.com/w/cpp/container/array/swap), the iterator will continue to point to the same array element, and will thus change its value.

#### [std::vector](https://en.cppreference.com/w/cpp/container/vector)

* Defined in header `<vector>`
```c++
template<
    class T,
    class Allocator = std::allocator<T>
> class vector;
(1)	
namespace pmr {
    template< class T >
    using vector = std::vector<T, std::pmr::polymorphic_allocator<T>>;
}
(2)	(since C++17)
```
* 1) std::vector is a sequence container that encapsulates dynamic size arrays.
* 2) std::pmr::vector is an alias template that uses a polymorphic allocator.
* The elements are stored contiguously, which means that elements can be accessed not only through iterators, but also using offsets to regular pointers to elements. This means that a pointer to an element of a vector may be passed to any function that expects a pointer to an element of an array.
* The storage of the vector is handled automatically, being expanded and contracted as needed. Vectors usually occupy more space than static arrays, because more memory is allocated to handle future growth. This way a vector does not need to reallocate each time an element is inserted, but only when the additional memory is exhausted. The total amount of allocated memory can be queried using capacity() function. `Extra memory can be returned to the system via a call to shrink_to_fit().`
* Reallocations are usually costly operations in terms of performance. The reserve() function can be used to eliminate reallocations if the number of elements is known beforehand.
* The complexity (efficiency) of common operations on vectors is as follows:
	* Random access - constant 𝓞(1)
	* Insertion or removal of elements at the end - amortized constant 𝓞(1)
	* Insertion or removal of elements - linear in the distance to the end of the vector 𝓞(n)
* std::vector (for T other than bool) meets the requirements of Container, AllocatorAwareContainer, SequenceContainer , ContiguousContainer (since C++17) and ReversibleContainer.
* Example
```c++
#include <iostream>
#include <vector>
 
int main()
{
    // Create a vector containing integers
    std::vector<int> v = {7, 5, 16, 8};
 
    // Add two more integers to vector
    v.push_back(25);
    v.push_back(13);
 
    // Print out the vector
    std::cout << "v = { ";
    for (int n : v)
        std::cout << n << ", ";
    std::cout << "}; \n";
}
/*
v = { 7, 5, 16, 8, 25, 13, };
*/
```

##### Iterator invalidation

| Operations | Invalidated | 
| - | - | 
| All read only operations | Never | 
| swap, std::swap | end() | 
| clear, operator=, assign | Always | 
| reserve, shrink_to_fit | If the vector changed capacity, all of them. If not, none. | 
| erase | Erased elements and all elements after them (including end()) | 
| push_back, emplace_back | If the vector changed capacity, all of them. If not, only end(). | 
| insert, emplace | If the vector changed capacity, all of them. If not, only those at or after the insertion point (including end()). | 
| resize | If the vector changed capacity, all of them. If not, only end() and any elements erased. | 
| pop_back | The element erased and end(). | 

##### Member types

##### Member functions

###### [std::vector<T,Allocator>::vector](https://en.cppreference.com/w/cpp/container/vector/vector)

* constructs the vector (public member function)
* Constructs a new container from a variety of data sources, optionally using a user supplied allocator alloc.
* [Initialize a vector in C++ (7 different ways) - GeeksforGeeks](https://www.geeksforgeeks.org/initialize-a-vector-in-cpp-different-ways/)
	* 1. Initializing by pushing values one by one 
	* 2. Specifying size and initializing all values 
	* 3. Initializing like arrays 
	* 4. Initializing from an array 
	* 5. Initializing from another vector 
	* 6. Initializing all elements with a particular value 
	* 7. Initialize an array with consecutive numbers using std::iota 
```c++
// CPP program to initialize a vector from
// an array.
#include <iostream>
#include <vector>
using namespace std;

int main()
{
	int arr[] = { 10, 20, 30 };
	int n = sizeof(arr) / sizeof(arr[0]);

	vector<int> vect(arr, arr + n);

	for (int x : vect)
		cout << x << " ";

	return 0;
}
```
* [2D Vector In C++ With User Defined Size - GeeksforGeeks](https://www.geeksforgeeks.org/2d-vector-in-cpp-with-user-defined-size/)
```c++
// CPP program
#include <iostream>
#include <vector>
using namespace std;
int main()
{
    int n = 3;
    int m = 4;

    /*
    We create a 2D vector containing "n"
    elements each having the value "vector<int> (m, 0)".
    "vector<int> (m, 0)" means a vector having "m"
    elements each of value "0".
    Here these elements are vectors.
    */
    vector<vector<int>> vec( n , vector<int> (m, 0));

    for(int i = 0; i < n; i++)
    {
        for(int j = 0; j < m; j++)
        {
            cout << vec[i][j] << " ";
        }
        cout<< endl;
    }
    
    return 0;
}
```
* [vector初始化与否导致的巨大性能差异](https://mp.weixin.qq.com/s/HISHvxxd1LVBwouAE-uZHg)
	* 最近在优化引擎代码，在优化的过程中发现一个很奇怪的问题，一个简单的对象，存放在std::vector<> v中，如果v定义的时候为每个元素指定初值，那么后面对v中每个元素的写就飞快；相反的，如果v定义的时候，不指定初始值，那么后面对v中元素写操作的时候，就花费大约前一种2-3倍的时间。

###### [std::vector<T,Allocator>::operator=](https://en.cppreference.com/w/cpp/container/vector/operator%3D)

* assigns values to the container (public member function)
* Replaces the contents of the container.
    * 1) Copy assignment operator. Replaces the contents with a copy of the contents of other.
    * If std::allocator_traits\<allocator_type>::propagate_on_container_copy_assignment::value is true, the allocator of *this is replaced by a copy of that of other. If the allocator of *this after assignment would compare unequal to its old value, the old allocator is used to deallocate the memory, then the new allocator is used to allocate it before copying the elements. Otherwise, the memory owned by *this may be reused when possible. In any case, the elements originally belonging to *this may be either destroyed or replaced by element-wise copy-assignment. (since C++11)
    * 2) Move assignment operator. Replaces the contents with those of other using move semantics (i.e. the data in other is moved from other into this container). other is in a valid but unspecified state afterwards.
    * If std::allocator_traits<allocator_type>::propagate_on_container_move_assignment::value is true, the allocator of *this is replaced by a copy of that of other. If it is false and the allocators of *this and other do not compare equal, *this cannot take ownership of the memory owned by other and must move-assign each element individually, allocating additional memory using its own allocator as needed. In any case, all elements originally belonging to *this are either destroyed or replaced by element-wise move-assignment.
    * 3) Replaces the contents with those identified by initializer list ilist.

###### [std::vector<T,Allocator>::assign](https://en.cppreference.com/w/cpp/container/vector/assign)

* assigns values to the container (public member function)
* Replaces the contents of the container.
    * 1) Replaces the contents with count copies of value value
    * 2) Replaces the contents with copies of those in the range \[first, last). The behavior is undefined if either argument is an iterator into *this.
    * This overload has the same effect as overload (1) if InputIt is an integral type. (until C++11)
    * This overload participates in overload resolution only if InputIt satisfies LegacyInputIterator. (since C++11)
    * 3) Replaces the contents with the elements from the initializer list ilist.
* All iterators, pointers and references to the elements of the container are invalidated. The past-the-end iterator is also invalidated.
* [c++ - How to initialize std::vector from C-style array? - Stack Overflow](https://stackoverflow.com/questions/2434196/how-to-initialize-stdvector-from-c-style-array)
	* Don't forget that you can treat pointers as iterators:
	* `w_.assign(w, w + len);`

###### Element access

* [std::vector<T,Allocator>::at - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/at)
	* access specified element with bounds checking (public member function)
	* Returns a reference to the element at specified location pos, with bounds checking.
	* If pos is not within the range of the container, an exception of type std::out_of_range is thrown.
* [std::vector<T,Allocator>::operator[] - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/operator_at)
	* access specified element (public member function)
	* Returns a reference to the element at specified location pos. No bounds checking is performed.
	* Notes
		* Unlike std::map::operator[], this operator never inserts a new element into the container. Accessing a nonexistent element through this operator is undefined behavior.

###### Iterators

* [std::vector<T,Allocator>::rbegin, std::vector<T,Allocator>::crbegin - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/rbegin)
	* Returns a reverse iterator to the first element of the reversed vector. It corresponds to the last element of the non-reversed vector. If the vector is empty, the returned iterator is equal to rend().

###### Capacity

* [std::vector<T,Allocator>::empty - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/empty)
	* Checks if the container has no elements, i.e. whether begin() == end().
* [std::vector<T,Allocator>::reserve - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/reserve)
	* reserves storage (public member function)
	* Increase the capacity of the vector (the total number of elements that the vector can hold without requiring reallocation) to a value that's greater or equal to new_cap. If new_cap is greater than the current capacity(), new storage is allocated, otherwise the function does nothing.
	* reserve() does not change the size of the vector.
	* If new_cap is greater than capacity(), all iterators, including the past-the-end iterator, and all references to the elements are invalidated. Otherwise, no iterators or references are invalidated.
* [std::vector<T,Allocator>::shrink_to_fit - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/shrink_to_fit)
	* reduces memory usage by freeing unused memory (public member function)
	* Requests the removal of unused capacity.
	* It is a non-binding request to reduce capacity() to size(). It depends on the implementation whether the request is fulfilled.
	* If reallocation occurs, all iterators, including the past the end iterator, and all references to the elements are invalidated. If no reallocation takes place, no iterators or references are invalidated.

###### Modifiers

* [std::vector<T,Allocator>::clear - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/clear)
	* Erases all elements from the container. After this call, size() returns zero.
	* Invalidates any references, pointers, or iterators referring to contained elements. Any past-the-end iterators are also invalidated.  
	* Leaves the capacity() of the vector unchanged (note: the standard's restriction on the changes to capacity is in the specification of vector::reserve, see [1])
* [std::vector<T,Allocator>::insert - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/insert)
	* Inserts elements at the specified location in the container.
		* 1-2) inserts value before pos
		* 3) inserts count copies of the value before pos
		* 4) inserts elements from range \[first, last) before pos.
		* The behavior is undefined if first and last are iterators into *this.
		* 5) inserts elements from initializer list ilist before pos.
	* Causes reallocation if the new size() is greater than the old capacity(). If the new size() is greater than capacity(), all iterators and references are invalidated. Otherwise, only the iterators and references before the insertion point remain valid. The past-the-end iterator is also invalidated.
* [std::vector\<T,Allocator>::erase - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/erase)
	* Erases the specified elements from the container.
		* 1) Removes the element at pos.
		* 2) Removes the elements in the range \[first, last).
	* Invalidates iterators and references at or after the point of the erase, including the end() iterator.
	* The iterator pos must be valid and dereferenceable. Thus the end() iterator (which is valid, but is not dereferenceable) cannot be used as a value for pos.
	* The iterator first does not need to be dereferenceable if first==last: erasing an empty range is a no-op.	
* How to erase certain value in vector ?
	* [c++ - How do I remove an item from a stl vector with a certain value? - Stack Overflow](https://stackoverflow.com/questions/39912/how-do-i-remove-an-item-from-a-stl-vector-with-a-certain-value)
```c++
std::vector<int> vec;
// .. put in some values ..
int int_to_remove = n;
vec.erase(std::remove(vec.begin(), vec.end(), int_to_remove), vec.end());

std::vector<int> c = {1, 2, 3, 4, 5, 6, 7};
int x = 5;
c.erase(std::remove_if(c.begin(), c.end(), [x](int n) { return n < x; }), c.end());
```
* [vector erase() and clear() in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/vector-erase-and-clear-in-cpp/)
* [std::vector<T,Allocator>::emplace_back - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/emplace_back)
	* Appends a new element to the end of the container. The element is constructed through std::allocator_traits::construct, which typically uses placement-new to construct the element in-place at the location provided by the container. The arguments args... are forwarded to the constructor as std::forward\<Args>(args)....
	* If the new size() is greater than capacity() then all iterators and references (including the past-the-end iterator) are invalidated. Otherwise only the past-the-end iterator is invalidated.	
* [vector::emplace_back - C++ Reference](http://www.cplusplus.com/reference/vector/vector/emplace_back/)
	* Construct and insert element at the end
		* Inserts a new element at the end of the vector, right after its current last element. This new element is constructed in place using args as the arguments for its constructor.
		* This effectively increases the container size by one, which causes an automatic reallocation of the allocated storage space if -and only if- the new vector size surpasses the current vector capacity.
		* The element is constructed in-place by calling allocator_traits::construct with args forwarded.
		* A similar member function exists, push_back, which either copies or moves an existing object into the container.
* [push_back() vs emplace_back() in C++ STL Vectors - GeeksforGeeks](https://www.geeksforgeeks.org/push_back-vs-emplace_back-in-cpp-stl-vectors/)
	* push_back():
		* This method is used to insert elements in a vector from the end of the container. As the flexibility in the size of the vector is dynamic, the size of the container also increased by 1 after inserting any new element.
		* Note: reserve() is used instead of using “vector\<Point> vertices(3)”, as the below syntax sometimes doesn’t work because there is no default constructor defined in the class.
	* emplace_back():
		* This method is used instead of creating the object using parameterized constructor and allocating it into a different memory, then passing it to the copy constructor, which will insert it into the vector. This function can directly insert the object without calling the copy constructor.
* [std::vector<T,Allocator>::resize - cppreference.com](https://en.cppreference.com/w/cpp/container/vector/resize)
	* changes the number of elements stored (public member function)
	* Resizes the container to contain count elements.
	* If the current size is greater than count, the container is reduced to its first count elements.
	* If the current size is less than count,
		* 1) additional default-inserted elements are appended
		* 2) additional copies of value are appended.
```c++
#include <iostream>
#include <vector>
 
int main()
{
    std::vector<int> c = {1, 2, 3};
    std::cout << "The vector holds: ";
    for (const auto& el: c) std::cout << el << ' ';
    std::cout << '\n';
 
    c.resize(5);
    std::cout << "After resize up to 5: ";
    for (const auto& el: c) std::cout << el << ' ';
    std::cout << '\n';
 
    c.resize(2);
    std::cout << "After resize down to 2: ";
    for (const auto& el: c) std::cout << el << ' ';
    std::cout << '\n';
 
    c.resize(6, 4);
    std::cout << "After resize up to 6 (initializer = 4): ";
    for (const auto& el: c) std::cout << el << ' ';
    std::cout << '\n';
}
/*
The vector holds: 1 2 3
After resize up to 5: 1 2 3 0 0
After resize down to 2: 1 2
After resize up to 6 (initializer = 4): 1 2 4 4 4 4
*/
```

##### Non-member functions

#### [std::deque](https://en.cppreference.com/w/cpp/container/deque)

* Defined in header `<deque>`
```c++
template<
    class T,
    class Allocator = std::allocator<T>
> class deque;  (1)	
namespace pmr {
    template< class T >
    using deque = std::deque<T, std::pmr::polymorphic_allocator<T>>;
}   (2)	(since C++17)
```
* `std::deque` (`double-ended queue`) is an indexed sequence container that allows `fast insertion and deletion` at both its `beginning` and its `end`. In addition, `insertion and deletion at either end of a deque never invalidates pointers or references to the rest of the elements`.
* As opposed to std::vector, the elements of a deque are `not` stored contiguously: typical implementations use a sequence of individually allocated fixed-size arrays, with additional bookkeeping, which means indexed access to deque must perform two pointer dereferences, compared to vector's indexed access which performs only one.
* The storage of a deque is automatically expanded and contracted as needed. Expansion of a deque is cheaper than the expansion of a std::vector because it does not involve copying of the existing elements to a new memory location. On the other hand, deques typically have large minimal memory cost; a deque holding just one element has to allocate its full internal array (e.g. 8 times the object size on 64-bit libstdc++; 16 times the object size or 4096 bytes, whichever is larger, on 64-bit libc++).
* The complexity (efficiency) of common operations on deques is as follows:
	* `Random access` - constant O(1)
	* `Insertion or removal of elements at the end or beginning` - constant O(1)
	* `Insertion or removal of elements` - linear O(n)
* std::deque meets the requirements of Container, AllocatorAwareContainer, SequenceContainer and ReversibleContainer.
* Example
```c++
#include <iostream>
#include <deque>
 
int main()
{
    // Create a deque containing integers
    std::deque<int> d = {7, 5, 16, 8};
 
    // Add an integer to the beginning and end of the deque
    d.push_front(13);
    d.push_back(25);
 
    // Iterate and print values of deque
    for(int n : d)
        std::cout << n << ' ';
}
/*
13 7 5 16 8 25
*/
```

##### Member functions

###### Capacity

* [std::deque<T,Allocator>::size](https://en.cppreference.com/w/cpp/container/deque/size)
    * Returns the number of elements in the container, i.e. `std::distance(begin(), end())`.

###### Modifiers

* [std::deque<T,Allocator>::erase](https://en.cppreference.com/w/cpp/container/deque/erase)
    * erases elements (public member function)
    * Erases the specified elements from the container.
        * 1) Removes the element at `pos`.
        * 2) Removes the elements in the range `[first, last)`.
    * All iterators and references are invalidated, unless the erased elements are at the `end` or the `beginning` of the container, in which case only the iterators and references to the erased elements are invalidated.
    * The past-the-end iterator is also invalidated unless the erased elements are at the beginning of the container and the last element is not erased.
    * The iterator `pos` must be valid and dereferenceable. Thus the [end()](https://en.cppreference.com/w/cpp/container/deque/end) iterator (which is valid, but is not dereferenceable) cannot be used as a value for `pos`.
    * The iterator `first` does not need to be dereferenceable if `first == last`: erasing an empty range is a no-op.
    * Return value
        * Iterator following the last removed element.
        * If `pos` refers to the last element, then the `end()` iterator is returned.
        * If `last == end()` prior to removal, then the updated `end()` iterator is returned.
        * If `[first, last)` is an empty range, then `last` is returned.
    * Exceptions
        * Does not throw unless an exception is thrown by the assignment operator of T.
    * Complexity
        * Linear: the number of calls to the destructor of T is the same as the number of elements erased, the number of calls to the assignment operator of T is no more than the lesser of the number of elements before the erased elements and the number of elements after the erased elements
    * Example
    ```c++
    #include <deque>
    #include <iostream>


    void print_container(const std::deque<int>& c) 
    {
        for (int i : c)
            std::cout << i << " ";
        std::cout << '\n';
    }

    int main( )
    {
        std::deque<int> c{0, 1, 2, 3, 4, 5, 6, 7, 8, 9};
        print_container(c);

        c.erase(c.begin());
        print_container(c);

        c.erase(c.begin()+2, c.begin()+5);
        print_container(c);

        // Erase all even numbers
        for (std::deque<int>::iterator it = c.begin(); it != c.end();)
        {
            if (*it % 2 == 0)
                it = c.erase(it);
            else
                ++it;
        }
        print_container(c);
    }
    /*
    0 1 2 3 4 5 6 7 8 9
    1 2 3 4 5 6 7 8 9
    1 2 6 7 8 9
    1 7 9
    */
    ```
* [std::deque<T,Allocator>::pop_back](https://en.cppreference.com/w/cpp/container/deque/pop_back)
    * Removes the last element of the container.
    * Calling pop_back on an empty container results in `undefined behavior`.
    * Iterators and references to the erased element are invalidated. The past-the-end iterator is also invalidated. Other references and iterators are not affected.
    * Example
    ```c++
    #include <deque>
    #include <iostream>

    template<typename T>
    void print(T const & xs)
    {
        std::cout << "[ ";
        for(auto const & x : xs) {
            std::cout << x << ' ';
        }
        std::cout << "]\n";
    }

    int main()
    {
        std::deque<int> numbers;

        print(numbers); 

        numbers.push_back(5);
        numbers.push_back(3);
        numbers.push_back(4);

        print(numbers); 

        numbers.pop_back();

        print(numbers); 
    }
    /*
    [ ]
    [ 5 3 4 ]
    [ 5 3 ]
    */
    ```
* [std::deque<T,Allocator>::push_front](https://en.cppreference.com/w/cpp/container/deque/push_front)    
    * inserts an element to the beginning (public member function)
    * Prepends the given element value to the beginning of the container.
    * All iterators, including the past-the-end iterator, are invalidated. No references are invalidated.
    * Complexity
        * Constant.
    * Exceptions
        * If an exception is thrown, this function has no effect (strong exception guarantee).
    * Example
    ```c++
    #include <deque>
    #include <iostream>
    #include <iomanip>
    #include <string>

    int main()
    {
        std::deque<std::string> letters;

        letters.push_front("abc");
        std::string s{"def"};
        letters.push_front(std::move(s));

        std::cout << "std::deque `letters` holds: ";
        for (auto&& e : letters) std::cout << std::quoted(e) << ' ';

        std::cout << "\nMoved-from string `s` holds: " << std::quoted(s) << '\n';
    }
    /*
    std::deque `letters` holds: "def" "abc" 
    Moved-from string `s` holds: ""
    */
    ```
    
##### MISC

* [Sliding Window Maximum (Maximum of all subarrays of size k) - GeeksforGeeks](https://www.geeksforgeeks.org/sliding-window-maximum-maximum-of-all-subarrays-of-size-k/#disqus_thread)
* [Deque-STL | HackerRank](https://www.hackerrank.com/challenges/deque-stl/problem)
```c++
#include <iostream>
#include <deque>
using namespace std;

void printKMax(int arr[], int n, int k){
    //Write your code here.
    deque<int>  queue(k);

    int i;
    // the first window with k elements
    for (i = 0; i < k; ++ i) {
        // remove smaller elements in queue
        while (!queue.empty() and arr[i] >= arr[queue.back()])
            queue.pop_back();
        // add new element
        queue.push_back(i);
    }

    // the remaining elements
    for (; i < n; ++ i) {
        cout << arr[queue.front()] << " ";

        // remove elements out of window
        while (!queue.empty() and queue.front() <= i - k)
            queue.pop_front();

        // remove smaller elements in queue
        while (!queue.empty() and arr[i] >= arr[queue.back()])
            queue.pop_back();

        // add new element
        queue.push_back(i);
    }

    // print the maximum element of the last window
    cout << arr[queue.front()] << endl;
}

int main(){

    int t;
    cin >> t;
    while(t>0) {
        int n,k;
        cin >> n >> k;
        int i;
        int arr[n];
        for(i=0;i<n;i++)
            cin >> arr[i];
        printKMax(arr, n, k);
        t--;
    }
    return 0;
}
```

#### [std::forward_list](https://en.cppreference.com/w/cpp/container/forward_list)

* std::forward_list is a container that supports fast insertion and removal of elements from anywhere in the container. Fast random access is not supported. It is implemented as a singly-linked list. Compared to std::list this container provides more space efficient storage when bidirectional iteration is not needed.
* Adding, removing and moving the elements within the list, or across several lists, does not invalidate the iterators currently referring to other elements in the list. However, an iterator or reference referring to an element is invalidated when the corresponding element is removed (via erase_after) from the list.
* std::forward_list meets the requirements of Container (except for the size member function and that operator=='s complexity is always linear), AllocatorAwareContainer and SequenceContainer.
* [std::forward_list<T,Allocator>::emplace_front - cppreference.com](https://en.cppreference.com/w/cpp/container/forward_list/emplace_front)
	* Inserts a new element to the beginning of the container. The element is constructed through std::allocator_traits::construct, which typically uses placement-new to construct the element in-place at the location provided by the container. The arguments args... are forwarded to the constructor as std::forward\<Args>(args)....
	* No iterators or references are invalidated.
* [std::forward_list<T,Allocator>::reverse - cppreference.com](https://en.cppreference.com/w/cpp/container/forward_list/reverse)
	* Reverses the order of the elements in the container. No references or iterators become invalidated.
* [std::forward_list<T,Allocator>::sort - cppreference.com](https://en.cppreference.com/w/cpp/container/forward_list/sort)
	* Sorts the elements in ascending order. The order of equal elements is preserved. The first version uses operator< to compare the elements, the second version uses the given comparison function comp.
	* If an exception is thrown, the order of elements in *this is unspecified.
```c++
#include <iostream>
#include <forward_list>

std::ostream& operator<<(std::ostream& ostr, const std::forward_list<int>& list)
{
    for (auto &i : list) {
        ostr << " " << i;
    }
    return ostr;
}

int main()
{
    std::forward_list<int> list = { 8,7,5,9,0,1,3,2,6,4 };

    list.emplace_front(10);

    std::cout << "before:     " << list << "\n";    // before:      10 8 7 5 9 0 1 3 2 6 4

    list.sort();
    std::cout << "ascending:  " << list << "\n";    // ascending:   0 1 2 3 4 5 6 7 8 9 10

    list.reverse();
    std::cout << "descending: " << list << "\n";    // descending:  10 9 8 7 6 5 4 3 2 1 0

    return 0;
}
```

#### [std::list](https://en.cppreference.com/w/cpp/container/list)

* Defined in header `<list>`
```c++
template<
    class T,
    class Allocator = std::allocator<T>
> class list;   (1)	
namespace pmr {
    template <class T>
    using list = std::list<T, std::pmr::polymorphic_allocator<T>>;
}   (2)	(since C++17)
```
* std::list is a container that supports `constant time` `insertion and removal of elements from anywhere` in the container. `Fast random access` is `not` supported. It is usually implemented as a `doubly-linked list`. Compared to `std::forward_list` this container provides `bidirectional iteration` capability while being `less space efficient`.
* Adding, `removing and moving` the elements within the list or across several lists does `not invalidate` the iterators or references. An iterator is invalidated `only` when the corresponding element is `deleted`.
* std::list meets the requirements of Container, AllocatorAwareContainer, SequenceContainer and ReversibleContainer.
```c++
#include <algorithm>
#include <iostream>
#include <list>
 
int main()
{
    // Create a list containing integers
    std::list<int> l = {7, 5, 16, 8};
 
    // Add an integer to the front of the list
    l.push_front(25);
    // Add an integer to the back of the list
    l.push_back(13);
 
    // Insert an integer before 16 by searching
    auto it = std::find(l.begin(), l.end(), 16);
    if (it != l.end())
        l.insert(it, 42);
 
    // Print out the list
    std::cout << "l = { ";
    for (int n : l)
        std::cout << n << ", ";
    std::cout << "};\n";
}
/*
l = { 25, 7, 5, 42, 16, 8, 13, };
*/
```

##### Member functions

###### Element access

* [std::list<T,Allocator>::front - cppreference.com](https://en.cppreference.com/w/cpp/container/list/front)
    * access the first element (public member function)
    * Returns a reference to the first element in the container.
    * Calling front on an empty container is undefined.
    * Complexity
        * Constant
    * Notes
        * For a container c, the expression c.front() is equivalent to *c.begin().
```c++
#include <list>
#include <iostream>
 
int main()
{
    std::list<char> letters {'o', 'm', 'g', 'w', 't', 'f'};
 
    if (!letters.empty()) {
        std::cout << "The first character is '" << letters.front() << "'.\n";
    }  
}
/*
The first character is 'o'.
*/
```
* [std::list<T,Allocator>::back - cppreference.com](https://en.cppreference.com/w/cpp/container/list/back)
    * access the last element (public member function)
    * Returns a reference to the last element in the container.
    * Calling back on an empty container causes undefined behavior.
    * Complexity
        * Constant.
    * Notes
        * For a non-empty container c, the expression c.back() is equivalent to *std::prev(c.end())

###### Modifiers

* [std::list<T,Allocator>::erase - cppreference.com](https://en.cppreference.com/w/cpp/container/list/erase)
    * erases elements (public member function)
    * `iterator erase( const_iterator pos ); (1) (since C++11)`
    * `iterator erase( const_iterator first, const_iterator last ); (2) (since C++11)`
    * Erases the specified elements from the container.
        * 1) Removes the element at pos.
        * 2) Removes the elements in the range \[first, last).
    * References and iterators to the erased elements are invalidated. Other references and iterators are not affected.
    * The iterator `pos` must be valid and dereferenceable. Thus the [end()](https://en.cppreference.com/w/cpp/container/list/end) iterator (which is valid, but is not dereferenceable) cannot be used as a value for `pos`.
    * The iterator `first` does not need to be dereferenceable if `first == last`: erasing an empty range is a no-op.
    * Parameters
        * pos	-	iterator to the element to remove
        * first, last	-	range of elements to remove
    * Return value
        * Iterator following the last removed element.
        * If `pos` refers to the last element, then the `end()` iterator is returned.
        * If `last == end()` prior to removal, then the updated `end()` iterator is returned.
        * If `[first, last)` is an empty range, then `last` is returned.
    * Exceptions
        * (none)
    * Complexity
        * 1) Constant.
        * 2) Linear in the distance between `first` and `last`.
```c++
#include <list>
#include <iostream>
#include <iterator>
 
void print_container(const std::list<int>& c) 
{
    for (int i : c)
        std::cout << i << " ";
    std::cout << '\n';
}
 
int main( )
{
    std::list<int> c{0, 1, 2, 3, 4, 5, 6, 7, 8, 9};
    print_container(c);
 
    c.erase(c.begin());
    print_container(c);
 
    std::list<int>::iterator range_begin = c.begin();
    std::list<int>::iterator range_end = c.begin();
    std::advance(range_begin,2);
    std::advance(range_end,5);
 
    c.erase(range_begin, range_end);
    print_container(c);
 
    // Erase all even numbers
    for (std::list<int>::iterator it = c.begin(); it != c.end();)
    {
        if (*it % 2 == 0)
            it = c.erase(it);
        else
            ++it;
    }
    print_container(c);
}
/*
0 1 2 3 4 5 6 7 8 9
1 2 3 4 5 6 7 8 9
1 2 6 7 8 9
1 7 9
*/
```
* [std::list<T,Allocator>::push_back - cppreference.com](https://en.cppreference.com/w/cpp/container/list/push_back)
    * adds an element to the end (public member function)
    * Appends the given element value to the end of the container.
        * 1) The new element is initialized as a copy of value.
        * 2) value is moved into the new element.
    * No iterators or references are invalidated.
    * Complexity
        * Constant.
    * Exceptions
        * If an exception is thrown (which can be due to Allocator::allocate() or element copy/move constructor/assignment), this function has no effect (strong exception guarantee).
```c++
#include <list>
#include <iostream>
#include <iomanip>
#include <string>
 
int main()
{
    std::list<std::string> letters;
 
    letters.push_back("abc");
    std::string s{"def"};
    letters.push_back(std::move(s));
 
    std::cout << "std::list `letters` holds: ";
    for (auto&& e : letters) std::cout << std::quoted(e) << ' ';
 
    std::cout << "\nMoved-from string `s` holds: " << std::quoted(s) << '\n';
}
/*
std::list `letters` holds: "abc" "def" 
Moved-from string `s` holds: ""
*/
```
* [std::list<T,Allocator>::emplace_back - cppreference.com](https://en.cppreference.com/w/cpp/container/list/emplace_back)
    * constructs an element in-place at the end (public member function)
    * Appends a new element to the end of the container. The element is constructed through std::allocator_traits::construct, which typically uses placement-new to construct the element in-place at the location provided by the container. The arguments `args...` are forwarded to the constructor as `std::forward<Args>(args)...`.
    * No iterators or references are invalidated.
    * Return value
        * (none)    (until C++17)
        * A reference to the inserted element.  (since C++17)
    * Complexity
        * Constant.
    * Exceptions
        * If an exception is thrown, this function has no effect (strong exception guarantee).
    * Example
        * The following code uses emplace_back to append an object of type President to a `std::list`. It demonstrates how emplace_back forwards parameters to the President constructor and shows how using emplace_back avoids the extra copy or move operation required when using push_back.
```c++
#include <list>
#include <string>
#include <cassert>
#include <iostream>
 
struct President
{
    std::string name;
    std::string country;
    int year;
 
    President(std::string p_name, std::string p_country, int p_year)
        : name(std::move(p_name)), country(std::move(p_country)), year(p_year)
    {
        std::cout << "I am being constructed.\n";
    }
    President(President&& other)
        : name(std::move(other.name)), country(std::move(other.country)), year(other.year)
    {
        std::cout << "I am being moved.\n";
    }
    President& operator=(const President& other) = default;
};
 
int main()
{
    std::list<President> elections;
    std::cout << "emplace_back:\n";
    auto& ref = elections.emplace_back("Nelson Mandela", "South Africa", 1994);
    assert(ref.year == 1994 && "uses a reference to the created object (C++17)");
 
    std::list<President> reElections;
    std::cout << "\npush_back:\n";
    reElections.push_back(President("Franklin Delano Roosevelt", "the USA", 1936));
 
    std::cout << "\nContents:\n";
    for (President const& president: elections) {
        std::cout << president.name << " was elected president of "
                  << president.country << " in " << president.year << ".\n";
    }
    for (President const& president: reElections) {
        std::cout << president.name << " was re-elected president of "
                  << president.country << " in " << president.year << ".\n";
    }
}
/*
emplace_back:
I am being constructed.
 
push_back:
I am being constructed.
I am being moved.
 
Contents:
Nelson Mandela was elected president of South Africa in 1994.
Franklin Delano Roosevelt was re-elected president of the USA in 1936.
*/
```
* [std::list<T,Allocator>::pop_back - cppreference.com](https://en.cppreference.com/w/cpp/container/list/pop_back)
    * removes the last element (public member function)
    * Removes the last element of the container.
    * Calling pop_back on an empty container results in undefined behavior.
    * References and iterators to the erased element are invalidated.
    * Complexity
        * Constant.
    * Exceptions
        * Throws nothing.
* [std::list<T,Allocator>::push_front - cppreference.com](https://en.cppreference.com/w/cpp/container/list/push_front)
    * inserts an element to the beginning (public member function)
    * Prepends the given element value to the beginning of the container.
    * No iterators or references are invalidated.
    * Complexity
        * Constant.
    * Exceptions
        * If an exception is thrown, this function has no effect (strong exception guarantee).
* [std::list<T,Allocator>::emplace_front - cppreference.com](https://en.cppreference.com/w/cpp/container/list/emplace_front)
    * constructs an element in-place at the beginning (public member function)
    * Inserts a new element to the beginning of the container. The element is constructed through std::allocator_traits::construct, which typically uses placement-new to construct the element in-place at the location provided by the container. The arguments args... are forwarded to the constructor as std::forward\<Args>(args)....
    * No iterators or references are invalidated.
    * Complexity
        * Constant.
    * Exceptions
        * If an exception is thrown, this function has no effect (strong exception guarantee).
* [std::list<T,Allocator>::pop_front - cppreference.com](https://en.cppreference.com/w/cpp/container/list/pop_front)
    * removes the first element (public member function)
    * Removes the first element of the container. If there are no elements in the container, the behavior is undefined.
    * References and iterators to the erased element are invalidated.
    * Complexity
        * Constant.
    * Exceptions
        * Does not throw.
```c++
#include <list>
#include <iostream>
 
int main()
{
    std::list<char> chars{'A', 'B', 'C', 'D'};
 
    for (; !chars.empty(); chars.pop_front())
    {
        std::cout << "chars.front(): '" << chars.front() << "'\n";
    }
}
/*
chars.front(): 'A'
chars.front(): 'B'
chars.front(): 'C'
chars.front(): 'D'
*/
```

### Associative

* Associative containers implement sorted data structures that can be quickly searched (O(log n) complexity).

| set | collection of unique keys, sorted by keys |
| - | - |
| map | collection of key-value pairs, sorted by keys, keys are unique | 
| multiset | collection of keys, sorted by keys | 
| multimap | collection of key-value pairs, sorted by keys

#### [std::set](https://en.cppreference.com/w/cpp/container/set)

* std::set is an associative container that contains a sorted set of unique objects of type Key. Sorting is done using the key comparison function Compare. Search, removal, and insertion operations have logarithmic complexity. Sets are usually implemented as red-black trees.
* Everywhere the standard library uses the Compare requirements, uniqueness is determined by using the equivalence relation. In imprecise terms, two objects a and b are considered equivalent if neither compares less than the other: !comp(a, b) && !comp(b, a).
* std::set meets the requirements of Container, AllocatorAwareContainer, AssociativeContainer and ReversibleContainer.

##### Member functions

###### Modifiers

#
* [std::set<Key,Compare,Allocator>::insert - cppreference.com](https://en.cppreference.com/w/cpp/container/set/insert)
    * inserts elements `or nodes (since C++17)` (public member function)
	* Inserts element(s) into the container, if the container doesn't already contain an element with an equivalent key.
```c++
#include <set>
#include <cassert>
#include <iostream>
 
int main()
{
    std::set<int> set;
 
    auto result_1 = set.insert(3);
    assert(result_1.first != set.end()); // it is a valid iterator
    assert(*result_1.first == 3);
    if (result_1.second)
        std::cout << "insert done\n";
 
    auto result_2 = set.insert(3);
    assert(result_2.first == result_1.first); // same iterator
    assert(*result_2.first == 3);
    if (!result_2.second)
        std::cout << "no insertion\n";
}
/*
insert done
no insertion
*/
```
* Need to check if key exists before call std::set::insert() or not?
    * No, it is not necessary to check if the key exists before calling std::set::insert(). The insert() function of std::set will automatically check if the key already exists in the set and will not add it again if it does. This is because the keys in a std::set are unique, and adding a duplicate key would violate that property.
    * So, you can safely call std::set::insert() with a key, and the function will take care of checking if it already exists. If the key does not exist, it will be added to the set, and if it does, nothing will happen.
#
* [std::set<Key,Compare,Allocator>::erase - cppreference.com](https://en.cppreference.com/w/cpp/container/set/erase)
    * erases elements (public member function)
	* Removes specified elements from the container.
	* 1) Removes the element at pos. Only one overload is provided if iterator and const_iterator are the same type. (since C++11)
	* 2) Removes the elements in the range \[first; last), which must be a valid range in *this.
	* 3) Removes the element (if one exists) with the key equivalent to key.
	* 4) Removes the element (if one exists) with key that compares equivalent to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type, and neither iterator nor const_iterator is implicitly convertible from K. It allows calling this function without constructing an instance of Key.
	* References and iterators to the erased elements are invalidated. Other references and iterators are not affected.
	* The iterator pos must be valid and dereferenceable. Thus the end() iterator (which is valid, but is not dereferenceable) cannot be used as a value for pos.

###### Lookup

* [std::set<Key,Compare,Allocator>::count - cppreference.com](https://en.cppreference.com/w/cpp/container/set/count)
    * returns the number of elements matching specific key (public member function)
	* Returns the number of elements with key that compares equivalent to the specified argument, which is either 1 or 0 since this container does not allow duplicates.
	* 1) Returns the number of elements with key key.
	* 2) Returns the number of elements with key that compares equivalent to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type. They allow calling this function without constructing an instance of Key.
* [std::set<Key,Compare,Allocator>::find - cppreference.com](https://en.cppreference.com/w/cpp/container/set/find)
    * finds element with specific key (public member function)
	* 1,2) Finds an element with key equivalent to key.
	* 3,4) Finds an element with key that compares equivalent to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type. It allows calling this function without constructing an instance of Key.
	* [set find() function in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/set-find-function-in-c-stl/)
		* The set::find is a built-in function in C++ STL which returns an iterator to the element which is searched in the set container. If the element is not found,  then the iterator points to the position just after the last element in the set.
		* Time Complexity: The time complexity of set_name.find( key ) is O( log N ). As the elements are stored in a sorted manner by default.
```c++
#include <iostream>
#include <set>
 
struct FatKey   { int x; int data[1000]; };
struct LightKey { int x; };
// Note: as detailed above, the container must use std::less<> (or other 
//   transparent Comparator) to access these overloads.
// This includes standard overloads, such as between std::string and std::string_view.
bool operator<(const FatKey& fk, const LightKey& lk) { return fk.x < lk.x; }
bool operator<(const LightKey& lk, const FatKey& fk) { return lk.x < fk.x; }
bool operator<(const FatKey& fk1, const FatKey& fk2) { return fk1.x < fk2.x; }
 
int main()
{  
// simple comparison demo
    std::set<int> example = {1, 2, 3, 4};
 
    auto search = example.find(2);
    if (search != example.end()) {
        std::cout << "Found " << (*search) << '\n';
    } else {
        std::cout << "Not found\n";
    }
 
// transparent comparison demo
    std::set<FatKey, std::less<>> example2 = { {1, {} }, {2, {} }, {3, {} }, {4, {} } };
 
    LightKey lk = {2};
    auto search2 = example2.find(lk);
    if (search2 != example2.end()) {
        std::cout << "Found " << search2->x << '\n';
    } else {
        std::cout << "Not found\n";
    }
}
```
* [std::set<Key,Compare,Allocator>::contains - cppreference.com](https://en.cppreference.com/w/cpp/container/set/contains)
    * checks if the container contains element with specific key (public member function)
	* 1) Checks if there is an element with key equivalent to key in the container.
	* 2) Checks if there is an element with key that compares equivalent to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type. It allows calling this function without constructing an instance of Key.

#### [std::map](https://en.cppreference.com/w/cpp/container/map)

* Defined in header `<map>`
```c++
template<
    class Key,
    class T,
    class Compare = std::less<Key>,
    class Allocator = std::allocator<std::pair<const Key, T>>
> class map;    (1)	
namespace pmr {
    template< class Key, class T, class Compare = std::less<Key> >
    using map = std::map<
        Key, T, Compare,
        std::pmr::polymorphic_allocator<std::pair<const Key, T>>
    >;
}   (2)	(since C++17)
```
* std::map is a `sorted associative container` that contains `key-value pairs` with `unique keys`. Keys are sorted by using the comparison function Compare. Search, removal, and insertion operations have `logarithmic complexity`. Maps are usually implemented as [red-black trees](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree).
* Everywhere the standard library uses the Compare requirements, uniqueness is determined by using the equivalence relation. In imprecise terms, two objects `a` and `b` are considered equivalent (not unique) if neither compares less than the other: `!comp(a, b) && !comp(b, a)`.
* std::map meets the requirements of Container, AllocatorAwareContainer, AssociativeContainer and ReversibleContainer.
* Example
```c++
#include <iostream>
#include <map>
#include <string>
#include <string_view>
 
void print_map(std::string_view comment, const std::map<std::string, int>& m)
{
    std::cout << comment;
    // iterate using C++17 facilities
    for (const auto& [key, value] : m)
        std::cout << '[' << key << "] = " << value << "; ";
 
// C++11 alternative:
//  for (const auto& n : m)
//      std::cout << n.first << " = " << n.second << "; ";
//
// C++98 alternative
//  for (std::map<std::string, int>::const_iterator it = m.begin(); it != m.end(); it++)
//      std::cout << it->first << " = " << it->second << "; ";
 
    std::cout << '\n';
}
 
int main()
{
    // Create a map of three (string, int) pairs
    std::map<std::string, int> m{{"CPU", 10}, {"GPU", 15}, {"RAM", 20}};
 
    print_map("1) Initial map: ", m);
 
    m["CPU"] = 25; // update an existing value
    m["SSD"] = 30; // insert a new value
    print_map("2) Updated map: ", m);
 
    // using operator[] with non-existent key always performs an insert
    std::cout << "3) m[UPS] = " << m["UPS"] << '\n';
    print_map("4) Updated map: ", m);
 
    m.erase("GPU");
    print_map("5) After erase: ", m);
 
    std::erase_if(m, [](const auto& pair){ return pair.second > 25; });
    print_map("6) After erase: ", m);
    std::cout << "7) m.size() = " << m.size() << '\n';
 
    m.clear();
    std::cout << std::boolalpha << "8) Map is empty: " << m.empty() << '\n';
}
/*
1) Initial map: [CPU] = 10; [GPU] = 15; [RAM] = 20; 
2) Updated map: [CPU] = 25; [GPU] = 15; [RAM] = 20; [SSD] = 30; 
3) m[UPS] = 0
4) Updated map: [CPU] = 25; [GPU] = 15; [RAM] = 20; [SSD] = 30; [UPS] = 0; 
5) After erase: [CPU] = 25; [RAM] = 20; [SSD] = 30; [UPS] = 0; 
6) After erase: [CPU] = 25; [RAM] = 20; [UPS] = 0; 
7) m.size() = 3
8) Map is empty: true
*/
```

##### Member functions

###### [std::map<Key,T,Compare,Allocator>::map](https://en.cppreference.com/w/cpp/container/map/map)

* constructs the map (public member function)
* Constructs new container from a variety of data sources and optionally using user supplied allocator alloc or comparison function object comp.
* [Copy a map in C++ | Techie Delight](https://www.techiedelight.com/copy-a-map-in-cpp/)
    * 1. Using copy constructor
    * 2. Using std::map::insert
    * 3. Using std::copy 
* [Descending Order in Map and Multimap of C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/descending-order-map-multimap-c-stl/)
	* We can use the third parameter, that is std::greater along with map and multimap to store elements in descending order.
	* Descending order in the map: 
		* A map stores key-value pairs. A self-balancing-BST (typically Red-Black tree) is used to implement it.
```c++
map<key_datatype, value_datatype, greater<int> > mapName;
```

###### Element access

* [map::operator[] - C++ Reference](http://www.cplusplus.com/reference/map/map/operator[]/)
	* access or insert specified element (public member function)
	* If k matches the key of an element in the container, the function returns a reference to its mapped value.
	* If k does not match the key of any element in the container, the function inserts a new element with that key and returns a reference to its mapped value. Notice that this always increases the container size by one, even if no mapped value is assigned to the element (the element is constructed using its default constructor).
	* A similar member function, map::at, has the same behavior when an element with the key exists, but throws an exception when it does not.
	* A call to this function is equivalent to:
		* (*((this->insert(make_pair(k,mapped_type()))).first)).second
* !!! DON'T use double as the key as it could not be found due to the double precision
	* [c++ - Floating point keys in std:map - Stack Overflow](https://stackoverflow.com/questions/6684573/floating-point-keys-in-stdmap)
	* use static_cast\<int>(std::round(key * 10)) as key instead

###### Iterators

* [std::map<Key,T,Compare,Allocator>::begin, std::map<Key,T,Compare,Allocator>::cbegin - cppreference.com](https://en.cppreference.com/w/cpp/container/map/begin)
	* Returns an iterator to the first element of the map.
	* If the map is empty, the returned iterator will be equal to end().
	* returns an iterator to the beginning (public member function)
	* [map::cbegin - C++ Reference](http://www.cplusplus.com/reference/map/map/cbegin/)
		* Return const_iterator to beginning
			* Returns a const_iterator pointing to the first element in the container.
			* A const_iterator is an iterator that points to const content. This iterator can be increased and decreased (unless it is itself also const), just like the iterator returned by map::begin, but it cannot be used to modify the contents it points to, even if the map object is not itself const.
			* If the container is empty, the returned iterator value shall not be dereferenced.
	* [map::begin() and end() in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/mapbegin-end-c-stl/)
	* [map cbegin() and cend() function in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/map-cbegin-and-cend-function-in-c-stl/)
		* `for (auto itr = mp.cbegin(); itr != mp.cend(); ++ itr) {}`
* [std::map<Key,T,Compare,Allocator>::end, std::map<Key,T,Compare,Allocator>::cend - cppreference.com](https://en.cppreference.com/w/cpp/container/map/end)
	* returns an iterator to the end (public member function)
	* Returns an iterator to the element following the last element of the map.
	* This element acts as a placeholder; attempting to access it results in undefined behavior.
* [std::map<Key,T,Compare,Allocator>::rbegin, std::map<Key,T,Compare,Allocator>::crbegin - cppreference.com](https://en.cppreference.com/w/cpp/container/map/rbegin)
	* returns a reverse iterator to the beginning (public member function)
	* [map rbegin() function in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/map-rbegin-function-in-c-stl/)
	* [c++ - Last key in a std::map - Stack Overflow](https://stackoverflow.com/questions/289715/last-key-in-a-stdmap)
		* `map.rbegin()->first`
* [std::map<Key,T,Compare,Allocator>::rend, std::map<Key,T,Compare,Allocator>::crend - cppreference.com](https://en.cppreference.com/w/cpp/container/map/rend)
	* returns a reverse iterator to the end (public member function)
	* Returns a reverse iterator to the element following the last element of the reversed map. It corresponds to the element preceding the first element of the non-reversed map. This element acts as a placeholder, attempting to access it results in undefined behavior.

###### Capacity

* [std::map<Key,T,Compare,Allocator>::empty - cppreference.com](https://en.cppreference.com/w/cpp/container/map/empty)
	* checks whether the container is empty (public member function)
	* Checks if the container has no elements, i.e. whether begin() == end().
	* Return value
		* true if the container is empty, false otherwise
	* Complexity
		* Constant. 

###### Modifiers

* [std::map<Key,T,Compare,Allocator>::clear - cppreference.com](https://en.cppreference.com/w/cpp/container/map/clear)
	* clears the contents (public member function)
	* Erases all elements from the container. After this call, size() returns zero.
	* Invalidates any references, pointers, or iterators referring to contained elements. Any past-the-end iterator remains valid.
* [std::map<Key,T,Compare,Allocator>::insert - cppreference.com](https://en.cppreference.com/w/cpp/container/map/insert)
	* inserts elements or nodes (since C++17) (public member function)
	* Inserts element(s) into the container, if the container doesn't already contain an element with an equivalent key.
```c++
#include <iomanip>
#include <iostream>
#include <map>
#include <string>
 
using namespace std::literals;
 
template<typename It>
void printInsertionStatus(It it, bool success)
{
    std::cout << "Insertion of " << it->first << (success ? " succeeded\n" : " failed\n");
}
 
int main()
{
    std::map<std::string, float> karasunoPlayerHeights;
 
    // Overload 3: insert from rvalue reference
    const auto [it_hinata, success] = karasunoPlayerHeights.insert({"Hinata"s, 162.8});
    printInsertionStatus(it_hinata, success);
 
    {
        // Overload 1: insert from lvalue reference
        const auto [it, success2] = karasunoPlayerHeights.insert(*it_hinata);
        printInsertionStatus(it, success2);
    }
    {
        // Overload 2: insert via forwarding to emplace
        const auto [it, success] = karasunoPlayerHeights.insert(std::pair{"Kageyama", 180.6});
        printInsertionStatus(it, success);
    }
 
    {
        // Overload 6: insert from rvalue reference with positional hint
        const std::size_t n = std::size(karasunoPlayerHeights);
        const auto it = karasunoPlayerHeights.insert(it_hinata, {"Azumane"s, 184.7});
        printInsertionStatus(it, std::size(karasunoPlayerHeights) != n);
    }
    {
        // Overload 4: insert from lvalue reference with positional hint
        const std::size_t n = std::size(karasunoPlayerHeights);
        const auto it = karasunoPlayerHeights.insert(it_hinata, *it_hinata);
        printInsertionStatus(it, std::size(karasunoPlayerHeights) != n);
    }
    {
        // Overload 5: insert via forwarding to emplace with positional hint
        const std::size_t n = std::size(karasunoPlayerHeights);
        const auto it = karasunoPlayerHeights.insert(it_hinata, std::pair{"Tsukishima", 188.3});
        printInsertionStatus(it, std::size(karasunoPlayerHeights) != n);
    }
 
    auto node_hinata = karasunoPlayerHeights.extract(it_hinata);
    std::map<std::string, float> playerHeights;
 
    // Overload 7: insert from iterator range
    playerHeights.insert(std::begin(karasunoPlayerHeights), std::end(karasunoPlayerHeights));
 
    // Overload 8: insert from initializer_list
    playerHeights.insert({{"Kozume"s, 169.2}, {"Kuroo", 187.7}});
 
 
    // Overload 9: insert node
    const auto status = playerHeights.insert(std::move(node_hinata));
    printInsertionStatus(status.position, status.inserted);
 
    node_hinata = playerHeights.extract(status.position);
    {
        // Overload 10: insert node with positional hint
        const std::size_t n = std::size(playerHeights);
        const auto it = playerHeights.insert(std::begin(playerHeights), std::move(node_hinata));
        printInsertionStatus(it, std::size(playerHeights) != n);
    }
 
 
    // Print resulting map
    std::cout << std::left << '\n';
    for (const auto& [name, height] : playerHeights)
        std::cout << std::setw(10) << name << " | " << height << "cm\n";
}
```
```c++
#include <iostream>
#include <map>


int main()
{
    std::map<uint64_t, double> myMap{ {1, 1}, {2, 2}, {3, 3} };

    for (auto it : myMap) {
        std::cout << it.first << " : " << it.second << "\n";
    }
    std::cout << "\n";

    myMap.insert(std::pair(3, 0));  // not inserted
    for (auto it : myMap) {
        std::cout << it.first << " : " << it.second << "\n";
    }
    std::cout << "\n";

    myMap.insert_or_assign(3, 0);   // assigned
    for (auto it : myMap) {
        std::cout << it.first << " : " << it.second << "\n";
    }
    std::cout << "\n";

    return 0;
}
/*
1 : 1
2 : 2
3 : 3

1 : 1
2 : 2
3 : 3

1 : 1
2 : 2
3 : 0
*/
```
* [std::map<Key,T,Compare,Allocator>::insert_or_assign - cppreference.com](https://en.cppreference.com/w/cpp/container/map/insert_or_assign)
	* inserts an element or assigns to the current element if the key already exists (public member function)
	* Notes
		* insert_or_assign returns more information than operator[] and does not require default-constructibility of the mapped type.
```c++
#include <iostream>
#include <map>
#include <string>
 
auto print_node = [](const auto &node) {
    std::cout << "[" << node.first << "] = " << node.second << '\n';
};
 
auto print_result = [](auto const &pair) {
    std::cout << (pair.second ? "inserted: " : "assigned: ");
    print_node(*pair.first);
};
 
int main()
{
    std::map<std::string, std::string> myMap;
 
    print_result( myMap.insert_or_assign("a", "apple"     ) );
    print_result( myMap.insert_or_assign("b", "banana"    ) );
    print_result( myMap.insert_or_assign("c", "cherry"    ) );
    print_result( myMap.insert_or_assign("c", "clementine") );
 
    for (const auto &node : myMap) { print_node(node); }
}
/*
inserted: [a] = apple
inserted: [b] = banana
inserted: [c] = cherry
assigned: [c] = clementine
[a] = apple
[b] = banana
[c] = clementine
*/
```
* [std::map<Key,T,Compare,Allocator>::erase - cppreference.com](https://en.cppreference.com/w/cpp/container/map/erase)
	* Removes specified elements from the container.
	* 1) Removes the element at pos.
	* 2) Removes the elements in the range \[first; last), which must be a valid range in *this.
	* 3) Removes the element (if one exists) with the key equivalent to key.
	* 4) Removes the element (if one exists) with key that compares equivalent to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type, and neither iterator nor const_iterator is implicitly convertible from K. It allows calling this function without constructing an instance of Key.
	* References and iterators to the erased elements are invalidated. Other references and iterators are not affected.
	* The iterator pos must be valid and dereferenceable. Thus the end() iterator (which is valid, but is not dereferenceable) cannot be used as a value for pos.
```c++
#include <map>
#include <iostream>
int main()
{
    std::map<int, std::string> c = {
        {1, "one" }, {2, "two" }, {3, "three"},
        {4, "four"}, {5, "five"}, {6, "six"  }
    };
 
    // erase all odd numbers from c
    for(auto it = c.begin(); it != c.end(); ) {
        if(it->first % 2 != 0)
            it = c.erase(it);
        else
            ++it;
    }
 
    for(auto& p : c) {
        std::cout << p.second << ' ';
    }
}
```
* [std::map<Key,T,Compare,Allocator>::extract - cppreference.com](https://en.cppreference.com/w/cpp/container/map/extract)
	* extracts nodes from the container (public member function)
	* [How to Modify a Key in a C++ Map or Set - Fluent C++](https://www.fluentcpp.com/2020/05/01/how-to-change-a-key-in-a-map-or-set-in-cpp/)
```c++
auto myMap = std::map<std::string, int>{ {"one", 1}, {"two", 2}, {"three", 3} };

auto node = myMap.extract("two");
if (!node.empty())
{
    node.key() = "dos";
    myMap.insert(std::move(node));
}

template<typename Container>
void replaceKey(Container& container,
                const typename Container::key_type& oldKey,
                const typename Container::key_type& newKey)
{
    auto node = container.extract(oldKey);
    if(!node.empty())
    {
        node.key() = newKey;
        container.insert(std::move(node));
    }
}
```
* [现代C++编程实践(三)—虐虐map容器](https://mp.weixin.qq.com/s/Pp9Gbp_NYqaTYHbqkQ09AQ)
* [std::map<Key,T,Compare,Allocator>::merge - cppreference.com](https://en.cppreference.com/w/cpp/container/map/merge)
	* splices nodes from another container (public member function)
	* Attempts to extract ("splice") each element in source and insert it into *this using the comparison object of *this. If there is an element in *this with key equivalent to the key of an element from source, then that element is not extracted from source. No elements are copied or moved, only the internal pointers of the container nodes are repointed. All pointers and references to the transferred elements remain valid, but now refer into *this, not into source.
	* The behavior is undefined if get_allocator() != source.get_allocator().
	* Parameters
		* source	-	compatible container to transfer the nodes from
	* Return value
		* (none)
	* Exceptions
		* Does not throw unless comparison throws.
	* Complexity
		* N*log(size()+N)), where N is source.size().
	* [Merge two maps, summing values for same keys in C++ - Stack Overflow](https://stackoverflow.com/questions/20771786/merge-two-maps-summing-values-for-same-keys-in-c)
```c++
#include <map>
#include <iostream>
#include <string>
 
int main()
{
  std::map<int, std::string> ma {{1, "apple"}, {5, "pear"}, {10, "banana"}};
  std::map<int, std::string> mb {{2, "zorro"}, {4, "batman"}, {5, "X"}, {8, "alpaca"}};
  std::map<int, std::string> u;

  std::cout << "u.size(): " << u.size() << '\n';
  std::cout << "ma.size(): " << ma.size() << '\n';

  u.merge(ma);

  std::cout << "u.size(): " << u.size() << '\n';
  std::cout << "ma.size(): " << ma.size() << '\n';

  u.merge(mb);

  std::cout << "mb.size(): " << mb.size() << '\n';
  std::cout << "mb.at(5): " << mb.at(5) << '\n';

  for(auto const &kv: u)
    std::cout << kv.first << ", " << kv.second << '\n';
}

/*
u.size(): 0
ma.size(): 3
u.size(): 3
ma.size(): 0
mb.size(): 1
mb.at(5): X
1, apple
2, zorro
4, batman
5, pear
8, alpaca
10, banana
*/
```

###### Lookup

* [std::map<Key,T,Compare,Allocator>::find - cppreference.com](https://en.cppreference.com/w/cpp/container/map/find)
	* finds element with specific key (public member function)
	* Return value
		* Iterator to an element with key equivalent to key. If no such element is found, past-the-end (see end()) iterator is returned.
	* Complexity
		* Logarithmic in the size of the container.
```c++
std::map<int,char> example = {{1,'a'},{2,'b'}};

auto search = example.find(2);
if (search != example.end()) {
    std::cout << "Found " << search->first << " " << search->second << '\n';
} else {
    std::cout << "Not found\n";
}
```
* [c++ - Most efficient way to access specific key of a map with an iterator? - Stack Overflow](https://stackoverflow.com/questions/23973879/most-efficient-way-to-access-specific-key-of-a-map-with-an-iterator)
	* `map<string,int>::iterator it = mymap.find("Node");`
* [std::map<Key,T,Compare,Allocator>::contains - cppreference.com](https://en.cppreference.com/w/cpp/container/map/contains)
	* checks if the container contains element with specific key (public member function)
* [std::map<Key,T,Compare,Allocator>::equal_range - cppreference.com](https://en.cppreference.com/w/cpp/container/map/equal_range)
	* returns range of elements matching a specific key (public member function)
	* Return value
		* std::pair containing a pair of iterators defining the wanted range: the first pointing to the first element that is not less than key and the second pointing to the first element greater than key.
		* If there are no elements not less than key, past-the-end (see end()) iterator is returned as the first element. Similarly if there are no elements greater than key, past-the-end iterator is returned as the second element.
	* Complexity
		* Logarithmic in the size of the container.
* [std::map<Key,T,Compare,Allocator>::lower_bound - cppreference.com](https://en.cppreference.com/w/cpp/container/map/lower_bound)
	* returns an iterator to the first element not less than the given key (public member function)
	* Return value
		* Iterator pointing to the first element that is not less than key. If no such element is found, a past-the-end iterator (see end()) is returned.
	* Complexity
		* Logarithmic in the size of the container.
* [std::map<Key,T,Compare,Allocator>::upper_bound - cppreference.com](https://en.cppreference.com/w/cpp/container/map/upper_bound)
	* returns an iterator to the first element greater than the given key (public member function)
	* Return value
		* Iterator pointing to the first element that is greater than key. If no such element is found, past-the-end (see end()) iterator is returned.
	* Complexity
		* Logarithmic in the size of the container.
	* [upper_bound in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/upper_bound-in-cpp/)
```c++
// CPP program to illustrate using
// std :: upper_bound with vectors
#include <bits/stdc++.h>

// Driver code
int main()
{
    std::vector<int> v{ 10, 20, 30, 40, 50 };

    // Print vector
    std::cout << "Vector contains :";
    for (int i = 0; i < v.size(); i++)
        std::cout << " " << v[i];
    std::cout << "\n";

    std::vector<int>::iterator upper1, upper2;

    // std :: upper_bound
    upper1 = std::upper_bound(v.begin(), v.end(), 35);
    upper2 = std::upper_bound(v.begin(), v.end(), 45);

    std::cout << "\nupper_bound for element 35 is at position : "
            << (upper1 - v.begin());
    std::cout << "\nupper_bound for element 45 is at position : "
            << (upper2 - v.begin());

    return 0;
}
```

##### Non-member functions

###### [std::erase_if (std::map)](https://en.cppreference.com/w/cpp/container/map/erase_if)

* Erases all elements satisfying specific criteria (function template)
* `erase_if( std::map<Key,T,Compare,Alloc>& c, Pred pred );` (since C++20)
* Return value
    * The number of erased elements.

##### MISC

* [Maps-STL | HackerRank](https://www.hackerrank.com/challenges/cpp-maps/problem)
```c++
#include <cmath>
#include <cstdio>
#include <vector>
#include <map>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */  
    map<string, int>    m;
    map<string, int>::iterator  it;
    int q, type, y;
    string  x;
    
    cin >> q;
    
    for (int i = 0; i < q; ++ i) {
        cin >> type >> x;
        switch (type) {
            case 1:
                cin >> y;
                // insert m[x] with default value 0 first if m[x] doesn't exist
                // then add y to m[x]
                m[x] += y;
                break;
            case 2:
                m.erase(x);
                break;
            case 3:
                // insert m[x] with default value 0 if m[x] doesn't exist
                cout << m[x] << endl;
        }
    }
    
    return 0;
}
```

#### [std::multiset](https://en.cppreference.com/w/cpp/container/multiset)

* collection of keys, sorted by keys (class template)
* std::multiset is an associative container that contains a sorted set of objects of type Key. Unlike set, multiple keys with equivalent values are allowed. Sorting is done using the key comparison function Compare. Search, insertion, and removal operations have logarithmic complexity.
* Everywhere the standard library uses the Compare requirements, equivalence is determined by using the equivalence relation as described on Compare. In imprecise terms, two objects a and b are considered equivalent if neither compares less than the other: !comp(a, b) && !comp(b, a).
* The order of the elements that compare equivalent is the order of insertion and does not change. (since C++11)
* std::multiset meets the requirements of Container, AllocatorAwareContainer, AssociativeContainer and ReversibleContainer.

#### [std::multimap](https://en.cppreference.com/w/cpp/container/multimap)

* collection of key-value pairs, sorted by keys (class template)
* Multimap is an associative container that contains a sorted list of key-value pairs, while permitting multiple entries with the same key. Sorting is done according to the comparison function Compare, applied to the keys. Search, insertion, and removal operations have logarithmic complexity.
* The order of the key-value pairs whose keys compare equivalent is the order of insertion and does not change. (since C++11)
* Everywhere the standard library uses the Compare requirements, equivalence is determined by using the equivalence relation as described on Compare. In imprecise terms, two objects a and b are considered equivalent if neither compares less than the other: !comp(a, b) && !comp(b, a).
* std::multimap meets the requirements of Container, AllocatorAwareContainer, AssociativeContainer and ReversibleContainer.

##### Member functions

###### Lookup

* [std::multimap<Key,T,Compare,Allocator>::find - cppreference.com](https://en.cppreference.com/w/cpp/container/multimap/find)
    * finds element with specific key (public member function)
    * 1,2) Finds an element with key equivalent to key. If there are `several` elements with key in the container, `any` of them may be returned.
    * 3,4) Finds an element with key that compares equivalent to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type. It allows calling this function without constructing an instance of Key.
    * Return value
        * Iterator to an element with key equivalent to key. If no such element is found, past-the-end (see end()) iterator is returned.
    * Complexity
        * Logarithmic in the size of the container.
* [std::multimap<Key,T,Compare,Allocator>::equal_range - cppreference.com](https://en.cppreference.com/w/cpp/container/multimap/equal_range)
    * returns range of elements matching a specific key (public member function)
    * Returns a range containing all elements with the given key in the container. The range is defined by two iterators, one pointing to the first element that is not less than key and another pointing to the first element greater than key. Alternatively, the first iterator may be obtained with lower_bound(), and the second with upper_bound().
    * 1,2) Compares the keys to key.
    * 3,4) Compares the keys to the value x. This overload participates in overload resolution only if the qualified-id Compare::is_transparent is valid and denotes a type. It allows calling this function without constructing an instance of Key.
    * Return value
        * std::pair containing a pair of iterators defining the wanted range: the first pointing to the first element that is not less than key and the second pointing to the first element greater than key.
        * If there are no elements not less than key, past-the-end (see end()) iterator is returned as the first element. Similarly if there are no elements greater than key, past-the-end iterator is returned as the second element.
        * Since emplace and unhinted insert always insert at the upper bound, the order of equivalent elements in the equal range is the order of insertion unless hinted insert or emplace_hint was used to insert an element at a different position. (since C++11)
    * Complexity
        * Logarithmic in the size of the container.
```c++
#include <iostream>
#include <map>
 
int main()
{
    std::multimap<int, char> dict {
        {1, 'A'},
        {2, 'B'},
        {2, 'C'},
        {2, 'D'},
        {4, 'E'},
        {3, 'F'}
    };
 
    auto range = dict.equal_range(2);
 
    for (auto i = range.first; i != range.second; ++i)
    {
        std::cout << i->first << ": " << i->second << '\n';
    }
}
/*
2: B
2: C
2: D
*/
```

### Unordered associative

* Unordered associative containers implement unsorted (hashed) data structures that can be quickly searched (O(1) amortized, O(n) worst-case complexity).

| unordered_set | collection of unique keys, hashed by keys | 
| - | - | 
| unordered_map | collection of key-value pairs, hashed by keys, keys are unique | 
| unordered_multiset | collection of keys, hashed by keys | 
| unordered_multimap | collection of key-value pairs, hashed by keys | 

#### [std::unordered_set](https://en.cppreference.com/w/cpp/container/unordered_set)

* Unordered set is an associative container that contains a set of unique objects of type Key. Search, insertion, and removal have average constant-time complexity.
* Internally, the elements are not sorted in any particular order, but organized into buckets. Which bucket an element is placed into depends entirely on the hash of its value. This allows fast access to individual elements, since once a hash is computed, it refers to the exact bucket the element is placed into.
* Container elements may not be modified (even by non const iterators) since modification could change an element's hash and corrupt the container.
* std::unordered_set meets the requirements of Container, AllocatorAwareContainer, UnorderedAssociativeContainer.
* Example
```c++
#include <iostream>
#include <unordered_set>
 
void print(const auto& set)
{
    for (const auto& elem : set)
        std::cout << elem << ' ';
    std::cout << '\n';
}
 
int main()
{
    std::unordered_set<int> mySet{2, 7, 1, 8, 2, 8}; // creates a set of ints
    print(mySet);
 
    mySet.insert(5); // puts an element 5 in the set
    print(mySet);
 
    if (auto iter = mySet.find(5); iter != mySet.end())
        mySet.erase(iter); // removes an element pointed to by iter
    print(mySet);
 
    mySet.erase(7); // removes an element 7
    print(mySet);
}
/*
Possible output:

8 1 7 2
5 8 1 7 2
8 1 7 2
8 1 2
*/
```

##### Iterator invalidation

| Operations | Invalidated |
| - | - |
| All read only operations, swap, std::swap	| Never |
| clear, rehash, reserve, operator=	| Always |
| insert, emplace, emplace_hint	| Only if causes rehash |
| erase	| Only to the element erased |

* Notes
    * The swap functions do not invalidate any of the iterators inside the container, but they do invalidate the iterator marking the end of the swap region.
    * References and pointers to data stored in the container are only invalidated by erasing that element, even when the corresponding iterator is invalidated.
    * After container move assignment, unless elementwise move assignment is forced by incompatible allocators, references, pointers, and iterators (other than the past-the-end iterator) to moved-from container remain valid, but refer to elements that are now in `*this`.

##### Member types

##### Member functions

###### Lookup

* [std::unordered_set<Key,Hash,KeyEqual,Allocator>::count - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_set/count)
    * returns the number of elements matching specific key (public member function)
    * Return value
        * 1) Number of elements with key key, that is either 1 or ​0​.
        * 2) Number of elements with key that compares equivalent to x.
    * Complexity
        * Constant on average, worst case linear in the size of the container.
    * Example
    ```c++
    #include <algorithm>
    #include <iostream>
    #include <unordered_set>
     
    int main()
    {
        std::unordered_set set{2, 7, 1, 8, 2, 8, 1, 8, 2, 8};
     
        std::cout << "The set is: ";
        for (int e : set)
            std::cout << e << ' ';
     
        const auto [min, max] = std::ranges::minmax(set);
     
        std::cout << "\nNumbers from " << min << " to " << max << " that are in the set: ";
        for (int i{min}; i <= max; ++i)
            if (set.count(i) == 1)
                std::cout << i << ' ';
        std::cout << '\n';
    }
    /*
    Possible output:
    
    The set is: 8 1 7 2
    Numbers from 1 to 8 that are in the set: 1 2 7 8
    */
    ```
* [std::unordered_set<Key,Hash,KeyEqual,Allocator>::contains - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_set/contains)
    * checks if the container contains element with specific key (public member function)
    * Return value
        * `true` if there is such an element, otherwise `false`.
    * Complexity
        * Constant on average, worst case linear in the size of the container.
    * Example
    ```c++
    #include <iostream>
    #include <unordered_set>
     
    int main()
    {
        std::unordered_set<int> example{1, 2, 3, 4};
     
        for (int x : {2, 5})
            if (example.contains(x))
                std::cout << x << ": Found\n";
            else
                std::cout << x << ": Not found\n";
    }
    /*
    Output:
    
    2: Found
    5: Not found
    */
    ```

#### [std::unordered_map](https://en.cppreference.com/w/cpp/container/unordered_map)

* Defined in header `<unordered_map>`
```c++
template<
    class Key,
    class T,
    class Hash = std::hash<Key>,
    class KeyEqual = std::equal_to<Key>,
    class Allocator = std::allocator< std::pair<const Key, T> >
> class unordered_map;  (1)	(since C++11)

namespace pmr {
template <
    class Key,
    class T,
    class Hash = std::hash<Key>,
    class KeyEqual = std::equal_to<Key>
> using unordered_map = std::unordered_map<Key, T, Hash, KeyEqual,
                            std::pmr::polymorphic_allocator<std::pair<const Key,T>>>;
}   (2)	(since C++17)
```
* Unordered map is an `associative container` that contains `key-value pairs` with `unique keys`. Search, insertion, and removal of elements have `average constant-time complexity`.
* Internally, the elements are `not sorted` in any particular order, but organized into `buckets`. Which bucket an element is placed into depends entirely on the hash of its key. Keys with the same hash code appear in the same bucket. This allows fast access to individual elements, since once the hash is computed, it refers to the exact bucket the element is placed into.
* std::unordered_map meets the requirements of Container, AllocatorAwareContainer, UnorderedAssociativeContainer.
* Example
```c++
#include <iostream>
#include <string>
#include <unordered_map>
 
int main()
{
    // Create an unordered_map of three strings (that map to strings)
    std::unordered_map<std::string, std::string> u = {
        {"RED","#FF0000"},
        {"GREEN","#00FF00"},
        {"BLUE","#0000FF"}
    };
 
    // Helper lambda function to print key-value pairs
    auto print_key_value = [](const auto& key, const auto& value)
    {
        std::cout << "Key:[" << key << "] Value:[" << value << "]\n";
    };
 
    std::cout << "Iterate and print key-value pairs of unordered_map, being\n"
                 "explicit with their types:\n";
    for( const std::pair<const std::string, std::string>& n : u )
        print_key_value(n.first, n.second);
 
    std::cout << "\nIterate and print key-value pairs using C++17 structured binding:\n";
    for( const auto& [key, value] : u )
        print_key_value(key, value);
 
    // Add two new entries to the unordered_map
    u["BLACK"] = "#000000";
    u["WHITE"] = "#FFFFFF";
 
    std::cout << "\nOutput values by key:\n"
                 "The HEX of color RED is:[" << u["RED"] << "]\n"
                 "The HEX of color BLACK is:[" << u["BLACK"] << "]\n\n";
 
    std::cout << "Use operator[] with non-existent key to insert a new key-value pair:\n";
    print_key_value("new_key", u["new_key"]);
 
    std::cout << "\nIterate and print key-value pairs, using `auto`;\n"
                 "new_key is now one of the keys in the map:\n";
    for( const auto& n : u )
        print_key_value(n.first, n.second);
}
/*
Iterate and print key-value pairs of unordered_map, being
explicit with their types:
Key:[BLUE] Value:[#0000FF]
Key:[GREEN] Value:[#00FF00]
Key:[RED] Value:[#FF0000]
 
Iterate and print key-value pairs using C++17 structured binding:
Key:[BLUE] Value:[#0000FF]
Key:[GREEN] Value:[#00FF00]
Key:[RED] Value:[#FF0000]
 
Output values by key:
The HEX of color RED is:[#FF0000]
The HEX of color BLACK is:[#000000]
 
Use operator[] with non-existent key to insert a new key-value pair:
Key:[new_key] Value:[]
 
Iterate and print key-value pairs, using `auto`;
new_key is now one of the keys in the map:
Key:[new_key] Value:[]
Key:[WHITE] Value:[#FFFFFF]
Key:[BLACK] Value:[#000000]
Key:[BLUE] Value:[#0000FF]
Key:[GREEN] Value:[#00FF00]
Key:[RED] Value:[#FF0000]
*/
```

##### Iterator invalidation

| Operations | Invalidated |
| - | - |
| All read only operations, swap, std::swap | Never |
| clear, rehash, reserve, operator= | Always |
| insert, emplace, emplace_hint, operator[] | Only if causes rehash |
| erase | Only to the element erased |

* Notes
    * The swap functions do not invalidate any of the iterators inside the container, but they do invalidate the iterator marking the end of the swap region.
    * References and pointers to either key or data stored in the container are only invalidated by erasing that element, even when the corresponding iterator is invalidated.

##### Member types

##### Member functions

###### [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::unordered_map](https://en.cppreference.com/w/cpp/container/unordered_map/unordered_map)

* constructs the unordered_map (public member function)
* Constructs new container from a variety of data sources. Optionally uses user supplied bucket_count as a minimal number of buckets to create, hash as the hash function, equal as the function to compare keys and alloc as the allocator.
* Notes
    * After container move construction (overload (4)), references, pointers, and iterators (other than the end iterator) to other remain valid, but refer to elements that are now in `*this`. The current standard makes this guarantee via the blanket statement in `[container.requirements.general]/12`, and a more direct guarantee is under consideration via `LWG 2321`.
    * Although not formally required until C++23, some implementations has already put the template parameter Allocator into `non-deduced contexts` in earlier modes.
* Example
```c++
#include <unordered_map>
#include <vector>
#include <bitset>
#include <string>
#include <utility>
 
struct Key {
    std::string first;
    std::string second;
};
 
struct KeyHash {
 std::size_t operator()(const Key& k) const
 {
     return std::hash<std::string>()(k.first) ^
            (std::hash<std::string>()(k.second) << 1);
 }
};
 
struct KeyEqual {
 bool operator()(const Key& lhs, const Key& rhs) const
 {
    return lhs.first == rhs.first && lhs.second == rhs.second;
 }
};
 
struct Foo {
    Foo(int val_) : val(val_) {}
    int val;
    bool operator==(const Foo &rhs) const { return val == rhs.val; }
};
 
template<> struct std::hash<Foo> {
    std::size_t operator()(const Foo &f) const {
        return std::hash<int>{}(f.val);
    }  
};
 
int main()
{
    // default constructor: empty map
    std::unordered_map<std::string, std::string> m1;
 
    // list constructor
    std::unordered_map<int, std::string> m2 =
    {
        {1, "foo"},
        {3, "bar"},
        {2, "baz"},
    };
 
    // copy constructor
    std::unordered_map<int, std::string> m3 = m2;
 
    // move constructor
    std::unordered_map<int, std::string> m4 = std::move(m2);
 
    // range constructor
    std::vector<std::pair<std::bitset<8>, int>> v = { {0x12, 1}, {0x01,-1} };
    std::unordered_map<std::bitset<8>, double> m5(v.begin(), v.end());
 
    //Option 1 for a constructor with a custom Key type
    // Define the KeyHash and KeyEqual structs and use them in the template
    std::unordered_map<Key, std::string, KeyHash, KeyEqual> m6 = {
            { {"John", "Doe"}, "example"},
            { {"Mary", "Sue"}, "another"}
    };
 
    //Option 2 for a constructor with a custom Key type
    // Define a const == operator for the class/struct and specialize std::hash
    // structure in the std namespace
    std::unordered_map<Foo, std::string> m7 = {
        { Foo(1), "One"}, { 2, "Two"}, { 3, "Three"}
    };
 
    //Option 3: Use lambdas
    // Note that the initial bucket count has to be passed to the constructor
    struct Goo {int val; };
    auto hash = [](const Goo &g){ return std::hash<int>{}(g.val); };
    auto comp = [](const Goo &l, const Goo &r){ return l.val == r.val; };
    std::unordered_map<Goo, double, decltype(hash), decltype(comp)> m8(10, hash, comp);
}
```

###### Iterators

* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::begin(size_type), std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::cbegin(size_type) - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/begin2)
    * returns an iterator to the beginning (public member function)

###### Capacity

* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::size - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/size)
    * returns the number of elements (public member function)

###### Modifiers

* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::emplace](https://en.cppreference.com/w/cpp/container/unordered_map/emplace)
    * constructs element in-place (public member function)
    * Inserts a new element into the container constructed in-place with the given args if there is no element with the key in the container.
    * Careful use of emplace allows the new element to be constructed while avoiding unnecessary copy or move operations. The constructor of the new element (i.e. `std::pair<const Key, T>`) is called with exactly the same arguments as supplied to emplace, forwarded via `std::forward<Args>(args)...`. The element may be constructed even if there already is an element with the key in the container, in which case the newly constructed element will be destroyed immediately.
    * If rehashing occurs due to the insertion, all iterators are invalidated. Otherwise iterators are not affected. References are not invalidated. Rehashing occurs only if the new number of elements is greater than `max_load_factor() * bucket_count()`.
    * Return value
        * Returns a pair consisting of an iterator to the inserted element, or the already-existing element if no insertion happened, and a `bool` denoting whether the insertion took place (`true` if insertion happened, `false` if it did not).
    * Exceptions
        * If an exception is thrown by any operation, this function has no effect (strong exception guarantee).
    * Complexity
        * Amortized constant on average, worst case linear in the size of the container.
    * Example
    ```c++
    #include <iostream>
    #include <utility>
    #include <string>
    #include <unordered_map>

    int main()
    {
        std::unordered_map<std::string, std::string> m;

        // uses pair's move constructor
        m.emplace(std::make_pair(std::string("a"), std::string("a")));

        // uses pair's converting move constructor
        m.emplace(std::make_pair("b", "abcd"));

        // uses pair's template constructor
        m.emplace("d", "ddd");

        // uses pair's piecewise constructor
        m.emplace(std::piecewise_construct,
                  std::forward_as_tuple("c"),
                  std::forward_as_tuple(10, 'c'));
        // as of C++17, m.try_emplace("c", 10, 'c'); can be used

        for (const auto &p : m) {
            std::cout << p.first << " => " << p.second << '\n';
        }
    }
    /*
    a => a
    b => abcd
    c => cccccccccc
    d => ddd
    */
    ```
* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::erase](https://en.cppreference.com/w/cpp/container/unordered_map/erase)
    * erases elements (public member function)
    * `iterator erase( const_iterator pos );`   (1)
    * `iterator erase( const_iterator first, const_iterator last );`    (2)	
    * `size_type erase( const Key& key );`  (3)
    * `template< class K > size_type erase( K&& x );`   (4)	(since C++23)
    * Removes specified elements from the container.
        * 1) Removes the element at `pos`.
        * 2) Removes the elements in the range `[first; last)`, which must be a valid range in `*this`.
        * 3) Removes the element (if one exists) with the key equivalent to `key`.
        * 4) Removes the element (if one exists) with key that compares equivalent to the value `x`. This overload participates in overload resolution only if `Hash::is_transparent` and `KeyEqual::is_transparent` are valid and each denotes a type, and neither iterator nor const_iterator is implicitly convertible from K. This assumes that such Hash is callable with both K and Key type, and that the KeyEqual is transparent, which, together, allows calling this function without constructing an instance of Key.
    * References and iterators to the erased elements are invalidated. Other iterators and references are not invalidated.
    * The iterator pos must be valid and dereferenceable. Thus the `end()` iterator (which is valid, but is not dereferenceable) cannot be used as a value for pos.
    * The order of the elements that are not erased is preserved. (This makes it possible to erase individual elements while iterating through the container.)
    * Complexity
        * Given an instance `c` of unordered_map:
            * 1) Average case: constant, worst case: `c.size()`
            * 2) Average case: `std::distance(first, last)`, worst case: `c.size()`
            * 3) Average case: `c.count(key)`, worst case: `c.size()`
            * 4) Average case: `c.count(x)`, worst case: `c.size()`
    * Example
    ```c++
    #include <unordered_map>
    #include <iostream>

    int main()
    {
        std::unordered_map<int, std::string> c =
        {
            {1, "one" }, {2, "two" }, {3, "three"},
            {4, "four"}, {5, "five"}, {6, "six"  }
        };

        // erase all odd numbers from c
        for (auto it = c.begin(); it != c.end();)
        {
            if (it->first % 2 != 0)
                it = c.erase(it);
            else
                ++it;
        }

        for (auto& p : c)
            std::cout << p.second << ' ';
    }
    /*
    two four six
    */
    ```
* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::extract - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/extract)
	* extracts nodes from the container (public member function)
	* Return value
		* A node handle that owns the extracted element, or empty node handle in case the element is not found in (2,3).
	* Exceptions
		* 1) Throws nothing.
		* 2,3) Any exceptions thrown by the Hash and KeyEqual object.
	* Complexity
		* 1,2,3) Average case O(1), worst case O(a.size()).
	* Notes
		* extract is the only way to change a key of a map element without reallocation:

###### Lookup

* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::at - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/at)
	* Returns a reference to the mapped value of the element with key equivalent to key. If no such element exists, an exception of type std::out_of_range is thrown.
* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::operator[] - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/operator_at)
	* Returns a reference to the value that is mapped to a key equivalent to key, performing an insertion if such key does not already exist.
* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::count - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/count)
	* returns the number of elements matching specific key
	* Return value
	    * 1) Number of elements with key key, that is either 1 or 0.
	    * 2) Number of elements with key that compares equivalent to x.
    * Complexity
        * Constant on average, worst case linear in the size of the container.
* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::find - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/find)
	* finds element with specific key (public member function)
	* Return value
	    * Iterator to an element with key equivalent to key. If no such element is found, past-the-end (see `end()`) iterator is returned.
    * Complexity
        * Constant on average, worst case linear in the size of the container.
    * Example
    ```c++
    #include <cstddef>
    #include <functional>
    #include <iostream>
    #include <string>
    #include <string_view>
    #include <unordered_map>

    using namespace std::literals;

    struct string_hash
    {
        using hash_type = std::hash<std::string_view>;
        using is_transparent = void;

        std::size_t operator()(const char* str) const        { return hash_type{}(str); }
        std::size_t operator()(std::string_view str) const   { return hash_type{}(str); }
        std::size_t operator()(std::string const& str) const { return hash_type{}(str); }
    };

    int main()
    {
        // simple comparison demo
        std::unordered_map<int,char> example = {{1, 'a'}, {2, 'b'}};

        if (auto search = example.find(2); search != example.end())
            std::cout << "Found " << search->first << " " << search->second << '\n';
        else
            std::cout << "Not found\n";

        // C++20 demo: Heterogeneous lookup for unordered containers (transparent hashing)
        std::unordered_map<std::string, size_t, string_hash, std::equal_to<>> map{{"one"s, 1}};
        std::cout << std::boolalpha
            << (map.find("one")   != map.end()) << '\n'
            << (map.find("one"s)  != map.end()) << '\n'
            << (map.find("one"sv) != map.end()) << '\n';
    }
    /*
    Found 2 b
    true
    true
    true
    */
    ```
* [std::unordered_map<Key,T,Hash,KeyEqual,Allocator>::contains - cppreference.com](https://en.cppreference.com/w/cpp/container/unordered_map/contains)
    * checks if the container contains element with specific key (public member function)
    * Return value
        * true if there is such an element, otherwise false.
    * Complexity
        * Constant on average, worst case linear in the size of the container.
    * Example
    ```c++
    #include <iostream>
    #include <unordered_map>
     
    int main()
    {
        std::unordered_map<int, char> example{{1, 'a'}, {2, 'b'}};
     
        for (int x : {2, 5})
            if (example.contains(x))
                std::cout << x << ": Found\n";
            else
                std::cout << x << ": Not found\n";
    }
    /*
    Output:
    
    2: Found
    5: Not found
    */
    ```

###### MISC

* [unordered_map - C++ Reference](https://www.cplusplus.com/reference/unordered_map/unordered_map/)
	* Unordered Map
	* Unordered maps are associative containers that store elements formed by the combination of a key value and a mapped value, and which allows for fast retrieval of individual elements based on their keys.
	* In an unordered_map, the key value is generally used to uniquely identify the element, while the mapped value is an object with the content associated to this key. Types of key and mapped value may differ.
	* Internally, the elements in the unordered_map are not sorted in any particular order with respect to either their key or mapped values, but organized into buckets depending on their hash values to allow for fast access to individual elements directly by their key values (with a constant average time complexity on average).
	* unordered_map containers are faster than map containers to access individual elements by their key, although they are generally less efficient for range iteration through a subset of their elements.
	* Unordered maps implement the direct access operator (operator[]) which allows for direct access of the mapped value using its key value as argument.
	* Iterators in the container are at least forward iterators.
	* [Static const map inside class/struct - C++ Forum](http://www.cplusplus.com/forum/general/266519/)

### Adaptors

* Container adaptors provide a different interface for sequential containers.

| stack | adapts a container to provide stack (LIFO data structure) | 
| - | - | 
| queue | adapts a container to provide queue (FIFO data structure) | 
| priority_queue | adapts a container to provide priority queue | 

#### [std::stack](https://en.cppreference.com/w/cpp/container/stack)

* The std::stack class is a container adaptor that gives the programmer the functionality of a stack - specifically, a LIFO (last-in, first-out) data structure.
* The class template acts as a wrapper to the underlying container - only a specific set of functions is provided. The stack pushes and pops the element from the back of the underlying container, known as the top of the stack.
* [std::stack<T,Container>::top - cppreference.com](https://en.cppreference.com/w/cpp/container/stack/top)
	* Returns reference to the top element in the stack. This is the most recently pushed element. This element will be removed on a call to pop(). Effectively calls c.back().
```c++
#include <stack>
#include <iostream>
 
void reportStackSize(const std::stack<int>& s)
{
    std::cout << s.size() << " elements on stack\n";
}
 
void reportStackTop(const std::stack<int>& s)
{
    // Leaves element on stack
    std::cout << "Top element: " << s.top() << '\n';
}
 
int main()
{
    std::stack<int> s;
    s.push(2);
    s.push(6);
    s.push(51);
 
    reportStackSize(s);
    reportStackTop(s);
 
    reportStackSize(s);
    s.pop();
 
    reportStackSize(s);
    reportStackTop(s);
}
/*
3 elements on stack
Top element: 51
3 elements on stack
2 elements on stack
Top element: 6
*/
```

#### [std::queue](https://en.cppreference.com/w/cpp/container/queue)

* The std::queue class is a container adaptor that gives the programmer the functionality of a queue - specifically, a `FIFO` (`first-in, first-out`) data structure.
* The class template acts as a wrapper to the underlying container - only a specific set of functions is provided. The queue `pushes the elements on the back` of the underlying container and `pops them from the front`.

##### Template parameters

* T	- The type of the stored elements. `The behavior is undefined if T is not the same type as Container::value_type. (since C++17)`
* Container	- The type of the underlying container to use to store the elements. The container must satisfy the requirements of [SequenceContainer](https://en.cppreference.com/w/cpp/named_req/SequenceContainer). Additionally, it must provide the following functions with the usual semantics:
    * back()
    * front()
    * push_back()
    * pop_front()
    * The standard containers [std::deque](https://en.cppreference.com/w/cpp/container/deque) and [std::list](https://en.cppreference.com/w/cpp/container/list) satisfy these requirements.

##### Member functions

###### Modifiers

* [std::queue<T,Container>::push](https://en.cppreference.com/w/cpp/container/queue/push)
    * inserts element at the end (public member function)
    * Pushes the given element value to the end of the queue.
        * 1) Effectively calls `c.push_back(value)`
        * 2) Effectively calls `c.push_back(std::move(value))`
* [std::queue<T,Container>::pop](https://en.cppreference.com/w/cpp/container/queue/pop)
    * removes the first element (public member function)
    * Removes an element from the front of the queue. Effectively calls `c.pop_front()`

#### [std::priority_queue](https://en.cppreference.com/w/cpp/container/priority_queue)

* A priority queue is a container adaptor that provides constant time lookup of the largest (by default) element, at the expense of logarithmic insertion and extraction.
* A user-provided Compare can be supplied to change the ordering, e.g. using std::greater\<T> would cause the smallest element to appear as the top().
* Working with a priority_queue is similar to managing a heap in some random access container, with the benefit of not being able to accidentally invalidate the heap.

### Views

## [Iterator library](https://en.cppreference.com/w/cpp/iterator)

### Iterator adaptors

* [std::reverse_iterator - cppreference.com](https://en.cppreference.com/w/cpp/iterator/reverse_iterator)
	* iterator adaptor for reverse-order traversal (class template)
	* std::reverse_iterator is an iterator adaptor that reverses the direction of a given iterator, which must be at least a LegacyBidirectionalIteratoror model bidirectional_iterator (since C++20). In other words, when provided with a bidirectional iterator, std::reverse_iterator produces a new iterator that moves from the end to the beginning of the sequence defined by the underlying bidirectional iterator.
	* For a reverse iterator r constructed from an iterator i, the relationship &*r == &*(i-1) is always true (as long as r is dereferenceable); thus a reverse iterator constructed from a one-past-the-end iterator dereferences to the last element in a sequence.
	* This is the iterator returned by member functions rbegin() and rend() of the standard library containers.
![image](https://user-images.githubusercontent.com/34557994/204089110-99992bc5-21e4-49a4-a8bd-04a8b1a06bc6.png)
* [std::make_reverse_iterator - cppreference.com](https://en.cppreference.com/w/cpp/iterator/make_reverse_iterator)
	* creates a std::reverse_iterator of type inferred from the argument (function template)
	* make_reverse_iterator is a convenience function template that constructs a std::reverse_iterator for the given iterator i (which must be a LegacyBidirectionalIterator) with the type deduced from the type of the argument.
* [std::back_inserter - cppreference.com](https://en.cppreference.com/w/cpp/iterator/back_inserter)
	* creates a std::back_insert_iterator of type inferred from the argument (function template)
	* back_inserter is a convenient function template that constructs a std::back_insert_iterator for the container c with the type deduced from the type of the argument.
	* Parameters
		* c	-	container that supports a push_back operation
	* Return value
		* A std::back_insert_iterator which can be used to add elements to the end of the container c
```c++
#include <iostream>
#include <vector>
#include <algorithm>
#include <iterator>
 
int main()
{
    std::vector<int> v{1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
    std::fill_n(std::back_inserter(v), 3, -1);
    for (int n : v)
        std::cout << n << ' ';
}
// 1 2 3 4 5 6 7 8 9 10 -1 -1 -1
```
* [std::inserter - cppreference.com](https://en.cppreference.com/w/cpp/iterator/inserter)
	* creates a std::insert_iterator of type inferred from the argument (function template)
	* inserter is a convenience function template that constructs a std::insert_iterator for the container c and its iterator i with the type deduced from the type of the argument.
	* Parameters
		* c	-	container that supports an insert operation
		* i	-	iterator in c indicating the insertion position
	* Return value
		* A std::insert_iterator which can be used to insert elements into the container c at the position indicated by i.
```c++
#include <algorithm>
#include <iostream>
#include <iterator>
#include <vector>
#include <set>
 
int main()
{
    std::multiset<int> s {1, 2, 3};
 
    // std::inserter is commonly used with multi-sets
    std::fill_n(std::inserter(s, s.end()), 5, 2);
 
    for (int n : s)
        std::cout << n << ' ';
    std::cout << '\n';
 
    std::vector<int> d {100, 200, 300};
    std::vector<int> v {1, 2, 3, 4, 5};
 
    // when inserting in a sequence container, insertion point advances
    // because each std::insert_iterator::operator= updates the target iterator
    std::copy(d.begin(), d.end(), std::inserter(v, std::next(v.begin())));
 
    for (int n : v)
        std::cout << n << ' ';
    std::cout << '\n';
}

/*
Output:

1 2 2 2 2 2 2 3 
1 100 200 300 2 3 4 5
*/
```

### Iterator operations

* Defined in header `<iterator>`

#### [std::advance](https://en.cppreference.com/w/cpp/iterator/advance)

* advances an iterator by given distance (function template)
* Increments given iterator it by n elements.
* If n is negative, the iterator is decremented. In this case, InputIt must meet the requirements of LegacyBidirectionalIterator, otherwise the behavior is undefined.
* [advance - C++ Reference](https://www.cplusplus.com/reference/iterator/advance/)
    * Advance iterator
        * Advances the iterator it by n element positions.
        * If it is a random-access iterator, the function uses just once operator+ or operator-. Otherwise, the function uses repeatedly the increase or decrease operator (operator++ or operator--) until n elements have been advanced.
* [std::advance in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/stdadvance-in-cpp/)
```c++
#include <iostream>
#include <iterator>
#include <vector>
 
int main() 
{
    std::vector<int> v{ 3, 1, 4 };
 
    auto vi = v.begin();
    std::advance(vi, 2);
    std::cout << *vi << ' ';
 
    vi = v.end();
    std::advance(vi, -2);
    std::cout << *vi << '\n';
}
/*
4 1
*/
```

#### [std::distance](https://en.cppreference.com/w/cpp/iterator/distance)

* returns the distance between two iterators (function template)
* Returns the number of hops from first to last.
* If InputIt is not LegacyRandomAccessIterator, the behavior is undefined if last is not reachable from first by (possibly repeatedly) incrementing first. If InputIt is LegacyRandomAccessIterator, the behavior is undefined if last is not reachable from first and first is not reachable from last. 
* Return value
    * The number of increments needed to go from first to last. `The value may be negative if random-access iterators are used and first is reachable from last`
* Example
```c++
#include <iostream>
#include <iterator>
#include <vector>
 
int main() 
{
    std::vector<int> v{ 3, 1, 4 };
    std::cout << "distance(first, last) = "
              << std::distance(v.begin(), v.end()) << '\n'
              << "distance(last, first) = "
              << std::distance(v.end(), v.begin()) << '\n';
               //the behavior is undefined (until C++11)
 
    static constexpr auto il = { 3, 1, 4 };
    // Since C++17 `distance` can be used in constexpr context.
    static_assert(std::distance(il.begin(), il.end()) == 3);
    static_assert(std::distance(il.end(), il.begin()) == -3);
}
/*
distance(first, last) = 3
distance(last, first) = -3
*/
```

#### [std::next](https://en.cppreference.com/w/cpp/iterator/next)

* increment an iterator (function template)
* Return the nth successor of iterator it.
* Notes
    * Although the expression `++c.begin()` often compiles, it is not guaranteed to do so: `c.begin()` is an rvalue expression, and there is no LegacyInputIterator requirement that specifies that increment of an rvalue is guaranteed to work. In particular, when iterators are implemented as pointers or its operator++ is lvalue-ref-qualified, `++c.begin()` does not compile, while `std::next(c.begin())` does.
```c++
#include <iostream>
#include <iterator>
#include <vector>
 
int main()
{
    std::vector<int> v{ 4, 5, 6 };
 
    auto it = v.begin();
    auto nx = std::next(it, 2);
    std::cout << *it << ' ' << *nx << '\n';
 
    it = v.end();
    nx = std::next(it, -2);
    std::cout << ' ' << *nx << '\n';
}
/*
4 6
 5
*/
```

#### [std::prev](https://en.cppreference.com/w/cpp/iterator/prev)

* decrement an iterator (function template)
* Return the nth predecessor (or -nth successor if n is negative) of iterator it.
* Complexity
    * Linear.
    * However, if BidirIt additionally meets the requirements of LegacyRandomAccessIterator, complexity is constant.
* Notes
    * Although the expression `--c.end()` often compiles, it is not guaranteed to do so: `c.end()` is an rvalue expression, and there is no iterator requirement that specifies that decrement of an rvalue is guaranteed to work. In particular, when iterators are implemented as pointers or its `operator--` is lvalue-ref-qualified, `--c.end()` does not compile, while `std::prev(c.end())` does.
* Example
```c++
#include <iostream>
#include <iterator>
#include <vector>
 
int main()
{
    std::vector<int> v{ 3, 1, 4 };
 
    auto it = v.end();
    auto pv = std::prev(it, 2);
    std::cout << *pv << '\n';
 
    it = v.begin();
    pv = std::prev(it, -2);
    std::cout << *pv << '\n';
}
/*
1
4
*/
```

### Range access

* These non-member functions provide a generic interface for containers, plain arrays, and [std::initializer_list](https://en.cppreference.com/w/cpp/utility/initializer_list).
* [std::begin, std::cbegin - cppreference.com](https://en.cppreference.com/w/cpp/iterator/begin)
	* returns an iterator to the beginning of a container or array(function template)
* [std::end, std::cend - cppreference.com](https://en.cppreference.com/w/cpp/iterator/end)
	* returns an iterator to the end of a container or array(function template)

## [Ranges library](https://en.cppreference.com/w/cpp/ranges)

* [起底 C++ Range 令人惊讶的局限性！](https://mp.weixin.qq.com/s/iB70FXO-D7C-72N4l9KnzA)
  * https://www.fluentcpp.com/2019/09/13/the-surprising-limitations-of-c-ranges-beyond-trivial-use-cases/

## [Algorithm library](https://en.cppreference.com/w/cpp/algorithm)

* The algorithms library defines functions for a variety of purposes (e.g. searching, sorting, counting, manipulating) that operate on ranges of elements. Note that a range is defined as \[first, last) where last refers to the element past the last element to inspect or modify.

### Execution policies

* Most algorithms have overloads that accept execution policies. The standard library algorithms support several execution policies, and the library provides corresponding execution policy types and objects. Users may select an execution policy statically by invoking a parallel algorithm with an execution policy object of the corresponding type.
* Standard library implementations (but not the users) may define additional execution policies as an extension. The semantics of parallel algorithms invoked with an execution policy object of implementation-defined type is implementation-defined.
* Parallel version of algorithms (except for std::for_each and std::for_each_n) are allowed to make arbitrary copies of elements from ranges, as long as both `std::is_trivially_copy_constructible_v<T>` and `std::is_trivially_destructible_v<T>` are true, where T is the type of elements.
* Defined in header `<execution>`
* Defined in namespace `std::execution`
* [std::execution::sequenced_policy, std::execution::parallel_policy, std::execution::parallel_unsequenced_policy, std::execution::unsequenced_policy - cppreference.com](https://en.cppreference.com/w/cpp/algorithm/execution_policy_tag_t)
	* execution policy types (class)
	* Notes
		* When using parallel execution policy, it is the programmer's responsibility to avoid data races and deadlocks:
* [std::execution::seq, std::execution::par, std::execution::par_unseq, std::execution::unseq - cppreference.com](https://en.cppreference.com/w/cpp/algorithm/execution_policy_tag)
	* global execution policy objects (constant)
	* std::execution::seq, std::execution::par, std::execution::par_unseq, and std::execution::unseq are instances of the execution policy types std::execution::sequenced_policy, std::execution::parallel_policy, std::execution::parallel_unsequenced_policy, and std::execution::unsequenced_policy respectively. They are used to specify the execution policy of parallel algorithms - i.e., the kinds of parallelism allowed.
	* Additional execution policies may be provided by a standard library implementation (possible future additions may include std::parallel::cuda and std::parallel::opencl)

#### MISC

* [c++ - Difference between execution policies and when to use them - Stack Overflow](https://stackoverflow.com/questions/39954678/difference-between-execution-policies-and-when-to-use-them)
* [c++ - std::for_each with std::execution::par_unseq not working on GCC but working with MSVC - Stack Overflow](https://stackoverflow.com/questions/65496175/stdfor-each-with-stdexecutionpar-unseq-not-working-on-gcc-but-working-with)

### Non-modifying sequence operations

#### [std::all_of, std::any_of, std::none_of](https://en.cppreference.com/w/cpp/algorithm/all_any_none_of)

* checks if a predicate is true for all, any or none of the elements in a range (function template)
* Example
```c++
#include <algorithm>
#include <functional>
#include <iostream>
#include <iterator>
#include <numeric>
#include <vector>
 
int main()
{
    std::vector<int> v(10, 2);
    std::partial_sum(v.cbegin(), v.cend(), v.begin());
    std::cout << "Among the numbers: ";
    std::copy(v.cbegin(), v.cend(), std::ostream_iterator<int>(std::cout, " "));
    std::cout << '\n';
 
    if (std::all_of(v.cbegin(), v.cend(), [](int i){ return i % 2 == 0; }))
        std::cout << "All numbers are even\n";
 
    if (std::none_of(v.cbegin(), v.cend(), std::bind(std::modulus<>(),
                                                     std::placeholders::_1, 2)))
        std::cout << "None of them are odd\n";
 
    struct DivisibleBy
    {
        const int d;
        DivisibleBy(int n) : d(n) {}
        bool operator()(int n) const { return n % d == 0; }
    };
 
    if (std::any_of(v.cbegin(), v.cend(), DivisibleBy(7)))
        std::cout << "At least one number is divisible by 7\n";
}

/*
Among the numbers: 2 4 6 8 10 12 14 16 18 20 
All numbers are even
None of them are odd
At least one number is divisible by 7
*/
```

#### [std::for_each](https://en.cppreference.com/w/cpp/algorithm/for_each)

* applies a function to a range of elements(function template)
```c++
template< class InputIt, class UnaryFunction >
UnaryFunction for_each( InputIt first, InputIt last, UnaryFunction f );
(1) (until C++20)
template< class InputIt, class UnaryFunction >
constexpr UnaryFunction for_each( InputIt first, InputIt last, UnaryFunction f );
(1) (since C++20)

template< class ExecutionPolicy, class ForwardIt, class UnaryFunction2 >
void for_each( ExecutionPolicy&& policy, ForwardIt first, ForwardIt last, UnaryFunction2 f );
(2) (since C++17)
```
* 1) Applies the given function object f to the result of dereferencing every iterator in the range `[first, last)`, in order.
* 2) Applies the given function object f to the result of dereferencing every iterator in the range `[first, last)` (not necessarily in order). The algorithm is executed according to policy. This overload does not participate in overload resolution unless `std::is_execution_policy_v<std::decay_t<ExecutionPolicy>> (until C++20) std::is_execution_policy_v<std::remove_cvref_t<ExecutionPolicy>> (since C++20)` is true.
* For both overloads, if the iterator type is mutable, f may modify the elements of the range through the dereferenced iterator. If f returns a result, the result is ignored.
* Unlike the rest of the parallel algorithms, for_each is not allowed to make copies of the elements in the sequence even if they are trivially copyable.

##### MISC

* [for_each loop in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/for_each-loop-c/)
    * It is versatile, i.e.  Can work with any container.
    * It reduces chances of errors one can commit using generic for loop
    * It makes code more readable
    * for_each loops improve overall performance of code
* [c++ - How can I change the value of the elements in a vector? - Stack Overflow](https://stackoverflow.com/questions/4807709/how-can-i-change-the-value-of-the-elements-in-a-vector)
```c++
double total = 0;
for_each( v.begin(), v.end(), [&total](double  v) { total += v; });
cout << "The sum of the values is: " << total << endl;

double total = std::accumulate(v.begin(), v.end(), 0.0);
```
* [c++ - Use of for_each on map elements - Stack Overflow](https://stackoverflow.com/questions/2850312/use-of-for-each-on-map-elements)
    * You can iterate through a std::map object. Each iterator will point to a std::pair<const T,S> where T and S are the same types you specified on your map.
    * If you still want to use std::for_each, pass a function that takes a std::pair<const int, MyClass>& as an argument instead.
    * And pass it to std::for_each:
    ```c++
    void CallMyMethod(std::pair<const int, MyClass>& pair) // could be a class static method as well
    {
      pair.second.Method();
    }

    std::for_each(Map.begin(), Map.end(), CallMyMethod);
    ```
* [c++ - Raw Loop on an array of bool is 5 times faster than transform or for_each - Stack Overflow](https://stackoverflow.com/questions/56873187/raw-loop-on-an-array-of-bool-is-5-times-faster-than-transform-or-for-each)
	* In this example, clang vectorizes indexing but (mistakenly) fails to vectorize iterating.
	* To summarize the results, there is no difference between using a raw loop and using std::transform or std::for_each. There IS, however, a difference between using indexing and using iterating, and for the purposes of this particular problem, clang is better at optimizing indexing than it is at optimizing iterating because indexing gets vectorized. std::transform and std::for_each use iterating, so they end up being slower (when compiled under clang).

#### [std::find, std::find_if, std::find_if_not](https://en.cppreference.com/w/cpp/algorithm/find)

##### MISC

* [find_if - C++ Reference](https://www.cplusplus.com/reference/algorithm/find_if/)
* Find element in range
  * Returns an iterator to the first element in the range \[first,last) for which pred returns true. If no such element is found, the function returns last.
* [std::find_if , std::find_if_not in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/stdfind_if-stdfind_if_not-in-c/)
* [c++ - How to find out if an item is present in a std::vector? - Stack Overflow](https://stackoverflow.com/questions/571394/how-to-find-out-if-an-item-is-present-in-a-stdvector)
* `std::find(vec.begin(), vec.end(), item) != vec.end()`

### Modifying sequence operations

#### [std::copy, std::copy_if](https://en.cppreference.com/w/cpp/algorithm/copy)

* copies a range of elements to a new location (function template)
* Copies the elements in the range, defined by \[first, last), to another range beginning at d_first.
* [c++ - How to use copy_if for maps - Stack Overflow](https://stackoverflow.com/questions/23548139/how-to-use-copy-if-for-maps)

#### [std::transform](https://en.cppreference.com/w/cpp/algorithm/transform)

* applies a function to a range of elements, storing results in a destination range (function template)
* std::transform applies the given function to a range and stores the result in another range, keeping the original elements order and beginning at d_first.
    * 1) The unary operation unary_op is applied to the range defined by \[first1, last1).
    * 3) The binary operation binary_op is applied to pairs of elements from two ranges: one defined by \[first1, last1) and the other beginning at first2.
    * 2,4) Same as (1,3), but executed according to policy. These overloads do not participate in overload resolution unless 
        * std::is_execution_policy_v\<std::decay_t\<ExecutionPolicy>> (until C++20) 
        * std::is_execution_policy_v\<std::remove_cvref_t\<ExecutionPolicy>> (since C++20) is true.
* unary_op and binary_op must not have side effects. (until C++11)
* unary_op and binary_op must not invalidate any iterators, including the end iterators, or modify any elements of the ranges involved. (since C++11)
* Parameters
    * `first1, last1`	-	the first range of elements to transform
    * `first2`	-	the beginning of the second range of elements to transform
    * `d_first`	-	the beginning of the destination range, may be equal to first1 or first2
    * `policy`	-	the execution policy to use. See execution policy for details.
    * `unary_op`	-	unary operation function object that will be applied.
        * The signature of the function should be equivalent to the following:
        * `Ret fun(const Type &a);`
        * The signature does not need to have const &.
        * The type Type must be such that an object of type InputIt can be dereferenced and then implicitly converted to Type. The type Ret must be such that an object of type OutputIt can be dereferenced and assigned a value of type Ret.
    * `binary_op`	-	binary operation function object that will be applied.
        * The signature of the function should be equivalent to the following:
        * `Ret fun(const Type1 &a, const Type2 &b);`
        * The signature does not need to have const &.
        * The types Type1 and Type2 must be such that objects of types InputIt1 and InputIt2 can be dereferenced and then implicitly converted to Type1 and Type2 respectively. The type Ret must be such that an object of type OutputIt can be dereferenced and assigned a value of type Ret.
    * Type requirements
        * -InputIt, InputIt1, InputIt2 must meet the requirements of LegacyInputIterator.
        * -OutputIt must meet the requirements of LegacyOutputIterator.
        * -ForwardIt1, ForwardIt2, ForwardIt3 must meet the requirements of LegacyForwardIterator.
* Return value
    * Output iterator to the element past the last element transformed.
* Complexity
    * 1-2) Exactly std::distance(first1, last1) applications of unary_op
    * 3-4) Exactly std::distance(first1, last1) applications of binary_op
* Exceptions
    * The overloads with a template parameter named ExecutionPolicy report errors as follows:
        * If execution of a function invoked as part of the algorithm throws an exception and ExecutionPolicy is one of the standard policies, std::terminate is called. For any other ExecutionPolicy, the behavior is implementation-defined.
        * If the algorithm fails to allocate memory, std::bad_alloc is thrown.
* Notes
    * std::transform does not guarantee in-order application of unary_op or binary_op. To apply a function to a sequence in-order or to apply a function that modifies the elements of a sequence, use std::for_each.
* Example
    * The following code uses transform to convert a string in place to uppercase using the std::toupper function and then transforms each char to its ordinal value:
```c++
#include <algorithm>
#include <cctype>
#include <iomanip>
#include <iostream>
#include <string>
#include <vector>
 
int main()
{
    std::string s{"hello"};
    std::transform(s.cbegin(), s.cend(),
                   s.begin(), // write to the same location
                   [](unsigned char c) { return std::toupper(c); });
    std::cout << "s = " << quoted(s) << '\n';
 
    // achieving the same with std::for_each (see Notes above)
    std::string g{"hello"};
    std::for_each(g.begin(), g.end(), [](char& c) { // modify in-place
        c = std::toupper(static_cast<unsigned char>(c));
    });
    std::cout << "g = " << quoted(g) << '\n';
 
    std::vector<std::size_t> ordinals;
    std::transform(s.cbegin(), s.cend(), std::back_inserter(ordinals),
                   [](unsigned char c) { return c; });
 
    std::cout << "ordinals: ";
    for (auto ord : ordinals) {
       std::cout << ord << ' ';
    }
 
    std::transform(ordinals.cbegin(), ordinals.cend(), ordinals.cbegin(),
                   ordinals.begin(), std::plus<>{});
 
    std::cout << "\nordinals: ";
    for (auto ord : ordinals) {
       std::cout << ord << ' ';
    }
    std::cout << '\n';
}
/*
s = "HELLO"
g = "HELLO"
ordinals: 72 69 76 76 79 
ordinals: 144 138 152 152 158
*/
```

##### MISC

* [std::transform() in C++ STL (Perform an operation on all elements) - GeeksforGeeks](https://www.geeksforgeeks.org/transform-c-stl-perform-operation-elements/)
* How to transform vector ?
```c++
#include <algorithm>
#include <iostream>
#include <vector>

struct myStruct
{
    int a, b;
};


int main()
{
    std::vector<myStruct> vMyStruct{ {1, 2}, {3, 4} };

    for (auto it : vMyStruct) {
        std::cout << it.a << " " << it.b << "\n";
    }

    std::transform(vMyStruct.cbegin(),
                    vMyStruct.cend(),
                    vMyStruct.begin(),
                    [](auto x) {
                        x.a += 10;
                        x.b += 10;
                        return x;
                    });

    std::cout << "After\n";
    for (auto it : vMyStruct) {
        std::cout << it.a << " " << it.b << "\n";
    }

    return 0;
}
/*
1 2
3 4
After
11 12
13 14
*/
```
* How to transform map v.s. vector ?
```c++
#include <iostream>
#include <algorithm>
#include <map>
#include <vector>


int main()
{
    // transform vector
    std::vector<double> myVec {1, 2, 3};

    std::transform(myVec.cbegin(),
                myVec.cend(),
                myVec.begin(),
                [](auto x) {    // effect
                    x = 2 * x;
                    return x;
                });

    for (auto it : myVec) {
        std::cout << it << "\n";
    }
    std::cout << "\n";

    // transform map
    std::map<uint64_t, double> myMap {{1, 1}, {2, 2}, {3, 3}};

    std::transform(myMap.begin(),
                myMap.end(),
                std::inserter(myMap, myMap.end()),
                [](auto x) {    // not effect
                    x.second = 2 * x.second;
                    return x;
                });

    for (auto it : myMap) {
        std::cout << it.first << " : " << it.second << "\n";
    }
    std::cout << "\n";

    std::transform(myMap.begin(),
                myMap.end(),
                std::inserter(myMap, myMap.end()),
                [](auto& x) {   // effect but safe with auto& ???
                    x.second = 2 * x.second;
                    return x;
                });

    for (auto it : myMap) {
        std::cout << it.first << " : " << it.second << "\n";
    }
    std::cout << "\n";

    return 0;
}
/*
2
4
6

1 : 1
2 : 2
3 : 3

1 : 2
2 : 4
3 : 6
*/
```
* [c++ - What is the difference between std::transform and std::for_each? - Stack Overflow](https://stackoverflow.com/questions/31064749/what-is-the-difference-between-stdtransform-and-stdfor-each#:~:text=std%3A%3Afor_each%20ignores%20the,guarantee%20the%20order%20of%20execution.)
	* std::transform is the same as map. The idea is to apply a function to each element in between the two iterators and obtain a different container composed of elements resulting from the application of such a function. You may want to use it for, e.g., projecting an object's data member into a new container. In the following, std::transform is used to transform a container of std::strings in a container of std::size_ts.
	* On the other hand, you execute std::for_each for the sole side effects. In other words, std::for_each closely resembles a plain range-based for loop.
	* Indeed, starting from C++11 the same can be achieved with a terser notation using range-based for loops
* [stl - C++ std::transform side effect - Stack Overflow](https://stackoverflow.com/questions/708742/c-stdtransform-side-effect)
* [How to apply transform to an STL map in C++ - Stack Overflow](https://stackoverflow.com/questions/7879326/how-to-apply-transform-to-an-stl-map-in-c)
	* You are missing the const in the first type of the pair.
	* `[](std::pair<const std::string, std::string>& p) {`
* [c++ - How do I use other values in a vector in a std::transform? - Stack Overflow](https://stackoverflow.com/questions/64191793/how-do-i-use-other-values-in-a-vector-in-a-stdtransform)
	* You can add lambda capture to store the previous element's value.
```c++
std::vector<int> v2(v1.size());
std::transform(v1.begin(), v1.end(), v2.begin(),
    [pv = 0](int val) mutable { int nv = pv + val; pv = val; return nv; });
```

#### [std::remove, std::remove_if](https://en.cppreference.com/w/cpp/algorithm/remove)

* removes elements satisfying specific criteria (function template)
* Return value
    * Past-the-end iterator for the new range of values (if this is not end, then it points to an unspecified value, and so do iterators to any values between this iterator and end).
* Complexity
    * Exactly std::distance(first, last) applications of the predicate.
* Notes
    * A call to remove is typically followed by a call to a container's erase method, which erases the unspecified values and reduces the physical size of the container to match its new logical size. These two invocations together constitute a so-called [Erase–remove idiom](https://en.wikipedia.org/wiki/Erase-remove_idiom), which can be achieved by the free function std::erase that has overloads for all standard sequence containers, or std::erase_if that has overloads for all standard containers (since C++20).
    * The similarly-named container member functions list::remove, list::remove_if, forward_list::remove, and forward_list::remove_if erase the removed elements.
    * These algorithms cannot be used with associative containers such as std::set and std::map because their iterator types do not dereference to MoveAssignable types (the keys in these containers are not modifiable).
    * The standard library also defines an overload of std::remove in \<cstdio>, which takes a const char* and is used to delete files.
    * Because std::remove takes value by reference, it can have unexpected behavior if it is a reference to an element of the range \[first, last).

##### MISC

* [std::remove, std::remove_if in c++ - GeeksforGeeks](https://www.geeksforgeeks.org/stdremove-stdremove_if-c/)
* [c++ - difference between erase and remove/remove_if algorithms? - Stack Overflow](https://stackoverflow.com/questions/3031923/difference-between-erase-and-remove-remove-if-algorithms)
    * No, std::remove_if will move the elements that don't match the predicate to the end of list and will return an iterator to the new "end". Erase will effectively drop the element (call the dtor) from the container.
    * The difference is perfectly illustrated by the examples
        * [remove_if - C++ Reference](https://cplusplus.com/reference/algorithm/remove_if/)
* [c++ - using remove_if for a map container - Stack Overflow](https://stackoverflow.com/questions/29004092/using-remove-if-for-a-map-container)
    * remove_if works by scanning the elements and once an element is to be removed, it remembers the "gap" that will leave (keeping an iterator pointing thereto) while advancing another iterator to find the next element to retain... it then starts copying or moving elements from the latter position to the former until it reaches end().
    * That doesn't work for map, because you can't overwrite the pair<key,value> elements wholesale: the key values aren't allowed to be modified or the sorted-order invariant the implementation needs could be invalidated.
    * So, you'll need to abandon remove_if. You could use a normal loop, being careful to save the iterator-to-next-element rather than attempting to advance from a just-erased iterator. Lots of other questions about how to erase elements from a map while iterating, e.g. here....
    * [c++ - How to remove from a map while iterating it? - Stack Overflow](https://stackoverflow.com/questions/8234779/how-to-remove-from-a-map-while-iterating-it)
* [c++ - remove_if equivalent for std::map - Stack Overflow](https://stackoverflow.com/questions/800955/remove-if-equivalent-for-stdmap)

#### [std::replace, std::replace_if](https://en.cppreference.com/w/cpp/algorithm/replace)

* replaces all values satisfying specific criteria with another value (function template)
* Replaces all elements satisfying specific criteria with new_value in the range `[first, last)`.
```c++
#include <algorithm>
#include <array>
#include <iostream>
#include <functional>
 
int main()
{
    std::array<int, 10> s{5, 7, 4, 2, 8, 6, 1, 9, 0, 3};
 
    std::replace(s.begin(), s.end(), 8, 88);
 
    for (int a : s) {
        std::cout << a << " ";
    }
    std::cout << '\n';
 
    std::replace_if(s.begin(), s.end(), 
                    std::bind(std::less<int>(), std::placeholders::_1, 5), 55);
    for (int a : s) {
        std::cout << a << " ";
    }
    std::cout << '\n';
}
/*
5 7 4 2 88 6 1 9 0 3
5 7 55 55 88 6 55 9 55 55
*/
```

#### [std::swap](https://en.cppreference.com/w/cpp/algorithm/swap)

* [swap() in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/swap-in-cpp/)

#### [std::iter_swap](https://en.cppreference.com/w/cpp/algorithm/iter_swap)

* swaps the elements pointed to by two iterators (function template)
* Swaps the values of the elements the given iterators are pointing to.
```c++
#include <random>
#include <vector>
#include <iostream>
#include <algorithm>
#include <functional>
 
template<class ForwardIt>
void selection_sort(ForwardIt begin, ForwardIt end)
{
    for (ForwardIt i = begin; i != end; ++i)
        std::iter_swap(i, std::min_element(i, end));
}
 
int main()
{
    std::random_device rd;
    std::mt19937 gen(rd());
    std::uniform_int_distribution<> dist(-9, +9);
    std::vector<int> v;
    std::generate_n(back_inserter(v), 20, bind(dist, gen));
 
    std::cout << "Before sort: " << std::showpos;
    for (auto e : v)
        std::cout << e << ' ';
 
    selection_sort(v.begin(), v.end());
 
    std::cout << "\nAfter sort : ";
    for (auto e : v)
        std::cout << e << ' ';
    std::cout << '\n';
}
/*
Before sort: -9 -3 +2 -8 +0 -1 +8 -4 -5 +1 -4 -5 +4 -9 -8 -6 -6 +8 -4 -6 
After sort : -9 -9 -8 -8 -6 -6 -6 -5 -5 -4 -4 -4 -3 -1 +0 +1 +2 +4 +8 +8
*/
```

#### [std::reverse](https://en.cppreference.com/w/cpp/algorithm/reverse)

* reverses the order of elements in a range (function template)
* Parameters
    * `first, last`	-	the range of elements to reverse
    * `policy`	-	the execution policy to use. See execution policy for details.
* Type requirements
    * -BidirIt must meet the requirements of ValueSwappable and LegacyBidirectionalIterator.
* Return value
    * (none)
* Complexity
    * Exactly (last - first)/2 swaps.
* Exceptions
    * The overload with a template parameter named ExecutionPolicy reports errors as follows:
    * If execution of a function invoked as part of the algorithm throws an exception and ExecutionPolicy is one of the standard policies, std::terminate is called. For any other ExecutionPolicy, the behavior is implementation-defined.
    * If the algorithm fails to allocate memory, std::bad_alloc is thrown.
```c++
#include <vector>
#include <iostream>
#include <iterator>
#include <algorithm>
 
int main()
{
    std::vector<int> v{1, 2, 3};
    std::reverse(v.begin(), v.end());
    for(auto e : v) std::cout << e;
    std::cout << '\n';
 
    int a[] = {4, 5, 6, 7};
    std::reverse(std::begin(a), std::end(a));
    for(auto e : a) std::cout << e;
}
/*
321
7654
*/
```

### Partitioning operations

### Sorting operations

#### [std::sort](https://en.cppreference.com/w/cpp/algorithm/sort)

* Sorts the elements in the range \[first, last) in non-descending order. The order of equal elements is not guaranteed to be preserved.
* [std::sort() in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/sort-c-stl/)
```c++
#include <algorithm>
#include <functional>
#include <array>
#include <iostream>
#include <string_view>
 
int main()
{
    std::array<int, 10> s = {5, 7, 4, 2, 8, 6, 1, 9, 0, 3};
 
    auto print = [&s](std::string_view const rem) {
        for (auto a : s) {
            std::cout << a << ' ';
        }
        std::cout << ": " << rem << '\n';
    };
 
    std::sort(s.begin(), s.end());
    print("sorted with the default operator<");
 
    std::sort(s.begin(), s.end(), std::greater<int>());
    print("sorted with the standard library compare function object");
 
    struct {
        bool operator()(int a, int b) const { return a < b; }
    } customLess;
    std::sort(s.begin(), s.end(), customLess);
    print("sorted with a custom function object");
 
    std::sort(s.begin(), s.end(), [](int a, int b) {
        return a > b;
    });
    print("sorted with a lambda expression");
}

/*
0 1 2 3 4 5 6 7 8 9 : sorted with the default operator<
9 8 7 6 5 4 3 2 1 0 : sorted with the standard library compare function object
0 1 2 3 4 5 6 7 8 9 : sorted with a custom function object
9 8 7 6 5 4 3 2 1 0 : sorted with a lambda expression
*/
```

### Binary search operations (on sorted ranges)

#### [std::lower_bound](https://en.cppreference.com/w/cpp/algorithm/lower_bound)

* returns an iterator to the first element not less than the given value (function template)
* Returns an iterator pointing to the first element in the range `[first, last)` that does not satisfy element < value (or comp(element, value)), (i.e. greater or equal to), or last if no such element is found.
* The range `[first, last)` must be partitioned with respect to the expression element < value (or comp(element, value)), i.e., all elements for which the expression is true must precede all elements for which the expression is false. A fully-sorted range meets this criterion.
* The first version uses operator< to compare the elements, the second version uses the given comparison function comp.

##### MISC

* [Lower Bound-STL | HackerRank](https://www.hackerrank.com/challenges/cpp-lower-bound/problem)
```c++
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */   
    int n, temp, q, y;
    vector<int> vec;
    vector<int>::iterator   low;
    
    cin >> n;
    for (int i = 0; i < n; i ++) {
        cin >> temp;
        vec.push_back(temp);
    }
    
    sort(vec.begin(), vec.end());
    
    cin >> q;
    for (int i = 0; i < q; i ++) {
        cin >> y;
        low = lower_bound(vec.begin(), vec.end(), y);
        if (*low == y) 
            cout << "Yes " << low - vec.begin() + 1 << endl;
        else
            cout << "No " << low - vec.begin() + 1 << endl;         
    }
    
    return 0;
}
```

#### [std::upper_bound](https://en.cppreference.com/w/cpp/algorithm/upper_bound)

* returns an iterator to the first element greater than a certain value (function template)
* Returns an iterator pointing to the first element in the range \[first, last) such that value < element (or comp(value, element)) is true (i.e. strictly greater), or last if no such element is found.
* The range `[first, last)` must be partitioned with respect to the expression !(value < element) or !comp(value, element), i.e., all elements for which the expression is true must precede all elements for which the expression is false. A fully-sorted range meets this criterion.
* The first version uses operator< to compare the elements, the second version uses the given comparison function comp.

### Other operations on sorted ranges

### Set operations (on sorted ranges)

#### [std::set_intersection](https://en.cppreference.com/w/cpp/algorithm/set_intersection)

* computes the intersection of two sets (function template)
* Constructs a sorted range beginning at d_first consisting of elements that are found in both sorted ranges `[first1, last1)` and `[first2, last2)`. If some element is found m times in `[first1, last1)` and n times in `[first2, last2)`, the first `std::min(m, n)` elements will be copied from the first range to the destination range. The order of equivalent elements is preserved. The resulting range cannot overlap with either of the input ranges.
```c++
#include <iostream>
#include <vector>
#include <algorithm>
#include <iterator>
int main()
{
    std::vector<int> v1{1,2,3,4,5,6,7,8};
    std::vector<int> v2{        5,  7,  9,10};
    std::sort(v1.begin(), v1.end());
    std::sort(v2.begin(), v2.end());
 
    std::vector<int> v_intersection;
 
    std::set_intersection(v1.begin(), v1.end(),
                          v2.begin(), v2.end(),
                          std::back_inserter(v_intersection));
    for(int n : v_intersection)
        std::cout << n << ' ';
}
```

##### MISC

* [std::set_intersection in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/std-set_intersection-in-cpp/)
	* find the common elements in two vectors

### Heap operations

### Minimum/maximum operations

#### [std::max](https://en.cppreference.com/w/cpp/algorithm/max)
	
* returns the greater of the given values (function template)
* [Maximum of three values in C++ - Code Review Stack Exchange](https://codereview.stackexchange.com/questions/26100/maximum-of-three-values-in-c)
	* `std::max({a, b, c})`

#### [std::max_element](https://en.cppreference.com/w/cpp/algorithm/max_element)
	
* returns the largest element in a range (function template)
* Finds the greatest element in the range `[first, last)`.
* Return value
    * Iterator to the greatest element in the range `[first, last)`. If several elements in the range are equivalent to the greatest element, returns the iterator to the first such element. Returns last if the range is empty.
* Complexity
    * Exactly max(N-1,0) comparisons, where N = std::distance(first, last).
```c++
#include <algorithm>
#include <iostream>
#include <vector>
#include <cmath>
 
static bool abs_compare(int a, int b)
{
    return (std::abs(a) < std::abs(b));
}
 
int main()
{
    std::vector<int> v{ 3, 1, -14, 1, 5, 9 }; 
    std::vector<int>::iterator result;
 
    result = std::max_element(v.begin(), v.end());
    std::cout << "max element at: " << std::distance(v.begin(), result) << '\n';
 
    result = std::max_element(v.begin(), v.end(), abs_compare);
    std::cout << "max element (absolute) at: " << std::distance(v.begin(), result) << '\n';
}
```

##### MISC

* [Find element with the maximum value in a map in C++ | Techie Delight](https://www.techiedelight.com/find-element-with-the-maximum-value-in-a-map-in-cpp/)
	* 1. Using std::max_element
	* 2. Using Loop
	* Note that user defined condition, e.g. x.second < 4 && y.second < 4, doesn't work
```c++
#include <iostream>
#include <map>
#include <algorithm>
 
int main()
{
    std::map<std::string, int> map = {
        {"two", 2}, {"one", 1}, {"four", 4}, {"three", 3}
    };
 
    auto pr = std::max_element(map.begin(), map.end(), [](const auto &x, const auto &y) {
                    return x.second < y.second;
                });
 
    std::cout << pr->first << std::endl;        // four

    pr = std::max_element(map.begin(), map.end(), [](const auto &x, const auto &y) {
                    return x.second < y.second && x.second < 4 && y.second < 4;
                });
 
    std::cout << pr->first << std::endl;        // still four rather than three
 
    return 0;
}
```

#### [std::min](https://en.cppreference.com/w/cpp/algorithm/min)
	
* Returns the smaller of the given values.
    * 1-2) Returns the smaller of a and b.
    * 3-4) Returns the smallest of the values in initializer list ilist.
* The (1,3) versions use operator< to compare the values, the (2,4) versions use the given comparison function comp.
* Notes
    * Capturing the result of std::min by reference produces a dangling reference if one of the parameters is a temporary and that parameter is returned:
```c++
int n = 1;
const int& r = std::min(n - 1, n + 1); // r is dangling
```
* Example
```c++
#include <algorithm>
#include <iostream>
#include <string_view>
 
int main()
{
    std::cout << "smaller of 1 and 9999 is " << std::min(1, 9999) << '\n'
              << "smaller of 'a', and 'b' is '" << std::min('a', 'b') << "'\n"
              << "shortest of \"foo\", \"bar\", and \"hello\" is \""
              << std::min({"foo", "bar", "hello"},
                          [](const std::string_view s1, const std::string_view s2)
                          {
                              return s1.size() < s2.size();
                          }) << "\"\n";
}
/*
smaller of 1 and 9999 is 1
smaller of 'a', and 'b' is 'a'
shortest of "foo", "bar", and "hello" is "foo"
*/
```

##### MISC

* [std::min in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/stdmin-in-cpp/)
* [max - Find the smallest amongst 3 numbers in C++ - Stack Overflow](https://stackoverflow.com/questions/9424173/find-the-smallest-amongst-3-numbers-in-c)
    * `std::min({x, y, z})`

#### [std::min_element](https://en.cppreference.com/w/cpp/algorithm/min_element)
	
* returns the smallest element in a range (function template)
* Return value
    * Iterator to the smallest element in the range `[first, last)`. If several elements in the range are equivalent to the smallest element, returns the iterator to the first such element. Returns last if the range is empty.
* Complexity
    * Exactly max(N-1,0) comparisons, where N = std::distance(first, last).
* Exceptions
    * The overloads with a template parameter named ExecutionPolicy report errors as follows:
        * If execution of a function invoked as part of the algorithm throws an exception and ExecutionPolicy is one of the standard policies, std::terminate is called. For any other ExecutionPolicy, the behavior is implementation-defined.
        * If the algorithm fails to allocate memory, std::bad_alloc is thrown.
```c++
#include <algorithm>
#include <iostream>
#include <vector>
 
int main()
{
    std::vector<int> v{3, 1, 4, 1, 5, 9};
 
    std::vector<int>::iterator result = std::min_element(v.begin(), v.end());
    std::cout << "min element at: " << std::distance(v.begin(), result);
}
/*
min element at: 1
*/
```

#### [std::minmax](https://en.cppreference.com/w/cpp/algorithm/minmax)

* returns the smaller and larger of two elements (function template)
* Returns the lowest and the greatest of the given values.
    * 1-2) Returns references to the smaller and the greater of a and b.
    * 3-4) Returns the smallest and the greatest of the values in initializer list ilist.
* The (1,3) versions use operator< to compare the values, whereas the (2,4) versions use the given comparison function comp.
* Return value
    * 1-2) Returns the result of std::pair\<const T&, const T&>(a, b) if a\<b or if a is equivalent to b. Returns the result of std::pair\<const T&, const T&>(b, a) if b<a.
    * 3-4) A pair with the smallest value in ilist as the first element and the greatest as the second. If several elements are equivalent to the smallest, the leftmost such element is returned. If several elements are equivalent to the largest, the rightmost such element is returned.
* Complexity
    * 1-2) Exactly one comparison
    * 3-4) At most ilist.size() * 3 / 2 comparisons
* Notes
    * For overloads (1,2), if one of the parameters is a temporary, the reference returned becomes a dangling reference at the end of the full expression that contains the call to minmax:
```c++
int n = 1;
auto p = std::minmax(n, n+1);
int m = p.first; // ok
int x = p.second; // undefined behavior
 
// Note that structured bindings have the same issue
auto [mm, xx] = std::minmax(n, n+1);
xx; // undefined behavior
```
* Example
```c++
#include <algorithm>
#include <iostream>
#include <vector>
#include <cstdlib>
#include <ctime>
 
int main()
{
    std::vector<int> v {3, 1, 4, 1, 5, 9, 2, 6}; 
    std::srand(std::time(0));
    std::pair<int, int> bounds = std::minmax(std::rand() % v.size(),
                                             std::rand() % v.size());
 
    std::cout << "v[" << bounds.first << "," << bounds.second << "]: ";
    for (int i = bounds.first; i < bounds.second; ++i) {
        std::cout << v[i] << ' ';
    }
    std::cout << '\n';
}
/*
v[2,7]: 4 1 5 9 2
*/
```

##### MISC

* [std::minmax() and std::minmax_element() in C++ STL - GeeksforGeeks](https://www.geeksforgeeks.org/stdminmax-stdminmax_element-c-stl/)

#### [std::minmax_element](https://en.cppreference.com/w/cpp/algorithm/minmax_element)

* returns the smallest and the largest elements in a range (function template)
* Finds the smallest and greatest element in the range \[first, last).
* Return value
    * a pair consisting of an iterator to the smallest element as the first element and an iterator to the greatest element as the second. Returns std::make_pair(first, first) if the range is empty. If several elements are equivalent to the smallest element, the iterator to the first such element is returned. If several elements are equivalent to the largest element, the iterator to the last such element is returned.
* Complexity
    * At most max(floor((3/2)*(N−1)), 0) applications of the predicate, where N = std::distance(first, last).
* Exceptions
    * The overloads with a template parameter named ExecutionPolicy report errors as follows:
        * If execution of a function invoked as part of the algorithm throws an exception and ExecutionPolicy is one of the standard policies, std::terminate is called. For any other ExecutionPolicy, the behavior is implementation-defined.
        * If the algorithm fails to allocate memory, std::bad_alloc is thrown.
* Notes
    * This algorithm is different from std::make_pair(std::min_element(), std::max_element()), not only in efficiency, but also in that this algorithm finds the last biggest element while std::max_element finds the first biggest element.
```c++
#include <algorithm>
#include <iostream>
 
int main() {
    const auto v = { 3, 9, 1, 4, 2, 5, 9 };
    const auto [min, max] = std::minmax_element(begin(v), end(v));
 
    std::cout << "min = " << *min << ", max = " << *max << '\n';
}
/*
min = 1, max = 9
*/
```

### Comparison operations

* Defined in header `<algorithm>`

#### [std::equal](https://en.cppreference.com/w/cpp/algorithm/equal)

* determines if two sets of elements are the same (function template)
* Two ranges are considered equal if they have the same number of elements and, for every iterator i in the range `[first1,last1)`, `*i` equals `*(first2 + (i - first1))`. The overloads (1,2,5,6) use `operator==` to determine if two elements are equal, whereas overloads (3,4,7,8) use the given binary predicate `p`.
* Notes
    * `std::equal` should `not` be used to compare the ranges formed by the iterators from `std::unordered_set`, `std::unordered_multiset`, `std::unordered_map`, or `std::unordered_multimap` because the order in which the elements are stored in those containers may be different even if the two containers store the same elements.
    * When comparing entire containers for equality, `operator==` for the corresponding container are usually preferred.
* Example
    * The following code uses std::equal to test if a string is a palindrome.
```c++
#include <algorithm>
#include <iostream>
#include <string_view>
 
constexpr bool is_palindrome(const std::string_view& s)
{
    return std::equal(s.begin(), s.begin() + s.size()/2, s.rbegin());
}
 
void test(const std::string_view& s)
{
    std::cout << "\"" << s << "\" "
        << (is_palindrome(s) ? "is" : "is not")
        << " a palindrome\n";
}
 
int main()
{
    test("radar");
    test("hello");
}
/*
"radar" is a palindrome
"hello" is not a palindrome
*/
```

### Permutation operations

### Numeric operations

* Defined in header `<numeric>`

#### [std::iota](https://en.cppreference.com/w/cpp/algorithm/iota)

* fills a range with successive increments of the starting value (function template)
* Fills the range `[first, last)` with sequentially increasing values, starting with value and repetitively evaluating ++value.
* Equivalent operation:
```c++
*(first)   = value;
*(first+1) = ++value;
*(first+2) = ++value;
*(first+3) = ++value;
...
```
* Complexity
    * Exactly last - first increments and assignments.
```c++
#include <algorithm>
#include <iomanip>
#include <iostream>
#include <list>
#include <numeric>
#include <random>
#include <vector>
 
class BigData // inefficient to copy
{
    int data[1024]; /* some raw data */
public:
    explicit BigData(int i = 0) { data[0] = i; /* ... */ }
    operator int () const { return data[0]; }
    BigData& operator=(int i) { data[0] = i; return *this; }
    /* ... */
};
 
int main()
{
    std::list<BigData> l(10);
    std::iota(l.begin(), l.end(), -4);
 
    std::vector<std::list<BigData>::iterator> v(l.size());
    std::iota(v.begin(), v.end(), l.begin());
    // Vector of iterators (to original data) is used to avoid expensive copying,
    // and because std::shuffle (below) cannot be applied to a std::list directly.
 
    std::shuffle(v.begin(), v.end(), std::mt19937{std::random_device{}()});
 
    std::cout << "Original contents of the list l:\t";
    for(auto const& n: l) std::cout << std::setw(2) << n << ' ';
    std::cout << '\n';
 
    std::cout << "Contents of l, viewed via shuffled v:\t";
    for(auto const i: v) std::cout << std::setw(2) << *i << ' ';
    std::cout << '\n';
}
/*
Original contents of the list l:        -4 -3 -2 -1  0  1  2  3  4  5
Contents of l, viewed via shuffled v:   -1  5 -4  0  2  1  4 -2  3 -3
*/
```

#### [std::accumulate](https://en.cppreference.com/w/cpp/algorithm/accumulate)
	
* sums up a range of elements(function template)
* Return value
    * 1) The sum of the given value and elements in the given range.
    * 2) The result of left fold of the given range over op
```c++
#include <iostream>
#include <numeric>
#include <map>
#include <vector>
 
int main()
{
    std::map<int, int> mp{{1, 1}, {3, 3}, {2, 2}};
    
    auto sum_map = std::accumulate(mp.begin(), mp.end(), 
                                    0, 
                                    [](const auto& a, const auto& b){
                                        return a + b.first * b.second;
                                    });
    
    std::vector<int> v{1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
 
    int sum = std::accumulate(v.begin(), v.end(), 0);
 
    int product = std::accumulate(v.begin(), v.end(), 1, std::multiplies<int>());
 
    auto dash_fold = [](std::string a, int b) {
                         return std::move(a) + '-' + std::to_string(b);
                     };
 
    std::string s = std::accumulate(std::next(v.begin()), v.end(),
                                    std::to_string(v[0]), // start with first element
                                    dash_fold);
 
    // Right fold using reverse iterators
    std::string rs = std::accumulate(std::next(v.rbegin()), v.rend(),
                                     std::to_string(v.back()), // start with last element
                                     dash_fold);
 
    std::cout << "sum_map: " << sum_map << '\n'
              << "sum: " << sum << '\n'
              << "product: " << product << '\n'
              << "dash-separated string: " << s << '\n'
              << "dash-separated string (right-folded): " << rs << '\n';
}
/*
sum_map: 14
sum: 55
product: 3628800
dash-separated string: 1-2-3-4-5-6-7-8-9-10
dash-separated string (right-folded): 10-9-8-7-6-5-4-3-2-1
*/
```

#### [std::inner_product](https://en.cppreference.com/w/cpp/algorithm/inner_product)
	
* computes the inner product of two ranges of elements (function template)
* Computes inner product (i.e. sum of products) or performs ordered map/reduce operation on the range `[first1, last1)` and the range beginning at first2.
```c++
#include <numeric>
#include <iostream>
#include <vector>
#include <functional>
int main()
{
    std::vector<int> a{0, 1, 2, 3, 4};
    std::vector<int> b{5, 4, 2, 3, 1};
 
    int r1 = std::inner_product(a.begin(), a.end(), b.begin(), 0);
    std::cout << "Inner product of a and b: " << r1 << '\n';
 
    int r2 = std::inner_product(a.begin(), a.end(), b.begin(), 0,
                                std::plus<>(), std::equal_to<>());
    std::cout << "Number of pairwise matches between a and b: " <<  r2 << '\n';
}
```

#### [std::partial_sum](https://en.cppreference.com/w/cpp/algorithm/partial_sum)
	
* computes the partial sum of a range of elements(function template)
* Return value
    * Iterator to the element past the last element written.

### Operations on uninitialized memory

### C library

## [Numerics library](https://en.cppreference.com/w/cpp/numeric)

* The C++ numerics library includes common mathematical functions and types, as well as optimized numeric arrays and support for random number generation.

### Mathematical functions and types

#### [Common mathematical functions](https://en.cppreference.com/w/cpp/numeric/math)

* The header `<cmath>` provides standard C library mathematical functions such as std::fabs, std::sqrt, and std::sin.
* [std::div, std::ldiv, std::lldiv - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/div)
	* Defined in header `<cstdlib>`
	* computes quotient and remainder of integer division (function)
	* Computes both the quotient and the remainder of the division of the numerator x by the denominator y.
	* The quotient is the result of the expression x/y. The remainder is the result of the expression x%y.

#
Basic operations

* [std::abs(float), std::fabs, std::fabsf, std::fabsl - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/fabs)
	* absolute value of a floating point value (|x|) (function)
* [std::fmod, std::fmodf, std::fmodl - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/fmod)
	* remainder of the floating point division operation (function)
	* The floating-point remainder of the division operation x/y calculated by this function is exactly the value x - n*y, where n is x/y with its fractional part truncated.
	* The returned value has the same sign as x and is less than y in magnitude.
```c++
#include <iostream>
#include <cmath>
#include <cfenv>
 
// #pragma STDC FENV_ACCESS ON
int main()
{
    std::cout << "fmod(+5.1, +3.0) = " << std::fmod(5.1,3) << '\n'
              << "fmod(-5.1, +3.0) = " << std::fmod(-5.1,3) << '\n'
              << "fmod(+5.1, -3.0) = " << std::fmod(5.1,-3) << '\n'
              << "fmod(-5.1, -3.0) = " << std::fmod(-5.1,-3) << '\n'
              << "fmod(1.1, 0.2) = " << std::fmod(1.1,0.2) << '\n'
              << "fmod(1.0, 0.2) = " << std::fmod(1.0,0.2) << '\n';
 
    // special values
    std::cout << "fmod(+0.0, 1.0) = " << std::fmod(0, 1) << '\n'
              << "fmod(-0.0, 1.0) = " << std::fmod(-0.0, 1) << '\n'
              << "fmod(5.1, Inf) = " << std::fmod(5.1, INFINITY) << '\n';
 
    // error handling
    std::feclearexcept(FE_ALL_EXCEPT);
    std::cout << "fmod(+5.1, 0) = " << std::fmod(5.1, 0) << '\n';
    if(std::fetestexcept(FE_INVALID))
        std::cout << "    FE_INVALID raised\n";
}
/*
fmod(+5.1, +3.0) = 2.1
fmod(-5.1, +3.0) = -2.1
fmod(+5.1, -3.0) = 2.1
fmod(-5.1, -3.0) = -2.1
fmod(1.1, 0.2) = 0.1
fmod(1.0, 0.2) = 0.2
fmod(+0.0, 1.0) = 0
fmod(-0.0, 1.0) = -0
fmod(5.1, Inf) = 5.1
fmod(+5.1, 0) = -nan
    FE_INVALID raised
*/
```
* [std::nan, std::nanf, std::nanl - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/nan)
	* not-a-number (NaN) (function)
	* Defined in header \<cmath>
	* `float       nanf( const char* arg ); (1)	(since C++11)`
	* `double      nan( const char* arg ); (2)	(since C++11)`
	* `long double nanl( const char* arg ); (3)	(since C++11)`
	* Converts the character string arg into the corresponding quiet NaN value, as if by calling std::strtof, std::strtod, or std::strtold, respectively.
		* 1) The call std::nanf("n-char-sequence"), where n-char-sequence is a sequence of digits, ASCII letters, and underscores, is equivalent to the call std::strtof("NAN(n-char-sequence)", (char**)nullptr);.
			* The call std::nanf("") is equivalent to the call std::strtof("NAN()", (char**)nullptr);.
			* The call std::nanf("string"), where string is neither an n-char-sequence nor an empty string, is equivalent to the call std::strtof("NAN", (char**)nullptr);.
		* 2) Same as (1), but calls std::strtod instead of std::strtof.
		* 3) Same as (1), but calls std::strtold instead of std::strtof.

#
Nearest integer floating point operations

* [std::ceil, std::ceilf, std::ceill - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/ceil)
	* nearest integer not less than the given value (function)
	* Notes
		* FE_INEXACT may be (but isn't required to be) raised when rounding a non-integer finite value.
		* The largest representable floating-point values are exact integers in all standard floating-point formats, so this function never overflows on its own; however the result may overflow any integer type (including std::intmax_t), when stored in an integer variable.
```c++
#include <cmath>
#include <iostream>
int main()
{
    std::cout << std::fixed
              << "ceil(+2.4) = " << std::ceil(+2.4) << '\n'
              << "ceil(-2.4) = " << std::ceil(-2.4) << '\n'
              << "ceil(-0.0) = " << std::ceil(-0.0) << '\n'
              << "ceil(-Inf) = " << std::ceil(-INFINITY) << '\n';
}
/*
ceil(+2.4) = 3.000000
ceil(-2.4) = -2.000000
ceil(-0.0) = -0.000000
ceil(-Inf) = -inf
*/
```
* [std::round, std::roundf, std::roundl, std::lround, std::lroundf, std::lroundl, std::llround, std::llroundf - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/round)
	* nearest integer, rounding away from zero in halfway cases (function)
```c++
#include <iostream>
#include <cmath>
#include <cfenv>
#include <climits>
 
// #pragma STDC FENV_ACCESS ON
 
int main()
{
    // round
    std::cout << "round(+2.3) = " << std::round(2.3)
              << "  round(+2.5) = " << std::round(2.5)
              << "  round(+2.7) = " << std::round(2.7) << '\n'
              << "round(-2.3) = " << std::round(-2.3)
              << "  round(-2.5) = " << std::round(-2.5)
              << "  round(-2.7) = " << std::round(-2.7) << '\n';
 
    std::cout << "round(-0.0) = " << std::round(-0.0)  << '\n'
              << "round(-Inf) = " << std::round(-INFINITY) << '\n';
 
    // lround
    std::cout << "lround(+2.3) = " << std::lround(2.3)
              << "  lround(+2.5) = " << std::lround(2.5)
              << "  lround(+2.7) = " << std::lround(2.7) << '\n'
              << "lround(-2.3) = " << std::lround(-2.3)
              << "  lround(-2.5) = " << std::lround(-2.5)
              << "  lround(-2.7) = " << std::lround(-2.7) << '\n';
 
    std::cout << "lround(-0.0) = " << std::lround(-0.0)  << '\n'
              << "lround(-Inf) = " << std::lround(-INFINITY) << '\n';
 
    // error handling
    std::feclearexcept(FE_ALL_EXCEPT);
    std::cout << "std::lround(LONG_MAX+1.5) = "
              << std::lround(LONG_MAX+1.5) << '\n';
    if (std::fetestexcept(FE_INVALID))
              std::cout << "    FE_INVALID was raised\n";
}
/*
round(+2.3) = 2  round(+2.5) = 3  round(+2.7) = 3
round(-2.3) = -2  round(-2.5) = -3  round(-2.7) = -3
round(-0.0) = -0
round(-Inf) = -inf
lround(+2.3) = 2  lround(+2.5) = 3  lround(+2.7) = 3
lround(-2.3) = -2  lround(-2.5) = -3  lround(-2.7) = -3
lround(-0.0) = 0
lround(-Inf) = -9223372036854775808
std::lround(LONG_MAX+1.5) = -9223372036854775808
    FE_INVALID was raised
*/
```
* [Round to 2 decimal places in C++ - Java2Blog](https://java2blog.com/round-to-2-decimal-places-cpp/#:~:text=double%20type%20variables.-,Using%20the%20ceil()%20function%20to%20round%20to%202%20decimal,decimal%20places%20in%20C%2B%2B.)
	* `std::round(x * 100.0) / 100.0`

#
Classification and comparison

* [std::isnan - cppreference.com](https://en.cppreference.com/w/cpp/numeric/math/isnan)
	* checks if the given number is NaN (function)
```c++
#include <iostream>
#include <cmath>
#include <cfloat>
 
int main()
{
    std::cout << std::boolalpha
              << "isnan(NaN) = " << std::isnan(NAN) << '\n'
              << "isnan(Inf) = " << std::isnan(INFINITY) << '\n'
              << "isnan(0.0) = " << std::isnan(0.0) << '\n'
              << "isnan(DBL_MIN/2.0) = " << std::isnan(DBL_MIN/2.0) << '\n'
              << "isnan(0.0 / 0.0)   = " << std::isnan(0.0/0.0) << '\n'
              << "isnan(Inf - Inf)   = " << std::isnan(INFINITY - INFINITY) << '\n';
}
/*
isnan(NaN) = true
isnan(Inf) = false
isnan(0.0) = false
isnan(DBL_MIN/2.0) = false
isnan(0.0 / 0.0)   = true
isnan(Inf - Inf)   = true
*/
```
* [NaN in C++ - What is it and How to Check For it? - GeeksforGeeks](https://www.geeksforgeeks.org/nan-in-cpp-what-is-it-and-how-to-check-for-it/)
	* NaN, an acronym for Not a Number is an exception that usually occurs in the cases when an expression results in a number that is undefined or can’t be represented. It is used for floating-point operations. For example:
		* The square root of negative numbers
		* Division by zero
		* Taking the log of zero or a negative number etc.

#### [Mathematical constants (since C++20)](https://en.cppreference.com/w/cpp/numeric/constants)

* The header \<numbers> provides several mathematical constants, such as std::numbers::pi or std::numbers::sqrt2
* [How to use the PI constant in C++?](https://www.tutorialspoint.com/how-to-use-the-pi-constant-in-cplusplus)
	* The PI constant is present in the cmath header file. The name of the constant is M_PI. 

### Miscellanous

#### [Pseudo-random number generation](https://en.cppreference.com/w/cpp/numeric/random)

* The header \<random> defines pseudo-random number generators and numerical distributions. The header \<cstdlib> also includes C-style random number generation via std::srand and std::rand.
* [std::uniform_int_distribution - cppreference.com](https://en.cppreference.com/w/cpp/numeric/random/uniform_int_distribution)
* [c++ - C++11 random numbers - Stack Overflow](https://stackoverflow.com/questions/14009637/c11-random-numbers/14009667#14009667)
* [c++ - Generate random numbers using C++11 random library - Stack Overflow](https://stackoverflow.com/questions/19665818/generate-random-numbers-using-c11-random-library/19666713#19666713)
```c++
#include <random>
#include <iostream>
 
int main()
{
    std::random_device rd;  //Will be used to obtain a seed for the random number engine
    std::mt19937 gen(rd()); //Standard mersenne_twister_engine seeded with rd()
    std::uniform_int_distribution<> distrib(1, 6);
 
    for (int n=0; n<10; ++n)
        //Use `distrib` to transform the random unsigned int generated by gen into an int in [1, 6]
        std::cout << distrib(gen) << ' ';
    std::cout << '\n';
}
```

## [Date and time utilities](https://en.cppreference.com/w/cpp/chrono)

* C++ includes support for two types of time manipulation:
	* The chrono library, a flexible collection of types that track time with varying degrees of precision (e.g. std::chrono::time_point).
	* C-style date and time library (e.g. std::time)
* [C++ Date and Time](https://www.tutorialspoint.com/cplusplus/cpp_date_time.htm)
* [Chrono in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/chrono-in-c/)

### [\<chrono>](https://en.cppreference.com/w/cpp/header/chrono)

* The chrono library defines three main types as well as utility functions and common typedefs.
	* clocks
	* time points
	* durations

#### Clocks

* A clock consists of a starting point (or epoch) and a tick rate. For example, a clock may have an epoch of January 1, 1970 and tick every second. C++ defines several clock types:
* [The Three Clocks - ModernesCpp.com](https://www.modernescpp.com/index.php/the-three-clocks)

##### [std::chrono::system_clock](https://en.cppreference.com/w/cpp/chrono/system_clock) 

* Class std::chrono::system_clock represents the system-wide real time wall clock.
* It may not be monotonic: on most systems, the system time can be adjusted at any moment. It is the only C++ clock that has the ability to map its time points to C-style time.
* std::chrono::system_clock meets the requirements of TrivialClock.
* [std::chrono::system_clock::now - cppreference.com](https://en.cppreference.com/w/cpp/chrono/system_clock/now)
	* Returns a time point representing the current point in time.
* [How to get current time and date in C++? - Stack Overflow](https://stackoverflow.com/questions/997946/how-to-get-current-time-and-date-in-c) 
	* In C++ 11 you can use std::chrono::system_clock::now()
* [c++11 - how to convert "std::chrono::system_clock::now()" to double - Stack Overflow](https://stackoverflow.com/questions/45464711/how-to-convert-stdchronosystem-clocknow-to-double)
	* https://wandbox.org/permlink/qe1MNGQAR5X3zJl8
```c++
#include <chrono>
#include <iostream>
int main()
{
    auto current_time = std::chrono::system_clock::now();
    auto duration_in_seconds = std::chrono::duration<double>(current_time.time_since_epoch());
    
    std::cout << duration_in_seconds.count() << std::endl; // 1.50169e+09
}
```
* How to get certain time in current date ?
```c++
#include <iostream>
#include <iomanip>   // std::put_time
#include <chrono> 

int main()
{
    using namespace std::chrono_literals;

    setenv("TZ", "Asia/Tokyo", 1);
 
    std::tm tm{};  // zero initialise
    tm.tm_year = 2022-1900; // 2022
    tm.tm_mon = 10-1; // Oct
    tm.tm_mday = 18; // 18th
    tm.tm_hour = 9;
    tm.tm_min = 0;
    tm.tm_sec = 0;
    tm.tm_isdst = 0; // Not daylight saving
    std::time_t t = std::mktime(&tm); 
    std::tm local = *std::localtime(&t);
    std::cout << "local: " << std::put_time(&local, "%c %Z") << '\n';
    // std::cout << "local: " << std::put_time(std::localtime(&t), "%c %Z") << '\n';

    auto from = std::chrono::system_clock::from_time_t(t) - 0h;
    auto time = from.time_since_epoch().count();
    std::cout << time << '\n';

    auto current_time = std::chrono::system_clock::now();
    auto current_time_t = std::chrono::system_clock::to_time_t(current_time);
    auto _local = *std::localtime(&current_time_t);
    std::cout << "_local: " << std::put_time(&_local, "%c %Z") << '\n';

    _local.tm_hour = 9;
    _local.tm_min = 0;
    _local.tm_sec = 0;
    _local.tm_isdst = 0; // Not daylight saving
    std::cout << "_local: " << std::put_time(&_local, "%c %Z") << '\n';

    std::time_t _t = std::mktime(&_local); 
    auto _from = std::chrono::system_clock::from_time_t(_t);
    auto _time = _from.time_since_epoch().count();
    std::cout << _time << '\n';

    return 0;
}
/*
local: Tue Oct 18 09:00:00 2022 JST
1666051200000000000
_local: Tue Oct 18 10:15:42 2022 JST
_local: Tue Oct 18 09:00:00 2022 JST
1666051200000000000
*/
```
* [Get current timestamp in milliseconds since Epoch in C++ | Techie Delight](https://www.techiedelight.com/get-current-timestamp-in-milliseconds-since-epoch-in-cpp/#:~:text=Since%20C%2B%2B11%2C%20we,of%20time%20elapsed%20since%20Epoch.)
	* 1. Using std::chrono
	* 2. Using std::time
```c++
#include <iostream>
#include <chrono>

int main()
{
	using namespace std::chrono;

	uint64_t ns = (system_clock::now().time_since_epoch()).count();
	std::cout << ns << " nanoseconds since the Epoch\n";

	uint64_t us = duration_cast<microseconds>(system_clock::now().time_since_epoch()).count();
	std::cout << us << " microseconds since the Epoch\n";

	uint64_t ms = duration_cast<milliseconds>(system_clock::now().time_since_epoch()).count();
	std::cout << ms << " milliseconds since the Epoch\n";

	uint64_t sec = duration_cast<seconds>(system_clock::now().time_since_epoch()).count();
	std::cout << sec << " seconds since the Epoch\n";

	return 0;
}
/*
1661387354156146179 nanoseconds since the Epoch
1661387354156241 microseconds since the Epoch
1661387354156 milliseconds since the Epoch
1661387354 seconds since the Epoch
*/
```
* [std::chrono::system_clock::to_time_t - cppreference.com](https://en.cppreference.com/w/cpp/chrono/system_clock/to_time_t)
	* Converts t to a std::time_t type.
	* If std::time_t has lower precision, it is implementation-defined whether the value is rounded or truncated.
* [std::chrono::system_clock::from_time_t - cppreference.com](https://en.cppreference.com/w/cpp/chrono/system_clock/from_time_t) 
	* Converts t to a time point type, using the coarser precision of the two types.
	* If time_point has lower precision, it is implementation defined whether the value is rounded or truncated.

##### [std::chrono::steady_clock](https://en.cppreference.com/w/cpp/chrono/steady_clock) 

* Class std::chrono::steady_clock represents a monotonic clock. The time points of this clock cannot decrease as physical time moves forward and the time between ticks of this clock is constant. This clock is not related to wall clock time (for example, it can be time since last reboot), and is most suitable for measuring intervals.
* std::chrono::steady_clock meets the requirements of TrivialClock.		

##### [std::chrono::high_resolution_clock](https://en.cppreference.com/w/cpp/chrono/high_resolution_clock) 

* Class std::chrono::high_resolution_clock represents the clock with the smallest tick period provided by the implementation. It may be an alias of std::chrono::system_clock or std::chrono::steady_clock, or a third, independent clock.
* std::chrono::high_resolution_clock meets the requirements of TrivialClock.		

#### Time point

* A time point is a duration of time that has passed since the epoch of a specific clock.
* [std::chrono::time_point - cppreference.com](https://en.cppreference.com/w/cpp/chrono/time_point)
	* a point in time (class template)
	* Class template std::chrono::time_point represents a point in time. It is implemented as if it stores a value of type Duration indicating the time interval from the start of the Clock's epoch.
	* [std::chrono::time_point<Clock,Duration>::time_since_epoch - cppreference.com](https://en.cppreference.com/w/cpp/chrono/time_point/time_since_epoch)
		* `constexpr duration time_since_epoch() const;`
		* returns the time point as duration since the start of its clock (public member function)
		* Returns a duration representing the amount of time between *this and the clock's epoch.
	* [operator==,!=,<,<=,>,>=,<=>(std::chrono::time_point) - cppreference.com](https://en.cppreference.com/w/cpp/chrono/time_point/operator_cmp)
		* Compares two time points. The comparison is done by comparing the results time_since_epoch() for the time points.
```c++
#include <iostream>
#include <chrono>
#include <ctime>
 
int main()
{
    const auto p0 = std::chrono::time_point<std::chrono::system_clock>{};
    const auto p1 = std::chrono::system_clock::now();
    const auto p2 = p1 - std::chrono::hours(24);
 
    std::time_t epoch_time = std::chrono::system_clock::to_time_t(p0);
    std::cout << "epoch: " << std::ctime(&epoch_time);
    std::time_t today_time = std::chrono::system_clock::to_time_t(p1);
    std::cout << "today: " << std::ctime(&today_time);
 
    std::cout << "hours since epoch: "
              << std::chrono::duration_cast<std::chrono::hours>(
                   p1.time_since_epoch()).count() 
              << '\n';
    std::cout << "yesterday, hours since epoch: "
              << std::chrono::duration_cast<std::chrono::hours>(
                   p2.time_since_epoch()).count() 
              << '\n';
}
/*
epoch: Thu Jan  1 00:00:00 1970
today: Fri Jun 30 10:44:11 2017
hours since epoch: 416338
yesterday, hours since epoch: 416314
*/
```

#### Duration

* A duration consists of a span of time, defined as some number of ticks of some time unit. For example, "42 seconds" could be represented by a duration consisting of 42 ticks of a 1-second time unit.
* [std::chrono::duration - cppreference.com](https://en.cppreference.com/w/cpp/chrono/duration)
	* a time interval (class template)
	* Class template std::chrono::duration represents a time interval.
	* It consists of a count of ticks of type Rep and a tick period, where the tick period is a compile-time rational fraction representing the time in seconds from one tick to the next.
	* The only data stored in a duration is a tick count of type Rep. If Rep is floating point, then the duration can represent fractions of ticks. Period is included as part of the duration's type, and is only used when converting between different durations.
	* [std::chrono::duration<Rep,Period>::count - cppreference.com](https://en.cppreference.com/w/cpp/chrono/duration/count)
		* Returns the number of ticks for this duration.
	* [std::chrono::duration_cast - cppreference.com](https://en.cppreference.com/w/cpp/chrono/duration/duration_cast)
		* Converts a std::chrono::duration to a duration of different type ToDuration.

##### Helper types

| std::chrono::nanoseconds(C++11)  | duration type with Period std::nano |
|- | - |
| std::chrono::microseconds(C++11) | duration type with Period std::micro |
| std::chrono::milliseconds(C++11) | duration type with Period std::milli |
| std::chrono::seconds(C++11)      | duration type with Period std::ratio<1> |
| std::chrono::minutes(C++11)      | duration type with Period std::ratio<60> |
| std::chrono::hours(C++11)        | duration type with Period std::ratio<3600> |
| std::chrono::days(C++20)         | duration type with Period std::ratio<86400> |
| std::chrono::weeks(C++20)        | duration type with Period std::ratio<604800> |
| std::chrono::months(C++20)       | duration type with Period std::ratio<2629746> |
| std::chrono::years(C++20)        | duration type with Period std::ratio<31556952> |

##### Literals

* Defined in inline namespace std::literals::chrono_literals

|[operator""h](https://en.cppreference.com/w/cpp/chrono/operator%22%22h) (C++14)|A std::chrono::duration literal representing hours (function)|
|-|-|
|[operator""min](https://en.cppreference.com/w/cpp/chrono/operator%22%22min) (C++14)|A std::chrono::duration literal representing minutes (function)|
|[operator""s](https://en.cppreference.com/w/cpp/chrono/operator%22%22s) (C++14)|A std::chrono::duration literal representing seconds (function)|
|[operator""ms](https://en.cppreference.com/w/cpp/chrono/operator%22%22ms) (C++14)|A std::chrono::duration literal representing milliseconds (function)|
|[operator""us](https://en.cppreference.com/w/cpp/chrono/operator%22%22us) (C++14)|A std::chrono::duration literal representing microseconds (function)|
|[operator""ns](https://en.cppreference.com/w/cpp/chrono/operator%22%22ns) (C++14)|A std::chrono::duration literal representing nanoseconds (function)|
|[operator""d](https://en.cppreference.com/w/cpp/chrono/operator%22%22d) (C++20)|A std::chrono::day literal representing a day of a month (function)|
|[operator""y](https://en.cppreference.com/w/cpp/chrono/operator%22%22y) (C++20)|A std::chrono::year literal representing a particular year (function)|

### [C-style date and time library](https://en.cppreference.com/w/cpp/chrono/c)

* Also provided are the C-style date and time functions, such as std::time_t, std::difftime, and CLOCKS_PER_SEC.
* Defined in header \<ctime>

#### Functions

* [std::time - cppreference.com](https://en.cppreference.com/w/cpp/chrono/c/time)
	* `std::time_t time( std::time_t* arg );`
	* returns the current time of the system as time since epoch (function)
	* Returns the current calendar time encoded as a std::time_t object, and also stores it in the object pointed to by arg, unless arg is a null pointer.
	* Parameters
		* arg	-	pointer to a std::time_t object to store the time, or a null pointer
	* Return value
		* Current calendar time encoded as std::time_t object on success, (std::time_t)(-1) on error. If arg is not null, the return value is also stored in the object pointed to by arg.
	* Notes
		* The encoding of calendar time in std::time_t is unspecified, but most systems conform to the POSIX specification and return a value of integral type holding 86400 times the number of calendar days since the Epoch plus the number of seconds that have passed since the last midnight UTC. Most notably, POSIX time does not (and can not) take leap seconds into account, so that this integral value is not equal to the number of S.I. seconds that have passed since the epoch, but rather is reduced with the number of leap seconds that have occurred since the epoch. Implementations in which std::time_t is a 32-bit signed integer (many historical implementations) fail in the year 2038.
```c++
#include <ctime>
#include <iostream>
 
int main()
{
    std::time_t result = std::time(nullptr);
    std::cout << std::asctime(std::localtime(&result))
              << result << " seconds since the Epoch\n";
}
/*
Wed Sep 21 10:27:52 2011
1316615272 seconds since the Epoch
*/
```
* [std::localtime - cppreference.com](https://en.cppreference.com/w/cpp/chrono/c/localtime)
	* `std::tm* localtime( const std::time_t *time );`
	* converts time since epoch to calendar time expressed as local time (function)
	* Converts given time since epoch as std::time_t value into calendar time, expressed in local time.
	* Parameters
		* time	-	pointer to a std::time_t object to convert
	* Return value
		* pointer to a static internal std::tm object on success, or null pointer otherwise. The structure may be shared between std::gmtime, std::localtime, and std::ctime, and may be overwritten on each invocation.
	* Notes
		* This function may not be thread-safe.
		* POSIX requires that this function sets errno to EOVERFLOW if it fails because the argument is too large.
		* POSIX specifies that the timezone information is determined by this function as if by calling tzset, which reads the environment variable TZ.
```c++
#include <iostream>
#include <sstream>
#include <iomanip>
#include <ctime>
 
int main()
{
    setenv("TZ", "/usr/share/zoneinfo/America/Los_Angeles", 1); // POSIX-specific
 
    std::tm tm{};  // zero initialise
    tm.tm_year = 2020-1900; // 2020
    tm.tm_mon = 2-1; // February
    tm.tm_mday = 15; // 15th
    tm.tm_hour = 10;
    tm.tm_min = 15;
    tm.tm_isdst = 0; // Not daylight saving
    std::time_t t = std::mktime(&tm); 
 
    std::cout << "UTC:   " << std::put_time(std::gmtime(&t), "%c %Z") << '\n';
    std::cout << "local: " << std::put_time(std::localtime(&t), "%c %Z") << '\n';
}
/*
UTC:   Sat Feb 15 18:15:00 2020 GMT
local: Sat Feb 15 10:15:00 2020 PST
*/
```
* [std::mktime - cppreference.com](https://en.cppreference.com/w/cpp/chrono/c/mktime)
	* `std::time_t mktime( std::tm* time );`
	* converts calendar time to time since epoch (function)
	* Converts local calendar time to a time since epoch as a time_t object. time->tm_wday and time->tm_yday are ignored. The values in time are permitted to be outside their normal ranges.
	* A negative value of time->tm_isdst causes mktime to attempt to determine if Daylight Saving Time was in effect.
	* If the conversion is successful, the time object is modified. All fields of time are updated to fit their proper ranges. time->tm_wday and time->tm_yday are recalculated using information available in other fields.
	* Parameters
		* time	-	pointer to a std::tm object specifying local calendar time to convert
	* Return value
		* Time since epoch as a std::time_t object on success or -1 if time cannot be represented as a std::time_t object.
	* Notes
		* If the std::tm object was obtained from std::get_time or the POSIX strptime, the value of tm_isdst is indeterminate, and needs to be set explicitly before calling mktime.
```c++
#include <iostream>
#include <sstream>
#include <iomanip>
#include <ctime>
 
int main()
{
    setenv("TZ", "/usr/share/zoneinfo/America/Los_Angeles", 1); // POSIX-specific
 
    std::tm tm{};  // zero initialise
    tm.tm_year = 2020-1900; // 2020
    tm.tm_mon = 2-1; // February
    tm.tm_mday = 15; // 15th
    tm.tm_hour = 10;
    tm.tm_min = 15;
    tm.tm_isdst = 0; // Not daylight saving
    std::time_t t = std::mktime(&tm); 
    std::tm local = *std::localtime(&t);
 
    std::cout << "local: " << std::put_time(&local, "%c %Z") << '\n';
}
/*
local: Sat Feb 15 10:15:00 2020 PST
*/
```
* [C library function - mktime()](https://www.tutorialspoint.com/c_standard_library/c_function_mktime.htm)
* [mktime - C++ Reference](https://cplusplus.com/reference/ctime/mktime/)
* [std::get_time - cppreference.com](https://en.cppreference.com/w/cpp/io/manip/get_time)
	* parses a date/time value of specified format (function template)
	* Defined in header \<iomanip>
	* `template< class CharT > /*unspecified*/ get_time( std::tm* tmb, const CharT* fmt ); (since C++11)`
	* When used in an expression in >> get_time(tmb, fmt), parses the character input as a date/time value according to format string fmt according to the std::time_get facet of the locale currently imbued in the input stream in. The resultant value is stored in a std::tm object pointed to by tmb.
```c++
#include <iostream>
#include <sstream>
#include <locale>
#include <iomanip>
 
int main()
{
    std::tm t = {};
    std::istringstream ss("2011-Februar-18 23:12:34");
    ss.imbue(std::locale("de_DE.utf-8"));
    ss >> std::get_time(&t, "%Y-%b-%d %H:%M:%S");
 
    if (ss.fail())
        std::cout << "Parse failed\n";
    else
        std::cout << std::put_time(&t, "%c") << '\n';
}
/*
Sun Feb 18 23:12:34 2011
*/
```
* [std::put_time - cppreference.com](https://en.cppreference.com/w/cpp/io/manip/put_time)
	* formats and outputs a date/time value according to the specified format (function template)
	* Defined in header \<iomanip>
	* `template< class CharT > /*unspecified*/ put_time( const std::tm* tmb, const CharT* fmt ); (since C++11)
	* When used in an expression out << put_time(tmb, fmt), converts the date and time information from a given calendar time tmb to a character string according to format string fmt, as if by calling std::strftime, std::wcsftime, or analog (depending on CharT), according to the std::time_put facet of the locale currently imbued in the output stream out.
```c++
#include <iostream>
#include <iomanip>
#include <ctime>
#include <chrono>
 
int main()
{
    std::time_t t = std::time(nullptr);
    std::tm tm = *std::localtime(&t);
 
    std::cout.imbue(std::locale("ru_RU.utf8"));
    std::cout << "ru_RU: " << std::put_time(&tm, "%c %Z") << '\n';
 
    std::cout.imbue(std::locale("ja_JP.utf8"));
    std::cout << "ja_JP: " << std::put_time(&tm, "%c %Z") << '\n';

    auto current_time = std::chrono::system_clock::now();
    auto current_time_t = std::chrono::system_clock::to_time_t(current_time);
    std::cout << std::put_time(std::localtime(&current_time_t), "%Y%m%d") << '\n';

    // convert current time to string
    std::stringstream ss {};
    ss << std::put_time(std::localtime(&current_time_t), "%Y%m%d");
    std::cout << ss.str() << '\n';
    
    return 0;
}
/*
ru_RU: Сб 26 ноя 2022 07:11:36 CET
ja_JP: 2022年11月26日 07時11分36秒 CET
20221126
20221126
*/
```

#### Constants

#### Types

* [std::tm - cppreference.com](https://en.cppreference.com/w/cpp/chrono/c/tm)
	* calendar time type (class)
	* Structure holding a calendar date and time broken down into its components.
	* Member objects

|int tm_sec | seconds after the minute – [0, 60] (since C++11) (public member object)|
|-|-|
|int tm_min|minutes after the hour – [0, 59] (public member object)|
|int tm_hour|hours since midnight – [0, 23] (public member object)|
|int tm_mday|day of the month – [1, 31] (public member object)|
|int tm_mon|months since January – [0, 11] (public member object)|
|int tm_year|years since 1900 (public member object)|
|int tm_wday|days since Sunday – [0, 6] (public member object)|
|int tm_yday|days since January 1 – [0, 365] (public member object)|
|int tm_isdst|Daylight Saving Time flag. The value is positive if DST is in effect, zero if not and negative if no information is available (public member object)|

```c++
#include <ctime>
#include <iostream>
 
int main()
{
    std::tm start{};
    start.tm_mday = 1;
 
    std::mktime(&start);
    std::cout << std::asctime(&start)
              << "sizeof(std::tm) = "
              << sizeof(std::tm) << '\n';
}
/*
Mon Jan  1 00:00:00 1900
sizeof(std::tm) = 56
*/
```
* [std::time_t - cppreference.com](https://en.cppreference.com/w/cpp/chrono/c/time_t)
	* time since epoch type (typedef)
	* Arithmetic type capable of representing times.
	* Although not defined, this is almost always an integral value holding the number of seconds (not counting leap seconds) since 00:00, Jan 1 1970 UTC, corresponding to POSIX time.

### MISC

* [现代C++编程实践(五)—如何使用时间库](https://mp.weixin.qq.com/s/JrXYKSm7sEHV8X87X-Bgzg)
```c++
#include <iostream>
#include <iomanip>
#include <chrono>


std::ostream& operator<<(std::ostream &os,const std::chrono::time_point<std::chrono::system_clock> &t) {
    const auto ltime(std::chrono::system_clock::to_time_t(t));
    const auto localTime(std::localtime(&ltime));
    return os << std::put_time(localTime, "%c %Z");
}

using hours = std::chrono::duration<std::chrono::hours::rep, 
                                    std::ratio_multiply<std::chrono::hours::period, std::ratio<1> > >;
constexpr hours operator ""_hours(unsigned long long h) {
    return hours {h};
}

int main()
{
    auto now(std::chrono::system_clock::now());
    std::cout << "当前时间是:" << now << "\n12小时后是:" << (now + 12_hours) << std::endl;
    return 0;
}
/*
当前时间是:Tue Oct 18 01:02:08 2022 UTC
12小时后是:Tue Oct 18 13:02:08 2022 UTC
*/
```
* [c++ - How to parse a date string into a c++11 std::chrono time_point or similar? - Stack Overflow](https://stackoverflow.com/questions/21021388/how-to-parse-a-date-string-into-a-c11-stdchrono-time-point-or-similar) 
	* [std::get_time - cppreference.com](https://en.cppreference.com/w/cpp/io/manip/get_time) 
		* When used in an expression in >> get_time(tmb, fmt), parses the character input as a date/time value according to format string fmt according to the std::time_get facet of the locale currently imbued in the input stream in. The resultant value is stored in a std::tm object pointed to by tmb.
	* [mktime - cppreference.com](https://en.cppreference.com/w/c/chrono/mktime)
		* Renormalizes local calendar time expressed as a struct tm object and also converts it to time since epoch as a time_t object. time->tm_wday and time->tm_yday are ignored. The values in time are not checked for being out of range.
		* A negative value of time->tm_isdst causes mktime to attempt to determine if Daylight Saving Time was in effect in the specified time.
		* If the conversion to time_t is successful, the time object is modified. All fields of time are updated to fit their proper ranges. time->tm_wday and time->tm_yday are recalculated using information available in other fields. 
* [Print System Time in C++ | Delft Stack](https://www.delftstack.com/howto/cpp/system-time-in-cpp/) 
	* [std::strftime - cppreference.com](https://en.cppreference.com/w/cpp/chrono/c/strftime)
		* Converts the date and time information from a given calendar time time to a null-terminated multibyte character string str according to format string format. Up to count bytes are written.
* [Outputting Date and Time in C++ using std::chrono - Stack Overflow](https://stackoverflow.com/questions/17223096/outputting-date-and-time-in-c-using-stdchrono)
* [c++ - C++11 get current date and time as string - Stack Overflow](https://stackoverflow.com/questions/34963738/c11-get-current-date-and-time-as-string)
* [c++ - Format no such file or directory - Stack Overflow](https://stackoverflow.com/questions/65083544/format-no-such-file-or-directory)
  * According to this: https://en.cppreference.com/w/cpp/compiler_support there are currently no compilers that support "Text formatting" (P0645R10, std::format). (As of December 2020)
* [c++ - can't include std::format - Stack Overflow](https://stackoverflow.com/questions/63017719/cant-include-stdformat)
  * As of July 2020 none of the standard library implementations provide std::format. Until they do you can use the {fmt} library std::format is based on:
* [c++ - How to use the \<format> header - Stack Overflow](https://stackoverflow.com/questions/61441494/how-to-use-the-format-header)
  * Use libfmt. The \<format> header is essentially a standardized libfmt (with a few small features removed, if I remember correctly).

## [Input/output library](https://en.cppreference.com/w/cpp/io)

* C++ includes two input/output libraries: an OOP-style stream-based I/O library and the standard set of C-style I/O functions.

### Stream-based I/O

* The stream-based input/output library is organized around abstract input/output devices. These abstract devices allow the same code to handle input/output to files, memory streams, or custom adaptor devices that perform arbitrary operations (e.g. compression) on the fly.
* Most of the classes are templated, so they can be adapted to any basic character type. Separate typedefs are provided for the most common basic character types (char and wchar_t). The classes are organized into the following hierarchy:
![image](https://user-images.githubusercontent.com/34557994/166664893-b2b25c27-7205-42f2-8836-cc67245bd81b.png)
* [【ZZ】cin、cin.get()、cin.getline()、getline()、gets()等函数的用法 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2011/04/21/2024345.html)

#### Abstraction

* Defined in header `<ios>`

##### [std::ios_base](https://en.cppreference.com/w/cpp/io/ios_base)

* manages formatting flags and input/output exceptions (class)

###### Member functions

###### Member classes

###### Member types and constants

#
[std::ios_base::openmode](https://en.cppreference.com/w/cpp/io/ios_base/openmode)

* stream open mode type
* Specifies available file open flags. It is a BitmaskType, the following constants are defined:

| Constant | Explanation |
| - | - |
| app | seek to the end of stream before each write |
| binary | open in binary mode |
| in | open for reading |
| out | open for writing |
| trunc | discard the contents of the stream when opening |
| ate | seek to the end of stream immediately after open |
| noreplace (C++23) | open in exclusive mode |

##### [std::basic_ios](https://en.cppreference.com/w/cpp/io/basic_ios)

* manages an arbitrary stream buffer (class template)
* The class `std::basic_ios` provides facilities for interfacing with objects that have `std::basic_streambuf` interface. Several `std::basic_ios` objects can refer to one actual `std::basic_streambuf` object.

###### Public member functions

#
Miscellaneous

* [std::basic_ios<CharT,Traits>::rdbuf](https://en.cppreference.com/w/cpp/io/basic_ios/rdbuf)
    * manages associated stream buffer (public member function)
    * Example
    ```c++
    #include <iostream>
    #include <sstream>

    int main()
    {
        std::ostringstream local;
        auto cout_buff = std::cout.rdbuf(); // save pointer to std::cout buffer

        std::cout.rdbuf(local.rdbuf()); // substitute internal std::cout buffer with
            // buffer of 'local' object

        // now std::cout work with 'local' buffer
        // you don't see this message
        std::cout << "some message";

        // go back to old buffer
        std::cout.rdbuf(cout_buff);

        // you will see this message
        std::cout << "back to default buffer\n";

        // print 'local' content
        std::cout << "local content: " << local.str() << "\n";
    }
    /*
    back to default buffer
    local content: some message
    */
    ```
* [c++ - How to read a whole text file at once? - Stack Overflow](https://stackoverflow.com/questions/13035674/how-to-read-a-file-line-by-line-or-a-whole-text-file-at-once)
```c++
int main(int argc, char* argv[])
{
    std::stringstream ss{};
    ss << std::cin.rdbuf();
    auto s = ss.str();
    std::cout << s << '\n' << s.size() << '\n';
}

$ cat ./test.in | ./my_pgm
```

##### [std::basic_ostream](https://en.cppreference.com/w/cpp/io/basic_ostream)

* Defined in header `<ostream>`
* wraps a given abstract device (std::basic_streambuf) and provides high-level output interface (class template)
* The class template basic_ostream provides support for high level output operations on character streams. The supported operations include formatted output (e.g. integer values) and unformatted output (e.g. raw characters and character arrays). This functionality is implemented in terms of the interface provided by the basic_streambuf class, accessed through the basic_ios base class. In typical implementations, basic_ostream has no non-inherited data members.

###### Member functions

#
Unformatted output

* [std::basic_ostream<CharT,Traits>::write](https://en.cppreference.com/w/cpp/io/basic_ostream/write)
    * inserts blocks of characters (public member function)
    * `basic_ostream& write( const char_type* s, std::streamsize count );`
    * Behaves as an UnformattedOutputFunction. After constructing and checking the sentry object, outputs the characters from successive locations in the character array whose first element is pointed to by s. Characters are inserted into the output sequence until one of the following occurs:
        * exactly count characters are inserted
        * inserting into the output sequence fails (in which case `setstate(badbit)` is called)
* Return value
    * `*this`
* Notes
    * This function is not overloaded for the types `signed char` or `unsigned char`, unlike the formatted `operator<<`
    * Also, unlike the formatted output functions, this function does not set the failbit on failure.
    * When using a non-converting locale (the default locale is non-converting), the overrider of this function in `std::basic_ofstream` may be optimized for zero-copy bulk I/O (by means of overriding `std::streambuf::xsputn`)
* Example
    * This function may be used to output object representations, i.e. binary output
```c++
#include <iostream>
 
int main()
{
    int n = 0x41424344;
    std::cout.write(reinterpret_cast<char*>(&n), sizeof n) << '\n';
 
    char c[]="This is sample text.";
    std::cout.write(c, 4).write("!\n", 2);
}
/*
DCBA
This!
*/
```

##### [std::basic_istream](https://en.cppreference.com/w/cpp/io/basic_istream)

* Defined in header `<istream>`
* wraps a given abstract device (std::basic_streambuf) and provides high-level input interface (class template)
* The class template basic_istream provides support for high level input operations on character streams. The supported operations include formatted input (e.g. integer values or whitespace-separated characters and characters strings) and unformatted input (e.g. raw characters and character arrays). This functionality is implemented in terms of the interface provided by the underlying basic_streambuf class, accessed through the basic_ios base class. The only non-inherited data member of basic_istream, in most implementations, is the value returned by `basic_istream::gcount()`.

###### Member functions

#
Unformatted input

* [std::basic_istream<CharT,Traits>::get](https://en.cppreference.com/w/cpp/io/basic_istream/get)
    * extracts characters (public member function)
    * Extracts character or characters from stream.
    * Example
    ```c++
    #include <sstream>
    #include <iostream>

    int main()
    {
        std::istringstream s1("Hello, world.");
        char c1 = s1.get(); // reads 'H'
        std::cout << "after reading " << c1 << ", gcount() == " <<  s1.gcount() << '\n';
        char c2;
        s1.get(c2);         // reads 'e'
        char str[5];
        s1.get(str, 5);     // reads "llo,"
        std::cout << "after reading " << str << ", gcount() == " <<  s1.gcount() << '\n';
        std::cout << c1 << c2 << str;
        s1.get(*std::cout.rdbuf()); // reads the rest, not including '\n'
        std::cout << "\nAfter the last get(), gcount() == " << s1.gcount() << '\n';
    }
    /*
    after reading H, gcount() == 1
    after reading llo,, gcount() == 4
    Hello, world.
    After the last get(), gcount() == 7
    */
    ```
* [std::basic_istream<CharT,Traits>::read](https://en.cppreference.com/w/cpp/io/basic_istream/read)
    * extracts blocks of characters (public member function)
    * Extracts characters from stream.
    * Example
    ```c++
    #include <iostream>
    #include <fstream>
    #include <sstream>
    #include <string>
    #include <cstdint>

    int main()
    {
        // read() is often used for binary I/O
        std::string bin = {'\x12', '\x12', '\x12', '\x12'};
        std::istringstream raw(bin);
        std::uint32_t n;
        if(raw.read(reinterpret_cast<char*>(&n), sizeof n))
            std::cout << std::hex << std::showbase << n << '\n';

        // prepare file for next snippet
        std::ofstream("test.txt", std::ios::binary) << "abcd1\nabcd2\nabcd3";

        // read entire file into string
        if(std::ifstream is{"test.txt", std::ios::binary | std::ios::ate}) {
            auto size = is.tellg();
            std::string str(size, '\0'); // construct string to stream size
            is.seekg(0);
            if(is.read(&str[0], size))
                std::cout << str << '\n';
        }
    }
    /*
    0x12121212
    abcd1
    abcd2
    abcd3
    */
    ```

#### File I/O

* Defined in header `<fstream>`
* [Reading and writing binary file in C/C++](https://www.tutorialspoint.com/reading-and-writing-binary-file-in-c-cplusplus#)

##### [std::basic_ifstream](https://en.cppreference.com/w/cpp/io/basic_ifstream)

* implements high-level file stream input operations (class template)
* [ifstream - C++ Reference](https://www.cplusplus.com/reference/fstream/ifstream/)
    * Input file stream class
        * Input stream class to operate on files.
        * Objects of this class maintain a filebuf object as their internal stream buffer, which performs input/output operations on the file they are associated with (if any).
        * File streams are associated with files either on construction, or by calling member open.
        * Apart from the internal file stream buffer, objects of this class keep a set of internal fields inherited from ios_base, ios and istream
    * [ifstream::is_open - C++ Reference](https://www.cplusplus.com/reference/fstream/ifstream/is_open/)
    * [ifstream::close - C++ Reference](https://www.cplusplus.com/reference/fstream/ifstream/close/)
    * [Read file line by line using C++](https://www.tutorialspoint.com/read-file-line-by-line-using-cplusplus)
    * [reading and using data in a .csv file - C++ Forum](http://www.cplusplus.com/forum/beginner/157129/)
    * [getline (string) - C++ Reference](https://www.cplusplus.com/reference/string/string/getline/)
    * [C++检测一个文件是否存在 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5640920.html)

##### [std::basic_ofstream](https://en.cppreference.com/w/cpp/io/basic_ofstream)

* implements high-level file stream output operations (class template)
* [ofstream - C++ Reference](https://www.cplusplus.com/reference/fstream/ofstream/)
    * Output file stream
        * Output stream class to operate on files.
        * Objects of this class maintain a filebuf object as their internal stream buffer, which performs input/output operations on the file they are associated with (if any).
        * File streams are associated with files either on construction, or by calling member open.
        * Apart from the internal file stream buffer, objects of this class keep a set of internal fields inherited from ios_base, ios and istream
    * [ofstream::close - C++ Reference](https://www.cplusplus.com/reference/fstream/ofstream/close/)
        * Close file
            * Closes the file currently associated with the object, disassociating it from the stream.
            * Any pending output sequence is written to the file.
            * If the stream is currently not associated with any file (i.e., no file has successfully been open with it), calling this function fails.
            * The file association of a stream is kept by its internal stream buffer:
            * Internally, the function calls rdbuf()->close(), and sets failbit in case of failure.
            * Note that any open file is automatically closed when the ofstream object is destroyed.
    * [ofstream::is_open - C++ Reference](https://www.cplusplus.com/reference/fstream/ofstream/is_open/)
        * Check if file is open
            * Returns whether the stream is currently associated to a file.
            * Streams can be associated to files by a successful call to member open or directly on construction, and disassociated by calling close or on destruction.
            * The file association of a stream is kept by its internal stream buffer:
                * Internally, the function calls rdbuf()->is_open()
    * [ofstream::ofstream - C++ Reference](https://www.cplusplus.com/reference/fstream/ofstream/ofstream/)
        * Construct object
            * Constructs an ofstream object
    * [replace line in a file C++](https://www.py4u.net/discuss/81342)

#### String I/O

* Defined in header `<sstream>`

##### [std::basic_ostringstream](https://en.cppreference.com/w/cpp/io/basic_ostringstream)

* implements high-level string stream output operations (class template)
* [ostringstream - C++ Reference](https://www.cplusplus.com/reference/sstream/ostringstream/)
	* Output stream class to operate on strings.
	* Objects of this class use a string buffer that contains a sequence of characters. This sequence of characters can be accessed directly as a string object, using member str.
	* Characters can be inserted into the stream with any operation allowed on output streams.
	* [ostringstream::str - C++ Reference](https://www.cplusplus.com/reference/sstream/ostringstream/str/)
	* string str() const;
	* void str (const string& s);
	* Get/set content
		* The first form (1) returns a string object with a copy of the current contents of the stream.
		* The second form (2) sets s as the contents of the stream, discarding any previous contents. The object preserves its open mode: if this includes ios_base::ate, the writing position is moved to the end of the new sequence.
		* Internally, the function calls the str member of its internal string buffer object.

##### [std::basic_stringstream](https://en.cppreference.com/w/cpp/io/basic_stringstream)

* implements high-level string stream input/output operations (class template)

###### Member types

###### Member functions

* [std::basic_stringstream::rdbuf](https://en.cppreference.com/w/cpp/io/basic_stringstream/rdbuf)
    * returns the underlying raw string device object (public member function)
    * Returns pointer to the underlying raw string device object.

#
String operations

* [std::basic_stringstream<CharT,Traits,Allocator>::str](https://en.cppreference.com/w/cpp/io/basic_stringstream/str)
    * gets or sets the contents of underlying string device object (public member function)
* Notes
    * The copy of the underlying string returned by str is a temporary object that will be destructed at the end of the expression, so directly calling c_str() on the result of str() (for example in `auto *ptr = out.str().c_str();`) results in a `dangling pointer`.
* Example
```c++
#include <sstream>
#include <iostream>
int main()
{
    int n;
 
    std::istringstream in;  // could also use in("1 2")
    in.str("1 2");
    in >> n;
    std::cout << "after reading the first int from \"1 2\", the int is "
              << n << ", str() = \"" << in.str() << "\"\n";
 
    std::ostringstream out("1 2");
    out << 3;
    std::cout << "after writing the int '3' to output stream \"1 2\""
              << ", str() = \"" << out.str() << "\"\n";
 
    std::ostringstream ate("1 2", std::ios_base::ate);
    ate << 3;
    std::cout << "after writing the int '3' to append stream \"1 2\""
              << ", str() = \"" << ate.str() << "\"\n";
}
/*
after reading the first int from "1 2", the int is 1, str() = "1 2"
after writing the int '3' to output stream "1 2", str() = "3 2"
after writing the int '3' to append stream "1 2", str() = "1 23"
*/
```

###### Non-member functions

#
* Inherited from [std::basic_istream](https://en.cppreference.com/w/cpp/io/basic_istream)
	* [operator>>](https://en.cppreference.com/w/cpp/io/basic_istream/operator_gtgt)
		* extracts formatted data (public member function of std::basic_istream\<CharT,Traits>)

#
* Inherited from [std::basic_ostream](https://en.cppreference.com/w/cpp/io/basic_ostream)
	* [operator<<](https://en.cppreference.com/w/cpp/io/basic_ostream/operator_ltlt)
		* inserts formatted data (public member function of std::basic_ostream\<CharT,Traits>)

#
* Inherited from [std::basic_ios](https://en.cppreference.com/w/cpp/io/basic_ios)

#
* Inherited from [std::ios_base](https://en.cppreference.com/w/cpp/io/ios_base)

###### MISC

* [stringstream in C++ and its applications - GeeksforGeeks](https://www.geeksforgeeks.org/stringstream-c-applications/)
	* A stringstream associates a string object with a stream allowing you to read from the string as if it were a stream (like cin).
	* Basic methods are –
		* clear() — to clear the stream
		* str() — to get and set string object whose content is present in stream.
		* operator << — add a string to the stringstream object.
		* operator >> — read something from the stringstream object,
* [StringStream | HackerRank](https://www.hackerrank.com/challenges/c-tutorial-stringstream/problem)
```c++
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
#include <sstream>  // std::stringstream
using namespace std;


vector<int> parseInts(const string &str)
{
    stringstream ss(str);
    char ch;
    int temp;
    vector<int> result;
    
    while (ss) {
        ss >> temp >> ch;
        result.push_back(temp);
    }
    
    return result;    
}


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */   
    string s;
    cin >> s;
    
    vector<int> vResult;
    vResult = parseInts(s);
    
    for (const int &i : vResult)
        cout << i << endl;
    
    return 0;
}
```

#### Synchronized output

* Defined in header \<syncstream>

| [basic_syncbuf (C++20)](https://en.cppreference.com/w/cpp/io/basic_syncbuf) | synchronized output device wrapper (class template) |
| - | - |
| [basic_osyncstream (C++20)](https://en.cppreference.com/w/cpp/io/basic_osyncstream) | synchronized output stream wrapper (class template) |

* [Synchronized Output Streams with C++20 - ModernesCpp.com](https://www.modernescpp.com/index.php/synchronized-outputstreams#:~:text=std%3A%3Acout%20is%20thread,Each%20character%20is%20written%20atomically.)
	* With C++20, writing synchronized to std::cout is a piece of cake. std::basic_syncbuf is a wrapper for a std::basic_streambuf. It accumulates output in its buffer. The wrapper sets its content to the wrapped buffer when it is destructed. Consequently, the content appears as a contiguous sequence of characters, and no interleaving of characters can happen.
	* Thanks to std::basic_osyncstream, you can directly write synchronously to std::cout by using a named synchronized output stream.
	* Here is how the previous program coutUnsynchronized.cpp is refactored to write synchronized to std::cout. So far, only GCC 11 supports synchronized output streams.

### Predefined standard stream objects

* Defined in header \<iostream>

| cin / wcin | reads from the standard C input stream stdin (global object) |
| - | - |
| cout / wcout | writes to the standard C output stream stdout (global object) | 
| [cerr / wcerr](https://en.cppreference.com/w/cpp/io/cerr) | writes to the standard C error stream stderr, unbuffered (global object) | 
| clog / wclog | writes to the standard C error stream stderr (global object) | 

#### [std::cin, std::wcin](https://en.cppreference.com/w/cpp/io/cin)

* reads from the standard C input stream stdin (global object)
* The global objects `std::cin` and `std::wcin` control input from a stream buffer of implementation-defined type (derived from [std::streambuf](https://en.cppreference.com/w/cpp/io/basic_streambuf)), associated with the standard C input stream [stdin](https://en.cppreference.com/w/cpp/io/c/std_streams).
* These objects are guaranteed to be initialized during or before the first time an object of type [std::ios_base::Init](https://en.cppreference.com/w/cpp/io/ios_base/Init) is constructed and are available for use in the constructors and destructors of static objects with [ordered initialization](https://en.cppreference.com/w/cpp/language/initialization#Non-local_variables) (as long as `<iostream>` is included before the object is defined).
* `Unless sync_with_stdio(false) has been issued, it is safe to concurrently access these objects from multiple threads for both formatted and unformatted input.`
* Once std::cin is constructed, `std::cin.tie()` returns `&std::cout`, and likewise, `std::wcin.tie()` returns `&std::wcout`. This means that any formatted input operation on std::cin forces a call to `std::cout.flush()` if any characters are pending for output.
* Notes
    * The 'c' in the name refers to "character" (stroustrup.com FAQ); cin means "character input" and wcin means "wide character input"
* [C++ cin 的详细用法](https://mp.weixin.qq.com/s/BP3gfSd7Ya_9MLE_ArM9LA)
    * https://dablelv.blog.csdn.net/article/details/48213811
    * 1. cin 简介
    * 2. cin 的常用读取方法
        * 2.1 cin>> 的用法
        * 2.2 cin.get() 的用法
            * 2.2.1 cin.get() 读取一个字符
            * 2.2.2 cin.get() 读取一行
        * 2.3 cin.getline() 读取一行
    * 3. cin 的条件状态
    * 4. cin 清空输入缓冲区
    * 5. 从标准输入读取一行字符串的其它方法
        * 5.1 getline() 读取一行
        * 5.2 gets() 读取一行

#### [std::cout, std::wcout](https://en.cppreference.com/w/cpp/io/cout)
	
* writes to the standard C output stream stdout (global object)
* The global objects std::cout and std::wcout control output to a stream buffer of implementation-defined type (derived from std::streambuf), associated with the standard C output stream stdout.
* These objects are guaranteed to be initialized during or before the first time an object of type std::ios_base::Init is constructed and are available for use in the constructors and destructors of static objects with ordered initialization (as long as \<iostream> is included before the object is defined).
* Unless `std::ios_base::sync_with_stdio(false)` has been issued, it is safe to concurrently access these objects from multiple threads for both formatted and unformatted output.
* By specification of std::cin, std::cin.tie() returns &std::cout. This means that any input operation on std::cin executes std::cout.flush() (via std::basic_istream::sentry's constructor). Similarly, std::wcin.tie() returns &std::wcout.
* By specification of std::cerr, std::cerr.tie() returns &std::cout. This means that any output operation on std::cerr executes std::cout.flush() (via std::basic_ostream::sentry's constructor). Similarly, std::wcerr.tie() returns &std::wcout. (since C++11)
* Notes
    * The 'c' in the name refers to "character" (stroustrup.com FAQ); cout means "character output" and wcout means "wide character output".
    * Because dynamic initialization of templated variables are unordered, it is not guaranteed that std::cout has been initialized to a usable state before the initialization of such variables begins, unless an object of type std::ios_base::Init has been constructed.
* [Fast I/O for Competitive Programming - GeeksforGeeks](https://www.geeksforgeeks.org/fast-io-for-competitive-programming/)
    ```c++
    #include <bits/stdc++.h>
    using namespace std;

    #define endl '\n'

    int main()
    {
      ios_base::sync_with_stdio(false);
      cin.tie(NULL);
      return 0;
    }
    ```
    * [c++ - Significance of ios_base::sync_with_stdio(false); cin.tie(NULL); - Stack Overflow](https://stackoverflow.com/questions/31162367/significance-of-ios-basesync-with-stdiofalse-cin-tienull/31165481#31165481)
    * [std::ios_base::sync_with_stdio - cppreference.com](https://en.cppreference.com/w/cpp/io/ios_base/sync_with_stdio)
    * [ios::tie - C++ Reference](https://www.cplusplus.com/reference/ios/ios/tie/)

### [Input/output manipulators](https://en.cppreference.com/w/cpp/io/manip)

* The stream-based I/O library uses I/O manipulators (e.g. std::boolalpha, std::hex, etc.) to control how streams behave.

#### [std::boolalpha, std::noboolalpha](https://en.cppreference.com/w/cpp/io/manip/boolalpha)
	
* switches between textual and numeric representation of booleans

#### [std::endl](https://en.cppreference.com/w/cpp/io/manip/endl)
	
* outputs '\n' and flushes the output stream (function template)
* Inserts a newline character into the output sequence os and flushes it as if by calling os.put(os.widen('\n')) followed by os.flush().
* This is an output-only I/O manipulator, it may be called with an expression such as out << std::endl for any out of type std::basic_ostream.
* Notes
    * This manipulator may be used to produce a line of output immediately, e.g. when displaying output from a long-running process, logging activity of multiple threads or logging activity of a program that may crash unexpectedly. An explicit flush of std::cout is also necessary before a call to std::system, if the spawned process performs any screen I/O. In most other usual interactive I/O scenarios, std::endl is redundant when used with std::cout because any input from std::cin, output to std::cerr, or program termination forces a call to std::cout.flush(). Use of std::endl in place of '\n', encouraged by some sources, may significantly degrade output performance.
    * In many implementations, standard output is line-buffered, and writing '\n' causes a flush anyway, unless std::ios::sync_with_stdio(false) was executed. In those situations, unnecessary endl only degrades the performance of file output, not standard output.
    * The code samples on this wiki follow Bjarne Stroustrup and The C++ Core Guidelines in flushing the standard output only where necessary.
    * When an incomplete line of output needs to be flushed, the std::flush manipulator may be used.
    * When every character of output needs to be flushed, the std::unitbuf manipulator may be used.

#### [std::quoted](https://en.cppreference.com/w/cpp/io/manip/quoted)
	
* inserts and extracts quoted strings with embedded spaces

#### MISC

* [manipulators - C++ Reference](http://www.cplusplus.com/reference/library/manipulators/)
    * Basic format flags
        * These manipulators are usable on both input and output streams, although many only have an effect when applied to either output or input streams.
        * Independent flags (switch on):
            * [showbase - C++ Reference](http://www.cplusplus.com/reference/ios/showbase/)
            * [showpos - C++ Reference](http://www.cplusplus.com/reference/ios/showpos/)
            * [uppercase - C++ Reference](http://www.cplusplus.com/reference/ios/uppercase/)
        * Independent flags (switch off):
            * [noshowpos - C++ Reference](http://www.cplusplus.com/reference/ios/noshowpos/)
            * [nouppercase - C++ Reference](http://www.cplusplus.com/reference/ios/nouppercase/)
        * Numerical base format flags ("basefield" flags):
            * [dec - C++ Reference](http://www.cplusplus.com/reference/ios/dec/)
            * [hex - C++ Reference](http://www.cplusplus.com/reference/ios/hex/?kw=hex)
        * Floating-point format flags ("floatfield" flags):
            * [fixed - C++ Reference](http://www.cplusplus.com/reference/ios/fixed/)
            * [scientific - C++ Reference](http://www.cplusplus.com/reference/ios/scientific/)
        * Adustment format flags ("adjustfield" flags):
            * [left - C++ Reference](http://www.cplusplus.com/reference/ios/left/)
            * [right - C++ Reference](http://www.cplusplus.com/reference/ios/right/)
    * Parameterized manipulators
        * These functions take parameters when used as manipulators. They require the explicit inclusion of the header file \<iomanip\>.
        * [setfill - C++ Reference](http://www.cplusplus.com/reference/iomanip/setfill/)
        * [setprecision - C++ Reference](http://www.cplusplus.com/reference/iomanip/setprecision/)
        * [setw - C++ Reference](http://www.cplusplus.com/reference/iomanip/setw/)
* [Print Pretty | HackerRank](https://www.hackerrank.com/challenges/prettyprint/problem)
```c++
#include <iostream>
#include <iomanip> 
using namespace std;

int main() {
  int T; cin >> T;
  cout << setiosflags(ios::uppercase);
  cout << setw(0xf) << internal;
  while(T--) {
      double A; cin >> A;
      double B; cin >> B;
      double C; cin >> C;

      // LINE 1 
      cout << hex << left << showbase << nouppercase; // formatting
      cout << (long long) A << endl; // output

      // LINE 2
      cout << dec << right << setw(15) << setfill('_') << showpos << fixed << setprecision(2); // formatting
      cout << B << endl; // output

      // LINE 3
      cout << scientific << uppercase << noshowpos << setprecision(9); // formatting
      cout << C << endl; // output
  }

  return 0;
}
```
* How to set precision of float / double in output ?
    * [std::setprecision - cppreference.com](https://en.cppreference.com/w/cpp/io/manip/setprecision)
        * /*unspecified*/ setprecision( int n );
        * When used in an expression out << setprecision(n) or in >> setprecision(n), sets the precision parameter of the stream out or in to exactly n.
    * [std::fixed, std::scientific, std::hexfloat, std::defaultfloat - cppreference.com](https://en.cppreference.com/w/cpp/io/manip/fixed)
        * This is an I/O manipulator, it may be called with an expression such as out << std::fixed for any out of type std::basic_ostream or with an expression such as in >> std::scientific for any in of type std::basic_istream.
        * `cout << fixed << setprecision(9) << e << endl; // 14049.304930000`

### [C-style file input/output](https://en.cppreference.com/w/cpp/io/c)

* The C I/O subset of the C++ standard library implements C-style stream input/output operations. The \<cstdio> header provides generic file operation support and supplies functions with narrow and multibyte character input/output capabilities, and the \<cwchar> header provides functions with wide character input/output capabilities.
* C streams are denoted by objects of type std::FILE that can only be accessed and manipulated through pointers of type std::FILE*. Each C stream is associated with an external physical device (file, standard input stream, printer, serial port, etc).
* [c++ - Where is `%p` useful with printf? - Stack Overflow](https://stackoverflow.com/questions/2369541/where-is-p-useful-with-printf)
	* Always use %p for pointers.

### [{fmt}](https://fmt.dev/latest/index.html)

* {fmt} is an open-source formatting library providing a fast and safe alternative to C stdio and C++ iostreams.
* [Usage — fmt 8.1.1 documentation](https://fmt.dev/latest/usage.html)
	* To use the {fmt} library, add fmt/core.h, fmt/format.h, fmt/format-inl.h, src/format.cc and optionally other headers from a release archive or the Git repository to your project. Alternatively, you can build the library with CMake.
* [Format String Syntax — fmt 8.1.1 documentation](https://fmt.dev/latest/syntax.html)

## [Filesystem library (since C++17)](https://en.cppreference.com/w/cpp/filesystem)

* The Filesystem library provides facilities for performing operations on file systems and their components, such as `paths`, `regular files`, and `directories`.
* The filesystem library was originally developed as [boost.filesystem](http://www.boost.org/doc/libs/release/libs/filesystem/doc/index.htm), was published as the technical specification ISO/IEC TS 18822:2015, and finally merged to ISO C++ as of C++17. The boost implementation is currently available on more compilers and platforms than the C++17 library.
* The filesystem library facilities may be unavailable if a hierarchical file system is not accessible to the implementation, or if it does not provide the necessary capabilities. Some features may not be available if they are not supported by the underlying file system (e.g. `the FAT filesystem lacks symbolic links and forbids multiple hardlinks`). In those cases, errors must be reported.
* The behavior is [undefined](https://en.cppreference.com/w/cpp/language/ub) if the calls to functions in this library introduce a `file system race`, that is, when multiple threads, processes, or computers interleave access and modification to the same object in a file system.

### Classes

* Defined in header \<filesystem>
* Defined in namespace std::filesystem 
* [\<filesystem> | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/standard-library/filesystem?view=msvc-160)
  * Include the header \<filesystem> for access to classes and functions that manipulate and retrieve information about paths, files, and directories.

#### [std::filesystem::path](https://en.cppreference.com/w/cpp/filesystem/path)

* represents a path (class)

##### Member functions

###### Concatenation

* [std::filesystem::path::concat, std::filesystem::path::operator+= - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/concat)
    * concatenates two paths without introducing a directory separator (public member function)
    * Concatenates the current path and the argument

###### Modifiers

* [std::filesystem::path::replace_filename - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/replace_filename)
    * replaces the last path component with another path (public member function)
* [std::filesystem::path::replace_extension - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/replace_extension)
    * replaces the extension (public member function)

###### Decomposition

* [std::filesystem::path::parent_path - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/parent_path)
    * returns the path of the parent path (public member function)
* [std::filesystem::path::filename - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/filename)
    * returns the filename path component (public member function)
* [std::filesystem::path::stem - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/stem)
    * returns the stem path component (filename without the final extension) (public member function)
    * Returns the filename identified by the generic-format path stripped of its extension.
    * Returns the substring from the beginning of filename() up to and not including the last period (.) character, with the following exceptions:
        * If the first character in the filename is a period, that period is ignored (a filename like ".profile" is not treated as an extension)
        * If the filename is one of the special filesystem components dot or dot-dot, or if it has no periods, the function returns the entire filename().
* [std::filesystem::path::extension - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/extension)
    * returns the file extension path component (public member function)

##### Non-member functions

* [std::filesystem::operator/(std::filesystem::path) - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/path/operator_slash)
    * Concatenates two path components using the preferred directory separator if appropriate (see operator/= for details).
    * Effectively returns path(lhs) /= rhs.

#### [std::filesystem::filesystem_error](https://en.cppreference.com/w/cpp/filesystem/filesystem_error)

* an exception thrown on file system errors (class)

#### [std::filesystem::directory_entry](https://en.cppreference.com/w/cpp/filesystem/directory_entry)

* a directory entry (class)
* Represents a directory entry. The object stores a path as a member and may also store additional file attributes (hard link count, status, symlink status file size, and last write time) during directory iteration.

##### Member functions

###### Observers

* [std::filesystem::directory_entry::path - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/directory_entry/path)
    * returns the path the entry refers to (public member function)
    * Returns the full path the directory entry refers to.
* [How can I get the list of files in a directory using C or C++? - Stack Overflow](https://stackoverflow.com/questions/612097/how-can-i-get-the-list-of-files-in-a-directory-using-c-or-c)
```c++
#include <string>
#include <iostream>
#include <filesystem>
namespace fs = std::filesystem;

int main()
{
    std::string path = "/path/to/directory";
    for (const auto & entry : fs::directory_iterator(path))
        std::cout << entry.path() << std::endl;
}
```

#### [std::filesystem::directory_iterator](https://en.cppreference.com/w/cpp/filesystem/directory_iterator)

* an iterator to the contents of the directory (class)
* directory_iterator is a LegacyInputIterator that iterates over the directory_entry elements of a directory (but does not visit the subdirectories). The iteration order is unspecified, except that each directory entry is visited only once. The special pathnames dot and dot-dot are skipped.
* If the directory_iterator reports an error or is advanced past the last directory entry, it becomes equal to the default-constructed iterator, also known as the end iterator. Two end iterators are always equal, dereferencing or incrementing the end iterator is undefined behavior.
* If a file or a directory is deleted or added to the directory tree after the directory iterator has been created, it is unspecified whether the change would be observed through the iterator.
* [c++ - Get an ordered list of files in a folder - Stack Overflow](https://stackoverflow.com/questions/30983154/get-an-ordered-list-of-files-in-a-folder)
```c++
std::vector<std::filesystem::path> files_in_directory;
std::copy(std::filesystem::directory_iterator(myFolder), std::filesystem::directory_iterator(), std::back_inserter(files_in_directory));
std::sort(files_in_directory.begin(), files_in_directory.end());

for (const std::string & filename : files_in_directory) {
    std::cout << path.string() << std::endl; // printed in alphabetical order
}
```

#### [std::filesystem::copy_options](https://en.cppreference.com/w/cpp/filesystem/copy_options)

* specifies semantics of copy operations (enum)
* [c++ - How to copy a file from a folder to another folder - Stack Overflow](https://stackoverflow.com/questions/9125122/how-to-copy-a-file-from-a-folder-to-another-folder)
* [std::filesystem::copy - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/copy)
    * Defined in header \<filesystem> since C++ 17
* [std::filesystem::create_directory, std::filesystem::create_directories - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/create_directory)
* [std::filesystem::current_path - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/current_path)
* [std::filesystem::exists - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/exists)
* [std::filesystem::file_size - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/file_size)
* [std::filesystem::remove, std::filesystem::remove_all - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/remove)
* [std::filesystem::rename - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/rename)
* [std::filesystem::temp_directory_path - cppreference.com](https://en.cppreference.com/w/cpp/filesystem/temp_directory_path)

#### [boost Filesystem Reference - Class path](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#class-path)

* [Chapter 35. Boost.Filesystem - Files and Directories](https://theboostcpplibraries.com/boost.filesystem-files-and-directories)
* [Filesystem Reference - copy_file()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#copy_file)
* [Filesystem Reference - create_directories()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#create_directories)
* [Filesystem Reference - exists()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#exists)
* [Filesystem Reference - filename()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#path-filename)
* [Filesystem Reference - path extension()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#path-extension)
* [Filesystem Reference - remove()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#remove)
* [Filesystem Reference - remove_all()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#remove_all)
* [Filesystem Reference - string()](https://www.boost.org/doc/libs/1_72_0/libs/filesystem/doc/reference.html#string)
* [c++ - How to use copy_file in boost::filesystem? - Stack Overflow](https://stackoverflow.com/questions/4785491/how-to-use-copy-file-in-boostfilesystem)
* [string - How can I extract the file name and extension from a path in C++ - Stack Overflow](https://stackoverflow.com/questions/4430780/how-can-i-extract-the-file-name-and-extension-from-a-path-in-c)

### Non-member functions

* Defined in header \<filesystem>
* Defined in namespace std::filesystem

### MISC

* [C如何获取文件夹下所有文件 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/3873279.html)
* [C++如何用system命令获取文件夹下所有文件名 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/3873250.html)
* [C++实现获取当前执行文件全路径 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2010/11/02/1867584.html)
* [freopen - C/C++文件输入输出利器 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2011/04/22/2024418.html)
* How to read csv files with BOM ?
	* read as UTF-8 file or
	* skip BOM in ifstream or
	* remove BOM in input files
	* [Byte order mark - Wikipedia](https://en.wikipedia.org/wiki/Byte_order_mark#Representations_of_byte_order_marks_by_encoding)
		* The byte order mark (BOM) is a particular usage of the special Unicode character, U+FEFF BYTE ORDER MARK, whose appearance as a magic number at the start of a text stream can signal several things to a program reading the text
	* [Byte Order Mark - Globalization | Microsoft Docs](https://docs.microsoft.com/en-us/globalization/encoding/byte-order-mark)
	* [c++ - Why am i getting these invalid characters before my file data? - Stack Overflow](https://stackoverflow.com/questions/30720619/why-am-i-getting-these-invalid-characters-before-my-file-data)
	* [c++ - Characters not recognized while reading from file - Stack Overflow](https://stackoverflow.com/questions/48985128/characters-not-recognized-while-reading-from-file)
		* [C++ read and write UTF-8 file using standard libarary | sockbandit](https://sockbandit.wordpress.com/2012/05/31/c-read-and-write-utf-8-file-using-standard-libarary/)
	* [byte - How do I remove the character "ï»¿" from the beginning of a text file in C++? - Stack Overflow](https://stackoverflow.com/questions/20778921/how-do-i-remove-the-character-%C3%AF-from-the-beginning-of-a-text-file-in-c/20778970)
	* [C++ reading from file puts three weird characters - Stack Overflow](https://stackoverflow.com/questions/10417613/c-reading-from-file-puts-three-weird-characters)
	* [r - Weird characters added to first column name after reading a toad-exported csv file - Stack Overflow](https://stackoverflow.com/questions/22974765/weird-characters-added-to-first-column-name-after-reading-a-toad-exported-csv-fi)
	* [How to remove BOM from any text/XML file](https://www.ibm.com/support/pages/how-remove-bom-any-textxml-file)
```c++
std::unordered_map<std::string, std::vector<std::string> > ReadCSV(const std::string& filename)
{
    std::ifstream ifs(filename, std::ifstream::in);
    std::unordered_map<std::string, std::vector<std::string> > mData{};

    if (ifs.is_open()) {
        std::string line{};
        auto checkedBOM = false;
        const std::unordered_set<std::string> setBOM{ "\xef\xbb\xbf" };

        while (std::getline(ifs, line)) {
            if (!checkedBOM) {
                if (setBOM.count(line.substr(0, 3)) > 0) {
                    line = line.substr(3);
                }
                checkedBOM = true;
            }

            std::stringstream ss{ line };
            std::string value{};
            std::vector<std::string> vValue{};

            while (std::getline(ss, value, ',')) {
                vValue.push_back(value);
            }

            mData[vValue[0]] = vValue;
        }

        ifs.close();
    }
    else {
        std::cerr << "Error opening file [" << filename << "]!";
    }

    return mData;
}
```

## [Regular expressions library](https://en.cppreference.com/w/cpp/regex)

* The regular expressions library provides a class that represents [regular expressions](https://en.wikipedia.org/wiki/Regular_expression), which are a kind of mini-language used to perform pattern matching within strings. Almost all operations with regexes can be characterized by operating on several of the following objects:
    * `Target sequence`. The character sequence that is searched for a pattern. This may be a range specified by two iterators, a null-terminated character string or a std::string.
    * `Pattern`. This is the regular expression itself. It determines what constitutes a match. It is an object of type std::basic_regex, constructed from a string with special syntax. See regex_constants::syntax_option_type for the description of supported syntax variations.
    * `Matched array`. The information about matches may be retrieved as an object of type std::match_results.
    * `Replacement string`. This is a string that determines how to replace the matches, see regex_constants::match_flag_type for the description of supported syntax variations.
* Example
```c++
#include <iostream>
#include <iterator>
#include <string>
#include <regex>
 
int main()
{
    std::string s = "Some people, when confronted with a problem, think "
        "\"I know, I'll use regular expressions.\" "
        "Now they have two problems.";
 
    std::regex self_regex("REGULAR EXPRESSIONS",
            std::regex_constants::ECMAScript | std::regex_constants::icase);
    if (std::regex_search(s, self_regex)) {
        std::cout << "Text contains the phrase 'regular expressions'\n";
    }
 
    std::regex word_regex("(\\w+)");
    auto words_begin = 
        std::sregex_iterator(s.begin(), s.end(), word_regex);
    auto words_end = std::sregex_iterator();
 
    std::cout << "Found "
              << std::distance(words_begin, words_end)
              << " words\n";
 
    const int N = 6;
    std::cout << "Words longer than " << N << " characters:\n";
    for (std::sregex_iterator i = words_begin; i != words_end; ++i) {
        std::smatch match = *i;
        std::string match_str = match.str();
        if (match_str.size() > N) {
            std::cout << "  " << match_str << '\n';
        }
    }
 
    std::regex long_word_regex("(\\w{7,})");
    std::string new_s = std::regex_replace(s, long_word_regex, "[$&]");
    std::cout << new_s << '\n';
}
/*
Text contains the phrase 'regular expressions'
Found 20 words
Words longer than 6 characters:
  confronted
  problem
  regular
  expressions
  problems
Some people, when [confronted] with a [problem], think 
"I know, I'll use [regular] [expressions]." Now they have two [problems].
*/
```

## [Concurrency support library](https://en.cppreference.com/w/cpp/thread)

* C++ includes built-in support for threads, atomic operations, mutual exclusion, condition variables, and futures.
* [CP: Concurrency and parallelism - C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#S-concurrency)
* [现代 C++ 并发编程基础](https://mp.weixin.qq.com/s/GGIczr97q-RxAfAnQKeDRg)
  * https://changkun.de/modern-cpp/zh-cn/07-thread/index.html
  * 并行基础
  * 互斥量与临界区
  * 期物
  * 条件变量
* [C++并发编程（C++11到C++17）](https://mp.weixin.qq.com/s/sLaJQl4cj_c-M2qy7iX__A)
  * 为什么要并发编程
  * 并发与并行
    * 并发（Concurrent）与并行（Parallel）都是很常见的术语。
  * 进程与线程
  * 并发系统的性能
  * C++与并发编程
  * 编译器与C++标准
  * 测试环境
  * 线程
  * 管理当前线程
  * 一次调用
  * 并发任务
  * 竞争条件与临界区
  * 互斥体与锁
  * 通用锁定算法
  * 通用互斥管理
  * 并行算法
* [多线程一定能优化程序性能吗？](https://mp.weixin.qq.com/s/tZn8Og6p_1nPc3vqeK_BZw)
	* 多线程与CPU
	* 多线程与IO
	* 多线程与内存
* [Advanced Parallel Programming in C++ – Patrick Diehl](https://www.diehlpk.de/blog/modern-cpp/)
* [thread、future、promise、packaged_task、async之间有什么关系？](https://mp.weixin.qq.com/s/fUD4HxtUNhnpVlqGNAbc6Q)
	* 并发编程一般指多线程编程，C++11之后关于多线程编程有几个高级API：
		* std::thread 
		* std::future
		* std::shared_future
		* std::promise
		* std::packaged_task
		* std::async
* [打开线程 | 进程 | 协程的大门](https://mp.weixin.qq.com/s/2rVYPeKBnTrFoSxmUEM08g)
	* 进程和线程是什么
	* 进程和线程有什么区别
	* 为什么有了进程又出现线程
	* 内核态和用户态有啥不同
	* 协程有什么特点
* [协程到底有什么用？6种I/O模式告诉你！](https://mp.weixin.qq.com/s/xSf3eHG4CX3rJkzuU8p5IQ)
	* 为了高效进行IO操作，我们采用的技术是这样演进的：
		* 单线程串行 + 阻塞式IO(同步)
		* 多线程并行 + 阻塞式IO(并行)
		* 单线程 + 非阻塞式IO(异步) + event loop
		* 单线程 + 非阻塞式IO(异步) + event loop + 回调
		* Reactor模式(更好的单线程 + 非阻塞式IO+ event loop + 回调)
		* 单线程 + 非阻塞式IO(异步) + event loop + 协程
	* 最终我们采用协程技术获取到了异步编程的高效以及同步编程的简单理解，这也是当今高性能服务器常用的一种技术组合。
* [深入理解协程](https://mp.weixin.qq.com/s/r8KjFEojQaRIqBC2TfByWg)
	* C++ 在互联网服务端开发方向依然占据着相当大的份额；百度，腾讯，甚至以java为主流开发语言的阿里都在大规模使用C++做互联网服务端开发，今天以C++为例子，分析一下要支持协程，需要考虑哪些问题，如何权衡利弊，反过来也可以了解到协程适合哪些场景。
* [异步编程到底在说啥？](https://mp.weixin.qq.com/s/aaCVgXekO6unpFDfKchVlA)
	* 同步就好比你排队去自助售票机取电影票，你必须排队等待前一个人取完电影票才能到你，你不能在前一个取票的过程中取自己的票，这时我们说取电影票时你和前一个人是同步的。
	* 而异步就好比去吃大餐，你在座位上看菜单点菜，其它人也可以点菜，你不需要等待其它人吃完饭才能下单，这时我们说你点菜和其它人吃饭是异步的。
* [C++异步从理论到实践总览篇](https://mp.weixin.qq.com/s/tnADuXt4FXIx46JuhgnrPw)
* [async的两个坑](https://mp.weixin.qq.com/s/gmF5WXHsuFwblYDu_jDeTA)
	* 一般人可能都知道C++异步操作有async这个东西。但不知道大家是否注意过，其实它有两个坑：
		* 它不一定真的会异步执行
		* 它有可能会阻塞

### Threads

* Threads enable programs to execute across several processor cores.
* Defined in header [\<thread>](https://en.cppreference.com/w/cpp/header/thread)

#### [std::thread](https://en.cppreference.com/w/cpp/thread/thread)

* manages a separate thread (class)
* Threads enable programs to execute across several processor cores.
* The class thread represents [a single thread of execution](https://en.wikipedia.org/wiki/Thread_(computing)). Threads allow multiple functions to execute concurrently.
* Threads begin execution immediately upon construction of the associated thread object (pending any OS scheduling delays), starting at the top-level function provided as a constructor argument. The return value of the top-level function is ignored and if it terminates by throwing an exception, std::terminate is called. The top-level function may communicate its return value or an exception to the caller via std::promise or by modifying shared variables (which may require synchronization, see std::mutex and std::atomic)
* std::thread objects may also be in the state that does not represent any thread (after default construction, move from, detach, or join), and a thread of execution may not be associated with any thread objects (after detach).
* No two std::thread objects may represent the same thread of execution; std::thread is not CopyConstructible or CopyAssignable, although it is MoveConstructible and MoveAssignable.

##### Member functions

###### [`std::thread::thread`](https://en.cppreference.com/w/cpp/thread/thread/thread)

* (constructor)
* constructs new thread object (public member function)
    * 1) Creates new thread object which does not represent a thread.
    * 2) Move constructor. Constructs the thread object to represent the thread of execution that was represented by other. After this call other no longer represents a thread of execution.
    * 3) Creates new std::thread object and associates it with a thread of execution. The new thread of execution starts executing `/*INVOKE*/(std::move(f_copy), std::move(args_copy)...)`, where
        * `/*INVOKE*/` performs the INVOKE operation specified in Callable`, which can be performed by std::invoke (since C++17)`, and
        * `f_copy` is an object of type `std::decay<Function>::type` and constructed from `std::forward<Function>(f)`, and
        * `args_copy...` are objects of types `std::decay<Args>::type...` and constructed from `std::forward<Args>(args)...`.
    * Constructions of these objects are executed in the context of the caller, so that any exceptions thrown during evaluation and copying/moving of the arguments are thrown in the current thread, without starting the new thread. The program is ill-formed if any construction or the `INVOKE` operation is invalid.
    * This constructor does not participate in overload resolution if `std::decay<Function>::type` is the same type as thread.
    * The completion of the invocation of the constructor `synchronizes-with` (as defined in `std::memory_order`) the beginning of the invocation of the copy of f on the new thread of execution.
    * 4) The copy constructor is deleted; threads are not copyable. No two `std::thread` objects may represent the same thread of execution.
* Parameters
    * other	- another thread object to construct this thread object with
    * f	- [Callable](https://en.cppreference.com/w/cpp/named_req/Callable) object to execute in the new thread
    * args...	-	arguments to pass to the new function
    * C++ named requirements: Callable
        * A Callable type is a type for which the INVOKE operation (used by, e.g., std::function, std::bind, and std::thread::thread) is applicable.
        * The INVOKE operation may be performed explicitly using the library function std::invoke. (since C++17)
        * The INVOKE operation with explicitly specified return type (INVOKE\<R>) may be performed explicitly using the library function std::invoke_r. (since C++23)
        * Notes
            * For pointers to member functions and pointers to data members, t1 may be a `regular pointer` or an `object of class type that overloads operator*`, such as `std::unique_ptr` or `std::shared_ptr`.
            * `Pointers to data members` are Callable, even though no function calls take place.
* Postconditions
    * 1) `get_id()` equal to `std::thread::id()` (i.e. joinable is false)
    * 2) `other.get_id()` equal to `std::thread::id()` and `get_id()` returns the value of `other.get_id()` prior to the start of construction
    * 3) `get_id()` not equal to `std::thread::id()` (i.e. joinable is true)
* Exceptions
    * 3) `std::system_error` if the thread could not be started. The exception may represent the error condition `std::errc::resource_unavailable_try_again` or another implementation-specific error condition.
* Notes
    * The arguments to the thread function are moved or copied by value. If a reference argument needs to be passed to the thread function, it has to be wrapped (e.g., with `std::ref` or `std::cref`).
    * Any return value from the function is ignored. If the function throws an exception, `std::terminate` is called. In order to pass return values or exceptions back to the calling thread, `std::promise` or `std::async` may be used.
* [thread::thread - C++ Reference](https://cplusplus.com/reference/thread/thread/thread/)
	* Data races
		* The move constructor (4) modifies x.
```c++
// constructing threads
#include <iostream>       // std::cout
#include <atomic>         // std::atomic
#include <thread>         // std::thread
#include <vector>         // std::vector

std::atomic<int> global_counter (0);

void increase_global (int n) { for (int i=0; i<n; ++i) ++global_counter; }

void increase_reference (std::atomic<int>& variable, int n) { for (int i=0; i<n; ++i) ++variable; }

struct C : std::atomic<int> {
  C() : std::atomic<int>(0) {}
  void increase_member (int n) { for (int i=0; i<n; ++i) fetch_add(1); }
};

int main ()
{
  std::vector<std::thread> threads;

  std::cout << "increase global counter with 10 threads...\n";
  for (int i=1; i<=10; ++i)
    threads.push_back(std::thread(increase_global,1000));

  std::cout << "increase counter (foo) with 10 threads using reference...\n";
  std::atomic<int> foo(0);
  for (int i=1; i<=10; ++i)
    threads.push_back(std::thread(increase_reference,std::ref(foo),1000));

  std::cout << "increase counter (bar) with 10 threads using member...\n";
  C bar;
  for (int i=1; i<=10; ++i)
    threads.push_back(std::thread(&C::increase_member,std::ref(bar),1000));

  std::cout << "synchronizing all threads...\n";
  for (auto& th : threads) th.join();

  std::cout << "global_counter: " << global_counter << '\n';
  std::cout << "foo: " << foo << '\n';
  std::cout << "bar: " << bar << '\n';

  return 0;
}
/*
increase global counter using 10 threads...
increase counter (foo) with 10 threads using reference...
increase counter (bar) with 10 threads using member...
synchronizing all threads...
global_counter: 10000
foo: 10000
bar: 10000
*/
```

###### Observers

* [`std::thread::joinable`](https://en.cppreference.com/w/cpp/thread/thread/joinable)
	* checks whether the thread is joinable, i.e. potentially running in parallel context (public member function)
	* Checks if the std::thread object identifies an active thread of execution. Specifically, returns true if get_id() != `std::thread::id()`. So a default constructed thread is not joinable.
	* A thread that has finished executing code, but has not yet been joined is still considered an active thread of execution and is therefore joinable.
	* Return value
		* true if the thread object identifies an active thread of execution, false otherwise
* [`std::thread::get_id`](https://en.cppreference.com/w/cpp/thread/thread/get_id)
	* Returns a value of `std::thread::id` identifying the thread associated with *this.
	* Return value
		* A value of type `std::thread::id` identifying the thread associated with *this. If there is no thread associated, default constructed `std::thread::id` is returned.
* [`std::thread::hardware_concurrency`](https://en.cppreference.com/w/cpp/thread/thread/hardware_concurrency)
	* returns the number of concurrent threads supported by the implementation (public static member function)
	* Returns the number of concurrent threads supported by the implementation. The value should be considered only a hint.
	* Return value
		* Number of concurrent threads supported. If the value is not well defined or not computable, returns ​0​.

###### Operations

* [`std::thread::join`](https://en.cppreference.com/w/cpp/thread/thread/join)
	* waits for the thread to finish its execution (public member function)
	* Blocks the current thread until the thread identified by `*this` finishes its execution.
	* The completion of the thread identified by `*this` synchronizes with the corresponding successful return from join().
	* No synchronization is performed on `*this` itself. Concurrently calling join() on the same thread object from multiple threads constitutes a data race that results in undefined behavior.
	* Postconditions
		* joinable() is false
	* Exceptions
		* std::system_error if an error occurs.
	* Error Conditions
		* resource_deadlock_would_occur if this->get_id() == std::this_thread::get_id() (deadlock detected)
		* no_such_process if the thread is not valid
		* invalid_argument if joinable() is false

##### MISC

* [Multithreading in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/multithreading-in-cpp/)
    * std::thread is the thread class that represents a single thread in C++. To start a thread we simply need to create a new thread object and pass the executing code to be called (i.e, a callable object) into the constructor of the object. Once the object is created a new thread is launched which will execute the code specified in callable.
    * A `callable` can be either of the three
        * A function pointer
        * A function object, e.g. A class with an overridden operator()
        * A lambda expression
    * After defining callable, pass it to the constructor.
    * Waiting for threads to finish
        * To wait for a thread use the std::thread::join() function. This function makes the current thread wait until the thread identified by *this has finished executing.
```c++
// CPP program to demonstrate multithreading
// using three different callables.
#include <iostream>
#include <thread>
using namespace std;

// A dummy function
void foo(int Z)
{
    for (int i = 0; i < Z; i++) {
        cout << "Thread using function"
            " pointer as callable\n";
    }
}

// A callable object
class thread_obj {
public:
    void operator()(int x)
    {
        for (int i = 0; i < x; i++)
            cout << "Thread using function"
                " object as callable\n";
    }
};

int main()
{
    cout << "Threads 1 and 2 and 3 "
        "operating independently" << endl;

    // This thread is launched by using
    // function pointer as callable
    thread th1(foo, 3);

    // This thread is launched by using
    // function object as callable
    thread th2(thread_obj(), 3);

    // Define a Lambda Expression
    auto f = [](int x) {
        for (int i = 0; i < x; i++)
            cout << "Thread using lambda"
            " expression as callable\n";
    };

    // This thread is launched by using
    // lamda expression as callable
    thread th3(f, 3);

    // Wait for the threads to finish
    // Wait for thread t1 to finish
    th1.join();

    // Wait for thread t2 to finish
    th2.join();

    // Wait for thread t3 to finish
    th3.join();

    return 0;
}
```
* [用三个线程按顺序循环打印ABC三个字母 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/8575543.html)
* [C++ 线程的使用](https://mp.weixin.qq.com/s/tMWxvw4Kmga5ayUfXHaaIw)
  * C++11 之前，C++ 语言没有对并发编程提供语言级别的支持，这使得我们在编写可移植的并发程序时，存在诸多的不便。现在 C++11 中增加了线程以及线程相关的类，很方便地支持了并发编程，使得编写的多线程程序的可移植性得到了很大的提高。
  * C++11 中提供的线程类叫做 std::thread，基于这个类创建一个新的线程非常的简单，只需要提供线程函数或者函数对象即可，并且可以同时指定线程函数的参数。我们首先来了解一下这个类提供的一些常用 API：
  * 1. 构造函数
  * 2. 公共成员函数
    * 2.1 get_id()
    * 2.2 join()
    * 2.3 detach()
    * 2.5 joinable()
    * 2.6 operator=
  * 3. 静态函数
  * 4. C 线程库
    * [C语言线程库的使用](https://mp.weixin.qq.com/s?__biz=MzI3ODQ3OTczMw==&mid=2247491745&idx=1&sn=d995e1617ed6ad3d56de28b5be127e73&scene=21#wechat_redirect)
* [Learn C++ Multi Threading in 20 Minutes - YouTube](https://www.youtube.com/watch?v=3aqxaZsvn80)
* How to insert into vector with thread safe ?
	* [multithreading - C++ STL Concurrent update to values in fixed size map - Is it safe? - Stack Overflow](https://stackoverflow.com/questions/47309237/c-stl-concurrent-update-to-values-in-fixed-size-map-is-it-safe)
	* [c++ - Can a std::map rebalance during the invocation of a const function? - Stack Overflow](https://stackoverflow.com/questions/26867435/can-a-stdmap-rebalance-during-the-invocation-of-a-const-function/26867506#26867506)
	* [c++ - Can different threads insert into a map if they always use different keys? - Stack Overflow](https://stackoverflow.com/questions/27829806/can-different-threads-insert-into-a-map-if-they-always-use-different-keys)
	* [c++ - Populating a vector in parallel, order not important - Stack Overflow](https://stackoverflow.com/questions/41191945/populating-a-vector-in-parallel-order-not-important)
	* [c++ - Why does vector "emplace_back" behave much slower in multiple threads than single threads - Stack Overflow](https://stackoverflow.com/questions/57343773/why-does-vector-emplace-back-behave-much-slower-in-multiple-threads-than-singl)
	* [c++ - Are std::vector emplace_back and push_back thread-safe - Stack Overflow](https://stackoverflow.com/questions/66471521/are-stdvector-emplace-back-and-push-back-thread-safe)
	* [`c++ - Are concurrent calls to emplace_back() and operator[]() from std::deque thread safe? - Stack Overflow`](https://stackoverflow.com/questions/41001062/are-concurrent-calls-to-emplace-back-and-operator-from-stddeque-thread-s)
	* [c++ - Fill a container from several threads - Code Review Stack Exchange](https://codereview.stackexchange.com/questions/104975/fill-a-container-from-several-threads)
	* [(2) How do I know if a thread has finished its operation in C++? - Quora](https://www.quora.com/How-do-I-know-if-a-thread-has-finished-its-operation-in-C++)
	* [(2) How can I know when a thread has finished? I want to check if a thread has finished and update some data structure. - Quora](https://www.quora.com/How-can-I-know-when-a-thread-has-finished-I-want-to-check-if-a-thread-has-finished-and-update-some-data-structure)
	* [a simple thread example to show thread-safe vector operation](https://gist.github.com/phg1024/8447146)
```c++
#include <iostream>
#include <mutex>
#include <string>
#include <thread>
#include <vector>
using namespace std;

int main()
{
    std::vector<std::string>    v_values{"test1", "test2", "test3", "test4"};
    std::vector<std::string>    v_results;
    v_results.reserve(v_values.size());

    std::cout << "std::thread::hardware_concurrency() : " << std::thread::hardware_concurrency() << "\n";
    auto max_n_threads = std::thread::hardware_concurrency();
    const auto n_threads = (v_values.size() >= max_n_threads) ? max_n_threads : v_values.size();
    std::cout << "n_threads : " << n_threads << "\n";

    std::vector<std::thread> v_threads;
    v_threads.reserve(n_threads);

    std::mutex  mtx_results;
    auto cmd = [&v_values, &n_threads, &mtx_results, &v_results](auto id) {
        std::cout << "id : " << id << "\n";
        auto s = ""s;

        for (auto i = id; i < v_values.size(); i += n_threads) {
            s = v_values.at(i);
            auto new_s = s.append("_result");
            const std::lock_guard<std::mutex> guard(mtx_results);   // lock required
            v_results.emplace_back(new_s);
        }
    };

    for (auto i = 0u; i < n_threads; ++ i) {
        v_threads.emplace_back(std::thread{cmd, i});
    }

    auto thread_count = 0;
    for (auto& it : v_threads) {
        std::cout << "Joining  : " << thread_count << " : " << it.get_id() << "\n";

        if (it.joinable()) {
            std::cout << "Joined  : " << thread_count << " : " << it.get_id() << "\n";
            it.join();
        }

        ++ thread_count;
    }

    std::cout << "v_results.size() : " << v_results.size() << "\n";
    for (auto s : v_results) {
        std::cout << s << " ";
    }

    return 0;
}
/*
std::thread::hardware_concurrency() : 2
n_threads : 2
Joining  : 0 : 140660807714560
Joined  : 0 : 140660807714560
id : 0
Joining  : 1 : 140660799321856
Joined  : 1 : 140660799321856
id : 1
v_results.size() : 4
test1_result test3_result test2_result test4_result 
*/
```

#### [std::jthread (C++20)](https://en.cppreference.com/w/cpp/thread/jthread)

* `std::thread` with support for auto-joining and cancellation (class)
* Defined in header `<thread>`
* `class jthread;   (since C++20)`
* The class jthread represents [a single thread of execution](https://en.wikipedia.org/wiki/Thread_(computing)). It has the same general behavior as `std::thread`, except that jthread automatically rejoins on destruction, and can be cancelled/stopped in certain situations.
* Threads begin execution immediately upon construction of the associated thread object (pending any OS scheduling delays), starting at the top-level function provided as a [constructor argument](https://en.cppreference.com/w/cpp/thread/jthread/jthread). The return value of the top-level function is ignored and if it terminates by throwing an exception, `std::terminate` is called. The top-level function may communicate its return value or an exception to the caller via `std::promise` or by modifying shared variables (which may require synchronization, see `std::mutex` and `std::atomic`)
* Unlike `std::thread`, the jthread logically holds an internal private member of type `std::stop_source`, which maintains a shared stop-state. The jthread constructor accepts a function that takes a `std::stop_token` as its first argument, which will be passed in by the jthread from its internal `std::stop_source`. This allows the function to check if stop has been requested during its execution, and return if it has.
* `std::jthread` objects may also be in the state that does not represent any thread (after default construction, move from, detach, or join), and a thread of execution may be not associated with any jthread objects (after detach).
* No two `std::jthread` objects may represent the same thread of execution; `std::jthread` is not `CopyConstructible` or `CopyAssignable`, although it is `MoveConstructible` and `MoveAssignable`.

#### Functions managing the current thread

##### [std::this_thread::sleep_for](https://en.cppreference.com/w/cpp/thread/sleep_for)

* stops the execution of the current thread for a specified time duration (function)
* Blocks the execution of the current thread for at least the specified sleep_duration.
* This function may block for longer than sleep_duration due to scheduling or resource contention delays.
* The standard recommends that a steady clock is used to measure the duration. If an implementation uses a system clock instead, the wait time may also be sensitive to clock adjustments.
* [Sleep v.s. sleep - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5584088.html)

### [Atomic operations library](https://en.cppreference.com/w/cpp/atomic)

* These components are provided for fine-grained atomic operations allowing for lockless concurrent programming. Each atomic operation is indivisible with regards to any other atomic operation that involves the same object. Atomic objects are [free of data races](https://en.cppreference.com/w/cpp/language/memory_model#Threads_and_data_races).
* Neither the _Atomic macro, nor any of the non-macro global namespace declarations are provided by any C++ standard library header other than `<stdatomic.h>`. (since C++23)
* Defined in header [\<atomic>](https://en.cppreference.com/w/cpp/header/atomic)

#### [std::atomic](https://en.cppreference.com/w/cpp/atomic/atomic)

* Each instantiation and full specialization of the std::atomic template defines an atomic type. If one thread writes to an atomic object while another thread reads from it, the behavior is well-defined (see memory model for details on data races).
* In addition, accesses to atomic objects may establish inter-thread synchronization and order non-atomic memory accesses as specified by std::memory_order.
* std::atomic is neither copyable nor movable.

##### Member functions

###### [std::atomic\<T>::atomic](https://en.cppreference.com/w/cpp/atomic/atomic/atomic)

* (constructor)
* constructs an atomic object (public member function)

###### [std::atomic\<T>::store](https://en.cppreference.com/w/cpp/atomic/atomic/store)
    
* atomically replaces the value of the atomic object with a non-atomic argument (public member function)

###### [std::atomic\<T>::load](https://en.cppreference.com/w/cpp/atomic/atomic/load)

* atomically obtains the value of the atomic object (public member function)

###### [std::atomic\<T>::compare_exchange_weak, std::atomic\<T>::compare_exchange_strong](https://en.cppreference.com/w/cpp/atomic/atomic/compare_exchange)

* atomically compares the value of the atomic object with non-atomic argument and performs atomic exchange if equal or atomic load if not (public member function)
* [atomic_compare_exchange_strong - C++ Reference](https://www.cplusplus.com/reference/atomic/atomic_compare_exchange_strong/)
    * Compare and exchange contained value (strong)
    * Compares the contents of the value contained in obj with the value pointed by expected:
    * - if true, it replaces the contained value with val.
    * - if false, it replaces the value pointed by expected with the contained value .

##### Specialized member functions

###### [`std::atomic<T>::fetch_add`](https://en.cppreference.com/w/cpp/atomic/atomic/fetch_add)

* atomically adds the argument to the value stored in the atomic object and obtains the value held previously (public member function)
* Atomically replaces the current value with the result of arithmetic addition of the value and arg. That is, it performs atomic post-increment. The operation is a read-modify-write operation. Memory is affected according to the value of order.
* For signed Integral types, arithmetic is defined to use two’s complement representation. There are no undefined results.
* For `T*` types, the result may be an undefined address, but the operation otherwise has no undefined behavior. The program is ill-formed if T is not an object type.
* Parameters
	* arg	-	the other argument of arithmetic addition
	* order	-	memory order constraints to enforce
* Return value
    * The value immediately preceding the effects of this function in the modification order of *this.
* Example
```c++
#include <iostream>
#include <thread>
#include <atomic>
#include <array>
 
std::atomic<long long> data{10};
std::array<long long, 5> return_values{};
 
void do_work(int thread_num)
{
    long long val = data.fetch_add(1, std::memory_order_relaxed);
    return_values[thread_num] = val;
}
 
int main()
{
    {
        std::jthread th0{do_work, 0};
        std::jthread th1{do_work, 1};
        std::jthread th2{do_work, 2};
        std::jthread th3{do_work, 3};
        std::jthread th4{do_work, 4};
    }
 
    std::cout << "Result : " << data << '\n';
 
    for (long long val : return_values) {
        std::cout << "Seen return value : " << val << std::endl;
    }
}
/*
Result : 15
Seen return value : 11
Seen return value : 10
Seen return value : 14
Seen return value : 12
Seen return value : 13
*/
```

##### MISC
 
* [Non-blocking algorithm - Wikipedia](https://en.wikipedia.org/wiki/Non-blocking_algorithm)
    * In computer science, an algorithm is called non-blocking if failure or suspension of any thread cannot cause failure or suspension of another thread;[1] for some operations, these algorithms provide a useful alternative to traditional blocking implementations. A non-blocking algorithm is lock-free if there is guaranteed system-wide progress, and wait-free if there is also guaranteed per-thread progress. "Non-blocking" was used as a synonym for "lock-free" in the literature until the introduction of obstruction-freedom in 2003.[2]
* [Linearizability - Wikipedia](https://en.wikipedia.org/wiki/Linearizability)
    * In concurrent programming, an operation (or set of operations) is linearizable if it consists of an ordered list of invocation and response events (callbacks), that may be extended by adding response events such that:
        * The extended list can be re-expressed as a sequential history (is serializable).
        * That sequential history is a subset of the original unextended list.
    * Informally, this means that the unmodified list of events is linearizable if and only if its invocations were serializable, but some of the responses of the serial schedule have yet to return.[1]
    * In a concurrent system, processes can access a shared object at the same time. Because multiple processes are accessing a single object, there may arise a situation in which while one process is accessing the object, another process changes its contents. Making a system linearizable is one solution to this problem. In a linearizable system, although operations overlap on a shared object, each operation appears to take place instantaneously. Linearizability is a strong correctness condition, which constrains what outputs are possible when an object is accessed by multiple processes concurrently. It is a safety property which ensures that operations do not complete in an unexpected or unpredictable manner. If a system is linearizable it allows a programmer to reason about the system.[2]
* [Compare-and-swap - Wikipedia](https://en.wikipedia.org/wiki/Compare-and-swap)
    * In computer science, compare-and-swap (CAS) is an atomic instruction used in multithreading to achieve synchronization. It compares the contents of a memory location with a given value and, only if they are the same, modifies the contents of that memory location to a new given value. This is done as a single atomic operation. The atomicity guarantees that the new value is calculated based on up-to-date information; if the value had been updated by another thread in the meantime, the write would fail. The result of the operation must indicate whether it performed the substitution; this can be done either with a simple boolean response (this variant is often called compare-and-set), or by returning the value read from the memory location (not the value written to it).
```c++
#include <atomic>
#include <chrono>

mutable std::atomic_bool _wait{ false };

void _setWaitInProgress() const
{
    auto expected = false;

    // if _wait is not able to exchange, it will keep looping unless it is released to exchange
    while (!(_wait.compare_exchange_strong(expected, true))) {
        expected = false;
        std::this_thread::sleep_for(std::chrono::milliseconds(5));
    }
}

void _setWaitDone() const
{
    _wait.store(false);
}

void TestAtomic()
{
    _setWaitInProgress();

    DoSomething();

    _setWaitDone();
}
```
* [The Atomic Boolean - ModernesCpp.com](https://www.modernescpp.com/index.php/the-atomic-boolean)
```c++
// atomicCondition.cpp

#include <atomic>
#include <chrono>
#include <iostream>
#include <thread>
#include <vector>

std::vector<int> mySharedWork;
std::atomic<bool> dataReady(false);

void waitingForWork(){
    std::cout << "Waiting " << std::endl;
    while ( !dataReady.load() ){             // (3)
        std::this_thread::sleep_for(std::chrono::milliseconds(5));
    }
    mySharedWork[1]= 2;                      // (4)
    std::cout << "Work done " << std::endl;
}

void setDataReady(){
    mySharedWork={1,0,3};                    // (1)
    dataReady= true;                         // (2)
    std::cout << "Data prepared" << std::endl;
}

int main()
{
    std::cout << std::endl;

    std::thread t1(waitingForWork);
    std::thread t2(setDataReady);

    t1.join();
    t2.join();

    for (auto v: mySharedWork){
        std::cout << v << " ";
    }

    std::cout << "\n\n";
}
```
![image](https://user-images.githubusercontent.com/34557994/156122924-ede55b2c-d15d-47cc-af2c-0b219f1d3391.png)
* [C++ 11 开发中的 Atomic 原子操作](https://mp.weixin.qq.com/s/FSE95BtgA2PT59HCX3EzsQ)

#### Memory synchronization ordering

##### [std::memory_order](https://en.cppreference.com/w/cpp/atomic/memory_order)

* defines memory ordering constraints for the given atomic operation (enum)
* Defined in header `<atomic>`
```c++
typedef enum memory_order {
    memory_order_relaxed,
    memory_order_consume,
    memory_order_acquire,
    memory_order_release,
    memory_order_acq_rel,
    memory_order_seq_cst
} memory_order;     (since C++11)(until C++20)

enum class memory_order : /*unspecified*/ {
    relaxed, consume, acquire, release, acq_rel, seq_cst
};
inline constexpr memory_order memory_order_relaxed = memory_order::relaxed;
inline constexpr memory_order memory_order_consume = memory_order::consume;
inline constexpr memory_order memory_order_acquire = memory_order::acquire;
inline constexpr memory_order memory_order_release = memory_order::release;
inline constexpr memory_order memory_order_acq_rel = memory_order::acq_rel;
inline constexpr memory_order memory_order_seq_cst = memory_order::seq_cst;     (since C++20)
```
* `std::memory_order` specifies how memory accesses, including regular, non-atomic memory accesses, are to be ordered around an atomic operation. Absent any constraints on a multi-core system, when multiple threads simultaneously read and write to several variables, one thread can observe the values change in an order different from the order another thread wrote them. Indeed, the apparent order of changes can even differ among multiple reader threads. Some similar effects can occur even on uniprocessor systems due to compiler transformations allowed by the memory model.
* The default behavior of all atomic operations in the library provides for `sequentially consistent ordering` (see discussion below). That default can hurt performance, but the library's atomic operations can be given an additional `std::memory_order` argument to specify the exact constraints, beyond atomicity, that the compiler and processor must enforce for that operation.

###### Explanation

#
Relaxed ordering

* Atomic operations tagged `memory_order_relaxed` are not synchronization operations; they do not impose an order among concurrent memory accesses. They only guarantee atomicity and modification order consistency.
* ...
* Typical use for relaxed memory ordering is incrementing counters, such as the reference counters of `std::shared_ptr`, since this only requires atomicity, but not ordering or synchronization (note that decrementing the shared_ptr counters requires acquire-release synchronization with the destructor)
```c++
#include <vector>
#include <iostream>
#include <thread>
#include <atomic>
 
std::atomic<int> cnt = {0};
 
void f()
{
    for (int n = 0; n < 1000; ++n) {
        cnt.fetch_add(1, std::memory_order_relaxed);
    }
}
 
int main()
{
    std::vector<std::thread> v;
    for (int n = 0; n < 10; ++n) {
        v.emplace_back(f);
    }
    for (auto& t : v) {
        t.join();
    }
    std::cout << "Final counter value is " << cnt << '\n';
}
/*
Final counter value is 10000
*/
```

#
Release-Acquire ordering

* If an atomic store in thread A is tagged `memory_order_release`, an atomic load in thread B from the same variable is tagged `memory_order_acquire`, and the load in thread B reads a value written by the store in thread A, then the store in thread A `synchronizes-with` the load in thread B.
* ...
* Mutual exclusion locks, such as `std::mutex` or [atomic spinlock](https://en.cppreference.com/w/cpp/atomic/atomic_flag), are an example of release-acquire synchronization: when the lock is released by thread A and acquired by thread B, everything that took place in the critical section (before the release) in the context of thread A has to be visible to thread B (after the acquire) which is executing the same critical section.
```c++
#include <thread>
#include <atomic>
#include <cassert>
#include <string>
 
std::atomic<std::string*> ptr;
int data;
 
void producer()
{
    std::string* p  = new std::string("Hello");
    data = 42;
    ptr.store(p, std::memory_order_release);
}
 
void consumer()
{
    std::string* p2;
    while (!(p2 = ptr.load(std::memory_order_acquire)))
        ;
    assert(*p2 == "Hello"); // never fires
    assert(data == 42); // never fires
}
 
int main()
{
    std::thread t1(producer);
    std::thread t2(consumer);
    t1.join(); t2.join();
}
```
* The following example demonstrates transitive release-acquire ordering across three threads, using a release sequence
```c++
#include <thread>
#include <atomic>
#include <cassert>
#include <vector>
 
std::vector<int> data;
std::atomic<int> flag = {0};
 
void thread_1()
{
    data.push_back(42);
    flag.store(1, std::memory_order_release);
}
 
void thread_2()
{
    int expected=1;
    // memory_order_relaxed is okay because this is an RMW,
    // and RMWs (with any ordering) following a release form a release sequence
    while (!flag.compare_exchange_strong(expected, 2, std::memory_order_relaxed)) {
        expected = 1;
    }
}
 
void thread_3()
{
    while (flag.load(std::memory_order_acquire) < 2)
        ;
    // if we read the value 2 from the atomic flag, we see 42 in the vector
    assert(data.at(0) == 42); // will never fire
}
 
int main()
{
    std::thread a(thread_1);
    std::thread b(thread_2);
    std::thread c(thread_3);
    a.join(); b.join(); c.join();
}
```

#
Release-Consume ordering

* If an atomic store in thread A is tagged `memory_order_release`, an atomic load in thread B from the same variable is tagged `memory_order_consume`, and the load in thread B reads a value written by the store in thread A, then the store in thread A is dependency-ordered before the load in thread B.
* ...
* This example demonstrates dependency-ordered synchronization for pointer-mediated publication: the integer data is not related to the pointer to string by a data-dependency relationship, thus its value is undefined in the consumer.
```c++
#include <thread>
#include <atomic>
#include <cassert>
#include <string>
 
std::atomic<std::string*> ptr;
int data;
 
void producer()
{
    std::string* p  = new std::string("Hello");
    data = 42;
    ptr.store(p, std::memory_order_release);
}
 
void consumer()
{
    std::string* p2;
    while (!(p2 = ptr.load(std::memory_order_consume)))
        ;
    assert(*p2 == "Hello"); // never fires: *p2 carries dependency from ptr
    assert(data == 42); // may or may not fire: data does not carry dependency from ptr
}
 
int main()
{
    std::thread t1(producer);
    std::thread t2(consumer);
    t1.join(); t2.join();
}
```

#
Sequentially-consistent ordering

* Atomic operations tagged `memory_order_seq_cst` not only order memory the same way as release/acquire ordering (everything that `happened-before` a store in one thread becomes a `visible side effect` in the thread that did a load), but also establish a `single total modification order` of all atomic operations that are so tagged.
* ...
* This example demonstrates a situation where sequential ordering is necessary. Any other ordering may trigger the assert because it would be possible for the threads c and d to observe changes to the atomics x and y in opposite order.
```c++
#include <thread>
#include <atomic>
#include <cassert>
 
std::atomic<bool> x = {false};
std::atomic<bool> y = {false};
std::atomic<int> z = {0};
 
void write_x()
{
    x.store(true, std::memory_order_seq_cst);
}
 
void write_y()
{
    y.store(true, std::memory_order_seq_cst);
}
 
void read_x_then_y()
{
    while (!x.load(std::memory_order_seq_cst))
        ;
    if (y.load(std::memory_order_seq_cst)) {
        ++z;
    }
}
 
void read_y_then_x()
{
    while (!y.load(std::memory_order_seq_cst))
        ;
    if (x.load(std::memory_order_seq_cst)) {
        ++z;
    }
}
 
int main()
{
    std::thread a(write_x);
    std::thread b(write_y);
    std::thread c(read_x_then_y);
    std::thread d(read_y_then_x);
    a.join(); b.join(); c.join(); d.join();
    assert(z.load() != 0);  // will never happen
}
```

### Mutual exclusion

* Mutual exclusion algorithms prevent multiple threads from simultaneously accessing shared resources. This prevents data races and provides support for synchronization between threads.
* Defined in header [\<mutex>](https://en.cppreference.com/w/cpp/header/mutex)

#### [std::mutex](https://en.cppreference.com/w/cpp/thread/mutex)

* The mutex class is a synchronization primitive that can be used to protect shared data from being simultaneously accessed by multiple threads.
* mutex offers exclusive, non-recursive ownership semantics:
	* A calling thread owns a mutex from the time that it successfully calls either lock or try_lock until it calls unlock.
	* When a thread owns a mutex, all other threads will block (for calls to lock) or receive a false return value (for try_lock) if they attempt to claim ownership of the mutex.
	* A calling thread must not own the mutex prior to calling lock or try_lock.
* The behavior of a program is undefined if a mutex is destroyed while still owned by any threads, or a thread terminates while owning a mutex. The mutex class satisfies all requirements of Mutex and StandardLayoutType.
* std::mutex is neither copyable nor movable.
* Notes
	* std::mutex is usually not accessed directly: std::unique_lock, std::lock_guard, or std::scoped_lock (since C++17) manage locking in a more exception-safe manner.
```c++
#include <iostream>
#include <map>
#include <string>
#include <chrono>
#include <thread>
#include <mutex>
 
std::map<std::string, std::string> g_pages;
std::mutex g_pages_mutex;
 
void save_page(const std::string &url)
{
    // simulate a long page fetch
    std::this_thread::sleep_for(std::chrono::seconds(2));
    std::string result = "fake content";
 
    std::lock_guard<std::mutex> guard(g_pages_mutex);
    g_pages[url] = result;
}
 
int main() 
{
    std::thread t1(save_page, "http://foo");
    std::thread t2(save_page, "http://bar");
    t1.join();
    t2.join();
 
    // safe to access g_pages without lock now, as the threads are joined
    for (const auto &pair : g_pages) {
        std::cout << pair.first << " => " << pair.second << '\n';
    }
}
/*
http://bar => fake content
http://foo => fake content
*/
```
* [mutex - C++ Reference](https://www.cplusplus.com/reference/mutex/mutex/)
	* class mutex;
	* Mutex class
		* A mutex is a lockable object that is designed to signal when critical sections of code need exclusive access, preventing other threads with the same protection from executing concurrently and access the same memory locations.
		* mutex objects provide exclusive ownership and do not support recursivity (i.e., a thread shall not lock a mutex it already owns) -- see recursive_mutex for an alternative class that does.
		* It is guaranteed to be a standard-layout class.

#### Generic mutex management

* [std::lock_guard - cppreference.com](https://en.cppreference.com/w/cpp/thread/lock_guard)
	* Defined in header \<mutex>
	* template\< class Mutex > class lock_guard; (since C++11)
	* The class lock_guard is a mutex wrapper that provides a convenient RAII-style mechanism for owning a mutex for the duration of a scoped block.
	* When a lock_guard object is created, it attempts to take ownership of the mutex it is given. When control leaves the scope in which the lock_guard object was created, the lock_guard is destructed and the mutex is released.
	* The lock_guard class is non-copyable.
	* Notes
		* [std::scoped_lock](https://en.cppreference.com/w/cpp/thread/scoped_lock) offers a replacement for lock_guard that provides the ability to lock multiple mutexes using a deadlock avoidance algorithm. (since C++17)
	* [std::lock_guard\<Mutex>::lock_guard - cppreference.com](https://en.cppreference.com/w/cpp/thread/lock_guard/lock_guard)
```c++
#include <thread>
#include <mutex>
#include <iostream>
 
int g_i = 0;
std::mutex g_i_mutex;  // protects g_i
 
void safe_increment()
{
    const std::lock_guard<std::mutex> lock(g_i_mutex);
    ++g_i;
 
    std::cout << "g_i: " << g_i << "; in thread #"
              << std::this_thread::get_id() << '\n';
 
    // g_i_mutex is automatically released when lock
    // goes out of scope
}
 
int main()
{
    std::cout << "g_i: " << g_i << "; in main()\n";
 
    std::thread t1(safe_increment);
    std::thread t2(safe_increment);
 
    t1.join();
    t2.join();
 
    std::cout << "g_i: " << g_i << "; in main()\n";
}
/*
g_i: 0; in main()
g_i: 1; in thread #140487981209344
g_i: 2; in thread #140487972816640
g_i: 2; in main()
*/
```
* [lock_guard - C++ Reference](https://www.cplusplus.com/reference/mutex/lock_guard/)
  * template \<class Mutex> class lock_guard;
  * Lock guard
    * A lock guard is an object that manages a mutex object by keeping it always locked.
    * On construction, the mutex object is locked by the calling thread, and on destruction, the mutex is unlocked. It is the simplest lock, and is specially useful as an object with automatic duration that lasts until the end of its context. In this way, it guarantees the mutex object is properly unlocked in case an exception is thrown.
    * Note though that the lock_guard object does not manage the lifetime of the mutex object in any way: the duration of the mutex object shall extend at least until the destruction of the lock_guard that locks it.
* [std::scoped_lock - cppreference.com](https://en.cppreference.com/w/cpp/thread/scoped_lock)
	* deadlock-avoiding RAII wrapper for multiple mutexes (class template)
	* The class scoped_lock is a mutex wrapper that provides a convenient RAII-style mechanism for owning one or more mutexes for the duration of a scoped block.
	* When a scoped_lock object is created, it attempts to take ownership of the mutexes it is given. When control leaves the scope in which the scoped_lock object was created, the scoped_lock is destructed and the mutexes are released. If several mutexes are given, deadlock avoidance algorithm is used as if by std::lock.
	* The scoped_lock class is non-copyable.

#### Generic locking algorithms

#### Call once

### Futures

* The standard library provides facilities to obtain values that are returned and to catch exceptions that are thrown by asynchronous tasks (i.e. functions launched in separate threads). These values are communicated in a shared state, in which the asynchronous task may write its return value or store an exception, and which may be examined, waited for, and otherwise manipulated by other threads that hold instances of std::future or std::shared_future that reference that shared state.
* Defined in header [`<future>`](https://en.cppreference.com/w/cpp/header/future)

#### [std::future](https://en.cppreference.com/w/cpp/thread/future)

* waits for a value that is set asynchronously (class template)
* The class template std::future provides a mechanism to access the result of asynchronous operations:
    * An asynchronous operation (created via [std::async](https://en.cppreference.com/w/cpp/thread/async), [std::packaged_task](https://en.cppreference.com/w/cpp/thread/packaged_task), or [std::promise](https://en.cppreference.com/w/cpp/thread/promise)) can provide a std::future object to the creator of that asynchronous operation.
    * The creator of the asynchronous operation can then use a variety of methods to query, wait for, or extract a value from the std::future. These methods may block if the asynchronous operation has not yet provided a value.
    * When the asynchronous operation is ready to send a result to the creator, it can do so by modifying shared state (e.g. [std::promise::set_value](https://en.cppreference.com/w/cpp/thread/promise/set_value)) that is linked to the creator's `std::future`.
* Note that std::future references shared state that is not shared with any other asynchronous return objects (as opposed to [std::shared_future](https://en.cppreference.com/w/cpp/thread/shared_future)).
* Examples
```c++
#include <iostream>
#include <future>
#include <thread>
 
int main()
{
    // future from a packaged_task
    std::packaged_task<int()> task([]{ return 7; }); // wrap the function
    std::future<int> f1 = task.get_future();  // get a future
    std::thread t(std::move(task)); // launch on a thread
 
    // future from an async()
    std::future<int> f2 = std::async(std::launch::async, []{ return 8; });
 
    // future from a promise
    std::promise<int> p;
    std::future<int> f3 = p.get_future();
    std::thread( [&p]{ p.set_value_at_thread_exit(9); }).detach();
 
    std::cout << "Waiting..." << std::flush;
    f1.wait();
    f2.wait();
    f3.wait();
    std::cout << "Done!\nResults are: "
              << f1.get() << ' ' << f2.get() << ' ' << f3.get() << '\n';
    t.join();
}
/*
Waiting...Done!
Results are: 7 8 9
*/
```
* Example with exceptions
```c++
#include <thread>
#include <iostream>
#include <future>
 
int main()
{
    std::promise<int> p;
    std::future<int> f = p.get_future();
 
    std::thread t([&p]{
        try {
            // code that may throw
            throw std::runtime_error("Example");
        } catch(...) {
            try {
                // store anything thrown in the promise
                p.set_exception(std::current_exception());
            } catch(...) {} // set_exception() may throw too
        }
    });
 
    try {
        std::cout << f.get();
    } catch(const std::exception& e) {
        std::cout << "Exception from the thread: " << e.what() << '\n';
    }
    t.join();
}
/*
Exception from the thread: Example
*/
```

##### Member functions

###### [`std::future<T>::future`](https://en.cppreference.com/w/cpp/thread/future/future)

* (constructor)
* constructs the future object (public member function)
```c++
future() noexcept;  (1)	(since C++11)
future( future&& other ) noexcept;  (2)	(since C++11)
future( const future& other ) = delete; (3)	(since C++11)
```
* Constructs a std::future object.
    * 1) Default constructor. Constructs a std::future with no shared state. After construction, `valid() == false`.
    * 2) Move constructor. Constructs a std::future with the shared state of other using move semantics. After construction, `other.valid() == false`.
    * 3) std::future is not [CopyConstructible](https://en.cppreference.com/w/cpp/named_req/CopyConstructible).
* Parameters
    * other	-   another std::future to acquire shared state from

###### Getting the result

#
[`std::future<T>::get`](https://en.cppreference.com/w/cpp/thread/future/get)

* returns the result (public member function)
* The get member function waits until the future has a valid result and (depending on which template is used) retrieves it. It effectively calls [wait()](https://en.cppreference.com/w/cpp/thread/future/wait) in order to wait for the result.
* The generic template and two template specializations each contain a single version of get. The three versions of get differ only in the return type.
* The behavior is undefined if [valid()](https://en.cppreference.com/w/cpp/thread/future/valid) is `false` before the call to this function.
* Any shared state is released. [valid()](https://en.cppreference.com/w/cpp/thread/future/valid) is `false` after a call to this member function.
* Notes
    * The implementations are encouraged to detect the case when `valid()` is `false` before the call and throw a [std::future_error](https://en.cppreference.com/w/cpp/thread/future_error) with an error condition of [std::future_errc::no_state](https://en.cppreference.com/w/cpp/thread/future_errc).
* Example
```c++
#include <thread>
#include <future>
#include <iostream>
#include <string>
#include <chrono>
 
std::string time() {
    static auto start = std::chrono::steady_clock::now();
    std::chrono::duration<double> d = std::chrono::steady_clock::now() - start;
    return "[" + std::to_string(d.count()) + "s]";
}
int main() {
    using namespace std::chrono_literals;
    {
        std::cout << time() << " launching thread\n";
        std::future<int> f = std::async(std::launch::async, []{
            std::this_thread::sleep_for(1s);
            return 7;
        });
        std::cout << time() << " waiting for the future, f.valid() == "
                  << f.valid() << "\n";
        int n = f.get();
        std::cout << time() << " future.get() returned with " << n << ". f.valid() = "
                  << f.valid() << '\n';
    }
 
    {
        std::cout << time() << " launching thread\n";
        std::future<int> f = std::async(std::launch::async, []{
            std::this_thread::sleep_for(1s);
            return true ? throw std::runtime_error("7") : 7;
        });
        std::cout << time() << " waiting for the future, f.valid() == "
                  << f.valid() << "\n";
        try {
            int n = f.get();
            std::cout << time() << " future.get() returned with " << n
                      << " f.valid() = " << f.valid() << '\n';
        } catch(const std::exception& e) {
            std::cout << time() << " caught exception " << e.what()
                      << ", f.valid() == " << f.valid() << "\n";
        }
    }
}
/*
[0.000004s] launching thread
[0.000461s] waiting for the future, f.valid() == 1
[1.001156s] future.get() returned with 7. f.valid() = 0
[1.001192s] launching thread
[1.001275s] waiting for the future, f.valid() == 1
[2.002356s] caught exception 7, f.valid() == 0
*/
```

###### State

#
[`std::future<T>::valid`](https://en.cppreference.com/w/cpp/thread/future/valid)

* checks if the future has a shared state (public member function)
* Checks if the future refers to a shared state.
* This is the case only for futures that were not default-constructed or moved from (i.e. returned by [std::promise::get_future()](https://en.cppreference.com/w/cpp/thread/promise/get_future), [std::packaged_task::get_future()](https://en.cppreference.com/w/cpp/thread/packaged_task/get_future) or [std::async()](https://en.cppreference.com/w/cpp/thread/async)) until the first time [get()](https://en.cppreference.com/w/cpp/thread/future/get) or [share()](https://en.cppreference.com/w/cpp/thread/future/share) is called.
* The behavior is undefined if any member function other than the destructor, the move-assignment operator, or valid is called on a future that does not refer to shared state (although implementations are encouraged to throw [std::future_error](https://en.cppreference.com/w/cpp/thread/future_error) indicating no_state in this case). It is valid to move from a future object for which `valid()` is false.
* Parameters
    * (none)
* Return value
    * true if `*this` refers to a shared state, otherwise false.
* Example
```c++
#include <future>
#include <iostream>
 
int main() {
    std::promise<void> p;
    std::future<void> f = p.get_future();
 
    std::cout << std::boolalpha;
 
    std::cout << f.valid() << '\n';
    p.set_value();
    std::cout << f.valid() << '\n';
    f.get();
    std::cout << f.valid() << '\n';
}
/*
true
true
false
*/
```

#
[`std::future<T>::wait`](https://en.cppreference.com/w/cpp/thread/future/wait)

* waits for the result to become available (public member function)
* Blocks until the result becomes available. `valid() == true` after the call.
* The behavior is undefined if `valid() == false` before the call to this function.
* Parameters
    * (none)
* Return value
    * (none)
* Exceptions
    * May throw implementation-defined exceptions.
* Notes
    * The implementations are encouraged to detect the case when `valid() == false` before the call and throw a [std::future_error](https://en.cppreference.com/w/cpp/thread/future_error) with an error condition of [std::future_errc::no_state](https://en.cppreference.com/w/cpp/thread/future_errc).
* Example
```c++
#include <chrono>
#include <iostream>
#include <future>
#include <thread>
 
int fib(int n)
{
  if (n < 3) return 1;
  else return fib(n-1) + fib(n-2);
}
 
int main()
{
    std::future<int> f1 = std::async(std::launch::async, [](){
        return fib(40);
    });
    std::future<int> f2 = std::async(std::launch::async, [](){
        return fib(43);
    });
 
    std::cout << "waiting... " << std::flush;
    const auto start = std::chrono::system_clock::now();
 
    f1.wait();
    f2.wait();
 
    const auto diff = std::chrono::system_clock::now() - start;
    std::cout << std::chrono::duration<double>(diff).count() << " seconds\n";
 
    std::cout << "f1: " << f1.get() << '\n';
    std::cout << "f2: " << f2.get() << '\n';
}
/*
waiting... 1.61803 seconds
f1: 102334155
f2: 433494437
*/
```

#### [std::async](https://en.cppreference.com/w/cpp/thread/async)

* runs a function asynchronously (potentially in a new thread) and returns a [std::future](https://en.cppreference.com/w/cpp/thread/future) that will hold the result (function template)
* The function template async runs the function f asynchronously (potentially in a separate thread which might be a part of a thread pool) and returns a `std::future` that will eventually hold the result of that function call.
    * 1) Behaves as if (2) is called with `policy` being `std::launch::async | std::launch::deferred`.
    * 2) Calls a function f with arguments args according to a specific launch policy policy.
        * If the `async` flag is set (i.e. `(policy & std::launch::async) != 0`), then async executes the callable object f on a new thread of execution (with all thread-locals initialized) as if spawned by `std::thread(std::forward<F>(f), std::forward<Args>(args)...)`, except that if the function f returns a value or throws an exception, it is stored in the shared state accessible through the `std::future` that async returns to the caller.
        * If the `deferred` flag is set (i.e. `(policy & std::launch::deferred) != 0`), then async converts f and `args...` the same way as by `std::thread` constructor, but does not spawn a new thread of execution. Instead, `lazy evaluation` is performed: the first call to a non-timed wait function on the `std::future` that async returned to the caller will cause the copy of f to be invoked (as an rvalue) with the copies of `args...` (also passed as rvalues) in the current thread (which does not have to be the thread that originally called `std::async`). The result or exception is placed in the shared state associated with the future and only then it is made ready. All further accesses to the same `std::future` will return the result immediately.
        * If neither `std::launch::async` nor `std::launch::deferred`, nor any implementation-defined policy flag is set in policy, the behavior is undefined.
    * If more than one flag is set, it is implementation-defined which policy is selected. For the default (both the `std::launch::async` and `std::launch::deferred` flags are set in policy), standard recommends (but doesn't require) utilizing available concurrency, and deferring any additional tasks.
* In any case, the call to `std::async` `synchronizes-with` (as defined in [std::memory_order](https://en.cppreference.com/w/cpp/atomic/memory_order)) the call to f, and the completion of f is sequenced-before making the shared state ready. If the async policy is chosen, the associated thread completion `synchronizes-with` the successful return from the first function that is waiting on the shared state, or with the return of the last function that releases the shared state, whichever comes first. If `std::decay<Function>::type` or each type in `std::decay<Args>::type` is not constructible from its corresponding argument, the program is ill-formed.
* Parameters
    * f	-   Callable object to call
    * args...	-	parameters to pass to f
    * policy	-	bitmask value, where individual bits control the allowed methods of execution
        * Bit   Explanation
        * [std::launch::async](https://en.cppreference.com/w/cpp/thread/launch)	enable asynchronous evaluation
        * [std::launch::deferred](https://en.cppreference.com/w/cpp/thread/launch)	enable lazy evaluation
* Return value
    * `std::future` referring to the shared state created by this call to `std::async`.
* Exceptions
    * Throws [std::system_error](https://en.cppreference.com/w/cpp/error/system_error) with error condition [std::errc::resource_unavailable_try_again](https://en.cppreference.com/w/cpp/thread/async#:~:text=std%3A%3Aerrc%3A%3Aresource_unavailable_try_again) if the launch policy equals [std::launch::async](https://en.cppreference.com/w/cpp/thread/launch) and the implementation is unable to start a new thread (if the policy is async|deferred or has additional bits set, it will fall back to deferred or the implementation-defined policies in this case), or [std::bad_alloc](https://en.cppreference.com/w/cpp/memory/new/bad_alloc) if memory for the internal data structures could not be allocated.
* Notes
    * The implementation may extend the behavior of the first overload of std::async by enabling additional (implementation-defined) bits in the default launch policy.
    * Examples of implementation-defined launch policies are the sync policy (execute immediately, within the async call) and the task policy (similar to async, but thread-locals are not cleared)
    * If the std::future obtained from std::async is not moved from or bound to a reference, the destructor of the std::future will block at the end of the full expression until the asynchronous operation completes, essentially making code such as the following synchronous:
    ```c++
    std::async(std::launch::async, []{ f(); }); // temporary's dtor waits for f()
    std::async(std::launch::async, []{ g(); }); // does not start until f() completes
    ```
    * (note that the destructors of std::futures obtained by means other than a call to std::async never block)
* Example
```c++
#include <iostream>
#include <vector>
#include <algorithm>
#include <numeric>
#include <future>
#include <string>
#include <mutex>
 
std::mutex m;
struct X {
    void foo(int i, const std::string& str) {
        std::lock_guard<std::mutex> lk(m);
        std::cout << str << ' ' << i << '\n';
    }
    void bar(const std::string& str) {
        std::lock_guard<std::mutex> lk(m);
        std::cout << str << '\n';
    }
    int operator()(int i) {
        std::lock_guard<std::mutex> lk(m);
        std::cout << i << '\n';
        return i + 10;
    }
};
 
template <typename RandomIt>
int parallel_sum(RandomIt beg, RandomIt end)
{
    auto len = end - beg;
    if (len < 1000)
        return std::accumulate(beg, end, 0);
 
    RandomIt mid = beg + len/2;
    auto handle = std::async(std::launch::async,
                             parallel_sum<RandomIt>, mid, end);
    int sum = parallel_sum(beg, mid);
    return sum + handle.get();
}
 
int main()
{
    std::vector<int> v(10000, 1);
    std::cout << "The sum is " << parallel_sum(v.begin(), v.end()) << '\n';
 
    X x;
    // Calls (&x)->foo(42, "Hello") with default policy:
    // may print "Hello 42" concurrently or defer execution
    auto a1 = std::async(&X::foo, &x, 42, "Hello");
    // Calls x.bar("world!") with deferred policy
    // prints "world!" when a2.get() or a2.wait() is called
    auto a2 = std::async(std::launch::deferred, &X::bar, x, "world!");
    // Calls X()(43); with async policy
    // prints "43" concurrently
    auto a3 = std::async(std::launch::async, X(), 43);
    a2.wait();                     // prints "world!"
    std::cout << a3.get() << '\n'; // prints "53"
} // if a1 is not done at this point, destructor of a1 prints "Hello 42" here
/*
The sum is 10000
43
world!
53
Hello 42
*/
```

#### MISC

* [从无栈协程到 C++异步框架](https://mp.weixin.qq.com/s/QVXE7QbxEchl8ue4SoijiQ)
	* 本文我们将尝试对整个 C++的协程做深入浅出的剥析, 方便大家的理解. 再结合上层的封装, 最终给出一个 C++异步框架实际业务使用的一种形态, 方便大家更好的在实际项目中应用无栈协程。

## Best Practice

* [C++ 实用指南](https://mp.weixin.qq.com/s/PZ27a-Epy_WUITk7SWOHCQ)
  * 介   绍
  * 一些问题
  * 其他问题？
  * 如何保持理智
  * 保持乐观，语言在不断发展
  * 使用指南
  * 还有工具！
  * 努力跟上最新进展
  * 细节太多了？
  * 使用你需要的东西
  * 增量变更
  * 最后的底线：你的旧代码仍然可以编译
  * 总   结
* [编写可移植 C/C++ 程序的一些要点](https://mp.weixin.qq.com/s/Q_vCEHmJuF6WB5NsfyHkpw)
  * https://blog.csdn.net/absurd
  * 1、分层设计，隔离平台相关的代码。
  * 2、事先熟悉各目标平台，合理抽象底层功能。
  * 3、尽量使用标准 C/C++ 函数。
  * 4、尽量不要使用 C/C++ 新标准里出现的特性。
  * 5、尽量不要使用 C/C++ 标准里没有明确规定的特性。
  * 6、尽量不要使用准标准函数。
  * 7、注意标准函数的细节。
  * 8、小心数据标准数据类型。
  * 9、最好不要使用平台独有的特性。
  * 10、最好不要使用编译器特有的特性。
  * 11、注意平台的特性。
  * 12、最好清楚不同平台的资源限制。
* [C++ 的门门道道 | 技术头条 - CSDN](https://mp.weixin.qq.com/s/XRq0D1UJTyVI-uyjfmJuqg)
  * C++是一门被广泛使用的系统级编程语言，更是高性能后端标准开发语言；C++虽功能强大，灵活巧妙，但却属于易学难精的专家型语言，不仅新手难以驾驭，就是老司机也容易掉进各种陷阱。
  * 本文结合作者的工作经验和学习心得，对C++语言的一些高级特性，做了简单介绍；对一些常见的误解，做了解释澄清；对比较容易犯错的地方，做了归纳总结；希望借此能增进大家对C++语言了解，减少编程出错，提升工作效率。
* [C/C++ 程序员的编程修养](https://mp.weixin.qq.com/s/X5eS6-iI8w-VNaASLTS0Eg)
  * 1、版权和版本
  * 2、缩进、空格、换行、空行、对齐
  * 3、程序注释
  * 4、函数的[in][out]参数
  * 5、对系统调用的返回进行判断
  * 6、if 语句对出错的处理
  * 7、头文件中的#ifndef
  * 8、在堆上分配内存
  * 9、变量的初始化
  * 10、h和c文件的使用
  * 11、出错信息的处理
  * 12、常用函数和循环语句中的被计算量
  * 13、函数名和变量名的命名
  * 14、函数的传值和传指针
  * 15、修改别人程序的修养
  * 16、把相同或近乎相同的代码形成函数和宏
  * 17、表达式中的括号
  * 18、函数参数中的const
  * 19、函数的参数个数（多了请用结构）
  * 20、函数的返回类型，不要省略
  * 21、goto语句的使用
  * 22、宏的使用
  * 23、static的使用
  * 24、函数中的代码尺寸
  * 25、typedef的使用
  * 26、为常量声明宏
  * 27、不要为宏定义加分号
  * 28、||和&&的语句执行顺序
  * 29、尽量用for而不是while做循环
  * 30、请sizeof类型而不是变量
  * 31、不要忽略Warning
  * 32、书写Debug版和Release版的程序
* [为什么说 C++ 太复杂？有必要这么复杂吗？| 原力计划 (qq.com)](https://mp.weixin.qq.com/s/qYbKq-krR_GkBNbHsvbl5Q)
  * [为什么说C++太复杂？复杂的必要性是为什么？_韩江雪de 小屋-CSDN博客](https://blog.csdn.net/qq_33375598/article/details/105927654)
* [为什么我十分喜欢C，却很不喜欢C++ (qq.com)](https://mp.weixin.qq.com/s/3MAr5sdeYkeoGNTOJ4f6TA)
  * [Why I still like C and strongly dislike C++ « Kostya's Boring Codec World (multimedia.cx)](https://codecs.multimedia.cx/2021/05/why-i-still-like-c-and-strongly-dislike-cpp/)
* [C++ 过去的这一年 (qq.com)](https://mp.weixin.qq.com/s/QymYhKJ_877DEdjYYFYHQQ)
  * 本年度我想强调的就以下三件事情：
    * C++ 20即将发布。
    * 开发工具 – 让编写C++代码更加容易！
    * C++在开发者中的稳定位置
  * 总而言之，我认为在未来的十年，我们可以以一种积极乐观的态度看待C++。虽然我们无法预知更远的将来会发生什么，但是至少在接下来的十年里，我相信C++应该是稳定的。有了所有这些工具的帮助，新的C++标准编写的C++代码会更加容易访问，并且更加不容易出错。在可预见的将来，C++仍然是追求性能的应用程序的无二选择，甚至它会取代C和Fortran。
* [“越来越像新语言的 C++，我与它结缘、痴迷、深耕的 14 年！”](https://mp.weixin.qq.com/s/C3FsZ822oA-CBYSQKn1F8w)
* [C/C++ include header file order - Stack Overflow](https://stackoverflow.com/questions/2762568/c-c-include-header-file-order)
	* My personal preference is to go from local to global, each subsection in alphabetical order, i.e.:
		* h file corresponding to this cpp file (if applicable)
		* headers from the same component,
		* headers from other components,
		* system headers.
	* My rationale for 1. is that it should prove that each header (for which there is a cpp) can be #included without prerequisites (terminus technicus: header is "self-contained"). And the rest just seems to flow logically from there.

### Bug

* [C ++ 中不容忽视的 25 个 API 错误设计！](https://mp.weixin.qq.com/s/Yyno5VNHr88BaQvMoZafVA)
  * https://www.acodersjourney.com/top-25-cplusplus-api-design-mistakes-and-how-to-avoid-them/
  * 错误＃1：不将你的API放在命名空间中
  * 错误＃2：在你的公共API头的全局范围中包含“using namespace”
  * 错误＃3：无视“三法则”
  * 错误＃4：不将API中的移动构造函数和移动赋值运算符标记为noexcept
  * 错误＃5：不将不可抛出的API标记为noexcept
  * 错误＃6：不将单个参数构造函数标记为显式
  * 错误＃7：不将只读数据/方法标记为const
  * 错误＃8：通过const引用返回API的内部
  * 错误＃9：使用隐式模板实例化时，使用模板实现细节来混淆公共头文件
  * 错误＃10：当用例已知时，不使用显式模板实例化
  * 错误＃11：在默认函数参数中公开内部值
  * 错误＃12：将#Defines用于C ++ API
  * 错误＃13：使用友元类
  * 错误＃14：不避免不必要的include头文件
  * 错误＃15：对外来（不是你自己的）对象类型使用前向声明
  * 错误＃16：不让头文件必须自行编译
  * 错误＃17：没有为你的API提供版本控制信息
  * 错误＃18：从一开始就没有决定静态或动态库的实现
  * 错误＃19：没有认识到ABI的兼容性
  * 错误＃20：向已发布的类API添加纯虚方法
  * 错误＃21：不记录API是同步还是异步
  * 错误＃22：没有使用平台/编译器支持的最低公共特性
  * 错误＃23：不考虑开源项目的头文件实现
  * 错误＃24：参数类型不一致
  * 错误＃25：没有API审核流程！
* [这 5 个 C/C++ Bug](https://mp.weixin.qq.com/s/w6YRs_3MkJTRz4Yo8aFOAw)
  * 1. 变量未初始化
  * 2. 数组越界
  * 3. 字符串溢出
  * 4. 内存重复释放
  * 5. 使用无效的文件指针
* [代码优化导致的奇葩问题](https://mp.weixin.qq.com/s/p2GRR3n0s338K1qAmZOhMA)
  * 总结、什么情况会导致这样的问题？
  * 1、堆栈溢出应该是一个原因，之前我有遇到的情况是栈空间设置太小，然后溢出到堆空间导致问题。
  * 2、使用某个函数导致溢出，我们使用的函数，比如，内存拷贝函数，如果长度设置不对，也会导致影响到其他的代码。
  * 3、还有就是上面说的编译器优化导致的问题。
* [C++编程新手容易犯的 10 种编程错误](https://mp.weixin.qq.com/s/tUT9sDR-d1aTzWof3TCjNg)
	* 1、有些关键字在 cpp 文件中多写了
	* 2、函数参数的默认值写到函数实现中了
	* 3、在编写类的时候，在类的结尾处忘记添加 ";" 分号了
	* 4、只添加了函数声明，没有函数实现
	* 5、cpp 文件忘记添加到工程中，导致没有生成供链接使用的 obj 文件
	* 6、函数中返回了一个局部变量的地址或者引用
	* 7、忘记将父类中的接口声明 virtual 函数，导致多态没有生效
	* 8、该使用双指针的地方，却使用了单指针
	* 9、发布 exe 程序时，忘记将 exe 依赖的 C 运行时库和 MFC 库带上
	* 10、应该使用深拷贝，却使用了浅拷贝
* [常见的C++软件异常场景分析与总结](https://mp.weixin.qq.com/s/QkSz04-YGo4PB2EWlJ-wqA)
	* https://blog.csdn.net/chenlycly/article/details/82734138
	* 1、野指针问题
	* 2、空指针问题
	* 3、堆内存被释放两次
	* 4、栈内存被当做堆内存来释放
	* 5、内存访问越界
	* 6、函数调用约定不一致引起的栈不平衡的问题
	* 7、调用虚函数时的二次寻址
	* 8、debug和release库混用的问题
	* 9、死循环问题
	* 10、死锁问题排查
	* 11、数据类型使用违规引起的问题
	* 12、抛出异常后导致部分代码被跳过的问题
	* 13、类对象没有初始化就直接访问问题
* [现代C++避坑指南](https://mp.weixin.qq.com/s/rY1smeTcR_k-YCeA4dY8VQ)
	* 避坑1  自动推导
		* 上面的代码在堆上定义了一个5G大小的内存，实际上已经超出了整型的最大值，可见，auto并不能避免溢出错误。
		* 另外，在容器中也是一样容器的大小是一个无符号整型数，假设容器的大小已经超出了无符号整型范围，那么即使auto也是分身乏术。
	* 避坑2  合理使用std::size()
	* 避坑3  循环陷阱
		* 在C++中，无符号整型是大于或者等于0的，经常用来标识数组的大小。在循环中使用它作为循环条件时也可能会产生错误。
	* 避坑4  虚拟函数
		* C++中，虚函数中隐藏一个潜在可能发生的问题，即如果子类中和父类定义了一个相同的方法，本意是想覆盖父类中的方法，但是却在子类中定义了一个新的方法
		* 从上面大代码片段可见，子类中重写的接口比父类多了一个参数，这样在有些编译器中编译时会发生告警。如果想要避免这个问题，可以使用C++11中的override关键字
	* 避坑5  null和nullptr
		* C++中，新增了关键字nullptr用来标识指针为空，传统是是用NULL判断，但是NULL实际上是一个宏定义，在和整型值进行判定的时候会被当做0值处理。
		* 实际编程时，在使用现代C++编程时，如果需要判断指针是否为空时建议使用nullptr。
* [终极 C++避坑指南|6万字长文](https://mp.weixin.qq.com/s/tSEFdJjpQJVrgztIWWwlMw)
* [C++陷阱与套路](https://mp.weixin.qq.com/s/WeIjy6XJRt8D7clgR-zzJg)

#### Memory Leak

* [C++ 如何避免内存泄露](https://mp.weixin.qq.com/s/oBTNXxUiU3StexuyCKPI6w)
  * 内存是如何泄露的
  * 经验 #1：尽量避免在堆上分配内存
  * 经验 #2：使用 Arena
  * 经验 #3：使用 Coroutine
  * 经验 #4：善用 RAII
  * 经验 #5：便于 Debug
* [你踩过几种C++内存泄露的坑？](https://mp.weixin.qq.com/s/8h_ek1NLE9mOKdA2WiOoQw)
  * 1. 函数内或者类成员内存未释放
  * 2. delete []
  * 3. delete (void*)
  * 4. Virtual destructor
  * 5. 对象循环引用
  * 6. 资源泄露
* [C++常见的三种内存破坏的场景和分析](https://mp.weixin.qq.com/s/uG4R-oSjf2AO-OVm2A1rPw)
  * 有一定C++开发经验的同学大多数踩过内存破坏的坑,有这么几种现象:
    * 比如某个变量整形，在程序中只可能初始化或者赋值为1或者2, 但是在使用的时候却发现其为0或者其他的情况。对于其他类型，比如字符串等，可能出现了一种出乎意料的值！
    * 程序在堆上申请内存或者释放内存的时候，在内存充足的情况下，居然出现了堆错误。
  * 当出现以上场景的时候，你该思考一下，是不是出现了内存破坏的情况了。而本文主要通过展示和分析常见的三种内存破坏导致覆盖相邻变量的场景，让读者在碰到类似的场景，不至于束手无策。而对于堆上的内存破坏，很常见并且棘手的场景，本人将在后续的文章和大家分享。
  * 1. 内存破坏之强制类型转换
  * 2. 字符串拷贝溢出
  * 3. 随机性的内存被修改
* [一文搞定 | Linux共享内存原理](https://mp.weixin.qq.com/s/RB6KRXF_uJF7wXjRvDyhmQ)
  * https://cloud.tencent.com/developer/article/1396351
  * 在Linux系统中，每个进程都有独立的虚拟内存空间，也就是说不同的进程访问同一段虚拟内存地址所得到的数据是不一样的，这是因为不同进程相同的虚拟内存地址会映射到不同的物理内存地址上。
  * 但有时候为了让不同进程之间进行通信，需要让不同进程共享相同的物理内存，Linux通过 共享内存 来实现这个功能。下面先来介绍一下Linux系统的共享内存的使用。
  * 共享内存使用
  * 共享内存实现原理
* [C/C++ 动态检测内存错误利器 - ASan](https://mp.weixin.qq.com/s/u6UtoXQkdcomtGZxX9vsvw)
  * ASan，即Address Sanitizer，是一个适用于c/c++程序的动态内存错误检测器，它由一个编译器检测模块（LLVM pass）和一个替换malloc函数的运行时库组成，在性能及检测内存错误方面都优于Valgrind，你值得拥有。

### GUI

* [List of platform-independent GUI libraries - Wikipedia](https://en.wikipedia.org/wiki/List_of_platform-independent_GUI_libraries)

### Logging

* [一文详解 C++ 日志框架](https://mp.weixin.qq.com/s/0heKciXbMl95WMTXLfr8UA)

### Parse Command Line

* [Chapter 31. Boost.Program_options - 1.72.0](https://www.boost.org/doc/libs/1_72_0/doc/html/program_options.html)
  * The program_options library allows program developers to obtain program options, that is (name, value) pairs from the user, via conventional methods such as command line and config file.
  * [Tutorial - 1.72.0](https://www.boost.org/doc/libs/1_72_0/doc/html/program_options/tutorial.html#id-1.3.32.4.3)
    * https://github.com/boostorg/program_options/blob/develop/example/first.cpp
  * [default_value() - Class template typed_value - 1.72.0](https://www.boost.org/doc/libs/1_72_0/doc/html/boost/program_options/typed_value.html#id-1_3_32_9_10_1_1_1_5_1-bb)
  * [c++ - Boost.Program_Options: When \<bool> is specified as a command-line option, what are valid command-line parameters? - Stack Overflow](https://stackoverflow.com/questions/15629771/boost-program-options-when-bool-is-specified-as-a-command-line-option-what-a)
  * [Chapter 63. Boost.ProgramOptions](https://theboostcpplibraries.com/boost.program_options)

### Performance

* [性能统计类](https://mp.weixin.qq.com/s/6LHThiscLQ1gNCwLlTSHRQ)
```c++
#include <iostream>
#include <chrono>
using namespace std;
class PerfSum{
    public:
        PerfSum()
        {
            _beginTime = std::chrono::high_resolution_clock::now();
        }
        ~PerfSum()
        {
            auto ms = std::chrono::duration_cast<std::chrono::milliseconds>(std::chrono::high_resolution_clock::now()-_beginTime);
            std::cout<<"统计性能结束，时间过去了"<< ms.count() <<"毫秒"<<std::endl;
        }
    private:
        std::chrono::high_resolution_clock::time_point _beginTime;
 };

//使用方法：
void TestStdVec()
{
    std::vector<int> vec ;
    PerfSum t;
    
    for(long i=0;i<1000000;i++) {
        vec.push_back(i);
    }
    std::cout<<"End"<<std::endl;
}

int main() 
{
    std::cout<<"标准容器插入1000000次:"<<std::endl;
    TestStdVec();
}
```
* [提高C++性能的编程技术](https://mp.weixin.qq.com/s/SqN8gphEzRNsQMExrFlZxw)
	* 最近看了一本书《提高C++性能的编程技术》，这本书内容比较老，有些内容不太适合现在的编译器，但里面很多内容还是值得我们学习的。
	* 我这里整理出了自认为有用的条目分享给大家，希望对大家有所帮助，想了解具体内容的的朋友可以直接去看书哈。
	* 我将这些内容分为了三大类别：
		* 对象的创建与销毁：主要介绍对象构造与销毁的代价和临时对象那些事。
		* 函数调用：主要介绍内联和虚函数及模板相关的知识点。
		* 设计：如何设计并编写出更高效的代码。
	* 对象的创建与销毁：
		* C++中对象的定义会隐式的执行构造函数和析构函数，这是有开销的，对象的生命周期不是无偿的，至少对象的创建和销毁会消耗CPU周期。所以若非必要，不要随便定义对象，要等到需要使用对象的地方再创建它。
		* 对象的创建或销毁会触发对父对象和成员对象的递归创建或销毁，要当心复杂层次中对象的复合使用。它们使得创建和销毁的开销更加高昂。
		* 对象的拷贝是有开销的，很多时候可以减少拷贝，考虑按引用或者指针传递和返回对象。
		* RVO可以省去创建和销毁局部对象的步骤，从而改善性能。
		* 临时对象会以构造函数和析构函数的形式降低一半的性能。在\<op>可能是“+、-、＊”或者“/”的地方，可以考虑使用\<op>=运算符消除临时对象。
		* 编译器必须初始化被包含的成员对象之后再执行构造函数体。必须在初始化阶段完成成员对象的创建。这可以降低随后在构造函数部分调用赋值操作符的开销。在某些情况下，这样也可以避免临时对象的产生。
		* 将构造函数声明为explicit，可以避免隐式转换，一般这块都会被列为项目的编码规范，不符合这个规范是过不了code review的。
	* 函数调用：
		* 绝大多数的性能优化是靠内联做到的。
		* 内联就是用方法的代码来替换对方法的调用。（和宏是不是挺像）
		* 内联通过消除调用开销来提升性能，并且允许进行调用间优化。
		* 内联也有缺点，尤其是滥用的情况下。内联可能会使代码量变大，而代码量增多后会较原先出现更多的缓存失败和页面错误。
		* 为什么说虚函数慢？虚函数的代价在于无法内联函数调用，因为这些调用是在运行时动态绑定的。唯一潜在的效率问题是从内联获得的速度（如果可以内联的话）。
		* 模板比继承提供更好的性能。它把对类型的解析提前到编译期间，也可以认为这是没有成本的。
	* 设计：
		* 软件性能和灵活性之间存在一种基本的平衡，太灵活的设计一般性能都不太好，你的设计只需在当前范围之内足够灵活就可以了。在完成同样的简单工作时，char\*有时可以比string对象更有效率。
		* 引用计数想必大家都知道，有些场景中没必要使用引用计数，使用的简单的非计数对象即可，但是有些情况下，引用计数是个非常有用且有效的设计，尤其是在下述场景中：
			* 目标对象是很大的资源消费者。
			* 资源分配和释放的代价很高。
			* 高度共享，好多对象共享同一资源
		* 最快的代码是从不执行的代码，可做以下思考：
			* 你打算使用该计算结果吗？不打算使用就别浪费资源啦
			* 你现在需要该结果吗？请在真正需要的时候再进行计算。在一些执行流程中有些结果永远不会被使用，因此不必过早地计算
			* 你是否已经知道结果？那可以考虑结果重复使用，而不是每次都做计算
		* 有的时候可能无法绕开该计算，此时就必须完成它，那如何加快计算速度？可做以下思考：
			* 该计算是否过于通用？上面说过，没必要过度设计，满足需求即可。
			* 有些情况下有些考虑使用库调用，有些库调用比较灵活，有些库调用性能比较高，考虑使用高效的算法和数据结构。
			* 尽量减少内存管理，这些调用的代价比较高。
			* 80-20原则，如果考虑所有可能的输入数据，则可以发现20%的数据在80%时间里出现。因此，应当以牺牲其他不经常出现的场景为代价来提高典型输入的处理速度。
			* 缓存、RAM和磁盘访问的速度差异很明显，可能有10倍以上的差异。应该多编写缓存友好的代码。
		* 有些计算只有在特定的if-else分支下才需要，所以没必要过早计算，因为有可能它的计算结果不会被用到。
		* 定期清理不需要的代码：大型软件往往会变得错综复杂，杂乱不堪。混乱软件的一大特点就是执行失效代码（那些曾经用来实现某个目标，但现在已经不需要的代码）。定期清理失效和僵死代码可以增强软件性能，同时对于软件也是一种维护。
		* 考虑利用多处理器：
			* 将任务做分解：将大的任务分为小任务，使线程并发地执行这些小任务。
			* 缩小临界区：临界区应该只包含关键代码，不直接操作共享资源的代码不要放在临界区内。
			* 减小锁粒度：不要用同样的锁来保护所有资源，除非这些资源是同时更新的。
			* 读写锁：读多写少可以考虑使用读写锁。
			* 伪共享：不要在类定义里把两个使用频度都很高的锁放太靠近，它们共享同一个缓存行可能触发缓存一致性风暴。
			* 惊群现象：仔细分析您的锁调用的特征。当锁被释放时，是所有的等待线程都被唤醒还是只唤醒一个线程？唤醒所有线程会威胁到应用的可扩展性。
		* 要使用的存储器离处理器越远，访问所需的时间就越长。离处理器最近的是寄存器，虽然容量很少，但是速度很快。对寄存器的优化对程序的性能提升而言是极为有益的。
		* 上下文切换的开销巨大，请尽量避免上下文切换。
* [C++ 性能优化，简直太硬核了！](https://mp.weixin.qq.com/s/PdLeGRQs-VihsPZjtlx-vA)
	* https://developer.aliyun.com/article/412574
	* 整型
		* 类型转换
			* int--> short/char (0~1 clock cycle)
			* int --> float/double (4~16个clock cycle), signed int 快于 unsigned int，唯一一个场景 signed 比 unsigned 快的
			* short/char 的计算通常使用 32bit 存储，只是返回的时候做了截取，故只在要考虑内存大小的时候才使用 short/char，如 array
			* 注：隐式类型转换可能会溢出，有符号的溢出变成负数，无符号的溢出变成小的整数
		* 运算
			* 除法、取余运算unsigned int 快于 signed int
			* 除以常量比除以变量效率高，因为可以在编译期做优化，尤其是常量可以表示成2^n时
			* ++i和i++本身性能一样，但不同的语境效果不一样，如array[i++]比arry[++i]性能好；当依赖自增结果时，++i性能更好，如a=++b,a和b可复用同一个寄存器
	* 浮点
		* 单精度、双精度的计算性能是一样的
		* 常量的默认精度是双精度
		* 不要混淆单精度、双精度，混合精度计算会带来额外的精度转换开销
	* 实例2
		* 读取效率
			* 对于内存的写，最好的办法就是减少写的次数，那么内存的读取呢？教科书的答案是：尽可能顺序访问内存。理解这句话还是得从 cache line 开始
			* cache line
			* cache miss
			* 建议
				* 一起使用的函数存储在一起。函数的存储通常按照源码中的顺序来的，如果函数A,B,C是一起调用的，那尽量让ABC的声明也是这个顺序
				* 一起使用的变量存储在一起。使用结构体、对象来定义变量，并通过局部变量方式来声明，都是一些较好的选择。例子见后文：
				* 合理使用对齐(attribute((aligned(64)))、预取(prefecting data)，让一个cacheline能获取到更多有效的数据
				* 动态内存分配、STL容器、string都是一些常容易cache不友好的场景，核心代码处尽量不用
		* 静态变量
		* 回顾
		* 流水线
	* 函数
		* 本身开销
			* 函数调用使得处理器跳到另外一个代码地址并回来，一般需要4 clock cycles，大多数情况处理器会把函数调用、返回和其他指令一起执行以节约时间。
			* 函数参数存储在栈上需要额外的时间( 包括栈帧的建立、saving and restoring registers、可能还有异常信息)。在64bit linux上，前6个整型参数(包括指针、引用)、前8个浮点参数会放到寄存器中；64bit windows上不管整型、浮点，会放置4个参数。
			* 在内存中过于分散的代码可能会导致较差的code cache
		* 常见的优化手段
			* 避免不必要的函数，特别在最底层的循环，应该尽量让代码在一个函数内。看起来与良好的编码习惯冲突(一个函数最好不要超过80行)，其实不然，跟这个系列其他优化一样，我们应该知道何时去使用这些优化，而不是一上来就让代码不可读。
			* 尝试使用inline函数，让函数调用的地方直接用函数体替换。inline对编译器来说是个建议，而且不是inline了性能就好，一般当函数比较小或者只有一个地方调用的时候，inline效果会比较好
			* 在函数内部使用循环(e.g., change for(i=0;i<100;i++) DoSomething(); into DoSomething() { for(i=0;i<100;i++) { ... } } )
			* 减少函数的间接调用，如偏向静态链接而不是动态链接，尽量少用或者不用多继承、虚拟继承
			* 优先使用迭代而不是递归
			* 使用函数来替换define，从而避免多次求值。宏的其他缺点：不能overload和限制作用域（undef除外）
	* 分支预测
		* 应用场景
		* 关键因素
		* 常见的优化手段
			* 1. 消除条件分支
			* 2. 循环展开
			* 3. 边界检查
			* 4. 使用数组
			* 5. 整形的 bit array 语义，适用于 enum、const、define
		* 本块小结
			* 尽可能的减少跳转和分支
			* 优先使用迭代而不是递归
			* 对于长的if...else，使用switch case，以减少后面条件的判断，把最容易出现的条件放在最前面
			* 为小函数使用inline，减少函数调用开销
			* 在函数内使用循环
			* 在跳转之间的代码尽量减少数据依赖
			* 尝试展开循环
			* 尝试通过计算来消除分支
* [每个C++工程师都要了解的十个性能陷阱](https://mp.weixin.qq.com/s/UW2Ual0v21KNQz60MHT1nQ)
	* 本文介绍的性能陷阱主要分为两大类：“有成本抽象”和“与编译器作对”。前者是指在使用 C++的功能/库时需要注意的隐形成本，后者则是一些 C++新手可能会写出不利于编译器优化的代码。另外本文的顺序是由基础到进阶，读者可以根据目录直接跳到自己想看的部分。
	* 有成本抽象
		* （一）虚函数
		* （二）隐形的拷贝
			* Member Initialization 构造函数
			* For 循环
			* Lambda 捕获
			* 隐式类型转换
		* （三）隐形的析构
			* 复杂类型的析构
			* 平凡析构类型
		* （四）滥用 std::shared_ptr
		* （五）类型擦除：std::function 和 std::any
		* （六）std::variant 和 std::optional
		* （七）std::async
			* 不指定 policy
			* 不保存返回值
	* 与编译器作对
		* （八）返回值优化 NRVO（Named Return Value Optimization)
			* 滥用 std::move
			* 工厂返回 std::optional
		* （九）尾递归优化
		* （十）自动向量化优化
* [编译器的优化真是太难了！](https://mp.weixin.qq.com/s/kWW6EeZbZRo6nel8CVy2Qg)

### Testing

* [有哪些好用的代码检查工具](https://mp.weixin.qq.com/s/lcIS5Krv2-Sus9pDYF7DAw)
	* https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis#C,_C++
	* https://github.com/chengxumiaodaren/cpp-learning
![image](https://user-images.githubusercontent.com/34557994/203918278-fe57db3c-5cae-42c3-9e8b-5154c1323d47.png)
* clangd
	* [What is clangd?](https://clangd.llvm.org/)
		* clangd understands your C++ code and adds smart features to your editor: code completion, compile errors, go-to-definition and more.
		* clangd is a language server that can work with many editors via a plugin. Here’s Visual Studio Code with the clangd plugin, demonstrating code completion:
		* clangd is based on the Clang C++ compiler, and is part of the LLVM project.
	* [clangd - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.vscode-clangd)
* [c-cpp/学习笔记之Catch2 at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BCatch2)
* [C++ 单元测试与代码覆盖率](https://mp.weixin.qq.com/s/QV62sN4ILPGk4Ko-a0ZsfA)
  * 本文以C++语言为基础，讲解如何进行单元测试并生成测试报告。
  * 在工具上，我们会使用下面这些：
    * GCC
    * CMake
    * Google Test
    * gcov
    * lcov
* [现代C++测试工具链(是时候抛弃gtest/google bench了)](https://mp.weixin.qq.com/s/fmcUmH-AEUFO9mIMDJRX7g)
	* http://www.purecpp.org/detail?id=2291
	* gtest的问题
		* gtest需要安装有时候带来很多不方便，比如需要经常切换gcc和clang的时候就比较麻烦，安装的gtest可能在另一个编译器下编译不过, 编写跨平台程序的时候需要多次安装gtest，非常不便。另外一个问题是网络原因，下载安装gtest或者git上拉gtest都可能因为网络原因失败。
	* 现代C++ unit test库
		* 除了gtest之外，还有很多轻量级易用的单元测试库，比如doctest和catch，相比gtest需要编译/安装，他们都是header only的，直接包含到工程里就可以做单元测试了，portable又没有任何依赖，而且对编译器版本要求也不高，只需要C++11就行了，用了之后只有一个字：爽！
		* 这里推荐使用[doctest](https://github.com/doctest/doctest)，原因是[它的性能比catch更好](https://github.com/doctest/doctest/blob/master/doc/markdown/benchmarks.md)，当然也比gtest好, 来看看doctest怎么用的吧。
	* doctest基本用法
	* doctest的断言宏
	* 现代C++ mock库
		* [FakeIt](https://github.com/eranpeer/FakeIt)是C++11写的header only的mock库，用起来也很方便：
	* 现代C++ benchmark库
		* [nanobench](https://github.com/martinus/nanobench)也是C++11写的header only的库，使用起来也很简单，包含头文件即可。
	* 总结
		* 用现代C++测试工具链：doctest+FakeIt+nanobench, 可以完美地替代gtest/gmock和google bench，没有任何依赖，无需安装，直接包含头文件就可以用，非常容易集成和使用，是时候抛弃google test和google bench了!

## Application

* [简单的生成Email的C++程序 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/archive/2010/10/26/1860900.html)
* [C++控制台打飞机小游戏 | CSDN 博文精选](https://mp.weixin.qq.com/s/ML7bm89cBwkLVpyPt1dmkg)
  * https://blog.csdn.net/C20190102/article/details/102727963

### FINANCE

#### QUANT

* [rburkholder/trade-frame: C++ 17 based library (with sample applications) for testing equities, futures, etfs & options based automated trading ideas using DTN IQFeed real time data feed and Interactive Brokers (IB TWS API) for trade execution. [I have a private repository which has more recent changes, which get back-ported randomly][irc: #tradeframe on OFTC]](https://github.com/rburkholder/trade-frame)
* [Building a Market Data Feed with Liquibook | Object Computing, Inc.](https://objectcomputing.com/resources/publications/sett/august-2013-building-a-market-data-feed-with-liquibook)
* How to build a order book ?
	* https://www.google.com/search?q=c%2B%2B+order+book+implementation&oq=c%2B%2B+order+book&aqs=edge.1.69i57j0i512j0i22i30l2j0i390l3.13525j0j1&sourceid=chrome&ie=UTF-8#scso=_TI-5Yt2ZPMPTz7sP5q6-8Ao27:740.9090576171875
	* https://github.com/bigfatwhale/orderbook
	* https://alexabosi.wordpress.com/2014/08/28/limit-order-book-implementation-for-low-latency-trading-in-c/
	* https://quant.stackexchange.com/questions/3783/what-is-an-efficient-data-structure-to-model-order-book
	* https://web.archive.org/web/20110219163448/http://howtohft.wordpress.com/2011/02/15/how-to-build-a-fast-limit-order-book/
	* https://github.com/charles-cooper/itch-order-book
	* https://www.google.com/search?q=c%2B%2B+tse+order+book&sxsrf=ALiCzsbmZMhBQv6SNPDcogDsFVIRhTLY-A%3A1656329814805&ei=Vpa5YuviMIjSz7sPoZ2G6AQ&ved=0ahUKEwjr5fexxc34AhUI6XMBHaGOAU0Q4dUDCA4&uact=5&oq=c%2B%2B+tse+order+book&gs_lcp=Cgdnd3Mtd2l6EAM6BwgAEEcQsANKBAhBGABKBAhGGABQxQpYrRFgwxRoAXABeACAAdABiAG_BZIBBTAuMy4xmAEAoAEByAEIwAEB&sclient=gws-wiz#scso=_bJa5YvmuMoGq4t4PltaniA822:0
	* https://objectcomputing.com/resources/publications/sett/august-2013-building-a-market-data-feed-with-liquibook
	* https://www.youtube.com/watch?v=fxN4xEZvrxI
	* https://github.com/olibre/Cpp14-OrderBook
	* https://github.com/topics/order-book?o=desc&s=forks

## FAQ

* How to execute command and get output ?
  * [process - How do I execute a command and get the output of the command within C++ using POSIX? - Stack Overflow](https://stackoverflow.com/questions/478898/how-do-i-execute-a-command-and-get-the-output-of-the-command-within-c-using-po)
  * [system - C++ Reference](https://www.cplusplus.com/reference/cstdlib/system/)
    * Execute system command
      * Invokes the command processor to execute a command.
      * If command is a null pointer, the function only checks whether a command processor is available through this function, without invoking any command.
      * The effects of invoking a command depend on the system and library implementation, and may cause a program to behave in a non-standard manner or to terminate.
  * [std::unique_ptr - cppreference.com](https://en.cppreference.com/w/cpp/memory/unique_ptr)
```c++
#include <cstdio>
#include <iostream>
#include <memory>
#include <stdexcept>
#include <string>
#include <array>

std::string exec(const char* cmd) {
    std::array<char, 128> buffer;
    std::string result;
    std::unique_ptr<FILE, decltype(&pclose)> pipe(popen(cmd, "r"), pclose);
    if (!pipe) {
        throw std::runtime_error("popen() failed!");
    }
    while (fgets(buffer.data(), buffer.size(), pipe.get()) != nullptr) {
        result += buffer.data();
    }
    return result;
}
```
* [What are Forward declarations in C++ - GeeksforGeeks](https://www.geeksforgeeks.org/what-are-forward-declarations-in-c/)
	* Forward Declaration refers to the beforehand declaration of the syntax or signature of an identifier, variable, function, class, etc. prior to its usage (done later in the program).
	* [c++ forward declaration of a static class member - Stack Overflow](https://stackoverflow.com/questions/15806331/c-forward-declaration-of-a-static-class-member)
		* No, you can't. You can either include the header in the header, or separate the implementation Use::f in an implementation file and include M's header there.
	* [Enum.7: Specify the underlying type of an enumeration only when necessary](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#enum7-specify-the-underlying-type-of-an-enumeration-only-when-necessary)
		* Reason: The default is the easiest to read and write. int is the default integer type. int is compatible with C enums.
		* Note: Specifying the underlying type is necessary in forward declarations of enumerations
* How to set Product Version of .dll files?
	* MSVS > Project *** > Resource Files > ***.rc > Version > VS_VERSION_INFO > ProductVersion
* How to encrypt DLL files ?
	* [开发笔记：如何对【动态链接库】文件进行加密保护？](https://mp.weixin.qq.com/s/cXDoaiuo5cUpxyNEcpzEGQ)
		* 1.写一个小工具软件，对 DLL 文件进行加密
		* 2.修改应用程序，对加密的 DLL 文件进行解密
		* 3.把加密的 DLL 文件解密到内存缓冲区中
		* 4. Linux 操作系统怎么办？
* [zlib](https://zlib.net/) ?
    * Zlib is a widely used software library that provides data compression services, designed to be portable and efficient both in terms of memory and speed. Its versatility and free availability make it a popular choice for compression and decompression tasks in various software applications. Here’s an overview of zlib, including its key features, typical uses, and integration methods.
    * Key Features of Zlib
        * Compression and Decompression: Zlib supports the Deflate compression algorithm, which is a combination of the LZ77 algorithm and Huffman coding. It provides a good balance between compression ratio and speed and is used in numerous formats, including PNG and ZIP.
        * Portability: Written in C, zlib is highly portable and can be compiled on virtually any platform, including all major operating systems like Linux, Windows, and macOS.
        * Performance: It offers fast compression and decompression speeds with a very reasonable memory footprint, making it suitable for performance-critical applications.
        * Flexibility: Zlib can be used at varying levels of compression, from very fast compression to very high ratios, depending on the requirements of the application.
        * Stability and Reliability: Zlib is mature and stable, having been developed and refined over many years.
    * Common Uses of Zlib
        * File Compression: Creating compressed archives in ZIP format.
        * Data Transmission: Compressing data for transmission over networks, especially where bandwidth is limited.
        * Embedded Systems: Due to its compact size and efficiency, it is often used in embedded systems for data compression.
        * Image Compression: Used in PNG image compression as part of the standard PNG specification.
        * Database Compression: Some database systems use zlib to compress data stored on disk.
    * How to Integrate Zlib in Projects
        * Integrating zlib into your project involves including its library and headers in your build environment and linking against the zlib library. Here’s how to do it in a general C or C++ project:
        * Installation
            * Linux: Install zlib using package managers like apt for Debian-based systems or yum for RedHat-based systems.
                ```bash
                sudo apt-get install zlib1g-dev  # Debian, Ubuntu
                sudo yum install zlib-devel     # RedHat, CentOS
                ```
            * Windows: Download the precompiled DLL and header files or build from source using MinGW or Visual Studio.
            * macOS: Typically pre-installed, but can be updated or reinstalled via Homebrew if needed.
                ```bash
                brew install zlib
                ```
        * Example C Code
            * Here’s a simple example of using zlib to compress and decompress a string in C:
            ```c
            #include <stdio.h>
            #include <string.h>
            #include <assert.h>
            #include <zlib.h>
            
            int main() {
                char *orig = "Text to be compressed";
                char comp[1024];
                char decomp[1024];
            
                uLong orig_size = strlen(orig) + 1; // Include the null terminator
                uLong comp_size = sizeof(comp);
            
                // Compress the string
                int comp_status = compress((Bytef *)comp, &comp_size, (const Bytef *)orig, orig_size);
                assert(comp_status == Z_OK);
            
                // Decompress the string
                uLong decomp_size = sizeof(decomp);
                int decomp_status = uncompress((Bytef *)decomp, &decomp_size, (const Bytef *)comp, comp_size);
                assert(decomp_status == Z_OK);
            
                printf("Original: %s\n", orig);
                printf("Decompressed: %s\n", decomp);
            
                return 0;
            }
            ```
    * Conclusion
        * Zlib continues to be a highly valuable resource for developers needing efficient compression and decompression capabilities in their software. Its ease of use, combined with its performance characteristics, makes it suitable for a wide range of applications from simple utility scripts to complex, high-performance applications. Whether you’re developing for web, desktop, or embedded environments, zlib provides a robust solution for your data compression needs.

### ERROR

* How to fix `error C1853: '.pch' precompiled header file is from a previous version of the compiler, or the precompiled header is C++ and you are using it from C (or vice versa)` ?
	* Rebuild All
* How to fix `error C2275: 'std::pair<int,double>::first_type': expected an expression instead of a type`?
    * add `typename`
```c++
template <typename Container>
static void construct(PyObject* object, boost::python::converter::rvalue_from_python_stage1_data* data)
{
    PyObject *first  = PyTuple_GET_ITEM(object, 0);
    PyObject *second = PyTuple_GET_ITEM(object, 1);
    void *storage = ((boost::python::converter::rvalue_from_python_storage<Container >*) data)->storage.bytes;

	new (storage) Container(boost::python::extract<Container::first_type>(first),
                            boost::python::extract<Container::second_type>(second));

	//new (storage) Container(boost::python::extract<typename Container::first_type>(first), 
	//                          boost::python::extract<typename Container::second_type>(second));

    data->convertible = storage;
}
```
* How to fix `Warning C26455 Default constructor should not throw. Declare it 'noexcept'`?
    * https://learn.microsoft.com/en-us/cpp/code-quality/c26455?view=msvc-170#Overview
    * The C++ Core Guidelines suggest that default constructors shouldn't do anything that can throw. When the default constructor can throw, all code that relies on a properly instantiated object may also throw.
    * Remarks
        * Consider the default constructors of the STL types, like `std::vector`. In these implementations, the default constructors initialize internal state without making allocations. In the `std::vector` case, the size is set to 0 and the internal pointer is set to `nullptr`. The same pattern should be followed for all default constructors.
        * Code analysis name: `DEFAULT_CTOR_NOEXCEPT`
* How to fix `Compiler error C2653: not a class or namespace name` ?
	* Generate full list of includes files to see include stack
		* MSVS > Property > C/C++ > Advanced > Show Includes > Yes
	* Fix circular dependency in header files. Need to look into the included header files as well.
	* [c++ - Compiler error C2653: not a class or namespace name - Stack Overflow](https://stackoverflow.com/questions/15740952/compiler-error-c2653-not-a-class-or-namespace-name)
		* You have a circular dependency in your headers. BaseEntity.h includes Input.h, which includes ScreenSystem.h, which includes GameScreen.h, which in turn re-includes BaseEntity.h. This leads to class names appearing before they are declared, causing compilation failure.
		* To avoid this, do not include headers unnecessarily. 
	* [c# - What is a circular dependency and how can I solve it? - Stack Overflow](https://stackoverflow.com/questions/38042130/what-is-a-circular-dependency-and-how-can-i-solve-it)
* How to fix `lint message lnt-accidental-copy 'auto' doesn't deduce references` ?
    * [lnt-accidental-copy | Microsoft Learn](https://learn.microsoft.com/en-us/cpp/ide/lnt-accidental-copy?view=msvc-170)
        * A copy is being made because `auto` doesn't deduce references.
        * Variables declared by using `auto` are never deduced to be type references. If you initialize an `auto` variable from the result of a function that returns by reference, it results in a copy. Sometimes this effect is desirable, but in many cases it causes an unintentional copy.
        * The `lnt-accidental-copy` check is controlled by the Accidental Copy setting in the C/C++ Code Style options. For information on how to change this setting, see [Configure the linter](https://learn.microsoft.com/en-us/cpp/ide/cpp-linter-overview?view=msvc-170#configure-the-linter).
        * Examples
        ```c++
        #include <string>
        #include <vector>
        
        std::string& return_by_ref();
        
        int& return_int_by_ref();
        
        void accidental_copy(std::vector<std::string>& strings)
        {
            for (auto s : strings) {} // Flagged: A new copy of each string is
                                      // made when the vector is iterated.
        
            auto s = return_by_ref(); // Flagged: the function returns by-reference
                                      // but a copy is made to initialize 's'.
        
            auto i = return_int_by_ref(); // Not flagged because no copy constructor is called.
        }
        ```
        * How to fix the issue
            * The fix the linter suggests is to change `auto` to `auto&` on the declaration.
            ```C++
            #include <string>
            
            std::string& return_by_ref();
            
            void accidental_copy(std::vector<std::string>& strings)
            {
                for (auto& s : strings) {}
            
                auto& s = return_by_ref();
            }
            ```
        * Remarks
            * The suggested fix isn't safe to apply in all cases. The fix may cause a compilation error or change the behavior of the code. It's important to understand how the suggested fix affects the code before applying it.
            * In cases where a temporary is returned, `const auto&` is necessary to prevent a compilation error. In this case, it may be preferable to continue to use `auto`.
            * Sometimes a copy is intentional, such as when you want to modify the copy without affecting the source instance, as shown in this example.
            ```C++
            void modifies_string(std::string& s);
            
            void example(std::vector<std::string>& strings)
            {
                for (auto s : strings) {
                    modifies_string(s);    // In this case, the copy may be intended so that
                                           // the original strings are not modified.
                }
            }
            ```
* How to fix `LNK1104: cannot open file 'libboost_log-vc142-mt-x32-1_72.lib'` when building project in MSVS ?
  * check the path, e.g. "BOOST_ROOT", in system enviroment variable to see if "\\" is appended at the end, e.g. C:\Program Files\boost\boost_1_72_0\
* How to fix `error LNK2019: unresolved external symbol "char * __stdcall _com_util::ConvertBSTRToString(wchar_t *)" (?ConvertBSTRToString@_com_util@@YGPADPA_W@Z) referenced in function "public: char const * __thiscall _bstr_t::Data_t::GetString(void)const " (?GetString@Data_t@_bstr_t@@QBEPBDXZ)` when #include \<comutil.h>?
  * Append "comsuppw.lib" to MSVS > Project Property > Linker > Input
  * [error LNK2019 related to ConvertStringToBSTR](https://social.microsoft.com/Forums/windows/he-IL/8e2b44f4-3884-445c-9da9-e6abb2783b4c/error-lnk2019-related-to-convertstringtobstr?forum=Vsexpressvc)
  * [ConvertStringToBSTR | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/convertstringtobstr?redirectedfrom=MSDN&view=msvc-160)
* How to fix `error LNK2019: unresolved external symbol __imp__UuidCreate@4` ?
	* Under Project menu, open <project name> Properties -> Configuration Properties -> Linker -> Command Line. Type Rpcrt4.lib into the Additional Options box.
	* [How to Link with .lib file -- UuidCreate()](https://forums.codeguru.com/showthread.php?448070-How-to-Link-with-lib-file-UuidCreate())
* Error `LNK2019: unresolved external symbol deflate referenced in function` ?
    * The error `LNK2019: unresolved external symbol deflate referenced in function` suggests that the linker is unable to find the definition for the deflate function, which is a part of the zlib compression library. This typically occurs during the linking stage of building a C++ application that uses zlib for compression tasks. Here’s how to resolve this linker error step by step:
        * Step 1: Verify zlib Inclusion
            * Ensure that zlib is properly included in your project. This means:
                * Including zlib Headers: You must include the zlib headers in your source files where you use zlib functions like deflate. Typically, you include it with:
                    * `#include <zlib.h>`
        * Step 2: Link against the zlib Library
            * The most common cause for this error is not linking against the zlib library correctly. You need to ensure that the zlib library (usually named zlib.lib or zlibstatic.lib on Windows) is linked in your project.
            * For Visual Studio:
                * Open the project properties by right-clicking on the project in Solution Explorer and selecting Properties.
                * Go to Linker -> Input -> Additional Dependencies and add zlib.lib or the appropriate library file for zlib.
                * Make sure that the path to the zlib library file is included in Linker -> General -> Additional Library Directories.
            * For a CMake Project:
                * Add the following in your CMakeLists.txt file:
                ```cmake
                find_package(ZLIB REQUIRED)
                if (ZLIB_FOUND)
                  include_directories(${ZLIB_INCLUDE_DIRS})
                  target_link_libraries(YourProjectName ${ZLIB_LIBRARIES})
                endif()
                ```
                * This script automatically handles finding and linking zlib, but ensure that CMake can find zlib (you might need to set ZLIB_ROOT as an environment variable or pass it as a CMake variable).
        * Step 3: Ensure Correct Library Path
            * Check that the path to zlib's library file (zlib.lib or similar) is correctly set in your project's settings. This path needs to be accessible to the linker.
        * Step 4: Rebuild the Project
            * After ensuring that zlib's headers are included and its library is linked, rebuild your project to see if the issue persists.
        * Step 5: Check the Library Version
            * Make sure that the zlib library version is compatible with your application. If you are linking against an old or incompatible version of zlib, it might lead to linking errors.
        * Step 6: Dependency on the Order of Linking
            * Sometimes the order in which libraries are linked can cause issues. Ensure zlib is linked after any dependent libraries in your linker settings.
        * Step 7: Static vs. Dynamic Linking
            * Consider whether you are linking statically or dynamically:
                * If you are using a static library (.lib), ensure that all dependent settings are configured for static linking.
                * If you are using a dynamic library (.dll), ensure that the corresponding .lib file is used during linking, and the .dll is available in your application’s runtime path.
    * Conclusion
        * Resolving the `LNK2019` error related to zlib involves ensuring that you have correctly included zlib's headers, linked against its library, and configured your project's library paths properly. Following these steps should help you effectively integrate zlib into your Windows-based C++ projects.
* How to fix `warning LNK4075: ignoring '/INCREMENTAL' due to '/OPT:ICF' specification` ?
  * Change default to below values in MSVS > Your project property > Linker > Optimization :
    * References = Keep Unreferenced Data (/OPT:NOREF)
    * Enable COMDAT Folding = Do Not Remove Redundant COMDATs (/OPT:NOICF)
  * [c++ - LNK4075: ignoring '/EDITANDCONTINUE' due to '/OPT:ICF' specification - Stack Overflow](https://stackoverflow.com/questions/1574367/lnk4075-ignoring-editandcontinue-due-to-opticf-specification)
  * [Linker Tools Warning LNK4075 | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/error-messages/tool-errors/linker-tools-warning-lnk4075?view=msvc-160)
* How to fix warning `control reaches end of non-void function -wreturn-type` ?
	* [c++ - control reaches end of non-void functions -wreturn-type - Stack Overflow](https://stackoverflow.com/questions/60863967/control-reaches-end-of-non-void-functions-wreturn-type)
	* check the conditions of return statement. Return statement is not executed under all conditions.
* How to fix compile error `fatal error: google/protobuf/stubs/common.h: No such file or directory` ?
	* `g++ -I /path_to_protobuf/`
	* [protocol buffers - protobuf common.h "No such file" - Stack Overflow](https://stackoverflow.com/questions/32039549/protobuf-common-h-no-such-file)
* How to fix compile error `has initializer but incomplete type` ?
	* `#include <sstream>`
	* [compilation - C++ compile error: has initializer but incomplete type - Stack Overflow](https://stackoverflow.com/questions/13428164/c-compile-error-has-initializer-but-incomplete-type)
* How to fix compile error `c - Undefined reference to pthread_create` ?
	* `gcc -pthread -o term term.c`
	* [c - Undefined reference to pthread_create in Linux - Stack Overflow](https://stackoverflow.com/questions/1662909/undefined-reference-to-pthread-create-in-linux)
* How to fix compile error `undefined reference to utils::FileUtils::func()` ?
	* check .cpp if FileUtils::func() exists
	* for template function, move the definition to .h
		* [c++ - undefined reference to template function - Stack Overflow](https://stackoverflow.com/questions/10632251/undefined-reference-to-template-function)
	* for inline function, move the definition to .h
		* [C++ inline resulted in undefined reference - Stack Overflow](https://stackoverflow.com/questions/32739086/c-inline-resulted-in-undefined-reference)
			* Inlines must be defined in the same translation unit where they are used. By defining your "inline" function in the .cpp file, it is only usable in the same .cpp file. You need to move it either to the header file, or some special "inlines" file that some projects prefer to keep their implementation details a bit more hidden (you'd then #include that inlines file, either in your header or in main.cpp).
		* [inline - C++ inlining class methods causes undefined reference - Stack Overflow](https://stackoverflow.com/questions/4769479/c-inlining-class-methods-causes-undefined-reference)
			* The body of an inline function needs to be in the header so that the compiler can actually substitute it wherever required. 
* How to fix compile error `error: unterminated #ifdef` ?
	* add missing `#endif`
* How to fix link error `undefined reference to 'std::filesystem::__cxx11::directory_iterator::operator*() const` ?
	* It need to add `-lstdc++fs` to option.
		* `g++ -lstdc++fs -std=c++17 -o fs fs.cpp -lstdc++fs`
	* [c++ - std::filesystem link error on ubuntu 18.10 - Stack Overflow](https://stackoverflow.com/questions/53852684/stdfilesystem-link-error-on-ubuntu-18-10) 
* How to fix error `**Cannot evaluate function -- may be inlined**` ?
	* [c++ - Cannot evaluate function -- may be inlined - Stack Overflow](https://stackoverflow.com/questions/22163730/cannot-evaluate-function-may-be-inlined)
* linux error `undefined reference to dlopen`?
    * The error undefined reference to 'dlopen' that you're encountering on Linux typically arises during the linking phase of compiling a program that uses the dlopen function from the Dynamic Loading API. This function is part of the libdl library, which provides mechanisms to dynamically load libraries at runtime.
    * What is dlopen?
        * dlopen is used to dynamically load a shared library into the application and retrieve a handle that can be used with other dl functions (dlsym, dlclose, etc.). This is particularly useful for applications that need to extend their functionality dynamically or need to choose at runtime which libraries to use.
    * How to Resolve the Error
        * To fix this linking error, you need to ensure that the linker is instructed to link against libdl. Here's how to do it:
        * Using the GCC Compiler
            * When compiling your program, you need to add -ldl to your GCC command line. This tells GCC to link your program with the libdl library, which contains the implementation for dlopen and other dynamic loading functions.
            * Here's an example command for compiling a C program that uses dlopen:
            ```sh
            gcc -o my_program my_program.c -ldl
            ```
            * This command compiles my_program.c into an executable my_program and links it with the libdl library to resolve the dlopen function reference.
    * Example Code Using dlopen
        * Here's a very simple example of using dlopen in a C program:
        ```c
        #include <stdio.h>
        #include <dlfcn.h>
        
        int main() {
            void* handle = dlopen("libm.so.6", RTLD_LAZY);
            if (!handle) {
                fprintf(stderr, "Error opening library: %s\n", dlerror());
                return 1;
            }
        
            dlclose(handle);
            return 0;
        }
        ```
    * Compile and Run the Example
        * To compile the above program, use the following command:
        ```sh
        gcc -o dynamic_loader_example dynamic_loader_example.c -ldl
        ```
        * This will produce an executable named dynamic_loader_example that when run, attempts to dynamically load the math library (libm.so.6). Make sure you change "libm.so.6" to a library that exists on your system if it's different.
    * Common Mistakes and Considerations
        * Order of Linker Flags: Make sure that the -ldl flag comes after the source files and other flags that might generate or require linking. The order of parameters in GCC can affect the linking process.
        * Conditional Use: If your software needs to compile on systems where libdl is not necessary (like BSD systems where the dlopen functionality is part of the standard C library), you may need to conditionally compile/link this library. This can be managed using preprocessor directives or build system conditions.
        * Check Library Paths: On some systems, library paths or names might be different, or additional configuration might be required to locate the libdl library.
    * By following these guidelines, you should be able to resolve the `undefined reference to 'dlopen'` error and successfully compile and link your applications that use dynamic loading APIs on Linux.

# END
