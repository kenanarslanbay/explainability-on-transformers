# Exploring Explainability of Transformer Models with SHAP

This repository is a step-by-step exploration of using SHAP (SHapley Additive exPlanations) to understand the inner workings of transformer-based models for text classification. The models are sourced from [Hugging Face](https://huggingface.co/), and the primary focus is to evaluate SHAP’s effectiveness in explaining their predictions.

---

![SHAP Logo](https://user-images.githubusercontent.com/38404461/65588818-7734b500-df88-11e9-907c-a0bc0c0fdfc1.png)


#### Why SHAP?
- Provides global and local explanations.
- Visualizes feature importance.
- Supports interpretability even for complex transformer architectures.

## Installation and Usage

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Transformers
- SHAP

### Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/transformer-shap-exploration.git
   cd transformer-shap-exploration
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook
   ```
4. Follow the step-by-step workflow in the notebook.

## Resources

- [Hugging Face Documentation](https://huggingface.co/docs)
- [SHAP Documentation](https://shap.readthedocs.io/)
- [Transformers GitHub](https://github.com/huggingface/transformers)