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



### 2.1.1. Análisis competitivo



### 2.1.2. Estrategias y tácticas frente a competidores



## 2.2. Entrevistas



### 2.2.1. Diseño de entrevistas



### 2.2.2. Registro de entrevistas



### 2.2.3. Análisis de entrevistas



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


