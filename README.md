# MATER Protopersona Companion Material

This repository contains the companion material referenced in the JBHI manuscript for the MATER project.

## Contents

- Protopersona development summary
- Comparative protopersona table
- Concise narrative profiles
- Full appendix LaTeX file: `protopersona-appendix.tex`
- Compiled appendix PDF: [protopersona-appendix.pdf](protopersona-appendix.pdf)
- Full scoring rubric

## Build

To build the appendix PDF from the LaTeX source, run:

```bash
latexmk -pdf protopersona-appendix.tex
```

## Development Summary

The protopersonas were developed through expert-informed user modelling during the early design phase of MATER.

A multidisciplinary panel contributed domain knowledge covering:

- maternal nutrition and dietetics
- clinical nutrition
- psychology
- speech therapy
- digital health implementation

The modelling process focused on recurring user patterns, barriers to adherence, digital literacy variability, and informational needs during pregnancy and breastfeeding.

## Comparative Table

| Dimension | Giulia Bianchi | Martina Rossi | Elena Verdi |
| --- | --- | --- | --- |
| Profile | Primiparous woman (30-35), highly educated, proactive in health information seeking. | Pregnant woman (30-40), often multiparous, balancing work and family responsibilities. | Pregnant woman (30-35) following a vegetarian or vegan diet with strong nutritional awareness. |
| Primary Needs | Evidence-based information, clear explanation of gestational weight gain, trimester-specific guidance, reassurance on physiological changes. | Concise and actionable guidance, quick monitoring tools, practical meal solutions. | Diet-specific recommendations, reassurance on nutrient adequacy, detailed explanations on supplementation and food safety. |
| Main Barriers / Frustrations | Conflicting online information, difficulty identifying reliable sources, anxiety about weight monitoring. | Time constraints, difficulty maintaining structured meal planning, excessive data-entry burden. | Generic dietary advice not adapted to plant-based diets, insufficient personalisation. |
| Behavioural Traits | High digital engagement, frequent consultation of apps and professionals, strong adherence to validated recommendations. | Goal-oriented interaction, sporadic tracking, efficiency-driven behaviours. | Highly proactive, careful nutrient monitoring, strong interest in detailed nutritional information. |
| Design Implications for MATER | Transparent sources, myth-debunking sections, structured educational pathways, reassuring weight monitoring feedback. | Streamlined interface, simplified tracking, quick food logging, visual weight trends, ready-to-use meal templates. | Diet-specific pathways (omnivorous/vegetarian/vegan), micronutrient indicators, advanced educational modules. |

## Notes

The repository is intended as companion material for the manuscript and can be extended with additional supporting files, such as a fuller narrative appendix or supplementary design artifacts.


## Additional Tables and Data

### SUS Results
- Item-level scores: `tables/sus_item_scores.md`
- Individual scores: `data/sus_results.csv`

### MARS Comparative Analysis
- Qualitative comparison table: `tables/mars_table.md`

### App Store Links
- See: `tables/app_links.md`

## SUS Items

The administered items were:

1. *I think that I would like to use this system frequently.*
2. *I found the system unnecessarily complex.*
3. *I thought the system was easy to use.*
4. *I think that I would need the support of a technical person to use this system.*
5. *I found the various functions in this system were well integrated.*
6. *I thought there was too much inconsistency in this system.*
7. *I would imagine that most people would learn to use this system very quickly.*
8. *I found the system very cumbersome to use.*
9. *I felt very confident using the system.*
10. *I needed to learn a lot of things before I could get going with this system.*
