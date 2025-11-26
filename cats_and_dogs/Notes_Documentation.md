### on VGG16

https://medium.com/@qakunnath/fine-tuning-a-pre-trained-vgg16-model-for-custom-image-classification-b1fd4bf56aad

Resize: All images are resized to 224x224 pixels, the standard input size for VGG16.
Normalize: The pixel values are normalized using mean and standard deviation values specific to ImageNet, ensuring compatibility with the pre-trained model (VGG 16 ayant été entrainé sur Image Net)

https://docs.pytorch.org/vision/stable/models/generated/torchvision.models.vgg16.html
