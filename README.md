# Reproducibility Guide

This guide provides instructions to reproduce the results and environment for the project "Harmonizing Multi-Omics Heterogeneity via Cross-Modal Attention and Sparse Gating".

## Demo in HuggingFace

[![Deploy on Spaces](https://huggingface.co/datasets/huggingface/badges/resolve/main/deploy-on-spaces-md.svg)](https://huggingface.co/spaces/ZulmanArif-Gani/Multi-Omics-Scanner-Predictive)



## Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ZulmanAG/Omics--Bio-informatika/blob/main/Omics_Bio_informatika(1).ipynb) <!-- IMPORTANT: Replace 'your-username', 'your-repo', and 'your_notebook_name.ipynb' with your actual GitHub repository details and notebook filename -->

**Note:** Please replace `YOUR_GITHUB_REPO_URL/your_notebook_name.ipynb` in the markdown above with the actual path to your notebook on GitHub after uploading it to make the 'Open in Colab' badge functional.

## 1. Environment Setup

To ensure all necessary Python dependencies are installed, we provide a `requirements.txt` file.

### Using pip:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
    cd YOUR_REPOSITORY_NAME
    ```
    (Replace `YOUR_GITHUB_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and repository name.)

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 2. Running the Notebook

Once the environment is set up, you can run the Jupyter Notebook (`your_notebook_name.ipynb`) using JupyterLab or Jupyter Notebook.

1.  **Start Jupyter (if not already running):**
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```

2.  **Open the notebook:** Navigate to `your_notebook_name.ipynb` in your browser and open it. You can then run all cells sequentially to reproduce the analysis and results.


## Citation
Zulman Arif, G. (2026). Harmonizing Multi-Omics Heterogeneity via Cross-Modal Attention and Sparse Gating: A Competition-Driven Hybrid Framework for Predictive Biology. Zenodo. https://doi.org/10.5281/zenodo.18839073



