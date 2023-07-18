# Neural Networks Project: Sequencer: Deep LSTM for Image Classification

## Requirements
- pytorch_lightning
- scikit_learn
- timm
- torchmetrics

Please use pip in order to install the required packages:
```
pip install -r requirements.txt
```

## Dataset
CIFAR10 is automatically downloaded in the code, if you want to use it, please make sure to call SequencerParams with dataset set to "cifar10".

For tiny-imagenet-200, please make sure to call SequencerParams with dataset set to "tiny-imagenet-200".

You can download the dataset with the following command:
```
wget http://cs231n.stanford.edu/tiny-imagenet-200.zip
```
You then need to unzip the archive in the working directory (./tiny-imagenet-200), the structure is the following:
```
- tiny-imagenet-2001/
    ─ train/
        - ...
    ─ val/
        - ...
    ─ test/
        - ...
    ─ wnids.txt
    ─ words.txt
```
