# sarif-parsing

Parses and processes SARIF files from static analysis tools like CodeQL, Semgrep, or other scanners. Triggers on "parse sarif", "read scan results", "aggregate findings", "deduplicate alerts", or "process sarif output". Handles filtering, deduplication, format conversion, and CI/CD integration of SARIF data. Does NOT run scans — use the Semgrep or CodeQL skills for that.

## Overview

This directory contains the operational guidance for the `sarif-parsing` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `sarif-parsing` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.

## Included resources

- `agents` — supporting material for this skill.
- `assets` — supporting material for this skill.
- `resources` — supporting material for this skill.
