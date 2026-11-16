# Phylogenetic analysis workflow

## 1. Sequence preparation (CLC Genomics Workbench)
- Raw sequence files checked and trimmed
- Forward and reverse reads assembled into a consensus sequence
- Consensus sequence exported in FASTA format

## 2. Alignment (MAFFT)
- Method:  auto 
- Output: aligned FASTA file
- Command: mafft --auto input.fasta > aligned.fasta
  
## 3. Tree construction (MEGA-12)
- Method:  Maximum Likelihood
- Substitution model: Tamura-Nei model with gamma distribution (TN93+G)
- Bootstrap replicates:  1000

## 4. Tree visualization (iTOL)
- Tree file exported from MEGA-12 in Newick format
- Annotated and exported as an image in iTOL

## Notes
- Sequences from this study: PX254913.1, PX254914.1
