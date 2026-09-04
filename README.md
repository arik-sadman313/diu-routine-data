# DIU Routine Data

This repository contains official DIU routine data.

- `latest.json` contains the current official routine.
- Historical routines are stored in `routines/`.
- The repository is intended to be consumed by the DIU Routine Web and Android applications.

## How to add a new official routine

1. Obtain the official verified routine PDF from the university.
2. Parse the PDF into the canonical JSON format using the DIU Routine Web parser.
3. Validate that the JSON contains ONLY the canonical fields (no `batch`, `section`, etc.).
4. Add the new JSON file to the `routines/` directory (e.g., `routines/fall-2026.json`).
5. Update `latest.json` to be an exact copy of, or pointer to, the newly added routine.
6. Commit and push the changes.
