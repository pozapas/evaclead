# Who Leads, Who Follows? Leadership and Guidance During Evacuation

## About

This repository is the companion archive for *Who Leads, Who Follows? A
Review of Leadership and Guidance Dynamics in Evacuation*. It makes the
review's evidence base, documentation, and reproducibility materials available
for transparent inspection and scholarly reuse.

The archive provides the structured evidence record supporting the review: search and
screening documentation, the included-study corpus, study-level quality
appraisal, bibliometric-analysis inputs and exports, figure source data, and
the completed PRISMA 2020 checklist. Together, these materials enable readers
to inspect the review workflow and reproduce its reported descriptive outputs
from the deposited records.

## At a glance

| Component | Coverage |
| --- | --- |
| Included corpus | 265 studies: 195 journal articles, 61 conference papers, 4 book chapters, 3 preprints, and 2 doctoral dissertations |
| Supplementary targeted-search yield | 29 included studies |
| Quality appraisal | 250 studies (223 from the primary search, 27 from the supplementary search); 202 assessed with the simulation instrument and 69 with the empirical instrument; 27 studies used both designs and received both appraisals |
| Bibliometric mapping | VOSviewer 1.6.21 term co-occurrence analysis of titles and abstracts |

## Repository structure

| Directory | Contents |
| --- | --- |
| [`search/`](search/) | Search documentation for the primary and supplementary search arms |
| [`corpus/`](corpus/) | Bibliographic record of every included study |
| [`screening/`](screening/) | Records included through the supplementary targeted search |
| [`appraisal/`](appraisal/) | Appraisal instruments, study-level ratings, and an independent consistency check |
| [`bibliometrics/`](bibliometrics/) | Text corpus, VOSviewer thesaurus, and exported network files |
| [`figures/`](figures/) | Editable PRISMA diagram and data supporting the review figures |
| [`prisma/`](prisma/) | Completed PRISMA 2020 checklist |

## Contents and provenance

### Search documentation

- `search/search_query_log.pdf` records the sources, dates, year spans, and yields for both search arms.
- `search/supplementary_search_queries.csv` contains the five supplementary keyword families as issued, with hit and retrieval counts.

The primary-search strings are reported in Appendix A of the paper.

### Included-study corpus and screening record

- `corpus/included_studies.csv` lists all 265 included studies with publication year, type, venue, DOI, and title.
- `screening/supplementary_arm_included.csv` identifies the 29 studies included through the supplementary targeted search.
- `screening/supplementary_arm_included.bib` provides the corresponding bibliographic records.

### Quality appraisal

- `appraisal/appraisal_rubric.md` documents the two instruments and criterion anchors. Instrument A adapts the 2018 Mixed Methods Appraisal Tool; Instrument B operationalizes verification and validation criteria for evacuation models.
- `appraisal/appraisal_by_study.csv` is the machine-readable, study-by-criterion appraisal record.
- `appraisal/appraisal_by_study.pdf` is a typeset rendering of the same record.
- `appraisal/consistency_check.md` reports the first author's independent second scoring of ten studies and the resulting intra-rater agreement figure.

Criterion-level frequencies are calculated only among studies to which the
criterion applies: 199 simulation studies and 67 empirical studies.

### Bibliometric analysis

- `bibliometrics/abstracts_corpus.txt` is the text corpus used for term co-occurrence analysis.
- `bibliometrics/vosviewer_thesaurus.txt` records the term-merge and exclusion rules.
- `bibliometrics/vosviewer_map.txt` and `bibliometrics/vosviewer_network.txt` are VOSviewer exports that can be reopened directly in VOSviewer.

The mapping used VOSviewer 1.6.21 and term co-occurrence over titles and
abstracts, with binary counting, a minimum of five occurrences, selection of
the top 60 percent by relevance, and association-strength normalization.

### Figures and reporting checklist

- `figures/prisma_flow.drawio` is the editable source for the study-selection diagram; `figures/prisma_flow.png` is its rendered version.
- `figures/figure_data/` contains the source counts for the publication-year, venue-frequency, appraisal, and modeling-approach figures (by modeling framework, movement mechanism, and decision-making method).
- `prisma/prisma_2020_checklist.pdf` is the completed PRISMA 2020 checklist, including the reported location of each item.

## Working with the materials

CSV files are UTF-8, comma-delimited tables and can be opened with spreadsheet
software or read programmatically. The VOSviewer map and network files are
intended to be opened together in VOSviewer. The PRISMA flow diagram can be
edited in diagrams.net using the `.drawio` source file.

## Interpretation and citation

These materials document the evidence base and analytic inputs for the paper;
they should be interpreted alongside its methods and results. When using or
discussing these materials, please cite *Who Leads, Who Follows? A Review of
Leadership and Guidance Dynamics in Evacuation*.
