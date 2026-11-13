# Contributing to MagicMatrix

Thanks for your interest in MagicMatrix.

## Current repository status

The repository is being prepared and does not yet contain the Android application source. Please avoid submitting speculative implementations of product behaviour before the relevant design or issue has been agreed.

## Before making a change

1. Check existing issues and discussions to avoid duplicate work.
2. For a significant change, open an issue describing the problem and proposed approach.
3. Keep pull requests focused and explain the user-visible impact.

## Puzzle correctness

Changes to puzzle generation or validation should include tests for:
- Number range and uniqueness.
- Every required row, column, and main diagonal.
- Consistency of the fixed clues with a valid completed square.
- Correct distinction between incomplete and invalid lines.
- Guaranteed solvability for generated puzzles.

Do not change the established list-rotation logic without first documenting and testing its existing rules.

## Pull requests

Include a clear summary, rationale, relevant screenshots for UI changes, and test/build results. Do not include API keys, signing keys, passwords, personal data, or other secrets.
