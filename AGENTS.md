# Project notes

- Edit `index.qmd` (the source). `quarto preview` generates the HTML; don't treat `_site/` as the source of truth.
- Code cell labels: use `#| fig-label: fig-...` for figures and `#| tbl-label: tbl-...` for tables, not `#| label: ...`. With `#| label: fig-...`, the `fig-wait-length` cell rendered as sub-figures. Switching to `fig-label` fixed it (confirmed by the project owner).
