# Experimental Hello World

This repository contains minimal "Hello, World!" programs implemented in 10 different programming languages.

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
### JavaScript (Node)
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
zig build-exe hello.zig -O ReleaseSmall && ./hello
```

## Example Output
For each language, running the program should output:
```
Hello, World!
```
