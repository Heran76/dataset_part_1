# Predicción del aterrizaje de la primera etapa del Falcon 9 - SpaceX

## Laboratorio 1 – Recolección y limpieza de datos

Proyecto final del curso IBM/Coursera "Applied Data Science Capstone" (actualizado 2025).

### Objetivo
Determinar si la primera etapa del Falcon 9 aterrizará con éxito para estimar el costo de un lanzamiento y ayudar a empresas a competir contra SpaceX.

### Contenido del repositorio
- `01-Data_Collection_and_Cleaning.ipynb` → Notebook completo con:
  - Solicitudes a la API de SpaceX (v4)
  - Limpieza y transformación de datos
  - Enriquecimiento con datos de cohetes, sitios de lanzamiento, cargas útiles y núcleos
  - Imputación de valores faltantes en PayloadMass
  - Exportación del dataset limpio
- `dataset_part_1.csv` → Dataset final con 90 lanzamientos de Falcon 9 (hasta nov-2020)

### Cómo ejecutarlo
```bash
pip install -r requirements.txt
jupyter notebook "01-Data_Collection_and_Cleaning.ipynb"
