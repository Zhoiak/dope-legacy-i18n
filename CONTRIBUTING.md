# Contributing translations

Thanks for helping translate **DOPE Legacy**! No coding needed — you only edit text.

## The files
Each language is one flat JSON file: `key → text`. `es.json` (Spanish) is the **source**; `en.json` is the reference. Example:

```json
{
  "nav.home": "Home",
  "billing.buy": "Buy now",
  "acc.deaths": "%d deaths"
}
```

## How to add a NEW language
1. Copy `es.json` (or `en.json`) to `<code>.json` using the ISO-639-1 code — e.g. `ru.json`, `it.json`, `pt.json`, `fr.json`, `pl.json`.
2. Translate the **values** (the right side). Leave the **keys** (left side) exactly as they are.
3. Open a Pull Request.

## How to improve an EXISTING language
Edit that file's values and open a PR. Completing **de.json** / **tr.json** is very welcome.

## Rules (please keep these — otherwise the app breaks)
- **Never change the keys** (`"nav.home"`), only the text after the colon.
- **Keep placeholders intact**: `%d`, `%s`, `%v` (numbers/words the app fills in) and `{{ ... }}` — copy them into your sentence, don't delete or reorder their meaning.
- **Keep HTML tags**: `<b>…</b>`, `<a …>…</a>`, `<br>` — translate the words, not the tags.
- **Partial is fine**: you don't need every key. Missing keys automatically fall back to Spanish, so a half-done language still works.
- **Valid JSON**: keep the quotes, colons and commas. If unsure, paste the file into any "JSON validator" before submitting.

## Tone / terminology
- The product is an **assistant** / **the Service** (automation). In user-facing copy, avoid calling it a "bot", the third-party game name, or "cheat/hack". Keep it natural for your language, not a literal word-for-word translation.
- Match the friendly, concise style of the English/Spanish text.

## Workflow
Fork → edit → **Pull Request**. A maintainer reviews (German and Turkish are key markets) and merges. Merged PRs get pulled into the app and go live on the next release. Thank you! 🛰️ — *(icon here is fine, this is a dev doc, not app UI)*
