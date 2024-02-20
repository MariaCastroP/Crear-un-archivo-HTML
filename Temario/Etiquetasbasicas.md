# Etiquetas básicas

En este apartado veremos algunas de las etiquetas fundamentales de elementos de HTML que utilizaremos para mostrar la información que nosotros necesitemos.

## Headings
Estos títulos que nos van a permitir resaltar información en tamaño y visibilidad, además de cuestiones de SEO.  

Generar una etiqueta heading 
~~~html
<h1> Archivo HTML </h1>
<h2> Bienvenidos a tu primer archivo html </h2>
<h3> PAsos para crear tu primer archivo html </h3>
~~~
El valor que corresponde a la letra “h” puede ir del 1 al 6, permite ordenar estos títulos del más importante al menos importante, por ejemplo, un h2 puede utilizarse en títulos y subtítulos.

>[!Note]
> No te olvides que para desplegar tu proyecto y poder visualizarlo debes crear una carpeta con tu archivo html y abrirlo en tu navegador

## Párrafos 
Te permiten ingresar información, y su etiqueta se muestra de la siguiente manera: 
~~~html
<p>contenido</p> 
~~~

Donde tenemos el contenido podemos poner la información que queremos que se visualice en nuestro navegador, pero recuerda aún sin estilos, porque eso lo veremos en otra lección. 

Podemos agregar un párrafo adicional con salto de línea por defecto, pero si queremos poner párrafos separados dentro del mismo, sin el salto de línea podemos ajustarlo con la siguiente etiqueta:
~~~html
<br>
~~~ 
Y conoce como break line. 

## Enlaces (links)
Los enlaces te permiten colocar un link como si fuera un hipervínculo, por medio de una palabra o varias podrás dirigirte al link que le indiques al usuario. 
~~~css
  <script> var pathToPDFFiles =  'DOC-CFE-SAMALAYUCA/ </script>
~~~
La sintaxis ```pathToPDFFiles``` proporciona una forma de trabajar con directorios y rutas de archivos.

~~~css
{"href": "Inventario_Settings"}
~~~
```href``` significa **“hyper reference”** e indica el link de destino deseado o nombre de documento en un path.Es muy útil cuando queremos llevar al usuario a ciertos documentos estratégicas, por ejemplo, reportes, imagenes, pdfs , etc. 

~~~css
<script src="jquery.js"></script>
~~~
El atributo ```src``` en una etiquera es la ruta hacia un archivo externo o recurso que quieres enlazar a tu documento HTML. Por ejemplo si tuvieses tu propio archivo personalizado en JavaScript llamado ```jquery.js``` lo agregarias como el ejemplo de arriba 🔝
Esto apuntaria a un archivo llamado ```jquery.js``` que esta en el mismo directorio del archivo ***.html*** 

~~~css
<script src="js/jquery.pagination.js"></script>
~~~

También puedes enlazar otros directorios usando ’..’ en la ruta del archivo. Esto salta un nivel arriba del directorio, luego a un directorio llamado ```js``` y luego al archivo ```jquery.pagination.js```.
