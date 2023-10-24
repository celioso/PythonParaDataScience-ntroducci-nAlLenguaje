# Python para Data Science: Introducción al Lenguaje
### Preparando el ambiente

**¡Hola!**

Mi nombre es Christian Velasco y es un placer darte la bienvenida a este curso de Python para Data Science: Introducción al Lenguaje.

Espero que sea una experiencia increíble de aprendizaje y que podamos vencer todos los desafíos juntos. En esta aula, vamos a dar nuestros primeros pasos en el lenguaje Python, aprendiendo sus fundamentos, algunas buenas prácticas y principales convenciones.

**Ambiente de Análisis**

Utilizaremos una herramienta de Google llamada Colaboratory, que es similar a Jupyter Notebook y no requiere configuración para su uso.

**Google Colaboratory**

Para usar este ambiente, debes tener una cuenta de Gmail, ya que cada Notebook virtual se almacenará en Google Drive. Si no tienes una cuenta de Gmail, créala haciendo clic en este enlace.

[Crear cuenta Gmail](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp "Crear cuenta Gmail")

**Información importante sobre Colaboratory**

- El código de tu *Notebook* se ejecuta en una máquina virtual dedicada a tu cuenta. Las máquinas virtuales se reciclan después de un cierto tiempo de inactividad, o si la ventana está cerrada.

- Para restaurar tu *Notebook*, es posible que debas cargar el archivo .csv y ejecutar las opciones "Tiempo de ejecución" y "Reiniciar y ejecutar todas ...".

- Para saber más sobre Colab, creamos un [artículo en Alura](https://www.aluracursos.com/blog/google-colab-que-es-y-como-usarlo "artículo en Alura") explicando a detalle cómo funciona la herramienta.

En caso de dudas durante el curso, cuenta siempre con el Foro de Alura, si no tuvieses ninguna duda, ¿qué tal ayudar a alguien en el Foro compartiendo conocimiento y experiencias?

**Sabiendo esto, ¡empecemos!**

### Para saber más: Historia de Python

Python es un lenguaje de programación interpretado, orientado a objetos de alto nivel y con semántica dinámica.

La simplicidad de Python reduce el mantenimiento de un programa. Python soporta bibliotecas y módulos (contenidos que veremos a lo largo del curso), lo que fomenta la programación modular y la reutilización del código.

Es uno de los lenguajes que más ha crecido debido a su compatibilidad (se ejecuta en la mayoría de los sistemas operativos) y la capacidad de soportar otros lenguajes. Aplicaciones que vemos a diario como Dropbox, Reddit e Instagram están escritas en Python.

Python también es el lenguaje más popular para análisis de datos y conquistó a la comunidad científica.

Breve historia del lenguaje

Python fue creado en 1990 por [Guido Van Rossum](https://es.wikipedia.org/wiki/Guido_van_Rossum "Guido Van Rossum") en el centro de Matemática Stichting en Holanda como sucesor del lenguaje [ABC](https://es.wikipedia.org/wiki/ABC_%28lenguaje_de_programaci%C3%B3n%29 "ABC"). Guido es recordado como el principal autor de Python, pero también otros programadores ayudaron con muchas contribuciones.

El lenguaje ABC fue diseñado para ser utilizado por "no programadores", pero al inicio mostró ciertas limitaciones y restricciones. El mayor reclamo de los primeros estudiantes "no programadores" de este lenguaje, era la presencia de reglas arbitrarias que los lenguajes de programación habían establecido tradicionalmente, muchas cosas de bajo nivel todavía se hacían y eso no agradaba al público.

A raíz de eso, Guido se propuso la tarea de crear un lenguaje de script simple que contenga algunas de las mejores propiedades de ABC. Mejoró el lenguaje ABC e incorporó las listas Python, diccionarios, declaraciones básicas y uso obligatorio de sangría, todo esto diferencia Python del lenguaje ABC.

Probablemente ya escuchaste o leíste en algún lugar que Python es un lenguaje interpretado o un lenguaje de script. En cierto sentido, también es cierto que Python es tanto un lenguaje interpretado como un lenguaje compilado. Un compilador traduce lenguaje Python a lenguaje de máquina. El código Python es traducido en un código intermediario que debe ser ejecutado por una máquina virtual conocida como PVM (Python Virtual Machine).

El intérprete hace la traducción en tiempo real para el código de máquina, es decir, en tiempo de ejecución. El compilador traduce todo el programa en código de máquina de una sola vez y luego lo ejecuta, creando un archivo que se puede ejecutar (ejecutable). El compilador genera un informe de errores (en caso existan) y el intérprete detiene la traducción cuando encuentra un primer error.

**¿Más información sobre Python?**

Para más información, accede a la [documentación oficial de Python en este link](https://docs.python.org/es/3/ "documentación oficial de Python en este link") o descarga el [Ebook de Python para Data Science](https://caelum-online-public.s3.amazonaws.com/ESP-DS-24-alura-latam-apostilla-python-para-DS/ds-24-ebook-alura-latam-python-para-data-science-vbf.pdf "Ebook de Python para Data Science") que construimos en Alura para ayudarte en esta jornada de aprendizaje.

### Haz lo que hicimos en aula: Variables y Función print()

En esta aula, aprendimos que es posible almacenar informaciones en la memoria de la computadora a través de variables. Vimos también que Python trae algunas [funciones integradas o built-in](https://docs.python.org/es/3/library/functions.html "funciones integradas o built-in"). Además, es posible crear nuestras propias funciones.

Con base en el contenido visto en clases, crea una función llamada `saludar` que cuando se ejecute, almacene el contenido digitado por el usuario a través de la función `input` en una variable llamada nombre. Después, utiliza la función `print` para mostrar un mensaje de bienvenida [concatenando](https://es.wikipedia.org/wiki/Concatenaci%C3%B3n "concatenando") el nombre ingresado.

### Lo que aprendimos

Lo que aprendimos en esta aula:
- Aprendimos qué son las variables.
- Creamos nuestra primera función.
- Entendimos la diferencia entre lenguaje de alto y bajo nivel.

### Proyecto del aula anterior

¿Comenzando esta etapa? Aquí puedes descargar los archivos del proyecto que hemos realizado anteriormente en el aula.

[Descarga los archivos en Github](https://github.com/alura-es-cursos/1784-python-para-data-science-introduccion "Descarga los archivos en Github") o haz clic [aquí](https://github.com/alura-es-cursos/1784-python-para-data-science-introduccion/archive/main.zip "aquí") para descargarlos directamentes.

### Para saber más: Operadores de Python

Creamos un código que verifica si la edad es `mayor` o `igual` a 18. Este operador no es aritmético y se conoce como operador de comparación. Python tiene más operadores de este tipo:

![Operadores](https://2.bp.blogspot.com/-TL4R4iL9T1w/WV7qCceaYpI/AAAAAAAAAIM/4Fb3aswf1QUD474LVdN5OCLhVCh01RnyQCLcBGAs/s1600/Ashampoo_Snap_2017.07.06_20h54m52s_001_.png "Operadores")

### Haz lo que hicimos en aula: Parámetros de una función

Funciones en Python son bloques de código que ejecutarán algún tipo de tarea o manipulación de datos, pudiendo o no recibir: datos de entrada (parámetros).

Crea una función llamada `verificar_si_puedes_conducir`, que recibe un parámetro llamado `edad` e incluye una condicional `if` para analizar si la edad es `mayor o igual` que `18` años. En caso positivo, haz que muestre un mensaje en la pantalla diciendo `Usted tiene edad suficiente para conducir`. De lo contrario ( `else` ), que muestre el mensaje `Usted NO tiene edad suficiente para conducir`. Después de ejecutar, crea la misma función sin parámetros, que almacene la edad digitada por el usuario. Como todo valor ingresado a través del teclado es un string, no olvides de convertir la `edad` para `int` con el código `int(edad)`.

### Lo que aprendimos

Lo que aprendimos en esta aula:

- Creamos una función que recibe un parámetro.
- Aprendimos a usar las condicionales.
- Convertimos el string `str` de la función `input`, que es pasado por el usuario para un valor entero `int`.

### Proyecto del aula anterior

¿Comenzando esta etapa? Aquí puedes descargar los archivos del proyecto que hemos realizado anteriormente en el aula.

[Descarga los archivos en Github](https://github.com/alura-es-cursos/1784-python-para-data-science-introduccion/tree/aula2 "Descarga los archivos en Github") o haz clic [aquí](https://github.com/alura-es-cursos/1784-python-para-data-science-introduccion/archive/aula2.zip "aquí") para descargarlos directamente.