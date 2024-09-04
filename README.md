# <h1 align=center> *Proyecto: FinDataSync* </h1>

---

## Descripción

**FinDataSync** es un proyecto clave implementado en BBVA para automatizar y optimizar la sincronización de datos financieros. Este proyecto se centra en mejorar la velocidad y efectividad del procesamiento de datos, garantizando la entrega rápida de informes significativos y precisos. A través de la utilización de Python y bibliotecas especializadas, FinDataSync maneja grandes volúmenes de información, reduciendo significativamente los tiempos de procesamiento y asegurando la creación de reportes financieros de alta relevancia estratégica.

### Funciones del Script

1. **cambiar_tipo(valor)**
   - *Descripción:* Cambia el tipo de un valor en función de su contenido: si es nulo, numérico o textual.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Clasifica adecuadamente los datos para permitir un procesamiento posterior más efectivo.

2. **crear_niveles(df)**
   - *Descripción:* Crea columnas de niveles en un DataFrame basado en la estructura y jerarquía del contenido.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Permite estructurar jerárquicamente los datos, facilitando análisis que dependen de la jerarquía de la información.

3. **proyecto_eliminar_filas_vacias(df)**
   - *Descripción:* Elimina filas vacías del DataFrame df, asegurando que solo se mantengan las filas con datos válidos.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Limpia el DataFrame de entradas vacías que podrían afectar el análisis y procesamiento posterior.

4. **replicar_niveles_inverso(df)**
   - *Descripción:* Replica y organiza las columnas de nivel en orden inverso, asegurando que los niveles jerárquicos superiores sean procesados adecuadamente.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Reorganiza los datos para asegurar que las jerarquías se mantengan correctamente al procesar los niveles en orden inverso.

5. **eliminar_filas_vacias(df)**
   - *Descripción:* Elimina filas que no contienen datos en ninguna de sus columnas, limpiando el DataFrame.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Mejora la calidad del DataFrame al asegurar que solo las filas con datos útiles sean consideradas para análisis.

6. **obtener_max_nivel(df)**
   - *Descripción:* Calcula el máximo nivel jerárquico presente en un DataFrame para organizar la información según su jerarquía.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Ayuda a determinar la jerarquía máxima en un conjunto de datos, crucial para análisis jerárquicos y estructurales.

7. **replicar_datos(df, columna_base)**
   - *Descripción:* Replica datos en columnas basándose en una columna base, asegurando consistencia en la información replicada.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Garantiza que los datos relacionados estén replicados adecuadamente para mantener la integridad y consistencia de la información.

8. **reemplazar_valores(df, columnas_a_reemplazar, valor_buscar, valor_reemplazo)**
   - *Descripción:* Busca y reemplaza valores específicos en las columnas seleccionadas de un DataFrame, actualizando el DataFrame con los valores nuevos.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Facilita la normalización de datos al reemplazar valores específicos en múltiples columnas, mejorando la consistencia y calidad de los datos.

9. **actualizar_columnas_por_fecha(df, columna_fecha)**
   - *Descripción:* Actualiza las columnas del DataFrame según la columna de fecha especificada, ajustando los datos a las fechas pertinentes.
   - *Tecnologías Utilizadas:* Python, pandas
   - *Impacto:* Asegura que los datos estén alineados temporalmente, lo que es esencial para análisis basados en periodos de tiempo.

10. **calcular_diferencias(df, columna_referencia)**
    - *Descripción:* Calcula las diferencias entre valores en columnas del DataFrame respecto a una columna de referencia, útil para análisis comparativos.
    - *Tecnologías Utilizadas:* Python, pandas
    - *Impacto:* Permite el análisis de variaciones y tendencias al comparar datos con una columna de referencia, mejorando el entendimiento de cambios a lo largo del tiempo.

11. **concatenar_columnas(df, columnas_a_concatenar, nueva_columna)**
    - *Descripción:* Concatenar los valores de las columnas especificadas en una nueva columna del DataFrame.
    - *Tecnologías Utilizadas:* Python, pandas
    - *Impacto:* Combina datos dispersos en diferentes columnas, facilitando su análisis y mejorando la legibilidad del DataFrame.

12. **filtrar_por_condiciones(df, condiciones)**
    - *Descripción:* Filtra el DataFrame según las condiciones especificadas, retornando solo las filas que cumplen con las condiciones.
    - *Tecnologías Utilizadas:* Python, pandas
    - *Impacto:* Permite el enfoque en subconjuntos específicos de datos para análisis más detallados.

13. **generar_resumen(df, columnas_grupo)**
    - *Descripción:* Genera un resumen del DataFrame agrupado por las columnas especificadas, calculando estadísticas como suma, promedio, etc.
    - *Tecnologías Utilizadas:* Python, pandas
    - *Impacto:* Proporciona un resumen rápido de datos clave, facilitando la toma de decisiones informadas.

14. **guardar_a_excel(df, ruta_salida, nombre_hoja="Hoja1")**
    - *Descripción:* Guarda el DataFrame en un archivo Excel en la ruta especificada, permitiendo la personalización del nombre de la hoja.
    - *Tecnologías Utilizadas:* Python, pandas, openpyxl
    - *Impacto:* Facilita la exportación de datos procesados para su posterior análisis o presentación, integrando la salida con herramientas comunes de oficina.

---

## Tecnología Usada

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
- ![OpenPyXL](https://img.shields.io/badge/OpenPyXL-1F4F5E?style=for-the-badge&logo=python&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## Impacto del Proyecto

El proyecto *FinDataSync* tuvo un impacto significativo en BBVA al:

- *Reducir errores:* Mediante la limpieza y normalización de datos, minimizando la posibilidad de errores en los informes.
- *Aumentar la eficiencia:* Automatizando procesos de datos y actualizaciones, reduciendo el tiempo requerido para estas tareas.
- *Disminuir los costos operativos:* Mejorando la precisión y rapidez del análisis de datos, lo que se traduce en una reducción de costos asociados con el manejo manual y la corrección de errores.

<p align="center">
<img src="https://example.com/quantum-dataworks-2.png" alt="Quantum DataWorks">
</p>

---
