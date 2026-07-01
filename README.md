# Predicción de Heladas Meteorológicas en el Perú

Pipeline de minería de datos para clasificación binaria de heladas usando
Random Forest, desarrollado para el curso Minería de Datos (CC442),
Universidad Nacional de Ingeniería.

## Dataset
Público: `abadpomamaquera/meteorological-data-for-frost-prediction-in-peru`
(Kaggle). 1,672,827 observaciones × 18 variables. El CSV (301 MB) no se
incluye en el repositorio; se descarga automáticamente vía `kagglehub`.

## Reproducibilidad
Semilla global fijada (SEED=42) en Python, NumPy y PYTHONHASHSEED.
Ejecución en CPU con scikit-learn.

## Instalación
​```bash
pip install -r requirements.txt
​```

## Uso
Abrir `notebooks/PC5_Mineria_De_Datos.ipynb` en Google Colab o Jupyter.

## Resultados principales
| Métrica | Valor |
|---------|-------|
| Recall (helada) | 92.34% |
| ROC-AUC | 0.9690 |
| Cohen's Kappa | 0.6710 |
| F1-Macro (test) | 0.8338 |