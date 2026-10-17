<picture>
  <source media="(prefers-color-scheme: dark)" srcset="">
  <source media="(prefers-color-scheme: light)" srcset="">
</picture>

## Open Interface Engineering

**A research project making free, open software that teaches how to save compute energy, and reports energy in joules.**

We write free, open source software and research. The tools report the energy cost of operations such as builds and queries in joules, a unit of physics, so that the cost of compute can be measured and reduced.

---

### What We Make

**[coding.openie.dev](https://coding.openie.dev)**: five IDE projects that report energy:

| IDE | Domain | Description |
|-----|--------|-------------|
| **Lux** | Web | Replaces the HTML/CSS/JS/TS ecosystem with a single language. Ships native + WASM. |
| **Joule** | Systems | Systems language with formal verification, energy budgets per function, and WebGPU compute. |
| **Arc** | General Purpose | Every programming language, including Python, Rust, Go, C++, Java, COBOL, Fortran, and 50+ more. |
| **Data** | Data Science | Notebooks with energy receipts per cell. Python, R, Julia, SQL with ML pipeline metering. |
| **DevOps** | Infrastructure | Terraform, Kubernetes, Docker, Ansible, CI/CD, all as a queryable infrastructure graph. |

### Five Interface Tracts

Every system fails at its boundaries. We address all five:

1. **Data**: protocols, formats, encoding, timing, API contracts
2. **Energy**: power delivery, voltage domains, thermal management, EMC
3. **Material**: mechanical fits, material compatibility, environmental specs
4. **Logistics**: assembly, routing, serviceability, manufacturing constraints
5. **Supply Chain**: sourcing, lifecycle, procurement, vendor constraints

### Public Projects

Standalone projects, all free and open source:

| Project | What it is | Install |
|---------|------------|---------|
| **[flow-g](https://github.com/openIE-dev/flow-g)** | Typed FunctionGraph IR for heterogeneous inference on CPU + Apple Silicon Metal + WGPU + AMX | `cargo binstall flowg` (binary releases; `cargo install flowg` installs a stub that points to them) |
| **[lux-lang](https://github.com/openIE-dev/lux-lang)** | Reactive, energy-aware language compiling to flowG | `cargo install openie-lux` |
| **[jmax](https://github.com/openIE-dev/jmax)** | Math-native language replacing MATLAB / Julia / R / Mathematica | `cargo install jmax` |
| **[joule-lang](https://github.com/openIE-dev/joule-lang)** | Self-hosted energy-aware language with compile-time budgets | `cargo install joulec` |
| **[jouledb](https://github.com/openIE-dev/jouledb)** | Energy-metered database with HDC primitives, joules per query | `cargo install jouledb` |
| **[pattern-lang](https://github.com/openIE-dev/pattern-lang)** | Pattern catalog + edge-first AI cascade runtime | see repo |

All software is released under MIT OR Apache-2.0, copyright Open Interface Engineering, Inc.

### RCE

RCE is a small programming language defined by a written specification. A
program describes the states it can be in, the events that can happen, and
how each event changes the state. The same program gives the same result
on every computer, always finishes, and is checked for mistakes before it
runs. Start with [The RCE Book](https://github.com/openIE-dev/rce-book).

| Repository | What it holds |
|---|---|
| **[rce](https://github.com/openIE-dev/rce)** | the specification (draft 0.7), its EBNF grammar, Lean proofs, and the reference checker and interpreter `rce` |
| **[rce-book](https://github.com/openIE-dev/rce-book)** | a step-by-step guide; every example is checked by `rce` |
| **[rce-examples](https://github.com/openIE-dev/rce-examples)** | programs grouped by area, from money and text to networks, science and hardware |
| **[tree-sitter-rce](https://github.com/openIE-dev/tree-sitter-rce)** | the grammar for editors that use tree-sitter |
| **[rce-ide](https://github.com/openIE-dev/rce-ide)** | an editor for RCE built on the reference checker ([downloads](https://github.com/openIE-dev/rce-ide/releases)) |

The RCE repositories are licensed under MIT OR Apache-2.0.

---

<sub>**[openie.dev](https://openie.dev)** · **[coding.openie.dev](https://coding.openie.dev)** · **[contact@openie.dev](mailto:contact@openie.dev)**</sub>
