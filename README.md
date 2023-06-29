# Multiclass Classification of Mathematics Questions using OpenAI

This repository contains a Jupyter notebook that explores three different methods to classify Mathematics questions into various categories using models by OpenAI. 

## Dataset

The questions are sourced from [Art of Problem Solving](https://artofproblemsolving.com/) with [Mathpix OCR](https://mathpix.com/) tool to transform them into LaTeX format. The categories are given by the website itself. The dataset can be found at [this link](https://huggingface.co/datasets/AFFFPupu/Maths_competition_questions/blob/main/AMC_questions.csv).

## Classification Categories

The categories are divided into two groups:

1. Difficulty levels: 
   - Introductory
   - Intermediate
   - Olympiad

2. Topics: 
   - Geometry
   - Number Theory
   - Algebra
   - Combinatorics

## Classification Techniques

We use three different methods for classification:

1. Zero-shot Classification using prompt guidance.
2. Fine-tuning the model.
3. Text embeddings.

## Instructions

1. Clone this repository to your local machine.
2. Install the dependencies listed in the `requirements.txt` file.
3. Run the Jupyter notebook.

## Dependencies

- openai
- pandas
- numpy

## Acknowledgments

This work is inspired by a notebook available at [openai-cookbook](https://github.com/openai/openai-cookbook/blob/main/examples/Multiclass_classification_for_questions.ipynb).

## Contact

Please raise an issue in this GitHub repository if you have any questions or comments.

