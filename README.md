# Cumulative genetic risk and C9orf72 repeat status independently associate with ALS status in two case-control studies

John F. Dou, Kelly M. Bakulski, Kai Guo Junguk Hur, Lili Zhou, Sara Saez-Atienzar, Ali R Stark, Ruth Chia, Alberto García-Redondo, Ricardo Rojas-García, Juan Francisco Vázquez-Costa, Ruben Fernandez Santiago, Sara Bandres-Ciga, Pilar Gómez-Garre, Maria Teresa Periñán, Pablo Mir, Jordi Pérez-Tur, Fernando Cardona, Manuel Menendez-Gonzalez, Javier Riancho, Daniel Borrego-Hernández, Lucía Galán-Dávila, Jon Infante Ceberio, Pau Pastor, Carmen Paradas, Spanish Neurological Consortiuma, Bryan J. Traynor6, Eva L. Feldman, and Stephen A Goutman

Members of the Spanish Neurological Consortium: Jesús Esteban-Pérez, Pilar Cordero-Vázquez, Sevilla Teresa, Adolfo López de Munain1, Julio Pardo-Fernández, Ivonne Jericó-Pascual, Oriol Dols-Icardo, Ellen Gelpi Mantius, Janet Hoenicka, Victoria Alvarez Martinez, Francisco Javier Rodríguez de Rivera Garrido, Katrin Beyer, Jordi Clarimón Echevarría


### Abstract 
**Background**: Most amyotrophic lateral sclerosis (ALS) patients lack a monogenic mutation. This study evaluates ALS cumulative genetic risk in an independent Michigan and Spanish replication cohort using polygenic scores.
**Methods**: ALS (n=219) and healthy control (n=223) participant samples from University of Michigan were genotyped and assayed for the C9orf72 hexanucleotide expansion. Polygenic scores excluding the C9 region were generated using an independent ALS genome-wide association study (20,806 cases, 59,804 controls). Adjusted logistic regression and receiver operating characteristic curves evaluated the association and classification between polygenic scores and ALS status, respectively. Population attributable fractions and pathway analyses were conducted. An independent Spanish study sample (548 cases, 2,756 controls) was used for replication.
**Results**: Polygenic scores constructed from 275 single nucleotide polymorphisms had the best model fit in the Michigan cohort. A standard deviation increase in ALS polygenic score associated with 1.28 (95%CI 1.04-1.57) times higher odds of ALS with area under the curve of 0.663 versus a model without the ALS polygenic score (p-value=1x10-6). The population attributable fraction of the highest 20th percentile of ALS polygenic scores, relative to the lowest 80th percentile, was 4.1% of ALS cases. Genes annotated to this polygenic score enriched for important ALS pathomechanisms. Meta-analysis with the Spanish study, using a harmonized 132 single nucleotide polymorphism polygenic score, yielded similar logistic regression findings (odds ratio: 1.13, 95%CI 1.04-1.23).
**Conclusion**: ALS polygenic scores can account for cumulative genetic risk in populations and reflect disease-relevant pathways. If further validated, this polygenic score will inform future ALS risk models.

### Citation Information 
Dou JF, Bakulski KM, Guo K, Hur J, Zhou L, Saez-Atienzar S, Stark AR, Chia R, García-Redondo A, Rojas-García R, Vázquez-Costa JF, SantiagonRF, Bandres-Ciga S, Gómez-Garre P, Periñán MT, Mir P, Pérez-Tur J, Cardona F, Menendez-Gonzalez M, Riancho J, Borrego-Hernández D, Galán-Dávila L, Ceberio JI, Pastor P, Spanish Neurological Consortium, Traynor BJ, Feldman EL, Goutman SA, & Spanish Neurological Consortium. 2022. Cumulative genetic risk and C9orf72 repeat status independently associate with ALS status in two case-control studies. medRxiv. https://doi.org/10.1101/2022.10.27.22281377 

### Script files 
01_missing.Rmd: Keep track of counting; checking and filtering based on missingness
02_sex.Rmd: samples missing sex confirmed to have correct predicted sex
03_MAF.Rmd: checking MAF frequency and Removing SNPs with a low MAF frequency
04_HWE.Rmd: checking Hardy-Weinberg equilibrium (HWE) and removing snps deviating from HWE
05_heterozygosity.Rmd: changing heterozygosity exclusion cutoff and removing samples with large deviations
06_relatedness.Rmd: checking relationships between individuals and sample match issue
07_Ancestry.Rmd: getting self report race/ethnicity and resolving merge issues
08_Impute.Rmd: imputation
09_PGS.Rmd: PGS modelling
