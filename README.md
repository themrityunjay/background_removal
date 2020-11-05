# Image Instance Segmentation and remove background of an Image
### Ideal for single object(person) background

This is an implementation of [Mask R-CNN](https://arxiv.org/abs/1703.06870) on Python 3, Keras, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.
### Image with background

![Image](assets/1c.jpg)

### Image with removed-background

![Image](assets/1c.png)




# Getting Started
* [main_background_remove.ipynb](samples/main_background_remove.ipynb) Is the easiest way to start. It shows an example of using a model pre-trained on MS COCO to segment objects in your own images.
It includes code to run object detection and instance segmentation on arbitrary images.
