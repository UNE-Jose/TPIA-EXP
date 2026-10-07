# 📅 Actividad 01 (A01): Congruencia de Zeller e Inteligencia Artificial

¡Bienvenido/a a la primera práctica de la asignatura **TPIA**! En esta actividad exploraremos cómo resolver un problema clásico de calendario mediante programación algorítmica y, posteriormente, daremos nuestros primeros pasos en el aprendizaje automático (*Machine Learning*).

---

## 🛠️ Actividad: Congruencia de Zeller en Python

El objetivo de esta sección es desarrollar un script en Python que interactúe con el usuario para calcular el día de la semana correspondiente a una fecha específica.

### 📋 Requisitos de la práctica:
1. **Entradas:** El programa debe solicitar tres valores numéricos por consola:
   * **Día**
   * **Mes**
   * **Año**
2. **Algoritmo:** Debes implementar la fórmula matemática de la **Congruencia de Zeller** para procesar la fecha ingresada en el calendario gregoriano.
3. **Salida:** El programa debe mostrar claramente por pantalla el día de la semana resultante (por ejemplo: *Lunes, Martes, Miércoles...*).

---

## 🤖 Reto: Primera Inteligencia Artificial

¿Puede una máquina "aprender" a calcular el día de la semana basándose en datos, sin aplicarle directamente la fórmula matemática de Zeller? ¡Vamos a comprobarlo!

### 🎯 Objetivo del Reto:
Diseñar y entrenar un modelo de Inteligencia Artificial utilizando Python (con librerías de Machine Learning como `scikit-learn`) que sea capaz de predecir el día de la semana a partir de los datos de entrada (día, mes y año).

### 📋 Pasos orientativos para la ampliación:
1. **Generación o recopilación de datos:** Construye o genera un conjunto de datos (dataset) con múltiples fechas y etiqueta cada una con su respectivo día de la semana correcto.
2. **Definición de Características (*Features*) y Etiquetas (*Labels*):**
   * *Features (X):* `[día, mes, año]`
   * *Labels (Y):* `[día_de_la_semana]`
3. **Entrenamiento:** Entrena un modelo clasificador adecuado para este problema.
4. **Validación:** Evalúa la precisión de tu modelo utilizando datos de prueba que no haya visto durante el entrenamiento.

> 💡 **Nota de entrega:** Asegúrate de que tu código esté debidamente comentado y estructurado dentro de tu carpeta personal de entregas. ¡Mucho éxito!