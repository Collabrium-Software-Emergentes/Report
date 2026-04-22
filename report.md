<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" alt="UPC Logo">
</div>

<div align="center">

# Universidad Peruana de Ciencias Aplicadas

### **Curso:** Arquitectura de Software Emergentes
### **NRC:** 
### **Profesor:** Marino Humberto Jara Palacios
### **Ingeniería de Software**

## Informe de Trabajo Final

### **Nombre del Startup:** Collabrium
### **Nombre del producto:** SynHub

</div>

---

## Integrantes

| Nombres                           | Código     |
| --------------------------------- | ---------- |
| Acuña Tomas, Diego Rolin          |            |
| Gomez Hurtado, Miguel Angel       | u202220294 |
| Guerrero Vasquez, Jhon Danny      | u202116246 |
| Paitan Pumacahua, Max Anthony     |            |
| Paiva Quispe, Josue Gonzalo       |            |

---

<div align="center">

*Abril 2026*

</div>

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| ------- | ----- | ----- | --------------------------- |
| 0.1 | 2026-04-14 | Miguel Gomez | Creación de la primera versión del documento |

## Project Report Collaboration Insights



## Contenido

- [Universidad Peruana de Ciencias Aplicadas](#universidad-peruana-de-ciencias-aplicadas)
- [Curso: Arquitectura de Software Emergentes](#curso-arquitectura-de-software-emergentes)
- [NRC](#nrc)
- [Profesor: Marino Humberto Jara Palacios](#profesor-marino-humberto-jara-palacios)
- [Ingeniería de Software](#ingeniería-de-software)
- [Informe de Trabajo Final](#informe-de-trabajo-final)
- [Nombre del Startup: Collabrium](#nombre-del-startup-collabrium)
- [Nombre del producto: SynHub](#nombre-del-producto-synhub)
- [Integrantes](#integrantes)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [1. Capítulo I: Introducción](#1-capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [2. Capítulo II: Requirements Elicitation & Analysis](#2-capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [3. Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [4. Capítulo IV: Strategic-Level Software Design](#4-capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)

## Student Outcome



---
# **<span class="mark">Capítulo I: Introducción</span>** 

## **<span class="mark">1.1. Startup Profile</span>** 

### <span class="mark">1.1.1. Descripción de la Startup</span>

<span class="mark">Collabrium es una startup tecnológica que nace con el
propósito de mejorar la forma en que las personas trabajan y colaboran
en equipo. A través de su plataforma principal, SynHub, busca ofrecer un
espacio digital accesible e intuitivo que ayude a los grupos académicos,
laborales o comunitarios a organizar sus actividades, repartir
responsabilidades de manera justa y mantener una comunicación clara y
constante.</span>

<span class="mark">Collabrium entiende que detrás de cada proyecto hay
personas con diferentes ritmos, talentos y necesidades. Por ello, su
propuesta no se limita a gestionar tareas, sino que promueve un entorno
de corresponsabilidad y equilibrio, donde cada integrante pueda aportar
de forma activa, sentirse escuchado y crecer junto a su equipo.</span>

<span class="mark">**Visión:** Ser un referente global en la creación de
soluciones digitales que fortalezcan la organización, la comunicación y
el bienestar dentro de los equipos, contribuyendo a construir
comunidades más colaborativas, equilibradas y humanas.</span>

<span class="mark">**Misión:** Desarrollar herramientas innovadoras y
accesibles que acompañen a las personas en sus dinámicas de trabajo en
equipo, facilitando la coordinación, la distribución justa de
responsabilidades y el diálogo constante. Collabrium busca que cada
grupo, sin importar su contexto, logre trabajar de forma más organizada,
eficiente y en armonía.</span>

<span class="mark">  
1.1.2. Perfiles de integrantes del equipo</span>

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 64%" />
</colgroup>
<thead>
<tr>
<th><mark>Integrante</mark></th>
<th><mark>Descripción:</mark></th>
</tr>
<tr>
<th style="text-align: center;"><img src="./media/image1.jpg"
style="width:1.67188in;height:2.96712in" /></th>
<th style="text-align: left;"><p><mark>Jhon Danny Guerrero Vasquez -
U202116246</mark></p>
<p><mark>Soy ingeniero de software especializado en backend con Java y
frameworks como Spring. Me enfoco en crear microservicios escalables y
eficientes, aplicando programación reactiva con Spring WebFlux. Tengo
experiencia en diseño de APIs RESTful y optimización de bases de datos
como MySQL y PostgreSQL. Además, implementó pruebas unitarias y sigo
metodologías Agile para garantizar la calidad del código. Estoy
comprometido con la integración continua en los aportes de cada
integrante de mi equipo.</mark></p></th>
</tr>
<tr>
<th><img src="./media/image2.jpg"
style="width:2.08333in;height:2.15278in" /></th>
<th style="text-align: left;"><p><mark>Acuña Tomas, Diego Rolin -
U202221436</mark></p>
<p><mark>Soy estudiante de Ingeniería de Software en la UPC, actualmente
cursando el octavo ciclo. Durante mi formación académica he adquirido
sólidos conocimientos en múltiples lenguajes de programación y
frameworks, desarrollando competencias especializadas en frontend,
backend y bases de datos. Me interesa especialmente contribuir a
proyectos de código abierto, como Angular, Spring y otras herramientas
modernas. Me considero una persona curiosa y proactiva, con una visión
optimista del futuro tecnológico.</mark></p></th>
</tr>
<tr>
<th style="text-align: center;"><img src="./media/image3.jpg"
style="width:2.01042in;height:2.35417in" /></th>
<th style="text-align: left;"><p><mark>Paitan Pumacahua, Max Anthony -
U201314454</mark></p>
<p><mark>Soy Max Anthony y tengo 29 años. Estoy retomando Ingeniería de
Software como segunda carrera, ya que siempre tuvo ello como objetivo;
en la actualidad, me encuentro cursando el noveno ciclo. Entre mis
habilidades están: Ágil capacidad de análisis -tanto individual como
también en colectivo-, empático en un contexto determinado -tomando
decisiones de manera sensata-, y puedo ser tanto gestor como un
participante activo dentro de un grupo de trabajo.</mark></p></th>
</tr>
<tr>
<th><img src="./media/image4.jpg"
style="width:2.09375in;height:2.81852in" /></th>
<th style="text-align: left;"><p><mark>Josue Gonzalo Paiva Quispe -
U202119095</mark></p>
<p><mark>Soy estudiante de Ingeniería de Software, me encuentro cursando
el 8vo ciclo y realizando prácticas pre profesionales como fullstack
junior web developer</mark></p></th>
</tr>
<tr>
<th></th>
<th style="text-align: left;"></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

## **<span class="mark">1.2. Solution Profile</span>**

### <span class="mark">1.2.1 Nombre del producto</span>

<span class="mark">El producto principal de Collabrium lleva por nombre
SynHub. El término surge de la combinación de dos ideas clave: “Syn”,
inspirado en “sincronizar” y “sinergia”, y “Hub”, entendido como un
centro o punto de encuentro.</span>

<span class="mark">Este nombre refleja la esencia del producto: ser un
espacio digital donde los equipos pueden sincronizar esfuerzos,
centralizar la organización y generar sinergias que fortalezcan la
colaboración.</span>

### <span class="mark">1.2.2 Antecedentes y problemática</span>

<span class="mark">What</span>

- <span class="mark">¿Cuál es el problema?</span>

<span class="mark">El problema radica en la baja adopción de soluciones
diseñadas para la organización colaborativa. A pesar de la
disponibilidad de diversas herramientas digitales, muchas personas y
grupos siguen recurriendo a métodos improvisados o poco eficientes para
coordinar actividades, lo que genera distribución desigual de tareas,
falta de seguimiento, comunicación fragmentada y pérdida de
productividad.</span>

- <span class="mark">¿Cuál es la relación con la persona en
  cuestión?</span>

<span class="mark">La relación es ofrecer a los miembros de equipos o
grupos una herramienta accesible y centrada en sus necesidades reales,
que facilite una organización más clara, una distribución de tareas
efectiva y una comunicación más fluida, promoviendo así su uso y
adopción en el día a día.</span>

<span class="mark">When</span>

- <span class="mark">¿Cuándo sucede el problema?</span>

<span class="mark">El problema surge cuando los equipos y grupos deben
coordinar actividades, repartir responsabilidades o mantener una
comunicación constante para alcanzar objetivos comunes.</span>

- <span class="mark">¿Cuándo utiliza el cliente el producto?</span>

<span class="mark">El cliente utiliza SynHub cuando necesita organizar,
coordinar o participar en actividades grupales de manera eficiente, ya
sea al inicio de un proyecto, durante la planificación de tareas o en el
seguimiento de responsabilidades.</span>

<span class="mark">Where</span>

- <span class="mark">¿Dónde está el cliente cuando usa el
  producto?</span>

<span class="mark">El cliente utiliza SynHub desde cualquier lugar con
acceso a Internet, ya sea en su hogar, en la oficina, en el aula o
incluso mientras se traslada, dependiendo de la plataforma que
utilice.</span>

- <span class="mark">¿Dónde surge el problema?</span>

<span class="mark">El problema surge dentro de los propios entornos
donde se desarrollan actividades grupales, como oficinas, instituciones
educativas, organizaciones comunitarias o espacios colaborativos, en los
que la coordinación efectiva es clave para lograr objetivos
comunes.</span>

<span class="mark">Who</span>

- <span class="mark">¿Quienes se ven involucrados en el problema?</span>

<span class="mark">Se ven involucrados tanto los organizadores o
coordinadores de equipos (como líderes de proyecto, docentes, jefes de
área o representantes comunitarios) miembros de equipos de trabajo (como
estudiantes, colaboradores, voluntarios o participantes) que enfrentan
dificultades para organizarse, distribuir responsabilidades y
comunicarse eficazmente. Why</span>

- <span class="mark">¿Cuáles son las causas del problema?</span>

<span class="mark">Las causas del problema radican en la falta de
adopción de soluciones para la organización de equipos. Esto se debe, en
gran parte, a la resistencia al cambio, la baja percepción de valor
inmediato y la falta de hábitos digitales consolidados en ciertos
grupos. Aunque existen herramientas disponibles, muchas personas
prefieren métodos tradicionales como chats informales, hojas de cálculo
o notas físicas, ya que perciben las apps como innecesarias, complicadas
o poco integradas a su rutina diaria. Además, la escasa promoción
interna o el desconocimiento de las funcionalidades clave también
limitan su uso efectivo.</span>

<span class="mark">How</span>

- <span class="mark">¿En qué condiciones los clientes usan nuestro
  producto?</span>

<span class="mark">Los clientes usan SynHub cuando forman parte de
equipos o grupos que necesitan coordinar actividades de manera
organizada y colaborativa, especialmente en contextos donde hay
múltiples tareas, horarios variables y responsabilidades
compartidas.</span>

<span class="mark">How Much</span>

- <span class="mark">¿Cuál es la magnitud del problema?</span>

<span class="mark">La magnitud del problema de desorganización y
comunicación ineficaz en equipos es considerable. Según el State of
Teams Report de Atlassian (2021), solo el 17% de los equipos se
consideran "saludables", mientras que el 54% son parcialmente saludables
y el 29% directamente insalubres (p. 12). Además, el 57% de los
participantes admitió que sus equipos no operan con la eficiencia
necesaria, lo que genera retrasos y afecta la productividad (Atlassian,
2021, p. 18). Esto se agrava por la falta de conexión interpersonal: el
56% de los miembros reportó sentirse poco vinculado con sus compañeros,
y el 37% mencionó que no puede expresar ideas libremente por falta de
seguridad psicológica (Atlassian, 2021, p. 24).</span>

### <span class="mark">1.2.3. Lean UX Process</span>

#### <span class="mark">1.2.3.1. Lean UX Problem Statements</span>

<span class="mark">En el entorno actual, tanto en contextos familiares
como laborales y comunitarios, los grupos enfrentan grandes desafíos
para coordinar tareas y mantener una comunicación fluida y estructurada
entre sus miembros. Aunque existen herramientas digitales como
aplicaciones de mensajería o tableros de tareas, muchas de estas
soluciones son fragmentadas, poco integradas o carecen de una lógica
colaborativa adaptada al trabajo en equipo cotidiano.</span>

<span class="mark">Esta falta de soluciones centralizadas y
personalizables genera desorganización, distribución desigual de
responsabilidades, olvidos, retrasos y fricciones entre los integrantes
de un grupo. Ya sea en un entorno familiar, una oficina, un equipo de
voluntariado o un pequeño negocio, la necesidad de una herramienta
unificada que facilite la colaboración, la planificación y el
seguimiento de actividades es cada vez más evidente.</span>

<span class="mark">SynHub nace como una plataforma digital diseñada para
cubrir esta brecha: una solución integral para la gestión de grupos que
permite distribuir tareas, visualizar reportes, recibir recordatorios y
mejorar la eficiencia del trabajo en conjunto.</span>

#### <span class="mark">1.2.3.2. Lean UX Assumptions</span>

<span class="mark">User Assumptions (Suposiciones de Usuario)</span>

- <span class="mark">¿Quién es el usuario?: El usuario es alguien que
  busca una solución para organizar las tareas en un equipo y mejorar la
  comunicación entre los miembros.</span>

- <span class="mark">¿Dónde encaja nuestro producto en su trabajo o
  vida?: Nuestro producto encaja en actividades grupales donde el
  usuario es partícipe junto a otros miembros, facilitando la gestión de
  tareas y responsabilidades dentro del equipo.</span>

- <span class="mark">¿Qué problemas resuelve nuestro producto?: Nuestro
  producto resuelve problemas de desorganización y falta de comunicación
  dentro del equipo.</span>

- <span class="mark">¿Cuándo y cómo se usa nuestro producto?: Nuestro
  producto se usa cuando hay necesidad de organización en actividades
  grupales, especialmente en momentos de planificación, seguimiento de
  tareas y coordinación entre miembros del equipo.</span>

- <span class="mark">¿Qué características son importantes?: Las
  características importantes incluyen la asignación de tareas, el
  seguimiento del avance del equipo, la visualización de horarios del
  equipo, la comunicación estructurada y la posibilidad de adaptar la
  herramienta a diferentes dinámicas de grupo.</span>

- <span class="mark">¿Cómo debe verse y comportarse nuestro producto?:
  Nuestro producto debe tener una interfaz intuitiva y amigable, que
  permita a los usuarios navegar fácilmente entre las distintas
  funcionalidades.</span>

<span class="mark">Business Assumptions (Suposiciones de Negocio)</span>

- <span class="mark">Necesidades y problemas: Creemos que los equipos de
  trabajo tienen la necesidad de organizar sus tareas de manera
  eficiente y mejorar la comunicación entre sus miembros.</span>

- <span class="mark">Plataforma: Estas necesidades se pueden resolver a
  través de una aplicación que ofrezca herramientas para la gestión de
  tareas y la comunicación, proporcionando una experiencia fluida y
  accesible.</span>

- <span class="mark">Segmentación: Los usuarios de la aplicación serán
  coordinadores de equipos e integrantes de esos equipos que buscan una
  forma accesible de organizar sus responsabilidades.</span>

- <span class="mark">Comportamientos: El valor principal que un usuario
  quiere obtener de nuestro servicio es la facilidad de uso y la mejora
  en la organización y comunicación dentro del equipo.</span>

- <span class="mark">Beneficios: Los usuarios obtendrán beneficios como
  una mejor organización personal, mayor claridad sobre sus
  responsabilidades dentro del equipo, y una sensación de logro al
  completar tareas.</span>

- <span class="mark">Captación de clientes: Adquiriremos la mayoría de
  nuestros usuarios a través de campañas de marketing digital y
  recomendaciones de usuarios actuales en el ámbito laboral y
  educativo.</span>

- <span class="mark">Modelo de ingresos: Generaremos ingresos a través
  de la clasificación de la aplicación como uno de pago.</span>

- <span class="mark">Competencia: Nuestra principal competencia en el
  mercado serán aplicaciones similares que ofrecen funciones de
  organización y gestión de tareas.</span>

- <span class="mark">Ventaja competitiva: Superaremos a la competencia
  gracias a nuestro enfoque en la personalización, la facilidad de uso y
  la integración de funciones específicas para la gestión de
  equipos.</span>

#### <span class="mark">1.2.3.3. Lean UX Hypothesis</span>

<span class="mark">Hypothesis Statement 01:</span>

- <span class="mark">Creemos que el producto encaja en actividades
  grupales donde el usuario es partícipe junto a otros miembros,
  facilitando la gestión de tareas y responsabilidades dentro del
  equipo.</span>

- <span class="mark">Sabremos que estamos en lo correcto cuando veamos
  comentarios positivos sobre la facilidad de uso y la integración del
  producto en la dinámica de equipo.</span>

<span class="mark">Hypothesis Statement 02:</span>

- <span class="mark">Creemos que el producto resuelve problemas de
  desorganización y falta de comunicación dentro del equipo.</span>

- <span class="mark">Sabremos que estamos en lo correcto cuando los
  usuarios reporten una mejora en la organización y coordinación de su
  equipo mediante encuestas o reseñas.</span>

<span class="mark">Hypothesis Statement 03:</span>

- <span class="mark">Creemos que el producto se usa cuando hay necesidad
  de organización en actividades grupales, especialmente en momentos de
  planificación, seguimiento de tareas y coordinación.</span>

- <span class="mark">Sabremos que estamos en lo correcto cuando veamos
  un aumento en la frecuencia de uso de la aplicación.</span>

<span class="mark">Hypothesis Statement 04:</span>

- <span class="mark">Creemos que las características importantes
  incluyen la asignación de tareas, la visualización de horarios del
  equipo, conocer la disponibilidad de los miembros y la posibilidad de
  personalizar roles y permisos.</span>

- <span class="mark">Sabremos que estamos en lo correcto cuando veamos
  comentarios positivos de los usuarios sobre estas características y un
  aumento en la satisfacción del usuario.</span>

<span class="mark">Hypothesis Statement 05:</span>

- <span class="mark">Creemos que los equipos de trabajo tienen la
  necesidad de organizar sus tareas de manera eficiente y mejorar la
  comunicación entre sus miembros.</span>

- <span class="mark">Sabremos que estamos en lo correcto cuando veamos
  un aumento en la adopción del producto por parte de equipos y
  comentarios positivos sobre su utilidad.</span>

<span class="mark">Hypothesis Statement 06:</span>

- <span class="mark">Creemos que los usuarios serán coordinadores de
  equipos e integrantes que buscan una forma accesible de organizar sus
  responsabilidades.</span>

- <span class="mark">Sabremos que estamos en lo correcto cuando la
  mayoría de los registros y perfiles de usuario coincidan con estos
  perfiles y necesidades.</span>

#### <span class="mark">1.2.3.4. Lean UX Canvas</span>

<img src="./media/image5.jpg"
style="width:6.26772in;height:3.94444in" />

## **<span class="mark">1.3. Segmento objetivo</span>** 

<span class="mark">Segmento Objetivo \#1: Coordinadores o Líderes de
Grupo</span>

<span class="mark">Este grupo incluye a personas que asumen la
responsabilidad de organizar y gestionar las actividades dentro de un
equipo o grupo. Pueden ser líderes de proyectos, responsables de
logística en voluntariados, administradores de espacios compartidos,
docentes coordinadores o encargados de comunidades (vecinales,
académicas o laborales). Estas personas buscan una herramienta que les
permita distribuir tareas, planificar actividades, hacer seguimiento del
cumplimiento y facilitar la comunicación interna. Características
clave:</span>

- <span class="mark">Edad: 25 a 60 años</span>

  - <span class="mark">Género: Ambos</span>

  - <span class="mark">Contexto: Trabajo en equipo (laboral, educativo,
    comunitario o institucional)</span>

  - <span class="mark">Ocupación: Líderes de proyectos, jefes de equipo,
    coordinadores, docentes, voluntarios, emprendedores</span>

  - <span class="mark">Uso de tecnología: Usuarios activos de
    plataformas colaborativas y herramientas de gestión de tareas (como
    Trello, Notion, Slack, etc.)</span>

  - <span class="mark">Necesidades: Distribuir responsabilidades,
    establecer fechas límite, tener visibilidad del progreso del equipo,
    mejorar la coordinación y reducir fricciones en la organización
    diaria.</span>

<span class="mark">Segmento Objetivo \#2: Miembros del Equipo o
Grupo</span>

<span class="mark">Corresponde a las personas que forman parte activa de
un grupo con tareas y roles específicos, pero que no necesariamente
tienen funciones administrativas. Incluye desde colaboradores de un
proyecto, estudiantes de un curso, miembros de una comunidad, hasta
empleados de una pequeña empresa. Este grupo busca mantenerse al tanto
de sus responsabilidades, recibir recordatorios, y colaborar de forma
clara y organizada con los demás. Características clave:</span>

- <span class="mark">Edad: 13 a 60 años</span>

  - <span class="mark">Género: Ambos</span>

  - <span class="mark">Contexto: Participación activa en un grupo
    organizado (laboral, educativo, social, comunitario, voluntariado,
    etc.)</span>

  - <span class="mark">Ocupación: Colaboradores, estudiantes,
    asistentes, voluntarios, trabajadores, participantes de redes de
    apoyo</span>

  - <span class="mark">Uso de tecnología: Habitualmente usan apps
    móviles, redes sociales, herramientas de trabajo remoto o
    colaboración básica</span>

  - <span class="mark">Necesidades: Consultar tareas, recibir
    recordatorios, gestionar su tiempo dentro del equipo, proponer
    cambios o ajustes, y mantenerse alineados con los objetivos
    grupales.</span>


---

# 2. Capítulo II: Requirements Elicitation & Analysis



## 2.1. Competidores



### 2.1.1. Análisis competitivo



### 2.1.2. Estrategias y tácticas frente a competidores



## 2.2. Entrevistas



### 2.2.1. Diseño de entrevistas



### 2.2.2. Registro de entrevistas



### 2.2.3. Análisis de entrevistas



## 2.3. Needfinding



### 2.3.1. User Personas



### 2.3.2. User Task Matrix



### 2.3.3. Empathy Mapping



### 2.3.4. As-is Scenario Mapping



## 2.4. Ubiquitous Language



---

# 3. Capítulo III: Requirements Specification



## 3.1. To-Be Scenario Mapping



## 3.2. User Stories



## 3.3. Impact Mapping



## 3.4. Product Backlog



---

# 4. Capítulo IV: Strategic-Level Software Design



## 4.1. Strategic-Level Attribute-Driven Design



### 4.1.1. Design Purpose



### 4.1.2. Attribute-Driven Design Inputs



#### 4.1.2.1. Primary Functionality (Primary User Stories)



#### 4.1.2.2. Quality attribute Scenarios



#### 4.1.2.3. Constraints



### 4.1.3. Architectural Drivers Backlog



### 4.1.4. Architectural Design Decisions



### 4.1.5. Quality Attribute Scenario Refinements



## 4.2. Strategic-Level Domain-Driven Design



### 4.2.1. EventStorming



### 4.2.2. Candidate Context Discovery



### 4.2.3. Domain Message Flows Modeling



### 4.2.4. Bounded Context Canvases



### 4.2.5. Context Mapping



## 4.3. Software Architecture



### 4.3.1. Software Architecture System Landscape Diagram



### 4.3.2. Software Architecture Context Level Diagrams



### 4.3.3. Software Architecture Container Level Diagrams



### 4.3.4. Software Architecture Deployment Diagrams


