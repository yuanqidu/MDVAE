# MDVAE

# Dependencies
rdkit, tensorflow

# Training MDVAE

To train and generate molecules:
python MDVAE.py --dataset qm9|zinc

# Evaluating MDVAE

To evaluate the generated molecules:
python evaluate.py --dataset qm9|zinc
