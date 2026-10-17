# Quality appraisal rubric

The two instruments used to appraise the studies reviewed in *Who Leads, Who Follows? A Review of Leadership and Guidance Dynamics in Evacuation*, with the anchors applied to each criterion.

Empirical and experimental studies are appraised with instrument A, simulation studies with instrument B, and studies combining both designs with both instruments. Each criterion is scored on three levels. No composite score is produced.

---

## Scoring levels

Results are reported as criterion-level frequencies rather than as a ranked quality score, because the purpose of the appraisal is to characterize the evidence base rather than to grade individual studies.

| Level | Meaning |
|---|---|
| **R** Reported | The item is present and specific enough to be checked or reproduced |
| **P** Partially reported | The item is addressed but incompletely, vaguely, or by reference only |
| **N** Not reported | No statement in the paper addresses the item |

`NA` is used where a criterion does not apply, and is reported separately rather than counted as `N`.

---

## Instrument A: empirical, experimental, and VR studies

Adapted from the Mixed Methods Appraisal Tool (MMAT), version 2018, for evacuation research. The MMAT's two screening questions are applied first; a study failing both is recorded as not appraisable.

**Screening:** Are there clear research questions? Do the collected data address them?

| ID | Criterion |
|---|---|
| **A1** | Research question stated and the study design is appropriate to answer it |
| **A2** | Participants described (number, recruitment, relevant characteristics) and appropriate to the question |
| **A3** | Measurements and instruments described clearly enough to be repeated, including apparatus, scenario, and what was recorded |
| **A4** | Outcome data complete, with attrition, exclusions, or missing data addressed |
| **A5** | Confounders and sources of bias identified and accounted for, including the effect of the experimental setting on behavior |

**Reference:** Hong QN, Fàbregues S, Bartlett G, Boardman F, Cargo M, Dagenais P, et al. The Mixed Methods Appraisal Tool (MMAT) version 2018 for information professionals and researchers. *Education for Information*. 2018. doi:10.3233/efi-180221

---

## Instrument B: simulation studies

The five criteria operationalize, for the purpose of appraising reporting completeness, the verification and validation concepts developed for building fire evacuation models.

| ID | Criterion |
|---|---|
| **B1** | Model description complete: governing rules or equations, behavioral assumptions, and geometry |
| **B2** | Parameter values sourced and justified, with an empirical or literature basis rather than assertion |
| **B3** | Verification or validation reported against analytical results, experimental data, other models, or documented incidents |
| **B4** | Sensitivity or robustness analysis reported, including the number of stochastic repeat runs where the model is non-deterministic |
| **B5** | Setup reproducible: software and version, scenario configuration, population, and initial conditions |

**References:**
- Ronchi E, Kuligowski ED, Reneke PA, Peacock RD, Nilsson D. *The Process of Verification and Validation of Building Fire Evacuation Models*. NIST Technical Note 1822. National Institute of Standards and Technology; 2013. doi:10.6028/NIST.TN.1822
- Ronchi E, Kuligowski ED, Nilsson D, Peacock RD, Reneke PA. Assessing the Verification and Validation of Building Fire Evacuation Models. *Fire Technology*. 2014. doi:10.1007/s10694-014-0432-3

---

## Application

1. Each study is classified as simulation, empirical, mixed, or other from the coded data, and the classification is confirmed against the full text at the time of scoring.
2. Scoring is performed from the full text of each study.
3. Each score carries a one-line justification identifying the location of the supporting evidence in the paper.
4. Results are reported as criterion-level frequencies, with a stacked-bar summary figure and a study-by-criterion table (`appraisal_by_study.csv`).

The appraisal implements step three, the assessment of study quality, of the five-step framework of Khan et al.:

Khan KS, Kunz R, Kleijnen J, Antes G. Five Steps to Conducting a Systematic Review. *Journal of the Royal Society of Medicine*. 2003. doi:10.1177/014107680309600304
