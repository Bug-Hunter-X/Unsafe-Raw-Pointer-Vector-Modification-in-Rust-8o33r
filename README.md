# Unsafe Raw Pointer Vector Modification in Rust

This repository demonstrates a common error involving unsafe operations in Rust when working with vectors. Modifying a vector's data through a raw pointer is inherently risky as it bypasses Rust's memory safety mechanisms.  The provided example showcases this issue and its potential consequences, emphasizing the importance of using safe alternatives whenever possible.

The `bug.rs` file shows the unsafe code that directly manipulates the vector's underlying memory via a raw pointer.  The `bugSolution.rs` file illustrates how to achieve the desired outcome safely using Rust's built-in methods and avoiding raw pointers.