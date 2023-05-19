# EE_596_NLP_Project2
## Exploring GPT-3 API through Zero-Shot and Few-Shot Prompting in Natural Language Processing
The primary objective of this project is to probe the potential of OpenAI's GPT-3 through zero-shot and few-shot prompting methods in the Natural Language Processing (NLP) domain. This investigation leverages the SuperGLUE datasets, focusing on multiple prompts and experimentation strategies to scrutinize the depth of GPT-3's NLP capabilities.

## Student: Naif Ganadily
## Professor: Chandra Bhagavatula
## Deadline: March 16

## Project Synopsis:
Five datasets (COPA, RTE, WSC, ReCoRD, and CommitmentBank) from SuperGLUE are utilized in this project. Both zero-shot and few-shot prompting methods (with up to 5 examples from the training set) are applied to each dataset. The prompts are varied and the results evaluated across diverse configurations.

The few-shot training examples are chosen from the training set based on three strategies:
1. Fixed: Consistent use of the same training examples for all test instances.
2. Random: Selection of N training examples at random for each test instance.
3. Relevant: Determination of the most similar training examples to the test instance (both text and embedding-based similarity considered).

The outcomes of the evaluations, reflecting the above scenarios, are reported in the subsequent section.

# Experiment Outcomes

The results from our experiments using GPT-3 in the Natural Language Inference (NLI) tasks are listed below. Various approaches: zero-shot, fixed, random, and relevant were deployed.

## GPT-3 Performance

GPT-3's performance was found wanting in most of the methods used. Here's a snapshot of the outcomes:

- Zero-shot:
  - Accuracy: 0.456 for Prompt 1, 0.444 for Prompt 2
- Fixed:
  - Accuracy: 0.66 for Prompt 1, 0.508 for Prompt 2
- Random:
  - Accuracy: 0.672 for Prompt 1, 0.5 for Prompt 2
- Relevant:
  - Accuracy: 0.768 for Prompt 1, 0.548 for Prompt 2

The performance on the test data was disappointing, with 0% accuracy across all methodologies.

- Zero-shot (Test Data):
  - Accuracy: 0.0 for both Prompt 1 and Prompt 2
- Fixed (Test Data):
  - Accuracy: 0.0 for both Prompt 1 and Prompt 2
- Random (Test Data):
  - Accuracy: 0.0 for both Prompt 1 and Prompt 2
- Relevant (Test Data):
  - Accuracy: 0.0 for Prompt 1 and Prompt 2

Despite the underwhelming results, opportunities for improvement exist, especially in dealing with contradiction and neutral cases. Additionally, the 'unknown' category, which was not included in these experiments, could be a focus for future tests.

These experiments were conducted using the CommonGen benchmark dataset, specifically created for evaluating the text generation prowess of language models. It's important to note that running similar tests on other datasets could lead to varying results.

## Project Requirements
Before executing the project, ensure the following python packages are installed:

!pip install jsonlines
!pip install openai
!pip install sentence_transformers


## Project Implementation
The project leverages several libraries including 'jsonlines', 'openai', 'sentence_transformers', 'numpy', 'pandas', 'matplotlib', and 'sklearn' to accomplish its goals. The complete code can be accessed in either Python script or Jupyter Notebook format.

The code carries out several tasks including data loading, generating few-shot examples, making predictions with GPT-3, evaluating the predictions, and creating confusion matrices for result visualization.

To use the code, clone the repository, install the necessary dependencies, and run the provided Python scripts or Jupyter Notebooks.

## Results
The exploration results are presented in a detailed report that outlines the evaluation metrics across all five datasets, taking into account the different scenarios implemented. The Python scripts provide confusion matrices and classification reports, offering in-depth insight into the model's performance under various settings.

Please remember to remove your API Keys before submitting or sharing your code.

## Usage
To utilize this repository:

1. Clone the repository to your local machine.
2. Install the necessary dependencies as mentioned in the Project Requirements section.
3. Insert your OpenAI API Key in the appropriate space in the scripts.
4. Update the path to your datasets in the code.
5. Run the Python scripts or Jupyter Notebooks to execute the project.

## Contribution
This project was conducted by Naif Ganadily under the guidance of Professor Chandra Bhagavatula. Forking this repository for research and development purposes is encouraged. Contributions aimed at enhancing this project are warmly welcomed. Please consider submitting a pull request if you'd like to contribute.

## License
This project is governed by the terms of the MIT license.
