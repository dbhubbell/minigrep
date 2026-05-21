# Refactoring
- Split the program into a main.rs and lib.rs
  - The main is the binary entry point and the lib makes it possible to unit test
  - Should parse command line, if not too complicated, do configs, call a run function in lib.rs, and handle any errors that run returns
  - main should handle running the program and lib should handle the logic of the actual work.
  - you can't actually test main, so this is one of the reasons for splitting it out like this

