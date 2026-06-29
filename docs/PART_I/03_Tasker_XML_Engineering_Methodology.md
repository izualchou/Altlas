# Chapter 03 - Tasker XML Engineering Methodology

## Purpose

This chapter defines the standard engineering workflow used by Atlas for Tasker XML development.

## Engineering Hierarchy

Action
→ Template
→ Pattern
→ Primitive
→ Primitive DAG
→ Engine
→ Engine DAG
→ Master

Project and Profile engineering begins only after Task-layer validation is complete.

## Development Rules

- XML-first engineering.
- Metadata-first implementation.
- Single Task incremental import.
- Append-only updates; never replace validated Tasks.
- Validate each Task independently before Engine integration.

## Validation Workflow

Design → Generate XML → Import → Execute → Export → Compare → Accept
