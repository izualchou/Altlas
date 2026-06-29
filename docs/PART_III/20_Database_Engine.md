# Chapter 20 - Database Engine

## Purpose
The Database Engine provides persistent storage for runtime history, recovery records, verification results and configuration.

## Responsibilities
- Store runtime history.
- Store verification results.
- Store recovery records.
- Store configuration and persistent state.
- Support reporting and analytics.

## Recommended Tables
- runtime_log
- verification_log
- recovery_log
- action_log
- configuration

## Rules
Database writes should be transactional where possible. Runtime execution must continue gracefully if persistence is temporarily unavailable.