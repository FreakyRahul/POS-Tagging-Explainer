### POS Tagging Explainer

This repository contains code for a simple Python application that performs Part-of-Speech (POS) tagging using the spaCy library. POS tagging is a fundamental task in natural language processing that assigns a grammatical category (such as noun, verb, adjective, etc.) to each word in a sentence.

### Functionality

The application provides a simple interface where users can input a sentence, and it will return a table containing each token in the sentence along with its corresponding POS tag and an explanation of the tag.

### Usage

To use the application:

1. Ensure you have Python installed on your system.
2. Install the required libraries by running the following commands:

```bash
pip install -U spacy
python -m spacy download en_core_web_sm
pip install gradio
```

3. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/POS-Tagging-Explainer.git
```

4. Navigate to the cloned directory:

```bash
cd POS-Tagging-Explainer
```

5. Run the application:

```bash
python app.py
```

6. Once the application is running, enter a sentence in the provided text box and press Enter. The application will display a table showing the POS tags for each token in the sentence along with explanations.
   
### Acknowledgments

Special thanks to spaCy and Gradio for providing powerful tools that make natural language processing accessible to everyone.
