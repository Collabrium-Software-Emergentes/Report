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
| Guerrero Vasquez, Jhon Danny      |            |
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

<img src="https://i.postimg.cc/0jHsLYyQ/familywall.png" alt="FamilyWall" width="200"/>

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
    <td style="text-align: center;"> <div>SynHub</div> <img src="./images/chapter-2/synhub.png" alt="SynHub" width="200"/> </td>
    <td style="text-align: center;"> <div>Asana</div> <img src="https://avatars.slack-edge.com/2024-09-05/7707480927360_791cc0c5cdf5b6720b21_512.png" alt="Asana" width="200"/> </td>
    <td style="text-align: center;"> <div>FamilyWall</div> <img src="https://i.postimg.cc/0jHsLYyQ/familywall.png" alt="Picniic" width="200"/> </td>
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


