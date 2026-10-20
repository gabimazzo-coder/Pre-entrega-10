# Predicción de Churn de Clientes - Modelado y Métricas

Este proyecto implementa un flujo de trabajo básico de Machine Learning para predecir la pérdida de clientes (**Churn**) utilizando Python y Scikit-Learn.

## 🚀 Cómo ejecutar el proyecto

1. **Clonar el repositorio:**
   ```bash
   git clone <URL_DE_TU_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
   ```

2. **Crear y activar un entorno virtual (Recomendado):**
   ```bash
   python -m venv venv
   # En Windows:
   venv\Scripts\activate
   # En Mac/Linux:
   source venv/bin/activate
   ```

3. **Instalar las dependencias necesarias:**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

4. **Abrir y ejecutar el Notebook:**
   ```bash
   jupyter notebook modelado_metricas.ipynb
   ```
   Ejecuta todas las celdas secuencialmente para entrenar el modelo y visualizar los resultados.

## 📊 Resumen de Resultados

* **Modelo utilizado:** Random Forest Classifier.
* **División de datos:** 80% entrenamiento, 20% prueba.
* **Conclusión de negocio:** Tras evaluar el rendimiento mediante la matriz de confusión, se determinó que **Recall** es la métrica de negocio fundamental. Maximizar el Recall mitiga el costo crítico de los falsos negativos (clientes propensos a abandonar el servicio que no son detectados a tiempo).
