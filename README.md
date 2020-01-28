# Cat-Dog-Classifier

## Classifying Cat and Dog Images via ML and CNN

### Dataset
Over 20,000 pictures of cats and dogs in different enviroments. Dataset available at:  [microsoft.com/en-us/download/details.aspx?id=54765](https://www.microsoft.com/en-us/download/details.aspx?id=54765 "Cat and Dogs Dataset").

### Used Libraries:

- Tensorflow-gpu
- OpenCV
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- tqdm

### ML Model: Convolutional Neural Network (CNN)

> The Convolutional Neural Network gained popularity through its use with image data, and is currently the state of the art for detecting what an image is, or what is contained in the image.
The basic CNN structure is as follows: Convolution -> Pooling -> Convolution -> Pooling -> Fully Connected Layer -> Output

> Convolution is the act of taking the original data, and creating feature maps from it.Pooling is down-sampling, most often in the form of "max-pooling," where we select a region, and then take the maximum value in that region, and that becomes the new value for the entire region. [pythonprogramming.net](https://pythonprogramming.net/convolutional-neural-network-deep-learning-python-tensorflow-keras/ "reference source")

---

### To run:

1. __`git clone https://github.com/rezan21/Cat-Dog-Classifier.git` or Download the repository and *unzip* it__

2. __Install required libraries__
    - Make sure all specified libraries are installed, if not, use `pip install`.
    
3. __Run Jupyter lab or notebook and open `cat_dogs_cnn.ipynb`__

4. __Apply following changes to the code__
    - delete/comment first 3 lines of the __first cell__
    - change first line of the __second cell__ to match the location where the dataset you downloaded is stored:
        - On mac: `DATADIR = '/Users/YOUR_USER_HERE/Downloads/Cat-Dog-Classifier-master/catsanddogs'`
        
5. __Run remaning cells__





