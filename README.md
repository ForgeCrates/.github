# ForgeCrates

Engineering low-level solutions for systems-level problems.

## Purpose

ForgeCrates exists to design and build correct, well-engineered solutions to low-level software problems — the kind of work that sits close to the operating system, the hardware, and the runtime, rather than on top of high-level abstractions.

The primary implementation language is Rust, chosen for its memory safety guarantees without sacrificing systems-level control. The scope of this organization is not restricted to Rust; C and other systems languages are used where they are the correct tool for the problem.

## Areas of focus

- **Systems programming** — memory management, allocators, schedulers, concurrency primitives, and lock-free data structures
- **Operating system internals** — file systems, I/O subsystems, process and thread management
- **Networking and protocols** — protocol implementations, custom runtimes, and socket-level systems
- **Performance engineering** — profiling tools, benchmarking utilities, and instrumentation for analyzing system behavior
- **Storage and I/O** — work involving NVMe, async I/O models, and related infrastructure-level subjects
- **Other Similar Fields**

## Standards

Every project in this organization is held to the following standards:

1. **Correctness first.** Low-level software has a low tolerance for undefined behavior, race conditions, and unsound assumptions. Correctness is not negotiable.
2. **Documented design decisions.** Each repository explains not just what the code does, but why it was designed that way, including trade-offs considered and rejected.
3. **No toy implementations.** Projects are built to function as real, working solutions — not simplified demonstrations.

## Repository structure

Each repository is self-contained and includes its own README covering:
- The problem the project solves
- Build and usage instructions
- Design rationale and known trade-offs

## Contact

For questions, feedback, or collaboration, open an issue on the relevant repository.
