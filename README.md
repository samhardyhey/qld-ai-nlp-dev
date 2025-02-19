# NLP Fundamentals Workshop 🤖

Workshop materials for QLD AI's NLP Fundamentals session (21.11.19), featuring Trove archive analysis and spaCy demonstrations.

## Features
- 📚 Trove API integration
- 🔍 Text preprocessing
- 📊 NLP analysis with spaCy
- 📈 Performance benchmarking

## Setup
```bash
# Install dependencies
pip install -r requirements.txt

# Download spaCy model
python -m spacy download en_core_web_md
```

## Notebooks
- 📥 `trove_scrape.ipynb`
  - Trove API content retrieval
  - Requires API key from [Trove](https://trove.nla.gov.au/)

- 🔬 `spacy_analysis.ipynb`
  - Document preprocessing
  - NLP analysis
  - Content formatting

- 📊 `spacy_vis_benchmarking.ipynb`
  - Dependency parsing visualization
  - NER output display
  - Pipeline performance analysis

## Structure
- 📓 `notebooks/` # Workshop notebooks
- 📊 `data/` # Sample dataset
- 📑 `slides/` # Presentation materials
- ⚙️ `requirements.txt` # Dependencies

*Note: Trove API key required for data collection notebooks.*