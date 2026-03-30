# Taller Integrador — Módulo 1

## Autor
Daniel Moreno Macias

## Descripción del proyecto
Este proyecto corresponde al Taller Integrador del Módulo 1 del Máster en IA & Data Science.  
El objetivo es aplicar conceptos básicos y prácticos de Python, Pandas, Git y documentación a través del análisis de un dataset de salud mundial.

El trabajo se desarrolló en un notebook de Jupyter y aborda tareas como:
- estructuras básicas de Python
- funciones
- listas y diccionarios
- carga y exploración de datos con Pandas
- limpieza de datos
- análisis estadístico básico
- filtrado y agrupación de información
- uso de Git y GitHub para el control de versiones

## Descripción del dataset
El archivo utilizado es `salud_mundial.csv`.

Este dataset contiene información de salud de **159 países** y cuenta con **13 columnas**.  
Incluye variables como:
- país
- región
- nivel de ingresos
- esperanza de vida
- gasto en salud per cápita
- mortalidad infantil
- médicos por cada 1000 habitantes
- población urbana
- obesidad
- diabetes
- tabaquismo
- camas hospitalarias
- cobertura de vacunación

**Fuente:** dataset académico proporcionado en el taller (`salud_mundial.csv`).

## Cómo ejecutar el notebook
1. Clona este repositorio en tu equipo:
   `git clone <URL_DEL_REPOSITORIO>`

2. Entra a la carpeta del proyecto:
   `cd <NOMBRE_DEL_REPOSITORIO>`

3. Crea y activa un entorno virtual (opcional, pero recomendado).

   En Windows:
   `py -m venv .venv`
   `.venv\Scripts\activate`

4. Instala las dependencias necesarias:
   `pip install pandas jupyter`

5. Asegúrate de que el archivo `salud_mundial.csv` esté en la misma carpeta que el notebook.

6. Abre Jupyter Notebook:
   `jupyter notebook`

7. Ejecuta el archivo `taller_modulo1.ipynb`.

8. Para validar que todo funciona correctamente, usa:
   `Kernel -> Restart & Run All`

## Hallazgos y conclusiones del análisis
1. El dataset reúne información de 159 países, lo que permite comparar indicadores de salud entre distintas regiones y niveles de ingresos.

2. La esperanza de vida central observada en el análisis fue de **73.2 años**, lo que sirve como referencia general para comparar países con mejores o peores indicadores de salud.

3. En el análisis realizado, **Slovakia** aparece como el país con mayor gasto en salud per cápita, mientras que **Afghanistan** presenta el menor gasto.

4. El dataset contiene valores nulos en algunas columnas numéricas, por lo que fue necesario aplicar limpieza de datos antes de continuar con el análisis.

5. Las variables incluidas permiten estudiar relaciones importantes entre economía y salud, por ejemplo entre gasto en salud, esperanza de vida, mortalidad infantil y cobertura de vacunación.

## Tecnologías usadas
- Python
- Pandas
- Jupyter Notebook
- Git
- GitHub