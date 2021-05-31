# MDVAE

# Dependencies
rdkit,
tensorflow,
typing,
docopt,
planarity

# Training MDVAE

To train and generate molecules:
<pre>python MDVAE.py --dataset qm9|zinc</pre>

# Evaluating MDVAE

To evaluate the generated molecules:
<pre>python evaluate.py --dataset qm9|zinc</pre>
