# Sílabo para Ambientes No Propietarios ESFOT-EPN 2016A

* **Materia:** ASI_TSI553 Ambientes No Propietarios
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

## Deberes/Proyectos

Cada semana se irá actualizando este sílabo para listar los deberes de cada semana, ejercicios en el aula y los proyectos.
Todas las tareas serán listadas en los [Contenidos del Curso](#contenidos-del-curso).

### Metodología de trabajo



If you're using GitHub Desktop, [these instructions](https://help.github.com/desktop/guides/contributing/) will help explain the Git/GitHub concepts. Here are the overall steps:

1. Fork the repository for the exercise/project (found under [github.com/advanced-js](https://github.com/advanced-js)).
1. Clone the repository to your computer.
1. Open the `index.html` file in a browser and open the Developer Tools.
1. Modify the files to complete your solution.
1. Refresh the `index.html` page to see the results, and repeat.
1. Make sure all of your code is committed.
1. Push/sync up to GitHub.
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) on the original repository. All assignments are due at the start of the following class, unless otherwise specified.
1. You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let me know it's been updated.

When the pull request is created, you should see a message saying that "the Travis CI build is in progress" – this means that your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix the issues and push up the changes.

Feedback will be given in the pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request as the work is still in-progress if you are stuck and want to ask a question – just mention `@afeld` with the question to make sure I know to look at it sooner.

Note that your solution will also be live at `http://USERNAME.github.io/EXERCISE`.  For exercises with multiple levels/versions, leave a new comment in the pull request saying "Level X finished!" before pushing commits for the next level. "BONUS" levels are for extra credit.

### Requirements

These apply to real life, as well.

* [Travis CI](https://docs.travis-ci.com/) build should pass, which includes:
    * All HTML files should pass [W3C Markup Validation](http://validator.w3.org).
    * All written JS should pass [JSHint](http://jshint.com).
* Must apply "good programming style" learned in class
    * Functions should be "short" (see [Sandi Metz's rules for developers](https://robots.thoughtbot.com/sandi-metz-rules-for-developers)).
    * Optimize for readability.
        * ["Programs must be written for people to read, and only incidentally for machines to execute." -Harold Abelson](https://www.goodreads.com/quotes/9168-programs-must-be-written-for-people-to-read-and-only)
    * Avoid using anonymous callbacks within other functions, especially if the callback is more than one or two lines.
    * For projects, use Object-Oriented Programming.
* Any borrowed code must be properly [annotated](http://documentup.com/advanced-js/syllabus#statements-on-plagiarism/instructor).
* Bonus points for:
    * [Automated tests](#test-frameworks)
    * Creativity (as long as requirements are fulfilled)

## Course Outline

### Class 1

1. Introduction
    * Put name on sticky note on back of monitor
    * Discuss what the class is going to cover
    * Everyone introduce themselves
        * Name
        * What you "do"
        * What are your goals for the class?
        * What's something in JS (or technology) you worry that your peers understand but you don't?
1. Setup
    * How many people are comfortable with Git/GitHub?
    * Install [GitHub Desktop](https://desktop.github.com/)
        * If you are comfortable with Git already, you can skip this.
    * Sign up for GitHub
1. GitHub workflow
    * Walk through [workflow](#workflow)
    * Create pull request on [students repository](https://github.com/advanced-js/students)
1. Explain how slides work
1. Get through `countdown_exercise` slide
1. Talk through [requirements](#homework-projects/requirements)

#### Homework

* Join [the chat room](https://gitter.im/advanced-js/syllabus).
* Access [NYU Classes](https://newclasses.nyu.edu) page, where grades will be posted.
    * [Documentation](https://wikis.nyu.edu/display/nyuclasses/Student+Quick-Start)
* Read [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/).
* Finish up and submit [echo](https://github.com/advanced-js/echo) and [countdown](https://github.com/advanced-js/countdown) exercises.
* Complete [blink](https://github.com/advanced-js/blink) exercise.

### Class 2

1. Look at various approaches for `countdown()`
    * Show recursive solution
1. Developer Tools walkthrough
    * Elements (HTML)
    * Console (JS)
    * Scripts (JS)
1. Pair program to build [Memory v1](https://github.com/advanced-js/memory) (see [pairing tips](#pairing-tips))
1. Cover OOP, though "oop_inheritance" slide
    * [Encapsulation example](http://jsbin.com/baqopu/1/edit?css,js,output)
    * Look at [Backbone.js Events](http://backbonejs.org/docs/backbone.html)

#### Homework

* Read [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [OOP exercise](https://github.com/advanced-js/oop), through V2
* [Memory v2](https://github.com/advanced-js/memory#v2) (individual)

### Class 3

1. Code review Memory
1. Get through [`oop_inheritance`](http://advanced-js.github.io/deck/examples/oop_inheritance/) slide
1. Cover automated testing
    * Build up a test framework from scratch
    * Examples in QUnit
        * [Simple](http://jsbin.com/woqusi/edit?html,js,output)
        * [Classes](http://jsbin.com/nukamun/edit?js,output)
        * [QUnit documentation](http://qunitjs.com/)
    * [Other frameworks](#test-frameworks)
1. Cover AJAX/CORS/JSONP ([files](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax))
    * Network tab in Developer Tools

#### Homework

* Read [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* Complete [OOP exercise](https://github.com/advanced-js/oop) through V4.
* [Memory V3](https://github.com/advanced-js/memory#v3)

### Class 4

1. Finish slides
1. Getting Serious example
    * Quick intro to Backbone.js
        * [Boilerplate](http://jsbin.com/IGivato/1/edit?html,js,output)
        * Click the Box [example app](http://jsbin.com/IGivato/5/edit?css,js,output)
        * TDD?
1. Multiple async
    * [Promises](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax/promises)/[jQuery.Deferred](http://api.jquery.com/jQuery.Deferred/)
    * Possibly show [async](https://github.com/caolan/async#control-flow-1) library?

#### Homework

* [Learn about AJAX](https://github.com/advanced-js/deck/tree/gh-pages/demos/ajax#readme)
* [Mashup](https://github.com/advanced-js/mashup)
* Improve your previous assignments

### Class 5

1. Present and code review Mashup projects
1. Possible topics (vote?):
    * Node.js
        * Server "Hello World" (from [Node.js homepage](http://nodejs.org/))
            * [HTTP module docs](http://nodejs.org/api/http.html)
        * HTTP requests
            * [Status codes](http://pretty-rfc.herokuapp.com/RFC2616#status.codes)
            * Headers
        * CommonJS?
    * [Regular Expressions](https://github.com/advanced-js/deck/tree/gh-pages/demos/regex.html)
        * Convert live input from a text area, e.g.
            * Link Twitter handles
            * Substitute select words for emoji, using [emoji-css](http://afeld.github.io/emoji-css/)
    * Object-Oriented design
    * [Code Retreat](http://coderetreat.org/facilitating/structure-of-a-coderetreat) – possible "problems":
        * [Game of Life](http://coderetreat.org/gol)
        * Tic Tac Toe

## Pairing Tips

* Three people is possible, but two works best
* Agree on an editor and environment that you're both comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to both people

## Resources

### Required Reading

* [Google JavaScript Style Guide](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
* [JavaScript Garden](http://bonsaiden.github.com/JavaScript-Garden/)
* [Mozilla's Introduction to Object-Oriented Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [What’s so great about JavaScript Promises?](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/)
* https://twitter.com/necolas/status/291978260433219584
* http://afeld.me/nerdery/1742468

### Beginner Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* Codecademy – [JavaScript](https://www.codecademy.com/learn/javascript) and [jQuery](https://www.codecademy.com/learn/jquery)
* [Eloquent JavaScript](http://eloquentjavascript.net/index.html) by Marijn Haverbeke, Chapters 1-5
* [Want to learn JavaScript in 2015?](https://medium.com/@_cmdv_/i-want-to-learn-javascript-in-2015-e96cd85ad225)
* see also – [Other Lists](#other-lists)

### Recommended Reading

* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) by Michael Fogus
* [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) by @darcyclarke (for testing yourself)
* [JavaScript Best Practices](http://www.thinkful.com/learn/javascript-best-practices-1/)
* [JavaScript Patterns](http://shichuan.github.io/javascript-patterns/) by @shichuan (thanks @iandrewfuchs)
* [JavaScript Patterns](http://www.amazon.com/JavaScript-Patterns-Stoyan-Stefanov/dp/0596806752) by Stoyan Stephanov
* [JavaScript Web Applications](http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X/) by Alex MacCaw
* [JavaScript: The Good Parts](http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742) by Douglas Crockford
* [Learning Advanced JavaScript slides](http://ejohn.org/apps/learn/) by John Resig
* [Static Web Apps](http://www.staticapps.org/)
* [Test-Driven JavaScript Development](http://www.amazon.com/Test-Driven-JavaScript-Development-Developers-Library/dp/0321683919) by Christian Johansen
* [The JavaScript Interpreter, Interpreted](http://www.slideshare.net/marthakelly/js-interpreter-interpreted) by Martha Girdler [(video)](https://www.youtube.com/watch?v=iSxNCYcPAFk)

#### Specific Topics

* [Classical Inheritance in JavaScript](http://www.crockford.com/javascript/inheritance.html) by Douglas Crockford
* [Partial Application in JavaScript](http://benalman.com/news/2012/09/partial-application-in-javascript/) by Ben Alman (thanks @michaelBenin)
* [HTML5 Rocks slides](http://slides.html5rocks.com/)
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) by Addy Osmani

#### Other Lists

* [JS: The Right Way](http://www.jstherightway.org/) (an overview of the JS landscape)
* [Code School](https://www.codeschool.com/paths/javascript)
* Thoughtbot's [Javascript Trail Map](https://upcase.com/javascript)
* [How To Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)
* [Superhero.js](http://superherojs.com)
* [Teach Yourself to Code](http://teachyourselftocode.com/javascript)

### Tools

* code validation: [JSLint](http://jslint.com) / [JSHint](http://jshint.com)
* debugging:
    * [Chrome Developer Tools](https://developer.chrome.com/devtools/index)
        * [Official debugging tutorial](https://developer.chrome.com/extensions/tut_debugging)
        * Tutorial: [JavaScript Diagnosis](http://www.macwright.org/2015/03/10/javascript-diagnosis.html)
    * [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
* sharing code snippets: [gist.github.com](https://gist.github.com/)
* asking questions: [Stack Overflow](http://stackoverflow.com/)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
    * [Recommended resources](http://hackerhours.org/resources.html#github)
* GitHub Pages
    * [Official site](https://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

#### HTML/CSS/JS Sandboxes

* [JS Bin](http://jsbin.com/) (recommended)
* [bl.ocks.org](http://bl.ocks.org/)
* [Cloud9](https://c9.io/)
* [CodePen](http://codepen.io/pen/)
* [JSFiddle](http://jsfiddle.net/)
* [Plunker](http://plnkr.co/)
* [rawgithub.com](http://rawgit.com/)

#### Frameworks

* Framework comparison: [TodoMVC](http://todomvc.com)
* [Testing](https://coderwall.com/p/ntbixw)

### Reference

* [Mozilla Developer Network](https://developer.mozilla.org/en/JavaScript) and [Learn JavaScript](https://developer.mozilla.org/en-US/learn/javascript)
* [w3schools](http://www.w3schools.com/jsref/default.asp)
* [JavaScript: The Definitive Guide](http://shop.oreilly.com/product/9780596000486.do) by David Flanagan

### More Examples

* [map/reduce](http://jsbin.com/ojapAsUR/2/edit?js) (in [Underscore](http://underscorejs.org/#map))

## Grading

* Class Participation – 30%
* Homework – 70%

## Statements on Plagiarism

### SCPS

> New York University takes plagiarism very seriously and regards it as a form of fraud.  The definition of plagiarism that has been adopted by the School of Continuing and Professional Studies is as follows: "Plagiarism is presenting someone else's work as though it were one's own.  More specifically, plagiarism is to present as one's own words quoted without quotation marks from another writer; a paraphrased passage from another writer’s work; or facts or ideas gathered, organized, and reported by someone else, orally and/or in writing.  Since plagiarism is a matter of fact, not of the student's intention, it is crucial that acknowledgement of the sources be accurate and complete.  Even where there is not a conscious intention to deceive, the failure to make appropriate acknowledgement constitutes plagiarism.  Penalties for plagiarism range from failure for a paper or course to dismissal from the University.

### Instructor

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers.  I won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/advanced-js are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.