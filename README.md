# ICSPORTS 2025: Can We Really Predict Which Football Players Will Succeed?

This repository contains the code and notebooks used for the ICSPORTS 2025 paper:  
**"Can We Really Predict Which Football Players Will Succeed?"**

## Repository Structure

```
icsports2025/
├── notebooks/
│   ├── soccer.ipynb
│   ├── soccer2.ipynb
│   ├── soccer3.ipynb
│   └── merged_soccer_full_notebook.ipynb
├── figures/
│   └── [your .png files here]
├── data/
│   └── [database.sqlite]
├── paper/
│   └── icsports2025_preprint.pdf
├── environment.yml
├── requirements.txt
├── README.md  
```

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/jonfeld/icsports2025.git
cd icsports2025
```

### 2. Install dependencies

Using pip:

```bash
pip install -r requirements.txt
```

Or using conda (recommended):

```bash
conda env create -f environment.yml
conda activate icsports2025
```

### 3. Add the data

Download `database.sqlite` from the [Kaggle European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer).  
Place the file in the `data/` directory:

```bash
mkdir data
mv /path/to/database.sqlite data/
```

### 4. Run the notebook

```bash
jupyter notebook notebooks/merged_soccer_full_notebook.ipynb
```

This will reproduce the results and visualizations from the paper.

## Notebooks Overview

| Notebook                          | Description                                         |
|----------------------------------|-----------------------------------------------------|
| `soccer.ipynb`                   | Raw feature engineering and exploration             |
| `soccer2.ipynb`                  | Modeling setup and evaluation                       |
| `soccer3.ipynb`                  | SHAP interpretability analysis                      |
| `merged_soccer_full_notebook.ipynb` | Complete notebook|

## Citation

```
@inproceedings{jfeldman2025success,
  author    = {Jonathan Feldman},
  title     = {{Can We Really Predict Which Football Players Will Succeed?}},
  booktitle = {Proceedings of the 13th International Conference on Sport Sciences Research and Technology Support (icSPORTS 2025)},
  year      = {2025},
  month     = {October},
  address   = {Marbella, Spain},
  note      = {Accepted; to be published in SCITEPRESS Digital Library},
}

}
```

## Contact

For questions or issues, contact [jonathan.feldman.2007@gmail.com].

## Acknowledgments

Some code was generated with help from ChatGPT (GPT-4), but all components were carefully reviewed, tested, and modified by the author to ensure accuracy and integrity.

