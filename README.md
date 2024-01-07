## EcoPredict Project
<img width="320" alt="image" src="https://github.com/BaharChidem/EcoPredict/assets/114008903/5b41ba45-5202-49c0-9960-ec2ef9f3e236">

## Overview
Ecopredict Empowering the Circular Economic ideas through AI.
The Circular Economic Conundrum: From Data to Decisions
It addresses this by evaluating and surfacing the most promising solutions, aiding in the transition to a sustainable, circular economy.It harnesses the power of AI to analyze and assess sustainability initiatives. Built on a BERT-based machine learning framework, it effectively processes environmental text data, categorizing  solutions and estimating their potential impact. EcoPredict is a valuable asset for decision-makers in the circular economy, offering data-driven insights to prioritize and quickly identify promising  ideas.


## Prerequisites
Ensure the following libraries are installed in your Jupyter environment:
- TensorFlow
- Hugging Face Transformers
- Scikit-learn
- Pandas

You can install these directly in a notebook cell:
```python
!pip install tensorflow transformers scikit-learn pandas
```

Dataset
Place your CSV dataset in an accessible directory. Update the file_path in the notebook to point to your dataset file.
- **Running the Notebook**
  - **Dataset Loading**: Set `file_path` to the location of your dataset.
  - **Preprocessing**: The script processes and encodes the text data.
  - **Data Splitting**: Divides the data into training and testing sets.
  - **Tokenization**: Uses the BERT tokenizer for data processing.
  - **TensorFlow Dataset Conversion**: Converts data for TensorFlow compatibility.
  - **BERT Model Setup**: Includes loading, compiling, training, and evaluating the model.


Execution
Run each cell in the Jupyter Notebook sequentially after setting up the dataset and installing the dependencies.

Developed by Bahar and Vaibhav
