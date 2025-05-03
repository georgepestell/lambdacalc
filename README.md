# Simply Typed Lambda Calculus Interpreter

A simple lambda calculus interpreter written in Haskell.

## Features

- Supports lambda expressions and type annotations to be defined and reduced to normal form using Alpha and Beta reduction
- Supports type inference and checking

# System-F Interpreter

The directory `systemf` contains an extended version of the interpreter, implementing basic system-f polymorphism.

# Pre-Requisites

- Requires a Haskell compiler (tested with GHC v.9.0.2)

# Running Instructions

## Simply Typed Lambda Calculus Interpreter

First, go into the `lambdacalc` directory:

```bash
cd lambdacalc`
```

Then, run either:

```
cabal run st
```

or

```
ghci -I src src/Lambda/Main.hs
main
```

## System-F Interpreter

First, go into the `systemf` directory:

```bash
cd systemf`
```

Then, run either:

```
cabal run st
```

or

```
ghci src/Lambda/Main.hs
main
```

## Running Tests

Tests exist for both the basic and system-f implementations in `test` folders in their associated directories. `cd` into the relevant root directory and run:

``bash
cabal test --test-show-details=direct
```
