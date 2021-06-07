---
layout: default
---

## INTRODUCCIÓN

El objetivo de este documento es informar sobre las emisiones de CO2 y gases de efecto invernadero a lo largo de la historia. El dataset en el que está basado recoge información variada sobre sobre emisiones de dichos gases por país y año. Además, se detalla el origen de dichas emisiones, es decir, si bien estos gases contaminantes que se emiten a la atmósfera provienen de la generación de cemento o de la producción de carbón, etc. También recoge datos sobre las muertes debido a enfermedades respiratorias repartidas por rangos de edad. Si bien es cierto que un fallecimiento por infección respiratoria no tiene por qué estar directamente relacionado con dichas emisiones, nos va a permitir comparar si al menos existe relación visual entre ambas.

Como se especifica en el repositorio, el dataset generado para esta práctica ha resultado de la combinación de tres datasets extraídos de la web Our World in Data [enlace](https://ourworldindata.org/). Our World in Data es una publicación científica online que se centra en problemas globales como puede ser la pobreza, hambre o enfermedades entre muchos otros. Todo su material es de código abierto bajo licencia Creative Commons. Se puede encontrar información sobre los datasets originales al final de este documento, en la sección de agradecimientos.

Se han utilizado diferentes visualizaciones como mapas, gráficas de barras, de líneas etc. para intentar dar respuesta a las distintas preguntas planteadas en la práctica anterior para la creación del dataset, y a las que puedan surgir nuevas. Algunas de las preguntas planteadas con anterioridad son:

> - ¿Qué países del mundo emiten mayor cantidad de CO2 y gases de efecto invernadero?
> - ¿Parece existir relación entre aquellos países con un volumen alto de emisiones de estos gases y las muertes por enfermedades respiratorias?
> - ¿Hay franjas de edad más sensibles a estos gases?
> - ¿Ha aumentado o disminuido la emisión de estos gases nocivos a lo largo de los años?
> - ¿En los últimos años parece que la sociedad ha tomado mayor consciencia sobre el tema del calentamiento global y muchas empresas parecen querer ser más verdes, se ve esto reflejado en los datos? ¿Hay menos emisiones?
> - ¿Qué países emiten los gases más nocivos?

Para ello vamos a repartir el presente documento en 3 partes.

- Emisiones de gases de efecto invernadero a escala global: donde se detallarán, a lo largo de los años, las emisiones totales de los distintos tipos de gases de efecto invernadero presentes en el dataset (CO2, metano y óxido nitroso) a escala global.

- Emisiones de CO2 a lo largo de la historia: el gas de efecto invernadero más presente en la atmósfera es el dióxido de carbono, o CO2. Es por ello, por lo que se ha creado una sección para detallar las emisiones de este tipo de gas.

- Muertes por afecciones respiratorias: como hemos mencionado no sabemos si existe relación entre las muertes por afecciones respiratorias y dichos tipos de gases invernadero. Sí que está probado que la acumulación de dichos gases en la atmósfera influyen en el cambio climático pero se quiere encontrar si se ve algún tipo de relación entre la presencia de dichos gases y las muertes por dichas afecciones.

## EMISIONES DE GASES DE EFECTO INVERNADERO A ESCALA GLOBAL

A estos gases se les conoce con el nombre de gases de efecto invernadero ya que atrapan el calor en la atmósfera influyendo en el cambio climático ya que hacen que la temperatura de la tierra aumente. Si bien es cierto que dichos gases son necesarios para la vida en la tierra ya que mantienen el calor, una alta concentración de los mismos provoca que la temperatura aumente perjudicando a la vida en el planeta. Siendo los gases de efecto invernadero más comunes el dióxido de carbono, el metano y el óxido nitroso[1], vamos a proceder a analizar varias gráficas a cerca de estos gases.

<div class="container-image-right">
    <p>
        En la visualización sobre las emisiones de efecto invernadero se puede apreciar que el dióxido de carbono es el gas más emitido a la atmósfera llegando hasta los 6 billones de toneladas emitidos. Muy por encima de los gases Óxido nitroso y metano. Es por ello que se ha creado un apartado únicamente para este gas en el presente documento.
    </p>
    <div class="container-image-right_title">
        <span>Emisiones de gases de efecto invernadero totales en millones de toneladas</span>
        <center>
            <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story1?:embed=yes&:display_count=yes&:showVizHome=no" width="415" height="300" frameborder="0">
            </iframe>
        </center>
    </div>
</div>

<div class="space"></div>

<div class="container-image-left map">
    <div class="container-image-left_title">
        <span>Emisiones de metano en millones de toneladas por país</span>
        <center>
            <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story2?:embed=yes&:display_count=yes&:showVizHome=no" width="635" height="400" frameborder="0">
            </iframe>
        </center>
    </div>
    <p>
        El mapa nos muestra como han evolucionado las emisiones de metano entre 1990 y 2016, únicos años registrados en el dataset con información sobre este tema.
        En los años 90, los principale emisores de metano eran Estados Unidos, Rusia, Europa y China, tres de las mayores economías del mundo.
        Las emisiones de metano se generan mediante la producción y transporte de carbón, gas natural y petróleo además de las prácticas ganaderas y agrícolas[1]. Basándonos en los datos recogidos de Our World in Data[2], los principales países productores de carne son China, Estados Unidos, Brasil, Rusia, Alemania e India. Lo que excepto alemania, coincide con los países que más gas metano emiten a la atmósfera.
        Cabe destacar la situación de China cuyas emisiones totales en millones de toneladas de gas metano eran de 732 en 1990, y que en un periodo de 26 años casi llega a duplicarlas.
    </p>
</div>

<div class="space"></div>

<div class="container-image-right map">
    <p>
       El óxido nitroso, al igual que el metano, proviene de la combustión de combustibles fósiles, de la producción gandera y agrícola[1]. Es por ello que el mapa tiene similitudes en cuanto a los países con mayor emisión de este gas. 
       Vemos que China, Estados Unidos, Rusia, India y Brasil vuelven a estar a la cabeza en cuanto a emisiones de metano.
       Además también se aprecia como las emisiones aumentan con los años, es decir, se está emitiendo a la atmósfera más óxido nitroso que hace dos décadas.
       Esta vez son China e Indica los dos países que prácticamente han duplicado su emisión de este gas en un periodo de 26 años.
    </p>
    <div class="container-image-right_title">
        <span>Emisiones de óxido nitroso en millones de toneladas por país</span>
        <center>
            <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story3?:embed=yes&:display_count=yes&:showVizHome=no" width="635" height="400" frameborder="0">
            </iframe>
        </center>
    </div>
</div>

<div class="space"></div>

## EMSISIONES DE CO2 A LO LARGO DE LA HISTORIA

De todos los gases de efecto invernadero presente en la atmósfera, el dióxido de carbono está presente en mayor concentración como hemos visto en la visualización: Emisiones de gases de efecto invernadero totales en millones de toneladas.

Mediante las siguientes visualizaciones se pretende ilustrar de manera clara como han evolucionado las emisiones de CO2 desde la revolución industrial inglesa hasta la actualidad, además de señalar que países son los mayores emisores de este gas.

<div class="wrapper">
    <div class="container-image-left map">
        <div class="container-image-left_title">
            <span>Emisiones de CO2 totales por país a lo largo de los años</span>
            <center>
                <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story4?:embed=yes&:display_count=yes&:showVizHome=no" width="635" height="400" frameborder="0">
                </iframe>
            </center>
        </div>
        <p>
            La siguiente visualización se trata de un mapa que presenta las emisiones anuales de dióxido de carbono (CO2) medidas en millones de toneladas por año abarcando desde 1750 hasta 2019.
            La revolución industrial comenzó a mediados del siglo XVII en Reino Unido, es por ello que durante los primeros años de la visualización únicamente hay registro de las emisiones de CO2 emitidas por dicho país hasta 1785. Se considera que anterior a 1750 las emisiones de dióxido de carbono a la atmósfera no eran significantes.
            Se puede ver que durante los 150 años posteriores al origen de la revolución industrial inglesa, se produjo un efecto dominó entre los distintos países del hemisferio norte. La industrialización se fue esparciendo a países como Estados Unidos, Canadá, Europa y Rusia. A partir de 1850 los países del hemisferio sur empezaron a emitir considerables cantidades de CO2 a la atmósfera.
        </p>
    </div>
    <p class="anex-previous">
        A partir de la década de los 60 prácticamente la totalidad de países estaba emitiendo más de 1 millón de toneladas de CO2 por año.
        En 2019, último registro de la base de datos, China está a la cabeza en emisiones, superando los 10 billones de toneladas. Seguida por Estados Unidos con más de 5 billones de toneladas emisiones e Indica con 2,6 billones de toneladas.
    </p>
</div>

<div class="space"></div>

<div class="wrapper">
    <div class="container-image-right lines">
        <p>
            En esta otra visualización se presenta, mediante un gráfico de líneas, las emisiones de CO2 por año, tanto por país como de manera global. 
            Centrándonos en la visualización global, se aprecia que la emisión de gases empieza a incrementar de forma exponencial a raíz del final la segunda guerra mundial, 1945. Es decir, hasta 1945 se habían emitido menos de 20 millones de toneladas por año, pero en los últimos 75 años se ha pasado de 20 a más de 120 millones de toneladas por año.
            Parece ser que a pesar de los múltiples acuerdos y protocolos establecidos para la reducción de distintos gases de tipo invernadero, entre ellos el CO2, implantados en las últimas tres décadas, éstos no están surgiendo efecto. Como se aprecia en la gráfica las emisiones de CO2 siguen al alza incrementando a un ritmo de unos cien millones de toneladas en la última década.
            Pero si analizamos cada país de forma individual vemos que algunos si están reduciendo las emisiones en los últimos años como es el caso de España. Se puede ver que a partir del año 2007. Este cambio es debido al primer periodo de compromiso del Protocolo de Kioto[3], que abarca desde 2008 hasta 2012, en el que los países que se habían acogido a dicho protocolo debían de reducir las emisiones en un 8% respecto a los años 1990-1995.
        </p>
        <div class="container-image-right_title">
            <span>Emisiones de CO2 por año</span>
            <center>
                <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story5?:embed=yes&:display_count=yes&:showVizHome=no" width="510" height="380" frameborder="0">
                </iframe>
            </center>
        </div>
    </div>
    <p class="anex-previous">
        A partir del 2012 empezó lo que se conoce como el segundo periodo de compromiso de dicho protocolo, donde la Unión Europea se ha comprometido a reducir las emisiones de gases de efecto invernadero en un 20% con respecto al año 1990.
        Si observamos la línea para otros países de la Unión Europea, se puede ver que la mayoría cumplen la misma norma de reducción de emisiones en los últimos 15 años.
    </p>
</div>

<div class="space"></div>

<div class="wrapper">
    <div class="container-image-left lines">
        <div class="container-image-left_title">
            <span>Emisiones de CO2 por año de las 10 economías más grandes[4]</span>
            <center>
                <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story6?:embed=yes&:display_count=yes&:showVizHome=no" width="510" height="380" frameborder="0">
                </iframe>
            </center>
        </div>
        <p>
            Para intentar frenar el cambio climático, cuya principal causa son las emisiones de gases de efecto invernadero a la atmósfera, todos los países deberían de poner de su parte para reducir dichas emisiones. Si bien es cierto que los cambios necesarios no suponen el mismo esfuerzo para todos los países además de que no todos lo países emiten la misma cantidad de gases. Véase el caso de China duplicando dichas emisiones con respecto a Estados Unidos.
            En la visualización Emisiones de CO2 por año de las 10 economías más grandes se puede ver, mediante un gráfico de líneas la diferencia de emisiones de los 10 países del mundo más ricos.
            Cabe destacar los casos de China e India, estos dos países siguen aumentando en la actualidad la cantidad de emisiones de CO2 mientras que el resto de los países que aparecen la lista, las han reducido en los últimos 5 años, exceptuando Canadá, cuyo total de emisiones se mantiene constante con respecto a años anteriores.
        </p>
    </div>
</div>

<div class="space"></div>

<div class="wrapper">
    <div class="container-image-right multiple-lines">
        <p>
            En esta otra visualización se quiere comparar de donde proceden las emisiones de CO2 sin distinguir países. El esfuerzo en la reducción de emisiones no tiene que ser únicamente de los países en sí,  las empresas deberían esforzarse por reducir dichas emisiones también. Al analizar la procedencia de dichos gases se pueden crear acciones específicas para las compañías que producen la mayor parte de los gases. 
            Analizando la gráfica se puede ver que la procedencia de las emisiones de CO2 se debe al carbón cuyo uso para la generación de electricidad, entre otras cosas, sigue siendo muy extendido. 
            Llama la atención también el pico y la drástica caída en la gráfica de las emisiones de CO2 debido a la quema de gas natural. Este pico abarca los años 70 y a partir de los años 80 es cuando se produce la caída. Esto puede estar relacionado con la prohibición de quemar el gas por parte de Noruega en esa época. Impuso restricciones a las distintas compañías que extraían petróleo en el mar del Norte lo que redujo las emisiones por quema en una gran cantidad[5]. 
            Al observar las gráficas en conjunto, en todas ellas se puede apreciar un salto al alza, en torno al año 2016. En noviembre de ese mismo año, la Organización de países exportadores de Petróleo (OPEP) cortó su producción en Noviembre[6]. Esto puede indicar que los países productores de petróleo supieran de antemano lo que iba a ocurrir, por lo que aumentaron la producción antes de que se produjera dicha restricción para así tener reservas de crudo y poder hacer frente a la demanda.
        </p>
        <div class="container-image-right_title">
            <span>Procedencia de las emisiones de CO2 a escala global</span>
            <center>
                <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story7?:embed=yes&:display_count=yes&:showVizHome=no" width="650" height="700" frameborder="0">
                </iframe>
            </center>
        </div>
    </div>
</div>

<div class="space"></div>

## MUERTES POR AFECCIONES RESPIRATORIAS 

<div class="wrapper">
    <div class="container-image-left map">
        <div class="container-image-left_title">
            <span>Índice de mortalidad por país por cada 100,000 personas</span>
            <center>
                <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story8?:embed=yes&:display_count=yes&:showVizHome=no" width="635" height="400" frameborder="0">
                </iframe>
            </center>
        </div>
        <p>
            En este mapa se representa la evolución del índice de mortalidad debido a infecciones respiratorias entre los años 1990 y 2017 en los distintos países del mundo. El dataset recoge datos de dichos fallecimientos a partir de 1990 hasta 2017 únicamente, de ahí que la gráfica empiece y termine en esos años.
            Se puede ver como a comienzo de la década de los 90 la incidencia es alta, sobre todo en la región de Asia, África, América del Sur y Europa del este. Conforme avanzan las décadas, el índice de mortalidad desciende considerablemente en los países de América del sur y Europa llegando a reducirse hasta un cuarto en este último comparado con 1990.
            En general, en los últimos 30 años, se produce un descenso del índice de mortalidad en la totalidad de países, aunque las cifras siguen siendo elevadas en la zona asiática y africana llamando la atención sobre todo las cifras de Papua Nueva Guinea.
        </p>
    </div>
    <p class="anex-previous">
        Si comparamos con el mapa Emisiones de CO2 totales por país a lo largo de los años, no se pueden apreciar coincidencias entre ambos mapas. Si tomamos el ejemplo de India, en los últimos años las emisiones de CO2 a la atmósfera han ido aumentando, sin embargo las muertes por causas respiratorias han ido disminuyendo. Por lo tanto, según los datos parece no haber relación, al menos a gran escala, entre las emisiones de CO2 y los fallecimientos por causas respiratorias.
    </p>
</div>

<div class="space"></div>

<div class="wrapper">
    <div class="container-image-right lines">
        <p>
            La siguiente es una visualización simple para ayudar al lector a comprender como han evolucionado las muertes debido a infecciones respiratorias en base a los distintos rangos de edad. 
            Se puede apreciar que las muertes por enfermedades respiratorias afecta principalmente a los grupos de más riesgo en general como son las personas mayores de 70 años y los niños de menos de 5 años, siendo estos últimos los más perjudicados. 
            Un punto positivo se ve en el rápido descenso en el índice de mortalidad para los dos grupos de más riesgo en los últimos 30 años situándose ambos índices en torno a los 100 fallecimientos por cada 100,000 personas. Bien es cierto que todavía dobla en cantidad al resto de los rangos de edad.
            Si comparamos los resultados de esta gráfica con lo que hemos visto en la visualización Emisiones de CO2 por año, vemos que no siguen la misma tendencia, mientras que las emisiones de CO2 no han parado de incrementarse, las muertes por infecciones respiratorias han decrecido, esto parece indicar de nuevo que no hay una relación entre ambos tópicos. 
        </p>
        <div class="container-image-right_title">
            <span>Índice de mortalidad por rangos de edad desde 1990 hasta 2019</span>
            <center>
                <iframe src="https://public.tableau.com/views/Book2_16223023474650/Story9?:embed=yes&:display_count=yes&:showVizHome=no" width="510" height="380" frameborder="0">
                </iframe>
            </center>
        </div>
    </div>
</div>

<div class="space"></div>

## CONCLUSIONES 


<div class="space"></div>

## AGRADECIMIENTOS

- Our World in data por proveer acceso a los distintos datasets en los que se basa esta práctica.
- Data on CO2 and Greenhouse Gas Emissions repositorio de datos coleccionado, limpiado y documentado por Hannah Ritchie, Max Roser and Edouard Mathieu para Our World in Data [enlace](https://github.com/owid/co2-data)
- DEATHS - CHRONIC RESPIRATORY DISEASES - SEX: BOTH - AGE: AGE-STANDARDIZED (RATE), datos recogidos por Our
World in Data [enlace](https://ourworldindata.org/grapher/respiratory-disease-death-rate) y publicados por Global Burden of Disease Collaborative Network. Global Burden of Disease Study 2017 (GBD 2017) Results. Seattle, United States: Institute for Health Metrics and Evaluation (IHME), 2018.
- DEATHS - UPPER RESPIRATORY INFECTIONS - SEX: BOTH - AGE: 50-69 YEARS (RATE), DEATHS - UPPER RESPIRATORY INFECTIONS - SEX: BOTH - AGE: UNDER 5 (RATE), DEATHS - UPPER RESPIRATORY INFECTIONS - SEX: BOTH - AGE: 70+ YEARS (RATE), DEATHS - UPPER RESPIRATORY INFECTIONS - SEX: BOTH - AGE: 5-14 YEARS (RATE), DEATHS - UPPER RESPIRATORY INFECTIONS - SEX: BOTH - AGE: 15-49 YEARS (RATE), datos recogidos por Our World in Data [enlace](https://ourworldindata.org/grapher/death-rate-upper-respiratory-age?country=~OWID_WRL) y publicados por Global Burden of Disease Collaborative Network. Global Burden of Disease Study 2017 (GBD 2017) Results. Seattle, United States: Institute for Health Metrics and Evaluation (IHME), 2018.

<div class="space"></div>

## RECURSOS

1. Descripción general de los gases de efecto invernadero - Agencia de Protección Ambiental de Estados Unidos. [enlace](https://espanol.epa.gov/la-energia-y-el-medioambiente/descripcion-general-de-los-gases-de-efecto-invernadero)
2. Meat and Dairy Production - Hannah Ritchie and Max Rose from Our World in Data. [enlace](https://ourworldindata.org/meat-production#:~:text=The%20United%20States%20is%20the,by%20Argentina%2C%20Australia%20and%20India).
3. Objetivos de reducción de emisiones de gases de efecto invernadero - Ministerio para la Transición Ecológica y el Reto Demográfico. [enlace](https://www.miteco.gob.es/es/cambio-climatico/temas/mitigacion-politicas-y-medidas/objetivos.aspx)
4. World GDP Ranking 2020, GDP by Country, Data and Charts, Knoema - [enlace](https://knoema.com/nwnfkne/world-gdp-ranking-2020-gdp-by-country-data-and-charts)
5. The politics of Methane – Barry G. Rabe. [enlace](https://www.brookings.edu/blog/fixgov/2019/07/08/the-politics-of-methane/)
6. Five events that shook world economy in 2016 – Rajesh Dutt. [enlace](https://economictimes.indiatimes.com/news/international/business/five-events-that-shook-world-economy-in-2016/articleshow/56182833.cms)