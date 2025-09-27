# Predicción de Churn de Empleados

**[English Version](README_EN.md)**  

Este proyecto aborda el problema de la **rotación de empleados** (employee churn) mediante modelos de *Machine Learning*.  
El objetivo es predecir qué empleados tienen mayor probabilidad de abandonar la empresa, ayudando así a los equipos de Recursos Humanos a tomar decisiones proactivas.

---

## 📂 Estructura del proyecto
- `notebooks/` → contiene el notebook principal con el análisis paso a paso.  
- `data/` → datasets utilizados (no incluidos en el repo público por privacidad).   

---

## ⚙️ Flujo de trabajo
1. **Exploración e inspección de datos**: estructura, tipos de variables y balance de clases.  
2. **Preprocesado**: escalado de variables numéricas y codificación *one-hot* de variables categóricas.  
3. **Modelado**:  
   - Regresión Logística (modelo base).  
   - Random Forest (modelo comparativo).  
4. **Evaluación**: métricas F1, ROC AUC, PR AUC, matriz de confusión y análisis de umbrales.  
5. **Conclusiones de negocio** (*takeaways*).  

---

## 📊 Resultados destacados
| Modelo              | Precisión | Recall | F1   | ROC AUC | PR AUC |
|---------------------|-----------|--------|------|---------|--------|
| Regresión Logística | 0.51      | 0.81   | 0.62 | 0.83    | 0.48   |
| Random Forest       | 0.99      | 0.98   | 0.98 | 1.00    | 0.99   |

## 🚀 Takeaways
- La **Regresión Logística** ofrece buen equilibrio entre interpretabilidad y rendimiento base.
- **Random Forest** eleva notablemente las métricas (casi perfecto en test).
- ⚠️ Métricas tan altas en RF pueden sugerir **overfitting**. En un caso real:
  - Validar en un conjunto externo/temporal (hold-out o datos recientes).
  - Limitar complejidad (profundidad, `min_samples_*`) y/o usar regularización.
  - Comparar estabilidad con modelos más simples (p. ej., Regresión Logística).
- La elección depende del **trade-off** precisión vs. recall y de la **explicabilidad** requerida por negocio.

---

## 📫 Contacto
- [LinkedIn](https://www.linkedin.com/in/daniel-pacheco-santamaria/)  
- [GitHub](https://github.com/dps1984)
