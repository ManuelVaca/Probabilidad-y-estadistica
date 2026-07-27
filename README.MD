# Diplomado en Técnicas Estadísticas y Minería de Datos
**Universidad Nacional Autónoma de México (UNAM)**
** Facultad de Estudios Superiores Acatlán**  
**Módulo II: Probabilidad y Modelos Estadísticos**  
*Autor: José Manuel Gómez Vaca*

---

## 📌 Descripción del Repositorio

Este repositorio contiene los cuadernos de trabajo (`.ipynb`) desarrollados para el Módulo II del Diplomado en Técnicas Estadísticas y Minería de Datos. El objetivo de este módulo es formalizar los fundamentos teóricos de la probabilidad mediante la Teoría de la Medida y profundizar en el modelado estadístico, apoyándose en implementaciones computacionales e intuición práctica a través de **Python**.

---

## 📂 Contenido del Módulo

### 📖 [Notebook 1: Axiomas de Kolmogorov y Teoría de la Medida](./01_Axiomas_Kolmogorov.ipynb)
* **Fundamentos Teóricos:** Espacio muestral ($\Omega$), $\sigma$-álgebras ($\mathcal{F}$) y la medida de probabilidad ($P$).
* **Axiomática de Kolmogorov:** Formalización rigurosa de los tres axiomas fundamentales y sus propiedades derivadas.
* **Espacios de Probabilidad:** Estructura del triplete $(\Omega, \mathcal{F}, P)$.
* **Simulaciones en Python:** Validación empírica de la Ley de los Grandes Números mediante experimentos de Monte Carlo.

### 📖 [Notebook 2: Variables Aleatorias, Funciones de Distribución y Momentos](./02_Variables_Aleatorias_y_Momentos.ipynb)
* **Concepto Formal:** Definición de Variable Aleatoria (V.A.) como función medible $X: \Omega \to \mathbb{R}$.
* **Tipos de Variables:** 
  * Variables Aleatorias Discretas y Función de Masa de Probabilidad (FMP).
  * Variables Aleatorias Continuas y Función de Densidad de Probabilidad (FDP).
* **Función de Distribución Acumulada (FDA):** Propiedades unificadas y relación con la FDP.
* **Momentos y Operadores:** Esperanza Matemática $\mathbb{E}[X]$, Varianza $\text{Var}(X)$, momentos crudos y momentos centrales.
* **Simulaciones en Python:** Generación y comparación de distribuciones teóricas vs. empíricas (Poisson y Normal) utilizando `numpy`, `scipy.stats` y `matplotlib`.

### 📖 Notebook 3: [Próximamente]
* *Tema en desarrollo...*

---

## 🛠️ Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.x
* **Librerías Principales:**
  * `numpy`: Cálculos numéricos y manejo de arreglos.
  * `scipy`: Funciones de distribución de probabilidad avanzadas (`scipy.stats`).
  * `matplotlib` / `seaborn`: Visualización gráfica de distribuciones y simulaciones.

---

## 🚀 Cómo Ejecutar los Notebooks

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/TU-USUARIO/diplomado-unam-estadistica.git](https://github.com/TU-USUARIO/diplomado-unam-estadistica.git)
   cd diplomado-unam-estadistica