# fashion-mnist-classification

## Project Overview
This project focuses on applying a simple Feedforward Neural Network (Multilayer Perceptron) to classify clothing items from the **Fashion MNIST dataset**. The objective of this assignment is to gain hands-on experience with neural network architectures in TensorFlow/Keras and understand how deep learning handles image data compared to traditional machine learning.

The model achieves an accuracy of approximately **88%** on the test set, successfully categorizing 10 different types of everyday garments and footwear.

---

## Repository Contents
* `Fashion_MNIST_Classification.ipynb` - The full, executed Google Colab Jupyter Notebook containing data visualization, preprocessing, training, and evaluation code.
* `README.md` - Project documentation and setup guide.

---

## Dependencies & Technical Stack
To run this project locally or in a notebook environment, you will need the following Python libraries installed:

* **Python 3.x**
* **TensorFlow / Keras** (For building, compiling, and training the neural network architecture)
* **Scikit-Learn** (For generating performance metrics like the classification report and confusion matrix)
* **Pandas & NumPy** (For data manipulation and array restructuring)
* **Matplotlib & Seaborn** (For plotting training loss/accuracy graphs and visualization of data)

---

## Instructions to Run the Notebook

### Option 1: Run in Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/).
2. Select the **GitHub** tab in the welcome pop-up window.
3. Paste the URL of this GitHub repository into the search bar and press enter.
4. Click on the `.ipynb` notebook file to open it.
5. Go to the top menu, click **Runtime**, and select **Run all**.

### Option 2: Run Locally
If you prefer running this on your own machine, clone this repository and install the dependencies:

```bash
# Clone the repository
git clone <(https://github.com/OgunbanjoT/Lab2AI/blob/main/AI_Assignment12.ipynb)>

# Navigate into the project folder
cd fashion-mnist-classification

# Install required libraries
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn

# Launch Jupyter Notebook or JupyterLab
jupyter notebook
