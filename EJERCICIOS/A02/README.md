# 🗺️ Actividad 02 (A02): Planificador de Rutas a Talleres Cercanos

¡Bienvenido/a a la segunda práctica de la asignatura **TPIA**! En esta actividad desarrollaremos una herramienta geoespacial interactiva en Python que sea capaz de procesar una dirección, encontrar los talleres mecánicos más cercanos y calcular la ruta óptima para llegar a ellos.

---

## 🛠️ Requisitos de la Práctica

El programa debe cumplir con los siguientes pasos lógicos en su ejecución:

1. **Entrada de Usuario:** 
   * Solicitar al usuario una dirección de origen o punto de interés por consola.
2. **Geolocalización:** 
   * Convertir la dirección introducida en coordenadas geográficas (latitud y longitud).
3. **Carga de Datos de Talleres:** 
   * Importar un conjunto de datos desde un archivo `.csv` que contenga la información y ubicación de los talleres disponibles.
4. **Cálculo de Proximidad:** 
   * Procesar las ubicaciones para determinar cuáles son los talleres más cercanos a la dirección ingresada.
5. **Cálculo y Visualización de la Ruta:** 
   * Calcular la ruta más corta hacia el taller seleccionado y generar un mapa interactivo que muestre visualmente el trayecto.

---

## 📚 Librerías Obligatorias a Utilizar

Para resolver este reto, deberás hacer uso de las siguientes librerías de Python:

* **`pandas`**: Para la lectura, manipulación y filtrado de los datos de los talleres almacenados en el archivo CSV.
* **`geopy`**: Para la geolocalización de direcciones y el cálculo de distancias geográficas.
* **`folium`**: Para la generación del mapa interactivo y la representación visual de la ruta y los puntos de interés.
* **`csv`**: Para la gestión de la importación de datos tabulares.

---

## 📋 Estructura Sugerida del Archivo CSV

Tu archivo de datos (`talleres.csv`) debería contar al menos con columnas similares a estas para que el script pueda procesarlo correctamente:

```text
nombre,direccion,latitud,longitud
"Taller Mecánico El Rápido","Calle Mayor 12, Ciudad",40.4168,-3.7038
"Reparaciones Gómez","Avenida de la Paz 45, Ciudad",40.4200,-3.7100