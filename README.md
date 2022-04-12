# PyConDe2022_Notes


## Pytest

## TDD 

Failing test - Passing Test - REFACTOR

- No new functionality without a failing test
- forced to do small incremental changes
- forced to think about what we do
- refactoring ensures ... well ... refactoring
- 


## Code readability

- no long lines - break up 
- break out virable initialisation
- make room around for loops
- PEP8
- automatic code formatters: black
- Readability is step 0
- comments can improve understandability (""" for multiline """ )
-functions only ever do one thing -- if its not easy to explain it won't be used
- specialised functions vs too general
- classes can make things clearer and cleaner
- Be clear with variable names .. what can you interpret (especially plurals and singulars)
- abbreviations are mentally expensive
- namings communicate intentions
- words can be misleading and even small details can be confusing
- add docstrings to functions

## Aspect-oriented programming
### Diving deep into decorators with Python

- cross cutting concerns z.B.: logging, caching, 
- static method is a function that takes a function and returns a function == Higher order fucntions
- staticmethod(meth()) becomes @staticmethod
- iteration is better than recursion. Recursion impacted by decorators
- class decorators vs metaclasses
- 
