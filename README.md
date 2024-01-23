# ETL- Data Analytics - Agricultura

El siguiente proyecto fue realizado para www.infodash.org

El objetivo fue realizar una busqueda de datos sobre el sector agricola de Argentina para luego poder crear un tablero de Power Bi para visualizar la información.

## Trabajo sobre los datos
Para el trabajo se utilizan dos fuentes de datos distintas.
  - Datos del sector agrícola
  - Datos sobre geolocalización

Los datos sobre el sector agropecuario con los que se trabaja son de caracter público y se pueden acceder desde el siguiente link 
- https://geoportal.magyp.gob.ar/tematizador/agricola/

Los datos de geolocalización también son de carácter público y se obtienen desde la siguiente API
- https://apis.datos.gob.ar/georef/api/departamentos

El uso de dos fuentes para obtener la información se debe a que los datos de agricultura están desagregados por localidades y provincias pero no tienen las coordenadas. Es por eso que se decide incorporar las mismas desde otro archivo para luego poder crear mapas en Power Bi con esas referencias.

Una vez obtenidos los datos se procede a realizar el trabajo de ETL con Python usando la librería pandas.

## Tablero de Power Bi

Con los datos obtenidos se crea un tablero interactivo con Power Bi para que se pueda acceder de manera más simple a la información

![img_04](/src/estimacionesAgricolas_04.jpg)
