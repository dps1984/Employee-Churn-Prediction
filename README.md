# Predicción de Churn de Empleados

**[English Version](README_EN.md)**  

Este proyecto aborda el problema de la **rotación de empleados** (employee churn) mediante modelos de *Machine Learning*.  
El objetivo es predecir qué empleados tienen mayor probabilidad de abandonar la empresa, ayudando así a los equipos de Recursos Humanos a tomar decisiones proactivas.

---

## 📂 Estructura del proyecto
- `notebooks/` → contiene el notebook principal con el análisis paso a paso.  
- `data/` → datasets utilizados (no incluidos en el repo público por privacidad).  
- `output/` → resultados y gráficas generadas.  

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

---

## 🚀 Takeaways
- El modelo de **Regresión Logística** ofrece un buen equilibrio entre interpretabilidad y desempeño inicial.  
- **Random Forest** mejora notablemente las métricas, mostrando casi un rendimiento perfecto en test.  
- En un escenario real, la elección dependería del compromiso entre **precisión**, **recall** y la necesidad de **explicabilidad** frente a complejidad del modelo.  

---

## 📫 Contacto
- [LinkedIn](https://www.linkedin.com/in/daniel-pacheco-santamaria/)  
- [GitHub](https://github.com/dps1984)
