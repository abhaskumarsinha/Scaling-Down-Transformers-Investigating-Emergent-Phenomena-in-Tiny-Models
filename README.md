# Scaling-Down-Transformers-Investigating-Emergent-Phenomena-in-Tiny-Models

This repository is the code of the paper, *Scaling Down Transformers: Investigating Emergent Phenomena in Tiny Models* by `Abhas Kumar Sinha`.

## **Abstract**


<p align='justify'>In this paper, we investigate the emergent learning capabilities of autoregressive
models, particularly Generative Pre-trained Transformers (GPTs), with a focus on
how these models learn and generalize from sparse datasets. Our findings show
that increasing the number of training epochs enhances emergent abilities, where
different loss reductions correlate with distinct task distributions in the pretraining
dataset. We demonstrate how GPT models decompose sparse data into latent
patterns, allowing them to learn new distribution information and extrapolate these
patterns to improve cross-task predictions. For instance, the model achieves nearly
65% accuracy with just 50 samples (out of 1680 possible samples) when encoding
two synthetic languages, and reaches accuracies of 93.5%, 99.75%, and 99.25%
with 100, 200, and 300 samples (out of 11880 possible samples), respectively, from
a larger dataset. Additionally, we highlight the influence of prompt design, dataset
characteristics, and latent variables on pattern recognition and task performance.
These results advance the understanding of large language models’ emergent
learning abilities, offering insights into their generalization power across diverse
tasks.</p>

![demonstration_page-0001](https://github.com/user-attachments/assets/e950a726-cbc0-436f-9b98-be3b031da9cd)

_Example of such latent variable pattern - θQ._

![latent_context_example_page-0001](https://github.com/user-attachments/assets/231517ff-919c-4d7e-858b-4ccb66bc12de)

_The above figure demonstrates how common latent variable patterns across different dataset
chunks are learned by the model, with θ1, θ2, and θ3 indicating three different datasets._

![image](https://github.com/user-attachments/assets/a162d4e3-356d-403f-9d0c-8e518a59fbd1)

## Installation
```
git clone https://www.github.com/abhaskumarsinha/Corpus2GPT.git
```

## Running
The notebooks are **NOT** reproduceable. Although they can be rerun to have similar results.

# References
1. Sinha, A.K. (2024) Corpus2GPT. _GitHub Repository_. Available at: https://github.com/abhaskumarsinha/Corpus2GPT/.

