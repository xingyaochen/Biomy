## Biomy
##Description: 
Biomy is a novel method of Quantitative Trait Loci analysis that is much more efficient and accessible! It does not require an F2 cross or microarray data. The function {traittree} clusters a set of mouse strains by their phenotypes, such as weight and blood pressure. Using a dataset of SNP data for those same strains, the function {maketree} scans through the entire SNP dataset to generate a large set of dendrograms, each clustering strains by consecutive 100 SNPs. csv files of SNP data for most strains can be found at opensource websites such as MGI, NCBI, or the University of North Carolina at Chapel Hill CSBio site. Correlating quantitative traits to Single Nucleotide Polymorphisms of strains. Next, the function {snpcor} runs correlation calculations with the trait dendrogram against each SNP dendrogram, and subsequently calculates Baker's correlation coefficients and the approximate location (bp) of the SNP. The function {snpcor.best} takes the correlation dataframe and subsets it into a smaller dataframe consisting of only SNPs with a correlation coefficient above a specified threshold. These are the most likely SNPs where causal genes are located. Finally, the function {drawtangle} visualizes the trait-SNP correlation by plotting out tanglegrams (two side by side dendrograms with lines connecting identical strains).
#
##Link: 
Visit this link to download the latest package: <https://github.com/16xchen/Biomy>
#
##Install:
To install the package into R, use the following commands:

install.packages("devtools")

library(devtools)

install_github("16xchen/Biomy")

library(Biomy)
#
##Contact: 
If there is any trouble with the package, contact me at <16xchen@mdirss.org>
#
#
