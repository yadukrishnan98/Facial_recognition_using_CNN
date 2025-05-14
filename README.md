## Image Classification task using CNN

This project repository consists of a notebook file that was used in my Masters dissertation titled 'Image Classification using CNN'. The dissertation explores the use of CNN in image classification tasks, and a brief overview of the core components of CNNs, including layers used in the architecture of a CNN, various regularization techniques and functions, in order to optimise model performance. 

A custom CNN model was built and trained on the very popular MNIST dataset and further analysed using various evaluation metrics to monitor benchmark performance of CNN models. A Faces dataset imported from Kaggle, was also used which comprises of over 19,000 images of various celebrities. These images can be classified into one of 3 classes - Young, Middle and Old, representing young aged, middle aged and old aged respectively. In this case, transfer learning was implemented using popular pre-trained models such as ResNet50V2, VGG16 and Xception. These models were then analysed and evaluated using performance metrics for comparison.



# Environment Setup

The notebook file in the repository was written using Python 3.11.9, as versions of Python above 3.12 are not compatible with the Tensorflow library, which is implemented in this project. Ensure a suitable python version is installed on your machine.

Ensure jupyter notebook is installed. If not installed, run the below line on your command line.

`pip install jupyter`

It is preferrable to create a virtual environment for your project so as to manage dependencies effectively. To create a virtual environment, navigate to your project folder and run the below line in your command line.

`python -m venv *environment name*`

Once created, activate the virtual environment using

`.\*environment name*\Scripts\activate`

To run your jupyter notebook, you will need a kernel to execute the code and fetch results. In order to do so, it is required to install the ipykernel package using

`pip install ipykernel`

This installs the necessary packages needed to create a kernel for your notebook environment. Now, you can create your kernel using the command.

`python -m ipykernel install --user --name='kernel name'`

Once this is done, you can start jupyter with the following command on command line.

`jupyter notebook`

In doing so, your local machine acting as a server serves a web page on your browser, on which you can also access your notebook. You can open the notebook file using your browser or continue using your preferred text editor. Since VS Code has been used in this project, you can select your jupyter kernel by opening the VS Code search bar: Ctrl+shift+p (on windows). Type in and choose: "Notebook: Select Notebook Kernel" and choose kernel that was created earlier. 

Other dependencies and packages can be found in the requirements.txt file in this repository and can be run using the command.

`pip install -r requirements.txt`

You are now ready to run and execute the notebook file.

