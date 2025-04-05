# CellPatientNet

CellPatientNet is a prototype under active development that employs a Graph Neural Network (GNN) to predict drug response by integrating multi-omics and clinical data. Our approach builds a comprehensive knowledge graph linking cancer cell lines, drugs, genes, and patients to uncover key biological mechanisms and quantify prediction uncertainty.

---

## Model Development & Training

- **Data Integration:**  
  We merge diverse datasets to construct a heterogeneous knowledge graph, connecting cell lines, genes, and patient data through multi-relational edges.

- **GNN Architecture:**  
  The prototype utilizes a metapath-based attention mechanism with transformer layers, optimized via rigorous hyperparameter tuning to effectively capture critical features and interactions.

- **Uncertainty Quantification:**  
  A Bayesian approach using Monte Carlo Dropout generates predictive means and variance estimates, ensuring robust performance even in the face of distributional shifts. Harmonization techniques further align disparate data sources.

---

## Validation & Evaluation

- **Model Validation:**  
  Our high-level validation strategy evaluates model robustness and clinical relevance through comprehensive performance assessments and fine-tuning protocols.

- **Data Modality Evaluation:**  
  We systematically analyze various molecular data types—both individually and in combination—to determine the most predictive and stable configuration for patient response.

---

## Getting Started

Explore the individual modules for detailed documentation on data preprocessing, model training, uncertainty quantification, and evaluation workflows. For questions or contributions, please open an issue or contact the maintainers.

CellPatientNet is a dynamic prototype that bridges preclinical insights with clinical application, supporting the advancement of precision oncology through robust hypothesis generation and validation.
