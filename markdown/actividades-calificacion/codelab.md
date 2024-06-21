autor: Nombre del autor
resumen: Resumen de tu codelab que sea legible para humanos
id: actividades-calificacion
categorías: codelab,markdown
entornos: Web
estado: Publicado
enlace de retroalimentación: Un enlace donde los usuarios pueden ir para proporcionar retroalimentación (Quizás el repositorio git)
cuenta de analítica: ID de Google Analytics
# Codelab to Create a Codelab

## **Introducción**

Esta guía está diseñada para facilitar la ***"creación de objetivos de aprendizaje, rúbricas personalizadas, mejorar las prácticas de evaluación y proporcionar retroalimentación constructiva***". 


A través de prompts detallados, esta guía ofrece un enfoque paso a paso para definir criterios claros y escalas de puntuación, asegurar la validez y aplicabilidad de las rúbricas, y aplicar estos criterios de manera objetiva en diversas actividades educativas.

Además, proporciona estrategias para ofrecer retroalimentación efectiva, ayudando a los estudiantes a entender sus fortalezas y áreas de mejora, y a establecer planes de acción para su desarrollo continuo.

Puedes comenzar desde cualquier sección de este codelab según tus necesidades actuales. Por ejemplo, si ya cuentas con una rúbrica elaborada, no es necesario que inicies desde la sección de creación de rúbricas. Si ya tienes una actividad lista con su enunciado, puedes dirigirte directamente a la sección de retroalimentación.

***Para que entiendas mejor cada prompt, verás en cada uno de ellos un ejemplo el cual ya hemos probado para ti, que se basa en ***"Historia Global"***, tomando como tema principal la historia de la Segunda Guerra Mundial.***

![Imagen Intro](img/foto.png)



## Creación de Objetivos de aprendizaje

### **Descripción**

En esta sección, aprenderás a definir objetivos de aprendizaje claros y específicos que guiarán el diseño de tus actividades educativas y las rúbricas correspondientes. Estos objetivos te ayudarán a focalizar tus esfuerzos de enseñanza y a proporcionar una dirección clara para los estudiantes.

### **Prerrequisitos**

No hay prerrequisitos específicos para esta sección. Puedes iniciar aquí si aún no has definido tus objetivos de aprendizaje.


### **Descripción del Prompt**

El prompt “Creación de Objetivos de aprendizaje” está diseñado para guiar a los profesores en la creación de objetivos de aprendizaje claros, específicos y medibles utilizando la Taxonomía de Bloom. Estos objetivos deben ser alcanzables y relevantes para el nivel educativo y materia específica, y deben estar diseñados para fomentar el desarrollo cognitivo de los estudiantes.

### **Prompt**
```console
Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO](Pregrado, Posgrado, educación continua, etc.)`

Materia o tema específico: `[MATERIA TEMA] (Estructuras de datos y algoritmos, física introductoria, etc.)`

Contexto del uso del objetivo: `[CONTEXTO USO] (Discusión de clase, exámenes, proyectos, etc.)`

Preguntas guía para definir los objetivos de aprendizaje (Metodología de Bloom):

1.⁠ ⁠Recordar:
¿Qué conceptos clave o información deben recordar los estudiantes de esta materia? `[CONCEPTOS CLAVE]`

2.⁠ ⁠Comprender:
¿Qué deben entender los estudiantes en relación con estos conceptos? ¿Cómo deben ser capaces de explicarlos? `[CONCEPTOS A ENTENDER]`

3.⁠ ⁠Aplicar:
¿Cómo deberían los estudiantes aplicar estos conceptos en situaciones prácticas o problemas? `[CONCEPTOS A APLICAR]`

4.⁠ ⁠Analizar:
¿Qué aspectos de la materia deben ser capaces de descomponer y analizar los estudiantes? ¿Cómo deben relacionar estos aspectos? `[ANALIZAR ASPECTOS]`

5.⁠ ⁠Evaluar:
¿Qué habilidades deben desarrollar los estudiantes para evaluar o juzgar los conceptos o situaciones presentadas en la materia? `[HABILIDADES EVALUACIÓN]`

6.⁠ ⁠Crear:
¿Qué deberían ser capaces de crear o diseñar los estudiantes utilizando los conceptos aprendidos? `[CREAR O DISEÑAR]`

Objetivo del prompt:

El objetivo es guiar a los profesores en la creación de objetivos de aprendizaje claros, específicos y medibles utilizando la Taxonomía de Bloom. Estos objetivos deben ser alcanzables y relevantes para el nivel educativo y materia específica, y deben estar diseñados para fomentar el desarrollo cognitivo de los estudiantes.

Formato de respuesta:

Proporcionar ejemplos de objetivos de aprendizaje completos que incluyan el nivel de Bloom, la acción a realizar, la habilidad a desarrollar y los criterios de evaluación. Mostrar esta información de manera textual con los detalles y luego en una tabla de resumen con toda la información sintetizada.
```

### **Detalle de los parámetros**

#### **1. Nivel Educativo de los Estudiantes:**

Indica el nivel educativo de los estudiantes para los cuales se crean los objetivos de aprendizaje:
"Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO]`..."

- **`[NIVEL EDUCATIVO]`**: Especifica el nivel de educación, por ejemplo, Pregrado, Posgrado, educación continua, etc.

#### **2. Materia o Tema Específico:**

Define la materia o tema específico relacionado con los objetivos de aprendizaje:
"Materia o tema específico: `[MATERIA TEMA]`..."

- **`[MATERIA TEMA]`**: Detalla la materia o el tema, como Estructuras de datos y algoritmos, física introductoria, etc.

#### **3. Contexto del Uso del Objetivo:**

Explica el contexto en el que se utilizarán los objetivos de aprendizaje:
"Contexto del uso del objetivo: `[CONTEXTO USO]`..."

- **`[CONTEXTO USO]`**: Describe el uso de los objetivos, como discusión de clase, exámenes, proyectos, etc.

#### **4. Preguntas Guía para Definir los Objetivos de Aprendizaje (Metodología de Bloom):**

Utiliza las siguientes preguntas para guiar la definición de los objetivos de aprendizaje según la Taxonomía de Bloom:

1. **Recordar:**
"¿Qué conceptos clave o información deben recordar los estudiantes de esta materia? `[CONCEPTOS CLAVE]`..."
    - **`[CONCEPTOS CLAVE]`**: Menciona los conceptos e información que los estudiantes deben recordar.
2. **Comprender:**
"¿Qué deben entender los estudiantes en relación con estos conceptos? ¿Cómo deben ser capaces de explicarlos? `[CONCEPTOS A ENTENDER]`..."
    - **`[CONCEPTOS A ENTENDER]`**: Indica los conceptos que los estudiantes deben entender y explicar.
3. **Aplicar:**
"¿Cómo deberían los estudiantes aplicar estos conceptos en situaciones prácticas o problemas? `[CONCEPTOS A APLICAR]`..."
    - **`[CONCEPTOS A APLICAR]`**: Describe cómo los estudiantes deben aplicar los conceptos en situaciones prácticas.
4. **Analizar:**
"¿Qué aspectos de la materia deben ser capaces de descomponer y analizar los estudiantes? ¿Cómo deben relacionar estos aspectos? `[ASPECTOS A ANALIZAR]`..."
    - **`[ASPECTOS A ANALIZAR]`**: Especifica los aspectos de la materia que deben ser analizados y descompuestos.
5. **Evaluar:**
"¿Qué habilidades deben desarrollar los estudiantes para evaluar o juzgar los conceptos o situaciones presentadas en la materia? `[HABILIDADES A EVALUAR]`..."
    - **`[HABILIDADES A EVALUAR]`**: Detalla las habilidades de evaluación que los estudiantes deben desarrollar.
6. **Crear:**
"¿Qué deberían ser capaces de crear o diseñar los estudiantes utilizando los conceptos aprendidos? `[CONCEPTOS A CREAR O DISEÑAR]`..."
    - **`[CONCEPTOS A CREAR O DISEÑAR]`**: Indica qué deberían ser capaces de crear o diseñar utilizando los conceptos aprendidos.

#### **5. Objetivo del Prompt:**

Define el objetivo del prompt:
"El objetivo es guiar a los profesores en la creación de objetivos de aprendizaje claros, específicos y medibles utilizando la Taxonomía de Bloom. Estos objetivos deben ser alcanzables y relevantes para el nivel educativo y materia específica, y deben estar diseñados para fomentar el desarrollo cognitivo de los estudiantes."

#### **6. Formato de Respuesta:**

Explica cómo se debe presentar la información:
"Proporcionar ejemplos de objetivos de aprendizaje completos que incluyan el nivel de Bloom, la acción a realizar, la habilidad a desarrollar y los criterios de evaluación. Mostrar esta información de manera textual con los detalles y luego en una tabla de resumen con toda la información sintetizada."


### **Ejemplo de Uso del Prompt**

En este ejemplo, realizamos la prueba con este prompt para el tema de Historia Global, teniendo como tema la Segunda Guerra Mundial

**Nivel educativo de los estudiantes**: Pregrado

**Materia o tema específico**: Historia global

**Contexto del uso del objetivo**: Actividad calificada

**Preguntas guía para definir los objetivos de aprendizaje (Metodología de Bloom):**

1. **Recordar:**
¿Qué conceptos clave o información deben recordar los estudiantes de esta materia? Clases sociales, segunda guerra mundial, causas y consecuencias históricas.

2. **Comprender:**
¿Qué deben entender los estudiantes en relación con estos conceptos? ¿Cómo deben ser capaces de explicarlos? Las diferencias de clases en el contexto de la segunda guerra mundial y la experiencia dependiendo de esto. Deben poder diferenciar las diferentes condiciones económicas y sociales en esa época.

3. **Aplicar:**
¿Cómo deberían los estudiantes aplicar estos conceptos en situaciones prácticas o problemas? Deben poder aprender a empatizar en diferentes contextos para saber cómo implementar soluciones diversas dependiendo del contexto.

4. **Analizar:**
¿Qué aspectos de la materia deben ser capaces de descomponer y analizar los estudiantes? ¿Cómo deben relacionar estos aspectos? El contexto, las diferencias sociales, el privilegio, las oportunidades. Deben relacionarlos con respecto a las condiciones vividas en la segunda guerra mundial.

5. **Evaluar:**
¿Qué habilidades deben desarrollar los estudiantes para evaluar o juzgar los conceptos o situaciones presentadas en la materia? Análisis, comparación y contraste, explicar.

6. **Crear:**
¿Qué deberían ser capaces de crear o diseñar los estudiantes utilizando los conceptos aprendidos? Material que dé cuenta de que comprende las diferentes perspectivas dependiendo de las condiciones socioeconómicas de cada quien

**Objetivo del prompt:**

El objetivo es guiar a los profesores en la creación de objetivos de aprendizaje claros, específicos y medibles utilizando la Taxonomía de Bloom. Estos objetivos deben ser alcanzables y relevantes para el nivel educativo y materia específica, y deben estar diseñados para fomentar el desarrollo cognitivo de los estudiantes.

**Formato de respuesta:**

Proporcionar ejemplos de objetivos de aprendizaje completos que incluyan el nivel de Bloom, la acción a realizar, la habilidad a desarrollar y los criterios de evaluación. Mostrar esta información de manera textual con los detalles y luego en una tabla de resumen con toda la información sintetizada.


### **Resultados de ejemplos de Objetivos de Aprendizaje Utilizando la Taxonomía de Bloom**

Una vez enviado este prompt, se obtuvo el siguiente resultado, la idea es que usted eliga todos los objetivos de aprendizaje que creas relevantes para tu actividad.

A continuación se presentan ejemplos de objetivos de aprendizaje para estudiantes de pregrado en el tema de Historia Global, utilizando la Taxonomía de Bloom para guiar el desarrollo cognitivo y la comprensión profunda de los conceptos clave.

#### 1. Recordar

**Objetivo:**
Recuerden las principales causas y consecuencias históricas de la Segunda Guerra Mundial, incluyendo las clases sociales implicadas.

- **Nivel de Bloom:** Recordar
- **Acción:** Listar, identificar, recordar
- **Habilidad a desarrollar:** Recuerdo de hechos y conceptos clave
- **Criterios de evaluación:** El estudiante debe ser capaz de enumerar al menos tres causas y tres consecuencias de la Segunda Guerra Mundial, relacionándolas con las clases sociales afectadas.

#### 2. Comprender

**Objetivo:**
Comprender las diferencias en las experiencias durante la Segunda Guerra Mundial basadas en las clases sociales, explicando cómo influenciaron estas diferencias.

- **Nivel de Bloom:** Comprender
- **Acción:** Explicar, describir, interpretar
- **Habilidad a desarrollar:** Comprensión de conceptos y principios
- **Criterios de evaluación:** El estudiante debe ser capaz de explicar cómo las diferencias de clase social impactaron las experiencias de las personas durante la Segunda Guerra Mundial, utilizando ejemplos concretos.

#### 3. Aplicar

**Objetivo:**
Aplicar el conocimiento sobre las clases sociales en la Segunda Guerra Mundial para analizar y sugerir soluciones a problemas socioeconómicos contemporáneos.

- **Nivel de Bloom:** Aplicar
- **Acción:** Aplicar, implementar, usar
- **Habilidad a desarrollar:** Aplicación de conocimientos en contextos nuevos
- **Criterios de evaluación:** El estudiante debe ser capaz de proponer soluciones basadas en las lecciones históricas sobre clases sociales en situaciones contemporáneas, demostrando entendimiento de las implicaciones históricas.

#### 4. Analizar

**Objetivo:**
Analizar cómo las diferencias socioeconómicas durante la Segunda Guerra Mundial influyeron en el acceso a privilegios y oportunidades, relacionándolas con el contexto histórico.

- **Nivel de Bloom:** Analizar
- **Acción:** Analizar, diferenciar, descomponer
- **Habilidad a desarrollar:** Análisis y síntesis de información
- **Criterios de evaluación:** El estudiante debe ser capaz de identificar y discutir cómo las diferencias socioeconómicas afectaron el acceso a privilegios y oportunidades durante la Segunda Guerra Mundial, proporcionando ejemplos detallados.

#### 5. Evaluar

**Objetivo:**
Evaluar críticamente las perspectivas históricas sobre las clases sociales durante la Segunda Guerra Mundial, comparando y contrastando diferentes puntos de vista.

- **Nivel de Bloom:** Evaluar
- **Acción:** Evaluar, criticar, justificar
- **Habilidad a desarrollar:** Evaluación de argumentos y juicio crítico
- **Criterios de evaluación:** El estudiante debe ser capaz de comparar y contrastar diferentes interpretaciones históricas sobre las clases sociales durante la Segunda Guerra Mundial, justificando su análisis con evidencia histórica.

#### 6. Crear

**Objetivo:**
Crear un ensayo o presentación que explore las diferentes perspectivas socioeconómicas durante la Segunda Guerra Mundial, demostrando comprensión de las implicaciones históricas y contemporáneas.

- **Nivel de Bloom:** Crear
- **Acción:** Crear, diseñar, elaborar
- **Habilidad a desarrollar:** Creación de nuevos patrones o estructuras
- **Criterios de evaluación:** El estudiante debe ser capaz de desarrollar un material (ensayo, presentación) que analice y compare las perspectivas socioeconómicas durante la Segunda Guerra Mundial, integrando múltiples puntos de vista y evidencias.

Estos objetivos están diseñados para ser claros, específicos y medibles, ayudando a guiar a los profesores en la creación de actividades y evaluaciones que promuevan el aprendizaje efectivo y profundo en el contexto de la historia global.

[Creación de objetivos de aprendizaje](https://www.notion.so/Creaci-n-de-objetivos-de-aprendizaje-12ad9acc2d214762bb2fa12f331d4071?pvs=21)





## Ideación de actividades

### **Descripción**

En esta sección, generarás ideas para actividades educativas que se pueden evaluar con una rúbrica. Aquí aprenderás a identificar objetivos de aprendizaje y a diseñar actividades que los cumplan.

### **Prerrequisitos**

- Haber completado la **Creación de Objetivos de aprendizaje**.


### **Descripción del prompt**

El prompt de “Ideación de actividades” es una herramienta diseñada para ayudar a los educadores a crear actividades interactivas y dinámicas que aumenten la participación, el interés y la motivación de los estudiantes. Este prompt es útil porque guía al docente a considerar diversos aspectos esenciales para la planificación de una actividad educativa efectiva, tales como el nivel educativo de los estudiantes, la materia específica, el contexto en el que se utilizará la actividad y los objetivos de aprendizaje deseados.

Además, el prompt incentiva la creación de múltiples alternativas para la actividad, promoviendo la flexibilidad y la adaptación a diferentes situaciones y necesidades educativas. Al desglosar los pros y contras de cada opción, los docentes pueden tomar decisiones informadas sobre qué actividades implementar, optimizando así el proceso de enseñanza-aprendizaje.

### **Prompt**
```console
Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO] (Pregrado, Posgrado, educación continua, etc.)`
Materia o tema específico: `[MATERIA TEMA] (Estructuras de datos y algoritmos, física introductoria, etc.)`

Contexto del uso del prompt: `[CONTEXTO USO] (Discusión de clase, bonos, actividad calificada, etc.)`
Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE] (Los estudiantes deben identificar al menos 3 estructuras de datos, los estudiantes deben comprender el concepto de un plano inclinado, etc)`

Objetivo del prompt: El objetivo es aumentar la participación, interés y motivación de los estudiantes a través de dinámicas interactivas que fomenten el pensamiento crítico, la resolución de problemas y el trabajo en equipo.

Formato de respuesta: Generar múltiples opciones y alternativas, desglosando los pros y contras de cada una de las opciones. Incluir una descripción de cada actividad y un ejemplo breve. Mostrar esto de manera textual al inicio con los detalles y luego en una tabla de resumen con toda la información sintetizada.
```

### **Detalle de los parámetros**

#### **1. Nivel Educativo de los Estudiantes:**

Indica el nivel educativo de los estudiantes para los cuales se crean los objetivos de aprendizaje:
"Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO]`..."

- **`[NIVEL EDUCATIVO]`**: Especifica el nivel de educación, por ejemplo, Pregrado, Posgrado, educación continua, etc.

#### **2. Materia o Tema Específico:**

Define la materia o tema específico relacionado con los objetivos de aprendizaje:
"Materia o tema específico: `[MATERIA TEMA]`..."

- **`[MATERIA TEMA]`**: Detalla la materia o el tema, como Estructuras de datos y algoritmos, física introductoria, etc.

#### **3. Contexto del Uso del Prompt:**

Explica el contexto en el cual se utilizará el prompt:
"Contexto del uso del prompt: `[CONTEXTO USO]`..."

- **`[CONTEXTO USO]`**: Describe el contexto, por ejemplo, Discusión de clase, bonos, actividad calificada, etc.

#### **4. Objetivos de Aprendizaje:**

Describe los objetivos de aprendizaje que se espera que los estudiantes logren:
"Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE]`..."

- **`[OBJETIVO DE APRENDIZAJE]`**: Detalla los objetivos, como Los estudiantes deben identificar al menos 3 estructuras de datos, los estudiantes deben comprender el concepto de un plano inclinado, etc.

#### **5. Objetivo del Prompt:**

Define el objetivo general del prompt:
"Objetivo del prompt: El objetivo es aumentar la participación, interés y motivación de los estudiantes a través de dinámicas interactivas que fomenten el pensamiento crítico, la resolución de problemas y el trabajo en equipo."

#### **6. Formato de Respuesta:**

Describe cómo se debe estructurar la respuesta:
"Formato de respuesta: Generar múltiples opciones y alternativas, desglosando los pros y contras de cada una de las opciones. Incluir una descripción de cada actividad y un ejemplo breve. Mostrar esto de manera textual al inicio con los detalles y luego en una tabla de resumen con toda la información sintetizada."


### **Ejemplo del Prompt**

**Nivel educativo de los estudiantes:** Pregrado

**Materia o tema específico:** Historia mundial: Segunda Guerra Mundial

**Contexto del uso del prompt:** Actividad calificada

**Objetivos de aprendizaje:**
- **Objetivo:** Los estudiantes podrán aplicar su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.
- **Acción:** Aplicar
- **Habilidad:** Aplicación
- **Criterios de Evaluación:** Los estudiantes participarán en un ejercicio de role-playing donde tendrán que tomar decisiones estratégicas basadas en diferentes contextos socioeconómicos de la Segunda Guerra Mundial.

**Objetivo del prompt:** El objetivo es aumentar la participación, interés y motivación de los estudiantes a través de dinámicas interactivas que fomenten el pensamiento crítico, la resolución de problemas y el trabajo en equipo.

**Formato de respuesta:**
Generar múltiples opciones y alternativas, desglosando los pros y contras de cada una de las opciones. Incluir una descripción de cada actividad y un ejemplo breve. Mostrar esto de manera textual al inicio con los detalles y luego en una tabla de resumen con toda la información sintetizada.

Una vez enviado este prompt, se obtuvo el siguiente resultado, la idea es que eligas la actividad que mas te guste y se acomode a los propositos que tengas en el curso 

### **Respuesta del prompt: opciones de actividades**

1. **Actividad: Juego de Memoria de Estructuras de Datos**
   - **Descripción:** Los estudiantes formarán equipos y jugarán un juego de memoria donde tendrán que emparejar tarjetas con nombres y características de diferentes estructuras de datos.
   - **Pros:** Fomenta el trabajo en equipo y la memoria visual.
   - **Contras:** Puede ser menos efectivo para estudiantes que prefieren el aprendizaje individual.

2. **Actividad: Debate sobre Eficiencia de Algoritmos**
   - **Descripción:** Los estudiantes discutirán en grupos sobre la eficiencia de diferentes algoritmos para resolver un problema específico.
   - **Pros:** Promueve el pensamiento crítico y la capacidad de argumentación.
   - **Contras:** Algunos estudiantes pueden sentirse incómodos al hablar en público.

3. **Actividad: Resolución de Problemas en Grupo**
   - **Descripción:** Los estudiantes trabajarán en grupos para resolver problemas de programación utilizando diferentes estructuras de datos.
   - **Pros:** Desarrolla habilidades de resolución de problemas y colaboración.
   - **Contras:** Requiere una preparación previa para comprender completamente las estructuras de datos.

[Ideación de actividades interactivas](https://www.notion.so/Ideaci-n-de-actividades-interactivas-7542a6c9213246588f1ec788d49390bc?pvs=21)

## **Refinamiento de una actividad**

### **Descripción**

Refina y mejora las actividades educativas ideadas previamente. Asegúrate de que sean claras, alcanzables y alineadas con los objetivos de aprendizaje.

### **Prerrequisitos**

- Haber completado la **Ideación de actividades**.

### **Descripción del prompt**

El prompt “Refinamiento de actividades” está diseñado para ayudar a educadores a refinar y detallar actividades educativas previamente seleccionadas, mejorando su claridad, viabilidad y efectividad en el cumplimiento de los objetivos de aprendizaje. Al responder una serie de preguntas sobre la descripción, recursos, duración, instrucciones, evaluación, participación, resultados esperados y adaptaciones, los educadores pueden desarrollar un documento completo y estructurado que integre toda la información necesaria para implementar exitosamente la actividad refinada en el contexto educativo específico.


### **Prompt**
```console
Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO] Pregrado, posgrado, educación continua, etc.`

Materia o tema específico: `[MATERIA TEMA] Historia, física, estructuras de datos`

Contexto del uso del prompt: `[CONTEXTO USO] Discusión de clase, bonos, actividad calificada`

Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE] Los estudiantes deben identificar al menos 3 estructuras de datos, los estudiantes deben comprender el concepto de un plano inclinado, etc.`

Objetivo del prompt: Refinar y detallar una actividad educativa seleccionada previamente para mejorar la claridad, viabilidad y efectividad en el cumplimiento de los objetivos de aprendizaje.

Formato de respuesta: Una vez que se respondan todas las preguntas, generar un documento que integre toda la información en un formato claro y estructurado, proporcionando una visión completa y detallada de la actividad refinada.

1. Descripción de la actividad:
• ¿Cuál es la actividad seleccionada? `[ACTIVIDAD SELECCIONADA]`
• ¿Cómo se desarrolla la actividad paso a paso? `[DESARROLLO PASOS]`

2. Recursos necesarios:
• ¿Qué materiales y recursos se necesitan para la actividad? `[MATERIALES NECESARIOS]`
• ¿Es necesario algún equipo o software específico? `[EQUIPO SOFTWARE]`

3. Duración de la actividad:
• ¿Cuánto tiempo se requiere para completar la actividad? `[TIEMPO REQUERIDO]`
• ¿La actividad se realizará en una sola sesión, en varias o fuera de clase? `[DURACIÓN SESIONES]`

4. Instrucciones para los estudiantes:
• ¿Cuáles son las instrucciones detalladas para los estudiantes? `[INSTRUCCIONES DETALLADAS]`
• ¿Qué información previa deben conocer los estudiantes antes de comenzar? `[INFORMACIÓN PREVIA]`

5. Evaluación:
• ¿Cómo se evaluará el desempeño de los estudiantes en esta actividad? `[EVALUACIÓN]`
• ¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.? `[TIPO EVALUACIÓN]`
6. Participación y roles:
• ¿Cómo se estructurará la participación de los estudiantes? (individual, parejas, grupos) `[ESTRUCTURA PARTICIPACIÓN]`
• ¿Qué roles específicos tendrán los estudiantes, si los hay? `[ROLES ESTUDIANTES]`

7. Resultados esperados:
• ¿Cuáles son los resultados y productos esperados de la actividad? `[RESULTADOS ESPERADOS]`
• ¿Cómo se alinean estos resultados con los objetivos de aprendizaje? `[ALINEACIÓN OBJETIVOS]`

8. Adaptaciones y consideraciones especiales:
• ¿Existen adaptaciones para estudiantes con necesidades especiales? `[ADAPTACIONES]`
• ¿Qué consideraciones adicionales deben tenerse en cuenta para asegurar la inclusión y la equidad? `[CONSIDERACIONES ESPECIALES]`
```


### **Detalle de los parámetros**

#### **1. Nivel Educativo de los Estudiantes:**

Indica el nivel educativo de los estudiantes:
"Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO]`..."

- **`[NIVEL EDUCATIVO]`**: Pregrado, Posgrado, educación continua, etc.

#### **2. Materia o Tema Específico:**

Define la materia o tema específico:
"Materia o tema específico: `[MATERIA TEMA]`..."

- **`[MATERIA TEMA]`**: Historia, Física, Estructuras de datos, etc.

#### **3. Contexto del Uso del Prompt:**

Explica el contexto del uso del prompt:
"Contexto del uso del prompt: `[CONTEXTO USO]`..."

- **`[CONTEXTO USO]`**: Discusión de clase, bonos, actividad calificada, etc.

#### **4. Objetivos de Aprendizaje:**

Detalla los objetivos de aprendizaje:
"Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE]`..."

- **`[OBJETIVO DE APRENDIZAJE]`**: Los estudiantes deben identificar al menos 3 estructuras de datos, comprender el concepto de un plano inclinado, etc.

#### **5. Descripción de la Actividad:**

Describe la actividad y sus pasos:

1. "¿Cuál es la actividad seleccionada? `[ACTIVIDAD SELECCIONADA]`..."
    - **`[ACTIVIDAD SELECCIONADA]`**: Describe brevemente la actividad.
2. "¿Cómo se desarrolla la actividad paso a paso? `[DESARROLLO PASOS]`..."
    - **`[DESARROLLO PASOS]`**: Detalla los pasos específicos.

#### **6. Recursos Necesarios:**

Lista los materiales y recursos necesarios:

1. "¿Qué materiales y recursos se necesitan? `[MATERIALES NECESARIOS]`..."
    - **`[MATERIALES NECESARIOS]`**: Enumera los materiales.
2. "¿Es necesario algún equipo o software específico? `[EQUIPO SOFTWARE]`..."
    - **`[EQUIPO SOFTWARE]`**: Indica si se necesita equipo o software específico.

#### **7. Duración de la Actividad:**

Indica el tiempo necesario:

1. "¿Cuánto tiempo se requiere? `[TIEMPO REQUERIDO]`..."
    - **`[TIEMPO REQUERIDO]`**: Estima el tiempo necesario.
2. "¿Se realizará en una sola sesión o en varias? `[DURACIÓN SESIONES]`..."
    - **`[DURACIÓN SESIONES]`**: Especifica si se realizará en una o varias sesiones.

#### **8. Instrucciones para los Estudiantes:**

Proporciona instrucciones detalladas:

1. "¿Cuáles son las instrucciones? `[INSTRUCCIONES DETALLADAS]`..."
    - **`[INSTRUCCIONES DETALLADAS]`**: Explica las instrucciones paso a paso.
2. "¿Qué información previa deben conocer? `[INFORMACIÓN PREVIA]`..."
    - **`[INFORMACIÓN PREVIA]`**: Describe la información previa necesaria.

#### **9. Evaluación:**

Detalla cómo se evaluará:

1. "¿Cómo se evaluará? `[EVALUACIÓN]`..."
    - **`[EVALUACIÓN]`**: Explica el método de evaluación.
2. "¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.? `[TIPO EVALUACIÓN]`..."
    - **`[TIPO EVALUACIÓN]`**: Indica los tipos de evaluación.

#### **10. Participación y Roles:**

Explica la participación y roles:

1. "¿Cómo se estructurará la participación? `[ESTRUCTURA PARTICIPACIÓN]`..."
    - **`[ESTRUCTURA PARTICIPACIÓN]`**: Describe la estructura de participación.
2. "¿Qué roles tendrán los estudiantes? `[ROLES ESTUDIANTES]`..."
    - **`[ROLES ESTUDIANTES]`**: Indica los roles específicos.

#### **11. Resultados Esperados:**

Define los resultados esperados:

1. "¿Cuáles son los resultados esperados? `[RESULTADOS ESPERADOS]`..."
    - **`[RESULTADOS ESPERADOS]`**: Describe los resultados esperados.
2. "¿Cómo se alinean estos resultados con los objetivos de aprendizaje? `[ALINEACIÓN OBJETIVOS]`..."
    - **`[ALINEACIÓN OBJETIVOS]`**: Explica la alineación con los objetivos.

#### **12. Adaptaciones y Consideraciones Especiales:**

Detalla adaptaciones y consideraciones especiales:

1. "¿Existen adaptaciones para estudiantes con necesidades especiales? `[ADAPTACIONES]`..."
    - **`[ADAPTACIONES]`**: Menciona las adaptaciones necesarias.
2. "¿Qué consideraciones adicionales deben tenerse en cuenta? `[CONSIDERACIONES ESPECIALES]`..."
    - **`[CONSIDERACIONES ESPECIALES]`**: Describe las consideraciones adicionales.

#### **Ejemplo de Uso del Prompt**

**Nivel educativo de los estudiantes:** Pregrado

**Materia o tema específico:** Historia Mundial: Segunda guerra mundial

**Contexto del uso del prompt:** Actividad calificada

**Objetivos de aprendizaje:**

Objetivo: Los estudiantes podrán aplicar su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.

**Acción:** Aplicar

**Habilidad:** Aplicación

**Criterios de Evaluación:** Los estudiantes participarán en un ejercicio de role-playing donde tendrán que tomar decisiones estratégicas basadas en diferentes contextos socioeconómicos de la Segunda Guerra Mundial.

**Objetivo del prompt:** Refinar y detallar una actividad educativa seleccionada previamente para mejorar la claridad, viabilidad y efectividad en el cumplimiento de los objetivos de aprendizaje.

**Formato de respuesta:** Una vez que se respondan todas las preguntas, generar un documento que integre toda la información en un formato claro y estructurado, proporcionando una visión completa y detallada de la actividad refinada.

1. **Descripción de la actividad:**

- ¿Cuál es la actividad seleccionada? Los estudiantes escriben una serie de cartas entre un soldado en el frente y su familia en casa, reflejando diferentes contextos socioeconómicos.
- ¿Cómo se desarrolla la actividad paso a paso? Los estudiantes deben desarrollar en grupos de 3 cartas entre un soldado y su familia, pero deben hacerlo desde la perspectiva de una persona de clase alta, media y baja de la época. Deben escribir las cartas durante clase y mostrar avances, y luego entregarlo una semana después

2. **Recursos necesarios:**

- ¿Qué materiales y recursos se necesitan para la actividad? Pueden usar computador o pueden hacerlo en papel, lo que prefieran
- ¿Es necesario algún equipo o software específico? Algún editor de texto si deciden utilizar computador

3. **Duración de la actividad:**

- ¿Cuánto tiempo se requiere para completar la actividad? 1 semana
- ¿La actividad se realizará en una sola sesión, en varias o fuera de clase? Inician en clase para poder resolver cualquier duda y tienen una semana para entregar desde el inicio de la actividad

4. **Instrucciones para los estudiantes:**

- ¿Cuáles son las instrucciones detalladas para los estudiantes? Deben organizarse en grupos de 3 estudiantes. Cada estudiante debe seleccionar representar cada clase socioeconómica seleccionada (alta, media, baja) y empezar a redactar la carta con el rol que le corresponda. Entre ellos deciden quién va a representar a quien
- ¿Qué información previa deben conocer los estudiantes antes de comenzar? Las causas de la segunda guerra mundial, cómo vivía una persona en europa en ese tiempo, cuales eran las diferentes condiciones socioeconómicas dependiendo de el país y clase social de los individuos, las consecuencias de la guerra

5. **Evaluación:**

- ¿Cómo se evaluará el desempeño de los estudiantes en esta actividad? Que las cartas reflejen el entendimiento de los conceptos explicados en clase de Las causas de la segunda guerra mundial, cómo vivía una persona en europa en ese tiempo, cuales eran las diferentes condiciones socioeconómicas dependiendo de el país y clase social de los individuos, las consecuencias de la guerra y que tengan una buena ortografía
- ¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.? Rubrica de evaluación

6. **Participación y roles:**

- ¿Cómo se estructurará la participación de los estudiantes? (individual, parejas, grupos) En grupos de 3, cada uno debe hacer una carta desde una perspectiva diferente
- ¿Qué roles específicos tendrán los estudiantes, si los hay? Uno por cada clase social

7. **Resultados esperados:**

- ¿Cuáles son los resultados y productos esperados de la actividad? Las 3 cartas terminadas desde las diferentes perspectivas
- ¿Cómo se alinean estos resultados con los objetivos de aprendizaje? Deben reflejar el entendimiento de los estudiantes de las diferencias entre las clases sociales y poder aplicar esto en soluciones a distintos contextos históricos

8. **Adaptaciones y consideraciones especiales:**

- ¿Existen adaptaciones para estudiantes con necesidades especiales? No
- ¿Qué consideraciones adicionales deben tenerse en cuenta para asegurar la inclusión y la equidad? Ninguna


Una vez implementado el prompt, se dio como resultado la siguiente actividad con sus caracteristicas, sientete libre de modificar caracteristicas o resultados de la actividad refinada 

#### Actividad Educativa Refinada: Cartas desde Diferentes Contextos Socioeconómicos durante la Segunda Guerra Mundial

#### 1. Descripción de la Actividad:

- **Actividad Seleccionada:** Los estudiantes escriben una serie de cartas entre un soldado en el frente y su familia en casa, reflejando diferentes contextos socioeconómicos.
- **Desarrollo Paso a Paso:** Los estudiantes se organizan en grupos de tres. Cada estudiante asume el rol de representar una clase socioeconómica diferente (alta, media, baja) durante la Segunda Guerra Mundial. Deben redactar tres cartas en total: una desde la perspectiva de cada clase social, reflejando cómo vivían, las preocupaciones y las condiciones durante la guerra. La actividad inicia en clase para discutir y resolver dudas, y los estudiantes tienen una semana para completar y entregar las cartas finalizadas.
  
#### 2. Recursos Necesarios:

- **Materiales y Recursos:** Papel y bolígrafos o computadoras con acceso a un editor de texto.
- **Equipo o Software Específico:** Opcionalmente, un editor de texto si se decide usar computadoras.

#### 3. Duración de la Actividad:

- **Tiempo Requerido:** La actividad se extiende a lo largo de una semana.
- **Estructura de Sesiones:** Inicio en clase para la discusión inicial y resolución de dudas, con la entrega final una semana después.

#### 4. Instrucciones para los Estudiantes:

- **Instrucciones Detalladas:**
  - Formen grupos de tres estudiantes.
  - Cada estudiante elige representar una clase social (alta, media, baja).
  - Escriban una carta desde la perspectiva de cada clase social, reflejando cómo la guerra afectó a cada uno.
  - Inicien la redacción en clase y organicen el trabajo para la entrega final.

- **Conocimientos Previos Requeridos:**
  - Causas de la Segunda Guerra Mundial.
  - Condiciones de vida en Europa durante el conflicto.
  - Diferencias socioeconómicas entre países y clases sociales.
  - Consecuencias de la guerra.

#### 5. Evaluación:

- **Criterios de Evaluación:**
  - Las cartas deben reflejar comprensión de las condiciones socioeconómicas durante la Segunda Guerra Mundial.
  - Uso adecuado de la ortografía y gramática.
- **Instrumentos de Evaluación:** Se utilizará una rúbrica detallada para evaluar las cartas.

#### 6. Participación y Roles:

- **Estructura de Participación:** Trabajo en grupos de tres estudiantes.
- **Roles Específicos:** Cada estudiante representa una clase social diferente (alta, media, baja).

#### 7. Resultados Esperados:

- **Productos de la Actividad:** Tres cartas finalizadas, una desde cada perspectiva socioeconómica.
- **Alineación con los Objetivos de Aprendizaje:** Las cartas demostrarán la comprensión de las diferencias entre las clases sociales y la capacidad de aplicar este entendimiento a contextos históricos específicos.

#### 8. Adaptaciones y Consideraciones Especiales:

- **Adaptaciones para Necesidades Especiales:** No se requieren adaptaciones específicas para esta actividad.
- **Consideraciones de Inclusión y Equidad:** Asegurar que todos los estudiantes tengan acceso equitativo a los recursos necesarios para completar la actividad.

Esta actividad está diseñada para permitir a los estudiantes explorar y comprender las diferentes realidades socioeconómicas durante la Segunda Guerra Mundial a través de un ejercicio de escritura creativa, promoviendo el pensamiento crítico y la empatía histórica.

[Refinamiento de actividades](https://www.notion.so/Refinamiento-de-actividades-2be8319cc31846f3886698dfe21646c2?pvs=21)

## Creación de una rúbrica

### **Descripción**

Aprenderás a crear una rúbrica efectiva, definiendo criterios claros y escalas de puntuación para evaluar actividades educativas.

### **Prerrequisitos**

- Haber completado el **Refinamiento de una actividad**.

### **Descripción del prompt**

El siguiente prompt está diseñado para ayudar a los profesores a crear rúbricas a partir de actividades previamente diseñadas por el prompt de creación de actividades, o previamente diseñadas por el profesor utilizando herramientas de inteligencia artificial generativa.

### **Prompt**
```console
Prompt: Crear una rúbrica para una actividad educativa

Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO]` (Pregrado, posgrado, educación continua, etc.)

Materia o tema específico: `[MATERIA/TEMA]` (Historia, física, estructuras de datos)

Contexto del uso del prompt: `[CONTEXTO USO]` (Discusión de clase, bonos, actividad calificada)

Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE]` (Los estudiantes deben identificar al menos 3 estructuras de datos, los estudiantes deben comprender el concepto de un plano inclinado, etc.)

Objetivo del prompt: Crear una rúbrica detallada y estructurada para evaluar una actividad educativa específica, asegurando que cubra todos los aspectos necesarios para una evaluación clara y justa de los estudiantes.

Formato de respuesta: Generar una rúbrica completa con criterios de evaluación, intervalos de calificación, puntaje total, distribución porcentual de los puntos, y comentarios específicos para cada nivel de desempeño.

Quiero que me preguntes por cada una de estas preguntas, una por una, y una vez tengas toda la información me des la respuesta final:

1. Descripción de la actividad:
• ¿Cuál es la actividad seleccionada? `[ACTIVIDAD SELECCIONADA]`
• ¿Cómo se alinea esta actividad con los objetivos de aprendizaje? `[ALINEACIÓN CON OBJETIVOS]`

2. Objetivos de aprendizaje:
• ¿Cuáles son los objetivos de aprendizaje específicos que esta actividad debe cumplir? `[OBJETIVOS ESPECÍFICOS]`
• ¿Qué habilidades o conocimientos específicos se espera que los estudiantes demuestren a través de esta actividad? `[HABILIDADES Y CONOCIMIENTOS]`

3. Criterios de evaluación:
• ¿Qué aspectos específicos de la actividad deben evaluarse para asegurar que se cumplan los objetivos de aprendizaje? `[ASPECTOS A EVALUAR]`
• ¿Cómo se pueden desglosar estos aspectos en criterios claros y medibles? `[CRITERIOS CLAROS Y MEDIBLES]`

4. Intervalo de calificación:
• ¿Cuál debería ser el rango de puntos para cada criterio de evaluación (punto mínimo y máximo)? `[RANGO DE PUNTOS]`
• ¿Cómo se puede estructurar este intervalo para reflejar diferentes niveles de dominio (perfecto, bueno, medio, bajo)? `[ESTRUCTURA DEL INTERVALO]`

5. Puntaje total:
• ¿Cuál es el puntaje total posible para la rúbrica? `[PUNTAJE TOTAL]`
• ¿Cómo podemos distribuir los puntos de manera justa para reflejar la importancia de cada criterio? `[DISTRIBUCIÓN JUSTA]`

6. Distribución porcentual:
• ¿Cómo se deben distribuir los puntos en los criterios de evaluación?
    ◦ Criterio 1: `[10%]`
    ◦ Criterio 2: `[20%]`
    ◦ ... `[DISTRIBUCIÓN PERCENTUAL]`

7. Comentarios por nivel de desempeño:
• ¿Cuáles son los comentarios específicos para cada posible cantidad de puntos asignada en cada criterio? `[COMENTARIOS ESPECÍFICOS]`
• ¿Cómo describiríamos el desempeño perfecto, bueno, medio y bajo para cada criterio, de manera que sea claro para los estudiantes? `[DESCRIPCIÓN DE DESEMPEÑO]`

8. Evaluación global:
• ¿Cómo se evaluará el desempeño global de los estudiantes en esta actividad? `[EVALUACIÓN GLOBAL]`
• ¿Qué otros métodos de evaluación (además de la rúbrica) podrían complementarse para tener una visión completa del rendimiento del estudiante? `[MÉTODOS COMPLEMENTARIOS]`

9. Formato de respuesta:
• Una vez que se respondan todas las preguntas, generar una tabla clara y detallada que organice toda la información, proporcionando una rúbrica completa y estructurada para la actividad seleccionada. 
```
### **Detalle de los parámetros**

#### **1. Nivel Educativo de los Estudiantes:**

Indica el nivel educativo de los estudiantes:
"Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO]`..."

- **`[NIVEL EDUCATIVO]`**: Pregrado, Posgrado, educación continua, etc.

#### **2. Materia o Tema Específico:**

Define la materia o tema específico:
"Materia o tema específico: `[MATERIA/TEMA]`..."

- **`[MATERIA/TEMA]`**: Historia, Física, Estructuras de datos, etc.

#### **3. Contexto del Uso del Prompt:**

Explica el contexto del uso del prompt:
"Contexto del uso del prompt: `[CONTEXTO USO]`..."

- **`[CONTEXTO USO]`**: Discusión de clase, bonos, actividad calificada, etc.

#### **4. Objetivos de Aprendizaje:**

Detalla los objetivos de aprendizaje:
"Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE]`..."

- **`[OBJETIVO DE APRENDIZAJE]`**: Los estudiantes deben identificar al menos 3 estructuras de datos, comprender el concepto de un plano inclinado, etc.

#### **5. Descripción de la Actividad:**

Describe la actividad y su alineación con los objetivos:

1. "¿Cuál es la actividad seleccionada? `[ACTIVIDAD SELECCIONADA]`..."
    - **`[ACTIVIDAD SELECCIONADA]`**: Describe brevemente la actividad.
2. "¿Cómo se alinea esta actividad con los objetivos de aprendizaje? `[ALINEACIÓN CON OBJETIVOS]`..."
    - **`[ALINEACIÓN CON OBJETIVOS]`**: Explica la alineación con los objetivos.

#### **6. Objetivos de Aprendizaje Específicos:**

Define los objetivos de aprendizaje específicos y habilidades:

1. "¿Cuáles son los objetivos de aprendizaje específicos que esta actividad debe cumplir? `[OBJETIVOS ESPECÍFICOS]`..."
    - **`[OBJETIVOS ESPECÍFICOS]`**: Lista los objetivos específicos.
2. "¿Qué habilidades o conocimientos específicos se espera que los estudiantes demuestren? `[HABILIDADES Y CONOCIMIENTOS]`..."
    - **`[HABILIDADES Y CONOCIMIENTOS]`**: Indica las habilidades y conocimientos esperados.

#### **7. Criterios de Evaluación:**

Establece los aspectos y criterios de evaluación:

1. "¿Qué aspectos específicos de la actividad deben evaluarse? `[ASPECTOS A EVALUAR]`..."
    - **`[ASPECTOS A EVALUAR]`**: Detalla los aspectos a evaluar.
2. "¿Cómo se pueden desglosar estos aspectos en criterios claros y medibles? `[CRITERIOS CLAROS Y MEDIBLES]`..."
    - **`[CRITERIOS CLAROS Y MEDIBLES]`**: Explica cómo desglosar los aspectos en criterios medibles.

#### **8. Intervalo de Calificación:**

Define el rango de puntos y estructura del intervalo:

1. "¿Cuál debería ser el rango de puntos para cada criterio de evaluación? `[RANGO DE PUNTOS]`..."
    - **`[RANGO DE PUNTOS]`**: Establece el rango de puntos.
2. "¿Cómo se puede estructurar este intervalo para reflejar diferentes niveles de dominio? `[ESTRUCTURA DEL INTERVALO]`..."
    - **`[ESTRUCTURA DEL INTERVALO]`**: Explica la estructura del intervalo.

#### **9. Puntaje Total:**

Determina el puntaje total y su distribución:

1. "¿Cuál es el puntaje total posible para la rúbrica? `[PUNTAJE TOTAL]`..."
    - **`[PUNTAJE TOTAL]`**: Indica el puntaje total.
2. "¿Cómo podemos distribuir los puntos de manera justa para reflejar la importancia de cada criterio? `[DISTRIBUCIÓN JUSTA]`..."
    - **`[DISTRIBUCIÓN JUSTA]`**: Explica la distribución justa de puntos.

#### **10. Distribución Porcentual:**

Distribuye los puntos porcentualmente:

1. "¿Cómo se deben distribuir los puntos en los criterios de evaluación? `[DISTRIBUCIÓN PERCENTUAL]`..."
    - **`[DISTRIBUCIÓN PERCENTUAL]`**: Indica la distribución porcentual de cada criterio.

#### **11. Comentarios por Nivel de Desempeño:**

Proporciona comentarios para cada nivel de desempeño:

1. "¿Cuáles son los comentarios específicos para cada posible cantidad de puntos asignada en cada criterio? `[COMENTARIOS ESPECÍFICOS]`..."
    - **`[COMENTARIOS ESPECÍFICOS]`**: Describe los comentarios específicos.
2. "¿Cómo describiríamos el desempeño perfecto, bueno, medio y bajo para cada criterio? `[DESCRIPCIÓN DE DESEMPEÑO]`..."
    - **`[DESCRIPCIÓN DE DESEMPEÑO]`**: Explica la descripción del desempeño.

#### **12. Evaluación Global:**

Establece la evaluación global y métodos complementarios:

1. "¿Cómo se evaluará el desempeño global de los estudiantes en esta actividad? `[EVALUACIÓN GLOBAL]`..."
    - **`[EVALUACIÓN GLOBAL]`**: Describe la evaluación global.
2. "¿Qué otros métodos de evaluación podrían complementarse para una visión completa del rendimiento del estudiante? `[MÉTODOS COMPLEMENTARIOS]`..."
    - **`[MÉTODOS COMPLEMENTARIOS]`**: Indica los métodos complementarios.

#### **13. Formato de Respuesta:**

Explica cómo se debe presentar la información:
"Una vez que se respondan todas las preguntas, generar una tabla clara y detallada que organice toda la información, proporcionando una rúbrica completa y estructurada para la actividad seleccionada."


### **Ejemplo de uso del prompt**

**Rúbrica de evaluación**

**Nivel educativo de los estudiantes:** Pregrado

**Materia o tema específico: Historia mundial:** Segunda guerra mundial

**Contexto del uso del prompt:** Actividad calificada

**Objetivos de aprendizaje:**

Objetivo: Los estudiantes podrán aplicar su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.

**Acción:** Aplicar

**Habilidad:** Aplicación

**Criterios de Evaluación:** Los estudiantes participarán en un ejercicio de role-playing donde tendrán que tomar decisiones estratégicas basadas en diferentes contextos socioeconómicos de la Segunda Guerra Mundial.

**Objetivo del prompt:**

Crear una rúbrica detallada y estructurada para evaluar una actividad educativa específica, asegurando que cubra todos los aspectos necesarios para una evaluación clara y justa de los estudiantes.

**Formato de respuesta:**

Generar una rúbrica completa con criterios de evaluación, intervalos de calificación, puntaje total, distribución porcentual de los puntos, y comentarios específicos para cada nivel de desempeño.

Quiero que me preguntes por cada una de estas preguntas, una por una, y una vez tengas toda la información me des la respuesta final:

1. **Descripción de la actividad:**

- ¿Cuál es la actividad seleccionada? Los estudiantes escribirán una serie de cartas entre un soldado en el frente y su familia en casa, reflejando diferentes contextos socioeconómicos. Se organizarán en grupos de 3 y cada estudiante representará una clase socioeconómica diferente (alta, media, baja). Redactarán 3 cartas: una desde la perspectiva del soldado y dos desde la perspectiva de su familia en casa. Las cartas se escribirán durante la clase para resolver dudas y se entregarán una semana después.
- ¿Cómo se alinea esta actividad con los objetivos de aprendizaje? Deben reflejar el entendimiento de los estudiantes de las diferencias entre las clases sociales y poder aplicar esto en soluciones a distintos contextos históricos

2. **Objetivos de aprendizaje:**

- ¿Cuáles son los objetivos de aprendizaje específicos que esta actividad debe cumplir? Los estudiantes podrán aplicar su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.
- ¿Qué habilidades o conocimientos específicos se espera que los estudiantes demuestren a través de esta actividad? Que sean capaces de analizar e interpretar los diferentes roles que existieron durante la guerra y contrastar y comparar entre ellos

3. **Criterios de evaluación:**

- ¿Qué aspectos específicos de la actividad deben evaluarse para asegurar que se cumplan los objetivos de aprendizaje? Ortografía, uso correcto de conceptos, veracidad con los eventos ocurridos
- ¿Cómo se pueden desglosar estos aspectos en criterios claros y medibles? Uso correcto de ortografía y coherencia textual, uso correcto de conceptos y relación con las cartas

4. **Intervalo de calificación:**

- ¿Cuál debería ser el rango de puntos para cada criterio de evaluación (punto mínimo y máximo)? Mínimo 2.5, máximo 5
- ¿Cómo se puede estructurar este intervalo para reflejar diferentes niveles de dominio (perfecto, bueno, medio, bajo)? Una correspondencia numérica donde 2.5 es deficiente, 3.5 es suficiente, 4.5 es sobresaliente y 5 excelente

5. **Puntaje total:**

- ¿Cuál es el puntaje total posible para la rúbrica? 5
- ¿Cómo podemos distribuir los puntos de manera justa para reflejar la importancia de cada criterio? Dar mayor importancia al uso correcto de conceptos y relación con las cartas y un porcentaje menor a ortografía y coherencia

6. **Distribución porcentual:**

- ¿Cómo se deben distribuir los puntos en los criterios de evaluación?

- uso correcto de conceptos (40%)

- relación con las cartas (40%)

- Uso correcto de ortografía y coherencia textual (20%)

7. **Comentarios por nivel de desempeño:**

- ¿Cuáles son los comentarios específicos para cada posible cantidad de puntos asignada en cada criterio? Ayúdame a generarlos
- ¿Cómo describiríamos el desempeño perfecto, bueno, medio y bajo para cada criterio, de manera que sea claro para los estudiantes? Ayúdame a generar la descripción

8. **Evaluación global:**

- ¿Cómo se evaluará el desempeño global de los estudiantes en esta actividad? A partir de la rúbrica y el nivel de desempeño en cada criterio
- ¿Qué otros métodos de evaluación (además de la rúbrica) podrían complementarse para tener una visión completa del rendimiento del estudiante? Ninguno

9. **Formato de respuesta:**

- Una vez que se respondan todas las preguntas, generar una tabla clara y detallada que organice toda la información, proporcionando una rúbrica completa y estructurada para la actividad seleccionada.

### **Resultados del prompt**

A continuación, se ve el resultado del prompt anterior, donde se ve la rubrica, la cual puede pasar por el proceso de refinamiento en el siguiente prompt

Vamos a organizar toda la información para crear una rúbrica completa y estructurada para la actividad de escribir cartas desde diferentes contextos socioeconómicos durante la Segunda Guerra Mundial.

#### 1. Descripción de la actividad:

- **Actividad Seleccionada:** Los estudiantes escribirán una serie de cartas entre un soldado en el frente y su familia en casa, reflejando diferentes contextos socioeconómicos. Se organizarán en grupos de 3 y cada estudiante representará una clase socioeconómica diferente (alta, media, baja). Redactarán 3 cartas: una desde la perspectiva del soldado y dos desde la perspectiva de su familia en casa. Las cartas se escribirán durante la clase para resolver dudas y se entregarán una semana después.
- **Cómo se alinea esta actividad con los objetivos de aprendizaje:** La actividad busca que los estudiantes apliquen su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.

#### 2. Objetivos de aprendizaje:

- **Objetivos de aprendizaje específicos:** Los estudiantes podrán aplicar su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.
- **Habilidades o conocimientos específicos:** Se espera que los estudiantes demuestren habilidades analíticas e interpretativas al contrastar y comparar los roles socioeconómicos durante la Segunda Guerra Mundial.

#### 3. Criterios de evaluación:

- **Aspectos específicos a evaluar:**
  - Ortografía y coherencia textual.
  - Uso correcto de conceptos históricos relevantes.
  - Relación con los eventos históricos y contextos socioeconómicos.

- **Desglose de criterios claros y medibles:** 
  - Ortografía y coherencia: Evaluar la precisión y la estructura gramatical de las cartas.
  - Uso correcto de conceptos: Verificar si los términos históricos son utilizados correctamente.
  - Relación con los contextos: Evaluar la precisión y la cohesión de las cartas con respecto a los eventos y contextos socioeconómicos.

#### 4. Intervalo de calificación:

- **Rango de puntos:** De 2.5 a 5.
- **Estructura del intervalo:**
  - 2.5: Deficiente.
  - 3.5: Suficiente.
  - 4.5: Sobresaliente.
  - 5: Excelente.

#### 5. Puntaje total:

- **Puntaje total posible:** 5 puntos.
- **Distribución de puntos:**
  - Uso correcto de conceptos y relación con las cartas: 80% del puntaje.
  - Ortografía y coherencia textual: 20% del puntaje.

#### 6. Distribución porcentual:

- **Uso correcto de conceptos:** 40%
- **Relación con las cartas:** 40%
- **Uso correcto de ortografía y coherencia textual:** 20%

#### 7. Comentarios por nivel de desempeño:

- **Desempeño perfecto (5):** Las cartas reflejan un entendimiento profundo de las diferencias socioeconómicas durante la Segunda Guerra Mundial, utilizando términos históricos de manera precisa y relacionándolos coherentemente con los contextos socioeconómicos.
- **Desempeño bueno (4.5):** Las cartas muestran un excelente manejo de los conceptos históricos y una buena conexión con los contextos, con mínimos errores gramaticales.
- **Desempeño medio (3.5):** Las cartas demuestran comprensión de los conceptos básicos, aunque con algunos errores en la precisión histórica y la cohesión textual.
- **Desempeño bajo (2.5):** Las cartas tienen múltiples errores en el uso de conceptos históricos y falta de conexión con los contextos socioeconómicos.

#### 8. Evaluación global:

- El desempeño global de los estudiantes será evaluado sumando los puntos asignados en cada criterio de la rúbrica.

#### 9. Formato de respuesta:

A continuación, la tabla clara y detallada que organiza toda la información en una rúbrica completa y estructurada:

| Criterio de Evaluación               | Descripción                                                                 | Puntos |
|--------------------------------------|-----------------------------------------------------------------------------|--------|
| Uso correcto de conceptos            | Precisión en el uso de términos históricos relevantes y su relación con las cartas. | 40%    |
| Relación con las cartas              | Coherencia y conexión de las cartas con los contextos socioeconómicos durante la Segunda Guerra Mundial. | 40%    |
| Ortografía y coherencia textual      | Correcta estructura gramatical y ortográfica de las cartas.                   | 20%    |

- **Puntaje Total:** 5 puntos

Esta rúbrica asegura que la evaluación de la actividad sea clara y justa, alineada con los objetivos de aprendizaje establecidos y proporcionando retroalimentación específica para cada nivel de desempeño.

[Creación de Rúbricas](https://www.notion.so/Creaci-n-de-R-bricas-a7fd72f57f0e4c7b94de5d93fb30d11f?pvs=21)

## **Refinamiento de la rúbrica**

### **Descripción**

Mejora y ajusta la rúbrica creada para asegurar que sea válida, fiable y aplicable a la actividad educativa.

### **Prerrequisitos**

- Haber completado la **Creación de una rúbrica**.

### **Descripción del Prompt**

Este prompt está diseñado para ayudar a los profesores a refinar una rúbrica a partir de una actividad previamente desarrollada y su respectiva rúbrica, ya sea por el prompt de actividades o por el docente utilizando herramientas de inteligencia artificial generativa.

### **Prompt**
 ``` console
Hola, soy un profesor de[materia] y necesito tu ayuda para refinar una rúbrica [Rúbrica realizada con el prompt de creación de rúbricas] ya creada para la siguiente actividad: [Actividad realizada previamente con el promt de actividades].

Quisiera que la rúbrica refinada tenga las siguientes características:

Problemas identificados: He identificado los siguientes problemas en la rúbrica actual:
- [Problema 1]
- [Problema 2]
- [Problema 3]
- ...

Criterios de evaluación: Quisiera refinar o añadir los siguientes criterios de evaluación:
- [Criterio de evaluación 1]
- [Criterio de evaluación 2]
- [Criterio de evaluación 3]
- ...

Además, necesito que se haga una corrección en [Corrección puntual/específica que se quiera hacer a la rúbrica]

Por favor, organiza esta información en una tabla clara y detallada.
```

### **Detalle de los parámetros**

#### **1. Introducción:**

Comienza el prompt con una breve presentación:
"Hola, soy un profesor de `[materia]` y necesito tu ayuda para refinar una rúbrica ya creada para la siguiente actividad: `[Actividad]`."

- **`[materia]`**: Sustituye esta sección con la materia que enseñas, por ejemplo, Matemáticas, Historia, Programación, etc. Sé detallado e incluye, de ser posible, el tema específico que estás tratando en tu materia.
- **`[Rúbrica]`**: Adjunta la rúbrica que se quiere refinar
- **`[Actividad]`**: Adjunta la actividad que se usa para esta rúbrica

#### **2. Problemas identificados:**

Indica los problemas o áreas que necesitan refinamiento en la rúbrica actual:
"He identificado los siguientes problemas en la rúbrica actual:

- [Problema 1]
- [Problema 2]
- [Problema 3]
- ..."
- **`[Problema 1]`, `[Problema 2]`, `[Problema 3]`**: Enumera los problemas específicos que has encontrado en la rúbrica actual que necesitan ser corregidos o mejorados.

#### **3. Criterios de Evaluación:**

Detalla los criterios de evaluación que deseas refinar o añadir:
"Quisiera refinar o añadir los siguientes criterios de evaluación:

- [Criterio de evaluación 1]
- [Criterio de evaluación 2]
- [Criterio de evaluación 3]
- ..."
- **`[Criterio de evaluación 1]`, `[Criterio de evaluación 2]`, `[Criterio de evaluación 3]`**: Especifica los criterios de evaluación que necesitas ajustar o incorporar en la rúbrica para mejorar la evaluación de los estudiantes.

#### **4. Corrección Puntual:**

Solicita una corrección específica o puntual que deseas hacer en la rúbrica:
"Además, necesito que se haga una corrección en `[Corrección puntual/específica que se quiera hacer a la rúbrica]`."

- **`[Corrección puntual/específica que se quiera hacer a la rúbrica]`**: Describe detalladamente la corrección o ajuste específico que deseas implementar en la rúbrica existente, acá puede libremente escribir algo puntual que no se haya detallado en los puntos anteriores a corregir.

#### **5. Formato de Visualización:**

Elige cómo deseas que se presente la rúbrica:
"...Por favor, organiza esta información en una tabla clara y detallada."

### **Ejemplo Completo:**

A continuación se presenta un ejemplo concreto del prompt para el refinamiento de rúbricas:

**1. Introducción:**

Hola, soy un profesor de Historia y necesito tu ayuda para refinar una rúbrica ya creada para la siguiente actividad: Los estudiantes deben realizar una presentación sobre un evento histórico relevante del siglo XX.

**2. Problemas Identificados:**

He identificado los siguientes problemas en la rúbrica actual:

- El criterio de originalidad no está claramente definido.
- La distribución de puntos entre los criterios no es equitativa.
- Falta un criterio para evaluar la coherencia del argumento histórico.

**3. Criterios de Evaluación:**

Quisiera refinar o añadir los siguientes criterios de evaluación:

- Añadir un criterio para evaluar la coherencia del argumento histórico presentado.
- Modificar el criterio de originalidad para incluir ejemplos específicos.
- Revisar la distribución de puntos para asegurar una evaluación más equilibrada.

**4. Corrección Puntual:**

Además, necesito que se haga una corrección en la ponderación de los puntos asignados a cada criterio para reflejar mejor su importancia relativa en la evaluación final.

**5. Formato de Visualización:**

### **RESPUESTA DEL PROMPT**

Por favor, organiza esta información en una tabla clara y detallada.

Aquí está la tabla clara y detallada con la rúbrica refinada para la actividad de escribir cartas desde diferentes contextos socioeconómicos durante la Segunda Guerra Mundial:

| Criterio de Evaluación               | Descripción                                                                 | Puntos |
|--------------------------------------|-----------------------------------------------------------------------------|--------|
| Uso correcto de conceptos históricos  | Precisión en el uso de términos históricos relevantes y su relación con las cartas. | 40%    |
| Coherencia con los contextos socioeconómicos | Coherencia y conexión de las cartas con los contextos socioeconómicos durante la Segunda Guerra Mundial. | 40%    |
| Ortografía y coherencia textual      | Correcta estructura gramatical y ortográfica de las cartas.                   | 20%    |

- **Puntaje Total:** 5 puntos

Esta rúbrica asegura que la evaluación de la actividad sea clara y justa, alineada con los objetivos de aprendizaje establecidos y proporcionando retroalimentación específica para cada nivel de desempeño.

[Refinamiento de Rúbricas](https://www.notion.so/Refinamiento-de-R-bricas-49b04c804018416e83b3569fc87112b3?pvs=21)

## Creación de enunciado con base en una rúbrica

### **Descripción**

Genera enunciados claros y detallados para las actividades, utilizando la rúbrica refinada como base para asegurar que los criterios de evaluación sean transparentes.

### **Prerrequisitos**

- Haber completado la **Creación de una rúbrica**.
- Haber completado el **Refinamiento de la rúbrica**.

### **Descripción del prompt**

Este prompt esta diseñado para crear un enunciado basado en una actividad y su rúbrica correspondiente, para ayudar al profesor a crear el contexto del problema de una forma clara para sus estudiantes, tal que incluya todos los requerimientos y sus valores en la nota.

### **Prompt**

```console
Nivel educativo de los estudiantes: [NIVEL EDUCATIVO] (Pregrado, posgrado, educación continua, etc.)

Materia o tema específico: [MATERIA/TEMA] (Historia, física, estructuras de datos)

Contexto del uso del prompt: [CONTEXTO USO] (Discusión de clase, bonos, actividad calificada)

Objetivos de aprendizaje: [OBJETIVO DE APRENDIZAJE] (Los estudiantes deben identificar al menos 3 estructuras de datos, los estudiantes deben comprender el concepto de un plano inclinado, etc.)

Objetivo del prompt:
Refinar y detallar una actividad educativa seleccionada previamente para mejorar la claridad, viabilidad y efectividad en el cumplimiento de los objetivos de aprendizaje.

Formato de respuesta:
Generar una descripción detallada de la actividad seleccionada, incluyendo todos los aspectos necesarios para su implementación exitosa.

Quiero que me preguntes por cada una de estas preguntas, una por una, y una vez tengas toda la información me des la respuesta final:

1. Descripción de la actividad:

¿Cuál es la actividad seleccionada?
¿Cómo se desarrolla la actividad paso a paso?
2. Recursos necesarios:

¿Qué materiales y recursos se necesitan para la actividad?
¿Es necesario algún equipo o software específico?
3. Duración de la actividad:

¿Cuánto tiempo se requiere para completar la actividad?
¿La actividad se realizará en una sola sesión, en varias o fuera de clase?
4. Instrucciones para los estudiantes:

¿Cuáles son las instrucciones detalladas para los estudiantes?
¿Qué información previa deben conocer los estudiantes antes de comenzar?
5. Evaluación:

¿Cómo se evaluará el desempeño de los estudiantes en esta actividad?
¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.?
6. Participación y roles:

¿Cómo se estructurará la participación de los estudiantes? (individual, parejas, grupos)
¿Qué roles específicos tendrán los estudiantes, si los hay?
7. Resultados esperados:

¿Cuáles son los resultados y productos esperados de la actividad?
¿Cómo se alinean estos resultados con los objetivos de aprendizaje?
8. Adaptaciones y consideraciones especiales:

¿Existen adaptaciones para estudiantes con necesidades especiales?
¿Qué consideraciones adicionales deben tenerse en cuenta para asegurar la inclusión y la equidad?
Formato de respuesta:
Una vez que se respondan todas las preguntas, generar un documento que integre toda la información en un formato claro y estructurado, proporcionando una visión completa y detallada de la actividad refinada.

```
### **Detalle de los parámetros**

#### **1. Nivel Educativo de los Estudiantes:**

Indica el nivel educativo de los estudiantes:
"Nivel educativo de los estudiantes: `[NIVEL EDUCATIVO]`..."

- **`[NIVEL EDUCATIVO]`**: Pregrado, Posgrado, educación continua, etc.

#### **2. Materia o Tema Específico:**

Define la materia o tema específico:
"Materia o tema específico: `[MATERIA/TEMA]`..."

- **`[MATERIA/TEMA]`**: Historia, Física, Estructuras de datos, etc.

#### **3. Contexto del Uso del Prompt:**

Explica el contexto del uso del prompt:
"Contexto del uso del prompt: `[CONTEXTO USO]`..."

- **`[CONTEXTO USO]`**: Discusión de clase, bonos, actividad calificada, etc.

#### **4. Objetivos de Aprendizaje:**

Detalla los objetivos de aprendizaje:
"Objetivos de aprendizaje: `[OBJETIVO DE APRENDIZAJE]`..."

- **`[OBJETIVO DE APRENDIZAJE]`**: Los estudiantes deben identificar al menos 3 estructuras de datos, comprender el concepto de un plano inclinado, etc.

#### **5. Descripción de la Actividad:**

Describe la actividad y su desarrollo paso a paso:

1. "¿Cuál es la actividad seleccionada? `[ACTIVIDAD SELECCIONADA]`..."
    - **`[ACTIVIDAD SELECCIONADA]`**: Describe brevemente la actividad.
2. "¿Cómo se desarrolla la actividad paso a paso? `[DESARROLLO PASO A PASO]`..."
    - **`[DESARROLLO PASO A PASO]`**: Detalla los pasos específicos.

#### **6. Recursos Necesarios:**

Lista los materiales y recursos necesarios:

1. "¿Qué materiales y recursos se necesitan para la actividad? `[MATERIALES Y RECURSOS]`..."
    - **`[MATERIALES Y RECURSOS]`**: Enumera los materiales requeridos.
2. "¿Es necesario algún equipo o software específico? `[EQUIPO O SOFTWARE]`..."
    - **`[EQUIPO O SOFTWARE]`**: Indica si se necesita equipo o software específico.

#### **7. Duración de la Actividad:**

Indica el tiempo necesario:

1. "¿Cuánto tiempo se requiere para completar la actividad? `[DURACIÓN]`..."
    - **`[DURACIÓN]`**: Estima el tiempo necesario.
2. "¿La actividad se realizará en una sola sesión, en varias o fuera de clase? `[SESIONES]`..."
    - **`[SESIONES]`**: Especifica si se realizará en una o varias sesiones.

#### **8. Instrucciones para los Estudiantes:**

Proporciona instrucciones detalladas:

1. "¿Cuáles son las instrucciones detalladas para los estudiantes? `[INSTRUCCIONES DETALLADAS]`..."
    - **`[INSTRUCCIONES DETALLADAS]`**: Explica las instrucciones paso a paso.
2. "¿Qué información previa deben conocer los estudiantes antes de comenzar? `[INFORMACIÓN PREVIA]`..."
    - **`[INFORMACIÓN PREVIA]`**: Describe la información previa necesaria.

#### **9. Evaluación:**

Detalla cómo se evaluará:

1. "¿Cómo se evaluará el desempeño de los estudiantes en esta actividad? `[EVALUACIÓN DESEMPEÑO]`..."
    - **`[EVALUACIÓN DESEMPEÑO]`**: Explica el método de evaluación.
2. "¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.? `[MÉTODOS DE EVALUACIÓN]`..."
    - **`[MÉTODOS DE EVALUACIÓN]`**: Indica los tipos de evaluación.

#### **10. Participación y Roles:**

Explica la participación y roles:

1. "¿Cómo se estructurará la participación de los estudiantes? `[PARTICIPACIÓN ESTRUCTURA]`..."
    - **`[PARTICIPACIÓN ESTRUCTURA]`**: Describe la estructura de participación.
2. "¿Qué roles específicos tendrán los estudiantes, si los hay? `[ROLES ESTUDIANTES]`..."
    - **`[ROLES ESTUDIANTES]`**: Indica los roles específicos.

#### **11. Resultados Esperados:**

Define los resultados esperados:

1. "¿Cuáles son los resultados y productos esperados de la actividad? `[RESULTADOS Y PRODUCTOS]`..."
    - **`[RESULTADOS Y PRODUCTOS]`**: Describe los resultados esperados.
2. "¿Cómo se alinean estos resultados con los objetivos de aprendizaje? `[ALINEACIÓN CON OBJETIVOS]`..."
    - **`[ALINEACIÓN CON OBJETIVOS]`**: Explica la alineación con los objetivos.

#### **12. Adaptaciones y Consideraciones Especiales:**

Detalla adaptaciones y consideraciones especiales:

1. "¿Existen adaptaciones para estudiantes con necesidades especiales? `[ADAPTACIONES]`..."
    - **`[ADAPTACIONES]`**: Menciona las adaptaciones necesarias.
2. "¿Qué consideraciones adicionales deben tenerse en cuenta para asegurar la inclusión y la equidad? `[CONSIDERACIONES ADICIONALES]`..."
    - **`[CONSIDERACIONES ADICIONALES]`**: Describe las consideraciones adicionales.

#### **13. Formato de Respuesta:**

Explica cómo se debe presentar la información:
"Una vez que se respondan todas las preguntas, generar un documento que integre toda la información en un formato claro y estructurado, proporcionando una visión completa y detallada de la actividad refinada."

### **Ejemplo del Prompt**


**Nivel educativo de los estudiantes:** Pregrado

**Materia o tema específico:** Historia Mundial: Segunda Guerra Mundial

**Contexto del uso del prompt:** Actividad calificada

**Objetivos de aprendizaje:** Los estudiantes podrán aplicar su comprensión de las diferencias socioeconómicas para empatizar y diseñar soluciones adaptadas a diversos contextos históricos.

**Objetivo del prompt:** Refinar y detallar una actividad educativa seleccionada previamente para mejorar la claridad, viabilidad y efectividad en el cumplimiento de los objetivos de aprendizaje.

**Formato de respuesta:**

1. **Descripción de la actividad:**
   - **¿Cuál es la actividad seleccionada?** Los estudiantes escribirán una serie de cartas entre un soldado en el frente y su familia en casa, reflejando diferentes contextos socioeconómicos durante la Segunda Guerra Mundial. Se organizarán en grupos de 3 y cada estudiante representará una clase socioeconómica diferente (alta, media, baja).
   - **¿Cómo se desarrolla la actividad paso a paso?** Los estudiantes deberán redactar 3 cartas en total: una desde la perspectiva del soldado y dos desde la perspectiva de su familia en casa, reflejando las condiciones económicas y sociales respectivas. Las cartas se escribirán durante la clase para resolver dudas y se entregarán una semana después.

2. **Recursos necesarios:**
   - **¿Qué materiales y recursos se necesitan para la actividad?** Papel, bolígrafos o acceso a computadoras para redactar las cartas.
   - **¿Es necesario algún equipo o software específico?** Se puede utilizar un editor de texto si se decide escribir las cartas en computadora.

3. **Duración de la actividad:**
   - **¿Cuánto tiempo se requiere para completar la actividad?** La actividad se desarrollará durante una semana, comenzando en clase para iniciar la redacción y resolver dudas.
   - **¿La actividad se realizará en una sola sesión, en varias o fuera de clase?** Comienza en clase y se completa fuera de ella, con una semana de plazo para la entrega final.

4. **Instrucciones para los estudiantes:**
   - **¿Cuáles son las instrucciones detalladas para los estudiantes?** Organizarse en grupos de 3 estudiantes. Cada estudiante selecciona representar una clase socioeconómica (alta, media, baja) y debe redactar las cartas correspondientes desde esa perspectiva.
   - **¿Qué información previa deben conocer los estudiantes antes de comenzar?** Deben tener conocimientos sobre las condiciones socioeconómicas durante la Segunda Guerra Mundial y cómo estas afectaron a diferentes grupos sociales.

5. **Evaluación:**
   - **¿Cómo se evaluará el desempeño de los estudiantes en esta actividad?** Se utilizará una rúbrica que evalúe el uso correcto de conceptos históricos, la coherencia con los contextos socioeconómicos y la calidad de la redacción.
   - **¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.?** Sí, se utilizará una rúbrica específica para evaluar las cartas escritas.

6. **Participación y roles:**
   - **¿Cómo se estructurará la participación de los estudiantes?** En grupos de 3 estudiantes, cada uno con un rol específico representando una clase socioeconómica.
   - **¿Qué roles específicos tendrán los estudiantes, si los hay?** Uno representando a un soldado y los otros dos representando diferentes miembros de la familia (padre, madre, hermano/a, etc.).

7. **Resultados esperados:**
   - **¿Cuáles son los resultados y productos esperados de la actividad?** Se espera la entrega de 3 cartas completas que reflejen adecuadamente las diferencias socioeconómicas y su impacto durante la Segunda Guerra Mundial.
   - **¿Cómo se alinean estos resultados con los objetivos de aprendizaje?** Los resultados deben demostrar la capacidad de los estudiantes para aplicar sus conocimientos sobre diferencias socioeconómicas en un contexto histórico específico.

8. **Adaptaciones y consideraciones especiales:**
   - **¿Existen adaptaciones para estudiantes con necesidades especiales?** No se especifican adaptaciones particulares en este caso.
   - **¿Qué consideraciones adicionales deben tenerse en cuenta para asegurar la inclusión y la equidad?** Asegurarse de que los grupos sean equitativos y que todos los estudiantes tengan acceso a los recursos necesarios para completar la actividad.

### **Resultados del prompt** 

#### **Descripción de la actividad:**

**¿Cuál es la actividad seleccionada?**
Los estudiantes escribirán una serie de cartas entre un soldado en el frente y su familia en casa, reflejando diferentes contextos socioeconómicos durante la Segunda Guerra Mundial. Se organizarán en grupos de 3 y cada estudiante representará una clase socioeconómica diferente (alta, media, baja).

**¿Cómo se desarrolla la actividad paso a paso?**
1. **Formación de grupos:** Los estudiantes se organizan en grupos de 3.
2. **Asignación de roles:** Cada estudiante selecciona una clase socioeconómica para representar: alta, media o baja.
3. **Investigación preliminar:** Los estudiantes investigan sobre las condiciones socioeconómicas de las clases asignadas durante la Segunda Guerra Mundial.
4. **Redacción inicial:** En clase, cada estudiante escribe una carta inicial desde la perspectiva del soldado en el frente.
5. **Redacción en casa:** Fuera de clase, los estudiantes escriben dos cartas adicionales desde la perspectiva de la familia en casa.
6. **Revisión y corrección:** Durante la semana, los estudiantes revisan y corrigen sus cartas con la ayuda de sus compañeros y el profesor.
7. **Entrega final:** Las cartas se entregan al final de la semana para su evaluación.

#### **Recursos necesarios:**

**¿Qué materiales y recursos se necesitan para la actividad?**
- Papel y bolígrafos o acceso a computadoras.
- Material de referencia sobre la Segunda Guerra Mundial y las condiciones socioeconómicas de la época.

**¿Es necesario algún equipo o software específico?**
- Un editor de texto si se decide escribir las cartas en computadora.

#### **Duración de la actividad:**

**¿Cuánto tiempo se requiere para completar la actividad?**
- La actividad se desarrollará durante una semana.

**¿La actividad se realizará en una sola sesión, en varias o fuera de clase?**
- Comienza en clase y se completa fuera de ella, con una semana de plazo para la entrega final.

#### **Instrucciones para los estudiantes:**

**¿Cuáles son las instrucciones detalladas para los estudiantes?**
1. **Organización:** Formar grupos de 3 estudiantes.
2. **Asignación:** Cada estudiante elige representar una clase socioeconómica: alta, media o baja.
3. **Redacción:** Escribir 3 cartas en total, una desde la perspectiva del soldado y dos desde la perspectiva de la familia en casa.
4. **Contexto:** Asegurarse de que las cartas reflejen las condiciones económicas y sociales de la clase socioeconómica seleccionada.
5. **Entrega:** Completar y entregar las cartas una semana después de la sesión inicial en clase.

**¿Qué información previa deben conocer los estudiantes antes de comenzar?**
- Conocimientos sobre las condiciones socioeconómicas durante la Segunda Guerra Mundial y cómo estas afectaron a diferentes grupos sociales.

#### **Evaluación:**

**¿Cómo se evaluará el desempeño de los estudiantes en esta actividad?**
- Se utilizará una rúbrica que evalúe:
  - Uso correcto de conceptos históricos.
  - Coherencia con los contextos socioeconómicos.
  - Calidad de la redacción.

**¿Se utilizarán rúbricas, cuestionarios, presentaciones, etc.?**
- Sí, se utilizará una rúbrica específica para evaluar las cartas escritas.

#### **Participación y roles:**

**¿Cómo se estructurará la participación de los estudiantes?**
- En grupos de 3 estudiantes, cada uno con un rol específico representando una clase socioeconómica.

**¿Qué roles específicos tendrán los estudiantes, si los hay?**
- Uno representando a un soldado y los otros dos representando diferentes miembros de la familia (padre, madre, hermano/a, etc.).

#### **Resultados esperados:**

**¿Cuáles son los resultados y productos esperados de la actividad?**
- La entrega de 3 cartas completas que reflejen adecuadamente las diferencias socioeconómicas y su impacto durante la Segunda Guerra Mundial.

**¿Cómo se alinean estos resultados con los objetivos de aprendizaje?**
- Los resultados deben demostrar la capacidad de los estudiantes para aplicar sus conocimientos sobre diferencias socioeconómicas en un contexto histórico específico.

#### **Adaptaciones y consideraciones especiales:**

**¿Existen adaptaciones para estudiantes con necesidades especiales?**
- No se especifican adaptaciones particulares en este caso.

**¿Qué consideraciones adicionales deben tenerse en cuenta para asegurar la inclusión y la equidad?**
- Asegurarse de que los grupos sean equitativos y que todos los estudiantes tengan acceso a los recursos necesarios para completar la actividad.

[Creación de enunciado con base en una actividad y una rúbrica](https://www.notion.so/Creaci-n-de-enunciado-con-base-en-una-actividad-y-una-r-brica-af0acd1dfd334e9ebae21495c485eceb?pvs=21)

## **Retroalimentación de una actividad con base en una rúbrica**

### **Descripción**

Proporciona retroalimentación constructiva a los estudiantes basada en los criterios y escalas de la rúbrica, ayudándoles a entender sus fortalezas y áreas de mejora.

### **Prerrequisitos**

- Haber recibido la actividad realizada por los estudiantes

### **Descripción del prompt**

Este prompt ayuda al docente a generar una retroalimentación completa sobre la entrega de una actividad específica, donde se entrega al prompt la actividad realizada, el enunciado y la rúbrica, para que el docente pueda complementar la calificación y retroalimentación de la actividad del estudiante.

### **Prompt** 

```console
Hola, soy un profesor de [materia], y quiero que me ayudes a crear una retroalimentación de [Tipo trabajo] que desarrolló un estudiante. 
Donde quiero analizar los siguientes puntos [puntos a evaluar/analizar], además, quiero que la retroalimentación tenga un nivel de detalle [general/especifico/puntual]. 
Por último, quiero que desarrolles un comentario constructivo acerca del trabajo desarrollado por el estudiante, mencionando puntualmente qué partes cumplen con lo que se quiere evaluar.
En que aspectos se puede mejorar, y qué se debe corregir. Quiero que la retroalimentación se visualize en [formato].
```

### **Detalle de los parámetros**

#### **1. Introducción:**

Comienza el prompt con una breve presentación:
"Hola, soy un profesor de `[materia]`..."

- **`[materia]`**: Sustituye esta sección con la materia que enseñas, por ejemplo, Matemáticas, Historia, Programación, etc. Sé detallado e incluye, de ser posible, el tema en específico que estás tratando en tu materia.

#### **2. Tipo de Trabajo:**

Indica el tipo de trabajo que necesitas retroalimentar:
"...quiero que me ayudes a crear una retroalimentación de `[Tipo trabajo (texto, código, etc)]`..."

- **`[Tipo trabajo]`**: Especifica el tipo de trabajo del estudiante. Ejemplos: ensayo, proyecto de código, presentación, etc.

#### **3. Puntos a Evaluar:**

Detalla los aspectos que deseas analizar:
"...donde quiero analizar los siguientes puntos `[puntos a evaluar/analizar]`..."

- **`[puntos a evaluar/analizar]`**: Lista los aspectos específicos que quieres que se aborden. Ejemplos: claridad, precisión, creatividad, cumplimiento de los requisitos, etc.

#### **4. Nivel de Detalle:**

Define el nivel de detalle deseado en la retroalimentación:
"...quiero que la retroalimentación tenga un nivel de detalle [general/específico/puntual]..."

- **`[general/específico/puntual]`**: Selecciona el nivel de profundidad que deseas. General para una visión amplia, específico para detalles precisos, o puntual para comentarios muy detallados sobre partes concretas.

#### **5. Comentario Constructivo:**

Solicita un comentario constructivo que aborde las fortalezas y áreas de mejora:
"...quiero que desarrolles un comentario constructivo acerca del trabajo desarrollado por el estudiante, mencionando puntualmente qué partes cumplen con lo que se quiere evaluar, en qué aspectos se puede mejorar, y qué se debe corregir."

#### **6. Formato de Visualización:**

Elige cómo deseas que se presente la retroalimentación:
"...Quiero que la retroalimentación se visualice `[Usando Bullet Points (Viñetas) / En forma de Tabla / Desarrollado en párrafos / Otro, especifique en qué formato]`..."

- **`[Usando Bullet Points (Viñetas) / En forma de Tabla / Desarrollado en párrafos / Otro]`**: Selecciona el formato que prefieres para la retroalimentación. Si eliges "Otro", especifica claramente el formato deseado.

### **Ejemplo del Prompt:**

A continuación se presenta un ejemplo concreto del prompt para retroalimentación de actividades:

***"Hola, soy un profesor de Historia, y quiero que me ayudes a crear una retroalimentación de un ensayo que desarrolló un estudiante. Donde quiero analizar los siguientes puntos: claridad en la argumentación, uso de fuentes, y originalidad. Además, quiero que la retroalimentación tenga un nivel de detalle específico. Por último, quiero que desarrolles un comentario constructivo acerca del trabajo desarrollado por el estudiante, mencionando puntualmente qué partes cumplen con lo que se quiere evaluar, en qué aspectos se puede mejorar, y qué se debe corregir. Quiero que la retroalimentación se visualice usando Bullet Points."***

### *Cartas desde el Frente: Voces de la Segunda Guerra Mundial*

#### **Carta del Soldado (Clase Baja)**

**Fecha: 15 de junio de 1943**

Querida Familia,

Espero que esta carta los encuentre bien. Los días aquí en el frente son largos y duros. La vida en las trincheras es algo que nunca imaginé. Nos falta de todo, especialmente comida y abrigo. A menudo, me encuentro soñando con un simple plato de comida caliente.

He hecho algunos amigos aquí, pero todos compartimos la misma desesperación y el anhelo de volver a casa. Las cartas que recibo de ustedes son lo único que me da fuerza. Espero que puedan mantener la granja funcionando y que todos estén bien.

Los extraño mucho y pienso en ustedes todos los días. Prometo que haré todo lo posible para regresar sano y salvo. Cuídense mucho.

Con cariño,
José

---

#### **Carta del Padre (Clase Baja)**

**Fecha: 22 de junio de 1943**

Querido José,

Recibimos tu carta y nos alegró saber de ti. Aquí en casa las cosas siguen difíciles, pero nos mantenemos fuertes. La cosecha no ha sido buena este año y estamos luchando para tener suficiente para comer. A veces, vendemos lo poco que tenemos en el mercado para comprar otras cosas necesarias.

Tu madre y tus hermanos te extrañan mucho. Intentamos mantener el ánimo, pero no es fácil. Cada día rezo para que regreses sano y salvo. Recuerda que eres nuestro orgullo y te queremos mucho.

Sigue siendo fuerte y cuídate.

Con amor,
Papá

---

#### **Carta del Hermano (Clase Baja)**

**Fecha: 22 de junio de 1943**

Hola, José,

Soy Juan. Papá me dejó escribirte una parte de la carta. Te extraño mucho y espero que estés bien. La escuela es difícil sin ti aquí para ayudarme con las tareas. Mamá siempre habla de ti y llora a veces por la noche.

Hemos tenido que trabajar mucho en la granja. Los días son largos y a veces no tenemos suficiente comida, pero seguimos adelante. Quiero que sepas que estoy cuidando de todos lo mejor que puedo.

Espero que regreses pronto. Te extraño mucho.

Con cariño,
Juan

---

#### **Carta del Soldado (Clase Media)**

**Fecha: 15 de junio de 1943**

Querida Familia,

Les escribo desde algún lugar de Francia. La vida en el frente es dura, pero nos las arreglamos. Las condiciones no son las mejores, pero tenemos suficiente para mantenernos. A veces, el frío y la lluvia hacen que todo sea más difícil, pero seguimos adelante.

Pienso mucho en ustedes y en nuestra casa. Me pregunto cómo estarán las cosas en el barrio. Espero que sigan bien y que puedan manejar todo sin mí. Sus cartas son mi único consuelo en estos tiempos difíciles.

Los extraño mucho. Espero poder regresar pronto.

Con amor,
Carlos

---

#### **Carta de la Madre (Clase Media)**

**Fecha: 22 de junio de 1943**

Querido Carlos,

Nos alegró mucho recibir tu carta. Estamos bien aquí en casa, aunque te extrañamos muchísimo. La vida sigue su curso, aunque con algunas dificultades. Tu padre ha tenido que trabajar más horas en la fábrica para compensar tu ausencia, pero nos las arreglamos.

Tu hermana acaba de terminar el colegio con muy buenas notas. Está pensando en seguir estudiando, pero la situación económica lo hace difícil. Mantenemos la esperanza de que la guerra termine pronto y puedas volver con nosotros.

Cuídate mucho y no dejes de escribir.

Con todo mi cariño,
Mamá

---

#### **Carta de la Hermana (Clase Media)**

**Fecha: 22 de junio de 1943**

Hola, Carlos,

Espero que estés bien. Mamá y papá recibieron tu carta y estamos muy contentos de saber de ti. La vida aquí sigue, pero no es lo mismo sin ti. Estoy terminando el colegio y considerando mis opciones para el futuro. Extraño nuestros paseos y charlas.

Papá trabaja mucho y mamá hace todo lo posible para mantenernos unidos y optimistas. A veces, la preocupación por ti es abrumadora, pero intentamos mantenernos fuertes por ti.

Te extraño y espero verte pronto.

Con amor,
María

---

#### **Carta del Soldado (Clase Alta)**

**Fecha: 15 de junio de 1943**

Querida Familia,

Les escribo desde el frente, donde las cosas son difíciles, pero estoy bien. Las condiciones son duras, pero recibimos buenos suministros y el equipo es de calidad. A pesar de todo, la guerra es un monstruo que nunca imaginé enfrentar.

Pienso en ustedes constantemente y en nuestra casa. Espero que estén manejando bien la situación y que no falte nada. Sus cartas son un bálsamo para mi espíritu y me mantienen enfocado.

Espero poder regresar pronto y retomar nuestras vidas. Los extraño mucho.

Con cariño,
Alejandro

---

#### **Carta del Padre (Clase Alta)**

**Fecha: 22 de junio de 1943**

Querido Alejandro,

Nos alegró mucho recibir tu carta. Aquí en casa estamos bien, aunque nos preocupamos por ti todo el tiempo. La empresa sigue funcionando bien, y hemos contratado a más personas para cubrir tus responsabilidades. Tu madre y tus hermanas están bien, aunque te extrañan mucho.

La situación en la ciudad es estable, aunque hay algunas restricciones debido a la guerra. Mantenemos la esperanza de que todo termine pronto y puedas volver a casa sano y salvo.

Cuídate mucho y mantente fuerte.

Con afecto,
Papá

---

#### **Carta de la Madre (Clase Alta)**

**Fecha: 22 de junio de 1943**

Querido Alejandro,

Nos llenó de alegría recibir tu carta. Todos aquí estamos bien, aunque la preocupación por ti es constante. Hacemos lo posible por mantenernos ocupados y optimistas. Tus hermanas están estudiando en casa y yo paso mucho tiempo en obras de caridad para apoyar a las familias necesitadas.

La casa se siente vacía sin ti, pero sabemos que estás haciendo lo correcto. Rezamos todos los días por tu seguridad y por tu pronto regreso.

Con todo mi amor,
Mamá

### **Resultados de la Retroalimentacion**

La idea es que te apoyes como profesor en la retroalimentacion de las actividades, tal que sea una herramienta para profundizar y dar una mejor retroalimentacion a los estudiantes.

### **Retroalimentación de la Actividad: Cartas desde el Frente**

#### Descripción de la Actividad:

**Evaluación General:**
La actividad de escribir cartas desde la perspectiva de diferentes contextos socioeconómicos durante la Segunda Guerra Mundial fue ejecutada de manera efectiva. Los estudiantes demostraron una comprensión sólida de las diferencias socioeconómicas y cómo estas afectaron a las personas durante el conflicto.

#### **Evaluación Detallada:**

**Uso Correcto de Conceptos Históricos:**
- **Cartas del Soldado (Clase Baja, Media, Alta):** Las cartas reflejan adecuadamente las condiciones de vida en el frente, incluyendo la escasez de suministros y las duras condiciones climáticas. Los detalles sobre la vida en las trincheras y el impacto emocional de la guerra están bien logrados.
- **Cartas de la Familia (Clase Baja, Media, Alta):** Las cartas muestran una comprensión clara de las condiciones socioeconómicas en el hogar, incluyendo dificultades económicas, trabajos adicionales y preocupaciones diarias. Se mencionan aspectos relevantes como la agricultura en la clase baja, la educación en la clase media, y la estabilidad económica en la clase alta.

**Coherencia con los Contextos Socioeconómicos:**
- **Clase Baja:** Las cartas reflejan con precisión las dificultades económicas extremas y la lucha por la supervivencia diaria. Se destacan los esfuerzos adicionales para mantener la granja y las carencias en la alimentación.
- **Clase Media:** Las cartas muestran una situación económica estable pero con desafíos, como la necesidad de trabajar más horas y la preocupación por el futuro educativo de los hijos.
- **Clase Alta:** Las cartas demuestran una mayor estabilidad económica, con menciones a la continuidad de la empresa familiar y las actividades caritativas, reflejando un contexto de privilegio y responsabilidad social.

**Calidad de la Redacción:**
- **Claridad y Coherencia:** Todas las cartas están bien estructuradas, con una narrativa clara y coherente. Los estudiantes lograron transmitir emociones y situaciones de manera efectiva.
- **Detalles y Precisión:** Los detalles específicos sobre la vida en el frente y en el hogar enriquecen las cartas, mostrando una investigación adecuada y una buena comprensión del contexto histórico.

#### **Participación y Roles:**

**Trabajo en Grupo:**
- Los estudiantes trabajaron bien en grupos, asignando roles específicos y colaborando para reflejar diferentes perspectivas socioeconómicas.
- La distribución de tareas y la integración de diferentes puntos de vista en las cartas fueron efectivas.

**Roles Específicos:**
- Cada estudiante representó adecuadamente su rol, ya sea como soldado o como miembro de la familia, con una atención cuidadosa a las diferencias de clase.

#### **Resultados y Productos Esperados:**

**Resultados Obtenidos:**
- Las cartas entregadas cumplen con los objetivos de aprendizaje al demostrar la capacidad de aplicar conocimientos sobre diferencias socioeconómicas en un contexto histórico específico.
- Los productos finales son cartas bien escritas que reflejan adecuadamente las experiencias de diferentes clases socioeconómicas durante la Segunda Guerra Mundial.

**Alineación con los Objetivos de Aprendizaje:**
- Los estudiantes lograron empatizar con las diferentes realidades socioeconómicas y diseñar narrativas que muestran una comprensión profunda de cómo estas diferencias afectaron a las personas durante la guerra.

#### **Adaptaciones y Consideraciones Especiales:**

**Inclusión y Equidad:**
- Asegurarse de que todos los estudiantes tuvieran acceso a los recursos necesarios fue fundamental para el éxito de la actividad.
- La equidad en la formación de grupos y la distribución de roles contribuyó a una experiencia de aprendizaje inclusiva.

#### **Recomendaciones para Futuras Actividades:**

1. **Ampliar la Investigación:** Incluir más recursos multimedia (videos, documentales) para enriquecer la comprensión del contexto histórico.
2. **Interacción entre Grupos:** Fomentar más la interacción entre grupos para que compartan sus perspectivas y aprendizajes, promoviendo una mayor colaboración y discusión.
3. **Rúbrica de Evaluación:** Asegurar que todos los estudiantes comprendan claramente la rúbrica de evaluación desde el inicio para orientar mejor su trabajo.

#### **Conclusión:**

La actividad fue exitosa en lograr sus objetivos de aprendizaje, con los estudiantes demostrando una comprensión sólida de las diferencias socioeconómicas y cómo estas impactaron a las personas durante la Segunda Guerra Mundial. Las cartas entregadas fueron bien escritas, coherentes y reflejan un esfuerzo significativo por parte de los estudiantes.

Usa este formato para obtener retroalimentaciones claras y detalladas que puedan ayudar a tus estudiantes a mejorar y alcanzar sus objetivos académicos.