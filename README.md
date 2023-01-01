# SV_SNPs
Structural Variants in Linkage Disequilibrium with GWAS-Significant SNPs

## snv_disease_sv_f100k_G0.8.txt
GWAS SNP-SV pairs that exceeded a squared correlation coefficient of 0.80 (g2>0.8)

--SVS: SV id assigned by this study. e.g. SV1 represents the first sv in file freeze3.sv.alt.vcf (also in freeze3.sv.alt.ID.vcf).

--FLANK: Relative position of this SNP and this SV. Within upstrem (-) 100k or downstream (+) 100k.

--G_VALUE: Correlation coefficient of this SV and SNP.

--P_VALUE(G): P value of G value.

--SNPS: SNP id.

--DISEASE/TRAIT: Disease or trait examined in study.

--MAPPED_TRAIT: Mapped Experimental Factor Ontology trait for this study.

--OR or BETA: Reported odds ratio or beta-coefficient associated with SNP risk allele.

--P-VALUE: Reported p-value for SNP risk allele.

--CHR_ID: Chromosome number associated with rs number.

--CHR_POS: Chromosomal position associated with rs number.

--STRONGEST SNP-RISK ALLELE: SNP + risk allele.

--RISK ALLELE FREQUENCY: Reported risk/effect allele frequency in controls.

--REPORTED GENE(S): Gene(s) reported by author.

--MAPPED_GENE: Gene(s) mapped to the SNP.

--RowNum: Row number in GWAS_Catalog_All_Associations_v1.0.2.tsv that you can get more information about this SNP and related disease/trait.

## snv_disease_sv_f100k.txt
All GWAS SNP-SV pairs generated in this study.

## freeze3.sv.alt.vcf
The original vcf file of SVs. Obtained from https://www.internationalgenome.org/data-portal/data-collection/hgsvc2

## freeze3.snv.alt.vcf
The original vcf file of SNVs. Obtained from https://www.internationalgenome.org/data-portal/data-collection/hgsvc2

## freeze3.sv.alt.ID.vcf
SVs vcf file with assigned IDs.

## freeze3.sv.alt.bed
Bed format file of SVs.

## GWAS_Catalog_All_Associations_v1.0.2.tsv
GWAS catalog of all associations.

Obtained from https://www.ebi.ac.uk/gwas/docs/file-downloads

More description could be found in https://www.ebi.ac.uk/gwas/docs/fileheaders
