# Código para recopilar información meteorológica de la página [www.ogimet.com](www.ogimet.com).

Guía para manejarse en la página:

- En la sección "Consulta de indicativos de estaciones meteorológicas de todo el mundo" se puede obtener el indicativo correspondiente a la estación meteorológica deseada.

Por ejemplo, para la ciudad de Córdoba, los indicativos son:

- 87344 -> Córdoba Aerodrome
        
- 87345 -> Córdoba Observatorio
   
En la sección "Resúmenes diarios Ogimet" se puede obtener un resumen diario en formato tabla para la estación meteorológica deseada, de acuerdo con su indicativo.

Este código realiza webscrapping para obtener los datos correspondientes a la tabla.

**Ejecución:**

``python ogimet_scraper.py``

(El dataset generado se guardará en formato ``.csv``, en el mismo directorio que el ``.py``)

En caso de querer cambiar el año de los datos del clima, modificar la variable ``year = 2018`` (línea 37) con el año deseado.
