## Teoria

1. Define los elementos que componen el siguiente snippet de código:

```html
<!DOCTYPE html>
<html lang="es">
  <head> 
  Es el cabezero de todo el codigo html
    
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
    <title>Home</title>
    Este es el nombre que recibirá nuestra pagina html, en este caso parece una pagina principal osea que nuestro index.html recibirá el nombre de Home.



  </head>
  <body>    
  Es el cuerpo donde va a ir todos los bloques todo el codigo que se mostrará en la página
    
    
  <h1>Hola mundo</h1>
  Este es el tituilo que se muestra en la pagina, a medida que el valor numerico sea menor el texto sera cada vez mas pequeño h1, h2, h3. 
    
    <main>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      
      p nos muestra el parrafo en el que hemos escrito
      
      <img src="https://avatars.githubusercontent.com/u/106534360?v=4">
      sirve para mostrar una imagen, el enlace siempre va detras de un src= u la etiqueta de la imagen no se cierra o no es necesario, es decir </img>


    </main>
  </body>
</html>
```

2. El siguiente snippet tiene un error, ¿como lo arreglarias?

html

```html
<p>Haz click <link href="https://google.com">aqui</link> para ir a Google</p>
```

Que los enlaces no se cierran</link>




3. ¿Como se llama el archivo html que un servidor muestra por defecto cuando entramos a la entrada de una página?

index.html

4. ¿Que es markdown? ¿Que usos conoces del mismo? Comparalo frente a HTML y explica cuando se usa uno u otro.

Markdown es un lenguaje que sirve para escribir texto, lo usamos sobrer todo para poder escribir cosas relacionadas con el código ya que ofrece funciones que hacen que se entienda bien.

El uso mas común que le damos a markdown es en el README.md de GitHub, editando los repositorios de nuestras asignaturas y otras veces lo solemos usar para escribir, documentar trabajos o hacer examenes.

La diferencia entre html y markdown es que html es un lenguaje de programacion usado en su mayoria por programacion web. En html no "puedes" tomar apuntes y no es la forma mas comoda de hacerlo. Sin embargo en markdown podemos escribir archivos de forma mas sencilla usando pocoscaracteres para hacerlo mas visual.

En relacion a eso he usado pandoc para pasar de Markdown a Html con ```pandoc ollama-guia.md``` por terminal que me ha devuelto el html.

5. Explica que hace el siguiente snippet de JavaScript:

```JavaScript
const nombre = localStorage.getItem('nombre')
```
Recoge alguna variable llamada nombre hacia la contante nombre

``` JavaScript
const edad = localStorage.getItem('edad')
```

Recoge alguna variable llamada edad hacia la contante edad

Asumiendo que nombre y edad existen, ¿que tipo de dato será cada uno?

