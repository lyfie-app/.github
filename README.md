<div align="center">
  <img src="public/luthor-logo-horizontal.png" alt="Luthor" width="420" />
  <p><strong>TypeScript-first rich text editor ecosystem for React, built on Lexical.</strong></p>
  <p>:rocket: Production-ready presets + :jigsaw: headless extension runtime + :unlock: MIT license</p>
</div>

<div align="center">

[![Project Status](https://img.shields.io/badge/status-active%20development-orange?style=for-the-badge)](https://github.com/lyfie-app/luthor)
[![Publish Packages](https://img.shields.io/github/actions/workflow/status/lyfie-app/luthor/publish-packages.yml?branch=main&label=publish&style=for-the-badge)](https://github.com/lyfie-app/luthor/actions/workflows/publish-packages.yml)
[![GitHub Release](https://img.shields.io/github/v/release/lyfie-app/luthor?style=for-the-badge)](https://github.com/lyfie-app/luthor/releases)

</div>


## :sparkles: Why Luthor

Luthor is an open-source rich text editor ecosystem designed for teams that want modern DX without editor lock-in.

- :package: **Two-package model**: start fast with presets, go deep with headless composition
- :shield: **TypeScript-first APIs**: safe command/state integrations
- :zap: **Lexical-powered**: modern performance and extensibility
- :art: **UI freedom**: build custom editor experiences when product requirements evolve
- :package: **ESM-first distribution**: optimized for modern React bundling

## :package: Packages

| Package | Purpose | Best for | npm |
| --- | --- | --- | --- |
| `@lyfie/luthor` | Plug-and-play editor presets + polished UI | Shipping quickly with minimal setup | [npm](https://www.npmjs.com/package/@lyfie/luthor) |
| `@lyfie/luthor-headless` | Headless extension runtime and typed editor system | Full UI control and custom workflows | [npm](https://www.npmjs.com/package/@lyfie/luthor-headless) |

## :rocket: Quick Start

```bash
pnpm add @lyfie/luthor react react-dom
```

```tsx
import { ExtensiveEditor } from "@lyfie/luthor";
import "@lyfie/luthor/styles.css";

export function App() {
  return <ExtensiveEditor placeholder="Start writing..." />;
}
```

Need full control?

```bash
pnpm add @lyfie/luthor-headless lexical @lexical/code @lexical/link @lexical/list @lexical/markdown @lexical/react @lexical/rich-text @lexical/selection @lexical/table @lexical/utils react react-dom
```

## :globe_with_meridians: Product Links

- Website: [luthor.fyi](https://www.luthor.fyi)
- Docs home: [luthor.fyi/docs/getting-started](https://www.luthor.fyi/docs/getting-started)
- Live demo: [luthor.fyi/demo](https://www.luthor.fyi/demo)
- GitHub: [lyfie-app/luthor](https://github.com/lyfie-app/luthor)
- Sponsor: [github.com/sponsors/lyfie-app](https://github.com/sponsors/lyfie-app)
