# CS690U-DGEB-project
Clustering Algorithms on Foundation Model Embeddings vs. One-Hot Encoding for Biological Sequences

------------------------------------------------------------------------

Project Structure

```
CS690U-DGEB-PROJECT/
├── .venv/
├── Experiments/
│   ├── ecoli_rna/                # all experiments related to E. coli dataset
│   └── mopb/                     # all experiments related to MopB dataset
├── Preprocessing/
│   └── Encoded_Data/             # folder storing all the encoded data
│   └── Encoding.ipynb            # encoding scripts
│   └── representation.ipynb      # scripts for UMAP plots
├── Visualization/                # scripts for result plots and all the generated plot
├── requirements.txt
└── .gitignore
```
------------------------------------------------------------------------

Setup

1. Clone the repository

```
git clone https://github.com/Teerat-CH/CS690U-DGEB-project.git
```

2. Create virtual environment

```
python -m venv .venv
```

3. Activate environment

```
source .venv/bin/activate
```

4. Install dependencies

```
pip install -r requirements.txt
```

5. run encoding.ipynb to generate the encoded data file

------------------------------------------------------------------------

Acknowledgements

This project uses and builds upon the work presented in:

West-Roberts, J., Kravitz, J., Jha, N., Cornman, A., & Hwang, Y. (2024).  
*Diverse Genomic Embedding Benchmark for functional evaluation across the tree of life*.  
Cold Spring Harbor Laboratory. https://doi.org/10.1101/2024.07.10.602933

<details>
<summary>BibTeX</summary>

```bibtex
@article{WestRoberts2024,
  title = {Diverse Genomic Embedding Benchmark for functional evaluation across the tree of life},
  doi = {10.1101/2024.07.10.602933},
  author = {West-Roberts, Jacob and Kravitz, Joshua and Jha, Nishant and Cornman, Andre and Hwang, Yunha},
  year = {2024}
}
