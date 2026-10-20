# Hi, I'm 0x7m7

C++ • AI Infrastructure • Memory Security Research

Systems-focused developer working toward production-level C++ and security research on widely deployed software.

## Focus Areas

### Systems & Modern C++
- Modern C++ (17/20/23) with strong ownership and memory-safety discipline
- Memory layouts, cache behavior, move semantics, optimizer-level reasoning
- Toolchain: GCC/Clang, sanitizers (ASan/UBSan/TSan), GDB, CMake/Ninja

### AI Infrastructure
- Inference runtimes, KV-cache and memory management, quantization paths
- High-performance execution on consumer hardware, not just datacenter GPUs
- Active targets: vLLM, llama.cpp, ONNX Runtime-class codebases

### Security Research
- Manual source auditing of parsers and JS engine shells (d8-style targets)
- Bug classes: use-after-free, buffer overflow, OOB access, type confusion
- Objective: CVEs, coordinated disclosure, and 0-day work in major engines

## Working Principles
- Security and performance are design constraints, not afterthoughts
- Test against sanitizers before shipping; audit line by line
- contributions over credentials — learn in public, verify with results

## Languages
![C++](https://img.shields.io/badge/C%2B%2B-23-00599C?logo=cplusplus&logoColor=white)

## Toolchain
- Compilers: GCC, Clang (with sanitizer builds)
- Debugging: GDB, valgrind, ASan/UBSan/TSan
- Build: CMake + Ninja, ccache
- Analysis: clang-tidy, cppcheck
- Environment: Linux, Git

## Currently
- Practicing: manual auditing of parser and engine-shell source
- Studying: V8 internals, memory allocator design, optimizer output
- Building: performance-oriented C++ projects (list as they land)
- Contributing: getting first commits into open-source AI infrastructure

## Contact
- GitHub: [@0x7m7](https://github.com/0x7m7)
