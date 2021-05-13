# Deep Learning Project Structure

How to make a Deep Learning Project Structure?

## /configs

- model configs
    + Choose the format
    + `.json`
    + `.ini`
    + `.yaml`
    + `.py`

## /data

- your datasets
    + train 
        - class 1
        - class 2
        - etc.
    + valid
        - class 1
        - class 2
        - etc.
    + test
        - class 1
        - class 2
        - etc.

## /docs

- project documents
    + install
    + how to run?
    + api structure

## /images

- save sample image
    + dataloader output image (+ transforms)
    + sample image for test
    + result

## /checkpoints

- your trained model

## /notebooks

- data processing notebook
- tutorial notebook

## /scripts

- train scripts
- test scripts
- run scripts

## /src

- `/data`
    + dataloader
    + data utils

- `/model`
    + model architecture
    + model utils

- `/visualization`
    + visualization tools

- `loss.py` and `/loss`
    + define custom loss

- `optim.py` and `/optim`
    + define custom optimizer

- `scheduler.py` and `/scheduler`
    + define custom scheduler

- `transforms.py` and `/transforms`
    + define custom data augmentation