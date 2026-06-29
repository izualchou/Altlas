# Chapter 14 - Observe Engine

## Purpose
The Observe Engine is responsible for collecting runtime state before any decision is made.

## Responsibilities
- Collect SIM and subscription information.
- Collect telephony state.
- Collect connectivity state.
- Collect network capabilities.
- Record timestamps and execution context.

## Data Sources
- Java Function
- Tasker native actions
- Android framework APIs

## Output Variables
OBS_SIM_*
OBS_NET_*
OBS_CELL_*
OBS_TIME_*

## Rules
Observe performs collection only. No validation or recovery logic is permitted in this layer.