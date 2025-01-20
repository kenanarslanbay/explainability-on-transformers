# Exploring Explainability of Transformer Models with SHAP

This repository is a step-by-step exploration of using SHAP (SHapley Additive exPlanations) to understand the inner workings of transformer-based models for text classification. The models are sourced from [Hugging Face](https://huggingface.co/), and the primary focus is to evaluate SHAP’s effectiveness in explaining their predictions.

## Objectives

1. **Understand Transformer Models**: Use state-of-the-art transformer-based models from Hugging Face for text classification tasks.
2. **Evaluate SHAP**: Investigate how well SHAP can explain the predictions of these models across different classes.

---

![SHAP Logo](https://shap.readthedocs.io/en/latest/_images/logo.png)

---


#### Why SHAP?
- Provides global and local explanations.
- Visualizes feature importance.
- Supports interpretability even for complex transformer architectures.

---

![SHAP Visualization](https://shap.readthedocs.io/en/latest/_images/force_plot.png)


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

```

## Resources

- [Hugging Face Documentation](https://huggingface.co/docs)
- [SHAP Documentation](https://shap.readthedocs.io/)
- [Transformers GitHub](https://github.com/huggingface/transformers)