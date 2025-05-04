# Makemore - Name Generation using Bigram, MLP, and Deep Neural Network Models

This repository contains an implementation of the Makemore name generation model using three approaches: a Bigram model, a Multi-Layer Perceptron (MLP), and a deeper neural network with Batch Normalization. The goal of this project is to generate plausible names based on patterns learned from existing names.

## Models Implemented

### 1. Bigram Model
A simple probabilistic model that generates names based on character transition probabilities learned from a dataset of names.

**Example names generated using the Bigram model:**
junide.
janasah.
prelay.
a.
nn.



### 2. Multi-Layer Perceptron (MLP)
A neural network-based approach that learns richer representations of character sequences to generate more realistic names.

**Example names generated using the MLP model:**
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



### 3. Deep Neural Network with Batch Normalization
A deeper model consisting of 6 layers and Batch Normalization, allowing for better generalization and training stability. This model further improves the realism and diversity of generated names.

**Example names generated using the deep model:**
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
salyansuiezajelveu.



## Usage
Clone the repository and run the provided scripts to train and generate names using any of the three models. The implementation includes training from scratch and sampling names from the trained models.

## Requirements
- Python 3.x  
- NumPy  
- PyTorch  
- Matplotlib (for visualization)

## Future Improvements
- Implement a Transformer-based model for better name generation  
- Add character embeddings for improved representation  
- Experiment with different architectures and hyperparameters  
