# Calculator
### To-Do:
1. Develop criteria for an expression class that can carry out basic operations. Keep it basic for now.
2. Write basic tests for expression class before implementing. Let's make sure we do this right

### Classes:
- Matrix
  - Immutable
  - This should only take in coefficient matrices for now
  - Methods:
    - Default constructor and constructor accepting filepath
    - Calculate echelon form
    - Calculate reduced echelon form
    - How will we do matrix equations?
  - Fields:
    - Two-dimensional array (or maybe an array of vectors?)
    - Links to reduced forms?
- Vector
  - Immutable? Should linear combinations change an instance? Maybe this would represent a basis?
  - Methods:
    - GetCombinationsOf?
- Expression/Formula
  - Immutable
  - Might only be used when addressing free variables
  - Methods
    - More or less the same as in Formula for CS 3500
    - Might have to do something unique for variables
  - Fields
    - The condensed string form of a formula
    - A way to store a formula that is easy to evluate
