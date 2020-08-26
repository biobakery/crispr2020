# crispr2020
https://huttenhower.sph.harvard.edu/crispr2020/ datasets downloads


# Accompanying dataset to the study "Natural CRISPR systems and targets in the human microbiome" 
 
## Description
 
This webpage hosts data products resulting from the CRISPR and _cas_ gene study of the Human Microbiome Project (HMP1-II) population, consisting of spacer and repeat sequences (`hmp1-II-crispr-spacers.tar.gz`, `hmp1-II-crispr-repeats.tar.gz`) recovered from shotgun metagenomes using a read-based approach (Crass, Skennerton et al, 2013). The functional and taxonomic spacer annotations were obtained by aligning the spacer content to each sample’s metagenome and corresponding UniRef90 collection (`hmp1-II-crispr-spacers-annotation.tar.gz`).
 
We further provide the UniRef90 profiling of the 2,355 metagenomes of the HMP1-II collection that was used as the basis of the Cas1-Cas12 analysis (Files `hmp1-II_uniref90.tar.gz` and `hmp1-II_uniref90_cas.tar.gz`). We used a custom HUMAnN 2 database to subset relevant protein families (`humann2_cas_mapping.tar.gz`).
 
## Datasets
 
CRISPR elements
 
| Dataset  | MD5 |  Description |  
|---|---|---|
| [hmp1-II-crispr-spacers-annotation.tar.gz](http://huttenhower.sph.harvard.edu/CRISPR_2020/hmp1-II-crispr-spacers-annotation.tar.gz) | `710c6dca143017c58acf3f98f7877736` |  annotated spacer set |
| [hmp1-II-crispr-spacers.tar.gz](http://huttenhower.sph.harvard.edu/CRISPR_2020/hmp1-II-crispr-spacers.tar.gz) | `104b51c91063161a7d4a5bfc30e4bc3d` | CRISPR spacers |  
| [hmp1-II-crispr-repeats.tar.gz](http://huttenhower.sph.harvard.edu/CRISPR_2020/hmp1-II-crispr-repeats.tar.gz) |  `a2893a93321792f9ec7fd569f1973ab5` |  CRISPR repeats | 
 
Cas profile
 
| Dataset  | MD5 |  Description |  
|---|---|---|
| [hmp1-II_uniref90.tar.gz](http://huttenhower.sph.harvard.edu/CRISPR_2020/hmp1-II_uniref90.tar.gz) | `todo` | Global UniRef90 Profile generated with the HMP Unified Metabolic Analysis Network (HUMAnN2) and normalized for gene length and sequencing depth | 
| [humann2_cas_mapping.tar.gz](http://huttenhower.sph.harvard.edu/CRISPR_2020/humann2_cas_mapping.tar.gz) |  `7e75d603475d63cd08e05ae2478c4d8a` |  Cas table of UniRef90 families used to subset the global UniRef90 Profile for Cas analysis | 
| [hmp1-II_uniref90_cas.tar.gz](http://huttenhower.sph.harvard.edu/CRISPR_2020/hmp1-II_uniref90_cas.tar.gz) | `ccd7e242dd80e50c17a10e2b9bd54e5e` | Filtered UniRef90 abundance profile for relevant Cas1 - Cas12 gene families (normalized for gene length and sequencing depth) | 
 
## Citation
 
If you find this data useful, please cite our paper
 
> Philipp C. Münch, PC, Franzosa EA, Stecher B, McHardy AC* and Huttenhower C*. Natural CRISPR systems and targets in the human microbiome, Cell Host & Microbe (in Revision)
* these authors share senior authorship

