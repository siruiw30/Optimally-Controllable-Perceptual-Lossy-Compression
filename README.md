# MNIST experiments
## Directory Tutorial
**train.py**: training dataset. \
**test.py**: testing dataset and plotting figures with different $\alpha$. \
**train_beta.py**: using for tuning $\beta$. \
**data**: MNIST, Fashion-MNIST and EMNIST are pre-loaded dataset in Pytorch.

1. Please download all the .py and .ipynb files.
2. Open the **MNIST_code.ipynb** on Google Colab.
3. The GPU is needed. Please change the runtime type to GPU first.
4. To train different dataset, please change the dataset loaded by `train_loader` in **train.py** or **train_beta.py**.
5. Remember to confirm that the file paths of generators are correct before running **test.py**.
