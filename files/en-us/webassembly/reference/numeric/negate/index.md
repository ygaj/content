---
title: Negate
slug: WebAssembly/Reference/Numeric/Negate
page-type: webassembly-instruction
sidebar: webassemblysidebar
---

The **`neg`** instructions, short for _negate_, are used to negate a number. That is, turn a positive number into a negative number and a negative number into a positive number.

{{EmbedInteractiveExample("pages/wat/neg.html", "tabbed-standard")}}

## Syntax

```wasm
;; load a number onto the stack
f32.const 2.7

;; negate
f32.neg

;; the top item on the stack will now be -2.7
```

| Instruction | Binary opcode |
| ----------- | ------------- |
| `f32.neg`   | `0x8c`        |
| `f64.neg`   | `0x9a`        |
