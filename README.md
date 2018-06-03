# Stone Code Generation for Rust
This is the pillar we need to do code-gen on the Stone API definitions for Rust.  There are a couple ways we can do this.
1. Use the Stone Python facilities and the Stone backend API to generate Rust.
2. Make a pure Rust code generator with lexers and parsers (oof)
I'm more in favor of the first option, but at the same time, the backend they have is kinda jank, and if we did pure-Rust
codegen, then we would be able to avoid external dependencies (which is nice).
