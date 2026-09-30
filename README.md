# cDAVF Classifier

Classifies one cranial dural arteriovenous fistula (one lesion at a time) with DES, Borden and Cognard, from the primary venous outlet, the secondary (highest-risk) venous outlet and four venous features.

**© Alex Kostynskyy. Software, classification dictionary and DES (Directness–Exclusivity–Strain) system. Borden and Cognard classifications are those of their original authors, applied here for reference.**
For research use only. Not for clinical decision-making. No licence is granted: reproduction, redistribution or adaptation of this software, the dictionary or the DES system requires the author's written permission.

## Files

| File | Purpose |
|---|---|
| `index.html` | The classifier page |
| `dictionary.js` | The classification dictionary, generated from `DES_BORDEN_COGNARD_DICTIONARY_YYYYMMDD.xlsm` |
| `config.js` | Tracking link (Google Apps Script) and contact email |
| `privacy.html` | Privacy notice (what is recorded and why) |
| `update.html` | Author tool: turns a new Excel dictionary into a new `dictionary.js`, with checks and a change report |

## Updating the dictionary

1. Open `update.html` on the published site.
2. Drop the new `DES_BORDEN_COGNARD_DICTIONARY_YYYYMMDD.xlsm` (the date becomes the version).
3. Review the checks and the change report, then download `dictionary.js`.
4. Upload it here (Add file → Upload files) and commit.
