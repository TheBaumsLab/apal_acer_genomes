# Genome assemblies, genetic maps, and annotations of Acropora palmata and Acropora cervicornis

![alt text](https://github.com/mistergroot/apal_acer_genomes/blob/main/Apalm_Acer_photo.jpg?raw=true)

Here, we make available the code and genomic resources described in [Locatelli et al., 2023](https://doi.org/10.1101/2023.12.22.573044). These files describe the genomic resources for Florida _Acropora palmata_ sampled at Horseshoe Reef (genet HS1, STAGdb ID HG0004) and _Acropora cervicornis_ sampled from Grassy Key (genet M5, STAGdb ID HG0005).

In `jupyter_notebooks/`, we provide code for _Acropora cervicornis_ (prefix `Acervicornis` in all files) genome assembly, gene prediction, and functional annotation in FunAnnotate. We additionally provide code for _Acropora palmata_ (prefix `Apalmata` in all files) and _Acropora cervicornis_ linkage map generation using LepWrap. Further, we provide code for some figure generation, whole genome alignments and dotplots, and phylogenetically significant gene family expansion analyses (CAFE5).

In `resources/`, we provide chromosome-level genome assemblies (`.fa.gz`), gene predictions (`.gff3.gz`), functional annotations (`.annotations.txt.gz`), masks for repetitive content (`.repeatmask.bed.gz`), and PLINK-formatted male, female, and sex-average genetic maps (`.map`) for _Acropora cervicornis_ and _Acropora palmata_. Please keep in mind that the assemblies and annotations for each species were generated in slightly different ways, as described in the manuscript. So not all files are identically formatted. 
