# MDVAE
Code for [Interpretable molecular graph generation via monotonic constraints](https://epubs.siam.org/doi/epdf/10.1137/1.9781611977172.9) (SDM 2022). 

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
