# DOPE Legacy — translations

Community translations for the **DOPE Legacy** web app (dope-legacy.com).

Each file is a flat `key → text` JSON:

| File | Language | Status |
|---|---|---|
| `es.json` | Spanish | source of truth |
| `en.json` | English | complete |
| `de.json` | German | in progress — help wanted |
| `tr.json` | Turkish | in progress — help wanted |
| `pl.json` | Polish | **English base — translation wanted** |
| `pt.json` | Portuguese (BR) | **English base — translation wanted** |
| `it.json` | Italian | **English base — translation wanted** |
| `fr.json` | French | **English base — translation wanted** |

The `pl` / `pt` / `it` / `fr` files start as a copy of `en.json` so every key is
already present — just translate the **values** (right side) and open a PR.
Missing or untranslated keys automatically fall back to Spanish, so a half-done
language still works.

**Want to help translate?** Read **[CONTRIBUTING.md](CONTRIBUTING.md)** — it takes 2 minutes to get started.

Wanted next: **ru** (and completing any of the above).

---

*This repo mirrors the app's translation files. Merged pull requests here are pulled into the app and shipped on the next deploy. Only UI text lives here — no code, no secrets.*
