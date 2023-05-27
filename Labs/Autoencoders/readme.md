MNIST Autoencoder
This is a simple implementation of an autoencoder for the MNIST dataset using TensorFlow and Keras. The autoencoder is trained to reconstruct the input images with a bottleneck layer of 64 units.
Requirements
Python 3.x
TensorFlow 2.x
NumPy
Matplotlib
Jupyter Notebook
Usage
Clone the repository:
Copy

git clone https://github.com/your-username/mnist-autoencoder.git
Open the Jupyter Notebook:
Copy

jupyter notebook autoencoder.ipynb
Run the notebook:
Click on "Cell" in the menu bar
Click on "Run All"
The notebook will train the autoencoder for 10 epochs and display the reconstructed images.
Results
The autoencoder achieves a validation loss of 0.0745 after 10 epochs of training. The reconstructed images are visually similar to the original images, indicating that the autoencoder is able to learn a good representation of the input data.
