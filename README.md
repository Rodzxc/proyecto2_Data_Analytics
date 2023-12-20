## Proyecto Individual N°2

##  Data Analytics

¡Bienvenidos a mi proyecto individual de Data Analytics!

### Descripción del proyecto
En este proyecto se asume el rol de un Data Analyst cuyo trabajo es realizar un análisis sobre un dataset de accidentes aéreos, para posteriormente disponibilizar la información en un dashboard interactivo utilizando Power BI.

### Contexto

Los riesgos asociados a las activiades aeronáuticas conllevan consecuencias que pueden ser catastróficas en términos de vidas humanas y pérdidas económicas. Por ello, es crucial investigar las causas de estos accidentes y aprender a prevenirlos y mitigar los efectos en el futuro aumentando los indices de seguridad.

### Objetivo

- Realizar un análisis exploratorio de los datos en un notebook.
- Realizar un dashboard funcional y coherente con el storytelling.
- Establecer conclusiones.
- Graficar y medir 2 KPIs, uno planteado en las consignas y el otro propuesto.
  1. Evaluar la disminución de un 10% la tasa de fatalidad de la tripulación en los últimos 10 años, comparado a la década anterior.
  2. Evaluar la disminución de un 5% la tasa promedio de supervivientes de los últimos 5 años, comparado con los 5 años anteriores.
- Read me con un reporte de análisis con base en los dashboards.

### Repositorio y archivos relevantes

En el repositorio de GitHub - Rodzxc/Proyecto2_Data_Analytics, puedes encontrar los siguientes archivos relevantes:

accidentes_aereos.ipynb: Contiene los códigos y las visualizaciones generadas durante el proceso de transformación, limpieza y el análisis exploratorio de datos.

accidentes_aereos.csv: Dataset sobre datos de accidentes de aviones, desde 1908 hasta 2021.

accidentes_aereos.pbix: Dashboard del proyecto, contiene 1 portada y 4 páginas navegables sobre los análisis y los KPIs.

### Repote del análisis 

### 1.País

En la página País, se pueden observar los accidentes segmentados por país.<br>
Se puede filtrar según el año, país, personas a bordo y la categoría de la aeronave.<br>
Se brinda información acerca la cantidad de accidentes, un promedio de la tasa de supervivencia y del total de personas a bordo por vuelo.<br>
Las diferentes gráficas permiten apreciar que Estados Unidos (USA) es el país con más cantidad de accidentes y con más fatalidades, seguida por Rusia.

### 2.Operador

En la página Operador, se pueden observar los accidentes segmentados por operador/empresa.<br>
Se puede filtrar según el año, país, operador, personas a bordo y la categoría de la aeronave.<br>
Se brinda información acerca la cantidad de accidentes, un promedio de los pasajeros por vuelo y la tasa de supervivencia.<br>
Las gráficas permiten apreciar que Aeroflot es la empresa con más cantidad de accidentes, seguida por la fuerza aérea estadounidense (U.S. Air Force). Ademàs, otras operadoras de este paìs se encuentran dentro del Top 6. 

### 3.Aeronaves

En la página Aeronave, se pueden observar los accidentes segmentados por aeronaves, tanto en su categoría (avión, helicòptero y globo dirigible) como en su tipo (marca / modelo).<br>
Se puede filtrar según el año, país, tipo, personas a bordo y la categoría de la aeronave.<br>
Se brinda información acerca la cantidad de accidentes, diferentes tipos de aeronaves y la tasa de supervivencia.<br>
Las gráficas permiten apreciar que la mayoría de los accidentes son provocados por aviones y una lista de aeronaves con más accidentes.

### Conclusión
Interpolando la lista de aeronaves con más accidentes, las operadoras con más accidentes (Aeroflot,  U.S Air Force, United Air Lines y U.S. Army Air Force); se llega a la conclusión de que estas responden en parte a la cantidad de accidentes en los Estados Unidos y Rusia.<br>
Se mantienen marcadas tendencias a la baja en los últimos años, tanto a nivel mundial como en Estados Unidos y Rusia.<br>
El factor climático no es relevante en los accidentes de las aeronaves menos inestables como los helicópteros. 
Por último, los objetivos propuestos para los KPIs develan que son históricamente difíciles de superar y sostener a lo largo de los años; y en los años más recientes, los valores no llegan a los objetivos.


<section id="celda1">
        <div class="contenedor">
            <p>
                <iframe title="GestionDeStock" width="1220" height="710" src="https://app.powerbi.com/view?r=eyJrIjoiMTY3NTQ4YWYtOTU1OS00Yzk5LThmYjMtMjFkOTQwM2Y3MWZhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&amp;pageName=ReportSection" frameborder="0" allowfullscreen="true"></iframe>
            </p>
        </div>
        <div class="text">
            <h2>Análisis de Pareto:</h2><br>
            <p>
                Listado y gráficas para determinar un criterio tipo ABCD según las cantidades vendidas, los ingresos de ventas y los precios de los artículos en stock.
            </p>
        </div>
    </section>
