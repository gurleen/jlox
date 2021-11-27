#jlox
## Gurleen Singh <gs585@drexel.edu>

jlox is an implementation of the Lox language written in Java,
as described by the book [_Crafting Interpreters_ by Bob Nystrom](https://craftinginterpreters.com/).

This is a tree-walk interpreter backed by a recursive descent parser.
All relevant modules are clearly marked in `com.gurleen.lox`.

Examples are in `examples/`. Run them with:
```
<compiled_lox_binary> helloworld.lox
```