# Segmentation-of-Sentinel-2-data

This repository provides a tutorial for working with Sentinel-2 hyperspectral data in remote sensing for semantic segmentation of crop types in Pytorch. 

The data utalized in repository is provided by the DENETHOR dataset found at the following repo: [DENETHOR](https://github.com/lukaskondmann/DENETHOR).

This repo demonstrates not only how to train a segmentation model for Sentinel-2 data, but also how to process prior to modelling of the data which is half the work! To get the data it is reccomended to create a free trial account at [Sentinel](https://www.sentinel-hub.com/) Hub account before continuing, downloading the data may seem a little confusing if one is new to remote sensing, therefore the request builder or EO browser can be utalized as an alternative.   

If you wish to skip the Sentinel Hub downloading part the data can also be found in the data folder. 

# Requriements

To susccesfully run this tutorial the following must be downloaded (using pip is probably the easiest)

```
pip3 install torch torchvision # remember to install with GPU support if needed
pip install geopandas
pip install cv2
```
If i have skipped any relevant package please reach out to me so that i might fix this. 

# Running the Code

To run the code there are two option, either download the python scripts directly from the folders "Pytorch code" and "Data Preprocessing" and run this in your favourite IDE. The second option is to download the juptyer notebook format directly and run the code from there. As an alternative to training the model from zero, it is possible to download a tranined model from the bst_model file located in the "Pretrained" folder.   
