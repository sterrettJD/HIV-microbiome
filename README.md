# HIV-microbiome
Gut microbiome of HIV+ individuals in rural Appalachia

## Index
- Analysis.ipynb contains the microbiome processing and statistical analysis.
- Lipidome.ipynb contains the short chain fatty acid analysis.
- SCNIC.ipynb contains code used to generate cooccurrence network and modules from the microbiome data.

## Front Range Microbiome Symposium Abstract

Human Immunodeficiency Virus (HIV) is associated with altered microbiome composition and increased risk for comorbid metabolic syndrome.
We analyzed liver steatosis and fibrosis, microbiomes, and short chain fatty acid (SCFA) profiles of 20 HIV+ individuals vs 20 HIV- 
(body mass index (BMI) and age-matched) control participants from rural Appalachia. 
Stool samples were sequenced using 16S rRNA metabarcoding on Illumina to generate paired-end 300 base pair reads, 
and SCFA concentrations were quantified via gas chromatography with flame ionization. 16S sequencing reads were binned into 
amplicon sequence variants using DADA2, a phylogenetic tree was created using saté-enabled phylogenetic placement, 
and taxonomy was assigned using a naïve-Bayes classifier trained on the SILVA database. Samples were rarefied to 52,495 reads, 
Faith’s phylogenetic diversity was used to assess alpha diversity, and unweighted UniFrac was used for beta diversity. 


We found increased liver steatosis (Welch’s t(37.7)=2.59, p=0.013) and fibrosis (t(28.9)=2.02, p=0.052) in HIV+ individuals. 
A Kruskal-Wallis test revealed no significant difference in alpha diversity by HIV status, 
but a permutational ANOVA revealed a significant difference in microbiome composition (pseudo-F = 1.91, p = 0.003). 
A Kruskal-Wallis test additionally revealed significantly lower fecal concentrations of acetate (H(1)=7.94, p=0.005) 
and butyrate (H(1) = 8.23, p = 0.004) in HIV+ individuals, whereas there were no significant differences in propionate, 
isobutyrate, isovalerate, valerate, and caproate. In HIV+ individuals, differential abundance testing (Gneiss, ANCOM) a
nd co-occurrence network module analysis (SCNIC + ANCOM) revealed increased relative abundances of the phylum Bacteroidota 
and the genus Prevotella, as well as a decreased relative abundance an uncultured group of Erysipelatoclostridiaceae. 
Overall, this study revealed a difference in microbiome composition and fecal fermentation profiles between HIV+ individuals and age- 
and BMI-matched controls, characterized by increased Prevotella and Bacteroidota.
