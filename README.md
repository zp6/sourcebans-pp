# CLA signatures

Orphan branch storing Contributor License Agreement signatures for the
SourceBans++ web panel.

- **Agreement text**: [`CLA.md`](https://github.com/sbpp/sourcebans-pp/blob/main/CLA.md) on `main`
- **Gating workflow**: [`.github/workflows/cla.yml`](https://github.com/sbpp/sourcebans-pp/blob/main/.github/workflows/cla.yml) on `main`
- **Rationale + how-to-sign**: [`CONTRIBUTING.md`](https://github.com/sbpp/sourcebans-pp/blob/main/CONTRIBUTING.md) on `main`

The `contributor-assistant/github-action` workflow appends each signature to
`signatures/cla.json` on this branch. The file is created on the first
successful sign — do not commit it manually (the action treats a
pre-existing file as a fatal error).

This branch is intentionally an orphan (no shared history with `main`).
