<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>INGENIERÍA DE SISTEMAS DE SOFTWARE</strong><br>
    <strong> SI720 Aplicaciones Web - WX54</strong><br>
    <strong>Profesor:  Alex Humberto Sánchez Ponce </strong><br>
    <br>INFORME <br>
    "Yielding Efficient Software Implementations" | "AidManager"
</p>


### Integrantes:
- Peña Rivera, Manuel Sebastian - U202210138
- Ramírez Hoffmann, Sebastián - U202211894
- Rodriguez Vargas, Arian Martin - U202212096
- Esteban Garcia, Nicolas Sebastián - U202217485
- Herrera Aguirre, Fabia Alejandra - U202219422   

---
# Registro de Versiones del Informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 1.0 | 14/04/2024 |Grupo 1 | Informe |

# Project Report Collaboration Insights
[URL de la organización](https://github.com/AplicacionesWeb-WX54)
[URL del repositorio](https://github.com/AplicacionesWeb-WX54/si730-WX54-Grupo1-Repository.git)
[URL de la Landing Page](https://github.com/AplicacionesWeb-WX54/LandingPage-AidManager)

# Student Outcome 3

|Criterio Especifico| Acciones Realizadas                                                                                                                                                                                |Conclusiones|
|-|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-|
|Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.| Nicolas Esteban:<br> **TB1:** Durante el proyecto, adquirí habilidades para transmitir conceptos complejos de manera comprensible a diversos grupos, lo que aumentó notablemente la colaboración y el compromiso con nuestra labor. Este proceso subrayó la relevancia de ajustar mi comunicación según el entorno, una lección de gran valor para mi desarrollo profesional futuro. <br><br>Arian Rodriguez Vargas:<br>**TB1**: Durante la ejecución del proyecto, conseguí transmitir de manera eficiente tanto los resultados como el proceso seguido, empleando Lean UX como enfoque principal. Además, compartí los descubrimientos fundamentales derivados de nuestra investigación en experiencia de usuario (UX).<br><br>Sebastian Ramirez Hoofman:<br>**TB1**: Cumplí eficazmente con las responsabilidades asignadas, respetando los horarios, normativas y plazos acordados por el equipo. <br><br>Sebastian Manuel Peña Rivera:<br>**TB1**: Durante la realización del proyecto, logré expresar de manera clara todas mis ideas durante las reuniones de equipo. Además, llevé a cabo una entrevista con un usuario potencial, donde expliqué el propósito de la misma y la información que necesitaba recopilar.<br><br>Fabia Alejandra, Herrera Aguirre:<br>**TB1**: A lo largo del proyecto, progresé satisfactoriamente en las responsabilidades asignadas y fortalecí habilidades interpersonales como la comunicación dentro del equipo. Además, obtuve una comprensión más sólida del proceso a seguir, lo que permitió su enfoque desde diversas perspectivas para una mejor posicionamiento.|Gracias a la eficiencia y la organización que mantuvimos, respaldadas por un sólido marco de trabajo establecido dentro del grupo, alcanzamos nuestro objetivo de desarrollar el primer entregable de manera precisa y oportuna. La colaboración efectiva, la comunicación clara y el compromiso compartido con los plazos establecidos fueron pilares clave en nuestro éxito|
|Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería..| Nicolas Esteban:<br> **TB1:** En mi participación en el proyecto, me dediqué a comunicar mis ideas y los resultados obtenidos de manera clara y objetiva. Desde la elaboración de informes hasta la realización de presentaciones, mi objetivo fue hacer que la información fuera accesible y comprensible para todos los involucrados.  <br><br> Arian Rodriguez Vargas<br>**TB1:** A lo largo de este proyecto, me encargué de documentar de manera adecuada el emprendimiento, utilizando las herramientas pertinentes y siguiendo las convenciones de idioma, estructura de nombres y prácticas de programación establecidas en los aspectos de la solución. Además, realicé y documenté minuciosamente los procesos de Lean UX, diseño, prototipado, entre otros, con el objetivo de lograr una comunicación efectiva con una amplia gama de audiencias.<br><br>Sebastian Ramirez Hoffman:<br>**TB1**: Utilizando herramientas colaborativas en línea, pude mejorar mi capacidad de comunicación y colaboración en equipo de manera significativa. Estas plataformas facilitaron la interacción y el intercambio de ideas entre los miembros del equipo, lo que contribuyó a un ambiente de trabajo más eficiente y productivo.<br><br>Sebastian Manuel, Peña Rivera:<br>**TB1**: En esta fase del proyecto, me dediqué a elaborar el análisis de requisitos de manera detallada, lo que sentó las bases para el desarrollo posterior. Luego, me enfoqué en la creación de la base de datos del sistema y en la construcción del diagrama de clases, asegurándome de que ambos elementos estuvieran alineados con los requerimientos identificados y contribuyeran a la solidez y funcionalidad del proyecto en su conjunto.<br><br>Fabia Herrera, Alejandra Aguirre:<br>**TB1:** La investigación realizada para este proyecto fue exhaustivamente documentada y resultó fundamental para el modelado de nuestra solución. En esta fase, mi responsabilidad fue investigar sobre posibles competidores, lo que nos proporcionó información valiosa para aprender de sus errores y aciertos, ayudándonos así a mejorar nuestra estrategia y diseño.                                                                                                                                                                                                       |Gracias a las herramientas colaborativas brindadas y las aplicaciones de comunicación logramos establecer fechas y límites para nuestros trabajos y de esta manera mantenernos informados sobre el progreso de los demas miembros del equipo.|

# Contenido

[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo]()  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)    
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

[2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)

[3.2. User Stories](#32-user-stories)

[3.3. Impact Mapping](#33-impact-mapping)

[3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Product Desig](#capítulo-iv-product-design)

[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)   
[4.2.5. Navigation Systems](#425-navigation-systems)

[4.3. Landing Page UI Design](#43-landing-page-ui-design)   
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)

[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
[4.4.3. Web Applications Mock-ups](#442-web-applications-mock-ups)   
[4.4.4. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)

[4.5. Web Applications Prototyping](#45-web-applications-prototyping)

[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)

[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams](#471-class-diagrams)  
[4.7.2. Class Dictionary](#472-class-dictionary)

[4.8. Database Design](#48-database-design)  
[4.8.1. Database Diagram](#481-database-diagram)

[Capítulo V: Product Implementation, Validation & Deploymen](#capítulo-v-product-implementation-validation--deployment)

[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)

[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
[5.2.X. Sprint ](#52x-sprint-n)  
[5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)  
[5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)  
[5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)  
[5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)  
[5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)  
[5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)  
[5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)  
[5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)

[5.3. Validation Interviews](#53-validation-interviews)  
[5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)

[5.4. Video About-the-Product](#54-video-about-the-product)

[Conclusiones](#conclusiones)

[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

[Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Nuestra startup **AidManager** se basa en una herramienta enfocada en gestionar los proyectos de ONG, esto se hara al recibir informacion de los mismos asistentes asignados al evento y por medio de nosotros se hara un analisis intensivo en oportunidades de mejora, reportes de inventario, asistentes del eveto entre otros. Adicionalmente la herramienta servira para planificar futuros eventos usando la misma informacion previamente registrada. 

#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-| 
|Ramírez Hoffmann, Sebastián  <img src="https://avatars.githubusercontent.com/u/129230632?v=4" alt="Imagen del compañero" style="width:60%">|U20221894|Ingenieria de software|C++, Python, Js, Reactjs, NodeJs, expressjs, MongoDB, SQL.  Paciencia, Liderazgo, Logico|
|Rodriguez Vargas, Arian Martin <img src="../assets/members-profile/arigeimpleis.jpg" alt="Imagen del compañero" style="width:60%">|U202212096|Ingenieria de software|C++, Python, persistente y amigable|
|Esteban Garcia, Nicolas Sebastian <img src="../assets/members-profile/nekolas-profile.png" alt="Imagen del compañero" style="width:60%">|U202217485|Ingenieria de software|HTML, CSS Y JS. Sociable.|
|Herrera Aguirre, Fabia Alejandra 	<img src="../assets/members-profile/pelufoto.png" alt="Imagen del compañero" style="width:60%">|U202219422|Ingenieria de software|C++, Python. Creativa.|
|Peña Rivera, Manuel Sebastian	<img src="../assets/members-profile/Manuel.jpg" alt="Imagen del compañero" style="width:60%">|U202210138|Ingenieria de software|C++, Python, MongoDB, SQL, Assembler. Responsabilidad y Buena Comunicación| 

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

Segun la Oficina de Naciones Unidas para la Coordinación de Asuntos Humanitarios (OCHA) en 2023 se reportaron 801,425 personas en necesidades de alimentacion, servicios de agua, saneamiento e higiene.
En el Peru existen 978 Organizaciones privadas sin fines de lucro de las cuales principalmente 428 se han categorizado como de salud, 19 de educacion y 35 de vivienda (SIGCTI, 2024), esto nos demuestra que existe un alto rango de organizaciones privadas sin fines de lucro. No obstante cuando buscamos organizaciones ONDG(Organizaciones No Gubernamentales de Desarollo) encontramos un total de 1835 (SIGCTI, 2024). Aun con muchas instituciones el alcance que se logra resulta ser preocupante, en la encuesta que se realizo por equillibrium CenDE en 2023 de entre casi 1,200 personas un 80% de estas reconocia que es una ONG no obstante 71% o no sabia o no conocia iniciativas realizadas por las ONGs en ese año, en esta misma encuesta solo un 7% no tenia interes alguno en participar en el abordamiento de problemas publicos ni socialmente es decir un 93% de las 1,200 estaban dispuestas a apoyar. Adicionalmente cuando estas mismas ONG reciben grandes cantidades de datos normalmente solo son para obtener una cifra que represente los asistentes a algun evento o cuanto se logro de un objetivo de donacion omitiendo lo enriquecedor de esta data recolectada, como se menciona en el articulo "Data Analytics for Nonprofits" (DigitalForNonprofits, 2023), en el mundo de hoy para realizar acciones estrategicas y maximisar recursos distintas empresas utilizan lo llamado analisis de datos, esta practica se puede aplicar a un modelo de negocios sin fines de lucro como las ONG donde se consiguen los mismos beneficios que brindan los analisis de datos.

Es aqui donde nosotros ideamos la propuesta de **AidManager**, es una aplicacion web que se basa en una herramienta de gestion utilizada por los encargados de gestionar el proyecto y los asistentes del proyecto haciendo uso de su informacion recopilada por medio de nosotros quienes por nuestro servicio de analisis de datos y gestion de proyectos le proporcionaremos oportunidades de mejora, graficas relevantes respecto a la data y recomendaciones en como pueden implementar una recolecion de datos mas efectiva para amplificar el impacto deseado, de misma manera de que se presentaran espacios donde el gestor pueda planificar su siguiente proyecto facilitando el seguimiento de este mismo y haciendo un registro mas efficiente. 

What (¿Que se está haciendo?): Se facilita el proceso de planeacion para actividades orientadas al apoyo social y donacion de bienes. Asimismo se proporciona un servicio de gestion avanzado para las ONG con el objetivo de aumentar el impacto de estas.

Why (¿Porque se está haciendo?): Se hace esta aplicacion web con el objetivo de darle una herramienta a las ONG para aumentar la eficiencia de sus proyectos de ayuda social proporcionando adicionalmente una plataforma donde sus mismos ayudantes puedan recopilar la informacion de manera efectiva.

When (¿Cuándo se usa?): Se usa cuando se tengan los datos recopilados del proyecto mas reciente y se busque ver las oportunidades de mejora e ideas para la eficacia de un siguiente proyecto en un formato visual que sea facil de entender. Asi como tambien se hara uso de la herramienta cuando este proyecto este en ejecucion donde los asistentes del mismo recopilaran los datos para que consecuentemente el supervisor asignado a gestionar del proyecto pueda observar las oportunidades de mejora.

Where (¿Dónde se usa?): El uso esta diseñado para Perú ya que se recompilara informacion de ONG's que esten actuando en este pais, de esta manera se podran hacer recomendaciones mas locales. Asimismo esta App Web se puede usar facilmente desde el telefono o escritorio.

Who (¿Quién lo usa?): El usuario principal para nosotros son los supervisores y ayudantes de las ONG ya que son estos los mismos que nos proporcionaran los datos recopilados para mejorar su impacto y requieren de una mejor organizacion, nuestro usuario principal entonces se divide en el segmento de supervisor / gerente y el ayudante / recolector de data.

How Much (¿Cuánto costaría?): La aplicacion web tendra sus funcionalidades core a medio de pago es decir el proceso de gestion recopilacion y refinamiento de datos junto con las mejores oportunidades de mejora para estas. Tanto el core de la app web como la subscripcion se tendran que renovar cada cierto tiempo donde las organizaciones se tendran que escoger un plan anual o mensual.

How (¿Cómo se lleva al cabo?)

Se hara un proceso de inscripcion y seguidamente se les presentara con la oportunidad de crear o importar un proyecto
seguidamente solicitara los datos recopilados de su proyecto mas reciente, de estos datos se mostraran graficos representando la demografica, gastos, junto con explicaciones, recomendaciones y oportunidades de mejora. Asimismo se proporcionara la herramienta para gestionar futuros proyectos la cual se podra usar de manera opcional para poder estructurar mejor los encargados, el presupuesto y objetivos del siguiente proyecto. Cuando se inicie un proyecto se dependera de los ayudantes de estos eventos a que recopilen la informacion de los usuarios por medio de nuestro aplicativo web, donde tendran que registrarse y coleccionar la data de los participantes a eventos.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
Se identifica una falta de organizacion por parte de las ONG donde existen distintas oportunidades para mejorar el alcance con una buena planificacion. No obstante, muchas organizaciones no tienen conocimiento del potencial que se puede obtener de esta informacion o no cuentan con un equipo dedicado al analisis de datos a niveles de Big Data o formas efectivas de recolectar esta misma informacion. Asimismo hemos identificado que existen diferentes factores los cuales llevan a un usuario interesado en una ONG a no tener motivos suficientes para participar de actividades sociales o de hacer donativos a estas mismas, una de estas siendo la falta de informacion y la carencia de visibilidad que estan tienen siendo que aun asi habiendo mas de 1000 ONG's en el Perú no se conocen muchas de estas ni de como poder ayudarlas. Frente a esta problematica nos planteamos la siguiente pregunta:
¿Como facilitamos el proceso de gestion de un proyecto de ayuda social para aumentar el flujo de participantes en las actividades que ofrecen las distintas ONG's a la poblacion de nuestro país de manera eficiente?
#### 1.2.2.2. Lean UX Assumptions.

Después de analizar la problemática y los factores que la ocasionan, podemos tener un panorama de cómo solucionar la necesidad del usuario declarando supuestos, lo cual corresponde al siguiente paso de la Lean UX. Por ello, es necesario tener un conocimiento previo de las empresas que tienen características similares a las nuestras y cómo estas se han desarrollado con el paso del tiempo. 

Se mencionan a tres potenciales competidores:

CauseVox:
Plataforma que facilita el crowdfunding no solo de bienes monetarios, sino también de recursos como víveres y vestimenta. Plataforma de recaudación de fondos que brinda herramientas necesarias para crear campañas llamativas para cumplir su meta de donación. su diversificacion de bienes junto con sus campañas muestran su capacidad para ser competidores.

Donadora:
Es una plataforma mexicana en la que se pueden financiar proyectos de caridad, así como proyectos de tipo artístico, científico, entre otros. Al entrar en la financiacion para diferentes proyectos fuera de la caridad presenta una aptidud para ser competidor.

Logalto:
Es un Programa web colaborativo para el monitoreo y la evaluación de proyectos de desarrollo internacional la cual proporciona una alta gama de herramientas de gestion de proyectos.

|Business Assumptions|User Assumptions|
|-|-|
|Creemos que nuestros usuarios tienen la necesidad de aumentar el flujo de personas a sus eventos y facilitar la creasion de estos gestionando sus datos y proyectos de manera efectiva. |Los usuarios de este producto son el personal encargado de gestion de proyecto y los ayudantes que participan de estos eventos de Organizaciones no gubernamentales. |
|Este problema se puede solucionar con una plataforma donde se pueda organizar y supervizar proyectos donde se pueda generar un analisis de datos con recomendaciones y oportunidedes de mejora con infromacion recoleccionada por los mismos ayudantes de estos eventos. Ademas de que se presente toda la informacion necesaria para un proceso de inscripcion o donacion |Nuestro producto encajaría en la vida cotidiana debido a que sera accesible, economicamente viable y facil de utilizar tanto para las personas que tengan que supervizar el proyecto como para los mismos ayudantes para la recoleccion de datos |
|Los usuarios iniciales Organizaciones no gubernamentales sin fines de lucro que deseen mejorar su impacto y alcance.  |Este producto resolverá la necesidad de gestionar proyectos mientras que se recopila y analiza informacion de manera efectiva, simple y facil de entender para tener mayores oportunidades de mejora. |
|El valor #1 de nuestro servicio es el analisis de datos comprensible, el registro de informacion relevante y la interfaz amigable y simple de usar. |El producto se utilizará al momento que se tenga que realizar un nuevo proyecto de ayuda social y se deba realizar un planeamiento.|
|El aplicativo adicionalmente contara con el sistema de registro de ayudantes y gerentes que tendran un limite segun los distintos planes que tenemos para las ONG de distintos tamaños |Las funciones mas importantes son, la capacidad de manejar y presentar los datos de manera que sean visualmente coherentes y poco abrumadores. La planificacion de proyectos haciendo un registrod de todo lo necesario para que se pueda ejecutar. Y finalmente, una interfaz facil de usar para tanto el ayudante como para el gestor del proyecto|
|Se conseguirán la mayoría de los usuarios por medio de marketing digital (como las redes sociales) y Noticieros. |Nuestro producto debe verse como una herramienta de gestion y analisis de datos. Asimismo siendo una herramienta que se usa para planificar proyectos de ayuda benefica de alta calidad y monitoreo |
|Conseguiremos ingresos de la aplicación por medio de la compra del servicio para las ONG y los distintos planes proporcionales al tamaño de las necesidades de la organizacion.||
|Nuestros competidores principales serán CauseVox, Donadora y Logalto. ||
|Los venceremos al tener una mejor interactividad y experiencia de usuario, una herramienta de gestion para proyectos futuros simple de entender y el proceso amigable y facil de utilizar para adquirir la informacion. ||
|El mayor riesgo del producto es la falta de alcance inicial, la capacidad de datos, la precicion de datos y la competencia. ||
|Solucionaremos esto por medio de campañas de publicidad, contactar a las ONG y dandoles a los recolectores las pautas a seguir para reducir el margen de error.||
|Pensamos que un assumption que si se prueba falso puede causar que el proyecto falle es la demanda actual de nuestro producto y la necesidad estimada.||

#### 1.2.2.3. Lean UX Hypothesis Statements.
- Creemos que, al brindar una interfaz poco compleja de usar para nuestros usuarios, podrán tener una mejor experiencia al gestionar sus datos y  proyectos de ayuda social.
  Sabremos que hemos tenido éxito cuando se incremente la cantidad de proyectos efectivos por parte de las ONG que usen nuestra herramienta. 

- Creemos que la aplicación facilitara la gestion y creacion de proyectos de ayuda social proporcionando mejores resultados y un mayor flujo de personas participando de estas actividades.  
  Sabremos que tuvimos exito cuando distintos proyectos de ONG reciban mas relevancia y participantes.

- Creemos que ayudar a las ONG a tener una mejor gestion y planeamiento en sus proyectos ayudara a mejorar la visibilidad y aumentar la cantidad de personas motivadas a participar.
  Sabremos que hemos tenido éxito, cuando a nivel nacional se empiece a notar un incremento en la ayuda social proporcionada. 

#### 1.2.2.4. Lean UX Canvas.
|-|-|-|
|-|-|-|
| Business Problem <br>¿Qué problema has identificado que necesitas resolver? Las ONG estan perdiendo conexion y requieren optimizar sus proyectos para mejorar su impacto. <br>Según CenDe de 1200 personas 72% de estas no han participado en alguna actividad de actividad de ayuda social.<br> Segun "Digital for non Profits" 78% de organizaciones nonprofit con capacidades analiticas tienen mejoras tales como mejora de reclutamiento, mejoras en el alcance y hacer seguimiento de presupuestos| Solution ideas <br>Herramienta de gestion de proyectos recopilando datos y recomendaciones de accion.<br><br>Ofrecer planes de pago a las para ONG cuyos proyectos tienen diferentes cantidades de personas.<br><br>Mejorar y optimizar los procesos de recoleccion de datos para un analisis mas exacto. | Business Outcomes <br>(Cambios en el comportamiento del usuario) <br>¿Qué cambios en el comportamiento del usuario indicarán que has solucionado un problema real de manera que añada valor a tus clientes? <br> El comportamiento que refleje que se ha solucionado un problema real sera cuando las actividades de ayuda social consigan ser mas efectivas y que los participantes de estas aumenten.|
| User & Customers <br>¿En qué tipo de usuarios y clientes tienes que centrarte primero? <br>Usuario: <br>Personas encargadas de la gestion y recoleccion de datos de un proyecto orientado a las ONG. <br>Cliente: la Organizacion sin fines de lucro que adquiere nuestra herramienta. <br> ONG que busquen una optimizacion en la cantidad de gastos y tiempo invertidos.  <br> |  UX Canvas| User benefits <br>¿Cuáles son los objetivos que los usuarios intentan obtener? <br> \- Se busca gestionar un proyecto de manera que se pueda entender las oportunidades de mejora, los datos registrados, las planificaciones del proyecto y como pueden llegar a mas con menos. <br> ¿Qué les motiva a buscar tu solución? <br> \- Los usuarios están motivados a buscar esta solución debido la interfaz intuitiva, las oportunidades de optimizacion economica y el seguimiento de las acciones, gastos y personal que participara. <br>Nuestra interfaz resulta intuitiva para el usuario en todo el proceso. <br> |
| Hyphotheses: <br>  \- Creemos que, al brindar una interfaz poco compleja de usar para nuestros usuarios, podrán tener una mejor experiencia al gestionar sus datos y  proyectos de ayuda social. <br><br>Sabremos que hemos tenido éxito cuando se incremente la cantidad de proyectos efectivos por parte de las ONG que usen nuestra herramienta. <br><br> \- Creemos que la aplicación facilitara la gestion y creacion de proyectos de ayuda social proporcionando mejores resultados y un mayor flujo de personas participando de estas actividades. <br><br> Sabremos que tuvimos exito cuando distintos proyectos de ONG reciban mas relevancia y participantes. <br><br> \- Creemos que ayudar a las ONG a tener una mejor gestion y planeamiento en sus proyectos ayudara a mejorar la visibilidad y aumentar la cantidad de personas motivadas a participar. <br><br> Sabremos que hemos tenido éxito, cuando a nivel nacional se empiece a notar un incremento en la ayuda social proporcionada. | ¿Qué es la cosa más importante que nosotros necesitamos aprender primero? <br> Lo principal que necesitamos aprender es generar un modelo de gestion el cual sea efectivo a nivel visual y de gestion, y adicionalmente, un repaso en lo que viene siendo la gestión del proyecto| <br> ¿Cuál es la mínima cantidad de trabajo que nosotros necesitamos hacer para aprender la siguiente cosa más importante? <br> Asistir a las clases y solicitar que se nos revise los avances del proyecto para poder hacer un seguimiento saludable del proyecto|


## 1.3. Segmentos objetivo.
| |Segmento 1 | Segmento 2  |
| - | - |-|
| Variables                 |  Usuarios interesados en participar de actividades de ayuda social o en donar | ONG |
| Geográfica                | En el Perú, de entre 1,200 personas el 93% de estas estan interesadas en participar en actividades de ayuda social (CenDE, 2023) | Existen más de 1000 ONG en el Perú (SIGCTI,2024), no obstante solo se reconocen de 10 principalmente (CenDE ,2023) |
| Demográfica               | Edades de entre 17 a 50+ años <br> Genero: Masculino y Femenino | Organizaciones registradas como ONG |
| Psicológica               | Piensa en participar de actividades sociales o de donaciones en algun momento mas las limitaciones como el tiempo, la disponibilidad economica, la fiabilidad de las ONG que busca o el proceso de inscripcion terminan desanimandolo | Estas Organizaciones requieren de mas donaciones o participantes para sus campañas u eventos y buscan formas de aumentar el impacto general de estos mismos. |
| Función de comportamiento | Actitudes: Tiene una idea de que es una ONG pero en su mayoria no sabe como puede participar o no sabe de los eventos actuales en los cuales puede formar parte, algunos no conocen otras ONG y otros tienen la motivacion pero no saben si las ONG que encuentren haran correcto uso de lo donado <br> Conocimientos: Sabe que es una ONG, tiene entendido que existen organizaciones fraudulentas que se hacen pasar por ONG, normalmente no sabe si se cumplio el objetivo despues de participar| Actitudes: Hacen todo lo posible para que las donaciones lleguen en su mayor porcentaje a los más necesitados, hacen proyectos de ayuda social sin hacer mucho uso de data analitics<br> Conoce: Saben quienes requieren de ayuda, un estimado de cuanto se necesita o que se necesita para considerar donaciones, organizan eventos para concientizar y poder apoyar. |

---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | Realizamos este análisis a fin de poder conocer el mercado al que nos enfrentamos en un inicio, para de esta manera poder evaluar las estrategias adoptadas por plataformas ya existentes, y así aprender de sus aciertos y errores. |


| |  | (Nosotros)| CauseVox|  Bloomerang | Logalto |
|-|-|-|-|-|-|
| PERFIL| Overview | Plataforma que facilita el proceso de gestionar proyectos y recolectar datos de estos mismos proporcionando asi una herramienta versatil para un objetivo concreto.  | Plataforma de recaudación de fondos que brinda herramientas necesarias para crear campañas llamativas para cumplir su meta de donación. | Cuenta con distintas herramientas de gestion, es de alcance global y tiene mas de una forma de apoyar a las ONG. |Es un Programa web colaborativo para el monitoreo y la evaluación de proyectos de desarrollo internacional la cual proporciona una alta gama de herramientas de gestion de proyectos.|
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? | Mientras que facilita el proceso de gestion de proyectos y ofrece oportunidades de mejora. Tambien facilita y optimiza la recolecion de datos. | Cuenta con herramientas que le permiten al usuario personalizar su propia campaña para recaudar fondos con su logo e imágenes con las que atraer potenciales donantes. |Permite categorizar los proyectos en 9 categorías, por lo que le facilita al usuario la búsqueda de iniciativas afines a este.| Cuenta con distintas herramientas de gestion, es de alcance global y tiene mas de una forma de apoyar a las ONG.
|| Mercado Objetivo                                        | ONG peruanas, de estas mismas mas especificamente sus gestores y ayudantes del proyecto. | Organizaciones sin fines de lucro, grupos comunitarios y empresas, e individuos que deseen financiar dichas iniciativas. | Personas de México que quieran apoyo para financiar un proyecto, organizaciones sin fines de lucro, e individuos que deseen financiar dichas iniciativas. | proyectos de desarrollo, ONG y fundaciones, ministerios, instituciones de gobierno y proveedores de fondos.|
| Perfil de marketing                                     | Estrategia de Marketing | Se hacen uso de redes sociales y de publicidad en línea | Publicidad por redes y publicidad en línea | Marketing por influencia, publicidad por redes |Publicidad por redes sociales.|
| Perfil del producto                                    | Productos y servicios | Aplicación web orientada a la gestion de proyectos de Organizaciones sin fines de lucro haciendo anlisis de datos, ofreciendo sugerencias y oportunidades de mejora, al mismo tiempo que facilita y agiliza el proceso de recoleccion de datos.| CauseVox es una plataforma de recaudación de fondos que facilita la creación y gestión de campañas de recaudación de fondos en línea. | Bloomerang ayuda a organizaciones sin fines de lucro a mejorar la experiencia de donación, ahorrar tiempo y a recaudar más fondos.| Loaglto es programa web colaborativo para el monitoreo y la evaluación de proyectos de desarrollo
 || Precios y costos                                        | Para las ONG se implementa un modelo estrictamente de pago el cual debe variar segun la cantidad de participantes en el proyecto o por el tamaño de la ONG | De pago | Gratuito | De pago|
|| Canales de distribución (Web y/o Móvil)                 | Web y Móvil Web | Móvil Web | Web y móvil Web ||
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores |  | Nosotros | CauseVox| Bloomerang | Logalto |
|-|-|-|-|-| - |
| Análisis SWOT | Fortalezas |- La aplicación cuenta con una función de gestion efectiva.<br>- Se presenta un modelo de organizacion facil de entender.<br>- Facil recolecion de datos y analisis.| - Permite la personalización completa del aspecto de las páginas de campaña.<br>- Herramientas para la promoción en redes sociales. | - Cuenta con servicio al cliente en tiempo real.<br>- La plataforma es accesible y fácil de usar para crear y gestionar campañas, y realizar estrategias de marketing por correo. | - Diferentes Funcionalidades para gestion de proyectos <br> -Multiples herramientas de seguimiento y planificacion <br> -Mas tiempo en el mercado. |
|| Debilidades   | - Limitación de recursos para el financiamiento de la promoción de la aplicación.<br>- Competencia con plataformas similares. | - Limitaciones en su alcance de mercado. | - Los precios de su servicio es elevado. | - Saturacion de herramientas. <br> - Proceso agobiante <br> - No es muy intuitivo. | 
|| Oportunidades | - Crear alianzas con ONGs o empresas podría mejorar el alcance de la aplicación.<br>- El aumento de conciencia social y de la disposición para apoyar a ONGs.<br>- La expansión de la aplicación a regiones extranjeras. | Desarrollar nuevas funcionalidades para mejorar la experiencia de usuario. |  La expansión de la aplicación a un público más amplio al ofrecer tipos de suscripción alternos y a menor precio.| - Separar las herramientas por paquetes que necesite el usuario. | 
|| Amenazas      | - La existencia de competidores establecidos.<br>- Preocupaciones sobre la seguridad de datos y las transacciones de las donaciones. | - Al ser un servicio de pago, potenciales organizaciones podrían optar por opciones accesibles. | - La aparición de competencia emergente.<br>- La desconfianza hacia algunas organizaciones benéficas por la percepción del mal manejo de fondos. | - La necesidad de una herramienta facil de usar que no requiera gran cantidad de funciones para lograr un solo objetivo. |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿Que navegadores y dispositivos usa? 

**Entrevistas usuario segmento 1**
1. ¿Cuando piensa en gestionar un proyecto en que piensa principalmente?
2. ¿Que metodos utiliza para organizar a sus ayudantes y como les asigna tareas?
3. ¿Que herramientas usa para gestionar o planificar proyectos?
4. ¿Como analiza sus datos, que herramientas/metodos usa?  
   
**Entrevistas usuario segmento 2**
1. ¿Que actividades son las principales en los eventos y como se las asignan? 
2. ¿Como recolectan informacion de los participantes, que herramientas?
3. ¿Como hacen llegar esta informacion a los gestores de proyecto?
4. ¿Si sucede un inconveniente el cual se debe de notificar al gestor del proyecto como se comunica con este, cree que la comunicacion con el gestor de proyecto es efectiva? 
### 2.2.2. Registro de entrevistas.
**Segmento 1**  
Nombre: Maria Jose Melendez
Edad: 53 años 
Ocupación: Directora de Hogar (CAEF)
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS1E1.png)  
[Seg1 - Entrevista - 1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ERgJ0_AWCqVErNukgws7eiIBIgGIeuzeYyiSeb76MeGP9w?e=f7I1Pt&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

En la entrevista Maria nos cuenta de como su ONG no tiene una herramienta de gestion determinada y como normalmente usan Excel para los analisis de sus datos, tambien relata que para la planificacion se hacen reuniones anuales y mensuales.

Nombre: Cesar Alva Posada
Edad: 57 años 
Ocupación: Sociologo encargado de Gestion de Proyectos  
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS1E2.png)  
[Seg1 -Entrevista - 2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESDqRfzRGHFMsuxKkO5AzPgB5n2DN_YAREAKth0-NdKi-A?e=2FxzuN&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

En esta entrevista Cesar explica como la metodologia que se usa es importante a la hora de organizarse asimismo nos comento de otras herramientas que se implementan para la gestion, no obstante tambien menciona que todos estos procesos se hacen de manera separada. Asimismo para la gestion de datos utiliza excel.

Nombre: Guilder Quiñones Aldean
Edad: 54 años 
Ocupación: Jefe de Proyectos  
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS1E3.png)  
[Seg1 - Entrevista - 3](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESDqRfzRGHFMsuxKkO5AzPgB5n2DN_YAREAKth0-NdKi-A?e=2FxzuN&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

El Jefe de Proyecto Guilder comparte su vision respecto a las herramientas usadas, de manera parecida a la entrevista anterior el usa excel para manejar sus datos mas tambien hace uso de programas de gestion como trello.

**Segmento 2**  
Nombre: Luis Herrera Gonzales
Edad: 19 años 
Ocupación: Estudiante - Ayudante 
![Imagen de entrevista](../assets/Entrevistas/EntrevistaS2E1.png)  
[Seg2 - Entrevista - 1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESesnqbIKNBIj2P7j6CMxpsBuPL5ecH8TMAAxZh29afhHw?e=pCWved&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Luis nos cuenta de como participa de estas actividades usando whatsapp como su principal fuente de recoleccion de datos y comunicacion con su gerente, menciona que tanto el uso del correo electronico y uso de whatsapp son obsoletos, toman mucho tiempo y no demuestran el nivel de formalidad deseado.

Nombre: Alvaro Jimenez
Edad: 19 años
Ocupación: Estudiante - Ayudante 
![Imagen de entrevista](/assets/Entrevistas/EntrevistaS2E2.png)  
[Seg2 - Entrevista - 2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/ESskiDGzwCZLrHJVscTBOOoBK0Bx2Q6u2aFn2dDAv0RB8w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=smRneZ)

Alvaro comenta sobre su experiencia como voluntario ayudante en una ONG. Se menciona como es la distribucion de tareas y la comunicacion entre los ayudantes y el gestor del proyecto. Tambien menciona que no es eficiente ni rapida la gestion de la organizacion y que el espera se pueda mejorar en algun futuro.

Nombre: Pol Landeo
Edad: 27 años 
Ocupación: Ayudante en una ONG
![Imagen de entrevista](../assets/Entrevistas/EntrevistaS2E3.png)  
[Seg2 - Entrevista - 3](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211894_upc_edu_pe/EVTCV3Z3klZEunW6DHRtpU4BIwJk7OE6UEs4NEG5tWiMpQ?e=l3SrWz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Pol nos cuenta que en su día a día hace uso de las herramientas de google para la administración de tareas y la comunicación con el gestor del proyecto, menciona que la comunicación con el gestor del proyecto es efectiva pero que la gestión de tareas no es tan eficiente. En cuanto a la recolección de datos, menciona que se hace de manera manual, por lo que sería de gran ayuda contar con una herramienta que facilite este proceso.


### 2.2.3. Análisis de entrevistas.
**Segmento 1:**

En el segmento 1 existe una preferencia en usar excel para el analisis de datos recibidos, las multiples herramientas para un proyecto y en base a que entregan sus tareas a sus colaboradores. Se puede observar que la mayoria no utiliza tecnologia y que a escala de necesidad sienten que puede resultar util. Mas no tienen mucho conocimiento de la tecnologia implementada.

**Segmento 2:**
Respecto al segmento 2 se nota una tendencia respecto a la necesidad de una herramienta la cual pueda obtener la informacion y mandarla al proyecto de manera efectiva y rapida, Asimismo de como se requiere de una plataforma para poder comunicarse con el supervisor.

## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento 1:**  
![Imagen User Persona 1](../assets/requirements-images/user%20persona_jefe.png)
**Segmento 2:**
![Imagen User Persona 1](../assets/requirements-images/user%20persona_organizadores.png)


### 2.3.2. User Task Matrix.
| ‎ | ‎  | Segmento 1  | Saul BuenHombre | Segmento 2  | Manuel Torres |
| --- | ------ | ----------- | ------------ | ----------- | ---------- |
| ID  | Titulo | Importancia | Frecuencia   | Importancia | Frecuencia |
| HU01 | Listado de proyectos a realizar | Alta | Alta | Media | Baja |
| HU02 | Actualizaciones de nuevos proyectos | Media | Media | Alta | Media |
| HU03 | Asignación de tareas del proyecto | Alta | Alta | Alta | Alta |
| HU04 | Calendario con fechas importantes | Media | Media | Alta | Alta |
| HU05 | Dashboard estadístico simple | Alta | Media | Media | Baja |
| HU06 | Lista de tareas completadas | Alta | Media | Alta | Media |
| HU07 | Generación de resúmenes | Alta | Alta | Media | Baja |
| HU08 | Status automático del proyecto | Media | Baja | Media | Media |
| HU09 | Registro de detalles en el proyecto | Alta | Baja | Alta | Media |
| HU10 | Solicitud de recursos | Alta | Media | Media | Media |
| HU11 | Fechas a expirar | Baja | Baja | Media | Baja |
| HU12 | Estimación de gastos  | Alta | Alta | Alta | Media |
| HU13 | Límite máximo de presupuesto | Alta | Media | Alta | Media |
| HU14 | Registro de gastos | Alta | Alta | Alta | Media |
| HU15 | Directorio de contactos | Media | Alta | Media | Alta |
| HU16 | Recomendaciones sobre el buen manejo de proyectos | Alta | Media | Alta | Alta |
| HU17 | Picos de riesgo | Alta | Alta | Alta | Media |
| HU18 | Documentos legales | Alta | Media | Media | Baja |
| HU19 | Gestión de donaciones | Alta | Media | Alta | Media |
| HU20 | Promoción y seguimiento | Media | Media | Baja | Baja |
### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?
- Interface facil de entender
- Funciones bien definidas 
- Ofrecemos un servicio completo junto a recomendaciones
  
**Onboarding and first use:**

Good

How can they feel successful?
- La interfaz es simple de entender
- Solicita poco y devuelve mucho
- Es eficiente para ambos segmentos
  
**Sharing:**

Good

Why would they invite others?
- Facilidad de usar
- Resultados acertados
- Servicio accesible

### 2.3.4. Empathy Mapping.
**Segmento 1:**
![Empathy Map Segmento1](../assets/requirements-images/user_persona-segmento1.png)

**Segmento 2:**
![Empathy Map Segmento1](../assets/requirements-images/user_persona-segmento2.png)

### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: Gestor de proyecto realiza su labor sin una herramienta que lo beneficie

As Is:
| Fases|        |       |      |     |
|----------|---------------|----------|--------------|-------------|
| Doing          | Realizando tareas de gestión de proyectos manualmente | Investigando posibles beneficiarios de donaciones | Contactando a los ayudantes que van a participar | Realizando seguimiento de datos en hojas de cálculo o documentos físicos |
| Thinking       | Considerando la eficacia de los procesos manuales actuales | Evaluando la credibilidad de las fuentes de información sobre beneficiarios | Reflexionando sobre la necesidad de una conexion mas profesional y continua con sus compañeros | Pensando en la necesidad de herramientas digitales para mejorar la gestión de proyectos |
| Feeling        | Preocupado por la eficiencia y precisión de los métodos manuales | Inquieto por la falta de garantías en la calidad de la información recopilada | Preocupado por la posibilidad de que suceda algo y no pueda contactarse | Frustrado por la falta de herramientas digitales que agilicen y optimicen el proceso de gestión de proyectos |



**Segmento 2**  
Escenario: Ayudante del proyecto es enviado a manejar el proyecto de manera presencial

As Is:
| Fases     |       |       |        |    |
|----------|----------------|------|---------|-----|
| Doing          | Realizando entrevistas en persona con posibles beneficiarios de donaciones | Implementando métodos manuales para la recolección de datos en el terreno | Colaborando activamente con el segmento objetivo 1 para entender las necesidades de información específicas | Explorando opciones de recolección de datos |
| Thinking       | Reflexionando sobre la relevancia de los datos recopilados en el contexto local | Evaluando la eficacia de los métodos manuales utilizados en el terreno | Considerando estrategias para mejorar la comunicación y colaboración con el segmento objetivo 1 de manera presencial | Evaluando la utilidad y seguridad de las herramientas de recolección de datos |
| Feeling        | Comprometido con la precisión y relevancia de los datos recopilados de manera presencial | Optimista sobre la efectividad de los métodos de recolección de datos en terreno | Satisfecho al contribuir de manera activa al proceso de gestión de proyectos en el lugar | Esperanzado por encontrar herramientas eficaces para la recolección de datos en entornos presenciales |



## 2.4. Ubiquitous Language.
```
Texto ubiquo: Se trata de un glosario de términos 
del dominio para mantenernos comunicados y actualizados, 
tanto el equipo como los stakeholders, relacionados al sector 
en el que se especializa la startup.
```

**1. Organización benéfica:** Una entidad sin fines de lucro que busca apoyar causas sociales, humanitarias o ambientales a través de donaciones.

**2. Necesidades benéficas:** Los artículos, suministros o recursos específicos que una organización benéfica requiere para llevar a cabo sus actividades o programas.

**3. Gestor de Proyecto:** Segmento Objetivo que representa a los gestores o supervisores del proyecto los cuales son encargados por las ONG en realizar un proyecto estos pueden trabajar solos o en grupos dependiendo de los objetivos de la ONG, finitamente estos son los que deberan revisar y analisar los datos recolectados.

**4. Lista de necesidades:** Una lista detallada de los artículos o suministros específicos que una organización benéfica necesita recibir como donación.

**5. Intermediario de donaciones:** Una plataforma o servicio que facilita la conexión entre organizaciones benéficas que necesitan donaciones y personas dispuestas a donar.

**6. ONG:** Entidad formada por personas que comparten un interés común en promover una causa social, política o ambiental.

**7. Usuario donante:** Un usuario de la plataforma que está interesado en donar artículos o suministros a organizaciones benéficas.

**8. Usuario receptor:** Una organización benéfica que está registrada en la plataforma y que busca recibir donaciones de artículos o suministros.

**9. Registro de donación:** Un registro de las donaciones realizadas por los usuarios, que puede incluir información sobre los artículos donados, la organización benéfica receptora, etc.

**10. Notificación de necesidad:** Una alerta o mensaje que se envía a los usuarios sobre las necesidades específicas de una organización benéfica en un momento dado.

---

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
 
Escenario 1: Gestor de proyecto realiza su labor con AidManager para que lo beneficie.
To-Be:
| Fases|        |   |    |   |
|----------|--------------|--------|----------|--------|
| Doing          | Utilizando la herramienta web para planificar proyectos | Accediendo a la información recolectada por los ayudantes | Manteniendo comunicación directa con los ayudantes a través de la plataforma | Analizando oportunidades de mejora proporcionadas por la herramienta |
| Thinking       | Considerando cómo optimizar la planificación de proyectos con la información obtenida | Evaluando la calidad y relevancia de la información recolectada | Reflexionando sobre la efectividad de la comunicación directa con los ayudantes | Identificando oportunidades de mejora sugeridas por la plataforma |
| Feeling        | Satisfecho con la eficiencia y precisión en la planificación de proyectos | Valorando la contribución de los ayudantes a través de la información recolectada | Confianza en la comunicación fluida con los ayudantes | Motivado por las oportunidades de mejora identificadas por la herramienta |


Escenario 2: Ayudante del proyecto es enviado a manejar el proyecto de manera presencial con AidManager.

TO-BE:
| Fases          |      |       |       |       |
|---------|--------|--------|------------------|---------|
| Doing          | Utilizando la herramienta web para recolectar información demográfica, geográfica y psicológica relevante | Comunicando la información recolectada de manera directa al gestor de proyectos | Colaborando con el gestor en la planificación y ejecución del proyecto utilizando la información recolectada | Manteniendo actualizado el inventario y presupuesto del proyecto en la plataforma |
| Thinking       | Reflexionando sobre la importancia y relevancia de la información recolectada para el proyecto | Evaluando la eficacia de la comunicación directa con el gestor a través de la plataforma | Considerando cómo mejorar la colaboración con el gestor utilizando la información recolectada | Identificando oportunidades de mejora en la gestión del inventario y presupuesto del proyecto |
| Feeling        | Comprometido con la precisión y relevancia de la información recolectada | Satisfecho al contribuir de manera significativa al proyecto a través de la información recolectada | Motivado por la colaboración directa con el gestor y el impacto positivo en el proyecto | Esperanzado por la mejora continua en la gestión del inventario y presupuesto del proyecto |


## 3.2. User Stories.
 
| HU0X | Historia Usuario | "Descripcion"  | Criterios de Aceptación |
|-|-|-|-|
| HU01 | Listado de proyectos a realizar | Como project manager encargado del proceso, quiero planificar lo que haré en un listado de tareas, para tener en cuenta lo proyectado.  | Given que soy un project manager,<br>When accedo al sistema de gestión de proyectos,<br>Then debo poder ver un listado de proyectos a realizar. |
| HU02 | Actualizaciones de nuevos proyectos | Como miembro del equipo y parte del proyecto, quiero mantenerme informado sobre los nuevos procesos o cambios que se hayan realizado en una lista de status, para no perderme de ningún detalle.  |Given que soy un miembro del equipo,<br>When accedo al sistema de gestión de proyectos,<br>Then debo poder ver las actualizaciones de nuevos proyectos en la lista de status. |
| HU03 | Asignación de tareas del proyecto | Como project manager encargado de un proyecto, quiero asignar a mis miembros del equipo algunas tareas y establecer fechas límites, para mantener un orden.  |Given que soy un project manager,<br>When asigno tareas a los miembros del equipo en el sistema de gestión de proyectos,<br>Then las tareas se asignan correctamente y se establecen fechas límites. |
| HU04 | Calendario con fechas importantes | Como miembro del parte del proyecto, quiero ver en un calendario las fechas y eventos relacionados al proyecto para no perderme ningún detalle.  |Given que soy un miembro del proyecto,<br>When accedo al calendario en el sistema de gestión de proyectos,<br>Then puedo ver todas las fechas importantes relacionadas al proyecto. |
| HU05 | Dashboard estadístico simple | Como project manager a cargo de un proyecto, quiero ver un resumen visual del progreso del proyecto en forma de gráficos, para tener una mejor visión de lo planificado.  |Given que soy un project manager,<br>When accedo al dashboard en el sistema de gestión de proyectos,<br>Then debo poder ver un resumen visual del progreso del proyecto en forma de gráficos. |
| HU06 | Lista de tareas completadas | Como miembro del proyecto, quiero ver mis tareas asignadas, organizadas y completadas en una lista, para tener mejor detalle de lo realizado. |Given que soy un miembro del proyecto,<br>When accedo a la lista de tareas en el sistema de gestión de proyectos,<br>Then puedo ver mis tareas asignadas, organizadas y completadas. |
| HU07 | Generación de resúmenes | Como project manager a cargo de un proyecto benéfico, quiero generar resúmen estadístico sobre lo planificado a gastar con un solo click, para optimizar tiempos. |Given que soy un project manager,<br>When genero un resumen estadístico en el sistema de gestión de proyectos,<br>Then debo poder hacerlo con un solo click para optimizar tiempos. |
| HU08 | Status automático del proyecto | Como miembro del proyecto, quiero ver un resumen ejecutivo del proyecto que incluya el estado actual, los hitos, riesgos identificados, para reconocer rápidamente lo planificado. |Given que soy un miembro del proyecto,<br>When accedo al resumen ejecutivo del proyecto en el sistema de gestión,<br>Then debo poder ver el estado actual, los hitos y riesgos identificados. |
| HU09 | Registro de detalles en el proyecto | Como miembro del proyecto, quiero registrar horas de trabajo y gastos relacionados con el proyecto para llevar un control preciso de los recursos utilizados  |Given que soy un miembro del proyecto,<br>When registro horas de trabajo y gastos en el sistema de gestión de proyectos,<br>Then debo poder llevar un control preciso de los recursos utilizados. |
| HU10 | Solicitud de recursos | Como miembro del proyecto, quiero solicitar, mandar análisis de nuevos recursos que se requieren al project manager, para que este al tanto de nuevos requerimientos.   |Given que soy un miembro del proyecto,<br>When solicito nuevos recursos en el sistema de gestión de proyectos,<br>Then debo poder enviar análisis de los recursos requeridos al project manager. |
| HU11 | Fechas a expirar | Como miembro del proyecto, quiero ver cuando una fecha límite está por llegar, para diferenciarlos de los que aun existe un rango de tiempo. |Given que soy un miembro del proyecto,<br>When accedo al sistema de gestión de proyectos,<br>Then debo poder ver las fechas límite por expirar y diferenciarlas claramente. |
| HU12 | Estimación de gastos  | Como project manager, quiero poder establecer y gestionar un presupuesto para el proyecto, incluyendo seguimiento de gastos y comparación con la estimación inicial. |Given que soy un project manager,<br>When establezco un presupuesto en el sistema de gestión de proyectos,<br>Then debo poder hacer seguimiento de gastos y compararlo con la estimación inicial. |
| HU13 | Límite máximo de presupuesto | Como project manager quiero que me alerte cuando vayamos gastando más de lo presupuestado de manera visual, para tener una diferencia y estar pendiente de ello.  |Given que soy un project manager,<br>When gasto más de lo presupuestado,<br>Then debo recibir una alerta visual en el sistema de gestión de proyectos. |
| HU14 | Registro de gastos | Como miembro del proyecto, quiero registrar los recursos que se han ido adquiriendo para que se vaya teniendo un alcance de lo que se va gastando. |Given que soy un miembro del proyecto,<br>When registro los recursos adquiridos en el sistema de gestión de proyectos,<br>Then debo tener un alcance de lo que se va gastando. |
| HU15 | Directorio de contactos | Como miembro del proyecto, quiero tener un listado de todos los demás miembros para poder ponerme en contacto con ellos. | Given que soy un miembro del proyecto,<br>When accedo al directorio de contactos en el sistema de gestión de proyectos,<br>Then debo poder ver el listado de todos los demás miembros. |
| HU16 | Recomendaciones sobre el buen manejo de proyectos | Como miembro del equipo quiero tener un repositorio en el que tenga diferentes fuentes recomendadas por la aplicación para el buen manejo de proyectos y campañas.  | Given que soy un miembro del equipo,<br>When accedo al repositorio de recomendaciones en el sistema de gestión de proyectos,<br>Then debo poder ver diferentes fuentes recomendadas para el buen manejo de proyectos. |
| HU17 | Picos de riesgo | Como project manager, quiero visualizar en el dashboard cuando algún ajuste de la campaña no está cuadrando, para mantenerme alerta del buen manejo del proyecto | Given que soy un project manager,<br>When accedo al dashboard en el sistema de gestión de proyectos,<br>Then debo poder visualizar picos de riesgo para mantenerme alerta. |
| HU18 | Documentos legales | Como project manager quiero subir los documentos legalizados sobre la organización benéfica para que sea compartido con los miembros del proyecto | Given que soy un project manager,<br>When subo documentos legales en el sistema de gestión de proyectos,<br>Then debo poder compartirlos con los miembros del proyecto. |
| HU19 | Gestión de donaciones | Como miembro del proyecto, quiero poder acceder a un sistema de gestión de donaciones para hacer un seguimiento de las contribuciones recibidas y su impacto en el proyecto. | Given que soy un miembro del proyecto,<br>When accedo al sistema de gestión de donaciones en el sistema de gestión de proyectos,<br>Then debo poder hacer un seguimiento de las contribuciones recibidas y su impacto en el proyecto. |
| HU20 | Promoción y seguimiento | Quiero poder acceder a un sistema de seguimiento de objetivos y resultados para evaluar el progreso del proyecto y realizar ajustes si es necesario. | Given que soy un usuario,<br>When accedo al sistema de seguimiento de objetivos y resultados en el sistema de gestión de proyectos,<br>Then debo poder evaluar el progreso del proyecto y realizar ajustes si es necesario. |


## 3.3. Impact Mapping.

![Impact Mapping Project Manager](../assets/impact-mapping-images/Impact-mapping-project-manager.png)
![Impact Mapping Organizer](../assets/impact-mapping-images/Impact-mapping-organizer.png)


## 3.4. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 1      | HU01          | Listado de organizaciones benéficas | Como usuario donante, quiero poder ver una lista de organizaciones benéficas registradas en la plataforma, para poder seleccionar a quién quiero donar. |     8    |
| 2      | HU02          | Lista de necesidades en recursos | Como usuario donante, quiero poder ver una lista de necesidades específicas de cada organización benéfica, para poder donar artículos que realmente necesitan. |         5         |
| 3      | HU03          | Detalles de lo necesitado | Como usuario donante, quiero poder ver información detallada sobre cada necesidad benéfica, incluyendo la cantidad requerida y la fecha límite de donación, para poder planificar mi donación. |         8         |
| 4      | HU04          | Donaciones sencillas y rápidas | Como usuario donante, quiero poder realizar donaciones en especie a través de la plataforma, para poder contribuir con las organizaciones benéficas de manera fácil y segura. |         5         |
| 5      | HU05          | Confirmación y agradecimiento | Como usuario donante, quiero recibir una confirmación de mi donación, incluyendo detalles sobre los artículos donados y la organización benéfica receptora, para tener un registro de mis contribuciones. |         5         |
| 6     | HU06 | Perfil y detalles de la organización | Como organización benéfica, quiero poder registrar los detalles de mi organización en la plataforma, incluyendo el nombre, la misión, la ubicación y la información de contacto, para poder recibir donaciones.  |     8    |
| 7     | HU07 | Creación lista de necesidades | Como organización benéfica, quiero poder crear una lista de necesidades específicas de mi organización, incluyendo la descripción de los artículos necesarios y la cantidad requerida, para poder comunicar nuestras necesidades a los usuarios donantes.  |     8    |
| 8     | HU08 | Notificaciones automáticas de nueva donación | Como organización benéfica, quiero poder recibir notificaciones cuando un usuario donante realice una donación a nuestra organización, para poder estar al tanto de las contribuciones recibidas. |     5    |
| 9     | HU09 | Gestión de la lista de necesidades | Como organización benéfica, quiero poder gestionar y actualizar nuestra lista de necesidades en la plataforma, para reflejar con precisión nuestras necesidades actuales.  |     5    |
| 10     | HU10 | Reseña y comentarios | Como usuario donante, quiero poder compartir información sobre las necesidades benéficas y las organizaciones registradas en la plataforma en mis redes sociales, para aumentar la visibilidad y las donaciones.  |     5    |
| 11     | HU11 | Historial de donaciones | Como usuario donante, quiero poder ver un historial de mis donaciones anteriores en la plataforma, incluyendo detalles como la fecha y los artículos donados, para poder realizar un seguimiento de mis contribuciones.  |     3    |
| 12     | HU12 | Recomendaciones y nuevos intereses  | Como usuario donante, quiero recibir recomendaciones personalizadas sobre organizaciones benéficas y necesidades específicas, basadas en mis intereses y patrones de donación anteriores, para facilitar el proceso de selección de donaciones.  |     5    |
| 13     | HU13 | Donaciones flexibles | Como usuario donante, quiero poder realizar donaciones monetarias a través de la plataforma, para apoyar a las organizaciones benéficas de manera flexible.  |     3    |
| 14     | HU14 | Eventos e iniciativas | Como usuario donante, quiero recibir notificaciones sobre eventos benéficos o campañas especiales organizadas por las organizaciones benéficas en la plataforma, para poder participar activamente en iniciativas adicionales de donación. |     5    |
| 15     | HU15 | Dashboard de estadísticas y reseñas | Como usuario donante, quiero poder ver el impacto de mis donaciones, incluyendo estadísticas y testimonios sobre cómo mis contribuciones han beneficiado a las organizaciones benéficas, para motivarme a seguir donando. |     2    |
| 16     | HU16 | Informes sobre las donaciones | Como organización benéfica, quiero poder acceder a informes y estadísticas sobre las donaciones recibidas a través de la plataforma, para evaluar el rendimiento de nuestras campañas de recaudación de fondos.  |     8    |
| 17     | HU17 | Mensajes de agradecimiento automáticos | Como organización benéfica, quiero poder enviar mensajes de agradecimiento automáticos a los usuarios donantes después de cada donación, para expresar nuestra gratitud de manera oportuna. |     3    |
| 18     | HU18 | Solicitud de apoyo | Como organización benéfica, quiero poder solicitar voluntarios a través de la plataforma, para apoyar nuestras operaciones y programas.  |     5    |
| 19     | HU19 | Publicaciones de agradecimiento y metas logradas | Como organización benéfica, quiero poder compartir historias de éxito y testimonios de beneficiarios de nuestros programas en la plataforma, para mostrar el impacto positivo de nuestras actividades.  |     3    |
| 20     | HU20 | Promoción y creación de eventos | Como organización benéfica, quiero poder crear y promocionar eventos benéficos en la plataforma, para recaudar fondos y aumentar la conciencia sobre nuestra causa. |     5    |

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.

Como startup, nos esforzamos por transmitir profesionalismo y eficiencia a través de nuestra aplicación web, AidManager. Hemos seleccionado una paleta de colores con tonos celestes y verdes para reflejar frescura y conexión con la naturaleza, mientras que las tipografías Poppins y Lora ofrecen una apariencia moderna, limpia y legible. Estas decisiones de diseño no solo buscan captar la atención de nuestros usuarios, sino también garantizar una experiencia agradable y efectiva, reforzando nuestro compromiso en la gestión eficiente de eventos benéficos y donaciones.

**Color:** (Descripcion de la paleta escogida para el proyecto y porque)

| Color | Descripción |
|-----------|-----------|
| Color primario    | Representa confianza, serenidad y estabilidad. Transmite la idea de fiabilidad y compromiso en la gestión de organizaciones benéficas, lo que inspira confianza en los donantes y en aquellos que buscan ayuda.<br><br><img src="../assets/StyleGuidelines-Images/PrimaryColor.jpeg" alt="Tipografias generales" style="width:70%"> |
| Color Secundario  | Este color evoca calma, frescura y bienestar. Simboliza la esperanza y el apoyo que tu startup ofrece a las personas necesitadas, así como la naturaleza refrescante de las soluciones que proporciona. <br><br><img src="../assets/StyleGuidelines-Images/SecondaryColor.jpeg" alt="Tipografias generales" style="width:70%">    |
| Color de Acento | Este color combina la estabilidad del azul con la vitalidad del verde. Representa el crecimiento, la renovación y la prosperidad, en el cual se busca mejorar la vida de las personas necesitadas y fomentar un cambio positivo en la comunidad. <br><br><img src="../assets/StyleGuidelines-Images/TittleColor.jpeg" alt="Tipografias generales" style="width:70%">   |
| Color de Fondo  | Este tono de verde transmite equilibrio, armonía y seguridad. Esto refleja la solidez y la integridad de tu startup en su enfoque hacia la gestión eficiente de eventos benéficos y donaciones, asegurando que los recursos se utilicen de manera responsable y efectiva. <br><br><img src="../assets/StyleGuidelines-Images/FooterColor.jpeg" alt="Tipografias generales" style="width:70%">  |

Paleta de colores empleado:
<center>
  <img src="../assets/StyleGuidelines-Images/PaletColor.jpg" alt="Tipografias generales" style="width:70%"><br><br>
</center>

**Tipografia:** (Descripcion de la tipografia escogida para el proyecto y porque)

| Tipografia | Descripcion |
|-----------|-----------|
| Poppins Font | Esta tipografía se eligió por su apariencia moderna, limpia y versátil. Su estilo geométrico y su excelente legibilidad la hacen ideal para comunicar profesionalismo y eficiencia en la gestión de organizaciones benéficas.  |
| Lora Font | Se seleccionó Lora por su elegancia y legibilidad, que complementa perfectamente la apariencia contemporánea de Poppins. Su estilo serifado transmite una sensación de tradición y prestigio, lo que refuerza la credibilidad de tu startup en el sector de la beneficencia. |

<br><center><img src="../assets/StyleGuidelines-Images/PoppinsFont.jpg" alt="Tipografias generales" style="width:70%"></center>
<center><img src="../assets/StyleGuidelines-Images/LoraFont.jpg" alt="Tipografias generales" style="width:70%"><br><br></center>

**Branding** (Describir logotipo y porque)

El logo de nuestra startup, que muestra la vista superior de alguien abriendo los brazos en un color verde azulado, simboliza nuestra dedicación a la apertura, el apoyo y la generosidad hacia aquellos que más lo necesitan. Representa nuestra misión de ofrecer ayuda directa y tangible, fomentando la solidaridad, la esperanza y la renovación en la comunidad.

<br><center><img src="../assets/StyleGuidelines-Images/LogoAidManager.jpg" alt="Tipografias generales" style="width:70%"><br><br></center>

### 4.1.2. Web Style Guidelines.
Descripcion de los elementos que se utilizaran en el web app

**Background:** (primary, secondary, terniary)

Para el background se hace uso del color FFFFF para resaltar la pagina y para separar secciones D9ED8F
![Background Preview web](/assets/searching-system/Search.png)


**Text Styles:** (H1, H2, p, a,)

Para el texto se escogieron colores que combinan con la tematica de la pagina y que facilitan la lectura del usuario
<center><img src="../assets/aidmanager-app-mockup/aam-6.png" alt="app web mock-up6" style="width:80%;"></center>

**Button Styles:** (Button, dropdowns, Switches)

Para los botones el color cambia segun el color del fondo
<center><img src="../assets/app-web-wireframe/aww-13.png" alt="app web wireframe13" style="width:80%;"></center>

**Icons:** (Fondo blanco con los iconos que vamos a usar)
Tendremos iconografia de busqueda, lapiz, ropa, reciclaje, icono de grafico, foco, etc

<center><img src="../assets/aidmanager-app-mockup/aam-6.png" alt="app web mock-up6" style="width:80%;"></center>

**Misc** 
Se determina el color y posicion segun la seccion
<center><img src="../assets/app-web-wireframe/aww-10.png" alt="app web wireframe10" style="width:80%;"></center>

## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
Sistemas de organización que usaremos para el proyecto.

El sistema de Organizacion se basa en un sistema Sequencial donde el usuario debe seguir el workdlow de la herramienta para llegar a su objetivo, no obstante ofrecemos atajos en el sidebar.

Asimismo existira una herarquia visual dependiendo si quien se ha ingresado es un gestor o colaborador/ayudante.
### 4.2.2. Labeling Systems.
En esta sección, nos esforzamos por garantizar que la presentación de la información al usuario sea clara y fácil de entender, con el objetivo de proporcionar una experiencia agradable y sin complicaciones. Para ello, hemos incorporado en el vocabulario de nuestra página palabras comunes y familiares que la mayoría de las personas utilizan en su día a día, de manera que puedan asociar de manera intuitiva los conceptos que manejamos. Por ejemplo:
| Label | Concepto Asociado |
|-----------|-----------|
| <center><img src="../assets/LabelingSystems/Home.png" alt="Home Label" style="height:50%"></center>| Se refiere a la página principal de nuestra landing page, donde los usuarios comienzan su recorrido. |
|<center><img src="../assets/LabelingSystems/About.png" alt="About us Label" style="height:50%"></center>|Una etiqueta que proporciona información sobre nuestra empresa, incluyendo su misión y visión.
|<center><img src="../assets/LabelingSystems/Organizations.png" alt="Organizations Label" style="height:50%"></center>| Segmento que muestra una recopilación de las organizaciones que colaboran con AidManager.
|<center><img src="../assets/LabelingSystems/Testimonials.png" alt="Testimonials Label" style="height:50%"></center>|Lista de reseñas que presenta experiencias y opiniones de clientes sobre AidManager.
|<center><img src="../assets/LabelingSystems/Get Started.png" alt="Home Label" style="height:50%"></center>|Call-to-action que invita a los usuarios a iniciar su experiencia concreta junto a AidManager.
### 4.2.3. SEO Tags and Meta Tags

**Meta & SEO (Search Engine Optimization) Tags:**  sirven para que la pagina web sea encontrada facilmente es lo que sale al encontrar la pagina en el buscador (se ponen en el <"head">)
* Titulo: ```<title> AidManager | La mejor opcion de ONG para la gestion de proyectos </title> ```
* Descripcion: ```<meta name = "description" content = "Gestiona, Recolecta, Analiza y Visualiza los datos y colaboradores de tus proyectos todo en un solo lugar."/> ```
* Palabras Clave: ```<meta name = "keyword" content = "ONG gestion, Gestionar Proyecto, ONG, dar Tareas, analisis de datos, Organizar, Orden "/> ```

### 4.2.4. Searching Systems.

Se hace un ejemplo respecto al segmento 1:

**Que se busca?:** 
El usuario busca su proyecto para gestionar.
**Que resultados se mostraran?:** Se debe de mostrar las cards con el proyecto que esta revisando.  
**Interface de busqueda:** el dashboard muestra en el sidebar la seccion home una vez se selecciona se mostraran las cards con sus proyectos, el usuario selecciona el proyecto especifico y se redirreciona a su proyecto para gestionar. 
![Search interface](/assets/searching-system/Search.png)

Cabe mencionar que este metodo se usa en los demas features.

### 4.2.5. Navigation Systems.

La navegacion de la web app se estara basando en un Sistema de navegacion Global donde por medio de las cards en el dashboard o los labels en el side bar el usuario se redirija a la seccion selecionada.

No obstante tambien se incluye la navegacion local cuando se trata de la seccion de proyectos y analytics donde se va a navegar entre los distintos proyectos de la ONG.

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
la pagina donde te registras y ves info del web app (te manda al web app)

Wireframe es todo lo funcional de la pagina
![Landing page Wireframe](/assets/landing-page-wireframe-image/Wireframe.png)
### 4.3.2. Landing Page Mock-up.

<img src="../assets/Landing page mock-up/Landing mock up.png" alt="Landing page mock up" style="width:100%;">

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
</br>

[URL del Wireframe hecho en Figma](https://www.figma.com/file/u8S0RHE4Kbl69EwQSVf7jb/AidManager-app-web-Wireframe?type=design&node-id=0%3A1&mode=design&t=FQRKS9G6nW0lMIRj-1)

**Segmento 1: Manager de ONG**
<center><img src="../assets/app-web-wireframe/aww-1.png" alt="app web wireframe1" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-2.png" alt="app web wireframe2" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-3.png" alt="app web wireframe3" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-4.png" alt="app web wireframe4" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-5.png" alt="app web wireframe5" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-6.png" alt="app web wireframe6" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-7.png" alt="app web wireframe7" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-8.png" alt="app web wireframe8" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-9.png" alt="app web wireframe9" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-10.png" alt="app web wireframe10" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-11.png" alt="app web wireframe11" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-12.png" alt="app web wireframe12" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-13.png" alt="app web wireframe13" style="width:80%;"></center>

**Segmento 2: Equipo de ONG**
<center><img src="../assets/app-web-wireframe/aww-14.png" alt="app web wireframe14" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-15.png" alt="app web wireframe15" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-16.png" alt="app web wireframe16" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-17.png" alt="app web wireframe17" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-18.png" alt="app web wireframe18" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-19.png" alt="app web wireframe19" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-20.png" alt="app web wireframe20" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-21.png" alt="app web wireframe21" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-22.png" alt="app web wireframe22" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-23.png" alt="app web wireframe23" style="width:80%;"></center>
<center><img src="../assets/app-web-wireframe/aww-24.png" alt="app web wireframe24" style="width:80%;"></center>


### 4.4.2. Web Applications Wireflow Diagrams.


![Web Aplication WireflowSegmento1](/assets/wireflow-images/wireflow.png)
![Web Aplication WireflowSegmento2](/assets/wireflow-images/wireflo2.png)


### 4.4.2. Web Applications Mock-ups.

</br>

[URL del Mock-up de la Aplicación hecho en Figma](https://www.figma.com/file/n5BSEAK3X9lFN2M1eqnmQX/AidManager-Prototype?type=design&node-id=0%3A1&mode=design&t=dhyNolXNOfDSlBEG-1)


**Segmento 1: Manager de ONG**
<center><img src="../assets/aidmanager-app-mockup/aam-1.png" alt="app web mock-up1" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-2.png" alt="app web mock-up2" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-3.png" alt="app web mock-up3" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-4.png" alt="app web mock-up4" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-5.png" alt="app web mock-up5" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-6.png" alt="app web mock-up6" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-7.png" alt="app web mock-up7" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-8.png" alt="app web mock-up8" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-9.png" alt="app web mock-up9" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-10.png" alt="app web mock-up10" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-11.png" alt="app web mock-up11" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-12.png" alt="app web mock-up12" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-13.png" alt="app web mock-up13" style="width:80%;"></center>

**Segmento 2: Equipo de ONG**
<center><img src="../assets/aidmanager-app-mockup/aam-14.png" alt="app web mock-up14" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-15.png" alt="app web mock-up15" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-16.png" alt="app web mock-up16" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-17.png" alt="app web mock-up17" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-18.png" alt="app web mock-up18" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-19.png" alt="app web mock-up19" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-20.png" alt="app web mock-up20" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-21.png" alt="app web mock-up21" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-22.png" alt="app web mock-up22" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-23.png" alt="app web mock-up23" style="width:80%;"></center>
<center><img src="../assets/aidmanager-app-mockup/aam-24.png" alt="app web mock-up24" style="width:80%;"></center>


### 4.4.3. Web Applications User Flow Diagrams.

![Web Aplication UserFlow](../assets/user-flow/Userflow1.png)
![Web Aplication UserFlow](../assets/user-flow/Userflo2.png)
![Web Aplication UserFlow](../assets/user-flow/Userflo3.png)
![Web Aplication UserFlow](../assets/user-flow/userflo4.png)
![Web Aplication UserFlow](../assets/user-flow/userflo5.png)



## 4.5. Web Applications Prototyping.
Se utilizó la herramienta Figma para realizar el primer prototipo de la aplicación web. 
<center><img src="../assets/app-web-prototyping/App-Web-Prototyping.png" alt="app web prototype" style="width:80%;"></center>

[URL del Prototipo hecho en Figma](https://www.figma.com/file/n5BSEAK3X9lFN2M1eqnmQX/Untitled?type=design&node-id=0%3A1&mode=design&t=dhyNolXNOfDSlBEG-1)
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
![System Context](../assets/system-diagrams/system-context.png) 
   
### 4.6.2. Software Architecture Container Diagrams.
![Container Diagram](../assets/system-diagrams/container-diagram.png)

### 4.6.3. Software Architecture Components Diagrams.
![Component Diagram](../assets/system-diagrams/component-payment.png)
**Payment Context**: Permite visualizar cómo se relacionan los componentes de la aplicación con el sistema de pagos. Se observa la interacción entre el cliente, la aplicación y el proveedor de pagos.

![Component Diagram](../assets/system-diagrams/component-collaborate.png)
**Collaborate Context**: Muestra la interacción entre los componentes de la aplicación y el sistema de colaboración. Se evidencia la comunicación entre el usuario, la aplicación y el sistema de colaboración.

![Component Diagram](../assets/system-diagrams/component-costsmanager.png)
**Costs Manager Context**: Representa la relación entre los componentes de la aplicación y el sistema de gestión de costos. Se visualiza la interacción entre el usuario, la aplicación y el sistema de gestión de costos.

![Component Diagram](../assets/system-diagrams/component-taskmanager.png)
**Task Manager Context**: Muestra cómo se relacionan los componentes de la aplicación con el sistema de gestión de tareas. Se evidencia la interacción entre el usuario, la aplicación y el sistema de gestión de tareas.

![Component Diagram](../assets/system-diagrams/component-userprofile.png)
**User Profile Context**: Permite visualizar la relación entre los componentes de la aplicación y el sistema de perfiles de usuario. Se observa la interacción entre el usuario, la aplicación y el sistema de perfiles de usuario.

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
![Class Diagram](../assets/diagrams/class_diagram.png)
### 4.7.2. Class Dictionary.

Se muestran las clases que son relevantes.

User - La clase user representa la cuenta de la Organizacion y los metodos mas importantes de estos.

| Atributo | Descripcion |
| - | - |
| last name | El nombre del usuario |
| dateBirth | Fecha de nacimiento del usuario |
| interests |  Intereses del usuario |


Project Manager - La clase representa los project managers

| Atributo | Descripcion |
| - | - |
| members | los User que son parte de la clase de Project Manager |
| projects | Los Projectos gestionados por el Projects Managers |
| events |  Los eventos gestionados por el Project Managers |
| mission |  Descripcion corta de la mision del Project Manager |
| vision |  Descripcion corta de la vision del Project Manager |
| siteWeb |  sitioWeb relacionado al Project Manager |
| appreciationMssg |  Mensaje de appreciacion por parte del Project Manager |

Assistant - la clase representa a los asistentes de eventos y proyectos

| Atributo | Descripcion |
| - | - |
| tasks | tareas dadas al estudiante |
| projects | proyectos asignados al ayudante |


Project - la clase Projecto representa 
| Atributo | Descripcion |
| - | - | 
| processes | proceso de ejecucion del proyecto |
| title | titulo del projecto |
| description | descripcion del proyecto |
| members | los miembros que seran asignados al proyecto |

| Metodo | Descripcion |
| - | - | 
| addMember | se agregan miembros al proyecto |
| removeMember | se remueven miembros al proyecto |




## 4.8. Database Design.
### 4.8.1. Database Diagram.
![Database Diagram](../assets/diagrams/database_diagram.png)

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
- Trello [https://trello.com](https://trello.com):
 Trello es una aplicación web de gestión de proyectos compatible con la mayoria de navegadores. Se utilizó Trello para la organización y registro de las tareas por hacer, las que están en proceso y las realizadas. De esta forma podemos tener control acerca del avance del proyecto y las actividades de cada uno de los miembros del equipo.

#### Product UX/UI Design
- Miro [https://miro.com](https://miro.com):
 Miro ha sido empleado en el desarrollo de los escenarios mapping y escenario mapping para ambos segmentos objetivos.

- Figma [https://figma.com](https://figma.com):
 Esta herramienta fue de vital importancia para la creación de los wireframes, mockups y mobile applications prototyping de manera colaborativa. Asimismo, su acceso es gratuito al contar con una cuenta registrada.

#### Software Developement
- Landing Page:
El desarrollo del landing page se llevó a cabo con las tecnologías de Vite + React. Vite es un entorno de desarrollo web que permite la creación de aplicaciones web modernas con React, Vue, Svelte y Vanilla JS. Para la creación de la landing page se utilizó React como librería de JavaScript.

- Frontend Web Application:
La aplicación web implica tener claro los conceptos básicos de HTML5, CSS3 y JavaScript, ya que se utilizará Vue como framework de JavaScript.

#### IDE's de desarrollo
- WebStorm [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/):
WebStorm es un entorno de desarrollo integrado (IDE) creado por JetBrains. Este entorno de desarrollo nos proporcionará distintas herramientas para agilizar el proceso de desarrollo

#### Software Testing
- Para las pruebas de testeo software, tanto de la landing page como de la aplicación web, se emplearon las herramientas de desarrollador de los principales navegadores web como Google Chrome [https://www.google.com/chrome/](https://www.google.com/chrome/), Microsoft Edge [https://www.microsoft.com/en-us/edge](https://www.microsoft.com/en-us/edge) y Mozilla Firefox [https://www.mozilla.org/en-US/firefox/browsers/](https://www.mozilla.org/en-US/firefox/browsers/). Estos navegadores cuentan con aplicaciones desktop y móviles las cuáles son totalmente gratuitas. En el caso de desktop podemos instalarlos desde sus sitios oficiales, en el caso de móvil, desde la tienda de aplicaciones del sistema operativo en cuestión.

#### Software Deployment
- Vercel [https://vercel.com](https://vercel.com):
Vercel es un servicio proporcionado por Zeit, Inc. que permite a los desarrolladores implementar aplicaciones web estáticas y dinámicas sin problemas. Para utilizar esta plataforma es necesario tener una cuenta registrada.

#### Software Documentation
- Markdown [https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax):
Markdown es un lenguaje de marcado ligero que nos permite formatear texto de manera sencilla utilizando un formato de texto plano. De esta forma documentamos la información importante acerca del contexto, organización, producción y creacíon del proyecto.

- LucidChart: [https://lucidchart.com/](https://lucidchart.com/):
LucidChart es una plataforma que cuenta con opciones para la creación de diagramas, mapas mentales, flujos, con el uso de plantillas y tableros con edición en tiempo real. Fue utilizado en el desarrollo del diagrama de clases UML, así como los Wireflows y User Flows.

- Structurizr [https://structurizr.com/](https://structurizr.com/):
Esta herramienta permite crear los diagramas C4 de manera rápida con una sintaxis similar a un lenguaje de programación. Para utilizar esta aplicación web hace falta tener una cuenta registrada.

- Vertabelo: [https://www.vertabelo.com/](https://www.vertabelo.com/)
Es una aplicación web colaborativa que facilita el diseño e implementación de bases de datos en una amplia variedad de motores. 

### 5.1.2. Source Code Management.
Para el proyecto se creó una organización en Github, que permitiría el trabajo colaborativo para todos los integrantes del equipo, además de contar con un repositorio para el control de versiones del código fuente. Se utilizó la herramienta de control de versiones Git, la cual es una herramienta de código abierto que permite el control de versiones de archivos de manera eficiente.  
**Organización**: [https://github.com/orgs/AplicacionesWeb-WX54/]  (https://github.com/orgs/AplicacionesWeb-WX54/)  
**Landing Page**: [https://github.com/AplicacionesWeb-WX54/LandingPage-AidManager](https://github.com/AplicacionesWeb-WX54/LandingPage-AidManager)

Para llevar a cabo la organización de desarollo del código, se crearon las siguientes ramas:
- **main**: Rama principal del proyecto, donde se encuentra el código estable y funcional.
- **development**: Rama de desarrollo, donde se realizan las integraciones de las funcionalidades de cada uno de los miembros del equipo.
- **feature/feature-name**: Ramas de funcionalidades, donde se desarrollan las funcionalidades de cada uno de los miembros del equipo.

## Commit Conventions:
El formato de nuestros commits sigue la estructura de los “Conventional Commits” en su versión 1.0.0 (https://www.conventionalcommits.org/en/v1.0.0/) con el objetivo de proporcionar una lectura sencilla de los mismos. Por ello seguimos el siguiente formato:
"< type>[optional scope]: < description>"
Donde:
- type: Especifica el tipo de cambio realizado, únicamente puede ser feat, fix, update, etc.
- scope: Es el alcance que tiene nuestro commit.
- description: Es un breve resumen de los cambios de código.

### 5.1.3. Source Code Style Guide & Conventions.

Para el desarrollo del código en HTML y CSS se decidió seguir la convención de Google HTML/CSS Style Guide. Entre las más importantes destacan:

* Se debe declarar el tipo de documento al principio del archivo con `<!DOCTYPE html>`.
* Indicar los meta tags.
* El elemento `<title>` se debe ubicar entre las etiquetas `<head>`.
* La identación es de dos espacios a la vez.
* Usar solo minúsculas para los elementos HTML, atributos, propiedades, valores y selectores CSS.
* Encerrar entre comillas los atributos de los elementos HTML.
* Cada elemento HTML debe tener su etiqueta de cierre.
* Evitar largas líneas de código.
* Indicar el ancho y alto de las imágenes, así como el texto alternativo (`alt`).

*Para el desarrollo del código en JavaScript, se eligió la convención Google JavaScript Style Guide. Algunas de estas convenciones son:*

* Cada línea de código debe terminar con un punto y coma (`;`).
* Tanto las variables como funciones deben estar en Camelcase.
* Los valores strings deben estar entre comillas simples.
* La identación del contenido es de +2.
* Se debe evitar definir variables con la sentencia `var`. En su lugar, se recomienda `let` y `const`.

*Para el desarrollo de los acceptance test con el lenguaje Gherkin, se seleccionó “Gherkin Conventions for Readable Specifications”. Entre ellas están:*

* Para describir los pasos del escenario, utilizar las palabras "Give", "When", "Then" y "And".
* Identar los pasos que comienzan con "And".
* Agregar líneas entre pasos.
* Encerrar entre comillas simples los parámetros.
* Usar un comentario separador y dos líneas en blanco entre cada escenario.


### 5.1.4. Software Deployment Configuration.

En este apartado, detallaremos los pasos realizados para el despliegue de la Landing Page utilizando el servicio "Vercel".

1. Luego de acceder a https://www.vercel.com/ e iniciar sesión o crear una cuenta, nos dirigimos al apartado "New Project" y conectamos nuestra cuenta de github para tener acceso a los respositorios disponibles.

<center>
    <img src="../assets/evidences-deployment/import-git-repository-image.jpeg" alt="Imagen del compañero" style="width:80%">
</center><br/>

2. Seleccionamos la organizacion "AplicacionesWeb-WX54" y nos dirigimos al repositorio de la Landing Page, la cual es "LandingPage-AidManager" y luego la importamos, una vez importado, realizamos la configuracion del proyecto para hacer el deploy.

<center>
    <img src="../assets/evidences-deployment/configure-project-image.jpeg" alt="Imagen del compañero" style="width:80%">
</center><br/>

1. Después de realizar la acción, observamos que el despliegue se realizó correctamente, adjuntamos los detalles del despliegue a producción.

<center>
    <img src="../assets/evidences-deployment/production-deploy-image.jpg" alt="Imagen del compañero" style="width:80%">
</center><br/>


## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

<table>
    <thead>
        <tr>
            <th> Sprint #</th>
            <th> Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold; text-align: center" colspan="2"> Sprint Planing Background</td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Date</td>
            <td> 12/04/2024 </td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Time</td>
            <td> 14:00 horas (GMT-5)</td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Location</td>
            <td> Modalidad remota por Discord.
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Prepared By</td>
            <td> Y.E.S.I Team
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Attendees (to planning meeting)</td>
            <td> Todos los miembros del equipo Y.E.S.I
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Sprint n – 0 Review Summary</td>
            <td> Dado que es nuestro primer sprint de desarrollo no existe
                un summary del sprint anterior.
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Sprint n – 1 Retrospective Summary</td>
            <td>
        </tr>
    <tbody>
<table>


#### 5.2.1.2. Sprint Backlog 1.

| Id   | Title            | Id   | Title                           | Description                                                                           | Estimations (Hours) | Assigned To                       | Status |
|------|------------------|------|---------------------------------|---------------------------------------------------------------------------------------|---------------------|-----------------------------------|--------|
| CC01 | Testimonials     | C01  | Sección Testimonials responsive | Desarrollo e implementación de los estilos que corresponden a la sección Testimonials | 3                   | Arian Rodriguez Vargas      | Done   |
| CC02 | BrandCarousel         | C02  | Sección Features responsive     | Desarrollo e implementación de los estilos que corresponden a la sección BrandCarousel     | 3                   | Peña Ramirez, Sebastian Piñera      | Done   |
| CC03 | Button component | C03  | Button Design responsive        | Desarrollo e implementación de los estilos que corresponden al Button                 | 2                   | Esteban Garcia, Nicolas Sebastian | Done   |
| CC04 | Navbar component | C04  | Sección Navbar responsive       | Desarrollo e implementación de los estilos que corresponden a la sección Navbar       | 3                   | Esteban Garcia, Nicolas Sebastian | Done   |
| CC05 | Contact          | C05  | Sección Contact responsive      | Desarrollo e implementación de los estilos que corresponden a la sección Contact      | 3                   | Fabia Alejandra, Herrera Aguirre  | Done   |
| CC06 | Footer           | C06  | Sección Footer responsive       | Desarrollo e implementación de los estilos que corresponden a la sección Footer       | 2                   | Fabia Alejandra, Herrera Aguirre  | Done   |
| CC07 | Hero             | C07  | Sección Hero responsive         | Desarrollo e implementación de los estilos que corresponden a la sección Hero         | 4                   | Sebastian Ramirez Hotman | Done   |
| CC08 | About            | C08  | Sección About responsive        | Desarrollo e implementación de los estilos que corresponden a la sección About        | 3                   | Sebastian Ramirez Hotman | Done   |
| CC10 | Service           | C010 | Sección Prices responsive       | Desarrollo e implementación de los estilos que corresponden a la sección Service       | 2                   | Arian Rodriguez Vargas       | Done   |

**Link to product backlog table:** https://github.com/orgs/AplicacionesWeb-WX54/projects/2 

<br/>
<img src="../assets/collaboration-insights/sprint-backlog.jpeg" alt="Captura Sprint 1 en Trello" width="100%">

#### 5.2.1.3. Development Evidence for Sprint Review.

| Repository                 | Branch                   | Commit ID | Commit Message                                                                      | Commit Message Body | Commited On(Date) |
|----------------------------|--------------------------|-----------|-------------------------------------------------------------------------------------|---------------------|-------------------|
| LandingPage-AidManager | main          | b28816c   | initial commit                                                                   | -                   | 7/04/2024        |
| LandingPage-AidManager | feature/footer           | b28816c   | Update Footer.jsx                                                                   | -                   | 9/04/2024        |
| LandingPage-AidManager | feature/contact          | d429bb8   | Update Contact.jsx                                                                  | -                   | 7/04/2024        |
| LandingPage-AidManager | feature/service | a624c36   | feat: add ServiceCar Component and Service Component                 | -                   | 8/04/2024        |
| LandingPage-AidManager | feature/testimonials     | a16c0c0   | feat: add TestimonialCard Component and Testimonials Component | -                   | 12/04/2024        |
| LandingPage-AidManager | feature/about            | 7e85194   | Update About.jsx                                                                    | -                   | 10/04/2024        |
| LandingPage-AidManager | feature/hero             | 56ab21c   | Update Hero.jsx                                                                     | -                   | 10/04/2024        |
| LandingPage-AidManager | feature/service          | c663461   | feat: Service section added                                                         | -                   | 12/04/2024        |
| LandingPage-AidManager | feature/navbar           | 1d527f8   | feat: Navbar added                                                                  | -                   | 7/04/2024        |
| LandingPage-AidManager | feature/brandCarousel           | 1d527f8   | feat: brandCarousel added added                                                                  | -                   | 11/04/2024        |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

En este sprint se realizaron las pruebas de aceptación en la herramienta de Gherkin. En el siguiente link se puede encontrar dichas pruebas de aceptación: https://github.com/AplicacionesWeb-WX54/Acceptance-Tests.git

| Repository          | Branch | Commit ID                                | Commit Message                     | Commit Message (Body) | Committed on (Date) |
|---------------------|--------|------------------------------------------|------------------------------------|-----------------------|---------------------|
| Acceptance-Test     | main   | 91507dffacabf6415efaa4e663c85756521a9f04 | Initial commit                     | -                     | 14/04/2024          |
| Acceptance-Test     | main   | 822c79119c080f39585630ce640ab7ee1c3c692f | feat: Added us-01 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | a24f512b364b04682994f111d1d4a9a05fa79f74 | feat: Added us-02 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | 00f760dedabd22b97928d7bf36dccf7ebe51cf67 | feat: Added us-03 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | 134caed2aea32dee6a049d956466d8580e0b1ab8 | feat: Added us-04 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | cd8cc231ff1973cbffd9adec1839191a5d98ea62 | feat: Added us-05 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | b8b7f2389d0f4e04f3e75dcfaa22d9f4d1d547d9 | feat: Added us-06 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | cd8cc231ff1973cbffd9adec1839191a5d98ea62 | feat: Added us-07 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | b8b7f2389d0f4e04f3e75dcfaa22d9f4d1d547d9 | feat: Added us-07 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | 56a8ed5b3dfc62a1be1658cfc6d08d00e8cbcf85 | feat: Added us-17 acceptance test  | -                     | 14/04/2024          |
| Acceptance-Test     | main   | e3b0c44298fc1c149afbf4c8996fb92427ae41e4 | feat: Added us-18 acceptance test  | -                     | 14/04/2024          |


#### 5.2.1.5. Execution Evidence for Sprint Review.

Para esta entrega, el equipo AidManager logró implementar exitosamente la landing page, en la cual se brindará información específica para conocer nuestra misión como startup, así como los servicios que ofrecemos en nuestra aplicación web.

**URL Landing Page:** https://landing-page-aid-manager-37nb.vercel.app/

**Hero en version desktop**

<img src="../assets/evidences-landing-page/hero-section-desktop.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**Hero en version mobile**

<img src="../assets/evidences-landing-page/hero-section-mobile.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

**About en version desktop**

<img src="../assets/evidences-landing-page/about-section-desktop.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**About en version mobile**

<img src="../assets/evidences-landing-page/about-section-mobile.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

**Service en version desktop**

<img src="../assets/evidences-landing-page/service-section-desktok.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**Service en version mobile**

<img src="../assets/evidences-landing-page/service-section-mobile.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

**Carousel en version desktop**

<img src="../assets/evidences-landing-page/carousel-section-desktop.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**Carousel en version mobile**

<img src="../assets/evidences-landing-page/carousel-section-mobile.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

**Testimonials en version desktop**

<img src="../assets/evidences-landing-page/testimonials-section-desktop.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**Testimonials en version mobile**

<img src="../assets/evidences-landing-page/testimonials-section-mobile.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

**Contact en version desktop**

<img src="../assets/evidences-landing-page/contact-section-desktop.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**Testimonials en version mobile**

<img src="../assets/evidences-landing-page/contact-section-mobile-1.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

<img src="../assets/evidences-landing-page/contact-section-mobile-2.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

//

**Footer en version desktop**

<img src="../assets/evidences-landing-page/footer-section-desktop.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

**Footer en version mobile**

<img src="../assets/evidences-landing-page/footer-section-mobile.jpeg" alt="Imagen del compañero" style="width:50%"><br/>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En este sprint los miembros de AidManager Solutions complementaron satisfactoriamente las tareas propuestas. El sprint estuvo relacionado mayormente con el diseño y desarrollo del software. A lo largo del desarrollo se fueron realizando correcciones a errores dentro del codigo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para el sprint presentado de la landing page se optó por varias herramientas para su desarrollo y despliegue en la web de manera pública.

* Git: Se utilizó para el control de versiones del código fuente.
* GitFlow: Se utilizó para ver el avance de los integrantes del equipo.
* GitHub: Se utilizó para crear el repositorio de la landing page, * donde se subió el código fuente.
* Vercel: Se utilizó esta herramienta ya que nos ofrece un despliegue sin costo de manera rápida y fácil, además que se puede vincular

Evidencias de despliegue en la plataforma Vercel:

<img src="../assets/evidences-deployment/production-deploy-image.jpg" alt="Imagen del compañero" style="width:100%"><br/>

#### 5.2.1.8. Team Collaboration Insights during Sprint.

Los integrantes del equipo, colaboraron de manera equitativa para desarrollar los diferentes features de la landing page, se utilizó la herramienta de GitFlow para manejar las actualizaciones que iba realizando cada uno, para ello existian las ramas: main, development, features, de modo que cada uno trabajaba en su rama feature, para luego trasladarlo a development y ver que este todo correcto y finalmente desplegarlo a producción con la rama main. Las evidencias muestran como los integrantes realizaron diferentes commits para los features.

A continuación se mostrarán los gráficos de insights durante el sprint:

<img src="../assets/collaboration-insights/overview-landing.jpeg" alt="Imagen del compañero" style="width:100%"><br/>


Flujo de trabajo entre las ramas:

<img src="../assets/collaboration-insights/network-graph.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

Evidencia de contribuciones:

<img src="../assets/collaboration-insights/commit-evidences.jpeg" alt="Imagen del compañero" style="width:100%"><br/>

# Conclusiones
TB1: AidManager se centra en la creación de una aplicación web que permita a las ONGs gestionar sus proyectos de manera eficiente, así como a los voluntarios colaborar en las diferentes actividades que se realizan. La landing page es el primer paso para dar a conocer la startup y los servicios que ofrece, de manera que se pueda captar la atención de los posibles usuarios. Se ha logrado implementar de manera exitosa la landing page, la cual se encuentra desplegada en la web de manera pública. Los integrantes del equipo colaboraron de manera equitativa para desarrollar los diferentes features de la landing page, se utilizó la herramienta de GitFlow para manejar las actualizaciones que iba realizando cada uno, para ello existían las ramas: main, development, features, de modo que cada uno trabajaba en su rama feature, para luego trasladarlo a development y ver que este todo correcto y finalmente desplegarlo a producción con la rama main. Las evidencias muestran como los integrantes realizaron diferentes commits para los features.

# Recomendaciones.
TB1: Se recomienda seguir trabajando de manera colaborativa y equitativa, de manera que se pueda lograr los objetivos propuestos en el tiempo establecido. Se recomienda seguir utilizando las herramientas de GitFlow para manejar las actualizaciones que se vayan realizando en el código fuente, de manera que se pueda tener un control de las versiones y de los cambios que se vayan realizando. Se recomienda seguir utilizando las herramientas de GitFlow para manejar las actualizaciones que se vayan realizando en el código fuente, de manera que se pueda tener un control de las versiones y de los cambios que se vayan realizando.

# Bibliografía
``` 

Nonprofits, D. F. (2023, 7 agosto). Data Analytics for Nonprofits.
        (https://www.linkedin.com/pulse/data-analytics-nonprofits-digitalfornonprofits/)


Everyone Thrives Consultant Services. (2023, 15 diciembre). Data: The Key to 
        Unlocking Nonprofit Success. https://www.linkedin.com/pulse/,data-analytics-nonprofits-digitalfornonprofits/data-key-unlocking-nonprofit-success-everyone-thrives-4btnc/


```

# Anexos
```

Video TB1
https://upcedupe-my.sharepoint.com/personal/u202211894_upc_edu_pe/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fu202211894%5Fupc%5Fedu%5Fpe%2FDocuments%2FAppWebWX54%2FVideo&ga=1

```





