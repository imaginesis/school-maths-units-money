# Units of measurement and money in school mathematics across 10 countries

Which units a child meets in maths lessons in Austria, France, Germany, Italy, the Netherlands, Poland, Spain,
Switzerland, the United Kingdom and the United States — metric or customary, whether the school teaches the
**decagram** (Poland, Austria, Italy; Spain's decree gives no closed list) or the **are and hectare**, which imperial units appear — and how
money is written there: symbol and its position (`3,50 zł`, `$3.50`, `€ 3,50`, `3.50 Fr.`), minor unit, coins
and banknotes. Prepared by Imaginesis (https://imaginesis.com), a maths worksheet generator that prints each
worksheet in the units and currency of the country it is for.

Snapshot: 2026-10-18. License: Creative Commons Attribution 4.0 (CC BY 4.0) — cite as
"Imaginesis units and money in school mathematics, 2026, https://doi.org/10.5281/zenodo.23451760".

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23451760.svg)](https://doi.org/10.5281/zenodo.23451760)

## Files

- `data/units.csv` — `measurement_systems` (in the order the country's school uses them), `decagram_dag`,
  `are_and_hectare`, `imperial_or_customary_units`, `symbols_length|area|volume|mass` (unit symbols that appear
  in Imaginesis word problems for that country), `sources` (curriculum documents the units were read from).
- `data/money.csv` — `currency` (ISO 4217), `symbol`, `symbol_position`, `example`, `minor_unit`, `minor_symbol`,
  `coins`, `banknotes`, `coin_series_property`.

## Why it matters

"45 dag" is a normal quantity on a Polish or Austrian worksheet and an unknown unit in Germany or France; "1 a"
is a school unit in the Netherlands and gone from the French primary curriculum since 2025. A word problem
about paying with coins only works if the coins exist: the US has no 2-cent coin but has a quarter, which
changes the answer to "pay 37 with the fewest coins".

## Related datasets

Notation and grade levels of the same 10 countries: https://doi.org/10.5281/zenodo.23451054. Curriculum crosswalk:
https://doi.org/10.5281/zenodo.23217841. Skill prerequisite graph: https://doi.org/10.5281/zenodo.23451451.

## Limits

Primary and lower-secondary school. Symbols in `symbols_*` are those used by Imaginesis tasks, not a complete
list of units taught; the `sources` column names where the school units were checked. Corrections welcome as
GitHub issues.
