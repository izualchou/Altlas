# Chapter 18 - Action Engine

## Purpose
The Action Engine executes validated recovery actions using Tasker-native actions, Java Function, and AutoInput.

## Inputs
RECOVERY_* variables

## Responsibilities
- Execute network recovery.
- Perform SIM switching.
- Invoke AutoInput workflows.
- Verify execution results.
- Return ACTION_* outputs.

## Execution Priority
1. Native Tasker Action
2. Java Function
3. AutoInput

## Rules
Actions must be deterministic, idempotent where possible, and produce structured ACTION_* outputs for downstream logging and validation.