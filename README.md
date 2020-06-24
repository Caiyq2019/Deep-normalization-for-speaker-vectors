# DNF
A Pytorch implementations of DNF for author's article ["Deep normalization for speaker vectors"](https://arxiv.org/abs/2004.04095)

The neural network structure is based on "Masked Autoregressive Flow", and the source code from [ikostrikov](https://github.com/ikostrikov/pytorch-flows/blob/master/README.md)

## Datasets
```bash
trainingset:Voxceleb 
testset: SITW, CNCeleb
```
Following this [link](https://pan.baidu.com/s/1NZXZhKbrJUk75FDD4_p6PQ) to download the dataset 
Extraction code：8xwe

## Run DNF
```bash
python train.py
```
The evaluation and scoring will be performed automatically during the training process.




