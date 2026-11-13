# Covenant land cover change

How land cover inside QEII National Trust open space covenants has changed
between 1996 and 2023, by region, from the New Zealand Land Cover Database.

**Live page:** https://rutherfordecology.github.io/usedfor/

Tick one or more regions in the Region menu to see their covenants, pick a period, and use the land
cover key (every type starts ticked; untick Select all, then tick a type) to
follow its pathways. The page is one
self-contained `index.html`, with no other files and no network requests.

## Totals only

Covenants are summed by regional council region and by the LCDB mapping date
that shows them as registered, so no single covenant can be picked out. Groups
of fewer than 5 covenants are left out (7 covenants). No covenant numbers or
boundaries are in this repository.

## How it's made

- Each covenant boundary is intersected with LCDB v6 polygons, and the area of
  each class is measured at each mapping date (1996, 2001, 2008, 2012, 2018,
  2023), in NZTM.
- "From registration" counts a covenant from the last LCDB date in or before
  the year it was registered (1996 for older covenants).
- LCDB maps at about 1 ha and shows only the cover at each date. Small
  clearings and edges won't show, and nor will anything that changed and
  recovered between dates. Thin changes along a boundary can come from
  linework rather than change on the ground.

## Sources

- Land Cover Database v6: Manaaki Whenua – Landcare Research, CC BY 4.0.
- QEII open space covenants: QEII National Trust – Ngā Kairauhī Papa, CC BY 4.0.
- Regional council boundaries 2025: Stats NZ – Tatauranga
  Aotearoa, CC BY 4.0.

Made by Rutherford Ecology.
