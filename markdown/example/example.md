autor: Su nombre
resumen: Resumen del codelab
id: nombre-carpeta-codelab
categorías: IAu,codelab
entornos: Web
estado: Publicado
enlace de retroalimentación: https://github.com/ncarvajalc/codelabs-iau/issues

# CodeLab de cómo crear un codelab usando markdown

## Resumen del codelab 
Duración: 0:02:00

Este tutorial describe cómo crear un codelab usando markdown. Va a explicar la sintaxis de markdown y cómo usarla para crear un codelab.

1. Usando un Google Doc
1. Usando un archivo markdown

En este codelab vamos a usar la segunda opción y autor nuestro codelab usando un archivo markdown. Esto nos da la flexibilidad de usar nuestro archivo markdown para otras cosas y también almacenarlo en nuestro repositorio de github con cualquier código que pueda ser usado para un tutorial.

Aquí hay una imagen de ejemplo de otro CodeLab que creé:
!image_caption


**Recursos:** 
* El hogar original de este codelab está ubicado aquí: [Enlace al Codelab](https://www.marcd.dev/codelab-4-codelab)
* El markdown para el codelab original está ubicado aquí: [codelab.md](https://github.com/Mrc0113/codelab-4-codelab/blob/master/codelab.md)
* [Google CodeLabs Tools Github](https://github.com/googlecodelabs/tools) - El repositorio que contiene la herramienta claat que usaremos hoy
* [Google Group for CodeLab Authors](https://groups.google.com/forum/#!forum/codelab-authors) - gran foro para hacer preguntas sobre codelabs y discutir funcionalidades futuras
* [Un blog que utilicé cuando comencé con Google Codelabs](https://medium.com/@mariopce/tutorial-how-to-make-tutorials-using-google-code-labs-gangdam-style-d62b35476816)

## Configuración del entorno
Duración: 0:04:00

Para crear un CodeLab necesitas *Go* y *claat* (la herramienta de línea de comandos de codelabs) instalados.

Las instrucciones a continuación son las que me funcionaron en Mac, pero también puedes encontrar instrucciones [aquí](https://github.com/googlecodelabs/tools/tree/master/claat)

#### Instalar Go 

Instala [Go](https://golang.org/dl/) si no lo tienes.
Puedes usar Homebrew si lo tienes en mac 
``` bash
$ brew install go
```

#### Configurar las variables de entorno de Go
A continuación se muestra lo que configuré en mac, pero las instrucciones están [aquí](https://golang.org/doc/install) para otras opciones de sistema operativo

``` bash
$ export GOPATH=$HOME/Go
$ export GOROOT=/usr/local/opt/go/libexec
$ export PATH=$PATH:$GOPATH/bin
$ export PATH=$PATH:$GOROOT/bin
```

#### Instalar claat
Instala claat
``` bash
$ go get -u -v -x github.com/googlecodelabs/tools/claat
```

Ahora deberías tener el comando *claat* disponible. 
``` bash
$ claat
```

## Crea tu primer CodeLab
Duración: 0:05:00

Ahora que tenemos el entorno configurado, vamos a crear un archivo markdown donde crearemos el codelab real.

Negativo
: Si estás usando Windows, asegúrate de configurar tu editor de texto para usar finales de línea UNIX! 

####
``` bash
$ vim codelab.md
```

#### Rellena los metadatos del encabezado
Copia y pega los encabezados de abajo en tu archivo markdown y cambia los valores apropiadamente. 
Las directrices están disponibles debajo de los encabezados de muestra. 

``` bash
autor: Nombre del autor
resumen: Resumen de tu codelab que sea legible para humanos
id: identificador-único-del-codelab
categorías: codelab,markdown
entornos: Web
estado: Publicado
enlace de retroalimentación: Un enlace donde los usuarios pueden ir para proporcionar retroalimentación (Quizás el repositorio git)
cuenta de analítica: ID de Google Analytics
```

Los metadatos consisten en pares de clave-valor de la forma "clave: valor". Las claves no pueden
contener dos puntos, y los campos de metadatos separados deben estar separados por líneas en blanco.
En la actualidad, los valores deben estar todos en una línea. Todos los metadatos deben venir antes del
título. Se pueden usar cualquier clave y valor arbitrarios; sin embargo, sólo los siguientes
serán entendidos por el renderizador:

* Resumen: Un resumen legible por humanos del codelab. Por defecto está en blanco.
* Id: Un identificador compuesto por letras minúsculas que idealmente describe el
    contenido del codelab. Este campo debe ser único entre
    los codelabs.
* Categorías: Una lista separada por comas de los temas que cubre el codelab.
* Entornos: Una lista de entornos en los que el codelab debería ser descubrible.
    Los codelabs marcados como "Web" serán visibles en el índice de codelabs. Los codelabs marcados
    como "Kiosco" sólo estarán disponibles en los kioscos de codelabs, que tienen equipo especial
    adjunto.
* Estado: El estado de publicación del codelab. Los valores válidos son:
    - Borrador: El codelab no está terminado.
    - Publicado: El codelab está terminado y visible.
    - Obsoleto: El codelab se considera obsoleto y no debe ser ampliamente publicitado.
    - Oculto: El codelab no se muestra en el índice.
* Enlace de retroalimentación: Un enlace para enviar a los usuarios si desean dejar comentarios sobre el
    codelab.
* Cuenta de analítica: Un ID de Google Analytics para incluir con todas las páginas del codelab.

#### Añade el Título
A continuación, añade tu título usando un solo carácter '#'
```
# Título del codelab
```

#### Añade Secciones y Duraciones
Luego, para cada sección, usa Encabezado 2 o '##' y especifica una duración opcional debajo para los cálculos de tiempo restante
Los tiempos de sección opcionales se utilizarán para totalizar automáticamente los tiempos de tutorial restantes y totales
En markdown he encontrado que el tiempo se formatea hh:mm:ss

Ejemplo
``` bash
## Sección 1
Duración: 0:10:00

## Sección 2
Duración: 0:05:00
```

#### Añade Contenido a la Sección
Ahora que tenemos 2 secciones en nuestro codelab titulado, vamos a añadir algún contenido a cada sección. 
Inventa el tuyo propio o copia y pega el ejemplo de abajo: 

Copia en la sección 1 (Debajo de Duración y encima de Sección 2):
```
### Cajas de Información
Texto plano seguido de cajas de información verdes y amarillas 

Negativo
: Esto aparecerá en una caja de información amarilla.

Positivo
: Esto aparecerá en una caja de información verde.

¡Has creado cajas de información!

### Viñetas
Texto plano seguido de viñetas
* Hola
* CodeLab
* Mundo

¡Has creado viñetas!

### Lista Numerada
1. Lista
1. Usando
1. Números

¡Has creado una lista numerada!

```

Copia en la sección 2 (Debajo de Duración): 
```
### Añadir un Enlace
¡Añadiendo un enlace!
[Ejemplo de un Enlace](https://www.google.com)

### Añadir una Imagen
¡Añadiendo una imagen!
![image_caption](https://googlecloud.tips/img/031/codelabs.png)

### Insertar un iframe
![https://codepen.io/tzoght/embed/yRNZaP](https://en.wikipedia.org/wiki/File:Example.jpg "Try Me Publisher")
```

Más ejemplos del Analizador de Markdown se pueden encontrar [aquí](https://github.com/googlecodelabs/tools/tree/master/claat/parser/md).

## Exportar y Servir
Duración: 0:02:00

Ahora que tienes un codelab inicial definido en tu archivo markdown, vamos a generar el contenido del sitio estático. 
Podemos exportar y servir el contenido localmente usando el comando `claat` que instalamos anteriormente. 

``` bash
$ claat export codelab.md
$ claat serve
```

* Tu navegador debería haberse abierto (si no lo hace, entonces intenta ir a localhost:9090 en tu navegador). 
* Elige el directorio que coincide con tu "id" que pusiste en los encabezados. 
* ¡Voilà! Deberías tener tu primer codelab!

## Aloja Tu CodeLab
Duración: 0:01:00

Cuando ejecutaste el comando `claat export` creaste el contenido web estático necesario para alojar tu codelab. 
Colocó el contenido web estático en un directorio especificado por tu "id" único y puedes verlo localmente abriendo la página index.html. 

Negativo
: Ten en cuenta que cuando lo ves localmente abriendo index.html, algunos de los gráficos pueden no aparecer (como access_time, Siguiente, Atrás), pero funcionan una vez en línea. 


Ahora que tienes el contenido estático puedes alojarlo como quieras.
Una opción es subirlo a github y servirlo desde Netlify.  

Si te gustaría crear tu propia página de inicio para codelabs, [como esta](https://codelabs.developers.google.com), ¡hay una herramienta para hacer eso también! 
Míralo aquí: [Sitio de CodeLabs](https://github.com/googlecodelabs/tools/blob/master/site/README.md)