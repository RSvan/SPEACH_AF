# SPEACH_AF

Sampling Protein Ensembles and Conformational Heterogeneity with Alphafold2


## Files
SPEACH_AF_scan (jupyter notebook): will generate modified MSA files (alanine mutagenesis) based on an initial MSA and PDB
  requires: Bio, numpy, copy

To run multiple copies use the following command (this replaces the modified batch.py file): <br>
  Colabfold_batch input output --num-seeds X<br>


## Data Directory
Data files associated with SPEACH_AF paper

## References
Paper
- Stein, SPEACH_AF: Sampling protein ensembles and conformational heterogeneity with Alphafold2. <br>
  PLoS Comput Biol (2022) 18(8), e1010483 doi: [10.1371/journal.pcbi.1010483](https://doi.org/10.1371/journal.pcbi.1010483)

If using ColabFold and Alphafold do not forget to cite these references and any associated references from using ColabFold
- Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S and Steinegger M. ColabFold - Making protein folding accessible to all. <br>
  Nat Methods (2022) 19(6), 679-682. doi: [10.1038/s41592-022-01488-1](https://doi.org/10.1038/s41592-022-01488-1)
- Jumper et al. "Highly accurate protein structure prediction with AlphaFold." <br>
  Nature (2021) 596, 583–589. doi: [10.1038/s41586-021-03819-2](https://doi.org/10.1038/s41586-021-03819-2)
