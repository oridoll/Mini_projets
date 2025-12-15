### on VGG16

https://medium.com/@qakunnath/fine-tuning-a-pre-trained-vgg16-model-for-custom-image-classification-b1fd4bf56aad

Resize: All images are resized to 224x224 pixels, the standard input size for VGG16.
Normalize: The pixel values are normalized using mean and standard deviation values specific to ImageNet, ensuring compatibility with the pre-trained model (VGG 16 ayant été entrainé sur Image Net)

https://docs.pytorch.org/vision/stable/models/generated/torchvision.models.vgg16.html

Fine tunning RestNet18:
https://docs.pytorch.org/vision/main/models/generated/torchvision.models.resnet18.html
Resize and Crop: All images are resized to 224x224 pixels
Normalize: rescaled to [0.0, 1.0] and then normalized using mean=[0.485, 0.456, 0.406] and std=[0.229, 0.224, 0.225].

Fine tunning torch tutorial
https://docs.pytorch.org/tutorials/intermediate/torchvision_tutorial.html
https://docs.pytorch.org/tutorials/beginner/transfer_learning_tutorial.html