**ColabTree**
Accessed using: This simple pipeline made by the Rodrigues lab, uses the ColabFold MMSEQ2 and HHSUITE filtering of proteins for fast protein phylogeny determination. It makes an A3M file and a fasta file using MMSEQ2. It then translates this into a PHYLIP file and uses FASTME default settings for phylogeny determination. If you would like to only change an a3m file into a tree or label your a3m file, and do not need to search use our other pipeline "ATree" !Picture 1.png Input the amino acid sequence of your protein, and this software will make a tree of the conservation of the gene or genes. If analysing a gene cluster please untick 'protein modelling' so you dont crash the system.

For publication quality analysis, we recommend you upload the nwk file created by this programme to iTOL https://itol.embl.de/upload.cgi

This workbook is based greatly off the Alphafold Colabfold notebook here: https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb and published here:

Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S, Steinegger M. ColabFold: Making protein folding accessible to all. Nature Methods, 2022

It relies on FASTME:

Vincent Lefort, Richard Desper, Olivier Gascuel, FastME 2.0: A Comprehensive, Accurate, and Fast Distance-Based Phylogeny Inference Program, Molecular Biology and Evolution, Volume 32, Issue 10, October 2015, Pages 2798–2800, https://doi.org/10.1093/molbev/msv150

To cite our tool use the following citation: Graham LBC, Rodrigues C. ColabTree: MMSEQs2 to Phylogeny Generator, Zenodo, 2024 10.5281/zenodo.11636770 
