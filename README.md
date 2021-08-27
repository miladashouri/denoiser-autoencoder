

# Introduction:

This project creates a denoiser model using an AutoEncoder model to map the noisy image data (Cell Images) to their original version. The dataset is pretty large. We will uses batches of data to fit the model. Consider using GPU processing and enough RAM (16GB at least) to load the data. In case of limited resources and for demonstration, we will fetch only part of data.

# ORIGINAL DATA SOURCE:

The dataset contains 2 folders - Infected - Uninfected. However, we will use the uninfected data only.

There is a total of 27,558 images.

Acknowledgements
This Dataset is taken from the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/ 


## Startup:
**The best way to start the model training is through creating a conda envireonment, for example:**

```conda create -n autoencoder ```

The dependencies required to run the jupyter notebook file are listed in the requirements.txt. simply run the following:

``` pip install -r requirements.txt ```

After installing the required dependencies, run the jupyter notebook by:

``` jupyter notebook ```

In the jupyter notebook navigator, run the model.ipynb. 


 