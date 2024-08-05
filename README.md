# Prodigy-Infotech-Genreative-AI-Internship-Tasks
# Task 1
## Installation

```bash
pip install transformers datasets

```
## Usage
```bash
The usage of transformers and datasets, particularly in the context of machine learning and natural language processing (NLP), 
has become increasingly popular due to the efficiency and effectiveness of these tools
```

## KINDLY PERFORM THIS TASK IN JUPYTER NOTEBOOK.

# Task 2
## Installation

```bash
pip install diffusers transformers gradio accelerate
```
## Usage
```bash
This library is primarily used for generating images using diffusion models. 
It provides various pipelines for tasks like text-to-image generation.
```
## Note 
### Adjust the Collab Notebook's settings if you have a intel graphics card to ensure code runs smoothly.

```bash 
STEP 1 : GO TO RUNTIME 

STEP 2 : CLICK ON CHANGE RUNTIME TYPE

STEP 3 : AFTER THAT, CLICK ON THE T4 GPU AND SELECT SAVE TO SAVE THIS SETTING.

```
## Note 
### If you have NVIDIA GRAPHICS IN YOUR SYSTEM DO NOT CHANGE THE ABOVE MENTIONED CHANGES TO YOUR COLLAB NOTEBOOK

## The Google Colab Notebook offers a GPU to provide better graphics for text transformation into images, therefore please complete this work there.

# Task 3
## What is Markov Chain?

### Markov Chain is a stochastic model which uses the mathematics to predict the probability of future events based on previous event. The example that everyone gives of a Markov chain in action is Google predicting what word your going to type next when you are typing an email,based upon the perhaps half-typed sentence right before it.

## What are transition in Markov Chain model?

### Here, transitions is a dictionary defined in the provided code which acts like Markov chain model to predict next generation of text. Language Model: Determines the probabilities of transitioning from one word to another in a continuous language

### Dictionary breakdown

#### The keys are the current words or states in the markov chain.
#### The dict from the above example in this case consists of a key value pair where values are dictionaries and these map to 
#### what all words can be used as next word with their corresponding probaility.

## For example
```bash
'the': {'small': 0.5, 'lazy': 0.5}
```
### This means that if the current word is 'the', there is a 50% chance (0.5 probability) that the next word will be 'small', and a 50% chance that the next word will be 'lazy'

### This transitions dictionary represents a simple example of a Markov chain model for generating sentences like "The small brown dog jumped over the lazy cat." The model captures the transition probabilities between words, allowing for the generation of new sentences based on the provided probabilities.

## KINDLY PERFORM THIS TASK IN JUPYTER NOTEBOOK.
