# EE_596_NLP_Project2
## Exploring GPT-3 API through Zero-Shot and Few-Shot Prompting in Natural Language Processing
This project aims to explore the capabilities of the OpenAI's GPT-3 API with the implementation of zero-shot and few-shot prompting techniques using the SuperGLUE datasets. The exploration further comprises different prompts and experiment methods to delve deeper into GPT-3's capabilities in Natural Language Processing (NLP).

## Student: Naif Ganadily
## Professor: Chandra Bhagavatula
## Due Date: March 16
## Project Description:
This exploration involves downloading five datasets (COPA, RTE, WSC, ReCoRD, and CommitmentBank) from SuperGLUE and applying zero-shot and few-shot prompting techniques (up to 5 examples chosen from the training set) for each dataset. The project uses two distinct prompts for each dataset and evaluates the results across various settings.

The few-shot training examples are selected from the training set following three strategies:

1. Fixed: Choose training examples once, using them for all test instances.
2. Random: Randomly select N training examples for each test instance.
3. Relevant: Find training examples most similar to the test instance (use text similarity AND embedding-based similarity).
The evaluation results are reported considering the above settings.

# Experiment Results

This section contains the results from our experiments using GPT-3 for Natural Language Inference (NLI) tasks. We employed a variety of approaches: zero-shot, fixed, random, and relevant. 

## GPT-3 Results

The performance of GPT-3 was found to be below average for most of the methods used. Here is an overview of the results:

- Zero-shot:
  - Accuracy: 0.456 for Prompt 1, 0.444 for Prompt 2
- Fixed:
  - Accuracy: 0.66 for Prompt 1, 0.508 for Prompt 2
- Random:
  - Accuracy: 0.672 for Prompt 1, 0.5 for Prompt 2
- Relevant:
  - Accuracy: 0.768 for Prompt 1, 0.548 for Prompt 2

The results for the test data were quite discouraging, with the model scoring 0% accuracy for all the methods used.

- Zero-shot (Test Data):
  - Accuracy: 0.0 for both Prompt 1 and Prompt 2
- Fixed (Test Data):
  - Accuracy: 0.0 for both Prompt 1 and Prompt 2
- Random (Test Data):
  - Accuracy: 0.0 for both Prompt 1 and Prompt 2
- Relevant (Test Data):
  - Accuracy: 0.0 for Prompt 1

Despite these results, there is still room for improvement, especially in handling contradiction and neutral cases. Also, the 'unknown' category was not tested in these experiments but should be included in future iterations.

These experiments were conducted using the CommonGen benchmark dataset, designed specifically for testing the text generation capabilities of language models. Further testing on other datasets might yield different results.

## Project Dependencies
Before running the project, you need to install a few python packages as:


!pip install jsonlines
!pip install openai
!pip install sentence_transformers

## Project Code
The project uses several libraries including 'jsonlines', 'openai', 'sentence_transformers', 'numpy', 'pandas', 'matplotlib', and 'sklearn' to accomplish the tasks. The complete code is available in Python script format and Jupyter Notebook.

The key functionalities of the code include loading data, generating few-shot examples, making predictions with GPT-3, evaluating the predictions, and generating confusion matrices for visualization of results.

To use the code, simply clone the repository, install the dependencies, and run the provided Python scripts or Jupyter Notebooks.

## Results
The results of the exploration are available in a comprehensive report detailing the evaluation metrics across the five datasets considering various scenarios implemented. The Python scripts provide confusion matrices and classification reports for detailed insights into the performance of the model across various settings.

Please note: Always remove your API Keys before submitting or sharing your code.

## Usage
To use this repository:

1. Clone the repository to your local machine.
2. Install the necessary dependencies mentioned in the Project Dependencies section.
3. Add your OpenAI API Key in the space provided in the scripts.
4. Update the path to your datasets in the code.
5. Run the Python scripts or Jupyter Notebooks to execute the project.

## Project Repository Structure
The project repository consists of the following key files:

1. README.md: A markdown file containing information about the project and instructions on how to use the code.
2. main.py: The primary Python script containing the implementation of the project.
3. requirements.txt: A text file containing the necessary Python packages needed to run the script.
4. classification_report.txt: A text file containing the classification report of the model's predictions.
5. project_notebook.ipynb: A Jupyter Notebook containing the implementation of the project with detailed explanations of the code.

## Contribution
This project is conducted by Naif Ganadily, under the guidance of Professor Chandra Bhagavatula. Please feel free to fork this repository for research and development purposes. Contributions to improve this project are welcomed. Please consider submitting a pull request if you wish to contribute.

## License
This project is licensed under the terms of the MIT
