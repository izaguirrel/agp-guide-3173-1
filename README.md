# agp-guide-3173-1

Test repository for GUIDE-3173 manual testing.

## Purpose

This repo tests that AGP update failures show the **actual command** that failed instead of a generic label.

## Test Scenarios

### Scenario 1: Yarn update failure (intentional)

The repo will use yarn but include a reference to a non-existent private package to force an update failure.

