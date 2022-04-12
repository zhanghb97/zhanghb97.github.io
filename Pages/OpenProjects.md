---
layout: default
title: Open Projects
nav_order: 2
---

# Open Projects

Currently, we provide open projects in the following directions.

## 1 - Domain-specific Compiler

<!-- - **Description**

We want to introduce the following 3 domain-specific MLIR dialects in the buddy compiler: Digital Image Processing (DIP), Digital Audio Processing (DAP), and Point Cloud (PC). Participants can choose 1~2 operations in a specific dialect to contribute. All projects in this direction will have a similar workflow.

(1) Data Structure Definition: Participants should add domain-specific data structure to interoperate with MLIR memory reference C/C++ data structure. For example, the MemRef constructor can work with OpenCV's Mat data structure (see [here](https://github.com/buddy-compiler/buddy-benchmark/blob/main/include/Utils/Container.h#L43) for more details).

(2) Operation Implementation: Participants should define their chosen operations in the specific dialect and implement their respective lowering passes using MLIR.

(3) Evaluation: Participants should register their created operation's use case in buddy benchmark and evaluate end-to-end cases against SOTA works in their respective domain. For example, we compare the Buddy Corr2D and OpenCV Filter2D in our benchmark framework (see [here](https://github.com/buddy-compiler/buddy-benchmark/tree/main/benchmarks/ImageProcessing) for more details). -->

### Project 1-1: Adding an Compiler Stack for RISC-V Costom Extensions.

- **Description**:
- **Expected outcomes**: 
- **Skills required**:  Good C/C++ skills, basic understanding of MLIR, LLVM, RISC-V.
- **Possible mentors**: Hongbin Zhang
- **Difficulty rating**: Hard

### Project 1-2: Adding Morphological Transformations in DIP Dialect.

- **Description**: There are 7 morphological operations which can be implemented for this project: Erosion, Dilation, Opening, Closing, Morphological Gradient, Top Hat, and Black Hat. 
- **Expected outcomes**: 1～2 morphological transformation operations and lowering passes.
- **Skills required**:  Good C/C++ skills, basic understanding of MLIR, Image Processing domain knowledge
- **Possible mentors**: Prathamesh Tagore
- **Difficulty rating**: Medium
<!-- 
### Project 1-2: Adding Noise Suppression Operation in DAP Dialect.

Participants should add noise suppression operation and related end-to-end support for noise suppression cases.

- **Expected outcomes**: noise suppression operations and lowering passes.
- **Skills required**:  Good C/C++ skills, basic understanding of MLIR, Audio Processing domain knowledge
- **Possible mentors**: Hongbin Zhang
- **Difficulty rating**: Hard

### Project 1-3: Adding Convolution Operation in PC Dialect.

Participants should add point cloud specific convolution operation and related end-to-end support.

- **Expected outcomes**: point cloud specific convolution operation and lowering pass.
- **Skills required**:  Good C/C++ skills, basic understanding of MLIR, basic domain knowledge
- **Possible mentors**: Hongbin Zhang
- **Difficulty rating**: Hard -->


## 2 - Performance Optimization

### Project 2-1: Vectorizing Convolution or GEMM Operations.

- **Description**: Optimize existing convolution and GEMM operations using vectorization. You can refer to the algorithm [here](https://github.com/opencv/opencv/blob/4.x/modules/dnn/src/layers/layers_common.simd.hpp).
- **Expected outcomes**: Vectorization passes for convolution or GEMM operations.
- **Skills required**: Good C++ coding skills, basic understanding of MLIR and vectorization.
- **Possible mentors**: Liutong Han, Hongbin Zhang
- **Difficulty rating**: Hard

## 3 - Benchark Framework

### Project 3-1: Adding More Deep Learning Benchmark Cases in buddy-benchmark.

- **Description**: 
- **Expected outcomes**: 
- **Skills required**:
- **Possible mentors**: Hongbin Zhang
- **Difficulty rating**: Medium

## 4 - Testing Framework

### Project 4-1: Improving the Testing Framework for buddy-mlir and buddy-benchmark.

- **Description**: 
- **Expected outcomes**:
- **Skills required**:
- **Possible mentors**: Hongbin Zhang
- **Difficulty rating**: Easy
