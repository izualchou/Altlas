# Chapter 11 - Profile Architecture

## Purpose

Defines how Atlas generates Tasker Profile XML.

## Architecture

Profiles bind Contexts to Tasks.

## Supported Context Types
- Event
- State
- Time
- Location

## Rules
- Profiles reference validated Tasks only.
- Multi-context profiles use explicit context nodes.
- Profile variables remain separate from runtime variables.
- Keep orchestration logic out of Profile definitions whenever possible.