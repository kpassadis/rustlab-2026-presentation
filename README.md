# Building a Declarative Computation Engine in Rust

Presentation at **RustLab 2026** conference, Bologna (November 3, 2026).

* **Interactive Micro-site:** https://kpassadis.github.io/rustlab-2026-presentation/
* **Slides (PDF):** [Building_a_Declarative_Computation_Engine_in_Rust.pdf](./Building_a_Declarative_Computation_Engine_in_Rust.pdf)

## Abstract

Domain experts express logic as equations, physical laws, and regulatory rules, while traditional enterprise IT implementations introduce slow release cycles for every parameter or model adjustment. This session presents **brick-rs**, a declarative computation engine in Rust that separates model specification (`definition.dsl`) from runtime execution (`runtime.dsl`), compiling a single DAG blueprint once for zero-allocation numerical linear algebra, asynchronous HTTP orchestration, and 50 Hz real-time PMU telemetry.
