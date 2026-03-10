# AGENTS.md

Guidelines for AI agents working on the ariadne repository.

## Repository Structure

ariadne — a self-hosted knowledge resolver for AI agent instructions.

```
/src              - Application source code
/docs             - Internal proposal & design documents (not tracked in git)
/build            - Build output (not tracked in git)
```

## Essential Commands

```bash
# TODO: Fill in after project setup
```

## Code Style

- **Language**: Kotlin
- **Framework**: Spring Boot (Phase 1)
- **Build tool**: Gradle (Kotlin DSL)

## Testing Patterns

```bash
# TODO: Fill in after project setup
```

## Common Pitfalls

1. **Don't commit `.env` files** — Contains secrets, excluded via `.gitignore`
2. **Don't commit `docs/`** — Internal design documents, excluded via `.gitignore`
3. **Don't skip tests** — Run full test suite before pushing
