# Visualising the Hidden Neurons of a Non-convolutional DNN Trained on the MNIST Database

This is an independent research project I (Ben Auer) undertook as part of the subject Real and Artifical Neural Networks (NEUR30006) at the University of Melbourne. This repository includes the final project report and the Jupyter notebook containing all the code used to create the report, mostly for ease of sharing my work with others. The network was trained and visualised entirely in NumPy, without using any modern ML packages, as this was prohibited by the course.

## Files

* [`Visualising Hidden Neurons Project Report Final.pdf`](Visualising Hidden Neurons Project Report Final.pdf): The final project report as a PDF (17 pp).
* [`Visualising Hidden Neurons Code Final.ipynb`](Visualising Hidden Neurons Code Final.ipynb): The complete Jupyter notebook.

## Usage

The Jupyter notebook is configured so that the parameters of any pre-trained non-convolutional MNIST classifier DNN can be loaded and its hidden neurons visualised. Alternatively a new DNN can be trained easily (with any neuron / layer configuration) and visualised. Visualisation images can also be saved and reloaded if desired. The code could likely be adapted for use with a convolutional classifier too, and I would be interested to see that if anyone wishes to do so.

## License

[MIT](https://choosealicense.com/licenses/mit/)
