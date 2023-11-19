# ElementKG
This repository is the implementation of **ElementKG**, which is model proposed in paper:[**Knowledge graph-enhanced molecular contrastive learning with functional prompt**](https://www.nature.com/articles/s42256-023-00654-0)

***

# Requirements
To run our code, please install dependency packages.
```
python      3.8
rdkit       2018.09.3
numpy       1.20.3
gensim      4.2.0
nltk        3.4.5
rdflib      7.0.0
```
# Tutorial
```python
from ElementKG import Molecular

# e.g
# smiles type can str or list
smiles = "[C@@H]1([C@@H]([C@@H]([C@H]([C@@H]([C@@H]1Cl)Cl)Cl)Cl)Cl)Cl" 

mol = Molecular(smiles)

# The features in mol.mol
print(mol.mol)

```


# References
Please cite the paper if you use this code in your work:
```bibtex
@article{fang2023knowledge,
  title={Knowledge graph-enhanced molecular contrastive learning with functional prompt},
  author={Fang, Yin and Zhang, Qiang and Zhang, Ningyu and Chen, Zhuo and Zhuang, Xiang and Shao, Xin and Fan, Xiaohui and Chen, Huajun},
  journal={Nature Machine Intelligence},
  pages={1--12},
  year={2023},
  publisher={Nature Publishing Group UK London}
}
```