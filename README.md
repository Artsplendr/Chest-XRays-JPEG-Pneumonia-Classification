#Chest XRays Pneumonia Classification

The dataset of chest X-ray images (as JPEG images) is available at the following link: https://data.mendeley.com/datasets/rscbjbr9sj/2.

The dataset is divided into train and test sets, with two classes: “Pneumonia” and “Normal”.

In this experiment, I will use pre-trained model Inception-ResNet-v2 from TF Hub (https://tfhub.dev/google/imagenet/inception_resnet_v2/classification/4) to train, and afterwards to fine-tune the model.

The model reached test accuracy 0,8477.

In the frame of the experiment, also new unseen pediatric chest X-Rays images were tested on this model with 70% accuracy as result.

The experiment is available in the Colab notebook.
