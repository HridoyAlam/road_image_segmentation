# road_image_segmentation
The aim of this project is road detection from satellite images using a variant of deep Convolutional Neural Networks which is known as U-Net. The output of the model is a segmentation mask which differentiates roads from other terrains.

# Dependencies
Keras with TensorFlow backend; Numpy; Matplotlib; OS; OpenCV; H5py;

# Dataset
Dataset for thsi project is collecled from https://www.cs.toronto.edu/~vmnih/data/ which provide Massachusetts Roads Dataset of salletile imagery. Each image resolution is 1500x1500 pixel. A per-pixel-classification technique is used, which means that a single pixel generates one feature vector, so an 1500x1500 image will generate 2250000 vectors, which is too large to be handled by a personal computer thats why we use kaggle notebooks.

# Group Mate
This project was done with my course mate [https://github.com/ismot-sadik-peyas] for our course Pattern Recongnization & Neural network Course.
## N.B
This project was done 5 months ago, but due to technical difficulties I did not upload this into my git account
