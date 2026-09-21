# Contributing to Multron

Thank you for your interest in contributing to Multron projects. We build high-performance, bloat-free desktop software with minimal resource consumption. Every line of code merged into our repositories must adhere to these standards.

---

## 1. Guiding Principles
* **Performance First:** Low CPU and memory footprint are non-negotiable. Profile before adding overhead.
* **Zero Telemetry:** We do not track, collect, or upload user data under any circumstances.
* **Minimal Dependency Surface:** Avoid pulling in bloated crates/packages when a lightweight or standard-library implementation suffices.

---

## 2. Development Workflow

We enforce a strict Pull Request workflow across all repositories.

1. **Fork & Branch:** Clone your fork locally and branch from `main`:
   ```bash
   git checkout -b feat/your-feature-name
   # or
   git checkout -b fix/issue-description