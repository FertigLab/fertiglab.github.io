---
title: <center>Research Areas</center>
---
<p>
  <div><center>{% include button.html text="Google Scholar" link="https://scholar.google.com/citations?user=nfCAUr8AAAAJ&hl=en&oi=ao" %} {% include button.html text="PubMed" link="https://pubmed.ncbi.nlm.nih.gov/?term=Fertig+EJ&cauthor_id=24233779" %}</center></div>
</p>

### Defining cellular phenotypes with molecular patterns that transfer across single-cell multi-omics datasets

Biological interpretation of single-cell multi-omics datasets requires distilling measurements of thousands of genes and millions of cells into a lower dimensional set of molecular programs underlying cellular phenotypes and function. Our Bayesian non-negative matrix factorization model <a href="https://www.bioconductor.org/packages/release/bioc/html/CoGAPS.html" target="_blank">Coordinated Gene Activity in Pattern Sets (CoGAPS)</a> provides the foundational tool to define these molecular patterns. We pioneered a transfer learning method, <a href="https://www.bioconductor.org/packages/release/bioc/html/projectR.html" target="_blank">projectR</a>, to map molecular patterns underlying cellular phenotypes and fate decisions between datasets. This approach empowers transfer of labels between datasets for automated annotation of cells, inference of regulatory programs from multi-omics integration, and in silico validation of cell regulatory programs. Our lab has developed <a href="https://pubmed.ncbi.nlm.nih.gov/30143323/" target="_blank">standardized notation</a> and <a href="https://doi.org/10.1101/2022.07.09.499398" target="_blank">pipelines</a> to empower biological interpretation of matrix factorization analyses for the bioinformatics community. Applied work to translational cancer biology has demonstrated that transfer learning empowers bi-directional bench to bedside research by quantitatively interrelating data of therapeutic response and carcinogenesis in biological models to processes in human biospecimens. 

### Accounting for inter-tumor heterogeneity in genomics

Genomic and epigenetic landscapes of tumors have higher variability than normal samples, increasing with in tumors worsening prognosis. Statistical analyses that compare the variability of the genomic measurements in tumor samples relative to normal for genes can prioritize molecular alterations in individual tumors. <a href="https://www.bioconductor.org/packages/release/bioc/html/GSReg.html" target="_blank">Expression Variation Analysis (EVA)</a> quantifies differential variability analysis of <a href="https://dx.doi.org/10.4137%2FCIN.S14066" target="_blank">pathways</a> and <a href="https://doi.org/10.1101/091637" target="_blank">splice variants</a>.

### Integrated genomics analysis for cancer

High-throughput genomics data enables unprecedented inference of the molecular drivers and biomarkers that distinguish <a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0078127" target="_blank">cancer subtypes</a> and <a href="https://doi.org/10.18632/oncotarget.12075" target="_blank">therapeutic response</a>. Analysis across diverse omics platforms is essential to find genetic and epigenetic drivers of cancer phenotypes. Research has focused on head and neck squamous cell carcinoma genomics, with additional pan cancer analyses of high-throughput data spanning primary tumors, model organisms, and cell lines.

### Algorithms to standardize high throughput data

Robust data preprocessing techniques are essential to providing high throughput data of sufficient quality for subsequent analyses. Often, these algorithms remove inter-sample variability making pattern detection impossible. The <a href="https://www.bioconductor.org/packages/release/bioc/html/sva.html" target="_blank">permuted surrogate variable analysis (pSVA) batch correction algorithm</a> and the <a href="http://bioconductor.org/packages/release/bioc/html/minfi.html" target="_blank">FunNorm preprocessing algorithm</a> remove technical artifacts from high throughput data while preserving signal for pattern detection.

### Mathematical models of cellular signaling networks

In addition to molecular data, mathematical models can predict the state of signaling pathways based upon their network structure. <a href="https://dx.doi.org/10.3389%2Ffgene.2011.00077" target="_blank">Stochastic models</a> are essential to capture the partially penetrant phenotypes during fate decisions in development. <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3795755/" target="_blank">Network models of coupled oscillators and switches</a> also demonstrate that dynamics must be inferred from their context in the broader network instead of from their structure in isolated motifs.

### Numerical weather prediction

In weather forecasting, data assimilation schemes that regularly integrate mathematical models and measurements of a dynamical system improves predictions of future states. Algorithms to incorporating indirect satellite observations into a flow-dependent data assimilation scheme, the local ensemble transform Kalman filter (LETKF) further improve forecasting accuracy.

<!-- <div><center>{% include button.html text="Publications" link="https://fertiglab.github.io/publications/" %}</center></div>
<be> -->
