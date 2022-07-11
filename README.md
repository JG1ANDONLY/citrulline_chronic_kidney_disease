# GWAS Study: Analysis of Citrulline Levels and Chronic Kidney Disease

## Introduction

Citrulline was first extracted from watermelon juice (Bahri et al., 2013). It has a unique metabolism: citrulline can only be synthesized by the intestine, and since citrulline is mainly metabolized into arginine by the kidney, citrulline has been employed as a marker of renal failure linked to impaired citrulline metabolism (Bahri et al., 2013).

In this project, I performed a GWAS analysis on the citrulline levels and chronic kidney disease and aimed to find SNPs with the most significant p-values for each peak in the Manhattan plots. 

## Methods

I used Manhattan plots and QQ plots with **NO** covariates to identify significant SNPs and discuss about causal polymorphisms. Principal Component Analysis (PCA) on genotype data was performed, and I obtained two principal components. Manhattan plots and QQ plots were made again with two principal components as two covariates. I also did Bonferroni correction, trying to reduce the type I error that falsely rejected the null hypothesis of no association and minimize the influence of linkage disequilibrium.

## Conclusion

I identified two clear peaks with two covariates added and their corresponding SNP number.

## References

Bahri, S., Zerrouk, N., Aussel, C., Moinard, C., Crenn, P., Curis, E., ... & Sfar, S. (2013). Citrulline: from metabolism to therapeutic use. *Nutrition*, *29*(3), 479-484.
