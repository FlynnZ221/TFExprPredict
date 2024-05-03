# Group 11 project

## Database
scRNA-seq data: [GSE146137](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE146137)

TFs downloaded form [tfcheckpoint](https://www.tfcheckpoint.org/)


## Instruction

How to run:
1. Use choose_seed_and_k.ipynb to choose a appropriate seed and k before clustering
2. Run through baseline.ipynb for clustering results
3. Regression(OLS, Ridge, LASSO, Elastic net are integrated in regression.ipynb)
4. Mutated gene are identified from sig_gene_selection.ipynb
4. database_preprocess.ipynb is used to preprocess mutated genes and bladder cancer genes (from literature serach)