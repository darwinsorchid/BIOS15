# Brain–body allometry in male and female birds

Report for BIOS15 testing whether brain mass scales with body mass differently in male and female birds.

## Research Question

Does the allometric relationship between brain and body mass differ between the sexes?

## Methods

Brain mass was modelled as a power function of body mass, linearized by log transformation of both variables and fitted with ordinary least squares regression separately for each sex. Individuals of unknown sex were excluded.

## Main results

| Sex | n | Slope (b) ± SE | R² (%) |
| --- | --- | --- | --- |
| Females | 483 | 0.575 ± 0.012 | 83.1 |
| Males | 615 | 0.550 ± 0.010 | 83.5 |

Both sexes show negative allometry (b < 1): brain mass increases less than proportionally with body mass.

## Files

| File | Contents |
| --- | --- |
| `LinReg_report.qmd` | Quarto source of the report (text, analyses and figures) |
| `LinReg_report.pdf` | Rendered report |
| `bird_allometry.csv` | Example dataset provided by the course |
| `linear-regression.Rproj` | RStudio project file |
| `styles.css` | Styling for the HTML output |

## Rendering

Open `linear-regression.Rproj` in RStudio and render `LinReg_report.qmd`.
