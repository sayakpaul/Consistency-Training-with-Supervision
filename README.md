# Consistency-Training-with-Supervision
Contains experimentation notebooks for my Keras Example [Consistency Training with Supervision](https://keras.io/examples/vision/consistency_training/). This example also provides a template for performing semi-supervised / weakly supervised learning. 

Promising results on [CIFAR-10-C](https://github.com/hendrycks/robustness) with the process shown in the example:

<p align="center">
<img src=https://i.ibb.co/HBJkM9R/image.png></img>
</p>

**More things one can incorporate**:

* Incorporate more data during training the student. 
* Filter high confidence predictions from teacher during training the student. 
* Use recipes like [Stochastic Depth](https://arxiv.org/abs/1603.09382) for training the teacher. The current example uses [Stochastic Weight Averaging](https://arxiv.org/abs/1803.05407) to induce geometric ensembling. 

Full-scale experiments are available [here](https://git.io/JO55v).

## Acknowledgements

* [ML-GDE program](https://developers.google.com/programs/experts/) for providing GCP credits. 
