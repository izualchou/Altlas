# Chapter 08 - Action Reference

## Purpose

This chapter defines how Atlas AI Generator models Tasker Actions.

## Action Model

Each Action consists of:
- Action ID
- Name
- Parameters
- Parameter Types
- Default Values
- XML Serialization
- Validation Rules

## Engineering Rules

- Action IDs must originate from official metadata or verified exports.
- Parameter ordering must remain deterministic.
- Unsupported attributes shall not be generated.
- XML output must be round-trip compatible.

## Action Lifecycle

Metadata → Template → Pattern → Primitive → Engine → Task XML