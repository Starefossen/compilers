## Exercises for Section 1.1

### Exercise 1.1.1

> What is the difference between a compiler and an interpreter?

A compiler produces an executable machine-language program based on the source
program, where the interpreter on the other hand directly executes the
operations specified in the source program on inputs supplied by the user.

### Exercise 1.1.2

> What are the advantages of (a) a compiler over an interpreter (b) an
> interpreter over a compiler?

A compiled program is typically much faster than it's interpreted counterpart
because the target program is machine language.

An interpreted program, however, can be run on any machine where the interpreter
is installed without having to compile the program first.

### Exercise 1.1.3

> What advantages are there to a language-processing system in which the
> compiler produces assembly language rather than machine language?

Assembly language is typically easier to produce than native binary code. It also
fits nicely into the unix philosophy to do one thing well. Let the compiler can
thus be more or less universal without having to worry too much on hardware
specific details which will be job of the assembler.

### Exercise 1.1.4

> A compiler that translates a high-level language into another high-level
> language is called a *source-to-source* translator. What advantages are there
> to using C as a target language for a compiler?

The C-language is more or less universal. Producing C as a target language for
a compiler means that the ultimate program may be run on any machine capable of
running C code. Also, a *source-to-source* translation is typically easier than a
full on compilation to machine-code.

### Exercise 1.1.5

> Describe some of the tasks that an assembler needs to perform.

 * Create object code
 * Resolve symbolic names
 * Macros
 * Instruction set optimization

## Exercises for Section 1.3

### Exercise 1.3.1

> Indicate which of the following terms:

```
    a) imperative         b) declarative  c) von Neumann
    c) object-oriented    d) functional   e) third-generation
    g) fourth-generation  h) scripting
```

> apply to which of the following languages:

```
    1) C      2) C++    3) Cobol    4) Fortran    5) Java
    6) Lisp   7) ML     8) Perl     9) Python    10) VB
```

| Language  | Classification  |
|-----------|-----------------|
| C         | third-generation, imperative, von Neuman      |
| C++       | third-generation, imperative, object-oriented |
| Cobol     | third-generation,
| Fortran   | third-generation, von Neuman
| Java      | third-generation, imperative, object-oriented |
| Lisp      | third-generation,
| ML        | functional
| Perl      | fourth-generation, scripting
| Python    | fourth-generation, scripting
| VB        | third-generation, object-oriented

