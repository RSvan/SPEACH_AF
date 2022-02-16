# SPEACH_AF

Sampling Protein Ensembles and Conformational Heterogeneity with Alphafold2


## Files
SPEACH_AF_scan (jupyter notebook): will generate modified MSA files (alanine mutagenesis) based on an initial MSA and PDB

batch.py: modified batch.py (original from Colabfold branched on 12/2022). <br>
  use in either two ways 
1. install ColabFold from https://github.com/sokrypton/ColabFold as described and replace the installed batch.py <br>
   (located in anaconda3/lib/python3.X/site-packages/colabfold or miniconda3/lib/python3.X/site-packages/colabfold) <br>
2. install a branched ColabFold (branched on 12/2022) which has the modified file
```
pip install "colabfold[alphafold] @ git+https://github.com/RSvan/ColabFold"
```

## References
Preprint of similar methodology
- Stein, RA and Mchaourab, HS. Modeling Alternate Conformations with Alphafold2 via Modification of the Multiple Sequence Alignment. <br>
  bioRxiv (2021) doi: [10.1101/2021.11.29.470469](https://www.biorxiv.org/content/10.1101/2021.11.29.470469v1)

If using ColabFold and Alphafold do not forget to cite the appropriate references
- Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S and Steinegger M. ColabFold - Making protein folding accessible to all. <br>
  bioRxiv (2021) doi: [10.1101/2021.08.15.456425](https://www.biorxiv.org/content/10.1101/2021.08.15.456425v2)
- Jumper et al. "Highly accurate protein structure prediction with AlphaFold." <br>
  Nature (2021) doi: [10.1038/s41586-021-03819-2](https://doi.org/10.1038/s41586-021-03819-2)
