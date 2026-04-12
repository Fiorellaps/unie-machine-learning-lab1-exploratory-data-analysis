[![UNIE Universidad](https://www.fsie.es/documentos/imagenes/Ventajas_afiliados/2024/UNIE/Brand_Unie_Vertical_Positive.png)](https://www.universidadunie.com/programas/master-formacion-permanente-virtual-inteligencia-artificial-deep-learning)

# Máster en Inteligencia Artificial y Deep Learning

## Machine Learning — Topic 1: Exploratory Data Analysis

Asignatura Machine Learning del Máster en IA y Deep Learning de UNIE. Practical Lab 1: Introduction to Exploratory Data Analysis

---

## Summary

Introductory notebooks covering the core Python libraries used in Exploratory Data Analysis: NumPy, Pandas, Matplotlib and Scikit-learn. Each topic includes a hands-on notebook and a solved version.

## Project Structure

```
datasets/
└── iris.csv                           # Iris dataset
src/
├── introduction_numpy.ipynb           # NumPy exercises
├── introduction_numpy_solved.ipynb    # NumPy solved
├── introduction_pandas.ipynb          # Pandas exercises
├── introduction_pandas_solved.ipynb   # Pandas solved
├── introduction_matplotlib.ipynb      # Matplotlib exercises
├── introduction_matplotlib_solved.ipynb  # Matplotlib solved
└── introduction_sklearn.ipynb         # Scikit-learn introduction
```

## Quick Start

```bash
# Create and activate environment
python3 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook src/introduction_numpy.ipynb
```

---

## Disclaimer

Provided as is, for academic use only.

## Copyright and License

© 2026 Isabel Bejerano-Blazquez

- Notebooks: [MIT License](LICENSE)
- Data: [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

Developed and tested on Python ≥ 3.12. Dependencies: see `requirements.txt`.
