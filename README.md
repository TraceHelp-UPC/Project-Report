<div align="center">

![UPC Logo](assets/images/upc_logo_caratula.png)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

**1ASI0728 Arquitecturas de Software Emergentes**
**202520**

NRC: **9046**

Profesor: **Royer Edelwer Rojas Malásquez**

**Informe del Trabajo Final (TB1)**

Nombre del Producto: **TraceHelp**

</div>

**Integrantes:**

| Apellidos y Nombres | Código |
| :--- | :--- |
| Borja Molina, Gabriel Sebastián | u202310308 |
| Chávez Uribe, Ario Joel | u202213468 |
| Binda Arbañil, Marcelo Alejandro | u202311157 |
| Martel Andrade, Cassius Estefano | u202312287 |

<div align="center">

**Septiembre de 2026**

</div>

---

## Registro de Versiones

| Versión | Fecha | Autor(es) | Descripción de la Modificación |
| :---: | :---: | :--- | :--- |
| **1.0 (TB1)** | 02/09/2026 | Cassius Martel<br>Gabriel Borja<br>Marcelo Binda<br>Ario Chavez | Entrega TB1 completa:<br>• Capítulo I: Introducción<br>• Capítulo II: Requirements Elicitation & Analysis<br>• Capítulo III: Requirements Specification<br>• Capítulo IV: Strategic-Level Software Design |

---

## Project Report Collaboration Insights

El presente informe ha sido desarrollado colaborativamente mediante un flujo estructurado de control de versiones en GitHub:
* **Repositorio Oficial:** [https://github.com/TraceHelp-UPC/Project-Report](https://github.com/TraceHelp-UPC/Project-Report)
* **Gestión de Cambios:** Cada capítulo y sección del documento técnico fue versionado y revisado de forma iterativa, asegurando trazabilidad formal, gobernanza del contenido y apego a las convenciones de ingeniería de software.

---

## Student Outcome ABET

El curso contribuye al cumplimiento del **Student Outcome ABET: ABET – EAC - Student Outcome 3**:

> **Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias. En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio Específico | Acciones Realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.** | • **Binda Arbañil, Marcelo Alejandro (TB1):** Expuso los fundamentos de las decisiones de diseño arquitectónico en las sesiones del Quality Attribute Workshop (QAW), argumentando objetivamente la elección de patrones y tácticas frente a sus compañeros.<br><br>• **Borja Molina, Gabriel Sebastián (TB1):** Explicó verbalmente los flujos de dominio mediante la técnica de Domain Storytelling, guiando al equipo en la comprensión secuencial de las interacciones entre los contextos delimitados.<br><br>• **Chavez Uribe, Ario Joel (TB1):** Condujo las entrevistas semiestructuradas, adaptando su tono y vocabulario para interactuar efectivamente tanto con perfiles ejecutivos como con personal operativo.<br><br>• **Martel Andrade, Cassius Estefano (TB1):** Sustentó oralmente la viabilidad de la arquitectura RAG frente al equipo, traduciendo conceptos técnicos complejos de IA generativa a beneficios claros de negocio durante la definición del Lean UX Canvas. | **TB1:** Durante esta primera etapa del proyecto, el equipo demostró capacidad para adaptar su discurso oral a distintas audiencias. A través de la conducción de entrevistas reales con Líderes de TI y Analistas de Soporte, así como en las sesiones grupales de EventStorming y QAW, logramos comunicar de manera asertiva y clara las problemáticas del negocio y las soluciones arquitectónicas, facilitando el entendimiento mutuo entre los requerimientos técnicos y las necesidades operativas de los usuarios. |
| **Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.** | • **Binda Arbañil, Marcelo Alejandro (TB1):** Escribió la especificación formal del proceso ADD, redactando los escenarios de atributos de calidad y los constraints técnicos con métricas objetivas y lenguaje propio de arquitectura de software.<br><br>• **Borja Molina, Gabriel Sebastián (TB1):** Elaboró la documentación escrita correspondiente al diseño de dominio (DDD), especificando con claridad las responsabilidades, lenguaje ubicuo y flujos de mensajes en los Bounded Context Canvases.<br><br>• **Chavez Uribe, Ario Joel (TB1):** Documentó el análisis de competidores y el registro de entrevistas, sintetizando datos cualitativos en hallazgos estadísticos precisos para la redacción de las fichas de User Personas y matrices de tareas.<br><br>• **Martel Andrade, Cassius Estefano (TB1):** Redactó las User Stories y Technical Stories en formato Gherkin, asegurando que los requerimientos fuesen comprensibles tanto para stakeholders de negocio como para futuros desarrolladores de la plataforma. | **TB1:** El equipo logró consolidar una comunicación escrita profesional y estructurada, fundamental para el desarrollo de software corporativo. La elaboración de artefactos formales como los Bounded Context Canvases, los escenarios de atributos de calidad (QAS) y el análisis competitivo evidencia la capacidad de documentar decisiones de ingeniería complejas con un nivel de objetividad y detalle que resulta fácilmente interpretable para directores de proyecto, arquitectos de software y auditores externos. |

---

## Tabla de Contenidos

1. [**Capítulo I: Introducción**](01-chap1-introduction.md)
   * 1.1. [Startup Profile](01-chap1-introduction.md#11-startup-profile)
     * 1.1.1. [Descripción de la Startup](01-chap1-introduction.md#111-descripción-de-la-startup)
     * 1.1.2. [Perfiles de integrantes del grupo](01-chap1-introduction.md#112-perfiles-de-integrantes-del-grupo)
   * 1.2. [Solution Profile](01-chap1-introduction.md#12-solution-profile)
     * 1.2.1. [Antecedentes y problemática](01-chap1-introduction.md#121-antecedentes-y-problemática)
     * 1.2.2. [Lean UX Process](01-chap1-introduction.md#122-lean-ux-process)
   * 1.3. [Segmentos Objetivo](01-chap1-introduction.md#13-segmentos-objetivo)

2. [**Capítulo II: Requirements Elicitation & Analysis**](02-chap2-requirements-elicitation-and-analysis.md)
   * 2.1. [Competidores](02-chap2-requirements-elicitation-and-analysis.md#21-competidores)
     * 2.1.1. [Análisis competitivo](02-chap2-requirements-elicitation-and-analysis.md#211-análisis-competitivo)
     * 2.1.2. [Estrategias y tácticas frente a competidores](02-chap2-requirements-elicitation-and-analysis.md#212-estrategias-y-tácticas-frente-a-competidores)
   * 2.2. [Entrevistas](02-chap2-requirements-elicitation-and-analysis.md#22-entrevistas)
     * 2.2.1. [Diseño de entrevistas](02-chap2-requirements-elicitation-and-analysis.md#221-diseño-de-entrevistas)
     * 2.2.2. [Registro de entrevistas](02-chap2-requirements-elicitation-and-analysis.md#222-registro-de-entrevistas)
     * 2.2.3. [Análisis de entrevistas](02-chap2-requirements-elicitation-and-analysis.md#223-análisis-de-entrevistas)
   * 2.3. [Needfinding](02-chap2-requirements-elicitation-and-analysis.md#23-needfinding)
     * 2.3.1. [User Personas](02-chap2-requirements-elicitation-and-analysis.md#231-user-personas)
     * 2.3.2. [User Task Matrix](02-chap2-requirements-elicitation-and-analysis.md#232-user-task-matrix)
     * 2.3.3. [Empathy Mapping](02-chap2-requirements-elicitation-and-analysis.md#233-empathy-mapping)
     * 2.3.4. [As-is Scenario Mapping](02-chap2-requirements-elicitation-and-analysis.md#234-as-is-scenario-mapping)
   * 2.4. [Ubiquitous Language](02-chap2-requirements-elicitation-and-analysis.md#24-ubiquitous-language)

3. [**Capítulo III: Requirements Specification**](03-chap3-requirements-specification.md)
   * 3.1. [To-Be Scenario Mapping](03-chap3-requirements-specification.md#31-to-be-scenario-mapping)
   * 3.2. [User Stories](03-chap3-requirements-specification.md#32-user-stories)
   * 3.3. [Impact Mapping](03-chap3-requirements-specification.md#33-impact-mapping)
   * 3.4. [Product Backlog](03-chap3-requirements-specification.md#34-product-backlog)

4. [**Capítulo IV: Strategic-Level Software Design**](04-chap4-strategic-level-software-design.md)
   * 4.1. [Strategic-Level Attribute-Driven Design](04-chap4-strategic-level-software-design.md#41-strategic-level-attribute-driven-design)
     * 4.1.1. [Design Purpose](04-chap4-strategic-level-software-design.md#411-design-purpose)
     * 4.1.2. [Attribute-Driven Design Inputs](04-chap4-strategic-level-software-design.md#412-attribute-driven-design-inputs)
     * 4.1.3. [Architectural Drivers Backlog](04-chap4-strategic-level-software-design.md#413-architectural-drivers-backlog)
     * 4.1.4. [Architectural Design Decisions](04-chap4-strategic-level-software-design.md#414-architectural-design-decisions)
     * 4.1.5. [Quality Attribute Scenario Refinement](04-chap4-strategic-level-software-design.md#415-quality-attribute-scenario-refinement)
   * 4.2. [Strategic-Level Domain-Driven Design](04-chap4-strategic-level-software-design.md#42-strategic-level-domain-driven-design)
     * 4.2.1. [EventStorming](04-chap4-strategic-level-software-design.md#421-eventstorming)
     * 4.2.2. [Candidate Context Discovery](04-chap4-strategic-level-software-design.md#422-candidate-context-discovery)
     * 4.2.3. [Domain Message Flows Modelling](04-chap4-strategic-level-software-design.md#423-domain-message-flows-modelling)
     * 4.2.4. [Bounded Context Canvases](04-chap4-strategic-level-software-design.md#424-bounded-context-canvases)
     * 4.2.5. [Context Mapping](04-chap4-strategic-level-software-design.md#425-context-mapping)
   * 4.3. [Software Architecture](04-chap4-strategic-level-software-design.md#43-software-architecture)
     * 4.3.1. [Software Architecture System Landscape](04-chap4-strategic-level-software-design.md#431-software-architecture-system-landscape)
     * 4.3.2. [Software Architecture Context Level Diagrams](04-chap4-strategic-level-software-design.md#432-software-architecture-context-level-diagrams)
     * 4.3.3. [Software Architecture Container Level Diagrams](04-chap4-strategic-level-software-design.md#433-software-architecture-container-level-diagrams)
     * 4.3.4. [Software Architecture Deployment Diagrams](04-chap4-strategic-level-software-design.md#434-software-architecture-deployment-diagrams)

* [**Conclusiones**](conclusions.md)
* [**Bibliografía**](bibliography.md)
