# S20 - Módulo 1. Actividad didáctica 2 - M1Simulación Estocástica del Juego Yahtzee mediante el Método de Montecarlo

# Ingeniería de Software y Datos · IU Digital de Antioquia
**Grupo:	25
**Integrantes:	Jose Hilario Lopez / Dennyn Pandales
**Facultad:	Ingeniería y Ciencias Agrícolas
**Programa:	Ingeniería de Software y Datos
**Asignatura:	Simulación - PREICA2602B020045
**Catedràtico: Julian Andres Loaiza
**Fecha de entrega	domingo 25 de Octubre

---

## Descripción del Proyecto
Este proyecto implementa una simulación numérica basada en el **Método de Montecarlo** para modelar el juego de dados clásico **Yahtzee** entre 2 jugadores. A través de 5,000 ejecuciones automáticas (130,000 turnos evaluados), se analiza la convergencia de las puntuaciones medias, la variabilidad estocástica y la probabilidad empírica de lograr combinaciones de alta complejidad como la categoría *Yahtzee*.

---

## Estructura del Repositorio
* `S20_Módulo_1_Actividad_didáctica_2_M1.ipynb`: Cuaderno interactivo de Google Colab con la lógica del juego, motor de Montecarlo, traza de intentos e histogramas/boxplots.
* `README.md`: Documentación formal del repositorio.

---

## Tecnologías Utilizadas
* **Lenguaje:** Python 3
* **Entorno:** Google Colab
* **Librerías principales:**
  * `random`: Generación de distribuciones discretas uniformes $P(X=k) = 1/6$.
  * `numpy` & `pandas`: Análisis numérico, agregación de métricas y tablas de traza.
  * `matplotlib` & `seaborn`: Visualización gráfica de distribuciones de densidad (KDE) y diagramas de caja.

---

## Instrucciones de Ejecución
1. Abrir el cuaderno de Jupyter / Colab en la plataforma [Google Colab](https://colab.research.google.com/).
2. Cargar o importar el archivo `S20_Módulo_1_Actividad_didáctica_2_M1.ipynb`.
3. Ejecutar todas las celdas secuencialmente (`Shift + Enter` o usando el menú *Entorno de ejecución > Ejecutar todo*).

---

## Resultados Principales
* **Puntaje Promedio General:** ~156.61 puntos ($\sigma \approx 39.25$).
* **Probabilidad Empírica de Yahtzee:** ~41.30% en una partida completa de 13 turnos mediante la estrategia de retención por frecuencias.
