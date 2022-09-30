# JIT Graveyard
A list of dead JIT compiler projects for CPython.

> Those who fail to learn from history are doomed to repeat it.

  Sir Winston Churchill

### Psyco

An importable extension module that enabled some form of JIT of the eval loop calling
CPython APIs. From the y2k Python 2.0 era. 32-bit x86 only. Python <= 2.6 only.

http://psyco.sourceforge.net/ _(yes, `http` without an `s` - "it's the 90s")_

The authors moved over to PyPy.

### Unladen Swallow

Aimed to use LLVM to build a method-at-a-time JIT for CPython 2.6

https://code.google.com/archive/p/unladen-swallow/

The `--with-computed-gotos` performance boost came from the initial pre-llvm Unladen Swallow work.

### Pyston version 1

Aimed to use LLVM to build a method-at-a-time JIT for CPython 2.6 (spot the similarity with Unladen Swallow)
*and* re-implement the rest of the VM in C++.

https://github.com/pyston/pyston_v1/tree/v1.0

Note Pyston version 2 is a different project and still alive
https://github.com/pyston/pyston

### Skybison

Originally called Pyro, this was Instagram (now Meta)'s attempt at repeating history.

Re-implemented the VM in C++, including an interpreter written in assembly.

https://github.com/facebookexperimental/skybison

### S6

2022's addition to the Graveyard. From an Alphabet research subsidary.

https://github.com/deepmind/s6


