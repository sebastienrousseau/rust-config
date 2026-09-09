# `@sebastienrousseau/rust-config` Features & Capabilities

An exhaustive overview covering **100% of the features, rules, and capabilities** provided by `@sebastienrousseau/rust-config`.

---

## Feature Matrix

| Feature | Scope | Status | Guarantee |
| :--- | :--- | :--- | :--- |
| **rustfmt.toml** | Core | Active | Deterministic rustfmt formatting preset enforcing 100 max width, reordered imports, and comment wrapping. |
| **clippy.toml** | Core | Active | Pedantic Clippy lint configuration alerting on needless borrows, arithmetic overflow risks, and unchecked unwrap calls. |
| **Zero Dependencies** | Packaging | Active | 0 external npm runtime dependencies |
| **Dual Packaging** | Distribution | Active | Full CommonJS and ESM interoperability |
| **TypeScript Types** | Typings | Active | Bundled `index.d.ts` declarations |

---

## Feature Deep Dive

### 1. rustfmt.toml
Deterministic rustfmt formatting preset enforcing 100 max width, reordered imports, and comment wrapping. Designed to guarantee deterministic behavior across all development and continuous integration environments.

### 2. clippy.toml
Pedantic Clippy lint configuration alerting on needless borrows, arithmetic overflow risks, and unchecked unwrap calls. Designed to guarantee deterministic behavior across all development and continuous integration environments.
