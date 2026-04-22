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

| Nombres                       | Código     |
|-------------------------------|------------|
| Acuña Tomas, Diego Rolin      | u202221436 |
| Gomez Hurtado, Miguel Angel   | u202220294 |
| Guerrero Vasquez, Jhon Danny  | U202116246 |
| Paitan Pumacahua, Max Anthony | U201314454 |
| Paiva Quispe, Josue Gonzalo   | U202119095 |

---

<div align="center">

*Abril 2026*

</div>

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| ------- | ----- | ----- | --------------------------- |
| 0.1 | 2026-04-14 | Miguel Gomez | Creación de la primera versión del documento |
| 1.0 | 2026-04-21 | Miguel Gomez <br> Diego Acuña <br> Jhon Guerrero <br> Max Paitan <br> Josue Paiva | - Capítulo 1 <br> - Capítulo 2 <br> - Capítulo 3 <br> - Capítulo 4 |

## Project Report Collaboration Insights

TB1:


## Contenido

- [Universidad Peruana de Ciencias Aplicadas](#universidad-peruana-de-ciencias-aplicadas)
    - [**Curso:** Arquitectura de Software Emergentes](#curso-arquitectura-de-software-emergentes)
    - [**NRC:**](#nrc)
    - [**Profesor:** Marino Humberto Jara Palacios](#profesor-marino-humberto-jara-palacios)
    - [**Ingeniería de Software**](#ingeniería-de-software)
  - [Informe de Trabajo Final](#informe-de-trabajo-final)
    - [**Nombre del Startup:** Collabrium](#nombre-del-startup-collabrium)
    - [**Nombre del producto:** SynHub](#nombre-del-producto-synhub)
  - [Integrantes](#integrantes)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido](#contenido)
  - [Student Outcome](#student-outcome)
- [**Capítulo I: Introducción**](#capítulo-i-introducción)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [1.2.1 Nombre del producto](#121-nombre-del-producto)
    - [1.2.2 Antecedentes y problemática](#122-antecedentes-y-problemática)
    - [1.2.3. Lean UX Process](#123-lean-ux-process)
      - [1.2.3.1. Lean UX Problem Statements](#1231-lean-ux-problem-statements)
      - [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
      - [1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)
      - [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
  - [**1.3. Segmento objetivo**](#13-segmento-objetivo)
- [2. Capítulo II: Requirements Elicitation \& Analysis](#2-capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
      - [A. User Persona: Coordinador de equipos](#a-user-persona-coordinador-de-equipos)
      - [B. User Persona: Miembro de equipo](#b-user-persona-miembro-de-equipo)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
      - [A. Segmento 1: Coordinadores o Líderes de Grupo](#a-segmento-1-coordinadores-o-líderes-de-grupo)
      - [B. Segmento 2: Miembros del Equipo o Grupo](#b-segmento-2-miembros-del-equipo-o-grupo)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
      - [A. Empathy Map: Coordinador de equipos](#a-empathy-map-coordinador-de-equipos)
      - [B. Empathy Map: Miembro de equipo](#b-empathy-map-miembro-de-equipo)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
      - [A. As-is Segmento 1: Coordinador de equipos](#a-as-is-segmento-1-coordinador-de-equipos)
      - [B. As-is Segmento 2: Miembro de equipo](#b-as-is-segmento-2-miembro-de-equipo)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [3. Capítulo III: Requirements Specification](#3-capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [4. Capítulo IV: Strategic-Level Software Design](#4-capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
  - [Enfoque Arquitectónico](#enfoque-arquitectónico)
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

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones
por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET –
EAC - Student Outcome 3.

<table>
  <thead>
    <tr>
      <th style="text-align: left;">Criterio específico</th>
      <th style="text-align: left;">Acciones realizadas</th>
      <th style="text-align: left;">Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.</td>
      <td>
        <strong>Gomez Hurtado, Miguel Angel</strong>
        <br> <em>TB1</em> <br>
        Expliqué al profesor y a mis compañeros el avance del proyecto, describiendo objetivos, resultados y conclusiones de manera clara. Además, aclare dudas en cuanto a conceptos de cada capítulo en este entrega y los formato de envíos de la misma.
        <br><br>
        <strong>Paiva Quispe, Josue Gonzalo</strong>
        <br> <em>TB1</em> <br>
        Mantuve comunicación activa con mis compañeros para el planteamiento del asistente de IA y su impacto en las US del producto.
        <br><br>
        <strong>Guerrero Vasquez, Jhon Danny</strong>
        <br> <em>TB1</em> <br>
        Aporte en la organización y ejecución de las actividades del equipo, asegurando que el trabajo avanzara de manera ordenada y estructurada. Esta participación permitió que las tareas se desarrollaran con claridad y consistencia, facilitando la coordinación y el progreso del proyecto frente a diferentes públicos y niveles jerárquicos.
        <br><br>
        <strong>Paitan Pumacahua, Max Anthony</strong>
        <br> <em>TB1</em> <br>
        Mantuve comunicación activa con mis compañeros de grupo, coordinando el avance y la división del trabajo. Además, participé activamente brindando mis puntos de vista, mis dudas y recomendaciones en el trabajo, específicamente en la sección de competidores y entrevistas.
        <br><br>
        <strong>Acuña Tomas, Diego Rolin</strong>
        <br> <em>TB1</em> <br>
        Para asegurar una comunicación clara y directa, nos pusimos de acuerdo y realizamos una reunión virtual en la que explicamos de qué trata el trabajo, cuáles son los objetivos de la startup y las características del producto. Además, si alguien tenía alguna duda, podíamos resolverla fácilmente. También realizamos reuniones presenciales al final de cada clase para reforzar la coordinación del equipo.
        <br><br>
      </td>
      <td>
        <strong>TB1</strong><br>
        Se evidenció la capacidad del grupo para comunicar oralmente ideas y resultados con claridad, objetividad y seguridad durante la creación del trabajo. La comunicación para pulir mediante softwares emergentes una solución ya sólida permitió la finalización de un primer avance.
      </td>
    </tr>
    <tr>
      <td>2. Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.</td>
      <td>
        <strong>Gomez Hurtado, Miguel Angel</strong>
        <br> <em>TB1</em> <br>
        Realize el análisis DDD del capítulo 4. Esto abarca desde el EventStorming hasta el Context Mapping. Además, diseñe la infraestructura de nuestro proyecto en los diferentes tipos de diagramas del mismo capítulo. Por último, registre mis entrevistas y documente los resultados del proyyecto.
        <br><br>
        <strong>Paiva Quispe, Josue Gonzalo</strong>
        <br> <em>TB1</em> <br>
        Desarrollé la épica nueva de agente de IA, además de sus US y TS respectivas. Elaboré impact mapping y To-be scenario mapping.
        <br><br>
        <strong>Guerrero Vasquez, Jhon Danny</strong>
        <br> <em>TB1</em> <br>
        En el desarrollo del proyecto, mi aporte se centró en la elaboración del Capítulo I, donde comuniqué de manera escrita y objetiva las ideas y resultados iniciales. Presenté el perfil de la startup y del producto, describí la problemática y los antecedentes, y estructuré el proceso Lean UX con sus supuestos e hipótesis, asegurando que la información se transmitiera con claridad y coherencia. Esta participación permitió que los avances se documentaran de forma organizada y comprensible para públicos de diferentes especialidades y niveles jerárquicos, facilitando la coordinación y el entendimiento del proyecto en su etapa inicial.
        <br><br>
        <strong>Paitan Pumacahua, Max Anthony</strong>
        <br> <em>TB1</em> <br>
        Realicé la primera parte del capítulo 2, el análisis de competidores, las preguntas de las entrevistas. Además, colaboré en la realización del Architectural Design Decisions, Quality Attribute Scenario Refinements, Architectural Drivers Backlog y los Constraints.
        <br><br>
        <strong>Acuña Tomas, Diego Rolin</strong>
        <br> <em>TB1</em> <br>
        Realicé el Needfinding desarrollando los user persona por segmento, el User Task Matrix con tareas priorizadas según frecuencia y severidad, el Empathy Mapping para entender emociones y necesidades de los usuarios, y el As-is Scenario Mapping para analizar cómo enfrentan hoy el problema en su día a día. Finalmente, cerramos con el Ubiquitous Language, donde definimos los términos clave que todo el equipo debe manejar para asegurar una comunicación clara y consistente.
        <br><br>
      </td>
      <td>
        <strong>TB1</strong><br>
        Se evidenció la capacidad del grupo para comunicar por escrito ideas y resultados mediante una presentación estructurada, clara y técnicamente adecuada. Se realizaron de manera debido la documentación delos capítulos 1, 2, 3 y 4 para la culminación del primer avance.
      </td>
    </tr>
  </tbody>
</table>

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
<th>Integrante</th>
<th>Descripción:</th>
</tr>
<tr>
<th style="text-align: center;"><img src="./media/image1.jpg"
style="width:1.67188in;height:2.96712in" /></th>
<th style="text-align: left;"><p>Jhon Danny Guerrero Vasquez -
U202116246</p>
<p>>Soy ingeniero de software especializado en backend con Java y
frameworks como Spring. Me enfoco en crear microservicios escalables y
eficientes, aplicando programación reactiva con Spring WebFlux. Tengo
experiencia en diseño de APIs RESTful y optimización de bases de datos
como MySQL y PostgreSQL. Además, implementó pruebas unitarias y sigo
metodologías Agile para garantizar la calidad del código. Estoy
comprometido con la integración continua en los aportes de cada
integrante de mi equipo.</p></th>
</tr>
<tr>
<th><img src="./media/image2.jpg"
style="width:2.08333in;height:2.15278in" /></th>
<th style="text-align: left;"><p>Acuña Tomas, Diego Rolin -
U202221436</p>
<p>Soy estudiante de Ingeniería de Software en la UPC, actualmente
cursando el octavo ciclo. Durante mi formación académica he adquirido
sólidos conocimientos en múltiples lenguajes de programación y
frameworks, desarrollando competencias especializadas en frontend,
backend y bases de datos. Me interesa especialmente contribuir a
proyectos de código abierto, como Angular, Spring y otras herramientas
modernas. Me considero una persona curiosa y proactiva, con una visión
optimista del futuro tecnológico.</p></th>
</tr>
<tr>
<th style="text-align: center;"><img src="./media/image3.jpg"
style="width:2.01042in;height:2.35417in" /></th>
<th style="text-align: left;"><p>Paitan Pumacahua, Max Anthony -
U201314454</p>
<p>Soy Max Anthony y tengo 29 años. Estoy retomando Ingeniería de
Software como segunda carrera, ya que siempre tuvo ello como objetivo;
en la actualidad, me encuentro cursando el noveno ciclo. Entre mis
habilidades están: Ágil capacidad de análisis -tanto individual como
también en colectivo-, empático en un contexto determinado -tomando
decisiones de manera sensata-, y puedo ser tanto gestor como un
participante activo dentro de un grupo de trabajo.</p></th>
</tr>
<tr>
<th><img src="./media/image4.jpg"
style="width:2.09375in;height:2.81852in" /></th>
<th style="text-align: left;"><p>Josue Gonzalo Paiva Quispe -
U202119095</p>
<p>Soy estudiante de Ingeniería de Software, me encuentro cursando
el 8vo ciclo y realizando prácticas pre profesionales como fullstack
junior web developer</p></th>
</tr>
<tr>
<th><img src="https://i.postimg.cc/fTbbZs0N/Miguel.png"
style="width:2.09375in;height:3.2in" /></th>
<th style="text-align: left;"><p>Miguel Angel Gomez Hurtado - U202220294</p>
<p>Tengo 24 años y estoy estudiando la carrera de Ingeniería Informática. Me encuentro en mi octavo ciclo en la UPC Sede San Miguel. Soy una persona académica y siempre estoy abierto al diálogo. Me apasiona mi carrera y siempre estoy dispuesto a aprender sobre este curso para brindar a mis futuros usuarios un buen producto acorde a sus necesidades.</p></th></th>
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

En esta sección se expone un estudio de los principales actores que compiten con nuestra startup, enfocándonos en aquellos que cuentan con modelos digitales similares o que, aunque no sean idénticos, ofrecen soluciones que coinciden en parte con la propuesta de SynHome. Se consideran tanto competidores directos, ubicados en el mismo segmento, como indirectos, que abarcan aspectos relacionados con la organización de actividades, planificación y coordinación colaborativa.

---

**1. Asana**

<img src="https://avatars.slack-edge.com/2024-09-05/7707480927360_791cc0c5cdf5b6720b21_512.png" alt="Asana" width="200"/>

**Descripción:**

Asana es una plataforma orientada a la gestión de proyectos que permite a los equipos estructurar tareas, asignar responsables y monitorear el avance de sus proyectos. Dispone de diversas visualizaciones, como listas y tableros Kanban, lo que facilita su adaptación a distintas dinámicas de trabajo.

**Características principales:**

* **Proyectos y tareas** estructurados en listas y tableros tipo Kanban.
* **Subtareas y relaciones de dependencia** para organizar procesos de trabajo.
* **Colaboración**: asignación de responsabilidades, comentarios y archivos.
* **Alertas y recordatorios** mediante correo electrónico y la aplicación.
* **Monitoreo e informes** del progreso (gráficos y porcentajes).
* **Integraciones** con herramientas como Slack, Google Drive y Microsoft Teams.
* **Aplicación móvil** intuitiva que permite gestionar tareas y colaborar.

---

**2. FamilyWall**

<img src="https://i.ibb.co/zVscqS8y/familywall.png" alt="FamilyWall" width="200"/>

**Descripción:**

FamilyWall es una solución digital orientada al entorno familiar que reúne múltiples funcionalidades en una sola plataforma. Su diseño amigable y visual la hace adecuada para familias con integrantes de distintas edades.

**Principales características:**

* **Listas colaborativas** de tareas y compras.
* **Geolocalización en tiempo real**, útil para ubicar a los miembros de la familia.
* **Sistema de mensajería** privada y grupal.
* **Espacio compartido multimedia** para fotos y videos familiares.

---

**3. ClickUp**

<img src="https://i.postimg.cc/MHrSh7pw/clickup.webp" alt="ClickUp" width="200"/>

**Descripción:**

ClickUp es una herramienta integral que combina funcionalidades de gestión de tareas, documentación, metas y más. Se destaca por su alto nivel de personalización y su capacidad de adaptarse a diversos flujos de trabajo.

**Características principales:**

* **Estructura jerárquica adaptable**: espacios, carpetas, listas y tareas.
* **Diversas vistas**: lista, tablero, cronograma y carga de trabajo.
* **Registro de tiempo** incorporado.
* **Documentación interna**, notas y wikis colaborativos.
* **Automatizaciones configurables**.
* **Comentarios con menciones** y edición colaborativa.
* **Plantillas reutilizables** para proyectos y tareas.
* **Aplicación móvil** completa, aunque puede resultar compleja para nuevos usuarios.

---

### 2.1.1. Análisis competitivo

<table> 
  <tr>
    <th colspan="6"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar acabo este análisis? </td>
    <td colspan="4"> Pregunta </td>
  </tr>
  <tr>
    <td colspan="4"> Este análisis se realiza para comprender el entorno competitivo, identificar a los actores del mercado, tomar decisiones estratégicas de desarrollo y construir una propuesta de valor sólida. </td>
  </tr>
  <tr>
    <td colspan="2"> Productos </td>
    <td style="text-align: center;"> <div>SynHub</div> <img src="https://i.ibb.co/23FVNcpw/synhub.png" alt="SynHub" width="200"/> </td>
    <td style="text-align: center;"> <div>Asana</div> <img src="https://avatars.slack-edge.com/2024-09-05/7707480927360_791cc0c5cdf5b6720b21_512.png" alt="Asana" width="200"/> </td>
    <td style="text-align: center;"> <div>FamilyWall</div> <img src="https://i.ibb.co/zVscqS8y/familywall.png" alt="FamilyWall" width="200"/> </td>
    <td style="text-align: center;"> <div>ClickUp</div> <img src="https://i.postimg.cc/MHrSh7pw/clickup.webp" alt="clickup" width="200"/> </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>SynHub es una solución digital colaborativa creada para apoyar la organización y gestión de actividades en distintos tipos de grupos, ya sean académicos, laborales o sociales.</td>
    <td>Herramienta enfocada en la gestión de proyectos y tareas que facilita la organización, el seguimiento y la planificación mediante diferentes vistas como listas y tableros Kanban.</td>
    <td>FamilyWall es una plataforma orientada a la organización familiar, que permite coordinar tareas, comunicaciones y contenido multimedia en un solo entorno.</td>
    <td>ClickUp es una solución integral que reúne herramientas para la gestión de tareas, documentos y objetivos, destacando por su alto nivel de personalización.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes? </td>
    <td>Fomenta la corresponsabilidad mediante funciones como seguimiento de tareas, validación de cumplimiento y reportes visuales con gráficos.</td>
    <td>Destaca por su facilidad de uso e interfaz intuitiva, permitiendo una rápida adopción por parte de los equipos. Sus múltiples integraciones amplían su funcionalidad.</td>
    <td>Contribuye a mejorar la comunicación familiar mediante chats y actualizaciones compartidas.</td>
    <td>Su alto grado de personalización y la integración de múltiples funciones en una sola plataforma resultan atractivos para equipos que buscan centralizar herramientas.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado Objetivo</td>
    <td>Equipos académicos y universitarios, así como grupos que requieren herramientas flexibles, accesibles y fáciles de usar.</td>
    <td>Organizaciones de cualquier tamaño que buscan optimizar la gestión de proyectos, desde startups hasta grandes empresas.</td>
    <td>Familias que necesitan una plataforma unificada para organizar actividades y compartir información.</td>
    <td>Empresas y equipos que requieren soluciones completas y altamente personalizables para gestionar sus proyectos.</td>
  </tr>
  <tr>
    <td>Estrategias de Marketing</td>
    <td>Modelo freemium: ofrecer una versión gratuita funcional y motivar la transición a planes premium con características adicionales.</td>
    <td>Uso de contenido educativo como guías y webinars para atraer usuarios, junto con una versión gratuita que incentiva la conversión a planes pagos.</td>
    <td>Implementación de pruebas gratuitas para impulsar la adopción de la plataforma.</td>
    <td>Enfoque en destacar su versatilidad mediante contenido educativo, testimonios y comparaciones con otras herramientas.</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos & Servicios</td>
    <td>Gestión de tareas compartidas y organización de responsabilidades dentro del hogar o equipo.</td>
    <td>Gestión de proyectos con vistas personalizadas, integraciones con herramientas externas y seguimiento del progreso.</td>
    <td>Funciones de listas, mensajería y compartición de contenido multimedia.</td>
    <td>Gestión de tareas y proyectos con múltiples vistas, documentación colaborativa, control de tiempo y automatizaciones.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Plan gratuito y plan premium con un costo de $6.99 por usuario al mes.</td>
    <td>Versión gratuita con funciones básicas y planes premium: $13.49 mensual o $10.99 mensual en plan anual.</td>
    <td>Plan premium de $4.99 mensual o $29.99 anual con funcionalidades adicionales.</td>
    <td>Versión gratuita y plan Unlimited: $9 mensual o $10.99 mensual en plan anual.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>Aplicaciones móviles disponibles en Android e iOS.</td>
    <td>Acceso mediante web y aplicaciones móviles en iOS y Android.</td>
    <td>Disponible en App Store y Google Play.</td>
    <td>Disponible tanto en web como en aplicaciones móviles.</td>
  </tr>
  <tr>
    <td rowspan="5">Análisis SWOT</td>
  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>Adaptabilidad a diferentes contextos y tipos de equipos.</td>
    <td>Interfaz sencilla e intuitiva.</td>
    <td>Amplio conjunto de funciones para la gestión familiar.</td>
    <td>Gran flexibilidad y capacidad de personalización.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Falta de posicionamiento y reconocimiento en el mercado.</td>
    <td>Restricciones en la personalización de procesos complejos.</td>
    <td>Limitaciones importantes en la versión gratuita.</td>
    <td>Complejidad inicial debido a la cantidad de funcionalidades.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Ingresar a nichos poco atendidos por soluciones complejas.</td>
    <td>Expansión hacia mercados emergentes.</td>
    <td>Crecimiento en el ámbito educativo.</td>
    <td>Desarrollo en sectores que requieren soluciones específicas.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competidores grandes podrían ofrecer versiones más económicas.</td>
    <td>Incremento de la competencia en herramientas de gestión.</td>
    <td>Limitaciones en integraciones con otras plataformas.</td>
    <td>Competencia con herramientas más especializadas y simples.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

**1. Estrategia de Diferenciación por Simplicidad y Usabilidad**

**Objetivo:** Posicionar a SynHub como la alternativa más sencilla, intuitiva y accesible para todo tipo de grupos.

**Tácticas:**

* Crear una **interfaz clara y visual**, fácil de navegar incluso para usuarios sin experiencia.
* Implementar un **onboarding ágil** (menos de 2 minutos para empezar).
* Incluir **tutoriales interactivos** y ayuda contextual dentro de la plataforma.
* Destacar frente a Asana y ClickUp con el mensaje: *“No necesitas ser experto para organizarte”*.

**2. Estrategia de Enfoque en Nichos Desatendidos**

**Objetivo:** Dirigirse a segmentos como estudiantes, voluntarios y comunidades.

**Tácticas:**

* Diseñar funcionalidades específicas para grupos no empresariales.
* Expandirse hacia **equipos híbridos** que combinan familia, trabajo y estudio.

**3. Estrategia de Humanización y Cercanía de Marca**

**Objetivo:** Generar confianza mediante una comunicación cercana y una experiencia positiva.

**Tácticas:**

* Brindar **soporte rápido y empático**.
* Utilizar un **lenguaje simple y humano**, evitando tecnicismos.
* Posicionarse como una plataforma cercana, a diferencia del enfoque corporativo de otros competidores.

**4. Estrategia de Precio Accesible y Transparente**

**Objetivo:** Captar usuarios que buscan soluciones completas a bajo costo.

**Tácticas:**

* Ofrecer un **plan gratuito funcional** y un **premium accesible**.
* Aplicar descuentos para sectores educativos y organizaciones sin fines de lucro.
* Incluir funcionalidades clave sin obligar a cambiar de plan constantemente.

---

## 2.2. Entrevistas

En esta sección se plantea el diseño, registro y análisis de entrevistas dirigidas a los segmentos objetivo.

### 2.2.1. Diseño de entrevistas

**1. Entrevista para el Coordinador o Líder de Grupo**

* Preguntas principales:

1.¿Podrías contarme un poco sobre ti? (edad, ocupación, lugar de residencia, estado civil)

2.¿A qué tipo de grupo o equipos perteneces o lideras actualmente?

3.¿Cuál es tu rol dentro de ese grupo?

* -Preguntas complementarias:

4.¿Con qué frecuencia se reúnen o interactúan?

5.Cuántas personas conforman el grupo o equipo que lideras?

6.¿Qué herramientas o plataformas digitales utilizas para coordinar al equipo?

7.¿Sueles tener problemas con la puntualidad, comunicación o cumplimiento?

8.¿Qué dispositivos usas más frecuentemente para organizarte (móvil, laptop, tablet)?

9.¿Usas redes sociales, apps colaborativas o agendas digitales?

10.¿Qué valoras más en una herramienta para organizar a tu equipo?

**2. Entrevista para el Miembro del Equipo o Grupo**

* Preguntas principales:

1.¿Podrías contarme un poco sobre ti? (edad, ocupación, lugar de residencia, estado civil)

2.¿A qué tipo de grupo o equipo perteneces actualmente?

3.¿Cuál es tu rol dentro del grupo? (por ejemplo: participante, colaborador, voluntario)

* Preguntas complementarias:

4.¿Qué tipo de tareas realizas habitualmente?

5.¿Qué herramientas o plataformas digitales utilizas para conocer tus actividades en el equipo?

6.¿Cómo te enteras de tus responsabilidades dentro del grupo?

7.¿Qué cosas te molestan o dificultan al trabajar en grupo?

8.¿Qué tipo de apps o plataformas te gustan más? (Ej: fáciles de usar, visuales, rápidas)

9.¿Usas más el celular o la computadora para tus tareas diarias?

10.¿Qué tipo de apps o plataformas te gustan más? (Ej: fáciles de usar, visuales, rápidas)

### 2.2.2. Registro de entrevistas

En esta sección se recopilan y resumen las ideas y hallazgos más relevantes obtenidos de las entrevistas realizadas tanto a coordinadores como a miembros de grupo. La información completa, incluidas las grabaciones de cada entrevista, está disponible en los siguientes enlaces:

<table cellpadding="8" cellspacing="0">
  <tbody>
    <tr>
      <td>Entrevista 1</td>
      <td> <img src="https://i.ibb.co/Q77YqSjd/interview-Melany.png" alt="interview 1" width="400"/> </td>
    </tr>
    <tr>
      <td>Nombre Entrevistado</td>
      <td>Melany Paitan</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>22</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Lima Cercado</td>
    </tr>
    <tr>
      <td>Ocupacion</td>
      <td>Estudiante</td>
    </tr>
    <tr>
      <td>Duración Entrevista</td>
      <td>03:15 </td>
    </tr>
    <tr>
      <td>Minuto de Inicio</td>
      <td>00:00 - 02:40</td>
    </tr>
  </tbody>
</table>

<table cellpadding="8" cellspacing="0">
  <tbody>
    <tr>
      <td>Entrevista 2</td>
      <td> <img src="assets/chapter2/entrevista2.png" alt="interview 1" width="400"/> </td>
    </tr>
    <tr>
      <td>Nombre Entrevistado</td>
      <td>Xavier Hager</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>23</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Santiago de Surco</td>
    </tr>
    <tr>
      <td>Ocupacion</td>
      <td>Estudiante</td>
    </tr>
    <tr>
      <td>Duración Entrevista</td>
      <td>03:27</td>
    </tr>
    <tr>
      <td>Minuto de Inicio</td>
      <td>00:00 - 03:27</td>
    </tr>
  </tbody>
</table>

<table cellpadding="8" cellspacing="0">
  <tbody>
    <tr>
      <td>Entrevista 3</td>
      <td> <img src="https://i.ibb.co/bRWK4wSv/integrante3.png" alt="interview 2" width="400"/> </td>
    </tr>
    <tr>
      <td>Nombre Entrevistado</td>
      <td>Andrés Coca</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>20</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Lima Metropolitana</td>
    </tr>
    <tr>
      <td>Ocupacion</td>
      <td>Estudiante</td>
    </tr>
    <tr>
      <td>Duración Entrevista</td>
      <td>06:10 </td>
    </tr>
    <tr>
      <td>Minuto de Inicio</td>
      <td>00:00 - 06:10</td>
    </tr>
  </tbody>
</table>

<table cellpadding="8" cellspacing="0">
  <tbody>
    <tr>
      <td>Entrevista 4</td>
      <td> <img src="https://i.postimg.cc/PxvP4x6Q/Entrevista-Diego-Lider.png" alt="interview 2" width="400"/> </td>
    </tr>
    <tr>
      <td>Nombre Entrevistado</td>
      <td>Diego Alonso Quispe Flores</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>24</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Villa el Salvador</td>
    </tr>
    <tr>
      <td>Ocupacion</td>
      <td>Líder de equipo</td>
    </tr>
    <tr>
      <td>Duración Entrevista</td>
      <td>08:09 </td>
    </tr>
    <tr>
      <td>Minuto de Inicio</td>
      <td>00:00 - 08:09</td>
    </tr>
  </tbody>
</table>

<table cellpadding="8" cellspacing="0">
  <tbody>
    <tr>
      <td>Entrevista 5</td>
      <td> <img src="https://i.ibb.co/tMMGnmZz/lider2.png" alt="interview 2" width="400"/> </td>
    </tr>
    <tr>
      <td>Nombre Entrevistado</td>
      <td>Fabio De la Cruz</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>54</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Villa el Salvador</td>
    </tr>
    <tr>
      <td>Ocupacion</td>
      <td>Líder de equipo</td>
    </tr>
    <tr>
      <td>Duración Entrevista</td>
      <td>03:17 </td>
    </tr>
    <tr>
      <td>Minuto de Inicio</td>
      <td>00:00 - 03:17</td>
    </tr>
  </tbody>
</table>

<table cellpadding="8" cellspacing="0">
  <tbody>
    <tr>
      <td>Entrevista 6</td>
      <td> <img src="https://i.ibb.co/k20CTyzC/lider3.png" alt="interview 2" width="400"/> </td>
    </tr>
    <tr>
      <td>Nombre Entrevistado</td>
      <td>Briggite Herrera Aguirre</td>
    </tr>
    <tr>
      <td>Edad</td>
      <td>22</td>
    </tr>
    <tr>
      <td>Distrito</td>
      <td>Los Olivos</td>
    </tr>
    <tr>
      <td>Ocupacion</td>
      <td>Líder de equipo</td>
    </tr>
    <tr>
      <td>Duración Entrevista</td>
      <td>04:34 </td>
    </tr>
    <tr>
      <td>Minuto de Inicio</td>
      <td>00:00 - 04:34</td>
    </tr>
  </tbody>
</table>

### 2.2.3. Análisis de entrevistas

En esta sección se recopilan y resumen las ideas y hallazgos más relevantes obtenidos de las entrevistas realizadas tanto a coordinadores como a miembros de grupo. La información completa, incluidas las grabaciones de cada entrevista, está disponible en el siguiente enlace:

URL: https://1drv.ms/v/c/9fed6c4f629930aa/IQA_ZEu7K2-7RrQH7CcVA6CFAYyE1I6TyF9RFQiOzFxuHDg?e=McVfoR

**Segmento Objetivo 1: Coordinadores o Líderes de Grupo**

* **Demografía:** La edad promedio de los coordinadores entrevistados es de 25 años, con todos los participantes trabajando en campos relacionados con la tecnología. Esto indica un perfil demográfico juvenil en roles de liderazgo dentro de entornos tecnológicos.
* **Tamaño del equipo:** Los coordinadores gestionan equipos de tamaños variados, habiendo un líder que supervisa un equipo de seis miembros. Esto sugiere una preferencia por equipos de tamaño pequeño a mediano para una gestión efectiva.
* **Frecuencia de comunicación:** Todos los coordinadores reportaron participar en reuniones o interacciones diarias, lo que destaca un enfoque estructurado de comunicación que fomenta la alineación del equipo. Esta comunicación constante es crucial para el éxito del proyecto.
* **Frecuencia de comunicación:** Todos los coordinadores reportaron participar en reuniones o interacciones diarias, lo que destaca un enfoque estructurado de comunicación que fomenta la alineación del equipo. Esta comunicación constante es crucial para el éxito del proyecto.

**Segmento Objetivo 2: Miembros del Equipo o Grupo**

* **Preferencias de comunicación:** El 67 % de los miembros del equipo prefiere una combinación de comunicación presencial y digital, con un fuerte énfasis en interacciones en tiempo real para la resolución de problemas. Esto refleja la necesidad de flexibilidad en los métodos de comunicación.
* **Estrategias de compromiso:** El 67 % de los miembros del equipo mencionó el uso de materiales creativos, como infografías y presentaciones, para mejorar el compromiso y la comprensión dentro del equipo. Esto sugiere que se valoran los métodos de comunicación innovadores.
* **Herramientas de gestión de tareas:** Todos los miembros del equipo informaron utilizar herramientas que les permiten seguir sus tareas de forma visual, lo que indica una preferencia universal por ayudas visuales para monitorear el progreso y mantener la motivación.


## 2.3. Needfinding

### 2.3.1. User Personas

#### A. User Persona: Coordinador de equipos

![Miguel Persona](assets/userPersonas/miguel.png)

#### B. User Persona: Miembro de equipo

![Gabriela Persona](assets/userPersonas/gabriela.png)

### 2.3.2. User Task Matrix

#### A. Segmento 1: Coordinadores o Líderes de Grupo

| Tarea | Frecuencia | Severidad |
|-------|-----------|-----------|
| Seleccionar integrantes del equipo y definir objetivo común | Alta | Media |
| Establecer grupos de trabajo y programar horarios | Baja | Alta |
| Organizar reuniones a través de diferentes canales de comunicación | Media | Media |
| Distribuir y asignar responsabilidades entre los miembros | Alta | Alta |
| Monitorear el progreso y actualizar estado de avances | Alta | Alta |
| Compilar y centralizar información de todos los participantes | Alta | Alta |
| Analizar resultados finales e identificar áreas de mejora | Media | Baja |

#### B. Segmento 2: Miembros del Equipo o Grupo

| Tarea | Frecuencia | Severidad |
|-------|-----------|-----------|
| Comprender los objetivos y el alcance del proyecto asignado | Baja | Media |
| Revisar y cumplir con los horarios y pautas establecidas | Alta | Alta |
| Participar activamente en reuniones de coordinación y seguimiento | Media | Alta |
| Ejecutar las tareas designadas conforme al cronograma establecido | Alta | Alta |
| Informar regularmente al líder sobre el progreso de sus actividades | Alta | Alta |
| Compartir resultados, hallazgos y documentación con el equipo | Media | Media |
| Proporcionar retroalimentación para identificar mejoras continuas | Baja | Media |

### 2.3.3. Empathy Mapping

En esta sección se muestra el **mapa de empatía**, una herramienta clave para 
entender con mayor profundidad lo que nuestros usuarios piensan, sienten 
y necesitan. Gracias a este análisis, podemos detectar oportunidades concretas 
para mejorar su experiencia.

#### A. Empathy Map: Coordinador de equipos

![Miguel Empathy Map](assets/empathyMaps/miguel.png)

#### B. Empathy Map: Miembro de equipo

![Gabriela Empathy Map](assets/empathyMaps/gabriela.png)

### 2.3.4. As-is Scenario Mapping

En esta sección se estructuran los escenarios actuales (As-Is) 
diferenciados por cada segmento objetivo, detallando para cada 
fase las actividades concretas que realizan, sus reflexiones 
internas y sus estados emocionales durante el proceso.

#### A. As-is Segmento 1: Coordinador de equipos

<table>
<tr style="background-color: #4472C4; color: white;">
  <th>Fases</th>
  <th>Configuración Inicial</th>
  <th>Asignación de Responsabilidades</th>
  <th>Monitoreo Continuo</th>
  <th>Cierre y Evaluación</th>
</tr>
<tr>
  <td><strong>Doing (Acciones)</strong></td>
  <td>Utiliza herramientas básicas como WhatsApp, Excel o documentos físicos para seleccionar miembros del equipo e intentar organizar tareas iniciales. Coordina reuniones a través de múltiples canales de comunicación.</td>
  <td>Distribuye tareas de forma manual y proporciona cronogramas. Debe recordar constantemente a los miembros sus responsabilidades y seguir el estado de cada tarea asignada.</td>
  <td>Consulta individualmente a cada miembro sobre avances. Realiza ajustes en cronogramas sobre la marcha. Gestiona conversaciones dispersas en múltiples plataformas.</td>
  <td>Recopila información fragmentada de diferentes fuentes para evaluar resultados. Intenta extraer lecciones aprendidas sin métricas claras de desempeño.</td>
</tr>
<tr>
  <td><strong>Thinking (Pensamientos)</strong></td>
  <td>"¿Cómo logro que todos entiendan sus roles?" "Espero poder coordinar de manera efectiva."</td>
  <td>"¿Entenderán realmente lo que se espera?" "¿Cuándo debo hacer seguimiento?"</td>
  <td>"¿Todos están realmente cumpliendo?" "¿Vamos en la dirección correcta?" "El desorden de información es un problema."</td>
  <td>"¿Tengo todos los datos necesarios?" "¿Resultó bien o mal?" "¿Qué puedo mejorar para próximas veces?"</td>
</tr>
<tr>
  <td><strong>Feeling (Sentimientos)</strong></td>
  <td>😟 Preocupación por la falta de respuesta inicial. 😰 Ansiedad por la carga de trabajo.</td>
  <td>😤 Desorganización por múltiples responsabilidades. ⚠️ Presión por cumplir con todos.</td>
  <td>😊 Satisfacción por el seguimiento constante. 😕 Inseguridad sobre si todo va bien. ⚡ Estrés por resultados variables.</td>
  <td>😞 Desilusión por resultados inconsistentes. 😤 Frustración por no tener métricas claras.</td>
</tr>
</table>

#### B. As-is Segmento 2: Miembro de equipo

<table>
<tr style="background-color: #70AD47; color: white;">
  <th>Fases</th>
  <th>Recepción de Tareas</th>
  <th>Gestión del Tiempo</th>
  <th>Participación y Comunicación</th>
  <th>Cierre y Aprendizaje</th>
</tr>
<tr>
  <td><strong>Doing (Acciones)</strong></td>
  <td>Recibe tareas a través de múltiples canales (WhatsApp, correos, mensajería verbal). No dispone de un horario unificado ni claridad sobre plazos comunes para todos los miembros del equipo.</td>
  <td>Batalla constante por recordar cronogramas, fechas de entrega y compromisos. Gestiona recordatorios personales sin sincronización con el equipo.</td>
  <td>Comunica su progreso mediante mensajes informales o cuando le preguntan. Espera confirmación sobre si está cumpliendo adecuadamente. Se cuestiona si debería informar más frecuentemente.</td>
  <td>Entrega las tareas completadas de forma aislada. No recibe retroalimentación clara ni sabe si cumplió con las expectativas.</td>
</tr>
<tr>
  <td><strong>Thinking (Pensamientos)</strong></td>
  <td>"¿Hasta cuándo tengo para hacer esto?" "¿Dónde estaba la información?" "¿Quién más debería saberlo?"</td>
  <td>"No tengo claro cuántas tareas tengo pendientes." "Ojalá no me olvide de esto." "¿De verdad es para hoy?"</td>
  <td>"¿Quién está en esta tarea conmigo?" "¿No quiero parecer que no hago nada." "Espero que alguien me ayude a aclarar."</td>
  <td>"¿Resultó bien lo que hice?" "¿Valió la pena el esfuerzo?" "¿Debería haber hecho algo diferente?"</td>
</tr>
<tr>
  <td><strong>Feeling (Sentimientos)</strong></td>
  <td>😕 Confundido por información dispersa. 😞 Poco motivado al inicio.</td>
  <td>😐 Inseguro sobre cronogramas. 😰 Ansioso por olvidar fechas.</td>
  <td>😐 Inseguro sobre su contribución. 😔 Culpable por no comunicar más. 😐 Preocupado por no cumplir.</td>
  <td>😕 Desconectado de los resultados. 😞 Desmotivado para repetir la experiencia.</td>
</tr>
</table>


## 2.4. Ubiquitous Language

A continuación se presenta el glosario de términos y conceptos del dominio de negocio de SynHub. Este lenguaje 
ubiquo es compartido por todos los miembros del equipo y stakeholders para garantizar una comunicación clara 
y sin ambigüedad.

| Término | Definición |
|---------|-----------|
| **Group (Grupo)** | Unidad de colaboración formada por un conjunto de personas con un objetivo común. Los grupos pueden tener naturaleza académica, laboral o comunitaria. Cada grupo tiene un ciclo de vida propio que incluye su creación, actividad y eventual eliminación o archivo. |
| **Leader (Líder)** | Integrante del grupo que asume la responsabilidad de organizar las actividades, crear y asignar tareas, gestionar invitaciones y validar el trabajo de los demás miembros. El líder tiene permisos extendidos dentro del grupo. |
| **Member (Miembro)** | Persona que pertenece a un grupo y tiene tareas o responsabilidades asignadas. Puede consultar sus tareas, actualizar su estado, enviar solicitudes y recibir notificaciones, pero no tiene permisos administrativos sobre el grupo. |
| **Task (Tarea)** | Unidad de trabajo que el líder crea y asigna a uno o más miembros del grupo. Toda tarea tiene un responsable, una descripción y una fecha límite, y atraviesa distintos estados a lo largo de su ciclo de vida. |
| **Task Status (Estado de Tarea)** | Condición actual en la que se encuentra una tarea dentro de su ciclo de vida. Los estados posibles son: En progreso, En revisión, Completada, Vencida y Cancelada. |
| **Assignment (Asignación)** | Acción mediante la cual el líder vincula una tarea a un miembro específico del grupo, estableciendo quién es el responsable de su ejecución y la fecha límite correspondiente. |
| **Due Date (Fecha Límite)** | Fecha y hora máxima establecida para que un miembro complete una tarea. Pasada esta fecha sin completarse, la tarea pasa automáticamente al estado Vencida. |
| **Invitation (Invitación)** | Solicitud formal enviada por un líder a un usuario para que se una a su grupo. El usuario recibe una notificación y puede aceptar o rechazar la invitación. |
| **Approval Request (Solicitud de Aprobación)** | Petición que realiza un miembro al marcar una tarea como completada, para que el líder la revise y valide. Mientras aguarda revisión, la tarea entra en estado En revisión. |
| **Extension Request (Solicitud de Extensión de Plazo)** | Petición formal de un miembro al líder para ampliar la fecha límite de una tarea, acompañada de un motivo justificado. El líder puede aceptarla o rechazarla. |
| **Validation (Validación)** | Acción mediante la cual el líder aprueba o rechaza una tarea enviada para revisión. Si se aprueba, la tarea queda definitivamente Completada; si se rechaza, regresa a En progreso con comentarios de feedback. |
| **Notification (Notificación)** | Aviso automático generado por el sistema ante eventos relevantes del dominio, como asignaciones de tareas, vencimientos de plazos, resultados de validaciones o cambios de estado. Puede entregarse dentro de la aplicación (in-app) o por correo electrónico. |
| **Productivity Dashboard (Panel de Productividad)** | Vista visual que consolida métricas de desempeño individual y grupal, permitiendo al líder conocer la carga de trabajo por miembro, la distribución de estados de tareas y el cumplimiento general del grupo. |
| **Productivity Metrics (Métricas de Productividad)** | Indicadores cuantitativos del desempeño de los miembros y del grupo en conjunto. Incluyen: número de tareas completadas, tasa de aprobación en primera revisión, tareas vencidas y solicitudes de extensión realizadas. |
| **Validation History (Histórico de Validaciones)** | Registro cronológico de todas las aprobaciones y rechazos realizados por el líder sobre las tareas del grupo. Permite identificar patrones de calidad y seguimiento individual por miembro. |
| **Workload Balance (Equilibrio de Carga)** | Distribución equitativa de tareas entre los miembros de un grupo, de modo que ningún integrante concentre una cantidad desproporcionada de responsabilidades. Es un valor central en la propuesta de SynHub. |
| **Co-responsibility (Corresponsabilidad)** | Principio que implica que todos los integrantes de un grupo comparten activamente el compromiso de cumplir con sus responsabilidades para el logro de los objetivos comunes. |
| **Group Lifecycle (Ciclo de Vida del Grupo)** | Conjunto de etapas por las que atraviesa un grupo desde su creación hasta su eliminación o archivo. Incluye: creación, incorporación de miembros, asignación de tareas, seguimiento, y cierre o archivo. |

---

# 3. Capítulo III: Requirements Specification



## 3.1. To-Be Scenario Mapping

**Segmento objetivo: Líderes de equipos de trabajo**

<img src="assets/chapter3/to-be.png" alt="cc-alerting" width="800">


**Segmento Objetivo: Miembros de equipos de trabajo**

<img src="assets/chapter3/to-be2.png" alt="cc-alerting" width="800">


## 3.2. User Stories


**Epics**

Además de las épicas referentes a la funcionalidad principal de Synhub, se añadió una séptima épica referente a la integración 
de un agente inteligente de asistencia basado en IA, que analiza datos del sistema parra generar recomendaciones y apoyo personalizado.

| Epic ID | Título                           | Descripción                                                                                                                                                                               |
|---------|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP-001  | Gestión de Grupos                | Creación, configuración y administración de grupos colaborativos e invitaciones. Cubre todo el ciclo de vida del grupo.                                                                   |
| EP-002  | Gestión de Tareas                | Creación, asignación (con responsables y fechas) y seguimiento de estados (En progreso, completada, caducada y cancelada).                                                                |
| EP-003  | Notificaciones Inteligentes      | Sistema centralizado de notificaciones (in-app/email) para eventos críticos, con gestión de preferencias, agrupamiento y recordatorios automáticos.                                       |
| EP-004  | Analítica y Reportes             | Generación automatizada de dashboards y métricas de productividad (individual/grupal).                                                                                                    |
| EP-005  | Solicitudes y Validaciones       | Flujo completo para solicitudes de procesamiento de tareas con estados, comentarios y notificaciones asociadas.                                                                           |
| EP-006  | Gestión de Usuarios              | Registro, inicio de sesión, edición de perfil y gestión de credenciales. Incluye autenticación y recuperación de acceso.                                                                  |
| EP-007  | Agente Inteligente de Asistencia | Integración de un agente basado en IA que analiza datos del sistema para generar recomendaciones, detectar riesgos y asistir a los usuarios en la gestión de tareas y toma de decisiones. |


**User Stories**

Con base en las épicas definidas se formularon las siguientes historias de usuario, incluyendo nuevas historias relacionadas con el agente inteligente de asistencia:

| ID     | Título                                        | Descripción                                                                                                                   | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                               | Epic   |
|--------|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| US-001 | Creación de grupo                             | Como líder, quiero crear grupos para organizar el trabajo de mi equipo.                                                       | Escenario 1: Creación básica: Given que soy líder, When completo nombre y descripción, Then el grupo se crea conmigo como único miembro. Escenario 2: Imagen de grupo: Given que subo una imagen, When guardo los cambios, Then aparece como identificación visual del grupo.                                                                                         | EP-001 |
| US-002 | Envío de invitaciones                         | Como líder, quiero invitar miembros a mi grupo para conformar el equipo.                                                      | Escenario 1: Invitación válida: Given que selecciono usuarios, When envío invitaciones, Then los usuarios reciben notificación. Escenario 2: Invitación a miembro existente: Given que el usuario ya está en el grupo, When intento invitarlo, Then el sistema muestra error "Usuario ya pertenece al grupo".                                                         | EP-001 |
| US-003 | Eliminación de grupo                          | Como líder, quiero eliminar grupos inactivos para mantener la organización.                                                   | Escenario 1: Confirmación requerida: Given que selecciono eliminar grupo, When confirmo la acción, Then todos los datos asociados se archivan. Escenario 2: Grupo con tareas activas: Given que hay tareas pendientes, When intento eliminar, Then el sistema pide reasignar tareas primero.                                                                          | EP-001 |
| US-004 | Creación de tareas                            | Como líder, quiero crear tareas para asignar trabajo a los miembros.                                                          | Escenario 1: Tarea básica: Given que completo título y descripción, When guardo la tarea, Then aparece en el listado con estado "En progreso". Escenario 2: Tarea sin responsable: Given que creo tarea sin asignar, When intento guardar, Then el sistema muestra error "Se requiere responsable".                                                                   | EP-002 |
| US-005 | Asignación de tareas                          | Como líder, quiero asignar tareas a miembros específicos para distribuir el trabajo.                                          | Escenario 1: Asignación individual: Given que selecciono un miembro, When asigno la tarea, Then recibe notificación y aparece en su listado. Escenario 2: Reasignación: Given que la tarea está asignada, When cambio el responsable, Then ambos miembros reciben notificación.                                                                                       | EP-002 |
| US-006 | Eliminación de tareas                         | Como líder, quiero eliminar tareas incorrectas o duplicadas.                                                                  | Escenario 1: Eliminación estándar: Given que selecciono una tarea, When la elimino, Then desaparece del listado principal. Escenario 2: Tarea completada: Given que la tarea está marcada como completada, When intento eliminarla, Then el sistema requiere confirmación adicional.                                                                                  | EP-002 |
| US-007 | Actualización de estado                       | Como miembro, quiero actualizar el estado de mis tareas para reflejar mi progreso.                                            | Escenario 1: Marcar como completada: Given que finalizo una tarea, When cambio el estado, Then el líder recibe notificación. Escenario 2: Cancelación: Given que una tarea ya no es necesaria, When la marco como cancelada, Then se registra con motivo opcional.                                                                                                    | EP-002 |
| US-008 | Reprogramación de tareas                      | Como líder, quiero cambiar fechas límite cuando surgen imprevistos.                                                           | Escenario 1: Cambio de fecha: Given que selecciono una tarea, When modifico la fecha límite, Then el responsable recibe notificación. Escenario 2: Histórico de cambios: Given que reprogramo una tarea, When consulto su historial, Then muestra fechas anteriores y justificación.                                                                                  | EP-002 |
| US-009 | Notificaciones multicanal                     | Como miembro, quiero recibir notificaciones tanto en la plataforma como por email para estar informado.                       | Escenario 1: Notificación in-app: Given que ocurre un evento relevante, When el sistema genera notificación, Then aparece un badge en el icono de campana. Escenario 2: Notificación por email: Given que ocurre un evento importante y no estoy activo, When pasan 24h sin iniciar sesión, Then recibo resumen por email.                                            | EP-003 |
| US-010 | Gráfico de distribución de tareas             | Como líder, quiero ver un gráfico pastel con la distribución de tareas por miembro para balancear cargas.                     | Escenario 1: Visualización básica: Given que accedo al dashboard, When selecciono "Distribución", Then muestra porcentajes por miembro. Escenario 2: Filtro por periodo: Given que elijo un rango de fechas, When aplico el filtro, Then el gráfico se actualiza.                                                                                                     | EP-004 |
| US-011 | Gráfico de estados de tareas                  | Como líder, quiero ver un gráfico de barras con el estado de todas las tareas del grupo.                                      | Escenario 1: Datos actualizados: Given que hay tareas en diferentes estados, When visualizo el reporte, Then muestra cantidades por estado. Escenario 2: Exportación: Given que el gráfico está cargado, When hago clic en "Exportar", Then descarga imagen PNG.                                                                                                      | EP-004 |
| US-012 | Reporte de reprogramaciones                   | Como líder, quiero ver un gráfico de líneas con la cantidad de tareas reprogramadas por semana.                               | Escenario 1: Tendencia temporal: Given que selecciono último trimestre, When genero el reporte, Then muestra línea con picos por semana. Escenario 2: Detalle por motivo: Given que hay reprogramaciones, When paso el cursor sobre un punto, Then muestra motivos frecuentes.                                                                                        | EP-004 |
| US-013 | Reporte de productividad individual           | Como líder, quiero evaluar el desempeño de cada miembro a través de métricas claras.                                          | Escenario 1: Datos básicos: Given que selecciono un miembro, When genero su reporte, Then muestra: tareas completadas/tiempo promedio. Escenario 2: Comparativa: Given que veo dos reportes, When los comparo, Then resalta diferencias significativas.                                                                                                               | EP-004 |
| US-014 | Solicitud de aprobación de tarea              | Como miembro, quiero enviar tareas completadas para validación del líder.                                                     | Escenario 1: Envío estándar: Given que marco tarea como completada, When envío a validación, Then cambia a estado "En revisión". Escenario 2: Documentación adjunta: Given que agrego evidencia, When envío la solicitud, Then el líder ve los archivos asociados.                                                                                                    | EP-005 |
| US-015 | Validación de tareas                          | Como líder, quiero aprobar o rechazar tareas completadas para asegurar calidad.                                               | Escenario 1: Aprobación: Given que la tarea cumple estándares, When la apruebo, Then se marca como definitivamente completada. Escenario 2: Rechazo con comentarios: Given que encuentro deficiencias, When rechazo con feedback, Then la tarea vuelve a "En progreso".                                                                                               | EP-005 |
| US-016 | Solicitud de extensión de plazo               | Como miembro, quiero pedir más tiempo para una tarea cuando surgen impedimentos.                                              | Escenario 1: Solicitud básica: Given que selecciono una tarea, When pido extensión con motivo, Then el líder recibe notificación. Escenario 2: Aprobación: Given que el líder acepta, When actualiza la fecha, Then el sistema registra el cambio.                                                                                                                    | EP-005 |
| US-017 | Histórico de validaciones                     | Como líder, quiero ver el historial de aprobaciones/rechazos para identificar patrones.                                       | Escenario 1: Filtro por miembro: Given que selecciono un colaborador, When consulto su historial, Then muestra tasa de aprobación. Escenario 2: Detalle por tarea: Given que veo una entrada, When hago clic, Then muestra comentarios del validador.                                                                                                                 | EP-005 |
| US-018 | Notificaciones de cambio de estado            | Como miembro, quiero recibir alertas cuando mis solicitudes cambian de estado.                                                | Escenario 1: Aprobación recibida: Given que mi solicitud es aprobada, When el líder toma acción, Then recibo notificación con detalles. Escenario 2: Rechazo: Given que mi solicitud es rechazada, When hay comentarios, Then los incluye en la notificación.                                                                                                         | EP-005 |
| US-019 | Visualización de miembros del grupo           | Como líder, quiero ver la lista de miembros de mi grupo para gestionar la colaboración.                                       | Escenario 1: Lista de miembros: Given que accedo a la sección de miembros, When visualizo la lista, Then se muestran los nombres y roles de cada miembro. Escenario 2: Detalles del miembro: Given que selecciono un miembro, When hago clic en su nombre, Then se muestran sus tareas asignadas y estado actual.                                                     | EP-001 |
| US-020 | Edición de información del grupo              | Como líder, quiero editar la información de mi grupo para mantenerla actualizada.                                             | Escenario 1: Actualización de nombre: Given que accedo a la configuración del grupo, When modifico el nombre y guardo los cambios, Then el nuevo nombre se refleja en todas las vistas. Escenario 2: Cambio de descripción: Given que edito la descripción del grupo, When guardo los cambios, Then la nueva descripción se muestra en la página principal del grupo. | EP-001 |
| US-021 | Visualización de tareas asignadas             | Como miembro, quiero ver las tareas que me han sido asignadas para gestionar mi trabajo.                                      | Escenario 1: Lista de tareas: Given que accedo a mi panel de tareas, When visualizo la lista, Then se muestran todas las tareas asignadas con su estado actual. Escenario 2: Detalle de tarea: Given que selecciono una tarea, When hago clic en ella, Then se muestran los detalles completos de la tarea.                                                           | EP-002 |
| US-022 | Comentario en tareas                          | Como miembro, quiero comentar en las tareas para comunicarme con el líder sobre el progreso.                                  | Escenario 1: Añadir comentario: Given que accedo a una tarea asignada, When escribo un comentario y lo envío, Then el comentario aparece en el hilo de la tarea. Escenario 2: Notificación al líder: Given que envío un comentario, When el líder accede a la tarea, Then ve el nuevo comentario destacado.                                                           | EP-002 |
| US-023 | Configuración de preferencias de notificación | Como usuario, quiero configurar mis preferencias de notificación para recibir solo las alertas relevantes.                    | Escenario 1: Selección de tipos de notificación: Given que accedo a la configuración de notificaciones, When selecciono los tipos de eventos que deseo recibir, Then solo recibo notificaciones de esos eventos. Escenario 2: Desactivación de notificaciones: Given que desactivo todas las notificaciones, When ocurre un evento, Then no recibo ninguna alerta.    | EP-003 |
| US-024 | Resumen semanal de actividad                  | Como miembro, quiero recibir un resumen semanal de mi actividad para revisar mi desempeño.                                    | Escenario 1: Generación del resumen: Given que ha transcurrido una semana, When se genera el resumen, Then recibo un informe con mis tareas completadas y pendientes. Escenario 2: Acceso al resumen: Given que recibo el resumen, When accedo al enlace proporcionado, Then puedo ver el detalle completo en la plataforma.                                          | EP-003 |
| US-025 | Visualización de carga de trabajo por miembro | Como líder, quiero ver la carga de trabajo de cada miembro para equilibrar las asignaciones.                                  | Escenario 1: Gráfico de barras: Given que accedo al panel de analítica, When selecciono "Carga de trabajo", Then se muestra un gráfico de barras con el número de tareas por miembro. Escenario 2: Identificación de sobrecarga: Given que un miembro tiene más tareas que otros, When visualizo el gráfico, Then se resalta su barra.                                | EP-004 |
| US-026 | Reporte de cumplimiento de plazos             | Como líder, quiero ver un reporte de cumplimiento de plazos para evaluar la eficiencia del equipo.                            | Escenario 1: Generación del reporte: Given que accedo a la sección de reportes, When selecciono "Cumplimiento de plazos", Then se muestra un informe con el porcentaje de tareas completadas a tiempo. Escenario 2: Filtro por periodo: Given que elijo un rango de fechas, When aplico el filtro, Then el reporte se actualiza.                                      | EP-004 |
| US-027 | Revisión de comentarios en tareas             | Como líder, quiero revisar los comentarios en las tareas para proporcionar retroalimentación oportuna.                        | Escenario 1: Acceso a comentarios: Given que accedo a una tarea, When visualizo la sección de comentarios, Then puedo leer todos los mensajes. Escenario 2: Responder a comentarios: Given que leo un comentario, When escribo una respuesta y la envío, Then el miembro recibe una notificación.                                                                     | EP-005 |
| US-028 | Confirmación antes de eliminar una tarea      | Como líder, quiero recibir una confirmación antes de eliminar una tarea para evitar borrados accidentales.                    | Escenario 1: Confirmación requerida: Given que selecciono eliminar una tarea, When hago clic en eliminar, Then se muestra un mensaje de confirmación. Escenario 2: Cancelación: Given que aparece el mensaje, When elijo "Cancelar", Then la tarea no se elimina.                                                                                                     | EP-005 |
| US-029 | Recomendación de asignación de tareas         | Como líder, quiero que el sistema sugiera automáticamente a qué miembro asignar una tarea para optimizar la carga de trabajo. | Escenario 1: Sugerencia automática: Given que creo una tarea, When solicito recomendación, Then el sistema sugiere un miembro basado en carga y desempeño. Escenario 2: Sin datos suficientes: Given que no hay historial suficiente, When solicito recomendación, Then el sistema indica que no puede generar sugerencia.                                            | EP-007 |
| US-030 | Generación automática de resúmenes            | Como miembro, quiero que el sistema genere resúmenes automáticos de mi actividad para ahorrar tiempo.                         | Escenario 1: Resumen generado: Given que hay actividad semanal, When solicito resumen, Then el sistema genera un resumen claro de tareas. Escenario 2: Sin actividad: Given que no hay actividad, When solicito resumen, Then indica que no hay datos suficientes.                                                                                                    | EP-007 |
| US-031 | Priorización inteligente de tareas            | Como miembro, quiero que el sistema ordene mis tareas automáticamente según prioridad para trabajar de forma más eficiente.   | Escenario 1: Priorización automática: Given múltiples tareas, When accedo a mi lista, Then se ordenan por urgencia e importancia. Escenario 2: Actualización dinámica: Given cambios en tareas, When se actualiza el estado, Then la prioridad se recalcula.                                                                                                          | EP-007 |
| US-032 | Detección de sobrecarga de trabajo            | Como líder, quiero que el sistema detecte miembros sobrecargados para redistribuir tareas.                                    | Escenario 1: Sobrecarga detectada: Given un miembro con muchas tareas, When el sistema analiza carga, Then lo marca como sobrecargado. Escenario 2: Balance adecuado: Given carga equilibrada, When el sistema analiza, Then no genera alerta.                                                                                                                        | EP-007 |
| US-033 | Recomendación de reprogramación               | Como líder, quiero que el sistema sugiera nuevas fechas cuando detecta retrasos para mejorar la planificación.                | Escenario 1: Recomendación de nueva fecha: Given una tarea en riesgo, When el sistema analiza, Then sugiere nueva fecha límite. Escenario 2: Sin necesidad: Given tarea en tiempo, When analiza, Then no sugiere cambios.                                                                                                                                             | EP-007 |
| TS-001 | Gestión de grupos (CRUD)                      | Como developer, quiero gestionar grupos para crear, actualizar, consultar y eliminar equipos.                                 | Escenario 1: CRUD exitoso → operaciones GET/POST/PATCH/DELETE responden correctamente (200/201). Escenario 2: Error → IDs inválidos retornan 404 o 400.                                                                                                                                                                                                               | EP-001 |
| TS-002 | Gestión de miembros en grupos                 | Como developer, quiero agregar, listar y obtener miembros de grupos.                                                          | Escenario 1: Miembro agregado → POST exitoso (200). Escenario 2: Miembro inexistente → error 404.                                                                                                                                                                                                                                                                     | EP-001 |
| TS-003 | Gestión de solicitudes de unión               | Como developer, quiero manejar solicitudes para unirse a grupos.                                                              | Escenario 1: Crear solicitud → POST exitoso (200). Escenario 2: Duplicada → error 409.                                                                                                                                                                                                                                                                                | EP-001 |
| TS-004 | Procesamiento de solicitudes                  | Como developer, quiero aceptar, rechazar o eliminar solicitudes.                                                              | Escenario 1: Cambio de estado → PATCH cambia estado (200). Escenario 2: Eliminación → DELETE elimina correctamente (204).                                                                                                                                                                                                                                             | EP-001 |
| TS-005 | Gestión de tareas (CRUD)                      | Como developer, quiero crear, actualizar, obtener y eliminar tareas.                                                          | Escenario 1: CRUD exitoso → operaciones correctas (200/201). Escenario 2: Error → datos inválidos retornan 400/404.                                                                                                                                                                                                                                                   | EP-002 |
| TS-006 | Asignación y consulta de tareas               | Como developer, quiero asignar tareas y consultarlas por miembro o grupo.                                                     | Escenario 1: Consulta válida → devuelve lista de tareas (200). Escenario 2: Sin tareas → array vacío.                                                                                                                                                                                                                                                                 | EP-002 |
| TS-007 | Gestión de estados de tareas                  | Como developer, quiero actualizar estados de tareas (pendiente, completada, rechazada, vencida).                              | Escenario 1: Cambio válido → estado actualizado (200). Escenario 2: Estado inválido → error 400.                                                                                                                                                                                                                                                                      | EP-002 |
| TS-008 | Comentarios en tareas                         | Como developer, quiero permitir comentarios en tareas para colaboración.                                                      | Escenario 1: Comentario creado → POST exitoso (201). Escenario 2: Tarea inexistente → error 404.                                                                                                                                                                                                                                                                      | EP-002 |
| TS-009 | Validaciones automáticas de tareas            | Como developer, quiero automatizar validaciones de tareas vencidas.                                                           | Escenario 1: Tareas vencidas → estado cambia automáticamente. Escenario 2: Sin cambios → respuesta 204.                                                                                                                                                                                                                                                               | EP-002 |
| TS-010 | Gestión de notificaciones                     | Como developer, quiero enviar y consultar notificaciones.                                                                     | Escenario 1: Notificación enviada → POST exitoso (200). Escenario 2: Consulta → lista de notificaciones (200).                                                                                                                                                                                                                                                        | EP-003 |
| TS-011 | Gestión de estado de notificaciones           | Como developer, quiero marcar notificaciones como leídas.                                                                     | Escenario 1: Actualización → cambia estado (200). Escenario 2: Ya leída → mensaje informativo.                                                                                                                                                                                                                                                                        | EP-003 |
| TS-012 | Generación de reportes                        | Como developer, quiero generar y consultar reportes de métricas.                                                              | Escenario 1: Generación → POST exitoso (200). Escenario 2: Sin datos → respuesta válida con contenido vacío.                                                                                                                                                                                                                                                          | EP-004 |
| TS-013 | Autenticación (Login)                         | Como developer, quiero autenticar usuarios mediante JWT.                                                                      | Escenario 1: Login exitoso → token generado (200). Escenario 2: Error → credenciales inválidas (401).                                                                                                                                                                                                                                                                 | EP-006 |
| TS-014 | Gestión de usuarios                           | Como developer, quiero crear, editar y obtener usuarios.                                                                      | Escenario 1: CRUD usuario → operaciones exitosas (200/201). Escenario 2: Usuario no encontrado → 404.                                                                                                                                                                                                                                                                 | EP-006 |
| TS-015 | Cambio de contraseña                          | Como developer, quiero permitir actualizar contraseña de usuarios.                                                            | Escenario 1: Cambio válido → éxito (200). Escenario 2: Datos inválidos → error 400.                                                                                                                                                                                                                                                                                   | EP-006 |
| TS-016 | Microservice IAM                              | Como developer, quiero gestionar autenticación centralizada.                                                                  | Escenario 1: Generación de JWT → incluye roles y expiración.                                                                                                                                                                                                                                                                                                          | EP-006 |
| TS-017 | Microservice Tasks                            | Como developer, quiero gestionar tareas de forma desacoplada.                                                                 | Escenario 1: Crear tarea → estado inicial "pendiente".                                                                                                                                                                                                                                                                                                                | EP-002 |
| TS-018 | Microservice Metrics                          | Como developer, quiero generar métricas de tareas.                                                                            | Escenario 1: Consulta → devuelve resumen de tareas.                                                                                                                                                                                                                                                                                                                   | EP-004 |
| TS-019 | Microservice Requests                         | Como developer, quiero gestionar solicitudes del sistema.                                                                     | Escenario 1: Crear solicitud → estado "abierta".                                                                                                                                                                                                                                                                                                                      | EP-005 |
| TS-020 | Microservice Groups                           | Como developer, quiero gestionar grupos desde un servicio independiente.                                                      | Escenario 1: Crear grupo → valida usuarios y responde (201).                                                                                                                                                                                                                                                                                                          | EP-001 |
| TS-021 | Generación automática de resúmenes con IA     | Como developer, quiero generar resúmenes automáticos de actividad usando IA.                                                  | Escenario 1: Resumen generado → Given actividad existente, When se solicita resumen, Then devuelve texto resumido (200). Escenario 2: Sin actividad → Then devuelve mensaje "sin datos".                                                                                                                                                                              | EP-007 |
| TS-022 | Algoritmo de priorización de tareas           | Como developer, quiero ordenar tareas automáticamente según prioridad.                                                        | Escenario 1: Priorización válida → Given múltiples tareas, When se ejecuta el algoritmo, Then devuelve lista ordenada. Escenario 2: Datos incompletos → Then mantiene orden original.                                                                                                                                                                                 | EP-007 |
| TS-023 | Detección de sobrecarga de usuarios           | Como developer, quiero detectar usuarios con exceso de tareas asignadas.                                                      | Escenario 1: Sobrecarga detectada → Given tareas asignadas, When se analiza carga, Then marca usuario como sobrecargado. Escenario 2: Carga balanceada → Then no genera alerta.                                                                                                                                                                                       | EP-007 |
| TS-024 | Motor de recomendaciones de reprogramación    | Como developer, quiero sugerir nuevas fechas para tareas en riesgo.                                                           | Escenario 1: Recomendación generada → Given tarea con retraso, When se analiza, Then sugiere nueva fecha. Escenario 2: Tarea en tiempo → Then no sugiere cambios.                                                                                                                                                                                                     | EP-007 |
| TS-025 | Integración con modelo de IA externo          | Como developer, quiero integrar un servicio de IA (API) para procesar datos.                                                  | Escenario 1: Integración exitosa → Given request válido, When se envía a la API, Then devuelve respuesta procesada (200). Escenario 2: Error de API → Then maneja fallback o error controlado.                                                                                                                                                                        | EP-007 |
| TS-026 | Servicio de análisis de métricas para IA      | Como developer, quiero consumir datos de métricas para alimentar el agente inteligente.                                       | Escenario 1: Datos disponibles → Given métricas existentes, When se consultan, Then se devuelven correctamente (200). Escenario 2: Sin datos → Then devuelve estructura vacía.                                                                                                                                                                                        | EP-007 |

## 3.3. Impact Mapping

<img src="assets/chapter3/impact-mapping.png" alt="cc-alerting" width="800">


## 3.4. Product Backlog

A continuación se presenta el backlog de producto con las historias de usuario y tareas técnicas priorizadas para el desarrollo de Synhub

| Prioridad | Story ID | Título                                     | Descripción                                                                                   | SP |
|-----------|----------|--------------------------------------------|-----------------------------------------------------------------------------------------------|----|
| 1         | US-001   | Creación de grupo                          | Como líder, quiero crear grupos para organizar el trabajo de mi equipo.                       | 5  |
| 1         | US-004   | Creación de tareas                         | Como líder, quiero crear tareas para asignar trabajo a los miembros.                          | 5  |
| 1         | US-005   | Asignación de tareas                       | Como líder, quiero asignar tareas a miembros específicos para distribuir el trabajo.          | 5  |
| 1         | TS-001   | Gestión de grupos (CRUD)                   | Como developer, quiero gestionar grupos para crear, actualizar, consultar y eliminar equipos. | 5  |
| 1         | TS-005   | Gestión de tareas (CRUD)                   | Como developer, quiero crear, actualizar, obtener y eliminar tareas.                          | 5  |
| 1         | TS-013   | Autenticación (Login)                      | Como developer, quiero autenticar usuarios mediante JWT.                                      | 5  |
| 1         | TS-020   | Microservice Groups                        | Como developer, quiero gestionar grupos desde un servicio independiente.                      | 3  |
| 1         | TS-017   | Microservice Tasks                         | Como developer, quiero gestionar tareas de forma desacoplada.                                 | 3  |
| 2         | US-002   | Envío de invitaciones                      | Como líder, quiero invitar miembros a mi grupo para conformar el equipo.                      | 5  |
| 2         | US-007   | Actualización de estado                    | Como miembro, quiero actualizar el estado de mis tareas para reflejar mi progreso.            | 3  |
| 2         | US-021   | Visualización de tareas asignadas          | Como miembro, quiero ver las tareas que me han sido asignadas para gestionar mi trabajo.      | 3  |
| 2         | US-019   | Visualización de miembros del grupo        | Como líder, quiero ver la lista de miembros de mi grupo para gestionar la colaboración.       | 3  |
| 2         | TS-002   | Gestión de miembros en grupos              | Como developer, quiero agregar, listar y obtener miembros de grupos.                          | 3  |
| 2         | TS-006   | Asignación y consulta de tareas            | Como developer, quiero asignar tareas y consultarlas por miembro o grupo.                     | 3  |
| 2         | TS-007   | Gestión de estados de tareas               | Como developer, quiero actualizar estados de tareas.                                          | 3  |
| 2         | TS-014   | Gestión de usuarios                        | Como developer, quiero crear, editar y obtener usuarios.                                      | 3  |
| 3         | US-008   | Reprogramación de tareas                   | Como líder, quiero cambiar fechas límite cuando surgen imprevistos.                           | 2  |
| 3         | US-022   | Comentario en tareas                       | Como miembro, quiero comentar en las tareas para comunicarme con el líder.                    | 2  |
| 3         | US-009   | Notificaciones multicanal                  | Como miembro, quiero recibir notificaciones tanto en la plataforma como por email.            | 3  |
| 3         | TS-003   | Gestión de solicitudes de unión            | Como developer, quiero manejar solicitudes para unirse a grupos.                              | 3  |
| 3         | TS-004   | Procesamiento de solicitudes               | Como developer, quiero aceptar, rechazar o eliminar solicitudes.                              | 3  |
| 3         | TS-010   | Gestión de notificaciones                  | Como developer, quiero enviar y consultar notificaciones.                                     | 3  |
| 3         | TS-011   | Gestión de estado de notificaciones        | Como developer, quiero marcar notificaciones como leídas.                                     | 2  |
| 3         | TS-019   | Microservice Requests                      | Como developer, quiero gestionar solicitudes del sistema.                                     | 3  |
| 4         | US-010   | Gráfico de distribución de tareas          | Como líder, quiero ver un gráfico pastel con la distribución de tareas.                       | 3  |
| 4         | US-011   | Gráfico de estados de tareas               | Como líder, quiero ver un gráfico de barras con el estado de tareas.                          | 3  |
| 4         | US-012   | Reporte de reprogramaciones                | Como líder, quiero ver un gráfico de líneas de tareas reprogramadas.                          | 2  |
| 4         | US-013   | Reporte de productividad individual        | Como líder, quiero evaluar el desempeño de cada miembro.                                      | 2  |
| 4         | US-025   | Visualización de carga de trabajo          | Como líder, quiero ver la carga de trabajo por miembro.                                       | 1  |
| 4         | US-026   | Reporte de cumplimiento de plazos          | Como líder, quiero evaluar la eficiencia del equipo.                                          | 1  |
| 4         | TS-012   | Generación de reportes                     | Como developer, quiero generar y consultar reportes de métricas.                              | 5  |
| 4         | TS-018   | Microservice Metrics                       | Como developer, quiero generar métricas de tareas.                                            | 3  |
| 5         | US-014   | Solicitud de aprobación de tarea           | Como miembro, quiero enviar tareas completadas para validación.                               | 3  |
| 5         | US-015   | Validación de tareas                       | Como líder, quiero aprobar o rechazar tareas completadas.                                     | 3  |
| 5         | US-016   | Solicitud de extensión de plazo            | Como miembro, quiero pedir más tiempo para una tarea.                                         | 2  |
| 5         | US-017   | Histórico de validaciones                  | Como líder, quiero ver historial de aprobaciones.                                             | 2  |
| 5         | US-018   | Notificaciones de cambio de estado         | Como miembro, quiero recibir alertas de cambios.                                              | 2  |
| 6         | TS-015   | Cambio de contraseña                       | Como developer, quiero permitir actualizar contraseña.                                        | 2  |
| 6         | TS-016   | Microservice IAM                           | Como developer, quiero gestionar autenticación centralizada.                                  | 3  |
| 7         | US-029   | Recomendación de asignación de tareas      | Como líder, quiero que el sistema sugiera asignaciones.                                       | 5  |
| 7         | US-030   | Generación automática de resúmenes         | Como miembro, quiero resúmenes automáticos.                                                   | 3  |
| 7         | US-031   | Priorización inteligente de tareas         | Como miembro, quiero que el sistema ordene tareas automáticamente.                            | 3  |
| 7         | US-032   | Detección de sobrecarga de trabajo         | Como líder, quiero detectar miembros sobrecargados.                                           | 3  |
| 7         | US-033   | Recomendación de reprogramación            | Como líder, quiero sugerencias de nuevas fechas.                                              | 3  |
| 7         | TS-021   | Generación automática de resúmenes con IA  | Como developer, quiero generar resúmenes con IA.                                              | 5  |
| 7         | TS-022   | Algoritmo de priorización de tareas        | Como developer, quiero ordenar tareas automáticamente.                                        | 3  |
| 7         | TS-023   | Detección de sobrecarga de usuarios        | Como developer, quiero detectar usuarios sobrecargados.                                       | 3  |
| 7         | TS-024   | Motor de recomendaciones de reprogramación | Como developer, quiero sugerir nuevas fechas.                                                 | 3  |
| 7         | TS-025   | Integración con modelo de IA externo       | Como developer, quiero integrar un servicio de IA.                                            | 5  |
| 7         | TS-026   | Servicio de análisis de métricas para IA   | Como developer, quiero consumir métricas para IA.                                             | 3  |


# 4. Capítulo IV: Strategic-Level Software Design



## 4.1. Strategic-Level Attribute-Driven Design



### 4.1.1. Design Purpose

El propósito del diseño de la aplicación es proporcionar una plataforma integral para la gestión de grupos, miembros, tareas, notificaciones, reportes y procesos de validación, asegurando una experiencia de usuario consistente y funcional para ambos segmentos.

La aplicación tiene como objetivo principal facilitar la colaboración, la asignación de responsabilidades y el seguimiento de avances en equipos de trabajo, ofreciendo funcionalidades que van desde la organización de grupos y distribución de tareas, hasta la generación de métricas y reportes.

## Enfoque Arquitectónico

Desde el punto de vista arquitectónico, el diseño prioriza:

- **Escalabilidad:** Soportando un número elevado de usuarios, grupos y transacciones.
- **Seguridad:** Gestionando accesos y roles mediante autenticación y control de permisos.
- **Disponibilidad:** Asegura que la plataforma tenga una accesibilidad del 99% con mínimas interrupciones en la gestión de tareas y notificaciones.


### 4.1.2. Attribute-Driven Design Inputs



#### 4.1.2.1. Primary Functionality (Primary User Stories)

| Requisito Funcional         | US - ID | Título                                        |
|-----------------------------|---------|-----------------------------------------------|
| Gestión de grupos           | US-001  | Creación de grupo                             |
| Gestión de grupos           | US-002  | Envío de invitaciones                         |
| Gestión de Tareas           | US-004  | Creación de tareas                            |
| Gestión de Tareas           | US-005  | Asignación de tareas                          |
| Gestión de Tareas           | US-007  | Actualización de estado                       |
| Notificaciones Inteligentes | US-009  | Notificaciones in-app                         |
| Notificaciones Inteligentes | US-010  | Notificaciones por email                      |
| Analíticas y Reportes       | US-012  | Gráfico de distribución de tareas             |
| Analíticas y Reportes       | US-015  | Reporte de productividad individual           |
| Solicitudes y Validaciones  | US-016  | Solicitud de aprobación de tarea              |
| Solicitudes y Validaciones  | US-017  | Validación de tareas                          |
| Gestión de Usuarios         | US-025  | Configuración de preferencias de notificación |


#### 4.1.2.2. Quality attribute Scenarios

| ID   | Atributo de calidad | Fuente                                      | Estímulo                                         | Medioambiente                                         | Artefacto                               | Respuesta                                            | Medida                                                        |
|------|---------------------|---------------------------------------------|--------------------------------------------------|-------------------------------------------------------|-----------------------------------------|------------------------------------------------------|---------------------------------------------------------------|
| QA-1 | Disponibilidad      | Usuario que desea acceder a sus tareas      | Solicita ver la lista de tareas en tiempo real   | Aplicación en horario normal con tráfico promedio     | Servicio de gestión de tareas           | La aplicación devuelve la lista completa sin errores | Tiempo de respuesta < 2s y 99% de disponibilidad del servicio |
| QA-2 | Interoperabilidad   | Usuario que recibe notificaciones por email | Configurar preferencias de notificación          | Sistema conectado a la red, servicio de correo activo | Servicio de notificaciones inteligentes | Notificación enviada y recibida correctamente        | Porcentaje de emails entregados correctamente = 100%          |
| QA-3 | Modificabilidad     | Equipo de desarrollo                        | Agrega un nuevo tipo de gráfico de productividad | Entorno de desarrollo con datos de prueba             | Servicio de reportes y dashboards       | Nuevo gráfico integrado sin afectar funcionalidades  | Integración < 2 días y pruebas unitarias exitosas             |
| QA-4 | Performance         | Usuario genera reporte                      | Solicita reporte con gran volumen de datos       | Aplicación bajo carga alta                            | Servicio de generación de reportes      | Reporte generado correctamente con todos los datos   | Tiempo de generación < 10s                                    |
| QA-5 | Seguridad           | Usuario o atacante externo                  | Intento de acceso sin permisos                   | Aplicación y red funcionando normalmente              | Servicio de autenticación y usuarios    | Acceso bloqueado y registrado en logs                | 100% de accesos no autorizados bloqueados + logs generados    |
| QA-6 | Testeabilidad       | Equipo de QA                                | Ejecuta pruebas de creación de grupos y tareas   | Entorno de pruebas controlado                         | Servicios de gestión de grupos y tareas | Resultados registrados y reproducibles               | Cobertura de pruebas > 90%                                    |
| QA-7 | Usabilidad          | Usuario final                               | Intenta crear o editar grupo o tarea             | App móvil funcionando                                 | Interfaz de usuario                     | Usuario completa operación sin confusión             | Tiempo promedio < 2 min por operación                         |

#### 4.1.2.3. Constraints

| Factor | Constraint (restricción posible para la aplicación) |
|--------|--------------------------------------------------|
| Topología de la red | Si la red tiene alta latencia o está segmentada, las notificaciones in-app y la sincronización de tareas podrían retrasarse. **Ejemplo:** un miembro marcó una tarea como completada (US-007), pero el líder no recibió la notificación inmediatamente debido a problemas de red. |
| Uso de un proveedor de base de datos | Si solo se puede usar un tipo específico de base de datos, puede limitar la optimización de consultas complejas. **Ejemplo:** generar un reporte de productividad individual (US-015) puede tardar más si la base de datos no soporta consultas avanzadas de agregación eficientemente. |
| Entorno web / móvil | Configuraciones restrictivas podrían bloquear correos o integraciones externas. **Ejemplo:** las notificaciones por email (US-010) no llegan a los usuarios, porque el servidor de correo está bloqueado por el firewall de la red corporativa. |
| Servidores (hardware, sistema operativo) | Servidores con recursos limitados pueden causar lentitud en operaciones intensivas. **Ejemplo:** al generar gráficos de carga de trabajo por miembro (US-027), la visualización se retrasa cuando varios líderes acceden al dashboard simultáneamente. |
| Uso de software de terceros o tecnología particular | Dependencias de librerías externas puede generar incompatibilidades futuras. **Ejemplo:** el módulo de gráficos de barras (US-012 y US-013) deja de renderizar correctamente después de actualizar la versión de las librerías involucradas. |
| Cumplimiento de normas existentes | La aplicación debe cumplir con las políticas internas de la empresa sobre auditoría y registro de acciones de los usuarios. **Ejemplo:** cada actualización de estado de tarea (US-007) debe registrarse con el fin de tener un seguimiento. |

### 4.1.3. Architectural Drivers Backlog

En esta iteración, hemos priorizado los drivers de **usabilidad** y **mantenibilidad**, orientando el diseño hacia un componente de asignación de tareas que permita crear, asignar y dar seguimiento a tareas por usuario de manera intuitiva, manteniendo responsabilidades desacopladas para facilitar la evolución del sistema.

| Driver ID | Título de Driver | Descripción | Importancia (Stakeholders) | Impacto (Technical Complexity) |
|---|---|---|---|---|
| AD-01 | Usabilidad | El componente de asignación de tareas debe permitir la creación, asignación y seguimiento de tareas de forma simple, clara e intuitiva para los usuarios. | Alto | Medio |
| AD-02 | Mantenibilidad | El componente debe diseñarse con responsabilidades desacopladas para facilitar mantenimiento, pruebas y evolución del sistema. | Alto | Alto |
| AD-03 | Gestión de tareas por usuario | El sistema debe soportar la administración y seguimiento de tareas asignadas a cada usuario dentro del grupo. | Alto | Medio |
| AD-04 | Separación de responsabilidades | La arquitectura debe dividir interfaz, lógica de negocio y acceso a datos para reducir acoplamiento. | Alto | Alto |
| AD-05 | Consistencia de datos | La asignación y actualización de tareas debe preservar integridad y coherencia en estados y responsables. | Alto | Medio |

### 4.1.4. Architectural Design Decisions

El equipo evaluó decisiones arquitectónicas para el componente de asignación de tareas, considerando como drivers principales la <strong>usabilidad</strong> y la <strong>mantenibilidad</strong>. El objetivo fue definir una solución que permita crear, asignar y dar seguimiento a tareas por usuario, manteniendo una estructura desacoplada y fácil de evolucionar.

<table>
  <tr>
    <td rowspan="2"><strong>Driver ID</strong></td>
    <td rowspan="2"><strong>Título de Driver</strong></td>
    <td colspan="2"><strong>Pattern 1: Arquitectura en Capas</strong></td>
    <td colspan="2"><strong>Pattern 2: MVC</strong></td>
    <td colspan="2"><strong>Pattern 3: Event-Driven</strong></td>
  </tr>
  <tr>
    <td><strong>Pro</strong></td>
    <td><strong>Con</strong></td>
    <td><strong>Pro</strong></td>
    <td><strong>Con</strong></td>
    <td><strong>Pro</strong></td>
    <td><strong>Con</strong></td>
  </tr>

  <tr>
    <td>AD-01</td>
    <td>Usabilidad</td>
    <td>Permite interfaces claras separando responsabilidades</td>
    <td>No gestiona interacción en tiempo real por sí sola</td>
    <td>Organiza bien la interacción UI</td>
    <td>Puede centrarse demasiado en la interfaz</td>
    <td>Permite actualización dinámica</td>
    <td>Aumenta complejidad innecesaria</td>
  </tr>

  <tr>
    <td>AD-02</td>
    <td>Mantenibilidad</td>
    <td>Bajo acoplamiento y alta modularidad</td>
    <td>Puede volverse rígida si se diseña mal</td>
    <td>Estructura simple</td>
    <td>No escala bien en backend complejo</td>
    <td>Desacopla componentes</td>
    <td>Difícil de depurar</td>
  </tr>

  <tr>
    <td>AD-03</td>
    <td>Gestión de tareas por usuario</td>
    <td>Facilita reglas de negocio</td>
    <td>Mayor estructura inicial</td>
    <td>Adecuado para CRUD</td>
    <td>Menor claridad en lógica compleja</td>
    <td>Útil para eventos derivados</td>
    <td>No ideal como base principal</td>
  </tr>

  <tr>
    <td>AD-04</td>
    <td>Separación de responsabilidades</td>
    <td>Alta</td>
    <td>Requiere disciplina</td>
    <td>Media</td>
    <td>Menos estructurada</td>
    <td>Alta</td>
    <td>No cubre toda la arquitectura</td>
  </tr>

  <tr>
    <td>AD-05</td>
    <td>Consistencia de datos</td>
    <td>Centraliza validaciones</td>
    <td>Puede requerir coordinación</td>
    <td>Simple</td>
    <td>Riesgo de mezclar lógica</td>
    <td>Útil en procesos asíncronos</td>
    <td>Complica consistencia inmediata</td>
  </tr>

</table>

<br>

<p><strong>Decisión:</strong> Hemos seleccionado la <strong>Arquitectura en Capas</strong> como patrón principal por su alta mantenibilidad y separación de responsabilidades. Se complementa con <strong>Event-Driven</strong> para notificaciones y eventos derivados.</p>

### 4.1.5. Quality Attribute Scenario Refinements

<table>
  <tr>
    <td colspan="3"><strong>Scenario Refinement for Scenario 1</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Scenario(s):</strong></td>
    <td>Usabilidad en la asignación de tareas</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Business Goals:</strong></td>
    <td>Facilitar la adopción del sistema y mejorar la experiencia del usuario al crear, asignar y revisar tareas.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Relevant Quality Attributes:</strong></td>
    <td>Usabilidad</td>
  </tr>
  <tr>
    <td></td>
    <td><strong>Stimulus:</strong></td>
    <td>El usuario necesita crear, asignar o revisar una tarea dentro del sistema.</td>
  </tr>
  <tr>
    <td rowspan="5"><strong>Scenario Components</strong></td>
    <td><strong>Stimulus Source:</strong></td>
    <td>Usuario autenticado</td>
  </tr>
  <tr>
    <td><strong>Environment:</strong></td>
    <td>Operación normal del sistema</td>
  </tr>
  <tr>
    <td><strong>Artifact (if Known)</strong></td>
    <td>Componente de asignación de tareas</td>
  </tr>
  <tr>
    <td><strong>Response:</strong></td>
    <td>El sistema permite realizar la acción de forma clara, rápida e intuitiva, mostrando retroalimentación inmediata.</td>
  </tr>
  <tr>
    <td><strong>Response Measure:</strong></td>
    <td>El usuario completa la acción en pocos pasos, sin errores y sin necesidad de ayuda externa.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Questions:</strong></td>
    <td>¿Cuántos pasos se requieren para asignar una tarea?<br>¿Qué feedback recibe el usuario?<br>¿Qué acciones deben ser visibles?</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Issues:</strong></td>
    <td>No se han definido métricas exactas de tiempo o interacción.<br>Falta detallar validaciones de interfaz.</td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td colspan="3"><strong>Scenario Refinement for Scenario 2</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Scenario(s):</strong></td>
    <td>Mantenibilidad del componente de tareas</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Business Goals:</strong></td>
    <td>Permitir cambios futuros en el sistema sin afectar otros módulos.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Relevant Quality Attributes:</strong></td>
    <td>Mantenibilidad</td>
  </tr>
  <tr>
    <td></td>
    <td><strong>Stimulus:</strong></td>
    <td>Se requiere modificar la lógica del componente de tareas (nuevas reglas o funcionalidades).</td>
  </tr>
  <tr>
    <td rowspan="5"><strong>Scenario Components</strong></td>
    <td><strong>Stimulus Source:</strong></td>
    <td>Desarrollador</td>
  </tr>
  <tr>
    <td><strong>Environment:</strong></td>
    <td>Mantenimiento o evolución del sistema</td>
  </tr>
  <tr>
    <td><strong>Artifact (if Known)</strong></td>
    <td>Componente de asignación de tareas</td>
  </tr>
  <tr>
    <td><strong>Response:</strong></td>
    <td>El cambio se realiza de manera localizada sin afectar otros componentes.</td>
  </tr>
  <tr>
    <td><strong>Response Measure:</strong></td>
    <td>Bajo impacto en otros módulos y facilidad de pruebas tras el cambio.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Questions:</strong></td>
    <td>¿Cómo se separan las responsabilidades?<br>¿Qué cambios futuros se esperan?<br>¿Qué partes deben estar desacopladas?</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Issues:</strong></td>
    <td>No están definidos completamente los límites entre capas.<br>Falta estrategia de pruebas para cambios futuros.</td>
  </tr>
</table>

## 4.2. Strategic-Level Domain-Driven Design

En esta sección se presenta el enfoque adoptado para la toma de decisiones estratégicas en el desarrollo del sistema, aplicando los principios del Domain-Driven Design (DDD). El objetivo principal consistió en identificar y establecer los límites naturales del dominio, descomponiendo la solución en contextos delimitados (Bounded Contexts).

Para llevar a cabo dicha descomposición, el equipo empleó herramientas colaborativas clave, tales como el Event Storming, que permite mapear y visualizar de manera dinámica los flujos de eventos, comandos y actores dentro del dominio; y el Bounded Context Canvas, utilizado para definir los elementos esenciales de cada contexto, incluyendo objetivos, modelos, responsabilidades y relaciones con otros contextos.

Dicho proceso estratégico permite no solo estructurar el sistema de forma más coherente, sino también alinear las decisiones técnicas con los objetivos de negocio, facilitando la comunicación entre los distintos actores involucrados en el desarrollo del proyecto.

### 4.2.1. EventStorming

En esta sección se expone y justifica el proceso de EventStorming ejecutado por el equipo, con el fin de construir una aproximación inicial al modelado general del dominio del problema. Dicha técnica, centrada en la identificación de eventos relevantes dentro del sistema, facilita la captura del conocimiento colectivo de los participantes y promueve conversaciones fundamentales acerca del comportamiento esperado del sistema ante diversos escenarios.

La sesión fue planificada estratégicamente con una duración comprendida entre una y dos horas. Durante esta actividad, se emplearon notas adhesivas digitales para representar eventos y comandos, lo que permite una exploración visual e iterativa del flujo de trabajo.

[![EventStorming](https://i.postimg.cc/pXfjDrxc/image.png)](https://postimg.cc/2V53Yz1n)

### 4.2.2. Candidate Context Discovery

Una vez concluida la sesión de Event Storming, se llevó a cabo un análisis detallado de los eventos identificados con el propósito de descubrir los contextos candidatos potencialmente relevantes para el dominio del problema. Dicho análisis consistió en la identificación de patrones y relaciones entre los eventos, así como en la evaluación de su impacto sobre el sistema. Como resultado, se establecieron agrupaciones de eventos pertenecientes a un mismo proceso de acción dentro de la aplicación.

[![Candidate Context Discovery](https://i.postimg.cc/wjMcpNSf/image.png)](https://postimg.cc/5XcF5X9L)

A continuación se muestra con detalle las líneas de acción creadas:

**Creación de grupo**

[![Creacion-de-grupo.png](https://i.postimg.cc/SR5QYwxm/Creacion-de-grupo.png)](https://postimg.cc/vxrwp2nK)

**Asignación de tareas**

[![Asignacion-de-tareas.png](https://i.postimg.cc/Xv7vhKmj/Asignacion-de-tareas.png)](https://postimg.cc/hX6gQmK6)

**Modificación de tareas**

[![Modificacion-de-tareas.png](https://i.postimg.cc/cHtdyFc5/Modificacion-de-tareas.png)](https://postimg.cc/tZbKFtwh)

**Cumplimiento de tareas**

[![Cumplimiento-de-tareas.png](https://i.postimg.cc/3rgHX4fb/Cumplimiento-de-tareas.png)](https://postimg.cc/bdNM8JhQ)

**Incumplimiento de tareas**

[![Incumplimiento-de-tareas.png](https://i.postimg.cc/G3PZ809x/Incumplimiento-de-tareas.png)](https://postimg.cc/w3vWZGX1)

Una vez creadas las líneas de acción se buscó encontrar los "pain points", solo se tuvo que modificar la línea de acción de creación de grupo. 

**Creación de grupo**

[![Creacion-de-Grupo-V2.png](https://i.postimg.cc/bwdy9Ytj/Creacion-de-Grupo-V2.png)](https://postimg.cc/LJKFHpDy)

Una vez terminadas las líneas de acción se buscó encontrar los "pivotal point", los cuales son eventos que pueden cambiar el flujo de la aplicación.
Los pivotal point encontrados fueron:

- La creación de un grupo
- La creación de una tarea
- La modificación de una tarea
- La asignación de una tarea
- Acciones que requieran enviar notificaciones
- El cumplimiento de tareas
- El incumplimiento de tareas

Gracias a encontrar los pivotal points se pudo identificar como los distintos eventos formaban parte de distintos contextos, los cuales son:

- Líderes
- Notificaciones
- Tareas
- Métricas
- Solicitudes

Finalmente se dividio cada evento en comandos, eventos, agregados, vistas y entidades, los cuales son los siguientes:

**Líderes**

[![Lideres.png](https://i.postimg.cc/bNst2fdD/Lideres.png)](https://postimg.cc/7fr6pc3w)

**Notificaciones**

[![Notificaciones.png](https://i.postimg.cc/vTDc958M/Notificaciones.png)](https://postimg.cc/xNDfVJbF)

**Tareas**

[![Tareas.png](https://i.postimg.cc/MGDTF9vJ/Tareas.png)](https://postimg.cc/TyKfyqVt)

**Métricas**

[![Metricas.png](https://i.postimg.cc/qvHvBP3F/Metricas.png)](https://postimg.cc/N5bcpPb8)

**Solicitudes**

[![Solicitudes.png](https://i.postimg.cc/RFhMb9k7/Solicitudes.png)](https://postimg.cc/jwV0DVd2)

### 4.2.3. Domain Message Flows Modeling

Como siguiente paso se buscó interconectar los bounded contexts encontrados en la sección anterior, para esto se buscó encontrar los eventos que se comunican entre los distintos contextos.

**Líderes y Notificaciones:** 
Al generar una invitación de grupo se envía una notificación al usuario invitado, y al aceptar la invitación se envía una notificación al creador del grupo.

[![Lideres-y-Notificaciones.png](https://i.postimg.cc/8cHg1YQq/Lideres-y-Notificaciones.png)](https://postimg.cc/H8VhzBL2)

**Tareas y Notificaciones:** 
Al crear una tarea se envía una notificación al usuario asignado, y al cumplir la tarea se envía una notificación al creador de la tarea.

[![Tareas-y-Notificaciones.png](https://i.postimg.cc/htX6wvvj/Tareas-y-Notificaciones.png)](https://postimg.cc/tsHBnXhQ)

**Notificaciones y Solicitudes:** 
Al momento de marcarse tareas como completadas o no completadas se envía una notificación al coordinador. Al asignar reprogramar tareas se enviará notificaciones al usuario antiguo y al nuevo usuario al que pertenece la tarea. Al modificar(actualizar, reprogramar o eliminar) tareas se enviará una notificación a todos los involucrados (coordinadores e integrantes).

[![Notificaciones-y-Solicitudes.png](https://i.postimg.cc/yx6rTY2W/Notificaciones-y-Solicitudes.png)](https://postimg.cc/VrTRf1fc)

**Solicitudes y Métricas:** Al validarse si se completó o no una tarea se crean o modifican las estadísticas de progreso grupal.

[![Solicitudes-y-Metricas.png](https://i.postimg.cc/3wMScZP5/Solicitudes-y-Metricas.png)](https://postimg.cc/ZWcx96bV)

Finalmente se muestra una captura global de la arquitectura del sistema, donde se puede ver la interacción entre los distintos componentes y como se comunican entre ellos.

[![Totalidad.png](https://i.postimg.cc/CxKSKw1h/Totalidad.png)](https://postimg.cc/BXRdY9Hk)

Enlace del Miro board sobre el que se trabajo: https://miro.com/app/board/uXjVHf1ECEI=/?share_link_id=687998549144

### 4.2.4. Bounded Context Canvases

En esta sección se desarrolla la descomposición estratégica del dominio a través de la elaboración de los Bounded Context Canvases, con el propósito de identificar y delimitar áreas funcionalmente coherentes dentro del sistema. Dicha práctica constituye una parte esencial del enfoque de Domain-Driven Design (DDD), dado que permite clarificar los límites semánticos y técnicos entre las distintas porciones del sistema, reduciendo la complejidad y favoreciendo la evolución independiente de cada componente.

El equipo ha definido previamente un conjunto de contextos delimitados candidatos, ordenados de acuerdo con su importancia funcional y estratégica. Con base en esta priorización, se procede al diseño iterativo de los Bounded Context Canvases. Cada canvas incorpora los siguientes elementos clave:

- **Context Overview Definition:** para comprender el propósito y el alcance del contexto.
- **Business Rules Distillation & Ubiquitous Language Capture:** para identificar las reglas de negocio fundamentales y establecer un lenguaje común entre los actores involucrados y los desarrolladores.
- **Capability Analysis y Capability Layering:** para entender las capacidades funcionales que ofrece el contexto y, si resulta necesario, organizarlas en capas.
- **Dependencies Capture:** para reconocer las relaciones con otros contextos y sus posibles implicaciones.
- **Design Critique:** para revisar y perfeccionar el diseño propuesto desde una perspectiva crítica y colaborativa.

**Líderes - Canvas**

[![Lideres-Canvas.png](https://i.postimg.cc/QCWKwc29/Lideres-Canvas.png)](https://postimg.cc/RJ40nJV4)

**Tareas - Canvas**

[![Tareas-Canvas.png](https://i.postimg.cc/j5DhqnVP/Tareas-Canvas.png)](https://postimg.cc/fthdBLRR)

**Solicitudes - Canvas**

[![Solicitudes-Canvas.png](https://i.postimg.cc/65JhwQYF/Solicitudes-Canvas.png)](https://postimg.cc/LhDP3mdV)

**Notificaciones - Canvas**

[![Notificaciones-Canvas.png](https://i.postimg.cc/8zwdhmNz/Notificaciones-Canvas.png)](https://postimg.cc/rD0tTWDB)

**Métricas - Canvas**

[![Metricas-Canvas.png](https://i.postimg.cc/fLSxQ4X0/Metricas-Canvas.png)](https://postimg.cc/KkFKtH0Z)

### 4.2.5. Context Mapping

El Context Mapping constituye una técnica fundamental dentro del enfoque estratégico del Domain-Driven Design (DDD), pues permite visualizar y comprender el modo en que interactúan los distintos contextos delimitados (Bounded Contexts) en un sistema complejo. Mediante esta herramienta, se identifican las relaciones, dependencias y límites de comunicación entre contextos, definiendo con claridad los flujos de información, los tipos de colaboración (tales como Customer/Supplier, Conformist, Partnership o Anticorruption Layer) y el empleo de patrones como Open Host Service.

El propósito del Context Mapping radica en facilitar una arquitectura de software más modular, mantenible y alineada con el dominio del negocio, permitiendo que cada contexto evolucione de manera autónoma sin generar acoplamientos innecesarios. Esta representación también respalda la toma de decisiones relativas a integraciones, responsabilidades y coordinación entre equipos.

[![Context-Mapping.png](https://i.postimg.cc/m2y7sycw/Context-Mapping.png)](https://postimg.cc/nCMXK7Gj)

| Destino (Downstream)       | Origen (Upstream)           | Tipo de Relación | ¿OHS? | Comentario                                                              |
| -------------------------- | --------------------------- | ----------------- | ------ | ----------------------------------------------------------------------- |
| Métricas      | Líderes         | Customer/Supplier | No     | Expone información grupal                                                      |
| Solicitudes | Líderes          | Customer/Supplier | Si     | Se nutre de los datos de los integrantres                               |
| Tareas        | Líderes       | Customer/Supplier | No     | Obtiene información de los integrantes de grupo                        |
| Tareas       | Solicitudes | Partnership       | No     | Comparte información entre sí de las tareas                           |
| Métricas     | Tareas     | Customer/Supplier | Si     | Se nutre de la información de las tareas para elaborar reportes        |
| Métricas     | Solicitudes  | Customer/Supplier | No     | Obtiene la infomración de actualización de cambios y solicitudes       |
| Notificaciones             | Líderes, Solicitudes, Tareas | Partnership       | No     | Emite notificaciones según instrucciones de los demás bounded context |

## 4.3. Software Architecture

La arquitectura del sistema se organiza en tres niveles. En primer lugar, el Context Diagram define las interacciones externas entre SynHub —núcleo del sistema—, sus usuarios (Miembro y Líder) y servicios externos como Cloudinarym, Gemini y Sendgrid. En segundo lugar, el Container Diagram descompone SynHub en módulos fundamentales (Mobile App, API REST, PostgreSQL y Landing Page), especificando sus responsabilidades y los mecanismos de comunicación interna. Finalmente, el Deployment Diagram detalla el despliegue físico y en la nube de estos componentes, abarcando servidores, dispositivos móviles y conexiones con APIs externas. En conjunto, estos diagramas garantizan un diseño escalable, integrado y adecuadamente estructurado.

### 4.3.1. Software Architecture System Landscape Diagram

El System Landscape diagrama representa el nivel inicial y de mayor abstracción en el modelo C4, diseñado para ofrecer una visión panorámica de la infraestructura tecnológica dentro de un contexto organizacional o de negocio. Este esquema articula la posición de un sistema de software específico en relación con otros sistemas externos, usuarios finales y actores institucionales, facilitando la identificación de dependencias, puntos de integración y límites del ecosistema completo. Su función principal es comunicar el alcance del proyecto a audiencias técnicas y no técnicas, estableciendo un marco de referencia que permite comprender el rol funcional y la interoperabilidad de la solución desarrollada dentro de un entorno complejo.

[![Landscape.png](https://i.postimg.cc/VL9jjrt6/Landscape.png)](https://postimg.cc/SJs24KDF)

### 4.3.2. Software Architecture Context Level Diagrams

El Context Diagram muestra a SynHub (el sistema central) interactuando con sus usuarios principales —el Miembro y el Líder— quienes utilizan la aplicación para gestionar actividades, mientras que SynHub se integra con Gemini, Cloudinary y Sendgrid. Este diagrama enfatiza las relaciones externas del sistema, sin detallar componentes internos, destacando cómo los actores clave (usuarios y servicios externos) se conectan con la plataforma principal para intercambiar información.

[![Context.png](https://i.postimg.cc/8PCwZCPb/Context.png)](https://postimg.cc/14LptsFg)

### 4.3.3. Software Architecture Container Level Diagrams

El diagrama de contenedores de **SynHub** propone una arquitectura de microservicios robusta y altamente desacoplada, fundamentada en la especialización de responsabilidades. En la capa de acceso, el **API Gateway** unifica la interacción del usuario final, delegando la localización física de los componentes al **Discovery Server**, lo cual permite un despliegue dinámico y escalable. La lógica de negocio se fragmenta en contenedores independientes —tales como IAM, Groups, Tasks, Requests, Metrics, Cloudinary, Email y AI Service—, algunos con persistencia de datos propia, garantizando un aislamiento óptimo. La comunicación síncrona mediante **REST/HTTPS** asegura una respuesta inmediata en operaciones críticas, mientras que la integración asíncrona a través del **Broker (RabbitMQ)** mediante el protocolo **AMQP** permite gestionar eventos de forma eficiente, desacoplando los servicios y fortaleciendo la resiliencia del sistema ante posibles fallos. Finalmente, la externalización de servicios complejos como **Gemini** para procesamiento de lenguaje, **Cloudinary** para gestión multimedia y **SendGrid** para notificaciones, consolida a SynHub como una plataforma moderna que aprovecha un ecosistema de servicios especializados para optimizar la experiencia de gestión de tareas.

[![Container.png](https://i.postimg.cc/8kLsxds6/Container.png)](https://postimg.cc/8sP166Rp)

Parte del usuario:

[![Container-P1.png](https://i.postimg.cc/HntYn27R/Container-P1.png)](https://postimg.cc/N25qPRDk)

Parte de microservicios principales:

[![Container-P2.png](https://i.postimg.cc/0N7L9NSQ/Container-P2.png)](https://postimg.cc/WDb9nTXL)

Parte de servicios externos:

[![Container-P3.png](https://i.postimg.cc/8PqKsSNn/Container-P3.png)](https://postimg.cc/Ln3B0Gqz)

### 4.3.4. Software Architecture Deployment Diagrams

El diagrama de despliegue, integrado en el nivel más físico del modelo C4 y en el estándar UML, es la representación técnica de la arquitectura de sistema sobre su infraestructura de ejecución. Su propósito fundamental es describir cómo los componentes de software (artefactos) se asignan, configuran y distribuyen en los nodos de hardware o entornos virtuales (como servidores, contenedores o servicios en la nube).

Este diagrama detalla la topología de la red, las dependencias entre los componentes de software y su ubicación física o lógica, permitiendo comprender la escalabilidad, la disponibilidad y la resiliencia del sistema en el entorno de producción. En esencia, actúa como el puente definitivo entre el diseño lógico del software y la realidad operativa, ilustrando el despliegue físico de los servicios, bases de datos y herramientas de soporte que conforman la solución.

[![Deployment.png](https://i.postimg.cc/nrtVHL0K/Deployment.png)](https://postimg.cc/1nJ1Byx4)

Parte de interacción de usuarios:

[![Deployment-P1.png](https://i.postimg.cc/sXCCWNSw/Deployment-P1.png)](https://postimg.cc/ns2WbT3D)

Parte de microservicios:

[![Deployment-P2.png](https://i.postimg.cc/3R1fwSZ6/Deployment-P2.png)](https://postimg.cc/ygJyQTtX)