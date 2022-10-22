# Contents
- [Contents](#contents)
- [Scaling analysis](#scaling-analysis)
  - [1 Trillion](#1-trillion)
  - [10 Trillion](#10-trillion)
  - [100 Trillion](#100-trillion)
- [What would you expect a 100 Trillion parameter model to be able to do that a 1 Trillion parameter model can’t?](#what-would-you-expect-a-100-trillion-parameter-model-to-be-able-to-do-that-a-1-trillion-parameter-model-cant)
- [In your view what is the most important idea to make training 100 Trillion parameter models possible?](#in-your-view-what-is-the-most-important-idea-to-make-training-100-trillion-parameter-models-possible)


# Scaling analysis

Please use the scaling laws from OpenAI and DeepMind to answer the following questions for different **#parameters** settings. There is no standardized answers to the following questions, but you should be able to justify your design choices during peer review.

References
- OpenAI paper: https://arxiv.org/abs/2001.08361
- Deepmind paper: https://arxiv.org/abs/2203.15556
- For your reference, here are some LLM and their number of parameters: https://openbmb.github.io/BMList

## 1 Trillion

1. Architecture related

| shape of the network (E-o, E-D, D-o) <!--E-o: Encoder-only, E-D: Encoder-Decoder, D-o: Decoder-only--> | Number of layers | Number of Dimensions | Number of Heads | Shape of the Feed Forward Layers | Width of the input |
| ---- | ---- | ---- | ---- | ---- | ---- |
| <your answer> | <your answer> | <your answer> | <your answer> | <your answer> | <your answer> |

2. data related

| Number of Tokens | Types of data | Where will you get the data? |
| ---- | ---- | ---- |
| <your answer> | <your answer> | <your answer> |

3. time related
  On current fastest hardware (20EF (bfp16)), how fast of a machine to train the model? Give answer in "X day / X week / X month / X year" format and explain why you think so.

<!-- For example, "some model" trained in 68 days / 9.714 weeks / 2.236 months / 0.186 years, with 32 A100 40GB GPUs. -->

<your answer>

## 10 Trillion


1. Architecture related

| shape of the network (E-o, E-D, D-o) <!--E-o: Encoder-only, E-D: Encoder-Decoder, D-o: Decoder-only--> | Number of layers | Number of Dimensions | Number of Heads | Shape of the Feed Forward Layers | Width of the input |
| ---- | ---- | ---- | ---- | ---- | ---- |
| <your answer> | <your answer> | <your answer> | <your answer> | <your answer> | <your answer> |

2. data related

| Number of Tokens | Types of data | Where will you get the data? |
| ---- | ---- | ---- |
| <your answer> | <your answer> | <your answer> |

3. time related
  On current fastest hardware (20EF (bfp16)), how fast of a machine to train the model? Give answer in "X day / X week / X month / X year" format and explain why you think so.

<!-- For example, "some model" trained in 68 days / 9.714 weeks / 2.236 months / 0.186 years, with 32 A100 40GB GPUs. -->

<your answer>

## 100 Trillion


1. Architecture related

| shape of the network (E-o, E-D, D-o) <!--E-o: Encoder-only, E-D: Encoder-Decoder, D-o: Decoder-only--> | Number of layers | Number of Dimensions | Number of Heads | Shape of the Feed Forward Layers | Width of the input |
| ---- | ---- | ---- | ---- | ---- | ---- |
| <your answer> | <your answer> | <your answer> | <your answer> | <your answer> | <your answer> |

2. data related

| Number of Tokens | Types of data | Where will you get the data? |
| ---- | ---- | ---- |
| <your answer> | <your answer> | <your answer> |

3. time related
  On current fastest hardware (20EF (bfp16)), how fast of a machine to train the model? Give answer in "X day / X week / X month / X year" format and explain why you think so.

<!-- For example, "some model" trained in 68 days / 9.714 weeks / 2.236 months / 0.186 years, with 32 A100 40GB GPUs. -->

<your answer>

# What would you expect a 100 Trillion parameter model to be able to do that a 1 Trillion parameter model can’t?

<your answer>

# In your view what is the most important idea to make training 100 Trillion parameter models possible?

<your answer>