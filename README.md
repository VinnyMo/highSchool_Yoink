# High School: Early C++ Experiments

**A collection of my high-school programming projects, notes, and a TI-83 backup.**

I remember working on these around 2012–2013. Several source headers are dated 2013; the Git history reflects their later upload in 2016 and subsequent edits. These are early projects I'm proud to still have, written well before AI coding tools.

The collection moves from loops, arrays, and pointers into linked lists, number theory, and small interactive programs. I've kept the original source and filenames so it's possible to see the work as it was.

## A few places to start

| Project | What it explores |
| --- | --- |
| [Twin-prime search](Find%20Differenct%20of%20Two%20Prime%20Limit.cpp) | Tests pairs of numbers two apart, with “Fast” and “Fancy” display modes |
| [Magic square matrix](MagicSquareMatrixMossman.cpp) | Builds, displays, and checks a magic square; source dated March 18, 2013 |
| [Base conversion](BaseConvertMossman.cpp) | Converts integer representations between supported bases; source dated April 2, 2013 |
| [Factorials and Fibonacci](MossmanFactFib.cpp) | Menu-driven number-sequence calculations; source dated February 9, 2013 |
| [Linked-list project](LinkedListMossman.cpp) | A student-record exercise with insertion, removal, filtering, and GPA calculations; source dated May 6, 2013 |
| [Fraction Action](Mossman%20Fraction%20Action.cpp) | Fraction arithmetic and an interactive console menu |

The twin-prime program is an exploration by computation, not a proof about whether infinitely many twin primes exist. My later prime-number experiments continue in [`funWithPrimes`](https://github.com/VinnyMo/funWithPrimes).

## What else is here

- **C++ fundamentals:** examples covering loops, arrays, strings, pointers, structures, functions, and file input/output
- **Small applications:** bowling scores, book prices, employee records, and pizza cost calculations
- **Working notes:** commented examples and experiments, including [`Threading Experiments.cpp`](Threading%20Experiments.cpp)
- **Calculator backup:** the original [`TI83.tig`](TI83.tig) file

## Reading and running the collection

This repository contains separate exercises and fragments, with no shared build system. Start with one source file and read its comments and includes before trying to compile it.

A few details matter on a modern machine:

- Several files use Windows-specific headers or console calls such as `windows.h`, `system("cls")`, and `system("pause")`.
- Many use `void main()` or renamed entry points, so they may need adaptation for a current standard C++ compiler.
- Some material is incomplete or commented out. For example, `RunComplex.cpp` references a `Complex.cpp` file that is not included here.
- The TI-83 backup is a calculator artifact, separate from the C++ sources.

The original programs have not been modernized as part of this presentation update. Treat them as learning history and inspect them before reuse.

<details>
<summary>Original school artwork</summary>

<img src="images/eastbuchanan-logo.png" alt="East Buchanan school logo from the original README" width="200">

</details>
