# Vision Transformer Implementation

This repository contains the implementation of the Vision Transformer model for the MNIST dataset. The Vision Transformer (ViT) is a novel neural network architecture proposed in the paper "Vision Transformer" by Alexey Dosovitskiy et al. The goal of this project is to demonstrate the effectiveness of the Vision Transformer architecture on a simple image classification task like MNIST.

## Project Structure

```
├── dataset
├── dataset.py
├── model.py
├── README.md
├── train.py
├── utils.py
└── Visual Transformer.pdf
```

- `dataset/`: Directory containing MNIST dataset.
- `dataset.py`: Python script for loading and preprocessing MNIST dataset.
- `model.py`: Implementation of the Vision Transformer model.
- `README.md`: This file, containing information about the project.
- `train.py`: Python script for training the Vision Transformer model on the MNIST dataset.
- `utils.py`: Utility functions used in the project.
- `Visual Transformer.pdf`: Paper describing the Vision Transformer architecture.

## Usage

1. Install the required dependencies:

```
pip install -r requirements.txt
```

2. Prepare the dataset by running `dataset.py`.

```bash
python dataset.py
```

3. Train the Vision Transformer model using `train.py`.

```bash
python train.py
```

4. Monitor the training progress and evaluate the model's performance.

## References

- [Vision Transformer Paper](Visual%20Transformer.pdf): "Vision Transformer" by Alexey Dosovitskiy et al.
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/): The MNIST dataset of handwritten digits.

## License

This project is licensed under the [MIT License](LICENSE).
