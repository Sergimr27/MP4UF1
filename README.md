# MP4UF1

### 1. Instalar Git
  
  * [https://git-scm.com](https://git-scm.com)
  
  * ``git --version`` verifica la version de git.
  
  
### 2.Establecer valores de configuración
    
    Esta información se utiliza para tener registro en los cambios que se van a desarollar. Esta configuración se realiza la 
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
       para picar código aunque también se puede hacer en local (lo explicaremos más adelante.  El online tienela misma funcionalidad 
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
 
 ### 5. Visual Studio Code (Entorno y Funcionamiento)
 
 head
  
  body
  
  html
  
  etiquetas
  
  html
  
  body
  
 
  
  p
  
  h1, h2, ..., h6
  
  title
  
  link: asociar elementos externos
  
  b: negrita
  
  ol: lista ordenada
  
  ul: lista no ordenada
  
  li: items de una lista
  
  a: enlaces(hipervínculos)
  
  img: añadir imagenes
  
  div: caja en html
  
  **atributos importantes**
  
  style: sirve para agregar estilos en linea
  
  href: asociado a la etiqueta link (define la ruta)
  
  src: ruta de imagen
  
  alt: imagen de descripción de la foto
  
  **propiedades//css**
  
  color: color de letra
  
  backgroung color: color de fondo
  
  font-size: tamaño letra
  
  padding: relleno
  
  paading-top
  
  padding-left
  
  ...
  
  margin
  
  margin-top
  
  margin-left
  
  ...
  
  background-image: imagen de fondo
  
  background-size: tamaño del fondo
  
  border
  
  
   estillos en linea es utilizar la etiqueta style y editar en la misma linea. Estilos internos dento del head
  
  https://www.w3schools.com/html/default.asp
  
