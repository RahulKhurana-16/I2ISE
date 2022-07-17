## End-to-end Image Search engine
The image search engines allow us to retrive similar images based on the query one.


## Project Instructions

### Getting Started

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/RahulKhurana-16/I2ISE.git
```

2. Install TensorFlow.
	- Option 1: __To install TensorFlow with GPU support__, follow [the guide](https://www.tensorflow.org/install/) to install the necessary NVIDIA software on your system.
	```
	pip install tensorflow-gpu==1.12.0
	```
	- Option 2: __To install TensorFlow with CPU support only__,
	```
	pip install tensorflow==1.12.0
	```

3. Install a few pip packages.
```
pip install -r requirements.txt
```

4. Download CIFAR-10 dataset.

	  - [Darknet mirror](https://pjreddie.com/projects/cifar-10-dataset-mirror/)
    ```
    1. Put downloaded data into dataset folder
    2. Put all images from `dataset/train` to `static/images`
    ```
    - [CIFAR-10 homepage](https://www.cs.toronto.edu/~kriz/cifar.html)
    
    ```
    1. Preprocessed the dataset (not covered here)
    2. Save each image in the jpg/png format into train/test folders
    3. Rest of the project stays the same
    ```


5. Run throuh image-search project.ipynb and generate all necessary files

6. Start the app.py file and enjoy!


