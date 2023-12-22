# Adapters

In this section we are evaluating the performance of the `roberta` model using
parameter efficient training methods (Adapters). For this we are using the
implementations from [AdapterHub](https://docs.adapterhub.ml/).

## Reasoning
Adapters tend to generalize better on smaller datasets than regular
fine-tuning. Because of the limited training data we want to explore whether
these methods can yield higher accuracy.
