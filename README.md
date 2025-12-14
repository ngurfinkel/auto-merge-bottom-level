# halo-auto-merge-test

Test repository for auto-merge workflow validation - Level 1 (bottom tier).

This repository demonstrates automatic PR creation and auto-merge functionality in a multi-tier setup.

## Purpose

When changes are merged to `main`, this triggers a workflow that:
1. Updates the submodule pointer in the parent repository (halo-node-test)
2. Creates an auto-PR with `(auto)` prefix
3. Auto-merge is enabled automatically
4. PR merges when all checks pass

## Part of Test Chain

halo-auto-merge-test → halo-node-test → halo-node-buildroot-test


## Test Run: 2025-12-14 11:26:59
