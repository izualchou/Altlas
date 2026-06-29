# Chapter 17 - Recovery Engine

## Purpose
The Recovery Engine executes recovery policies selected by the Decision Engine.

## Inputs
RISK_SCORE
RISK_LEVEL
RISK_REASON
RISK_ACTION

## Responsibilities
- Execute recovery policy.
- Retry with backoff.
- Support rollback.
- Record recovery outcome.

## Recovery Priority
1. Soft recovery
2. Network refresh
3. SIM switch
4. Rollback

## Rules
Recovery must be idempotent where possible and every recovery action must produce structured RECOVERY_* outputs.