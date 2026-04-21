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
| 1.0 | 2026-04-21 | Miguel Gomez <br> Diego Acuña <br> Jhon Guerrero <br> Max Paitan <br> Josue Paiva | - Capítulo 1 <br> - Capítulo 2 <br> - Capítulo 3 <br> - Capítulo 4 |

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

# 1. Capítulo I: Introducción



## 1.1. Startup Profile



### 1.1.1. Descripción de la Startup



### 1.1.2. Perfiles de integrantes del equipo



## 1.2. Solution Profile



### 1.2.1. Antecedentes y problemática



### 1.2.2. Lean UX Process



#### 1.2.2.1. Lean UX Problem Statements



#### 1.2.2.2. Lean UX Assumptions



#### 1.2.2.3. Lean UX Hypothesis Statements



#### 1.2.2.4. Lean UX Canvas



## 1.3. Segmentos objetivo



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

### 2.2.3. Análisis de entrevistas

En esta sección se recopilan y resumen las ideas y hallazgos más relevantes obtenidos de las entrevistas realizadas tanto a coordinadores como a miembros de grupo. La información completa, incluidas las grabaciones de cada entrevista, está disponible en el siguiente enlace:

URL:

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



### 4.1.2. Attribute-Driven Design Inputs



#### 4.1.2.1. Primary Functionality (Primary User Stories)



#### 4.1.2.2. Quality attribute Scenarios



#### 4.1.2.3. Constraints



### 4.1.3. Architectural Drivers Backlog



### 4.1.4. Architectural Design Decisions



### 4.1.5. Quality Attribute Scenario Refinements



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
| Analítica y Reportes      | Gestión de Grupos          | Customer/Supplier | No     | Expone info grupal                                                      |
| Solicitudes y Validaciones | Gestión de Grupos          | Customer/Supplier | Si     | Se nutre de los datos de los integrantres                               |
| Gestión de Tareas         | Gestión de Grupos          | Customer/Supplier | No     | Obtiene información de los integrantes de grupo                        |
| Gestión de Tareas         | Solicitudes y Validaciones  | Partnership       | No     | Comparte información entre sí de las tareas                           |
| Analítica y Reportes      | Gestión de Tareas          | Customer/Supplier | Si     | Se nutre de la información de las tareas para elaborar reportes        |
| Analítica y Reportes      | Solicitudes y Validaciones  | Customer/Supplier | No     | Otiene la infomración de actualización de cmabios y solicitudes       |
| Notificaciones             | Grupos, solicitudes, tareas | Partnership       | No     | Emite notificaciones según instrucciones de los demás bounded context |

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