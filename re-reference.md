# Dereferencing:
In many programming languages, variables store values directly. For example, when you declare an integer `int x = 5;` in C, the variable `x` directly holds the value 5. However, there are situations where instead of storing the value directly, you store the address of where that value resides in memory. Such a storage mechanism is called a pointer or a reference.

Dereferencing is the act of accessing the value that a pointer or reference points to. It's like saying, "I don't want to work with the address anymore; I want to work with the actual value at that address."

How Dereferencing Works in Rust
In Rust, the `&` symbol is used to create a reference to a value, and the `*` symbol is used to dereference that reference.

```Rust
let x = 5;          // x holds the value 5 directly.
let y = &x;         // y is a reference to x.
let z = *y;         // z now holds the value 5, obtained by dereferencing y.
```

We declare an integer `x` with a value of `5`.
We then declare `y` as a reference to `x`. This means `y` doesn't hold the value `5`; it holds the memory address where 5 is stored.
Finally, we declare `z` and set it to the dereferenced value of `y` using the `*` symbol. After this operation, `z` will hold the value `5`.

Dereferencing is like looking inside an envelope to read the letter inside. The envelope's address is like the memory address (or the reference), and the letter inside is the actual value. When you dereference, you're opening the envelope to see or modify its contents.
