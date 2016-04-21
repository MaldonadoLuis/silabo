# Sílabo para Ambientes No Propietarios ESFOT-EPN 2016A

* **Materia:** ASI_TSI553 Ambientes No Propietarios
* **Lugar:** TECET22
* **Horario:**  Martes de 17:00 a 20:00
* **Profesor:** Edwin Salvador, [edwin.salvador@epn.edu.ec](mailto:edwin.salvador@epn.edu.ec)
* Pueden revisar el sílabo y colaborar mediante la creación de [issues](https://github.com/EPN-ANP-2016A/silabo/issues)
* Para ayuda es mejor enviar un [email](mailto:edwin.salvador@epn.edu.ec) para coordinar una hora de reunión.

## Objetivos del Curso

* Diferenciar los diferentes frameworks que existen dentro de un lenguaje de programación web backend.
* Describir las ventajas que oferece el versionamiento de código.
* Explicar diferentes técnicas de programación web para el desarrollo de aplicaciones web con contenidos dinámicos.
* Utilizar herramientas no propietarias para desarrollo de soluciones web.
* Seleccionar librerias adecuadas dependendiendo de los requerimientos de la aplicación.
* Configurar servidores web.
* Utilizar tecnologias actuales para el desarrollo web.
* Configurar un repositorio para versionamiento de código.
* Demostrar solidez en principios de respeto a las normas y estándares internacionales.
* Demostrar creatividad e innovación.
* Integrar grupos de trabajo para el desarrollo de aplicaciones 

## Prerequisitos

* TSI463 Arquitectura Web
* Alto conocimiento sobre programación 
* Conocimientos básicos de HTML y CSS

Estos conocimientos no serán reforzados en clase, se recomienda  a cada estudiante repasar conceptos de programación si hiciera falta para poder llevar la materia con éxito.

## Contenidos del Curso

El curso estará divido en 3 partes principales: Introducción a PHP y MySQL, Desarrollo de aplicaciones con Symfony y Desarrollo de páginas web con Wordpress (existe la posibilidad de cambiar Wordpress por Ruby, se aceptará sugerencia de los estudiantes). Entre los temas de la materia se incluye:

* **Capítulo 1: CONCEPTOS FUNDAMENTALES**
      * HTTP y el protocolo petición-respuesta
      * Benificios de utilizar PHP
      * Servidor web Apache
      * Acerca de Open Source
* **Capítulo 2: INTRODUCCION AL ENTORNO DE TRABAJO**
      * Introduccion al versionamiento de código (Git y GitHub)
      * Instalar XAMPP en diferentes ambientes
      * Introducción a PHP 
          * Comentarios, Sintaxis, Variables, Operadores, Asignación, Tipos, Constantes y constantes predefinidas
          * Funciones, Ámbito de las variables
          * Expresiones y control del flujo en PHP
          * Funciones y objetos
          * Arreglos
          * Cookies sesiones y autenticaciones
* **Capítulo 3: MySQL**
      * Introducción a MySQL
      * Acceso via la línea de comandos y acceso via phpMyAdmin
      * Creación de la base de datos, índices
      * Acceso a MySQL via PHP
* **Capítulo 4: UTILIZACIÓN DE FRAMEWORKS**
      * Introducción a Symfony
      * Estructura de Symfony
      * Acciones y enrutamiento
      * BDD con Symfony
      * Vistas
      * Formularios
* **Capítulo 5: Wordpress**
      * Introducción
      * Instalación y configuración
      * Entradas
      * Páginas
      * Gestión de contenidos
      * Usuarios
      * Temas y personalización
      * Plugins

Para la clase se utilizará la metodología de la [**Clase Invertida** o **Flipped Classroom**](https://www.youtube.com/watch?v=ePOnn0H9GMY). Será necesario ver cada semana los videos para poder resolver los ejercicios presentados en el aula.


## Calendario de clases

### Clase 1
  Introducción a la materia y explicación de la metodología de trabajo.

### Temas para la siguiente clase
      * Git - hasta el Capítulo 4 (60 min aprox) - Si desean aprender la interfaz gráfica de Github pueden ver el Capítulo 5.
      * Fundamentos de PHP Capítulo 01 (45 min aprox) **Entregar los ejercicios realizados en los videos**

## Deberes/Proyectos

Cada semana se irá actualizando este sílabo para listar los deberes de cada semana, ejercicios en el aula y los proyectos.
Todas las tareas serán listadas en los [Contenidos del Curso](#contenidos-del-curso).

Todos los deberes deberán ser entregados **únicamente** vía GitHub. Para utilizar GitHub Desktop puede ver los videos del capítulo 5 del curso de Git que se les compartió la primera clase. También pueden leer [estas instrucciones](https://help.github.com/desktop/guides/contributing/) de la documentación oficial de GitHub.

Cada deber semanal o proyecto bimestral tendrá un repositorio propio, para entregar los deberes los estudiantes deben seguir estos pasos:

1. Hacer Fork del repositorio para el deber/proyecto se estará publicado en [github.com/EPN-ANP-2016A](https://github.com/EPN-ANP-2016A).
1. Clonar el repositorio a su computadora.
1. Modicar los archivos necesarios para completar la solución.
1. Asegurarse de hacer commit de todo el código `git commit -m "comnetario descriptivo del commit"`.
1. Subir los cambios a GitHub `git push origin master`.
1. [Crear un pull request](https://help.github.com/articles/creating-a-pull-request/) en el repositorio original. La fecha límite para todos los deberes es hasta el inicio de la siguiente clase, a menos que se indique lo contrario.
1. Pueden continuar subiendo cambios y mejoras hasta la fecha límite (asegurarse de incluir un comentario descriptivo de los cambios realizados en cada commit).

Se dará la retroalimentación en el pull request, y también podrán realizar preguntas a través del mismo.

### Requisitos

Esto se aplica también a la vida real:

* Tienen que utilizar "estándares de programación" como veremos en clases.
    * Las funciones deben ser cortas.
    * Optimizar para legibilidad.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * Cumplir con los estándares acordados según la herramienta que utilicemos.
* Cualquier código que utilicen de otros autores debe ser [referenciado](https://github.com/EPN-ANP-2016A/silabo#codigo-de-etica).
* Puntos extra por iniciativa y creatividad siempre y cuando se cumplan todos los requisitos.

## Trabajos en equipo

* Trabajaremos en grupo de tres personas para los proyectos del bimestre.
* Es recomendable que todo el equipo se ponga de acuerdo en un ambiente de trabajo (editor de texto o IDE).
* La persona que menos entiende debe trabajar más en el equipo.
* Todos deben participar activamente en el proyecto. Se revisará los logs de commits para ver la participación de cada uno en el proyecto.

## Peerwise

* Ingresar a [PeerWise](https://peerwise.cs.auckland.ac.nz)
* Registrase con el usuario del tipo `nombreapellido`
* **ID del curso:** 13117, su identificador es su email personal registrado en el SAEw.
* Realizar al menos 5 preguntas en PeerWise relacionadas con la materia. Preguntas de opción múltiple. Pueden ser ejercicios similares a los deberes o videos.
* Responder al menos 5 preguntas de sus compañeros.
* La nota será definida según la participación que hayan tenido en PeerWise, el tipo de preguntas que hayan realizado y el número de preguntas que hayan respondido y la dificultad de las preguntas respondidas.

## Calificaciones

Preguntas peerwise            10%
Deberes                               30%
Proyecto                               40%
Examen bimestral práctico  20%

## Código de Ética

### LA ESCUELA POLITÉCNICA NACIONAL

> La tradición y el prestigio de la Politécnica exigen que el comportamiento de sus miembros se encuadre en el respeto mutuo, la honestidad, el apego a la verdad y el compromiso con la institución.

Con tal antecedente, el presente Código de Ética define la norma de conducta de los miembros de la Escuela Politécnica Nacional:

RESPETO HACIA SÍ MISMO Y HACIA LOS DEMÁS
• Fomentar la solidaridad entre los miembros de la comunidad.
• Comportarse de manera recta, que afirme la autoestima y contribuya al prestigio institucional, que sea ejemplo y referente para los demás.
• Respetar a los demás y en particular la honra ajena y rechazar todo tipo de acusaciones o denuncias infundadas.
• Respetar el pensamiento, visión y criterio ajenos.
• Excluir toda forma de violencia y actitudes discriminatorias.
• Apoyar un ambiente pluralista y respetuoso de las diferencias.
• Convertir la puntualidad en norma de conducta.
• Evitar el consumo de bebidas alcohólicas, tabaco, substancias psicotrópicas o estupefacientes.

HONESTIDAD
• Hacer de la honestidad el principio básico de comportamiento en todos los actos.
• Actuar con justicia, probidad y diligencia.
• Actuar de acuerdo a la conciencia, sin que presiones o aspiraciones particulares vulneren los intereses institucionales.
• Velar por el cumplimiento de las garantías, derechos y deberes de los miembros de la Comunidad Politécnica.
• Tomar oportunamente las medidas correctivas necesarias para superar las irregularidades que pudieren ocurrir.

VERDAD
• Hacer una mística de la prosecución de la verdad, tanto en la actividad académica como en lo cotidiano.
• Informar con transparencia y en forma completa.
• Emitir mensajes con autenticidad, que no distorsionen eventos ni realidades.

COMPROMISO CON LA INSTITUCIÓN
• Ser leal a la Politécnica y a los valores institucionales.
• Cumplir las normas constitucionales, legales, estatutarias, reglamentarias y las resoluciones de la autoridad legítimamente designada.
• Reconocer y aceptar las consecuencias de las decisiones.
• Participar activamente en la vida y en la dirección de la institución, de acuerdo a los mecanismos de participación, aportando proactivamente con iniciativas de mejoramiento institucional y mantenerse informado.
• Emplear los recursos institucionales con austeridad, de acuerdo a los fines correspondientes.
• Contribuir al ornato y limpieza de nuestra Casa de Estudios. 

### Políticas de profesor

Respetar los términos de uso y/o licencia de cualquier código que se reuse.
Se tendrá en cuenta la asistencia a clases.
No se aceptan deberes atrasados.
Todo el material estará publicado en este repositorio.
**Para poder rendir el examen deben entregar todos los deberes y trabajos**.

## Licencia

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/advanced-js are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.