# Curso de Tableau: Visualización de Datos y Storytelling para Negocios

![Logo](https://static.platzi.com/media/achievements/badge_tableau_visualizacion_datos_storytelling_negocios-8dd94dc6-37a3-4dc6-a39c-347.png)

## Archivos

[Slides](/files/slides.pdf)

## Proyecto

### Game of Thrones DataViz

Pon a prueba todas tus habilidades con Tableau para crear dashboards y storyboards interactivos sobre los mejores (¿o peores?) asesinos de Game of Thrones.

## Instructor

Luis Jorge Novelo

# Indice

1. [Fundamentos de Tableau](#fundamentos-de-tableau)
    * [Importancia de la visualización de datos](#importancia-de-la-visualización-de-datos)
    * [Tableau y las herramientas de visualización de datos](#tableau-y-las-herramientas-de-visualización-de-datos)
    * [Anatomía e interfaz de Tableau Public](#anatomía-e-interfaz-de-tableau-public)
    * [Importación de datos: tu primera visualización](#importación-de-datos-tu-primera-visualización)

---

# Fundamentos de Tableau

## Importancia de la visualización de datos

Es la Representación gráfica de información.

* Input: Información (data).
* Output: Revelaciones (Insights) e historias.

### ¿Para qué?

Tenemos muchas fuentes, muchos datos, en todo momento y lugar. La visualización nos ayuda a encontrar información pertinente y relevante que nos va a ayudar a nuestra organización.

No es un tema actual, se remonta a los mapas de las constelaciones de la astronomía y puede ser tan antiguos como los abacos.

[The Growing Importance of Data Visualization](https://www.tableau.com/learn/webinars/growing-importance-data-visualization)

## Tableau y las herramientas de visualización de datos

### Herramientas más comunes para DataViz

* Excel
* Tableau
* Power BI
* Google Analytics
* Google Data Studio

## Anatomía e interfaz de Tableau Public

![Tableau](/images/dash-tableau.png)

Tableau está dividido en 3 grandes partes.
1. Del lado izquierdo muestra la información de todas las conexiones a las cuales tenemos acceso.
2. Central: Los archivos recientemente abiertos o cerrados. También podemos acceder a archivos desde Tableau Public.
3. Del lado derecho, está la sección de "Descubra más", en esta sección están las novedades, o nuevos descubrimientos, noticias o visualizaciones en las últimas fechas en Tableau Public. Podemos encontrar también nuevas capacitaciones, artículos del estado actual de los servidores.

Si presionamos Esc, nos redirige a la hoja de trabajo.

![Hoja de trabajo](/images/hoja-trabajo-tableau.png)

1. Del lado izquierdo, por el momento vacío, pero ahí se podrán visualizar los valores de nuestros datos.
2. En la parte central, va a ser nuestro lienzo, ahí vamos a mostrar nuestras columnas, nuestras filas, filtros y las marcas.
3. En la parte derecha, Tableau nos muestra diferentes visualizaciones que podemos utilizar en nuestros datos.

## Importación de datos: tu primera visualización

En esta clase vamos a importar un [archivo de excel](/files/Sample-Superstore.xls) a Tableau Public.

1. Creamos la conexión con el archivo, en conexiones damos clic a Archivo de excel, lo buscamos y le damos clic a Importar.

![Excel](/images/dash-excel.png)

2. En la parte derecha veremos las hojas del archivo. Para esta demostración solo utilizaremos 'Orders'. Clic y se arrastra a la parte central.

![Orders](/images/dash-orders.png)

3. Importante que debemos tener en cuenta al momento de analizar es el tipo de dato por columna. Si no queremos revisar columna por columna, podemos dar clic a 'Administrar metadatos', esto nos cambiará la vista y nos mostrará la columna y su tipo.

![Columnas metadatos](/images/dash-metadatapng.png)

4. Damos clic en 'Hoja 1', el nombre de la hoja de trabajo de Tableau, y el dash cambia, ahora a la izquierda nos aparecerá las columnas.

![Dash columnas](/images/dash-columnas.png)

De esto podemos destacar que las columnas de tipo texto (discreto) son de color azul, y las de tipo numérico (continuo) son de color verde.

Tableau funciona con la metodología de Drag and Drop, se debe tener en cuenta qué se quiere utilizar como fila y qué utilizar como columna. Como ejemplo, queremos saber el total de ventas por categoría, arrastramos las ventas y las columnas al dashboard central y Tableau selecciona los datos automáticamente.

![Resultado](/images/total-ventas-categorias.PNG)

Tableau también permite transformar el tipo de información, por ejemplo, si las columnas están horizontalmente, las acomoda verticalmente, también puede generar diferentes colores para cada columna y engrosar o reducir su ancho utilizando la etiqueta correcta en la marca adecuada.

![Columnas](/images/dash-mod.png)