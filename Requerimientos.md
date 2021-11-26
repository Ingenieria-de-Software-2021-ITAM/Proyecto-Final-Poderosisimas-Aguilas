## ○ Software Requirements con al menos 3 Casos de Uso por Requerimiento
### 1.1 Login con cuenta del itam
  #### Descripción 
    Funcionalidad que permite que el usuario tenga acceso al programa por medio de su correo institucional y una contraseña única que decidirá al momento de registrar su cuenta con nuestro programa. 
  #### Prioridad
    Alta
  #### Estímulos
    Cuando el usuario entre a nuestra página, de no tener un login guardado se le redigirá a la página de login para que ingrese su correo y contraseña. 
  #### Caso de uso
    El usuario debería de ver una pantalla con dos textboxes, cada uno con una etiqueta que indique que información ingresar. En una de las cajas se debería de ingresar el correo institucional y en el otro la contraseña utilizada. Luego hará click en un botón para ingresar
  #### Requerimientos funcionales
    REQ-1: Botón para validar la información e ingresar
    REQ-2: Cajas de texto para ingresar la información
### 1.2. Crear Post de sugerencia
  #### Descripción 
    Funcionalidad que permite que un usuario cree un post para hacer una sugerencia al ITAM. Este post puede tener: Título, descripcción, imagen. 
  #### Prioridad
    Media
  #### Estímulos
    El usuario deberá acceder al módulo de creacion de contenido por medio de un botón en la página de sugerencias. Dentro de este se encontrará con los textboxes necesarios para poder ingresar su información. 
  #### Caso de uso
    Cuando el usuario entre al módulo de creación de contenido, este se encontrará con 3 textboxes, cada uno con su respectiva etiqueta, e ingresará un título, una descripción, y si lo desea una imagen para poder compartir su sugerencia con el ITAM y los usuarios de nuestra página por medio de un botón. El usuario de igual manera seleccionará a que categoria pertenece la sugerencia.
  #### Requerimientos funcionales
    REQ-1: Cajas de texto para ingresar la información
    REQ-2: Botón para publicar el contenido
### 1.3. Feed de sugerencia
  #### Descripción 
    Funcionalidad que permite que los usuarios vean sugerencias de otros usuarios según la categoria deseada.
  #### Prioridad
    Media
  #### Estímulos
    Cuando el usuario de click en el botón de propuestas, se le será direccionado a esta página. Dentro de ella podrá interactuar con posts por medio de reacciones predeterminadas. 
  #### Caso de uso
    Cuando el usuario entre a la página, será automaticamente llevado a un feed donde podrá interactuar con los posts por medio de un botón desglosable con reacciones que indiquen que le gusta o dejar un comentario. 
  #### Requerimientos funcionales
    REQ-1: Botónes de reacción para cada post
    REQ-2: Barra de scroll para moverse entre posts
    REQ-3: Lista de posts que siga algún algoritmo
    
### 1.4. Reacción a la sugerencia
  #### Descripción 
    Funcionalidad que permite a los usuarios ver y asignar una reaccion de me gusta a las sugerencias de la comunidad. 
  #### Prioridad
    Media
  #### Estímulos
    El usuario deberá de poder ver las reacciones por medio de un boton en cada post de su feed. Al darle click, se asigna un valor a la interacción entre el usuario y el post. 
  #### Caso de uso
    Cuando el usuario entre a su feed, en cada post verá el botón de me gusta, y deberá poder darles click para indicar que tuvo una reacción similar a dicho post. 
  #### Requerimientos funcionales
    REQ-1: Botón like
### 1.5 Comentario a la sugerencia
  #### Descripción
    Funcionalidad que permite a los usuarios hacer comentarios sobre las sugerencias publicadas por la comunidad.
  #### Prioridad
    Media
  #### Estímulos
    El usuario deberá poder ver la opción de hacer un comentario por medio de un boton en cada post de su feed. Al darle click, el textbox para hacer su comentario se abrirá.
  #### Caso de uso
    Cuando el usuario entre asu feed, en cada post verá el botón para comentar, y deberá poder darle click para agregar un comentario a dicho post.
  #### Requerimientos funcionales
    REQ-1: Botón comentario
    REQ-2: Textbox comentario
    REQ-3: Botón publicar comentario
### 1.6. Categorias de sugerencia
  #### Descripción 
    Funcionalidad que permite que los usuarios entren a varias página dedicadas a diferentes categorias para entrar a ver los posts de la categoría deseada.
  #### Prioridad
    Media
  #### Estímulos
    El usuario será redireccionado a esta págian por medio de un botón que aparecerá en la sección de botones de la página de feed. 
  #### Caso de uso
    El usuario entrará a la pàgina y verá las categorias, cada una con su respectiva etiqueta.
  #### Requerimientos funcionales
    REQ-1: Botón categoría 1
    REQ-1: Botón categoría 2
    REQ-1: Botón categoría 3
    REQ-1: Botón categoría 4
### 1.7. Página de propuestas cumplidas
  #### Descripción 
    Funcionalidad que permite que la comunidad vea una serie de las propuestas que el ITAM tomó en cuenta y cumplió. 
  #### Prioridad
    Baja
  #### Estímulos
    El usuario accederá a esta página por medio de un botón que aparecerá hasta arriba a la derecha de la página.
  #### Caso de uso
    El usuario entrará a esta página por medio del botón y podrá ver una serie de propuestas que se han cumplído en varios cuadros.
  #### Requerimientos funcionales
    REQ-1: Barra de scroll 
    REQ-2: Lista de propuestas cumplidas dadas por el mismo ITAM
### 1.8. Ver usuarios
  #### Descripción 
    Funcionalidad que permite buscar a otros usuarios y demuestra sus perfiles.
  #### Prioridad
    Media
  #### Estímulos
    El usuario dará click en un botón que aparecerá en la barra de menú superior para acceder a esta página.
  #### Caso de uso
    Cuando el usuario de click en el botón y entre, apareceán varios usuarios, al igual que una barra de busqueda para encontrar a un usuario en específico. Al seleccionar a un usuario se desplegara la información de este usuario al igual que sugerencias que ha publicado.
  #### Requerimientos funcionales
    REQ-1: Serch bar para buscar a los usuarios
    REQ-2: Datos de el usuario seleccionado
    REQ-3: Lista de datos de usuarios
### 1.9. Ver usuario
  #### Descripción 
    Funcionalidad que permite que el usuario vea su perfil y los datos que ha dado al programa, como su correo, su contraseña o su foto de perfil, así como los usuarios que sigue y que lo siguen. 
  #### Prioridad
    Alta
  #### Estímulos
    El usuario dará click en un botón que aparecerá en la parte izquierda de su feed para acceder a esta página.
  #### Caso de uso
    Cuando el usuario de click en el botón y entre, apareceán sus datos y dos botones, uno par aver a la gente que sigue, y otro para ver a la gente que lo sigue. Al hacer click en estos botones, se desplegará la lista de usuarios. 
  #### Requerimientos funcionales
    REQ-1: Botón para ver usuarios seguidos
    REQ-2: Botón para ver usuarios que sigue
    REQ-3: Lista de datos del usuario desplegada
