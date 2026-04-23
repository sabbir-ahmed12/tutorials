## Phase 1 — CS Fundamentals (months 1–6)
### C/C++ mastery

 - [ ] Pointers, memory model, RAII
 - [ ] Templates, STL internals
 - [ ] Build systems: CMake, Make
 - [ ] Sanitizers: ASan, UBSan
 - [ ] Resource: Effective Modern C++ (Scott Meyers)

### Compiler theory

 - [ ] Lexing, parsing, ASTs
 - [ ] IR design, CFG, SSA form
 - [ ] Dataflow analysis basics
 - [ ] Register allocation concepts
 - [ ] Resource: Stanford CS143 (free online) or Crafting Interpreters

### Computer architecture

 - [ ] Cache hierarchies, SIMD
 - [ ] Memory bandwidth vs latency
 - [ ] Pipeline hazards, out-of-order execution
 - [ ] GPU vs CPU execution model
 - [ ] Resource: Computer Organization & Design (Patterson & Hennessy)


## Phase 2 — LLVM & Compiler Infrastructure (months 6–12)
### LLVM core

 - [ ] Build LLVM from source
 - [ ] Write your first LLVM pass
 - [ ] Understand IR: instructions, types, metadata
 - [ ] Implement a simple optimization (DCE, mem2reg)
 - [ ] Resource: llvm.org tutorials + LLVM Cookbook

### First real project

 - [ ] Build a toy compiler → LLVM IR
 - [ ] Target: arithmetic language with functions
 - [ ] Add an optimization pass
 - [ ] Publish on GitHub with benchmarks
 - [ ] Resource: Kaleidoscope tutorial (official LLVM docs)

### Python + tooling

 - [ ] Python profiling (cProfile, py-spy)
 - [ ] pybind11: bridge C++ ↔ Python
 - [ ] pytest, hypothesis for testing
 - [ ] Git, CI/CD, code review practices
 - [ ] Resource: Real Python profiling guide (free)


## Phase 3 — GPU Programming & CUDA (months 12–18)
### CUDA fundamentals

 - [ ] Thread hierarchy: grid, block, warp
 - [ ] Shared memory, coalesced access
 - [ ] Occupancy, latency hiding
 - [ ] Nsight Compute profiling
 - [ ] Resource: NVIDIA CUDA C++ Programming Guide (free) + CUDA by Example

### GPU kernel project

 - [ ] Implement matrix multiply from scratch
 - [ ] Optimize: tiling, shared memory, async copy
 - [ ] Profile with Nsight Compute
 - [ ] Beat cuBLAS on a small problem
 - [ ] Resource: Simon Boehm's blog — "How to optimize a CUDA matmul"

### OpenAI Triton

 - [ ] Understand Triton's tile abstraction
 - [ ] Write a fused softmax kernel
 - [ ] Write a flash attention variant
 - [ ] Compare against cuBLAS/PyTorch
 - [ ] Resource: Triton official tutorials (triton-lang.org)


## Phase 4 — MLIR & Deep Learning Compilers (months 18–24)
### MLIR

 - [ ] Understand dialects, passes, patterns
 - [ ] Write a custom MLIR dialect
 - [ ] Lower from high-level → LLVM IR
 - [ ] Understand affine & linalg dialects
 - [ ] Resource: mlir.llvm.org getting started + MLIR paper (CGO 2020)

### DL frameworks internals

 - [ ] PyTorch: FX graph, torch.compile
 - [ ] JAX: XLA compilation pipeline
 - [ ] TVM: relay IR, schedule primitives
 - [ ] Trace a model → see compiler output
 - [ ] Resource: PyTorch internals blog (Horace He) + JAX docs

### Capstone project

 - [ ] Build an MLIR-based DL graph optimizer
 - [ ] Target: fuse ops, eliminate redundant transposes
 - [ ] Benchmark on real models (ResNet, BERT)
 - [ ] Write a blog post or paper
 - [ ] Resource: Study iree-project, torch-mlir on GitHub


## Phase 5 — Portfolio, Research & Job Readiness (months 24–36)
### Open source contributions

 - [ ] Contribute to LLVM, MLIR, or Triton
 - [ ] Fix a real bug or add an optimization pass
 - [ ] Engage on mailing lists / Discourse
 - [ ] Get a PR merged
 - [ ] Resource: LLVM GitHub + LLVM Discourse forum

### Research track (optional but powerful)

 - [ ] Read top papers: NeurIPS, CGO, PLDI, MLSys
 - [ ] Reproduce a paper's results
 - [ ] Extend it — publish or arXiv preprint
 - [ ] Resource: MLSys conference proceedings (free PDFs)

### Interview prep

 - [ ] Systems design for compiler pipelines
 - [ ] LeetCode (medium/hard) in C++
 - [ ] Compiler-specific: CFG, dominators, SSA
 - [ ] Mock interviews with compiler engineers
 - [ ] Resource: Compiler Design interview questions + LeetCode


## Resources:
- OpenCL: https://github.com/mikeroyal/OpenCL-Guide#OpenCL-learning-resources
- OpenCL Course: https://handsonopencl.github.io/
