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



### 2.3.2. User Task Matrix



### 2.3.3. Empathy Mapping



### 2.3.4. As-is Scenario Mapping



## 2.4. Ubiquitous Language



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


