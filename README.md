# IB3A
Source code for the paper "Invisible Black-Box Backdoor Attack against Deep Cross-Modal Hashing Retrieval".

## Requirements
* python == 3.7.10
* pytorch == 1.4.0
* torchvision == 0.2.1
* numpy == 1.19.2
* h5py == 3.4.0
* scipy == 1.7.1

## Datasets
We use three cross-modal datasets for experiments. Since MS-COCO do not have common text features, we use the pre-trained BERT model to extract 1024-dimension text features. All datasets are available by the following link:

* FLICKR-25K: https://pan.baidu.com/s/1Ie9PDqC9mAmBdxqX0KJ0ng <br> Password: yjkd
* MS-COCO: https://pan.baidu.com/s/1ocZTVx1GFFdceoSYbIWkbQ <br> Password: 2a6l
* NUS-WIDE: https://pan.baidu.com/s/1Yvqt4Bdjsq1gPaJn2IqIEw <br> Password: doi1

## Knockoffs
We provide an knockoff of 32-bit DCMH on the FLICKR-25K dataset. The knockoff can be obtained by the following link:

* The Trained 32-bit DCMH on FLICKR-25K: https://pan.baidu.com/s/1JcQd_SepWVz-Js4X8yqjPQ <br> Password: b6sd

## Victim models
We carry out backdoor attack for three cross-modal hashing methods, including DCMH, CPAH, DADH. All attacked hashing models can be obtained by the following link:

* Deep Cross-Modal Hashing (DCMH): https://github.com/WendellGul/DCMH
* Consistency-Preserving Adversarial Hashing (CPAH): https://github.com/comrados/cpah
* Deep Adversarial Discrete Hashing (DADH): https://github.com/Zjut-MultimediaPlus/DADH

## Citation
T. Wang, F. Li, L. Zhu, J. Li, Z. Zhang, H. T. Shen, Invisible Black-Box Backdoor Attack against Deep Cross-Modal Hashing Retrieval, ACM Transactions on Information Systems (TOIS), xx(x): x–xx, 2024.
