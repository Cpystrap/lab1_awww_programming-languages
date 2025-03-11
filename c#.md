---
layout: default
title: "C#"
permalink: /strona2/c_sharp.md/
---


# ![Logo](https://www.tiobe.com/wp-content/themes/tiobe/tiobe-index/images/C_.png) C#

***

## Description

 C# (/ˌsiː ˈʃɑːrp/ see SHARP)[b] is a general-purpose high-level programming language supporting multiple paradigms. C# encompasses static typing,[16]: 4  strong typing, lexically scoped, imperative, declarative, functional, generic,[16]: 22  object-oriented (class-based), and component-oriented programming disciplines.[17]
 The principal inventors of the C# programming language were Anders Hejlsberg, Scott Wiltamuth, and Peter Golde from Microsoft.[17] It was first widely distributed in July 2000[17] and was later approved as an international standard by Ecma (ECMA-334) in 2002 and ISO/IEC (ISO/IEC 23270 and 20619[c]) in 2003. Microsoft introduced C# along with .NET Framework and Microsoft Visual Studio, both of which are technically speaking, closed-source. At the time, Microsoft had no open-source products. Four years later, in 2004, a free and open-source project called Microsoft Mono began, providing a cross-platform compiler and runtime environment for the C# programming language. A decade later, Microsoft released Visual Studio Code (code editor), Roslyn (compiler), and the unified .NET platform (software framework), all of which support C# and are free, open-source, and cross-platform. Mono also joined Microsoft but was not merged into .NET.


***

| Infobox            | Value                          |
|---------------------|--------------------------------|
| **Paradigm**        | Multi-paradigm:structured,imperative,object-oriented,event-driven,task-driven,functional,generic,reflective,concurrent |
| **Designed by**     | Anders Hejlsberg(Microsoft) |
| **First appeared**  | 2000; 25 years ago(2000)[1] |
| **Developer**       | Mads Torgersen (Microsoft) |
| **Typing discipline** | Static,dynamic,[3]strong,safe,nominative,partly inferred |
| **OS** | N/A |

***

## History
During the development of the .NET Framework, the class libraries were originally written using a managed code compiler system named Simple Managed C (SMC).[22][23] In January 1999, Anders Hejlsberg formed a team to build a new language at the time called COOL, which stood for "C-like Object Oriented Language".[24] Microsoft had considered keeping the name "COOL(C-like Object Oriented Language)" as the final name of the language, but chose not to do so for trademark reasons. By the time the .NET project was publicly announced at the July 2000 Professional Developers Conference, the language had been renamed C#, and the class libraries and ASP.NET runtime were ported to C#.
 Hejlsberg is C#'s principal designer and lead architect at Microsoft, and was previously involved with the design of Turbo Pascal, Embarcadero Delphi (formerly CodeGear Delphi, Inprise Delphi and Borland Delphi), and Visual J++. In interviews and technical papers, he has stated that flaws[25] in most major programming languages (e.g. C++, Java, Delphi, and Smalltalk) drove the fundamentals of the Common Language Runtime (CLR), which, in turn, drove the design of the C# language.
 James Gosling, who created the Java programming language in 1994, and Bill Joy, a co-founder of Sun Microsystems, the originator of Java, called C# an "imitation" of Java; Gosling further said that "[C# is] sort of Java with reliability, productivity and security deleted."[26][27] 
In July 2000, Hejlsberg said that C# is "not a Java clone" and is "much closer to C++" in its design.[28]


***

## Design
The Ecma standard lists these design goals for C#:[17]
 During the development of the .NET Framework, the class libraries were originally written using a managed code compiler system named Simple Managed C (SMC).[22][23] In January 1999, Anders Hejlsberg formed a team to build a new language at the time called COOL, which stood for "C-like Object Oriented Language".[24] Microsoft had considered keeping the name "COOL(C-like Object Oriented Language)" as the final name of the language, but chose not to do so for trademark reasons. By the time the .NET project was publicly announced at the July 2000 Professional Developers Conference, the language had been renamed C#, and the class libraries and ASP.NET runtime were ported to C#.
 Hejlsberg is C#'s principal designer and lead architect at Microsoft, and was previously involved with the design of Turbo Pascal, Embarcadero Delphi (formerly CodeGear Delphi, Inprise Delphi and Borland Delphi), and Visual J++. In interviews and technical papers, he has stated that flaws[25] in most major programming languages (e.g. C++, Java, Delphi, and Smalltalk) drove the fundamentals of the Common Language Runtime (CLR), which, in turn, drove the design of the C# language.


***

## Implementations
Microsoft has developed open-source reference C# compilers and tools. The first compiler, Roslyn, compiles into intermediate language (IL), and the second one, RyuJIT,[119] is a JIT (just-in-time) compiler, which is dynamic and does on-the-fly optimization and compiles the IL into native code for the front-end of the CPU.[120] RyuJIT is open source and written in C++.[121] Roslyn is entirely written in managed code (C#), has been opened up and functionality surfaced as APIs.  It is thus enabling developers to create refactoring and diagnostics tools.[4][122] Two branches of official implementation are .NET Framework (closed-source, Windows-only) and .NET Core (open-source, cross-platform); they eventually converged into one open-source implementation: .NET 5.0.[123] At .NET Framework 4.6, a new JIT compiler replaced the former.[119][124]
 Other C# compilers (some of which include an implementation of the Common Language Infrastructure and .NET class libraries):
 The Unity game engine uses C# as its primary scripting language. The Godot game engine has implemented an optional C# module due to a donation of $24,000 from Microsoft.[125]


***

## Syntax
The core syntax of the C# language is similar to that of other C-style languages such as C, Objective-C, C++ and Java, particularly:
 Some notable features of C# that distinguish it from C, C++, and Java where noted, are:
 By design, C# is the programming language that most directly reflects the underlying Common Language Infrastructure (CLI).[70]  Most of its intrinsic types correspond to value-types implemented by the CLI (Common Language Infrastructure) framework. However, the language specification does not state the code generation requirements of the compiler: that is, it does not state that a C# compiler must target a Common Language Runtime (CLR), or generate Common Intermediate Language (CIL), or generate any other specific format. Some C# compilers can also generate machine code like traditional compilers of Objective-C, C, C++, Assembly and Fortran.[71][72]