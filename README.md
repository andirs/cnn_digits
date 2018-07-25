# Digit Classification
Classification of digits from 0 to 9 is a text-book example of neural networks. It provides a few interesting challenges and potential tweaks making it perfect to let your first neural net run wild. The project foreshadows how to build and train a neural net that's responsive to new inputs with as little as 1000 self-drawn digits. The project has been deployed in an [web-app](http://digits.rvbin.com) and can be trained with new data. The ingredients of this project are Python, Django, Tensorflow as well as JavaScript and Bootstrap for the front-end. This repo focuses on the model creation and backend functions for the classification task.

Find [a running example](http://digits.rvbin.com) of the final model here.

## Data
The data used to train the model can be found [here](https://drive.google.com/open?id=1J1G1jK8hotALkZZWR07fTjrGfZvLkH2y). It conists out of 1010 drawings of digits from 0 to 9.

## Requirements
All requirements to run this project are stored in `requirements.txt`. To install everything I suggest using a virtual environment and running 

```pip install -r requirements.txt ```