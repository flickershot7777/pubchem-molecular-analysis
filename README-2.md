# YOU check it out on google collob
https://github.com/flickershot7777/pubchem-molecular-analysis.git
# PubChem Molecular Properties Analysis

This repository contains a Jupyter Notebook that analyzes and visualizes molecular properties of selected drug-like compounds obtained from [PubChem](https://pubchem.ncbi.nlm.nih.gov/).

The project focuses on understanding relationships between molecular weight, XLogP (an estimate of LogP), and how these properties influence solvent selection in drug development.

---

## 📚 Dataset

The molecular data is fetched directly from PubChem using PUG REST API:

```
https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/cid/2244,1983,702,6322,5957/property/MolecularWeight,XLogP,InChIKey,CanonicalSMILES/CSV
```

Compounds analyzed:
- Aspirin
- Paracetamol
- Caffeine
- Ibuprofen
- Naproxen

---

## 🛠 Technologies Used

- Python 3.11
- pandas
- matplotlib
- seaborn

---

## 📊 Project Structure

| File | Description |
|:----|:-------------|
| `molecular_property_analysis_pubchem.ipynb` | Jupyter notebook performing full data loading, cleaning, visualization, and analysis |
| `README.md` | Project overview and instructions |

---

## 🔥 Visualizations

- **Scatter Plot**: Molecular Weight vs XLogP colored by compound name
- **Bar Plot**: XLogP value for each compound

---

## 💡 Key Insights

- Molecular weight and lipophilicity (XLogP) vary significantly among the compounds.
- High XLogP values suggest more hydrophobic compounds, guiding solvent selection towards non-polar solvents.
- Low XLogP values suggest higher water solubility, favoring polar solvents.

---

## 🚀 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/flickershot7777/pubchem-molecular-analysis.git
    ```
2. Open the notebook:
    - Launch Jupyter Notebook or Jupyter Lab or google collab(prefered)
    - Open `molecular_property_analysis_pubchem.ipynb`
3. Install dependencies if needed:
    ```bash
    pip install pandas matplotlib seaborn
    ```
4. Run all cells!

Alternatively, open the notebook directly in **Google Colab** for easy execution.

---

## 📌 Author

- **Varun** – Data Science & Python Enthusiast

---


