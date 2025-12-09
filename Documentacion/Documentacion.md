# Área de Ingeniería en Computación  
## Sistemas de Información Geográfica  
### Proyecto 3  

---

### Estudiantes  
- **Pamela Morataya Sandoval** – 2022108818  
- **Harlen Quirós Gómez** – 2022035693  

---

### Profesor  
- **Armando Arce Orozco**  

---

### Fecha  
- **8 de diciembre, 2025**  
- **II Semestre, 2025**  

---

## Introducción  

Este proyecto tiene como objetivo la creación de un mapa en mosaico personalizado utilizando **TileMill** y las capas de datos proporcionadas en el repositorio del curso. Como parte de los requerimientos, cada grupo debe trabajar con un cantón específico; en este caso, el mapa se desarrolla para el **cantón de San Ramón**.  

El trabajo consiste en recortar todas las capas geográficas con base en el límite cantonal asignado y utilizarlas para generar un mapa que integre información de tipo ráster y vectorial. Como imagen base se emplea un mapa derivado de los datos contenidos en el archivo `geo_hitos.zip`, a partir del cual se genera una representación como altitud, relieve sombreado, aspecto o pendiente.  

Además, se incorporarán capas de polígonos (provincias, cantones, distritos), capas de líneas (carreteras y ríos) y capas de puntos (poblados, escuelas, hospitales, gasolineras, hoteles, bancos, entre otros). Para complementar el mapa, también se incluirá información adicional obtenida desde **OpenStreetMap**, como calles y comercios. Todas las capas deben estilizarse adecuadamente en TileMill, controlando su visualización mediante niveles de zoom y aplicando simbología diferenciada para evitar confusiones.  

La idea es que el mapa generado se exporte y se publique en una plataforma de hosting web, junto con una página `index.html` que permita visualizarlo. Este documento describirá el proceso seguido, las herramientas que se emplearon y la organización de las capas utilizadas para cumplir con todas las especificaciones dadas en el PDF del proyecto.  

---

## Elementos  

Para el desarrollo del proyecto se realizó un recorte de todos los datos que intersectaban con el cantón de **San Ramón**, ubicado en la provincia de **Alajuela, Costa Rica**. Este proceso incluyó capas como distritos, ríos, carreteras, centros poblados y demás archivos `.shp` contenidos en el paquete `GEO_CR.zip`. De esta manera, se logró un manejo más eficiente y simplificado de la información geoespacial.  

![Imagen de elementos en MapWindows](./img1.png)

Asimismo, a partir de los datos proporcionados por el profesor —hospitales, escuelas diurnas, clínicas, gasolineras, agencias bancarias y hoteles— se llevó a cabo un proceso de **intersección espacial** con el cantón de San Ramón, permitiendo conservar únicamente los datos correspondientes al área de estudio.  

Adicionalmente, mediante la plataforma **OpenStreetMap** se extrajo un archivo `.osm` de la zona, el cual contiene una mayor variedad de elementos del cantón. Debido a la extensión territorial del mismo, no fue posible exportar el cantón completo en una sola operación. Sin embargo, esta información permitió la generación de nuevos archivos `.shp` correspondientes a zonas verdes, edificaciones y otros elementos de interés.  

---

## Explicación de TileMill  
![Imagen de elementos en TileMill](./img2.png)
*(Pendiente de completar)*  

---

## Explicación de los Puntos de Elevación / Mapa de Calor  

*(Pendiente de completar)*  

---

## Link del Proyecto  

*(Pendiente de agregar)*  

---

## Conclusiones  

El desarrollo de este proyecto permitió aplicar de manera práctica los conceptos fundamentales de los **Sistemas de Información Geográfica (SIG)**, mediante la integración, recorte, procesamiento y visualización de información geoespacial del cantón de San Ramón, en la provincia de Alajuela. A través del uso de fuentes oficiales y abiertas como **GEO_CR** y **OpenStreetMap**, fue posible construir una base de datos espacial completa, diversa y adaptada a las necesidades específicas del área de estudio.  

El proceso de intersección espacial facilitó la depuración de la información, garantizando que únicamente se preservaran los datos relevantes dentro del límite cantonal, lo que optimizó tanto el rendimiento como la claridad del mapa resultante. Asimismo, la generación de capas temáticas —como infraestructura vial, recursos hídricos, centros educativos, servicios de salud, comercios y zonas verdes— permitió una representación integral del entorno urbano y rural del cantón.  

Finalmente, la publicación del mapa en la web consolidó el objetivo principal del proyecto, al ofrecer una herramienta interactiva, accesible y visualmente estructurada para la exploración del territorio. Este trabajo no solo evidencia el potencial de los SIG como apoyo a la toma de decisiones, sino también la importancia del uso responsable de datos geoespaciales abiertos para el análisis y la planificación territorial.  
