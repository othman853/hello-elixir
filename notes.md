## Fastest way to get a Hello World

- Define a script file called `hello_world.exs`
- Write the hello world code into the file

Run it:

```sh
elixir hello_world.exs
```

## Compilation and File Extensions

Some file extensions exist to demonstrate different usage intentions. E.g:
- `.ex`: Used to represent code that will be compiled into bytecode
- `.exs`: Used to represent scripting code

A module's bytecode generated from compilation will be stored in a file with `.beam` extension:

``` sh
# math.ex contains the Math module definition
elixirc math.ex
```
Generates `Elixir.Math.beam`.

The pratical difference between `.ex` and `.exs` files is that only `.ex` will generate `.beam` files. Both formats will compile and load
their modules into memory.

All beam files will be available in the REPL if it's started in the folder that contains the `.beam` files.

## Project structure
A project usually contains three folders:
- ebin: contains the compiled bytecode
- lib: contains Elixir files (E.g: .ex files)
- test: contains test files (E.g: .exs files)

## Modules

Modules are groups of functions.
  - Functions can't exist outside a module (?)


