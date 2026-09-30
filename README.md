# cDAVF Classifier

Classifies one cranial dural arteriovenous fistula (one lesion at a time) with DES, Borden and Cognard, from the primary venous outlet, the secondary (highest-risk) venous outlet and four venous features.

**© Alex Kostynskyy. cDAVF classification algorithm and DES. All rights reserved.**
For research use only. Not for clinical decision-making. No licence is granted: reproduction, redistribution or adaptation of the algorithm, the dictionary or this code requires the author's written permission.

## Files

| File | Purpose |
|---|---|
| `index.html` | The classifier page |
| `dictionary.js` | The classification dictionary, generated from `DES_BORDEN_COGNARD_DICTIONARY_YYYYMMDD.xlsm` |
| `config.js` | Survey link and optional contact email |
| `update.html` | Author tool: turns a new Excel dictionary into a new `dictionary.js`, with checks and a change report |

## Updating the dictionary

1. Open `update.html` on the published site.
2. Drop the new `DES_BORDEN_COGNARD_DICTIONARY_YYYYMMDD.xlsm` (the date becomes the version).
3. Review the checks and the change report, then download `dictionary.js`.
4. Upload it here (Add file → Upload files) and commit.
