#EDA(Análisis Exploratorio de Datos ) Word

[FALTAIntroducción]

El objetivo consiste en investigar, entender y poner en practica el ciclo de vida de los datos.
Al finalizar el proyecto se realizará un analisis de resultados, el exito se determinarán segun el grado de comprensión, ejecución y documentación de las competencias necesarias para resolver cada paso realizado.

El proyecto se dividirá en X pasos:

1. Busqueda De Información y datasets
2. Organización de los datos y la información recopilada
3. Normalización de los datos utiles en un mismo dataset
4. Representar las relaciones de los datos mediante Weka y PowerBI
5. Elavorar un análisis de los resultados
6. Establecer 3 conclusiones interesantes
7. Desarrollar consultar los datos y confirmar (facilmente) las conclusiones propuestas.
8. Redactar articulo que incluya conclusiones y recursos tecnicos mencionados.
9. Evaluación de competencias adquiridas



1. 

Para realizar este proyecto se recopilarán metricas sobre los paises. 

Aunque el paso 2 ya consiste, integramente, en organizar los datos; a la hora de recopilar información y datasets debemos organizar los datos que esperamos encontrar, estableciendo un punto de partida para la busqueda.

Por ello se plantea la siguiente categorización de la información a recabar de cada pais:

Categorías:

1.  Socioeconómica:
    - PIB per cápita
    - Índice de Desarrollo Humano (IDH)
    - Tasa de Desempleo
    - Tasa de pobreza
2.  Demográfica:
    - Población Total
    - Esperanza de vida al nacer
    - Tasa de natalidad/mortalidad
    - Crecimiento poblacional
    - Distribución etaria
3.  Medioambiental:
    - Emisiones de CO2 per cápita
    - Índice de sostenibilidad ambiental
    - Biodiversidad y áreas protegidas
    - Consumo de energía per cápita
    - Acceso a agua potable
4.  Tecnológica y de Innovación:
    - Índice de Innovación Global
    - Acceso a Internet
    - Usuarios de teléfonos móviles per cápita
    - Inversión en I+D
5.  Salud:
    - Gasto en salud per cápita
    - Cobertura de vacunación
    - Prevalencia de enfermedades crónicas
    - Tasa de mortalidad infantil
    - Número de médicos por cada mil habitantes
6.  Política:
    - Índice de Democracia
    - Libertad de prensa
    - Índice de corrupción
    - Estabilidad política
7.  Educación:
    - Tasa de alfabetización
    - Tasa de matriculación en educación primaria/ secundaria/superior
    - Gasto en educación como porcentaje del PIB
    - Número de años promedio de escolaridad
8.  Transporte e Infraestructura:
    - Kilómetros de carretera per cápita
    - Cantidad de aeropuertos internacionales
    - Número de vehículos per cápita
    - Acceso a electricidad
9.  Cultural:
    - Número de sitios patrimonio de la humanidad (UNESCO)
    - Diversidad lingüística
    - Índice de felicidad
    - Gasto en cultura y recreación
10.  Seguridad y Crimen:
    - Tasa de homicidios por cada 100.000 habitantes
    - Índice de criminalidad
    - Gasto en defensa y seguridad

Los datos de analisis se recopilaran desde webs que ofrezcan recursos gratuitos online.

La referencia inicial es kaggle, tal y como dice datascientest.com, "Kaggle es una plataforma web que reúne la comunidad Data Science más grande del mundo", por lo tanto es un buen lugar donde descargar y comparar la consistencia de datasets. 

Aun así siempre es recomendable investigar multiples opciones antes de limitarse a una unica herramienta o plataforma. La eleccion de fuentes es más efectiva cuando tiene en cuenta que datos se buscan, relacionados con paises en este caso. 
Aquí las plataformas mas interesantes tras la investigación:

https://datasetsearch.research.google.com/

https://datasetsearch.research.google.com/search?src=0&query=by%20country&docid=L2cvMTFsZHE4emQzeA%3D%3D
https://www.theglobaleconomy.com/rankings/Inflation/






https://analisisdatos.blog/data-sets-20-sitios-para-descargar-datos/

Google Dataset Search:
Es una herramienta que permite encontrar datasets almacenados en diferentes sitios web de todo el mundo. Su interfaz amigable facilita la búsqueda de datos sobre una amplia gama de temas.
    URL: datasetsearch.research.google.com

Kaggle Datasets:
    Es una comunidad en línea donde los científicos de datos y los entusiastas del machine learning pueden encontrar, descargar y publicar datasets. También proporciona competencias y tutoriales para mejorar tus habilidades en ciencia de datos.
    URL: www.kaggle.com/datasets

Awesome Public Datasets en GitHub:
    Este repositorio en GitHub contiene una lista curada de datasets disponibles públicamente en una variedad de temas. Es una excelente fuente de datos para aquellos interesados en explorar diferentes dominios.
    URL: github.com/awesomedata/awesome-public-datasets

UN Data:
    Ofrece una visualización de todos los datos públicos recolectados por las Naciones Unidas, proporcionando una fuente valiosa de información sobre temas globales.
    URL: data.un.org

World Bank Data:
    No sólo proporciona datos relacionados con la economía de los países, sino también una gran cantidad de datos sobre salud, educación, ciencia y tecnología.
    URL: data.worldbank.org

Datos.gob.es:
    Encuentra datos públicos recolectados por el gobierno español. También permite el acceso a datasets de otros gobiernos, convirtiéndose en una forma de acceder a datasets gratuitos.
    URL: datos.gob.es

Google Public Data:
    A través de esta plataforma, Google ofrece datos que se pueden encontrar en otros datasets. Es interesante para explorar colecciones de datos de diferentes dominios.
    URL: www.google.com/publicdata

OpenCorporates:
    Se autodenomina como el mayor dataset de empresas, proporcionando datos de cualquier empresa del mundo. Es necesario registrarse para acceder a la información.
    URL: opencorporates.com

API de Instagram:
    Especialmente útil para profesionales de marketing, esta API permite obtener información de otros usuarios y creadores de Instagram o medir la interacción con los perfiles.
    URL: developers.facebook.com

Organización Mundial de la Salud (OMS):
    Comparte datos públicos de todos los países sobre salud infantil, medicamentos esenciales, COVID-19, malaria, entre otros temas relacionados con la salud.
    URL: www.who.int

OpenAQ:
    Su misión es combatir la contaminación del aire, ofreciendo un dataset de calidad del aire de fuentes públicas proporcionadas por el gobierno y otras entidades.
    URL: openaq.org

FiveThirtyEight:
    Recoge datos utilizados para análisis y storytelling, compartiendo posteriormente todos los datos recogidos para ser totalmente transparentes.
    URL: data.fivethirtyeight.com

UCI Machine Learning Repository:
    Este repositorio es una colección de bases de datos, implementaciones de algoritmos y conjuntos de datos para el aprendizaje automático.
    URL: archive.ics.uci.edu/ml

Amazon AWS Public Datasets:
    Amazon ofrece una variedad de datasets públicos que cualquier persona puede acceder y utilizar, abarcando una amplia gama de temas y disciplinas.
    URL: registry.opendata.aws

Reddit Datasets Subreddit:
    Una comunidad de Reddit donde los usuarios comparten y discuten sobre datasets interesantes y útiles.
    URL: www.reddit.com/r/datasets

Data.gov:
    Plataforma del gobierno de EE.UU. que proporciona acceso a muchos datasets sobre una variedad de temas.
    URL: www.data.gov

European Union Open Data Portal:
    Proporciona acceso a datasets públicos de la Unión Europea sobre una variedad de temas.
    URL: data.europa.eu

Data & Sons:
    Plataforma que permite comprar, vender y compartir datasets.
URL: dataandsons.com

Quandl:
Ofrece una amplia gama de datos financieros, económicos y alternativos, facilitando la obtención de datos para análisis financiero.
URL: www.quandl.com

DataHub:
Plataforma que proporciona acceso a muchos datasets de alta calidad sobre una variedad de temas.
URL: datahub.io

https://iddigitalschool.com/bootcamps/10-sitios-donde-descargar-datasets-de-calidad/

UCI Machine Learning Repository: La Universidad de California, Irvine, proporciona un repositorio extenso con datasets utilizados comúnmente en la investigación de machine learning. Cubre una amplia gama de temas, desde finanzas hasta biología.

Google Dataset Search: Esta herramienta de Google facilita la búsqueda de datasets en la web. Permite filtrar por diferentes tipos de archivos y temas, proporcionando enlaces directos a los conjuntos de datos.

Data.gov: El portal oficial de datos abiertos del gobierno de los Estados Unidos. Ofrece acceso a una gran cantidad de datos gubernamentales en áreas como salud, educación, medio ambiente y más.

Awesome Public Datasets GitHub Repo: Este repositorio en GitHub recopila una lista impresionante de datasets públicos organizados por categorías. Es una excelente fuente para descubrir datasets interesantes y diversos.

Open Data Portal: Numerosos países y ciudades tienen sus propios portales de datos abiertos. Ejemplos incluyen el Portal Europeo de Datos y el Portal de Datos Abiertos de Nueva York. Explora los portales locales para acceder a información específica de regiones.

Amazon AWS Datasets: Amazon Web Services (AWS) ofrece una colección de datasets públicos que se pueden acceder fácilmente a través de su plataforma. Esto incluye datos en áreas como biología, finanzas y geociencias.

UNICEF Data: UNICEF proporciona datasets relacionados con la infancia y el desarrollo en todo el mundo. Estos datos pueden ser valiosos para proyectos centrados en la mejora de la calidad de vida de los niños.

Enigma Public: Enigma Public es una plataforma que agrega y cura datos de fuentes públicas y privadas. Ofrece una amplia variedad de datos en áreas como economía, energía y salud.

World Bank Open Data: El Banco Mundial ofrece acceso a una amplia gama de indicadores económicos y sociales de países de todo el mundo. Es una fuente valiosa para proyectos relacionados con el desarrollo global.


https://bigdatamagazine.es/10-sitios-donde-encontrar-data-sets-gratuitos/
https://www.interviewquery.com/p/free-datasets
https://careerfoundry.com/en/blog/data-analytics/where-to-find-free-datasets/


Aquí algunos articulos que recopilan las plataformas mas usadas:
https://analisisdatos.blog/data-sets-20-sitios-para-descargar-datos/
https://iddigitalschool.com/bootcamps/10-sitios-donde-descargar-datasets-de-calidad/
https://bigdatamagazine.es/10-sitios-donde-encontrar-data-sets-gratuitos/
https://www.interviewquery.com/p/free-datasets
https://careerfoundry.com/en/blog/data-analytics/where-to-find-free-datasets/


https://datascientest.com/

La busqueda de información se realizará mediante la plataforma kaggle:


1.  Socioeconómica:
    - PIB per cápita
    - Índice de Desarrollo Humano (IDH)
    - Tasa de Desempleo
    - Tasa de pobreza
    - Coeficiente de Gini
2.  Demográfica:
    - Población Total
    - Esperanza de vida al nacer
    - Tasa de natalidad/mortalidad
    - Crecimiento poblacional
    - Distribución etaria
3.  Medioambiental:
    - Emisiones de CO2 per cápita
    - Índice de sostenibilidad ambiental
    - Biodiversidad y áreas protegidas
    - Consumo de energía per cápita
    - Acceso a agua potable
4.  Tecnológica y de Innovación:
    - Índice de Innovación Global
    - Acceso a Internet
    - Usuarios de teléfonos móviles per cápita
    - Inversión en I+D
5.  Salud:
    - Gasto en salud per cápita
    - Cobertura de vacunación
    - Prevalencia de enfermedades crónicas
    - Tasa de mortalidad infantil
    - Número de médicos por cada mil habitantes
6.  Política:
    - Índice de Democracia
    - Libertad de prensa
    - Índice de corrupción
    - Estabilidad política
7.  Educación:
    - Tasa de alfabetización
    - Tasa de matriculación en educación primaria/ secundaria/superior
    - Gasto en educación como porcentaje del PIB
    - Número de años promedio de escolaridad
8.  Transporte e Infraestructura:
    - Kilómetros de carretera per cápita
    - Cantidad de aeropuertos internacionales
    - Número de vehículos per cápita
    - Acceso a electricidad
9.  Cultural:
    - Número de sitios patrimonio de la humanidad (UNESCO)
    - Diversidad lingüística
    - Índice de felicidad
    - Gasto en cultura y recreación
10.  Seguridad y Crimen:
    - Tasa de homicidios por cada 100.000 habitantes
    - Índice de criminalidad
    - Gasto en defensa y seguridad
