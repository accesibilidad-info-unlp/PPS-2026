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

### Hallazgo 1: Imágenes sin texto alternativo

- Referencia: [Imagen sin alt](informe-auditoria.md#imagen-sin-alt)
- Impacto en usuarios: Las personas ciegas o con discapacidad visual que utilizan lectores de pantalla no pueden conocer el contenido de las imágenes informativas si estas no poseen una descripción textual. Esto puede provocar pérdida de información importante.
- Severidad: Alta.
- Esfuerzo estimado: Medio.
- Prioridad: Alta.
- Justificación: Se detectaron un total de 12 imágenes sin texto alternativo. Este problema afecta directamente al acceso a la información visual del sitio. Se considera prioritario porque las imágenes pueden contener información relevante para comprender las publicaciones y actividades escolares.

### Hallazgo 2: Errores de contraste entre texto y fondo

- Referencia: Informe de auditoría, sección 4. Identificación y clasificación de hallazgos.
- Impacto en usuarios: Las personas con baja visión, dificultades visuales o sensibilidad a determinados contrastes pueden tener dificultades para leer los textos del sitio. También puede afectar la lectura en dispositivos con pantallas de baja calidad o en ambientes con mucha iluminación.
- Severidad: Alta.
- Esfuerzo estimado: Medio.
- Prioridad: Alta.
- Justificación: Se detectaron 31 errores de contraste. Uno de los ejemplos presenta una relación de contraste de 4.36:1, inferior al mínimo de 4.5:1 exigido para texto normal por WCAG 2.1, criterio 1.4.3. Debido a que el problema afecta la legibilidad de los contenidos, se considera una prioridad alta.

### Hallazgo 3: Tablas con títulos vacíos utilizadas como buscador

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

### Hallazgo 1: Imágenes sin texto alternativo

Solución propuesta: Incorporar el atributo alt en las 12 imágenes detectadas. Las imágenes informativas deberán contar con una descripción breve y clara que transmita su contenido o función. En el caso de imágenes decorativas, se utilizará un atributo alternativo vacío (alt="") para evitar que los lectores de pantalla anuncien información innecesaria.

### < Nombre del hallazgo 1 >

- **Solución propuesta:** <¿Qué cambios se proponen realizar?>

Repetir esta estructura para cada hallazgo.

## 5. Organización y seguimiento del trabajo

Registrar los recursos utilizados para organizar las tareas de remediación.

- **Repositorio de GitHub:** < Enlace >
- **GitHub Projects:** < Enlace al tablero >

Cada problema seleccionado deberá contar con una Issue que permita registrar y realizar el seguimiento de su resolución.

Las tareas se organizarán mediante un tablero Kanban y se utilizarán etiquetas para identificar su severidad, tipo de problema y criterios WCAG relacionados.

## 6. Observaciones finales

Registrar decisiones importantes, problemas que no serán abordados durante esta iteración y otras consideraciones relevantes para la implementación.

Los problemas que queden pendientes deberán conservarse documentados, indicando los motivos y las posibles soluciones para futuras iteraciones.

Los cambios aprobados pasarán a la siguiente etapa: remediación.

