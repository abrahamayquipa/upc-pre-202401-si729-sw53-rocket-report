
![Upc Logo](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.001.png)

**Universidad Peruana de Ciencias Aplicadas**


Ingeniería de software

Aplicaciones web

SW51

**Informe del Trabajo Final**

Alex Humberto Sánchez Ponce

Rocket

*“RocketOrganize”*


|**Integrantes**|**Código**|
| :-: | :-: |
|Ayquipa Ubaldo, Abraham Israel|U202218475|
|Mayuri Armas, Jose Carlo |U2020111437|
|Vilchez Rios, Mateo Alejandro |U202210059|
|Ramos Rios, Belen del Rocio|U202216246|
|Vargas Revollé, Ariana|U20221A928|

Marzo de 2024-01

**Registro de Versiones del Informe**
**

|**Versión**|**Fecha**|**Autor**|**Descripción de modificación**|
| :-: | :-: | :-: | :-: |
|#01|08/04/2024|Todos los participantes|Elaboración del capítulo 1: Introducción|

**Student Outcome**

|**Criterio Específico**|**Acciones Realizadas**|**Conclusiones**|
| :- | :- | :- |
|La capacidad de identificar, formular y resolver problemas complejos de ingeniería aplicando los principios de ingeniería, ciencia y matemática.|Reconocimiento de un problema actual en estudiantes autistas. Formulamos una solución con la creación de un producto de software.|Se identificó un problema y se trabaja en su solución.|
|Elaborar una propuesta de solución a una problemática o lograr mejora de una solución ya existente a través de la innovación.** |Hasta el momento no se ha programado nada.|Cuando llegue el momento, estaremos listos para programar y darle un correcto funcionamiento.|


<a name="_k3gyangg8ba3"></a>**Capítulo I: Introducción** 

1\.1. Startup Profile 
#### <a name="_gjdgxs"></a>**1.1.1. Descripción de la Startup** 

En un entorno educativo que se vuelve cada vez más complejo, con instituciones lidiando con desafíos tanto operativos como pedagógicos, surge una necesidad evidente: simplificar la gestión académica y administrativa. Nuestra aplicación atiende directamente esta demanda, ofreciendo una solución que reduce la sobrecarga de tareas administrativas y facilita la atención a las necesidades individuales de cada estudiante.

Diseñada para hacer el día a día de los profesores más manejable, nuestra plataforma permite un registro eficiente y detallado de calificaciones y asistencia, así como el seguimiento del bienestar psicológico de los estudiantes. Por otro lado, ofrece herramientas para una gestión integral de la infraestructura escolar, abarcando desde el mantenimiento de equipos hasta la optimización del uso de aulas, incluyendo el monitoreo de seguridad. Además, integra un sistema de inventario para útiles escolares y una base de datos para materiales de clase, asegurando que los recursos necesarios estén siempre al alcance.

Misión: Empoderar a las instituciones educativas con una herramienta que aligera la carga administrativa del personal, mejora la gestión académica y promueve un ambiente educativo saludable y productivo.

Visión: Convertirnos en el aliado indispensable para educadores y administrativos, proporcionando la solución definitiva para una gestión educativa eficiente que mejore la experiencia de enseñanza y aprendizaje.

1\.1.2. Perfiles de integrantes del equipo![](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.002.png)

***Ayquipa Ubaldo Abraham Israel - U202218475***

Soy estudiante de la carrera de ingeniería de software, actualmente cursando el 5to ciclo de carrera. Aunque soy fullstack developer, tengo más inclinación por el desarrollo frontend. Mi stack arranca con Next.js(Framework de React) + Typescript para el front y Node.js + Express.js + MongoDB para el back. Como todo buen programador, me considero un eterno estudiante, por lo que me encuentro en este momento estudiando Docker y Redis.

`  	`***Mayurí Armas, Jose Carlo - U202011437![](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.003.jpeg)***

Mi nombre es Jose, tengo 20 años. Elegí esta carrera ya que desde pequeño me fascinaba la tecnología y los diseños tanto de app, web, etc. Además, considero que tengo buenas habilidades para trabajar en grupo. Entre mis principales habilidades se encuentra la capacidad de guardar información, la empatía, el ser resiliente y tengo conocimiento en los lenguajes de C++,C#, python,JS,Kotlin y en frameworks como vue y angular.

***Vargas Revollé, Ariana - U200221A928![](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.004.jpeg)***

Soy estudiante de la carrera de Ingeniería de Software cursando actualmente el 5to ciclo. Me interesa el rubro de ciberseguridad y me gusta leer sobre nuevas tecnologías y su impacto en la vida de las personas. Me gusta trabajar en equipo y aprender de otras personas. Conocimientos en HTML, CSS, C++, Python, SQL y MongoDB, JavaScript y familiar con los ambientes de POO, Lean UX, Agile Frameworks y Máquinas Virtuales

![](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.005.jpeg)

`	`***Vilchez Rios, Mateo Alejandro - U202210059***

Soy estudiante de la carrera de Ingeniería de Software cursando actualmente el 5to ciclo. Me considero una persona eficiente, disciplinada y responsable. Poseo conocimientos básicos en C++, Java y JavaScript. Manejo de Base de Datos relacionales. Me comprometo a brindar todo el apoyo necesario para cumplir con todos los requerimientos.

***Ramos Rios, Belén del Rocio- U202216246![](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.006.png)***

Actualmente estoy cursando el quinto ciclo de la carrera de Ingeniería de Software, etapa que ha reforzado mi sentido de responsabilidad y mi capacidad para colaborar eficazmente en equipo. Además de mis habilidades interpersonales, poseo conocimiento en lenguajes de programación como JavaScript (JS), C++, y SQL Estoy siempre en busca de nuevas oportunidades de aprendizaje que me permitan expandir mis conocimientos y contribuir de manera significativa en cualquier proyecto en el que participe.

1\.2. Solution Profile 
#### <a name="_30j0zll"></a>**1.2.1 Antecedentes y problemática** 

**Antecedentes**

En el ámbito educativo actual, las instituciones enfrentan una creciente complejidad operativa y pedagógica, agravada por la sobrecarga de tareas administrativas y el desafío de atender las necesidades individuales de cada estudiante. Este escenario exige una gestión eficiente que no solo aborde los aspectos académicos sino también la infraestructura, el bienestar de los estudiantes, y la optimización de recursos.

Tradicionalmente, la falta de herramientas integradas ha resultado en procesos ineficientes y una gestión fragmentada, lo que impacta negativamente en la calidad de la educación y en el ambiente laboral de los profesores y administrativos.

**Problemática**

La necesidad de simplificar la gestión académica y administrativa en las instituciones educativas es evidente. Los procesos manuales o sistemas desarticulados conducen a una gestión ineficaz, sobrecarga de trabajo para el personal, y un seguimiento insuficiente del progreso y bienestar de los estudiantes. Esto no solo afecta la calidad de la educación sino que también genera un ambiente laboral estresante y poco productivo para profesores y administrativos. La falta de una solución integral que abarque desde la gestión de calificaciones y asistencia hasta la infraestructura escolar y el bienestar estudiantil limita significativamente la capacidad de las instituciones para ofrecer una educación de calidad y un ambiente saludable y productivo. 

La aplicación que proponemos aborda directamente estos desafíos al ofrecer una solución integrada para la gestión académica y administrativa, permitiendo un registro eficiente de calificaciones y asistencia, así como un seguimiento proactivo del bienestar psicológico de los estudiantes.

- Who?

¿Quiénes enfrentan desafíos en la gestión académica y administrativa?

Los profesores y personal administrativo de instituciones educativas que lidian con procesos manuales o sistemas desarticulados.

- What? 

¿Qué aspectos de la gestión educativa se buscan mejorar con nuestra solución?

La eficiencia en el registro de calificaciones y asistencia, el seguimiento del bienestar de los estudiantes, y la gestión integral de la infraestructura escolar.

- Where?

¿Dónde se implementará esta solución para abordar la problemática?

En instituciones educativas de todo nivel y tamaño, buscando una cobertura geográfica amplia.

- When? 

¿Cuándo es el momento ideal para implementar nuestra solución en las instituciones educativas?

Tan pronto como las instituciones identifiquen la necesidad de mejorar su gestión educativa y estén dispuestas a adoptar tecnología innovadora.

- Why?

¿Por qué es crítica la necesidad de una solución como la nuestra en el contexto educativo actual?

Debido a la creciente complejidad y las demandas de un entorno educativo moderno que requiere atención personalizada y eficiencia administrativa.

- How? 

¿Cómo facilita nuestra solución la gestión académica y administrativa de las instituciones educativas?

Mediante una plataforma integrada que automatiza y optimiza los procesos, desde el seguimiento académico hasta la gestión de recursos, aliviando la carga administrativa y promoviendo un enfoque más centrado en el estudiante.

- How Much? 

La gestión eficiente de los recursos académicos y administrativos es crucial para el éxito de las instituciones educativas. Este estudio propone analizar cómo una aplicación integral de gestión académica puede transformar la operatividad de dichas instituciones, mejorando la comunicación, optimizando la gestión del tiempo y recursos, potenciando el seguimiento y evaluación del rendimiento estudiantil.


"Enhancing Efficiency in Education through Learning Management Systems: A Case Study of the Blackboard System" por Smith, John y Doe, Jane. Este artículo de investigación examina cómo un sistema de gestión del aprendizaje específico, Blackboard, puede aumentar la eficiencia y facilitar la gestión del aprendizaje para profesores y administradores en una universidad. El estudio presenta datos sobre la reducción de tiempo en tareas administrativas y la mejora en la distribución de materiales de curso.

#### <a name="_1fob9te"></a>**1.2.2 Lean UX Process**

### <a name="_3znysh7"></a>**1.2.2.1. Lean UX Problem Statements**  

Nuestra aplicación ofrece soporte en la gestión del bienestar y rendimiento de los estudiantes y en los procesos administrativos de las instituciones educativas de educación básica.

Hemos observado que los factores principales que afectan a las escuelas son la dificultad que tienen para registrar y acceder a información fundamental sobre el mantenimiento de los equipos e infraestructura, capacidad de aforo en las instalaciones y el monitoreo de los escolares. Esto causa un empleo ineficaz del tiempo y del personal de la institución, lo cual resulta un proceso de la toma de decisiones poco eficiente.

¿Cómo podemos mejorar los procesos administrativos y de gestión estudiantil para que los colegios tengan más éxito basándonos en el tiempo y la cantidad de personal empleado en el proceso de la toma de decisiones?

**1.2.2.2. Lean UX Assumptions**

**Business Assumptions:**

1\. Creo que mis clientes necesitan optimizar los procesos administrativos y de gestión estudiantil.

2\. Estas necesidades se pueden resolver con una aplicación que ofrezca soporte en la gestión del bienestar  y rendimiento de los estudiantes, así como los procesos administrativos de las instituciones educativas.

3\. Mis clientes iniciales serán instituciones educativas públicas y privadas de educación básica.

4\. El valor #1 que un cliente quiere obtener de mi servicio es el soporte inmediato y eficaz en los procesos administrativos y de gestión estudiantil.

5\. El cliente también puede obtener beneficios adicionales como la mejora de la supervisión de los estudiantes y el uso óptimo de la capacidad en las instalaciones.

6\. Voy a adquirir la mayoría de mis clientes a través de estrategias de marketing a través de email y redes sociales.

7\. Voy a ganar dinero mediante un modelo de suscripción.

8\. Mi competencia principal en el mercado será aplicaciones con funcionalidades similares enfocadas en el sector educativo.

9\. Los venceremos debido a que nuestra aplicación se enfoca en optimizar los recursos de tiempo y personal mediante el soporte de procesos administrativos únicamente del sector educativo.

10\. Mi mayor riesgo es la resistencia al uso de nuevas tecnologías por parte de las instituciones educativas.

11\. Resolveremos esto mediante servicios de capacitación y una interfaz intuitiva para el usuario.

**User Assumptions:**

¿Quién es el usuario?

El usuario es principalmente el personal administrativo y docente de instituciones educativas de educación básica, como directores, secretarios, maestros y personal de apoyo.

¿Dónde encaja nuestro producto en su trabajo o vida?

Nuestro producto se integra en su vida laboral al proporcionar una herramienta centralizada para gestionar eficientemente los procesos administrativos y de gestión estudiantil en la escuela. Ayuda a simplificar tareas como el seguimiento de mantenimiento, la gestión de la capacidad de las instalaciones y el monitoreo del rendimiento de los estudiantes.

¿Qué problemas resuelve nuestro producto?

Nuestro producto resuelve problemas de ineficiencia en la gestión escolar al facilitar el acceso y la gestión de información relevante. Aborda la dificultad para registrar y acceder a datos sobre mantenimiento, capacidad y rendimiento estudiantil, lo que permite una toma de decisiones más informada y eficiente.

¿Cuándo y cómo se utiliza nuestro producto?

Nuestro producto se utiliza de manera regular durante la jornada laboral en la escuela, tanto por el personal administrativo para gestionar datos y realizar informes, como por los maestros para acceder a información sobre el rendimiento de los estudiantes y planificar sus actividades educativas.

¿Qué características son importantes?

Las características importantes incluyen un diseño intuitivo y fácil de usar, capacidad de personalización para adaptarse a las necesidades específicas de cada institución educativa, acceso rápido a información relevante sobre mantenimiento, capacidad y rendimiento estudiantil.

¿Cómo debería lucir y comportarse nuestro producto?

Nuestro producto debe tener una apariencia limpia y profesional, con una interfaz de usuario intuitiva que permita una navegación fácil y rápida. Debe comportarse de manera ágil y eficiente, ofreciendo respuestas rápidas y confiables a las consultas y acciones del usuario. Además, debe ofrecer notificaciones y alertas pertinentes para mantener a los usuarios informados sobre cambios importantes o eventos relevantes en la escuela.

**Business Outcomes:**

Aumento en la Retención de Clientes: 

Observaremos una mayor retención de clientes a largo plazo, lo que se refleja en una disminución de la tasa de abandono del producto y un aumento en los ingresos recurrentes.

Mejora en la reputación y confianza:

Observaremos una mejora en la confianza y la percepción de las instituciones educativas en el mercado hacia nuestro startup, reflejado en el aumento de suscripciones con una validez de 1 año.

Aumento en los ingresos:

Veremos un aumento en los ingresos debido al aumento de suscripciones a nuestra aplicación.

Mayor visibilidad en el mercado:

Observaremos que tenemos una mayor visibilidad en el mercado, lo que se refleja en la cantidad de instituciones que solicitan información y pruebas de la aplicación.

**User Outcomes:**

Mayor Eficiencia en el Trabajo:

Los usuarios podrán completar tareas administrativas y de gestión estudiantil de manera más eficiente, lo que les permitirá dedicar más tiempo a actividades educativas y estratégicas.

Toma de Decisiones Informada:

Los usuarios tendrán acceso rápido y fácil a información relevante sobre mantenimiento, capacidad y rendimiento estudiantil, lo que les permitirá tomar decisiones informadas y basadas en datos.

Reducción del Estrés Laboral:

Los usuarios experimentarán una reducción en el estrés relacionado con la gestión escolar al utilizar una plataforma intuitiva que simplifica sus tareas diarias y les brinda mayor control sobre los procesos.

Satisfacción Personal y Laboral:

Los usuarios experimentarán una mayor satisfacción personal y laboral al ver cómo nuestra solución mejora la eficiencia y efectividad de su trabajo, lo que podría conducir a una mayor motivación y compromiso con su labor educativa.

**Features:**

La implementación de un sistema de gestión de información centralizado y fácil de usar será valorado por los usuarios, ya que mejorará significativamente la accesibilidad y la eficiencia en la recuperación de datos relevantes sobre mantenimiento, capacidad y rendimiento estudiantil.

La creación de paneles de control personalizables será apreciada por los usuarios, ya que les permitirá visualizar y analizar rápidamente la información clave para la toma de decisiones, adaptándose a sus necesidades específicas y preferencias de presentación de datos.

La capacidad de personalización del sistema será un aspecto importante para los usuarios, ya que les permitirá adaptar la plataforma a las particularidades de su institución educativa y a sus propios flujos de trabajo, mejorando así la utilidad y la satisfacción general del producto.

La inclusión de herramientas de seguimiento de la asistencia y el comportamiento de los estudiantes será apreciada por los usuarios, ya que les ayudará a identificar tendencias y patrones relevantes para la intervención temprana y el apoyo personalizado a los estudiantes.

**1.2.2.3. Lean UX Hypothesis Statements**

**Hypothesis 1: Business outcomes.**

Creemos que, mejorando el acceso y la eficiencia en el seguimiento de mantenimiento, capacidad y rendimiento estudiantil, para el uso del personal administrativo y profesores de los colegios, nosotros lograremos obtener una mayor tasa de retención y aceptación por parte de las instituciones. Sabremos que es verdad cuando veamos un incremento en la cantidad de suscripciones y observemos que estas se mantienen activas al pasar los meses.

` `**Hypothesis 2:** **User outcomes.**

Creemos que, ofreciendo funcionalidades enfocadas en el soporte de los procesos necesarios para la gestión del bienestar y rendimiento del alumno y de la infraestructura del colegio, para el uso del personal administrativo y los profesores, nosotros lograremos que nuestros usuarios aumenten su productividad y motivación. Sabremos que es verdad cuando veamos reflejado en las encuestas hacia el personal un aumento de bienestar y satisfacción.

**Hypothesis 3: Business Assumption.**

Creemos que al ofrecer soporte inmediato y eficaz en los procesos administrativos y de gestión estudiantil, nosotros lograremos cubrir la necesidad principal de nuestros usuarios. Sabremos que es cierto cuando veamos que el 20% de los clientes que usen la prueba gratis se unen al plan de suscripción durante un periodo mínimo de 12 meses.

**Hypothesis 4: User Assumptions.**

Creemos que implementando una interfaz intuitiva y simple para el personal administrativo y profesores. Nosotros lograremos que los usuarios puedan registrar y acceder a datos sobre mantenimiento, capacidad y rendimiento estudiantil de forma rápida y eficaz. Sabremos que hemos tenido éxito  cuando se vea una disminución en la cantidad de personal y tiempo que requiere para realizar un procedimiento relacionado a la gestión estudiantil y de la infraestructura.

**Hypothesis 5: Features.**

Creemos que al ofrecer características altamente personalizables que cubren directamente las necesidades del personal administrativo y los profesores en la gestión escolar, lograremos una mayor aceptación y uso del producto. Sabremos que es cierto cuando veamos un aumento en la frecuencia de uso de las características recientemente implementadas y cuando los usuarios expresen su satisfacción con la capacidad de personalización de la aplicación.

**1.2.2.4. Lean UX Canvas**

![](Aspose.Words.d1f5ab46-661c-414c-831c-da9787db4499.007.png)

**Link del Lean UX Canvas: [https://miro.com/welcomeonboard/NEdsWTNwa0FKdWVGUmlFUEJ6R3dldkpBRHNxRmNIeEdhNWVDNHhoRnBlZENuSElYbm1hN3JjNFNwOUJpdUIzWHwzNDU4NzY0NTIzMzkyNDUwNjk1fDI=?share_link_id=776423401253**](https://miro.com/welcomeonboard/NEdsWTNwa0FKdWVGUmlFUEJ6R3dldkpBRHNxRmNIeEdhNWVDNHhoRnBlZENuSElYbm1hN3JjNFNwOUJpdUIzWHwzNDU4NzY0NTIzMzkyNDUwNjk1fDI=?share_link_id=776423401253)**
## <a name="_2et92p0"></a>**1.3. Segmentos objetivo**

**Segmento objetivo #1: Profesores**

Aspectos demográficos:

- Sexo: Masculino y femenino.
- Edad: 30-60 años.
- Estado civil: Variado.
- Tamaño de la familia: Diverso, desde individuos solos hasta familias grandes.

Aspectos geográficos:

- Ubicación: Principalmente en ciudades con universidades y colegios.

Aspectos psicográficos:

- Valores: Alta valoración de la educación continua y el desarrollo profesional.
- Intereses: Fuerte interés en tecnologías y plataformas que faciliten la enseñanza y la investigación.
- Comportamiento: Compromiso con la calidad educativa y la mentoría estudiantil. Buscan constantemente mejorar la experiencia de aprendizaje y mantenerse actualizados en su campo.

**Segmento objetivo #2: Equipo Administrativo**

Aspectos demográficos:

- Sexo: Masculino y femenino.
- Edad: 25-55 años.
- Estado civil: Variado.
- Tamaño de la familia:  Diverso, desde individuos solos hasta familias grandes.

Aspectos geográficos:

- Ubicación: Mayormente ubicados en ciudades o áreas suburbanas.

Aspectos psicográficos:

- Valores: Importancia a la eficiencia, organización y optimización de procesos.
- Intereses: Altamente interesados en sistemas y software que simplifiquen la gestión administrativa y académica, reduciendo la carga de trabajo manual y automatizando procesos rutinarios.
- Comportamiento: El equipo administrativo busca optimizar procesos administrativos y la infraestructura educativa, valorando soluciones que les liberen tiempo para enfocarse en tareas estratégicas. Prefieren herramientas intuitivas, confiables y que faciliten la toma de decisiones a través de reportes detallados.
