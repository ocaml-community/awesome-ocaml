Awesome OCaml [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=============

<img src="colour-logo.png" width="70%" />

> _**Everything you'll ever need on the road to mastering OCaml.**_

A curated list of references to awesome OCaml tools, frameworks, libraries and articles. Additionally there is a collection of freely available [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books), [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) and [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations).

A community-driven review of the current state of the OCaml ecosystem and its suitability for various programming domains and tasks can be found in:

- [State of the OCaml Ecosystem - August 2015](https://github.com/rizo/awesome-ocaml/blob/master/sotu.md)

Your favorite package is not listed? Fork and [create a Pull Request](https://github.com/rizo/awesome-ocaml/edit/master/README.md) to add it!

If you are beginner and want to learn the basics of OCaml programming here is the [**Beginner's guide to OCaml beginner's guides**](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html).

## Contents

- [Community](#community)
- [Algorithms and Data Structures](#algorithms-and-data-structures)
- [Application Libraries](#application-libraries)
- [Blogs](#blogs)
- [Books](#books)
- [Code Analysis and Linters](#code-analysis-and-linters)
- [Compilers and Compiler Tools](#compilers-and-compiler-tools)
- [Concurrency](#concurrency)
- [Databases](#databases)
- [Developer Tools](#developer-tools)
- [Exercises](#exercises)
- [Formal Software Verification](#formal-software-verification)
- [General](#general)
- [Graphics](#graphics)
- [Language-related](#language-related)
- [Logging](#logging)
- [Metaprogramming](#metaprogramming)
- [Mobile Applications](#mobile-applications)
- [Networking](#networking)
- [Online Courses](#online-courses)
- [Package Management](#package-management)
- [Parallelism](#parallelism)
- [Questions](#questions)
- [Regular Expressions](#regular-expressions)
- [Science and Technical Computing](#science-and-technical-computing)
- [Security](#security)
- [Semantic Technology](#semantic-technology)
- [Serialization](#serialization)
- [System Programming](#system-programming)
- [Testing](#testing)
- [Web Development](#web-development)

* * *


## Community

- [Official OCaml Website](http://ocaml.org/)
- [Official OCaml Mailing List](http://caml.inria.fr/resources/forums.en.html)
- [OCaml Planet](http://ocaml.org/community/planet/)
- [OCaml SubReddit](http://reddit.com/r/ocaml)


## Algorithms and Data Structures

- [Comparing a Machine Learning Algorithm Implemented in F# and OCaml](http://philtomson.github.io/blog/2014/05/29/comparing-a-machine-learning-algorithm-implemented-in-f-number-and-ocaml/)
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) – A generic graph library for OCaml.
- [ods](https://github.com/owainlewis/ods) – A large collection of data structures and algorithms for OCaml.
- [combine](https://github.com/backtracking/combine) – OCaml library for combinatorics <https://www.lri.fr/~filliatr/combine/>.


## Application Libraries

- [Batteries Included](https://github.com/ocaml-batteries-team/batteries-included) – A community-maintained foundation library for your OCaml projects.
- [Cmdliner](https://github.com/dbuenzli/cmdliner) – Declarative definition of command line interfaces for OCaml.
- [Core](https://github.com/janestreet/core) – Jane Street Capital's standard library overlay.
- [React](http://erratique.ch/software/react) – React is an OCaml module for functional reactive programming (FRP). It provides support to program with time varying values: declarative events and signals.
- [ctypes](https://github.com/ocamllabs/ocaml-ctypes) – Library for binding to C libraries using pure OCaml.
- [easy-format](https://github.com/mjambon/easy-format) – Pretty-printing library for OCaml.
- [ocaml-rpc](https://github.com/mirage/ocaml-rpc) – Light library to deal with RPCs in OCaml.
- [ocaml-containers](https://github.com/c-cube/ocaml-containers) – A small standard library extension, string library, and (in "misc") a bunch of random things of lower quality. BSD license.

## Blogs

- [Gagallium](http://gallium.inria.fr/blog/)
- [Type OCaml – Many things about OCaml](http://typeocaml.com)
- [OCaml Platform](https://opam.ocaml.org/blog/)

## Books

- [More OCaml: Algorithms, Methods, and Diversions](http://www.amazon.com/More-OCaml-Algorithms-Methods-Diversions/dp/0957671113/) – In More OCaml John Whitington takes a meandering tour of functional programming with OCaml, introducing various language features and describing some classic algorithms. The book ends with a large worked example dealing with the production of PDF files. There are questions for each chapter together with worked answers and hints.
- [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html) by Allen Downey and Nicholas Monje – How to Think Like a Computer Scientist is an introductory programming textbook based on the OCaml language. It is a modified version of Think Python by Allen Downey. It is intended for newcomers to programming and also those who know some programming but want to learn programming in the function-oriented paradigm, or those who simply want to learn OCaml.
- [OCaml from the Very Beginning](http://ocaml-book.com/) by J. Whitington - OCaml from the Very Beginning will appeal both to new programmers, and experienced programmers eager to explore functional languages such as OCaml.
- [Pearls of Functional Algorithm Design](http://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383) by Richard Bird - It summaries 30 hard algorithm problems in function programming world. Although it is for Haskell, the algorithm problems are very interesting and trying to solve them in OCaml also helps the thinking of functional programming. Partial solutions in OCaml are [here](https://github.com/MassD/pearls).
- [Real World OCaml](https://realworldocaml.org/) by Y. Minsky, A. Madhavapeddy and J. Hickey - Functional programming for the masses.
- [Unix System Programming in OCaml](http://ocamlunix.forge.ocamlcore.org/) by X. Leroy and D. Rémy – Introduction to Unix system programming, with an emphasis on communications between processes.
- [Using, Understanding, and Unraveling OCaml](http://caml.inria.fr/pub/docs/u3-ocaml) – This book describes both the OCaml language and the theoretical grounds behind its powerful type system.
- [Purely Functional Data Structures](http://www.amazon.co.uk/Purely-Functional-Structures-Chris-Okasaki/dp/0521631246/ref=sr_1_1?ie=UTF8&qid=1406279836&sr=8-1&keywords=functional+data+structures) - This is the first or only book focus on various data structures in FP world. A must-read one.
- [OCaml for Scientists](http://www.ffconsultancy.com/products/ocaml_for_scientists/) - by Jon Harrod.

## Code Analysis and Linters

- [Mascot](http://mascot.x9c.fr/) - Mascot is a style-checker for OCaml sources
- [pfff](https://github.com/facebook/pfff) – pfff is a set of tools and APIs to perform some static analysis, dynamic analysis, code visualizations, code navigations, or style-preserving source-to-source transformations such as refactorings on source code.
- [infer](https://github.com/facebook/infer) - infer is a static analyzer for Java, C and Objective-C
- [flow](https://github.com/facebook/flow) - flow is a static type checker for JavaScript


## Compilers and Compiler Tools

- **Compilers Written in OCaml**:
  - [cDuce](http://www.cduce.org/) - cDuce is a modern XML-oriented functional language with innovative features.
  - [Compcert C Compiler](http://compcert.inria.fr/) - It is a C Compiler supporting most of the ISO C90 and C99 / ANSI C  features.
  - [Eff Programming Language](http://www.eff-lang.org/) - Eff is a functional language with handlers of not only exceptions, but also of other computational effects such as state or I/O.
  - [Hack Programming Language](http://hacklang.org/)
  - [Haxe Programming Language](http://haxe.org/)
  - [Neko Programming Language](http://nekovm.org) - Originally the compiler was written in OCaml.
  - [Mezzo Programming Language](http://protz.github.io/mezzo/) - Mezzo is a programming language in the ML tradition, which places strong emphasis on the control of aliasing and access to mutable memory.
  - [OCaml-Java](http://www.ocamljava.org) - OCaml to Java bytecode compiler.
  - [Opa Programming Language](http://opalang.org/)
  - [Rhine](https://github.com/artagnon/rhine-ml) – A Lisp on LLVM written in OCaml.
  - [Rust Programming Language](http://rust-lang.org) - Originally written in OCaml before bootstrapping.
  - [Quick C-- Target Language](http://www.cminusminus.org/) - It is now a dead project. [Github Repo](https://github.com/nrnrnr/qc--). [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).
  - [Others](http://caml.inria.fr/cgi-bin/hump.en.cgi?sort=0&browse=88) - Some other compilers implemented in OCaml, quite a few dead now.
- **Parser and Lexer Generators**:
  - [Opal](https://github.com/pyrocat101/opal) – Self-contained monadic parser combinators for OCaml.
  - [Menhir](http://gallium.inria.fr/~fpottier/menhir) – Menhir is a LR(1) parser generator for OCaml.
  - [ocamllex/ocamlyacc](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) – lex and yacc implementation for OCaml.
- **Articles**:
  - [Kaleidoscope: Implementing a Language with LLVM in Objective Caml¶](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)
  - [Getting started with OCaml bindings for LLVM](http://nopaniers.calepin.co/getting-started-with-ocaml-bindings-for-llvm.html)


## Concurrency

- [Async](http://janestreet.github.io/) — A monadic concurrence library to go with the Core library.
- [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).
- [Lwt](http://ocsigen.org/lwt/) — A cooperative threads library for OCaml.


## Databases

- **Bindings**
  - [Dbm](https://forge.ocamlcore.org/projects/camldbm/) — A binding to the NDBM/GDBM Unix "databases".
  - [Mongo.ml](http://massd.github.io/mongo/) – An OCaml driver for Mongodb
  - [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) — PG'OCaml provides an interface to PostgreSQL databases for OCaml applications.
  - [SQLite3](https://github.com/mmottl/sqlite3-ocaml/) — OCaml bindings to the SQLite3 database.
  - [Sqlite3EZ](https://mlin.github.io/ocaml-sqlite3EZ/) — Thin wrapper for SQLite3 with a simplified interface.
  - [ocaml-redis](https://github.com/0xffea/ocaml-redis) – Redis bindings for OCaml.
  - [mysql](http://ocaml-mysql.forge.ocamlcore.org/) – Bindings to libmysqlclient for interacting with MySQL databases.
  - [mysql_protocol](https://github.com/slegrand45/mysql_protocol) – Implementation of MySQL Protocol with the Bitstring library.
- **New Implementations**
  - [Irmin](https://github.com/mirage/irmin) — A distributed database that follows the same design principles as Git.
  - [Obigstore](http://obigstore.forge.ocamlcore.org/) — A database with BigTable-like data model atop LevelDB.
  - [RunOrg](https://github.com/RunOrg/RunOrg) - It is a WIP database server written in OCaml.
- **Overlays**
  - [Macaque](https://github.com/ocsigen/macaque) — Macaque is a library for safe and flexible database queries using comprehensions on top of PG'OCaml.
  - [ORM](https://github.com/mirage/orm/) — ORM for SQLite.
- **Articles**:
  - [Implementing the Binary Memcached Protocol with Ocaml and Bitstring](http://andreas.github.io/2014/08/22/implementing-the-binary-memcached-protocol-with-ocaml-and-bitstring/)


## Developer Tools

- [Try OCaml](http://try.ocamlpro.com/) – Try OCaml in your web browser.
- [iocaml](https://github.com/andrewray/iocaml) – An OCaml kernel for the IPython notebook.
- [utop](https://github.com/diml/utop) – Universal toplevel for OCaml with support of multiline edition, history, real-time and context sensitive completion, colors, and more.
- [ocp-browser](http://www.typerex.org/ocp-index.html#ocp-browser) — Small ncurses-based API and documentation browser. Provided with ocp-index.
- [ocamlbrowser](http://caml.inria.fr/pub/docs/manual-ocaml/browser.html) — A source and compiled interface browser, written using LablTk. Included in the standard distribution for ocaml <= 4.01 and with labltk for ocaml >= 4.02.
- [ghim](https://github.com/samoht/ghim) – A command-line tool to manage Github Issues.
- [OCaml Yeoman Generator](https://github.com/mabrasil/generator-ocaml) – Yeoman generator to scaffold OCaml modules.
- **Foreign Function Interface**:
  - [ocaml-main-program-in-c](https://github.com/johnwhitington/ocaml-main-program-in-c) – Example build system for making mixed C/Ocaml binaries where the main program is in C.
  - [Modular foreign function bindings](http://openmirage.org/blog/modular-foreign-function-bindings)
- **Editor Plugins**:
  - [merlin](https://github.com/the-lambda-church/merlin) – Context sensitive completion for Ocaml in Vim and Emacs.
  - [tuareg](https://github.com/ocaml/tuareg) - OCaml mode for Emacs that can run the toplevel and the debugger within Emacs.
  - [Sublime better ocaml](https://github.com/whitequark/sublime-better-ocaml) — Better OCaml mode for Sublime Text.
    - [Sublime text package](https://github.com/def-lkb/sublime-text-merlin)
  - [ocp-index](http://www.typerex.org/ocp-index.html) — Easy access to the interface information of installed OCaml libraries for editors like Emacs and Vim.
    - [Sublime text package](https://sublime.wbond.net/packages/OCaml%20Autocompletion)
  - [ocp-indent](http://www.typerex.org/ocp-indent.html) — Indentation tool for OCaml, to be used from editors like Emacs and Vim.
    - [Vim interface](https://github.com/def-lkb/ocp-indent-vim).
- Code coverage
  - [Bisect](http://bisect.x9c.fr/) 
  - [Bisect_ppx](https://github.com/rleonid/bisect_ppx) a more recent fork of the previous tool.


## Exercises

- [99 problems](http://ocaml.org/learn/tutorials/99problems.html). 99% solutions are [here](https://github.com/MassD/99).
- [Rosetta Code](http://rosettacode.org/wiki/Category:OCaml)
- [OCaml at Exercism](http://exercism.io/languages/ocaml) – Exercism is your place to engage in thoughtful conversations about code. Explore simplicity, idiomatic language features, and expressive readable code. [Solutions](https://github.com/exercism/xocaml).


## Formal Software Verification

- [Coq](http://coq.inria.fr/) – Coq is a formal proof management system. It provides a formal language to write mathematical definitions, executable algorithms and theorems together with an environment for semi-interactive development of machine-checked proofs.
- [Why3](http://why3.lri.fr/) – Why3 is a platform for deductive program verification. It provides a rich language for specification and programming, called WhyML, and relies on external theorem provers, both automated and interactive, to discharge verification conditions.
- [Alt-Ergo](http://alt-ergo.lri.fr/) – Alt-Ergo is an open-source SMT solver dedicated to the proof of mathematical formulas generated in the context of program verification.


## General

- [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
- [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
- [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
- [Why We Use OCaml](http://tech.esper.com/2014/07/15/why-we-use-ocaml/)
- [Why OCaml?](http://www.mimisbrunnr.net/~munin/blog/why-ocaml.html)
- [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
- [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
- [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)
- [Why OCaml, why now?](http://spyder.wordpress.com/2014/03/16/why-ocaml-why-now/)
- [A blog about game development in OCaml](http://cranialburnout.blogspot.ca/)
- [(Functional) Alternatives to inheritance](http://ocamltutorials.blogspot.se/2013/06/alternatives-to-subtyping.html)
- [camlPDF](https://github.com/johnwhitington/camlpdf) – OCaml library for reading, writing and modifying PDF files.
- [capnp-ocaml 2.0: The Road to Unembarrassing Performance](http://pelzlpj.github.io/capnp-ocaml/2014/09/02/capnp-ocaml-2.0/)
- [slacko](https://github.com/Leonidas-from-XIV/slacko) – A neat interface for Slack in OCaml.
- [Learn X in Y minutes](https://learnxinyminutes.com/docs/ocaml/) - Where X=OCaml.

## Graphics

- **2D**
  - [archimedes](http://archimedes.forge.ocamlcore.org/) — 2D plotting library.
  - [cairo2](https://github.com/Chris00/ocaml-cairo) — Binding to Cairo, a 2D Vector Graphics Library. Integrates well with lablgtk.
  - [Vg](https://github.com/dbuenzli/vg) – Declarative 2D vector graphics for OCaml.
- **3D**
  - [glMLite](http://www.linux-nantes.org/~fmonnier/OCaml/GL/) — OpenGL bindings for OCaml. Provides an (experimental) functional API.
  - [lablgl](https://forge.ocamlcore.org/projects/lablgl/) — Interface to OpenGL. Integrates well with lablgtk.
  - [tgls](http://erratique.ch/software/tgls) — Thin bindings OpenGL 3.{2,3},4.{0,1,2,3,4} and OpenGL ES {2,3}.
- **GUI**
  - [lablgtk](http://lablgtk.forge.ocamlcore.org/) — GTK2 bindings for OCaml with various higher-level facilities to define GUIs.
  - [lablqt](https://github.com/Kakadu/lablqt) – Qt5 bindings for OCaml.
  - [labltk](https://forge.ocamlcore.org/projects/labltk/) — Interface to the Tcl/Tk GUI framework. In the standard distribution for ocaml <= 4.01.
  - [TSDL](http://erratique.ch/software/tsdl) – Tsdl is an OCaml module providing thin bindings to the cross-platform SDL library.


## Language-related

- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) – OCaml pattern-matching extended with regexps
- [Inlined records in constructors](http://www.lexifi.com/blog/inlined-records-constructors)
- [Algebraic Data Types](http://tech.esper.com/2014/07/30/algebraic-data-types/)
- [XEN – OCaml Best Practices for Developers](http://wiki.xen.org/wiki/OCaml_Best_Practices_for_Developers)
- [OCaml Style Guide](https://github.com/pyrocat101/ocaml-style-guide) - See also: [[1]](https://www.seas.upenn.edu/~cis500/cis500-f06/resources/programming_style.html), [[2]](http://www.cs.cornell.edu/Courses/cs312/2001sp/style.html), [[3]](https://www.seas.upenn.edu/~cis120/current/programming_style.shtml).
- [A safe but strange way of modifying OCaml compiler](https://bitbucket.org/camlspotter/compiler-libs-hack)
- [Fiddling with the OCaml Type System](http://technotroph.wordpress.com/2013/10/25/fiddling-with-the-ocaml-type-system/)



## Logging

- [dolog](https://github.com/UnixJunkie/dolog) – A dumb OCaml logger.
- [Volt](https://github.com/codinuum/volt) – A variant of Bolt OCaml logging tool.


## Metaprogramming

- **Articles**:
  - [A Guide to Extension Points in OCaml](http://whitequark.org/blog/2014/04/16/a-guide-to-extension-points-in-ocaml/)
  - [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
  - [Syntax extensions without Camlp4: let's do it!](http://www.lexifi.com/blog/syntax-extensions-without-camlp4-lets-do-it)
  - [Reading Camlp4 – Ambassador to the Computers](http://ambassadortothecomputers.blogspot.pt/p/reading-camlp4.html)
- **Syntax Extensions**:
  - [ppx_import](https://github.com/whitequark/ppx_import) – Import is a syntax extension that allows to pull in types or signatures from other compiled interface files.
  - [ppx_string_interpolate](https://github.com/sheijk/ppx_string_interpolate) – A simple ppx filter to support string interpolation like `[%str "value of foo is $(foo)"]`.
  - [ppx_monad](https://github.com/m2ym/ppx_monad) – Monad syntax extension for OCaml.
  - [ppx_deriving_yojson](https://github.com/whitequark/ppx_deriving_yojson) – A Yojson codec generator for OCaml.
- **Tools and Language Extensions**:
  - [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) – an OCaml dialect for multi-stage programming.
  - [Fan](http://thinkinginmeta.com/Fan) – Fan is a compile-time metaprogramming system for OCaml, originally inspired from Camlp4. It's a combination of OCaml and Lispy Macros. It shares the same concrete syntax with OCaml.
  - [camlp5](http://camlp5.gforge.inria.fr/) - Camlp5 is a preprocessor-pretty-printer of OCaml.
  - [camlp4](http://caml.inria.fr/pub/docs/manual-camlp4/manual002.html) - Camlp4 is part of the standard OCaml distribution and is different from Camlp5.


## Mobile Applications

- **Articles**:
  - [OCaml on iOS 7 Released](http://psellos.com/2014/08/2014.08.ocamlxarm-402.html)


## Networking

- **HTTP Tools**:
  - [ocaml-cohttp](https://github.com/mirage/ocaml-cohttp) – Very lightweight HTTP server using Lwt or Async.
  - [ocurl](https://github.com/ygrek/ocurl) – OCaml bindings to libcurl.
- **ZeroMQ Bindings**:
  - [ocaml-zmq](https://github.com/issuu/ocaml-zmq) – ZeroMQ bindings for OCaml.
  - [async-zmq](https://github.com/rgrinberg/async-zmq) – Async wrapper around ocaml-zmq.
  - [lwt-zmq](https://github.com/hcarty/lwt-zmq) – Lwt-friendly interface to ZeroMQ for OCaml.
- [ocaml-dns](https://github.com/mirage/ocaml-dns) – A pure OCaml implementation of the DNS protocol.
- [onanomsg](https://github.com/rgrinberg/onanomsg) – nanomsg bindings for OCaml.
- [fluent-logger](https://github.com/fluent/fluent-logger-ocaml) – Fluentd logger for OCaml.


## Online Courses

- [Introduction to Functional Programming in OCaml](https://www.france-universite-numerique-mooc.fr/courses/parisdiderot/56002/session01/about).
- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php).
- [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).
- [University of Illinois] (https://courses.engr.illinois.edu/cs421/fa2014/) - Course that uses OCaml to teach functional programming and programming language design


## Package Management
- **Distribution**:
  - [OPAM](http://opam.ocamlpro.com/) – A flexible Git-friendly package manager with multiple compiler support.
  - [ocamlfind](http://projects.camlcity.org/projects/findlib.html) — Local OCaml library manager. Used by most of the OCaml ecosystem.
  -	[WODI for Windows](http://wodi.forge.ocamlcore.org/) - A package manager for Windows.
  -	[makorel](https://github.com/sagotch/makorel) – Release OPAM packages easily.

- **Build Tools**:
  - [Oasis](http://oasis.forge.ocamlcore.org/) - A tool to integrate a configure, build and install system in your OCaml project. It helps to create standard entry points in your build system and allows external tools to analyse your project easily.
    - [oasis2opam](https://github.com/ocaml/oasis2opam) — Tool to convert OASIS metadata to OPAM package descriptions.
  - [obuild](https://github.com/ocaml-obuild/obuild) – Simple package build system for ocaml.
  - [jenga](https://github.com/janestreet/jenga) – Monadic build system from Jane Street.
  - [ocamlbuild](http://ocaml.org/learn/tutorials/ocamlbuild/) — Build system provided with the compiler.
  - [ocaml-makefile](https://github.com/mmottl/ocaml-makefile) — Easy to use Makefile for small to medium-sized OCaml-projects.
  - [topkg](https://github.com/dbuenzli/topkg) — OPAM-aware packaging system using ocamlbuild.


## Parallelism

(_Note: Sorted from the easier to use to the more flexible._)

- **Libraries**:
  - [Parmap](http://rdicosmo.github.io/parmap/) — Provides easy-to-use parallel map and fold functions.
  - [ForkWork](https://github.com/mlin/forkwork) — A simple library for forking child processes to perform work on multiple cores.
  - [Functory](http://functory.lri.fr/About.html) — A distributed computing library which facilitates distributed execution of parallelizable computations in a seamless fashion.
  - [Rpc.Parallel](https://github.com/janestreet/rpc_parallel) — A library for spawning processes on a cluster of machines, and passing typed messages between them.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html) — An enhanced system platform library. Contains the `netmulticore` library to compute tasks on as many cores of the machine as needed.
  - [Nproc](https://github.com/MyLifeLabs/nproc) – Process pool implementation for OCaml.

- **Articles**:
  - [What is the state of OCaml's parallelization abilities?](http://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)


## Questions

- [OCaml polymorphism example other than template function?](http://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [OCaml - polymorphic print and type losing](http://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)


# Science and Technical Computing

- [biocaml](https://github.com/biocaml/biocaml) – OCaml Bioinformatics Library <http://biocaml.org>.
- [guizmin](https://github.com/pveber/guizmin) – OCaml library for building bioinformatics pipelines.
- [lacaml](https://mmottl.github.io/lacaml/) - OCaml bindings for BLAS/LAPACK (high-performance linear algebra Fortran libraries).
- [onumerical](https://github.com/cheshire/onumerical) – Numerical library for OCaml.
- [oml](https://github.com/hammerlab/oml) - OCaml library for general numerical work.
- [ocephes](https://github.com/rleonid/ocephes) - Bindings to frequently used `C` special funcitons library.

## Regular Expressions

- [Re](https://github.com/ocaml/ocaml-re) – a pure OCaml regular expressions library with combinators, supporting several formats (glob, posix, str...)
- [ocaml-pcre](https://github.com/mmottl/pcre-ocaml) – bindings to the PCRE library (perl-compatible regular expressions)
- [Humane-re](https://github.com/rgrinberg/humane-re) – Humane-re attempts to provide an easy interface for 90% of your regex needs Courtesy of ocaml-re

## Security

- [ocaml-tls](https://github.com/mirleft/ocaml-tls) – TLS in pure OCaml.


## Semantic Technology

- [OCaml-RDF](http://zoggy.github.io/ocaml-rdf/) – OCaml library to manipulate RDF graphs and execute Sparql queries.


## Serialization

- [bencode](https://github.com/rgrinberg/bencode) — Bencode (.torrent file format) reader/writer.
- [biniou](https://github.com/mjambon/biniou) – Extensible binary data format, like JSON but faster.
- [jsonm](http://erratique.ch/software/jsonm) — Non-blocking streaming JSON codec for OCaml.
- [xmlm](http://erratique.ch/software/xmlm) — A streaming codec to decode and encode the XML data format.
- [yojson](http://mjambon.com/yojson.html) — An optimized parsing and printing library for the JSON format.
- [sexplib](https://github.com/janestreet/sexplib) – A S-expression parser and printer


## System Programming

- [Mirage OS](https://github.com/mirage/mirage) – Mirage is a programming framework for constructing secure, high-performance network applications across a variety of cloud computing and mobile platforms.
- [ocaml-fat](https://github.com/mirage/ocaml-fat) – Read and write FAT format filesystems from OCaml.
- [ocaml-git](https://github.com/mirage/ocaml-git) – Pure OCaml low-level git bindings.
- [ocaml-vchan](https://github.com/mirage/ocaml-vchan) – Pure OCaml implementation of the "vchan" shared-memory communication protocol.


## Testing

- [Alcotest](https://github.com/samoht/alcotest) – A lightweight and colourful test framework.
- [OUnit](https://github.com/warrenharris/ounit) – OUnit is a unit test framework for OCaml. It allows one to easily create unit-tests for OCaml code. It is based on HUnit, a unit testing framework for Haskell.
- [QCheck](https://github.com/c-cube/qcheck) — QCheck is a property testing library inspired from Haskell's QuickCheck
- [iTeML](https://github.com/vincent-hugot/iTeML) (formerly known as [qtest](http://batteries.vhugot.com/qtest/))  — supports inline pragma's to generate tests.
- [Kaputt](http://kaputt.x9c.fr) —  comprehensive testing framework.
- [Pa_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) —  General inline testing macro's.
- [TestSimple](https://github.com/hcarty/ocaml-testsimple) - A lightweight unit testing framework compatible with the [Test Anything Protocol](https://testanything.org/).
  
 

## Web Development

- **Frameworks**:
  - [Opium](https://github.com/rgrinberg/opium) – Sinatra like web toolkit for OCaml.
  - [Eliom](http://ocsigen.org/eliom/) – Eliom is a framework for programming web sites and client/server web applications. It uses very new concepts making programming very different from all other web programming tools, and allowing to write a complex web site in very few lines of code.
  - [Ohm](http://ohm-framework.com/) - Ohm was an open source web framework for the OCaml language which is now dead.
  - [webmachine](https://github.com/inhabitedtype/ocaml-webmachine) – A REST toolkit for OCaml. OCaml webmachine is a layer on top of cohttp that implements a state-machine-based HTTP request processor. It's particularly well-suited for writing RESTful APIs. As the name suggests, this is an OCaml port of the webmachine project.

- **Tools**:
  - [COW](https://github.com/mirage/ocaml-cow) – Caml on the Web (COW) is a set of parsers and syntax extensions to let you manipulate HTML, CSS, XML, JSON and Markdown directly from OCaml code.
  - [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)
    has many relevant web libraries —
    [Nethtml](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Nethtml.html)
    html parser,
    [Netasn1](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netasn1.html)
    for ASN.1 parsing,
    [Netencoding](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netencoding.html)
    for Base64, Quoted Printable, URL encoding and HTML escaping,
    [Netmime](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netmime.html)
    for MIME processing, etc. See the [list of
    modules](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/index.html)
    in Ocamlnet's manual.
  - [tyxml](http://ocsigen.org/tyxml) — Library to build valid (according to the W3C spec) Html and Svg trees.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml) – Js_of_ocaml is a compiler of OCaml bytecode to Javascript. It makes it possible to run Ocaml programs in a Web browser.
  - [ocaml-uri](https://github.com/mirage/ocaml-uri) – RFC3986 URI parsing library.
  - [Goji](https://github.com/klakplok/goji) – An OCaml bindings generator for JavaScript libraries.
  - [Syndic](https://github.com/Cumulus/Syndic) – RSS and Atom feed parsing
  - [ocaml-mustache](https://github.com/rgrinberg/ocaml-mustache) – mustache.js logic-less templates in OCaml.
  - [atdjs](https://github.com/barko/atdjs) – atd code generator for OCaml/js_of_ocaml.
  - [jingoo](https://github.com/tategakibunko/jingoo) – OCaml template engine almost compatible with jinja2.
  - [dispatch](https://github.com/inhabitedtype/ocaml-dispatch) – Path-based dispatching for client- and server-side applications.
  - [Lambda Soup](https://github.com/aantron/lambda-soup) - Functional HTML scraping and manipulation with CSS selectors, à la Python's Beautiful Soup.
  - [Markup.ml](https://github.com/aantron/markup.ml) - Error-recovering streaming HTML5 and XML parsers, serializers.

- **Open Source Projects**:
  - [Cumulus](https://github.com/Cumulus/Cumulus) – Hacker news like website with the OCaml framework Ocsigen

* * *

_Inspired by awesome projects line. Discover [more awesomeness](https://github.com/bayandin/awesome-awesomeness) :sparkles:._
