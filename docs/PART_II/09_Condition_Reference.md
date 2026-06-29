# Chapter 09 - Condition Reference

## Purpose

This chapter defines how Atlas AI Generator models Tasker Conditions and conditional execution.

## Condition Categories

- If / Else / End If
- Variable Conditions
- State Conditions
- Event Conditions
- Expression Conditions

## Engineering Rules

- Use only verified condition operators.
- Preserve deterministic evaluation order.
- Avoid implicit side effects in condition evaluation.
- Conditions must remain compatible with exported Tasker XML.

## Condition Lifecycle

Metadata → Condition Template → Pattern → Engine → Runtime
