[![Create Release](https://github.com/levrotech/zig-znippets/actions/workflows/release.yaml/badge.svg)](https://github.com/levrotech/zig-znippets/actions/workflows/release.yaml)

# Znippets

This extension contains code snippets for Ziglang for [VSCode][code].

## Snippets

Below is a list of all available snippets and the triggers of each one. Snippets are categorized into the following 📑:

- Standard Library
- Variables
- Pointers
- Types
- Loops

These snippets also contain a helpful description that can further provide you with more information to help you code better 😎

Some snippets have not been added since ZLS provides an ergonomic and always updated version of them 💪

> **_NOTE:_**  The **⇥** means the `TAB` key.

### Standard Library

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `imstd⇥`   | import the standard library into the current scope | `const std = @import ("std");` |
| `writer⇥`   | add the writer to the standard output | `const stdout = std.io.getStdOut.writer();` |

### Variables

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `const⇥`   | declare a constant | `const name: type = ;` |
| `var⇥`   | declare a variable | `var name: type = ;` |

### Pointers

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `ptr⇥`   | declare a pointer | `const name_ptr: *type = &;` <br> `var name_ptr: *type = &;` |
| `ptrλ⇥`   | declare a pointer constants | `const name_ptr: *const type = &;` |

### Types

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `fn⇥`   | declare a function | `fn name() void {}` |
| `fn!⇥`   | declare a function with an error union type | `fn name() !void {}` |
| `pfn⇥`   | declare a public function | `pub fn name() void {}` |
| `pfn!⇥`   | declare a public function with an error union type | `pub fn name() !void {}` |
| `arr⇥`   | declare an array | `const name = [_]type{};` <br> `var name = [_]type{};` |
| `matrix⇥`   | declare a multidimensional array | `const name = [_][_]type{[_]u8{}};` <br> `var name = [_][_]type{[_]u8{}};` |
| `err⇥`   | declare an error set | `const Error = error {};` |
| `enum⇥`   | declare an enum | `const Enum = enum() {};` |
| `struct⇥`   | declare a struct | `const Struct = struct {};` |

### Loops

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `while⇥`   | add a while loop | `while() : () {}` |### Standard Library

### Standard Library

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `imstd⇥`   | import the standard library into the current scope | `const std = @import ("std");` |
| `writer⇥`   | add the writer to the standard output | `const stdout = std.io.getStdOut.writer();` |

[code]: https://code.visualstudio.com/
