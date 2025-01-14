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
