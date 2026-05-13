<p align="center">
  <img src="https://i.imgur.com/frPdUOx.png" alt="logo" width=100px>
</p>

<p align="center"><b>Universidad Peruana de Ciencias Aplicadas</b></p>
<p align="center"><b>Facultad de Ingenieria</b></p>
<br>

<p align="center">Curso: 1ASI0572 - Desarrollo y Soluciones IOT</p>
<p align="center"><b>NRC:</b> 6785</p>
<br>
<p align="center"><b>Nombre del profesor:</b> Marco Antonio León Baca</p>

### <p align="center"><b>"Informe del Trabajo Final"</b></p>
<br>
<p align="center"><b>Nombre del grupo:</b> Nexora</p>
<p align="center"><b>Nombre del producto:</b> NexBell</p>
<br>

<p align="center">Integrantes:</p>

<table align="center"; style="width: 100%; border-collapse: collapse; margin: 0 auto;">
  <tr>
    <th style="border: 1px solid black; padding: 8px; text-align: center;">Código</th>
    <th style="border: 1px solid black; padding: 8px; text-align: center;">Nombre</th>

  </tr>
  </tr>
    <tr>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">U202310931</td>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">Bellido Salas, Raúl</td>
    
  </tr>
  <tr>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">U202310308</td>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">Borja Molina, Gabriel Sebastián</td>
  </tr>
  </tr>
    <tr>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">U202311532</td>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">Suárez Romero, Santiago Manuel</td>

  </tr>  
  <tr>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">U202311184</td>  
    <td style="border: 1px solid black; padding: 8px; text-align: center;">Gómez Flores, Daniela Araceli</td>
  </tr>
    <tr>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">U202118264</td>
    <td style="border: 1px solid black; padding: 8px; text-align: center;">Burga Loarte, Anaely Zarely</td>
  </tr>
</table>

<br>
<hr>

<div style="page-break-after: always;"></div>

# <p align="center">Registro de Versiones del Informe</p>

| Versión | Fecha | Autor | Descripción de modificación |
| :---- | :---- | :---- | :---- |
| AV1 | 24/04/2026 | **· Bellido Salas Raúl <br> · Borja Molina, Gabriel Sebastián <br> · Suárez Romero, Santiago Manuel  <br> · Gomez Flores, Daniela Araceli <br> · Burga Loarte, Anaely Zarely** | En la primera entrega del informe de nuestro proyecto, se han desarrollado los cuatro primeros capítulos, los cuales abarcan la definición de la startup, el planteamiento del problema y la propuesta de solución. Asimismo, se incluye el análisis de los segmentos objetivo, la aplicación del proceso Lean UX y la validación inicial mediante entrevistas y análisis competitivo. Estos elementos permiten establecer una base sólida para el desarrollo del proyecto, alineando la problemática identificada con una solución tecnológica viable y centrada en las necesidades de los usuarios. |
| TP1 | 13/05/2026 | **· Bellido Salas Raúl <br> · Borja Molina, Gabriel Sebastián <br> · Suárez Romero, Santiago Manuel  <br> · Gomez Flores, Daniela Araceli <br> · Burga Loarte, Anaely Zarely**| En esta entrega articulamos el diseño UX/UI y la ingeniería de software de NexBell mediante el desarrollo de los Capítulos V y VI. En un solo bloque, documentamos las guías de estilo bajo el enfoque Vigilant Elegance (General, Web, Mobile e IoT), la arquitectura de información en sus cinco sistemas clave y la interacción visual de la Landing Page y la aplicación móvil para el Edificio San Martín mediante el desglose de Wireframes, Wireflows, Mock-ups, User Flows, el prototipo en Figma y el diseño del hardware (IoT Device Design). Asimismo, consolidamos la infraestructura técnica mediante la gestión de configuración de software (SCM), detallando el entorno de desarrollo, el control de versiones en GitHub con GitFlow, las convenciones de código y el despliegue continuo en la nube, culminando con la documentación completa del Sprint 1 que integra desde el backlog inicial hasta las evidencias de desarrollo, suite de pruebas, APIs, puesta en producción y la retrospectiva colaborativa del equipo|

<hr>

<div style="page-break-after: always;"></div>

# Project Report Collaboration Insights

Elaboramos el informe de nuestro proyecto en un repositorio llamado “ProjectReport” en nuestra organización llamada “Nexora” porque ahí desarrollaremos el producto de nuestra startup.  
Enlace del repositorio “ProjectReport”: [https://github.com/Nexora-solution/NexBell-ProjectReport.git](https://github.com/Nexora-solution/NexBell-ProjectReport.git)   

<ins>**AV1:**</ins>  
Para poder lograr la elaboración grupal de este informe del proyecto, creamos primero un documento en google y posteriormente agregamos las partes en GitHub en formato markdown. A continuación, se mostrará una imagen de los insights de los commits realizados por cada miembro en dicho repositorio.  
**Figura 1**  
*Insights de ProjectReports*  
<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1777073710/WhatsApp_Image_2026-04-24_at_6.33.33_PM_fw4cbs.jpg" alt="PI5" width="1000">
</p> 

<div style="page-break-after: always;"></div>

# Tabla de Contenidos
  - [Student Outcome](#student-outcome)
  - [Capítulo I: Introducción](#capítulo-i-introducción)
      * [1.1. Startup Profile](#11-startup-profile)
          * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
          * [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
      * [1.2. Solution Profile](#12-solution-profile)
          * [1.2.1. Nombre del producto](#121-nombre-del-producto)
          * [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
          * [1.2.3. Lean UX Process](#123-lean-ux-process)
              * [1.2.3.1. Lean UX Problem Statements](#1231-lean-ux-problem-statements)
              * [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
              * [1.2.3.3. Lean UX Hypothesis Statements](#1233-lean-ux-hypothesis-statements)
              * [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
      * [1.3. Segmentos objetivo](#13-segmentos-objetivo)
  - [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
      * [2.1. Competidores](#21-competidores)
          * [2.1.1. Análisis competitivo](#211-an%C3%A1lisis-competitivo)
          * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-t%C3%A1cticas-frente-a-competidores)
      * [2.2. Entrevistas](#22-entrevistas)
          * [2.2.1. Diseño de entrevistas](#221-dise%C3%B1o-de-entrevistas)
          * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
          * [2.2.3. Análisis de entrevistas](#223-an%C3%A1lisis-de-entrevistas)
      * [2.3. Needfinding](#23-needfinding)
          * [2.3.1. User Personas](#231-user-personas)
          * [2.3.2. User Task Matrix](#232-user-task-matrix)
          * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
          * [2.3.4. Empathy Mapping](#234-empathy-mapping)
      * [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
      * [2.5. Ubiquitous Language](#25-ubiquitous-language)
  - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
      * [3.1. User Stories](#31-user-stories)
      * [3.2. Impact Mapping](#32-impact-mapping)
      * [3.3. Product Backlog](#33-product-backlog)
  - [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
      * [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
          * [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
          * [Paso 1: Identificación de Eventos de Dominio (Domain Events)](#paso-1-identificación-de-eventos-de-dominio-domain-events)
          * [Paso 2: Definición de Líneas de Tiempo (Timelines)](#paso-2-definición-de-líneas-de-tiempo-timelines)
          * [Paso 3: Identificación de Comandos (Commands)](#paso-3-identificación-de-comandos-commands)
          * [Paso 4: Sistemas Externos (External Systems)](#paso-4-sistemas-externos-external-systems)
          * [Paso 5: Actores y Políticas (Actors & Policies)](#paso-5-actores-y-políticas-actors--policies)
          * [Paso 6: Puntos de Dolor (Pain Points)](#paso-6-puntos-de-dolor-pain-points)
          * [Paso 7: Modelos de Lectura (Read Models)](#paso-7-modelos-de-lectura-read-models)
          * [Paso 8: Puntos Pivotales (Pivotal Points)](#paso-8-puntos-pivotales-pivotal-points)
              * [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
            * [Contexto Candidato 1: Identity and Access Management (IAM)](#contexto-candidato-1-identity-and-access-management-iam)
            * [Contexto Candidato 2: Security (Core Domain)](#contexto-candidato-2-security-core-domain)
            * [Contexto Candidato 3: Audit](#contexto-candidato-3-audit)
            * [Contexto Candidato 4: Intercom](#contexto-candidato-4-intercom)
            * [Contexto Candidato 5: Directory](#contexto-candidato-5-directory)
              * [4.1.1.2. Domain Message Flows Modelling](#4112-domain-message-flows-modelling)
            * [Escenario 1: Creación de cuentas de edificio inicial](#escenario-1-creación-de-cuentas-de-edificio-inicial)
            * [Escenario 2: Registro de visita pendiente por residente](#escenario-2-registro-de-visita-pendiente-por-residente)
            * [Escenario 3: Gestión de visita automática del sistema](#escenario-3-gestión-de-visita-automática-del-sistema)
            * [Escenario 4: Aprobación de visita por conserje](#escenario-4-aprobación-de-visita-por-conserje)
            * [Escenario 5: Aprobación de visita por residente](#escenario-5-aprobación-de-visita-por-residente)
              * [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
            * [1. Bounded Context: Identity and Access Management (IAM)](#1-bounded-context-identity-and-access-management-iam)
            * [2. Bounded Context: Security (Core Domain)](#2-bounded-context-security-core-domain)
            * [3. Bounded Context: Audit](#3-bounded-context-audit)
            * [4. Bounded Context: Intercom](#4-bounded-context-intercom)
            * [5. Bounded Context: Directory](#5-bounded-context-directory)
          * [4.1.2. Context Mapping](#412-context-mapping)
          * [Tabla de Relaciones de Contexto](#tabla-de-relaciones-de-contexto)
          * [Decisiones, Supuestos, Riesgos y Mitigaciones](#decisiones-supuestos-riesgos-y-mitigaciones)
            * [1. Decisiones y Supuestos](#1-decisiones-y-supuestos)
            * [2. Riesgos y Mitigaciones](#2-riesgos-y-mitigaciones)
          * [4.1.3. Software Architecture](#413-software-architecture)
              * [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
              * [4.1.3.2. Software Architecture Context Level Diagram](#4132-software-architecture-context-level-diagram)
              * [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
      * [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
        * [4.2.1. Bounded Context: IAM (Identity & Access Management)](#421-bounded-context-iam-identity--access-management)
            * [4.2.1.1. Domain Layer](#4211-domain-layer)
            * [4.2.1.2. Interface Layer](#4212-interface-layer)
            * [4.2.1.3. Application Layer](#4213-application-layer)
            * [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
          * [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams)
          * [4.2.5.6. Bounded Context Software Architecture Container Level Diagrams](#4256-bounded-context-software-architecture-container-level-diagrams)
            * [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams)
            * [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram)
        * [4.2.2. Bounded Context: Security](#422-bounded-context-security)
          * [4.2.2.1. Domain Layer](#4221-domain-layer)
          * [4.2.2.2. Interface Layer](#4222-interface-layer)
          * [4.2.2.3. Application Layer](#4223-application-layer)
          * [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
          * [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams-1)
          * [4.2.5.6. Bounded Context Software Architecture Container Level Diagrams](#4256-bounded-context-software-architecture-container-level-diagrams-1)
            * [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams-1)
            * [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram-1)
        * [4.2.3. Bounded Context: Directory](#423-bounded-context-directory)
          * [4.2.3.1. Domain Layer](#4231-domain-layer)
          * [4.2.3.2. Interface Layer](#4232-interface-layer)
          * [4.2.3.3. Application Layer](#4233-application-layer)
          * [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
          * [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams-2)
          * [4.2.5.6. Bounded Context Software Architecture Container Level Diagrams](#4256-bounded-context-software-architecture-container-level-diagrams-2)
            * [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams-2)
            * [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram-2)
        * [4.2.4. Bounded Context: Intercom & Notifications](#424-bounded-context-intercom--notifications)
          * [4.2.4.1. Domain Layer](#4241-domain-layer)
          * [4.2.4.2. Interface Layer](#4242-interface-layer)
          * [4.2.4.3. Application Layer](#4243-application-layer)
          * [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
          * [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams-3)
          * [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams)
            * [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams-3)
            * [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram-3)
        * [4.2.5. Bounded Context: Audit](#425-bounded-context-audit)
          * [4.2.5.1. Domain Layer](#4251-domain-layer)
          * [4.2.5.2. Interface Layer](#4252-interface-layer)
          * [4.2.5.3. Application Layer](#4253-application-layer)
          * [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
          * [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams-4)
          * [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams-1)
            * [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams-4)
            * [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram-4)
  - [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
      * [5.1 Style Guidelines](#51-style-guidelines)
          * [5.1.1 General Style Guidelines](#511-general-style-guidelines)
          * [5.1.2 Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
      * [5.2 Information Architecture](#52-information-architecture)
          * [5.2.1 Organization Systems](#521-organization-systems)
          * [5.2.2 Labelling Systems](#522-labelling-systems)
          * [5.2.3 SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
          * [5.2.4 Searching Systems](#524-searching-systems)
          * [5.2.5 Navigation Systems](#525-navigation-systems)
      * [5.3 Landing Page UI Design](#53-landing-page-ui-design)
          * [5.3.1 Landing Page Wireframe](#531-landing-page-wireframe)
          * [5.3.2 Landing Page Mock-up](#532-landing-page-mock-up)
      * [5.4 Applications UX/UI Design](#54-applications-uxui-design)
          * [5.4.1 Applications Wireframes](#541-applications-wireframes)
          * [5.4.2 Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
          * [5.4.2 Applications Mock-ups](#542-applications-mock-ups)
          * [5.4.3 Applications User Flow Diagrams](#543-applications-user-flow-diagrams)
      * [5.5 Applications Prototyping](#55-applications-prototyping)
      * [5.6 IoT Device Design](#56-iot-device-design)
  - [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
      * [6.1 Software Configuration Management](#61-software-configuration-management)
          * [6.1.1 Software Development Environment Configuration](#611-software-development-environment-configuration)
          * [6.1.2 Source Code Management](#612-source-code-management)
          * [6.1.3 Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
          * [6.1.4 Software Deployment Configuration](#614-software-deployment-configuration)
      * [6.2 Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
          * [6.2.1 Sprint 1](#621-sprint-1)
              * [6.2.1.1 Sprint Planning 1](#6211-sprint-planning-1)
              * [6.2.1.2 Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
              * [6.2.1.3 Sprint Backlog 1](#6213-sprint-backlog-1)
              * [6.2.1.4 Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
              * [6.2.1.5 Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
              * [6.2.1.6 Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
              * [6.2.1.7 Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
              * [6.2.1.8 Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
              * [6.2.1.9 Team Collaboration Insights during Sprint](#6219-team-collaboration-insights-during-sprint)
  - [Conclusiones](#conclusiones)
  - [Bibliografía](#bibliografía)
  - [Anexos](#anexos)

<hr>
<div style="page-break-after: always;"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome **ABET: ABET – EAC - Student Outcome 7: Aprendizaje Continuo y Autónomo** <br>
**Criterio:**  *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos* <br>
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del equipo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome.
| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Bellido Salas, Raúl**<br>• *AV1:* Redacción de historias de usuario, definición de estrategias técnicas y conducción de entrevistas.<br>• *TB1:* Liderazgo en diseño táctico (DDD) para módulos IAM y Security, mapeo de Container Diagrams y modelos de base de datos.<br>• *TP:* Liderazgo técnico en la construcción del backend del Sprint 1, guiando el diseño de las REST APIs y la lógica de persistencia de datos.<br><br>**Borja Molina, Gabriel Sebastián**<br>• *AV1:* Liderazgo en investigación de problemáticas, diseño de Event Storming y Bounded Context Canvas.<br>• *TB1:* Liderazgo técnico en diseño de dispositivo IoT "Clair" en Wokwi, definición de hardware (ESP32) y capas de datos (MQTT/HTTP).<br>• TP: Dirección estratégica de la Gestión de Configuración de Software (SCM) y del flujo de ramificación GitFlow en el repositorio de la entrega parcial.<br><br>**Suárez Romero, Santiago Manuel**<br>• *AV1:* Análisis de antecedentes y liderazgo en la delimitación de Bounded Contexts.<br>• *TB1:* Liderazgo en diseño visual y UX/UI (wireframes/mockups) bajo el concepto "Vigilant Elegance".<br> •TP: Liderazgo en la codificación del frontend responsive de la Landing Page durante el desarrollo del Sprint 1.<br><br>**Gomez Flores, Daniela Araceli**<br> *AV1:* Definición del problema central, coordinación de Needfinding (User Personas/Journey Maps) y Product Backlog.<br>• *TB1:* Liderazgo en Arquitectura de Información, sistemas de navegación, etiquetado y búsqueda.<br>•*TP:*Liderazgo en el control de calidad (QA), coordinando la definición de la suite de pruebas unitarias y de aceptación de las interfaces del software. <br><br>**Burga Loarte, Anaely Zarely**<br>• *AV1:* Liderazgo en diagramas de arquitectura de alto nivel (Landscape/Context/Deployment) y apoyo en historias de usuario.<br>• *TB1:* Diseño UI/UX de Landing Page, configuración SEO/ASO e integración de los 12 pasos de diseño IoT. <br> • *TP:* Liderazgo de diseño en el prototipado e interacciones complejas de la aplicación móvil móvil en Figma y la consistencia técnica de la entrega parcial.| **AV1 - Objetivo:** Establecer una base de liderazgo compartido para avanzar de forma coordinada en la estructuración.<br>**AV1 - Conclusión:** El equipo demostró liderazgo conjunto al distribuir responsabilidades según fortalezas, logrando una propuesta sólida y coherente.<br><br>**TB1 - Objetivo:** Profundizar en el diseño técnico (táctico, IoT y UX/UI) distribuyendo el liderazgo para una evolución consistente.<br>**TB1 - Conclusión:** Se consolidó la visión técnica, logrando que el backend, las interfaces y el hardware IoT empataran de forma fluida y acelerada. <br><br> **TP - Objetivo:** Consolidar el co-liderazgo multi-rol para transformar las especificaciones teóricas de la solución en un incremento de software funcional, integrado y desplegado. <br> **TP - Conclusión:** El liderazgo distribuido permitió avanzar simultáneamente en los frentes de infraestructura, código y diseño físico, garantizando un producto de software robusto que cumple con las métricas de arquitectura esperadas para el hito parcial |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.** | **Bellido Salas, Raúl**<br>• *AV1:* Planificación de tareas y metas. Integración de perspectivas en la toma de decisiones técnicas.<br>• *TB1:* Coordinación de sesiones de revisión de arquitectura para unificar expectativas entre la API y la aplicación móvil.<br> **•TP:** Planificación del Sprint Backlog técnico, gestionando la unificación de los contratos de las APIs con las demandas operativas de la aplicación.<br><br>**Borja Molina, Gabriel Sebastián**<br>• *AV1:* Generación de base de conocimiento común mediante hallazgos de investigación y diagramas compartidos.<br>• *TB1:* Síntesis y comunicación de restricciones técnicas de hardware y esquemas JSON con el equipo de software. <br> •**TP:** Moderación e integración de las ramas de desarrollo individuales en GitHub, asegurando un entorno de código colaborativo y libre de conflictos técnicos.<br><br>**Suárez Romero, Santiago Manuel**<br>• *AV1:* Documentación clara de contextos para reducir ambigüedades y conflictos de criterio.<br>• *TB1:* Ciclos de feedback continuo sobre prototipos visuales, fortaleciendo el compromiso con la calidad final.<br>• **TP:** Establecimiento de metas colaborativas de diseño frontend, garantizando la consistencia visual total entre los estilos web y móviles creados por el equipo.<br><br>**Gomez Flores, Daniela Araceli**<br>• *AV1:* Promoción de entorno inclusivo compartiendo hallazgos de investigación para toma de decisiones informada.<br>• *TB1:* Alineación entre la investigación UX y la arquitectura de información con las historias de usuario aprobadas.<br>• **TP:** Planificación de los criterios de aceptación y las metas de validación del Sprint 1, integrando el flujo de negocio con el código entregado.<br><br>**Burga Loarte, Anaely Zarely**<br>• *AV1:* Creación de referencias visuales comunes (diagramas de arquitectura) para alinear al equipo.<br>• *TB1:* Gestión de la consistencia del reporte final, integrando software, hardware e interfaces en una única voz grupal.<br> •**TP:** Conducción de las sesiones de Sprint Planning y retrospectivas del equipo, estructurando un entorno inclusivo para asegurar la entrega a tiempo de la infraestructura técnica y del informe del TP.| **AV1 - Objetivo:** Construir un entorno de trabajo colaborativo para planificar y cumplir tareas alineadas.<br>**AV1 - Conclusión:** La distribución clara de tareas y la integración de resultados individuales evidenciaron una planificación efectiva y cumplimiento de metas.<br><br>**TB1 - Objetivo:** Integrar eficientemente decisiones de hardware, interfaz y backend mediante comunicación transparente.<br>**TB1 - Conclusión:** La alta interdependencia demandó gran colaboración. La planificación iterativa garantizó que cada avance técnico complementara el entregable final satisfactoriamente. <br><br> **TP - Objetivo:** Gestionar la ejecución colaborativa del Sprint 1 mediante la sincronización ágil de metas de software, control de calidad y despliegue continuo en la nube. <br>**TP - Conclusión:** El establecimiento de revisiones periódicas e integración continua mediante GitFlow habilitó un espacio de trabajo inclusivo y de alta velocidad, logrando el cumplimiento total de los objetivos de desarrollo y despliegue previstos para la entrega parcial.|
<div style="page-break-after: always;"></div>
                                           
# Capítulo I: Introducción 

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nexora es una startup peruana conformada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), orientada al desarrollo de soluciones tecnológicas innovadoras basadas en el Internet de las Cosas (IoT), con el objetivo de mejorar la seguridad y la gestión de accesos en entornos residenciales.

La propuesta de Nexora se enfoca en modernizar la infraestructura tradicional de edificios multifamiliares y condominios, reemplazando sistemas de intercomunicación analógicos por plataformas digitales inteligentes. A través de la integración de dispositivos embebidos, aplicaciones web y sistemas de notificación en tiempo real, se busca optimizar los procesos de validación de visitantes, reducir costos de mantenimiento y aumentar la eficiencia operativa del personal de seguridad.

Asimismo, la startup apuesta por soluciones escalables, accesibles y centradas en el usuario, permitiendo conectar el entorno físico con el entorno digital. De esta manera, Nexora contribuye a la transformación de espacios convencionales en ecosistemas inteligentes, mejorando la experiencia de residentes, administradores y personal de conserjería.

**Misión:**
Desarrollar soluciones tecnológicas innovadoras basadas en Internet de las Cosas (IoT) que optimicen la seguridad y la gestión de accesos en entornos residenciales, brindando productos eficientes, accesibles y fáciles de usar para todos los usuarios involucrados.

**Visión:**
Ser una startup líder en Latinoamérica en el desarrollo de soluciones inteligentes para la seguridad residencial, reconocida por su innovación, confiabilidad y capacidad de transformar digitalmente la gestión de edificios y condominios.

### 1.1.2. Perfiles de los integrantes del equipo

| Raúl Bellido | Ingeniería de Software |
| -- | --|
| <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776792366/raul_lssksc.jpg" height=200px width=350px> | Soy un estudiante de ingeniería de software. Mi nombre es Raúl Bellido y tengo 19 años. Actualmente estudio en la UPC, donde vengo desarrollando mis habilidades en programación utilizando lenguajes como C# y C++. Mi principal enfoque es el desarrollo de aplicaciones móviles que contribuyan al crecimiento y bienestar del Perú, buscando generar un impacto positivo a través de la tecnología. |

| Gabriel Borja | Ingeniería de Software |
| -- | --|
| <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776966554/gabriel_dgnakv.jpg" height=200px width=350px> | Soy un estudiante de la carrera de Ingeniería de Software en la UPC. Enfocado principalmente en el desarrollo web, busco especializarme en la elaboración de soluciones robustas y orientadas al usuario. Cuento con conocimiento de lenguajes como Python, C++ y C#. Me caracterizo por ser una persona creativa, amigable y responsable. Me comprometo a brindar mi apoyo al equipo para desarrollar el proyecto y aprobar el curso de manera satisfactoria. |

| Santiago Suárez | Ingeniería de Software |
| -- | --|
| <img src="https://i.imgur.com/vgOqZYW.jpeg" height=200px width=400px> | Soy de la carrera de ingeniería de software. Mis cualidades son ser creativo, trabajar en grupo, me adapto a diferentes entornos. Además, siempre trato de apoyar con los conocimientos que he aprendido a lo largo de mi vida y siempre trato de aprender algo nuevo. |

| Daniela Gómez | Ingeniería de Software |
| -- | --|
| <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776792340/yo_uzhre7.jpg" height=200px width=400px> | Soy Daniela Gómez Flores, estudiante de Ingeniería de Software en la UPC, actualmente cursando el 7mo ciclo. Me gusta trabajar de manera organizada, aprender cosas nuevas y mantener un buen equilibrio en mis actividades. La música es parte importante de mi día a día y me motiva a seguir creciendo tanto en lo académico como en lo personal.  |

| Anaely Burga | Ingeniería de Software |
| -- | --|
| <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778274678/WhatsApp_Image_2026-05-08_at_15.44.55_p9qvsb.jpg" height=200px width=300px> | Soy estudiante de la carrera de Ingeniería de Software, con interés en el análisis de usuarios y el diseño de soluciones centradas en el usuario. Durante mi formación he desarrollado habilidades lo que me permite comprender mejor las necesidades del usuario y proponer soluciones innovadoras, permitiéndome adaptarme a distintos entornos de desarrollo y seguir aprendiendo continuamente. |

## 1.2. Solution Profile

### 1.2.1. Nombre del producto

NexBell, el producto insignia de nuestra startup, es una solución integral de videoportero inteligente basada en tecnología IoT y una robusta plataforma web, diseñada para transformar la seguridad en edificios residenciales y condominios. Este sistema redefine la gestión de accesos al eliminar por completo la necesidad de cableado interno tradicional, lo que se traduce en una reducción drástica de los costos de instalación y mantenimiento para las juntas de propietarios.

La propuesta de valor de NexBell se centra en empoderar al personal de seguridad y conserjería, permitiéndoles validar visitas mediante video en tiempo real y enrutar las alertas de acceso directamente a los smartphones de los residentes a través de notificaciones móviles. Al integrar un registro digital detallado de cada ingreso, NexBell no solo agiliza la comunicación, sino que eleva los estándares de seguridad y moderniza la experiencia de vivir en comunidad mediante una gestión digitalizada, eficiente y escalable.

### 1.2.2. Antecedentes y problemática

Los edificios multifamiliares y condominios en Lima suelen depender de sistemas de intercomunicadores cableados tradicionales. Estos sistemas presentan múltiples puntos de falla como cables rotos en las paredes, teléfonos malogrados en los departamentos, su mantenimiento es altamente costoso para la junta de propietarios, y no ofrecen registro visual de quién ingresa al edificio. El problema central es la ineficiencia y vulnerabilidad en el control de accesos de edificios residenciales, causada por infraestructura analógica obsoleta que impide al personal de seguridad tener herramientas modernas de validación visual, registro auditable y comunicación asíncrona con los residentes.

Como parte del proceso de definición de la problemática, se aplicó la técnica The 5 W’s and 2 H’s (Who, What, Where, When, Why, How, How Much), permitiendo estructurar de manera preliminar la descripción de los antecedentes y el planteamiento del problema. 

### ***Who:***
* **¿Quiénes están involucrados?**
El proyecto involucra a un ecosistema de cuatro actores clave: la Startup (NexBell) como proveedora de la tecnología, la Administración del Inmueble/Junta de Propietarios como tomadores de decisión financiera, el Personal de Seguridad como operadores directos del sistema en recepción; y los Residentes, quienes son los usuarios finales que reciben las notificaciones y validan los accesos.

* **¿A quiénes les sucede el problema?**
El problema impacta principalmente a dos grupos:
    - **A la Junta de Propietarios y Administradores:** Quienes enfrentan la carga económica de reparaciones constantes y la frustración de gestionar un sistema que no ofrece garantías de seguridad reales ni registros de auditoría.
    - **A los Residentes:** Quienes sufren la falta de comunicación cuando no están en casa y la vulnerabilidad de vivir en un edificio con controles de acceso fácilmente burlables o inoperativos.

* **¿Quién lo utilizará?**
La plataforma NexBell tiene dos perfiles de usuario principales según los segmentos objetivo:
    * **Personal de seguridad o conserjería:** Utilizarán la interfaz de la plataforma web y el hardware IoT para iniciar llamadas de video, registrar visitas y monitorear el estado de los accesos en tiempo real.
    * **Residentes:** Utilizarán la aplicación móvil en sus smartphones para recibir alertas, visualizar quién está en la puerta y autorizar el ingreso de manera remota y asíncrona.

### ***What:***
* **Descripción del producto**
NexBell es una plataforma integral de seguridad e intercomunicación inteligente basada en IoT y entorno web. Su función principal es reemplazar la infraestructura de citofonía análoga por un sistema de videoportero digital que permite la validación de visitas mediante video en tiempo real, gestión de alertas en dispositivos móviles y almacenamiento en la nube de registros de acceso, eliminando la dependencia de cableado físico complejo.

* **¿Cuál es el problema?**
La problemática central es la obsolescencia tecnológica y la ineficiencia operativa de los sistemas de control de acceso en edificios de Lima. Actualmente, la infraestructura analógica genera altos costos de mantenimiento por fallas físicas (cables y terminales), vulnerabilidad ante ingresos no autorizados por falta de registro visual y una comunicación deficiente entre el personal de seguridad y los residentes, quienes no siempre se encuentran físicamente en su unidad para autorizar ingresos. Bajo este escenario, la falta de modernización tecnológica eleva el riesgo de incidentes delictivos que, según cifras de APESEG (2024), ya afectan anualmente a 1 de cada 10 viviendas en zonas urbanas, agravándose en edificios con sistemas vulnerables y prácticamente obsoletos.
    - **Alcance típico (edificio de ~20 departamentos):**
    0.5–1.2 km de cableado interno y 20–30 puntos de terminación.
    - **Frecuencia de fallos:**
    Los sistemas analógicos empiezan a mostrar fallos comunes cada 5–8 años en condiciones urbanas, debido a múltiples causas: como el desgaste de componentes eléctricos, picos de voltaje o conexiones defectuosas (Seisa, 2025).
    En entornos de alta humedad, como en las ciudades peruanas (Consultoría & Servicios en Hidrocarburos y Minería S.A.C., 2019), las incidencias pueden llegar a duplicarse.
    - **Impacto operativo:**
    Cada evento de falla suele implicar 48–72 horas de indisponibilidad (diagnóstico, acceso por obra civil y reparación), con afectación directa a la gestión de visitas y la percepción de seguridad.

* **¿Cuál es la relación con la persona en cuestión?**
La relación se establece mediante una interacción tripartita: para el Personal de Seguridad, NexBell es la herramienta de validación y control operativo; para los Residentes, es el medio de comunicación asíncrona y supervisión desde sus smartphones; y para la Junta de Propietarios, representa una solución de optimización de costos y valorización del patrimonio inmobiliario a través de la digitalización.

### ***Where:***
* **Localización del sistema**
El sistema tiene una presencia dual. Físicamente, se ubica en los puntos de control y acceso (porterías, recepciones y puertas peatonales/vehiculares) de edificios residenciales y condominios multifamiliares. Digitalmente, la solución reside en la nube (plataforma web) y se extiende a los dispositivos móviles de los usuarios, permitiendo una cobertura total del perímetro del inmueble.

* **¿Dónde está el usuario cuando utiliza el producto?**
NexBell rompe la barrera de la ubicación física:
    * **El Personal de Seguridad:** Se encuentra en su puesto de vigilancia o recepción dentro del edificio, operando la estación base.
    * **El Residente:** Puede encontrarse en cualquier lugar con conexión a internet (su oficina, el transporte público, otra ciudad o dentro de su propio departamento), ya que recibe las notificaciones y el video directamente en su smartphone.

* **¿Dónde surge el problema?**
El problema se origina en la infraestructura interna del edificio, específicamente en las canalizaciones de las paredes y los ductos de comunicación donde el cableado antiguo se deteriora. Asimismo, surge en el vacío de comunicación que ocurre cuando el residente está fuera de su unidad habitacional, dejando el punto de acceso al edificio como un eslabón débil en la cadena de seguridad.

### ***When:***

* **Temporalidad del problema**
La operación de NexBell es de carácter continuo y en tiempo real (24/7). El proceso se activa instantáneamente en el momento en que un visitante se presenta en el punto de acceso; la plataforma web procesa la señal de video y dispara las notificaciones push de forma síncrona para asegurar que la comunicación ocurra en pocos segundos, garantizando la fluidez en la recepción.

* **¿Cuándo sucede el problema?**
El problema se manifiesta en dos momentos críticos:
    * **De forma latente y permanente:** Debido al deterioro progresivo del cableado que puede fallar en cualquier momento sin previo aviso.
    * **En el momento del contacto:** Cuando el personal de seguridad intenta comunicarse con un residente que no está en su departamento o cuando el intercomunicador físico presenta estática o inoperatividad, generando cuellos de botella y riesgos de seguridad en la entrada.

* **¿Cuándo utiliza el cliente el servicio?**
El servicio es utilizado en cada evento de interacción en el edificio:

    * **El Personal de Seguridad:** Cada vez que llega un visitante, proveedor de servicios o delivery.
    * **El Residente:** Al recibir alertas de visitas, al revisar el historial de ingresos para auditoría personal o al abrir la puerta de forma remota para un tercero autorizado.
    * **La Administración:** De forma periódica (mensual o semanal) para revisar reportes de incidencias y registros de auditoría digital.

### ***Why:***
* **Justificación del producto**
La implementación de NexBell se justifica por la necesidad imperativa de modernizar la seguridad residencial y optimizar la gestión económica de las juntas de propietarios. Al digitalizar el acceso, se garantiza la trazabilidad de cada ingreso (auditoría), se reduce la vulnerabilidad del edificio ante intrusiones y se elimina el gasto recurrente en reparaciones de hardware físico obsoleto. Además, responde a las demandas de conectividad del residente moderno, proporcionando comodidad y control directo desde cualquier lugar, lo que incrementa el valor comercial de la propiedad.

* **¿Cuál es la causa del problema?**
La causa raíz reside en la dependencia de infraestructura física pasiva (cables de cobre y terminales analógicos) instalada hace décadas, la cual sufre un desgaste inevitable y es difícil de diagnosticar. A esto se suma la falta de innovación en el sector de portería tradicional, que no ha integrado capacidades de red ni procesamiento de video, dejando al personal de seguridad limitado a una comunicación por audio de baja fidelidad sin capacidad de registro o respuesta remota.
    - **Causa técnica:**
La alta humedad y la sulfatación aceleran la corrosión de conductores y terminales, provocando pérdida de audio, estática y fallos en mecanismos de apertura (Consultoría & Servicios en Hidrocarburos y Minería S.A.C., 2019).
    - **Degradación y vida útil:**
Un sistema analógico en Lima tiende a entrar en falla crítica entre 5 y 8 años (Sunat, 2022); un sistema digital, con actualizaciones periódicas, tiene expectativa útil de 12–15 años.
    - **Costo de re‑tendido completo:**
Rehacer canalizaciones y acabados en un edificio pequeño o mediano: aproximadamente S/6,000 a S/12,000, según el alcance de la intervención y terminaciones, teniendo en cuenta el costo de obra civil, materiales necesarios y reemplazo de dispositivos (Cámara Peruana de la Construcción, 2019; Colegio de Arquitectos del Perú, 2025).

### ***How:***
* **Mecanismo de la solución**
La solución opera mediante un ecosistema de Internet de las Cosas (IoT). Al llegar una visita, el personal de seguridad utiliza una estación base conectada a la red (vía Wi-Fi o Ethernet) para iniciar una sesión de video. Esta señal se transmite a través de una plataforma web robusta alojada en la nube, que actúa como puente para enviar notificaciones push y streaming de video cifrado directamente a la aplicación móvil del residente, permitiendo una validación bidireccional y la apertura remota del acceso.

* **¿En qué condiciones los clientes usan nuestro producto?**
Los clientes utilizan el producto bajo condiciones de movilidad y conectividad. No dependen de estar físicamente junto a un teléfono de pared; el único requisito es que el edificio cuente con conexión a internet en la recepción y que el residente tenga acceso a datos móviles o Wi-Fi en su smartphone, permitiendo la gestión de seguridad tanto desde la comodidad del hogar como desde el exterior.

* **¿Cómo se integra el sistema en la organización?**
La integración es no invasiva y escalable. Al eliminar el cableado interno, la instalación se reduce a la configuración de los nodos IoT en los puntos de acceso y el registro de la base de datos de residentes en el panel administrativo de la plataforma web. La organización no necesita contratar técnicos especializados para mantenimiento de infraestructura, sino que gestiona todo de forma digital a través de un modelo de soporte de software.

* **¿Cómo prefieren los usuarios acceder al producto?**
Los usuarios prefieren un acceso omnichannel y simplificado:
    * El personal de seguridad prefiere una interfaz web centralizada en una tablet o computadora de escritorio que les permita gestionar múltiples accesos simultáneamente.
    * El residente prefiere el acceso vía aplicación móvil, priorizando la inmediatez de las notificaciones y la facilidad de una interfaz intuitiva para autorizar visitas con un solo toque.

### ***How Much:***
* **¿Cuánto cuesta?**
NexBell opera bajo un modelo de SaaS (Software as a Service) combinado con una inversión inicial mínima de hardware. Este esquema incluye:
    * **Costo de Implementación Inicial:** Una inversión reducida destinada a la adquisición y configuración de los nodos IoT en los puntos de acceso, eliminando los miles de dólares que costaría el cableado tradicional.
    * **Suscripción por Membresía:** Un pago recurrente (mensual o anual) por parte de la junta de propietarios o administración. Este modelo cubre el alojamiento en la nube, actualizaciones constantes de software, soporte técnico remoto y el almacenamiento de los registros de seguridad.

* **Impacto Económico y Operativo**
El impacto se traduce en una optimización radical de los recursos del edificio:
    * **Reducción de CAPEX:** Se elimina el gasto de capital masivo en infraestructura física (cables, ductos y citófonos por departamento). El ahorro en instalación puede superar el 70% en comparación con sistemas analógicos.
    * **Eliminación de Costos de Mantenimiento Correctivo:** Al no haber cables que se rompan dentro de las paredes, desaparecen las cuotas extraordinarias por reparaciones complejas y albañilería.
    * **Valorización del Inmueble:** La modernización tecnológica aumenta el valor percibido y real de las unidades inmobiliarias, posicionando al edificio como una propiedad inteligente y segura.
    * **Eficiencia en Seguridad:** El personal de conserjería reduce los tiempos de gestión de visitas y errores de comunicación, permitiéndoles enfocarse en otras tareas de vigilancia, lo que maximiza la productividad del servicio de seguridad contratado.
    * **Impacto por departamento (ahorro 5 años):** En un edificio de 20 dptos, ahorro acumulado estimado entre S/300 y S/1,000 por departamento, además de mejora en disponibilidad del servicio y reducción de días de indisponibilidad.

* **Evidencia de estadística**
    * **Brecha de Inseguridad:** Según el INEI (2025-2026), más del 80% de la población urbana en Perú percibe que podría ser víctima de un delito en los próximos 12 meses. Específicamente en Lima Metropolitana y el Callao, el 60% de los ciudadanos se siente inseguro al transitar por su propio barrio durante la noche, lo que eleva la demanda por sistemas de vigilancia activos y registros digitales.
    * **Incremento en Delitos de Extorsión:** Las denuncias por extorsión (modalidad que suele incluir el reglaje en viviendas y edificios) aumentaron un 44% en Lima durante el último año (ComexPerú, 2026). Esto refuerza la necesidad de NexBell de ofrecer un registro visual auditable que permita identificar visitantes antes de conceder el acceso.

### 1.2.3. Lean UX Process

#### 1.2.3.1. Lean UX Problem Statements

 - Hemos observado que los edificios residenciales en Lima presentan dificultades en la gestión de accesos, debido al uso de sistemas de intercomunicación tradicionales que no permiten validación visual ni registro digital de visitantes.
 **¿Cómo podemos ayudar a los administradores y conserjes a mejorar el control de accesos mediante una solución digital con monitoreo en tiempo real y registro automatizado?**
  
 - Hemos observado que el personal de conserjería depende de llamadas telefónicas internas y registros manuales, lo que genera retrasos y errores en la validación de visitantes.
 **¿Cómo podemos brindarles una herramienta rápida, intuitiva y confiable que les permita gestionar visitas sin depender de procesos manuales?**

 - Hemos observado que los residentes no siempre se encuentran en sus departamentos, lo que dificulta la comunicación con el personal de seguridad cuando reciben visitas o entregas.
 **¿Cómo podemos permitir que los residentes reciban notificaciones en tiempo real y respondan desde cualquier lugar mediante sus dispositivos móviles?**

 - Hemos observado que los sistemas actuales no generan un historial verificable de accesos, lo que limita la trazabilidad y auditoría en caso de incidentes.
 **¿Cómo podemos implementar un sistema que registre automáticamente cada interacción, incluyendo fecha, hora e imagen del visitante?**

#### 1.2.3.2. Lean UX Assumptions

**Assumptions worksheet**

 - El 70% de los conserjes en edificios urbanos depende de métodos manuales (cuadernos o llamadas) para registrar visitas, lo que genera errores y pérdida de información.<
 
 - El 80% de los residentes considera importante poder visualizar quién visita su hogar antes de autorizar el acceso, especialmente en zonas urbanas con mayor percepción de inseguridad.
 
 - Más del 65% de los usuarios prefiere recibir notificaciones en su celular en lugar de depender de estar físicamente en su departamento para atender visitas.

 - El 60% del personal de seguridad tiene conocimientos tecnológicos básicos, por lo que requiere sistemas simples, intuitivos y rápidos de operar.

- Los residentes valoran la seguridad y privacidad, ya que al menos el 75% considera importante contar con un registro de quién ingresó al edificio.

**User Outcome Assumptions** 

 - Los residentes podrán validar visitas en menos de 10 segundos mediante notificaciones en tiempo real y visualización de imagen o video.

 - Se reducirá en un 50% el tiempo de gestión de visitas por parte del conserje al eliminar procesos manuales.
 
 - El nivel de seguridad percibido por los residentes aumentará en al menos un 40% al contar con validación visual y registro digital.
 
 - Más del 60% de los usuarios confiará en el sistema como principal medio de control de accesos en el edificio.

**Business Assumptions**

 - El 50% de las juntas de propietarios en edificios modernos está dispuesto a invertir en soluciones tecnológicas que reduzcan costos de mantenimiento a largo plazo.
 
 - El modelo de negocio basado en instalación + servicio (suscripción opcional) es viable para condominios de nivel socioeconómico medio y alto en Lima.
 
 - Se estima que el 30% de los edificios nuevos buscará soluciones inteligentes de seguridad en los próximos años.
 
 - La adopción del sistema será progresiva, con una tasa de implementación inicial del 20% en edificios piloto.

**Business Outcome Assumptions**

 - Los edificios que implementen la solución podrán reducir en un 25% los costos de mantenimiento asociados a sistemas tradicionales de intercomunicación.
 
 - El valor percibido del inmueble aumentará en al menos un 15% al incorporar tecnología de seguridad inteligente.
 
 - Se incrementará la eficiencia operativa del personal de seguridad en un 40%, reduciendo errores y t tiempos de respuesta.
 
 - La startup Nexora IoT podrá escalar su solución a múltiples edificios, logrando crecimiento sostenido en el mercado local.

**Feature Assumptions**

 - El sistema de notificaciones push permitirá que el 90% de las alertas de visitas sean recibidas en menos de 5 segundos.
   
 - La captura de imagen del visitante será utilizada en más del 80% de las validaciones realizadas por los residentes.
 
 - El dashboard web permitirá al conserje gestionar visitas en menos de 3 clics por operación.
 
 - El historial de accesos será consultado al menos una vez por semana por administradores en el 70% de los edificios.
 
 - El sistema funcionará correctamente en condiciones normales de red WiFi en el 95% de los casos.

#### 1.2.3.3. Lean UX Hypothesis Statements

- Creemos que, al implementar un sistema de notificaciones en tiempo real hacia dispositivos móviles, se logrará que al menos el 80% de los residentes visualice una alerta de visita en menos de 5 segundos; sabremos que esto es cierto cuando el tiempo promedio de recepción de notificaciones sea inferior a ese intervalo.

- Creemos que, al integrar la captura de imagen del visitante mediante el dispositivo IoT, se logrará que el 85% de las validaciones de acceso se realicen con mayor confianza; sabremos que esto es cierto cuando la mayoría de accesos registrados incluyan evidencia visual utilizada en la decisión del conserje o residente.

- Creemos que, al incorporar el registro de audio del visitante con sus datos, se logrará que el proceso de validación sea más preciso y reduzca errores de identificación; sabremos que esto es cierto cuando las incidencias por registros incorrectos disminuyan en al menos un 40%.

- Creemos que, al proporcionar un dashboard web intuitivo para el personal de conserjería, se logrará que el 70% de las gestiones de visitas se realicen en menos de 15 segundos; sabremos que esto es cierto cuando el tiempo promedio de registro por visitante se mantenga por debajo de ese valor.

- Creemos que, al digitalizar el registro de accesos, se logrará que el 90% de las visitas queden almacenadas con información completa (hora, imagen y datos del visitante); sabremos que esto es cierto cuando la base de datos refleje consistencia en los registros generados.

- Creemos que, al permitir el registro previo de visitas por parte de los residentes, se logrará que el 60% de los accesos frecuentes se validen de manera más rápida; sabremos que esto es cierto cuando los registros coincidan con visitas previamente autorizadas en el sistema.

- Creemos que, al reemplazar sistemas tradicionales por una solución basada en IoT, se logrará reducir los costos operativos relacionados al mantenimiento en al menos un 25%; sabremos que esto es cierto cuando los gastos reportados por las juntas de propietarios disminuyan en comparación con periodos anteriores.

- Creemos que, al implementar una solución tecnológica accesible y escalable, se logrará que al menos el 50% de los edificios piloto adopten el sistema como herramienta principal de control de accesos; sabremos que esto es cierto cuando se mantenga una tasa de uso continuo por parte del personal de seguridad y residentes.

#### 1.2.3.4. Lean UX Canvas
<p align="center">
  <img src="https://i.imgur.com/D4JC1HD.png" alt="Lean UX Canvas" width="1000">
</p>

## 1.3. Segmentos Objetivo

Para garantizar que la solución tecnológica propuesta responda de manera efectiva a las necesidades del entorno residencial actual, se han identificado y analizado dos segmentos clave que enfrentan problemáticas en la gestión de accesos y seguridad en edificios multifamiliares.

A continuación, se detallan los perfiles estratégicos que forman parte del modelo de negocio, profundizando en sus características demográficas, geográficas y psicográficas, las cuales sustentan su relevancia dentro del dominio del problema.

<ins>**Segmento Objetivo 1: Juntas de propietarios y administradores de inmuebles**</ins>  
 
 **- Aspectos demográficos:**

  - **Sexo:** Masculino y femenino.
  - **Rango de edad:** 30 años a más.
  - **Nivel socioeconómico:** Clases A y B (administradores de edificios, representantes de juntas de propietarios y gestores inmobiliarios).
  - **Nivel educativo:** Educación técnica o universitaria, con conocimientos en gestión administrativa o inmobiliaria.

 **- Aspectos geográficos:**

  - **Nacionalidad:** Peruana.
  - **Zona geográfica:** Distritos urbanos de Lima Metropolitana con alta densidad residencial, tales como Miraflores, San Isidro, Surco y Lince.
  - **Entorno laboral:** Edificios multifamiliares y condominios ubicados en zonas urbanas consolidadas.

 **- Aspectos psicográficos:** 

  - **Dolor principal:** Altos costos de mantenimiento de sistemas tradicionales de intercomunicación, así como la falta de herramientas modernas para el control eficiente de accesos.
  - **Intereses:** Implementación de soluciones tecnológicas que mejoren la seguridad del inmueble, optimicen los procesos operativos y aumenten el valor del edificio.
  - **Actitudes:** Son analíticos y orientados a resultados, valoran soluciones confiables, escalables y que representen una inversión rentable a largo plazo.
  - **Necesidades clave:** Reducción de costos operativos, mejora en la seguridad del edificio, acceso a registros digitales de visitas y control centralizado de accesos.


<ins>**Segmento Objetivo 2: Personal de seguridad o conserjería**</ins> 

 **- Aspectos demográficos:**

  - **Sexo:** Masculino y femenino.
  - **Rango de edad:** 25 a 60 años.
  - **Nivel socioeconómico:** Clases C y D (trabajadores del sector servicios).
  - **Nivel educativo:** Educación secundaria completa o técnica básica.

 **- Aspectos geográficos:**

  - **Nacionalidad:** Peruana.
  - **Zona geográfica:** Edificios residenciales ubicados en zonas urbanas de Lima Metropolitana.
  - **Entorno laboral:** Recepciones, porterías o garitas de seguridad en edificios multifamiliares y condominios.

 **- Aspectos psicográficos:**  

  - **Dolor principal:** Dependencia de procesos manuales como registros en papel y llamadas internas, lo que genera errores, retrasos y dificultad en la gestión de visitas.
  - **Estilo de vida:** Laboral, con turnos rotativos y alta responsabilidad en el control de accesos y seguridad del edificio.
  - **Actitudes:** Buscan herramientas simples, rápidas y confiables que no requieran conocimientos técnicos avanzados.
  - **Intereses:** Facilitar su trabajo diario, reducir errores operativos y mejorar la comunicación con los residentes.
  - **Necesidades clave:** Sistema intuitivo, validación rápida de visitantes, registro automático de accesos y capacidad de comunicación eficiente con los residentes.

<hr>
<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

Con el fin de entender el entorno del mercado y la posición de nuestra solución, se realizó un análisis competitivo que identifica a los principales competidores en el ámbito de seguridad residencial. A través del siguiente Competitive Analysis Landscape, se comparan aspectos clave como propuesta de valor, características del producto, mercado objetivo y fortalezas de cada alternativa, permitiendo reconocer oportunidades de diferenciación para NexBell.

| Competitive Analysis Landscape |   |   |   |   |   |
|---|---|---|---|---|---|
| ¿Por qué realizar este análisis? |   Identificar brechas de mercado frente a soluciones de software locales y hardware tradicional, permitiendo que Nexora se posicione como la opción más accesible y de mejor experiencia de usuario (UX) para juntas de propietarios en Lima.   |
|  | | <img src="https://i.imgur.com/V5ax3EN.png" width=80px><br/><center>NexBell</center>  | <img src="https://media.licdn.com/dms/image/v2/D4E0BAQFbn4FXst-boA/company-logo_200_200/B4EZdhIVt2GcAI-/0/1749681265951/doormanlatam_logo?e=2147483647&v=beta&t=2bwVLlR3g5EUaAXGhLH_iLgsnxcrDGK2uqzmZbZmM58" width=80px><br/><center>Doorman</center> |  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSg_QHNHvPvy1bqD1N7DatdiejA9uAqOkMtdQ&s" width=80px><br/><center>Portero Seguro</center> |  <img src="https://emisoft.cuscoinformatico.com/storage/marcas/logo-hikvision.png" width=80px><br/><center>Hikvision</center>  |
| Perfil | Overview | Startup de la UPC enfocada en IoT y "Zero Hardware" en departamentos para modernizar edificios. | Startup consolidada que usa IA e IoT para portería virtual y gestión integral. | Empresa de "Teleportería" con vigilancia remota 24/7 y tótems de seguridad. | Gigante global de hardware de seguridad y videoporteros IP. |
|        | Ventaja competitiva<br/>¿Qué valor ofrece a los clientes? | Reducción drástica de costos de instalación (App-centric) y enfoque en UX para adultos mayores. | IA para automatizar procesos y una red de partners para servicios del edificio. | Seguridad activa 24/7 con respuesta rápida y ahorro de hasta 40% vs. portero físico. | Durabilidad industrial y ecosistema completo de seguridad (CCTV, alarmas). |
| Perfil de Marketing | Mercado Objetivo         | Edificios antiguos y nuevos en distritos como San Miguel, Pueblo Libre y Magdalena. | Condominios modernos y edificios de alta gama en Miraflores y San Isidro. | Edificios medianos (hasta 40 dptos.) que buscan eliminar el gasto de vigilantes físicos. | Constructoras e inmobiliarias que instalan sistemas desde los planos. |
|                     | Estrategias de Marketing | B2B con administradoras de edificios y marketing directo a Juntas de Propietarios. | Growth hacking en LinkedIn, alianzas con inmobiliarias y presencia en eventos Tech. | Venta basada en el ahorro de costos directos (ROI rápido) y seguridad perimetral. | Distribución masiva mediante canales técnicos (Wilson, centros comerciales tecnológicos). |
| Perfil de Producto  | Productos & Servicios    | Citofonía virtual, apertura remota vía App y panel de gestión para conserjes. | App para residentes, gestión de paquetes, portería remota y marketplace de servicios. | Vigilancia por cámaras con audio bidireccional, control de accesos y tótems. | Videoporteros físicos, cámaras IP, software Hik-Connect y biometría. |
|                     | Precios & Costos         | Modelo SaaS (Suscripción mensual baja) con costo de instalación mínimo. | Contratos anuales. Suscripción por departamento (SaaS + Hardware inicial). | Planes mensuales desde S/ 1,190 (12x7) hasta S/ 2,490 (24x7) por edificio. | Inversión inicial alta en equipos ($500 - $3,000+). Sin mensualidades obligatorias. |
|      | Canales de distribución (Web y/o Móvil) | App Móvil (iOS/Android) y Web de administración. | App nativa, Web y Central de Operaciones. | Hardware propietario en sitio + App de monitoreo para el residente. | Distribuidores oficiales y tiendas de seguridad electrónica. |
| Análisis SWOT          | Fortalezas            | Agilidad de startup, conocimiento del usuario local y bajo costo de entrada. | Marca posicionada, tecnología de IA robusta y expansión regional. | Servicio humano real detrás de la tecnología (sensación de seguridad). | Marca líder mundial, alta calidad de video y soporte técnico extenso. |
|                       | Debilidades            | Marca nueva en el mercado y dependencia de la conexión a internet del usuario. | Costo puede ser elevado para edificios con presupuestos ajustados. | Modelo menos escalable al requerir personal humano en la central. | Instalación compleja; requiere cableado y mantenimiento físico recurrente. |
|                       | Oportunidades          | Gran cantidad de edificios antiguos en Lima con intercomunicadores malogrados. | Alianzas con empresas de seguros y banca. | Expansión a provincias donde la seguridad física es muy cara. | Integración de sus equipos con plataformas SaaS de terceros (como Nexora). |
|                       | Amenazas               | Ingreso de funciones similares en apps de administración como ComunidadFeliz. | Competencia de empresas de seguridad tradicionales (Prosegur). | Posibles fallas en la red eléctrica o de internet que inhabiliten el sistema. | Guerra de precios de fabricantes chinos genéricos (Dahua, etc.). |

#

### 2.1.2. Estrategias y tácticas frente a competidores

El despliegue de NexBell en el mercado residencial peruano requiere un análisis que trascienda la implementación técnica. Para ello, se han diseñado estrategias el cual permite a Nexora identificar cómo sus fortalezas internas pueden aprovechar las oportunidades del entorno, al mismo tiempo que se establecen mecanismos de defensa ante las amenazas del sector.

 - **Diferenciación Tecnológica y "Zero Hardware":** Implementación de una arquitectura basada en IoT y Citofonía Virtual que elimina la necesidad de cableado interno complejo. A diferencia de Hikvision, que requiere inversiones altas en equipos y mantenimiento físico ($500 - $3,000+), NexBell utiliza una infraestructura ágil que permite una instalación mínima y reducción de costos operativos para las Juntas de Propietarios.

 - **Experiencia de Usuario (UX Local):** Diseño centrado en el usuario peruano, con un enfoque especial en la facilidad de uso para adultos mayores. Mientras competidores como Doorman se enfocan en condominios modernos de alta gama, NexBell se posiciona como la opción más accesible y de mejor experiencia para residentes en distritos como San Miguel, Pueblo Libre y Magdalena, simplificando la validación de visitas desde el móvil.

 - **Seguridad y Auditoría Digital:** A diferencia de sistemas tradicionales o fabricantes chinos genéricos, NexBell ofrece una bitácora inmutable de registros digitales, fotos y horarios de acceso. Esta capacidad de auditoría eleva la percepción de seguridad en un 40%, superando a soluciones de hardware que no incluyen gestión de datos inteligente o soporte local auditable.

 - **Modelo de Negocio y Escalabilidad (SaaS):** Posicionamiento como la alternativa SaaS (Software as a Service) más económica para edificios con presupuestos ajustados, utilizando una suscripción mensual baja. Este modelo permite un ROI más rápido en comparación con servicios de teleportería como Portero Seguro, que requieren planes mensuales elevados de hasta S/ 2,490, permitiendo que Nexora escale rápidamente en edificios antiguos con intercomunicadores obsoletos.

 - **Estrategia Go-to-Market y Alianzas:** Enfoque en la captación directa mediante alianzas con administradoras de edificios y marketing dirigido a Juntas de Propietarios. La estrategia se orienta a convertir la debilidad de ser una "marca nueva" en una ventaja de servicio personalizado y cercano, estableciendo vínculos con banca y seguros para ofrecer NexBell como un valor agregado de protección patrimonial frente a la frialdad de las corporaciones globales.

 - **Resiliencia y Soporte Local:** Mitigación de riesgos de conectividad mediante protocolos de comunicación local y guías de configuración robustas. Al ser una startup de la UPC, Nexora aprovecha el conocimiento del entorno físico local para ofrecer un mantenimiento preventivo y soporte que los distribuidores de marcas internacionales no garantizan de forma personalizada.

## 2.2 Entrevistas.

Esta sección detalla el proceso de investigación cualitativa realizado con el objetivo de validar las hipótesis planteadas sobre la problemática de seguridad y control de accesos en edificios residenciales.
A través de entrevistas a representantes de los segmentos objetivo, se busca comprender sus necesidades, experiencias actuales y percepciones frente a soluciones tecnológicas, obteniendo información clave para el desarrollo del sistema propuesto.

### 2.2.1. Diseño de entrevistas

Se presenta la elaboración de guías de preguntas estructuradas, dirigidas a los dos segmentos principales del proyecto: administradores de edificios residenciales y personal de seguridad o conserjería.

<ins>**Segmento Objetivo 1: Juntas de propietarios y administradores de inmuebles**</ins> 

**Objetivo de la entrevista:** Comprender los principales problemas en la gestión de seguridad del edificio, evaluar los costos y limitaciones de los sistemas actuales, y validar el interés en implementar una solución tecnológica basada en IoT para el control de accesos.

***Características demográficas:***

 - ¿Cuál es su nombre?
 - ¿Cuál es su edad?
 - ¿Qué cargo ocupa dentro del edificio o empresa administradora?
 - ¿En qué distrito se encuentra el edificio que administra?
 - ¿Cuántos departamentos o residentes aproximadamente tiene el edificio?

***Preguntas sobre la problemática:***

 - ¿Qué tipo de sistema utilizan actualmente para el control de accesos (intercomunicador, registro manual, otros)?
 - ¿Cuáles son los principales problemas que ha identificado en este sistema?
 - ¿Qué tan frecuentes son las fallas o inconvenientes en la comunicación entre portería y residentes?
 - ¿Qué dificultades existen para llevar un registro de las visitas?
 - ¿Qué tan costoso resulta el mantenimiento del sistema actual?
 - ¿Ha ocurrido alguna situación de inseguridad relacionada con el control de accesos?

***Preguntas sobre la solución:*** 

 - Si existiera un sistema que permita validar visitantes mediante imagen y notificaciones en tiempo real, ¿qué tan útil le parecería?
 - ¿Qué funcionalidades consideraría indispensables en una solución de este tipo?
 - ¿Qué beneficios esperaría obtener al implementar un sistema digital de control de accesos?
 - ¿Qué factores influirían en su decisión de adquirir una solución como esta (costo, facilidad de uso, seguridad, etc.)?
 - ¿Estaría dispuesto a invertir en una solución que reduzca costos de mantenimiento a largo plazo? ¿En qué rango?

<ins>**Segmento Objetivo 2: Personal de seguridad o conserjería**</ins> 

**Objetivo de la entrevista:** Identificar las dificultades operativas en la gestión de visitas, comprender su nivel de interacción con herramientas tecnológicas y validar la usabilidad de un sistema digital de control de accesos.

***Características demográficas:***

 - ¿Cuál es su nombre?
 - ¿Cuál es su edad?
 - ¿Cuánto tiempo lleva trabajando como conserje o personal de seguridad?
 - ¿En qué distrito trabaja actualmente?
 - ¿Qué turnos suele cubrir (día, noche, rotativo)?

***Preguntas sobre la problemática:***

 - ¿Cómo registra actualmente el ingreso de visitantes al edificio?
 - ¿Qué dificultades encuentra al momento de identificar o validar a un visitante?
 - ¿Qué tan frecuente es que tenga que comunicarse con los residentes para autorizar ingresos?
 - ¿Qué problemas se presentan cuando el residente no se encuentra en su departamento?
 - ¿Ha tenido errores o confusiones al registrar visitas? ¿Por qué cree que suceden?
 - ¿Qué tan cómodo se siente usando tecnología en su trabajo diario?

***Preguntas sobre la solución:*** 

 - Si tuviera una pantalla donde pudiera ver la imagen del visitante antes de atenderlo, ¿le sería útil? ¿Por qué?
 - ¿Qué tan fácil cree que sería usar un sistema digital para registrar visitas en lugar de cuadernos?
 - ¿Qué funcionalidades le ayudarían a hacer su trabajo más rápido o sencillo?
 - ¿Le gustaría que el sistema registre automáticamente la información de cada visitante?
 - ¿Qué le preocuparía al usar un sistema como este (fallas, complejidad, tiempo de uso)?

### 2.2.2. Registro de Entrevistas.

**Segmento objetivo \#1: Juntas de propietarios y administradores de inmuebles**  

**Entrevista \#1:** 

* **Nombre:** Nicolas 
* **Apellido:** Deza
* **Distrito:** Miraflores

**Figura** 

*Entrevista \#1 para NexBell* 

<p align="center">
  <img src="https://res.cloudinary.com/dbsohlwoq/image/upload/v1776468840/entrevista_raul_1_blaqjt.jpg" width="1000">
</p>

* **URL:** https://goo.su/uUlzE  
* **Inicio:** 0:04
* **Fin:** 4:50
* **Resumen:**

El entrevistado es Nicolás, administrador en una empresa de gestión inmobiliaria a cargo de tres proyectos, incluyendo un edificio de 64 departamentos en Miraflores. Actualmente, utilizan un sistema de intercomunicadores analógicos y registro manual en cuaderno, lo cual genera graves problemas de trazabilidad y fiabilidad. El desafío principal es el deterioro del cableado, cuyo mantenimiento es costoso y requiere reparaciones constantes que no solucionan el problema de fondo. Además, se reportó una brecha de seguridad reciente donde un repartidor ingresó sin autorización por errores en la comunicación verbal. Nicolás considera indispensable una solución digital con interfaz sencilla, respaldo en la nube y notificaciones en tiempo real para los residentes. El factor decisivo para la compra sería el costo-beneficio, priorizando un sistema que no requiera obra civil (romper paredes) y que se amortice en máximo un año y medio mediante el ahorro en técnicos.


**Entrevista \#2:** 

* **Nombre:** Mariel Fernanda   
* **Apellido:** Casoida Alegria
* **Distrito:** San Borja 

**Figura 3** 

*Entrevista \#2 para NexBell* 

<p align="center">
  <img src="https://res.cloudinary.com/dbsohlwoq/image/upload/v1776468840/entrevista_raul_2_woc1as.jpg" width="1000">
</p>

* **URL:** https://goo.su/azYMZt   
* **Inicio:** 0:09  
* **Fin:** 5:15  
* **Resumen:**

La entrevistada es Mariel, quien cumple el doble rol de administradora y tesorera de un edificio pequeño de 12 departamentos en San Borja. Al ser una comunidad reducida, el principal problema es que los costos de mantenimiento del sistema analógico actual son muy altos al prorratearse entre pocos vecinos; cualquier reparación de cables o placas impacta fuertemente en su presupuesto. Los desafíos clave incluyen la mala calidad del audio, la falta de un registro formal de visitas que dependen de la memoria del portero y la falta de movilidad, ya que los residentes (muchos de ellos profesionales que viajan) no pueden contestar si no están físicamente en el departamento. Mariel busca una solución inalámbrica que no requiera romper paredes, que permita la apertura remota desde el celular y que genere un registro fotográfico de quienes ingresan. Para este segmento, la prioridad es la simplicidad de uso para evitar quejas de los vecinos y "modernizar" el edificio para que se sienta premium, con una inversión única de entre 20 y 50 dólares por departamento.


**Entrevista \#3:** 

* **Nombre:** Jose   
* **Apellido:** Rodriguez 
* **Distrito:** Lince

**Figura 4** 

*Entrevista \#3 para NexBell* 

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/Captura_de_pantalla_2026-04-21_a_la_s_5.37.34_a._m._lenkzo" width="1000">
</p> 

* **URL:** https://goo.su/ui0ETm
* **Inicio:** 0:02
* **Fin:** 6:17
* **Resumen:**

El entrevistado es un administrador de 32 años que gestiona un edificio de 28 departamentos en Lince, habitado principalmente por jóvenes. El problema central es un sistema de accesos obsoleto (intercomunicador y Excel) que falla ante visitas simultáneas y genera graves brechas de seguridad, como la suplantación de identidad por falta de registro visual. Los desafíos clave incluyen el cableado deteriorado y los altos costos recurrentes en reparaciones técnicas. Busca una solución digital con verificación por imagen, historial fotográfico y acceso remoto que reduzca su carga operativa y modernice el control de visitas. Para este perfil, la prioridad es la seguridad y la reducción de gastos de mantenimiento, prefiriendo un modelo de pago accesible de entre 15 y 30 dólares por departamento que sea fácil de aprobar por la junta de propietarios.

---

**Segmento objetivo \#2: Personal de seguridad o conserjería**

**Entrevista \#4:** 

* **Nombre:** Gabriel
* **Apellido:** Polanco
* **Distrito:** Surco

**Figura 5** 

*Entrevista \#4 para NexBell* 

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/Captura_de_pantalla_2026-04-21_a_la_s_5.37.56_a._m._lssgzz" width="1000">
</p>

* **URL:** https://goo.su/bvDM8p
* **Inicio:** 0:02
* **Fin:** 05:43
* **Resumen:**

El entrevistado es un conserje de 49 años con amplia experiencia en seguridad que trabaja en un edificio en Surco. El problema principal es el registro manual en cuaderno, que resulta lento, propenso a errores de escritura y genera cuellos de botella críticos durante las horas pico de deliveries. Los desafíos clave incluyen las interferencias del intercomunicador y la dificultad para contactar a residentes, lo que deriva en conflictos con visitantes y una alta carga operativa en turnos de 12 horas. Busca una herramienta digital tipo tablet que automatice el registro, envíe notificaciones directas al celular de los vecinos y permita la verificación visual por imagen. Para este perfil, la prioridad es el orden y la agilidad del flujo en portería, siempre que el sistema sea estable ante caídas de internet y lo suficientemente resistente para el uso rudo diario.


**Entrevista \#5:** 

* **Nombre:** Kylie 
* **Apellido:** Pizarro
* **Distrito:** Pueblo Libre

**Figura 6** 

*Entrevista \#5 para NexBell*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776477309/entrevista_daniela_1_cfvce8.jpg" width="1000">
</p>

* **URL:** https://goo.su/75NbpG7   
* **Inicio:** 0:01 
* **Fin:** 5:29
* **Resumen:**

La entrevistada es Kylie Pizarro, conserje de 23 años que trabaja en turno nocturno en un edificio de Pueblo Libre. Actualmente, el control de accesos se realiza mediante un cuaderno y un intercomunicador, lo que le genera dificultades como errores en el registro, desorden de información y retrasos al validar visitas, especialmente cuando los residentes no responden. Además, expresa inseguridad al no contar con una forma visual de verificar la identidad de los visitantes, dependiendo únicamente de lo que estos declaran. El cansancio del turno nocturno también influye en posibles equivocaciones durante el proceso. Kylie considera que una solución digital que incluya captura de imagen, registro automático y notificaciones en tiempo real facilitaría significativamente su trabajo, haciéndolo más rápido, seguro y organizado. Para ella, es clave que el sistema sea simple, confiable y fácil de usar, ya que esto le permitiría adoptar la tecnología sin complicaciones en su rutina diaria.


**Entrevista \#6:** 

* **Nombre:** Mario  
* **Apellido:** Villafuentes   
* **Distrito:** Cercado de Lima

**Figura 7** 

*Entrevista \#6 para NexBell* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776825105/entrevista_mario_pvop8h.jpg" width="1000">
</p> 

* **URL:** https://goo.su/KG8QCzd   
* **Inicio:** 0:02 
* **Fin:** 6:41
* **Resumen:**

El entrevistado es Mario Villafuentes, conserje del condominio Parque Central, donde señala que la seguridad es deficiente y poco controlada. Actualmente, utiliza cuadernos para registrar visitas, lo que le genera desorden y falta de claridad en la información. Indica que los residentes muchas veces no responden cuando intenta comunicarse, lo que dificulta la validación de accesos. Además, menciona que en varias ocasiones no logra diferenciar si una persona es residente o visitante, lo que incrementa el riesgo de ingreso no autorizado. También comenta que algunas visitas se incomodan cuando se les solicita información, lo que complica aún más su trabajo. Durante su turno, reconoce que en momentos como su refrigerio la puerta puede quedar sin supervisión, lo que genera incertidumbre sobre quién ingresa o sale del edificio. Frente a esta situación, considera que una solución digital sería de gran ayuda, especialmente si permite llevar un historial de accesos, relacionar a los propietarios con sus departamentos y organizar mejor la gestión en condominios con múltiples torres, asignando control por cada una de ellas.


### 2.2.3. Análisis de entrevistas

Esta sección presenta la documentación organizada de las entrevistas aplicadas a cada segmento objetivo. Aquí se detallan los perfiles, las respuestas obtenidas y las observaciones clave de cada sesión, garantizando la transparencia y el orden de la información recopilada.

Esta estructura facilita el análisis de datos y sirve como base sólida para el desarrollo de herramientas de diseño centrado en el usuario, permitiendo construir con precisión User Personas, Mapas de Empatía y Matrices de Tareas.


**Segmento objetivo \#1: Juntas de propietarios y administradores de inmuebles**


Esta sección detalla el análisis cualitativo derivado de las entrevistas a los administradores de los distritos de Miraflores, San Borja y Lince. Los datos obtenidos permiten validar las hipótesis de negocio y entender los motivadores de compra del sistema NexBell.

***- Tabla Comparativa de Entrevistas***

| Variable | Entrevista #1 (Miraflores) | Entrevista #2 (San Borja) | Entrevista #3 (Lince) |
| :--- | :--- | :--- | :--- |
| **Perfil del Edificio** | Alta densidad (64 dptos) | Baja densidad (12 dptos) | Mediana densidad (28 dptos) |
| **Problema Principal** | Deterioro de cableado y falta de trazabilidad. | Alto costo de mantenimiento por pocos vecinos. | Fallas por humedad e inseguridad (suplantación). |
| **Sistema Actual** | Analógico + Cuaderno manual. | Analógico (Solo audio). | Intercomunicador + Excel/Cuaderno. |
| **Funcionalidad Vital** | Notificaciones en tiempo real y respaldo en la nube. | Apertura remota y registro fotográfico. | Historial de fotos y acceso para el administrador. |
| **Disponibilidad de Inversión** | $30 - $40 por departamento. | $20 - $50 por departamento. | $15 - $30 (Financiado). |
| **Factor de Decisión** | Retorno de inversión (ROI) en 1.5 años. | Simplicidad y estética "Premium". | Reducción de cuota de mantenimiento técnica. |


***- Hallazgos Clave del Segmento***

- **Obsolescencia de la Infraestructura Física:** El **100% de los entrevistados** identificó el cableado como el mayor punto de dolor. El mantenimiento no solo es costoso, sino ineficiente, ya que las reparaciones son "parches" que no solucionan la degradación del cobre o las fallas por humedad.

- **Necesidad de Validación Visual:** Se confirmó que el audio no es suficiente para garantizar la seguridad. Los administradores reportaron incidentes de **suplantación de identidad** (técnicos falsos) y accesos no autorizados de repartidores de delivery debido a la mala calidad de comunicación de los intercomunicadores tradicionales.

- **El Cambio hacia la Movilidad (Smartphone):** Existe una demanda creciente por parte de los residentes (especialmente jóvenes y profesionales) de gestionar el acceso desde el celular. La incapacidad de atender visitas cuando el residente no está físicamente en el departamento se percibe como una limitación crítica del sistema actual.

- **Viabilidad Financiera:** Los administradores están dispuestos a invertir en tecnología siempre que:

  - **No requiera obra civil:** Evitar romper paredes es una prioridad absoluta (15% del peso en la decisión).
  - **Ahorro operativo:** El sistema debe pagarse solo mediante la eliminación de los costos fijos de técnicos y repuestos analógicos.

***- Resumen de Validación de Hipótesis***

| Hipótesis Planteada | Estado | Sustento de la Entrevista |
| :--- | :--- | :--- |
| El mantenimiento analógico es un gasto crítico. | **Validada** | Los tres administradores coinciden en que el gasto técnico anual es elevado e improductivo. |
| La seguridad es la principal preocupación. | **Validada** | Se mencionaron brechas de seguridad reales por falta de registro visual. |
| Los residentes prefieren usar su smartphone. | **Validada** | Es la solución a la falta de comunicación cuando el residente viaja o trabaja fuera. |

***- Conclusión del Análisis***
   
El segmento de administradores actúa como el **decisor económico**. NexBell no debe venderse solo como un "intercomunicador inteligente", sino como una **solución de eficiencia presupuestaria** que profesionaliza la seguridad del edificio sin los costos logísticos de la infraestructura cableada.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/Gemini_Generated_Image_8rnw3g8rnw3g8rnw_1_tyaluk" width="1000">
</p> 

**Segmento objetivo \#2: Personal de seguridad o conserjería** 

Este análisis se centra en la viabilidad operativa de NexBell desde la perspectiva de quienes utilizarán el sistema diariamente: los conserjes.

***- Puntos de Dolor Identificados***

- **El "Cuello de Botella" del Delivery:** En las tres entrevistas se identificó que el flujo de repartidores genera caos. El conserje debe abandonar otras tareas (vigilancia, rondas) para marcar repetidamente a departamentos que no contestan.
- **Fallas de Comunicación:** El ruido, la estática de los citófonos viejos y los cruces de líneas provocan errores en el registro y malentendidos con los residentes.
- **Responsabilidad Compartida:** Los conserjes temen ser culpados si un paquete se pierde o alguien entra sin permiso. Actualmente, el cuaderno manual es su única "prueba", la cual es fácilmente cuestionable.

***- Expectativas sobre la Solución***
- **Autogestión del Residente:** Lo más valorado es que el sistema envíe la alerta directamente al celular del dueño. Esto quita al conserje el rol de "operador telefónico" y le permite enfocarse en la vigilancia.
- **Identificación Visual:** Poder ver quién está afuera antes de interactuar reduce el riesgo de agresiones o ingresos por presión social (cuando el visitante exige entrar rápido).
- **Digitalización del Registro:** El reemplazo del cuaderno por una interfaz táctil se percibe como una mejora en la limpieza y profesionalismo de su trabajo.

***- Barreras de Adopción***

- **Estabilidad Tecnológica:** Existe un temor genuino a que la caída del internet deje al edificio incomunicado.
- **Brecha Generacional:** Se identificó la preocupación de que residentes adultos mayores tengan dificultades con la App, lo que generaría fricciones que el conserje tendría que resolver.

***- Validación de Hipótesis***

| Hipótesis | Estado | Sustento |
| :--- | :--- | :--- |
| El registro manual es ineficiente y propenso a errores. | **Validada** | Los conserjes admiten que por el apuro omiten datos o escriben de forma ilegible. |
| El personal de seguridad está dispuesto a usar tablets/pantallas. | **Validada** | Incluso los perfiles de mayor edad ya usan WhatsApp y ven con buenos ojos la modernización. |
| La validación visual reduce el estrés laboral. | **Validada** | Saber quién está en la puerta antes de atender da una sensación de control y seguridad. | 

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/Gemini_Generated_Image_j87wfkj87wfkj87w_lw6qbd" alt="Class Diagram">
</p>

## 2.3. Needfinding

En esta sección, se transforma la información recolectada durante la investigación en hallazgos estratégicos mediante el uso de artefactos clave de experiencia de usuario. A través de herramientas como User Personas, User Task Matrix, User Journey Maps y Empathy Maps, se analiza el contexto actual en el que se desenvuelven los usuarios, así como sus necesidades, comportamientos y principales problemáticas.

Estos artefactos permiten comprender de manera integral a los actores involucrados en la gestión de accesos en entornos residenciales, proporcionando una base sólida para la toma de decisiones de diseño. De esta forma, se asegura que la propuesta de solución de Nexora esté alineada con las necesidades reales de los usuarios y contribuya a mejorar su experiencia y eficiencia operativa.

### 2.3.1. User Personas

Se presentan los User Personas de Nexora, construidos a partir del análisis de entrevistas realizadas a los segmentos objetivo y la revisión de soluciones existentes en el ámbito de seguridad residencial. Cada arquetipo representa de manera estructurada las características, motivaciones, frustraciones y comportamientos de los actores clave dentro del ecosistema del edificio, como administradores y personal de conserjería.

Estas representaciones permiten comprender de forma más profunda las necesidades reales de los usuarios, asegurando que el diseño de la solución tecnológica responda de manera efectiva a los problemas identificados en la gestión de accesos y seguridad. De esta manera, los User Personas funcionan como una guía estratégica para el desarrollo de funcionalidades alineadas con el contexto operativo del proyecto.

<div style="page-break-after: always;"></div>

<ins>**Segmento Objetivo 1: Juntas de propietarios y administradores de inmuebles**</ins>  

**Figura:** *User persona de María Fernández*

<p align="center">
  <img src="https://res.cloudinary.com/dxtlqfkp9/image/upload/v1776296243/Mar%C3%ADa_Fern%C3%A1ndez_hjtdj0.png" alt="Class Diagram" height=1000px width=700px>
</p>

*Nota. Elaboración propia de UXPressia*

<div style="page-break-after: always;"></div>

<ins>**Segmento Objetivo 2: Personal de seguridad o conserjería**</ins>

**Figura:** *User persona de José Ramírez*

<p align="center">
  <img src="https://res.cloudinary.com/dxtlqfkp9/image/upload/v1776296233/Jos%C3%A9_Ram%C3%ADrez_mfmy85.png" alt="Class Diagram" height=1000px width=700px>
</p>

*Nota. Elaboración propia de UXPressia*

<div style="page-break-after: always;"></div>

### 2.3.2. User Task Matrix

En esta sección se describen las principales tareas que realizan los segmentos objetivo dentro del contexto de seguridad y control de accesos en edificios residenciales. Estas actividades forman parte de su rutina diaria y se ejecutan independientemente de la existencia de una solución tecnológica como Nexora, ya sea mediante procesos manuales, sistemas tradicionales de intercomunicación o herramientas básicas de registro.

El análisis considera a dos actores principales: la administradora del edificio, responsable de la supervisión y toma de decisiones, y el personal de conserjería, encargado de la operación directa del control de accesos. La identificación de estas tareas permite entender la frecuencia e importancia de cada actividad, proporcionando una base sólida para priorizar funcionalidades dentro del sistema propuesto.


| User Tasks                                                        | María Fernández         | María Fernández           | José Ramírez |  José Ramírez            |
| ----------------------------------------------------------------- | ------------------------------------- | ----------- | ---------------------------- | ----------- |
|                                                                   | **Frecuencia**             |  **Importancia** |         **Frecuencia**          |  **Importancia** |
| Identificar fallas en el sistema de intercomunicación tradicional | Alta                                  | Alta        | Media                        | Media       |
| Evaluar costos de mantenimiento del sistema de seguridad          | Alta                                  | Alta        | Baja                         | Media       |
| Supervisar el control de accesos del edificio                     | Media                                 | Alta        | Alta                         | Alta        |
| Registrar visitas y controlar ingresos manualmente                | Baja                                  | Media       | Alta                         | Alta        |
| Validar la identidad de visitantes antes de permitir el acceso    | Media                                 | Alta        | Alta                         | Alta        |
| Comunicarse con residentes para autorizar visitas                 | Baja                                  | Media       | Alta                         | Alta        |
| Llevar un registro de ingresos y salidas del edificio             | Media                                 | Alta        | Alta                         | Alta        |
| Detectar situaciones de riesgo o accesos no autorizados           | Media                                 | Alta        | Alta                         | Alta        |
| Evaluar nuevas soluciones tecnológicas para mejorar la seguridad  | Media                                 | Alta        | Baja                         | Media       |
| Revisar reportes o historial de accesos del edificio              | Media                                 | Alta        | Media                        | Media       |


### 2.3.3. User Journey Mapping

En esta sección se representa de manera integral la experiencia actual de los usuarios a través de un User Journey Map, donde se analizan sus acciones, pensamientos y emociones a lo largo de las distintas etapas del proceso de gestión de accesos en el edificio. Este recorrido permite visualizar cómo interactúan con los sistemas tradicionales y qué dificultades enfrentan en cada fase.

Al identificar los puntos de dolor (pains) y oportunidades de mejora (gains), se logra transformar la información obtenida en la investigación en insumos clave para el diseño de la solución. Este enfoque facilita la detección de ineficiencias, momentos críticos y necesidades no cubiertas, orientando el desarrollo de Nexora hacia una experiencia más eficiente, segura y centrada en el usuario.

<div style="page-break-after: always;"></div>

<ins>**Segmento Objetivo 1: Juntas de propietarios y administradores de inmuebles**</ins>  

**Figura:** *User Journey Mapping de María Fernández*

<p align="center">
  <img src="https://res.cloudinary.com/dxtlqfkp9/image/upload/v1776303068/Journey_Mapping_de_Juntas_de_propietarios_y_administradores_de_muebles_wrswek.png" alt="Class Diagram">
</p>

*Nota. Elaboración propia de UXPressia*

<div style="page-break-after: always;"></div>

<ins>**Segmento Objetivo 2: Personal de seguridad o conserjería**</ins>

**Figura:** *User Journey Mapping de José Ramírez*

<p align="center">
  <img src="https://res.cloudinary.com/dxtlqfkp9/image/upload/v1776307102/Jouney_Mapping_de_Personal_de_seguridad_o_conserjeria_2_w3bow9.png" alt="Class Diagram">
</p>

*Nota. Elaboración propia de UXPressia*

<div style="page-break-after: always;"></div>

### 2.3.4. Empathy Mapping

El Empathy Map permite profundizar en la comprensión de los usuarios al analizar lo que piensan, sienten, dicen y hacen en relación con la problemática del control de accesos en edificios residenciales. A través de esta herramienta, se identifican percepciones, preocupaciones y comportamientos que no siempre son evidentes en un análisis superficial.

Esta representación facilita una visión más humana del usuario, destacando sus frustraciones frente a sistemas tradicionales y sus expectativas respecto a soluciones tecnológicas modernas. Como resultado, se obtienen insights valiosos que contribuyen a diseñar una propuesta alineada con sus verdaderas necesidades y mejorar significativamente su experiencia en el entorno residencial.

<ins>**Segmento Objetivo 1: Juntas de propietarios y administradores de inmuebles**</ins>  

**Figura**

*Empathy Mapping de María Fernández*

<p align="center">
  <img src="https://res.cloudinary.com/dxtlqfkp9/image/upload/v1776304501/Empathy_map_de_junta_de_propietarios_y_admintradores_de_inmuebles_kqdw1b.png" alt="Class Diagram">
</p>

*Nota. Elaboración propia de UXPressia*

<ins>**Segmento Objetivo 2: Personal de seguridad o conserjería**</ins>

**Figura**

*Empathy Mapping de José Ramírez*

<p align="center">
  <img src="https://res.cloudinary.com/dxtlqfkp9/image/upload/v1776303068/Empathy_map_de_persona_de_seguridad_l52v13.png" alt="Class Diagram">
</p>

*Nota. Elaboración propia de UXPressia*

<div style="page-break-after: always;"></div>

## 2.4. Big Picture EventStorming

El Big Picture EventStorming es una metodología de taller colaborativo diseñada para explorar dominios de negocio complejos mediante la visualización de procesos de software. Esta técnica facilita la alineación entre los expertos del dominio y el equipo técnico, permitiendo identificar la lógica de negocio, los puntos de fricción y las dependencias del sistema de manera comprensiva.
En NexBell, el equipo lo aplicó para modelar el flujo de gestión de visitas y control de acceso inteligente, siguiendo los pasos que se detallan a continuación:

#### Fase 1: Identificación de Eventos de Dominio (Domain Events)
En la etapa inicial, se procedió a identificar los Eventos de Dominio, definidos como sucesos relevantes que ocurren dentro del sistema y se expresan en tiempo pasado. Esta lluvia de ideas masiva permite capturar todas las interacciones posibles, estableciendo la base semántica del proyecto.

<p align="center">
<img align="center" src="https://i.imgur.com/TEms3yG.jpeg" alt="Domain Events" style="height: auto;"></p>

#### Fase 2: Construcción de la Línea de Tiempo (Timelines)
Una vez definidos los eventos, estos se organizaron cronológicamente para establecer una narrativa coherente. Este proceso de secuenciación permite identificar flujos paralelos, ramificaciones en la toma de decisiones y posibles lagunas en la lógica del proceso, asegurando que la continuidad del servicio (desde el timbrado hasta el registro final) sea consistente.

<p align="center">
<img align="center" src="https://i.imgur.com/HPudNcV.jpeg" alt="Timelines" style="height: auto;"></p>

#### Fase 3: Definición de Actores
Se procedió a asignar Actores a cada flujo, identificando a los agentes humanos (Residente, Conserje, Administrador o Visitante) que interactúan con el sistema. Esta asignación es crítica para comprender las responsabilidades y los permisos dentro de la plataforma, diferenciando quién recibe una notificación y quién tiene la autoridad para ejecutar acciones como la apertura remota.

<p align="center">
<img align="center" src="https://i.imgur.com/UBD0aBX.jpeg" alt="Actors" style="height: auto;"></p>

#### Fase 4: Integración de Sistemas Externos e IoT
Dada la naturaleza del proyecto, se identificaron los Sistemas Externos y dispositivos de hardware que interactúan con el software. En esta etapa se integraron elementos como sensores magnéticos, dispositivos IoT de control de puerta y servicios de terceros (Niubiz para pagos y Gmail para notificaciones), mapeando las dependencias tecnológicas del ecosistema.

<p align="center">
<img align="center" src="https://i.imgur.com/4OApAa7.jpeg" alt="External Systems" style="height: auto;"></p>

#### Fase 5: Identificación de Comandos
Los Comandos representan las intenciones de los usuarios o la voluntad de ejecutar una acción específica que resulta en un evento. En esta fase, se vincularon acciones como "Abrir puerta", "Iniciar sesión" o "Emitir notificación" con sus respectivos disparadores, estableciendo la relación de causalidad directa entre la interfaz de usuario y los cambios de estado en el sistema.

<p align="center">
<img align="center" src="https://i.imgur.com/wKDrzI1.jpeg" alt="Commands" style="height: auto;"></p>

#### Fase 6: Definición de Políticas (Policies)
Se establecieron las Políticas o reglas de negocio que automatizan procesos ante eventos específicos. Estas actúan como puentes lógicos y permiten documentar los criterios de seguridad, auditoría y flujo de trabajo que rigen el comportamiento autónomo del sistema.

<p align="center">
<img align="center" src="https://i.imgur.com/cPTMU3T.jpeg" alt="Policies" style="height: auto;"></p>

#### Fase 7: Identificación de Puntos Críticos (Hotspots)
Finalmente se realizó una fase de diagnóstico para identificar los Puntos Críticos o Hotspots. Esta etapa consiste en señalizar áreas de incertidumbre, riesgos técnicos o fricciones operativas que podrían comprometer la robustez del software. En este proyecto, se priorizaron factores como la latencia en la comunicación de dispositivos IoT y errores durante procesos manuales. La detección temprana de estos puntos de dolor permite al equipo anticipar fallos y diseñar estrategias de mitigación, asegurando que los cimientos de la arquitectura sean resilientes frente a escenarios de error.

<p align="center">
<img align="center" src="https://i.imgur.com/P0w4P91.jpeg" alt="Hotspots" style="height: auto;"></p>

## 2.5. Ubiquitous Language

En esta sección se define el Ubiquitous Language del proyecto, el cual consiste en un conjunto de términos y conceptos clave utilizados dentro del dominio de la solución propuesta. Este lenguaje común permite que todos los miembros del equipo y stakeholders compartan una misma comprensión del problema y de la solución, evitando ambigüedades en la comunicación.

| Ubiquitous Term                                | Definition of Functional Domain                                                                                                                       |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Resident (Residente)**                       | Persona que vive en el edificio y utiliza la aplicación móvil para registrar visitas y recibir notificaciones sobre la llegada de visitantes.         |
| **Doorman (Portero)**                         | Persona encargada de la portería que valida la identidad de los visitantes y controla el acceso al edificio mediante el sistema web.                  |
| **Visitor (Visitante)**                        | Persona externa al edificio que desea ingresar y cuyos datos son previamente registrados por el residente o capturados por el sistema.                |
| **Visit (Visita)**                             | Registro creado por el residente que contiene la información de un visitante esperado, como nombre, documento de identidad y departamento de destino. |
| **Visit Request (Solicitud de visita)**        | Evento generado cuando un visitante llega al edificio y es detectado por el sistema, iniciando el proceso de validación.                              |
| **Access Validation (Validación de acceso)**   | Proceso en el cual el conserje verifica la identidad del visitante utilizando la información registrada y la evidencia capturada (foto y audio).      |
| **Access Decision (Decisión de acceso)**       | Resultado del proceso de validación, donde se determina si el visitante es aprobado o rechazado para ingresar al edificio.                            |
| **Access Record (Registro de acceso)**         | Información almacenada sobre la visita, incluyendo hora, estado (aprobado o rechazado), evidencia y departamento asociado.                            |
| **Notification (Notificación)**                | Alerta enviada al residente para informarle sobre la llegada de un visitante o el estado de su solicitud de acceso.                                   |
| **Visitor Evidence (Evidencia del visitante)** | Conjunto de datos capturados por el sistema al momento de la llegada del visitante, incluyendo fotografía y audio.                                    |
| **Motion Detection (Detección de movimiento)** | Evento que ocurre cuando el sensor identifica la presencia de una persona frente al dispositivo.                                                      |
| **Entry Point (Punto de acceso)**              | Ubicación física donde se encuentra el dispositivo de captura (puerta o ingreso del edificio).                                                        |
| **Door Status (Estado de la puerta)**          | Condición actual de la puerta de acceso (abierta o cerrada), monitoreada por el sistema.                                                              |
| **Access Log (Historial de accesos)**          | Registro histórico de todas las visitas procesadas, incluyendo detalles del visitante y decisiones de acceso.                                         |
| **User Profile (Perfil de usuario)**           | Información personal del usuario (residente o conserje) dentro del sistema.                                                                           |
| **Apartment (Departamento)**                   | Unidad habitacional dentro del edificio asociada a un residente y utilizada para dirigir las visitas.                                                 |
| **Visit Detail (Detalle de visita)**           | Información completa de una visita específica, incluyendo datos del visitante, evidencia y estado de acceso.                                          |
| **Approval (Aprobación)**                      | Acción mediante la cual se permite el ingreso del visitante al edificio.                                                                              |
| **Rejection (Rechazo)**                        | Acción mediante la cual se niega el ingreso del visitante al edificio.                                                                                |
| **Visit History (Historial de visitas)**       | Lista de visitas asociadas a un residente o gestionadas por el conserje.                                                                              |

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. User Stories

| Epic ID  | Título  |
| :---: | :---: |
| EP01  | Registro y autenticación de usuarios |
| EP02  | Gestión de visitas |
| EP03  | Captura de eventos del visitante |
| EP04  | Validación y control de acceso |
| EP05  | Notificaciones al usuario |
| EP06  | Monitoreo e historial de visitas |
| EP07  | Seguridad del sistema |
| EP08  | Landing Page |

| N° | ID | Título | Descripción Detallada | Criterios de Aceptación (Escenarios Dado que-When-Then) | Epic | Puntos |
| :--- | :--- | :--- | :--- | :--- | :---: | :---: |
| 1 | **US01** | Registrarse como residente | **Como** residente, **quiero** registrarme en el sistema, **para** gestionar mis visitas autónomamente. | **E1: Registro exitoso** Dado que el usuario ingresa datos válidos, Cuando pulsa registrar, Entonces se crea el perfil. <br> **E2: Validación de datos** Dado que datos incompletos, Cuando intenta registrar, Entonces el sistema muestra error de validación. | 1 | 3 |
| 2 | **US02** | Registrarse como Portero | **Como** Portero, **quiero** crear una cuenta profesional, **para** acceder al panel de control web. | **E1: Alta de portero** Dado que datos profesionales válidos, Cuando pulsa crear cuenta, Entonces se asigna rol Portero. <br> **E2: Correo duplicado** Dado que correo ya registrado, Cuando intenta crear cuenta, Entonces el sistema deniega el registro. | 1 | 3 |
| 3 | **US03** | Iniciar sesión | **Como** usuario, **quiero** ingresar con mis credenciales, **para** acceder a mis funciones. | **E1: Inicio correcto** Dado que correo y clave correctos, Cuando pulsa entrar, Entonces el sistema inicia sesión. <br> **E2: Credenciales inválidas** Dado que clave incorrecta, Cuando intenta entrar, Entonces el sistema bloquea el acceso. | 1 | 2 |
| 4 | **US04** | Cerrar sesión | **Como** usuario, **quiero** finalizar mi sesión, **para** proteger mi información. | **E1: Cierre exitoso** Dado que sesión activa, Cuando pulsa cerrar, Entonces el sistema invalida el token. <br> **E2: Acceso tras cierre** Dado que sesión cerrada, Cuando intenta volver atrás, Entonces el sistema redirige al login. | 1 | 1 |
| 5 | **US05** | Editar perfil | **Como** usuario, **quiero** actualizar mis datos, **para** mantener mi contacto vigente. | **E1: Actualización de perfil** Dado que nuevos datos válidos, Cuando guarda cambios, Entonces el perfil se actualiza en la BD. <br> **E2: Formato inválido** Dado que formato de correo inválido, Cuando intenta guardar, Entonces el sistema rechaza el cambio. | 1 | 2 |
| 6 | **US06** | Registrar visita | **Como** residente, **quiero** pre-registrar una visita, **para** agilizar el ingreso. | **E1: Registro de visita** Dado que datos de visita válidos, Cuando registra, Entonces se crea el registro vinculado al depto. <br> **E2: DNI vacío** Dado que DNI vacío, Cuando intenta registrar, Entonces el sistema impide la creación. | 2 | 3 |
| 7 | **US07** | Verificar visitante | **Como** Portero, **quiero** comparar datos del visitante, **para** confirmar su identidad. | **E1: Verificación correcta** Dado que DNI en base de datos, Cuando el portero consulta, Entonces el sistema confirma registro. <br> **E2: Registro no encontrado** Dado que DNI no registrado, Cuando el portero consulta, Entonces el sistema sugiere registro manual. | 2 | 3 |
| 8 | **US08** | Asociación automática | **Como** Developer, **quiero** vincular visita a departamento, **para** trazabilidad. | **E1: Asociación por sesión** Dado que sesión de residente X, Cuando crea visita, Entonces el sistema inserta el ID del depto X. <br> **E2: Sesión caída** Dado que sesión caída, Cuando intenta asociar, Entonces el sistema lanza error de autenticación. | 2 | 2 |
| 9 | **US09** | Gestionar visitas | **Como** residente, **quiero** editar o borrar visitas, **para** corregir errores. | **E1: Edición pendiente** Dado que visita pendiente, Cuando edita datos, Entonces los cambios se reflejan en tiempo real. <br> **E2: Bloqueo de borrado** Dado que visita ya procesada, Cuando intenta borrar, Entonces el sistema bloquea la acción. | 2 | 3 |
| 10 | **US10** | Activar cámara IoT | **Como** Portero, **quiero** activación por sensor, **para** monitoreo automático. | **E1: Activación por movimiento** Dado que sensor PIR detecta movimiento, Cuando se activa, Entonces la cámara inicia el stream. <br> **E2: Modo nocturno** Dado que baja luz, Cuando se activa, Entonces el sistema enciende el modo nocturno. | 3 | 5 |
| 11 | **US11** | Capturar imagen | **Como** Portero, **quiero** una fotografía, **para** evidencia visual del ingreso. | **E1: Captura de foto** Dado que presencia detectada, Cuando el sistema captura, Entonces la foto se sube al Cloud. <br> **E2: Falla de cámara** Dado que error de cámara, Cuando intenta capturar, Entonces el sistema notifica fallo al hardware. | 3 | 5 |
| 12 | **US12** | Grabar audio | **Como** Portero, **quiero** audio del ingreso, **para** contexto de seguridad. | **E1: Grabación iniciada** Dado que timbre activado, Cuando graba, Entonces se genera un archivo .mp3 de 5 segundos. <br> **E2: Micrófono silenciado** Dado que micrófono silenciado, Cuando inicia evento, Entonces el sistema muestra alerta de silencio. | 3 | 5 |
| 13 | **US13** | Transmitir al servidor | **Como** Developer, **quiero** envío automático, **para** disponibilidad inmediata. | **E1: Envío a API** Dado que paquete multimedia listo, Cuando finaliza evento, Entonces se transmite vía REST API. <br> **E2: Cola local** Dado que pérdida de Wi-Fi, Cuando intenta enviar, Entonces el sistema encola los datos localmente. | 3 | 5 |
| 14 | **US14** | Asociar multimedia | **Como** Portero, **quiero** multimedia ligado al registro, **para** auditoría. | **E1: Vinculación de archivos** Dado que ID de visita activo, Cuando recibe multimedia, Entonces el sistema vincula los archivos. <br> **E2: Reenvío requerido** Dado que archivo corrupto, Cuando asocia, Entonces el sistema pide reenvío desde el IoT. | 3 | 3 |
| 15 | **US15** | Visualizar espera | **Como** Portero, **quiero** lista en tiempo real, **para** organizar la atención. | **E1: Cola FIFO** Dado que eventos entrantes, Cuando el portero mira el panel, Entonces se ven en orden FIFO. <br> **E2: Sin eventos** Dado que lista vacía, Cuando no hay eventos, Entonces se muestra mensaje "Sin visitas en espera". | 4 | 3 |
| 16 | **US16** | Visualizar foto | **Como** Portero/Residente, **quiero** ver la foto, **para** identificar al visitante. | **E1: Vista de imagen** Dado que foto almacenada, Cuando abre detalle, Entonces la imagen se despliega en HD. <br> **E2: Imagen por defecto** Dado que link roto, Cuando intenta abrir, Entonces el sistema muestra imagen por defecto. | 4 | 2 |
| 17 | **US17** | Reproducir audio | **Como** Portero/Residente, **quiero** oír el audio, **para** verificar la declaración. | **E1: Reproducción completa** Dado que audio grabado, Cuando pulsa play, Entonces se reproduce el sonido completo. <br> **E2: Error de formato** Dado que error de códec, Cuando intenta oír, Entonces el sistema lanza alerta de formato. | 4 | 2 |
| 18 | **US18** | Comparar datos | **Como** Developer, **quiero** match de DNI automático, **para** reducir carga. | **E1: Coincidencia encontrada** Dado que DNI capturado igual a DNI pre-registrado, Cuando compara, Entonces marca como "Match". <br> **E2: Sin coincidencia** Dado que DNI no registrado, Cuando compara, Entonces marca como "Desconocido". | 4 | 5 |
| 19 | **US19** | Registrar acceso OK | **Como** Developer, **quiero** log de acceso, **para** trazabilidad. | **E1: Acceso concedido** Dado que aprobación del residente, Cuando se procesa, Entonces se crea log "Acceso Concedido". <br> **E2: Reintento de log** Dado que error en BD, Cuando intenta grabar log, Entonces el sistema reintenta la operación. | 4 | 3 |
| 20 | **US20** | Registrar rechazo | **Como** Developer, **quiero** log de denegación, **para** seguridad. | **E1: Acceso denegado** Dado que rechazo del residente, Cuando se procesa, Entonces se guarda log "Acceso Denegado". <br> **E2: Motivo del rechazo** Dado que rechazo manual de portero, Cuando guarda, Entonces incluye motivo del rechazo. | 4 | 3 |
| 21 | **US21** | Sincronizar decisión | **Como** Portero, **quiero** ver decisión del residente, **para** abrir puerta. | **E1: Aprobación en app** Dado que residente acepta en App, Cuando el portero mira web, Entonces el estado cambia a Verde. <br> **E2: Rechazo en app** Dado que residente rechaza en App, Cuando el portero mira web, Entonces el estado cambia a Rojo. | 4 | 3 |
| 22 | **US22** | Enviar Notificación | **Como** Developer, **quiero** Push Notifications, **para** alertar al residente. | **E1: Notificación enviada** Dado que visitante para depto 101, Cuando el IoT timbra, Entonces el móvil 101 recibe notificación. <br> **E2: Reintento FCM** Dado que residente offline, Cuando envía push, Entonces el sistema reintenta vía Firebase FCM. | 5 | 5 |
| 23 | **US23** | Datos en App | **Como** residente, **quiero** ver DNI/Nombre en alerta, **para** saber quién es. | **E1: Datos visibles** Dado que datos disponibles, Cuando recibe alerta, Entonces el cuerpo del mensaje muestra el DNI. <br> **E2: Sin DNI** Dado que datos nulos, Cuando recibe alerta, Entonces el mensaje indica "Visitante sin DNI". | 5 | 2 |
| 24 | **US24** | Foto en App | **Como** residente, **quiero** ver la foto en la App, **para** seguridad. | **E1: Thumbnail en alerta** Dado que foto en Cloud, Cuando abre notificación, Entonces se muestra el thumbnail en la alerta. <br> **E2: Recarga manual** Dado que fallo de red, Cuando intenta ver foto, Entonces el sistema muestra botón "Recargar". | 5 | 2 |
| 25 | **US25** | Log de visualización | **Como** Developer, **quiero** registro de lectura, **para** auditoría. | **E1: Lectura registrada** Dado que notificación abierta, Cuando el usuario pulsa, Entonces se guarda fecha y hora de lectura. <br> **E2: Evento no atendido** Dado que notificación ignorada, Cuando pasan 5 min, Entonces el log marca "No atendida". | 5 | 2 |
| 26 | **US26** | Historial residente | **Como** residente, **quiero** ver mis alertas pasadas, **para** control personal. | **E1: Historial activo** Dado que historial activo, Cuando el usuario abre lista, Entonces se muestran eventos del mes. <br> **E2: Historial vacío** Dado que historial vacío, Cuando consulta, Entonces el sistema muestra "Sin registros". | 5 | 3 |
| 27 | **US27** | Detalle completo | **Como** residente, **quiero** evidencia total, **para** decidir mejor. | **E1: Vista detallada** Dado que vista detallada, Cuando usuario entra, Entonces ve foto, audio y datos de una vez. <br> **E2: Carga pendiente** Dado que multimedia no cargada, Cuando entra, Entonces el sistema muestra spinners de carga. | 5 | 2 |
| 28 | **US28** | Acciones App | **Como** residente, **quiero** botones Aprobar/Rechazar, **para** abrir remoto. | **E1: Apertura remota** Dado que botón Aprobar presionado, Cuando procesa, Entonces el hardware activa el relé de puerta. <br> **E2: Cierre del evento** Dado que botón Rechazar presionado, Cuando procesa, Entonces se cierra el evento en portería. | 5 | 3 |
| 29 | **US29** | Detectar presencia | **Como** Portero, **quiero** saber si hay gente en puerta, **para** atención proactiva. | **E1: Presencia detectada** Dado que sensor detecta persona, Cuando supera 10 seg, Entonces la web marca "Gente en puerta". <br> **E2: Puerta libre** Dado que cese de movimiento, Cuando pasa tiempo, Entonces el estado vuelve a "Puerta Libre". | 6 | 5 |
| 30 | **US30** | Estado de puerta | **Como** Portero, **quiero** saber si puerta está abierta, **para** seguridad. | **E1: Alerta por apertura** Dado que contacto magnético abierto, Cuando se rompe el circuito, Entonces la web muestra "ALERTA". <br> **E2: Estado seguro** Dado que contacto cerrado, Cuando está normal, Entonces se muestra icono de candado cerrado. | 6 | 3 |
| 31 | **US31** | Logs de hardware | **Como** administrador, **quiero** auditoría de puerta física, **para** seguridad. | **E1: Apertura registrada** Dado que apertura física, Cuando ocurre el evento, Entonces se guarda log con ID de dispositivo. <br> **E2: Cierre registrado** Dado que cierre físico, Cuando ocurre el evento, Entonces se guarda log de tiempo de apertura. | 6 | 3 |
| 32 | **US32** | Historial portería | **Como** Portero, **quiero** ver todas las visitas, **para** administración. | **E1: Filtrado por fecha** Dado que búsqueda por fecha, Cuando el portero filtra, Entonces se muestran todas las visitas del día. <br> **E2: Filtrado por residente** Dado que búsqueda por residente, Cuando filtra, Entonces muestra visitas a ese departamento. | 6 | 3 |
| 33 | **US33** | Modificar clave | **Como** residente, **quiero** cambiar mis credenciales, **para** protección. | **E1: Cambio de clave** Dado que clave antigua correcta, Cuando cambia clave, Entonces se actualiza el hash en BD. <br> **E2: Clave incorrecta** Dado que clave antigua incorrecta, Cuando intenta cambiar, Entonces el sistema bloquea el cambio. | 7 | 5 |
| 34 | **US34** | Recuperar cuenta | **Como** residente, **quiero** resetear clave por email, **para** recuperar acceso. | **E1: Token enviado** Dado que correo registrado, Cuando solicita reset, Entonces el sistema envía token al email. <br> **E2: Token vencido** Dado que token expirado, Cuando intenta usarlo, Entonces el sistema deniega el cambio de clave. | 7 | 5 |
| 35 | **US35** | Hashing BCrypt | **Como** Developer, **quiero** encriptar claves, **para** seguridad de datos. | **E1: Hash seguro** Dado que registro de usuario, Cuando guarda clave, Entonces el sistema aplica BCrypt con salt. <br> **E2: Claves ilegibles** Dado que intento de lectura BD, Cuando se mira tabla, Entonces las claves son ilegibles. | 7 | 3 |
| 36 | **US36** | Roles y Permisos | **Como** Developer, **quiero** validación RBAC, **para** proteger recursos. | **E1: Acceso restringido** Dado que residente logueado, Cuando intenta entrar a panel web, Entonces el sistema da Error 403. <br> **E2: Permiso válido** Dado que portero logueado, Cuando intenta registrar visita ajena, Entonces el sistema lo permite. | 7 | 5 |
| 37 | **US37** | Visualizar información | **Como** interesado, **quiero** ver el propósito en la Landing, **para** conocer NexBell. | **E1: Presentación inicial** Dado que acceso a Landing Page, Cuando carga la web, Entonces visualiza el eslogan y objetivo. <br> **E2: Descripción IoT** Dado que scroll hacia abajo, Cuando navega, Entonces encuentra la descripción de la seguridad IoT. | 8 | 3 |
| 38 | **US38** | Visualizar funciones | **Como** interesado, **quiero** conocer funciones web, **para** entender el flujo. | **E1: Lista de funciones** Dado que sección de funciones, Cuando el usuario entra, Entonces ve lista de captura y alertas. <br> **E2: Detalle funcional** Dado que clic en ícono funcional, Cuando interactúa, Entonces se despliega la descripción técnica. | 8 | 2 |
| 39 | **US39** | Visualizar beneficios | **Como** interesado, **quiero** ver ventajas principales, **para** valor agregado. | **E1: Beneficios visibles** Dado que sección beneficios, Cuando revisa texto, Entonces visualiza ahorro de tiempo y seguridad. <br> **E2: Comparativa clara** Dado que sección comparativa, Cuando lee, Entonces entiende la diferencia con sistemas clásicos. | 8 | 2 |
| 40 | **US40** | Visualizar contacto | **Como** interesado, **quiero** ver datos de contacto, **para** comunicación técnica. | **E1: Datos de soporte** Dado que llegada al footer, Cuando busca soporte, Entonces visualiza correos y redes sociales. <br> **E2: Confirmación de envío** Dado que formulario contacto, Cuando envía mensaje, Entonces recibe confirmación de recepción. | 8 | 1 |
| 41 | **US41** | Navegar entre secciones | **Como** interesado, **quiero** moverme fácilmente, **para** acceso sin fricciones. | **E1: Inicio del sitio** Dado que clic en menú superior, Cuando pulsa "Inicio", Entonces el navegador hace scroll al tope. <br> **E2: Salto a beneficios** Dado que clic en "Beneficios", Cuando pulsa, Entonces el navegador se desliza a la sección central. | 8 | 2 |

## 3.2. Impact Mapping

El Impact Mapping es la técnica de planificación estratégica que hemos adoptado en Nexora para asegurar que cada esfuerzo de desarrollo en NexBell esté directamente vinculado a un objetivo de negocio tangible. Esta metodología nos permite evitar el "desperdicio" de funciones (bloatware) y garantiza que la tecnología IoT implementada responda a necesidades reales del mercado residencial en Lima.

Nuestra estructura de Impact Mapping se desglosa en cuatro niveles fundamentales:

 - **Business Goal (¿Por qué?):** Es el punto de partida que define el éxito para Nexora. En este caso, el objetivo principal es modernizar la seguridad residencial reduciendo en un 25% los costos de mantenimiento y mejorando la eficiencia operativa en los edificios piloto mediante la digitalización de accesos.

 - **Personas (¿Quién?):** Identificamos a los actores cuyo comportamiento queremos influenciar. Esto incluye a los residentes (que necesitan comodidad y seguridad), al personal de conserjería (que busca agilizar su trabajo diario) y a las juntas de propietarios (que toman las decisiones financieras y de gestión).

 - **Impacts (¿Cómo?):** Describimos los cambios de conducta que esperamos ver en nuestros actores. Por ejemplo: que el conserje abandone el registro manual en papel, que el residente valide visitas instantáneamente desde su smartphone y que la administración tenga trazabilidad total de los eventos de seguridad.

 - **Deliverables (¿Qué?):** Son las soluciones técnicas que desarrollaremos para lograr los impactos deseados. Aquí se incluyen el dispositivo IoT NexBell, la aplicación móvil de notificaciones y el Dashboard Web para administración, todos diseñados bajo un modelo escalable y de bajo costo de instalación.

Al alinear estos cuatro niveles, el Impact Mapping de NexBell actúa como un filtro crítico: solo aquellas funcionalidades que demuestren un impacto directo en la seguridad y ahorro de los residentes son priorizadas en nuestro flujo de trabajo.

<p align="center">
<img src="https://i.imgur.com/KUvSUPF.png" alt="PB" width="1000">
</p>

## 3.3. Product Backlog

El Product Backlog de Nexora representa el inventario dinámico y priorizado de todas las funcionalidades, mejoras y requisitos técnicos necesarios para consolidar a NexBell como la solución líder en videoportería inteligente. Este documento no solo sirve como una lista de tareas, sino como la hoja de ruta estratégica que alinea el desarrollo tecnológico con las necesidades críticas de nuestros usuarios: residentes, porteros y administradores.

***Product Backlog de Nexora***
<p align="center">
<img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1777057982/TRELLO_zeiz9v.jpg" alt="PB" width="1000">
</p>

***Nota*** Elaboración propia en Trello. 

| N | Story ID | Title | Description | Story Points |
| ----- | :---- | :---- | :---- | :---- |
| 1 | US37 | Visualizar información general del sistema | Como persona interesada, quiero visualizar información general del sistema en la página principal, para comprender el propósito de la solución y cómo mejora el control de acceso de visitantes en edificios residenciales. | 2 |
| 2 | US41 | Navegar entre secciones informativas | Como la persona interesada, quiero navegar entre las diferentes secciones de la página web, para acceder fácilmente a la información del sistema. | 2 |
| 3 | US38 | Visualizar funcionalidades principales | Como la persona interesada, quiero conocer las funcionalidades principales del sistema, para entender cómo se realiza el registro, validación y monitoreo de visitantes. | 2 |
| 4 | US39 | Visualizar beneficios del sistema | Como la persona interesada, quiero visualizar los beneficios del sistema, para comprender el valor que ofrece a residentes y personal del edificio. | 2 |
| 5 | US40 | Visualizar información de contacto | Como la persona interesada, quiero visualizar información de contacto del proyecto, para poder comunicarme con el equipo responsable del sistema. | 1 |
| 6 | US10 | Activar cámara automáticamente | Como Portero, quiero que la cámara del dispositivo IoT se active automáticamente al detectar presencia, para agilizar el inicio del proceso de validación de acceso sin necesidad de activación manual. | 5 |
| 7 | US11 | Capturar imagen del visitante | Como Portero, quiero recibir una fotografía clara de la persona que se encuentra en el ingreso, para contar con información visual del visitante que facilite el proceso de validación y la decisión de acceso. | 5 |
| 8 | TS13 | Transmitir datos del evento al servidor central | Como Developer, quiero que el dispositivo IoT transmita automáticamente al servidor los datos capturados del visitante, para que el sistema registre un nuevo evento de visita disponible en tiempo real para el Portero. | 5 |
| 9 | US12 | Grabar audio del visitante | Como Portero, quiero que el sistema capture el audio del entorno durante el proceso de verificación de identidad, para obtener mayor contexto sonoro y mejorar la precisión de la validación de acceso. | 5 |
| 10 | US14 | Asociar captura a una visita | Como Portero, quiero que la información del visitante se vincule automáticamente a los datos de la visita registrada, para consultar el historial de visitas de manera íntegra y organizada. | 3 |
| 11 | US15 | Visualizar visitantes en espera | Como Portero, quiero visualizar en tiempo real una lista de visitantes que se encuentran en espera de validación, para poder gestionar el orden de atención y tomar decisiones de acceso de manera organizada. | 3 |
| 12 | US16 | Visualizar foto del visitante | Como Portero o residente, quiero visualizar la imagen capturada del visitante asociada a la solicitud de acceso, para facilitar la identificación visual antes de tomar una decisión. | 2 |
| 13 | TS18 | Comparar datos del visitante con visitas registradas | Como Developer, quiero que el sistema compare los datos capturados del visitante contra las visitas previamente registradas, para clasificar el evento y asistir al Portero en la validación de acceso. | 5 |
| 14 | US21 | Sincronizar decisión del residente sobre una visita | Como Portero, quiero que el sistema refleje automáticamente la decisión tomada por el residente sobre una visita, para poder actuar sobre el acceso sin necesidad de comunicación externa. | 3 |
| 15 | TS19 | Registrar acceso aprobado de visitante | Como Developer, quiero que el sistema genere automáticamente un registro de acceso cuando un visitante es autorizado, para mantener un historial confiable con trazabilidad completa del evento. | 3 |
| 16 | TS20 | Registrar intento de acceso rechazado | Como Developer, quiero que el sistema registre los eventos de acceso rechazado junto con su evidencia, para mantener trazabilidad de los intentos no autorizados en el historial del edificio. | 3 |
| 17 | US17 | Reproducir audio del visitante | Como Portero o residente, quiero reproducir el audio capturado del visitante durante el evento de ingreso, para escuchar la información proporcionada y apoyar el proceso de validación manual. | 2 |
| 18 | TS22 | Generar y enviar notificación de llegada al residente | Como Developer, quiero que el sistema genere y envíe automáticamente una notificación al residente cuando se registra la llegada de un visitante, para que pueda tomar una decisión de acceso de manera oportuna. | 5 |
| 19 | US23 | Mostrar datos del visitante | Como residente, quiero visualizar la información básica del visitante notificado, para poder identificar rápidamente a la persona que solicita acceso. | 2 |
| 20 | US24 | Mostrar foto del visitante | Como residente, quiero visualizar la imagen del visitante capturada por el sistema, para poder identificarlo visualmente antes de tomar una decisión sobre su acceso. | 2 |
| 21 | US28 | Permitir aprobar o rechazar visita | Como residente, quiero poder aprobar o rechazar una visita, para decidir si se permite o no el ingreso del visitante al edificio. | 3 |
| 22 | US27 | Permitir visualizar detalle del visitante | Como residente, quiero acceder al detalle completo de la visita, para contar con mayor información del visitante antes de tomar una decisión sobre su acceso. | 2 |
| 23 | TS25 | Registrar recepción de notificación por el residente | Como Developer, quiero que el sistema registre el momento en que el residente accede a una notificación de visita, para mantener trazabilidad del estado de atención de cada evento. | 2 |
| 24 | US26 | Visualizar historial de notificaciones | Como residente, quiero acceder a un historial de notificaciones recibidas, para poder revisar eventos pasados relacionados con visitas y mantener un control personal. | 3 |
| 25 | US06 | Registrar una visita | Como residente, quiero registrar los datos de una visita en el sistema, para que el Portero tenga la información anticipada y pueda gestionar el ingreso del visitante. | 3 |
| 26 | TS08 | Asociar visita a departamento automáticamente | Como Developer, quiero que el sistema asocie automáticamente cada visita al departamento del residente que la registró, para garantizar la correcta identificación del destino del visitante en el historial. | 2 |
| 27 | US07 | Ingresar y verificar datos del visitante | Como Portero, quiero verificar la información del visitante utilizando los datos previamente registrados en el sistema, para confirmar su identidad antes de permitir el acceso. | 3 |
| 28 | US09 | Gestionar visita registrada | Como residente, quiero poder editar o eliminar una visita registrada antes de su llegada, para mantener la información actualizada o evitar confusiones si el visitante ya no asistirá. | 3 |
| 29 | US29 | Detectar presencia en la puerta | Como Portero, quiero que el sistema detecte automáticamente cuando una persona se encuentra frente a la puerta de ingreso, para poder atender oportunamente a los visitantes sin necesidad de estar físicamente en la entrada. | 5 |
| 30 | US32 | Visualizar historial de visitas | Como Portero, quiero que el sistema me permita visualizar un registro completo y organizado de todas las visitas (pendientes, aprobadas y rechazadas), para llevar un control claro y confiable de las personas que han ingresado o intentado ingresar al edificio. | 3 |
| 31 | US30 | Visualizar estado de la puerta | Como Portero, quiero visualizar en el sistema el estado actual de la puerta (abierta o cerrada), para poder garantizar el control de accesos y la seguridad del edificio en todo momento. | 3 |
| 32 | US31 | Registrar eventos de apertura y cierre de la puerta | Como administrador o residente, quiero que el sistema registre automáticamente los eventos de apertura y cierre de la puerta, para contar con un historial confiable que permita auditar los accesos al edificio. | 3 |
| 33 | US01 | Registrarse como residente | Como residente, quiero registrarme en el sistema proporcionando mis datos personales, credenciales y mi departamento asociado, para poder acceder a la aplicación móvil y gestionar el registro y seguimiento de mis visitas dentro del edificio. | 3 |
| 34 | US02 | Registrarse como Portero | Como Portero, quiero registrarme en el sistema proporcionando mis credenciales, para poder acceder al sistema web y gestionar la validación de visitantes. | 3 |
| 35 | US03 | Iniciar sesión en el sistema | Como usuario, quiero iniciar sesión en el sistema utilizando mis credenciales registradas, para acceder a las funcionalidades correspondientes a mi rol. | 2 |
| 36 | US04 | Cerrar sesión en el sistema | Como usuario, quiero cerrar sesión para finalizar mi acceso al sistema de forma segura. | 1 |
| 37 | US05 | Editar datos del perfil | Como usuario, quiero actualizar la información de mi perfil para mantener mis datos personales correctos y actualizados dentro del sistema. | 2 |
| 38 | TS36 | Validar sesiones y autorización en la plataforma | Como Developer, quiero implementar un mecanismo de validación de sesiones y autorización en cada solicitud del sistema, para garantizar que solo usuarios autenticados y autorizados puedan ejecutar acciones dentro de la plataforma. | 5 |
| 39 | TS35 | Proteger datos sensibles | Como Developer, quiero almacenar las contraseñas utilizando hashing seguro, para proteger la información de los usuarios. | 3 |
| 40 | US34 | Recuperar contraseña | Como residente, quiero recuperar el acceso a mi cuenta en caso de olvidar mi contraseña, para poder continuar utilizando el sistema sin perder mi información. | 5 |
| 41 | US33 | Modificar datos de autenticación | Como residente, quiero que el sistema me permita actualizar mis credenciales de acceso (nombre de usuario, contraseña y correo electrónico), para mantener la seguridad y vigencia de mi cuenta dentro de la plataforma. | 5 |

<hr>
<div style="page-break-after: always;"></div>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming
El Event Storming es una técnica colaborativa de modelado que facilita la identificación de eventos clave y requisitos del negocio. Esta herramienta permite diseñar arquitecturas robustas alineadas con el Domain-Driven Design (DDD), optimizando la visualización de flujos y estructuras de código. Para el desarrollo de este ejercicio, se empleó la plataforma Miro como entorno virtual para asegurar una colaboración eficiente.

##### Paso 1: Identificación de Eventos de Dominio (Domain Events)

En esta primera fase del taller, el equipo se enfocó en identificar los Eventos de Dominio, definidos como sucesos de relevancia que ocurren dentro del sistema y que se expresan invariablemente en tiempo pasado. El objetivo principal fue mapear de forma exhaustiva las interacciones y cambios de estado del negocio, tales como la detección de dispositivos IoT o la gestión de visitas, sin considerar aún restricciones técnicas. Este proceso permitió establecer una base compartida de conocimiento sobre el comportamiento esperado del software y definir el alcance inicial del ecosistema del proyecto.
<p align="center">
<img src="https://i.imgur.com/PjXqHN1.jpeg" alt="Step 1: Domain Events" width="1100">
</p>

##### Paso 2: Definición de Líneas de Tiempo (Timelines)

Una vez identificados los eventos de dominio, se procedió a organizarlos cronológicamente para establecer una narrativa lógica del sistema. En esta etapa, el equipo estructuró los eventos en líneas de tiempo, permitiendo identificar relaciones de causalidad, secuencias de procesos (como el flujo desde el inicio de sesión hasta el registro de una visita) y posibles ramificaciones en la lógica de negocio. Este ordenamiento lineal es fundamental para detectar lagunas de información o eventos faltantes, asegurando que el flujo de la aplicación sea coherente y cubra todos los escenarios de interacción del usuario y los dispositivos IoT.
<p align="center">
<img src="https://i.imgur.com/m5j7rxv.jpeg" alt="Step 2: Timelines" width="1100">
</p>

##### Paso 3: Identificación de Comandos (Commands)

En esta etapa, se integraron los Comandos, representados en color azul, los cuales actúan como los desencadenantes o intenciones que provocan la aparición de los eventos de dominio. Este paso permitió definir las acciones específicas que los usuarios o sistemas externos ejecutan. Al vincular cada comando con su respectivo evento, se logró modelar la interactividad del sistema y las decisiones que la lógica de negocio debe procesar. Esta definición es crucial para el posterior diseño de la API y los controladores, ya que establece los puntos de entrada de información y las peticiones que el sistema debe soportar.
<p align="center">
<img src="https://i.imgur.com/CoUeMmI.jpeg" alt="Step 3: Commands" width="1100">
</p>

##### Paso 4: Sistemas Externos (External Systems)
En esta fase se identificaron los servicios y plataformas de terceros que interactúan con nuestro sistema para completar flujos de negocio específicos. Mediante el uso de etiquetas de color rosado, se representaron dependencias críticas como Edge API para el control de hardware, Gmail para notificaciones y Niubiz para la gestión de pagos. Este mapeo permite delimitar las fronteras del sistema e identificar qué procesos dependen de la disponibilidad y respuesta de proveedores externos.
<p align="center">
<img src="https://i.imgur.com/OVIL5pC.jpeg" alt="Step 4: External Systems" width="1100">
</p>

##### Paso 5: Actores y Políticas (Actors & Policies)
En esta etapa final de modelado, se asignaron los Actores (como Residentes, Conserjes y Administradores) a sus respectivos comandos para definir roles y responsabilidades dentro del sistema. Paralelamente, se establecieron las Políticas (etiquetas de color lila), las cuales representan reglas de negocio automáticas. Esta integración permite visualizar tanto la interacción humana como la automatización de flujos.

<p align="center">
<img src="https://i.imgur.com/TGodYw9.jpeg" alt="Step 5: Actors & Policies" width="1100">
</p>

##### Paso 6: Puntos de Dolor (Pain Points)
Durante esta fase, se identificaron y señalaron las posibles debilidades, riesgos o cuellos de botella del sistema, representados mediante notas de color rojo. Este análisis crítico permitió detectar áreas de incertidumbre, como posibles fallos en la conectividad de los dispositivos IoT o riesgos en el procesamiento de pagos. La identificación temprana de estos Pain Points es fundamental en el proceso de ingeniería, ya que permite priorizar esfuerzos de desarrollo y diseñar mecanismos de contingencia para garantizar la resiliencia de la aplicación.

<p align="center">
<img src="https://i.imgur.com/toy1waW.jpeg" alt="Step 6: Pain Points" width="1100">
</p>

##### Paso 7: Modelos de Lectura (Read Models)
En esta etapa se definieron los Read Models, representados por las notas de color azul claro situadas al inicio de cada flujo. Estos modelos especifican la información o vistas de datos que el usuario requiere consultar antes de emitir un comando. Este paso es clave para el diseño de la interfaz de usuario, ya que establece qué datos deben ser recuperados de la base de datos y presentados de manera clara para facilitar la interacción con el sistema.

<p align="center">
<img src="https://i.imgur.com/5TDzQje.jpeg" alt="Step 7: Read Models" width="1100">
</p>

##### Paso 8: Puntos Pivotales (Pivotal Points)
Como cierre del taller, se identificaron los Pivotal Points, representados mediante líneas verticales que dividen secciones clave del flujo. Estos puntos marcan momentos de alta relevancia donde ocurre un cambio significativo en el estado del proceso o en el contexto de la operación. La identificación de estos hitos es crucial para la arquitectura de software, ya que actúan como indicadores naturales para definir los límites de los Bounded Contexts. Esto facilita la modularización del sistema, permitiendo que componentes como la gestión de accesos, el registro de visitas y el control de dispositivos IoT operen de manera independiente pero coordinada.

<p align="center">
<img src="https://i.imgur.com/gz8QJTH.jpeg" alt="Step 8: Pivotal Points" width="1100">
</p>

#### 4.1.1.1. Candidate Context Discovery
Con la base establecida en el Event Storming, se procedió a la fase de Candidate Context Discovery para definir los límites lógicos del sistema NexBell. El objetivo principal fue descomponer la complejidad de la solución de videoportero inteligente en Bounded Contexts preliminares, asegurando que cada módulo responda de manera eficiente a las necesidades de seguridad y gestión residencial.


##### Contexto Candidato 1: Identity and Access Management (IAM)
El primer contexto delimitado identificado es el Identity and Access Management (IAM). Este actúa como un componente transversal de seguridad encargado de gestionar el ciclo de vida de las identidades y los permisos de acceso para todos los actores del ecosistema NexBell.

<p align="center">
<img src="https://i.imgur.com/0qQWx0O.jpeg" alt="IAM BC" width="1100">
</p>

De acuerdo con el modelado realizado, este contexto agrupa las siguientes capacidades críticas:

- **Gestión y Modificación de Credenciales:** Centraliza la lógica para el cambio de contraseñas y actualización de correos electrónicos, garantizando que cualquier modificación sea validada y registrada de forma segura en la base de datos.
- **Recuperación de Accesos:** Gestiona los flujos de autoservicio para el restablecimiento de cuentas mediante la integración con servicios externos (Gmail) para el envío de tokens de recuperación con tiempo de expiración.
- **Control de Sesiones Activas:** Supervisa el estado de autenticación de los usuarios, permitiendo el inicio y cierre de sesiones de manera integrada con el resto de los módulos del sistema.
- **Almacenamiento Seguro:** Define las políticas de persistencia y protección de los datos sensibles de identidad, asegurando que la información de acceso sea tratada bajo estándares de seguridad robustos.

##### Contexto Candidato 2: Security (Core Domain)
El contexto de Security constituye el núcleo estratégico de la solución NexBell. Su propósito es arbitrar y validar todas las interacciones de control de acceso físico, garantizando que cada apertura de puerta o flujo de comunicación cumpla con las reglas de negocio establecidas para el entorno residencial.

<p align="center">
<img src="https://i.imgur.com/Wk3ZVPt.jpeg" alt="Security BC" width="1100">
</p>

Basado en el modelado, este contexto centraliza las siguientes responsabilidades:

- **Gestión de Permisos y Autorización:** Define y valida las facultades de cada actor. Mientras que el Conserje actúa como un supervisor con capacidades de gestión global, los Residentes poseen permisos específicos para el control de sus propios accesos y la autorización de sus visitas planificadas.
- **Gestión de Acceso Biométrico (Reconocimiento Facial):** Integra la lógica de validación de identidad mediante reconocimiento facial tanto para residentes como para conserjes y visitas. Este componente es crítico para automatizar ingresos y elevar los estándares de seguridad sin sacrificar la agilidad.
- **Respuesta e Interacción en Puerta:** Orquestra el flujo de eventos que ocurre ante la "Detección de visitante", vinculando las notificaciones en tiempo real, la verificación visual por cámara y la comunicación bidireccional entre el punto de acceso y el smartphone del usuario.
- **Control de Interfaces y Funciones Críticas:** Administra el acceso a funcionalidades de alto impacto, como la apertura remota de puertas a través de dispositivos IoT y la visualización del historial de ingresos, asegurando que solo los actores autorizados puedan consultar o activar estas operaciones.

##### Contexto Candidato 3: Audit
El contexto de Audit se define como el sistema de registro histórico y trazabilidad de interacciones sociales dentro del edificio. A diferencia de un log técnico, este módulo está centrado exclusivamente en la gestión de la información relativa al flujo de personas, proporcionando una base de datos auditable para residentes y administración.

<p align="center">
<img src="https://i.imgur.com/0AjeTvb.jpeg" alt="Audit BC" width="1100">
</p>

Según el modelado, sus responsabilidades principales incluyen:

- **Registro Integral de Visitas:** Centraliza la información de todos los tipos de ingresos: visitas planificadas por el residente, visitas atendidas en tiempo real y detección de visitantes no anunciados. Cada registro captura metadatos críticos como timestamps, acciones realizadas y el departamento destino.
- **Gestión del Historial de Visitas:** Permite la persistencia y consulta organizada de los eventos pasados. Este componente es esencial para que los residentes puedan revisar quién accedió a su hogar y en qué momento, fortaleciendo la confianza en el sistema.
- **Captura de Evidencia Multimedia:** Se encarga de vincular los eventos de visita con la captura de datos provenientes del hardware (como grabaciones de audio o fotos de visitantes), creando un expediente digital completo de cada interacción en la puerta.
- **Tratamiento de Información de Visita:** Gestiona el ciclo de vida de los datos de la visita (creación, edición de información pendiente y eliminación), asegurando que la cola de visitas se mantenga actualizada y sea veraz.

##### Contexto Candidato 4: Intercom
El contexto de Intercom representa la capa de mediación tecnológica entre el sistema y el hardware IoT. Su función principal es la gestión de señales físicas, la transmisión de flujos multimedia y el control de dispositivos de campo, operando con un nivel de granularidad más detallado que el de los registros administrativos.

<p align="center">
<img src="https://i.imgur.com/FFtwB5E.jpeg" alt="Intercom BC" width="1100">
</p>

De acuerdo con el análisis de flujos, este contexto integra las siguientes capacidades:

- **Control y Captura de Eventos de Hardware:** Gestiona la telemetría proveniente de sensores magnéticos y motores. A diferencia de otros módulos, este contexto registra acciones técnicas inmediatas (como "Apertura de puerta detectada" o "Estado de sensor verificado"), permitiendo una monitorización precisa del estado físico de los accesos.
- **Gestión de Comunicación en Tiempo Real:** Orquestra las "llamadas" y la transmisión de video entre el videoportero y los dispositivos de los residentes o conserjes. Este componente maneja la señalización necesaria para iniciar, mantener y finalizar la comunicación bidireccional.
- **Interfaz con Edge API:** Actúa como el cliente principal de los servicios de borde (Edge API), traduciendo los comandos de usuario en acciones físicas sobre el hardware y procesando las notificaciones emitidas por el timbre o los sensores de movimiento.
- **Visualización de Datos del Dispositivo IoT:** Proporciona los modelos de lectura necesarios para que los actores autorizados consulten el estado en vivo de los componentes electrónicos, asegurando que la infraestructura responda correctamente a las peticiones del sistema.

##### Contexto Candidato 5: Directory
El contexto de Directory funciona como el repositorio central de información organizativa y perfiles del condominio. Su propósito es estructurar la relación entre los usuarios y el entorno físico del edificio, sirviendo de base para la personalización y el contexto de las interacciones dentro de la plataforma NexBell.

<p align="center">
<img src="https://i.imgur.com/shTZAei.jpeg" alt="Intercom BC" width="1100">
</p>

De acuerdo con el modelado, este contexto gestiona las siguientes áreas:

- **Gestión de Perfiles de Usuario:** Almacena y permite la actualización de la información pública o de contacto de los residentes y conserjes. A diferencia del contexto IAM, este no maneja credenciales de acceso, sino la identidad social y profesional de los miembros de la comunidad.
- **Asociación de Unidades Habitacionales:** Contiene la lógica para vincular a cada residente con su departamento correspondiente. Esta estructura es esencial para que funciones externas, como el registro de visitas, puedan identificar correctamente el destino de un visitante.
- **Registro y Onboarding de Edificios:** Maneja el flujo inicial de contratación y creación del ecosistema digital del edificio, integrando pasarelas de pago (Niubiz) para la activación del servicio y la posterior creación masiva de cuentas de personal y residentes.
- **Almacenamiento de Información Organizativa:** Actúa como una "guía de perfiles" útil para la gestión interna, permitiendo que el sistema muestre datos claros sobre quién está a cargo de la portería o qué vecino ha emitido una solicitud, mejorando la trazabilidad operativa.

#### 4.1.1.2. Domain Message Flows Modelling
Tras definir los Bounded Contexts, se utilizó Domain Storytelling para modelar gráficamente la interacción y el flujo de mensajes entre ellos. Esta técnica transforma los procesos en narrativas dinámicas que validan la arquitectura de NexBell, asegurando que la colaboración entre actores y sistemas cumpla con los objetivos reales del negocio.

##### Escenario 1: Creación de cuentas de edificio inicial
Este escenario describe el flujo de orquestación entre los distintos contextos y actores durante el proceso de onboarding de un nuevo condominio en la plataforma NexBell. La narrativa visual evidencia cómo una acción administrativa desencadena una serie de colaboraciones automáticas para establecer la infraestructura lógica del edificio:

- **Inicio del Proceso:** El flujo comienza con el Administrador, quien realiza el registro del edificio y el pago de la suscripción a través de un sistema externo de verificación de pagos.
- **Colaboración entre Contextos:** Una vez confirmado el pago, el sistema interactúa con el contexto Directory para la generación automática de cuentas basadas en los datos del edificio. Posteriormente, se delega al contexto IAM el almacenamiento y asignación de las credenciales genéricas iniciales.
- **Interacción con los Usuarios Finales:** El Administrador distribuye estas credenciales a los Residentes y Conserjes, quienes acceden al panel de control para actualizar su información personal y personalizar sus claves de acceso.
- **Cierre del Flujo (Seguridad):** El proceso culmina en el contexto IAM mediante la encriptación de las nuevas credenciales y se comunica con el contexto Security para la asignación definitiva de permisos, dejando el sistema plenamente operativo para el nuevo edificio.
<p align="center">
<img src="https://i.imgur.com/u9ACqcK.jpeg" alt="1" width="1100">
</p>

##### Escenario 2: Registro de visita pendiente por residente
Este flujo de Domain Storytelling ilustra el proceso proactivo mediante el cual un residente autoriza de forma anticipada el ingreso de un tercero, asegurando que la información esté disponible para el personal de seguridad antes de la llegada del visitante.

- **Interacción Inicial:** El Residente inicia el flujo accediendo al formulario de registro en su panel de control, donde ingresa los datos de identificación del visitante.
- **Procesamiento y Persistencia:** Una vez enviado el formulario, la información viaja hacia el contexto Audit. Este componente es responsable de generar la "visita pendiente" en la cola de registros, actuando como la fuente de verdad única para los eventos de acceso planificados.
- **Sincronización en Tiempo Real:** Tras la creación del registro, el sistema emite automáticamente una notificación de actualización. Esta señal llega al panel de control del Conserje, quien visualiza el cambio en la lista de visitas pendientes.
- **Resultado Operativo:** El flujo concluye con la actualización de la interfaz de conserjería, permitiendo que el personal de seguridad esté debidamente informado y pueda agilizar la validación del visitante al momento de su llegada física al edificio.

<p align="center">
<img src="https://i.imgur.com/rDfGVZC.jpeg" alt="2" width="1100">
</p>

##### Escenario 3: Gestión de visita automática del sistema

Este diagrama de Domain Storytelling detalla el flujo de mayor complejidad técnica y valor operativo: la automatización del acceso mediante biometría. En este escenario, el sistema actúa de forma autónoma para validar y permitir el ingreso de un residente sin intervención humana.

* **Detección y Reconocimiento:** El flujo se dispara cuando el Residente es detectado por los sensores de movimiento. El contexto Intercom captura la señal y activa el reconocimiento facial, iniciando la verificación biométrica.
* **Validación de Identidad:** El mensaje se traslada al contexto Directory, donde el sistema compara la imagen capturada con la base de datos de rostros autorizados. Una vez confirmada la coincidencia, se emite una confirmación de identidad.
* **Autorización de Seguridad:** El contexto Security recibe la confirmación y verifica los permisos de apertura automática asociados a ese perfil. Al validar que el actor tiene las facultades necesarias, envía la orden de ejecución al sistema físico.
* **Ejecución y Cierre de Auditoría:** Finalmente, el sistema efectúa la apertura de la puerta automáticamente y envía un mensaje al contexto Audit. Este último genera un registro de acción automática, asegurando que el evento quede debidamente documentado con su respectiva marca de tiempo y tipo de acceso.

<p align="center">
<img src="https://i.imgur.com/UHzAL9r.jpeg" alt="3" width="1100">
</p>

##### Escenario 4: Aprobación de visita por conserje

Este escenario detalla el flujo de comunicación y control cuando un visitante no registrado llega al edificio, requiriendo la intervención del Conserje para validar su identidad y autorizar el acceso de manera remota.

* **Notificación y Comunicación:** El proceso inicia con la detección del visitante por los sensores magnéticos/movimiento. El contexto Intercom emite una notificación de timbre al personal de seguridad e inicia una llamada en tiempo real, permitiendo la comunicación bidireccional entre el conserje y el visitante.
* **Captura de Evidencia y Validación:** De forma paralela, el contexto Audit inicia la grabación de la interacción y envía la imagen capturada por la cámara al conserje. Este último verifica la identidad del visitante consultando la lista de visitas pendientes y la información proporcionada por el contexto Security.
* **Autorización y Ejecución:** Una vez validada la identidad a través del panel de control, el Conserje autoriza la apertura de la puerta. Esta instrucción es procesada por el contexto Audit para mantener la trazabilidad y ejecutada físicamente por el dispositivo IoT a través de sus actuadores (motores).
* **Registro Final:** El flujo concluye con el sistema registrando la interacción completa en la bitácora del contexto Audit, documentando tanto la identidad del visitante como la decisión tomada por el conserje, cerrando así el ciclo de seguridad.


<p align="center">
<img src="https://i.imgur.com/eF5T4jm.jpeg" alt="3" width="1100">
</p>

##### Escenario 5: Aprobación de visita por residente

Este escenario modela la interacción directa entre el visitante y el residente a través de la plataforma, permitiendo la gestión de accesos sin necesidad de intermediarios (conserjería). Representa el flujo de comunicación crítica y ejecución remota que define la experiencia de usuario de NexBell.

* **Notificación y Enlace Multimedia**: El flujo inicia con la detección del visitante, tras lo cual el contexto Intercom envía una notificación de timbre directamente al smartphone del Residente e inicia una comunicación de voz. Simultáneamente, el contexto Audit activa la grabación de la interacción y despacha la imagen del visitante hacia el terminal del usuario.
* **Validación de Identidad**: El Residente visualiza la imagen desde su panel de control y verifica la identidad del visitante contrastándola con la lista de visitas pendientes asociadas a su departamento, proceso gestionado bajo las reglas del contexto Audit.
* **Autorización de Seguridad**: Una vez confirmada la identidad, el sistema consulta al contexto Security para gestionar los permisos de acceso a la imagen y validar la facultad del residente para ejecutar la apertura.
* **Ejecución y Registro Final**: Tras la autorización del residente, el contexto Audit procesa la orden, lo que desencadena que el dispositivo IoT accione físicamente la apertura de la puerta. El proceso concluye con el sistema registrando la interacción completa en la bitácora de auditoría, garantizando la trazabilidad total del evento.

<p align="center">
<img src="https://i.imgur.com/vcgKHiQ.jpeg" alt="3" width="1100">
</p>

#### 4.1.1.3. Bounded Context Canvases

En esta sección se presentan los lienzos detallados para los cinco contextos candidatos identificados. Cada canvas actúa como un contrato estratégico que define la misión, el lenguaje ubicuo y las decisiones críticas de los módulos que integran la solución **NexBell**, asegurando la trazabilidad desde la portería física hasta el ecosistema digital de **Nexora**.

---

#### **1. Bounded Context: Identity and Access Management (IAM)**

Este contexto transversal de seguridad se encarga de gestionar el ciclo de vida de las identidades y los permisos de acceso lógico para todos los actores del sistema.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/1_hsvfpb" alt="Bounded Context Canvas IAM" width="1000">
</p>


**Explicación del Canvas:**
* **Propósito:** Centralizar la lógica de autenticación y autorización, garantizando procesos seguros de cambio de credenciales y recuperación de accesos mediante la integración con servicios externos como Gmail.
* **Decisiones de Negocio:** Encapsula las reglas de expiración de sesiones (Time-to-Live), las políticas de validación para el restablecimiento de cuentas y el registro seguro de modificaciones de identidad.

---

#### **2. Bounded Context: Security (Core Domain)**

Constituye el núcleo estratégico de NexBell. Su propósito es arbitrar y validar todas las interacciones de control de acceso físico en el entorno residencial.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/2_ignmpn" alt="Bounded Context Canvas Security" width="1000">
</p>


**Explicación del Canvas:**
* **Propósito:** Definir y validar los permisos de acceso basándose en reglas de negocio y **Reconocimiento Facial Biométrico**, gestionando la respuesta ante la detección de visitantes en tiempo real.
* **Decisiones de Negocio:** Determina las facultades de cada actor (Conserje vs. Residente), gestiona el flujo de escalamiento si un usuario es inalcanzable y procesa las anomalías detectadas por modelos de Machine Learning.

---

#### **3. Bounded Context: Audit**

Se define como el sistema de registro histórico y trazabilidad de interacciones sociales dentro del edificio, proporcionando una base de datos auditable para residentes y administración.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/3_m4bwp0" alt="Bounded Context Canvas Audit" width="1000">
</p>


**Explicación del Canvas:**
* **Propósito:** Centralizar la información de todos los ingresos (visitas planificadas y no anunciadas), vinculando los eventos con **Evidencia Multimedia** (audio y fotos) capturada por el hardware.
* **Decisiones de Negocio:** Define la política de retención de datos (Data Retention Policy), las reglas para vincular metadatos de hardware a unidades específicas y el tratamiento de la información de visitas pendientes.

---

#### **4. Bounded Context: Intercom**

Representa la capa de mediación tecnológica entre el sistema y el hardware IoT, gestionando señales físicas y flujos multimedia.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/4_te9aqc" alt="Bounded Context Canvas Intercom" width="1000">
</p>


**Explicación del Canvas:**
* **Propósito:** Gestionar la comunicación técnica y segura con el IoT Gateway, traduciendo señales de dispositivos físicos (sensores magnéticos) en eventos de software accionables.
* **Decisiones de Negocio:** Administra los intervalos de *Heartbeat* para los dispositivos de borde, la seguridad de las conexiones MQTT y la priorización del tráfico de video/audio en tiempo real a través de la Edge API.

---

#### **5. Bounded Context: Directory**

Funciona como el repositorio central de información organizativa y perfiles, estructurando la relación entre los usuarios y el entorno físico del edificio.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/5_kr1yac" alt="Bounded Context Canvas Directory" width="1000">
</p>


**Explicación del Canvas:**
* **Propósito:** Gestionar los perfiles de usuario y las asociaciones unívocas entre residentes y sus unidades habitacionales, sirviendo como base para la personalización de las interacciones.
* **Decisiones de Negocio:** Maneja el flujo de *onboarding* de nuevos edificios, la integración con pasarelas de pago y la estructura de perfiles sociales necesaria para la trazabilidad operativa de la comunidad.
 
### 4.1.2. Context Mapping

El Mapa de Contextos de **NexBell** define las fronteras de responsabilidad y las estrategias de integración entre los diferentes contextos acotados. Dado que el proyecto busca implementar un ecosistema analítico basado en Machine Learning para optimizar la gestión de inventarios y procesos de acceso, la estructura refleja un núcleo central de toma de decisiones que orquesta los servicios de soporte e infraestructura.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/f_auto,q_auto/12_fa9kd6" width="1000">
</p>

---

#### **Tabla de Relaciones de Contexto**

Esta tabla detalla la naturaleza técnica y organizacional de las integraciones en la solución.

| Desde (Upstream) | Hacia (Downstream) | Propósito | Patrón DDD | Contrato | Mensajes / Consultas | SLA / Notas |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Access Management** | **Notification Context** | Notificar al residente en tiempo real para la validación de visitas mediante la app móvil. | Upstream (OHS) / Downstream (CF) | Eventos de Dominio (JSON) | `VisitRegisteredEvent`, `AlertNotification` | Disponibilidad crítica; entrega inmediata (< 3s). |
| **Access Management** | **IoT Management** | Orquestar la apertura física de cerraduras y monitorear el estado de sensores de puerta. | Customer / Supplier | Published Language (Protobuf) | `UnlockDoorCommand`, `DeviceStatusQuery` | Latencia en hardware requerida < 1.5s. |
| **Access Management** | **Audit & Analytics** | Proveer flujos de datos para el ecosistema analítico basado en Machine Learning. | Upstream (OHS) / Downstream (CF) | Canonical Schema | `AccessAuthorizedEvent`, `EntryAnomalyDetected` | Almacenamiento persistente para entrenamiento de modelos. |

---

#### **Decisiones, Supuestos, Riesgos y Mitigaciones**

A continuación, se presentan las consideraciones estratégicas y técnicas que sustentan el diseño del mapa de contextos.

##### **1. Decisiones y Supuestos**
* **Abstracción de Hardware**: Se implementa un **Published Language (PL)** para que el dominio de acceso sea agnóstico al hardware físico, permitiendo integrar diversos protocolos IoT (MQTT/HTTP) sin modificar el núcleo del negocio.
* **Calidad de Datos Analíticos**: Se asume que el sistema de analítica requiere flujos de datos limpios y constantes de cada evento de acceso para cumplir con el objetivo de optimizar la gestión de recursos en el edificio.
* **Protección de Dominio (ACL)**: El contexto de Notificaciones utiliza una **Anti-Corruption Layer (ACL)** para proteger la lógica interna de **NexBell** ante cambios en las APIs externas de proveedores como Firebase o APNS.

##### **2. Riesgos y Mitigaciones**
* **Riesgo de Desincronización Física**: Posible inconsistencia entre el estado lógico de la aplicación y el estado real de la puerta por fallos de red.
    * **Mitigación**: Implementación de un flujo de confirmación obligatoria (*DoorUnlockedEvent*) y monitoreo de estado (*Heartbeat*) constante desde el IoT Gateway.
* **Riesgo de Latencia en Notificaciones**: El residente podría no recibir la alerta a tiempo debido a saturación en servicios de terceros.
    * **Mitigación**: Generación automática de códigos de respaldo y visualización de alertas en el dashboard del conserje para gestión manual.
* **Riesgo de Saturación Analítica**: El procesamiento masivo de eventos para Machine Learning podría degradar el rendimiento del sistema transaccional.
    * **Mitigación**: Uso de una arquitectura orientada a eventos (EDA) para procesar la analítica de forma asíncrona y aislada del flujo principal.
      
### 4.1.3. Software Architecture


#### 4.1.3.1. Software Architecture System Landscape Diagram

(*System Landscape*) proporciona una visión panorámica de alto nivel de todo el ecosistema de **NexBell**. Este diagrama ilustra cómo los diferentes actores (Residentes y Conserjes) interactúan con la solución y cómo el sistema se integra con servicios externos críticos y hardware IoT para garantizar la seguridad y eficiencia operativa del condominio.

<p align="center">
  <img src="https://i.imgur.com/B4LPo15.jpeg" alt="System Landscape Diagram - NexBell">
</p>


**Explicación del Diagrama:**

Este diagrama describe los límites del sistema y sus interdependencias estratégicas para la solución de **Nexora**:

1.  **Actores del Sistema:** Se identifican dos roles clave; el **Residente**, enfocado en la gestión de su unidad habitacional y validación de visitas desde su app, y el **Conserje**, encargado de la vigilancia, la gestión del directorio y la trazabilidad operativa global del edificio.
2.  **Sistemas Internos:** Representan los tres pilares de la arquitectura: la interfaz móvil del usuario (NexBell App), el panel administrativo web (Nexora Dashboard) y el **IoT Edge Gateway**, que actúa como el puente físico para el control de accesos y sensores.
3.  **Integraciones Externas:**
    * **Biometric AI Service:** Servicio fundamental para el reconocimiento facial que permite automatizar los ingresos de forma segura y ágil.
    * **Google Mail & Niubiz:** Servicios de soporte indispensables para la gestión de identidad (recuperación de cuentas) y la monetización del servicio (onboarding de nuevos edificios).
    * **Firebase / APNS:** Garantizan que las notificaciones de seguridad y alertas de visitas lleguen de forma instantánea al smartphone del residente, sin importar la marca del dispositivo.

**Decisiones de Arquitectura y Supuestos:**

| Decisión / Supuesto | Justificación Técnica |
| :--- | :--- |
| **Arquitectura de Borde (Edge):** El uso de un Gateway físico permite que el procesamiento de apertura y lectura de sensores sea local y rápido, minimizando la latencia en el punto de acceso. | Crítico para cumplir con los requerimientos de eficiencia operativa y garantizar la disponibilidad del sistema incluso con fluctuaciones de internet. |
| **Desacoplamiento de Notificaciones:** Uso de proveedores externos especializados (FCM/APNS). | Asegura que el envío de alertas sea altamente confiable y optimiza el consumo de batería en los dispositivos móviles de los usuarios al no mantener procesos en segundo plano innecesarios. |
| **Motor de IA Externo:** Integración vía API para biometría facial. | Permite a **Nexora** enfocarse en la lógica de negocio residencial y la experiencia de usuario, delegando la complejidad del procesamiento de imágenes a servicios de IA de alta precisión y escalabilidad. |

#### 4.1.3.2. Software Architecture Context Level Diagram

<p align="center">
<img src="https://imgur.com/RaYmJrq.png" alt="Context" width="1100">
</p>

<p align="center">
<img src="https://i.imgur.com/gQpmrNG.png" alt="Container" width="1100">
</p>

#### 4.1.3.3. Software Architecture Deployment Diagrams

El Diagrama de Despliegue describe la topología física y la infraestructura donde reside la solución **NexBell**. Se detalla la distribución de los artefactos de software en tres niveles clave: el dispositivo del usuario, la infraestructura local del edificio (*Edge*) y el ecosistema escalable en la nube de **Nexora**.

<p align="center">
  <img src="https://i.imgur.com/bvfbnD0.png" alt="Deployment Diagram - NexBell Solution">
</p>


**Explicación de la Infraestructura:**

1.  **Capa de Usuario (User Tier):** Las aplicaciones móviles y el panel administrativo interactúan directamente con los servicios de la nube. La aplicación móvil establece además una conexión de baja latencia con el hardware local para funciones críticas de video y audio.
2.  **Capa de Borde (Edge Tier - Edificio):** En cada condominio se despliega un **IoT Edge Gateway**. Este nodo procesa las señales de los sensores y ejecuta los comandos de apertura de forma local, garantizando la operatividad ante fallos de internet y sincronizándose asíncronamente con la nube.
3.  **Capa de Nube (Cloud Tier):** Orquesta la inteligencia de todo el ecosistema. Contiene los microservicios core para la gestión de residentes, el motor de biometría facial y la base de datos centralizada que alimenta el sistema analítico.

**Decisiones de Infraestructura:**

| Componente | Tecnología | Justificación Técnica |
| :--- | :--- | :--- |
| **Capa de Usuario** | HTTPS / JWT | Garantiza que las comunicaciones entre el smartphone y la nube sean seguras y que cada petición esté debidamente autorizada mediante tokens de sesión. |
| **Edge Computing** | Gateway Local | Permite que las operaciones críticas, como la apertura de puertas, ocurran en menos de 1 segundo al no depender totalmente de la latencia de una red externa. |
| **Comunicación IoT** | MQTT (TLS) | Protocolo ligero diseñado para dispositivos con recursos limitados; ideal para enviar estados de la puerta y recibir comandos con un consumo mínimo de datos. |
| **Escalabilidad Cloud** | Docker / K8s | Facilita el despliegue rápido de actualizaciones y el escalamiento de la API conforme se integran nuevos edificios al ecosistema de **Nexora**. |
| **Video en Vivo** | WebRTC / RTSP | Protocolos de baja latencia indispensables para que el residente pueda visualizar y hablar con el visitante en tiempo real sin retrasos perceptibles. |

## 4.2. Tactical-Level Domain-Driven Design

En este nivel se define la implementacion del dominio por Bounded Context, detallando las capas Domain, Interface, Application e Infrastructure para la solucion NexBell. La arquitectura se apoya en C# .NET, autenticacion JWT, hashing BCrypt, SignalR para tiempo real y persistencia SQL (SQL Server/PostgreSQL).

### 4.2.1. Bounded Context: IAM (Identity & Access Management)

Este bounded context gestiona las identidades y el acceso al sistema. Su responsabilidad es garantizar que únicamente usuarios registrados (residentes y porteros) puedan acceder a la plataforma y operar según su rol. Administra el ciclo completo de autenticación: registro, inicio de sesión, recuperación de contraseña y control de sesiones activas. Sirve como base sobre la cual los demás bounded contexts validan la identidad del usuario que realiza cada operación.

#### 4.2.1.1. Domain Layer

**- Entities**

| Elemento | Propósito | Métodos clave |
| ----- | ----- | ----- |
| `UserAccount` | Representa la cuenta de un usuario del sistema (residente o portero), incluyendo sus credenciales y estado. | `Register(...)`, `Activate()`, `ChangePassword(...)`, `AssignRole(...)`, `Deactivate()` |
| `UserSession` | Gestiona el ciclo de vida de una sesión activa, incluyendo el refresh token asociado. | `Open(...)`, `RotateRefreshToken(...)`, `Revoke(...)`, `IsExpired()` |
| `PasswordResetTicket` | Representa una solicitud de restablecimiento de contraseña con tiempo de expiración. | `Issue(...)`, `MarkAsUsed()`, `IsValid()` |

**- Value Objects**

| Elemento | Propósito |
| ----- | ----- |
| `EmailAddress` | Encapsula y valida el formato del correo electrónico. |
| `PasswordHash` | Almacena el hash BCrypt de la contraseña del usuario. |
| `RefreshTokenValue` | Representa el token de renovación de sesión. |
| `RoleName` | Define el rol del usuario dentro del sistema (`Resident`, `Doorman`). |


**- Interfaces de dominio**

| Interface | Responsabilidad | Métodos clave |
| ----- | ----- | ----- |
| `IUserAccountRepository` | Persistencia de cuentas de usuario. | `GetByEmailAsync(...)`, `GetByIdAsync(...)`, `AddAsync(...)`, `UpdateAsync(...)` |
| `IUserSessionRepository` | Persistencia de sesiones y refresh tokens. | `GetByRefreshTokenAsync(...)`, `AddAsync(...)`, `UpdateAsync(...)`, `RevokeAllByUserAsync(...)` |
| `IPasswordHasher` | Define la política de hashing y verificación de contraseñas. | `Hash(string plainPassword)`, `Verify(string plainPassword, string hash)` |
| `ITokenIssuer` | Define la emisión y validación de tokens JWT. | `IssueAccessToken(UserAccount account)`, `Validate(string jwt)` |

**- Eventos de dominio**

| Evento | Disparador | Datos relevantes |
| ----- | ----- | ----- |
| `UserRegisteredDomainEvent` | Registro exitoso de una cuenta. | `UserId`, `Email`, `Role` |
| `UserLoggedInDomainEvent` | Inicio de sesión exitoso. | `UserId`, `SessionId`, `OccurredAt` |
| `PasswordResetRequestedDomainEvent` | Solicitud de recuperación de contraseña. | `UserId`, `TicketId`, `ExpiresAt` |
| `SessionRevokedDomainEvent` | Cierre o revocación de sesión. | `UserId`, `SessionId`, `Reason` |


#### 4.2.1.2. Interface Layer

Esta capa expone los endpoints REST que permiten a los clientes (aplicación móvil del residente y dashboard web del portero) interactuar con las funcionalidades de autenticación.

| Controlador | Endpoint | Handler invocado |
| ----- | ----- | ----- |
| `AuthController` | `POST /api/iam/register` | `RegisterUserCommandHandler` |
| `AuthController` | `POST /api/iam/login` | `LoginCommandHandler` |
| `AuthController` | `POST /api/iam/refresh` | `RefreshSessionCommandHandler` |
| `SessionController` | `POST /api/iam/logout` | `RevokeSessionCommandHandler` |
| `PasswordController` | `POST /api/iam/password/request-reset` | `RequestPasswordResetCommandHandler` |
| `PasswordController` | `POST /api/iam/password/confirm-reset` | `ConfirmPasswordResetCommandHandler` |

#### 4.2.1.3. Application Layer

Esta capa orquesta los flujos de negocio relacionados con autenticación y gestión de cuentas, coordinando las entidades del dominio con los repositorios e interfaces de infraestructura.

| Command Handler | Responsabilidad |
| ----- | ----- |
| `RegisterUserCommandHandler` | Valida unicidad de correo, crea la cuenta con rol asignado y emite el evento de registro. |
| `LoginCommandHandler` | Verifica credenciales, abre una sesión activa y emite el JWT de acceso. |
| `RefreshSessionCommandHandler` | Rota el refresh token y reemite un nuevo JWT sin requerir credenciales. |
| `RevokeSessionCommandHandler` | Cierra la sesión activa del usuario o todas sus sesiones simultáneas. |
| `RequestPasswordResetCommandHandler` | Genera un ticket de recuperación con tiempo de expiración y lo envía al correo registrado. |
| `ConfirmPasswordResetCommandHandler` | Valida el ticket, actualiza la contraseña y lo marca como utilizado. |


#### 4.2.1.4. Infrastructure Layer

Esta capa implementa las interfaces definidas en el dominio y gestiona la conexión con la base de datos y servicios externos.

| Componente | Tecnología | Contrato que implementa |
| ----- | ----- | ----- |
| `EfUserAccountRepository` | EF Core \+ SQL | `IUserAccountRepository` |
| `EfUserSessionRepository` | EF Core \+ SQL | `IUserSessionRepository` |
| `BcryptPasswordHasher` | BCrypt (EksBlowfish) | `IPasswordHasher` |
| `JwtTokenIssuer` | JWT \+ HMAC/SHA-256 | `ITokenIssuer` |
| `OutboxEventPublisher` | Outbox Pattern \+ Background Service | Publicación asíncrona de eventos de dominio |


#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

*Component Level Diagrams del Bounded Context IAM (Identity & Access Management)*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983166/component_yrelzo.png" width="1000">
</p> 

*Nota.* Elaboración propia

<div style="page-break-after: always;"></div>

#### 4.2.5.6. Bounded Context Software Architecture Container Level Diagrams

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

*Domain Layer Class Diagrams Bounded Context IAM (Identity & Access Management)*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983166/class_ue9jox.png" width="1000">
</p> 

*Nota.* Elaboración propia

##### 4.2.5.6.2. Bounded Context Database Design Diagram

*Database Design Diagram del Bounded Context IAM (Identity & Access Management)*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983166/database_pxgnuq.png" width="1000">
</p> 

*Nota.* Elaboración propia

### 4.2.2. Bounded Context: Security

Este bounded context se encarga de la autorización de acciones críticas dentro del sistema y del control del dispositivo físico de entrada. Su responsabilidad es evaluar si un usuario autenticado tiene permiso para ejecutar una operación sensible, como aprobar el ingreso de un visitante, y traducir esa decisión en un comando físico enviado al dispositivo IoT de la puerta. No gestiona identidades ni sesiones, eso es responsabilidad de IAM. Security opera únicamente sobre la pregunta: ¿este usuario puede hacer esto ahora?

#### 4.2.2.1. Domain Layer

**- Entities**

| Elemento | Propósito | Métodos clave |
| ----- | ----- | ----- |
| `AccessPolicy` | Define qué acciones puede ejecutar cada rol dentro del sistema. | `GrantPermission(...)`, `RevokePermission(...)`, `CanExecute(...)` |
| `DoorCommand` | Representa un comando de apertura o cierre enviado al dispositivo IoT de la puerta. | `Request(...)`, `MarkDispatched(...)`, `MarkConfirmed(...)`, `MarkFailed(...)` |

**- Value Objects**

 Elemento | Propósito |
| ----- | ----- |
| `PermissionCode` | Identifica de forma única un permiso funcional dentro del sistema. |
| `CommandType` | Tipo de comando físico que se enviará al dispositivo (`Unlock`, `Lock`). |
| `EntryPointId` | Identifica el punto de acceso físico al que se dirige el comando. |

**- Interfaces de dominio**

| Interface | Responsabilidad | Métodos clave |
| ----- | ----- | ----- |
| `IAccessPolicyRepository` | Persistencia de las reglas de autorización por rol. | `GetByRoleAsync(...)`, `UpdateAsync(...)` |
| `IDoorCommandRepository` | Persistencia del historial de comandos enviados al dispositivo. | `AddAsync(...)`, `GetByIdAsync(...)`, `UpdateAsync(...)` |
| `IIoTCommandGateway` | Envío seguro de comandos al dispositivo IoT de la puerta. | `SendAsync(DoorCommand command, CancellationToken ct)` |

**- Eventos de dominio**

| Evento | Disparador |
| ----- | ----- |
| `AccessAuthorizedDomainEvent` | El sistema validó que el usuario tiene permiso para ejecutar la acción solicitada. |
| `AccessDeniedDomainEvent` | El sistema rechazó la acción por no cumplir con las políticas de autorización. |
| `DoorCommandDispatchedDomainEvent` | El comando físico fue enviado exitosamente al dispositivo IoT. |
| `DoorCommandFailedDomainEvent` | El comando físico no pudo ser entregado o ejecutado por el dispositivo. |

#### 4.2.2.2. Interface Layer

Esta capa expone los endpoints que permiten evaluar permisos y enviar comandos físicos al dispositivo de entrada, consumidos principalmente por el dashboard web del portero.

| Controlador | Endpoint | Handler invocado |
| ----- | ----- | ----- |
| `AuthorizationController` | `POST /api/security/authorize` | `EvaluateAccessCommandHandler` |
| `DoorControlController` | `POST /api/security/door/unlock` | `DispatchDoorCommandHandler` |
| `DoorControlController` | `POST /api/security/door/lock` | `DispatchDoorCommandHandler` |

#### 4.2.2.3. Application Layer

Esta capa orquesta la evaluación de permisos y el despacho de comandos físicos, coordinando las políticas de acceso con el gateway del dispositivo IoT.

| Command Handler | Responsabilidad |
| ----- | ----- |
| `EvaluateAccessCommandHandler` | Consulta la política del rol del usuario y determina si la acción solicitada está permitida. Emite `AccessAuthorizedDomainEvent` o `AccessDeniedDomainEvent` según el resultado. |
| `DispatchDoorCommandHandler` | Crea el comando físico correspondiente, lo envía al dispositivo IoT a través del gateway y registra el resultado. |

#### 4.2.2.4. Infrastructure Layer

| Componente | Tecnología | Contrato que implementa |
| ----- | ----- | ----- |
| `EfAccessPolicyRepository` | EF Core \+ SQL | `IAccessPolicyRepository` |
| `EfDoorCommandRepository` | EF Core \+ SQL | `IDoorCommandRepository` |
| `IoTHttpCommandGateway` | HTTP \+ firma HMAC | `IIoTCommandGateway` |

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

*Component Level Diagrams del Bounded Context Security*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983129/component_fblnm4.png" width="600px" height="900px">
</p> 

*Nota.* Elaboración propia

#### 4.2.5.6. Bounded Context Software Architecture Container Level Diagrams

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

*Domain Layer Class Diagrams Bounded Context Security*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983128/class_k37pkt.png" width="1000">
</p> 

*Nota.* Elaboración propia

##### 4.2.5.6.2. Bounded Context Database Design Diagram

*Database Design Diagram del Bounded Context Security*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983129/database_tva66c.png" width="1000">
</p> 


### 4.2.3. Bounded Context: Directory

Este bounded context gestiona la información estructural del edificio: los departamentos que lo componen y los residentes asociados a cada uno. Su responsabilidad es servir como fuente de verdad para identificar a qué residente corresponde una visita y hacia dónde deben dirigirse las notificaciones. Directory no procesa solicitudes de acceso ni toma decisiones, únicamente provee y mantiene actualizada la información del directorio del edificio para que otros bounded contexts puedan consultarla.

#### 4.2.3.1. Domain Layer

Esta capa representa la estructura del edificio y las reglas de negocio relacionadas con la asignación de residentes a departamentos. El agregado raíz es BuildingDirectory, que controla la consistencia de toda la topología del edificio.

**- Entities**

| Elemento | Propósito | Métodos clave |
| ----- | ----- | ----- |
| `BuildingDirectory` | Agregado raíz. Representa la topología completa del edificio y controla la integridad de sus departamentos. | `AddApartment(...)`, `RemoveApartment(...)` |
| `Apartment` | Representa una unidad habitacional del edificio y su estado de ocupación. | `Create(...)`, `AssignResident(...)`, `UnassignResident(...)`, `UpdateLabel(...)` |
| `ResidentDirectoryProfile` | Ficha del residente dentro del directorio, usada para direccionar visitas y notificaciones correctamente. | `Create(...)`, `UpdateContact(...)`, `LinkApartment(...)` |

**- Value Objects**

| Elemento | Propósito |
| ----- | ----- |
| `ApartmentCode` | Identificador legible y único de un departamento dentro del edificio (por ejemplo, "101", "B-3"). |
| `ResidentDocument` | Documento de identidad del residente, usado para validación y búsqueda. |
| `ContactChannel` | Encapsula el canal de contacto del residente (correo electrónico o teléfono) usado para notificaciones. |

**- Interfaces de dominio**

| Interface | Responsabilidad | Métodos clave |
| ----- | ----- | ----- |
| `IApartmentRepository` | Persistencia y consulta de departamentos del edificio. | `GetByCodeAsync(...)`, `AddAsync(...)`, `UpdateAsync(...)` |
| `IResidentDirectoryRepository` | Persistencia y consulta de perfiles de residentes en el directorio. | `GetByIdAsync(...)`, `GetByApartmentAsync(...)`, `UpdateAsync(...)` |

**- Eventos de dominio**

| Evento | Disparador |
| ----- | ----- |
| `ApartmentCreatedDomainEvent` | Se registra un nuevo departamento en el edificio. |
| `ResidentAssignedToApartmentDomainEvent` | Se vincula un residente a un departamento por primera vez o se actualiza el vínculo. |
| `ResidentContactUpdatedDomainEvent` | El residente actualiza su información de contacto en el directorio. |

#### 4.2.3.2. Interface Layer

Esta capa expone los endpoints que permiten administrar la estructura del edificio y consultar la información del directorio. Es consumida principalmente por el dashboard del portero y por otros bounded contexts que necesitan resolver a qué residente corresponde un departamento.

| Controlador | Endpoint | Handler invocado |
| ----- | ----- | ----- |
| `ApartmentsController` | `POST /api/directory/apartments` | `CreateApartmentCommandHandler` |
| `ApartmentsController` | `PUT /api/directory/apartments/{code}/resident` | `AssignResidentCommandHandler` |
| `ResidentsController` | `PUT /api/directory/residents/{id}/contact` | `UpdateResidentContactCommandHandler` |
| `DirectoryQueryController` | `GET /api/directory/apartments/{code}/resident` | `GetResidentByApartmentQueryHandler` |

#### 4.2.3.3. Application Layer

Esta capa orquesta los flujos de gestión del directorio del edificio. Incluye tanto comandos que modifican el estado del directorio como consultas que otros bounded contexts utilizan para resolver el destino de una visita o notificación.

| Handler | Responsabilidad |
| ----- | ----- |
| `CreateApartmentCommandHandler` | Registra un nuevo departamento en la topología del edificio y emite `ApartmentCreatedDomainEvent`. |
| `AssignResidentCommandHandler` | Vincula un residente a un departamento existente y emite `ResidentAssignedToApartmentDomainEvent`. |
| `UpdateResidentContactCommandHandler` | Actualiza los datos de contacto del residente en el directorio y emite `ResidentContactUpdatedDomainEvent`. |
| `GetResidentByApartmentQueryHandler` | Resuelve qué residente está asociado a un departamento dado, para que Intercom & Notifications pueda dirigir correctamente la notificación de llegada. |

#### 4.2.3.4. Infrastructure Layer

Esta capa implementa la persistencia del directorio mediante EF Core y expone proyecciones optimizadas para consultas frecuentes por código de departamento.

| Componente | Tecnología | Contrato que implementa |
| ----- | ----- | ----- |
| `EfApartmentRepository` | EF Core \+ SQL | `IApartmentRepository` |
| `EfResidentDirectoryRepository` | EF Core \+ SQL | `IResidentDirectoryRepository` |
| `DirectoryReadModelProjection` | SQL Views | Proyecciones optimizadas para consultas rápidas por departamento |

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

*Component Level Diagrams del Bounded Context Directory*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983075/comoponene_prfmlo.png" width="1000">
</p> 

*Nota.* Elaboración propia

#### 4.2.5.6. Bounded Context Software Architecture Container Level Diagrams

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

*Domain Layer Class Diagrams Bounded Context Directory*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983075/class_lhspv0.png" width="1000">
</p> 

*Nota.* Elaboración propia

##### 4.2.5.6.2. Bounded Context Database Design Diagram

*Database Design Diagram del Bounded Context Directory*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983076/database_fhi3ub.png" width="1000">
</p> 

*Nota.* Elaboración propia

### 4.2.4. Bounded Context: Intercom & Notifications

Este bounded context representa el núcleo operativo del sistema. Se encarga de gestionar todo el flujo que ocurre desde que un visitante llega al edificio hasta que el residente toma una decisión sobre su acceso. Sus responsabilidades incluyen recibir el evento de llegada del dispositivo IoT, procesar y almacenar la evidencia capturada (imagen y audio), mantener la cola de atención del portero en tiempo real, notificar al residente correspondiente y registrar su respuesta. Intercom y Notifications se mantienen en un mismo bounded context porque forman parte de un flujo continuo e inseparable: la notificación siempre es consecuencia directa de la captura, y la decisión del residente siempre responde a esa notificación.

#### 4.2.4.1. Domain Layer

Esta capa modela el ciclo de vida completo de una solicitud de visita, desde su creación hasta el registro de la decisión final. El agregado raíz es VisitRequest, que coordina la evidencia capturada, la notificación enviada y la decisión del residente.

**- Entities**

| Elemento | Propósito | Métodos clave |
| ----- | ----- | ----- |
| `VisitRequest` | Agregado raíz. Representa el ciclo de vida completo de la llegada de un visitante: desde la detección IoT hasta la decisión de acceso. | `Open(...)`, `AttachEvidence(...)`, `MarkNotified(...)`, `RegisterDecision(...)`, `Close(...)` |
| `VisitorEvidence` | Representa la evidencia multimedia (foto y audio) capturada durante el evento de llegada del visitante. | `Create(...)`, `ValidateIntegrity(...)` |
| `NotificationDispatch` | Registra el intento de envío de notificación al residente, incluyendo su estado de entrega. | `Schedule(...)`, `MarkSent(...)`, `MarkDelivered(...)`, `MarkFailed(...)` |
| `IntercomQueueItem` | Representa la posición de una solicitud en la cola de atención del portero, permitiendo gestionar el orden de atención. | `Enqueue(...)`, `AssignDoorman(...)`, `Dequeue(...)` |

**- Value Objects**

| Elemento | Propósito |
| ----- | ----- |
| `VisitRequestId` | Identificador único de una solicitud de visita. |
| `EvidenceUri` | Referencia a la ubicación del archivo de foto o audio almacenado. |
| `DoorStatus` | Representa el estado físico del punto de acceso en el momento del evento (`Open`, `Closed`). |

**- Interfaces de dominio**

 Interface | Responsabilidad | Métodos clave |
| ----- | ----- | ----- |
| `IVisitRequestRepository` | Persistencia y consulta de solicitudes de visita. | `AddAsync(...)`, `GetByIdAsync(...)`, `UpdateAsync(...)`, `GetPendingAsync(...)` |
| `INotificationGateway` | Envío de notificaciones push al residente. | `SendAsync(NotificationDispatch notification, CancellationToken ct)` |
| `IRealtimeQueueGateway` | Publicación en tiempo real de actualizaciones de cola para el dashboard del portero. | `PublishQueueUpdateAsync(VisitRequest request, CancellationToken ct)` |
| `IEvidenceStorage` | Almacenamiento de archivos multimedia de evidencia. | `SaveAsync(...)` |

**- Eventos de dominio**

| Evento | Disparador |
| ----- | ----- |
| `VisitRequestReceivedDomainEvent` | El dispositivo IoT detecta la llegada de un visitante y crea la solicitud. |
| `VisitorEvidenceCapturedDomainEvent` | La evidencia multimedia fue recibida, validada y adjuntada a la solicitud. |
| `DoormanQueueUpdatedDomainEvent` | La cola operacional del portero fue actualizada con una nueva solicitud o cambio de estado. |
| `ResidentNotificationSentDomainEvent` | La notificación push fue emitida exitosamente al residente correspondiente. |
| `AccessDecisionReceivedDomainEvent` | El residente registró su decisión de aprobación o rechazo desde la aplicación móvil. |

#### 4.2.4.2. Interface Layer

Esta capa expone los endpoints consumidos por el dispositivo IoT, la aplicación móvil del residente y el dashboard web del portero. Incluye además un hub de SignalR para la comunicación en tiempo real con el dashboard.

| Controlador / Hub | Endpoint | Handler invocado |
| ----- | ----- | ----- |
| `IoTIngressController` | `POST /api/intercom/visit-requests` | `CreateVisitRequestCommandHandler` |
| `IoTIngressController` | `POST /api/intercom/visit-requests/{id}/evidence` | `AttachVisitorEvidenceCommandHandler` |
| `ResidentDecisionController` | `POST /api/intercom/visit-requests/{id}/decision` | `RegisterAccessDecisionCommandHandler` |
| `IntercomQueueController` | `GET /api/intercom/queue/pending` | `GetPendingQueueQueryHandler` |
| `DoormanHub` (SignalR) | Canal en tiempo real | `PublishQueueUpdateAsync(...)` |

#### 4.2.4.3. Application Layer

Esta capa orquesta el flujo principal del sistema: desde la recepción del evento IoT hasta el registro de la decisión del residente. Coordina la evidencia, las notificaciones y la cola del portero manteniendo la consistencia del agregado VisitRequest.

| Handler | Responsabilidad |
| ----- | ----- |
| `CreateVisitRequestCommandHandler` | Recibe el evento del dispositivo IoT, crea la solicitud de visita en estado pendiente y la incorpora a la cola del portero. Emite `VisitRequestReceivedDomainEvent`. |
| `AttachVisitorEvidenceCommandHandler` | Almacena la foto y el audio recibidos, los valida y los adjunta a la solicitud correspondiente. Emite `VisitorEvidenceCapturedDomainEvent`. |
| `NotifyResidentCommandHandler` | Consulta el directorio para identificar al residente del departamento destino y envía la notificación push con los datos del visitante. Emite `ResidentNotificationSentDomainEvent`. |
| `RegisterAccessDecisionCommandHandler` | Registra la decisión del residente (aprobación o rechazo) sobre la solicitud de visita y actualiza su estado. Emite `AccessDecisionReceivedDomainEvent`. |
| `GetPendingQueueQueryHandler` | Retorna la lista actualizada de solicitudes pendientes en la cola del portero, ordenadas cronológicamente. |

#### 4.2.4.4. Infrastructure Layer

Esta capa implementa las interfaces del dominio conectando con la base de datos, el servicio de almacenamiento de archivos, el sistema de notificaciones push y el hub de tiempo real.

| Componente | Tecnología | Contrato que implementa |
| ----- | ----- | ----- |
| `EfVisitRequestRepository` | EF Core \+ SQL | `IVisitRequestRepository` |
| `BlobEvidenceStorage` | Blob Storage / S3 compatible | `IEvidenceStorage` |
| `FcmApnsNotificationGateway` | FCM / APNs SDK | `INotificationGateway` |
| `SignalRRealtimeQueueGateway` | SignalR | `IRealtimeQueueGateway` |

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

*Component Level Diagrams del Bounded Context Intercom & Notifications*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983010/componen_iiplhh.png" width="1000">
</p> 

*Nota.* Elaboración propia

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

*Domain Layer Class Diagrams Bounded Context Intercom & Notifications*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983010/class_wmhwgv.png" width="1000">
</p> 

*Nota.* Elaboración propia

##### 4.2.5.6.2. Bounded Context Database Design Diagram

*Database Design Diagram del Bounded Context Intercom & Notifications*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776983010/database_vygufa.png" width="1000">
</p> 

*Nota.* Elaboración propia

### 4.2.5. Bounded Context: Audit

Este bounded context se encarga de registrar de forma persistente e inmutable todos los eventos relevantes relacionados con el acceso de visitantes al edificio. Su responsabilidad es mantener un historial confiable que permita la trazabilidad completa de cada decisión tomada dentro del sistema, incluyendo aprobaciones, rechazos y la evidencia asociada a cada evento. Audit no toma decisiones ni interactúa con el dispositivo IoT directamente; únicamente escucha los eventos emitidos por otros bounded contexts y los persiste de forma ordenada y consultable. Es el contexto que da soporte a las revisiones posteriores y fortalece la seguridad del edificio mediante un control histórico de accesos.

#### 4.2.5.1. Domain Layer

Esta capa modela el registro inmutable de cada evento de acceso. El agregado raíz es AccessRecord, que agrupa todos los eventos puntuales ocurridos durante el ciclo de vida de una visita y una vez cerrado no puede ser modificado.

**- Entities**

| Elemento | Propósito | Métodos clave |
| ----- | ----- | ----- |
| `AccessRecord` | Agregado raíz. Representa el registro inmutable y completo del resultado de una solicitud de acceso, incluyendo la decisión tomada y la evidencia asociada. | `Create(...)`, `Seal()` |
| `AccessTimelineEntry` | Representa un evento puntual dentro del historial de una solicitud de acceso (llegada, notificación enviada, decisión registrada, puerta abierta). | `Append(...)` |

**- Value Objects**

| Elemento | Propósito |
| ----- | ----- |
| `AccessDecision` | Encapsula la decisión final sobre el acceso del visitante (`Approved`, `Rejected`). |
| `AuditTimestamp` | Marca temporal normalizada en UTC, usada para garantizar consistencia en el orden cronológico de los eventos. |
| `CorrelationId` | Identificador que permite correlacionar un registro de Audit con la solicitud original en Intercom & Notifications. |

**- Interfaces de dominio**

| Interface | Responsabilidad | Métodos clave |
| ----- | ----- | ----- |
| `IAccessRecordRepository` | Escritura y lectura de registros inmutables de acceso. | `AddAsync(...)`, `GetByIdAsync(...)`, `GetByResidentAsync(...)` |
| `IAuditQueryRepository` | Consultas optimizadas para el historial de visitas filtrado por estado, fecha o departamento. | `SearchAsync(...)`, `GetByDateRangeAsync(...)` |

**- Eventos de dominio**

| Evento | Disparador |
| ----- | ----- |
| `AccessRecordCreatedDomainEvent` | Se registra formalmente una decisión de acceso en el historial. |
| `AccessRecordSealedDomainEvent` | El registro queda cerrado e inmutable, no puede recibir más entradas. |

#### 4.2.5.2. Interface Layer

Esta capa expone los endpoints que permiten registrar nuevos eventos de acceso y consultar el historial. Es consumida principalmente por el dashboard web del portero y la aplicación móvil del residente para visualizar el historial de visitas.

| Controlador | Endpoint | Handler invocado |
| ----- | ----- | ----- |
| `AuditController` | `POST /api/audit/access-records` | `RegisterAccessRecordCommandHandler` |
| `AuditController` | `GET /api/audit/access-records/{id}` | `GetAccessRecordByIdQueryHandler` |
| `AuditQueryController` | `GET /api/audit/access-records` | `SearchAccessRecordsQueryHandler` |

#### 4.2.5.3. Application Layer

Esta capa orquesta el registro y la consulta del historial de accesos. Escucha los eventos emitidos por Intercom & Notifications para crear los registros correspondientes y expone consultas para que el portero y el residente puedan revisar el historial de visitas.

| Handler | Responsabilidad |
| ----- | ----- |
| `RegisterAccessRecordCommandHandler` | Recibe el resultado de una decisión de acceso desde Intercom & Notifications, crea el registro inmutable con toda la información asociada y emite `AccessRecordCreatedDomainEvent`. Una vez persistido, sella el registro emitiendo `AccessRecordSealedDomainEvent`. |
| `GetAccessRecordByIdQueryHandler` | Retorna el detalle completo de un registro de acceso específico, incluyendo la línea de tiempo de eventos asociados. |
| `SearchAccessRecordsQueryHandler` | Permite filtrar el historial de accesos por estado (aprobado/rechazado), fecha o departamento, retornando resultados paginados para su visualización. |

#### 4.2.5.4. Infrastructure Layer

Esta capa implementa la persistencia del historial de accesos mediante EF Core y expone proyecciones SQL optimizadas para las consultas del historial.

| Componente | Tecnología | Contrato que implementa |
| ----- | ----- | ----- |
| `EfAccessRecordRepository` | EF Core \+ SQL | `IAccessRecordRepository` |
| `SqlAuditQueryRepository` | SQL \+ proyecciones | `IAuditQueryRepository` |

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

*Component Level Diagrams del Bounded Context Audit*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776981860/component_e5kwnl.png" width="1000">
</p> 

*Nota.* Elaboración propia

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

*Domain Layer Class Diagrams Bounded Context Audit*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776981860/classs_bazhln.png" width="1000">
</p> 

*Nota.* Elaboración propia

##### 4.2.5.6.2. Bounded Context Database Design Diagram

*Database Design Diagram del Bounded Context Audit*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1776981860/database_jo0k0s.png" width="1000">
</p> 

*Nota.* Elaboración propia

<hr>

<div style="page-break-after: always;"></div>

# Capítulo V: Solution UI/UX Design

## 5.1 Style Guidelines

## 5.1.1 General Style Guidelines

La presente guía de estilo establece los fundamentos visuales y comunicacionales para todos
los productos digitales de **Nexbell**. El objetivo principal es garantizar una experiencia
de usuario consistente, profesional y coherente, sentando las bases de un sistema de diseño escalable.
Para ello, se ha decidido adoptar **Material Design 3 de Google** como sistema de diseño base, adaptándolo 
a la identidad de nuestra marca.

### 5.1.1 General Style Guidelines.



#### **Branding y Tono de Comunicación**

La identidad de **Nexbell** se construye sobre una base de precisión técnica y sofisticación residencial, valores críticos para la seguridad de alta gama .

* *Personalidad de la Marca:** Nexbell se proyecta bajo el concepto de **"Vigilant Elegance"**, combinando la exactitud estéril de la tecnología avanzada con la calidez sofisticada de un entorno de lujo .
* *Estilo Visual:** Se utiliza una estética **"Deep Tech"** minimalista, donde una base de negro puro permite que la luminosidad turquesa guíe la atención del usuario, evocando protección de vanguardia y control sin esfuerzo .
* *Tono de Comunicación:** El lenguaje debe reflejar tensión tipográfica y claridad técnica :
* *Intelectual y de Alto Nivel:** Para las declaraciones heroicas y mensajes editoriales .
* *Técnico y Funcional:** Para los datos de seguridad, estados del sistema y lectura de dispositivos IoT .

#### **Paleta de Colores**

La paleta sigue una filosofía de **"Negro Puro"** para asegurar profundidad infinita y eficiencia energética en pantallas OLED, utilizando el turquesa como indicador de seguridad y actividad .

| Rol del Color | Nombre | Código HEX | Aplicación |
| :--- | :--- | :--- | :--- |
| **Primario** | Primary Turquoise | `#74d7cf` | Estado activo e indicador de "Seguro" . |
| **Secundario** | Secondary Turquoise| `#74d7ce` | Estados de interacción (hover) y detalles decorativos . |
| **Terciario** | Tertiary Accent | `#ffb59a` | Elementos de acento específicos . |
| **Fondo** | Background | `#000000` | Base sólida para contraste máximo . |
| **Error** | Error Red | `#ffb4ab` | Alertas críticas de seguridad . |
| **Bordes** | Tonal Borders | `#1a1a1a` | Definición de contenedores secundarios . |

#### **Tipografía**

El sistema emplea una tensión tipográfica sofisticada entre lo editorial y lo técnico .

| Elemento | Fuente | Grosor | Tamaño | Aplicación |
| :--- | :--- | :--- | :--- | :--- |
| **Headline Accent** | ebGaramond | Medium (500) | 48px | Títulos editoriales y hero statements . |
| **Headline Large** | Geist | Bold (600) | 32px | Títulos funcionales de la UI . |
| **Body Medium** | Geist | Regular (400) | 16px | Lectura de datos y cuerpo de texto . |
| **Label Caps** | Geist | Bold (600) | 12px | Metadatos técnicos y estados (Uppercase) . |

#### **Layout y Espaciado (Spacing)**

Se implementa un sistema basado en una **cuadrícula de 4px** para mantener un ritmo vertical estricto y una sensación arquitectónica estructurada .

* *Unidad Base:** 4px .
* *Gutter:** 24px para separación entre columnas .
* *Margen:** 32px para evitar la saturación visual en los bordes de la pantalla .
* *Zonas de Control:** Se utilizan grandes espacios negativos para separar el estado de seguridad principal de los controles ambientales secundarios .

#### **Formas y Elevación**

* *Geometría de Píldora:** Los botones, campos de entrada y distintivos de estado deben ser siempre **completamente redondeados (pill-shaped)** para suavizar el borde técnico de la interfaz .
* *Contenedores:** Las tarjetas de video y gráficos utilizan un radio de **1.5rem (rounded-xl)** para proyectar estabilidad arquitectónica .
* *Profundidad Luminosa:** En lugar de sombras, se utiliza un **brillo turquesa suave** (`rgba(66, 168, 161, 0.3)`) para resaltar elementos de estado crítico como el botón de "Armado" .
* *Efecto de Cristal:** Los modales y superposiciones utilizan un fondo blanco al 10% de opacidad con un desenfoque de fondo (*backdrop blur*) de más de 20px para un efecto de "vidrio ahumado" .


### 5.1.2 Web, Mobile and IoT Style Guidelines.

A continuación, se presenta la aplicación detallada de los 12 pasos de diseño IoT para el prototipo de NexBell, estructurada de forma clara y alineada con la arquitectura "Zero Hardware" en departamentos:

**1. Definition of the System Requirements**

| Categoría | Especificación |
|-----------|----------------|
| **Objetivo Principal** | Control de accesos inteligente, videoportería virtual y notificación en tiempo real para edificios residenciales. |
| **Parámetros a Medir** | Presencia humana (movimiento), proximidad del visitante, estado físico de la puerta (abierta/cerrada), nivel de audio ambiental. |
| **Requisitos Funcionales** | • Detección y notificación de visitantes en tiempo real<br>• Apertura remota de cerraduras<br>• Transmisión inalámbrica WiFi<br>• Indicación visual de estado. |
| **Requisitos No Funcionales** | • Tiempo de envío de alerta < 5 segundos<br>• Operación 24/7 en punto de control<br>• Resistente a condiciones típicas de recepción (0-50°C). |

**2. Selection of the IoT System Typology**

| Aspecto | Descripción |
|---------|-------------|
| **Tipo de Sistema** | **Real-time Access Control IoT System** con arquitectura Edge-Cloud. |
| **Topología** | Nodo perimetral (ESP32) conectado vía WiFi a un Edge Gateway o directamente al Cloud. |
| **Procesamiento** | Validación rápida local (Edge) para apertura rápida, y Cloud para enrutamiento de notificaciones, registro de auditoría y almacenamiento multimedia. |
| **Resiliencia** | Capacidad asíncrona temporal si falla internet, permitiendo control por conserjería física local. |

**3. Definition of Physical Layer Requirements**

| Componente | Especificaciones Técnicas |
|------------|---------------------------|
| **Sensor de Movimiento (PIR)** | • Salida digital (HIGH/LOW) para eventos de llegada.<br>• Rango de cono ajustable (3-7 metros). |
| **Sensor Ultrasónico HC-SR04** | • Validación de distancia analítica (reducir falsos positivos del PIR).<br>• Precisión de 2cm a 400cm. |
| **Sensor Magnético (Simulado/Pot)**| • Monitorea el estado físico de la puerta (Abierta/Cerrada). |
| **Módulo de Audio/Captura** | • Sensor de sonido para captura preliminar/activación por voz. En el modelo final incluye hardware multimedia. |
| **LED Panel / Indicador** | • Feedback visual para el visitante (encendido, error, puerta abierta). |

**4. Definition of Exchange Layer Requirements**

| Capa | Protocolo | Descripción |
|-----------|-----------|-------------|
| **Embedded → Cloud/Edge** | MQTT (TLS) / HTTP REST | Envío de telemetría de sensores y recepción de comandos de apertura remota. |
| **Cloud → Mobile App** | FCM / APNS | Push Notifications de baja latencia a los residentes. |
| **Conectividad** | WiFi 802.11 b/g/n | Módulo integrado en el ESP32. |
| **Formato Datos** | JSON | Payload: `device_id`, `event_type`, `distance_cm`, `door_status`, `timestamp`. |
| **Seguridad** | Hashing, JWT, TLS 1.2 | Protección contra suplantación física y cifrado extremo a extremo. |

**5. Definition of Information Layer Requirements**

| Proceso | Detalle |
|---------|---------|
| **Adquisición Datos** | GPIO para PIR y Ultrasonido. ADC de 12-bits para sensores analógicos. |
| **Lógica de Fusión** | Se cruza la detección del PIR con el HC-SR04 (< 1 metro) para confirmar "Visitante Presente". |
| **Estructura JSON** | `{"device":"gate_01", "event":"visitor_detected", "door":"closed"}` |
| **Buffer Local** | Cola local de eventos físicos durante caídas temporales de WiFi. |
| **Sincronización** | Estampado de tiempo (NTP) en cada paquete generado. |

**6. Definition of Application Service Layer Requirements**

| Interfaz | Funcionalidades |
|----------|----------------|
| **Mobile App (Residente)** | • Alertas push interactivas: "Aprobar" / "Rechazar".<br>• Visualización de imagen/audio y apertura remota de chapa. |
| **Web Dashboard (Conserje)** | • Cola priorizada de visitantes (FIFO).<br>• Monitoreo de estado de todas las puertas del edificio.<br>• Accionamiento de apertura e historial. |
| **API REST / Cloud** | • Búsqueda en directorio, asociación de departamento a residente y registro auditable (log). |

**7. Selection of the Architectures of Data Exchange and Information Integration Layers**

| Componente | Tecnología | Función |
|------------|------------|---------|
| **Cloud API Gateways** | .NET / C# Web API | Enrutamiento seguro, RBAC, exposición de módulos del Bounded Context. |
| **Microservicios (DDD)** | .NET / C# | Contextos: IAM, Directory, Security (Core), Audit, Intercom. |
| **Database** | SQL Server / PostgreSQL | Tablas transaccionales de visitas, logs de auditoría inmutables, directorio de residentes. |
| **Message Broker** | MQTT Broker / SignalR | Manejo asíncrono para señales del hardware IoT y websockets para UI del conserje en tiempo real. |
| **External Services** | Firebase (FCM) | Entrega de notificaciones ricas al smartphone del residente. |

**8. Selection of the Sensors and the Actuators**

| Componente | Rol en NexBell | Especificaciones Clave |
|------------|----------------|------------------------|
| **PIR y HC-SR04** | Activadores de flujo | Detonantes del escenario sin intervención táctil (Touchless). |
| **Relé Electromagnético** | Actuador / Cerradura | Recibe pulso (HIGH) desde el ESP32 para liberar el mecanismo de puerta (5V/12V). |
| **Contacto Magnético** | Auditoría y Seguridad | Detecta aperturas forzadas o puertas dejadas abiertas. |
| **Módulo Multimedia** | Evidencia | (Proyección) Micrófono / Cámara para validación visual pre-apertura. |

**9. Selection of the Microcontroller**

| Aspecto | Especificaciones (ESP32 DevKit C V4) |
|---------|--------------------------------------|
| **Microcontrolador** | Dual-core Xtensa LX6 @ 240MHz. Potencia suficiente para preprocesar audio básico. |
| **Conectividad** | WiFi integrado + Bluetooth (para aprovisionamiento inicial). |
| **Pines y E/S** | Múltiples GPIOs soportan interrupciones hardware (PIR), I2C, SPI para pantallas o cámaras (OV2640 futuro). |
| **Alimentación** | 5V vía USB o Vin constantes desde la fuente de la portería central. |

**10. Definition of the Data Processing for Each Node and in Cloud**

**Procesamiento Embedded (ESP32):**
1. Interrupción activada por PIR.
2. Comprobación cruzada de distancia vía HC-SR04.
3. Empaquetado JSON: Envío de HTTP POST / Mensaje MQTT al Cloud marcando "Event: Visitor_Arrival".
4. Recepción de comando "Unlock" desde la nube y disparo del relé de 3 segundos.

**Procesamiento in Cloud (.NET):**
1. Enrutamiento del evento: Identifica qué residente/departamento asociar a esa puerta.
2. Consulta de permisos (Security BC): Solo los usuarios del depto destino pueden aprobar.
3. Despacho notificaciones: Usa Firebase FCM enviando la alerta con metadata.
4. Auditoría (Audit BC): Registra cada intento de interacción con el dispositivo IoT.

**11. Analysis of the Processing Time**

| Operación | Capa | Latencia Estimada |
|-----------|------|-------------------|
| Detección Hardware (PIR + Ultrasonido) | Embedded | < 100 ms |
| Enrutamiento API + Búsqueda de Usuario | Cloud | < 300 ms |
| Entrega Firebase (Push) al celular | Network | 1 a 3 segundos |
| Apertura operada por usuario | Cloud → Embedded | < 500 ms tras botón de 'Aprobar' |
| **Latencia Total de Experiencia** | End-to-End | **< 4 segundos (Detección a Smartphone)** |

**12. Definition of the Graphical User Interface**

| Dispositivo / App | Componentes Clave de UI |
|-------------------|--------------------------|
| **NexBell Mobile (Residente)** | • Lock Screen Notification interactiva (Botones contextuales de Aprobar/Rechazar).<br>• Visor en vivo con datos del visitante (DNI provisto si hubo pre-registro). |
| **Nexora Dashboard (Web/Conserje)**| • Tabla visual de visitas pendientes (modo grilla o fila).<br>• Botón masivo para "Abrir Puerta".<br>• Indicador Semáforo universal (Rojo=Cerrado/Alarma, Verde=Abierta, Amarillo=Visitante). |
| **Punto IoT Físico (Embedded)** | • Indicación minimalista mediante un LED verde parpadeando durante procesamiento, rojo en denegado. |

#### 5.1.2.1. Aplicación del Proceso para Web 1 (Landing Page & Dashboard)
Para el entorno web inicial, enfocado en capturar el interés de potenciales clientes y proveer la interfaz de gestión base, las directrices generales se adaptan bajo los siguientes parámetros técnicos:

* **Estructura de Layout y Grillas:** Se implementa una cuadrícula responsiva basada en columnas fluidas (12 columnas para pantallas de escritorio `>= 1200px`) con un *gutter* fijo de `24px` y márgenes laterales de `32px` para evitar el hacinamiento visual de la información de control.
* **Jerarquía Tipográfica en Pantalla Ancha:** Se prioriza el uso de *Headline Accent (ebGaramond)* a `48px` para los enunciados principales (*Hero Statements*) de la Landing Page, mientras que el panel administrativo utiliza *Headline Large (Geist)* a `32px` para asegurar la legibilidad técnica inmediata de los datos en monitores de escritorio.
* **Estados de Interacción de Escritorio (Desktop Hovers):** Los elementos interactivos como botones en forma de píldora (Pill-shaped) y tarjetas del dashboard web adoptan una transición cromática suave hacia el color secundario (*Secondary Turquoise* `#74d7ce`) al detectar el puntero (hover), acompañado de un sutil brillo turquesa de profundidad lumínica.

#### 5.1.2.2. Aplicación del Proceso para Mobile 1 (Aplicación Residencial)
Para el entorno móvil inicial, cuyo propósito crítico es permitir la interacción, recepción de alertas en tiempo real y la validación de visitas por parte del residente, el mismo proceso del *General Style* se traslada considerando los factores de forma portátiles:

* **Zonas de Control y Áreas Seguras (Safe Areas):** El layout se diseña sobre una grilla móvil simplificada (4 columnas). Se respeta estrictamente el uso de espacios negativos en los extremos de la pantalla y márgenes de seguridad para evitar superposiciones con los *notches* físicos de los dispositivos móviles o las barras de navegación del sistema operativo.
* **Densidad e Interacción Táctil:** Aunque se mantiene la geometría redondeada en botones y campos de entrada (*Pill-shaped*), los objetivos de selección (*Touch Targets*) se configuran con un tamaño mínimo de `48px × 48px` para garantizar la precisión táctil de los dedos, implementando respuestas visuales instantáneas al presionar.
* **Optimización de Elementos Críticos Móviles:** El despliegue de las alertas críticas de seguridad utiliza el color de error (*Error Red* `#ffb4ab`), maximizando el contraste sobre el fondo negro puro (`#000000`) de la aplicación. Las tipografías funcionales como *Body Medium (Geist)* a `16px` y *Label Caps* a `12px` se configuran con interlineados generosos para facilitar una lectura veloz en situaciones de alerta en el celular.


### 5.2. Information Architecture

#### 5.2.1. Organization Systems

Para garantizar que los usuarios de **Nexbell** puedan navegar y procesar la información de seguridad de manera eficiente, la arquitectura de la información se ha estructurado aplicando sistemas de organización visual y de categorización de contenido adaptados al entorno residencial.

##### **Sistemas de Organización Visual**

- **Jerárquica (Visual Hierarchy):** Se aplicará principalmente en el **Dashboard del Conserje/Administrador**, donde las alertas de acceso actuales y las llamadas en espera se mostrarán con mayor prominencia visual. La jerarquía tipográfica guiará al usuario para distinguir rápidamente entre un aviso de visita y una notificación del sistema.

- **Secuencial (Step-by-step):** Este sistema se aplicará en flujos de trabajo críticos como la **validación de una visita**, el **onboarding de un nuevo residente** y el **proceso de registro de una encomienda o paquete**. Guía al usuario de principio a fin, minimizando errores en la toma de datos de seguridad.

- **Matricial (Matrix):** Utilizado para la visualización de conjuntos de datos complejos como el **Historial de Accesos** y el **Directorio de Residentes**, permitiendo consultar, ordenar y filtrar registros según departamento, fecha o tipo de ingreso.

##### **Esquemas de Categorización del Contenido**

- **Alfabético:** Se aplicará para facilitar la búsqueda en la lista de **Residentes** y el directorio de **Proveedores de Servicios** frecuentes.

- **Cronológico:** El pilar para el historial de seguridad. Se presentará en orden cronológico descendente (lo más reciente primero) en secciones como **Registro de Visitas**, **Historial de Llamadas** y **Bitácora de Incidentes de Seguridad**.

- **Por Tópicos (By Topic):** La navegación se organizará por módulos funcionales: **Intercomunicador, Visitantes, Residentes, Encomiendas y Seguridad**.

- **Según Audiencia (By Audience):** - El **Personal de Seguridad (Conserje)** tendrá acceso a la consola de intercomunicación, gestión de visitas en tiempo real y registro de paquetes.
    - El **Residente** dispondrá de una vista simplificada en su móvil para recibir videollamadas, autorizar accesos y revisar su historial personal de visitas.
    - El **Administrador del Edificio** tendrá acceso a métricas de uso, auditorías de seguridad y gestión de pagos de la plataforma.

#### 5.2.2. Labelling Systems

El sistema de etiquetado de **Nexbell** busca construir un lenguaje de interfaz predecible que evite ambigüedades en situaciones donde la rapidez de respuesta es vital.

##### **Etiquetas de Navegación Principal**

- **Inicio:** Dashboard principal.
- **Intercom:** Acceso a la consola de llamadas y video.
- **Visitantes:** Gestión de visitas actuales y pre-autorizadas.
- **Directorio:** Lista de residentes y departamentos.
- **Encomiendas:** Registro de paquetes y correspondencia.
- **Auditoría:** Historial completo de accesos.
- **Mi Cuenta:** Configuración de perfil.

##### **Etiquetas de Acciones Principales (CTA)**

- **+ Pre-autorizar Visita**
- **Abrir Puerta**
- **Iniciar Videollamada**
- **Registrar Paquete**
- **Añadir Residente**
- **Reportar Alerta**

##### **Etiquetas de Acciones de Gestión**

- **Autorizar**
- **Denegar**
- **Editar**
- **Finalizar Llamada**
- **Ver Registro**
- **Filtrar**

##### **Etiquetas de Estado y Datos**

- **Estado de Acceso:** `Autorizado`, `Denegado`, `En Espera`.
- **Estado de Puerta:** `Cerrada`, `Abierta`, `Alarma`.
- **Tipo de Visita:** `Familiar`, `Delivery`, `Servicio Técnico`.

#### 5.2.3. SEO Tags and Meta Tags

##### **SEO Tags para el Landing Page**

- **Title Tag:** `Nexbell | Videoportería Inteligente y Citofonía Virtual en Perú`
    - **Sustento:** Incluye la marca y términos clave ("Videoportería", "Citofonía Virtual") para captar administradores buscando modernizar sus edificios.

- **Meta Description:** `Moderniza la seguridad de tu edificio con Nexbell. Videoportería IoT, control de accesos desde el móvil y gestión de visitas en tiempo real sin cableado tradicional.`
    - **Sustento:** Resalta el beneficio principal (sin cableado) y las funciones clave para incentivar el interés de juntas de propietarios.

- **Meta Keywords:** `videoportero inteligente, intercomunicador wifi edificio, citofonia virtual peru, control de accesos residencial, seguridad edificios lima, app para condominios`

##### **ASO (App Store Optimization) para la Aplicación Móvil**

- **App Title:** `Nexbell: Videoportería y Seguridad`
- **App Subtitle:** `Atiende tu puerta desde el celular.`
- **App Keywords:** `intercomunicador, timbre, video, seguridad, edificio, condominio, residente, acceso, portero, lima`
- **App Description:** - **Corta:** `Atiende visitas, visualiza quién toca tu puerta y autoriza ingresos desde donde estés.`
    - **Larga:** `Nexbell transforma el intercomunicador de tu edificio en una experiencia digital y segura. Recibe videollamadas de tus visitas directamente en tu smartphone, incluso si no estás en casa.

      Con Nexbell podrás:
        - Ver y hablar con tus visitantes en tiempo real.
        - Pre-autorizar invitados con códigos QR o invitaciones digitales.
        - Recibir alertas de encomiendas y paquetes en recepción.
        - Consultar el historial de quién ha visitado tu hogar.

      Sin instalaciones complejas dentro de tu departamento. ¡Más seguridad, más comodidad!`

#### 5.2.4. Searching Systems

##### **Búsqueda de Residentes**

- **Opción de Búsqueda:** El conserje podrá buscar por **número de departamento** o **apellido del residente**.
- **Filtros Disponibles:** Por **Torre/Bloque** y **Estado de Cuenta** (`Activo`, `Inactivo`).

##### **Búsqueda en Historial de Accesos**

- **Opción de Búsqueda:** Búsqueda por **nombre del visitante** o **DNI**.
- **Filtros Disponibles:** **Fecha/Hora**, **Tipo de Visita** (`Delivery`, `Visita`, `Servicios`) y **Resultado** (`Aprobado`, `Denegado`).

##### **Búsqueda de Encomiendas**

- **Opción de Búsqueda:** Localización por **Departamento** destinatario.
- **Filtros Disponibles:** **Estado del Paquete** (`En Conserjería`, `Entregado`) y **Empresa de Courier**.

#### 5.2.5. Navigation Systems

##### **Sistema de Navegación para la Aplicación Móvil**

- **Navegación Primaria (Bottom Nav):** Acceso rápido a `Inicio`, `Visitas`, `Llamadas` y `Perfil`.
- **Navegación Jerárquica:** Al tocar una notificación de visita, el usuario entra al detalle del visitante y puede retroceder al historial.
- **Pestañas (Tabs):** En la sección de Visitas se usará `Pendientes` y `Pasadas`.
- **Botón de Acción Flotante (FAB):** En la pantalla de Visitas para "+ Crear Invitación".

##### **Sistema de Navegación para el Landing Page**

- **Navegación Primaria (Sticky Header):** Secciones de `Cómo Funciona`, `Planes`, `Seguridad` y el botón `Contacto Comercial`.
- **Navegación Secundaria (Footer):** Enlaces a `Soporte Técnico`, `Políticas de Privacidad` y acceso al **Portal de Administración**.

## 5.3. Landing Page UI Design.

En esta sección se presenta el diseño de interfaz de usuario (UI) de alta fidelidad para la Landing Page de Nexora. Este diseño consolida la identidad visual de la startup, utilizando una paleta de colores y tipografías que transmiten seguridad, modernidad y eficiencia tecnológica.

El diseño UI se ha optimizado para guiar al usuario a través de un flujo narrativo claro, desde el reconocimiento de la problemática de los sistemas analógicos hasta la adopción del ecosistema NexBell. Se han aplicado principios de Responsive Design para garantizar que la experiencia sea consistente tanto en navegadores de escritorio como en dispositivos móviles, asegurando que los elementos de interacción (CTA) sean accesibles y visualmente destacados para maximizar la conversión de clientes potenciales.

#### 5.3.1. Landing Page Wireframe.

El wireframe de la Landing Page de Nexora ha sido diseñado bajo un enfoque de baja fidelidad, priorizando la jerarquía de la información y la experiencia de usuario (UX) para los dos segmentos interesados: juntas de propietarios que buscan modernización y administradores de edificios. La estructura se divide en módulos clave que comunican la propuesta de valor de NexBell:

 - Header (Navegación): Se implementa un Sticky Header que facilita el acceso rápido a las secciones de "Cómo Funciona", "Planes de Suscripción", "Seguridad IoT" y un botón de "Contacto Comercial" destacado para la conversión.

 - Sección Hero: En la parte superior se presenta el eslogan principal y el objetivo de la startup, destacando la eliminación de cableado analógico y la transición hacia una portería inteligente basada en la nube.

 - Módulo de Funciones Principales: Mediante el uso de tarjetas informativas e íconos, se describen las capacidades técnicas del sistema, tales como la captura de evidencia multimedia, el enrutamiento de llamadas al smartphone y la gestión de alertas en tiempo real.

 - Sección de Beneficios: Se detallan las ventajas competitivas de la solución, enfocándose en el ahorro de costos operativos (CAPEX), la valorización del patrimonio inmobiliario y la mejora en la seguridad mediante el registro auditable de visitas.

 - Sección de Planes (Pricing): Un módulo comparativo que presenta el modelo de negocio Software as a Service (SaaS), permitiendo a los interesados visualizar las opciones de membresía según el tamaño del condominio o edificio.

 - Footer: Contiene enlaces secundarios a soporte técnico, políticas de privacidad y el acceso directo al portal de administración para usuarios ya registrados.

Este diseño asegura que el usuario interesado comprenda el flujo de trabajo de la solución IoT y los beneficios de reemplazar la infraestructura tradicional por el ecosistema digital de Nexora.

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778710148/landing_i7zhsy.png" width="1000">
</p> 

#### 5.3.2. Landing Page Mock-up.

En esta sección se presenta el Mock-up de la Landing Page, proporcionando una representación visual realista de cómo interactúa la interfaz de Nexora en un entorno de escritorio. A diferencia del diseño UI plano, el mock-up permite visualizar la profundidad, las texturas y la disposición final de los elementos en un contexto de uso real.

Este recurso es fundamental para validar la estética del producto y asegurar que el mensaje de innovación de NexBell se comunique de forma impactante. La composición resalta la claridad del dashboard de administración y la facilidad con la que un propietario puede entender el servicio desde el primer contacto visual.

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682636/Html_Body_7_ehhk4i.png" width="1000">
</p> 

#### 5.4. Applications UX/UI Design.

En esta sección se detalla el diseño de la interfaz y la experiencia de usuario para la plataforma web de NexBell. El enfoque se centra en la eficiencia operativa, permitiendo que tanto administradores como personal de seguridad gestionen los accesos, visualicen registros multimedia y administren la base de datos de residentes de manera intuitiva y centralizada.

### 5.4.1. Applications Wireframes.

Se presentan los wireframes de baja fidelidad que definen la arquitectura de información y el flujo de navegación de la aplicación web. Estos esquemas permiten validar la disposición de los módulos de control, el tablero de monitoreo y las secciones de auditoría sin distracciones visuales. El objetivo principal es asegurar que las funcionalidades críticas sean accesibles con la menor cantidad de clics posibles, optimizando el tiempo de respuesta ante eventos de seguridad.

*- Vista de Inicio de sesion*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682627/Html_Body_8_jfrjwg.png" width="1000">
</p> 

*- Vista de Bienvenida*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682627/Html_Body_9_lyxci3.png" width="1000">
</p> 

*- Vista de Dashboard*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682628/Html_Body_13_sj51ug.png" width="1000">
</p> 

*- Vista de Historial* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682629/Html_Body_11_feosk2.png" width="1000">
</p> 

*- Vista de Verificación* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682629/Html_Body_12_dzpzun.png" width="1000">
</p> 

*- Vista de Perfil* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682629/Html_Body_10_uofxgt.png" width="1000">
</p> 


### 5.4.2. Applications Wireflow Diagrams.

En esta sección detallamos los diagramas de *wireflow* de la aplicación **NexBell** para el Edificio San Martín, mapeando la arquitectura de información, la distribución de componentes y el flujo de navegación interactiva entre las interfaces diseñadas para el personal de portería.

El prototipo se ha estructurado en cinco grupos de flujos operativos independientes para validar la usabilidad y la eficiencia del sistema antes de proceder con el desarrollo del software.

---

#### Grupo 1: Flujo de Acceso, Registro e Inicialización de Jornada
Este diagrama mapea el ciclo de vida de la autenticación de los operarios y la inicialización segura del entorno de monitoreo.

**Descripción del Proceso:**
1. **Validación de Credenciales:** El flujo inicia en la pantalla *Iniciar sesión*, donde el portero ingresa sus credenciales de acceso. El sistema valida los datos contra el módulo de usuarios.
2. **Recuperación de Contraseña:** Desde el Login, el flujo permite una bifurcación hacia la interfaz de *Recuperar contraseña* en caso de que el usuario requiera restablecer sus credenciales de seguridad.
3. **Creación de Cuenta:** Si el usuario no tiene una cuenta activa, se le redirige al formulario de *Registro*, donde captura sus datos personales y selecciona el rol operativo (*Portero*). Al completar el proceso con éxito, el sistema muestra una pantalla intermedia de *Registro exitoso*.
4. **Inicialización de Jornada (Welcome):** Tras una autenticación o registro exitoso, el flujo redirige a la interfaz de bienvenida (*"Bienvenido de vuelta, José Peralta"*). Aquí el sistema realiza una carga dinámica de datos contextuales en tiempo real: ubicación del módulo (*Main Gate - Edificio San Martín*), fecha/hora del servidor, y el estado perimetral inicial (puerta *Cerrada*, sensores *Activos* y *2 visitantes* en cola). El flujo concluye cuando el operador presiona el botón principal **"Iniciar turno →"**, cambiando su estado a activo en el backend e inicializando el dashboard principal.

   
<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778699506/Captura_de_pantalla_2026-05-13_a_la_s_2.11.40_p._m._nqqqbw.png" width="1000">
</p> 

---

#### Grupo 2: Flujo de Gestión de Notificaciones y Configuración del Sistema
Este diagrama detalla cómo el operador interactúa con las alertas del entorno y gestiona los ajustes operativos globales de la plataforma.

**Descripción del Proceso:**
1. **Procesamiento de Alertas:** Al ingresar al sistema, el portero visualiza el módulo de *Notificaciones*. El sistema clasifica y ordena los eventos automáticamente. Se validan las transiciones para alertas de tipo informativo rutinario (ej. *"Nuevo visitante registrado"*) y alertas de advertencia de vulnerabilidad técnica o física (ej. *"Batería Baja: Sensor Perimetral 08"*), las cuales forzan un estado visual diferenciado para asegurar la atención inmediata del operador.
2. **Configuración Global:** El operador puede acceder a la interfaz de *Ajustes*, donde el flujo permite interactuar con los *toggles* funcionales para habilitar/deshabilitar alertas sonoras y notificaciones de escritorio, así como seleccionar el idioma base de la interfaz.
3. **Soporte Técnico:** Si el operador requiere asistencia, el flujo se bifurca hacia el *Centro de Ayuda y Soporte*, desplegando guías rápidas de resolución de problemas y un formulario integrado para enviar tickets de soporte al equipo técnico de NexBell.

---

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778699582/Captura_de_pantalla_2026-05-13_a_la_s_2.12.57_p._m._pv9ufz.png" width="1000">
</p> 

---

#### Grupo 3: Flujo de Mantenimiento de Cuenta y Seguridad del Operador
Este diagrama valida el flujo de actualización de la información personal de los porteros y la seguridad de sus credenciales de acceso.

**Descripción del Proceso:**
1. **Consulta de Perfil:** Desde la barra de navegación fija, el operador accede a su interfaz de *Perfil*, donde el sistema renderiza su ficha de identidad completa, incluyendo datos del edificio (*Edificio San Martín*) y contactos de emergencia del personal de seguridad.
2. **Mantenimiento de Datos:** Al presionar el disparador de edición, el flujo abre la interfaz de *Editar perfil*, permitiendo al operador actualizar su información de contacto o subir/eliminar su fotografía de identidad para el monitoreo administrativo.
3. **Actualización de Credenciales:** El flujo se bifurca de manera segura hacia el módulo de *Cambio de contraseña*. Aquí se simula el ingreso de la contraseña actual, el establecimiento de una nueva credencial blindada por un control CAPTCHA visual y la finalización con el disparador *"Guardar nueva contraseña"* para robustecer la seguridad de la cuenta del operario.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778700167/Captura_de_pantalla_2026-05-13_a_la_s_2.22.41_p._m._b9lzhn.png" width="1000">
</p> 

---

#### Grupo 4: Flujo de Verificación y Control de Accesos (Módulo Crítico)
Este diagrama detalla el flujo lógico del proceso de control de ingresos residenciales, mapeando la interacción entre los datos multimedia y el control físico de accesos.

**Descripción del Proceso:**
1. **Identificación de Visitas:** El flujo inicia cuando un visitante se encuentra en cola de espera. El portero accede a la pantalla de *Verificación de Visitas*, donde el sistema carga la fotografía del rostro en alta resolución, su nombre verificado (*Carlos Méndez*) y su ID correlativo (*Visitante #001*).
2. **Evaluación Cruzada:** El operador interactúa con el componente de reproducción de audio para escuchar la autorización de voz vinculada. Simultáneamente, el sistema cruza la información visual y multimedia con la ficha técnica del residente anfitrión asignado para validar la legitimidad del ingreso.
3. **Impacto en Hardware (IoT):** El usuario cuenta con dos disparadores de alta prioridad: rechazar el acceso o presionar **"Permitir Ingreso"**. Al aprobar la solicitud, el flujo ejecuta una transición instantánea hacia un modal de éxito con el estado *"¡ACCESO APROBADO!"*, simulando la liberación física de la cerradura electromecánica (IoT) y registrando el evento en la bitácora histórica. El flujo concluye limpiando la cola con la vista *"Todo al día"*.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778700385/Captura_de_pantalla_2026-05-13_a_la_s_2.26.19_p._m._bk1zyf.png" width="1000">
</p> 

---

#### Grupo 5: Flujo de Monitoreo Central (Dashboard) y Finalización de Jornada
Este diagrama valida la jerarquía visual del panel de control central y el flujo de cierre seguro de la sesión operativa.

**Descripción del Proceso:**
1. **Supervisión en Tiempo Real:** Tras iniciar el turno, el operador opera principalmente sobre el *Dashboard*. El sistema renderiza un panel analítico centralizado: estado de la puerta, resumen de visitas esperadas y la bitácora de actividad reciente. Se validan los diagramas para componentes interactivos clave como los medidores estadísticos diarios y semanales.
2. **Cierre de Sesión Seguro:** Cuando el operador decide concluir su jornada laboral, presiona el disparador de *Log Out*. El flujo ejecuta una transición hacia el modal flotante de confirmación (*"¿Cerrar sesión?"*), donde el sistema despliega datos contextuales técnicos (hora de inicio y dispositivo utilizado). Al confirmar con el botón de acción principal **"Sí, cerrar sesión"**, el flujo termina de manera segura, destruyendo los tokens de sesión locales y redirigiendo al estado inicial de *Login* de la aplicación.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778700345/Captura_de_pantalla_2026-05-13_a_la_s_2.25.39_p._m._houger.png" width="1000">
</p> 


### 5.4.4. Applications Mock-ups.

Los mock-ups de alta fidelidad muestran la apariencia final de la aplicación web, integrando los componentes visuales de la marca y elementos de interacción detallados. En esta etapa se aplican estilos, tipografías y contrastes de color que mejoran la legibilidad en entornos de trabajo continuo (como centros de control). Estos diseños finales permiten visualizar cómo el sistema presenta las alertas en tiempo real y la gestión de datos, garantizando una herramienta profesional, robusta y fácil de usar.


*- Vista de Inicio de sesion*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778681905/Html_Body_hkcg06.png" width="1000">
</p> 

*- Vista de Bienvenida*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778681905/Html_Body_1_eulqqj.png" width="1000">
</p> 

*- Vista de Perfil* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778681905/Html_Body_2_ze7kz2.png" width="1000">
</p> 

*- Vista de Historial* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778682431/Html_Body_6_y3tf2m.png" width="1000">
</p> 

*- Vista de Dashboard*

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778681904/Html_Body_5_w2ltlt.png" width="1000">
</p> 

*- Vista de Verificación* 

<p align="center">
  <img src="https://res.cloudinary.com/df8xwy4xb/image/upload/v1778681904/Html_Body_4_jk0muo.png" width="1000">
</p> 

### 5.4.4. Applications User Flow Diagrams.

En esta sección detallamos la secuencia lógica, las bifurcaciones de decisión y el flujo de datos que experimenta el personal de seguridad (portero/vigilante) al interactuar con el sistema **NexBell**. El objetivo de este mapeo es asegurar que las transiciones entre estados del software respondan eficientemente a las operaciones críticas de control residencial en tiempo real.

#### Descripción detallada de los procesos del sistema:

1. **Flujo de Autenticación e Inicialización de Jornada (Login & Welcome):**
   * **Validación de Credenciales:** El flujo inicia en la interfaz de *Acceso al sistema*. El usuario ingresa su correo y contraseña; el sistema valida los datos contra la base de datos de usuarios. En caso de no contar con un perfil activo, el flujo permite redirigir al usuario al formulario de *Crear Cuenta*, donde se registran los datos personales y se asigna explícitamente el rol operativo (*Portero*).
   * **Carga de Estado Contextual:** Tras una autenticación exitosa, el sistema redirige a una pantalla de bienvenida dinámica (*"Bienvenido de vuelta, José Peralta"*). En esta vista, el sistema realiza una consulta inmediata para renderizar datos en tiempo real: ubicación del módulo (*Main Gate - Edificio San Martín*), fecha/hora del servidor, y un resumen del estado físico del perímetro estructurado en tres componentes: estado de la puerta (*Cerrada*), estado de los sensores (*Activos*) y la cola de visitas pendientes (*2 visitantes*).
   * **Disparador de Estado Activo:** El proceso de inicio concluye cuando el operador presiona el botón principal **"Iniciar turno →"**. Esta acción cambia el estado del usuario en el sistema a "Activo" e inicializa el entorno principal de monitoreo.

2. **Flujo de Gestión y Clasificación de Notificaciones:**
   * **Procesamiento de Eventos:** Al ingresar al *Dashboard*, el sistema despliega el módulo de *Notificaciones (Historial de alertas y eventos del sistema)*.
   * **Bifurcación por Criticidad:** Las alertas se ordenan automáticamente por prioridad. Los eventos informativos rutinarios (ej. *"Nuevo visitante registrado"*) generan tarjetas oscuras con opción de expansión, mientras que los eventos de vulnerabilidad técnica o física (ej. *"Batería Baja: Sensor Perimetral 08"*) disparan un estado de *Advertencia* visualmente diferenciado para forzar la atención del operador.

3. **Flujo de Verificación y Control de Accesos (Módulo Crítico):**
   * **Identificación y Carga de Ficha:** Cuando una visita se encuentra en cola, el operador accede al panel de *Verificación de Visitas*. La interfaz renderiza la captura fotográfica del visitante, su nombre completo extraído del registro (*Carlos Méndez*) y su ID correlativo (*Visitante #001*).
   * **Validación Multimedia y Cruzada:** El operador interactúa con un componente de reproducción de audio para escuchar la autorización de voz vinculada. Simultáneamente, el sistema cruza la información en pantalla con la ficha técnica del residente anfitrión asignado a ese departamento para validar la legitimidad del ingreso.
   * **Resolución del Flujo e Impacto en Hardware:** El usuario cuenta con dos disparadores de alta prioridad: rechazar el acceso o presionar **"Permitir Ingreso"**. Al aprobar la solicitud, el sistema ejecuta una transición hacia un modal de éxito con el estado *"¡ACCESO APROBADO!"*, lo que simula el envío del pulso digital para liberar la cerradura física (IoT) y registra la entrada en la bitácora histórica. El flujo finaliza limpiando la cola con la vista *"Todo al día"*.

---
<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778696776/Captura_de_pantalla_2026-05-13_a_la_s_1.26.10_p._m._ow0whu.png" width="1000">
</p> 


## 5.5. Applications Prototyping.

Para validar la arquitectura de información, la consistencia visual y la usabilidad de **NexBell** antes de proceder con la fase de codificación frontend, desarrollamos un prototipo de alta fidelidad en la plataforma **Figma**, utilizando las herramientas de la pestaña *Prototype*.

Nos aseguramos de consolidar toda la experiencia interactiva en un flujo continuo y unificado, eliminando puntos de inicio (*Flow starting points*) redundantes para garantizar que las pruebas de usuario y las simulaciones de navegación reflejen el comportamiento real del sistema en un entorno de producción.

<p align="center">
  <img src="https://res.cloudinary.com/dx0i2vioe/image/upload/v1778696916/Captura_de_pantalla_2026-05-13_a_la_s_1.27.28_p._m._batmyt.png" width="1000">
</p> 

Enlace del video: https://tinyurl.com/yc3c7emm

#### Criterios de diseño e interacción implementados:

* **Enfoque Visual "Vigilant Elegance" (UI Oscura):** Implementamos un tema oscuro puro (fondos negros con tipografía clara de alta densidad utilizando la fuente *Geist*). Este enfoque mitiga la fatiga ocular del operador durante jornadas prolongadas de monitoreo nocturno y genera un contraste de alto impacto para las alertas críticas a través de nuestro color de acento turquesa (*Secondary Turquoise* `#74D7CE`).
* **Consistencia de Componentes y Mitigación de Errores:** Todos los campos de entrada de formularios, botones de acción y tarjetas de información utilizan esquinas redondeadas (*Pill-shaped / Smooth Cards*). Esta geometría limpia organiza visualmente los datos en bloques lógicos, optimizando la velocidad de lectura y reduciendo el error humano al gestionar datos críticos o contraseñas.
* **Comportamiento y Transiciones de la Interfaz:** * Configuramos disparadores de tipo clic (`On Click`) con transiciones inmediatas (`Instant`) para simular la navegación fluida a través de la barra lateral fija (*Main Gate, Dashboard, Visitors, History, Profile*).
  * Empleamos transiciones desvanecidas (`Dissolve`) para modelar de manera realista la superposición de ventanas emergentes y estados de confirmación (como el modal de *Cerrar Sesión*).

#### Módulos de software validados en el prototipo:

* **Módulo de Autenticación y Registro:** Flujo completo de Login, recuperación de credenciales y creación de cuenta con validación de rol.
* **Panel de Configuración Global:** Simulación de *Toggles* funcionales para activar/desactivar alertas sonoras del sistema, notificaciones de escritorio y selector de idioma.
* **Gestión de Cuenta y Seguridad:** Flujo de actualización de perfil (carga de foto de identidad) y el módulo para *Cambiar Contraseña*, el cual integra la validación visual de un componente CAPTCHA para robustecer la seguridad de la cuenta.
  
## 5.6. IoT Device Design.
<img src="https://i.imgur.com/dGdKVQa.jpeg" alt="iot imagen v1">
### Diagrama del prototipo (Wokwi)


- **Editor:** Wokwi
- **Microcontrolador:** ESP32 DevKit C V4
- **Sensores y actuadores:** PIR, ultrasonico HC-SR04, sensor de sonido (simulado), electromagnetico (simulado), LED de estado


### Componentes y proposito

| Componente | Rol en NexBell | Descripcion tecnica |
|-----------|-----------------|---------------------|
| **ESP32 DevKit C V4** | Nodo principal | WiFi integrado, ADC para sensores analogicos, GPIO para control de actuadores |
| **PIR Motion Sensor** | Deteccion de presencia | Dispara evento de llegada de visitante |
| **HC-SR04** | Proximidad/confirmacion | Valida distancia a puerta y reduce falsos positivos |
| **Potenciometro “Electromag”** | Estado de puerta (simulado) | Simula lectura de sensor magnetico en la puerta |
| **Potenciometro “Sound Sensor”** | Evidencia de audio (simulada) | Simula nivel de ruido/voz en la puerta |
| **LED** | Estado local | Indicador de alertas o estado de conexion |

### Conexiones principales 

| Sensor/Actuador | Pin ESP32 | Tipo de senal |
|----------------|-----------|---------------|
| LED (con resistencia) | GPIO 2 | Digital (salida) |
| PIR OUT | GPIO 13 | Digital (entrada) |
| HC-SR04 TRIG | GPIO 5 | Digital (salida) |
| HC-SR04 ECHO | GPIO 18 | Digital (entrada) |
| Electromag (pot) | GPIO 34 | Analogica (entrada) |
| Sound sensor (pot) | GPIO 32 | Analogica (entrada) |

### Constraints para NexBell 

1. **Instalacion sin cableado interno:** El dispositivo no debe requerir cableado hacia departamentos. Se prioriza WiFi local.
2. **Latencia operativa:** La deteccion y notificacion debe ocurrir en segundos (flujo visitante → alerta).
3. **Robustez en porteria:** Sensores deben resistir uso diario y cambios de iluminacion/ruido.
4. **Consumo moderado:** Operacion continua en puntos de acceso sin sobrecargar energia.
5. **Escalabilidad modular:** Sensores pueden reemplazarse o mejorarse sin afectar el firmware base.

### Flujos de IoT soportados

- **Deteccion de llegada:** PIR activa evento inicial.
- **Confirmacion de presencia:** HC-SR04 valida distancia.
- **Estado de puerta:** Lectura analogica simula estado abierto/cerrado.
- **Evidencia local:** Sensor de sonido simula captura de audio ambiente.
- **Indicacion local:** LED senala estado del sistema o alerta.

### Validacion preliminar

- Lecturas analogicas estables en GPIO 32/34.
- Activacion y lectura digital de PIR.
- Medicion de distancia con HC-SR04 funcional.
- LED responde a eventos locales como prueba de estados.

### Observaciones

- En esta fase, sensores de puerta y sonido se simulan con potenciometros. En la version fisica se reemplazaran por sensor magnetico real y microfono con preamplificador.
- La arquitectura esta preparada para evolucionar hacia captura multimedia real (camara + microfono), manteniendo el ESP32 como nodo de control.

<div style="page-break-after: always;"></div>

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration.

| Actividad | Producto o Herramienta | Propósito de uso | Ruta (SaaS/Descarga) |
|---|---|---|---|
| Project Management | Jira | Gestión de tareas, seguimiento del progreso mediante tableros Kanban y control de sprints. | [https://www.atlassian.com/software/jira](https://www.atlassian.com/software/jira) |
| Requirements Management | Trello | Centralización de historias de usuario, matriz de trazabilidad y especificación de requerimientos funcionales. | [https://trello.com](https://trello.com) |
| Product Design | Figma | Diseño de prototipos de alta fidelidad, wireframes de la interfaz móvil y web, y flujos de usuario (UX). | [https://www.figma.com](https://www.figma.com) |
| Software Development | Visual Studio Code | Entorno de desarrollo integrado (IDE) principal para la codificación del backend y frontend. | [https://code.visualstudio.com](https://code.visualstudio.com) |
| IoT Hardware Simulation | Wokwi | Simulación de circuitos electrónicos, microcontroladores (ESP32) y sensores para validar la lógica del Edge antes de la implementación física. | [https://wokwi.com](https://wokwi.com/) |
| Software Deployment | Microsoft Azure | Plataforma de nube para el despliegue de microservicios, base de datos MySQL y hosting de la web. | [https://azure.microsoft.com](https://azure.microsoft.com) |
| Software Testing | Postman | Pruebas funcionales de la API, validación de endpoints y automatización de colecciones de pruebas manuales. | [https://www.postman.com](https://www.postman.com) |
| Database Management | MySQL Workbench | Modelado de datos (DER), administración de la base de datos remota en Azure y ejecución de scripts SQL. | [https://www.mysql.com](https://www.mysql.com) |
| Software Documentation | GitHub Wiki | Documentación técnica detallada de la arquitectura, manuales de usuario y guías de instalación. | [https://github.com](https://github.com/) |

### 6.1.2. Source Code Management

En esta sección se definen los mecanismos y el plan de organización técnica que el equipo de Nexora empleará para el control y seguimiento de los cambios en el ecosistema NexBell. La gestión del código fuente es una pieza crítica para garantizar la integridad de una solución IoT de este tipo, ya que requiere la sincronización precisa entre el software de borde (Edge API), la lógica de negocio en el backend y la interfaz de usuario web.

Para asegurar un desarrollo paralelo eficiente y una trazabilidad completa de cada iteración, se utilizará GitHub como plataforma centralizada de control de versiones. Esto permitirá mantener un historial detallado de las mejoras en la seguridad de los accesos y la gestión de video en tiempo real, facilitando la colaboración continua y el despliegue escalable de la solución.

A continuación, se detallan los repositorios que alojan el código fuente de los componentes de la solución NexBell, abarcando desde la lógica del dispositivo IoT hasta los servicios web:

| Producto | Repositorio | Descripción |
|---|---|---|
| Landing Page | [https://github.com/Nexora-solution/NexBell-LandingPage](https://github.com/Nexora-solution/Nexbell-LandingPage) | Contiene el código fuente del sitio web público de NexBell, enfocado en el marketing digital, la presentación de la propuesta de valor y el contacto para potenciales clientes. |
| Frontend | [https://github.com/Nexora-solution/NexBell-FrontendWeb](https://github.com/Nexora-solution/Nexbell-FrontendWeb) | Aloja la interfaz web de la aplicación principal, diseñada para el personal de conserjería y administración. Incluye el dashboard de gestión de accesos, monitoreo de video y control de residentes. |
| Backend | [https://github.com/Nexora-solution/NexBell-WebServices](https://github.com/Nexora-solution/NexBell-WebServices) | Repositorio del núcleo de la solución. Implementa la lógica de negocio, la API RESTful para la persistencia de datos en MySQL, el manejo de notificaciones y la autenticación de usuarios. |
| Edge API | [https://github.com/Nexora-solution/NexBell-EdgeAPI](https://github.com/Nexora-solution/NexBell-EdgeAPI) | Contiene el firmware y la lógica de borde para los dispositivos IoT. Gestiona la interacción con sensores, el control del videoportero y la comunicación de eventos hacia la nube. |
| Report | [https://github.com/Nexora-solution/NexBell-ProjectReport](https://github.com/Nexora-solution/NexBell-ProjectReport) | Repositorio central de documentación del proyecto. Almacena los entregables académicos y el informe final del curso. |
| Testing | [https://github.com/Nexora-solution/NexBell-Testing](https://github.com/Nexora-solution/NexBell-Testing) | Repositorio de pruebas y archivos feature de la solución. |

#### Estrategia de Trabajo y Versionamiento

El equipo adopta el modelo GitFlow de Vincent Driessen para organizar el flujo de trabajo. Este esquema permite separar claramente el código en desarrollo de las versiones estables listas para producción.
* **Main Branch (Rama Principal):** Contiene el código fuente que se encuentra actualmente en producción. Cada commit en esta rama corresponde a una versión estable y etiquetada.
* **Develop Branch (Rama de Desarrollo):** Es la rama de integración principal. Aquí se consolidan todas las funcionalidades terminadas antes de pasar a una fase de lanzamiento.
* **Feature Branches (feature/…):** Ramas temporales creadas para desarrollar una funcionalidad específica. Se originan en develop y se reintegran a ella al finalizar la tarea.
* **Release Branches (release/…):** Se utilizan para preparar una nueva versión de producción. Permiten correcciones menores y preparación de metadatos antes de fusionarse en main y develop.
* **Hotfix Branches (hotfix/…):** Ramas de emergencia destinadas a solucionar errores críticos detectados en producción. Se originan directamente en main y se reintegran tanto a main como a develop.

Para el control de versiones, se aplica el Versionamiento Semántico (SemVer) bajo el formato MAJOR.MINOR.PATCH:
* **MAJOR:** Cambios incompatibles con versiones previas (ej. cambio estructural en la Edge API).
* **MINOR:** Nuevas funcionalidades compatibles (ej. nueva vista en el Frontend).
* **PATCH:** Corrección de errores menores.

Se adopta el estándar de Conventional Commits para asegurar que el historial de cambios sea legible y automatizable. La estructura de cada mensaje debe ser:
* **Estructura:** \<tipo\>(\<alcance\>): \<descripción\>
* **Cuerpo (Opcional):** \<descripción detallada del cambio\>

Tipos comunes: feat (nueva funcionalidad), fix (corrección de error), docs (cambios en documentación), refactor (mejora de código sin cambiar funciones).
> Ejemplo: feat(edge): add motion sensor trigger for video recording

### 6.1.3. Source Code Style Guide & Conventions

El equipo Nexora se compromete a mantener un estándar de código limpio, profesional y uniforme para la solución NexBell. Dado que el proyecto integra múltiples entornos (Edge, Backend y Frontend), se adoptan las siguientes normativas transversales:
* **Nomenclatura en Inglés:** Todos los elementos de programación (clases, variables, métodos, componentes y comentarios técnicos) deben nombrarse estrictamente en inglés para mantener estándares internacionales.
* **Clean Code:** Se aplican principios de responsabilidad única y legibilidad para facilitar la integración entre los componentes de hardware y software.
* **Gherkin Conventions:** Las especificaciones de pruebas de aceptación en archivos .feature seguirán un formato estandarizado para asegurar la validación de los flujos de seguridad del videoportero.

A continuación, se detallan las convenciones específicas para cada tecnología del ecosistema NexBell:

| Lenguaje / Framework | Convención de nombres | Guía referencial |
| --- | --- | --- |
| **HTML / CSS** | `kebab-case` para IDs, clases y nombres de archivos. | [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html) |
| **JavaScript (Vue.js)** | `camelCase` para variables y funciones. `PascalCase` para nombres de componentes (`.vue`). | [Vue.js Official Style Guide](https://vuejs.org/style-guide/) |
| **C# (EF Core 9)** | `PascalCase` para clases, métodos y propiedades. `camelCase` para variables locales y parámetros. | [Microsoft C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions) |
| **C++ (IoT / ESP32)** | `camelCase` para variables y sensores. `PascalCase` para funciones de control de hardware. | [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) |
| **MySQL** | `snake_case` para nombres de tablas y columnas. `UPPERCASE` para palabras clave SQL. | [SQL Style Guide](https://www.sqlstyle.guide/) |

#### Pruebas de Comportamiento (Behavior-Driven Development)

Para la redacción de los criterios de aceptación y las pruebas de la solución IoT, se aplican los estándares de Gherkin. Esto garantiza que las interacciones entre el residente y el videoportero NexBell sean comprendidas tanto por el equipo técnico como por los stakeholders:

* **Estilo Declarativo:** Se prioriza describir el comportamiento del sistema sobre la implementación técnica.
* **Estructura Base:** Uso riguroso de las palabras clave: Feature, Scenario, Given (Dado que), When (Cuando), Then (Entonces) y And (Y).
* **Idioma:** Redacción obligatoria en inglés para mantener consistencia con los repositorios de código.

### 6.1.4. Software Deployment Configuration

En esta sección se describe el flujo de despliegue y la configuración de infraestructura para el sistema de NexBell. El equipo Nexora ha optado por una estrategia de despliegue híbrida que aprovecha las fortalezas de diferentes proveedores de nube para optimizar la latencia, la escalabilidad y la disponibilidad de la solución.

El proceso de entrega continua inicia con la integración del código en GitHub, activando flujos de trabajo que automatizan la publicación de la Landing Page y la Web Application en Netlify, garantizando una distribución global eficiente. Por otro lado, la lógica de negocio y la persistencia de datos se centralizan en Microsoft Azure, proporcionando un entorno robusto para el procesamiento de los Web Services. Este esquema asegura que cada componente de NexBell opere en un entorno optimizado para su función específica, facilitando el mantenimiento y la trazabilidad del producto final.

<p align="center">
  <img src="https://i.imgur.com/bvfbnD0.png" alt="Deployment Diagram - NexBell Solution">
</p>

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1

| Sprint # | Sprint 1 |
|---|---|
| Sprint Planning Background |
| Date | 06/05/2026 |
| Time | 3:30 PM |
| Location | Virtual |
| Prepared by | Gómez Flores, Daniela Araceli |
| Attendees (to planned meeting) | Gómez Flores, Daniela Araceli / Bellido Salas, Raúl / Borja Molina, Gabriel Sebastián / Suárez Romero, Santiago Manuel / Burga Loarte, Anaely Zarely |
| Sprint Goal & User Stories |
| Sprint 1 Goal | **Nuestro objetivo es** consolidar la presencia digital de NexBell y validar la experiencia de usuario principal para la administración. <br> **Creemos que** esto permite a los potenciales clientes residenciales comprender claramente nuestra propuesta de valor y ofrece al personal de seguridad una visión general del flujo de trabajo de gestión. <br> **Esto se confirmará cuando** un visitante pueda navegar por la página de inicio completa para conocer los beneficios del sistema, y ​​cuando un usuario administrador pueda interactuar con el panel principal, visualizando registros de visitantes ficticios e interfaces de videoportero simuladas, todo ello implementado en un entorno web. |
| Sprint 1 Velocity | 30 |
| Sum of Story Points |  24 |

#### 6.2.1.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Identidad Visual y Diseño UX/UI | Desarrollo de la Landing Page | Arquitectura de Frontend y Mocking de Datos | Configuración de CI/CD y Despliegue | Gestión de Documentación e Informe Final |
|---|---|---|---|---|---|---|
| Bellido Salas, Raúl             | raulbellidosalas | L | C | C | C | C |
| Borja Molina, Gabriel Sebastián | borj410 | C | C | C | C | L |
| Suárez Romero, Santiago Manuel  | SDarXx | C | C | L | C | C |
| Gómez Flores, Daniela Araceli   | DanieGF1 | C | L | C | C | C |
| Burga Loarte, Anaely Zarely     | userxx1000 | C | C | C | L | C |

#### 6.2.1.3. Sprint Backlog 1

| User Story Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **US37** | Visualizar información | TS01 | Project Setup & Landing Framework | Configuración inicial del proyecto Vue.js, estructura de carpetas y layout base de la Landing Page. | 8 | Developer Team | Done |
| **US37** | Visualizar información | TS02 | Hero Section Development | Implementación de la sección principal con eslogan, logo y propuesta de valor de NexBell. | 4 | Developer Team | Done |
| **US38** | Visualizar funciones | TS03 | Features Grid Implementation | Creación de componentes visuales para listar las funciones de captura de video y alertas IoT. | 6 | Developer Team | Done |
| **US39** | Visualizar beneficios | TS04 | Benefits Section Styling | Maquetado de la sección comparativa de seguridad y ahorro de costos usando CSS (kebab-case). | 6 | Developer Team | Done |
| **US40** | Visualizar contacto | TS05 | Contact Form & Footer | Desarrollo del formulario de contacto y footer con enlaces a redes sociales y soporte técnico. | 5 | Developer Team | Done |
| **US41** | Navegar secciones | TS06 | Navigation & Smooth Scroll | Implementación del Navbar responsivo y lógica de desplazamiento suave entre secciones de la página. | 4 | Developer Team | Done |
| **US01, US02** | Registros | TS07 | Registration Views (UI) | Diseño de las vistas de registro para Residentes y Porteros con validaciones de formulario en el lado del cliente. | 10 | Developer Team | Done |
| **US03** | Iniciar sesión | TS08 | Login View (UI) | Creación de la interfaz de inicio de sesión con campos para credenciales y acceso al panel. | 6 | Developer Team | Done |
| **US15** | Visualizar espera | TS09 | Dashboard Layout & Sidebar | Estructura principal del panel administrativo del Portero, incluyendo barra lateral de navegación. | 8 | Developer Team | Done |
| **US15** | Visualizar espera | TS10 | Waiting List Component (Mock) | Desarrollo del componente de lista en tiempo real usando un archivo JSON de datos simulados (Mocks). | 10 | Developer Team | Done |
| **US16** | Visualizar foto | TS11 | Photo Detail Modal | Implementación de la ventana modal para visualizar las capturas HD de los visitantes (con imágenes de prueba). | 7 | Developer Team | Done |
| **General** | Deployment | TS12 | Netlify CI/CD Pipeline | Configuración de la automatización en Netlify para que cada commit en GitHub despliegue la versión actual. | 4 | Developer Team | Done |
| **General** | Documentation | TS13 | Styles & Conventions Audit | Revisión final de código para asegurar cumplimiento de la guía de estilos (Naming en inglés, PascalCase en Vue). | 6 | Developer Team | Done |

#### 6.2.1.4. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited On |
|---|---|---|--|---|---|
| Nexbell-LandingPage | main | f74d36f9be37815f4d4269f066925e176ac228bc | feat: landing page nexbell redesign | - | 11/05/2026 |
| Nexbell-FrontendWeb | main | adae769981822605f367ed6a61c290aad7185450 | feat: initial project setup | - | 10/05/2026 |
| Nexbell-FrontendWeb | develop | adae769981822605f367ed6a61c290aad7185450 | feat: initial project setup | - | 10/05/2026 |
| Nexbell-FrontendWeb | develop | b7d65c0066ed41c231604d237e7c271e195c3282 | feat: build NexBell doorman web app from Figma mockups | Setup Tailwind CSS v3 with NexBell color palette and Space Grotesk/Geist fonts <br> Configure Vue Router with all routes for auth and doorman flows <br> Create DoormanLayout with sidebar navigation and logout modal <br> Auth views: Login (split layout), Register, RegisterSuccess, ForgotPassword <br> Doorman views: Welcome, Dashboard, Visitors (verify/approve/reject), History (with date filter modal), Profile, EditProfile, Settings, Support <br> Build compiles cleanly with zero TypeScript errors | 11/05/2026 |
| Nexbell-FrontendWeb | develop | d6aa9ab87999c3f50c5516b43ab7a96e3144da78 | feat: add stores, composables, data layer and fix dependencies | Add Pinia stores: authStore (login/register/logout) and visitorsStore (approve/reject) <br> Add composables: useI18n and useTheme with localStorage persistence <br> Add seed data: users.json, visitors.json, accessHistory.json <br> Add i18n locales: en.ts and es.ts <br> Add TypeScript types: User, Visitor, AccessRecord, DoorEvent <br> Add pinia and lucide-vue-next as official dependencies | 11/05/2026 |
| Nexbell-FrontendWeb | develop | 2935d471dbbbfbf22427cf6599acbf0384387088 | feat: integrate Pinia for state management, enhance visitor registration, and improve UI components | - | 11/05/2026 |
| Nexbell-FrontendWeb | develop | eac4a5dd51bad9650954b6be5a10f2a487474ca2 | feat: complete doorman web app - i18n, theme, charts, profile, notification | - | 12/05/2026 |
| Nexbell-FrontendWeb | feature/login | eac4a5dd51bad9650954b6be5a10f2a487474ca2 | feat: complete doorman web app - i18n, theme, charts, profile, notification | - | 12/05/2026
| Nexbell-FrontendWeb | develop | fc500aaba60edf64b7ffd3c2a9baa60b3e2f4a65 | Merge pull request #1 from Nexora-solution/feature/login | - | 12/05/2026 |

#### 6.2.1.5. Testing Suite Evidence for Sprint Review

En esta sección se presentan las evidencias correspondientes a la suite de pruebas diseñada bajo el enfoque BDD. Para ello, se elaboraron archivos .feature utilizando el lenguaje Gherkin. Esta estructura permite describir el comportamiento esperado del sistema de forma clara, verificable y alineada con los criterios de aceptación establecidos para cada historia de usuario.

<p align="center">
  <img src="https://i.imgur.com/plIOw2P.jpeg" alt="g1" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/kIirKpZ.jpeg" alt="g2" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/M6YPG6h.jpeg" alt="g3" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/kNMYB9O.jpeg" alt="g4" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/rF2gxey.jpeg" alt="g5" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/LihbDFc.jpeg" alt="g6" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/l1EaB5H.jpeg" alt="g7" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/2qmdERQ.jpeg" alt="g8" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/DROK0Wj.jpeg" alt="g9" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/HxUPvdN.jpeg" alt="g10" width="1000">
</p>

#### 6.2.1.6. Execution Evidence for Sprint Review



#### 6.2.1.7. Services Documentation Evidence for Sprint Review

Durante el presente sprint no se realizaron actividades de desarrollo sobre el Backend, por lo que no se generaron nuevos endpoints ni modificaciones en las rutas de servicios existentes. En consecuencia, esta sección se conserva como evidencia de referencia documental, indicando que no aplica la inclusión de una tabla de endpoints para este incremento. La implementación de servicios web será incorporada en sprints posteriores, cuando se aborde el desarrollo del backend correspondiente.

#### 6.2.1.8. Software Deployment Evidence for Sprint Review
Durante el presente Sprint, el equipo Nexora ha establecido las bases de la infraestructura de entrega continua (CD) para los componentes públicos y administrativos de la solución NexBell. Las actividades de despliegue se centraron en el aprovisionamiento de recursos en la plataforma Netlify, seleccionada por su eficiencia en la distribución de contenido estático y SPA (Single Page Applications).

El proceso incluyó la creación de la organización del proyecto, la vinculación directa con los repositorios de GitHub para habilitar Continuous Deployment y la configuración de las variables de entorno necesarias para la ejecución de los componentes desarrollados en Vue.js. A continuación, se detallan los enlaces de acceso y las evidencias del despliegue exitoso para cada producto digital:

##### NexBell Landing Page Deployment
<p align="center">
  <img src="https://i.imgur.com/hHFvYN9.png" alt="landing-page" width="1000">
</p>

Link de acceso a la Landing Page: [https://nexbell.netlify.app/](https://nexbell.netlify.app/)

##### NexBell Web Application (Frontend) Deployment



#### 6.2.1.9. Team Collaboration Insights during Sprint
A través del análisis de las métricas de GitHub, se evidencia la sinergia alcanzada por el equipo de Nexora durante este primer ciclo de desarrollo. Los Insights reflejan una distribución equitativa del trabajo y una resolución ágil de conflictos mediante revisiones constantes. Esta cohesión permitió superar los obstáculos técnicos iniciales en la arquitectura, transformando los desafíos en un esfuerzo colectivo que culminó con la entrega exitosa de la primera versión funcional de Fluxus.

<p align="center">
  <img src="https://i.imgur.com/0XXKy9k.jpeg" alt="team-collaboration" width="1000">
</p>

<p align="center">
  <img src="https://i.imgur.com/YvS9aeV.jpeg" alt="team-collaboration" width="1000">
</p>

<div style="page-break-after: always;"></div>

# Conclusiones

 - Durante el desarrollo del AV1, el equipo logró establecer una base conceptual y arquitectónica sólida para el sistema Nexora, partiendo desde la identificación del problema hasta la estructuración técnica completa del proyecto. El proceso de investigación inicial, que incluyó entrevistas con usuarios potenciales, análisis de antecedentes y la elaboración de artefactos de needfinding como user personas, user journey maps y empathy maps, permitió comprender en profundidad las limitaciones de los sistemas de intercomunicación tradicionales en edificios residenciales y validar la propuesta de valor del sistema. Esta base de conocimiento orientada al usuario se tradujo en decisiones de diseño coherentes y fundamentadas, garantizando que Nexora responde a necesidades reales y no a supuestos sin sustento.

 - La adopción de Domain-Driven Design como enfoque arquitectónico central del proyecto demostró ser una decisión acertada para gestionar la complejidad del dominio de Nexora. La identificación y definición de cinco bounded contexts, IAM, Security, Directory, Intercom & Notifications y Audit, permitió al equipo separar responsabilidades de forma clara, evitar el acoplamiento entre módulos y establecer contratos de comunicación bien definidos entre servicios. El nivel de detalle alcanzado en cada contexto, incluyendo entidades, value objects, agregados, interfaces de dominio, eventos de dominio y capas de aplicación e infraestructura, evidencia que el equipo no solo comprendió los conceptos teóricos del DDD sino que fue capaz de aplicarlos de manera concreta al dominio del problema planteado.

 - La estructuración del product backlog y la definición de las historias de usuario con criterios de aceptación en formato Gherkin representaron un avance significativo en la planificación del desarrollo del sistema. La organización de cuarenta y un historias en ocho épicas, priorizadas según el valor que cada funcionalidad aporta al negocio, proporciona al equipo una hoja de ruta clara y ejecutable para las siguientes entregas. Este trabajo de planificación, combinado con la arquitectura técnica definida mediante los diagramas de componentes, clases de dominio y base de datos para cada bounded context, sitúa al equipo en una posición favorable para iniciar el desarrollo del sistema con claridad sobre qué construir, en qué orden y bajo qué criterios de calidad verificables.

<div style="page-break-after: always;"></div>

# Bibliografía
* Asociación Peruana de Empresas de Seguros. (2024, 18 de diciembre). *Una de cada diez viviendas sufrió un robo o intentaron robarla este año*. APESEG. Recuperado el 16 de abril de 2026, de [https://www.apeseg.org.pe/2024/12/una-de-cada-diez-viviendas-sufrio-un-robo-o-intentaron-robarla-este-ano/](https://www.apeseg.org.pe/2024/12/una-de-cada-diez-viviendas-sufrio-un-robo-o-intentaron-robarla-este-ano/)
* Cámara Peruana de la Construcción (2019, Octubre). *Costos y Presupuestos en Edificación*. CAPECO. Recuperado el 6 de mayo de 2026, de [https://topodata.com/wp-content/uploads/2019/10/Costos-y-Presupuestos-en-Edificacion-CAPECO.pdf](https://topodata.com/wp-content/uploads/2019/10/Costos-y-Presupuestos-en-Edificacion-CAPECO.pdf)
* Colegio de Arquitectos del Perú Regional Lima (2025, Enero). *VALORES UNITARIOS A COSTO DIRECTO DE ALGUNAS OBRAS COMPLEMENTARIAS E INSTALACIONES FIJAS Y PERMANENTES LIMA METROPOLITANA Y PROVINCIA CONSTITUCIONAL DEL CALLAO AL 31 DE OCTUBRE DE 2024*. Limacap. Recuperado el 6 de mayo de 2026, de [https://limacap.org/wp-content/uploads/2025/01/Valores-de-obras-complementarias-2025.pdf](https://limacap.org/wp-content/uploads/2025/01/Valores-de-obras-complementarias-2025.pdf)
* ComexPerú. (2026, 2 de febrero). *Inseguridad en cifras: ¿qué muestran las denuncias?*. ComexPeru. Recuperado el 16 de abril de 2026, de [https://www.comexperu.org.pe/articulo/inseguridad-en-cifras-que-muestran-las-denuncias](https://www.comexperu.org.pe/articulo/inseguridad-en-cifras-que-muestran-las-denuncias)
* Consultoría & Servicios en Hidrocarburos y Minería S.A.C. (2019, Julio). *Servicio de estudio de corrosión en Piura y Tumbes- Electronoroeste S.A.*. Osinergmin. Recuperado el 6 de mayo de 2026, de [https://www2.osinergmin.gob.pe/GRT/Procesos-Regulatorios/VAD-2019-2023/VAD-2019-2023-9-Electronoroeste_Informe%20Corrosi%C3%B3n%2001.pdf](https://www2.osinergmin.gob.pe/GRT/Procesos-Regulatorios/VAD-2019-2023/VAD-2019-2023-9-Electronoroeste_Informe%20Corrosi%C3%B3n%2001.pdf)
* Instituto Nacional de Estadística e Informática. (2026, marzo). Victimización en el Perú 2025. INEI. Recuperado el 16 de abril de 2026, de [https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib2076/index.html](https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib2076/index.html)
* Seisa (2025, 14 de agosto). *Fallas intermitentes en equipos eléctricos: Causas y solución con el Osciloscopio Serie 2 MSO-EDU*. Seisa. Recuperado el 6 de mayo de 2026, de [https://seisa.com.co/fallas-intermitentes-en-equipos-electricos-causas-y-solucion-con-el-osciloscopio-serie-2-mso-edu/?srsltid=AfmBOoo5cojL6JiRAIzLx9f2mtgWt50ZBgYlMyyMjT4cyrS5r5Lt-WmZ](https://seisa.com.co/fallas-intermitentes-en-equipos-electricos-causas-y-solucion-con-el-osciloscopio-serie-2-mso-edu/?srsltid=AfmBOoo5cojL6JiRAIzLx9f2mtgWt50ZBgYlMyyMjT4cyrS5r5Lt-WmZ)
* Sunat (2022). *Tabla de Tiempos de Vida Útil de los Equipos*. Sunat. Recuperado el 6 de mayo de 2026, de [https://www.sunat.gob.pe/legislacion/superin/2022/anexo-071-2022.pdf](https://www.sunat.gob.pe/legislacion/superin/2022/anexo-071-2022.pdf)

<div style="page-break-after: always;"></div>

# Anexos

* Big Picture Event Storming: [https://miro.com/welcomeonboard/b05EK1NyM2xabzdKenlkS1BLZnJtU2hHSTV6b2dRdWlRb1hmaFhraVpINTk0RTU0eWR4Wll4MisvbDRZV1B6NkQ2VFFpbUZLS3p3cXhIdXVPR0ZwQ1M5RXhhZk9iZ2ptOTR4Rmx2RXpVZkYwMi90WFdlZm05Vkg2TG9LSHZCNkd3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=240856445434](https://miro.com/welcomeonboard/b05EK1NyM2xabzdKenlkS1BLZnJtU2hHSTV6b2dRdWlRb1hmaFhraVpINTk0RTU0eWR4Wll4MisvbDRZV1B6NkQ2VFFpbUZLS3p3cXhIdXVPR0ZwQ1M5RXhhZk9iZ2ptOTR4Rmx2RXpVZkYwMi90WFdlZm05Vkg2TG9LSHZCNkd3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=240856445434)
* Link del Keynote:
[https://canva.link/i6aikeu52j3nqwg](https://canva.link/i6aikeu52j3nqwg)
* Link del Video de exposición:
[https://1drv.ms/v/c/efacef44bdb3cff4/IQBm1zy7b_qNSbRAuI_wKHYxAbjVaCgbniIWZQCTtqWtAcU?e=rZWk2d](https://canva.link/i6aikeu52j3nqwg)
