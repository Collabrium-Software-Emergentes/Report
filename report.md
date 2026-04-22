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
        Hice esto
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
        Hice esto
        <br><br>
        <strong>Paitan Pumacahua, Max Anthony</strong>
        <br> <em>TB1</em> <br>
        Realicé la primera parte del capítulo 2, el análisis de competidores, las preguntas de las entrevistas. Además, colaboré en la realización del Architectural Design Decisions, Quality Attribute Scenario Refinements, Architectural Drivers Backlog y los Constraints.
        <br><br>
        <strong>Acuña Tomas, Diego Rolin</strong>
        <br> <em>TB1</em> <br>
        Hice esto
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


