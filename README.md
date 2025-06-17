# Análisis de Evasión de Clientes (Churn) en TelecomX

## 📌 Propósito del Análisis

El objetivo de este proyecto es analizar los factores que influyen en la evasión de clientes (churn) en la empresa TelecomX. El churn representa la pérdida de clientes, un problema crítico para las empresas de telecomunicaciones. Mediante el análisis exploratorio de datos, se identifican patrones y variables asociadas al churn, permitiendo diseñar estrategias efectivas para reducir la fuga de clientes y mejorar la rentabilidad.

---

## 📁 Estructura del Proyecto

- **Telecom_X2 (1).ipynb**: Notebook principal con todo el análisis, visualizaciones y conclusiones.
- **telecom_x.py**: Script Python con lógica similar al notebook, útil para automatizar el análisis o reutilizar funciones.
- **Otros archivos**: Hay otros notebooks y documentos en la carpeta, pero el análisis principal está en `Telecom_X2 (1).ipynb`.

---

## 📊 Ejemplos de Gráficos e Insights Obtenidos

### Ejemplos de Gráficos:
- **Distribución de Churn**: Gráficos de barras y pastel que muestran la proporción de clientes que han abandonado la empresa.
- **Churn por Variables Categóricas**: Gráficos de barras segmentados por género, tipo de contrato, servicios contratados, método de pago, etc.
- **Churn por Variables Numéricas**: Boxplots e histogramas que comparan la antigüedad del cliente, cargos mensuales y totales entre clientes que permanecen y los que se van.
- **Matriz de Correlación**: Heatmap que muestra la relación entre variables numéricas y el churn.
- **Servicios Contratados vs. Churn**: Gráficos que relacionan la cantidad de servicios adicionales y el gasto diario con la probabilidad de churn.

### Insights Clave:
- Los clientes con menor antigüedad y cargos mensuales más altos tienden a abandonar más.
- Los contratos mensuales presentan una tasa de churn significativamente mayor que los contratos a largo plazo.
- La ausencia de servicios adicionales (seguridad, respaldo, soporte técnico) está asociada a una mayor evasión.
- Los clientes con menos servicios contratados y mayor gasto diario presentan mayor tasa de churn.

---

## ▶️ Instrucciones para Ejecutar el Notebook

1. **Requisitos previos**:
   - Tener instalado Python 3.x.
   - Instalar las siguientes librerías si no las tienes:
     ```bash
     pip install pandas numpy matplotlib seaborn requests
     ```

2. **Abrir el notebook**:
   - Puedes abrir `Telecom_X2 (1).ipynb` con Jupyter Notebook, JupyterLab, Google Colab o VSCode.

3. **Ejecutar las celdas**:
   - Ejecuta cada celda en orden. El notebook descarga automáticamente los datos desde GitHub y realiza todo el análisis paso a paso.

4. **Explora los resultados**:
   - Observa los gráficos y lee los insights y recomendaciones al final del notebook.

---

## 📬 Contacto

Para dudas o sugerencias, puedes contactar al autor del proyecto. 