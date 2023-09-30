conda create --name openvc-env
conda activate openvc-env
conda install -c conda-forge opencv
pip install opencv-python
import cv2 as cv
cv.__version__