# ClipDen Network — website stub

A free, static companion website stub for **Boss / LuLu KEEP ClipDen Network**. Soft Chair cream/plum look. Preparation only: no paid hosting, no store upload, no account system, no live map, no payments, and no live booking engine.

## Pages

| File | Role |
|------|------|
| `index.html` | Home, map placeholder, preference-feed tease |
| `feed.html` | Facebook-style style/news feed with curated trend links (+ beard/grooming slot) |
| `settings.html` | Richer web settings: feed topics, gender (Male/Female/Other), beard & moustache prefs, privacy show/hide, area |
| `for-clients.html` | Client discovery and profile preview |
| `for-providers.html` | Provider profile fields and manual-availability booking rule |
| `privacy.html` | Granular privacy controls (Cuts-specific — **not** the EST Google Sites URL) |
| `terms-prep.html` | Terms PREP placeholder + links to desk UGC/AUP pack |
| `help-assist-contact.html` | Help / Assist / Contact Us with Soft Chair honesty |

## KEEP references

- `../WEBSITE-VISION-KEEP-2026-09-28.md` — app-like companion, style news feed, richer settings
- `../GENDER-PREFERENCE-KEEP-2026-09-28.md` — Male / Female / Other
- `../BEARD-MOUSTACHE-STYLES-KEEP-2026-09-28.md` — first-class facial-hair prefs
- Desk UGC: `/workspace/endrody-ops/desk/safety-ugc/` (AUP + liability PREP — not lawyer-reviewed)

## Open locally

```bash
cd /workspace/endrody-ops/product-pipeline/smart-cuts/website-stub
python3 -m http.server 8000
```

Then open <http://localhost:8000>. Pages use inline CSS (or `styles.css` in the thin preview) and a plain text `ClipDen` wordmark until Iris final art; no build step.

## Scope honesty

- Forms are non-submitting visual stubs.
- Booking slots appear only after a provider manually publishes availability (none live here).
- Addresses default to hidden; “Licensed” / “Pending verify” are not official verification.
- Assist ≠ AI — human Help / Assist / Contact language only.
- Privacy for Cuts needs its **own** public URL later (do not reuse EST privacy).
- Terms / AUP are **PREP / not lawyer-reviewed**.

## Shareable preview

See desk `HOSTING-FREE-OPTIONS.md` and `WEBSITES-STATUS-2026-09-28.md` for free hosting next steps.
