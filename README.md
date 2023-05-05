
# What is ZigC language?
  
ZigC is a C language with a lot of modern concepts introduced by Zig language, getting rid of seemingly unnecessary features and some illogical syntax from C/C++. 
  
In result, ZigC is easier than C++/Rust, faster than Go/Java, safer than C/C++, familiar than Rust/Zig, smaller than Go/Rust/C, and more machine friendly than C/C++/Asm/Rust/Go.
  
## ZigC added and following features:
  
* intuitive error handling with composite value or error type -- ex. `int!error`
* compile time processing and generics
* self reference within struct
* arbitrary bit integer, i7 or i15
* ?? 'undefined'
* 'unreacheable'
* @ builtin functions
* test blocks
* ignored variable `_`
  
* return value from if/for/switch block
* array .len and boundary check
* wrap arround operaters `+%, -%, *%, /%`
* optional variables `int?` for possible null or undefined values
* concurrency by suspend/resume/nosuspend, async and await, anyframe
* SIMD vector operations
  
## ZigC removed and following things:
  
* no header files, no macros
* no unnecessary loops (while/do while)
* no 'unsigned' keyword
* no increment/decrement '++', '--'
* no class

