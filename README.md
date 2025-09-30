# 📚 Book Recommendation System

Project uses NLP and semantic similarity to build a book recommendation system with Gradio UI.

## Structure
- data/ → CSVs, tagged text
- notebooks/ → Jupyter notebooks
- images/ → UI assets
- chroma_db/ → Chroma vector DB (large, ignored)
- models/ → info on required models

## Installation
git clone https://github.com/{GITHUB_USERNAME}/{REPO_NAME}.git
cd {REPO_NAME}
pip install -r requirements.txt

## Usage
Run notebooks in order:
(Create .env with OpenAI key)
(Uncomment cells that create and save files not in repo)
1. data_importing.ipynb
2. text_classification.ipynb
3. semantic_analysis.ipynb
4. gradio_dashboard.ipynb
