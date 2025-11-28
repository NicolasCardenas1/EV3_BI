**Objetivo:** Integrar y comparar modelos de Machine Learning sobre sismicidad en Chile, utilizando el mismo dataset `seismic_data.csv` (CSN/Chile) de las evaluaciones anteriores. En `EV3_BI.ipynb` se aplican y documentan: regresión (comparando modelos lineal y basado en árboles), clasificación (árbol lógico y modelo híbrido Random Forest) y clustering jerárquico, junto con la redacción del estudio según el método científico.

**Ejecución:** Clonar el repositorio `EV3_BI`, verificar que el archivo `data/seismic_data.csv` esté en la carpeta `data/`, abrir `EV3_BI.ipynb` y ejecutar *Run All* seleccionando el entorno `.venv` con **Python 3.12.10**.  
En caso de que falten dependencias:

- **Opción A (recomendada):** en la terminal, crear el entorno virtual:
 `python -m venv .venv`  
  `.\.venv\Scripts\Activate.ps1` (PowerShell)  

  y luego `python -m pip install -r requirements.txt`.

Luego, en "Select Kernel", seleccionar `.venv` con **Python 3.12.10** 

**Dependencias y versión de Python:** ver `requirements.txt` (pandas, numpy, matplotlib, seaborn, scikit-learn, nbformat, ipykernel, jupyter); probado en **Python 3.12.10**.  
El notebook carga el dataset desde `data/`, guarda las figuras en `figuras/` y fija semillas (`random_state=42`) para favorecer la reproducibilidad entre distintos equipos.
