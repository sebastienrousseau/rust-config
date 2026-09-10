# `@sebastienrousseau/rust-config` API Specification

Comprehensive schema, property definitions, and exported options reference for `@sebastienrousseau/rust-config`.

---

## Description

Shareable Rust configuration standards providing hardened rustfmt formatting and pedantic Clippy lints.

---

## Programmatic Entrypoints

| Specifier | Module Type | Target Runtime | Path |
| :--- | :--- | :--- | :--- |
| `.` (default) | Dual (CJS/ESM) | Node.js >= 18 | `index.cjs` / `index.mjs` |
| `@sebastienrousseau/rust-config` | Dual (CJS/ESM) | Node.js >= 18 | `index.cjs` / `index.mjs` |
| `index.d.ts` | TypeScript | TypeScript >= 5.0 | Type declarations |

---

## Feature & Property Reference

### 1. rustfmt.toml

- **Description**: Deterministic rustfmt formatting preset enforcing 100 max width, reordered imports, and comment wrapping.
- **Scope**: Production & Development
- **Status**: Stable & Active

### 2. clippy.toml

- **Description**: Pedantic Clippy lint configuration alerting on needless borrows, arithmetic overflow risks, and unchecked unwrap calls.
- **Scope**: Production & Development
- **Status**: Stable & Active
