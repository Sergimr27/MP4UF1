# MP4UF1

### 1. Instalar Git
  
  * [https://git-scm.com](https://git-scm.com)
  
  * ``git --version`` verifica la version de git.
  
  
### 2.Establecer valores de configuración
    
    Esta información se utiliza para tener registro en los cambios que se van a desarollar. Esta configuración se realiza la <img width="230" alt="147563188-df88c721-7f93-447c-9a13-0f0a09195ef5" src="https://user-images.githubusercontent.com/91189406/147563244-f00305df-e0f7-4e23-82bd-eec7b11e23e2.png">

    primera vez que se utiliza Git.
    
    ```
    // Ejemplo
    git config --global user.name "Danny"
    git config --global user.email danny.larrea.argudo@gmail.com
    ```
    
 ### 3. Creación repositorio (GitHub)
 
   Para crear un nuevo repositorio, tendremos que ir a la página oficial [GitHub](https://github.com/). Los pasos a seguir son los siguientes:
   
       1. Iniciar sesión o registrarse, en el caso de no tener cuenta.
       
       2. Darle click al icono verde de New Repositoy, situado en la parte izquierda de la pantalla.
       
       3. Te saldrán una serie de opciones:
       
          - Te dirá que nombre quieres ponerle al repositorio, hay que poner el que se va más apropiado.
          
          - Posteriormente da dos opciones: si marcas que sea público, lo puede ver todo el mundo. 
            En cambio, si le das a privado solo lo podréis ver tu y tus colaboradores.
          
       4. Añadimos README file y ya estaria listo.
       
        También podriamos importar un repositorio ya creado. Es muy sencillo cuando estamos creando un repositorio hacemos click a 
       Import a repository sale en letras azules. Cuando utilizamos esta opción tenemos que poner el link de un repositorio ya 
       creado donde lo indica. Posteriormente, ponemos el nombre y realizamos los pasos explicados anteriormente.
  
       
       Cuando comenzar a escribir código es tan sencillo como darle click al icono de lápiz para comenzar a editar un documento.
       En un repositorio hay muchos menús como el de seguridad, configuración, código,...
       Cuando hemos acabado el repositorio le damos a "commit changes" para guardar los cambios. Si queremos poner información del
       repositorio le tenemos que dar a "about" y poner la descripción adecuada del repositorio, el link de la web y los topicos,
       en este último se escribe en que lenguaje esta escrito: html, css,... Para poner el link de la vamos a la configuración y 
       activamos las "GitHub Pages". Posteriormente, copiamos y pegamos el linl y ya esta echo.
       Si en un fututo queremos borrar el repositorio nos vamos a configuración y a borrar repositorio.
       Por último, si le damos al punto con el repositorio abierto nos redirige al "Visual Studio Code Online" y tenemos otro entorno 
       para picar código aunque también se puede hacer en local (lo explicaremos más adelante.  El online tiene la misma funcionalidad 
       que el local.
    
      
      
 ### 4.Etiquetas básicas de Github
 
  **Encabezados**
  
  Para crear un encabezado, agrega uno a seis símbolos # antes del encabezado del texto. La cantidad de # que usas determinará el tamaño del ecanbezado.
 
 ```
# El encabezado más largo
## El segundo encabezado más largo
###### El encabezado más pequeño
```

  **Estilo de texto**
  
  Se puede indicar énfasis en el texto utilizando negritas, cursivas o tachada.
  
   **Estilo** | **Sintaxis** | **Ejemplo** | **Resultado**
   ---------------- |  ---------------- |  ---------------- |  ---------------- 
   Negrita | ``** **`` | ``**Este texto está en negrita**`` | **Este texto está en negrita**
   Cursiva| ``* *`` | ``*Este texto está en cursiva*`` | *Este texto está en cursiva*
   Tachado | ``~~ ~~`` | ``~~Este texto está tachado~~`` | ~~Este texto está tachado~~
   Negrita y cursiva | ``*** ***`` | ``***Este texto está en negrita y cursiva***`` | ***Este texto está en negrita***
   
   **Código de Cita**
   
   Se utiliza dentro de un enunciado con comillas simples. El texto entre las comillas simples no se formateará. 
   
   Ejemplo:
   
   ```
   Los mejores jugadores de futbol son:
   Leo Messi
   Cristiano Ronaldo
   ```
  
  **Enlaces**
  
  Para crear un enlace en linea se utilizan poniendo el texto del enlace entre corchetes [ ], y posteriormente la URL entre paréntesis ( )
  
  Ejemplo:
  
  Esta documentación se ha echo utlizando [GitHub Pages](https://pages.github.com/).
  
  **Imagenes**
  
  Puedes insertar una imagen en tu repositorio si agregas una ``!`` y pones el texto alternativo entre ``[ ]``. Entonces pon el enlace de la imagen entre paréntesis ``()``.
  
  Ejemplo:
  
  ![badbunny](https://user-images.githubusercontent.com/91189406/138928549-3417be0f-9db9-40ac-8607-a2055182ef70.png)

  **Listas**
  
  Se puede realizar una lista desordenada al colocar una o más líneas de texto con ``-`` o ``*``.
  
  Ejemplos:
  ```
  - Huevos
  - Tomate
  - Aceite
  ```
  * Mantequilla
  * Patatas
  * Coles
  
  Para crear una lista ordenada es tan sencillo como, colocar antes de cada línea un número.
  
  Ejemplo:
  
  ```
  1. Barcelona
  2. Madrid
  3. Sevilla
  ```
  
  **Usar emojis**
  
  Puedes agregar emojis a tu escritura al escribir ``:EMOJICODE``:
  
  * Gané la medalla de oro.🥇
  * Aprendi el abecedario. 🔤
  * Me desperté cuando sono la alarma.⏰

  **Listas Anidadas**
  
  Para crear una lista anidada mediante el editor web en GitHub puedes alinear tu lista visualmente. Hay que escribir los elementos de la lista uno debajo del otro. Exactamente, en la primera letra de la linea.
  
  Ejemplo:
  ```
  1. Bambas
     - Nike
       -Air Max
  ```
 
 ### 5. Visual Studio Code (Entorno y Funcionamiento):
      
 Es un editor de código fuente desarrollado por Microsoft para Windows, Linux y macOS. Es compatible con varios lenguajes de programación como ``html``, ``css``, ``JavaScript``,... Una vez creado para crear un repositorio vamos a ``Archivo`` y le damos a ``Abrir Carpeta`` y una vez seleccionada crear dentro un index.html. Una vez creado el directorio podemos empezar a picar código. Cuando hemos acabado para guardar lo podemos hacer manualmente yendo a ``Contro de código fuente`` o ``Ctrl+Alt+Maj``. Dentro de este tendremos que darle click a ``Confirmar`` para que se guarden los cambios o  directamente hacer un ``Ctrl+S`` y se guarda automáticamente. Taambién podemos descargar las extensiones que nos interesen.
 
 **Podemos crear un repositório de GitHub y trabajar con Visual Studio?** 
 La respuesta es si. Para hacerlo es tan sencillo como darle click al icono de ``code`` en el repósitorio de GitHub y copiar el link que nos aparece. Irnos al Visual Studio, abrimos la carpeta donde queremos se creará el directorio y si hacemos click en el menú ``Terminal`` y le damos a ``Nuevo Terminal`` podremos ejercutar el comando ``git clone`` y pegamos el link del repositorio copiado anteriormente.

Ejemplo:
```
git clone https://github.com/Sergimr27/CSS-inline-to-interno.git
 ```
 
Una vez echo esto ya estara el directorio crado. Cuando hayamos aterminado de trabajar solo tendremos que guardarlo y para subir los cambios al GitHub solo tendremos que usar 3 comandos: ``git add.``, ``git commit -m "texto"`` y ``git push origin main``

Ejemplo:
```
git add.
git commit -m "texto definitivo"
git push origin main
```

Ya estarán los cambios subidosy podremos trabajar tanto en linea como en local.

 **Comandos Visual Studio Code**:
 
 - git add: sirve para lo explicado anteriormente, es para añadir al repositorio en linea los cambios realizados.
 - git commit -m "texto definitivo": sirve para poner nombre al cambio realizado
 - git push origin main: envia los cambios a la rama original, en nuestro caso al repositorio de Github
 - cd: para situarnos en el repositorio que nosotros queramos y que nos redirija a este. Ejemplo:  ``cd test/``                                                       
 - pwd: para ver en que directorio estamos situados
 - git clone: sirve a la hora de clonar un repositorio, como hemos explicado anteriormente.
 
 **html**
 
 Es un lenguaje de marcas. Es el lenguaje estandard para crear sitios web.
 
 **Estructura**:
 
```HTML
<!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Document</title>
     </head>
     <body>
     </body>
     </html>
 ```
 
 **Etiquetas básicas**
 
 head: cabeza o parte superiror del código
  
 body: cuerpo
  
 html: lenguaje en le que esta escrito, indica que esta escrito en html
  
 p: parrágo 
 
 h1, h2, ..., h6: encabezado
 
 title: título
  
 link: asociar elementos externos
  
 b: negrita
  
 ol: lista ordenada
  
 ul: lista no ordenada
  
 li: items de una lista
  
 a: enlaces(hipervínculos)
  
 img: añadir imagenes
  
 div: caja en html
 
 footer: pie de página
 
 section: sección
 
 header: encabezado
 
 article: artículo
 
  Para poner un icono de página tenemos que crar en Visual Studio un directorio ``img``. Posteriormente ir a [Font Awesome](https://fontawesome.com/). y descargar el que nos guste más y después guardarlo en el directorio `img``. Para unirlo con el index html solo tenemos que utilizar la etiqueta ``link`` y unirlo con la imagen de directorio ``img``. Una vez echo esto ya tendriamos nuestra icono de web. Para ver como queda Abrimos el index.html des de la carpeta donde lo habíamos guardado y podemos ver tanto el icono como lo que hayamos echo hasta el momento.
  
  
 **Atributos importantes**
  
  style: sirve para agregar estilos en linea
  
  href: asociado a la etiqueta link (define la ruta)
  
  src: ruta de imagen
  
  alt: imagen de descripción de la foto
  
  **Propiedades//css**
  
  color: color de letra
  
  backgroung color: color de fondo
  
  font-size: tamaño letra
  
  padding: relleno. Cuando queremos hacer una regla para el `padding` siempre la indicamos con una letra para saber el tamaño que tiene, como en las camisetas.
  
  paading-top: relleno de arriba
  
  padding-left: relleno de abajo
  
  ...
  
  margin: márgen
  
  
  
  margin-top: márgen de arriba
  
  margin-left: márgen de la izquierda.
  
  ...
  
  background-image: imagen de fondo
  
  background-size: tamaño del fondo
  
  border: borde
  
  text-align: alineación del texto
  
  justify-content: para justificar el contenido. Tendria esta estructura.
  
  
  <img width="203" alt="Captura de pantalla 2021-12-28 122927" src="https://user-images.githubusercontent.com/91189406/147562081-2bb499a6-9df3-4705-a2b2-40142b47dddb.png">

  Para adjuntar videos o mapas entre otras cosas utilizamos la etiqueta `iframe`, para hacerlo nos vamos al video que que queremos, le damos a comartir y a insertar vídeo. Entonces nos sale un texto en formato `html` que copiaremos y pegaremos en nuestro `index.html`. Posteriormente, se podrá cambiar la altura que viene predeterminada o hacer una classe nueva para añadirle estilos, podremos modificar la anchura. 
A continuación se puede ver un ejemplo de como quedaria:


<img width="721" alt="Captura de pantalla 2021-12-28 124431" src="https://user-images.githubusercontent.com/91189406/147563453-1157c1d8-b410-4a65-aac6-1c50326f25e8.png">



<img width="230" alt="Captura de pantalla 2021-12-28 124454" src="https://user-images.githubusercontent.com/91189406/147563188-df88c721-7f93-447c-9a13-0f0a09195ef5.png">


<img width="960" alt="Captura de pantalla 2021-12-28 124635" src="https://user-images.githubusercontent.com/91189406/147563227-5e63df3b-833c-45a7-a316-2d081c79cef0.png">

  **Estilos css**
  
  Hay 3 formaas de añadir estilos:
  - En linea: se introducen en la misma linea de código. En la etiqueta donde lo queramos aplicar.
  - Internos: se introducen dentro de la etiqueta head. Si añadimos un estilo en el body se aplicara en todo el directorio. Para que solo se aplique solo donde nosotros queremos pondremos la etiqueta en questión si queremos que se aplique en todo lo que lleve esa equiqueta.
 Ejemplo:
 ```
 Siempre se ciera con corchetas. Y siempre se pone entre la etiqueta style.
 <style> 
 body {
    margin: 0;
    padding-left: 20%;
    padding-right: 20%;
    background-color: aliceblue;
}
<style/>
```
En cambio si solo queremos que lo lleve una pequeña parte. En la linea de código donde queremos aplicarlo tenemos que poner la etiqueta ``<style class="nombre">`` o ``>style id="nombre">``. Una vez puesto esto tendremos que poner lo que veremos en el siguiente ejemplo:
```
<style>
#fondo-lista {
    background-color: rgba(0, 255, 0, 0.5);
}
 .idea-principal {
            color: rgba(150, 0, 255, 0.5);
            font-size: 30px;
            padding: 10px 20px;
        }
<style/>
``` 
Ponemos ``#`` cuando es ``id`` y ``.`` cuando es ``class``
  - Externos: Son iguales que los internos pero estan echos a parte en un directorio css, que posteriormente habrá que enlazar con la etiqueta ``link`` al index.html.
  
*{
} :universal

li{
}selector elementos 

.test{
}selector de clase

#testh{
}selector de id

li p{
} sselector colindante

li>p{
} selector de los hijos directos

**Formato Web**

Cuando se crea una página web y se tienen que querer en cuentas las filas y la columnas según donde quieras ubicar los diferentes elementos. Para esto tendremos que utilizar la etiqueta `div` cada vez que sea una fila diferente le pondremos la classe `row`, para ubicar elementos en diferentes columnas es tan sencillo como añadir otro `div` con clase `column-n`donde pondremos el número de columnas que habrá y allí es donde podremos meter el contenido. Siempre se dividira el porcentaje de la pantalla entre el número de columnas para saber lo que ocupa es decir que si hay 4 en la hoja de estilos pondremos un `with`del `25%`.
Ejemplo:
<img width="785" alt="Captura de pantalla 2021-12-28 130526" src="https://user-images.githubusercontent.com/91189406/147564659-381b35be-0916-48c9-a862-f5f81a084a01.png">


<img width="629" alt="Captura de pantalla 2021-12-28 130548" src="https://user-images.githubusercontent.com/91189406/147564674-c8882b03-cc6f-48c5-98d3-d7572fdf6b1a.png">

Esto quedaría asi:

<img width="960" alt="Captura de pantalla 2021-12-28 130446" src="https://user-images.githubusercontent.com/91189406/147564692-aa4b668c-f3f5-4f55-8501-24b05da5b8c6.png">

**Media Queries**

Las media queries son útiles cuando deseas modificar tu página web o aplicación en función del tipo de dispositivo o de unas caracteristicas específicas. Dentro de esto añadiremos solo las reglas que queremos modificar. Como se ve en la siguiente imagen:

<img width="369" alt="Captura de pantalla 2021-12-28 131237" src="https://user-images.githubusercontent.com/91189406/147565125-e7de84f6-62ec-42d4-8bbc-490140dd5411.png">

Para que no nos aparezca una barra de scroll cuando hacemos más pequeña nuestra página tenemos que añadir  `scroll-behabior: smooth` en la etiqueta `html` de la hoja de estilos.

**¿Cómo hacer un un menú que este fijo en la izquierda?**

Para hacer un menú y que cada palabra nos lleve a una parte diferente de la página utilizaremos `id`. Para ello creamos un `div` con clase `row`, a su vez dentro de este crearemos otro `div` con clase `column-nav` y aqui es donde añadiremos todo. Utilizaremos la etieuta `li` y añadiremos dentro de esta la palabra que vayamos a utilizar y a su vez estara dentro de la etiqueta `a` y en el link pondremos `#nombre-id`. Es decir que pondremos el nombre de `id` que hayamos puesto en la parte del documento que queremos enlazar. Como se puede ver en las siguientes imagenes:

<img width="404" alt="Captura de pantalla 2022-01-13 171553" src="https://user-images.githubusercontent.com/91189406/149367614-53975a49-a393-47f2-8be6-5bc9614d7300.png">

<img width="644" alt="Captura de pantalla 2022-01-13 171642" src="https://user-images.githubusercontent.com/91189406/149367649-f7b2bb3a-d7d8-4f4f-a29b-0818a110efb9.png">

<img width="939" alt="Captura de pantalla 2022-01-13 171845" src="https://user-images.githubusercontent.com/91189406/149368067-2f052b2b-07a0-459a-becf-2abd140f1cf8.png">

Para que este fijo tenemos que crear una regla para el menú utilizando `position: fixed` de esta forma se quedará fijo.

