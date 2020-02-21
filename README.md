# Uso de Generador template HTML para Documentación de API con especificación Swagger YAML



### Para el uso de la aplicación que genera un template HTML con el contenido de la documentación de una API a partir de la especificación en formato Swagger versión 2.0 con archivo YAML, se debe: 



1.- Instalar la librería/dependencia PyYAML en su última versión, ello con el siguiente comando:
`pip3 install -U PyYAML` o `pip install -U PyYAML` dependiendo de la versión de Python que se quiera usar (Python 3.X or later para pip3 o Python 2.X or earlier para pip)



2.- Ejecutar en la consola de comandos en la ruta del programa 

             `../api_yaml_html_converter/swagger-yaml-to-html.py` o 
             `../api_yaml_html_converter/yaml-to-html-swagger.py`

> El primero crea el template HTML con la documentación, teniendo el posible BUG de no contener todos los íconos Swagger.
> El segundo programa, corrige el incidente de los íconos y contiene más CSS



* Para crear un template HTML con estos comandos, es necesario ejecutar:

      `python3 swagger-yaml-to-html.py < espec_doc.yml > api_doc.html`  o
      `python3 yaml-to-html-swagger.py < espec_doc.yml > api_doc.html` 
 



