# 3. "Custom types" Comments


## 3.1 Structures

Ok so WTF is the `'a` in:

```
struct Person<'a> {
    name: &'a str,
    age: u8,
}
```

Destructuring is cool.

You can write:

```
let Point { x: x, y: y } = p;
```

But you get two warnings because there is a simpler way of writing it:
```
let Point { x, y } = p;
```

## 3.2 Enums

Oh, inspect. Nice.

### 3.2.1 use

I don't like it very much. It reminds me of javascript's `with`.

### 3.2.2 c-like

Nice. And introduces casting.

### 3.2.3 Test case

I think this is the first time where we actually see methods (not functions)

## 3.3 Constants

Again we have this `'strange` things.

This example does not make it clear where the `static` differst from `const`.









