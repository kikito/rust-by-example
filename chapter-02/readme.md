# 2. "Primitives" Comments

* I like that the number sizes are explicit instead of dependant on compiler flags like in C.
* `isize` and `usize` are "Pointer size". No idea what that means.
* Unicode from the start. Nice.
* Unit type `()` is an empty tuple. That is interesting.
* I like the explicitness of suffixes: `1i8` vs `1u64`. The defaults (`i32`, `f64`) seem ok.
* What, exactly, is `mut`? Is it a "type modifier"? A reserved word? Both?

## 2.1 Literals and operators

* Nice quality of life options for numbers: 0x, 0b, 0o and the underscores

## 2.2 Tuples

* `tuple.0` and `tuple.1` are interesting-looking. I seem to remember that pattern of using `.1`
  and `.0` was used in other places as well.
* "simple" destructuring as we have in Lua instead of the complex one they have in modern javascript. Cool.

## 2.3 Arrays and Slices


* So in the previous example transpose was invoked by doing `transpose(matrix)`. On this case the length of an
  array is `xs.len()`. `len` is a method, not a function.






