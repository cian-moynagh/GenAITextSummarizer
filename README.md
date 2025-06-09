# GenAITextSummarizer

This project provides an example implementation of an **Intelligent Document Summarizer** supporting extractive and abstractive methods. It preserves diverse viewpoints in business documents such as reports, articles and emails.

## Setup
1. Create a virtual environment (optional).
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter and open `Intelligent_Document_Summarizer.ipynb`.

## Sample Data
Example documents are located in the `sample_data` folder. Feel free to replace them with your own text files.

## Usage
Run the notebook cells to generate summaries. The notebook demonstrates:
- Extractive summarization using LexRank
- Abstractive summarization with a transformer model
- Viewpoint preservation and evaluation metrics
- Length-controlled summaries for different audiences

## Guidelines
See `GUIDELINES.md` for recommendations on creating fair and balanced summaries. The `templates` folder contains a basic template for inclusive summarization.
