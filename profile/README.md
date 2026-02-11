<div align="center">

# `> MESOTRON FORGE // SYSTEM ONLINE`

<img src="https://img.shields.io/badge/SYSTEM_STATUS-35%25_OPERATIONAL-yellowgreen?style=for-the-badge&color=0f3d0f&labelColor=black" />
<img src="https://img.shields.io/badge/MODE-FOUNDATION_BUILD-blue?style=for-the-badge&color=005cc5&labelColor=black" />

### Open Source Studio • Polyglot systems in Python • Rust • Elixir

<strong>[ ENTER DOSSIER → <a href="https://mesotron.dev">mesotron.dev</a> ] (loading…)</strong>

</div>

---
## `> manifest --list`

| Python                                   | Elixir                                    | Rust                               |
|------------------------------------------|-------------------------------------------|------------------------------------|
| **[taph](https://github.com/mesotron-dev/taph)** <br>Immutable object primitives & atomic types. A thread-safe bedrock. (v0.1.1) | **[dist_guard](https://github.com/mesotron-dev/dist-guard)**<br>Zero-trust mTLS for Elixir/OTP: private CA + one-command release setup (pre-alpha) | ⚡ **[quaestor](https://github.com/mesotron-dev/quaestor)**<br>High-performance filesystem audit suite — Rayon scanner + static reports + Axum server (pre-alpha) | 
| **[faultrig](https://github.com/mesotron-dev/faultrig)** <br>Robust detailed package exception engine. | **[otp_pki](https://github.com/mesotron-dev/otp-pki)**<br>Ergonomic Elixir wrapper for Erlang :public_key raw records + high-level API (pre-alpha) | **[litestash-rs](https://github.com/mesotron-dev/litestash-rs)**<br>Planned Rust port |
| **[pkgrig](https://github.com/mesotron-dev/pkgrig)**<br>Production Python scaffolding: Nuitka binaries + Chainguard containers + cloud-native CI/CD (pre-alpha) | **[xuap](https://github.com/mesotron-dev/xuap)**<br>Blazing-fast uap-core compliant User-Agent parser for Elixir (pre-alpha) | —                                  |
| **[devrig](https://github.com/mesotron-dev/devrig)**<br>Unified dev/build rig: lint → test → Nuitka binary → secure Chainguard containers (pre-alpha) | **[litestash_ex](https://github.com/mesotron-dev/litestash_ex)**<br>Planned Elixir port | —                                  |
| **[forgeconf](https://github.com/mesotron-dev/forgeconf)**<br>Typed, cloud-native config with .env.toml schema & Secret Manager deploy (pre-alpha) | —                                   | —                                  |
| **[quarryforge](https://github.com/mesotron-dev/quarryforge)**<br>Lossless Fossil SCM → GitHub migration with full history & author mapping | —                                  | —                                  | 
| **[litestash-engine](https://github.com/mesotron-dev/litestash-engine)**<br>Core engine extracted from legacy Litestash | —                                  | —                                  | 
| **[litestash](https://github.com/mesotron-dev/litestash)**<br>High-performance sharded SQLite KV store: typed, beta 0.5 → major refactor in progress | —                                  | —                                  | 

---

## `> log --status`

### Python 

---

0. **Primitives**
    * `taph` released.
    * `faultrig` build activated.
1. **Toolchain**
    * `pkgrig` build paused pending Taph & FaultRig import.
    * `devrig` & `forgeconf` queued.

### Elixir

---

0. **Primitives**
    * `otp_pki` 75% complete. Queued after `forgeconf`.
1. **Toolchain**
    * `dist_guard` 80% complete. Queued after `forgeconf`. 
    * `xuap` Queued after `dist_guard`

---

## `> tech-note -f TN-2026-001.taph --section 4`

### 4. Roadmap: The Path to v0.2.0

While 0.1.0 focused on the **Declarative API** (using the `class` keyword), version 0.2.0 will introduce the **Functional API**.

#### 4.1 Factory Functions
The upcoming release will provide `immutable()` and `namespace()` factories. These tools will allow developers to generate protected types programmatically, further reducing boilerplate:

```python
# Planned for v0.2.0
User = taph.immutable("User", "id name", active=True)
```

This factory approach will automatically generate the `__init__` and `__slots__`, folding the architectural knowledge of Taph into a single function call.

---

<div align="center">
  <sub><strong>Origin:</strong> <a href="https://github.com/mesotron-dev/litestash">LiteStash</a> • <strong>Philosophy:</strong> A Pragmatic Modernist Approach to Software Engineering.
</sub>
</div>
