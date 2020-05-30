# ConjurersBrew/

This repository houses the complete materials for reproducing microbiota-related results and metabolite PCA/hierarchical clustering published in: <br/>

## Metabolite profile comparisons between ascending and descending colon tissue in healthy adults

Baxter et al. 2020 <br/>
Journal: *World Journal of Gastroenterology* <br/>
[doi](https://www.wjgnet.com/1007-9327/full/v26/i3/335.htm) and [PMID](https://pubmed.ncbi.nlm.nih.gov/31988593/) <br/>
citation: Baxter, BA, KD Parker, MJ Nosler, S Rao, R Craig, C Seiler, EP Ryan. 2020. Metabolite profile comparisons between ascending and descending colon tissue in healthy adults. *World J Gastroenterol*. doi: 10.3748/wjg.v26.i3.335. PMID: 31988593. <br/>

**Abstract:** ***Background***: Obesity is a risk factor for colorectal cancer, yet metabolic distinctions between healthy right and left colon tissue, before cancer is diagnosed, remains largely unknown. This study compared right-ascending and left-descending colon tissue metabolomes to identify differences from the stool metabolome in normal weight, overweight, and obese adults. ***Aim***: To examine right and left colon tissue metabolites according to body mass index that may serve as mechanistic targets for interventions and biomarkers for colon cancer risk. ***Methods***: Global, non-targeted metabolomics was applied to assess right-ascending and left-descending colon tissue collected from healthy adults undergoing screening colonoscopies to test the hypothesis that BMI differentially impacts colon tissue metabolite profiles. The colon tissue and stool metabolome of healthy adults (n = 24) was analyzed for metabolite signatures and metabolic pathway networks implicated in progression of colorectal cancer. ***Results***: Ascending and descending colon contained 504 host, food, and microbiota-derived metabolites from normal weight, overweight and obese adults grouped according to body mass index. Amino acids, lipids, and nucleotides were among the chemical types that further differentiated from the stool metabolite profiles. Normal weight adults had 46 significantly different metabolites between ascending and descending colon tissue locations, whereas there were 37 metabolite differences in overweight and 28 metabolite differences for obese adults (P < 0.05). Obese adults had trimethylamine N-oxide, endocannabinoids and monoacylglycerols with different relative abundances identified between ascending and descending colon. Primary and secondary bile acids, vitamins, and fatty acids also showed marked relative abundance differences in colon tissue from overweight/obese adults. ***Conclusion***: There were metabolite profile differences between right-ascending and left-descending colon tissue in healthy adults. Colon lipids and other metabolites in obese and overweight adults were distinguished from normal weight participants and associated with gut inflammation, nutrient absorption, and products of microbiota metabolism. ***Keywords***: Ascending; Colon; Descending; Metabolomics; Obesity; Stool. <br/>

## Overview
`raw_fastq/` = demultiplexed (individual) fastq sequence files for each sample <br/>
`sra/` = items relevant for submission to the NCBI Sequence Read Archive ([BioProject Accession PRJNA594611](https://www.ncbi.nlm.nih.gov/bioproject/?term=594611)) <br/>
`ConjurersBrew.Rproj` = base of operations for running scripts in R Studio <br/>

## prior to uploading - I am working on organizing the following into an easier format for reproducibility:
`class/` = contains reference sequences used to train taxonomy classifiers (see: `Script_01.R` section *Q - STEP X*) <br/>
`dada2/` = contains outputs for dada2 feature table construction (see: `Script_01.R` section *Q - STEP 3* and *Q - STEP 4*) <br/>
`dvrs/` = contains outputs for alpha and beta diversity analysis in QIIME2 (see: `Script_01.R` section *Q - STEP X* and *Q - STEP X*) <br/>
`main/` = pdfs for main text figures <br/>
`reads/` = contains raw and trimmed sequence reads (see: `Script_01.R` sections *Q - STEP 1* and *Q - STEP 2*) <br/>
`supplement/` = includes figures/tables/files for supplementary materials <br/>
`taxa/` = contains Greengenes/SILVA taxonomic classifications for each FeatureID (see: `Script_01.R` section *Q - STEP 6*) <br/>
`tree/` = contains outputs for phylogenetic tree created in QIIME2 (see: `Script_01.R` section *Q - STEP X*) <br/>
`vault/` = central storage for items produced in each of the `.R` scripts <br/>
`sampledata_CB.txt` = sample data file <br/>
`Script_01.R` = manifest creation and QIIME 2 processing/analysis <br/>
`Script_02.R` = metataxonomics analysis <br/>
`Script_03.R` = metabolite PCA/hierarchical clustering <br/>

Due to file size restrictions, a few items cannot be uploaded into their respective locations above. To overcome this limitation, the master directory with complete materials will be compressed and uploaded to Google Drive. That directory will then be available for download by clicking "Download anyway" after visiting the following [link ~pending](https://github.com/kdprkr/ConjurersBrew). To setup proper file paths, download, uncompress, and move `ConjurersBrew/` onto the `Desktop/`. <br/>

If any files cannot be located or if any links are broken, **please open an issue**. <br/>

If you have any questions regarding any items here, **please contact me via the email listed on my profile**. <br/>
