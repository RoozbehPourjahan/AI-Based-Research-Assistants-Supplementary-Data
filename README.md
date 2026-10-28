# AI-Based Research Assistants: Supplementary Data

Supplementary data for the manuscript *AI-Based Research Assistants: A Task-Oriented Review of Capability, Risk and Ethical Governance in Scientific Research*.

- GitHub: https://github.com/RoozbehPourjahan/AI-Based-Research-Assistants-Excel-Supplementaries

This repository is the only location holding materials for this study. No analysis code is deposited.

## Contents

| File | Description |
|---|---|
| `Supplementary_Data.xlsx` | Sheet `README`: sampling and scoring procedure, column definitions, raw-to-Final score mapping. Sheet `Data`: the 88 sampled tool-task cells with the first-pass Final score and the second-pass sub-factor scores (S, C, E, V) and Final score. |
| `LICENSE` | Creative Commons Attribution 4.0 International. |

## What the data support

The file supports the reliability analysis of the manuscript (Sections 3.4.3, 3.5.8.1 and 3.6; Tables 2, 6a and 6b). All statistics in those sections can be recomputed from the `Data` sheet using the definitions in the `README` sheet. The statistics of Section 3.5.7 can be recomputed from Table 6 of the manuscript.

The Final scores of the remaining cells of the 49 x 12 grid are not deposited. They are fully determined by Tables 4 to 6 of the manuscript through the derivation rule of Section 3.5.6.

## Sample

88 of the 588 cells (15%), a random sample stratified by the ten task categories with proportional allocation by the Largest Remainder method. Both scoring passes were made by the same rater in the same session, so the agreement statistics quantify same-session consistency and not test-retest or inter-rater reliability.

## Columns of the `Data` sheet

| Column | Content |
|---|---|
| `ID` | Running number of the sampled cell (1-88) |
| `Task`, `Category`, `Tool` | The sampled tool-task cell (names follow Tables 4 and 5) |
| `Pass1_Final` | First-pass Final score (1-5) |
| `Pass2_S`, `Pass2_C`, `Pass2_E`, `Pass2_V` | Second-pass sub-factors, 0-2 each |
| `Pass2_Raw` | Sum S + C + E + V (formula, 0-8) |
| `Pass2_Final` | Second-pass Final score (1-5), mapped from `Pass2_Raw` |

## Citation

If you use these data, please cite the manuscript.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0); see `LICENSE`.
