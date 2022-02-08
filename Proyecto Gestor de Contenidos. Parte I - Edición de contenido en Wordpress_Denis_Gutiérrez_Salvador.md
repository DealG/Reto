###### *Implantación de Aplicaciones Web - Curso 2021/2022 - IES Leonardo Da Vinci - Alberto Ruiz/Laura de Jaén*
## Proyecto Gestor de Contenidos. Parte I - Edición de contenido en Wordpress
#### Entrega de: *Denis Alexander Gutiérrez Salvador*
----
#### 1. Descripción:

El objetivo de esta práctica es examinar las opciones de edición de Wordpress: aprenderemos a crear entradas, editarlas, asignarles categorías, moderar comentarios, añadir páginas estáticas, subir archivos...

Esta práctica es guiada hasta cierto punto: Wordpress es fácil de usar y la intención es que explores sus posibilidades por tu cuenta. Las indicaciones de la práctica marcan únicamente los mínimos que debes alcanzar.

#### 2. Formato de entrega:

**Incluye capturas de pantalla a lo largo de todo el trabajo. Escoge la temática o diseño que prefieras para desarrollar tu blog / web.** Documenta los posibles problemas que puedan surgir, explicando cómo los has solucionado.

#### 3. Trabajo a realizar

##### 3.1. Registro

En este punto debes tener creada tu cuenta en WordPress. Las decisiones sobre la temática de tu blog tendrán efecto sobre la estética inicial del mismo. Observa que en todos los pasos hay una opción gratuita, aunque se te sugieran opciones de pago. Recuerda que debes haber confirmado tu cuenta (se te enviará un enlace a tu dirección de correo electrónico) antes de poder invitar a otros usuarios a colaborar en tu sitio.

1. Una vez estés en el panel de control, observa que arriba a la izquierda te dice que tu sitio es privado: publícalo para que sea visible. De nuevo se te ofrecerán planes de pago para registrar dominios, pero continúa con tu nombre de subdominio gratuito dentro de `wordpress.com`.

![image-20220201115905742](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201115905742.png)



![image-20220201115958722](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201115958722.png)

1. Dedica unos minutos a familiarizarte con el funcionamiento del panel de control, y cómo puedes visualizar tu sitio web, incluso en pantalla completa, mientras se mantiene una línea superior que te permite regresar al panel de control.
2. Ten en cuenta que en Wordpress.com se nos ofrece un panel de control algo simplificado. Si quieres ver el panel de control (llamado "Escritorio") que veremos cuando hagamos una instalación personalizada, puedes encontrarlo siempre accediendo a la URL de tu blog seguido de `/wp-login.php`. 



##### 3.2. Preparación de un usuario editor

Si accedes al panel de control mediante `wp-login.php` y observas las opciones del menú, verás que se mezclan opciones relativas a la edición de contenido (entradas, páginas, medios y comentarios) con otras relativas a la administración del sitio (temas, usuarios, plugins...). 

En esta práctica vamos a examinar las opciones de edición, y más adelante veremos las opciones de administración. Aunque podríamos realizar todas las prácticas con el usuario administrador, para editar resulta más sencillo y seguro trabajar con un usuario que no tenga permisos de administración.

En esta primera parte vamos a crear ese usuario:

1. Una vez dentro del panel de control, accede a la sección de Usuarios

![image-20220201125402547](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201125402547.png)



1. En la versión simplificada de escritorio de WordPress, no podemos añadir usuarios manualmente, sino que tenemos que invitar a otras personas a través de su correo electrónico.

1. Invita a otro usuario "compañero" con el perfil "Editor".

![image-20220201125506634](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201125506634.png)



1. Si tienes curiosidad sobre las diferencias entre los distintos usuario, haz clic en el icono de "Ayuda"  y después escoge "Roles de usuario"
2. Inicia sesión en otro navegador con el otro usuario y verás que sólo tienes disponibles las opciones de edición de contenido: vamos a irlas examinando a lo largo de la práctica

![image-20220201125900201](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201125900201.png)



##### 3.3. Entradas

Las entradas o "posts" son el componente principal de un blog. En este apartado vamos a explorar la forma de publicar contenido en nuestro blog. Recuerda que tienes disponible una sección de "Ayuda" en la parte superior.

En esta práctica debes hacer un blog. Recuerda que puedes escoger el tema que prefieras (si estás haciendo los retos de Servicios de Red e Internet, también puedes usarlo). El blog debe incluir la documentación necesaria.  Piensa en las secciones que tu web necesitará tener.

###### 3.3.1. Añadiendo una entrada

5. Accede a la sección de entradas y crea una nueva. Introduce un título y un contenido de muestra

![image-20220201131128759](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201131128759.png)

Analiza el menú "Publicar": nuestras ociones serán:

* Vista previa: para ver cómo va a quedar nuestra entrada antes de publicarla
* Sólo guardar: útil si dejamos la entrada  a medias, o si queremos que otro colaborador o editor pueda revisar nuestro trabajo antes de publicarlo. En este caso utilizamos la opción "Estado" y cambiamos de "Borrador" a "Pendiente de revisar"
* Publicar: cuando todo esté listo, con esta acción la entrada será visible en el blog

![image-20220201131246788](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201131246788.png)

5. Intenta averiguar las diferencias entre los distintos tipos de entrada (menú "Formato"). Ten en cuenta, que, gracias a la función de "Vista previa", no necesitas publicar la entrada para ver cómo va a quedar.

5. Comprueba que puedes editar tu entrada directamente en HTML en lugar de usar el asistente de edición. Prueba también la opción de "Edición rápida" desde el escritorio del panel de control

![image-20220201131740466](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201131740466.png)

5. Cuando tengas la entrada preparada, en lugar de publicarla inmediatamente prográmala para que se publique 10 minutos después. Para ello haz clic en "Editar" junto al mensaje "Publicar inmediatamente". Esta opción es útil para blogs que publican sus entradas en una hora determinada 

![image-20220201131917247](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201131917247.png)



![image-20220201131959887](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201131959887.png)



![image-20220201132018950](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201132018950.png)



###### 3.3.2. Categorías y etiquetas

Habrás visto que hay dos secciones del menú dedicadas a categorías y etiquetas. Se trata de herramientas que nos permiten organizar las entradas de nuestro blog para que sea más fácil acceder a la información, pero ¿cuál es la diferencia?

* Las categorías permiten agrupar entradas de una temática similar. Es posible incluir subcategorías, es decir, las categorías son jerárquicas. En tu blog aparecerá (a no ser que no lo desees) un listado de categorías en el menú lateral, de forma que el lector pueda acceder fácilmente a todas las entradas de una categoría. 
  * Sin las categorías, un blog con mucho contenido resulta muy incómodo de consultar, puesto que la única forma de leerlo es ir recorriendo una a una las entradas.
* Las etiquetas (tags) son muy parecidas... La única diferencia a nivel práctico es que no son jerárquicas. Pero su misión es diferente: indicar qué temas se tratan en la entrada. Habitualmente las etiquetas son más numerosas. Por ejemplo, puede haber un artículo que pertenezca a la categoría "Informática", subcategoría "Procesadores". Pero sus etiquetas pueden incluir "intel", "amd", "seguridad", "procesadores", o incluso asuntos que no tengan nada que ver con los procesadores pero que son mencionados en el artículo. 
  * Para el usuario es una forma de encontrar rápidamente entradas relacionadas con un tema que le ha interesado. 
  * Para el desarrollador es una forma de lograr que los buscadores tengan en cuenta nuestro contenido cuando un usuario busque esos temas

Como ves, en ambos casos la idea es que el usuario pueda acceder rápidamente a contenido relacionado con lo que le interesa. **No es obligatorio utilizar etiquetas, pero sí categorías**. Si no asignas una categoría, se asignará una estándar ("sin categoría") así que merece la pena darle al menos un nombre.

10. Experimenta con las categorías y etiquetas. Crea varias entradas y utiliza estas herramientas para organizar el contenido. Mira también blogs reales que conozcas para coger ideas sobre cómo categorizar o etiquetar nuestras publicaciones.

![image-20220201132519616](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201132519616.png)

![image-20220201132625957](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201132625957.png)



![image-20220201132931734](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201132931734.png)

![image-20220201140228237](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201140228237.png)

##### 3.4. Medios

La sección de medios te permite subir imágenes, vídeos o cualquier otro contenido a tu estructura de carpetas.

12. En la sección de Medios, añade dos imágenes que te interese incluir después en tus entradas. Observa que subirlas es muy sencillo (sólo hay que arrastrarlas) y que luego puedes renombrarlas o incluso editarlas (útil para ajustar el tamaño)

![image-20220201135659381](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201135659381.png)



12. Ahora edita una de tus entradas y utiliza la opción "Añadir objeto" para incluir las imágenes

![image-20220201135719279](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201135719279.png)



12. Sigue en "Entradas" y comprueba que al "Añadir objeto" es posible subir el elemento desde este menú, sin necesidad de ir previamente a "Medios" cada vez que queramos incluir una imagen

![image-20220201135941004](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201135941004.png)



12. Desde "Entradas", crea una galería de imágenes seleccionando varias de las que tengas disponibles 

![image-20220201140316569](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201140316569.png)

![image-20220201140331694](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201140331694.png)



![image-20220201140356869](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201140356869.png)

![image-20220201140412889](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201140412889.png)



##### 3.5. Páginas

Wordpress nació como CMS especializado en blogs, pero fue evolucionando y muchos usuarios han creado con él páginas completas de empresas o instituciones. Para esto resulta de gran ayuda incluir páginas estáticas: no son entradas de un blog con una fecha determinada, sino páginas HTML que siempre mostrarán lo mismo y dan pie a las "secciones" (Sobre nosotros, Contacto, Productos,...) de mi sitio web. 

Una decisión importante sobre nuestro blog es qué queremos que se vea en la página principal: básicamente tenemos dos opciones:

* La lista de entradas (normalmente se muestra primero la más reciente). Es la opción por defecto, y estarás acostumbrado a ver este comportamiento en los blogs que conozcas
* Una página principal estática: esto tiene más sentido en portales web de empresas o instituciones. 

16. Crea y publica dos páginas estáticas. Una de ellas será posteriormente tu portada, tenlo en cuenta para el contenido. Incluye en cada una de ellas un medio (puedes subirlo sobre la marcha). Observa que puedes decidir la URL que se asignará a cada una.

![image-20220201140907571](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201140907571.png)



![image-20220201142648880](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201142648880.png)

![image-20220201143106785](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201143106785.png)





##### 3.6. Comentarios

Los comentarios ayudan a mantener vivo un blog y fidelizar a los usuarios, que acuden una y otra vez a una entrada ya leída para mantener discusiones sobre su contenido. Sin embargo, los comentarios pueden ser una auténtica pesadilla para el editor, puesto que es necesario luchar no sólo contra:

 * Mensajes de publicidad o SPAM (tanto de texto como enlaces)
* Los denominados "trolls", cuya única misión es sabotear la discusión (a veces lanzando mensajes de odio)
* Mensajes con contenido inapropiado (el concepto "inapropiado" variará según la temática y público objetivo de tu blog)

Mediante la sección de comentarios, el editor puede aprobar o eliminar comentarios de usuarios. Más adelante veremos también que el administrador puede desactivar los comentarios de una o todas las entradas.

17. Deja un comentario en una de tus entradas, y pide a un compañero que haga lo mismo accediendo a tu CMS (como tendrás  problemas de acceso externo, lo más sencillo es que tu compañero acceda desde tu propio equipo en otro navegador). Comprueba que al visitar el blog (utiliza otra pestaña o navegador) quedan pendientes de aprobación (más adelante cambiaremos esta configuración)

![image-20220201144853180](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201144853180.png)



17. Comprueba que los últimos comentarios aparecen directamente en el escritorio del panel de administración, así como en la sección "Comentarios"



17. Aprueba los comentarios y comprueba que son visibles

![image-20220201145235515](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201145235515.png)

17. Comprueba que un usuario al que le ha sido aprobado un comentario puede ya hacer sucesivos comentarios sin necesidad de aprobación

![image-20220201145550920](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201145550920.png)

17. Registra tu dirección de correo en [Gravatar](http://es.gravatar.com/) y comprueba cómo tu icono de perfil aparecerá en los comentarios (no sólo en todos los sitios de Wordpress en que comentes sino en muchos otros, como Slack)

![image-20220201145730118](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201145730118.png)







![image-20220201145948468](C:\Users\keirzar\AppData\Roaming\Typora\typora-user-images\image-20220201145948468.png)
