# Cheminformatics for Drug Discovery

A practical Jupyter notebook tutorial covering foundational cheminformatics 
workflows for early-stage drug discovery — no machine learning required.

## Authors
Jane Anebi & Festus Ogungbemiro — May 2026

## Topics Covered
- Molecular representation (SMILES, InChI)
- Physicochemical descriptors (MW, cLogP, TPSA, Fsp3 …)
- Lipinski Ro5, Veber, and lead-likeness filters
- Tanimoto similarity & chemical space (PCA)
- Bemis-Murcko scaffold analysis
- PAINS filtering
- MCS detection (EGFR inhibitors)
- 2D structure grids & 3D visualization

## Requirements
```bash
conda install -c conda-forge rdkit -y
pip install pandas matplotlib seaborn py3Dmol scikit-learn ipywidgets
```

## Quick Start
```bash
git clone https://github.com/festusoladayoonline-debug
/cheminformatics-drug-discovery
cd cheminformatics-drug-discovery
jupyter notebook cheminformatics_drug_discovery.ipynb
```

## Citation
If you use this tutorial, please cite:
> Anebi J. & Ogungbemiro F. (2026). Cheminformatics for Drug Discovery.
> [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20233636.svg)](https://doi.org/10.5281/zenodo.20233636)

## References
1. Lipinski et al. (1997). Adv. Drug Deliv. Rev., 23, 3–25
2. Veber et al. (2002). J. Med. Chem., 45, 2615–2623
3. Bemis & Murcko (1996). J. Med. Chem., 39, 2887–2893
4. Baell & Holloway (2010). J. Med. Chem., 53, 2719–2740
5. Landrum G. et al. RDKit. https://www.rdkit.org

## License
MIT License — free to use, adapt, and share with attribution.
