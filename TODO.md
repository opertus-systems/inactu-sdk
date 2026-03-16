# TODO

Last updated: 2026-03-16

## Priority

- Merge or close the remaining dependency PR:
  - `#29` `@types/node`
- Keep the hardened TypeScript receipt parsing path covered by regression tests.
- Audit any future file-reading helpers for TOCTOU patterns; do not reintroduce `stat()` plus `readFile()` trust gaps.

## Notes

- The receipt bounds hardening work is already merged.
- Some dependency branches need fresh checks after base-branch movement.
