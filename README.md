# Telecom X - Análisis de Evasión de Clientes (Churn)

## Descripción del Proyecto

Este proyecto se centra en el análisis de datos de **evasión de clientes** (Churn) de la empresa **Telecom X**, una compañía de telecomunicaciones que enfrenta un alto índice de pérdida de clientes. El objetivo es **limpiar, transformar y explorar los datos** proporcionados para identificar patrones y posibles causas de esta evasión. Los hallazgos de este análisis servirán como base para un análisis predictivo posterior que podrá ayudar a la empresa a reducir su tasa de churn.

## Aplicación Práctica del Conocimiento

### Limpieza y Tratamiento de Datos
La limpieza de datos es una habilidad fundamental para cualquier analista de datos. En este desafío, aplicamos los conocimientos sobre el manejo de **valores nulos**, **duplicados** y **valores fuera de estándar** para garantizar que los datos sean consistentes y estén listos para el análisis. Este proceso es esencial para asegurar que los resultados obtenidos sean precisos y confiables.

### Análisis Exploratorio de Datos (EDA)
El análisis exploratorio de datos (EDA) es crucial para comprender las características del conjunto de datos. Durante este desafío, aplicamos **estadísticas descriptivas** y **visualizaciones** para identificar patrones, tendencias y relaciones entre las variables. El objetivo es formular hipótesis y generar **insights** que ayuden a la empresa a comprender las causas subyacentes de la evasión de clientes y a mejorar sus estrategias.

## Descripción del Desafío

Telecom X te ha contratado como analista de datos para abordar el **problema de Churn**. Te han proporcionado un conjunto de datos en formato **JSON**, el cual tendrás que **extraer, limpiar y explorar** para proporcionárselos al equipo de ciencia de datos. Este equipo realizará un análisis predictivo sobre los datos para entender las razones detrás de la evasión de clientes.

Durante este desafío, pondrás en práctica las habilidades que has adquirido en los cursos de **ETL**, **análisis exploratorio de datos** y usarás herramientas como **Python**, **Pandas** y **Matplotlib** para completar el desafío.

## Material de Apoyo

### Herramientas Utilizadas:
- **Python**: Lenguaje de programación para manipulación de datos y creación de visualizaciones.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **Matplotlib**: Biblioteca para la creación de gráficos y visualizaciones.
- **Google Colab**: Entorno en línea para ejecutar código Python.

### Pasos del Proyecto:
1. **Extracción de Datos**: Obtén los datos de la API proporcionada, que te entregará un archivo **JSON**. Puedes cargarlo en tu entorno de trabajo (Google Colab) para comenzar con la limpieza y el análisis.
   
2. **Limpieza de Datos**: 
   - Elimina o trata los valores nulos.
   - Convierte las columnas de texto como "Yes"/"No" en valores binarios (0 y 1).
   - Asegúrate de que todos los tipos de datos sean correctos para cada columna.
   
3. **Análisis Exploratorio de Datos (EDA)**:
   - Realiza una descripción estadística de los datos.
   - Crea visualizaciones para explorar la distribución de **Churn** y otras variables clave.
   - Identifica patrones y tendencias que puedan dar indicios sobre las causas de la evasión de clientes.
   
4. **Informe Final**:
   - Escribe un informe con las conclusiones obtenidas del análisis exploratorio.
   - Describe las posibles causas del churn y proporciona recomendaciones para abordar el problema.
   - Tu informe será parte de un proyecto más grande para desarrollar un modelo predictivo.

## Instrucciones para el Proyecto

1. **Clonación del Proyecto**: 
   - Si estás utilizando un entorno como Google Colab, simplemente importa los datos JSON proporcionados a tu notebook.
   
2. **Estructura de Archivos**:
   - El proyecto debe incluir un script de Python (`.py` o un notebook `.ipynb`) que cubra todos los pasos de extracción, limpieza, y análisis de datos.
   - Asegúrate de que todo el código esté bien documentado con comentarios explicativos.

3. **Conclusiones**:
   - Al final del desafío, completa el **informe final** en la tarjeta correspondiente de Trello. Este informe debe incluir tus hallazgos sobre la evasión de clientes y tus recomendaciones.

## Recursos

- [Trello Board de Material de Apoyo y Listo para Iniciar](https://trello.com)
- API de datos: **JSON** de Telecom X (URL proporcionada en el material de apoyo).

## Requisitos de Instalación

Este proyecto depende de las siguientes bibliotecas:

- `requests`
- `pandas`
- `matplotlib`

Puedes instalarlas ejecutando el siguiente comando en tu entorno de trabajo:

```bash
pip install requests pandas matplotlib
