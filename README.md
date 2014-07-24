Awesome OCaml
=============

A curated list of awesome OCaml tools, frameworks, libraries and articles.  
Fork and create a Pull Request to contribute!

(_Inspired by [awesome-python](https://github.com/vinta/awesome-python). Discover more [awesomeness](https://github.com/bayandin/awesome-awesomeness)._)

## Contents

- [Tools](#tools)
- [Web Development](#web-development)
- [Database Tools](#databas-tools)
- [Concurrency](#concurrency)
- [Graphics](#graphics)
- [Metaprogramming](#metaprogramming)
- [Language-related](#language-related)
- [Serialization](#serialization)
- [Data Processing](#data-processing)
- [Books](#books)
- [Excises](#excises)
- [Community](#community)
- [Online Courses](#online-courses)
- [General](#general)


## Tools

- [OPAM](http://opam.ocamlpro.com/) – A flexible Git-friendly package manager with multiple compiler support.
- [utop](https://github.com/diml/utop) – Universal toplevel for OCaml with support of multiline edition, history, real-time and context sensitive completion, colors, and more.
- [Oasis](http://oasis.forge.ocamlcore.org/) - A tool to integrate a configure, build and install system in your OCaml project. It helps to create standard entry points in your build system and allows external tools to analyse your project easily.
- [obuild](https://github.com/ocaml-obuild/obuild) – Simple package build system for ocaml.
- [Cmdliner](https://github.com/dbuenzli/cmdliner) – Declarative definition of command line interfaces for OCaml.
- [ctypes](https://github.com/ocamllabs/ocaml-ctypes) – Library for binding to C libraries using pure OCaml.
- [tuareg mode for emacs](https://github.com/ocaml/tuareg) - An emacs mode enabling sytax highlighting for editing .ml
- [merlin](https://github.com/the-lambda-church/merlin) - Another emacs mode for OCaml, with more comprehensive support


## Web Development

- **Frameworks**:
  - [Opium](https://github.com/rgrinberg/opium) – Sinatra like web toolkit for OCaml.
  - [Eliom](http://ocsigen.org/eliom/) – Eliom is a framework for programming web sites and client/server web applications. It uses very new concepts making programming very different from all other web programming tools, and allowing to write a complex web site in very few lines of code.
  - [Ohm](http://ohm-framework.com/) – Ohm is a web framework for the OCaml language.
- **Tools**:
  - [COW](https://github.com/mirage/ocaml-cow) – Caml on the Web (COW) is a set of parsers and syntax extensions to let you manipulate HTML, CSS, XML, JSON and Markdown directly from OCaml code.
  - [js_of_ocaml](http://ocsigen.org/js_of_ocaml) – Js_of_ocaml is a compiler of OCaml bytecode to Javascript. It makes it possible to run Ocaml programs in a Web browser.
- **Open Source Projecs**:
  - [Cumulus](https://github.com/Cumulus/Cumulus) – Hacker news like website with the OCaml framework Ocsigen


## Database Tools

- [Mongo.ml](http://massd.github.io/mongo/) – An OCaml driver for Mongodb
- [Macaque](https://github.com/ocsigen/macaque) - Macaque is a library for safe and flexible database queries using comprehensions.
- [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) - PG'OCaml provides an interface to PostgreSQL databases for OCaml applications.

## Concurrency

- [What is the state of OCaml's parallelization abilities?](http://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)
- [Developing Applications With Objective Caml – Concurrent Programming](http://caml.inria.fr/pub/docs/oreilly-book/pdf/chap19.pdf)


## Graphics

- [Vg](https://github.com/dbuenzli/vg) – Declarative 2D vector graphics for OCaml.
- [lablqt](https://github.com/Kakadu/lablqt) – Qt5 bindings for OCaml.


## Metaprogramming

- [Syntax extensions without Camlp4: let's do it!](http://www.lexifi.com/blog/syntax-extensions-without-camlp4-lets-do-it)
- [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) – an OCaml dialect for multi-stage programming.


## Language-related

- [OCaml polymorphism example other than template function?](http://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
- [Ocaml - polymorphic print and type losing](http://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)
- [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
- [mikmatch](https://github.com/mjambon/mikmatch) – OCaml pattern-matching extended with regexps
- <http://caml.inria.fr/pub/ml-archives/ocaml-beginners/2003/11/b8036b7a0c1d082111d7a83c8f6dbfbb.en.html>


## Serialization

- [biniou](https://github.com/mjambon/biniou) – Extensible binary data format, like JSON but faster.


## Data Processing

- [React](http://erratique.ch/software/react) – React is an OCaml module for functional reactive programming (FRP). It provides support to program with time varying values: declarative events and signals.
- [easy-format](https://github.com/mjambon/easy-format) – Pretty-printing library for OCaml.


## Books

- [Real World OCaml](https://realworldocaml.org/) by Y. Minsky, A. Madhavapeddy and J. Hickey - Functional programming for the masses.
- [Unix System Programming in OCaml](http://ocamlunix.forge.ocamlcore.org/) by X. Leroy and D. Rémy – Introduction to Unix system programming, with an emphasis on communications between processes.
- [OCaml from the Very Beginning](http://ocaml-book.com/) by J. Whitington - OCaml from the Very Beginning will appeal both to new programmers, and experienced programmers eager to explore functional languages such as OCaml.
- [Pearls of Functional Algorithm Design](http://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383/ref=sr_1_1?s=books&ie=UTF8&qid=1406229921&sr=1-1&keywords=functional+pearls) by Richard Bird - It summaries 30 hard algorithm problems in function programming world. Although it is for Haskell, the algorithm problems are very interesting and trying to solve them in OCaml also helps the thinking of functional programming. Partial solutions in OCaml is [here](https://github.com/MassD/pearls)

## Excises

- [99 problems](https://github.com/MassD/pearls). 99% solutions are [here](https://github.com/MassD/99)

## Community

- [OCaml Planet](http://planet.ocamlcore.org/) – OCaml community feed aggregator.
- [Official OCaml mailing list](http://caml.inria.fr/resources/forums.en.html)

## Online Courses

- [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/courses/cs3110/2011sp/lecturenotes.asp)


## General

- [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
- [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
- [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
- [Why We Use OCaml](http://tech.esper.com/2014/07/15/why-we-use-ocaml/)
- [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
- [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
- [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)
