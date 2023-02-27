# MALARIAL_CELL_DETECTION
Classification of Healthy and Parasitised Malarial Cell
import numpy
import pandas
import matplotlib.pyplot

# OS ALLOWS TO OPERATE/INTERACT ON UNDERLYING OPERATING SYSTEM  
import os 
import cv2

#PILLOW/PIL IS THE ORIGINAL LIBRARIES FOR DEALING/PREPROCESSING  WITH IMAGES 
from PIL import Image

from tensorflow import keras 
import tensorflow.keras.layers as k 

from tqdm import tqdm 

from IPython.display import SVG

import livelossplot
plot_losses = livelossplot.PlotLossesKeras()
