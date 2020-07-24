# Prototypical Networks

ProtoNets learns a metric space for solving few-shot classification by computing distances between the query image and a prototype representation of the class.

This repository is part of first of a three-part webinar series on Meta Learning.
1. [Metric-based Meta Learning](https://www.meetup.com/Disrupt-4-0/events/271470964/) (this)
2. [Model-based Meta Learning](https://www.meetup.com/Disrupt-4-0/events/271778989/)
3. [Optimization-based Meta Learning](https://www.meetup.com/Disrupt-4-0/events/271778940/)

## Requirements

* PyTorch
* Numpy
* Scipy
* OpenCV
* Matplotlib
* Tqdm

## Usage

1. Download the [train](https://github.com/brendenlake/omniglot/blob/master/python/images_background.zip) and [evaluation](https://github.com/brendenlake/omniglot/blob/master/python/images_evaluation.zip) datasets.
2. Unzip the downloaded zip files in a folder called `omniglot/`.
3. Run the code cells in [ProtoNets-Omniglot.ipynb](ProtoNets-Omniglot.ipynb).
4. Alternatively, you can run this repository in colab <a href="https://colab.research.google.com/drive/1We4qwJBBA8BwLuOIQZKLLU4MzskWDHUH?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Credits

* [Prototypical Networks paper](http://papers.nips.cc/paper/6996-prototypical-networks-for-few-shot-learning.pdf)
* Author's Implementation https://github.com/jakesnell/prototypical-networks
