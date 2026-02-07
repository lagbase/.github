# Contributing to Lagbase

Thanks for your interest in contributing to Lagbase.

This guide applies to all repositories under the [github.com/lagbase](https://github.com/lagbase) organization.

## Current Status

🚧 **Pre-launch** — We're not accepting external contributions yet.

The codebase is actively being developed and the architecture may change significantly before launch.

## How to Help Now

1. **Join the waitlist** at [lagbase.com](https://lagbase.com)
2. **Star the repos** to show interest
3. **Report bugs** via GitHub Issues (once we launch)
4. **Share feedback** at [hello@lagbase.com](mailto:hello@lagbase.com)

## After Launch

Once we're live, we'll open up contributions for:
- Bug fixes
- Documentation improvements
- New Decision Lag Artifact ideas
- DLA specification proposals
- Accessibility improvements
- Performance optimizations
- SDK improvements and new language bindings

## Repository Guide

| Repository | What to Contribute |
|------------|-------------------|
| `lagbase-core` | DLA engine improvements, new DLA types |
| `lagbase-web` | UI/UX improvements, accessibility |
| `lagbase-api` | API endpoints, performance |
| `lagbase-cli` | CLI commands, output formats |
| `lagbase-sdk-js` | SDK features, TypeScript types |
| `lagbase-sdk-python` | SDK features, type hints |
| `lagbase-mcp` | MCP tools, resources |
| `dla-spec` | Specification proposals (RFC process) |
| `dla-schemas` | Schema updates, validators |
| `docs` | Documentation, tutorials |
| `examples` | Templates, integration examples |

## Code Style

- TypeScript strict mode (all TS repos)
- Prettier for formatting
- ESLint for linting
- Tailwind CSS for styling (web repos)
- Type hints required (Python repos)

## Commit Convention

```
type(scope): description

feat(core): add evidence chain DLA type
fix(web): resolve export button alignment
docs(api): update rate limit documentation
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

---

Questions? Email [hello@lagbase.com](mailto:hello@lagbase.com) or reach out on Twitter [@lagaboratory](https://x.com/lagaboratory).
