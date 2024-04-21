# 学习笔记之Boost

* [Boost C++ Libraries](https://www.boost.org/)
    * Boost provides free peer-reviewed portable C++ source libraries.
    * [Boost Getting Started on Windows - 1.77.0](https://www.boost.org/doc/libs/1_77_0/more/getting_started/windows.html)
    * [Boost Downloads](https://www.boost.org/users/download/)
    * [Boost Libraries - 1.85.0](https://www.boost.org/doc/libs/1_85_0/libs/libraries.htm)
    * [Invocation](https://www.boost.org/build/doc/html/bbv2/overview/invocation.html)
* [c++ - How do you build the x64 Boost libraries on Windows? - Stack Overflow](https://stackoverflow.com/questions/302208/how-do-you-build-the-x64-boost-libraries-on-windows/302257)
```sh
b2 --build-dir=build/x64 address-model=64 threading=multi --build-type=complete --stagedir=./stage/x64
```
* [Building Boost 32-bit and 64-bit libraries on Windows](http://informilabs.com/building-boost-32-bit-and-64-bit-libraries-on-windows/)
```sh
cd \where_i_extracted_boost\  
bootstrap.bat  
b2 --build-dir=build/x86 address-model=32 threading=multi --build-type=complete --stagedir=./stage/x86 --toolset=msvc-14.0 -j 12  
b2 --build-dir=build/x64 address-model=64 threading=multi --build-type=complete --stagedir=./stage/x64 --toolset=msvc-14.0 -j 12  
```

## [Boost.Interprocess - 1.77.0](https://www.boost.org/doc/libs/1_77_0/doc/html/interprocess.html)

* [Sharing memory between processes - 1.77.0](https://www.boost.org/doc/libs/1_77_0/doc/html/interprocess/sharedmemorybetweenprocesses.html)
    * What is shared memory?
        * Shared memory is the fastest interprocess communication mechanism. The operating system maps a memory segment in the address space of several processes, so that several processes can read and write in that memory segment without calling operating system functions. However, we need some kind of synchronization between processes that read and write shared memory.
        * Consider what happens when a server process wants to send an HTML file to a client process that resides in the same machine using network mechanisms:
            * The server must read the file to memory and pass it to the network functions, that copy that memory to the OS's internal memory.
            * The client uses the network functions to copy the data from the OS's internal memory to its own memory.
        * As we can see, there are two copies, one from memory to the network and another one from the network to memory. And those copies are made using operating system calls that normally are expensive. Shared memory avoids this overhead, but we need to synchronize both processes:
            * The server maps a shared memory in its address space and also gets access to a synchronization mechanism. The server obtains exclusive access to the memory using the synchronization mechanism and copies the file to memory.
            * The client maps the shared memory in its address space. Waits until the server releases the exclusive access and uses the data.
        * Using shared memory, we can avoid two data copies, but we have to synchronize the access to the shared memory segment.

## [Boost.Log v2 - 1.85.0](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/index.html)

### [Introduction](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/index.html#log.intro)

#### [How to read the documentation](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/index.html#log.intro.how_to_read)

* If this is your first experience with the library, it is recommended to read the [Design overview](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/design.html) section for a first glance at the library's capabilities and architecture. The [Installation](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/installation.html) and [Tutorial](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial.html) sections will help to get started experimenting with the library. The tutorial gives an overview of the library features with sample code snippets. Some tutorial steps are presented in two forms: simple and advanced. The simple form typically describes the most common and easy way to do the task and it is being recommended to be read by new users. The advanced form usually gives an expanded way to do the same thing but with an in-depth explanation and the ability to do some extra customization. This form may come in handy for more experienced users and should generally be read if the easy way does not satisfy your needs.
* Besides the tutorial there is a [Detailed features description](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/detailed.html) chapter. This part describes other tools provided by the library that were not covered by the tutorial. This chapter is best read on a case by case basis.
* Last, but not least, there is a [Reference](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/reference.html) section which gives the formal description of library component interfaces.
* To keep the code snippets in this documentation simple, the following namespace aliases are assumed to be defined:
```c++
namespace logging = boost::log;
namespace sinks = boost::log::sinks;
namespace src = boost::log::sources;
namespace expr = boost::log::expressions;
namespace attrs = boost::log::attributes;
namespace keywords = boost::log::keywords;
```

### [Tutorial](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial.html)

* In this section we shall walk through the essential steps to get started with the library. After reading it you should be able to initialize the library and add logging to your application. The code of this tutorial is also available in examples residing in the libs/log/examples directory. Feel free to play with them, compile and see the result.

#### [Trivial logging](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial.html#log.tutorial.trivial)

```c++
#include <boost/log/trivial.hpp>

int main(int, char*[])
{
    BOOST_LOG_TRIVIAL(trace) << "A trace severity message";
    BOOST_LOG_TRIVIAL(debug) << "A debug severity message";
    BOOST_LOG_TRIVIAL(info) << "An informational severity message";
    BOOST_LOG_TRIVIAL(warning) << "A warning severity message";
    BOOST_LOG_TRIVIAL(error) << "An error severity message";
    BOOST_LOG_TRIVIAL(fatal) << "A fatal severity message";

    return 0;
}
```

#### [Trivial logging with filters](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/trivial_filtering.html)

#### [Setting up sinks](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/sinks.html)

#### [Creating loggers and writing logs](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/sources.html)

#### [Adding more information to log: Attributes](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/attributes.html)

#### [Log record formatting](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/formatters.html)

#### [Filtering revisited](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/advanced_filtering.html)

#### [Wide character logging](https://www.boost.org/doc/libs/1_85_0/libs/log/doc/html/log/tutorial/wide_char.html)

## [Boost.Python - 1.76.0](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/index.html)

* Welcome to Boost.Python, a C++ library which enables seamless interoperability between C++ and the Python programming language. The library includes support for:
    * References and Pointers
    * Globally Registered Type Coercions
    * Automatic Cross-Module Type Conversions
    * Efficient Function Overloading
    * C++ to Python Exception Translation
    * Default Arguments
    * Keyword Arguments
    * Manipulating Python objects in C++
    * Exporting C++ Iterators as Python Iterators
    * Documentation Strings

### [Boost.Python Tutorial](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/tutorial/index.html)

#### [QuickStart](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/tutorial/index.html#tutorial.quickstart)

* The Boost Python Library is a framework for interfacing Python and C++. It allows you to quickly and seamlessly expose C++ classes functions and objects to Python, and vice-versa, using no special tools -- just your C++ compiler. It is designed to wrap C++ interfaces non-intrusively, so that you should not have to change the C++ code at all in order to wrap it, making Boost.Python ideal for exposing 3rd-party libraries to Python. The library's use of advanced metaprogramming techniques simplifies its syntax for users, so that wrapping code takes on the look of a kind of declarative interface definition language (IDL).

##### Hello World

* Following C/C++ tradition, let's start with the "hello, world". A C++ Function:
```c++
char const* greet()
{
   return "hello, world";
}
```
* can be exposed to Python by writing a Boost.Python wrapper:
```c++
#include <boost/python.hpp>

BOOST_PYTHON_MODULE(hello_ext)
{
    using namespace boost::python;
    def("greet", greet);
}
```
* That's it. We're done. We can now build this as a shared library. The resulting DLL is now visible to Python. Here's a sample Python session:
```python
>>> import hello_ext
>>> print hello_ext.greet()
hello, world
```

##### MISC

* `BOOST_PYTHON_MODULE` ?
    * `BOOST_PYTHON_MODULE` is a macro provided by the boost.python library that simplifies the process of exporting C++ code to Python. It defines a module initializer function that creates a new Python module and registers functions, classes, and other objects defined in C++ to be accessible from Python.
    * Here is an example of using `BOOST_PYTHON_MODULE` to define a simple Python module that exposes a single C++ function:
    ```c++
    #include <boost/python.hpp>

    int add(int x, int y) {
        return x + y;
    }

    BOOST_PYTHON_MODULE(example) {
        using namespace boost::python;
        def("add", add);
    }
    ```
    * In this example, the `BOOST_PYTHON_MODULE` macro defines the `initexample()` function, which is the module initializer for the example module. Inside the `initexample()` function, the `def()` function is used to register the `add()` function, allowing it to be called from Python with the same name.
    * To use this module in Python, simply compile the C++ code into a shared library and import it like any other Python module:
    ```python
    import example

    print(example.add(2, 3))  # Output: 5
    ```
    * Note that `BOOST_PYTHON_MODULE` takes the name of the module as an argument, which determines the name of the shared library and the name that must be used when importing the module in Python.
    * In addition to functions, `BOOST_PYTHON_MODULE` can also be used to export classes, namespaces, constants, and other objects to Python. It provides a simple and flexible way to create custom Python modules that leverage the power and performance of C++.

#### [Functions](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/tutorial/tutorial/functions.html)

* In this chapter, we'll look at Boost.Python powered functions in closer detail. We will see some facilities to make exposing C++ functions to Python safe from potential pifalls such as dangling pointers and references. We will also see facilities that will make it even easier for us to expose C++ functions that take advantage of C++ features such as overloading and default arguments.

##### [Auto-Overloading](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/tutorial/tutorial/functions.html#tutorial.functions.auto_overloading)

* It was mentioned in passing in the previous section that `BOOST_PYTHON_FUNCTION_OVERLOADS` and `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` can also be used for overloaded functions and member functions with a common sequence of initial arguments. Here is an example:
```c++
void foo()
{
   /*...*/
}

void foo(bool a)
{
   /*...*/
}

void foo(bool a, int b)
{
   /*...*/
}

void foo(bool a, int b, char c)
{
   /*...*/
}
```
* Like in the previous section, we can generate thin wrappers for these overloaded functions in one-shot:
    * `BOOST_PYTHON_FUNCTION_OVERLOADS(foo_overloads, foo, 0, 3)`
* Then...
    * `.def("foo", (void(*)(bool, int, char))0, foo_overloads());`
* Notice though that we have a situation now where we have a minimum of zero (0) arguments and a maximum of 3 arguments.

###### MISC

* `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` v.s. `BOOST_PYTHON_FUNCTION_OVERLOADS` ?
    * Both `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` and `BOOST_PYTHON_FUNCTION_OVERLOADS` are macros in boost.python used to define overloaded C++ functions for Python. However, they are used in different contexts.
    * `BOOST_PYTHON_FUNCTION_OVERLOADS` is used to define overloaded non-member functions, while `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` is used to define overloaded member functions of a class.
    * Here is an example of using `BOOST_PYTHON_FUNCTION_OVERLOADS` to define overloaded non-member functions:
    ```c++
    #include <boost/python.hpp>

    int add(int x, int y) {
        return x + y;
    }

    int add(int x, int y, int z) {
        return x + y + z;
    }

    BOOST_PYTHON_FUNCTION_OVERLOADS(add_overloads, add, 2, 3);

    BOOST_PYTHON_MODULE(example) {
        using namespace boost::python;
        def("add", add, add_overloads());
    }
    ```
    * In this example, the `add()` function is overloaded to accept either two or three arguments. `BOOST_PYTHON_FUNCTION_OVERLOADS` is used to define the overloads and their respective argument counts. The `add_overloads()` object is then passed to the `def()` function to expose the overloaded `add()` function to Python.
    * Now, here is an example of using `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` to define overloaded member functions of a class:
    ```c++
    #include <boost/python.hpp>

    class Rectangle {
    public:
        Rectangle(int w, int h) : width(w), height(h) {}
        int area() const { return width * height; }
        int perimeter() const { return 2 * (width + height); }
        int diagonal(int x, int y) const { return std::sqrt(x * x + y * y); }
    private:
        int width;
        int height;
    };

    BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS(Rectangle_diagonal_overloads, Rectangle::diagonal, 2, 3);

    BOOST_PYTHON_MODULE(example) {
        using namespace boost::python;
        class_<Rectangle>("Rectangle", init<int, int>())
            .def("area", &Rectangle::area)
            .def("perimeter", &Rectangle::perimeter)
            .def("diagonal", &Rectangle::diagonal, Rectangle_diagonal_overloads());
    }
    ```
    * In this example, the `diagonal()` member function of the Rectangle class is overloaded to accept either two or three arguments. `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` is used to define the overloads and their respective argument counts. The `Rectangle_diagonal_overloads()` object is then passed to the `.def()` member function of the Rectangle class to expose the overloaded `diagonal()` function to Python.
    * So, to summarize, `BOOST_PYTHON_FUNCTION_OVERLOADS` is used to define overloaded non-member functions, while `BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS` is used to define overloaded member functions of a class.

### [Boost.Python Reference Manual](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/index.html)

#### [2. High Level Components](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/high_level_components.html)

##### [boost/python/def.hpp](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/high_level_components/boost_python_def_hpp.html)

* def() is the function which can be used to expose C++ functions and callable objects as Python functions in the current scope.
* Example
```c++
#include <boost/python/def.hpp>
#include <boost/python/module.hpp>
#include <boost/python/args.hpp>

using namespace boost::python;

char const* foo(int x, int y) { return "foo"; }

BOOST_PYTHON_MODULE(def_test)
{
    def("foo", foo, args("x", "y"), "foo's docstring");
}
```

###### MISC

* `def()` v.s. `.def()` in boost.python ?
    * Both def() and .def() are functions used in boost.python to expose C++ functions to Python. However, they are used in different contexts.
    * The def() function is used to define a Python function that maps to a C++ function. It is typically used in the module definition to expose one or more C++ functions to Python. Here is an example:
    ```c++
    #include <boost/python.hpp>

    int add(int x, int y) {
        return x + y;
    }

    BOOST_PYTHON_MODULE(example) {
        using namespace boost::python;
        def("add", add);
    }
    ```
    * In this example, the def() function is used to define a Python function named add that maps to the C++ function add(). When the module is imported into Python, the add() function can be called like any other Python function.
    * On the other hand, the .def() member function is used to add methods to a class that is being exposed to Python. It is typically used inside the class_ definition to add one or more methods to the Python class. Here is an example:
    ```c++
    #include <boost/python.hpp>

    class Rectangle {
    public:
        Rectangle(int w, int h) : width(w), height(h) {}
        int area() const { return width * height; }
        int perimeter() const { return 2 * (width + height); }
    private:
        int width;
        int height;
    };

    BOOST_PYTHON_MODULE(example) {
        using namespace boost::python;
        class_<Rectangle>("Rectangle", init<int, int>())
            .def("area", &Rectangle::area)
            .def("perimeter", &Rectangle::perimeter);
    }
    ```
    * In this example, the .def() member function is used to add two methods, area() and perimeter(), to the Python class Rectangle. The first argument of .def() is the name of the method in Python, and the second argument is a pointer to the C++ method.
    * So, to summarize, def() is used to define Python functions that map to C++ functions, while .def() is used to add methods to a Python class that is defined in C++.

#### [4. Function Invocation and Creation](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/function_invocation_and_creation.html)

##### [boost/python/overloads.hpp](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/function_invocation_and_creation/boost_python_overloads_hpp.html#function_invocation_and_creation.boost_python_overloads_hpp.macros)

* Defines facilities for generating families of overloaded Python functions and extension class methods from C++ functions and member functions with default arguments, or from similar families of C++ overloads
* Example
```c++
#include <boost/python/module.hpp>
#include <boost/python/def.hpp>
#include <boost/python/args.hpp>
#include <boost/python/tuple.hpp>
#include <boost/python/class.hpp>
#include <boost/python/overloads.hpp>
#include <boost/python/return_internal_reference.hpp>

using namespace boost::python;

tuple f(int x = 1, double y = 4.25, char const* z = "wow")
{
    return make_tuple(x, y, z);
}

BOOST_PYTHON_FUNCTION_OVERLOADS(f_overloads, f, 0, 3)

struct Y {};
struct X
{
    Y& f(int x, double y = 4.25, char const* z = "wow")
    {
        return inner;
    }
    Y inner;
};

BOOST_PYTHON_MEMBER_FUNCTION_OVERLOADS(f_member_overloads, f, 1, 3)

BOOST_PYTHON_MODULE(args_ext)
{
    def("f", f,
        f_overloads(
            args("x", "y", "z"), "This is f's docstring"
        ));


    class_<Y>("Y")
        ;

    class_<X>("X", "This is X's docstring")
        .def("f1", &X::f,
                f_member_overloads(
                    args("x", "y", "z"), "f's docstring"
                )[return_internal_reference<>()]
        )
        ;
}
```

##### [Models of CallPolicies](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/function_invocation_and_creation/models_of_callpolicies.html#function_invocation_and_creation.models_of_callpolicies.boost_python_return_value_policy)
    
###### [boost/python/return_value_policy.hpp](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/function_invocation_and_creation/models_of_callpolicies.html#function_invocation_and_creation.models_of_callpolicies.boost_python_return_value_policy)

* return_value_policy instantiations are simply models of CallPolicies which are composed of a ResultConverterGenerator and optional Base CallPolicies.
* Example
    * C++ module definition:
    ```c++
    #include <boost/python/module.hpp>
    #include <boost/python/class.hpp>
    #include <boost/python/copy_const_reference.hpp>
    #include <boost/python/return_value_policy.hpp>

    // classes to wrap
    struct Bar { int x; }

    struct Foo {
       Foo(int x) : { b.x = x; }
       Bar const& get_bar() const { return b; }
     private:
       Bar b;
    };

    // Wrapper code
    using namespace boost::python;
    BOOST_PYTHON_MODULE(my_module)
    {
       class_<Bar>("Bar");

       class_<Foo>("Foo", init<int>())
          .def("get_bar", &Foo::get_bar
              , return_value_policy<copy_const_reference>())
          ;
    }
    ```
    * Python code:
    ```c++
    >>> from my_module import *
    >>> f = Foo(3)         # create a Foo object
    >>> b = f.get_bar()    # make a copy of the internal Bar object
    ```

#### [5. To/From Python Type Conversion](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/to_from_python_type_conversion.html)

##### [boost/python/extract.hpp](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/to_from_python_type_conversion.html#to_from_python_type_conversion.boost_python_extract_hpp)

* Exposes a mechanism for extracting C++ object values from generalized Python objects. Note that `extract<...>` can also be used to "downcast" an object to some specific ObjectWrapper. Because invoking a mutable python type with an argument of the same type (e.g. list([1,2]) typically makes a copy of the argument object, this may be the only way to access the ObjectWrapper's interface on the original object.

###### MISC

* `boost::python::extract` ?
    * `boost::python::extract` is a class template in the Boost.Python library that is used to extract a C++ object from a Python object. It provides a generic way to convert a Python object to a C++ object by checking the type of the Python object and using the appropriate conversion function.
    * The `boost::python::extract` class template takes one template argument, which specifies the C++ type to which the Python object should be converted. The extract object can be constructed with a Python object, and the () operator can be used to obtain the C++ object.
    * Here's an example that demonstrates how to use `boost::python::extract` to extract an int from a Python object:
    ```c++
    #include <boost/python.hpp>

    namespace py = boost::python;

    int extract_int(py::object obj) {
        py::extract<int> ex(obj);
        if (ex.check()) {
            return ex();
        } else {
            throw std::runtime_error("Cannot extract int");
        }
    }

    BOOST_PYTHON_MODULE(my_module) {
        py::def("extract_int", extract_int);
    }
    ```
    * In this example, the extract_int function takes a Python object as its argument and tries to extract an int from it using `boost::python::extract<int>`. If the extraction is successful, the function returns the int value. If the extraction fails, the function throws a `std::runtime_error` exception.
    * When you call the extract_int function from Python, you can pass any object that can be converted to an int, such as an int, a float, or a str. If the object cannot be converted to an int, the function will raise an exception.

##### [boost/python/to_python_converter.hpp](https://www.boost.org/doc/libs/1_76_0/libs/python/doc/html/reference/to_from_python_type_conversion/boost_python_to_python_converter.html)

* to_python_converter registers a conversion from objects of a given C++ type into a Python object.

###### MISC

* `boost::python::to_python_converter` ?
    * `boost::python::to_python_converter` is a template class in the boost.python library that allows users to define custom converters between C++ types and Python objects. It is used to convert C++ objects to Python objects when returning values from C++ functions or passing arguments to C++ functions that expect Python objects.
    * Here is an example of using `boost::python::to_python_converter` to define a custom converter for a user-defined `MyClass` type:
    ```c++
    #include <boost/python.hpp>

    class MyClass {
    public:
        int value;

        MyClass(int value) : value(value) {}
    };

    struct MyClass_to_python {
        static PyObject* convert(const MyClass& obj) {
            boost::python::dict dict;
            dict["value"] = obj.value;
            return boost::python::incref(dict.ptr());
        }
    };

    BOOST_PYTHON_MODULE(example) {
        boost::python::to_python_converter<MyClass, MyClass_to_python>();
    }
    ```
    * In this example, `MyClass` is a simple user-defined class with a single integer member variable. The `MyClass_to_python` struct defines the conversion logic between `MyClass` objects and Python objects. The `convert()` function takes a const MyClass& reference and returns a new Python dictionary with the value member variable stored as a key-value pair.
    * The `boost::python::to_python_converter` template is then used to register the custom converter for the `MyClass` type with the example module.
    * With this custom converter in place, instances of `MyClass` can be returned from C++ functions and automatically converted to Python objects:
    ```c++
    MyClass create_myclass() {
        return MyClass(42);
    }

    BOOST_PYTHON_MODULE(example) {
        boost::python::to_python_converter<MyClass, MyClass_to_python>();

        boost::python::def("create_myclass", create_myclass);
    }
    ```
    * In this example, the `create_myclass()` function returns a new instance of `MyClass`, which is automatically converted to a Python dictionary object when the function is called from Python:
    ```c++
    import example

    obj = example.create_myclass()
    print(obj)  # Output: {'value': 42}
    ```
    * Note that `boost::python::to_python_converter` can be used to define custom converters for a wide range of C++ types, including primitive types, standard library types, and user-defined types. It provides a powerful and flexible mechanism for integrating C++ code with Python.

### MISC

* [TNG/boost-python-examples: Some examples for the use of boost::python](https://github.com/TNG/boost-python-examples)
* [boost python - Checking whether a converter has already been registered - Stack Overflow](https://stackoverflow.com/questions/9888289/checking-whether-a-converter-has-already-been-registered)
```c++
#include <boost/python.hpp>
#include <map>
#include <utility>
#include <vector>

template<typename K, typename V>
struct map_to_dict
{
    static PyObject* convert(const std::map<K, V>& m)
    {
        boost::python::dict d;        
        for (const auto& [key, value] : m) {
            d[key] = value;
        }

        return boost::python::incref(d.ptr());
    }
};

template<typename K, typename V>
void register_map_to_dict_converter()
{
    auto typeID = boost::python::type_id<std::map<K, V> >();
    if (auto reg = boost::python::converter::registry::query(typeID); reg == nullptr || reg->m_to_python == nullptr)
    {
        boost::python::to_python_converter<std::map<K, V>, map_to_dict<K, V> >();
    }
}

template<typename T1, typename T2>
struct pair_to_tuple
{
    static PyObject* convert(const std::pair<T1, T2>& p)
    {
        return boost::python::incref(boost::python::make_tuple(p.first, p.second).ptr());
    }
};

template<typename T1, typename T2>
void register_pair_to_tuple_converter()
{
    auto typeID = boost::python::type_id<std::pair<T1, T2> >();
    if (auto reg = boost::python::converter::registry::query(typeID); reg == nullptr || reg->m_to_python == nullptr)
    {
        boost::python::to_python_converter<std::pair<T1, T2>, pair_to_tuple<T1, T2> >();
    }
}

template<typename T>
struct vector_to_list
{
    static PyObject* convert(const std::vector<T>& vec)
    {
        boost::python::list lst;
        for (const auto& it : vec)
        {
            lst.append(boost::python::object(it));
        }
        return boost::python::incref(lst.ptr());
    }
};

template <typename T>
void register_vector_to_list_converter()
{
    auto typeID = boost::python::type_id<std::vector<T> >();
    if (auto reg = boost::python::converter::registry::query(typeID); reg == nullptr || reg->m_to_python == nullptr)
    {
        boost::python::to_python_converter<std::vector<T>, vector_to_list<T> >();
    }
}

BOOST_PYTHON_MODULE(example)
{
    register_map_to_dict_converter<int, double>();
    register_pair_to_tuple_converter<int, int>();
    register_vector_to_list_converter<double>();
}
```

## FAQ

### ERROR

* `libboost_atomic-vc142-mt-gd-x64-1_76.lib` v.s. `libboost_atomic-vc142-mt-x64-1_76.lib` ?
   * The difference between the two Boost library filenames you provided, `libboost_atomic-vc142-mt-gd-x64-1_76.lib` and `libboost_atomic-vc142-mt-x64-1_76.lib`, reflects different build configurations used for compiling the Boost libraries. These naming conventions convey important information about how each library was compiled, including compiler version, threading support, debug status, and architecture. Here's a breakdown of each component in the filenames and what they indicate:
   * Breakdown of Boost Library Filenames
      * 1. `libboost_atomic-vc142-mt-gd-x64-1_76.lib`
         * libboost_atomic: The name of the Boost library, in this case, Boost.Atomic.
         * vc142: Compiled with Microsoft Visual C++ compiler version 14.2, which corresponds to Visual Studio 2019.
         * mt: Uses multithreading. The mt tag indicates that the library is built with multithreading enabled and links to the multithreaded version of the runtime library.
         * gd:
            * g: Compiled with debugging symbols. This includes additional debug information which helps during debugging but increases the size of the binary.
            * d: Linked against a debug version of the Microsoft runtime libraries (/MDd or /MTd depending on whether it is dynamic or static). This is crucial for debugging applications as it uses the debug heap and other debug facilities.
         * x64: Built for 64-bit architectures.
         * 1_76: The version of the Boost library, in this case, version 1.76.
      * 2. `libboost_atomic-vc142-mt-x64-1_76.lib`
         * libboost_atomic: The name of the Boost library, Boost.Atomic.
         * vc142: Compiled with Microsoft Visual C++ compiler version 14.2 (Visual Studio 2019).
         * mt: Multithreaded support is enabled.
         * x64: Built for 64-bit architectures.
         * 1_76: Version 1.76 of the Boost library.
      * Note: The absence of gd or d indicates that this is a release version without debug symbols and linked against the release version of the Microsoft runtime libraries (/MD or /MT).
   * Choosing the Right Library
      * Debugging: When you are developing and debugging your application, you should link against the debug versions of libraries (e.g., libboost_atomic-vc142-mt-gd-x64-1_76.lib). These libraries are compiled with debug information and linked against debug versions of runtime libraries, which offer debugging facilities like checks for memory leaks, use of uninitialized memory, etc.
      * Release: For production releases, use the release versions of libraries (e.g., libboost_atomic-vc142-mt-x64-1_76.lib). These are optimized for performance and size, and do not include debug information, making them faster and smaller.
   * Configuring Your Project
      * In Visual Studio, you can set up your project properties to automatically link the appropriate library based on the current configuration:
         * Go to Project Properties.
         * Under Configuration Properties, go to C/C++ -> General and add the appropriate directories to the Additional Include Directories for Boost headers.
         * Under Linker -> General, add the directories containing the Boost libraries to the Additional Library Directories.
         * Under Linker -> Input, add the specific Boost libraries to the Additional Dependencies field, possibly using different settings for debug and release configurations.
   * By correctly configuring your development environment and choosing the appropriate library versions for different stages of your development cycle, you can leverage Boost's capabilities effectively while ensuring that your application remains robust and optimized.
* `libboost_log-vc142-mt-x64-1_76.lib(*.obj) : error LNK2038: mismatch detected for '_ITERATOR_DEBUG_LEVEL': value '0' doesn't match value '2' in *.obj` ?
    * The error `LNK2038: mismatch detected for '_ITERATOR_DEBUG_LEVEL': value '0' doesn't match value '2'` in a Visual Studio project indicates a mismatch between the iterator debug level settings used to compile different parts of your application. This mismatch typically arises when some components (like your own code) are compiled in Debug mode (which sets _ITERATOR_DEBUG_LEVEL to 2), while others (like precompiled libraries, in this case, Boost) are compiled in Release mode (which sets _ITERATOR_DEBUG_LEVEL to 0). Here's how you can resolve this issue:
    * Understanding the Error
        * _ITERATOR_DEBUG_LEVEL = 2: This setting is used when compiling with Debug configuration in Visual Studio. It enables various checks for iterators to help catch bugs, but it also makes the code slower.
        * _ITERATOR_DEBUG_LEVEL = 0: This setting is used in Release mode. It turns off iterator debugging features for better performance.
        * The mismatch happens if you link libraries compiled with different settings of _ITERATOR_DEBUG_LEVEL. This is not allowed because it can lead to runtime errors.
    * Steps to Resolve the Issue
        * 1. Consistent Configuration Settings
            * Ensure that all parts of your project and all linked libraries are compiled with the same configuration settings (either all Debug or all Release). This is the most straightforward way to avoid such mismatches.
                * Check Project Configuration: Make sure that your project's configuration (Debug/Release) matches that of the linked Boost libraries. If you are in Debug mode, ensure you are linking against Boost libraries compiled in Debug mode.
        * 2. Rebuild All Components
            * If you've switched between configurations (e.g., from Debug to Release or vice versa), make sure to rebuild your entire project and all dependencies to ensure all components are compiled with the correct settings.
            * Clean and Rebuild: Use the "Clean" feature in Visual Studio followed by a "Rebuild All". This ensures there are no old object files with incompatible settings.
        * 3. Boost Library Configuration
            * Make sure you have both Debug and Release versions of the Boost libraries available.
            * Download or Compile the Correct Version: If you don’t have the correct versions, you might need to download them or build them from source. Boost uses different naming conventions to differentiate between Debug and Release builds, e.g., `libboost_log-vc142-mt-gd-x64-1_76.lib` for Debug.
        * 4. Check Compiler Flags
            * Verify that the compiler flags related to iterator debugging are consistently set across your project. You can check and set these flags in the C++ project properties:
                * Open Project Properties.
                * Navigate to C++ -> Preprocessor.
                * Make sure that _DEBUG is defined in Debug mode and not defined in Release mode.
                * Navigate to C++ -> Code Generation.
                * Ensure that the Runtime Library settings are consistent across all project configurations. Use `/MDd` for Debug and `/MD` for Release.
        * 5. Use Property Sheets for Consistency
            * If you are managing a larger solution with multiple projects, consider using property sheets in Visual Studio to ensure consistent settings across all projects.
    * Conclusion
        * The `LNK2038` error related to `_ITERATOR_DEBUG_LEVEL` mismatch requires ensuring consistent compilation settings across your entire project and linked libraries. By aligning the Debug/Release configurations and carefully managing compiler settings, you can eliminate such conflicts and ensure a stable build environment. This will prevent linking errors and potential runtime problems due to inconsistencies in the build settings.
* linux `undefined symbol: _ZTIN5boost10filesystem16filesystem_errorE` ?
    * The error undefined symbol: _ZTIN5boost10filesystem16filesystem_errorE indicates that the linker is unable to resolve a symbol related to the Boost Filesystem library. This symbol corresponds to the type information for the boost::filesystem::filesystem_error exception class. This typically happens when the Boost Filesystem library is not correctly linked during the compilation of your application.
    * How to Resolve This Error
        * To fix this issue, you will need to ensure that your project is correctly linking against the Boost Filesystem library, and that your build environment is properly set up to find and use the Boost libraries. Here’s how you can address this:
        * 1. Install Boost Correctly
            * First, ensure that Boost is correctly installed on your system. Boost can be installed from source or through your distribution’s package manager.
            * From Source: Download the latest Boost library from Boost.org and follow the installation instructions. Typically, you will need to run ./bootstrap.sh and then ./b2 to build and install.
            * Package Manager:
                * On Debian/Ubuntu: sudo apt-get install libboost-all-dev
                * On Fedora/CentOS: sudo dnf install boost-devel (Fedora), sudo yum install boost-devel (CentOS)
        * 2. Linking Boost Filesystem
            * You need to explicitly link the Boost Filesystem library in your compilation command. This is usually done by adding -lboost_filesystem along with -lboost_system since Boost Filesystem depends on Boost System.
            * Here’s how you might compile a C++ program using Boost Filesystem:
            ```sh
            g++ -o my_app my_app.cpp -lboost_filesystem -lboost_system
            ```
            * Ensure that you are linking against the right versions of these libraries, and that they are in your linker's search path. If they are installed in a non-standard location, you may need to specify the path using `-L/path/to/boost/libs`.
        * 3. Specifying Include and Library Paths
            * If Boost is installed in a custom directory, you will need to specify the include and library paths in your compilation command:
            ```sh
            g++ -o my_app my_app.cpp -I/path/to/boost/include -L/path/to/boost/lib -lboost_filesystem -lboost_system
            ```
        * 4. Dynamic vs. Static Linking
            * If you are using static linking rather than dynamic linking, make sure that you have built the static libraries of Boost and specify them accordingly in your linker flags. Sometimes you might need to define BOOST_ALL_NO_LIB to prevent auto-linking of the wrong library type.
        * 5. Ensure Correct Compilation Order
            * Sometimes, the order of libraries in the linking command matters. Generally, list your dependencies after your objects and sources:
            ```sh
            g++ -o my_app my_app.cpp -lboost_filesystem -lboost_system
            ```
        * 6. Check for ABI Compatibility
            * Make sure that all your libraries and your own application are compiled with the same version of the compiler, using compatible ABI settings (e.g., using the same C++ standard library, same compiler flags like -std=c++11).
    * Debugging Further
        * If the issue persists:
            * Use `ldd` on Linux to check dynamic libraries dependencies.
            * Use `nm` to check for symbols in the libraries:
            ```sh
            nm -C libboost_filesystem.so | grep filesystem_error
            ```
            * This will help verify that the symbol is indeed in the Boost Filesystem library.

# END
