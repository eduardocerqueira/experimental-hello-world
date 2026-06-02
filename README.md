# Experimental Hello World

This repository contains minimal "Hello, World!" programs implemented in 54 different programming languages.

Every program file begins with a comment naming its language, written in that language's own comment syntax (e.g. `# Python`, `// C`, `-- Haskell`, `; Clojure`, `% Erlang`, `(* OCaml *)`).

## Run Instructions

### Fish shell
```bash
fish hello.fish
```

### Gleam
```bash
gleam run hello.gleam
# or: gleam build && ./build/dev/erlang/hello/beam.snapshot
```

### Wren
```bash
wren hello.wren
```

### Janet
```bash
janet hello.janet
```

## Prerequisites
- Ensure you have the following toolchains installed:
  - Python
  - Rust
  - Go
  - Node.js
  - Ruby
  - Java
  - GCC or Clang for C
  - PHP
  - Kotlin
  - Zig
  - C++
  - TypeScript
  - Swift
  - Haskell
  - Elixir
  - Lua
  - Perl
  - Bash
  - R
  - Dart

## How to Run
### Python
```bash
python hello.py
```
### Rust
```bash
rustc hello.rs && ./hello
```
### Go
```bash
go run hello.go
```
### JavaScript
```bash
node hello.js
```
### Ruby
```bash
ruby hello.rb
```
### Java
```bash
javac hello.java && java Hello
```
### C
```bash
gcc hello.c -o hello && ./hello
```
### PHP
```bash
php hello.php
```
### Kotlin
```bash
kotlinc hello.kt -include-runtime -d hello.jar && java -jar hello.jar
```
### Zig
```bash
zig build-exe hello.zig && ./hello
```
### C++
```bash
g++ hello.cpp -o hello && ./hello
```
### TypeScript
```bash
npx ts-node hello.ts
```
### Swift
```bash
swift hello.swift
```
### Haskell
```bash
runghc hello.hs
```
### Elixir
```bash
elixir hello.exs
```
### Lua
```bash
lua hello.lua
```
### Perl
```bash
perl hello.pl
```
### Bash
```bash
bash hello.sh
```
### R
```bash
Rscript hello.R
```
### Dart
```bash
dart run hello.dart
```
