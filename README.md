# MagicMatrix

**MagicMatrix** is an Android magic-square puzzle game concept. Complete a partially filled number grid by placing the available numbers so that every required row, column, and main diagonal satisfies the same magic constant.

> **Repository status:** This public repository is currently being prepared. The application source code and build configuration have not yet been committed here. This README describes the intended product; it does not claim that an installable build or every feature below is already available.

## The puzzle

A magic square is an arrangement of distinct numbers in a square grid where each row, each column, and the two main diagonals have the same sum.

For a normal (n \times n) magic square containing the integers from 1 through (n²), the magic constant is:

\[
M = \frac{n(n² + 1)}{2}
\]

MagicMatrix is designed around completing partially filled magic-square grids—not finding hidden numbers or solving a generic number hunt.

## Intended features

- Partially completed magic-square puzzles with fixed clues and editable cells.
- A number picker for filling the empty cells.
- Row, column, and diagonal sum feedback.
- Hints, notes, undo, and erase controls.
- Puzzle levels with Easy, Medium, Hard, and Expert difficulty.
- Matrix sizes from 3×3 through 6×6, subject to puzzle-generation support.
- A fixed five-minute (300-second) gameplay timer across difficulties and matrix sizes.
- Daily challenges and custom games, designed to work offline.
- Local high scores and recognition-focused achievements.
- Light, dark, and system appearance modes.

These are product goals. Features should be marked as implemented only after they are present and tested in the committed application.

## Fair-puzzle requirements

A generated puzzle should be based on a valid completed magic square, with selected cells removed to form the playable board. The puzzle generator should validate each board before presenting it to a player.

Validation should check the number range and uniqueness, all required row/column/diagonal sums, and consistency of the remaining clues with at least one valid completion. Difficulty should be based on clue density and logical complexity—not simply on making the grid larger. An incomplete line should not be reported as incorrect merely because it has not reached the target sum yet.

## Design direction

- **Light theme:** white surfaces, cool light-grey supporting surfaces, dark readable text, and green interaction highlights.
- **Dark theme:** true black background, dark-grey cards, soft-white text, and green interaction highlights.
- **Accent:** emerald/mint green. Avoid dominant blue or purple gradients.
- **Experience:** minimal, readable, mobile-first, and focused on the puzzle.

## Intended technology

The current implementation direction is **Android with Kotlin and Jetpack Compose**. The application source and exact build requirements are not present in this repository yet, so build instructions will be added after the project files are committed.

## Privacy

Read the [Privacy Policy](PRIVACY_POLICY.md). It must be checked against the exact app release and its enabled SDKs before distribution.

## License

This repository is published under the [MIT License](LICENSE). See the license file for the complete terms.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before proposing changes. Bug reports and focused improvements are welcome.

## Security

Please read [SECURITY.md](SECURITY.md) for responsible vulnerability reporting.

## Project links

- Repository: https://github.com/varuntejabodepudi/magic-matrix
- Developer: https://github.com/varuntejabodepudi
