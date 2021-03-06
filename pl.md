# Programming Language Theory & Implementation
## Theories
### Semantics
- [x] 📘 [Practical Foundations for Programming Languages](http://www.cs.cmu.edu/~rwh/pfpl/)
- [x] 📘 [The Formal Semantics of Programming Languages: An Introduction](https://mitpress.mit.edu/books/formal-semantics-programming-languages)
- [ ] 📘 [Essentials of Programming Languages, third edition (The MIT Press)](https://www.amazon.com/Essentials-Programming-Languages-MIT-Press/dp/0262062798)
- [ ] 📘 [Programming Language Concepts (Undergraduate Topics in Computer Science)](https://www.amazon.com/Programming-Language-Concepts-Undergraduate-Computer/dp/1447141555)
- [ ] 📄 [Call-by-name, call-by-value, and the λ-calculus](https://homepages.inf.ed.ac.uk/gdp/publications/cbn_cbv_lambda.pdf)

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
- [ ] 📘 [Engineering: A Compiler](https://www.amazon.com/Engineering-Compiler-Keith-Cooper/dp/012088478X)
- [ ] 📘 [Modern Compiler Implementation in ML](https://www.amazon.com/Modern-Compiler-Implement-Andrew-Appel/dp/0521607647)
- [ ] 📘 [An introduction to creating a C compiler for those who want to know the lower layers](https://www-sigbus-info.translate.goog/compilerbook?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en) - Book in Japanese, but the Google translation is readable enough
- [ ] 🎓🎥📘 [Fall 2020 IU Compiler Course](https://github.com/IUCompilerCourse/IU-P423-P523-E313-E513-Fall-2020)
    - [website](https://iucompilercourse.github.io/IU-P423-P523-E313-E513-Fall-2020/)

### Compiler Optimization
- [x] 🎓🎥 [CS 6120: Advanced Compilers](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/)

#### Dynamic Language Optimization
- [ ] 📄 [Optimizing Compiler Technology for SELF, a Dynamically-typed Object-oriented Programming Language](https://dl.acm.org/doi/10.1145/74818.74831)

### Program Analysis
- [ ] 🎓 [17-355/17-665/17-819 Program Analysis](http://www.cs.cmu.edu/~aldrich/courses/17-355-19sp/)

### Compiler Architecture
- [x] 🎥 [How the TypeScript Compiler Compiles - understanding the compiler internal](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/)
- [ ] 🎥 [Anders Hejlsberg on Modern Compiler Construction](https://channel9.msdn.com/Blogs/Seth-Juarez/Anders-Hejlsberg-on-Modern-Compiler-Construction)
- [ ] 📘 [AOSA book: LLVM](https://aosabook.org/en/llvm.html)

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
