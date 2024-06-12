# DSRJNMF

This project proposed a deep-self reconstructed joint nonnegative matrix factorization (DSRJNMF) model to identify the imaging genetic association of complex diseases. 

The code in this project will reproduce the results in our paper, "*Deep Self-reconstruction Driven Joint Nonnegative Matrix Factorization Model for Identifying Multiple Genomic Imaging Associations in Complex Diseases*". The code was implemented and tested using Matlab.

You can run it by the .zip archive named DSRJNMF. The *DSRJNMF.zip* contains the *DSR* file and *JNMF* file. 

1. You can run the DSR model using *main_SR1.m* in the DSR file.The input files include *WSI.csv*, *miRNA.csv* and *genes.csv*.The output is the reconstructed three files. Afterwards, the reconstructed files are used as inputs to the JNMF model.

2. The reconstructed datasets were normalized to obtain *WSI_re_normalized.csv*, *miRNA_re_normalized.csv* and *miRNA_re_normalized.csv* in the JNMF file. After that the JNMF model can be implemented by running the *main.m* file in the JNMF file and the output is the decomposed *W* and three *H* matrices.

3. The three *H* matrices can be used to identify the significant features and select the appropriate co-modules.

Contact Information:

Jin Deng, South China Agricultural University, Guangzhou, Guangdong, China. Email: jindsmu@gmail.com

References:

[1]M. L. Wang, W. Shao, X. K. Hao, S. Huang, and D. Q. Zhang, “Identify connectome between genotypes and brain network phenotypes via deep self-reconstruction sparse canonical correlation analysis, Bioinformatics, vol. 38, no. 8, pp. 2323-2332, Apr 12, 2022.

[2]J. Deng, W. M. Zeng, S. Z. Luo, W. Kong, Y. H. Shi, Y. Li, and H. Zhang, “Integrating multiple genomic imaging data for the study of lung metastasis in sarcomas using multi-dimensional constrained joint non-negative matrix factorization”, Information Sciences, vol. 576, pp. 24-36, Oct, 2021.

[3]D. D. Lee, and H. S. Seung, “Learning the parts of objects by non-negative matrix factorization”, Nature, vol. 401, no. 6755, pp. 788-791, Oct, 1999.

[4]S. H. Zhang, C. C. Liu, W. Y. Li, H. Shen, P. W. Laird, and X. J. Zhou, “Discovery of multi-dimensional modules by integrative analysis of cancer genomic data”, Nucleic Acids Research, vol. 40, no. 19, pp. 9379-9391, Oct, 2012.

[5]C. Boutsidis, and E. Gallopoulos, “SVD based initialization: A head start for nonnegative matrix factorization”, Pattern Recognition, vol. 41, no. 4, pp. 1350-1362, Apr, 2008.
