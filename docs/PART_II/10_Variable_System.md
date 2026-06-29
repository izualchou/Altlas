# Chapter 10 - Variable System

## Purpose

This chapter defines the Atlas variable architecture used by the AI Generator and runtime engines.

## Variable Principles

- Variables are metadata-defined.
- Variables follow a one-way data flow.
- Runtime variables are transient unless explicitly persisted.
- Persistent state should be stored separately from temporary execution state.

## Recommended Layers

OBS_*      Observation layer
VERIFY_*   Verification layer
RISK_*     Decision layer
RECOVERY_* Recovery layer
ACTION_*   Action layer
ASE_*      Persistent system variables

## Engineering Rules

- Use consistent prefixes.
- Avoid reusing variables across layers.
- Prefer immutable inputs between engines.
- Clear temporary variables after execution.
