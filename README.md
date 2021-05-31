# MDVAE

# Dependencies
rdkit, tensorflow

# Training MDVAE

To train and generate molecules:
<pre>python MDVAE.py --dataset qm9|zinc</pre>

# Evaluating MDVAE

To evaluate the generated molecules:
python evaluate.py --dataset qm9|zinc
