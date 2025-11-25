# RAE

This is source code for, 
@inproceedings{RAE,
author = {Zhao, Sibo and Bewong, Michael and Kwashie, Selasi and Hu, Junwei and Feng, Zaiwen},
title = {RAE: A Rule-Driven Approach for Attribute Embedding in Property Graph Recommendation},
year = {2025},
url = {https://doi.org/10.1007/978-3-032-06106-5_2},
keywords = {Recommendation Systems, Property Graphs, Rule Mining, Attribute Embedding, Graph Convolutional Network},
location = {Porto, Portugal}
}

## Mine Rules
For rule mining, check the following repository:
[RefExternalKG](https://github.com/MuyangLiu/RefExternalKG)

## Generate Embedding
To generate the embedding, run the following command:

```bash
python rae.py --d 128 --full 0 --t 5 --data <dataset_name> --kappa 1024
```

## Train
To train the model, use the following command:
```bash
python Rae_gcn.py --dataset <dataset_name>
```
