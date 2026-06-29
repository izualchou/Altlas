# Chapter 07 - XML Schema

## Purpose

This chapter defines the canonical XML schema conventions used by Atlas AI Generator.

## Hierarchy
Project -> Profile -> Task -> Action

## Principles
- Generate valid Task XML first.
- Preserve Tasker export compatibility.
- Use official metadata to determine element structure and parameters.
- Avoid undocumented attributes.

## Schema Rules
- Stable element ordering.
- Deterministic attribute generation.
- Metadata-driven parameter serialization.
- Round-trip compatible output.
