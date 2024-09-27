

# Personalized Real Estate Agent

**Personalized Real Estate Agent** is an AI-powered application designed to personalize real estate listings based on buyer preferences. By utilizing large language models (LLMs) and vector databases, the system provides tailored property recommendations and generates descriptive summaries for each listing. 

## Features

- **Vector-based Matching:** Uses embeddings to compare buyer preferences against property listings, ensuring accurate matches.
- **Language Model Integration:** Incorporates OpenAI's GPT models to generate personalized descriptions for property listings.
- **RetrievalQA System:** Retrieves relevant property data using a question-answering format, providing a seamless user experience for querying the dataset.
  
## Technologies

- **Python 3.8+**
- **OpenAI GPT-4** for text generation and property description.
- **Langchain** for managing LLMs, embeddings, and retrieval systems.
- **Chroma** for vector storage and similarity search.

## Project Structure

- `HomeMatch.ipynb`: Main Jupyter Notebook containing the code for embeddings, model inference, and querying.
- `requirements.txt`: List of dependencies required to run the project.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/HomeMatch.git
    cd HomeMatch
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook HomeMatch.ipynb
    ```

## Usage

1. **Prepare Buyer Preferences:** Input buyer preferences into the system to generate relevant property matches.
2. **Run the Notebook:** Execute the cells in the Jupyter Notebook to process the listings and generate recommendations.
3. **Query the System:** Use the built-in RetrievalQA chain to ask questions about the listings and receive AI-generated responses.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to the project.
