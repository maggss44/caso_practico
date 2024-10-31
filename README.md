# Caso_practico
Análisis de fraude en tarjetas de crédito.

En este repo se encuentra todo lo necesarios para ejecutar el proyecto, el ambiente de conda esta en el root bajo el nombre environment.yml
Los datos no están disponibles en github, por lo que el usuario deberá crear la carpeta data en el root del repo y cargar ahí el archivo csv.
Es importante primero ejecutar el notebook eda.ipynb anste de ejecutar el notebook modelos.ipynb

Hay dos notebooks en el root del repo:
- eda.ipynb contiene el análisis exploratorio y la selección de variables.
- models.ipynb contiene los modelos y está separado en dos secciones:
    - Modelos de prueba: donde hago pruebas en modelos lineale referentes a el uso del dataset desbalanceado, sobremuestreado usando SMOTE y submuestrado removiendo datos de la clase mayoritaria.
    - Actual models: despues de elegir como quiero utilizar el dataset (submuestrado), procedo a ajustar tres modelos diferentes con esos datos.
