# Lox Interpreter in Java

## Build

```
cd java/source
javac -d ../build com/craftinginterpreters/lox/Lox.java
```

## Run

```
cd java/build
java com.craftinginterpreters.lox.Lox [filename]
```

If you supply a filename, the interpreter will attempt to parse it as Lox code. If you don't, the interpreter will start a REPL.
