# Análisis de Evasión de Clientes (Churn) — TelecomX

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (*Churn*) en una empresa de telecomunicaciones utilizando técnicas de **Análisis Exploratorio de Datos (EDA)** con Python.

A través del análisis de variables demográficas, contractuales, de servicio y de facturación, se busca identificar patrones y factores asociados a la cancelación del servicio, generando insights que apoyen la toma de decisiones estratégicas orientadas a la **retención de clientes**.

El proyecto fue desarrollado como parte de un desafío técnico y está orientado a demostrar habilidades en:
- Limpieza y preparación de datos
- Análisis exploratorio
- Visualización de datos
- Interpretación de resultados con enfoque de negocio

---

## 📂 Estructura del proyecto

├── TelecomX_Data.json # Dataset original en formato JSON
├── churn_analysis.ipynb # Notebook principal con el análisis completo
├── README.md # Documentación del proyecto

---

## 📊 Dataset

- **Formato:** .ipynb
- **Estructura:** Datos anidados (clientes, servicios, facturación)
- **Registros:** ~7.200 clientes
- **Variable objetivo:** `Churn` (Yes / No)

El dataset contiene información sobre:
- Datos demográficos del cliente
- Tipo de contrato
- Servicios contratados
- Métodos de pago
- Cargos mensuales y totales

---

## ⚙️ Tecnologías y dependencias

El proyecto fue desarrollado utilizando **Python** y las siguientes librerías:

- `pandas`
- `numpy`
- `matplotlib`
- `json`


---
## ▶️ Ejecución del proyecto

1. Clonar o descargar el repositorio.
2. Verificar que Python 3.8 o superior esté instalado.
3. Abrir el archivo `churn_analysis.ipynb` en:
   - Jupyter Notebook
   - Google Colab
4. Ejecutar las celdas en orden para reproducir el análisis completo.

## 🔍 Contenido del análisis

1. Carga de datos  
   - Importación del archivo JSON  
   - Normalización de datos anidados  

2. Limpieza y tratamiento  
   - Corrección de tipos de datos  
   - Manejo de valores nulos e inconsistencias  
   - Creación de variables derivadas  

3. Análisis exploratorio  
   - Distribución de churn  
   - Evasión por variables categóricas  
   - Evasión por variables numéricas  
   - Visualizaciones  

4. Conclusiones e insights  
   - Identificación de perfiles de alto riesgo  

5. Recomendaciones  
   - Estrategias para reducir la evasión

## 📈 Principales hallazgos

- Los contratos *Month-to-month* presentan la mayor tasa de evasión.
- Clientes con cargos mensuales más altos muestran mayor probabilidad de churn.
- La evasión ocurre principalmente en clientes con bajo tiempo de permanencia.
- Métodos de pago no automáticos presentan mayor tasa de cancelación.

## 🛠️ Posibles problemas y soluciones

- **Error al cargar el archivo**  
  Verificar que la ruta sea correcta.

## 🚀 Próximos pasos

- Implementar modelos predictivos de churn.
- Aplicar técnicas de balanceo de clases.
- Evaluar modelos con métricas como recall y F1-score.
- Crear dashboards interactivos para visualización.


