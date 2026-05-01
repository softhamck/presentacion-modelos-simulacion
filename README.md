# Presentación web - Taller 2: Modelos y Simulación

Presentación web interactiva desarrollada para el **Taller 2 de Modelos y Simulación**.
El proyecto presenta la construcción de un modelo basado en **método Delphi, lógica difusa, simulación Montecarlo y modelos de regresión**, aplicado al análisis del rendimiento físico a partir de variables relacionadas con el sueño y la actividad física.

La presentación está construida en HTML usando **Reveal.js**, lo que permite visualizarla como diapositivas directamente desde el navegador.


## Controles de la presentación

La presentación funciona como diapositivas web.

Flecha derecha  → Siguiente diapositiva
Flecha izquierda → Diapositiva anterior
F               → Pantalla completa
ESC             → Vista general de diapositivas

---

## Tema del proyecto

El trabajo analiza la relación entre la **calidad del sueño** y el **nivel de actividad física o entrenamiento**, utilizando un sistema de inferencia difuso tipo Mamdani.

El modelo busca estimar un **rendimiento físico estimado** a partir de variables como:

- Horas de sueño.
- Eficiencia del sueño.
- Pasos diarios.
- Minutos de actividad intensa.

---

## Partes del trabajo

### Parte A: Aplicación del método Delphi

Se aplica el método Delphi a un grupo de expertos para identificar, priorizar y validar las variables más importantes del modelo.

Incluye:

- Ronda 1: exploración de factores relacionados con sueño, actividad física y rendimiento.
- Ronda 2: priorización de variables mediante escala de valoración.
- Ronda 3: validación final de variables, rangos, etiquetas lingüísticas y reglas difusas.

---

### Parte B: Construcción del sistema de inferencia difuso

Con las variables aprobadas por consenso, se construye un sistema de inferencia difuso tipo **Mamdani**.

Incluye:

- Variables de entrada.
- Variable de salida.
- Etiquetas lingüísticas.
- Funciones de pertenencia triangulares.
- Reglas difusas tipo `SI... ENTONCES...`.

---

### Parte C: Simulación Montecarlo

Después de construir el sistema difuso, se generan escenarios aleatorios para las variables de entrada.

Incluye:

- Generación de mínimo 1.000 simulaciones.
- Evaluación de cada escenario en el sistema difuso.
- Análisis estadístico de los resultados.
- Visualización de tendencias del rendimiento físico estimado.

---

### Parte D: Integración de regresión

Se construyen modelos predictivos usando la base generada por la simulación Montecarlo.

Incluye:

- K-NN Regression.
- Random Forest.
- Árbol de Decisión.
- Regresión Lineal.
- Evaluación mediante MAE, RMSE y R².
- Interpretación de variables con mayor influencia.

---

## Estructura del proyecto

```text
presentacion-modelos-simulacion/
│
├── index.html
├── page_1.html
├── page_2.html
├── page_3.html
├── page_4.html
├── page_5.html
├── page_6.html
├── page_7.html
├── page_8.html
└── README.md
```
