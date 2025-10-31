---
permalink: /
title: "Statistical Innovation for Biomedical Discovery"
excerpt: "Zhao Lab"
author_profile: true
header:
  overlay_image: "{{ '/assets/img/sparseSOMNiBUS-overview.png' | relative_url }}"
  overlay_filter: 0.25
  caption: "Overview of sparseSOMNiBUS analysis pipeline (Zhao et al., *Biostatistics*, 2025)."
redirect_from: 
  - /about/
  - /about.html
---


Welcome to the **Zhao Lab** in the Department of Mathematics & Statistics at York University (Toronto, Canada).  
Our research focuses on developing *innovative statistical and computational methods* for analyzing high-dimensional biological data, with applications in **genomics, epigenomics, and precision health**.


---

## 🧭 Research Overview

We work at the interface of **statistics**, **genomics**, and **causal inference**, building models that make sense of high-dimensional, noisy, and biologically complex data.

Our current research themes include:

- **High-dimensional inference in genetic and epigenetic association**  
  Regional DNA methylation QTL mapping using penalized and smooth functional modeling.

- **Causal inference and Mendelian randomization**  
  Accounting for correlated genetic instruments and sample overlap in large-scale summary data.

- **Wearable omics and dynamic precision health**  
  Integrating wearable sensor data with genomic, proteomic, and metabolomic features for disease phenotyping.

---


## 🔬 Recent Highlight: sparseSOMNiBUS

<div style="text-align:center;">
  <img src="{{ '/assets/img/sparseSOMNiBUS-overview.png' | relative_url }}" alt="sparseSOMNiBUS overview" width="95%">
</div>


`sparseSOMNiBUS` (**Sparse Smooth Omnibus Model for Regional DNA Methylation QTL Mapping**) is our newly published method for identifying **regional mQTLs** using high-resolution bisulfite sequencing data.  
It unifies smooth functional modeling with sparse variable selection, allowing accurate estimation of SNP–CpG associations across genomic regions.

> **Reference**  
> Zhao K, Yang AY, Oualkacha K, Zeng Y, Klein K, Hudson M, Colmegna I, Bernatsky S, Greenwood CMT.  
> *A novel high-dimensional model for identifying regional DNA methylation QTLs.*  
> *Biostatistics*, Volume 26, Issue 1, 2025, kxaf032.  
> [https://doi.org/10.1093/biostatistics/kxaf032](https://doi.org/10.1093/biostatistics/kxaf032)

---

### 📈 Model Illustration

<div style="text-align:center;">
  <img src="{{ '/assets/img/sparseSOMNiBUS-path.png' | relative_url }}" alt="sparseSOMNiBUS tuning parameter path and validation deviance" width="95%">
</div>

`sparseSOMNiBUS` fits a penalized regression model balancing **smoothness** and **sparsity**.  
The tuning parameter λ is selected via cross-validation using both the *minimum mean deviance (λ_min)* and the *1-SE rule (λ_1SE)* to achieve model parsimony and interpretability.


---

## 🧑🔬 Join Us

We are always looking for motivated students and postdocs interested in:
- Statistical genetics and epigenomics  
- Causal inference and Mendelian randomization  
- High-dimensional and functional data analysis  
- Integrative modeling of multi-omics and wearable data  

**If you are excited about developing new statistical methods for biomedical discovery, feel free to reach out!**  
📧 [kaiqiong@yorku.ca](mailto:kaiqiong@yorku.ca)

---


