# Chapter 02 - Engineering Principles

## Purpose

This chapter defines the engineering principles that govern Atlas.

## Core Principles

1. XML-first: Generate and validate Tasker XML directly.
2. Metadata-first: Use capabilities.xml, datadef.xml, and tasker.js as the authoritative metadata layer.
3. Validation-first: Every generated artifact must pass import, runtime, export, and round-trip validation.
4. Incremental development: Build with single-Task imports and append-only updates.
5. Deterministic generation: AI output must be reproducible from identical inputs.
6. Separation of concerns: Observe, Verify, Decision, Recovery, and Action remain independent runtime layers.

## Engineering Workflow

Action → Template → Pattern → Primitive → Engine → Engine DAG → Master

Project/Profile integration is performed only after the Task layer has been validated.
