# ConjurersBrew/

This repository houses the complete materials for reproducing microbiota-related results and metabolite PCA/hierarchical clustering published in: <br/>

## Metabolite profile comparisons between ascending and descending colon tissue in healthy adults

Baxter et al. 2020 <br/>
Journal: *World Journal of Gastroenterology* <br/>
[doi](https://www.wjgnet.com/1007-9327/full/v26/i3/335.htm) and [PMID](https://pubmed.ncbi.nlm.nih.gov/31988593/) <br/>
citation: Baxter, BA, KD Parker, MJ Nosler, S Rao, R Craig, C Seiler, EP Ryan. 2020. Metabolite profile comparisons between ascending and descending colon tissue in healthy adults. *World J Gastroenterol*. doi: 10.3748/wjg.v26.i3.335. PMID: 31988593. <br/>

**Abstract:** ***Background***: Obesity is a risk factor for colorectal cancer, yet metabolic distinctions between healthy right and left colon tissue, before cancer is diagnosed, remains largely unknown. This study compared right-ascending and left-descending colon tissue metabolomes to identify differences from the stool metabolome in normal weight, overweight, and obese adults. ***Aim***: To examine right and left colon tissue metabolites according to body mass index that may serve as mechanistic targets for interventions and biomarkers for colon cancer risk. ***Methods***: Global, non-targeted metabolomics was applied to assess right-ascending and left-descending colon tissue collected from healthy adults undergoing screening colonoscopies to test the hypothesis that BMI differentially impacts colon tissue metabolite profiles. The colon tissue and stool metabolome of healthy adults (n = 24) was analyzed for metabolite signatures and metabolic pathway networks implicated in progression of colorectal cancer. ***Results***: Ascending and descending colon contained 504 host, food, and microbiota-derived metabolites from normal weight, overweight and obese adults grouped according to body mass index. Amino acids, lipids, and nucleotides were among the chemical types that further differentiated from the stool metabolite profiles. Normal weight adults had 46 significantly different metabolites between ascending and descending colon tissue locations, whereas there were 37 metabolite differences in overweight and 28 metabolite differences for obese adults (P < 0.05). Obese adults had trimethylamine N-oxide, endocannabinoids and monoacylglycerols with different relative abundances identified between ascending and descending colon. Primary and secondary bile acids, vitamins, and fatty acids also showed marked relative abundance differences in colon tissue from overweight/obese adults. ***Conclusion***: There were metabolite profile differences between right-ascending and left-descending colon tissue in healthy adults. Colon lipids and other metabolites in obese and overweight adults were distinguished from normal weight participants and associated with gut inflammation, nutrient absorption, and products of microbiota metabolism. ***Keywords***: Ascending; Colon; Descending; Metabolomics; Obesity; Stool. <br/>

## Overview
`sra/` = items relevant for submission to the NCBI Sequence Read Archive ([BioProject Accession PRJNA594611](https://www.ncbi.nlm.nih.gov/bioproject/?term=594611)) <br/>





If any files cannot be located or if any links are broken, **please open an issue**. <br/>

If you have any questions regarding any items here, **please contact me via the email listed on my profile**. <br/>








`class/` = contains reference sequences used to train taxonomy classifiers (see: `Code_S1.R`) <br/>
`dada2/` = contains outputs for dada2 feature table construction (see: `Code_S1.R`) <br/>
`main/` = pdfs for main text figures <br/>
`raw_fastq/` = demultiplexed (individual) fastq sequence files for each sample <br/>
`revision_01/` = items produced for revised submission (1st round) to *Beneficial Microbes* <br/>
`revision_02/` = items produced for revised submission (2nd round) to *Beneficial Microbes* <br/>
`sra/` = items relevant for submission to the NCBI Sequence Read Archive ([BioProject Accession PRJNA516457](https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA516457)) <br/>
`submission/` = items produced for original submission (pre-revisions) to *Beneficial Microbes* <br/>
`supplement/` = includes figures/tables/files for supplementary materials <br/>
`taxa/` = contains Greengenes/SILVA taxonomic classifications for each FeatureID (see: Code_S1.R) <br/>
`vault/` = central storage for items produced by `Code_S1.R` and `Code_S2.R` <br/>
`Code_S1.R` = manifest creation and QIIME 2 processing <br/>
`Code_S2.R` = post QIIME 2 analysis conducted in R <br/>
`MerlinsManuscript.Rproj` = base of operations for running `Code_S1.R` and `Code_S2.R` in R Studio <br/>
`MetadataFile_S1.txt` = sample data file <br/>
`manifest_R1.csv` = manifest file for importing demultplexed fastq files into QIIME 2 (see: `Code_S1.R`) <br/>
`seqs_R1.qzv` = sequence read visualization artifact <br/>
`seqs_R1_trim.qzv` = trimmed sequence read visualization artifact <br/>
