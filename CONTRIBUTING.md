# Contributing to ezmode projects

## License

All ezmode-games repositories are licensed under **AGPL-3.0**.

This means:
- You can use, modify, and distribute the code
- If you modify and deploy the code, you must open source your modifications
- Network use counts as distribution (if you run a modified version as a service, you must share the source)

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a branch for your changes
4. Make your changes
5. Submit a pull request

## Code Standards

- **pnpm only** - No npm or yarn
- **No `any` types** - Use `unknown` and narrow, or fix the types
- **Biome** for linting and formatting
- **UUIDv7** for all IDs
- Run `pnpm preflight` before submitting

## Pull Requests

- Keep PRs focused on a single change
- Include tests for new functionality
- Update documentation if needed
- Reference related issues

## Issues

- Search existing issues before creating new ones
- Use issue templates when available
- Include reproduction steps for bugs
- Be specific about expected vs actual behavior

## Questions?

Join our [Discord](https://discord.gg/XJx4mYQZ) for help.
