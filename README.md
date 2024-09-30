**LLM Education Material**
***

This git repo contains education and training material for the test and evaluation (T&E) of an Large Langugage Model (LLM). 

Jupyter notebooks are provided. The user will be able to load an pre-trained LLM, load test datasets, run tests on LLM and evaluate the performance of LLM.

**Jupyter Notebook Descriptions**
***

1. LLM_T&E_Basics_Tutorial.ipynb: This notebook serves an introduction to the fundamentals in testing LLMs. It covers basic concepts and provides hands-on examples familiarize the user with the following:

    - **Loading an LLM**: Step-by-step instructions on how to load a pre-trained LLM, with an overview on basic inferencing using LLM
    - **Understanding Prompts**: Explanation of what a prompt is and how it influences the behavior of the model, including examples and prompting strategies
    - **Exploring Model Parameters**: Learn how different parameters, such as temperautre, max tokens, and top-k, impact the output of the model. The user can experiment with these parameters to see how they impact the model response.

2. Question_Answering_MCQ_Task.ipynb: This notebook demonstrates how to test LLMs for Question & Answering (Q&A) tasks.

3. NER_task.ipynb: This notebook introduces how to test LLMs on Named Entity Recognition (NER) tasks.

4. Summarization_task.ipynb: This notebook demonstrates on how to test LLMs for Summarization task. 


## Installation and Quickstart

Use the package manager [conda](https://anaconda.org/conda-forge/stable-baselines3) to install the environment dependencies. Pip will be used to install additional dependencies within the individual notebooks.

```bash
conda env create -f environment.yml
conda activate llm
jupyter lab
```
