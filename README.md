# TensorFlow Convolutional Network

A low-level TensorFlow CNN example that classifies MNIST digits using convolution, max pooling, and fully connected layers.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python convolutional_network_raw.py
```

Keras downloads MNIST on first run. The script trains for 200 steps, reports validation accuracy, and plots sample predictions.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/).