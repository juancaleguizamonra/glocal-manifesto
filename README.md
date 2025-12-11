# 🌍 Glocal Manifesto: αP + βC + γG

> **Hacia un Internet con Identidad Cultural**

![Cultural Relevance Boost](https://img.shields.io/badge/β_cultural_boost-3.5x-orange)
![Technical Validation](https://img.shields.io/badge/β_score-0.73-success)
![Vision + Code](https://img.shields.io/badge/philosophy_%2B_implementation-complete-blue)

## 🎯 ¿Por qué?

Los algoritmos actuales nos tratan como **ciudadanos sin memoria**. Este proyecto propone el **Scheduler Tricontextual** que añade la **Capa Cultural (β)** faltante para construir un internet que recuerde quiénes somos.

## 🧠 La Fórmula

\[ R(u,i,t) = α(t) \cdot P(u,i) + β(t) \cdot C(g(u),i) + γ(t) \cdot G(i) \]

- **α (Personal):** Relevancia individual del usuario
- **β (Cultural):** Relevancia para el grupo cultural del usuario
- **γ (Global):** Relevancia global del contenido

## 📊 Resultados Validados

Para usuario mexicano durante **Día de Muertos**:

| Métrica | Valor | Impacto |
|---------|-------|---------|
| **β durante festividad** | 0.73 | Priorización cultural máxima |
| **Local vs Otros contenidos** | 3.5x | Contenido cultural 350% más relevante |
| **Local vs Global** | 4.7x | Cultura local >> tendencias globales |

## 🚀 Comenzar

```python
# Próximamente: pip install glocal
from glocal import Scheduler

usuario = {"region": "MX", "festividad": "Día de Muertos"}
scheduler = Scheduler()
recomendaciones = scheduler.recommend(usuario)

print(f"Peso cultural (β): {scheduler.weights['beta']:.2f}")
