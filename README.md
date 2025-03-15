# RAE

## Mine Rules
For rule mining, check the following repository:
[RefExternalKG](https://github.com/MuyangLiu/RefExternalKG)

## Generate Embedding
To generate the embedding, run the following command:

```bash
python rae.py --d 128 --full 0 --t 5 --data <dataset_name> --kappa 1024

## Train
To train the model, use the following command:
```bash
python Rae_gcn.py --dataset <dataset_name>
