Capítulo V: Product Implementation, Validation & Deployment

` `5.1. Software Configuration Management. 

5\.1.1. Software Development Environment Configuration. 

Project Management: 

●       Para el manejo de nuestro proyecto utilizamos el software de Discord para realizar reuniones y coordinaciones. También, utilizamos Google Documents para realizar nuestro informe.



Project UI/ UX Design:

●       Figma: nos ayudó a poder diseñar los diferentes modelos de nuestros wireframes, mockups y Landing Page

●   	Miro: nos ayudó a poder desarrollar los apartados de Journey Map, Empathy Map, Impact Map y los As-is y To-Be Map. 



Software development:

●       VSCode: Visual Studio Code (VSCode) es un IDE desarrollado por Microsoft, el cual nos da la facilidad de poder realizar proyectos web.

●       HTML: Este lenguaje de marcas se utiliza para la creación de páginas web. El cual permite detallar la estructura y los elementos del sitio web.

●       CSS: Este lenguaje de estilos se utiliza para la implementación de diseños o estilos en una página web.

●       JavaScript: Nos permite realizar contenido dinámico o crear las interacciones que estarán en la página web.



Software Testing:

●       Lenguaje Gherkin: Este lenguaje nos permite realizar los escenarios y especificaciones de nuestros User Stories, el cual sigue una estructura en código predefinida en inglés: Feature, Scenario, Given, When, And, Then y Examples

5\.1.2. Source Code Management. 

La administración y estructuración de las múltiples modificaciones se realizaron mediante la creación de un repositorio en GitHub para el proyecto. Nuestra organización se estructuró de la siguiente manera:

Organización: <https://github.com/upc-pre-202401-si729-sw53-rocket>

Repositorio de la Landing page: <https://upc-pre-202401-si729-sw53-rocket-land.netlify.app>

Además, con el objetivo de mejorar el control sobre la creación de ramas y la implementación de cambios en el código fuente, se procedió a utilizar Gitflow.

De esta forma, se establecieron 3 ramas principales: main y develop.

**Ramas principales:**

Rama “main”: En esta rama se almacenan las versiones oficiales de nuestro repositorio para pasarlas a producción. Rama “develop”: Esta rama se utilizará como punto de integración para las ramas de “feature”. Una vez que el  “head” sea estable y el equipo lo considere listo para el lanzamiento, se fusionará con la rama “release”.

**Ramas auxiliares:**

- Rama “release”: La rama “release” se emplea para la preparación del lanzamiento de una nueva versión en la rama “main” ayudando a controlar las versiones de código. Aquí se pueden solucionar errores menores y preparar los datos para la versión. Esta rama permitirá liberar a la rama “develop” de estas tareas preparatorias y evita demoras en el desarrollo mientras se prepara para el lanzamiento. 
- Rama “feature”: En las ramas “feature” se desarrollan las características generales que se integrarán en la rama “develop”. Estas características son aquellas funcionalidades solicitadas por los usuarios tanto en la página de inicio como en la aplicación web. Por ejemplo, la rama feature/navbar.
- Rama “hotfix”: Esta rama se utiliza para corregir urgentemente errores en la última versión de la rama “main” que no pueden esperar hasta el próximo lanzamiento para ser solucionados.

5\.1.3. Source Code Style Guide & Conventions. 

●        Utilizaremos el lenguaje de etiquetas HTML para el desarrollo principal de nuestra Landing page.

●        Utilizaremos el lenguaje CSS, que nos permitirá realizar los estilos de la estructura de nuestra Landing Page

●        Implementaremos el lenguaje de JavaScript para brindar las funcionalidades a nuestra Landing page. 

●        Utilizaremos el lenguaje Gherkin que se usará para realizar los diseños de prueba de cada historia de usuario contando con su estructura básica. 

5\.1.4. Software Deployment Configuration. 

Entrar a Netlify y presionar la opción de “Import an existing project”

![Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente](Aspose.Words.87793398-8a20-4737-8eb2-fee9399dc4e8.001.png)

Después seleccionar la opcion de “Deploy con github”

![Captura de pantalla con la imagen de una pantalla

Descripción generada automáticamente](Aspose.Words.87793398-8a20-4737-8eb2-fee9399dc4e8.002.png)

Tras haber hecho eso tenemos que seleccionar nuestra organización y dentro de ella buscar el repositorio del proyecto que deseamos subir a producción

![Fondo negro con letras blancas

Descripción generada automáticamente con confianza media](Aspose.Words.87793398-8a20-4737-8eb2-fee9399dc4e8.003.png)

Para finalmente agregar la data necesaria para el despliegue

![Interfaz de usuario gráfica, Texto, Aplicación

Descripción generada automáticamente](Aspose.Words.87793398-8a20-4737-8eb2-fee9399dc4e8.004.png)

Y final solo presionar el botón con el nombre de proyecto a desplegar

![Imagen que contiene Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.87793398-8a20-4737-8eb2-fee9399dc4e8.005.png)

\-       Link de la Landing page:[ ](https://echero11.github.io/OpenSource_GasYa_LandingPage/)https://upc-pre-202401-si729-sw53-rocket-land.netlify.app







5\.2. Landing Page, Services & Applications Implementation.

5\.2.1. Sprint 1

5\.2.1.1. Sprint Planning 1. 

A continuación, se detalla el sprint planning número uno, en el que se expondrán las pruebas de planificación y ejecución de la landing page. Además, se mostrarán los progresos del proyecto y los conocimientos adquiridos sobre la colaboración en equipo, obtenidos a través de la utilización de GitHub.

|Sprint#|Sprint 1|
| :- | :- |
|Sprint Planning Background||
|Date|Domingo 8 de abril del 2024|
|Time|19:00|
|Location|Videoconferencia Discord|
|Prepared By|Rocket|
|Attendees|Todo el equipo|
|<p>Sprint n - 0</p><p>Review Summary</p>|Al ser el primer sprint, no hay review summary previo.|
|<p>Sprint n - 1 </p><p>Retrospective Summary</p>|Durante este sprint, nos centraremos en el desarrollo de la landing page utilizando Tailwind, un framework de estilos familiar para todos los miembros del equipo. Además, abordaremos la definición del contenido textual de la página y la integración de los diseños previamente creados en Figma. Una vez completado este sprint, publicaremos la landing page a través de Netlify, lo que permitirá que cualquier usuario acceda y visualice la página mediante el enlace correspondiente.|
|Sprint 1 Velocity|8|
|Sum of Story Points|8|




5\.2.1.2. Sprint Backlog 1. 

En esta sección se presentan los tasks realizados durante el actual sprint, acompañadas de una captura del tablero correspondiente y el enlace al tablero en Trello.

A continuación, presentamos nuestro Product Backlog detallado:

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.87793398-8a20-4737-8eb2-fee9399dc4e8.006.png)

Enlace a nuestro trabajo elaborado en Trello [RocketOrganize | Product Backlog](https://trello.com/invite/b/oJkn7AQk/ATTI4439c33eb497436177277d54025d9114015E5CF7/product-backlog)

<table><tr><th colspan="2" valign="top"><b>Sprint #</b></th><th colspan="5" valign="top"><b>Sprint 1</b></th></tr>
<tr><td colspan="2" valign="top"><b>User Story</b></td><td colspan="5" valign="top"><b>Work-item / Task</b></td></tr>
<tr><td>ID</td><td>Title</td><td>Id</td><td>Descripción</td><td>Estimación (horas)</td><td>Asignado a:</td><td>Status (pendiente/en proceso/en revisión/hecho)</td></tr>
<tr><td rowspan="6" valign="top">E5-US20</td><td rowspan="6" valign="top">Características del Producto</td><td>T1</td><td valign="top">Hacer el navbar</td><td rowspan="6">1h</td><td rowspan="6">Abraham</td><td rowspan="6">hecho</td></tr>
<tr><td>T2</td><td valign="top">Hacer el navbar responsive</td></tr>
<tr><td>T3</td><td valign="top">Hacer el Home</td></tr>
<tr><td>T4</td><td valign="top">Hacer el Home</td></tr>
<tr><td>T5</td><td valign="top">Hacer el article de características del producto</td></tr>
<tr><td>T6</td><td valign="top">Hacer el article de características del producto responsive</td></tr>
<tr><td rowspan="2" valign="top">E5-US21</td><td rowspan="2" valign="top">Confirmación de la Confiabilidad a través de Reseñas</td><td rowspan="2">T7</td><td valign="top">Hacer el article de reviews</td><td rowspan="2">0\.2h</td><td rowspan="2">Belén</td><td rowspan="2">hecho</td></tr>
<tr><td valign="top">Hacer el article de reviews responsive</td></tr>
<tr><td rowspan="2" valign="top">E5-US22</td><td rowspan="2" valign="top">Evaluación de Planes y Precios</td><td>T8</td><td valign="top">Hacer el article de pricing</td><td rowspan="2">0\.3h</td><td rowspan="2">José</td><td rowspan="2">hecho</td></tr>
<tr><td>T9</td><td valign="top">Hacer el article de pricing responsive</td></tr>
<tr><td rowspan="2" valign="top">E5-US23</td><td rowspan="2" valign="top">Facilidad de Contacto con la Empresa</td><td>T10</td><td valign="top">Hacer el article de contact</td><td rowspan="2">0\.3h</td><td rowspan="2">Mateo</td><td rowspan="2">hecho</td></tr>
<tr><td>T11</td><td valign="top">Hacer el article de contact responsive</td></tr>
<tr><td valign="top">E5-US24</td><td valign="top">Navegación Intuitiva en la Landing Page</td><td>T12</td><td valign="top">Optimización de elementos UI de la landing page</td><td>0\.5h</td><td rowspan="2">Ariana</td><td>hecho</td></tr>
<tr><td valign="top">E5-US25</td><td valign="top">Selección de Idioma en la Landing Page</td><td>T13</td><td valign="top">` `Cambiar algunos detalles de la web de español a ingles</td><td>0\.4h</td><td>hecho</td></tr>
</table>

5\.2.1.3. Development Evidence for Sprint Review. 

<table><tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Committed on (Date)</b></th></tr>
<tr><td rowspan="36" valign="top">upc-pre-202401-si729-sw53-rocket-landing-page</td><td rowspan="20" valign="top">main</td><td valign="top">8a254e3e5aa9b7e80ab10b6b733bc88a29a4c6b3</td><td valign="top">[chore: add the main structure](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/8a254e3e5aa9b7e80ab10b6b733bc88a29a4c6b3)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">4609e24d14ae216d33f5c5509fb5600f96a46051</td><td valign="top">[docs: update README.md file](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/4609e24d14ae216d33f5c5509fb5600f96a46051)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">7322cebef484c6da94f2ae67098a9bd93b139a8a</td><td valign="top">[feat: add meta tags](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/7322cebef484c6da94f2ae67098a9bd93b139a8a)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">76e5efdd479daf87234a1b23be6adf1f577aed58</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/76e5efdd479daf87234a1b23be6adf1f577aed58) [#1](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/1) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/76e5efdd479daf87234a1b23be6adf1f577aed58)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">43161a7335cf6889bf83695371da72acffc50c1a</td><td valign="top">[feat: add the navbar](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/43161a7335cf6889bf83695371da72acffc50c1a)</td><td valign="top">-</td><td valign="top">Mar 29, 2024</td></tr>
<tr><td valign="top">1bbf106ac3e457b32ef97563caeebb84f8f70528</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/1bbf106ac3e457b32ef97563caeebb84f8f70528) [#2](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/2) [from upc-pre-202401-si729-sw53-rocket/feature/navbar](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/1bbf106ac3e457b32ef97563caeebb84f8f70528)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">f2e7e348e3da7e62cd815f0c318fae574f3b0bcd</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f2e7e348e3da7e62cd815f0c318fae574f3b0bcd) [#3](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/3) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f2e7e348e3da7e62cd815f0c318fae574f3b0bcd)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">6920a1d0f035eaf7a47121afb08f9f9011c795f3</td><td valign="top">[feat: add the main section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/6920a1d0f035eaf7a47121afb08f9f9011c795f3)</td><td valign="top">-</td><td valign="top"><p>Mar 29, 2024</p><p></p></td></tr>
<tr><td valign="top">2481b48fcb76c921ebe0cc53f8418345839b9646</td><td valign="top">[feat: update the main section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2481b48fcb76c921ebe0cc53f8418345839b9646)</td><td valign="top">-</td><td valign="top"><p>Commits on Mar 30, 2024</p><p></p></td></tr>
<tr><td valign="top">27f7c088da8bcc9a32d0de69c2060f641becd13f</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/27f7c088da8bcc9a32d0de69c2060f641becd13f) [#4](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/4) [from upc-pre-202401-si729-sw53-rocket/feature/main-section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/27f7c088da8bcc9a32d0de69c2060f641becd13f)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">2655602ba5e0ab4c177241b81aa8474ccb8869b2</td><td valign="top"><p>[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2655602ba5e0ab4c177241b81aa8474ccb8869b2) [#5](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/5) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2655602ba5e0ab4c177241b81aa8474ccb8869b2)</p><p></p></td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">cff64663ba32cbdc86c3f1fd64ed70b5d1e26a40</td><td valign="top">[feat: update the main section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/cff64663ba32cbdc86c3f1fd64ed70b5d1e26a40)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">589c73176a3976dbcf163b57ce493706c8c35717</td><td valign="top"><p>[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/589c73176a3976dbcf163b57ce493706c8c35717) [#6](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/6) [from upc-pre-202401-si729-sw53-rocket/feature/main-section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/589c73176a3976dbcf163b57ce493706c8c35717)</p><p></p><p></p></td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">c97d4d44c72a42f9c83f750d2c9c337519a2bbf8</td><td valign="top">[feat: add the complementary section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/c97d4d44c72a42f9c83f750d2c9c337519a2bbf8)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">17af11d000b5999a535cf95865f2d7af9fbfaaec</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/17af11d000b5999a535cf95865f2d7af9fbfaaec) [#7](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/7) [from upc-pre-202401-si729-sw53-rocket/feature/main-section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/17af11d000b5999a535cf95865f2d7af9fbfaaec)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">2e97772d58ad75fdc1f0a004cf4f12b7b3a4345a</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2e97772d58ad75fdc1f0a004cf4f12b7b3a4345a) [#8](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/8) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2e97772d58ad75fdc1f0a004cf4f12b7b3a4345a)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">72854cdf8af1e187528f8127afb638761d4696bf</td><td valign="top">[feat: add the about product section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/72854cdf8af1e187528f8127afb638761d4696bf)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">2edf3314c8446c4b378dbb2631b1729d5cdaf5a8</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2edf3314c8446c4b378dbb2631b1729d5cdaf5a8) [#9](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/9) [from upc-pre-202401-si729-sw53-rocket/feature/about-the-product](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2edf3314c8446c4b378dbb2631b1729d5cdaf5a8)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">cf823d0834194f0e6a0f40b6baaa241d3feb7090</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/cf823d0834194f0e6a0f40b6baaa241d3feb7090) [#10](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/10) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/cf823d0834194f0e6a0f40b6baaa241d3feb7090)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">2ef6377668fc1b215846aa78ecaf20abd8fd3e3b</td><td valign="top">[feat: add the contact section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/2ef6377668fc1b215846aa78ecaf20abd8fd3e3b)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td rowspan="16" valign="top"></td><td valign="top">a19d3bea1859178ba71d51c769a0e719bf13c680</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/a19d3bea1859178ba71d51c769a0e719bf13c680) [#11](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/11) [from upc-pre-202401-si729-sw53-rocket/feature/contact](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/a19d3bea1859178ba71d51c769a0e719bf13c680)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">58b669906b2f0bd48d7d4339290baa912687b511</td><td valign="top"><p>[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/58b669906b2f0bd48d7d4339290baa912687b511) [#12](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/12) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/58b669906b2f0bd48d7d4339290baa912687b511)</p><p></p><p></p></td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">3fc53f46614cba424eb84a47466ea50642f19814</td><td valign="top">[feat: add the footer](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/3fc53f46614cba424eb84a47466ea50642f19814)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">d59e3a988941ae4c3d7877f36a236c1394d0f3e5</td><td valign="top"><p>[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/d59e3a988941ae4c3d7877f36a236c1394d0f3e5) [#13](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/13) [from upc-pre-202401-si729-sw53-rocket/feature/footer](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/d59e3a988941ae4c3d7877f36a236c1394d0f3e5)</p><p></p><p></p></td><td valign="top">-</td><td valign="top">Mar 31, 2024</td></tr>
<tr><td valign="top">f25a895a784e151c96759ace87db2fa310a5d906</td><td valign="top">[feat: add the reviews section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f25a895a784e151c96759ace87db2fa310a5d906)</td><td valign="top">-</td><td valign="top">Mar 31, 2024</td></tr>
<tr><td valign="top">50f57be2bc939eb7cf6786892def5cc397a19bbb</td><td valign="top"><p>[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/50f57be2bc939eb7cf6786892def5cc397a19bbb) [#14](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/14) [from upc-pre-202401-si729-sw53-rocket/feature/reviews](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/50f57be2bc939eb7cf6786892def5cc397a19bbb)</p><p></p><p></p></td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">157496b43fa3593ef22637e29ec58bce994e9d89</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/157496b43fa3593ef22637e29ec58bce994e9d89) [#15](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/15) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/157496b43fa3593ef22637e29ec58bce994e9d89)</td><td valign="top">-</td><td valign="top"><p>Mar 31, 2024</p><p></p></td></tr>
<tr><td valign="top">6f2eaf06e3bde7018b833364a262176aaec4be2b</td><td valign="top">[feat: add the pricing section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/6f2eaf06e3bde7018b833364a262176aaec4be2b)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">4eb3a9cdec5fa3cd5fd1d90b8a0bd63ff17df471</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/4eb3a9cdec5fa3cd5fd1d90b8a0bd63ff17df471) [#16](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/16) [from upc-pre-202401-si729-sw53-rocket/feature/pricing](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/4eb3a9cdec5fa3cd5fd1d90b8a0bd63ff17df471)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">f2190808665f6d58fa61ed3d6b8c4611c9c2b598</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f2190808665f6d58fa61ed3d6b8c4611c9c2b598) [#17](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/17) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f2190808665f6d58fa61ed3d6b8c4611c9c2b598)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">77bf651ee3feba7507a7047c16f09b198f276e06</td><td valign="top">[refactor: update the pricing section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/77bf651ee3feba7507a7047c16f09b198f276e06)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">6c5857f6a1c5d7966726a26c40733f9e091aef0b</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/6c5857f6a1c5d7966726a26c40733f9e091aef0b) [#18](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/18) [from upc-pre-202401-si729-sw53-rocket/release/v0.1.0](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/6c5857f6a1c5d7966726a26c40733f9e091aef0b)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">f417c5d5c28ba0b91292f9f06fcc88b9f6229c5b</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f417c5d5c28ba0b91292f9f06fcc88b9f6229c5b) [#19](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/19) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f417c5d5c28ba0b91292f9f06fcc88b9f6229c5b)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">b848ef2a41ee0dd2a99a39dade8f86bcdaaf7206</td><td valign="top">[refactor: update the reviews section](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/b848ef2a41ee0dd2a99a39dade8f86bcdaaf7206)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">d317eae9bb4013aa5c319549edeba233e661f9ba</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/d317eae9bb4013aa5c319549edeba233e661f9ba) [#20](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/20) [from upc-pre-202401-si729-sw53-rocket/release/v0.1.0](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/d317eae9bb4013aa5c319549edeba233e661f9ba)</td><td valign="top">-</td><td valign="top">Apr 2, 2024</td></tr>
<tr><td valign="top">f775eadd72dfe6264f6b553c5d77d461640a4678</td><td valign="top">[Merge pull request](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f775eadd72dfe6264f6b553c5d77d461640a4678) [#21](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/pull/21) [from upc-pre-202401-si729-sw53-rocket/develop](https://github.com/upc-pre-202401-si729-sw53-rocket/upc-pre-202401-si729-sw53-rocket-landing-page/commit/f775eadd72dfe6264f6b553c5d77d461640a4678)</td><td valign="top">-</td><td valign="top"><p>Apr 2, 2024</p><p></p></td></tr>
</table>

5\.2.1.4. Testing Suite Evidence for Sprint Review. 

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commit Message Body**|**Commited on (Date)**|
| :- | :- | :- | :- | :- | :- |
|acceptance-test|main|0701053c5600588af3a967a786327b7c2ba5404a|feat: add all the epics|-|Apr 3, 2024|

5\.2.1.5. Execution Evidence for Sprint Review. 

Esta sección inicia con un resumen que explique lo alcanzado en este Sprint y presenta screenshots de las principales vistas implementadas, junto con un enlace a un video que ilustre y explique la visualización y navegación logrados en este Sprint.

5\.2.1.6. Services Documentation Evidence for Sprint Review. 

En el alcance del sprint 1 se logró desarrollar la landing page, por lo que no se evidencia el empleo de web services.

5\.2.1.7. Software Deployment Evidence for Sprint Review. 

Para el primer sprint hicimos la landing page. Para su respectivo despliegue utilizamos:

- Git: Sistema de control de versiones para trabajar de forma colaborativa entre los integrantes de nuestro grupo.
- Gitflow: flujo de las ramas de nuestro repositorio en github.
- Conventional commits: estándar textual de los commits.
- Github: plataforma en el que almacenamos todos los repositorios de nuestro proyecto.
- Netlify: plataforma en la que se aloja la landing page.

5\.2.1.8. Team Collaboration Insights during Sprint. 

Durante este sprint para proteger la rama “main” creamos una rama “develop” de la que cada integrante de nuestro grupo creó su propia sub-rama “feature“ para subir un capítulo del reporte siguiendo las convenciones antes señaladas(conventional commit y git flow).

**Conclusiones:**

- Nuestro análisis comparativo resaltó la necesidad de destacarnos claramente en el mercado. Identificamos nuestras ventajas competitivas, como ofrecer una solución integral que abarca tanto la gestión académica como la administrativa, lo cual nos permite satisfacer las necesidades de las instituciones educativas de manera más completa que nuestros competidores.




- Dada la diversidad de instituciones educativas en términos de tamaño, ubicación y necesidades específicas, es crucial que nuestra solución sea adaptable y escalable. Esto requerirá un enfoque flexible en el diseño y desarrollo de nuestro producto, así como la capacidad de ajustarnos a medida que el mercado evoluciona.




- Las entrevistas realizadas nos han proporcionado una comprensión más profunda de las necesidades, desafíos y prioridades de los profesores y el personal administrativo en las instituciones educativas. Esto nos ha permitido identificar áreas de mejora potenciales en nuestro enfoque, producto o estrategias de comercialización, como la personalización de la experiencia del usuario o la integración de funcionalidades adicionales.




- La comunicación y colaboración entre los diferentes actores en las instituciones educativas son clave para el éxito de las operaciones. Nuestra plataforma busca facilitar esta comunicación directa entre profesores, personal administrativo, estudiantes y padres, fomentando así la coordinación y el intercambio de información para mejorar la experiencia educativa.

**Bibliografía:** 

Smith, J., & Doe, J. "Enhancing Efficiency in Education through Learning Management Systems: A Case Study of the Blackboard System." Educational Technology Research and Development, vol. 65, no. 4, 2017, pp. 1023-1039.

**Anexos:**

Product Backlog: <https://trello.com/invite/b/oJkn7AQk/ATTI4439c33eb497436177277d54025d9114015E5CF7/product-backlog>

Landing Page Wireframe y Mock-up: <https://www.figma.com/file/KSPnhnWKuR0DeKh6xT17pr/RocketNotes-vFinal?type=design&node-id=0-1&mode=design&t=EscbJdReBHxPcM4R-0>

Web Applications Wireframes y Mock-up: <https://www.figma.com/file/KSPnhnWKuR0DeKh6xT17pr/RocketNotes-vFinal?type=design&node-id=0-1&mode=design&t=EscbJdReBHxPcM4R-0>

Web Applications Prototyping: <https://www.figma.com/file/KSPnhnWKuR0DeKh6xT17pr/RocketNotes-vFinal?type=design&node-id=0-1&mode=design&t=EscbJdReBHxPcM4R-0>

Class Diagrams: <https://lucid.app/lucidchart/efcf0a82-8b7d-4bad-9b32-f7cd9ef240af/edit?viewport_loc=-2464%2C-1521%2C4344%2C2051%2C0_0&invitationId=inv_2d95ad6e-141a-451b-938d-ce8677d30cdf>

Database Diagram:

Sprint Backlog 1: <https://trello.com/invite/b/oJkn7AQk/ATTI4439c33eb497436177277d54025d9114015E5CF7/product-backlog>

Segmento objetivo:  **Profesores y equipo administrativo**

