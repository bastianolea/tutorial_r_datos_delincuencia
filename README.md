# Scraping de estadísticas delictuales del Centro de Estudios y Análisis del Delito con R
Por Bastián Olea Herrera

En este script se detalla cómo descargar datos históricos de estadísticas delictuales del Centro de Estudios y Análisis del Delito (CEAD) de Chile utilizando técnicas de web scraping en R. 

El proceso implica analizar el funcionamiento del sitio web de CEAD para poder replicar su método de solicitud de datos en R, y así acceder de forma directa en R a los datos que necesitemos desde el sitio, sin necesidad de entrar al sitio web ni realizar operaciones manuales. Esto resulta conveniente dado que puede ser engorroso utilizar la interfaz del sitio web de CEAD para obtener los datos manualmente, o bien, si se necesita obtener un gran volumen de datos desde el sitio. Por lo demás, obtener los datos de forma manual mediante el sitio web no es una práctica reproducible, mientras que siguiendo estas instrucciones obtenemos un conjunto de funciones que hacen que el proceso de obtención de estadísticas delictuales sea automático, reproducible y sencillo.

Las estadísticas disponibles en el [sitio web de CEAD](https://cead.spd.gov.cl/estadisticas-delictuales/) corresponden a los siguientes datos oficiales: Estadísticas Oficiales de Delitos de Mayor Connotación Social (DMCS), Violencia Intrafamiliar (VIF), Incivilidades y otros hechos informados por Carabineros y la Policía de Investigaciones de Chile al Ministerio del Interior y Seguridad Pública.

Accede al [tutorial de web scraping de datos de delincuencia en este enlace](https://bastianolea.github.io/tutorial_r_datos_delincuencia/)
