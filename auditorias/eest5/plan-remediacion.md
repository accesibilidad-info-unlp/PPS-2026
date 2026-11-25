# Plan de remediación de accesibilidad

## 1. Datos generales

- **Sitio evaluado:**  Escuela de Educación Secundaria Técnica N.º 5.
- **URL del sitio:** [EEST5](https://eest5-laplata.blogspot.com/) 
- **Evaluadores:**  Santiago Fleitas,Yeny Gamarra,Liz Medina 
- **Fecha de elaboración:** 24/11/2026
- **Informe de auditoría:** [Informe de auditoría](informe-auditoria.md)

## 2. Proceso de planificación

Para elaborar el presente plan de remediación se analizaron los hallazgos obtenidos durante la auditoría de accesibilidad del sitio web de la Escuela de Educación Secundaria Técnica N.º 5.

Se utilizaron los resultados de las herramientas Lighthouse y WAVE, junto con la información recopilada durante la evaluación manual.

El proceso de planificación contempló las siguientes actividades:

Revisión de los hallazgos: se identificaron tres problemas principales: imágenes sin texto alternativo, errores de contraste y tablas con títulos vacíos utilizadas para organizar elementos de búsqueda.

Análisis del impacto en los usuarios: se evaluó cómo estos problemas pueden dificultar el acceso a la información, especialmente para personas con discapacidad visual que utilizan lectores de pantalla o necesitan un contraste adecuado para leer.

Evaluación de severidad y esfuerzo: se determinó la gravedad de cada problema y el trabajo técnico necesario para solucionarlo.
Asignación de prioridades: se establecieron prioridades según el impacto que los errores generan en la experiencia de navegación.

**Definición de soluciones:** se propusieron modificaciones en el código HTML, los atributos de las imágenes y los estilos CSS.
Selección de problemas: se decidió abordar los tres hallazgos identificados durante esta iteración, comenzando por los que generan mayores barreras de accesibilidad.
El objetivo es mejorar la accesibilidad general del sitio y favorecer que todas las personas puedan navegar, comprender e interactuar con sus contenidos.

## 3. Análisis y priorización de hallazgos

###  Imagen sin alt

- Referencia: [Imagen sin alt](informe-auditoria.md#imagen-sin-alt)
- Impacto en usuarios: Las personas ciegas o con discapacidad visual que utilizan lectores de pantalla no pueden conocer el contenido de las imágenes informativas si estas no poseen una descripción textual. Esto puede provocar pérdida de información importante.
- Severidad: Alta.
- Esfuerzo estimado: Medio.
- Prioridad: Alta.
- Justificación: Se detectaron un total de 12 imágenes sin texto alternativo. Este problema afecta directamente al acceso a la información visual del sitio. Se considera prioritario porque las imágenes pueden contener información relevante para comprender las publicaciones y actividades escolares.

### Errores de contraste

- Referencia: Informe de auditoría, sección 4. Identificación y clasificación de hallazgos.
- Impacto en usuarios: Las personas con baja visión, dificultades visuales o sensibilidad a determinados contrastes pueden tener dificultades para leer los textos del sitio. También puede afectar la lectura en dispositivos con pantallas de baja calidad o en ambientes con mucha iluminación.
- Severidad: Alta.
- Esfuerzo estimado: Medio.
- Prioridad: Alta.
- Justificación: Se detectaron 31 errores de contraste. Uno de los ejemplos presenta una relación de contraste de 4.36:1, inferior al mínimo de 4.5:1 exigido para texto normal por WCAG 2.1, criterio 1.4.3. Debido a que el problema afecta la legibilidad de los contenidos, se considera una prioridad alta.

### Tablas con titulos vacios

- Referencia: Informe de auditoría, sección 4. Código HTML del componente de búsqueda detectado por WAVE.
- Impacto en usuarios: El uso de tablas para organizar elementos de interfaz que no representan datos tabulares puede generar información estructural innecesaria para las tecnologías de asistencia. Además, el campo de búsqueda y los controles asociados necesitan nombres accesibles para que las personas que utilizan lectores de pantalla puedan identificarlos y utilizarlos correctamente.
- Severidad: Media.
- Esfuerzo estimado: Medio.
- Prioridad: Media.
- Justificación: Se identificó una tabla utilizada para distribuir elementos de un buscador y otros controles de Blogger. Aunque visualmente no se presenta como una tabla de datos, su estructura HTML puede ser interpretada como tal por los lectores de pantalla. Se considera importante corregir su estructura semántica y revisar los controles que contiene.
Revisar los problemas identificados en la auditoría y determinar su prioridad de remediación.

### < Nombre del hallazgo >

- **Referencia:** < Enlace al hallazgo en el informe de auditoría o Issue de GitHub >
- **Impacto en usuarios:** <¿Cómo puede afectar el problema a las personas que utilizan el sitio?>
- **Severidad:** < Alta / Media / Baja >
- **Esfuerzo estimado:** < Alto / Medio / Bajo >
- **Prioridad:** < Alta / Media / Baja >
- **Justificación:** <¿Por qué se asignó esta prioridad?>

Repetir esta estructura para cada hallazgo analizado.

## 4. Soluciones propuestas

Registrar las soluciones para los problemas que se decidió abordar.

### Imagen sin alt

Solución propuesta: Incorporar el atributo alt en las 12 imágenes detectadas. Las imágenes informativas deberán contar con una descripción breve y clara que transmita su contenido o función. En el caso de imágenes decorativas, se utilizará un atributo alternativo vacío (alt="") para evitar que los lectores de pantalla anuncien información innecesaria.

### Errores de contraste

Corregir los colores del texto y del fondo para garantizar que exista un contraste suficiente y que los contenidos puedan leerse correctamente.
Se deberán revisar los 31 errores de contraste detectados por las herramientas de evaluación. Para solucionarlos, se modificarán los estilos CSS del sitio, ajustando los colores de las letras y los fondos.Se utilizará como referencia el criterio WCAG 2.1, 1.4.3 (Contraste mínimo), que establece una relación de contraste de al menos 4.5:1 para textos normales y 3:1 para textos grandes.
También se comprobará que los cambios mantengan una apariencia visual coherente con el diseño original del sitio y que los textos sean fáciles de leer para personas con baja visión o dificultades visuales.

### Tablas con titulos vacios
Revisar la estructura HTML del buscador y reemplazar las tablas utilizadas únicamente para organizar elementos visuales por contenedores semánticos adecuados, como div o form, utilizando CSS para controlar su distribución.El objetivo es evitar que los lectores de pantalla interpreten estos elementos como tablas de datos cuando en realidad se utilizan para organizar los controles del buscador.

### < Nombre del hallazgo  >

- **Solución propuesta:** <¿Qué cambios se proponen realizar?>

Repetir esta estructura para cada hallazgo.

## 5. Organización y seguimiento del trabajo

Registrar los recursos utilizados para organizar las tareas de remediación.

- **Repositorio de GitHub:** [Trabajo en proceso EEST5](https://github.com/accesibilidad-info-unlp/PPS-2026/tree/main/auditorias/eest5/trabajo_en_procesos)
- **GitHub Projects:** < Enlace al tablero >

Cada problema seleccionado deberá contar con una Issue que permita registrar y realizar el seguimiento de su resolución.

Las tareas se organizarán mediante un tablero Kanban y se utilizarán etiquetas para identificar su severidad, tipo de problema y criterios WCAG relacionados.

