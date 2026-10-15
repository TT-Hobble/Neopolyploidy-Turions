# Neopolyploidy-turions
This repository contains data CSVs and analysis code used to examine the association between polyploidy and turion germination for the Hobble et al. manuscript "Neopolyploidy accelerates early stages of turion germination in Spirodela polyrhiza".

## Dataset Description
This dataset contains germination observations for diploid (2X) and neopolyploid (4X) Spirodela polyrhiza turions. Individual turions were monitored throughout germination, and the day on which key developmental milestones (flotation, root emergence, and first daughter-frond production) occurred was recorded.

### Directory Structure
```text
├── main/
│   ├── Turion_Data_Long.csv             # Raw data used in analysis
│   └── Turion_Analysis.Rmd              # R markdown used to complete analysis
```

#### CSV Column Explanations
- Year: Gemination assay year
- Geno: Genetic background
- Ploidy: Ploidy level (2X for diploids or 4X for neopolyploids).
- Flask_Rep: Turion production flask replicate
- Box#: Storage box ID
- EppLocation: Location withint storage box
- Turion_Rep: Turion replicate ID
- Tube: Germination tube ID
- Stage: Developmental stage observed:
  - Float = Surface flotation
  - Root = Root sprouting
  - Frond = First daughter frond
- Day: Day that stage was observed
