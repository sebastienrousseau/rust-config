---
title: "Usage — @sebastienrousseau/rust-config"
description: "How to use and configure @sebastienrousseau/rust-config."
layout: "doc"
---

# Usage

`@sebastienrousseau/rust-config` can be consumed across all standard module formats.

## CommonJS

```javascript
const config = require("@sebastienrousseau/rust-config");
console.log(config.presets);
```

## ES Modules

```javascript
import config from "@sebastienrousseau/rust-config";
console.log(config.defaultPreset);
```
