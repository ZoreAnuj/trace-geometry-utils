# trace-geometry-utils

A Rust library for 2D and 3D geometric transformations, tailored for computer vision and robotics applications. It provides a foundation for building robust spatial reasoning systems, inspired by the original Sophus library.

## Key Features
*   Implementations for SO(2), SO(3), SE(2), and SE(3) Lie groups.
*   Efficient operations for rotation, transformation, and interpolation.
*   Support for automatic differentiation for optimization tasks.
*   Clean, idiomatic Rust API with a focus on performance and safety.

## Tech Stack
*   **Language:** Rust
*   **Core Dependencies:** `nalgebra`, `num-traits`, `approx`

## Getting Started
Add the library to your `Cargo.toml`:
```toml
[dependencies]
trace-geometry-utils = { git = "https://github.com/zoreanuj/trace-geometry-utils" }
```
Import and use the modules in your code:
```rust
use trace_geometry_utils::se3;
```