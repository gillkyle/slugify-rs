# slug
A small library for generating [slugs][wikipedia] from unicode strings.

Documentation: https://docs.rs/slug

[wikipedia]: https://en.wikipedia.org/wiki/Semantic_URL#Slug

## Usage
```rust
extern crate slug;
use slug::slugify;

let slug = slugify("Hello world");
```

## See

`slug.wasm` for a pre-compiled file that should be useable.

To regenerate, run:

`cargo build --target wasm32-wasi`
