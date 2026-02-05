# ts-starter

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-5.9-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vitest-4.0-6E9F18?logo=vitest&logoColor=white" alt="Vitest">
  <img src="https://img.shields.io/badge/pnpm-8+-F69220?logo=pnpm&logoColor=white" alt="pnpm">
  <img src="https://img.shields.io/badge/ESLint-9.39-4B32C3?logo=eslint&logoColor=white" alt="ESLint">
  <img src="https://img.shields.io/badge/VitePress-1.6-646CFF?logo=vite&logoColor=white" alt="VitePress">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
</p>

A modern TypeScript project starter template with built-in development tools and best practices.

## Features

- 🚀 **TypeScript** - Type-safe development
- 📦 **tsdown** - Fast TypeScript bundler for library development
- ✅ **Vitest** - Lightning fast unit testing
- 🔍 **ESLint** - Code linting with @antfu/eslint-config
- 📝 **Commitlint** - Conventional commit messages
- 🪝 **Git Hooks** - Pre-commit hooks with simple-git-hooks
- 📚 **VitePress** - Documentation site generator
- 🔄 **pnpm** - Fast, disk space efficient package manager

## Quick Start

### Prerequisites

- Node.js >= 18
- pnpm >= 8

### Installation

```bash
# Clone the repository
git clone https://github.com/oiij/ts-starter.git
cd ts-starter

# Install dependencies
pnpm install
```

## Development

```bash
# Start development mode with watch
pnpm dev

# Run the source code directly
pnpm start

# Type checking
pnpm type:check
```

## Building

```bash
# Build the project
pnpm build
```

The build output will be in the `dist` directory.

## Testing

```bash
# Run tests
pnpm test

# Run tests with UI
pnpm test --ui
```

## Linting

```bash
# Lint code
pnpm lint

# Fix linting issues
pnpm lint:fix
```

## Documentation

```bash
# Start documentation site in development mode
pnpm docs:dev

# Build documentation site
pnpm docs:build

# Preview built documentation site
pnpm docs:preview
```

## Committing Changes

This project uses conventional commits with commitlint and cz-git.

```bash
# Stage changes and commit with interactive prompt
pnpm commit

# Or use commitizen directly
pnpm cz
```

## Publishing

```bash
# Bump version and publish to npm
pnpm release
```

## Scripts

| Script | Description |
|--------|-------------|
| `pnpm dev` | Start development mode with watch |
| `pnpm build` | Build the project |
| `pnpm start` | Run source code directly |
| `pnpm test` | Run tests |
| `pnpm lint` | Lint code |
| `pnpm lint:fix` | Fix linting issues |
| `pnpm type:check` | Run TypeScript type checking |
| `pnpm docs:dev` | Start documentation site |
| `pnpm docs:build` | Build documentation site |
| `pnpm commit` | Interactive commit with conventional commits |
| `pnpm release` | Bump version and publish |
| `pnpm update:deps` | Update dependencies interactively |

## Project Structure

```
ts-starter/
├── src/              # Source code
├── test/             # Test files
├── docs/             # VitePress documentation
├── dist/             # Build output
├── package.json      # Package configuration
├── tsconfig.json     # TypeScript configuration
├── tsdown.config.ts  # tsdown configuration
├── vitest.config.ts  # Vitest configuration
└── eslint.config.js  # ESLint configuration
```

## License

[MIT](./LICENSE) License © 2024 [oiij](https://github.com/oiij)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`pnpm commit`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
