# Chapter 05 - XML Generation Rules

## Purpose

This chapter defines the mandatory rules for deterministic Tasker XML generation.

## Generation Order

1. Load official metadata.
2. Select verified Actions.
3. Build Templates.
4. Compose Patterns.
5. Assemble Engines.
6. Generate Task XML.
7. Validate Tasks.
8. Generate Profile XML.
9. Generate Project XML.

## Rules

- Never invent Action IDs.
- Never invent XML attributes.
- Generate only from verified metadata.
- Reuse Templates and Patterns whenever possible.
- Each Task has a single responsibility.
- Every Task must be independently importable and verifiable.

## Acceptance

Generated XML must complete the full validation lifecycle before repository integration.