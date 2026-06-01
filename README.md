# Hello World in 10 Languages

This repository contains minimal 'Hello, World!' programs written in 10 different programming languages.

## Languages

- [Python](python/hello.py)
- [Rust](rust/hello.rs)
- [Go](go/hello.go)
- [JavaScript (Node)](javascript/hello.js)
- [Ruby](ruby/hello.rb)
- [Java](java/Hello.java)
- [C](c/hello.c)
- [PHP](php/hello.php)
- [Kotlin](kotlin/hello.kt)
- [Zig](zig/hello.zig)

## Instructions

### Python
Run with:
```
python python/hello.py
```

### Rust
Run with:
```
cargo run --manifest-path rust/Cargo.toml
```

Or compile first:
```
cargo build --manifest-path rust/Cargo.toml
./rust/target/debug/experimental_hello_world
```

### Go
Run with:
```
go run go/hello.go
```

Or compile first:
```
go build go/hello.go
./hello
```

### JavaScript (Node)
Run with:
```
node javascript/hello.js
```

### Ruby
Run with:
```
ruby ruby/hello.rb
```

### Java
Compile first, then run:
```
javac java/Hello.java
cd java
java Hello
```

### C
Compile first, then run:
```
gcc c/hello.c -o c/hello
c/c/hello
```

### PHP
Run with:
```
php php/hello.php
```

### Kotlin
Compile first, then run:
```
kotlinc kotlin/hello.kt -include-runtime -d kotlin/hello.jar
kotlin -jar kotlin/hello.jar
```

### Zig
Run with:
```
zig run zig/hello.zig
```
