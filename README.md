# Neural OCR
### How to use


  - First you need to generate data, go to the datagen folder and do it

  - Then we have to extract features from our images and save them to torch/numpy (same folder)

  - Train your net. Here's a little example (works really bad) how to do this using linear based RNN (look Conditional Character-Level RNN)

  - You really should use Tensorboard cuz it's really helpful tool

### Requirements

  - PIL

  - tqdm

  - glob

  - Your ML lib (either keras or pytorch or whateveryouwant)

  - CTC lib for it (keras already has native one)

  - Tensorboard (and TendorboardX for pytorch)

### To install main dependencies use
 
>Basic requirements:

``` sh

$ pip install -r requirements.txt

```

>Pytorch:

``` sh
$ pip install -r req_pytorch.txt

```
>Keras:

``` sh
$ pip install -r req_keras.txt

```

> If you want keras gpu, run:
``` sh
$ pip install tensorflow-gpu
```
> If you are windows youser you have to install it through conda environments



# Useful links:


  - [CTC Loss (RU)](https://www.youtube.com/watch?v=SAfJ6nP2rrI )
 
 - [CTC Loss (RU) part 2](https://www.youtube.com/watch?v=eYIL4TMAeRI)

  - [Dropbox blog](https://blogs.dropbox.com/tech/2017/04/creating-a-modern-ocr-pipeline-using-computer-vision-and-deep-learning/)

  - [Hackermoon article](https://hackernoon.com/latest-deep-learning-ocr-with-keras-and-supervisely-in-15-minutes-34aecd630ed8)

  - [LSTM & GRU (RU)](https://www.youtube.com/watch?v=wYI7RZz4Rz0)


# [Igor's wise comment](https://docs.google.com/document/d/1wT8G1G47hoxx4dFnVm-25sqi5N7TX3Qy53YMdfg7fIA/edit)

