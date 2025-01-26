# Supplementary Materials for Regional Differences in Central Yiddish Vowel Length: Central Poland and the Unterland (forthcoming)

This repository contains supplementary materials for Regional Differences in Central Yiddish Vowel Length: Central Poland and the Unterland. These materials complement the  paper by providing detailed participant information and comprehensive statistical analyses.

## Repository Organization

Our materials are organized into two main sections:

### 1. Participant Information (/tables/participant_data/)
The participant information tables serve as  source documentation for the USC Shoah Foundation Visual History Archive testimonies analyzed in this study, in accordance with the agreement between the Corpus of Spoken Yiddish in Europe (CSYE) and the USC Shoah Foundation. Each entry includes:

- Unique VHA code for testimony identification
- Speaker demographic information
- Interview metadata (location, date)
- Associated audio file references

### 2. Statistical Analyses (/appendices/)
We provide three detailed appendices containing linear mixed effects model outputs:
- Appendix A examines durational distinctions for the high vowels [iː] and [i]
- Appendix B analyzes durational distinctions for [aː] and [a]
- Appendix C investigates durational distinctions for [uː] and [u]

Each appendix includes complete model specifications, diagnostics, and interpretations.

## How to Use These Materials

### Accessing Participant Data
The participant data files can be read using standard statistical software:

```R
# In R
poland_data <- read.csv("tables/participant_data/poland_participants.csv")
```

```python
# In Python
import pandas as pd
poland_data = pd.read_csv("tables/participant_data/poland_participants.csv")
```

### Understanding the Analyses
Each appendix is written in Markdown format and can be viewed directly on GitHub. They include:
- Full model specifications
- Comprehensive output tables
- Model diagnostics
- Interpretations of results

## Data Privacy and Ethics
All participant data has been anonymized according to [relevant ethical guidelines]. This study was approved by [ethics board information].

## Questions and Contact
If you have questions about:
- Participant data: [contact information]
- Statistical analyses: [contact information]
- General inquiries: [contact information]

## Citation
If you use these materials in your research, please cite our paper:

[Citation information]

## License
[Appropriate license information]

## Acknowledgments
[Any acknowledgments for data collection, analysis help, or funding sources]
