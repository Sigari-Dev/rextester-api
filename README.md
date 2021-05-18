# Rextester Api

Simple Python interface for rextester.com, using requests

## Instalation
`git clone https://github.com/Sigari-Dev/rextester-api`

## Usage:


When executing a code using the library it will return RextesterResult object that holds the following attributes:

- `result` - The result of your code
- `warnings` - Any warnings trown by rextester's compiler
- `errors` - Any errors trown by rextester's compiler
- `stats` - The compilation stats: absolute running time, cpu time, memory peak and absolute service time

### usage:

```python
>>> from rextester import Rextester
>>> Rextester("python 3", "print('Hello World')", None).result
Hello World
>>> Rextester("python 3", "print('Hello World')", None).stats
Absolute running time: 0.37 sec, cpu time: 0.05 sec, memory peak: 8 Mb, absolute service time: 0,52 sec
```

## Languages:


```
c#, vb.net, f#, java, python, c (gcc), c++ (gcc), php, pascal, objective-c, haskell, ruby, perl, lua, nasm, sql server, javascript, lisp, prolog, go, scala, scheme, node.js, python 3, octave, c (clang), c++ (clang), c++ (vc++), c (vc), d, r, tcl, mysql, postgresql, oracle, swift, bash, ada, erlang, elixir, ocaml, kotlin, brainfuck, fortran

```

## Channel:

©2021 - <a href=https://t.me/PiniGerTeam>PiniGerTeam™</a>
