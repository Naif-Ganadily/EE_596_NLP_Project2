# EE_596_NLP_Project2
## GPT-3 API Exploration: Zero-Shot and Few-Shot Prompting in Natural Language Processing
Greetings, I am Naif Ganadily, a Master of Science in Electrical Engineering student under the mentorship of Professor Chandra Bhagavatula. I have the pleasure of presenting to you the details of my recent project focused on Natural Language Processing (NLP), where I delved into the capacities of the GPT-3 API, utilizing zero-shot and few-shot prompting techniques. I successfully completed this endeavor on March 16th.

## Project Overview
This project aimed to uncover the robust potentialities of the GPT-3 API through the lens of both zero-shot and few-shot prompting. I initiated this exploration by employing five distinct datasets - COPA, RTE, WSC, ReCoRD, and CommitmentBank, retrieved from the SuperGLUE dataset. The ambition was to execute zero-shot and few-shot prompting, limiting the example selection to no more than five from the training set for each dataset. I subjected each dataset to two unique prompts, a fascinating task to undertake.

I adhered to the training set to cherry-pick the few-shot training examples and utilized three distinct selection methods: Fixed, Random, and Relevant. Each method offered a unique strategy to the selection process, contributing to the dynamism and captivation of the project.

Upon completion of the tests, I engaged in a meticulous evaluation of the results and compiled an exhaustive report summarizing the outcomes across all test scenarios. This evaluation phase was critical to understanding the effectiveness and efficiency of the implemented methodologies.

## Resources Employed
Numerous resources were indispensable for the successful completion of this project. These included:

OpenAI GPT3 Access Login https://platform.openai.com/login
OpenAI Documentation https://platform.openai.com/docs/guides/completion
SuperGLUE Dataset https://super.gluebenchmark.com/tasks
Code Examples https://github.com/openai/openai-python 

## Project Deliverables
The culmination of my work comprises all the project code, available in the form of a Python script and a Jupyter Notebook, and an elaborate report, delivered in PDF format. The report provides a thorough elucidation of the evaluation metrics on the five datasets across the varying scenarios implemented.

## Setup Procedure
This project utilized a selection of Python packages, which can be set up using the following commands:

python
Copy code
!pip install jsonlines
!pip install openai
!pip install sentence_transformers

Access to Project Code
You are welcome to explore my work further. Access to the core code structure and the utilized GPT-3 API operations are available in this Python Notebook.

This project presented an enriching and challenging avenue to probe the capacities of the GPT-3 API. I am grateful for the opportunity to spearhead this venture. The insights garnered from this exploration into NLP promise to be an invaluable asset for my future scholarly pursuits. I sincerely hope that my work sparks inspiration and provides a helpful resource for your journey in NLP as well.

## Repository Structure
The repository contains the following key files and directories:

src/: Directory containing the source code files for the project.
notebooks/: Directory containing the Jupyter notebooks with various experiments and explorations.
data/: Directory containing the datasets used in this project.
requirements.txt: Text file containing the required Python libraries for this project.
report.pdf: The final comprehensive report detailing the findings of this project.
How to Use
Before diving into the code, make sure to install the necessary dependencies as specified in the requirements.txt file. You can do this by running the following command in your terminal:

python
Copy code
pip install -r requirements.txt
The src/ directory contains the main Python scripts which implement the zero-shot and few-shot prompting methods. Each script has comments explaining the functionality of the code.

The notebooks/ directory contains the Jupyter notebooks. These notebooks show the step-by-step process of the implementation, including any experimental results and visualizations.

The data/ directory is where the datasets are stored. Each dataset is in a separate sub-directory.

## Contributing
Feedback and contributions are welcome. If you'd like to suggest changes or improvements, please open an issue or submit a pull request.


## Contact
If you have any questions or comments about this project, please feel free to reach out to me at naif.ganadily@email.com.

I hope this project provides a useful starting point or inspiration for your own explorations of the GPT-3 API and its capabilities. It's a powerful tool with a wide range of applications, and I look forward to seeing what the community will do with it in the future.
