conda create -n mmp_env python=3.10
conda activate mmp_env
conda install -c conda-forge rdkit
python -m pip install mmpdb
pip install chembl_structure_pipeline


conda env export > environment.yml
conda list --export > requirements.txt


mmpdb help-smiles-format
