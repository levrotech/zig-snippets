# Znippets

This extension contains code snippets for Ziglang for [VSCode][code].

## Snippets

Below is a list of all available snippets and the triggers of each one. Snippets are categorized into the following 📑:

- Variables
- Types
- Loops

These snippets also contain a helpful description that can further provide you with more information to help you code better 😎

> **_NOTE:_**  The **⇥** means the `TAB` key.

### Variables

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `const⇥`   | declare a constant | `const name: type = ;` |
| `var⇥`   | declare a variable | `var name: type = ;` |

### Types

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `fn⇥`   | declare a function | `fn name() void {}` |
| `fn!⇥`   | declare a function with an error union type | `fn name() !void {}` |
| `pfn⇥`   | declare a public function | `pub fn name() void {}` |
| `pfn!⇥`   | declare a public function with an error union type | `pub fn name() !void {}` |
| `err⇥`   | declare an error set | `const Error = error {};` |
| `enum⇥`   | declare an enum | `const Enum = enum() {};` |
| `struct⇥`   | declare a struct | `const Struct = struct {};` |

### Loops

| Trigger  | Content | Preview |
| :-------: | ------- | -------- |
| `while⇥`   | add a while loop | `while() : () {}` |

[code]: https://code.visualstudio.com/