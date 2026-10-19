# Fortune

Hi, Computers bully me.

```rust
struct Developer {
    name: &'static str,
    age: u8,
    location: &'static str,
    currently_learning: Vec<&'static str>,
    believes_everything_can_be_built_from_scratch: bool,
}

let me = Developer {
    name: "Fortune",
    age: 16,
    location: "Nigeria",
    currently_learning: vec![
        "Rust",
        "Operating Systems",
        "Networking",
        "Distributed Systems",
    ],
    believes_everything_can_be_built_from_scratch: true, // sometimes...
};
```
