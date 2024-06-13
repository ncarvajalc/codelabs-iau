# Codelabs IAu

## Descripción

El siguiente repositorio contiene los codelabs generados para la iniciativa de Inteligencia Artificial Aumentada de la Universidad de los Andes.

## Estructura del proyecto

El proyecto está estructurado de la siguiente manera:

```tree
./
├── claat/
│   └── bin/
│       ├── claat-linux-x86*
│       ├── claat-mac*
│       └── claat-windows-x86.exe*
├── codelabs/
│   ├── <nombre_codelab>/
│   ...
├── markdown/
│   ├── <nombre_codelab>/
│   ...
└── README.md
```

## Extensiones recomendadas

Para el desarrollo de los codelabs se recomienda el uso de las siguientes extensiones de Visual Studio Code:

- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Spanish - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-spanish)

Instale y active estas extensiones para una mejor experiencia de desarrollo. En el caso de la extensión `Spanish - Code Spell Checker`, se recomienda activarla a nivel de workspace para que funcione correctamente.

## Uso de la herramienta de generación de codelabs

Para generar los codelabs se utiliza la herramienta [claat](https://github.com/googlecodelabs/tools/releases/tag/v2.2.6)

En la carpeta `claat/bin` se encuentran los binarios de `claat` para los sistemas operativos Windows, Linux y MacOS. Si su sistema operativo no es compatible con estos binarios, puede instalar claat desde el siguiente [enlace](https://github.com/googlecodelabs/tools/tree/main/claat) y seguir las instrucciones de instalación.

Para utilizar la herramienta `claat`, desde la carpeta raíz del proyecto ejecute el siguiente comando:

### Configuración Mac y Linux

#### Configuración en Mac

```bash
claat/bin/claat-mac help
```

#### Configuración en Linux

```bash
claat/bin/claat-linux-x86 help
```

### Configuración en Windows

```bash
claat\bin\claat-windows-x86.exe help
```

## Generación de codelabs con markdown

Para generar un codelab usando markdown, desde la carpeta raíz del proyecto ejecute el siguiente comando:

### Generación en Mac y Linux (Markdown)

#### Generación en Mac (Markdown)

```bash
claat/bin/claat-mac export -o codelabs <ruta_markdown>.md
```

#### Generación en Linux (Markdown)

```bash
claat/bin/claat-linux-x86 export -o codelabs <ruta_markdown>.md
```

### Generación en Windows (Markdown)

```bash
claat\bin\claat-windows-x86.exe export -o codelabs <ruta_markdown>.md
```

Donde `<ruta_markdown>` es la ruta del codelab en formato markdown.

## Generación de codelabs con Google Docs

Para generar un codelab, desde la carpeta raíz del proyecto ejecute el siguiente comando:

### Generación en Mac y Linux (Google Docs)

#### Generación en Mac (Google Docs)

```bash
claat/bin/claat-mac export -o codelabs <ID-GOOGLE-DOCS>
```

#### Generación en Linux (Google Docs)

```bash
claat/bin/claat-linux-x86 export -o codelabs <ID-GOOGLE-DOCS>
```

### Generación en Windows (Google Docs)

```bash
claat\bin\claat-windows-x86.exe export -o codelabs <ID-GOOGLE-DOCS>
```

Donde `<ID-GOOGLE-DOCS>` es el ID del documento de Google Docs que contiene el codelab. Por ejemplo si el enlace del documento es `https://docs.google.com/document/d/1a2b3c4d5e6f7g8h9i0j/edit`, el ID del documento es `1a2b3c4d5e6f7g8h9i0j`.
