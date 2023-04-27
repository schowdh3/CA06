# CA06

#About the Notebook
The notebook is written in Python to define, train, and evaluate a neural network on the MNIST dataset. Data has been optained using the following link https://github.com/ArinB/MSBA-CA-Data/raw/main/CA06/Mall_Customers.csv

#Required Packages
The notebook requires the following libraries to be installed:

Seaborn
KMeans
silhoutte_score
StandardScaler
Matplotlib
Pandas
NumPy
These libraries are installed in the notebook using the pip package manager.

#Content
Section 1: Install Dependencies
This section installs the necessary libraries for the notebook using pip.

Section 2: Load and Preprocess Data
This section loads the MNIST dataset from the Keras library, and preprocesses it by reshaping the images and normalizing the pixel values.

Section 3: Define the Neural Network
This section defines a simple neural network architecture using Keras with two fully connected layers and a softmax output layer.

Section 4: Train the Neural Network
This section trains the neural network using the Adam optimizer and categorical cross-entropy loss function.

Section 5: Evaluate the Neural Network
This section evaluates the performance of the trained neural network on the test dataset using accuracy as the metric. The section also plots some sample predictions made by the network on test data
