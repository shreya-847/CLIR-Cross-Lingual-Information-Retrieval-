# CLIR-Cross-Lingual-Information-Retrieval

This is a group project by **Shreya Sindhu Tumuluru**, **SG Navya**, and **Riddhi Rai**.

Demonstrates a Cross-Lingual Information Retrieval (CLIR) system using **LLaMA**, **BERT**, and **Latent Semantic Analysis (LSA)** models. Each model is used separately for a comparative study to evaluate their effectiveness in retrieving relevant information across different languages.

## Features
- **Multilingual Data Processing**: Preprocess text data in multiple languages.
- **Model Training**: Train and fine-tune LLaMA, BERT, and LSA models.
- **Comparative Evaluation**: Compare the performance of different models in information retrieval tasks.

## Files
- **`BERT.ipynb`**: Trains and fine-tunes the BERT model for cross-lingual information retrieval.
- **`LSA.ipynb`**: Trains and fine-tunes the LSA model for cross-lingual information retrieval.
- **`Llama2.ipynb`**: Trains and fine-tunes the LLaMA model for cross-lingual information retrieval. Utilizes the Pinecone vector database for efficient retrieval.

## Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/shreya-847/CLIR-Cross-Lingual-Information-Retrieval.git
    cd CLIR-Cross-Lingual-Information-Retrieval
    ```

2. **Set up the environment**:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Run the Notebooks**:
    - Open `BERT.ipynb` in Jupyter Notebook and run all cells to train and evaluate the BERT model.
    - Open `LSA.ipynb` in Jupyter Notebook and run all cells to train and evaluate the LSA model.
    - Open `Llama2.ipynb` in Jupyter Notebook and run all cells to train and evaluate the LLaMA model.

2. **Evaluate Models**:
    Perform information retrieval and evaluate the performance of each model based on the outputs provided in the notebooks.

## Notes
- The LLaMA model utilizes the Pinecone vector database for efficient retrieval.
- Ensure that you have the necessary data files and dependencies before running the notebooks.

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to add new features, please open an issue or submit a pull request.

## Acknowledgements
Special thanks to the developers and researchers behind LLaMA, BERT, and LSA models for their foundational work. We also appreciate the open-source community for their valuable resources and support.
