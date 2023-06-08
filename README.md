README.md

# What is ZigC language anyway?
  
ZigC is a C-like language with a lot of modern concepts introduced in Zig language, and getting rid of a lot of seemingly unnecessary features from C/C++ and embarrassing peculiarities from Zig syntax. 
  
In result, ZigC is easier than C++/Rust, faster than Go/Java, safer than C/C++, familiar than Rust/Zig, smaller than Rust/C++, and more machine friendly than C/C++/Rust/Go.
  
## ZigC added and following features:
  
* Error handling with errorable types. Mandatory error handling. Error as return value.
* Types as values. Strong type checking, type reflections. 
* Allowing developers to run explicit compile time evaluation.
* Generics by compile time type constructors.
* Arbitrary bit width integers, i1, i7, i15, upto i65535.
* Safety by array boundary check, separation of indexable pointers and normal pointers, explicit nullable types, sentinel terminated string.
* General allocator to check double free, use-after-free, dangling pointer and memory leak.
* Built-in test blocks and build framework.
* Concurrency by async/await, suspend/resume.
* Easy SIMD vector computation.
* Seamless embrace of C and libc replacement.
* Universal compiler accommodation of C and C++.
* Extensive crosscompilation.

  
## ZigC removed and following things from C/C++:
  
* no header files, no macros
* no unnecessary loops (while/do while)
* no 'unsigned' keyword
* no increment/decrement '++', '--'
* no class, no inheritance
* no operator overloading
  
## ZigC corrected Zig syntax as follows:
  
* Back to C like syntax from Pascal-like variable, function declaration.
* JSON like struct iniatialization. Array bracket [] for array initialization.
* Simple for loops, removing crapy while/for syntax.
* Semicolon in struct/union, instead of comma.
* Back to switch/case/default.
* Non-null, non-error 'quotation, instead of |capture|.
* Error sets merge A|B, not A||B. Array concat + and mult *, not ++ and **. anyframe(return_type) not anyframe->return_type.
* Public and static.
* Non-public main.
* ! operator, not try ...
* catch (null), instead of 'orelse'.

 
