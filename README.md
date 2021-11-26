# Proyecto-Final-Poderosisimas-Aguilas
Proyecto final de las poderosas águilas del América. En este proyecto explicaremos como desarrollaríamos un software para que los estudiantes del ITAM puedan dar sugerencias para convertir a su universidad en un mejor lugar. 

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
    El usuario deberá acceder al módulo de creacion de contenido por medio de un botón en la página principal. Dentro de este se encontrará con los textboxes necesarios para poder ingresar su información. 
  #### Caso de uso
    Cuando el usuario entre al módulo de creación de contenido, este se encontrará con 3 textboxes, cadda uno con su respectiva etiqueta, e ingresará un título, una descripcción, y si lo desea una imagen para poder compartir su sugerencia con el ITAM y los usuarios de nuestra página por medio de un botón. 
  #### Requerimientos funcionales
    REQ-1: Cajas de texto para ingresar la información
    REQ-2: Botón para publicar el contenido
### 1.3. Feed de sugerencia
  #### Descripción 
    Funcionalidad que permite que los usuarios vean sugerencias de los amigos y profesores específicos que ellos siguen o con con los que ellos tienen relación
  #### Prioridad
    Media
  #### Estímulos
    Cuando el usuario de click en el botón de login, se le será direccionado a esta página. Dentro de ella podrá interactuar con posts por medio de reacciones predeterminadas. 
  #### Caso de uso
    Cuando el usuario entre a la página, será automaticamente llevado a su feed donde podrá interactuar con los posts por medio de un botón desglosable con reacciones que indiquen que le gusta, que cree que ayudaría al ITAM, o que piensa necesita más desarrollo. 
  #### Requerimientos funcionales
    REQ-1: Botónes de reacción para cada post
    REQ-2: Barra de scroll para moverse entre posts
    REQ-3: Lista de posts que siga algún algoritmo
    
### 1.4. Reacción a la sugerencia
  #### Descripción 
    Funcionalidad que permite a los usuarios ver y asignar diferentes reacciones (like, ayudaría al ITAM, necesita desarrollo) a las sugerencias de la comunidad. 
  #### Prioridad
    Media
  #### Estímulos
    El usuario deberá de poder ver las reacciones por medio de botones en cada post de su feed. Al darles click, se asigna un valor a la interacción entre el usuario y el post. 
  #### Caso de uso
    Cuando el usuario entre a su feed, en cada post verá las 3 opcciones de botón, y deberá poder darles click para indicar que tuvo una reacción similar a dicho post. 
  #### Requerimientos funcionales
    REQ-1: Botón like
    REQ-2: Botón le serviría al ITAM
    REQ-3: Botón necesita desarrollo
### 1.5. Rankings de sugerencia
  #### Descripción 
    Funcionalidad que permite que los usuarios entren a una página dedicada de rankings para entrar a ver los posts con los mejores "ratings" en la categoría de likes y de "le serviría al ITAM". 
  #### Prioridad
    Baja
  #### Estímulos
    El usuario será redireccionado a esta págian por medio de un botón que aparecerá en la sección de botones de la página de feed. 
  #### Caso de uso
    El usuario entrará a la pàgina y verá los rankings en dos listas separadas, cada una con su respectiva etiqueta.
  #### Requerimientos funcionales
    REQ-1: Lista likes
    REQ-2: Lista "le serviría al ITAM"
### 1.6. Página de trending de sugerencia
  #### Descripción 
    Funcionalidad que permite que el usuario entre a ver los posts que recientemente han tenido un gran número de reacciones de like o de "le serviría al ITAM" e interactúe con ellos.
  #### Prioridad
    Media
  #### Estímulos
    Por medio de un botón que aparecerá del lado izquierdo de su feed, el usuario accederá a esta página donde verá los posts que recientemente han tenido un gran número de reacciones de like o de "le serviría al ITAM" y les pueda asignar su propia reacción usando el mismo sistema de botones que tiene su feed.
  #### Requerimientos funcionales
    REQ-1: Botones de reacción para los posts
    REQ-2: Lista de posts "trending" en las últimas 3 semanas. 
### 1.7. Página de propuestas cumplidas
  #### Descripción 
    Funcionalidad que permite que la comunidad vea una lista de las propuestas que el ITAM tomó en cuenta y cumplió. 
  #### Prioridad
    Baja
  #### Estímulos
    El usuario accederá a esta página por medio de un botón que aparecerá a la izquierda de su feed principal
  #### Caso de uso
    El usuario entrará a esta página por medio del botón y podrá ver los rankings en una lista vertical, donde podrá ir hacia abajo y hacia arriba por medio de una barra de scroll. 
  #### Requerimientos funcionales
    REQ-1: Barra de scroll 
    REQ-2: Lista de propuestas cumplidas dadas por el mismo ITAM
### 1.8. Ver usuario
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
## ○ Plan de Calidad
Haga click [Aqui](Plan de Calidad.md) 
## ○ Arquitectura y justificación
Decidimos usar una arquitectura por microservicios mezclada con eventos, puedes verlo [Aqui](Arquitectura.md)
## ○ Metodología y justificación
Decidimos usar una metodologia por prototipo, para mas detalles [Aqui](Metodologia.md)
## ○ Código del proyecto

## ○ Documentación para replicar

## ○ Propuesta económica
Si quiere saber acerca de nuestra propuesta económica, haga click aquí  [Aqui](EstimacionesAguilasPF.xlsx)
