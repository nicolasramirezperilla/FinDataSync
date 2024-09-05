<div align="center">
    <img src="https://github.com/nicolasramirezperilla/FinDataSync/blob/master/Logo%20-%20FinData%20Sync.png" alt="FinDataSync Banner" width="500"/>
</div>

# <h1 align=center> *Project: FinDataSync* </h1>

---

## <h2 align=center> Description </h2>

**FinDataSync** is a key project implemented at BBVA to automate and optimize financial data synchronization. This project focuses on improving the speed and effectiveness of data processing, ensuring the rapid delivery of meaningful and accurate reports. By utilizing Python and specialized libraries, FinDataSync handles large volumes of information, significantly reducing processing times and ensuring the creation of highly strategic financial reports.

## <h2 align=center> Project Team </h2>

- **Nicolás Ramírez Perilla**: Leader and sole contributor. His experience includes previous projects at Colsubsidio and CVN, with a focus on automation and optimization of data processes.

<div align="center">
    <img src="https://github.com/nicolasramirezperilla/FinDataSync/blob/master/Team%20Work.png" alt="FinDataSync TeamWork" width="300"/>
</div>

## <h2 align=center> Script Functions </h2>

- **cambiar_tipo(valor)**  
  *Description:* Changes the type of a value based on its content: whether it is null, numeric, or textual.  
  *Technologies Used:* Python, pandas  
  *Impact:* Properly classifies data for more effective subsequent processing.

- **crear_niveles(df)**  
  *Description:* Creates level columns in a DataFrame based on the structure and hierarchy of the content.  
  *Technologies Used:* Python, pandas  
  *Impact:* Allows hierarchical structuring of data, facilitating analysis that depends on the hierarchy of information.

- **proyecto_eliminar_filas_vacias(df)**  
  *Description:* Removes empty rows from the DataFrame df, ensuring that only rows with valid data are kept.  
  *Technologies Used:* Python, pandas  
  *Impact:* Cleans the DataFrame of empty entries that could affect subsequent analysis and processing.

- **replicar_niveles_inverso(df)**  
  *Description:* Replicates and organizes level columns in reverse order, ensuring that higher hierarchical levels are processed appropriately.  
  *Technologies Used:* Python, pandas  
  *Impact:* Reorganizes data to ensure that hierarchies are correctly maintained when processing levels in reverse order.

- **eliminar_filas_vacias(df)**  
  *Description:* Removes rows that do not contain data in any of their columns, cleaning the DataFrame.  
  *Technologies Used:* Python, pandas  
  *Impact:* Improves DataFrame quality by ensuring that only rows with useful data are considered for analysis.

- **obtener_max_nivel(df)**  
  *Description:* Calculates the maximum hierarchical level present in a DataFrame to organize information according to its hierarchy.  
  *Technologies Used:* Python, pandas  
  *Impact:* Helps determine the maximum hierarchy in a dataset, crucial for hierarchical and structural analysis.

- **replicar_datos(df, columna_base)**  
  *Description:* Replicates data in columns based on a base column, ensuring consistency in replicated information.  
  *Technologies Used:* Python, pandas  
  *Impact:* Ensures related data is adequately replicated to maintain the integrity and consistency of the information.

- **reemplazar_valores(df, columnas_a_reemplazar, valor_buscar, valor_reemplazo)**  
  *Description:* Searches for and replaces specific values in the selected columns of a DataFrame, updating the DataFrame with new values.  
  *Technologies Used:* Python, pandas  
  *Impact:* Facilitates data normalization by replacing specific values in multiple columns, improving data consistency and quality.

- **actualizar_columnas_por_fecha(df, columna_fecha)**  
  *Description:* Updates the columns of the DataFrame based on the specified date column, aligning the data to the relevant dates.  
  *Technologies Used:* Python, pandas  
  *Impact:* Ensures data is temporally aligned, which is essential for time-based analyses.

- **calcular_diferencias(df, columna_referencia)**  
  *Description:* Calculates the differences between values in DataFrame columns with respect to a reference column, useful for comparative analysis.  
  *Technologies Used:* Python, pandas  
  *Impact:* Enables analysis of variations and trends by comparing data with a reference column, enhancing understanding of changes over time.

- **concatenar_columnas(df, columnas_a_concatenar, nueva_columna)**  
  *Description:* Concatenates the values from the specified columns into a new column in the DataFrame.  
  *Technologies Used:* Python, pandas  
  *Impact:* Combines scattered data from different columns, facilitating analysis and improving DataFrame readability.

- **filtrar_por_condiciones(df, condiciones)**  
  *Description:* Filters the DataFrame based on the specified conditions, returning only the rows that meet the conditions.  
  *Technologies Used:* Python, pandas  
  *Impact:* Allows focus on specific data subsets for more detailed analysis.

- **generar_resumen(df, columnas_grupo)**  
  *Description:* Generates a summary of the DataFrame grouped by the specified columns, calculating statistics such as sum, average, etc.  
  *Technologies Used:* Python, pandas  
  *Impact:* Provides a quick summary of key data, facilitating informed decision-making.

- **guardar_a_excel(df, ruta_salida, nombre_hoja="Hoja1")**  
  *Description:* Saves the DataFrame to an Excel file at the specified path, allowing customization of the sheet name.  
  *Technologies Used:* Python, pandas, openpyxl  
  *Impact:* Facilitates the export of processed data for further analysis or presentation, integrating the output with common office tools.

## <h2 align=center> Technologies Used </h2>

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
- ![OpenPyXL](https://img.shields.io/badge/OpenPyXL-1F4F5E?style=for-the-badge&logo=python&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## <h2 align=center> Challenges and Issues </h2>

- Cloud synchronization.
- Functions in Google Colab.
- Incomplete formats.
- Rustic parameters.
- Usage limitations.

## <h2 align=center> Success Measurement </h2>

- **KPIs**: Accuracy of financial reports, efficiency in data processing, and handling of simultaneous transactions.
- **Results**: The system managed up to 10,000 simultaneous transactions without performance degradation.

## <h2 align=center> Data Sources and Integration </h2>

- **Sources**: ERP systems, Google Sheets spreadsheets, SQL databases.
- **Integration**: Use of APIs for ERP systems and Python scripts for Google Sheets and databases.

<div align="center">
    <img src="https://github.com/nicolasramirezperilla/FinDataSync/blob/master/ETL%20Flow%20Chart%20-%20FinData%20Sync.png" alt="FinDataSync ETL" width="600"/>
</div>

## <h3 align=left> Version Management and Updates </h3>

- **System**: Version control with Git, management through specific branches, code reviews, and testing.

## <h3 align=left> Financial Reports </h3>

- **Types**: Financial statements, cash flow analysis, account balances.
- **Customization**: Templates in Google Sheets with options to select periods and adjust parameters.

## <h3 align=left> Security </h3>

- **Measures**: Two-factor authentication, data encryption, role-based access control, security audits.

## <h3 align=left> Testing and Performance </h3>

- **Testing**: Performance with up to 10,000 simultaneous transactions, unit testing of each module.
- **Results**: No performance issues detected, accurate and fast reports.

## <h3 align=left> Continuous Optimization </h3>

- **Next Steps**: Implementation of new features based on feedback, improvement in data integration, performance optimization.

## <h2 align=center> Conclusions </h2>

**FinDataSync** has proven to be a robust and efficient solution for financial data synchronization and processing, exceeding expectations in terms of speed and accuracy. The implementation of this solution has resulted in a significant improvement in data management and report generation, providing strategic value to BBVA.

---
