# Image-Preprocessing-Model-with-Canny-filter-for-American-Sign-Language-Classification
The model is a convolution neural network with the main service being the preprocessing phase. The baseline is a sequential model of one convolutional layer followed by one max pooling layer. Optinally, it is possible to apply one batch normalization to increase the training speed and flatten those layers into a single vector. The most important part underlies the preprocessing step where a sequence of filters are applied to validate the hypothesis if the edge detection results in a more superior performance in the American Sign Language classification problem. 

The preprocessing step comprises of:\
      - Grayscale transformer\
      - Gaussian Blur\
      - Canny filter\
      - Dilation and Closing method

      
Ultimately, the outcome of the model did not qualify the expectation and was completely biased to one particular class(N) due to many reasons. The most feasible explantion is that the datasets have no variation in background, light condition, hand shape, and others. Thus, when being test in a wholly different dataset, the model give a poor performance with the accuracy as approximately 5%. Consequently, the future project would put more concentration on the dataset to have a more dependable validation on the model.
