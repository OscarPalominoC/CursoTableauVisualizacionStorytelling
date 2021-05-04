# Curso de Tableau: Visualización de Datos y Storytelling para Negocios

![Logo](https://static.platzi.com/media/achievements/badge_tableau_visualizacion_datos_storytelling_negocios-8dd94dc6-37a3-4dc6-a39c-347.png)

## Archivos

[Slides](/files/slides.pdf)

## Proyecto

### Game of Thrones DataViz

Pon a prueba todas tus habilidades con Tableau para crear dashboards y storyboards interactivos sobre los mejores (¿o peores?) asesinos de Game of Thrones.

[Proyecto: Storyboard peores asesinos de Game of Thrones](https://public.tableau.com/profile/oscar.palomino#!/vizhome/DeathsinGOT_16174206774640/HistoriaGameofThrones)

## Instructor

Luis Jorge Novelo

# Indice

1. [Fundamentos de Tableau](#fundamentos-de-tableau)
    * [Importancia de la visualización de datos](#importancia-de-la-visualización-de-datos)
    * [Tableau y las herramientas de visualización de datos](#tableau-y-las-herramientas-de-visualización-de-datos)
    * [Anatomía e interfaz de Tableau Public](#anatomía-e-interfaz-de-tableau-public)
    * [Importación de datos: tu primera visualización](#importación-de-datos-tu-primera-visualización)
    * [Tu primer dashboard](#tu-primer-dashboard)
    * [Comunidad Tableau](#comunidad-tableau)
    * [Errores comunes al diseñar visualizaciones de datos](#errores-comunes-al-diseñar-visualizaciones-de-datos)
    * [Define la audiencia y objetivo de tu visualización](#define-la-audiencia-y-objetivo-de-tu-visualización)
2. [Tipos de gráficas y visualización de datos en Tableau](#tipos-de-gráficas-y-visualización-de-datos-en-tableau)
    * [Gráfica de barras y dispersión](#gráfica-de-barras-y-dispersión)
    * [Tablas y valores calculados](#tablas-y-valores-calculados)
    * [Fechas y gráficas de líneas](#fechas-y-gráficas-de-líneas)
    * [Mapas con filtros, parámetros y KPIs](#mapas-con-filtros-parámetros-y-kpis)
    * [Creación de tableros interactivos con acciones y filtros](#creación-de-tableros-interactivos-con-acciones-y-filtros)
3. [Dashboard y visualización de asesinos en Game of Thrones](#dashboard-y-visualización-de-asesinos-en-game-of-thrones)
4. [Recomendaciones finales: mejora tu Storytelling con Tableau](#recomendaciones-finales-mejora-tu-storytelling-con-tableau)
    * [Narración de historias y visualización de datos con storytelling](#narración-de-historias-y-visualización-de-datos-con-storytelling)
    * [Artículo: Estructura del Storytelling](#artículo-estructura-del-storytelling)

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

## Tu primer dashboard

Los Dashboards son un conjunto de visualizaciones de datos, generalmente se utiliza en los reportes y en enfocar nuestros esfuerzos específicamente en unos cuantos dataviz.

[Dasboard creado](https://public.tableau.com/profile/oscar.palomino#!/vizhome/DemoSales_16171684153650/Dashboard1)

## Comunidad Tableau

La comunidad de Tableau es una de las más importantes dentro de la visualización de datos. Uno de sus retos más importantes ocurre todos los lunes llamado [#MakeOverMonday](https://twitter.com/search?q=makeovermonday), ocurre todos los lunes, la comunidad libera una DB y al final del día la gente puede subir sus descubrimientos a Twitter y compartir sus descubrimientos y visualizaciones, para que todos puedan entenderse y comunicarse.

Otro evento importante es el Iron Viz, este simplemente se puede llevar por medio de una nominación en general de la comunidad. 

Otra comunidad interesante es Kaggle, esta es una plataforma en la que se pueden encontrar diversas DB de distintos tipos.

## Errores comunes al diseñar visualizaciones de datos

**☢ Cómo evitar errores comunes para la data viz ☢**

* Cuando relaciones dos o más gráficas, procura que las escalas no sean distintas.
* Procura que el orden de tus valores sean correctamente ordenados según la relación que ocupe en el gráfico.
* Ten en cuenta que debes diferenciar los valores de tu gráfica. Es recomendable diferenciar cada categoría por colores según su importancia para nuestro análisis.

[Which is the best chart: Selecting among 14 types of charts Part I](https://www.youtube.com/watch?v=C07k0euBpr8&ab_channel=365DataScience)

## Define la audiencia y objetivo de tu visualización

* Tenemos que saber qué mensaje queremos transmitir para saber cuál es el dataviz que mejor se acomode a nuestro mensaje. A diferente mensaje, diferente dataviz. No todos los dataviz son pertinentes para nuestros tipos de datos.
* Debemos definir la audiencia, para saber el lenguaje con el que ellos hablan, debemos saber sus terminos y saber las visualizaciones con las que ellos están familiarizados.
* Debemos definir un perfil *Persona*, vamos a tener que definir a sutanito y describir sus pasatiempos, las preguntas que podría tener por su modelo de trabajo o por el lugar en el que se desempeña, así como sus preferencias y habilidades para la interpretación de datos.
* ¿Cómo lo haré? Debemos definir si nuestra visualización va a ser estática o dinámica. Dependiendo de la presentación podemos entregar una simple imagen o entregar un archivo como lo hacemos en Tableau. Podemos hacer filtros dinámicos para que la audiencia pueda hacer un estilo de visión de rayos X y así poder ver a fondo nuestros hallazgos.
* Debemos formularnos las preguntas claves que quisieramos responder, cuáles son las dudas que tiene esta persona sobre nuestros datos y nuestro reporte. Tenemos que tratar de contestar estas dudas por medio de nuestras visualizaciones o dashboards.

### Plantilla de un perfil personal

![Plantilla](/images/plantilla-persona.png)

### Ética en las visualizaciones

Es 100% seguro que van a creer en nuestras visualizaciones, es por eso que **NO HAY CABIDA PARA NUESTRAS PREFERENCIAS PERSONALES**, debemos dejar que los datos hablen por medio de nuestras visualizaciones, siempre debemos usar gráficos que muestren la realidad de los hechos.

Debemos comprender que una vez que nuestra credibilidad se pierde, es muy difícil volver a retomarla, es muy importante ser muy minuciosos al mommento de entregar o comunicar nuestro mensaje.

### Reto: Perfil Persona

**Nombre**: Oscar

*"Ingeniero indutrial que necesita mejorar las condiciones de seguridad de su personal a cargo, con el fin de reducir el índice de accidentalidad al mínimo".*

Oscar necesita visualizaciones de los hallazgos del índice de accidentalidad en el tiempo, de los insumos utilizados por su personal y los costos allegados a estos.

**Rol**: HSE.

**Organización**: Acme.

**Metas**: 
* Disminuir el índice de accidentalidad.
* Disminuir los costos de insumos mejorando procedimientos.

**Retos y Necesidades**: 
* Excelente con los números.
* Necesita los datos más significativos para crear estrategias.
* Es muy visual, necesita los colores para diferenciar datos positivos y negativos.

# Tipos de gráficas y visualización de datos en Tableau

## Gráfica de barras y dispersión

### Gráfica de barras

La forma de utilizar esta herramienta es mediante el Drag and Drop, así que simplemente arrastramos las columnas en el apartado de columnas y las ventas en el apartado de las filas. Para darle color a la gráfica arrastramos las categorías en el apartado de color, y con esto tenemos representado las ventas por categorías.

![Ventas por categorías](/images/ventas-x-categorias.png)

### Gráfico de dispersión

En este, arrastramos los 2 valores numéricos en el apartado filas y seleccionamos el tipo de gráfico de dispersión. Nos va a mostrar la sumatoria final de estos 2, ahora, para que nos muestre punto por punto, damos clic a la pestaña análisis, y desmarcamos "Agregar medidas". Para mejorar la visualización arrastramos las ganancias al apartado de color y lo modificamos, en la parte de Editar colores marcamos "Color escalonado" y colocamos el valor de 2, con esto todo lo que esté por debajo de cero tendrá un color diferente a lo que esté por encima de cero. Todo lo que esté por debajo del cero son pérdidas. Ahora, podemos identificar quiénes son los clientes que están generando las perdidas, para esto, arrastramos el customer name en el apartado de descripción emergente.

![Profit vs sales](/images/profit-vs-sales.png)

### Reto: Realizar gráfico de barras de ventas por región

![Ventas por región](/images/ventas-x-region.PNG)

En adición a este reto, realicé un scatter plot de ganancias vs sales por las regiones.

![Ventas vs profit por región](/images/profit-vs-sales-x-region.PNG)

## Tablas y valores calculados

El formato de tabla es muy útil para poder ver información que pueda ser pertinente, pero también puede ser útil utilizar colores para reducir la carga sensorial de la audiencia.

Para crear una tabla de valores primero arrastramos las categorías y fecha de ordenes a las filas, luego, damos clic en el '+' de las fechas para que nos muestre los trimestres, ahora, los trimestres lo arrastramos a las columnas, arrastramos el profit al contenido de la tabla y modificamos el color, de esta manera creamos de una manera sencilla una tabla de valores.

![Tabla de valores](/images/tabla-utilidades.PNG)

### Campo calculado

Los campos calculados son aquellos que se crean a través de formulas matemáticas, son interesantes pues pueden tomar los valores de multiples campos de los que dispongamos en la DB. Para crear uno, damos clic derecho en la parte libre de abajo de la lista de campos, damos clic en 'crear campo calculado', le ponemos nombre y la formula matemática.

![Campo calculado](/images/campo-calculado.PNG)

Para utilizar este campo, arrastramos las categorías a las filas y arrastramos el campo calculado al contenido de la tabla. Como es un valor decimal debemos convertirlo a numérico, esto se hace dando clic derecho al campo creado en la columna de la izquierda, 'Propiedades predeterminadas' > 'Formato de número' > 'Porcentaje', seleccionamos la cantidad de decimales y damos clic a aceptar. Estos valores lo que quieren decir es que por cada dolar que entra a la empresa, ese es el porcentaje de ganancia por dolar.

![Profit vs sales ratio](/images/profit-vs-sales-ratio.png)

## Fechas y gráficas de líneas

Las líneas se utilizan para representar el proceso o un seguimiento de un elemento en un tiempo. Arrastramos sales y fecha de orden y lo dividimos en los trimestres, se colorea por fecha.

Hacemos este mismo proceso con las ganancias y creamos un nuevo dashboard. En el dashboard estandarizamos las medidas y podemos ver a mejor detalle el comportamiento de las ventas y las ganancias por trimestre, así mismo, también observamos lo que realmente ingresa a la empresa.

![Gráfico de línea](/images/line-chart.png)

### Reto: Gráfico de línea con los descuentos por trimestre

![Reto](/images/prom-descuentos-x-anno.PNG)

## Mapas con filtros, parámetros y KPIs

En esta clase vamos a ver las visualizaciones en forma de mapa, y mejor aún, cómo podemos hacer nuestros disparadores de KPI junto con un disparador o ajustador de nuestras tolerancias.

Para esto, debemos observar que los campos tengan el ícono de mundo, si lo tienen, los podemos utilizar. Si arrastramos las ciudades al centro, podemos ver cómo se genera un mapa de las ciudades que tiene nuestra DB. Tableau toma mi ubicación actual y trata de ubicar las ciudades en el país en el que me encuentro, pero eso es un error, puesto que la DB contiene ciudades únicamente de USA. Para ellos vamos a la pestaña de 'mapa', clic en 'editar ubicaciones', seleccionamos el país, región o estado, y esto lo enlazamos con los campos disponibles en la DB.

![Mapa](/images/mapa.png)

Ahora, vamos a crear los KPI, en Tableau estos se conocen como parámetros. Clic derecho a la parte izquierda y damos a 'Crear parámetro'. Ver imágen para saber cómo quedó el parámetro.

![Parámetro](/images/parametro.PNG)

Creamos un nuevo campo calculado con nombre 'KPI por descuento'.

```
IF [Discount] > [Tolerancia]
THEN TRUE
END
```

Ahora hace falta agregar funcionalidad, damos clic derecho al parámetro y luego clic a 'mostrar parámetro'. A la derecha de la plataforma nos muestra la tolerancia, como está enlazada con el descuento no va a mostrar nada puesto que 1 es el 100%, así que si ponemos 0.3 cambiarán de color algunas ciudades, es ahí dónde podemos ver que el parámetro está funcionando.

![parametro funcionando](/images/parametro-funcionando.png)

Modificamos los colores y ahora vamos a agregar un filtro, arrastramos los descuentos al apartado de filtros, seleccionamos mínimo y le damos un valor de 0,30. Aquí no vale el punto decimal.

![Mapa con filtro](/images/mapa-con-filtro.png)

### Reto

1. Crear un mapa con las ciudades que hayan vendido más de 5K USD.

![Reto solucionado](/images/ciudades-ventas-5k.png)

2. Crear un mapa con los estados que hayan vendido más de 50K USD.

![Reto solucionado](/images/estados-ventas-50k.png)

## Creación de tableros interactivos con acciones y filtros

**¿Cómo hacer dashboards dinámicos?**

Tienes que ir a:

dashboard > acciones > añadir acción > filtro

Esto, nos permite que se apliquen filtros de forma automática a todas nuestras gráficas que lo contengan en el db.

[Dashboard creado](https://public.tableau.com/profile/oscar.palomino#!/vizhome/DemoSales2/Dashboard2)

# Dashboard y visualización de asesinos en Game of Thrones

1. Descargamos el [dataset](/files/game-of-thones-deaths.xlsx).
2. Exploramos los datos. Durante la exploración observamos que el nombre de las columnas NO está en la primera fila, por lo tanto, debemos borrar el contenido hasta que aparezca en la primera fila el nombre de las columnas.
![Exploración](/images/exploracion.png)

![Exploración](/images/exploracion2.png)

3. Conectamos el archivo a nuestro Tableau.
4. Analizamos la información.
    * Cada fila representa una muerte en GOT.
5. Realizamos las visualizaciones pertinentes:
    * Gráfico de barras ordenados de mayor a menor del mayor asesino.
    * Tablas respecto a las casas más asesinas, los que llevan más víctimas, el total de víctimas, y armas favoritas.
    * Creamos un filtro dinámico con los asesinos (Dashboard > Acciones > Añadir acción).
    * Creamos un dashboard básico con esta información.
    
    ![Dash](/images/dash-GOT1.png)

    * Convertimos Season y Episode en dimensiones (Click derecho 'Convertir a dimensión').
    * Usamos Season como columna y Episode como fila, añadimos el conteo de muertes como contenido de la tabla. Creamos un dashboard con estos 2 datos.

    ![Dash2](/images/dash-GOT2.png)

    * Creamos una nueva visualización usando la ubicación y el conteo de muertes. Seleccionamos como visualización el mapa de árbol. Este mapa indica que entre más grande el área ocupada, mayor número de muertes en esta ubicación.
    * Añadimos esta visualización y la tabla de asesinos en el dashboard.

    ![Dash3](/images/dash-GOT3.png)
    * Añadimos detalles de las víctimas y las casas a las que pertenecen.
    ![Dash4](/images/dash-GOT4.png)

# Recomendaciones finales: mejora tu Storytelling con Tableau

## Narración de historias y visualización de datos con storytelling

Los Storytelling, siempre deben acompañar las gráficas de un preámbulo que explique la metodología usada. Con ello, podremos exponer toda nuestra información precisa sin ambigüedad.

### Partes de un storytelling

* Introducción (citar fuentes, y hacer precisiones sobre información consultada)
* Resumen de nuestros resultados (sirven explicar contundente qué encontramos y cómo lo encontramos, así como detellar cómo utilizar la herramienta)
* Presentación de nuestros Data viz. (recomendable no usar más de tres data viz)
* Conclusiones. Describimos las preguntas que queríamos resolver.
* Incluir recomendaciones. (Nuestro criterio para explicar cómo resolver el problema en cuestión).

[Historia creada](https://public.tableau.com/profile/oscar.palomino#!/vizhome/DeathsinGOT_16174206774640/HistoriaGameofThrones)

## Artículo: Estructura del Storytelling

Narrar historias o “storytelling” como se le conoce dentro del mundo de la visualización de datos es una herramienta muy útil y frecuentemente subestimada que puede ayudarnos a entender mejor nuestra información mientras cautivamos a la audiencia asegurando la retención del mensaje de una manera efectiva.

Esto puede sonar complicado, pero te aseguro que es más sencillo de lo que parece.

El storytelling es prácticamente poder presentar nuestros descubrimientos utilizando una narración en forma de historia.

Para esto, Tableau cuenta con una herramienta creada específicamente para este fin, las Historias (Story).

**¿Qué es una Historia?** Es el lienzo en el que se nos permitirá recopilar nuestros dataviz y tableros para poder convertirlos en una presentación que facilite la narración de nuestro contexto, descubrimientos, el proceso y nuestras conclusiones

Ejemplo de una Historia en Tableau

![Story](/images/story1.png)

Como verás, Tableau nos prepara de una manera sencilla todo el ambiente necesario para nuestra creación de narrativas.

Ya conocemos la herramienta, pero debemos hablar acerca de lo que haremos con ella, te voy a dejar ahora una pequeña guía para que puedas hacer Storytelling increíble.

Primero definiremos la estructura de la Historia. Para poder crear una historia que cause impacto te puedo recomendar el siguiente orden:

* Contexto
* Resumen
* Puntos de interés
* Conclusiones
* Recomendaciones

### Contexto

Utiliza este apartado para poder contar cómo es que elegiste iniciar el proyecto, con qué fin lo estás haciendo, que pensabas encontrar o cuáles eran las preguntas que querías contestar.

El contexto es muy importante porque le explica a la audiencia la razón de nuestro trabajo y las intriga para poder saber más en las siguientes etapas de nuestra historia.

Por lo general, debes aclarar aquí el qué, quién, cómo y para qué del trabajo.

Ejemplo:

Durante mi tiempo de business intelligence en la empresa de Walmart, tras la primera reunión del departamento de datos del año, decidimos analizar el comportamiento de usuarios para poder incrementar las ventas por temporada en nuestras sucursales. Recuerdo bien ese día porque precisamente al momento de salir del trabajo y encender el auto, en la radio anunciaban tener precaución por el acercamiento de un huracán. Evidentemente fui corriendo a la primera tienda que encontré para comprar los productos esenciales… ¡Y fue ahí, parado en el anaquel comprando agua y enlatados cuando me di cuenta de que nunca habíamos analizado el comportamiento de los clientes de Walmart ocasionado por desastres naturales!. La idea me iluminó la mente y me pareció muy interesante hacer una investigación a fondo sobre los productos más vendidos al momento que se pronostican desastres naturales…

Si te das cuenta, en esta pequeña historia estoy dando todo el contexto que llevó al análisis de datos e inició el proyecto sobre los efectos de los desastres naturales en el comportamiento de compra en Walmart.

Utiliza el contexto a tu favor, trata de conectar con la audiencia utilizando lenguaje común y situaciones que les pudieran ser familiares.

### Resumen

Esta sección puedes utilizarla como segunda sección de la narración o al final junto con las conclusiones, yo la utilizo inmediatamente después del contexto para resumir al instante mis descubrimientos y generar intriga en la audiencia acerca de cómo llegué a esos resultados, generando que queden muy atentos a todo el proceso que conllevó el trabajo.

Continuando con el ejemplo anterior, el apartado de resumen llevaría una narración así:

Poptarts… El artículo más vendido en Walmart después de anunciarse los huracanes son las Poptarts sabor fresa… Quedé impresionado, fue un descubrimiento increíble.

![Resumen](/images/resumen.png)

### Puntos de interés

Esta sección deberá constar de las dataviz que mejor representen tus descubrimientos, tu proceso y tus resultados.

Aquí te recomiendo que utilices tanto dataviz individuales como dashboards, es muy importante que tu elección refleje de una manera adecuada la información para que puedas comunicar de la manera más efectiva tu mensaje.

Yo utilizo 3 puntos de interés dentro de mis narraciones para tratar de mantener la presentación muy directa y orientada a los resultados. Te dejo este ejemplo:

Primer punto de interés para definir los limitantes del KPI del proyecto utilizando un diagrama de cajas (boxplot).

![boxplot](/images/boxplot.png)

Segundo punto de interés a modo de implementación de KPI’s y un panorama general del proyecto utilizando un dashboard con varias visualizaciones de datos

![Dash 1](/images/dash.png)

Y tercer punto de interés, una comparativa que me permita realzar el peor y el mejor resultado según el proyecto:

![Dash 2](/images/dash11.png)

¡Ojo! Cada uno de los puntos de interés debe tener una narración explicativa y cronológica con relación a tu historia para que mantenga su coherencia.

Si te sirve, piensa en los puntos de interés como la ayuda visual que te permitirá recordar los puntos importantes a mencionar dentro de tu historia.

### Conclusiones

Aquí simplemente reforzaremos el mensaje sobre los resultados finales de nuestro proyecto para dejar muy en claro y de manera contundente lo que pudimos encontrar o las respuestas que contestamos durante el ejercicio. Esta sección es importante porque nos permite darle un cierre a nuestra historia con un descubrimiento o mensaje final.

Es aquí en donde podemos dar nuestro toque personal y demostrar nuestra opinión con lo encontrado. Te recomiendo muchísimo que incluyas siempre esta sección, ya que nos ofrece un escaparate para poder demostrar nuestras habilidades para el análisis de datos.

### Recomendaciones

Este apartado te servirá para poder aclarar las limitantes de tu trabajo, tratar de indagar más a fondo o simplemente invitar a la audiencia a investigar más sobre el tema tratado. Contar con un apartado de recomendaciones te abre las puertas a futuros análisis y ofrece a la audiencia información suficiente como referencia.

Ahora ya tienes una estructura base con la cual podrás trabajar al momento de hacer storytelling.

Aprovecha el tiempo que tienes frente a tu audiencia y cuenta historias inolvidables.
