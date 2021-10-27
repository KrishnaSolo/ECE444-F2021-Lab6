# ECE444-F2021-Lab6

**Note:** Repo was built following https://github.com/mjhea0/flaskr-tdd

### What are the pros and cons of TDD?

TDD is great way to ensure modular code is being written. By requiring developers to write tests
on expected behaviours, the code being written to meet these test will be modularized in terms of
functionality. Refactoring after tests pass also ensures that code is further cleaned up and this
is much easier to do iteratively (as part of TDD) rather than trying to refactor code from x years ago.
TDD also ensures that code being written is testable. Since the code you write has to pass the tests,
it will be designed to be testable. This makes maintaining code easier and makes spotting regressions easier.
TDD, also forces developers to make sure their assumptions are correct. By starting with the test first, developers
need to have a good understanding of the specifications and force them to understand what should the desired
behaviours be in edge cases. This latter component can lead to clarification and identifying flaws in designs
earlier then without using TDD. While TDD has many advantages, it is not perfect. If you are working on a time sensitive
project, TDD will tend to be slower then other developmenet methods. If you are working with legacy code, TDD can be hard
to apply on this older code. TDD is also challenging as writing good test is an art and not all functionalities can be
tested easily. 
