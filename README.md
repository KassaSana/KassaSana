## Kassahun Sanayew

Software engineer co-op at CVS Health and Computer Engineering master's student at the University of Florida, graduating December 2026. I write C++ and Java, mostly on storage, systems, and data tooling.

### Open source

- **NVIDIA stdexec.** Found an MSVC miscompilation in `[[msvc::no_unique_address]]` that corrupted lambda captures. Fixed it and reported it to Microsoft. [#2383](https://github.com/NVIDIA/stdexec/pull/2383)
- **NVIDIA CCCL.** Added IEEE 754 binary128 support to ten `cuda::std` math functions, checked bit-exact against libquadmath on about 8 million inputs. Seven more are in review. [#12398](https://github.com/NVIDIA/cccl/pull/12398)
- **DuckDB.** Fixed DISTINCT aggregates sharing a branch with a different ORDER BY. [#27852](https://github.com/duckdb/duckdb/pull/27852)
- **Apache DataFusion.** Two merged fixes: [#25788](https://github.com/apache/datafusion/pull/25788), [#25807](https://github.com/apache/datafusion/pull/25807)

### Projects

- **[Snapback](https://github.com/KassaSana/Snapback).** C++ focus tracker with a wait-free ring buffer at about 30 ns per push.
- **[durablekv](https://github.com/KassaSana/durablekv).** Crash-safe LSM-tree key-value store in C++20.

[Portfolio](https://kassasana.github.io) · [LinkedIn](https://www.linkedin.com/in/kassahun-sanayew-a39164223/) · [Email](mailto:k.sanayew@ufl.edu)
