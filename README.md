# AI-Healthcare-Imaging

I have learnt and used U-Net architecture for the Liver segmentation model.
WHat is U-Net??
U-Net is a deep learning algorithm that is used for semantic segmentation.

What is Segmentation?
In segmentation we select the area from the image belonging to the given class by choosing all pixels that lie in the class .
Other than segmentation  we can do Image Classification and Image Detection.
In classification we just check if given image is present or not.
In Detection ,we guess the image what it is of.

There are 2 types of segmantation:1.Instance 2.Semantic
Semantic Segmentaion:General class for all the instance is identified.
Instace Segmentation:All the seperate classes are identified.


U-Net consists of of two sections -Encoder and Decoder.
It is called U-Net as the shape of the architecture resembles english alphabet -U.

It is easiest deep learning architecture as it consists of only convolutional layers followed by max pooling.
Max pooling refers to selecting the maximum value within a window of a samlpe and sliding the window  to reduce dimensions of the sample and easier training.

Software Used:Python,VsCode,3D Slicer(visualisatio),MONAI
DataSet:Kaggle

Here,we have cropped the images into smaller squares and then used them fpr training and testing.
