# Hi, I'm 0x7m7

**C++ • Systems Infrastructure • Runtime & Inference Engineering**

C++ developer focused on systems infrastructure, high-performance runtimes, and the low-level machinery behind AI inference.

## Focus Areas

### C++

- Modern C++ (C++17/20/23): RAII, move semantics, templates, concepts, and `constexpr`
- Memory model, atomics, lock-free data structures, and cache-aware design
- Custom allocators, arenas, and zero-copy buffer management
- Profiling and benchmarking with `perf`, `VTune`, and Google Benchmark

### Runtime & Systems Infrastructure

- Async I/O: `epoll`, `io_uring`, and coroutine-based schedulers
- Thread pools, work-stealing executors, and NUMA-aware scheduling
- Networking: TCP, RDMA, and gRPC services
- Linux internals, shared memory IPC, and production-grade daemons

### Inference Runtime & AI Infrastructure

- Inference engines and model-serving runtimes
- CUDA/ROCm integration, kernel launch pipelines, and GPU memory management
- Continuous batching, KV-cache management, and request scheduling
- Quantization, operator fusion, and graph execution

### Active Targets

- Low-latency inference servers and runtime internals
- High-throughput proxies, schedulers, and task queues
- Memory-efficient storage engines and caching layers
- Open source inference and systems infrastructure

## Working Principles

- Correctness, performance, and simplicity are design constraints, not afterthoughts
- Explicit ownership and deterministic resource lifetimes
- Sanitizer-tested (ASan, TSan, UBSan) and benchmarked before shipping
- Contributions over credentials: build in public, verify with results

## Toolchain

- **Language:** C++ (GCC, Clang)
- **Build Systems:** CMake, Bazel, Ninja
- **Analysis:** `clang-tidy`, `cppcheck`, ASan / TSan / UBSan, Valgrind
- **Profiling & Testing:** `perf`, `gdb`, Google Test, Google Benchmark
- **GPU:** CUDA, Nsight
- **Environment:** Linux, Git, Docker

## Contact

- GitHub: [@0x7m7](https://github.com/0x7m7)
