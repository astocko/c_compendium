# The C Compendium

This repository is a compendium of C articles, books, libraries, source code, and tools. The original list was sourced from the blog post [A List of C Resources](http://astocko.com/a-list-of-c-resources/).

- [Articles](#articles)
- [Books](#books)
- [Other Writings](#other-writings)
- [Libraries](#libraries)
- [Source Code](#source-code)
  - [Projects to Study](#projects-to-study)
- [Tools](#tools)
  - [Compilers](#compilers)
    - [C99/C11 Compatibility](#c99c11-compatibility)
  - [Build Systems](#build-systems)
  - [Code Generation/Macros](#code-generationmacros)
  - [Lexer/Parsers](#lexerparsers)
  - [IDE](#ide)
- [Contribute](#contribute)
- [TODO](#todo)

## Articles
* [Organizing Code Files in C and C++](http://www.gamedev.net/page/resources/_/technical/general-programming/organizing-code-files-in-c-and-c-r1798)
* [Quake 2 Source Code Review](http://fabiensanglard.net/quake2/index.php)
* [Zed Shaw's Awesome Debug Macros](http://c.learncodethehardway.org/book/ex20.html)
* [Why should I have written ZeroMQ in C, not C++](http://250bpm.com/blog:4) - A set of articles on the merits of C over C++ from the Martin Sústrik's point of view; controversial but interesting


## Books
* [Expert C Programming](http://www.amazon.com/dp/0131774298/?tag=stackoverfl08-20) - Written for experienced C programmers who want to quickly pick up some of the insights and techniques of experts and master the fine arts of ANSI C, this volume passes on the wisdom of a highly experienced C compiler writer and his colleagues to help programmers reach new heights, and avoid common software pitfalls along the way.
* [Learn C The Hard Way](http://c.learncodethehardway.org/book/) - [Zed Shaw's](http://en.wikipedia.org/wiki/Zed_Shaw) book, a great resource to learn C
* [21st Century C: C Tips from the New School](http://shop.oreilly.com/product/0636920025108.do) - A book to bring old school C programmers into the 21st Century
* [The C Programming Language](http://cm.bell-labs.com/cm/cs/cbook/) - The authors present the complete guide to ANSI standard C language programming.

## Other Writings
* [Comp.Lang.C FAQ](http://c-faq.com/) - This page is the top of an HTML version of the Usenet comp.lang.c Frequently Asked Questions list (also known as the "clc FAQ"). An FAQ list is a collection of questions commonly asked on Usenet, together with presumably definitive answers, provided in an attempt to keep repeated questions on the newsgroup down to a low background drone so that discussion can move on to more interesting matters.
* [ISO C Standard](http://www.open-std.org/jtc1/sc22/wg14/) - The ISO C Standard

## Libraries
* [Apophenia](https://github.com/b-k/apophenia) - Apophenia is an open statistical library for working with data sets and statistical or simulation models. It provides functions on the same level as those of the typical stats package (such as OLS, probit, or singular value decomposition) but gives the user more flexibility to be creative in model-building
* [Blosc](http://www.blosc.org/) - Blosc, an extremely fast, multi-threaded, meta-compressor library
* [GNU Scientific Library](http://www.gnu.org/software/gsl/) - "The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite."
* [Klib: a Generic Library in C](https://github.com/attractivechaos/klib) - A macro heavy C library providing containers and other utilities. Avoids the use of void* for performance.
* [Mongoose](https://code.google.com/p/mongoose/) - An embeddable C http server
* [Nanomsg](http://nanomsg.org/index.html) - An evolution of ZeroMQ, a high performance brokerless message queue
* [SFMT](http://www.math.sci.hiroshima-u.ac.jp/~%20m-mat/MT/SFMT/index.html) - SIMD version of the Mersenne Twister random number generator. Floating point and integer versions
* [TinyCThread](https://tinycthread.github.io/) - Small, portable implementation of the C11 threads API
* [TurboPFor](https://github.com/powturbo/TurboPFor) - Fast integer compression library. Includes random access without decompression.

## Source Code
### Projects to Study
* [Mongrel](https://github.com/zedshaw/mongrel2) - Mongrel2 is an application, language, and network architecture agnostic web server that focuses on web applications using modern browser technologies.
* [LuaJIT](http://repo.or.cz/w/luajit-2.0.git) - LuaJIT is a Just-In-Time Compiler (JIT) for the Lua programming language. Lua is a powerful, dynamic and light-weight programming language. It may be embedded or used as a general-purpose, stand-alone language. http://luajit.org/luajit.html
* [Redis](https://github.com/antirez/redis) - Redis is an in-memory database that persists on disk. The data model is key-value, but many different kind of values are supported: Strings, Lists, Sets, Sorted Sets, Hashes, HyperLogLogs, Bitmaps. 
http://redis.io
* [SQLite](http://www.sqlite.org/src/doc/trunk/README.md) - SQLite is a software library that implements a self-contained, serverless, zero-configuration, transactional SQL database engine. SQLite is the most widely deployed SQL database engine in the world. The source code for SQLite is in the public domain.

## Tools
### Compilers
* [clang](http://clang.llvm.org/) - The goal of the Clang project is to create a new C, C++, Objective C and Objective C++ front-end for the LLVM compiler.
* [icc](https://software.intel.com/en-us/c-compilers) - Intel C/C++ Compiler, also known as icc or icl, is a group of C and C++ compilers from Intel available for OS X, Linux, Windows and Intel-based Android devices
* [GCC](https://gcc.gnu.org/) - The GNU Compiler Collection includes front ends for C, C++, Objective-C, Fortran, Java, Ada, and Go, as well as libraries for these languages (libstdc++, libgcj,...). GCC was originally written as the compiler for the GNU operating system. 
* [MSVC](http://msdn.microsoft.com/en-us/vstudio) - Microsoft Visual Studio Compiler
* [Pelles C](http://www.smorgasbordet.com/pellesc/) - Pelles C is a complete development kit for Windows. It contains among other things an optimizing C compiler, a macro assembler, a linker, a resource compiler, a message compiler, a code signing utility, a make utility and an install builder.
* [TCC](http://bellard.org/tcc/) - The Tiny C Compiler

#### C99/C11 Compatibility
* [clang status](http://clang.llvm.org/compatibility.html#c)
* [icc c99 status](https://software.intel.com/en-us/articles/c99-support-in-intel-c-compiler)
* [gcc c11 status](https://gcc.gnu.org/wiki/C11Status)
* Pelles C - C99/C11 compliant

### Build Systems
* [biicode](https://www.biicode.com/) - C/C++ dependency manager and build system
* [CMake](http://www.cmake.org/) - CMake is a family of tools designed to build, test and package software
* [GYP](https://code.google.com/p/gyp/) - GYP (Generate Your Projects) is a build automation tool. GYP is created by Google to generate native IDE project files (such as Visual Studio and Xcode) for building the Chromium web browser and is licensed as open source software using the BSD software license.
* [Make](http://www.gnu.org/software/make/) - GNU Make is a tool which controls the generation of executables and other non-source files of a program from the program's source files.
* [Ninja](http://martine.github.io/ninja/) - Ninja is a small build system with a focus on speed. It differs from other build systems in two major respects: it is designed to have its input files generated by a higher-level build system, and it is designed to run builds as fast as possible
* [tup](http://gittup.org/tup/) - Tup is a file-based build system for Linux, OSX, and Windows

### Code Generation/Macros
* [Cog](http://nedbatchelder.com/code/cog/) - Code generation tool
* [DynASM](http://luajit.org/dynasm.html) - DynASM is a Dynamic Assembler for code generation engines. DynASM has been developed primarily as a tool for LuaJIT, but might be useful for other projects, too. If you are writing a just-in-time compiler or need to generate code on the fly (e.g. for high-performance graphics or other CPU-intensive computations), DynASM might be just what you are looking for.
* [Jinja](http://jinja.pocoo.org/docs/dev/) - Jinja2 is a modern and designer-friendly templating language for Python, modelled after Django’s templates
* [Warp](https://github.com/facebook/warp) - Alternative performance oriented C/C++ preprocessor implemented in D by Facebook

### Lexer/Parsers
* [Lemon](http://www.hwaci.com/sw/lemon/) - The Lemon program is an LALR(1) parser generator. It takes a context free grammar and converts it into a subroutine that will parse a file using that grammar. Used in SQLite, implemented in two C files: [lemon.c](http://www.sqlite.org/src/artifact?ci=trunk&filename=tool/lemon.c) and [lempar.c](http://www.sqlite.org/src/artifact?ci=trunk&filename=tool/lempar.c).
* [Ragel](http://www.colm.net/open-source/ragel/) - Ragel compiles executable finite state machines from regular languages. Ragel targets C, C++, Obj-C, C#, D, Java, Go and Ruby. Ragel state machines can not only recognize byte sequences as regular expression machines do, but can also execute code at arbitrary points in the recognition of a regular language

### IDE
* [CLion](https://www.jetbrains.com/clion/) - JetBrains' C/C++ IDE
* [Eclipse CDT](https://eclipse.org/cdt/) - The CDT Project provides a fully functional C and C++ Integrated Development Environment based on the Eclipse platform.
* [KDevelop](https://www.kdevelop.org/) - It is a feature-full, plugin extensible IDE for C/C++ and other programming languages.
* [NetBeans](https://netbeans.org/features/cpp/)  - Develop professional native applications in C, C++, and Fortran for a variety of platforms including Windows, Linux, OS X, and the Solaris operating system
* [YouCompleteMe](http://valloric.github.io/YouCompleteMe/) - VIM code completion for C-family and other languages

## Contribute
* Fork and and submit a PR
* Please keep contributions small and manageable

## TODO
* The main priority is adding content and properly categorizing