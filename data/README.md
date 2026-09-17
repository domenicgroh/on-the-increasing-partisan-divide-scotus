# Source data

This directory contains the source data required to reproduce the analyses.

The analyses in this repository rely on four externally produced datasets.

The required filenames are:

- `CSI-1953-2014.xls`
- `CSI_2015-2024.zip`
- `SCDB_2025_01_justiceCentered_Citation.csv_.zip`
- `CLRSalienceEstimates100714.RData`

## 1. Case Salience Index, 1953–2014

**Authors:** Todd A. Collins and Christopher A. Cooper

**Original download:**  
https://www.wcu.edu/WebFiles/Excel/CSI-1953-2014.xls

**Archived download:**  
https://web.archive.org/web/20260910201013/https://www.wcu.edu/WebFiles/Excel/CSI-1953-2014.xls

**Required filename:**  
`CSI-1953-2014.xls`

Because no explicit redistribution license could be identified, the original data file is not redistributed in this repository. Users should download it from the original provider or archived location and place it in the `data/` directory.

## 2. Case Salience Index, 2015–2024

**Authors:** Matthew T. Cota, Rachael Houston, Elizabeth A. Lane, and Jessica A. Schoenherr

**Original download:**  
https://matthewtcota.com/files/CSI_2015-2024.zip

**Archived download:**  
https://web.archive.org/web/20260910201142/https://matthewtcota.com/files/CSI_2015-2024.zip

**Required filename:**  
`CSI_2015-2024.zip`

Users should download the source file from the original provider or archived location and place it in the `data/` directory.

## 3. Supreme Court Database

**Dataset:** Supreme Court Database, 2025 Release 01

The analysis uses the **Justice-Centered, Citation-Organized** dataset.

**Original release page:**  
https://scdb.la.psu.edu/data/2025-release-01/

**Archived release page:**  
https://web.archive.org/web/20260910200834/https://scdb.la.psu.edu/data/2025-release-01/

**Required filename:**  
`SCDB_2025_01_justiceCentered_Citation.csv_.zip`

Because no explicit redistribution license could be identified, the original SCDB data file is not redistributed in this repository. Users should obtain the relevant file from the original or archived release page and place it in the `data/` directory.

## 4. Clark–Lax–Rice pre-decision salience estimates

**Authors:** Tom S. Clark, Jeffrey R. Lax, and Douglas R. Rice

**Dataset:** *Measuring the Political Salience of Supreme Court Cases*

**Original download:**  
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2F29637

**Archived download:**  
https://web.archive.org/web/20260917195840/https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2F29637

**DOI:**  
https://doi.org/10.7910/DVN/29637

**Required filename:**  
`CLRSalienceEstimates100714.RData`

These data provide the pre-decision salience estimates used in the salience-measurement validation analyses. The analysis code expects this file to be placed in the `data/` directory.

Because the data are externally produced, users should obtain the file from the original Harvard Dataverse record and comply with the terms specified by the original provider.

## Licensing

The MIT License in the root of this repository applies only to the analysis code authored for this project.

It does not apply to the externally produced source datasets described above. Those datasets remain subject to the terms of their respective original providers.
