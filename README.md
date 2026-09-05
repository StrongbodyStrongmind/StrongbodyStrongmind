<p align="center">
  <img src="./banner.svg" alt="StrongbodyStrongmind - AI Compiler Engineer" width="100%" />
</p>

## AI Compiler Engineer

Focused on TVM, TensorIR, TIR and compiler performance optimization.

`TVM` / `TensorIR` / `TIR` / `Scheduling` / `Lowering` / `CodeGen` / `GPU Performance`

---

## About

I focus on AI compiler optimization, with current work centered on TVM, TensorIR / TIR, and performance-oriented compiler transformations.

My main interest is understanding optimization across the stack:

```text
Tensor IR -> Scheduling -> Compiler Passes -> Lowering -> CodeGen -> Hardware Performance
```

## TVM Compiler Stack

<p align="center">
  <img src="./compiler-pipeline.svg" alt="TVM compiler pipeline from model and graph IR to TensorIR, TIR, CodeGen, runtime, CPU and GPU" width="100%" />
</p>

## Open Source

### Apache TVM

| Contribution | Status | Area |
| --- | --- | --- |
| [apache/tvm#20265](https://github.com/apache/tvm/pull/20265) | Open | TIR lowering: ignore None-valued pragma annotations to avoid invalid AttrStmt values. |

## Featured Work

### [tensortrail](https://github.com/StrongbodyStrongmind/tensortrail)

Educational end-to-end tensor compiler work, focused on the path from Graph IR to Kernel IR, lowering, C CodeGen, native runtime execution, and NumPy-based verification.

### [Apache TVM](https://github.com/StrongbodyStrongmind/tvm)

Studying and contributing to real TensorIR / TIR compiler optimization problems in the Apache TVM stack.

### [gcc-x86-prefetch-opt](https://github.com/StrongbodyStrongmind/gcc-x86-prefetch-opt)

Compiler fundamentals work around x86 prefetch behavior and hardware-aware optimization.

## TVM / TIR Optimization Work

Technical areas I am working on:

```text
TIR transformations
Index simplification and canonicalization
Tensor scheduling
Memory access optimization
GPU thread mapping
Vectorization
Operator performance optimization
Hardware-aware compiler behavior
```

## Current Focus

| Area | Focus |
| --- | --- |
| TVM / TensorIR | Tensor program representation and schedule primitives |
| TIR Pass Design | Correctness-preserving transformations and lowering behavior |
| Tensor Scheduling | Loop structure, memory locality, and execution mapping |
| GPU Performance | Thread mapping, vectorization, and memory access behavior |
| Code Generation | Bridging low-level IR to efficient executable kernels |

## Tech Stack

| Category | Tools |
| --- | --- |
| Languages | C++, Python, C |
| Compiler | TVM, TensorIR, TIR |
| Systems | Linux, Git |
| Performance | GPU, SIMT, Profiling |

---

<p align="center">
  <sub>IR → Schedule → CodeGen → Performance.</sub>
</p>
