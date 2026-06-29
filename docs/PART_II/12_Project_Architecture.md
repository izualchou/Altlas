# Chapter 12 - Project Architecture

## Purpose

Defines the canonical Tasker Project architecture used by Atlas.

## Architecture Layers

- Project
- Profiles
- Runtime Engines
- Tasks
- Actions

## Design Principles

- Project coordinates runtime components.
- Profiles trigger validated runtime engines.
- Engines encapsulate business logic.
- Tasks remain modular and reusable.
- Actions are generated from verified metadata.

## Recommended Runtime Flow

Project -> Profile -> Observe -> Verify -> Decision -> Recovery -> Action -> Logging

## Acceptance

Projects are generated only after all dependent Tasks and Profiles have completed validation.