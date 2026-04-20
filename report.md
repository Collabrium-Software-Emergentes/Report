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


