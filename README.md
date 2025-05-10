# 🛒 Detección de Anomalías en Ventas por Sucursal con Isolation Forest

Este proyecto implementa un análisis de detección de anomalías en las ventas diarias de distintas sucursales utilizando el algoritmo de aprendizaje no supervisado **Isolation Forest**. Fue desarrollado como parte de mi portafolio profesional como **Analista de Datos**.

---

## 📌 Objetivo

Identificar días con ventas atípicas (muy altas o muy bajas) por sucursal, para apoyar la toma de decisiones en control de calidad, detección de errores de registro o eventos inusuales (como fraudes o promociones extremas).

---

## 🧠 Técnicas y Herramientas

- Python (pandas, matplotlib, sklearn)
- Machine Learning: **Isolation Forest**
- Estadística: Z-Score, IQR
- Visualización: Series de tiempo con anomalías destacadas
- Exportación de resultados a Excel

---

## 📂 Estructura del Proyecto

```bash
├── ventas_diarias.xlsx           # Dataset simulado con ventas diarias
├── deteccion_anomalias.ipynb     # Notebook de Google Colab con el análisis completo
├── anomalías_detectadas.xlsx     # Exportación de anomalías encontradas
├── README.md                     # Documentación del proyecto

---
🚀 Cómo ejecutar
Clona este repositorio:

git clone https://github.com/tu-usuario/deteccion-anomalias-ventas.git

Sube el archivo ventas_diarias.xlsx al entorno de Google Colab o ejecuta localmente con Jupyter.

Ejecuta el notebook paso a paso.

📈 Resultados
Detección precisa de valores atípicos por sucursal

Visualización clara de picos o caídas inusuales

Modelo sin necesidad de etiquetado previo

Exportación de registros anómalos para revisión externa

👤 Autor
[José Miguel Henríquez Arrau]
Data Analyst | Python | SQL | Power BI
📧 [jose.miguelhen@gmail.com]
🔗 linkedin.com/in/jos%C3%A9-miguel-henr%C3%ADquez-arrau-sociologo-fullstack-web/

🧠 Lecciones aprendidas
Cómo aplicar modelos no supervisados a datos de negocio

Importancia de ajustar modelos por contexto (una sucursal ≠ todas)

Valor de combinar visualización + ML para insights reales

📌 Licencia
Este proyecto es de uso libre con fines educativos y profesionales.
