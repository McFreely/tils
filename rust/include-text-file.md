# Include Text files

Instead of loading and parsing a file by hand with the io library, we can use the 
include_str! macro

```rust
const stopwords: &'static str = include_str!("stopwords.txt");
```

[source](https://doc.rust-lang.org/std/macro.include_str!.html)
