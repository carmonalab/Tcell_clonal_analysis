# Reproducible code for reference-based T cell clonal analysis 

A computational workflow to perform T cell states and clonal analysis from scRNA-seq data based on the R packages Seurat, ProjecTILs and scRepertoire. Given a scRNA-seq T cell dataset with TCR sequence information, cell states are automatically annotated by reference projection using the ProjecTILs method. TCR information is used to track individual clonotypes, assess their clonal expansion, proliferation rates, bias towards specific differentiation states, and the clonal overlap between T cell subtypes. 

## How to run the workflow

Clone the repository to your local machine
```
git clone git@github.com:carmonalab/Tcell_clonal_analysis.git
```

Navigate to the new directory and open the .Rproj file in Rstudio. Load one of the notebooks to reproduce the analyses.

**NOTE:** we use [renv](https://rstudio.github.io/renv/articles/renv.html) to generate reproducible R environments. The `renv::restore()` call in the preamble of the scripts ensures that all packages with the correct version are installed and loaded. 

