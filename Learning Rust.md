There are really good books out there that already teach you how to learn rust, so my aim is not to really write another one, however I plan to focus on teaching some fundamental concepts to the users of the language. I can start with explaining some of the basics in rust


### Variables in rust
* Variables are of two types in rust it is much like javascript in the way you use let to assign a value to a variable. Variables are immutable in rust, but you can declare them to be mutable by using the keyword `mut`  
* To assign a variable in rust you use `let x = 5`;
* You can also use const which states that the variable is constant and should not be modified.

### Scalar types in rust
-   `bool`: Representing boolean true/false values.
-   `char`: Representing a Unicode scalar value.
-   `i8`, `i16`, `i32`, `i64`, `i128`: Representing signed integers with different sizes.
-   `u8`, `u16`, `u32`, `u64`, `u128`: Representing unsigned integers with different sizes.
-   `f32`, `f64`: Representing single and double precision floating-point numbers.
-   `isize`, `usize`: Representing signed and unsigned integers with the same size as the pointer type on the current platform.



Questions for rust

#### What is the use of the &string in rust  ? 
n Rust, strings are represented by the `String` type, which is part of the standard library. The `&str` type, on the other hand, represents a string slice, which is a reference to a part of a `String`.The reason for this distinction is that `String` is a heap-allocated data structure that can be modified, whereas `&str` is a reference to a string that is stored on the stack and is guaranteed to be immutable.