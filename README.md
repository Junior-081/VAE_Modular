# Implementation of a Variational Autoencoder using Pytorch


## Description:

The variational autoencoder (VAE) is a framework for training two neural networks: an encoder and a decoder, in order to learn a mapping from a high-dimensional data representation to a lower-dimensional space and back again


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FrfL4__qTlfGkHNwppdjK1kZleHcHdxU?usp=sharing)

# Install the Project

```
$ https://github.com/Nwanna-Joseph/VAE_Modular.git
```

```
$ cd Bernouilli-Naive-Bayes
```
# Virtual environment

## Mac OS

### Create virtual environment 

```
$ python3 -m venv NAME_ENV
```
### Activate your environment 

```
$ source NAME_ENV/bin/activate
```

## Linux OS

### Create virtual environment

```
$ conda create -n venv NAME_ENV
```

### Activate your environment 

```
$ activate NAME_ENV
```

# Requirement installations
To run this, make sure to install all the requirements by:

```
$ pip install -r requirements.txt 
```

## Run the model 
 1) To train the network ```python train.py```
 2) To generate new SMILE ```python generate.py```
 3) To install dependencies ```pip install -r requirements.txt ```

## Dependencies:
 1) numpy
 2) torch
 3) argparse
 4) torchvision

## Folder Structure:
 1) data : Contains files related to the SMILES data
 2) tests: Contains scripts for unit testing 
 3) saved_model: Where models that have been trained are saved

## Files : 
 1) data/SMILEDataset : The SMILE dataset class built on pytorch
 2) data/smiles.txt: The training data
 3) args_params.py : Manages the extraction of the command line arguments
 4) encode_data.py : Manages one-hot encoding and decoding
 5) main.py: Manages the training of the network
 6) model.py : Manages the Variational Autoencoder Neural Network class for encoding, decoding and reparameterization
 7) utils.py : Manages the utility functions for softmax, temperature sampling, one-hot encoding and decoding, loss function, generating new models, e.t.c


## Contributors (Group Members)
<div style="display:flex;align-items:center">

<div style="display:flex;align-items:center">
<div>
    <h5> <a href='https://github.com/Junior-081'> Junior Kaningini </a> </h5> <img src="photo_junior.jpg" height= 7% width= 7%>
 </div>
    
<div>
    <h5> <a href='#'>Angela Munayo </a> </h5> <img src="images/f.jpeg" height= 7% width= 7%>
    
</div>

<div>
    <h5> <a href='#'> Gasana Elysee  </a> </h5> <img src="images/sari.jpeg" height= 7% width= 7%>
    
</div>
 
  <div>
        <h5> <a href=''>  Nwanna Joseph</a> </h5> <img src="images/f.jpeg" height= 7% width= 7%>
     </div>

</div>


## Special Thanks to :
 1) The organizers of the AMMI 2022 program
