# Molecular Docking Workflow

Demostration of molecular docking pipeline: protein preparation, ligand preparation, docking with AutoDock Vina.

## Workflow

1. **Protein Preparation**  
   - Prepare protein structures from the [Protein Data Bank (PDB)](https://www.rcsb.org/).  
   - Detect binding pockets using [fpocket](https://github.com/Discngine/fpocket).

2. **Ligand Preparation**  
   - Convert ligand files to PDBQT format using [Open Babel](https://openbabel.org/wiki/Main_Page).

3. **Docking**  
   - Perform docking with [AutoDock Vina](http://vina.scripps.edu/) using defined binding site coordinates.

4. **Visualization**  
   - View protein-ligand complexes interactively with [py3Dmol](https://pypi.org/project/py3Dmol/).

## Requirements

- **Software**: fpocket, Open Babel, AutoDock Vina, MGLTools  
- **Python Libraries**: NumPy, py3Dmol  
