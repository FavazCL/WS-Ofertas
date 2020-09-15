# Web Scrapping de Portales de Empleo

En este repositorio encontrará toda la información relacionadas a ofertas de trabajo provenientes de los siguientes portales:

1. **Chiletrabajos.cl** - OK

2. **Laborum.cl** - OK

3. **bne.cl** - OK

Se almacenaran de la siguiente manera:

> *nombre-portal*/*nombre-archivo.json*

La extracción se realizará automaticamente en los siguientes horarios:

* **17:45** > Chiletrabajos.cl > *Esto se debe a que la zona horaria del portal no es la de "America/Santiago" y existen varias horas de diferencia.*

* **17:45** > Laborum.cl 

* **17:45** > Bne.cl

Luego de las extracciones se hace un consolidado de todas las ofertas el día actual, y se almacenan en:

> consolidado/*consolidado-fecha*

Para poder visualizar de mejor manera los archivos **.json** puede utilizar esta web: https://jsonformatter.curiousconcept.com/
