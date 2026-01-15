---
layout: default
title: Ejemplo práctico · Regresión lineal (Bloque 1)
---

# Ejemplo práctico: interpretación de una regresión lineal

## Contexto del ejemplo

En este ejemplo se muestra cómo **interpretar los resultados de una regresión lineal simple** a partir del output generado por un programa estadístico de uso libre (**JASP o jamovi**).

El objetivo **no es aprender a ejecutar el análisis**, sino comprender:

- qué pregunta responde el modelo,
- cómo interpretar los coeficientes,
- y qué conclusiones pueden extraerse en un contexto educativo.

---

## Situación de investigación

Supongamos un estudio en el que se analiza la relación entre:

- **Tiempo de estudio semanal** (variable predictora)
- **Rendimiento académico** (variable criterio)

La pregunta de investigación es:

> ¿Existe una relación entre el tiempo de estudio del alumnado y su rendimiento académico?

---

## ¿Cómo se realiza este análisis en JASP o jamovi?

A continuación se describen los **pasos básicos** para realizar una regresión lineal simple utilizando un programa estadístico de uso libre como **JASP** o **jamovi**.

> El objetivo de estos pasos es **familiarizarse con el procedimiento**, no memorizar la interfaz.

### Paso 1. Cargar los datos
- Abrir JASP o jamovi.
- Cargar un archivo de datos (por ejemplo, en formato `.csv` o `.sav`).
- Comprobar que las variables están correctamente identificadas como **numéricas**.

### Paso 2. Acceder al análisis de regresión
- Ir al menú **Regression**.
- Seleccionar **Linear Regression**.

### Paso 3. Definir el modelo
- Arrastrar la variable **Rendimiento académico** al campo *Dependent Variable*.
- Arrastrar la variable **Tiempo de estudio semanal** al campo *Covariates*.

### Paso 4. Ejecutar el análisis
- El programa genera automáticamente el output del modelo.
- No es necesario modificar opciones adicionales en esta fase inicial.

A partir de este punto, el análisis produce una serie de tablas y resultados que deben ser **interpretados**, no simplemente reportados.


---

## Output del análisis (JASP / jamovi)

Tras ejecutar una regresión lineal simple en JASP o jamovi, se obtiene un output que incluye:

- Coeficiente de regresión (B)
- Error estándar
- Valor *t*
- Valor *p*
- Coeficiente de determinación (*R²*)

---

## Claves de interpretación

Al interpretar el output, es importante fijarse en:

- **Signo del coeficiente B**  
  Indica si la relación es positiva o negativa.

- **Magnitud del coeficiente**  
  Informa sobre el cambio esperado en la variable criterio ante una unidad de cambio en el predictor.

- **Valor p asociado al coeficiente**  
  Permite evaluar si la relación observada es compatible con el azar.

- **R²**  
  Indica la proporción de varianza explicada por el modelo.

---

## Conclusión sustantiva

A partir del modelo, el investigador puede formular una conclusión del tipo:

> Un mayor tiempo de estudio semanal se asocia con un mayor rendimiento académico, explicando una proporción moderada de la variabilidad observada.

Esta conclusión debe interpretarse **en términos asociativos**, no causales.

---

## Nota didáctica

En las sesiones prácticas de la asignatura se trabajará con outputs reales generados en JASP o jamovi, reforzando la interpretación de resultados y la lectura crítica de modelos estadísticos.

