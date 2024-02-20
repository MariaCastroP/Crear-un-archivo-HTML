# Metadatos

Los metadatos dentro de documentos HTML son datos (información) sobre datos. <br> 
Se utilizan tipicamente para especificar caracteres, descripciones, tipos de vista, estilos, titulos.<br> 
Los metadatos no son especificamente desplegados en la página pero si analizados y decodificados por la máquina. <br> 

~~~html
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
~~~
Este elemento simplemente especifica la codificación de caracteres del documento, es decir, el conjunto de caracteres que el documento puede usar.<br>
```utf-8``` es un conjunto de caracteres universal que incluye casi todos los caracteres de casi cualquier idioma humano. <br>
```content=text/html``` Especifica el valor asociado con el atributo en este caso texto en formato html. <br>
```http-equiv="Content-Type"``` este atributo provee un Encabezado HTTP para la información de contenido. 

~~~html
var theTreeAsJsonObject = 
       [ 
           {"data": {"title": "3 CALIBRACION DE EQUIPOS"}, "children": 
            [
                  {"metadata": {"href": "Proceso_de_calibracion_CYATAM"}, "data": {"title": "Proceso de calibracion"}, "attr": {"id": "uy0000"}},
                  {"metadata": {"href": "Certificados"}, "data": {"title": "Certificados de calibracion"}, "attr": {"id": "uy0001"}},
                          
             ],"attr": {"id": "uy0002"}},                         
         
      ];
~~~
Los objetos JSON tienen la facilidad de leerse o interpretarse como cadena. Un árbol de programación es como su nombre lo indica una ramificación de datos, veamoslo como un arbol genealogico que conforme va creciendo los papás tienen a sus hijos y los hijos más hijos que le pertenecen. La estructura de arriba 👆🏽👆🏽 ejemplifica perfectamente las ramificaciones de las que hablabamos.  <br>
En la primera parte esta la declaracion del objeto JSON como arbol  ```var theTreeAsJsonObject = ``` , <br>
posteriormente tenemos las ramificaciones ```{ "data": {"title": "1 Titulo_de_la_carpeta "}``` <br>
y sus nombrados "hijos"  ```{"metadata":{"href": Documento_ligado "},"data": {"title": "Titulo_del_ocumento ligado"}, "attr": {"id": "uy0000"}}```
