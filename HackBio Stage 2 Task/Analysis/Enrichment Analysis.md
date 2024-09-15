<!--StartFragment-->


# **Stage 2 Task - Gene Expression and Functional Enrichment Analysis**

**Contributors** : Mahima Chakraborty (@mahima\_ch), Pooja Solanki (@poojasolanki2024), Mercy Ade-Ige (@MaiStar), Nourhan Saad (@Nourhan-25), Mariam Mohamed (@Mariam000v), Osama Shukri (@Osama)


## **Introduction**

In this project, we have visualized and interpreted a glioblastoma gene expression dataset to generate a heatmap and perform downstream functional enrichment analysis in order to interpret patterns of gene expression and understand the biological significance of differentially expressed genes using R programming.

Our analysis of the upregulated genes in the glioblastoma identified the below enriched pathways as the top five in terms of biological processes, in which they are significantly involved in the pathogenesis of cancer, especially glioblastoma.

**1) Transcription by RNA polymerase II (GO:0006357)**

This process is a part of crucial pathways involved in regulation of gene expression, hence the regulation of cell proliferation and survival. Transcription dysregulation can promote oncogenes leading to tumorigenesis and survival of cancer cells; therefore, it is a hallmark in glioblastoma \[21].

**2) Embryonic morphogenesis (GO:0048598)**

The enriched involvement of the analysed genes in embryonic morphogenesis, further highlights the involvement of the development pathways in glioblastoma. The development pathways are crucial for building and maintaining tissue structure and shape, therefore their dysregulation promotes malignancy \[19].

**3) Anatomical structure morphogenesis (GO:0009653)**

The involvement of the analysed genes in this process, suggests that glioblastoma changes its morphology when grows and invade the brain, by utilizing the morphogenetics to enhance its structure and adaptability. This promotes its resistance to anticancer therapies \[22,23].

**4) Regulation of Neuron Differentiation (GO:0045664)**

This process involves modulating the frequency or extent of neuron differentiation, where neural stem or progenitor cells become specialized neurons. GBM can exhibit aberrant neurogenesis, with tumor cells co-opting neuron differentiation pathways to enhance growth and survival. Upregulation of these genes might indicate that GBM leverages these mechanisms for increased aggressiveness and treatment resistance \[20].

**5) Proximal/distal pattern formation involved in nephron development (GO:0072047)**

Proximal-distal patterning is crucial for nephron development and can be observed from the earliest stages of nephron formation. In the renal vesicle, gene expression is already organized along the future proximal-distal axis, highlighting the importance of this regulatory mechanism. Research indicates that intrinsic signals, particularly components of the Notch pathway, are central to regulating this patterning. However, additional cell signaling mechanisms may also influence this developmental process, underscoring the complexity of nephron morphogenesis \[25].

**Conclusion**:

Further investigation about these significantly upregulated genes would enhance the understanding of glioblastoma pathogenicity, which can lead to new biomarkers discovery and development of new therapeutic strategies.

***


# **References**

1. Johnson, K.A., Krishnan, A. Robust normalization and transformation techniques for constructing gene coexpression networks from RNA-seq data. Genome Biol 23, 1 (2022). <https://doi.org/10.1186/s13059-021-02568-9>

2. <https://bioinformatics-core-shared-training.github.io/RNAseq_November_2020_remote/html/02_Preprocessing_Data.html#raw-counts>

3. Booeshaghi, A. S., & Pachter, L. (2021). Normalization of single-cell RNA-seq counts by log(x + 1) or log(1 + x). Bioinformatics, 37(15), 2223-2224. <https://doi.org/10.1093/bioinformatics/btab085>

4. Bioinformagician. (2022, April 13). 3 ways to convert Ensembl IDs to gene symbols | Bioinformatics 101 \[Video]. YouTube. <https://www.youtube.com/watch?v=cWe359VnfaY>

5. Zhao, S., Guo, Y., Sheng, Q., & Shyr, Y. (2014). Advanced Heat Map and Clustering Analysis Using Heatmap3. BioMed Research International, 2014. <https://doi.org/10.1155/2014/986048>

6. Comprehensive R Archive Network (CRAN). (2024, February 2). Various R Programming Tools for Plotting Data \[R package gplots version 3.1.3.1]. <https://cran.r-project.org/web/packages/gplots/index.html>

7. Bonnin, S. (2020b, March 9). 18.1 heatmap.2 function from gplots package | Introduction to R. <https://biocorecrg.github.io/CRG_RIntroduction/heatmap-2-function-from-gplots-package>

8. Differential gene expression. (n.d.). <https://biocorecrg.github.io/CRG_Bioinformatics_for_Biologists/differential_gene_expression.html#:~:text=The%20Fold%20change%20indicates%20whether,Type%20compared%20to%20Knock%20Out>

9. Peng, R. D. (2020, May 1). 10 Plotting and Color in R | Exploratory Data Analysis with R. <https://bookdown.org/rdpeng/exdata/plotting-and-color-in-r.html>

10. Holtz, Y. (n.d.). R Color Brewer’s palettes. <https://r-graph-gallery.com/38-rcolorbrewers-palettes.html>

11. Biostatsquid. (2023, April 12). How to interpret a heatmap for differential gene expression analysis - simply explained! \[Video]. YouTube. <https://www.youtube.com/watch?v=Bfx9R5mL2NY>

12. Biostatsquid, & Biostatsquid. (2024, August 25). Heatmaps for gene expression analysis – simple explanation with an example - biostatsquid.com. biostatsquid.com - Easy computational Biology and biostatistics. <https://biostatsquid.com/heatmaps-simply-explained/>

13. McDermaid, A., Monier, B., Zhao, J., Liu, B., & Ma, Q. (2019). Interpretation of differential gene expression results of RNA-seq data: Review and integration. Briefings in Bioinformatics, 20(6), 2044-2054. <https://doi.org/10.1093/bib/bby067>

14. Data Analysis. (n.d.). <https://www.bioconductor.org/help/course-materials/2015/Uruguay2015/day5-data_analysis.html>

15. Biostatsquid. (2022, November 11). Volcano plots with ggplot2 for differential gene expression| Beginner-friendly R \[Video]. YouTube. <https://www.youtube.com/watch?v=sIRnaKo1aKE>

16. Shi, Y., Wang, M., Shi, W., Lee, J. H., Kang, H., & Jiang, H. (2019). Accurate and efficient estimation of small P-values with the cross-entropy method: applications in genomic data analysis. Bioinformatics (Oxford, England), 35(14), 2441–2448. <https://doi.org/10.1093/bioinformatics/bty1005>

17. H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016.

18. Slowikowski, K. (2024, September 7). Getting started with ggrepel. <https://cran.r-project.org/web/packages/ggrepel/vignettes/ggrepel.html>

19. Curry, R. N., & Glasgow, S. M. (2021). The Role of Neurodevelopmental Pathways in Brain Tumors. Frontiers in Cell and Developmental Biology, 9, 659055. <https://doi.org/10.3389/fcell.2021.659055>

20. Germano, I., Swiss, V., & Casaccia, P. (2010). Primary brain tumors, neural stem cell, and brain tumor cancer cells Neuropharmacology, 58(6), 903–910. <https://doi.org/10.1016/j.neuropharm.2009.12.019>

21. Li, X.-L., Xie, Y., Chen, Y.-L., Zhang, Z.-M., Tao, Y.-F., Li, G., Wu, D., Wang, H.-R., Zhuo, R., Pan, J.-J., Yu, J.-J., Jia, S.-Q., Zhang, Z., Feng, C.-X., Wang, J.-W., Fang, F., Qian, G.-H., Lu, J., Hu, S.-Y., … Pan, J. (2023). The RNA polymerase II subunit B (RPB2) functions as a growth regulator in human glioblastoma. Biochemical and Biophysical Research Communications, 674, 170–182. <https://doi.org/https://doi.org/10.1016/j.bbrc.2023.06.088>

22. Majc, B., Sever, T., Zarić, M., Breznik, B., Turk, B., & Lah, T. T. (2020). Epithelial-to-mesenchymal transition as the driver of changing carcinoma and glioblastoma microenvironment. Biochimica et Biophysica Acta (BBA) - Molecular Cell Research, 1867(10), 118782. <https://doi.org/https://doi.org/10.1016/j.bbamcr.2020.118782>

23. Wu, J., Jiang, J., Chen, B., Wang, K., Tang, Y., & Liang, X. (2021). Plasticity of cancer cell invasion: Patterns and mechanisms. Translational Oncology, 14(1), 100899. <https://doi.org/https://doi.org/10.1016/j.tranon.2020.100899>

25) Thomas Carroll, Callie S. Kwartler, Chapter 12 - Developmental Roles of the Stroma, Editor(s): Melissa H. Little, Kidney Development, Disease, Repair and Regeneration, Academic Press, 2016, Pages 133-145, ISBN 9780128001028, <https://doi.org/10.1016/B978-0-12-800102-8.00012-6>. (<https://www.sciencedirect.com/science/article/pii/B9780128001028000126>)

\


<!--EndFragment-->
