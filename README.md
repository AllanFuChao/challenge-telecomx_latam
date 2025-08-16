# 📊 Análisis de Churn de Clientes – Telecom X

Este proyecto analiza la evasión de clientes (churn) en la empresa Telecom X, con el objetivo de identificar patrones y factores clave que influyen en la cancelación de servicios. Utilizando Python y técnicas de análisis de datos, se construyó una base sólida para apoyar el desarrollo de modelos predictivos y estrategias de retención.

## 🧱 Estructura del Proyecto

- **Importación y limpieza de datos** desde archivos `.json`
- **Normalización de tablas** y conversión de tipos
- **Construcción del DataFrame `datos_finales`** con las siguientes columnas:
  - `CustomerID`
  - `Gender`
  - `Contract`
  - `PaymentMethod`
  - `MonthlyCharges`
  - `TotalCharges`
  - `Churn`

## 📈 Principales Hallazgos

- **Tasa de churn**: 26.39% de los clientes han cancelado sus servicios.
- **Género**: No hay diferencias significativas en la tasa de churn entre hombres y mujeres.
- **Tipo de contrato**: Los contratos mensuales (`Month-to-month`) presentan la mayor tasa de evasión.
- **Método de pago**: El método `Electronic check` está asociado con una tasa de churn inusualmente alta.
- **Cargos totales**: Los clientes que cancelan tienden a tener cargos totales bajos, lo que sugiere que muchos son nuevos.
- **Cargos mensuales**: Los clientes con cargos más altos tienden a churnear más, posiblemente por percepción de alto costo.

## 💡 Recomendaciones

- Incentivar contratos de largo plazo con beneficios exclusivos.
- Promover métodos de pago automáticos (como tarjeta de crédito o transferencia bancaria).
- Fortalecer el onboarding de nuevos clientes en los primeros meses.
- Implementar campañas de retención para clientes con cargos mensuales altos.
- Monitorear clientes con bajo historial de facturación para detectar señales tempranas de cancelación.

## 🛠 Tecnologías Utilizadas

- Python
- Pandas
- Numpy
- Google Collab
- Diferentes sistemas AI

---

📌 Este análisis proporciona una base sólida para el equipo de Data Science de Telecom X, facilitando la creación de modelos predictivos y estrategias efectivas de fidelización.
