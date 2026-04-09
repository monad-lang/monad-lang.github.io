# Introduction

The Monad language is currently a hobby project to implement a dependently typed programming language with compatibility with Rust.

## Hello world example

Here is a simple example

```monad
use io

def main : IO Unit := IO.println "Hello, World!"
```
