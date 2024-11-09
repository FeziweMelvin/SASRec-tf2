SASRec: Self-Attentive Sequential Recommendation
TensorFlow 2.0 implementation of the following paper on recommendation for action sequences:

Wang-Cheng Kang, Julian McAuley (2018). Self-Attentive Sequential Recommendation. In Proceedings of IEEE International Conference on Data Mining (ICDM'18)

https://cseweb.ucsd.edu/~jmcauley/pdfs/icdm18.pdf

Datasets
“The Instacart Online Grocery Shopping Dataset 2017”, Accessed from https://www.instacart.com/datasets/grocery-shopping-2017 on 2019/09/16

https://www.instacart.com/datasets/grocery-shopping-2017

Instacart Shopping Dataset

Usage
Data Preparation
Download the dataset from the above URL

Place it under data/packed

python instacart_preprocess.py

Prepare the original data

study
python train.py
