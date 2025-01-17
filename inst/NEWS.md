- Added `ORthr` and `featureLvls` arguments to plotEnrichmentResults. Issue: [715](https://github.com/PoisonAlien/maftools/issues/715)

# CHANGES IN VERSION 2.8.0

## NEW FUNCTIONS
- `cancerhotspots` Genotype known cancer hotspots from the tumor BAM file
- `bamreadcounts` extract nucleotide counts for targeted variants from the BAM file.
- `maftools` now natively loads TCGA cohorts. `tcgaAvailable` and `tcgaLoad` will display and load the desired cohorts.
- Added `MAF` constructor function
- Added `maf2mae` for converting `MAF` to `MultiAssayExperiment` class objects Issue: [640](https://github.com/PoisonAlien/maftools/issues/640) [293](https://github.com/waldronlab/MultiAssayExperiment/pull/293) Discussion: [285](https://github.com/waldronlab/MultiAssayExperiment/discussions/285)
- Added `plotProtein` and `mafbarplot`

## ENHANCEMENTS
- Added protein domains for the gene `ALMS1`. Issue: [705](https://github.com/PoisonAlien/maftools/issues/705)
- Added `titv_col` argument to oncoplot. Issue: [702](https://github.com/PoisonAlien/maftools/issues/702)
- Added protein domains for the gene `FAM205A`. Issue: [701](https://github.com/PoisonAlien/maftools/issues/701)
- `oncoplot` can now summarize `variant_classifications` similar to cBioPortal style. Issue: [686](https://github.com/PoisonAlien/maftools/issues/686) 
- Added pathway support for `mafCompare()` or `clinicalEnrichment()`. Issue: [681](https://github.com/PoisonAlien/maftools/issues/681) 
- Added default title for side and topbar plots to `oncoplot`. Issue: [682](https://github.com/PoisonAlien/maftools/issues/682) 
- Added `annotationOrder` argument to `coOncoplot`. Issue: [676](https://github.com/PoisonAlien/maftools/issues/676) 
- Added `plot` argument to `survGroup`. Thank you [OmarElAshkar](https://github.com/OmarElAshkar) PR: [674](https://github.com/PoisonAlien/maftools/issues/674) 
- Added `rmFlags` argument to `read.maf`. Issue: [668](https://github.com/PoisonAlien/maftools/issues/668)
- Added `path_order` argument to `oncoplot` for custom ordering of pathways on oncoplot. 
- Added `geneMar` argument to `coBarplot`. Issue: [260](https://github.com/PoisonAlien/maftools/issues/260) 

## BUG FIXES
- `coOncoplot` not allowing more than one additional feature. Issue: [675](https://github.com/PoisonAlien/maftools/issues/675)
