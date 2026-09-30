# GENE EMERGENCE — Curated Reproducibility Repository

## Overview

This repository contains the curated computational and reproducibility materials associated with the GENE EMERGENCE project.

The repository is intentionally separated from the much larger working directory. Only selected analysis code, final reproducibility datasets, manuscript-ready tables, final results, and provenance documentation are included.

The complete working directory is not part of this GitHub release.

---

## Repository structure

```text
.
├── code/
│   ├── analysis/
│   ├── original_author/
│   └── provenance/
│
├── data/
│   ├── final_reproducibility/
│   └── metadata/
│
├── results/
│   ├── final_summary/
│   └── final_tables/
│
├── figures/
│
└── docs/
```

### code/analysis/

Selected analysis and provenance scripts retained for reproducibility of the upstream computational workflow.

### data/final_reproducibility/

Locked final datasets used in the validated analyses, including sequence datasets, matched tables, paired-feature tables, mechanistic tables, null distributions, ancestral-state tables, and validation data.

### results/final_summary/

Final master results, final claims, and manuscript results.

### results/final_tables/

Manuscript-ready evidence tables and supplementary tables.

### figures/

Reserved for the final manuscript figures.

Three manuscript figures are intentionally uploaded manually at the final GitHub curation stage.

### docs/

Repository provenance, build metadata, and the repository manifest.

---

## Reproducibility principle

This repository is a curated reproducibility release, not a copy of the complete working directory.

The full Part 31 working directory contains intermediate analyses, temporary outputs, historical files, and other working materials.

Those materials are intentionally excluded from this release.

The curated repository preserves the selected final datasets, results, tables, and analysis code needed to document the final computational analysis.

---

## Integrity verification

Before GitHub packaging, the curated repository underwent a dedicated integrity audit.

The audit verified:

- all manifest files exist
- all selected source files exist
- source and copied file sizes match
- manifest SHA-256 hashes match
- source-to-copy SHA-256 hashes match
- no unexpected files are present
- no files >=100 MB are present
- no manuscript figures were copied unintentionally
- the required repository directory structure is present

### Final integrity result

**PASS**

At the final integrity audit:

- Total files: 33
- Total size: approximately 6.784 MB
- Computational files: 27
- Final reproducibility files: 23
- Selected analysis/provenance scripts: 4
- Manuscript figures copied during build: 0
- Full 3.2 GB Part 31 working directory copied: No

---

## Manuscript figures

Three manuscript figure slots are reserved:

1. Figure 1 — manual upload pending
2. Figure 2 — manual upload pending
3. Figure 3 — manual upload pending

No manuscript figure was reconstructed or copied automatically during the repository build.

---

## Provenance

Detailed provenance information:

`docs/provenance.md`

Repository manifest:

`docs/REPOSITORY_MANIFEST.csv`

---

## Citation

If you use these computational materials, please cite the associated manuscript together with this repository.

Citation metadata are provided in:

`CITATION.cff`

---

## Repository status

| Component | Status |
|---|---|
| Curated repository | Complete |
| Source/copy integrity | PASS |
| SHA-256 verification | PASS |
| Large-file check | PASS |
| Unexpected-file check | PASS |
| Manuscript figures | Manual upload pending |
| GitHub packaging | Prepared |

---

## Important filename note

Several final reproducibility files retain their original `PART_31_*` filenames.

These filenames are intentional and correspond to selected final analysis outputs.

Their presence does not indicate that the full Part 31 working directory has been copied.

---

## License

No open-source license has been assigned in this repository yet.

The license will be finalized before public release.
