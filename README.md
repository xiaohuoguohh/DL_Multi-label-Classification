# DL_Multi-label-Classification

I used the RSENEXT50 as beseline model, and only train the image data to obtain the classification results. On the basis of the original model, I modified the original model and added channel attention layer before the final fully connected layer.
In the basic model, I did not use text data for training. Here I used the BI-LSTM model to train and classify the text data. Here I train the text data and image data at the same time. The image model uses the RESNEXT50 model, and the text data uses the NLP BILSTM model. In the training, the feature concatenate output after the attention layer is put into the fully connected layer, and then the classification output. Under such improvement, the effect of the model has been improved to a certain extent.

<img width="608" alt="Screen Shot 2021-06-22 at 10 33 19" src="https://user-images.githubusercontent.com/78587287/122915081-ee7dbf80-d38d-11eb-8bde-2f1ee157091c.png">
