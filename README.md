# The Quinn Group — Brand Guidelines

Brand guidelines for **The Quinn Group** — Anne Warner & Sean Quinn, Realtors at Water Pointe Realty, serving Stuart and the Treasure Coast, Florida.
Prepared by Makarios Marketing.

## Files

| File | What it is |
|---|---|
| `index.html` | The guidelines. Open in a browser, or print to PDF. |
| `The-Quinn-Group-Brand-Guidelines.pdf` | A4 PDF, generated from `index.html`. |
| `qg-cover.jpg`, `qg-divider.jpg` | Cover and spread photography (their own listings). |
| `mfi-logo-dark.png`, `mfi-logo-light.png` | Logo, dark and reversed. |

## Contents

1. The Idea · 2. Positioning · 3. Colour · 4. Typography · 5. Layout · 6. Photography
7. Voice · 8. The Team · 9. Logo · 10. Social · 11. Components · 12. Naming

## Design system

Pulled from the live build (myfloridainsider.com).

| Token | Hex | Use |
|---|---|---|
| `--blue` | `#3076BB` | Coastal blue — the one accent |
| `--blue-deep` | `#245A8F` | Links, small type, hovers |
| `--blue-lt` | `#8FBEE6` | Accent on dark grounds |
| `--ink` | `#121418` | Headlines, body, dark bands |
| `--grey` | `#7A7A7A` | Secondary text |
| `--mist` | `#F5F4F2` | Alternating section bands |
| `--paper` | `#FFFFFF` | Base surface |
| `--sand` | `#C6A98E` | Warm accent |
| `--red` | `#DE0026` | Alerts only |

Display: **Fahkwang** 300/400. Interface: **Open Sans** 400–700.

## Regenerating the PDF

```
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --disable-gpu --virtual-time-budget=20000 \
  --print-to-pdf="The-Quinn-Group-Brand-Guidelines.pdf" --no-pdf-header-footer \
  "file://$PWD/index.html"
```

## To confirm with the client

- Brokerage name (Water Pointe Realty is inferred, not stated on the site).
- Anne and Sean's titles, years of experience, and designations.
- Team bios (drafted from site testimonials; need their own words).
- Which name leads: "The Quinn Group" vs the "My Florida Insider" domain.
