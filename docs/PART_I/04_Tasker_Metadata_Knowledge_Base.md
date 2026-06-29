# Chapter 04 - Tasker Metadata Knowledge Base

## Purpose

Atlas uses official Tasker metadata as the authoritative source for XML generation and validation.

## Primary Metadata Sources

1. capabilities.xml
2. datadef.xml
3. tasker.js
4. Verified Tasker XML exports

## Responsibilities

### capabilities.xml
- Action registry
- Events
- States
- Conditions
- Plugins

### datadef.xml
- Action parameters
- XML schema
- Default values
- Serialization rules

### tasker.js
- JavaScript API
- Runtime interfaces
- Variable access

### Verified XML Exports
- Import compatibility
- Export compatibility
- Action IDs
- Parameter ordering

## Engineering Rules

- Never invent Action IDs.
- Never invent XML attributes.
- Official metadata takes precedence over inference.
- Verified exports confirm implementation behavior.
