# Guía para la accesibilización de documentos educativos

## 1. Introducción

La accesibilización de documentos educativos busca reducir las barreras que pueden dificultar el acceso, la navegación, la lectura y la comprensión de sus contenidos.

Un documento accesible debe permitir que la información pueda ser utilizada por diferentes personas, incluyendo aquellas que utilizan tecnologías de apoyo como lectores de pantalla.

Esta guía presenta recomendaciones generales para la accesibilización de documentos educativos y puede aplicarse tanto a documentos creados digitalmente como a materiales que fueron digitalizados a partir de documentos impresos.

La guía está pensada como un documento en evolución. En futuras versiones se podrán incorporar recomendaciones específicas para libros digitalizados, OCR, documentos con fórmulas matemáticas, gráficos, tablas complejas, notas al pie, referencias y otros elementos habituales en materiales educativos extensos.

## 2. Identificar el documento a trabajar

Antes de comenzar la accesibilización es importante identificar qué tipo de documento se va a trabajar, ya que el proceso puede variar según su origen y características.

### Documento creado digitalmente

Es un documento cuyo contenido fue producido originalmente mediante una herramienta digital como un procesador de textos, un editor de presentaciones o un programa de maquetación.

En estos casos se puede trabajar directamente sobre su estructura, contenido y elementos visuales.

### Documento digitalizado

Es un documento que originalmente estaba en formato impreso y fue convertido a un archivo digital mediante un escáner, una cámara u otro medio de digitalización.

Un caso habitual es un libro escaneado en el que cada página del PDF está formada por una imagen.

En estos casos es necesario comprobar si el contenido puede ser seleccionado, buscado y leído por tecnologías de apoyo.

### Documento digitalizado con OCR

El reconocimiento óptico de caracteres u OCR permite convertir el texto presente en una imagen en texto digital.

El OCR puede ser un paso necesario para trabajar con libros escaneados y otros documentos digitalizados, pero su aplicación no garantiza por sí misma la accesibilidad del documento.

Después de realizar el OCR es necesario revisar el contenido y reconstruir su estructura cuando sea necesario.

Se deben prestar especial atención a posibles errores en:

- Palabras y caracteres
- Números
- Signos de puntuación
- Títulos y subtítulos
- Columnas
- Tablas
- Fórmulas
- Notas al pie
- Referencias
- Saltos de página

## 3. Principios de accesibilidad

Los principios de accesibilidad de las WCAG (Web Content Accessibility Guidelines) pueden utilizarse como marco general para orientar la accesibilización de los documentos.

### Perceptible

La información debe poder ser percibida por las personas de diferentes maneras.

En un documento esto implica, entre otras cuestiones, prestar atención al texto, las imágenes, el contraste y las alternativas para los contenidos visuales.

### Operable

El contenido debe poder utilizarse mediante diferentes formas de interacción.

En documentos digitales esto incluye, por ejemplo, que la navegación y los elementos interactivos puedan utilizarse mediante tecnologías de apoyo y diferentes dispositivos de entrada.

### Comprensible

El contenido y su organización deben facilitar la comprensión y la navegación.

La estructura, los títulos, el lenguaje, los enlaces y la presentación de la información deben ayudar a las personas a encontrar y comprender el contenido.

### Robusto

El contenido debe poder ser interpretado correctamente por diferentes programas y tecnologías de apoyo.

La estructura del documento debe proporcionar información que pueda ser reconocida por las herramientas utilizadas para acceder al contenido.

Estos principios sirven como marco para las recomendaciones de esta guía. No es necesario clasificar cada recomendación según un principio, ya que una misma práctica puede contribuir a más de uno.

## 4. Estructura del documento

Los documentos deben tener una organización jerárquica y lógica.

La estructura no debe depender únicamente de la apariencia visual. Los títulos, subtítulos, párrafos y listas deben estar identificados mediante las herramientas de estructura disponibles en el programa utilizado.

### Títulos y subtítulos

Utilizar una jerarquía coherente de títulos y subtítulos.

Por ejemplo:

- Title: identifica el documento completo
- Heading 1: identifica las secciones principales del contenido
- Heading 2: subsecciones de un Heading 1
- Heading 3: subsecciones de un Heading 2

El **título del documento** identifica el documento en su conjunto, mientras que los **Heading** organizan su contenido en diferentes niveles. 

No se debe utilizar únicamente el tamaño de la letra, la negrita o las mayúsculas para indicar que un texto es un título.

Una estructura correcta permite que las personas puedan comprender la organización del documento y facilita la navegación mediante lectores de pantalla.

### Orden de lectura

El contenido debe seguir un orden lógico.

En términos generales, la información debe poder recorrerse de principio a fin sin que imágenes, columnas, cuadros u otros elementos alteren inesperadamente la secuencia.

### Índice

En documentos extensos, como libros y materiales académicos, es recomendable incorporar un índice que permita localizar las diferentes partes del contenido.

Cuando el formato lo permita, el índice debería permitir navegar directamente hacia las secciones correspondientes.

### Páginas

Los documentos extensos deben mantener una numeración coherente de las páginas.

También se debe comprobar que los saltos de página no interrumpan innecesariamente la comprensión del contenido.

## 5. Texto y legibilidad

El contenido textual debe presentarse de manera que facilite la lectura y comprensión.

Se recomienda:

- Utilizar una tipografía de buena legibilidad
- Utilizar un tamaño de texto adecuado
- Mantener un interlineado que facilite la lectura
- Utilizar una alineación que favorezca la lectura
- Separar visualmente los diferentes bloques de contenido
- Evitar bloques de texto innecesariamente extensos
- Mantener un contraste suficiente entre texto y fondo
- No utilizar únicamente el color para transmitir información
- Explicar las abreviaturas y acrónimos cuando aparecen por primera vez
- Utilizar un lenguaje claro y adecuado al público destinatario

Las recomendaciones relacionadas con tipografía, tamaño, interlineado y presentación deben considerarse especialmente al crear o editar el documento. En materiales existentes, como libros digitalizados, puede ser necesario priorizar primero la recuperación del contenido y su estructura.

## 6. Imágenes y otros elementos visuales

Las imágenes pueden transmitir información importante para comprender un documento educativo.

Es necesario determinar qué función cumple cada imagen.

### Imágenes informativas

Cuando una imagen aporta información necesaria para comprender el contenido, debe contar con una descripción textual adecuada.

La descripción debe comunicar la información relevante de la imagen y su relación con el contenido.

No es necesario comenzar la descripción con expresiones como "foto de" o "imagen de", salvo que ese dato sea relevante.

### Imágenes decorativas

Cuando una imagen tiene únicamente una función decorativa y no aporta información necesaria para comprender el contenido, debe identificarse como decorativa para evitar que una tecnología de apoyo intente transmitir información que no es necesaria.

### Gráficos y diagramas

Los gráficos y diagramas requieren especial atención porque la información puede estar representada principalmente de forma visual.

Cuando un gráfico o diagrama transmite información necesaria para comprender el contenido, se debe acompañar con un texto explicativo y descriptivo que comunique sus datos, relaciones o conclusiones principales.

La descripción debe ser suficiente para comprender la información relevante sin necesidad de acceder visualmente al gráfico.

## 7. Tablas

Las tablas deben utilizarse cuando realmente aportan valor para organizar información.

Se recomienda:

- Mantener una estructura sencilla
- Identificar los encabezados de filas o columnas cuando corresponda
- Mantener una relación clara entre encabezados y datos
- Evitar tablas excesivamente complejas
- Repetir los encabezados cuando una tabla ocupa varias páginas, cuando la herramienta utilizada lo permita

En documentos extensos es importante comprobar que la estructura de la tabla pueda ser interpretada correctamente por las tecnologías de apoyo.

## 8. Listas

Cuando una serie de elementos constituye una lista, se deben utilizar las herramientas de lista disponibles en el editor.

Utilizar:

- Listas con viñetas para elementos sin un orden determinado
- Listas numeradas cuando existe una secuencia o un orden

No se recomienda simular listas utilizando únicamente caracteres como guiones, asteriscos o números escritos manualmente cuando el editor permite crear una lista estructurada.

## 9. Enlaces

El texto utilizado para un enlace debe permitir comprender su propósito.

Se deben evitar expresiones genéricas como:

- "Clic aquí"
- "Más información"
- "Ver más"

Es preferible utilizar un texto que describa el destino del enlace.

Por ejemplo:

> Descargar la guía de accesibilidad de documentos

en lugar de:

> Para descargar la guía haga clic aquí

## 10. Verificación

La accesibilización debe finalizar con una instancia de verificación.

Algunas comprobaciones básicas son:

- El texto puede seleccionarse cuando corresponde
- El documento puede recorrerse siguiendo un orden lógico
- Los títulos tienen una estructura jerárquica
- El índice permite localizar las secciones
- Las imágenes informativas tienen una alternativa textual adecuada
- Las imágenes decorativas están identificadas como tales
- Las tablas tienen encabezados correctamente definidos
- Las listas utilizan una estructura adecuada
- Los enlaces tienen textos significativos
- La información no depende únicamente del color
- Existe un contraste suficiente
- El contenido puede ser interpretado mediante tecnologías de apoyo

Las herramientas automáticas pueden ayudar a detectar determinados problemas, pero no sustituyen la revisión del contenido, la estructura y la experiencia de uso.

Por este motivo, la verificación debería combinar herramientas automáticas con comprobaciones manuales.

## Bibliografía

- Universidad Nacional de Córdoba. *Cómo crear contenido accesible en Word y luego convertir el archivo a formato PDF*
- Curso de accesibilización de documentos 2025
- Programa de Capacitación “Discapacidad y Accesibilidad Académica” 2026. *Discapacidad y accesibilidad académica. Módulo 3*
- World Wide Web Consortium (W3C). *Web Content Accessibility Guidelines (WCAG)*