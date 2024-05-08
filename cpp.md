# C++

## Clang

What is the difference between `clang` and `clang++`?

- https://stackoverflow.com/questions/20047218/what-is-the-difference-clang-clang-std-c11

  - `clang`/`clang++` are _drivers_ -- they analyze the input files and choose the 
  appropriate compilers/assemblers/linkers
  - `clang` links only against the `C` standard library
  - `clang++` links against the `C` and `C++` standard library
