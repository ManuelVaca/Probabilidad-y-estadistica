# Diplomado en Técnicas Estadísticas y Minería de Datos
**Universidad Nacional Autónoma de México (UNAM)**
**Facultad de Estudios Superiores Acatlán**  
**Módulo II: Probabilidad y Modelos Estadísticos**  
*Autor: José Manuel Gómez Vaca*

---

## 📌 Descripción del Repositorio

Este repositorio contiene los cuadernos de trabajo (`.ipynb`) desarrollados para el Módulo II del Diplomado en Técnicas Estadísticas y Minería de Datos. 
El objetivo de este módulo es formalizar los fundamentos teóricos de la probabilidad mediante la Teoría de la Medida y profundizar en el modelado estadístico, apoyándose en implementaciones computacionales e intuición práctica a través de **Python**.

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
* **Función generadora de momentos y función característica:** Un poco de la teoría de estas maravillosas funciones y su uso y relación con las transformadas ya conocidad (Laplace y Fourier) 

### 📖 [Notebook 3: Estadística Inferencial, Estimadores y Métodos de Estimación](./03_Estadistica_Inferencial.ipynb)
* **Conceptos Fundamentales:** Distinción formal entre parámetro ($\theta$), estimador ($\hat{\theta}$) como variable aleatoria y estimación puntual como valor numérico.
* **Método de Momentos (MM):** Estimación analítica igualando momentos poblacionales teóricos ($\mathbb{E}[X^k]$) con momentos muestrales empíricos ($m_k$).
* **Estimación por Máxima Verosimilitud (EMV / MLE):** Construcción de la función de verosimilitud $L(\theta)$ y log-verosimilitud $\ell(\theta)$, analizando condiciones de primer y segundo orden.
* **Regularidad y Soporte:** Impacto del soporte de la distribución en la optimización (casos regulares vs. no regulares dependientes del parámetro).
* **Escenarios Analizados:**
  * *Poisson:* Derivación analítica de $\hat{\lambda}_{MM}$ y $\hat{\lambda}_{MLE}$.
  * *Normal:* Estimación simultánea de $(\mu, \sigma^2)$ y análisis del sesgo muestral ($n$ vs. $n-1$).
  * *Uniforme $(0, \theta)$:* Resolución del caso no regular mediante el estadístico de orden máximo $X_{(n)}$.
* **Simulaciones y Métodos Numéricos:** Evaluación del comportamiento asintótico de los estimadores, ajuste numérico con `scipy.optimize` y visualización de distribuciones muestrales en Python.

---

## 🛠️ Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.x
* **Librerías Principales:**
  * `numpy`: Empleado para realizar cálculos numéricos y manejo de arreglos.
  * `scipy`: Funciones de distribución de probabilidad avanzadas (`scipy.stats`).
  * `matplotlib` / `seaborn`: Visualización gráfica de distribuciones y simulaciones.

---

## 🚀 Cómo Ejecutar los Notebooks

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/TU-USUARIO/diplomado-unam-estadistica.git](https://github.com/TU-USUARIO/diplomado-unam-estadistica.git)
   cd diplomado-unam-estadistica