# MNIST Dataset

This project uses the **MNIST Handwritten Digits Dataset** provided by TensorFlow/Keras.

The dataset is automatically downloaded the first time the notebook is executed.

```python
import tensorflow as tf

mnist = tf.keras.datasets.mnist

(x_train, y_train), (x_test, y_test) = mnist.load_data()
```

## Dataset Information

- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- Grayscale images
- 10 classes (digits 0–9)

Since the dataset is bundled with TensorFlow, no manual download is required.