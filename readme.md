# How to generate dll from Rust



Use `cargo build --lib` to build the `.dll`/`.so` itself.

Directory tree:

```
│   Cargo.toml
│
└───src/
        lib.rs
        main.rs
```

SEO:  
- Use rust.rs and lib.rs in same project
- Use lib.rs as DLL
- Export normal rust lib as DLL `cargo build --lib` 
- Gen headfile.h  use `cargo run`
- open visual studio project in vc/rustdll.sln
