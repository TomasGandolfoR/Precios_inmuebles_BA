# Precios de los inmuebles en Buenos Aires
## comprensión comercial
En este caso hipotético, la empresa Properati solicita que con sus datos recolectados se implementen soluciones de ciencia de datos para facilitar la labor de sus tasadores.

Según la página oficial de la empresa:
>La **misión** de Properati es empoderar a nuestros usuarios para que tengan el mejor camino a su próxima casa, mediante herramientas tecnológicas y datos relevantes. En paralelo, buscamos ayudar a los vendedores a que sean más eficientes y brinden el mejor servicio posible a los potenciales compradores.

>**Visión**: Ser la plataforma de inmuebles más enfocada en el usuario del mundo, sin importar dónde se encuentre. Tenemos un horizonte global, pero también la versatilidad necesaria para satisfacer las necesidades locales.

Adicionalmente:
>*Quienes busquen un nuevo hogar o quieran invertir* en propiedades encontrarán en Properati, además de las ofertas disponibles, valiosa información para tomar las mejores decisiones: promedios de precios, características de los barrios, comparaciones, etc.
>Properati también ofrece una propuesta novedosa para las *inmobiliarias o agentes* que quieran vender una propiedad, ya que el modelo de negocios se basa en entregar contactos de calidad.

Vemos que Properati brinda servicio tanto a compradores como vendedores. Entre estos servicios está el proporcionar información valiosa y de calidad para facilitar una correcta toma de decisiones, incluyendo los precios. Por lo que comprender cuáles son las variables que más influyen en éstos y a su vez poder estimar cuál sería el precio más probable o acorde para una determinada propiedad, es sin dudas valioso para los fines del negocio.

**El presente proyecto se propone los siguientes objetivos:**
* Determinar cuáles son las variables que determinan los precios.
* Desarrollar los modelos de asignación de precios.

El **alcance del proyecto** comprende los bienes inmueble del tipo PH, casas y departamentos en la Ciudad Autónoma de Buenos Aires. Entre el 01/01/2019 y el 25/01/2020.

Los datos fueron obtenidos por la página oficial de Properati, pre-filtrados por Acámica.

## Orden del repositorio
En el notebook 'EDA.ipynb' se realiza el análisis exploratorio de los datos junto con los modelos iniciales, con los que se establece un punto de partida para tener como referencia en los próximos modelos.

En el notebook 'Model.ipynb' se realiza el modelado y el procesamiento de features con ayuda de lo desarrollado en el EDA, se establece el modelo y conclusiones finales.

Para aquellos que además de visualizar deseen ejecutar el código, los datos pueden descargarlos [aquí](https://drive.google.com/file/d/1AjaUAYMrzpBHHr31aqvNFnhzCQOgrPtH/view?usp=sharing)


