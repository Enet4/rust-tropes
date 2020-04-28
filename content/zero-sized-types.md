+++
title = "ZST"
+++

ZST stands for "Zero-Sized Types". The unit type is one example: `()`. [Unit-like structs](https://doc.rust-lang.org/book/ch05-01-defining-structs.html?highlight=unit,struct#unit-like-structs-without-any-fields) are another. The Rust compiler further optimizes your program by compiling these away.
