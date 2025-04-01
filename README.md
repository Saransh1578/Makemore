# Makemore - Name Generation using Bigram Model and MLP

This repository contains an implementation of the Makemore name generation model using a Bigram model and a Multi-Layer Perceptron (MLP). The goal of this project is to generate plausible names based on patterns learned from existing names.

## Models Implemented

### 1. Bigram Model
A simple probabilistic model that generates names based on character transition probabilities learned from a dataset of names.

**Example names generated using the Bigram model:**
```
junide.
janasah.
prelay.
a.
nn.
```

### 2. Multi-Layer Perceptron (MLP)
A neural network-based approach that learns richer representations of character sequences to generate more realistic names.

**Example names generated using the MLP model:**
```
mona.
kayanniellen.
hayah.
rethrus.
jernegan.
chedo.
lillemy.
jenreigh.
edo.
naraelyzion.
kalin.
shorergianaiel.
kin.
renleigh.
terorius.
kacdi.
kymeri.
els.
kayshis.
kyla.
```

## Usage
Clone the repository and run the provided scripts to train and generate names using either model. The implementation includes training from scratch and sampling names from the trained models.

## Requirements
- Python 3.x
- NumPy
- PyTorch
- Matplotlib (for visualization)

## Future Improvements
- Implement a Transformer-based model for better name generation
- Add character embeddings for improved representation
- Experiment with different architectures and hyperparameters

## License
This project is licensed under the MIT License.

