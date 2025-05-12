# XAI3 - PDP (Partial Dependence Plots)

Este repositorio contiene la solución al **Ejercicio 5** de la práctica de XAI3: métodos agnósticos de interpretación, específicamente utilizando **Partial Dependence Plots (PDP)**.

## 📂 Contenido del repositorio

| Archivo | Descripción |
|--------|-------------|
| `XAI3.pdf` | Enunciado original del ejercicio. |
| `day.csv` | Dataset de bicicletas por día. |
| `kc_house_data.csv` | Dataset de precios de viviendas. |
| `hour.csv` | Dataset horario de bicicletas (no utilizado directamente). |
| `pdp_bikes.R` | Código para PDP unidimensional y bidimensional usando `day.csv`. *(pendiente de subir)* |
| `pdp_houses.R` | Código para PDP sobre predicción de precios de casas. *(pendiente de subir)* |
| `XAI3_Report.pdf` | Informe con respuestas, gráficos e interpretaciones. *(pendiente de subir)* |

## 🧠 Ejercicios realizados

1. **PDP unidimensional** para las variables:
   - `days_since_2011`, `temp`, `hum`, `windspeed` sobre la predicción de `cnt` (número de bicicletas).

2. **PDP bidimensional** entre `temp` y `hum` para analizar su efecto combinado.

3. **PDP aplicado a precios de vivienda** usando variables como `bedrooms`, `bathrooms`, `sqft_living`, etc.

## 🛠 Herramientas utilizadas

- Lenguaje: `R` (también compatible con Python)
- Librerías: `randomForest`, `pdp`, `ggplot2`, `dplyr`
- Control de versiones: `git` + `GitHub`

## 📌 Autor

- **EDM33**  
  `edmetsinf33@gmail.com`  
<<<<<<< HEAD
  Universidad Politécnica de Valencia (UPV)

---


=======
  Universidad Politécnica de Valencia (UPV)
>>>>>>> b5f2591 (Añadido README.md con descripción del proyecto)
