# PromptSE

# Data
##  The labeled drug-side effect dataset
data/drug_se_matrix.txt: The adjacency matrix $A$ with $a_{ij}=y_{ij}$, the label of $(d_i, s_j)$
## Train-test split
data/train.csv, data/test.csv, data/valid.csv: the indices of train/test/valid set
## Side effect features
data/LLM3.xlsx: LLM-derived representations of side effects
data/side_effect_vectors.xlsx: word2vec-derived representations of side effects
## drug features
afp_torxcast.npy, drugs.fpt, mols_vec.pkl, mpnn_toxcast.npy, nf_toxcast.npy, weave_toxcast.npy from https://github.com/yuliyi/MSDSE/tree/main/data

# Requirement
Python version: 3.11
PyTorch version: 2.2.2

# Code
Run train_MLDSP for model PromptSE and run train_MLDSPP for model PromptSE+.
