# Step Molecular Dynamics using xTB (extended tight binding)

## The automated Interaction Site Screening (aISS)
1. Running this command: `xtb dock rec.xyz lig.xyz --gbsa methanol`

## Molecular dynamics 
1. Running this command: `xtb final_structures.xyz --input md.inp --omd`

## Plot energy using matplotlib and pandas 
1. Plot energy with this script: https://github.com/purnawanpp/xtb_md/blob/main/xtb_md.ipynb
