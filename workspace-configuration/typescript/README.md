# Kaiden Workspace Configuration Type

[![npm version](https://img.shields.io/npm/v/@openkaiden/workspace-configuration.svg)](https://www.npmjs.com/package/@openkaiden/workspace-configuration)
[![Apache-2.0](https://shields.io/badge/license-Apache%202-yellow.svg)](https://opensource.org/license/apache-2-0)

TypeScript type definitions for the Kaiden Workspace Configuration.

## Installation

```bash
npm install @openkaiden/workspace-configuration
```

Or with your preferred package manager:

```bash
# pnpm
pnpm add @openkaiden/workspace-configuration

# yarn  
yarn add @openkaiden/workspace-configuration

# bun
bun add @openkaiden/workspace-configuration
```

## Usage

```typescript
import type { components } from '@openkaiden/workspace-configuration';

type WorkspaceConfiguration = components['schemas']['WorkspaceConfiguration'];
```

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.
