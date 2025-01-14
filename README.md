<h1 style="font-size:25px;">PFDA Project: Single-Cell Analysis Notebook</h1>

<h2 style="font-size:20px;">Overview</h2>
<p style="font-size:15px;">Single-cell analysis is a technique used to study the transcriptomic profiles of individual cells, enabling the identification of distinct cell populations, their states, and functions. This approach is crucial for exploring cellular heterogeneity, uncovering rare cell types, and understanding how cell populations differ in health and disease, including conditions like COVID-19.</p>

<p style="font-size:15px;">I decided to do this analysis as it is what I am doing at the moment for work and it is very intersting to me. This is the dataset that was used for this analysis:</p>
<p style="font-size:15px;">https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE171524</p>

<h2 style="font-size:20px;">Workflow Summary</h2>
<ul>
   <li><b>Data Preprocessing</b>: Quality control, normalization, and log transformation of gene expression data.</li>
   <li><b>Highly Variable Gene Selection</b>: Identification of genes driving biological variability.</li>
   <li><b>Dimensionality Reduction</b>: PCA for capturing major sources of variation.</li>
   <li><b>Clustering</b>: Leiden algorithm to group cells into clusters.</li>
   <li><b>Marker Gene Identification</b>: Detection of genes distinguishing clusters.</li>
   <li><b>Cell Type Proportions</b>: Comparison of cell type frequencies between conditions.</li>
</ul>

<hr>

<h2 style="font-size:20px;">Key Findings</h2>
<ul>
   <li>COVID-19 samples showed increased alveolar macrophages and decreased alveolar Type II cells, suggesting immune response and lung damage.</li>
   <li>Identified marker genes that distinguish clusters and cell types.</li>
</ul>

<h2 style="font-size:20px;">Usage</h2>
<p style="font-size:15px;">Clone this repository. Install dependencies from requirements.txt in the Project folder and run through the single-cell.ipynb notebook.</p>
<p style="font-size:15px;">This should be able to run without on just a CPU but a GPU is recomended for Harmony.</p>

<h2 style="font-size:20px;">References</h2>
<p style="font-size:15px;">You will see all of the below put to use in the notebook. Here are some handy links to reference if working through the notebook:</p>
<p style="font-size:15px;">For general help with scanpy: https://scanpy.readthedocs.io/en/stable/tutorials/basics/clustering.html</p>
<p style="font-size:15px;">For more info om harmonypy: https://github.com/slowkow/harmonypy</p>
<p style="font-size:15px;">For finding marker genes: https://www.panglaodb.se/markers.html?cell_type=%27T%20cells%27</p>
<p style="font-size:15px;">A githib with many great single-cell tutorials: https://github.com/mousepixels/sanbomics_scripts</p>
<p style="font-size:15px;">The single-cell bible: https://www.sc-best-practices.org/preamble.html</p>
<ul>
   <li><b>Scanpy:</b> Wolf, F.A., Angerer, P. & Theis, F.J. (2018). Scanpy: large-scale single-cell gene expression data analysis. Genome Biology, 19, 15. <a href="https://doi.org/10.1186/s13059-017-1382-0" target="_blank">DOI</a></li>
   <li><b>scVI-tools:</b> Gayoso, A., Lopez, R., et al. (2022). A Python library for deep probabilistic analysis of single-cell omics data. Nature Biotechnology, 40, 163–166. <a href="https://doi.org/10.1038/s41587-021-01206-w" target="_blank">DOI</a></li>
   <li><b>Harmonypy:</b> Korsunsky, I., et al. (2019). Fast, sensitive and accurate integration of single-cell data with Harmony. Nature Methods, 16, 1289–1296. <a href="https://doi.org/10.1038/s41592-019-0619-0" target="_blank">DOI</a>
</li>
   <li><b>Single-Cell Analysis:</b> Zheng, G.X.Y., et al. (2017). Massively parallel digital transcriptional profiling of single cells. Nature Communications, 8, 14049. <a href="https://doi.org/10.1038/ncomms14049" target="_blank">DOI</a></li>
   <li><b>Leiden Algorithm:</b> Traag, V.A., Waltman, L., & van Eck, N.J. (2019). From Louvain to Leiden: guaranteeing well-connected communities. Scientific Reports, 9, 5233. <a href="https://doi.org/10.1038/s41598-019-41695-z" target="_blank">DOI</a></li>
</ul>
