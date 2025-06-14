# Makemore - Name Generation using Bigram Model and MLPs

This repository contains implementations of the Makemore name generation model using a Bigram model, a standard Multi-Layer Perceptron (MLP), and a deeper MLP with Batch Normalization. The goal of this project is to generate plausible names based on patterns learned from existing names.

## Models Implemented

### 1. Bigram Model
A simple probabilistic model that generates names based on character transition probabilities learned from a dataset of names.

**Example names generated using the Bigram model:**
````
junide.
janasah.
prelay.
a.
nn.
````

### 2. Multi-Layer Perceptron (MLP)
A neural network-based approach that learns richer representations of character sequences to generate more realistic names.

**Example names generated using the MLP model:**

````
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
````

### 3. Deeper MLP with Batch Normalization
An enhanced MLP model featuring a deeper architecture (6 layers) and incorporating Batch Normalization. This aims to potentially improve training stability and generalization for name generation.

**Example names generated using the Deeper MLP with Batch Normalization model:**

````
mria.
mmyan.
seelendhnyal.
rethrsjendrleg.
ade.
kdieliin.
miloen.
ekeisean.
xarlelleimhlara.
noshdh.
rgshiries.
kin.
reneliqxnthacfiu.
zayvde.
jymeli.
ehs.
kay.
mistoyan.
hal.
salyansuiezajelveu
````

### 4. Manual Backpropagation MLP (from Scratch)
A fully custom MLP model where both the forward and backward passes are implemented manually using pure PyTorch tensor operations—without relying on PyTorch's autograd. This design serves as a foundational learning exercise to deeply understand gradient flow, parameter updates, and the mechanics of training neural networks at the lowest level. The model captures the essence of backpropagation by explicitly computing gradients for each layer and updating weights accordingly.

** Example names generated using the Manual Backpropagation MLP model:
````
mora.
mayah.
see.
mad.
ryla.
reisha.
ejdrie.
cadelynnelin.
shi.
jen.
eden.
sana.
arleigh.
malaia.
noshub.
roshiriel.
kindreelynn.
novana.
ubdence.
ryyah.
````

## Usage
Clone the repository and run the provided scripts to train and generate names using any of the implemented models. The implementation includes training from scratch and sampling names from the trained models.

## Requirements
- Python 3.x
- NumPy
- PyTorch
- Matplotlib (for visualization)

## Future Improvements
- Implement a Transformer-based model for better name generation
- Add character embeddings for improved representation
- Experiment with different architectures and hyperparameters
