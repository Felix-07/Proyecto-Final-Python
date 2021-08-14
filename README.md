# Análisis de Incidentes Viales en la CDMX con base en la información proporcionada por el C5

## Equipo 11

**Integrantes**

-Ximena Ávila Villagómez

-Ana Katherine Cuevas Flores

-Félix Alberto Nieto García

-Alejandro De Fuentes Martínez

## Resumen 
El proyecto consiste en el la limpieza, procesamiento y análisis de datos de incidentes viales en la CDMX desde el 2014 hasta el 2021. Los datos fueron recopilados por El Centro de Comando, Control, Cómputo, Comunicaciones y Contacto Ciudadano  ( [C5](https://www.c5.cdmx.gob.mx/)) de la Ciudad de México, la cual es la dependencia del Gobierno  encargada de captar información para la toma de decisiones en la capital del país a través del video monitoreo, de la captación de llamadas telefónicas y de aplicaciones informáticas de inteligencia. 

## Contenido

1. **Un documento escrito**: 
Documento el [reporte del proyecto](https://github.com/Felix-07/Proyecto-Final-Python/blob/main/Entrega_Final_Procesamiento_Ximena%C3%81vila_AnaCuevas_FelixNieto_AlejandroFuentes/Reporte%20-%20Proyecto%20Incidentes%20Viales%20en%20la%20CDMX%20-%20C5%20-%2013%20Agosto%202021.pdf) en formato *pdf* con  que contiene el marco teórico de referencia, preguntas relevantes, análisis del problema, comentarios, información del proyecto y referencias. 

2. **Un Jupyter Notebook**: 
 Se presenta el [código](https://github.com/Felix-07/Proyecto-Final-Python/blob/main/Entrega_Final_Procesamiento_Ximena%C3%81vila_AnaCuevas_FelixNieto_AlejandroFuentes/Proyecto_Final_Python_Final_Final_13Ago21.ipynb) en formato *ipynb* en donde se muestra proceso de cada una de las partes del proyecto, así como los resultados obtenidos. 

3. **Vídeo**:
Se adjunta el [link del vídeo](https://www.youtube.com/watch?v=H1bo_fPujoQ) donde cada uno de los integrantes expone de manera breve cada parte del proyecto.

4. **Datasets**:
Se adjuntan los archivos *csv* originales así como los procesados en una [carpeta de google drive](https://drive.google.com/drive/folders/1ua_Z7qMB_qVfzblyBNlwf2it-tOIaGTK?usp=sharing), en el se encuentran los Datasets de los incidentes viales reportados del 2014 al 2020, incidentes viales reportados del 2021, los datos limpios y los polígonos delimitadores de las alcaldías.


5. **Presentación**:
[Presentación](https://github.com/Felix-07/Proyecto-Final-Python/blob/main/Extra/Presentacio%CC%81n%20para%20el%20Video%20en%20Equipo%20-%20Proyecto%20-%20Procesamiento%20de%20Datos%20con%20Python%20-%2013Agosto2021.pdf) utilizada en el vídeo en formato *pdf*.

## Índice del código
0. Librerías
1. Identificación del problema
2. Plantemiento de preguntas
3. Colección de datos
4. Análisis exploratorio de los datos

   4.1 Descripción general de los datasets
  
   4.2 Concatenación de los datasets
  
   4.3 Verificación de los datos
   
   4.4 Especificaciones generales para la limpieza
   
5. Limpieza de datos  

   5.1 Tranformación de datos
  
   5.2 Eliminación de NaNs
  
6. Procesamiento y resultados

   6.1 Frecuencias generales de los datos categoricos
  
   6.2 Accidentes afirmativos y su clasificación
  
   6.3 Accidentes afirmativo por delegacion 
  
   6.4 Accidentes afirmativo por año
  
   6.5 infomación de accidentes por delegaciónes  un mes y año en particular
  
   6.6 Serie de tiempo de accidentes afirmativos
  
7. APIs

   7.1 Delimitación territorial de las 16 alcaldías de la Ciudad de México
  
   7.2 Mapa interactivo de accidentes 
  
8. Conclusiones
9. Planes a futuro

## Notas
* Debido a la naturaleza de GitHub no es posible mostrar las graficas y mapas interactivos dentro del código. Si se desea ver las graficas y mapas puede ejecutar el [Jupyternotebook vesión Colab](https://colab.research.google.com/gist/Felix-07/a3b57ffaebacdb6cdb26179440550c82/proyecto-final-python.ipynb).
* Por otra parte se puede descargar [los mapas interactivos](https://github.com/Felix-07/Proyecto-Final-Python/tree/main/Mapas%20interactivos) (formato *html*) o vizualizarlos en internet: [mapa de cluster](https://felix-07.github.io/Proyecto-Final-Python/Accidentes_A_2021_cluster.html), [mapa de calor](https://felix-07.github.io/Proyecto-Final-Python/accidentes_2021_5_heatmap.html) y [Delimitación territorial de la CDMX](https://felix-07.github.io/Proyecto-Final-Python/alcaldias.html).
* En caso de tener problemas al visualizar los documentos en formato *pdf*, se recomienda utilizar el navegador Google Chrome.
