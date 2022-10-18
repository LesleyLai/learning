# Programming Language Theory & Implementation
## Theories
### Semantics
- [x] 📘 [Practical Foundations for Programming Languages](http://www.cs.cmu.edu/~rwh/pfpl/)
- [x] 📘 [The Formal Semantics of Programming Languages: An Introduction](https://mitpress.mit.edu/books/formal-semantics-programming-languages)
- [ ] 📘 [Essentials of Programming Languages, third edition (The MIT Press)](https://www.amazon.com/Essentials-Programming-Languages-MIT-Press/dp/0262062798)
- [ ] 📘 [Programming Language Concepts (Undergraduate Topics in Computer Science)](https://www.amazon.com/Programming-Language-Concepts-Undergraduate-Computer/dp/1447141555)
- [ ] 📄 [Call-by-name, call-by-value, and the λ-calculus](https://homepages.inf.ed.ac.uk/gdp/publications/cbn_cbv_lambda.pdf)
- [x] 📄 [Implementation Strategies for Mutable Value Semantics](https://www.jot.fm/issues/issue_2022_02/article2.pdf) - About the design of the [Val](https://www.val-lang.dev/) language

### Type System
- [ ] 📘 [Types and Programming Languages](https://mitpress.mit.edu/books/types-and-programming-languages)
- [ ] 📘 [Advanced Topics in Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/attapl/)
- [ ] 📄 [Type systems](http://lucacardelli.name/papers/typesystems.pdf)
- [ ] 🎥 ["Propositions as Types" by Philip Wadler](https://www.youtube.com/watch?v=IOiZatlZtGU)

#### Dependent Typing
- [x] 📘 [The Little Typer](https://mitpress.mit.edu/books/little-typer)

## Implementations

### Overview
- [x] 📘 [Crafting Interpreter](http://www.craftinginterpreters.com/)
- [x] 📄 [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf)
- [ ] 📘 [A Practical Approach to Compiler Construction](https://www.amazon.com/Practical-Approach-Compiler-Construction-Undergraduate/dp/3319527878)
- [ ] 📘 [Engineering: A Compiler](https://www.amazon.com/Engineering-Compiler-Keith-D-Cooper-dp-0128154128/dp/0128154128)
- [ ] 📘 [Modern Compiler Implementation in ML](https://www.amazon.com/Modern-Compiler-Implement-Andrew-Appel/dp/0521607647)
- [ ] 🎓🎥📘 [Fall 2020 IU Compiler Course](https://github.com/IUCompilerCourse/IU-P423-P523-E313-E513-Fall-2020)
    - [website](https://iucompilercourse.github.io/IU-P423-P523-E313-E513-Fall-2020/)

### Compiler Description/Architecture
- [ ] 📘 [An introduction to creating a C compiler for those who want to know the lower layers](https://www-sigbus-info.translate.goog/compilerbook?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en) - Book in Japanese, but the Google translation is readable enough
- [ ] 📄 [A New C Compiler by Ken Thompson](http://c9x.me/compile/bib/new-c.pdf)
- [ ] 📄 [A Tour Through the Portable C Compiler. S. C. Johnson.](http://c9x.me/compile/bib/pcc-tour.pdf)
- [ ] 📘 [A Retargetable C Compiler: Design and Implementation. David R. Hanson and Christopher W. Fraser.](https://www.amazon.com/Retargetable-Compiler-Design-Implementation/dp/0805316701)
- [x] 🎥 [How the TypeScript Compiler Compiles - understanding the compiler internal](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/)
- [ ] 🎥 [Anders Hejlsberg on Modern Compiler Construction](https://channel9.msdn.com/Blogs/Seth-Juarez/Anders-Hejlsberg-on-Modern-Compiler-Construction)
- [ ] 📘 [AOSA book: LLVM](https://aosabook.org/en/llvm.html)
- [x] 🎥 [Responsive compilers - Nicholas Matsakis - PLISS 2019](https://youtu.be/N6b44kMS6OM)

### Type System Implementation
- [ ] 📄 [Compiling Swift generics, Part I](https://forums.swift.org/t/compiling-swift-generics-part-i/60898)

### Compiler Optimization
- [ ] 📘 [Building an Optimizing Compiler](https://keybase.theophile.me/info/morgan-optimizing-compiler.pdf)
- [x] 🎓🎥 [CS 6120: Advanced Compilers](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/)
- [ ] 📄 [What every compiler writer should know about programmers or “Optimization” based on undefined behaviour hurts performance](http://c9x.me/compile/bib/ubc.pdf)
- [ ] 📄 [Constant Propagation with Conditional Branches](http://c9x.me/compile/bib/constpropssa.pdf)
- [ ] 📄 [Global Code Motion Global Value Numbering](http://c9x.me/compile/bib/click-gvn.pdf)

#### Dominators and Static Single Assignment
- [ ] 📘 [The Static Single Assignment Book](http://ssabook.gforge.inria.fr/latest/book.pdf)
- [ ] 📄[Simple and Efficient Construction of Static Single Assignment Form. 2013 Matthias Braun, Sebastian Buchwald, Sebastian Hack, Roland Leißa, Christoph Mallon, and Andreas Zwinkau.](http://c9x.me/compile/bib/braun13cc.pdf)
- [ ] 📄[An Efficient Method of Computing Static Single Assignment Form. Ron Cytron, Jeanne Ferrante, Barry K. Rosen, Mark N. Wegman, and F. Kenneth Zadeck.](http://c9x.me/compile/bib/ssa.pdf)
- [ ] 📄[A Simple, Fast Dominance Algorithm. Keith D. Cooper, Tymothy J. Harvey, and Ken Kennedy.](http://c9x.me/compile/bib/quickdom.pdf)

#### Dynamic Language Optimization
- [ ] 📄 [Optimizing Compiler Technology for SELF, a Dynamically-typed Object-oriented Programming Language](https://dl.acm.org/doi/10.1145/74818.74831)

### Register Allocation
- [ ] 📄 [Linear Scan Register Allocation. Massimiliano Poletto and Vivek Sarkar.](http://c9x.me/compile/bib/linearscan.pdf)
- [ ] 📄 [Linear Scan Register Allocation on SSA Form. Christian Wimmer Michael Franz.](http://c9x.me/compile/bib/Wimmer10a.pdf)
- [ ] 📄 [Iterated Register Coalescing. Lal George and Andrew W. Appel.](http://c9x.me/compile/bib/irc.pdf)
- [ ] 📄 [A Generalized Algorithm for Graph-Coloring Register Allocation. Michael D. Smith, Norman Ramsey, and Glenn Holloway.](http://c9x.me/compile/bib/pcc-rega.pdf)
- [ ] 🔗 [The Solid-State Register Allocator](https://www.mattkeeter.com/blog/2022-10-04-ssra)

### Codegen
- [ ] 📄 [Engineering a Simple, Efficient Code Generator Generator. Christopher W. Fraser, David R. Hanson, and Todd A. Proebsting.](http://c9x.me/compile/bib/iburg.pdf)

### Program Analysis
- [ ] 🎓 [17-355/17-665/17-819 Program Analysis](http://www.cs.cmu.edu/~aldrich/courses/17-355-19sp/)

### Parsing
- [x] 📘 [Crafting Interpreter](http://www.craftinginterpreters.com/) Chapter 4, 6, 16, 17 - 
contains handwritten lexer and recursive descent parser. And chapter 17 is a great overview of Pratt Parsing

#### Partt Parsing
- [ ] 🔗 [Pratt Parsers: Expression Parsing Made Easy](http://journal.stuffwithstuff.com/2011/03/19/pratt-parsers-expression-parsing-made-easy/)
- [ ] 🔗 [Pratt Parsing Index and Updates](https://www.oilshell.org/blog/2017/03/31.html) A "meta-link" that contains various resources on Pratt parsing
- [ ] 🔗 [Top Down Operator Precedence](https://tdop.github.io/) - Original pratt parsing paper
- [ ] 🔗 [Pratt Parsing in Parsec. Perfect.](http://kindlang.blogspot.com/2016/08/pratt-parsing-in-parsec-perfect.html)
- [ ] 🔗 [A Monadic Pratt Parser](https://matthewmanela.com/blog/a-monadic-pratt-parser/)
- [ ] 🔗 Eli Bendersky, [Top-Down operator precedence parsing](https://eli.thegreenplace.net/2010/01/02/top-down-operator-precedence-parsing)

### GC
- [ ] 🔗 [Baby's First Garbage Collector](https://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/) - Mark and sweep. From Bob Nystrom, the same person behind "Crafting Interpreter."
- [x] 📘 [Crafting Interpreter](http://www.craftinginterpreters.com/) Chapter 26 - It introduces tricolor garbage collection.
- [ ] 📘 [The Garbage Collection Handbook](https://gchandbook.org/)
- [ ] 📄 [A Unified Theory of Garbage Collection](https://researcher.watson.ibm.com/researcher/files/us-bacon/Bacon04Unified.pdf)
- [ ] 📄 [Deconstructing the Garbage-First Collector](https://users.cecs.anu.edu.au/~steveb/pubs/papers/g1-vee-2020.pdf) - an overview of garbage first collector in HotSpot

### Functional Languages
- [ ] 📘 [The Implementation of Functional Programming Languages](https://www.microsoft.com/en-us/research/wp-content/uploads/1987/01/slpj-book-1987-small.pdf) - by Simon Peyton Jones

### LLVM
- [ ] 🔗 [Understanding the Clang AST](https://lowlevelbits.org/how-to-learn-compilers-llvm-edition/)
- [ ] 🔗 [clang-tutor](https://github.com/banach-space/clang-tutor/)
- [ ] 🔗 [llvm-tutor](https://github.com/banach-space/llvm-tutor)
- [ ] 🎥 [LLVM IR Tutorial - Phis, GEPs and other things, oh my!](https://www.youtube.com/watch?v=m8G_S5LwlTo)
- [ ] 🎥 [2019 LLVM Developers’ Meeting: E. Christopher & J. Doerfert “Introduction to LLVM”](https://www.youtube.com/watch?v=J5xExRGaIIY)

###  Linking and loading
- [ ] 📘 [Advanced C and C++ Compiling](https://www.amazon.com/Advanced-C-Compiling-Milan-Stevanovic/dp/1430266678)
- [ ] 📘 [Linkers & Loaders](https://www.amazon.com/dp/1558604960)
- [ ] 🔗 [Linkers](https://www.airs.com/blog/archives/38) - Blog post series by the author of gold linker

### Machine specific
See [Low Level Programming](low_level_programming.md)

## Education
- [x] 📄 [Towards a Notional Machine for Runtime Stacks and Scope: When Stacks Don’t Stack Up](https://cs.brown.edu/~sk/Publications/Papers/Published/ck-nm-stacks/)