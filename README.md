# corpus-navrules

Per-rule text mirror of **COMDTINST M16672.2D, Navigation Rules: International–Inland**
(US Coast Guard), as distributed today by the USCG Navigation Center:
https://www.navcen.uscg.gov/pdf/navRules/NavRules.pdf (226 pp, born-digital PDF,
downloaded 2026-10-04, text extracted with pypdf — no OCR).

## Shape

- `rules/rule-01..rule-38` — one file per rule, International text followed by the
  Inland variant where the rules differ (exactly the order the book prints);
  rule title in each file header. 38 rule files.
- `annexes/annex-i..annex-v` — the five annexes (33 CFR 84–88, incl. Pilot Rules).

43 files total, ~276 KB of text. Every file's provenance is in `MANIFEST.tsv`.

## Currency caveat (stated plainly)

The *Navigation Rules and Regulations Handbook* (COMDTINST M16672.2F, 2024)
supersedes M16672.2D. At build time the Handbook PDF was not retrievable from
navcen.uscg.gov (the page links resolve 404); this PDF is what the Navigation
Center itself still serves at the canonical URL. The current amalgamated legal
texts (33 CFR 83–88, 72 COLREGs) are linked from
https://www.navcen.uscg.gov/navigation-rules-amalgamated — refresh lane for a
future pin.

## Licence

US government work — not subject to copyright in the United States (17 USC 105).
No registration needed; keep this notice and the source URL.
