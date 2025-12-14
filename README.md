# auto-merge-bottom-level

Test repository for auto-merge workflow validation - Level 1 (bottom tier).

This repository demonstrates automatic PR creation and auto-merge functionality in a multi-tier setup.

## Purpose

When changes are merged to `main`, this triggers a workflow that:
1. Updates the submodule pointer in the parent repository (auto-merge-middle-level)
2. Creates an auto-PR with `(auto)` prefix
3. Auto-merge is enabled automatically
4. PR merges when all checks pass

## Part of Test Chain

auto-merge-bottom-level → auto-merge-middle-level → auto-merge-top-level


## Test Run: 2025-12-14 16:12:00
Testing auto-merge workflow with renamed repositories

Test run at: 2025-12-14 16:15:40
