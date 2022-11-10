# AI/ML SIG Charter

**Goals**
*
* ISA for AI/ ML: Organizing global research, development and evaluation of RISC-V ISA extensions for AI/ML acceleration

* Optimize a full software stack especially graph compiler to translate ONNX graph models to RISC-V architecture to support portability of ML, AI and NLP applications.

* Specify the benchmarks, performance metrics, and the evaluation methodology that will be used to track performance comparisons of optimized vs. current implementations and vs. other popular architectures.

* Propose software-hardware co-optimizations for better support of the target applications.


**Scope**
*
* Evaluate the current support level for extensions such as the vector V, Zvediv, and P extensions and identify suitability for AI/ML workloads.

* Define the current support for approximate computing data types popular im ML applications (bfloat16, fp16, fp8, int8, int4, ...etc) and explore bfloat8, fp4, etc.

* Define matrix multiplication vector extensions (evaluate strassen's algorithm and other optimizations such as AI optimized multiplication).

* Define spiking neural network model extensions - example LFI neuron model.

* Evaluate if a software managed cache would benefit for prefetching and define appropriate cache model.

* Define the success metrics in terms of optimization coverage, functionality, energy, performance evaluation, and code size.

* Arrange and coordinate efforts between developers from different entities willing to contribute to the optimization of the SW stack. 

* Collaborate with the simulation infrastructure working group to get proper evaluation platforms (functional simulators & cycle-timing simulator). 

* Collaborate with other related task groups (V extension group): discuss their proposals’ effect on our target applications and to propose our own based on our analysis.

* Responsible for ongoing oversight and monitoring of the evolving ML/AI software stack and related aspects of RISC-V architecture.
