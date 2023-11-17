# Attempting to write a c compiler
This is a repo where I am going to put my implementation of a C compiler built following the information in the book
_Writing a C Compiler_ by Nora Sandler published by nostarch press. Currently, this book is in early access. This means that
the version of the book I am basing my work on is most likely not finalized! If you come accross this repo at a later date,
it is very possible, and even likely, that the first edition of the book will be published. There may be significant differences between the early access version that I am using.

## Dependencies
- Node: I am writing this compiler using node `v20.9.0`. I do not make any guarantees about compatibillity with any other version.
- Writing a c-compiler-test-suite: Nora graciously included an entire test suite to accompany every chapter of her book (!wow!). I have simply cloned that entire repository as a sub directory in this repo. I will most likely convert this to a sub-module at a later date. For now, I will simply use whatever version of that test suite is cloned in this repo. Currently, I am using the `comlete-test-suite` branch in that repo.
- The test runner in `./writing-a-c-compiler-test/test-compiler` depends on python 3.8 or newer