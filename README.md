Image Classification task using CNN

This project repository consists of a notebook file that was used in my Masters dissertation titled 'Image Classification using CNN'. The dissertation explores the use of CNN in image classification tasks, and a brief overview of the core components of CNNs, including layers used in the architecture of a CNN, various regularization techniques and functions, in order to optimise model performance. 

A custom CNN model was built and trained on the very popular MNIST dataset and further analysed using various evaluation metrics to monitor benchmark performance of CNN models. A Faces dataset imported from Kaggle, was also used which comprises of over 19,000 images of various celebrities. These images can be classified into one of 3 classes - Young, Middle and Old, representing young aged, middle aged and old aged respectively. In this case, transfer learning was implemented using popular pre-trained models such as ResNet50V2, VGG16 and Xception. These models were then analysed and evaluated using performance metrics for comparison.



Code

The notebook file in the repository was written using Python 3.11.9, as versions of Python above 3.12 are not compatible with the Tensorflow library, which is implemented in this project. Other dependencies can be found in the requirements.txt file in this repository and can be run using the command

pip install -r requirements.txt

