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

RCE (Reality Code Engine) is a programming language and toolchain in which
every program has one fixed, checkable Form. The same program gives the same
result on every computer, always finishes, and is checked before it runs.
There is one language: the specification at one commit (draft 0.9). The
standard library is batteries-included and hash-pinned.

- **Monorepo:** [openIE-dev/rce](https://github.com/openIE-dev/rce) — specification, Lean proofs, reference checker `rce`, stdlib, book, examples, conformance, tree-sitter grammar, IDE sources, and playground.
- **Playground:** [openie-dev.github.io/rce](https://openie-dev.github.io/rce/)
- **Book:** [openie-dev.github.io/rce/book](https://openie-dev.github.io/rce/book/)
- **Build:** clone `rce`, then `cd spec/checker && cargo build --release` (see the repository README).

Former satellites `rce-book`, `rce-examples`, `tree-sitter-rce`, and `rce-ide` are archived; use the monorepo.

---

<sub>**[openie.dev](https://openie.dev)** · **[coding.openie.dev](https://coding.openie.dev)** · **[contact@openie.dev](mailto:contact@openie.dev)**</sub>
