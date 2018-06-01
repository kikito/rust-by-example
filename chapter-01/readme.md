# 1. "Hello World" comments

## 1 - Hello world
* `rustc` to generate an executable

## 1.1 - Comments

* library docs are integrated. Use `///` comments to document. Markdown allowed. `rustdoc`
* `rustdoc --test` allows *executing the code that you put in the comments*, so you can make executable tests in the comments.
* If you do `cargo test` that also executes those extra tests
* `rustc` for compiling, `rustdoc` for document, but no `rusttest` for tests (cargo instead). That is weird.

## 1.2 - Formatted print
* `println!` throws a *compile-time* error if the string does not match the args!
  (that is because `println!` is a macro, not a regular function)
* The fact that the precision can be also a parameter makes things a bit difficult to understand.


### 1.2.1 - Debug
* The syntax for including traits seems ... too special. I would have done something along the lines of:

    struct Structure(i32): Debug

### 1.2.2 - Display

#### 1.2.2.1 - Testcase: List

### 1.2.3 - Formatting

* Use named parameters to avoid having to duplicate params on the exercise
  (you could also use numbers for the positions, but it would be difficult to read)
* `{r:02X}` is valid but `{r:X02}` isn't. I could not find a place that detailed the order of these things







