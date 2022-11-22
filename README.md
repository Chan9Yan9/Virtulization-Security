# Virtulization-Security
Some interesting papers &amp; projects

## Papers
###  1. VDF (RAID 2017)
VDF is a targeted evolutionary fuzzing framework for discovering bugs within the software-based virtual devices implemented as part of a hypervisor, which selectively instruments the code of a given virtual device, and performs record and replay of memory-mapped I/O (MMIO) activity specific to the virtual device.

### 2. Hyper-Cube (NDSS 2020)
Hyper-Cube is a fuzzer that aims explicitly at testing hypervisors in an efficient, effective, and precise way, which is based on a custom operating system that implements a custom bytecode interpreter.

### 3. NYX (USENIX 2021)
NYX is a highly optimized, coverage-guided hypervisor fuzzer, whose fast snapshot restoration mechanism can reload the system under test thousands of times per second is key to performance. NYX's mutation engine based on custom bytecode programs, encoded as directed acyclic graphs (DAG), and affine types, that enables the required flexibility to express complex interactions.

### 4. V-Shuttle (CCS 2021)
V-Shuttle is a hypervisor fuzzing framework aiming the vitual device, whose DMA redirection mechanism and the fuzzing mutation scheduling mechanism make fuzzing scalable and semantics-aware.


### 5. Morphuzz (USENIX 2022)
Morphuzz is a generic approach that leverages insights about hypervisor design combined with coverage-guided fuzzing to find bugs in virtual device implementations.

### 6. MundoFuzz (USENIX 2022)
Mundofuzz develops a statistical differential coverage measurement methods to capture the clean coverage information for hypervisor inputs and learns the input grammar through inspecting the coverage characteristics of the given hypervisor inputs.

### 7. Hyperfuzzer (CCS 2021)
Hyperfuzzer develops hybrid fuzzer towards Virtual CPU, which based on Hyper-V. HyperFuzzer leverages Intel-PT to record the control flow of hypervisor, and introduces a novel technique called Nimble Symbolic Execution which relies on the only control flow trace and the fuzzing input to perform symbolic execution. Hyperfuzzer also use unrealated constraint elimination and bit-wise symbolic variebles to get high efficiency.