# Chapter 15 - Verify Engine

## Purpose
The Verify Engine evaluates observed runtime data and produces normalized verification results.

## Verification Layers
- Capability Verification
- HTTP Verification
- DNS Verification
- Ping Verification
- Quality Evaluation

## Inputs
OBS_* variables

## Outputs
VERIFY_CAPABILITY_*
VERIFY_HTTP_*
VERIFY_DNS_*
VERIFY_PING_*
VERIFY_QUALITY_*

## Rules
Verification performs no recovery actions. Each verification layer is independent and contributes structured evidence to the Decision Engine.