# JIT Graveyard
A list of dead JIT compiler projects for CPython.

> Those who fail to learn from history are doomed to repeat it.

  Sir Winston Churchill

## The main efforts

### Unladen Swallow

Aimed to use LLVM to build a method-at-a-time JIT for CPython 2.6

https://code.google.com/archive/p/unladen-swallow/

### Pyston version 1

Aimed to use LLVM to build a method-at-a-time JIT for CPython 2.6 (spot the similarity with Unladen Swallow)
*and* re-implement the rest of the VM in C++.

https://github.com/pyston/pyston_v1/tree/v1.0

Note Pyston version 2 is a different project and still alive
https://github.com/pyston/pyston

### Sky Bison

Originally called Pyro, this was Instragram (now Meta)'s attempt at repeating history.

Re-implemented the VM in C++, but used their own back end instead of LLVM.
The back end lives on in Cinder.

https://github.com/facebookexperimental/skybison

### S6

The latest addition to the graveyard and Google's second effort.

https://github.com/deepmind/s6


