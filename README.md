# Predicción de Rotación de Empleados

**[English Version](README.md)**  

Este proyecto aborda el problema de la **rotación de empleados** mediante el uso de modelos de *Machine Learning*.  
El objetivo es predecir qué empleados tienen mayor probabilidad de abandonar la compañía, ayudando a los equipos de RRHH a tomar decisiones proactivas.

---

## 🧠 Contexto de Negocio

La rotación de empleados tiene un impacto directo en la continuidad operativa, el rendimiento de los equipos y los costes de reclutamiento.
Este proyecto explora cómo los insights basados en datos pueden ayudar a los equipos de RRHH a identificar empleados en riesgo de salida de forma temprana y priorizar acciones de retención.

---

## 📂 Estructura del Proyecto
- `notebooks/` → contiene el notebook principal con el análisis paso a paso.  
- `data/` → datasets utilizados (no incluidos en el repositorio público por motivos de privacidad).  

---

## ⚙️ Flujo de Trabajo
1. **Exploración de datos**: estructura, tipos de variables y balance de clases.  
2. **Preprocesado**: escalado de variables numéricas y one-hot encoding de variables categóricas.  
3. **Modelado**:  
   - Regresión Logística (modelo base).  
   - Random Forest (modelo de referencia).  
4. **Evaluación**: F1 score, ROC AUC, PR AUC, matriz de confusión y análisis de umbrales.  
5. **Conclusiones orientadas a negocio**.  

---

## 📊 Resultados Clave
| Modelo              | Precisión | Recall | F1   | ROC AUC | PR AUC |
|---------------------|-----------|--------|------|---------|--------|
| Regresión Logística | 0.51      | 0.81   | 0.62 | 0.83    | 0.48   |
| Random Forest       | 0.99      | 0.98   | 0.98 | 1.00    | 0.99   |

🚀 Conclusiones
- La Regresión Logística proporciona un modelo base sólido e interpretable, adecuado para su discusión con stakeholders.
- Random Forest mejora significativamente el rendimiento predictivo, pero requiere una validación cuidadosa antes de su uso en contextos reales.

⚠️ Consideraciones importantes:
- Métricas tan altas en Random Forest pueden indicar overfitting.
- En un entorno real, los modelos deberían validarse con datos temporales o conjuntos externos.
- La selección del modelo debe equilibrar capacidad predictiva, estabilidad y nivel de explicabilidad, según las necesidades del negocio.

---

## 📫 Contacto
- [LinkedIn](https://www.linkedin.com/in/daniel-pacheco-santamaria/)  
- [GitHub](https://github.com/dps1984)
