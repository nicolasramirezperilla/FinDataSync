# <h1 align=center> *Proyecto: FinDataSync* </h1>

---

## <h2 align=center> Descripción </h2>

**FinDataSync** es un proyecto clave implementado en BBVA para automatizar y optimizar la sincronización de datos financieros. Este proyecto se centra en mejorar la velocidad y efectividad del procesamiento de datos, garantizando la entrega rápida de informes significativos y precisos. A través de la utilización de Python y bibliotecas especializadas, FinDataSync maneja grandes volúmenes de información, reduciendo significativamente los tiempos de procesamiento y asegurando la creación de reportes financieros de alta relevancia estratégica.

## <h2 align=center> Funciones del Script </h2>

- **cambiar_tipo(valor)**  
  *Descripción:* Cambia el tipo de un valor en función de su contenido: si es nulo, numérico o textual.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Clasifica adecuadamente los datos para permitir un procesamiento posterior más efectivo.

- **crear_niveles(df)**  
  *Descripción:* Crea columnas de niveles en un DataFrame basado en la estructura y jerarquía del contenido.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Permite estructurar jerárquicamente los datos, facilitando análisis que dependen de la jerarquía de la información.

- **proyecto_eliminar_filas_vacias(df)**  
  *Descripción:* Elimina filas vacías del DataFrame df, asegurando que solo se mantengan las filas con datos válidos.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Limpia el DataFrame de entradas vacías que podrían afectar el análisis y procesamiento posterior.

- **replicar_niveles_inverso(df)**  
  *Descripción:* Replica y organiza las columnas de nivel en orden inverso, asegurando que los niveles jerárquicos superiores sean procesados adecuadamente.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Reorganiza los datos para asegurar que las jerarquías se mantengan correctamente al procesar los niveles en orden inverso.

- **eliminar_filas_vacias(df)**  
  *Descripción:* Elimina filas que no contienen datos en ninguna de sus columnas, limpiando el DataFrame.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Mejora la calidad del DataFrame al asegurar que solo las filas con datos útiles sean consideradas para análisis.

- **obtener_max_nivel(df)**  
  *Descripción:* Calcula el máximo nivel jerárquico presente en un DataFrame para organizar la información según su jerarquía.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Ayuda a determinar la jerarquía máxima en un conjunto de datos, crucial para análisis jerárquicos y estructurales.

- **replicar_datos(df, columna_base)**  
  *Descripción:* Replica datos en columnas basándose en una columna base, asegurando consistencia en la información replicada.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Garantiza que los datos relacionados estén replicados adecuadamente para mantener la integridad y consistencia de la información.

- **reemplazar_valores(df, columnas_a_reemplazar, valor_buscar, valor_reemplazo)**  
  *Descripción:* Busca y reemplaza valores específicos en las columnas seleccionadas de un DataFrame, actualizando el DataFrame con los valores nuevos.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Facilita la normalización de datos al reemplazar valores específicos en múltiples columnas, mejorando la consistencia y calidad de los datos.

- **actualizar_columnas_por_fecha(df, columna_fecha)**  
  *Descripción:* Actualiza las columnas del DataFrame según la columna de fecha especificada, ajustando los datos a las fechas pertinentes.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Asegura que los datos estén alineados temporalmente, lo que es esencial para análisis basados en periodos de tiempo.

- **calcular_diferencias(df, columna_referencia)**  
  *Descripción:* Calcula las diferencias entre valores en columnas del DataFrame respecto a una columna de referencia, útil para análisis comparativos.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Permite el análisis de variaciones y tendencias al comparar datos con una columna de referencia, mejorando el entendimiento de cambios a lo largo del tiempo.

- **concatenar_columnas(df, columnas_a_concatenar, nueva_columna)**  
  *Descripción:* Concatenar los valores de las columnas especificadas en una nueva columna del DataFrame.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Combina datos dispersos en diferentes columnas, facilitando su análisis y mejorando la legibilidad del DataFrame.

- **filtrar_por_condiciones(df, condiciones)**  
  *Descripción:* Filtra el DataFrame según las condiciones especificadas, retornando solo las filas que cumplen con las condiciones.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Permite el enfoque en subconjuntos específicos de datos para análisis más detallados.

- **generar_resumen(df, columnas_grupo)**  
  *Descripción:* Genera un resumen del DataFrame agrupado por las columnas especificadas, calculando estadísticas como suma, promedio, etc.  
  *Tecnologías Utilizadas:* Python, pandas  
  *Impacto:* Proporciona un resumen rápido de datos clave, facilitando la toma de decisiones informadas.

- **guardar_a_excel(df, ruta_salida, nombre_hoja="Hoja1")**  
  *Descripción:* Guarda el DataFrame en un archivo Excel en la ruta especificada, permitiendo la personalización del nombre de la hoja.  
  *Tecnologías Utilizadas:* Python, pandas, openpyxl  
  *Impacto:* Facilita la exportación de datos procesados para su posterior análisis o presentación, integrando la salida con herramientas comunes de oficina.

## <h2 align=center> Tecnología Usada </h2>

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
- ![OpenPyXL](https://img.shields.io/badge/OpenPyXL-1F4F5E?style=for-the-badge&logo=python&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## <h2 align=center> Desafíos y Problemas </h2>

- Sincronización en la nube.
- Funciones en Google Colab.
- Formatos inconclusos.
- Parámetros rústicos.
- Limitaciones de uso.

## <h2 align=center> Medición del Éxito </h2>

- **KPIs**: Precisión de los informes financieros, eficiencia en el procesamiento de datos, y capacidad de manejo de transacciones simultáneas.
- **Resultados**: El sistema manejó hasta 10,000 transacciones simultáneas sin degradación del rendimiento.

## <h2 align=center> Equipo del Proyecto </h2>

- **Nicolás Ramírez Perilla**: Líder y único colaborador. Su experiencia incluye proyectos previos en Colsubsidio y CVN, y un enfoque en la automatización y optimización de procesos de datos.

## <h2 align=center> Fuentes de Datos y Integración </h2>

- **Fuentes**: Sistemas ERP, hojas de cálculo en Google Sheets, bases de datos SQL.
- **Integración**: Utilización de APIs para sistemas ERP y scripts de Python para Google Sheets y bases de datos.

## <h2 align=center> Gestión de Versiones y Actualizaciones </h2>

- **Sistema**: Control de versiones con Git, gestión mediante ramas específicas, revisiones de código y pruebas.

## <h3 align=left> Informes Financieros </h3>

- **Tipos**: Estado financiero, análisis de flujo de efectivo, balances de cuenta.
- **Personalización**: Plantillas en Google Sheets con opciones para seleccionar períodos y ajustar parámetros.

## <h3 align=left> Seguridad </h3>

- **Medidas**: Autenticación de dos factores, cifrado de datos, control de acceso basado en roles, auditorías de seguridad.

## <h3 align=left> Pruebas y Rendimiento </h3>

- **Pruebas**: Rendimiento con hasta 10,000 transacciones simultáneas, pruebas unitarias de cada módulo.
- **Resultados**: Sin problemas de rendimiento detectados, informes precisos y rápidos.

## <h3 align=left> Optimización Continua </h3>

- **Próximos Pasos**: Implementación de nuevas funcionalidades basadas en feedback, mejora en la integración de datos, optimización del rendimiento.

## <h2 align=center> Conclusiones </h2>

**FinDataSync** ha demostrado ser una solución robusta y eficiente para la sincronización y procesamiento de datos financieros, superando las expectativas en términos de velocidad y precisión. La implementación de esta solución ha resultado en una mejora significativa en la gestión de datos y la generación de informes, proporcionando un valor estratégico a BBVA.

---
