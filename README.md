# DeepLearning_Project2

Based on the traditional ViT model, a convolutional neural network (CNN) is used to extract features from the original data, and then input the filtered patches into ViT for training. 

It is expected that the robustness of the mixed model will be enhanced by the accuracy of CNN on small datasets and the accuracy of the ViT model on large datasets. We tested on the CIFIR-10 dataset and got some results, but the test accuracy of the model is not ideal at present, and we will continue to revise and improve it in the follow-up work.

The current coding part shows in `vit.ipynb` file.
