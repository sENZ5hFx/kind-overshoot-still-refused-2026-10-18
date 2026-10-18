# Named queries — 2026-10-18

Prior-art scope before any candidate: Notion data source `collection://382d9c24-c10c-4fbf-9628-c7be3a1e4007`, latest rows through CLOSED-2026-10-16, and `sENZ5hFx/realm-discovery-engine-outputs` sessions through 2026-10-16. Kind-Overshoot was still queued. No 2026-10-17 repository exists.

## Retrieval attempts

1. Wiley `pdfdirect` and HTML for doi:10.1029/2024GB008329 — HTTP 403.
2. Semantic Scholar graph API — openAccessPdf URL is the DOI page, status HYBRID, license CCBY. Not a file. A follow-up search call returned HTTP 429.
3. PMC and Europe PMC for Wilson et al. 2022 PNAS — recaptcha HTML, not a PDF. Not scored. Not used up.
4. Nature article PDF doi:10.1038/s43247-024-01561-x — downloaded, hashed, text-extracted.
5. MOESM1 and MOESM2 from media.springernature.com — downloaded, hashed, text-extracted. MOESM2 captions only. Figures not digitized.

## Not opened

- Walker and Palevsky 2025 PDF and Supporting Information. Still the queued source.
- Wang and Fennel Zenodo 10.5281/zenodo.10960312 (3.6 GB). Not a printed table.
- Friedlingstein Global Carbon Budget 2025 preprint. Residual 1.7 inherited, not re-measured.
