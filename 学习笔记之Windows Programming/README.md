# 学习笔记之Windows Programming

* [Get Started with Win32 and C++ - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/learnwin32/learn-to-program-for-windows)
  * The aim of this Get Started series is to teach you how to write a desktop program in C++ using Win32 and COM APIs.
  * In the first module, you'll learn step-by-step how to create and show a window. Later modules will introduce the Component Object Model (COM), graphics and text, and user input.
  * [Working with Strings - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/learnwin32/working-with-strings)
* [Windows API - Wikipedia](https://en.wikipedia.org/wiki/Windows_API)
  * The Windows API, informally WinAPI, is Microsoft's core set of application programming interfaces (APIs) available in the Microsoft Windows operating systems. The name Windows API collectively refers to several different platform implementations that are often referred to by their own names (for example, Win32 API); see the versions section. Almost all Windows programs interact with the Windows API. On the Windows NT line of operating systems, a small number (such as programs started early in the Windows startup process) use the Native API.[1]
  * Developer support is available in the form of a software development kit, Microsoft Windows SDK, providing documentation and tools needed to build software based on the Windows API and associated Windows interfaces.
  * The Windows API (Win32) is focused mainly on the programming language C[2] in that its exposed functions and data structures are described in that language in recent versions of its documentation. However, the API may be used by any programming language compiler or assembler able to handle the (well-defined) low-level data structures along with the prescribed calling conventions for calls and callbacks. Similarly, the internal implementation of the API's function has been developed in several languages, historically.[3] Despite the fact that C is not an object-oriented programming language, the Windows API and Windows have both historically been described as object-oriented. There have also been many wrapper classes and extensions (from Microsoft and others) for object-oriented languages that make this object-oriented structure more explicit (Microsoft Foundation Class Library (MFC), Visual Component Library (VCL), GDI+, etc.). For instance, Windows 8 provides the Windows API and the WinRT API, which is implemented in C++[4] and is object-oriented by design.[4]
* [c-cpp/学习笔记之ATL & MFC at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BATL%20%26%20MFC)
* [c-cpp/学习笔记之COM(Component Object Model) at main · haoran119/c-cpp](https://github.com/haoran119/c-cpp/tree/main/%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%E4%B9%8BCOM(Component%20Object%20Model))
* [GetExitCodeThread function (processthreadsapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getexitcodethread?redirectedfrom=MSDN)
  * Retrieves the termination status of the specified thread.
  * Return value
    * If the function succeeds, the return value is nonzero.
    * If the function fails, the return value is zero. To get extended error information, call GetLastError.
  * Remarks
    * This function returns immediately. If the specified thread has not terminated and the function succeeds, the status returned is STILL_ACTIVE. If the thread has terminated and the function succeeds, the status returned is one of the following values:
    * The exit value specified in the ExitThread or TerminateThread function.
    * The return value from the thread function.
    * The exit value of the thread's process.
  * [c++ - How can you get the return value of a Windows thread? - Stack Overflow](https://stackoverflow.com/questions/7100441/how-can-you-get-the-return-value-of-a-windows-thread)

## ATL & MFC

* [Microsoft C/C++ Documentation | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/?view=msvc-160)
  * [ATL COM Desktop Components | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl/atl-com-desktop-components?view=msvc-160)
    * The ATL Reference documents the `Active Template Library (ATL)`, a set of template-based C++ classes that simplify the programming of Component Object Model (COM) objects. COM is a binary specification for creating and consuming software components on Windows. To fully take advantage of ATL, a working familiarity with COM is highly recommended. For more information about COM, see Component Object Model (COM).
    * [Active Template Library (ATL) Concepts | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl/active-template-library-atl-concepts?view=msvc-160)
      * The Active Template Library (ATL) is a set of template-based C++ classes that let you create small, fast Component Object Model (COM) objects. It has special support for key COM features, including stock implementations, dual interfaces, standard COM enumerator interfaces, connection points, tear-off interfaces, and ActiveX controls.
      * If you do a lot of ATL programming, you will want to learn more about COM and .NET attributes, which is designed to simplify COM programming. For more information, see Attributed Programming. (COM and .NET attributes are not to be confused with the [[attribute]] feature in the C++ standard.)
  * [MFC Desktop Applications | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/mfc/mfc-desktop-applications?view=msvc-160)
    * The Microsoft Foundation Class (MFC) Library provides an object-oriented wrapper over much of the Win32 and COM APIs. Although it can be used to create very simple desktop applications, it is most useful when you need to develop more complex user interfaces with multiple controls. You can use MFC to create applications with Office-style user interfaces. For documentation on the Windows platform itself, see Windows documentation. For information on building Windows applications in C++ without MFC, see Build desktop Windows apps using the Win32 API.
* [ATL-MFC Shared Classes | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/atl-mfc-shared-classes?view=msvc-160)
  * These utility classes can be used in any native C++ project without requiring any MFC DLL.
  * [Classes Shared by MFC and ATL | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/reference/classes-shared-by-mfc-and-atl?view=msvc-160)
    * [CTime Class | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/reference/ctime-class?view=msvc-160)
      * Represents an absolute time and date.
      * [CTime::GetCurrentTime](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/reference/ctime-class?view=msvc-160#getcurrenttime)
      * [CTime::Format](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/reference/ctime-class?view=msvc-160#format)
      * [strftime, wcsftime, _strftime_l, _wcsftime_l | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/c-runtime-library/reference/strftime-wcsftime-strftime-l-wcsftime-l?view=msvc-160)
* [CComVariant class | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl/reference/ccomvariant-class?view=msvc-170)
  * This class wraps the VARIANT type, providing a member indicating the type of data stored.
  * [VARIANT (oaidl.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/oaidl/ns-oaidl-variant)
    * VARIANTARG describes arguments passed within DISPPARAMS, and VARIANT to specify variant data that cannot be passed by reference.
    * When a variant refers to another variant by using the VT_VARIANT | VT_BYREF vartype, the variant being referred to cannot also be of type VT_VARIANT | VT_BYREF. VARIANTs can be passed by value, even if VARIANTARGs cannot.
* [Using CString | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/using-cstring?view=msvc-160)
  * The topics in this section describe how to program with CString. For reference documentation about the CString class, see the documentation for CStringT.
  * To use CString, include the atlstr.h header.
  * The CString, CStringA, and CStringW classes are specializations of a class template called CStringT based on the type of character data they support.
  * A CStringW object contains the wchar_t type and supports Unicode strings. A CStringA object contains the char type, and supports single-byte and multi-byte (MBCS) strings. A CString object supports either the char type or the wchar_t type, depending on whether the MBCS symbol or the UNICODE symbol is defined at compile time.
  * A CString object keeps character data in a CStringData object. CString accepts NULL-terminated C-style strings. CString tracks the string length for faster performance, but it also retains the NULL character in the stored character data to support conversion to LPCWSTR. CString includes the null terminator when it exports a C-style string. You can insert a NULL at other locations in a CString, but it may produce unexpected results.
  * The following set of string classes can be used without linking an MFC library, with or without CRT support: CAtlString, CAtlStringA, and CAtlStringW.
  * CString is used in native projects. For managed-code (C++/CLI) projects, use System::String.
  * To add more capabilities than CString, CStringA, or CStringW currently offer, you should create a subclass of CStringT that contains the additional features.
  * [CString Operations Relating to C-Style Strings | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/cstring-operations-relating-to-c-style-strings?view=msvc-160)
  * [CString::operator LPCTSTR | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/visualstudio/visual-studio-6.0/aa300569(v=vs.60)?redirectedfrom=MSDN)
  * [c++ - What is LPCTSTR? - Software Engineering Stack Exchange](https://softwareengineering.stackexchange.com/questions/194764/what-is-lpctstr)
    * LPCTSTR = L‌ong P‌ointer to a C‌onst T‌CHAR STR‌ing (Don't worry, a long pointer is the same as a pointer. There were two flavors of pointers under 16-bit windows.)
    * Here's the table:
      * LPSTR = char*
      * LPCSTR = const char*
      * LPWSTR = wchar_t*
      * LPCWSTR = const wchar_t*
      * LPTSTR = char* or wchar_t* depending on _UNICODE
      * LPCTSTR = const char* or const wchar_t* depending on _UNICODE
  * [[MS-DTYP]: LPCSTR | Microsoft Docs](https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-dtyp/f8d4fe46-6be8-44c9-8823-615a21d17a61)
  * [[MS-DTYP]: LPCWSTR | Microsoft Docs](https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-dtyp/76f10dd8-699d-45e6-a53c-5aefc586da20)
  * [CSimpleStringT Class | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/reference/csimplestringt-class?view=msvc-170)
    * [CSimpleStringT::GetString](https://docs.microsoft.com/en-us/cpp/atl-mfc-shared/reference/csimplestringt-class?view=msvc-170#getstring)
      * Retrieves the character string.
      * Return Value
        * A pointer to a null-terminated character string.

## [CMD](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands) 

* Windows built-in commands

### [Command-line reference A-Z](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands#command-line-reference-a-z)

#### [xcopy](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/xcopy)

* [XCOPY - Wikipedia](https://en.wikipedia.org/wiki/XCOPY)
    * In computing, XCOPY is a command used on IBM PC DOS, MS-DOS, IBM OS/2,[1] Microsoft Windows,[2] FreeDOS,[3] ReactOS,[4] and related operating systems for copying multiple files or entire directory trees from one directory to another and for copying files across a network.
* xcopy ?
    * xcopy is a command-line utility on Windows for copying multiple files or entire directory trees from one directory to another. It is a more powerful version of the copy command with additional features.
    * Basic Usage:
        * `xcopy source [destination] [options]`
        * source - Specifies the file(s) to copy.
        * destination - Specifies the location and/or name of new files.
        * options - Flags that specify how the files will be copied.
    * Commonly Used Options:
        * /S: Copies directories and subdirectories, excluding empty ones.
        * /E: Copies directories and subdirectories, including empty ones.
        * /I: If in doubt, it assumes that the destination is a directory (e.g., when the destination does not exist).
        * /H: Copies hidden and system files.
        * /R: Overwrites read-only files.
        * /Y: Suppresses prompting to confirm you want to overwrite an existing destination file.
        * `/EXCLUDE:file1[+file2][+file3]...`: Specifies a list of files containing strings. Each string should be in a separate line in the files. When any of the strings match any part of the absolute path of the file to be copied, that file will be excluded from being copied.
    * Examples:
        * Copy a file to another directory:
            * `xcopy C:\example.txt D:\`
        * Copy a directory and its contents to another directory:
            * `xcopy C:\example D:\backup\example /E`
        * Copy a directory excluding certain files:
        ```sh
        echo .txt > exclude.txt
        xcopy C:\example D:\backup\example /E /EXCLUDE:exclude.txt
        ```
        * Suppress overwrite prompt:
            * `xcopy C:\example.txt D:\example.txt /Y`
    * Always remember to have a backup of your data when using command-line utilities, especially when copying or moving files. If used incorrectly, data might be overwritten or lost.
* How to ignore "Does <destination> specify a file name or directory name on the target" when xcopy a file to a file ?
    * When you use xcopy to copy a file to another file (as opposed to copying a file into a directory), xcopy prompts the user with the question
    * You can bypass this prompt by redirecting an input to xcopy. Here's how you can do it:
        * Using echo:
            * If you're certain that the destination is a file, you can use the echo command to send the F input to xcopy:
            * `echo F | xcopy C:\source\example.txt D:\destination\example.txt`
        * Using the `/I` switch:
            * The `/I` switch tells xcopy to assume that the destination is a directory if there's any ambiguity. This is more suited for copying directories or when the destination doesn't already exist, but it can sometimes be useful for files too, especially if the destination file already exists.
            * `xcopy C:\source\example.txt D:\destination\example.txt /I`
            * However, note that the `/I` switch is more of a workaround in this context. The more direct way is using `echo F |`.
            * Always ensure you're copying to the correct destination and make backups of important data, as misuse can result in data loss.

## COM

* [`Component Object Model (COM)` - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/com/component-object-model--com--portal)
  * Purpose
    * COM is a platform-independent, distributed, object-oriented system for creating binary software components that can interact. COM is the foundation technology for Microsoft's OLE (compound documents) and ActiveX (Internet-enabled components) technologies.
  * Where applicable
    * COM objects can be created with a variety of programming languages. Object-oriented languages, such as C++, provide programming mechanisms that simplify the implementation of COM objects. These objects can be within a single process, in other processes, even on remote computers.
* [Component Object Model - Wikipedia](https://en.wikipedia.org/wiki/Component_Object_Model)
  * Component Object Model (COM) is a binary-interface standard for software components introduced by Microsoft in 1993. It is used to enable inter-process communication object creation in a large range of programming languages. COM is the basis for several other Microsoft technologies and frameworks, including OLE, OLE Automation, Browser Helper Object, ActiveX, COM+, DCOM, the Windows shell, DirectX, UMDF and Windows Runtime. The essence of COM is a language-neutral way of implementing objects that can be used in environments different from the one in which they were created, even across machine boundaries. For well-authored components, COM allows reuse of objects with no knowledge of their internal implementation, as it forces component implementers to provide well-defined interfaces that are separated from the implementation. The different allocation semantics of languages are accommodated by making objects responsible for their own creation and destruction through reference-counting. Type conversion casting between different interfaces of an object is achieved through the QueryInterface method. The preferred method of "inheritance" within COM is the creation of sub-objects to which method "calls" are delegated.
  * COM is an interface technology defined and implemented as standard only on Microsoft Windows and Apple's Core Foundation 1.3 and later plug-in application programming interface (API).[1] The latter only implements a subset of the whole COM interface.[2] For some applications, COM has been replaced at least to some extent by the Microsoft .NET framework, and support for Web Services through the Windows Communication Foundation (WCF). However, COM objects can be used with all .NET languages through .NET COM Interop. Networked DCOM uses binary proprietary formats, while WCF encourages the use of XML-based SOAP messaging. COM is very similar to other component software interface technologies, such as CORBA and Enterprise JavaBeans, although each has its own strengths and weaknesses. Unlike C++, COM provides a stable application binary interface (ABI) that does not change between compiler releases.[3] This makes COM interfaces attractive for object-oriented C++ libraries that are to be used by clients compiled using different compiler versions.
* [Is component object model still used?](https://livebook.manning.com/book/powershell-in-depth-second-edition/chapter-34/)
  * .NET Framework, folks relied on an earlier technology called the Component Object Model (COM). COM is basically a set of rules that enable developers to write software components that can easily interoperate. COM is still in wide use today, although it's considered an older cousin to the . NET Framework.
* [c++ - What is COM (Component Object Model) in a nutshell? - Stack Overflow](https://stackoverflow.com/questions/455687/what-is-com-component-object-model-in-a-nutshell)
* [Essential COM - Don Box - Google Books](https://books.google.co.uk/books?id=kfRWvKSePmAC&dq=essential+com&printsec=frontcover&source=bn&hl=en&sa=X&oi=book_result&ct=result#v=onepage&q=essential%20com&f=false)
* [Migrating COM/DCOM Applications in Microsoft .NET Framework](https://www.c-sharpcorner.com/article/migrating-comdcom-applications-in-microsoft-net-framework/)
* [Managed and Unmanaged Code - Key Differences - ParTech](https://www.partech.nl/en/publications/2021/03/managed-and-unmanaged-code---key-differences#)
  * DIFFERENCE BETWEEN MANAGED AND UNMANAGED CODE?
    * Managed code is the one that is executed by the CLR of the .NET framework while unmanaged or unsafe code is executed by the operating system.
    * The managed code provides security to the code while undamaged code creates security threats.
    * In unsafe or unmanaged code the unsafe modifier is used to write the block of code while any other code written outside the unsafe code block is managed code.
    * Memory buffer overflow problems do not occur in managed code as it is taken care of by the runtime environment but these problems occur in unmanaged code.
    * Runtime services are provided in managed code while they are not provided in unmanaged code.
    * Source code is first converted to intermediate language and then to native language in managed code while it is directly converted into the native language in unmanaged code.
    * Unmanaged code provides low-level access while managed code does not provide that.
    * In unsafe or unmanaged code the unsafe modifier is used to write the block of code while any other code written outside the unsafe code block is managed code.
* [Compiler COM Support | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/compiler-com-support?view=msvc-160)
  * The Microsoft C++ compiler can directly read component object model (COM) type libraries and translate the contents into C++ source code that can be included in the compilation. Language extensions are available to facilitate COM programming on the client side for desktop apps.
  * By using the #import preprocessor directive, the compiler can read a type library and convert it into a C++ header file that describes the COM interfaces as classes. A set of #import attributes is available for user control of the content for the resulting type library header files.
  * You can use the __declspec extended attribute uuid to assign a globally unique identifier (GUID) to a COM object. The keyword __uuidof can be used to extract the GUID associated with a COM object. Another __declspec attribute, property, can be used to specify the get and set methods for a data member of a COM object.
  * A set of COM support global functions and classes is provided to support the VARIANT and BSTR types, implement smart pointers, and encapsulate the error object thrown by _com_raise_error:
    * Compiler COM Global Functions
    * _bstr_t
    * _com_error
    * _com_ptr_t
    * _variant_t
  * [BSTR | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/automat/bstr)
    * A BSTR (Basic string or binary string) is a string data type that is used by COM, Automation, and Interop functions. Use the BSTR data type in all interfaces that will be accessed from script.
  * [_bstr_t class | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/bstr-t-class?view=msvc-160)
    * A _bstr_t object encapsulates the BSTR data type. The class manages resource allocation and deallocation through function calls to SysAllocString and SysFreeString and other BSTR APIs when appropriate. The _bstr_t class uses reference counting to avoid excessive overhead.
  * [_bstr_t::operator +=, _bstr_t::operator + | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/bstr-t-operator-add-equal-plus?view=msvc-160)
    * Appends characters to the end of the _bstr_t object, or concatenates two strings.
  * [_bstr_t::wchar_t*, _bstr_t::char* | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/cpp/bstr-t-wchar-t-star-bstr-t-char-star?view=msvc-160)
    * Returns the BSTR characters as a narrow or wide character array.
* [CoInitialize function (objbase.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-coinitialize)
  * Initializes the COM library on the current thread and identifies the concurrency model as single-thread apartment (STA).
  * New applications should call CoInitializeEx instead of CoInitialize.
  * If you want to use the Windows Runtime, you must call Windows::Foundation::Initialize instead.
* [CoUninitialize function (combaseapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-couninitialize)
  * Closes the COM library on the current thread, unloads all DLLs loaded by the thread, frees any other resources that the thread maintains, and forces all RPC connections on the thread to close.
* [HRESULT - Wikipedia](https://en.wikipedia.org/wiki/HRESULT)
  * In the field of computer programming, the HRESULT is a data type used in Windows operating systems, and the earlier IBM/Microsoft OS/2 operating system, to represent error conditions, and warning conditions.
  * The original purpose of HRESULTs was to formally lay out ranges of error codes for both public and Microsoft internal use in order to prevent collisions between error codes in different subsystems of the OS/2 operating system.
  * HRESULTs are numerical error codes. Various bits within an HRESULT encode information about the nature of the error code, and where it came from.
  * HRESULT error codes are most commonly encountered in COM programming, where they form the basis for a standardized COM error handling convention.
  * [HRESULT | Microsoft Docs](https://docs.microsoft.com/en-us/office/client-developer/outlook/mapi/hresult)
    * The following HRESULT values are the most common. More values are contained in the header file Winerror.h.
  * [Common HRESULT Values - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/seccrypto/common-hresult-values)
  * [COM Error Codes (Generic) (Winerror.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/com/com-error-codes-1)

  Name	| Description	| Value
  -|-|-
  S_OK	| Operation successful	| 0x00000000
  E_ABORT	| Operation aborted	| 0x80004004
  E_ACCESSDENIED	| General access denied error	| 0x80070005
  E_FAIL	| Unspecified failure	| 0x80004005
  E_HANDLE	| Handle that is not valid	| 0x80070006
  E_INVALIDARG	| One or more arguments are not valid	| 0x80070057
  E_NOINTERFACE	| No such interface supported	| 0x80004002
  E_NOTIMPL	| Not implemented	| 0x80004001
  E_OUTOFMEMORY	| Failed to allocate necessary memory	| 0x8007000E
  E_POINTER	| Pointer that is not valid	| 0x80004003
  E_UNEXPECTED	| Unexpected failure	| 0x8000FFFF

* [Universally unique identifier - Wikipedia](https://en.wikipedia.org/wiki/Universally_unique_identifier)
  * A universally unique identifier (UUID) is a 128-bit label used for information in computer systems. The term globally unique identifier (GUID) is also used, often in software created by Microsoft.[1]
  * When generated according to the standard methods, UUIDs are, for practical purposes, unique. Their uniqueness does not depend on a central registration authority or coordination between the parties generating them, unlike most other numbering schemes. While the probability that a UUID will be duplicated is not zero, it is close enough to zero to be negligible.[2][3]
  * Thus, anyone can create a UUID and use it to identify something with near certainty that the identifier does not duplicate one that has already been, or will be, created to identify something else. Information labeled with UUIDs by independent parties can therefore be later combined into a single database or transmitted on the same channel, with a negligible probability of duplication.
  * Adoption of UUIDs is widespread, with many computing platforms providing support for generating them and for parsing their textual representation.
  * [GUID - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/guiddef/ns-guiddef-guid)
    * A GUID identifies an object such as a COM interfaces, or a COM class object, or a manager entry-point vector (EPV). A GUID is a 128-bit value consisting of one group of 8 hexadecimal digits, followed by three groups of 4 hexadecimal digits each, followed by one group of 12 hexadecimal digits. The following example GUID shows the groupings of hexadecimal digits in a GUID: 6B29FC40-CA47-1067-B31D-00DD010662DA.
    * The GUID structure stores a GUID.
  * [CLSIDFromString function (combaseapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-clsidfromstring)
    * Converts a string generated by the StringFromCLSID function back into the original CLSID.
  * [CoCreateGuid function (combaseapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cocreateguid?redirectedfrom=MSDN)
    * Creates a GUID, a unique 128-bit integer used for CLSIDs and interface identifiers.
    * [windows - What's the C++ version of Guid.NewGuid()? - Stack Overflow](https://stackoverflow.com/questions/1327157/whats-the-c-version-of-guid-newguid)
  * [StringFromGUID2 function (combaseapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-stringfromguid2)
    * Converts a globally unique identifier (GUID) into a string of printable characters.
  * [StringFromCLSID function (combaseapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-stringfromclsid?redirectedfrom=MSDN)
    * Converts a CLSID into a string of printable characters. Different CLSIDs always convert to different strings.
  * [c++ - Print a GUID variable - Stack Overflow](https://stackoverflow.com/questions/1672677/print-a-guid-variable)
  ```c++
  #include <iostream>
  #include <string>
  #include <stdexcept>
  #include <comutil.h>

  int main()
  {
      GUID guid{};
      HRESULT hr = CoCreateGuid(&guid);
      std::string toFilename{};

      if (S_OK == hr) {
          OLECHAR buffer[64];

          auto size = StringFromGUID2(guid, buffer, 64);
          if (size > 0) {
              _bstr_t tempFilename = _bstr_t(buffer);

              // remove enclosing braces
              toFilename += std::string(tempFilename).substr(1, tempFilename.length() - 2);
          }
      }
      else {
          throw std::runtime_error("Error creating a GUID!");
      }

      std::cout << toFilename << std::endl;

      return 0;
  }
  ```
  * [c++ - How to initialize a constant CLSID - Stack Overflow](https://stackoverflow.com/questions/29975918/how-to-initialize-a-constant-clsid)
  ```c++
  const CLSID clsid2 = { 0x557cf406, 0x1a04, 0x11d3, { 0x9a,0x73,0x00,0x00,0xf8,0x1e,0xf3,0x2e } };
  ```
  * How to convert from CLSID to string ?
    * [[MS-OAUT]: LPOLESTR | Microsoft Docs](https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-oaut/b2c46afb-4717-4cbb-8828-d6e0ae743463)
  ```c++
  auto getSCLSID = []() {
      lpolestr sCLSID{};
      auto hr = stringfromclsid(clsid, &sCLSID);
      cotaskmemfree(sCLSID);

      return sCLSID;
  ```

## EXCEL

* How to calculate the difference of two timestamp columns ans sort it descending order in excel?
    * `=IF(G2<>"", G2-F2+(F2>G2), "")`
    * [How to calculate time difference with milliseconds in Excel?](https://www.extendoffice.com/documents/excel/4693-excel-time-difference-with-milliseconds.html)
    * [Excel formula: If cell is not blank | Exceljet](https://exceljet.net/formula/if-cell-is-not-blank)
    * [Fill a formula down into adjacent cells](https://support.microsoft.com/en-us/office/fill-a-formula-down-into-adjacent-cells-041edfe2-05bc-40e6-b933-ef48c3f308c6#ID0EBBF=Web)
    * [How to Sort and Ignore Blanks in Excel & Google Sheets - Automate Excel](https://www.automateexcel.com/how-to/sort-ignore-blanks/#:~:text=Now%20you%20can%20sort%20the,Filter%20%3E%20Sort%20Largest%20to%20Smallest.)
* How to replace last occurred "}}" to "}," and append string "test"?
    * To achieve the task of replacing the last occurrence of "}}" with "}," and then appending the string "test" in an Excel cell, you can use a combination of Excel's built-in functions such as `SUBSTITUTE`, `SEARCH`, `LEN`, and `CONCATENATE` (or `&` for concatenation). Here's a step-by-step approach to creating an Excel formula that accomplishes this:
    * Sample Excel Formula
        * Suppose your original text is in cell A1. Here is how you can construct the formula:
            * `=SUBSTITUTE(A1, "}}", "},", LEN(A1) - LEN(SUBSTITUTE(A1, "}}", "")) / 2) & "test"`
    * Explanation
        * `SUBSTITUTE(A1, "}}", "},", LEN(A1) - LEN(SUBSTITUTE(A1, "}}", "")) / 2)`:
            * `SUBSTITUTE(A1, "}}", "},", <instance_num>)` replaces the specified instance of "}}" in A1 with "},"
            * `LEN(A1) - LEN(SUBSTITUTE(A1, "}}", ""))` calculates the total length of all "}}" occurrences in A1. By subtracting the length of A1 without "}}" from the total length of A1, you get twice the count of "}}" since each "}}" is two characters long.
            * Dividing by 2 gives you the number of "}}" occurrences. Using this in the SUBSTITUTE function specifies to replace the last occurrence.
        * `& "test"`: Concatenates "test" to the end of the string resulting from the SUBSTITUTE function.
        * This formula is quite efficient but assumes that "}}" does indeed occur in the text. If "}}" might not be present, you might want to add error handling to avoid displaying formula errors:
        * `=IF(ISERROR(SEARCH("}}", A1)), A1 & "test", SUBSTITUTE(A1, "}}", "},", LEN(A1) - LEN(SUBSTITUTE(A1, "}}", "")) / 2) & "test")`
    * Error Handling Added
        * `IF(ISERROR(SEARCH("}}", A1)), A1 & "test", ...)`:
            * `SEARCH("}}", A1)` looks for "}}" in A1. If "}}" is not found, SEARCH will result in an error.
            * `IF(ISERROR(...), A1 & "test", ...)` checks if an error occurred (meaning "}}" was not found). If true, it simply appends "test" to the original text. If false, it proceeds with the replacement and appending as described above.
    * Using this formula allows you to dynamically replace the last occurrence of "}}" with "}," and append "test" to the string in Excel, adjusting appropriately based on whether "}}" is present.

## MSXML

* [MSXML SDK Overview | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/ms760399(v=vs.85))
  * What Is MSXML?
    * `Microsoft XML Core Services (MSXML)` allows customers to build high-performance XML-based applications that provide a high degree of interoperability with other applications that adhere to the XML 1.0 standard.
    * Among the core services MSXML provides is developer support for the following:
    * The Document Object Model (DOM), a standard library of application programming interfaces (APIs) for accessing XML documents.
    * Helper APIs to assist with programming for the XML namespace or the HyperText Transfer Protocol (HTTP) when it is used to send data directly between Web servers.
    * XML Schema Definition (XSD). Earlier MSXML versions such as MSXML 3.0, 4.0, and 5.0 as support the XML Data Reduced schema definition language (XDR), which was introduced by Microsoft to support XML schema working needs before XSD became a W3C standard. Support for XDR is removed from MSXML 6.0.
    * The Simple API for XML (SAX), a programmatic alternative to DOM-based processing.
    * The Schema Object Model (SOM), an additional set of APIs for accessing XML Schema documents programmatically that was available in MSXML 4.0 and later.
    * XML Digital Signatures support, which provides the ability to sign and verify XML document data through digital encryption. This support is only available in MSXML 5.0 for Microsoft Office Applications.
* [MSXML - Wikipedia](https://en.wikipedia.org/wiki/MSXML)
  * Microsoft XML Core Services (MSXML) are set of services that allow applications written in JScript, VBScript, and Microsoft development tools to build Windows-native XML-based applications. It supports XML 1.0, DOM, SAX, an XSLT 1.0 processor, XML schema support including XSD and XDR, as well as other XML-related technologies.
* [IXMLDOMParseError | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/ms757019(v=vs.85))
  * Returns detailed information about the last parse error, including the error number, line number, character position, and a text description.
  * [IXMLDOMParseError Members | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/ms767720(v=vs.85))

## [PowerShell](https://learn.microsoft.com/en-us/powershell/)

* [PowerShell - Wikipedia](https://en.wikipedia.org/wiki/PowerShell)
    * PowerShell is a task automation and configuration management program from Microsoft, consisting of a command-line shell and the associated scripting language. Initially a Windows component only, known as Windows PowerShell, it was made open-source and cross-platform on August 18, 2016, with the introduction of PowerShell Core.[5] The former is built on the .NET Framework, the latter on .NET (previously .NET Core).
    * Since Windows 10 build 14971, PowerShell replaced Command Prompt and became the default command shell for File Explorer.[6][7]
    * In PowerShell, administrative tasks are generally performed via cmdlets (pronounced command-lets), which are specialized .NET classes implementing a particular operation. These work by accessing data in different data stores, like the file system or Windows Registry, which are made available to PowerShell via providers. Third-party developers can add cmdlets and providers to PowerShell.[8][9] Cmdlets may be used by scripts, which may in turn be packaged into modules. Cmdlets work in tandem with the .NET API.
    * PowerShell's support for .NET Remoting, WS-Management, CIM, and SSH enables administrators to perform administrative tasks on both local and remote Windows systems. PowerShell also provides a hosting API with which the PowerShell runtime can be embedded inside other applications. These applications can then use PowerShell functionality to implement certain operations, including those exposed via the graphical interface. This capability has been used by Microsoft Exchange Server 2007 to expose its management functionality as PowerShell cmdlets and providers and implement the graphical management tools as PowerShell hosts which invoke the necessary cmdlets.[8][10] Other Microsoft applications including Microsoft SQL Server 2008 also expose their management interface via PowerShell cmdlets.[11]
    * PowerShell includes its own extensive, console-based help (similar to man pages in Unix shells) accessible via the Get-Help cmdlet. Updated local help contents can be retrieved from the Internet via the Update-Help cmdlet. Alternatively, help from the web can be acquired on a case-by-case basis via the -online switch to Get-Help.
 
### [REFERENCE - PowerShell Module Browser](https://learn.microsoft.com/en-us/powershell/module/)

#### Expand-Archive

* Expand-Archive in powershell ?
    * Expand-Archive is a cmdlet in PowerShell that allows you to extract the contents of an archive file, such as a ZIP file.
    * Syntax:
        * `Expand-Archive [-Path] <string> [-DestinationPath] <string> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]`
    * Parameters:
        * -Path: Specifies the path to the archive file you want to expand.
        * -DestinationPath: Specifies the path to the folder where you want to save the expanded files. If the destination folder does not exist, PowerShell creates it for you.
        * -PassThru: Returns an object representing the item with which you are working. By default, this cmdlet does not generate any output.
        * -WhatIf: Shows what would happen if the cmdlet runs. The cmdlet is not run.
        * -Confirm: Prompts you for confirmation before running the cmdlet.
    * Example:
        * Suppose you have a ZIP file at C:\source\example.zip and you want to extract its contents to D:\destination:
        * `Expand-Archive -Path "C:\source\example.zip" -DestinationPath "D:\destination"`
        * After running the above command, the contents of example.zip would be extracted to the D:\destination directory.
        * Expand-Archive is especially useful in automation scripts and other administrative tasks where you might need to handle compressed files without manually intervening or using third-party tools.

#### Get-ChildItem

* Get-ChildItem in powershell ?
    * Get-ChildItem is a cmdlet in PowerShell that retrieves the items (like files and folders) and child items (like files inside a folder) from specified locations.
    * Basic Usage:
        * `Get-ChildItem [-Path] <string[]>`
        * -Path: Specifies the path to the items. If not provided, it defaults to the current location.
    * Commonly Used Parameters:
        * -Recurse or -R: Gets items in the specified locations and in all child items of the locations.
        * -Filter <string>: Gets only the specified items. Wildcards are permitted.
        * -Include <string[]>: Gets only the specified items from the Path. This parameter works only when the command includes the -Recurse parameter.
        * -Exclude <string[]>: Omits the specified items. This parameter is effective only when the command includes the -Recurse parameter.
        * -Hidden: Gets hidden items.
        * -File: Gets only files.
        * -Directory: Gets only directories.
    * Examples:
        * List all items in the current directory:
            * `Get-ChildItem`
        * List all items in a specific directory:
            * `Get-ChildItem -Path C:\Example\`
        * List all .txt files in a directory:
            * `Get-ChildItem -Path C:\Example\ -Filter *.txt`
        * List all items recursively in a directory:
            * `Get-ChildItem -Path C:\Example\ -Recurse`
        * List only directories within a directory:
            * `Get-ChildItem -Path C:\Example\ -Directory`
        * List only files within a directory:
            * `Get-ChildItem -Path C:\Example\ -File`
        * List all .txt and .pdf files recursively, excluding files named example.txt:
            * `Get-ChildItem -Path C:\Example\ -Recurse -Include *.txt, *.pdf -Exclude example.txt`
        * The Get-ChildItem cmdlet provides a flexible way to list and filter items in directories, making it a fundamental tool in many PowerShell scripting scenarios.
     
#### New-Item

* New-Item in powershell ?
    * New-Item is a cmdlet in PowerShell used to create a new item. "Item" in this context is quite broad; it can be a file, directory, or other types of item, depending on the provider. For instance, in the file system provider, items are files and directories.
    * Basic Usage:
        * `New-Item -Path <path> -ItemType <type> -Name <name>`
        * -Path: Specifies the path to the location where you want to create the item.
        * -ItemType: Specifies the type of item to create. Common values are Directory and File for the filesystem provider.
        * -Name: Specifies the name of the item to create.
    * Examples:
        * Create a new directory:
            * `New-Item -Path "C:\Users\YourUsername" -ItemType Directory -Name "NewFolder"`
        * Create a new file:
            * `New-Item -Path "C:\Users\YourUsername\NewFolder" -ItemType File -Name "example.txt"`
        * Create a new file with content:
            * `New-Item -Path "C:\Users\YourUsername\NewFolder" -ItemType File -Name "example.txt" -Value "Hello, World!"`
        * Using shorthand:
            * For creating directories, you can often omit -ItemType:
                * `New-Item "C:\Users\YourUsername\AnotherNewFolder"`
            * Similarly, for files:
                * `New-Item "C:\Users\YourUsername\NewFolder\anotherExample.txt"`
        * Creating items in other providers:
            * For instance, in the registry provider, you might create a new registry key or value.
    * Notes:
        * If the specified item already exists, New-Item will throw an error. If you want to check if an item exists and only create it if it doesn't, you would need to wrap your New-Item command in an if statement that checks for the item's existence.
        * The -Force parameter can be used to force the command to run without asking for user confirmation.
        * It's always a good idea to check the documentation or use Get-Help New-Item to see the full range of parameters and their descriptions when working with a cmdlet in PowerShell.

#### Remove-Item

* Remove-Item in powershell ?
    * In PowerShell, the Remove-Item cmdlet is used to delete one or more items, which can be files, folders, registry keys, or other types of items depending on the provider.
    * Basic Usage:
        * Delete a single file:
            * `Remove-Item -Path 'C:\path\to\file.txt'`
        * Delete a folder:
            * `Remove-Item -Path 'C:\path\to\folder' -Recurse`
    * Parameters:
        * -Path: Specifies the path to the item to remove. Wildcards are accepted.
        * -LiteralPath: Specifies the path to the item to remove, but without interpreting any wildcards. This is useful when filenames contain wildcard characters like `[, ], *, or ?`.
        * -Recurse: If specified, all items in the specified locations will be removed. Useful for deleting folders and their contents.
        * -Force: Forces the removal of an item, without prompting for confirmation. This can also help in deleting hidden or read-only files.
        * -WhatIf: Shows what would happen if the cmdlet runs. The cmdlet is not run.
        * -Confirm: Prompts you for confirmation before running the cmdlet.
    * Examples:
        * Delete multiple files:
            * `Remove-Item -Path 'C:\path\to\*.txt' -Force`
        * Delete a directory and its contents:
            * `Remove-Item -Path 'C:\path\to\folder' -Recurse -Force`
        * Delete a file without interpreting wildcards:
            * `Remove-Item -LiteralPath 'C:\path\to\[file].txt'`
        * Check what would be deleted without actually deleting:
            * `Remove-Item -Path 'C:\path\to\folder' -Recurse -WhatIf`
    * Always be cautious when using Remove-Item, especially with the -Force and -Recurse flags, as it can lead to unintended data loss. It's a good practice to use the -WhatIf parameter first to see what would be deleted before actually running the command.

#### Write-Output

* Write-Output in powershell ?
    * Write-Output is a cmdlet in PowerShell that sends the specified objects to the next command in the pipeline. If the command is the last command in the pipeline, the objects are displayed in the console.
    * Basic Usage:
        * `Write-Output "Your message here"`
    * Examples:
        * Display a simple message:
            * `Write-Output "Hello, World!"`
        * Output a list of numbers:
            * `Write-Output 1,2,3,4,5`
        * Using variables:
        ```sh
        $name = "Alice"
        Write-Output "Hello, $name!"
        ```
        * Piping output to another cmdlet:
            * `Write-Output 1,2,3,4,5 | ForEach-Object { $_ * 2 }`
            * This would multiply each number in the list by 2 and display the results.
        * Sending multiple items as separate pipeline elements:
            * `Write-Output "First line", "Second line", "Third line"`
            * Each string is sent as a separate pipeline element.
            * Write-Output is useful when you want to ensure that the output is sent to the pipeline and not just displayed on the screen. However, in most day-to-day scripting in PowerShell, you might see just the object or string on its own or use the simpler Write-Host cmdlet to print something directly to the console.
    * Remember, while both Write-Output and Write-Host can display information to the console, there's a key difference:
        * Write-Output sends objects down the pipeline.
        * Write-Host displays information directly to the console and doesn't pass any output objects to the pipeline.

#### Test-Path

* Test-Path in powershell ?
    * In PowerShell, Test-Path is a cmdlet that allows you to determine if a particular path (like a file or a folder) exists. This can be useful in scripts or functions where you need to take different actions based on the presence or absence of a file or folder.
    * Basic Usage:
        * `Test-Path -Path "C:\path\to\your\file_or_folder"`
        * If the path exists, it will return $true. Otherwise, it will return $false.
    * Examples:
        * Check if a file exists:
            * `Test-Path -Path "C:\Users\Username\Documents\example.txt"`
        * Check if a directory exists:
            * `Test-Path -Path "C:\Users\Username\Documents\ExampleFolder"`
        * Check for a wildcard match:
            * `Test-Path -Path "C:\Users\Username\Documents\*.txt"`
            * This will return $true if there's at least one .txt file in the specified directory.
        * Using with conditional statements:
        ```sh
        if (Test-Path -Path "C:\Users\Username\Documents\example.txt") {
            Write-Host "File exists!"
        } else {
            Write-Host "File does not exist."
        }
        ```
    * Parameters:
        * -Path: Specifies the path to be tested. You can also pipe a path to Test-Path.
        * -LiteralPath: Like -Path, but doesn't recognize characters like * or ? as wildcards.
        * -IsValid: Returns $true if the path is syntactically valid, regardless of whether the items exist.
        * -PathType: Tests the type of item at the path. Valid values are Any, Container, and Leaf. "Container" generally refers to directories, and "Leaf" refers to files.
    * This cmdlet is especially useful for ensuring a file or directory's existence before trying operations that might fail or produce errors if the item doesn't exist.

## FAQ

* How to add host in Windows ?
  * code %windir%\system32\drivers\etc\hosts
  * [Create a new Windows hosts file](https://support.norton.com/sp/en/au/home/current/solutions/v72822654)
* How to check all environment variables ?
```sh
ls env:
dir env:
```
* How to check PowerShell version ?
  * $PSVersionTable.PSVersion
  * [How to Check your PowerShell Version (All the Ways!)](https://adamtheautomator.com/powershell-version/)
* How to check if process is in deadlock ?
    * Task Manager > Performance > Open Resource Monitor > Select process > Analyze Wait Chain...
* How to check if TCP port is open ?
  * [How do I know if a TCP port is open or closed? - Synology Knowledge Center](https://kb.synology.com/en-global/DSM/tutorial/Whether_TCP_port_is_open_or_closed)
    * `telnet www.example.com 1723`
  * [How to Check Which Ports Are Open on a Windows 10 PC](https://www.alphr.com/how-to-check-which-ports-open-windows-10-pc/#:~:text=Windows%2010%20Open%20Ports%20FAQs&text=Run%20the%20Command%20Prompt%20as,to%20the%20local%20IP%20address.)
    * `netstat -ab`
* How to create a MiniDump for a process when it crashes ?
  * [Arnavion/crashdump: An example of an out-of-process crash dumper](https://github.com/Arnavion/crashdump)
    * Demonstrates how to have a C process (crasher.exe) have a stack trace and minidump taken if it crashes. Both are done by another process (dumper.exe), which is crucial to getting a dump with a sane stack trace.
    * crasher registers an exception handler with SetUnhandledExceptionFilter. This handler starts dumper and waits for it to exit. It passes its process ID, thread ID, and exception pointers (containing the context record) to dumper in the commandline. The exception pointer is useful because it contains the context of the original exception instead of the current context (inside the exception handler). crasher then waits for dumper to finish (but see miscellaneous 1 below).
    * On startup, dumper use the process and thread IDs from its commandline to open handles to crasher. Then it uses some calls to ReadProcessMemory to fetch dumper's exception pointers and context record. It then uses this context record to set up the original stack frame and starts walking the stack using StackWalk64. It also uses the Sym* API to load crasher's PDB and other PDBs so that it can print function names, and parameter names and values for each frame. This verbose code is under printStack(), and is mostly composed of interpreting the types of the function parameters and extracting their values into human-readable form.
    * Lastly, dumper uses MiniDumpWriteDump to write a minidump.
    * The motivation to have a stack printer separate from a minidump writer is to cover the cases where the user of crasher may be concerned about private data in the dump that they would not like to share with you. With a textual stack trace, they can vet it to strip private data before sending it to you.
  * [How to write Mini Dump on software crash - Mecanik Dev](https://mecanik.dev/2020/09/24/how-to-write-mini-dump-on-software-crash/)
    * That’s not a solution because there are functions in place for these situations in Windows API. More simply put, you can make your software write a Mini Dump upon crash and then you can just open it inside Visual Studio (or whatever debugger you want) and see exactly where it crashed.
  * [c++ - Creating a MiniDump of a running process - Stack Overflow](https://stackoverflow.com/questions/2598615/creating-a-minidump-of-a-running-process)
  * [Crash Dump Analysis - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/dxtecharts/crash-dump-analysis)
    * Not all bugs can be found prior to release, which means not all bugs that throw exceptions can be found before release. Fortunately, Microsoft has included in the Platform SDK a function to help developers collect information on exceptions that are discovered by users. The MiniDumpWriteDump function writes the necessary crash dump information to a file without saving the whole process space. This crash dump information file is called a minidump. This technical article provides info about how to write and use a minidump.
  * [DbgHelp Functions - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/debug/dbghelp-functions)
  * [Minidump Files - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/debug/minidump-files)
    * Applications can produce user-mode minidump files, which contain a useful subset of the information contained in a crash dump file. Applications can create minidump files very quickly and efficiently. Because minidump files are small, they can be easily sent over the internet to technical support for the application.
    * A minidump file does not contain as much information as a full crash dump file, but it contains enough information to perform basic debugging operations. To read a minidump file, you must have the binaries and symbol files available for the debugger.
  * [MiniDumpWriteDump function (minidumpapiset.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/minidumpapiset/nf-minidumpapiset-minidumpwritedump)
    * Writes user-mode minidump information to the specified file.
  * [MINIDUMP_EXCEPTION_INFORMATION (minidumpapiset.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/minidumpapiset/ns-minidumpapiset-minidump_exception_information)
    * Contains the exception information written to the minidump file by the MiniDumpWriteDump function.
  * [GetLastError function (errhandlingapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-getlasterror)
    * Retrieves the calling thread's last-error code value. The last-error code is maintained on a per-thread basis. Multiple threads do not overwrite each other's last-error code.
  * [SetErrorMode function (errhandlingapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-seterrormode)
    * Controls whether the system will handle the specified types of serious errors or whether the process will handle them.
  * [SetUnhandledExceptionFilter function (errhandlingapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-setunhandledexceptionfilter)
    * Enables an application to supersede the top-level exception handler of each thread of a process.
    * After calling this function, if an exception occurs in a process that is not being debugged, and the exception makes it to the unhandled exception filter, that filter will call the exception filter function specified by the lpTopLevelExceptionFilter parameter.
    * Return value
      * The SetUnhandledExceptionFilter function returns the address of the previous exception filter established with the function. A NULL return value means that there is no current top-level exception handler.
  * [UnhandledExceptionFilter function (errhandlingapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-unhandledexceptionfilter)
    * An application-defined function that passes unhandled exceptions to the debugger, if the process is being debugged. Otherwise, it optionally displays an Application Error message box and causes the exception handler to be executed. This function can be called only from within the filter expression of an exception handler.
  * [Exception-Handling Constants | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/c-runtime-library/exception-handling-constants?view=msvc-170)
    * The constant EXCEPTION_CONTINUE_SEARCH, EXCEPTION_CONTINUE_EXECUTION, or EXCEPTION_EXECUTE_HANDLER is returned when an exception occurs during execution of the guarded section of a try-except statement. The return value determines how the exception is handled. For more information, see try-except Statement in the C++ Language Reference.
  * [CreateProcessW function (processthreadsapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessw)
    * Creates a new process and its primary thread. The new process runs in the security context of the calling process.
    * If the calling process is impersonating another user, the new process uses the token for the calling process, not the impersonation token. To run the new process in the security context of the user represented by the impersonation token, use the CreateProcessAsUser or CreateProcessWithLogonW function.
  * [GetModuleFileNameW function (libloaderapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/libloaderapi/nf-libloaderapi-getmodulefilenamew)
    * Retrieves the fully qualified path for the file that contains the specified module. The module must have been loaded by the current process.
    * To locate the file for a module that was loaded by another process, use the GetModuleFileNameEx function.
  * [What happens to custom unhandled exception filters if a debugger is not running? - The Old New Thing](https://devblogs.microsoft.com/oldnewthing/20180726-00/?p=99345)
  * [How to debug application using SetUnhandledExceptionFilter function for exception handling.](https://microsoft.public.vc.language.narkive.com/1vxrvZ1J/how-to-debug-application-using-setunhandledexceptionfilter-function-for-exception-handling)
  * [Effective Exception Handling in Visual C++ - CodeProject](https://www.codeproject.com/Articles/207464/Exception-Handling-in-Visual-Cplusplus)
    * This article describes the standard techniques of handling exceptions and errors in Visual C++ programs running in Windows.
  * [calloc | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/c-runtime-library/reference/calloc?view=msvc-170)
    * Allocates an array in memory with elements initialized to 0.
  * [sprintf_s, _sprintf_s_l, swprintf_s, _swprintf_s_l | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/c-runtime-library/reference/sprintf-s-sprintf-s-l-swprintf-s-swprintf-s-l?view=msvc-170)
    * Write formatted data to a string. These are versions of sprintf, _sprintf_l, swprintf, _swprintf_l, __swprintf_l with security enhancements as described in Security Features in the CRT.
  * How to compress dump file ?
    * cdb -c ".dump small.dmp; q" -z big.dmp
    * [CDB Command-Line Options - Windows drivers | Microsoft Docs](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/cdb-command-line-options)
      * -c " command "
        * Specifies the initial debugger command to run at start-up. This command must be surrounded with quotation marks. Multiple commands can be separated with semicolons. (If you have a long command list, it may be easier to put them in a script and then use the -c option with the $<, $><, $><, $$>< (Run Script File) command.)
      * -z DumpFile
        * Specifies the name of a crash dump file to debug. If the path and file name contain spaces, this must be surrounded by quotation marks. It is possible to open several dump files at once by including multiple -z options, each followed by a different DumpFile value. For details, see Analyzing a User-Mode Dump File.
    * [Debugging Using CDB and NTSD - Windows drivers | Microsoft Docs](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-using-cdb-and-ntsd)
    * [Analyzing a User-Mode Dump File - Windows drivers | Microsoft Docs](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/analyzing-a-user-mode-dump-file)
    * [.dump (Create Dump File) - Windows drivers | Microsoft Docs](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/-dump--create-dump-file-)
      * The .dump command creates a user-mode or kernel-mode crash dump file.
  * [学会这个绝招，让 C++ 崩溃无处可逃！](https://mp.weixin.qq.com/s/mHYBFB0PuN4kDtj_j51gUQ)
    * Breakpad 是 Google 用 C++ 编写的一个开源、跨平台的崩溃报告系统，它支持 Windows、Linux 和 macOS，并提供了一个上传器，可以在进程崩溃时向一个配置好的 URL 提交 minidump 文件。
    * 目前，有很多大型项目都在使用 Breakpad，例如：Google Chrome、Firefox、Google Picasa、Camino、Google Earth 等。
    * 主页：https://chromium.googlesource.com/breakpad/breakpad/
    * 文档：https://chromium.googlesource.com/breakpad/breakpad/+/HEAD/docs
    * GitHub 地址：https://github.com/google/breakpad
* How to edit environmet variables ?
  * [How to edit, clear, and delete environment variables in Windows - Digital Citizen](https://www.digitalcitizen.life/remove-edit-clear-environment-variables/)
* How to lock files ?
  * You can simply use the Win32 API CreateFile and then specify no sharing rights. This will ensure that no other processes can access the file.
  * The dwShareMode DWORD specifies the type of sharing you would like, for example GENERIC_READ. If you specify 0 then that means no sharing rights should be granted.
  ```c++
  HANDLE hFile = CreateFile(_T("c:\\file.txt"), GENERIC_READ, 0, NULL, OPEN_EXISTING, 0, NULL);
  ```
  * If you want to only lock a certain part of the file you can use LockFile or LockFileEx.
  ```c++
  //Lock the first 1024 bytes
  BOOL bLocked = LockFile(hFile, 0, 0, 1024, 0);
  ```
  * [Locking files using C++ on Windows - Stack Overflow](https://stackoverflow.com/questions/853805/locking-files-using-c-on-windows)
  * [CreateFileA function (fileapi.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-createfilea?redirectedfrom=MSDN)
  * [c++ - Using std:fstream how to deny access (read and write) to the file - Stack Overflow](https://stackoverflow.com/questions/839856/using-stdfstream-how-to-deny-access-read-and-write-to-the-file)
* How to read from registry ?
  * [ReadStringsFromRegistry/README.md at master · GiovanniDicanio/ReadStringsFromRegistry](https://github.com/GiovanniDicanio/ReadStringsFromRegistry/blob/master/README.md)
    * To retrieve a string value from the Windows registry, the Win32 RegGetValue() API can be used.
  * [c++ - How to read a value from the Windows registry - Stack Overflow](https://stackoverflow.com/questions/34065/how-to-read-a-value-from-the-windows-registry)
    * Since Windows >=Vista/Server 2008, RegGetValue is available, which is a safer function than RegQueryValueEx. No need for RegOpenKeyEx, RegCloseKey or NUL termination checks of string values (REG_SZ, REG_MULTI_SZ, REG_EXPAND_SZ).
    * [C++ - Use Modern C++ to Access the Windows Registry | Microsoft Docs](https://docs.microsoft.com/en-us/archive/msdn-magazine/2017/may/c-use-modern-c-to-access-the-windows-registry)
  * [RegGetValueA function (winreg.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetvaluea)
    * Retrieves the type and data for the specified registry value.
  * [RegGetValueW function (winreg.h) - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetvaluew)
    * Retrieves the type and data for the specified registry value.
  * [Registering Classes | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/windows/desktop/automat/registering-classes?redirectedfrom=MSDN)
  * [windows - How to find an absolute path to DLL registered in registry with C++? - Stack Overflow](https://stackoverflow.com/questions/15265837/how-to-find-an-absolute-path-to-dll-registered-in-registry-with-c)
    * SOFTWARE\Classes\WOW6432Node\CLSID\{CLSID}\InprocServer32
  * [CLSID Key - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/com/clsid-key-hklm)
    * A CLSID is a globally unique identifier that identifies a COM class object. If your server or container allows linking to its embedded objects, you need to register a CLSID for each supported class of objects.
  * [c# - How to get the default value of key from the registry - Stack Overflow](https://stackoverflow.com/questions/45349967/how-to-get-the-default-value-of-key-from-the-registry)
    * Instead of using "(Default)", you'll need to use an empty string ("").
* How to get UNC path of local folder ?
  * [windows - UNC path to a folder on my local computer - Stack Overflow](https://stackoverflow.com/questions/2787203/unc-path-to-a-folder-on-my-local-computer)
    * If you're going to access your local computer (or any computer) using UNC, you'll need to setup a share. If you haven't already setup a share, you could use the default administrative shares. Example: 
    * \\localhost\c$\my_dir
  * [What is Universal Naming Convention (UNC)? - Definition from WhatIs.com](https://whatis.techtarget.com/definition/Universal-Naming-Convention-UNC)
    * In a network, the Universal Naming Convention (UNC) is a way to identify a shared file in a computer without having to specify (or know) the storage device it is on. 
    * In Windows operating systems, the UNC name format is:
    * \\servername\sharename\path\filename
* How to modifying the "Path to executable" of a windows service ?
    * [Modifying the "Path to executable" of a windows service - Stack Overflow](https://stackoverflow.com/questions/7190480/modifying-the-path-to-executable-of-a-windows-service)
      * It involves editing the registry, but service information can be found in HKEY_LOCAL_MACHINE\System\CurrentControlSet\Services. Find the service you want to redirect, locate the ImagePath subkey and change that value.
      * Or There is also this approach seen on SuperUser which uses the sc command line instead of modifying the registry
* What's Maximum Path Length Limitation on Windows ?
    * [Maximum Path Length Limitation - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/fileio/maximum-file-path-limitation?tabs=cmd)
      * In the Windows API (with some exceptions discussed in the following paragraphs), the maximum length for a path is MAX_PATH, which is defined as 260 characters. A local path is structured in the following order: drive letter, colon, backslash, name components separated by backslashes, and a terminating null character. 
      * [Naming Files, Paths, and Namespaces - Win32 apps | Microsoft Docs](https://docs.microsoft.com/en-us/windows/win32/fileio/naming-a-file)
* How to map network driver on Windows ?
  * Computer -> Map Network Drive -> Folder : \\\server.au\usrname  -> DOMAIN/USRNAME
* How to restore right-click menu to classic one in Win11 ?
  * [How to Restore Right-Click Context menu in Windows 11. - wintips.org - Windows Tips & How-tos](https://www.wintips.org/how-to-restore-right-click-context-menu-in-windows-11/)
