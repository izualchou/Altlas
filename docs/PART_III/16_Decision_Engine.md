# Chapter 16 - Decision Engine

## Purpose
The Decision Engine converts verification evidence into deterministic recovery decisions.

## Inputs
VERIFY_* variables

## Outputs
RISK_SCORE
RISK_LEVEL
RISK_REASON
RISK_ACTION

## Responsibilities
- Aggregate verification evidence.
- Classify failures.
- Select recovery policies.
- Prevent unnecessary recovery actions.

## Rules
Decision logic must be deterministic, explainable, and independent of implementation-specific recovery actions.