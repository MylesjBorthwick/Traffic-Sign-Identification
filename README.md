# Traffic-Sign-Identification
Machine learning project focused on multi-classification of traffic signs ussing a CNN (Convoluted Neural Network)


### Authors: Myles Borthwick, Kenneth Loughery, Dylan Hofer, Gabriel Mathias, Nusrat Zerin Zenia

#### *This repository includes the jupyter notebook with our final model as well as a report detailing the dataset, methodologies and discussion associated with this project*.


## Introduction
With the advent of deep learning technology, automotive companies have started to shift their
focus towards automated vehicles to improve road safety by eliminating operator error, the
leading cause of vehicular accidents [1]. However to enable the automated vehicles to operate
smoothly in the current landscape of transportation they must be able to follow the same traffic
rules current drivers adhere to. While there are many areas of consideration in respect to
automated vehicles, successfully detecting and recognising traffic signs can be considered a
fundamental starting point.

## Results
The CNN model described in Figure 4 was able to achieve excellent accuracy values for the test
dataset, with the highest accuracy being 97.97% (found after the final presentation was filmed,
prior it was 97.7%). Figure 5 shows the model’s accuracy for the training and validation data
over the first 70 epochs, which is increasing steadily, showing that the model is not overfitting.
To get to our final model, weeks of iterations were conducted to find the best possible score,
using different model sizes, different dropout ranges, and different regularization parameters. In
our final model, our dropout coefficient increased by 0.1 with every layer, starting at 0.2 and
finishing at 0.5 for the fully connected 348 kernel layer. Likewise, our l2 regularization
increments by 0.1 from 0.1 to 0.4 for our fully connected layer.



