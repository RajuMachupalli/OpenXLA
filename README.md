# OpenXLA
> Write this document to simplify the OpenXLA flow and its understanding.

> Platforms: Python, JAX, Tensorflow

> Operations set: StableHLO

> Compilers: XLA, IREE

**OpenXLA**: It is an open-source machine learning compiler that can optimize models from different frameworks for various hardware platforms.
**StableHLO**: StableHLO is an operation set for high-level operations (HLO) in machine learning (ML) models. It's a portability layer between different ML frameworks and ML compilers: ML frameworks that produce StableHLO programs are compatible with ML compilers that consume StableHLO programs. StableHLO is based on the MHLO dialect and enhances it with additional functionality.

**MHLO**: 

**MLIR**:

**IREE**:

![image](https://github.com/RajuMachupalli/OpenXLA/assets/52839597/aa79bea8-f846-4f7e-b952-6fc0d91db076)
Compilation process in XLA

# Notes
1. Clang: C/C++ front end for LLVM.


# Additional MAterials
1. Blog for undertsnading LLVM backend. https://sourcecodeartisan.com/2020/09/13/llvm-backend-0.html
2. Chapter from LLVM author about the LLVM architecture. https://aosabook.org/en/v1/llvm.html
