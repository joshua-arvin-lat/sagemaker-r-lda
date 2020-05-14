## An Introduction to SageMaker LDA in R

R implementation counterpart of "An Introduction to SageMaker LDA". You can access the notebook [here](./main.ipynb)


### Description

**Amazon SageMaker LDA** is an unsupervised learning algorithm that attempts to describe a set of observations as a mixture of distinct categories. **Latent Dirichlet Allocation (LDA)** is most commonly used to discover a user-specified number of topics shared by documents within a text corpus.

In this notebook, we will demonstrate the **R** implementation counterpart of **An Introduction to SageMaker LDA** written in Python. Given that majority of the **SageMaker** sample notebooks are written in **Python**, data scientists already using the R language can use this notebook as a reference so that they are not forced to convert existing scripts and notebooks already written with the R language.

Similar to the original notebook written in Python, the following are not the goals of this notebook:

- discuss and interpret the generated synthetic document data
- understand the LDA model
- interpret the meaning of the inference output
