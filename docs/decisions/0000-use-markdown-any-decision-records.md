# Use Markdown Any Decision Records

## Context and Problem Statement

We want to record architecture, design and code decisions made in the project.

Which format and structure should these records follow?

Where should the records live?

## Considered Options

### Format

- [MADR](https://adr.github.io/madr/) 3.0.0 – The Markdown Any Decision Records
- Formless

### Location

- [s3gw repository](https://github.com/s3gw-tech/s3gw)
- SUSE Confluence

## Decision Outcome

MADR in s3gw-tech/s3gw, because

- Architecture, design and code decisions should be open and public
- Github merge request workflow adds an easy review workflow we
  already know and use for code.
- Implicit assumptions should be made explicit.
- MADR allows for structured capturing of any decision.
- The MADR format is lean and fits our development style.
- The MADR structure is comprehensible and facilitates usage & maintenance.
- The MADR project is vivid.
