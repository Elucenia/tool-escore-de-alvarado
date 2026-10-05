<!-- ELUCENIA technical documentation · escore-de-alvarado · en · no clinical/professional/rights approval -->

# Alvarado score

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-de-alvarado)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Pain migration to the right iliac fossa

`migra`

### Anorexia (or acetone in urine)

`anorex`

### Nausea or vomiting

`nausea`

### Right iliac fossa tenderness

`dor`

### Rebound tenderness (Blumberg sign)

`desc`

### Temperature ≥ 37.3 °C

`febre`

### Leukocytosis \> 10,000/mm³

`leuco`

### Left shift (neutrophils \> 75%)

`desvio`

## Method edition

Alvarado 1986: MANTRELS 8 items, 0–10; version with left shift

## Documented formula

MANTRELS: Migration (1), Anorexia (1), Nausea/vomiting (1), Tenderness in right iliac fossa (2), Rebound tenderness (1), Elevated temperature (1), Leukocytosis (2), Shift to the left (1). Total 0 to 10.

## Limits and population

Alvarado 1986 was developed from 305 hospitalized patients with abdominal pain suggestive of appendicitis and eight clinical/laboratory factors. The original abstract does not automatically validate different age groups, pregnant patients or discharge/imaging strategies. Decision thresholds and the population of the version used must be checked separately; the tool implements the variant including a left shift.

## References

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
