# ECGpred: Correlation and prediction of gene expression level from amino acid and dipeptide composition of its protein

This study explores the relationship between the amino acid and dipeptide composition of a protein and its corresponding gene expression levels. By analyzing high-throughput microarray data,
the study demonstrates that the primary sequence of a protein contains significant information that correlates with how much of that protein is expressed in a cell.

## Citation
Raghava, G. P. S., & Han, J. H. (2005).
Correlation and prediction of gene expression level from amino acid and dipeptide composition of its protein. BMC Bioinformatics, 6:59.

https://doi.org/10.1186/1471-2105-6-59


This dataset can also be found on Zenodo at

## About the Research

In the post-genomic era, understanding the regulation of gene expression is a major challenge. While many studies focus on regulatory elements in DNA or mRNA stability, this study investigates the
"protein-side" of the equation. It suggests that the amino acid composition—essentially the building blocks of the protein—is non-randomly associated with the abundance of that protein.

* **Dataset**: The study utilized protein sequence data and gene expression levels for *Saccharomyces cerevisiae* (yeast).


* **Methodology**: Systematic correlation analysis was performed between expression levels and the frequency of 20 amino acids and 400 possible dipeptides.



## Key Features

### 1. Significant Correlation with Amino Acid Composition

The study identified that the frequency of certain amino acids in a protein's primary sequence strongly correlates with its expression level.

* **Positive Correlation**: Amino acids like Valine, Glycine, and Alanine show a significant positive correlation with high expression levels.


* **Negative Correlation**: Residues such as Asparagine, Leucine, and Isoleucine tend to be more frequent in proteins with lower expression levels.


* **Overall Impact**: Amino acid composition alone can account for a significant portion of the variance in gene expression.



### 2. Dipeptide Composition Analysis

Beyond single amino acids, the study examined pairs of adjacent residues (dipeptides).

* **Higher Predictive Power**: Dipeptide composition provides more detailed information and shows a higher correlation with expression levels than simple amino acid composition.


* **Specific Patterns**: Certain dipeptides are highly preferred in abundant proteins, while others are avoided.



### 3. Predictive Modeling

The researchers developed computational models to predict the expression level of a gene based solely on its protein sequence.

* **Machine Learning**: Support Vector Machine (SVM) and Artificial Neural Network (ANN) models were implemented.


* **Performance**: The models achieved a correlation coefficient of up to 0.70 between predicted and experimental expression levels.


## Applications

* **Functional Genomics**: Estimating the expression levels of genes in newly sequenced genomes where experimental data is not yet available.


* **Proteomics**: Understanding protein stability and turnover rates, as amino acid composition may influence a protein's half-life and cellular abundance.


* **Synthetic Biology**: Designing synthetic genes with optimized sequences to achieve specific expression targets by manipulating their amino acid and dipeptide composition.



## Contact & Authors

Prof. Gajendra P. S. Raghava (Corresponding Author)

raghava@iiitd.ac.in

IIIT Delhi
## Support

The research was supported by the **Council of Scientific and Industrial Research (CSIR)** and the **Department of Biotechnology (DBT)**, Government of India.
