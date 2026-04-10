<p align="center">
  <img src="https://i.imgur.com/frPdUOx.png" alt="logo">
</p>

# <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
## <p align="center">Ingeniería de Software</p>

<p align="center">Periodo: 2026-10</p>
<p align="center">1ASI0572 | Desarrollo y Soluciones IOT</p>
<p align="center">NRC: 6785</p>
<p align="center">Docente: Marco Antonio León Baca</p>

---

## <p align="center">Informe del TB1</p>

<p align="center"><b>Startup:</b> Nexora</p>
<p align="center"><b>Producto:</b> NexBell</p>

<br>

<center>

## Integrantes
| **Código**  | **Apellidos y nombres**  |
| :---: | :---: |
| U20231b866  | Bellido Salas, Raúl |
| U202311184  | Borja Molina, Gabriel Sebastián |
| U202318049  | Suárez Romero, Santiago Manuel |
| U202314513  | Gómez Flores, Daniela Araceli |
| U202318615  | Burga Loarte, Anaely Zarely |

</center>

<hr>

<p align="center">Abril 2026</p>

<br>

# REGISTRO DE VERSIONES DE INFORME

<center>

| Versión  | Fecha  | Autor  | Descripción de modificación  |
| :---: | :---: | ----- | ----- |
| TB1  | xx/04/2026  | **Bellido Salas Raúl <br>  Borja Molina, Gabriel Sebastián <br> Suárez Romero, Santiago Manuel  <br> Gomez Flores, Daniela Araceli <br> Burga Loarte, Anaely Zarely**  | Para este primer avance  |

</center>

# PROJECT COLLABORATION INSIGHTS



# Contenido

Aquí tienes la continuación del índice en formato Markdown, manteniendo la estructura jerárquica y los enlaces internos solicitados para completar el documento:

-----

  - [STUDENT OUTCOME](#student-outcome)
  - [CAPÍTULO I: INTRODUCCIÓN](#capítulo-i-introducci%C3%B3n)
      * [1.1. Startup Profile](#11-startup-profile)
          * [1.1.1. Descripción de la Startup](#111-descripci%C3%B3n-de-la-startup)
          * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
      * [1.2. Solution Profile](#12-solution-profile)
          * [1.2.1. Nombre del producto](#121-nombre-del-producto)
          * [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problem%C3%A1tica)
          * [1.2.3. Lean UX Process](#123-lean-ux-process)
              * [1.2.3.1. Lean UX Problem Statements](#1231-lean-ux-problem-statements)
              * [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
              * [1.2.3.3. Lean UX Hypothesis Statements](#1233-lean-ux-hypothesis-statements)
              * [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
      * [1.3. Segmentos objetivo](#13-segmentos-objetivo)
  - [CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS](capítulo-ii-requirements-elicitation--analysis)
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
  - [CAPÍTULO III: REQUIREMENTS SPECIFICATION](capítulo-iii-requirements-specification)
      * [3.1. User Stories](#31-user-stories)
      * [3.2. Impact Mapping](#32-impact-mapping)
      * [3.3. Product Backlog](#33-product-backlog)
  - [CAPÍTULO IV: SOLUTION SOFTWARE DESIGN](capítulo-iv-solution-software-design)
      * [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
          * [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
              * [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
              * [4.1.1.2. Domain Message Flows Modelling](#4112-domain-message-flows-modelling)
              * [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
          * [4.1.2. Context Mapping](#412-context-mapping)
          * [4.1.3. Software Architecture](#413-software-architecture)
              * [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
              * [4.1.3.2. Software Architecture Context Level Diagram](#4132-software-architecture-context-level-diagram)
              * [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
      * [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
          * [4.2.1. Bounded Context: [Nombre]](#421-bounded-context-nombre)
              * [4.2.1.1. Domain Layer](#4211-domain-layer)
              * [4.2.1.2. Interface Layer](#4212-interface-layer)
              * [4.2.1.3. Application Layer](#4213-application-layer)
              * [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
              * [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
              * [4.2.1.6. Bounded Context Software Architecture Container Level Diagrams](#4216-bounded-context-software-architecture-container-level-diagrams)
                  * [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
                  * [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)


# STUDENT OUTCOME

El curso contribuye al cumplimiento del Student Outcome **ABET: ABET – EAC - Student Outcome 7: Aprendizaje Continuo y Autónomo** <br>
**Criterio:**  *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos* <br>
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del equipo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome.

<center>

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---|---|---|
| a | b | c |

</center>
<br>

# CAPÍTULO I: INTRODUCCIÓN

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nexora es una startup peruana integrada por estudiantes de la UPC, dedicada a redefinir la seguridad y la convivencia en entornos residenciales mediante soluciones avanzadas de Internet de las Cosas (IoT). Nuestra misión es transformar espacios convencionales, como edificios multifamiliares y condominios, en entornos inteligentes y altamente funcionales.

Para lograrlo, nos enfocamos en reemplazar los sistemas tradicionales de intercomunicación por plataformas digitales modernas que permiten una gestión de accesos más eficiente y segura. Mediante el uso de dispositivos embebidos, aplicaciones web y notificaciones en tiempo real, ofrecemos una propuesta de valor centrada en la escalabilidad y la reducción de costos de mantenimiento. En Nexora, conectamos lo físico con lo digital para optimizar la experiencia de residentes y personal de seguridad, garantizando soluciones tecnológicas accesibles y de alto impacto. <br>

### Misión
Desarrollar soluciones tecnológicas innovadoras basadas en IoT que mejoren la seguridad y gestión de accesos en entornos residenciales, ofreciendo productos eficientes, accesibles y fáciles de usar.

### Visión
Ser una startup líder en Latinoamérica en soluciones inteligentes de seguridad residencial, destacando por la innovación, confiabilidad y accesibilidad de sus productos tecnológicos.

### 1.1.2. Perfiles de los integrantes del equipo

| Raúl Bellido | Ingeniería de Software |
| -- | --|
| <img src="#" height=200px width=200px> | Hola mundo |

| Gabriel Borja | Ingeniería de Software |
| -- | --|
| <img src="#" height=200px width=200px> | Soy un estudiante de la carrera de Ingeniería de Software en la UPC. Enfocado principalmente en el desarrollo web, busco especializarme en la elaboración de soluciones robustas y orientadas al usuario. Cuento con conocimiento de lenguajes como Python, C++ y C#. Me caracterizo por ser una persona creativa, amigable y responsable. Me comprometo a brindar mi apoyo al equipo para desarrollar el proyecto y aprobar el curso de manera satisfactoria. |

| Santiago Suárez | Ingeniería de Software |
| -- | --|
| <img src="#" height=200px width=200px> | Soy de la carrera de ingeniería de software. Mis cualidades son ser creativo, trabajar en grupo, me adapto a diferentes entornos. Además, siempre trato de apoyar con los conocimientos que he aprendido a lo largo de mi vida y siempre trato de aprender algo nuevo. |

| Daniela Gómez | Ingeniería de Software |
| -- | --|
| <img src="#" height=200px width=200px> | Soy Daniela Gómez Flores, estudiante de Ingeniería de Software en la UPC, actualmente cursando el 7mo ciclo. Me gusta trabajar de manera organizada, aprender cosas nuevas y mantener un buen equilibrio en mis actividades. La música es parte importante de mi día a día y me motiva a seguir creciendo tanto en lo académico como en lo personal.  |

| Anaely Burga | Ingeniería de Software |
| -- | --|
| <img src="#" height=200px width=200px> | Hola mundo |

## 1.2. Solution Profile

### 1.2.1. Nombre del producto

NexBell, el producto insignia de nuestra startup, es una solución integral de videoportero inteligente basada en tecnología IoT y una robusta plataforma web, diseñada para transformar la seguridad en edificios residenciales y condominios. Este sistema redefine la gestión de accesos al eliminar por completo la necesidad de cableado interno tradicional, lo que se traduce en una reducción drástica de los costos de instalación y mantenimiento para las juntas de propietarios.

La propuesta de valor de NexBell se centra en empoderar al personal de seguridad y conserjería, permitiéndoles validar visitas mediante video en tiempo real y enrutar las alertas de acceso directamente a los smartphones de los residentes a través de notificaciones móviles. Al integrar un registro digital detallado de cada ingreso, NexBell no solo agiliza la comunicación, sino que eleva los estándares de seguridad y moderniza la experiencia de vivir en comunidad mediante una gestión digitalizada, eficiente y escalable.

### 1.2.2. Antecedentes y problemática

Los edificios multifamiliares y condominios en Lima suelen depender de sistemas de intercomunicadores cableados tradicionales. Estos sistemas presentan múltiples puntos de falla (cables rotos en las paredes, teléfonos malogrados en los departamentos), su mantenimiento es altamente costoso para la junta de propietarios, y no ofrecen registro visual de quién ingresa al edificio. El problema central es la ineficiencia y vulnerabilidad en el control de accesos de edificios residenciales, causada por infraestructura analógica obsoleta que impide al personal de seguridad tener herramientas modernas de validación visual, registro auditable y comunicación asíncrona con los residentes.

<br>

Como parte del proceso de definición de la problemática, se aplicó la técnica The 5 W’s and 2 H’s (Who, What, Where, When, Why, How, How Much), permitiendo estructurar de manera preliminar la descripción de los antecedentes y el planteamiento del problema. 

#### Who?


#### What?


#### Where?


#### When?


#### Why?


#### How?


#### How much?


### 1.2.3. Lean UX Process

#### 1.2.3.1. Lean UX Problem Statements


#### 1.2.3.2. Lean UX Assumptions


#### 1.2.3.3. Lean UX Hypothesis Statements


#### 1.2.3.4. Lean UX Canvas


## 1.3. Segmentos objetivo

Para asegurar que la solución propuesta responda de manera efectiva a las necesidades del entorno residencial moderno, se han identificado dos segmentos clave dentro del dominio del problema. Estos segmentos representan tanto al cliente que adquiere la solución como al usuario que interactúa directamente con el sistema. <br>
A continuación, se detallan los perfiles estratégicos considerando sus características demográficas, geográficas y psicográficas, las cuales justifican su relevancia dentro del modelo de negocio.


1) **El Cliente Principal (Quién paga):** Juntas de Propietarios y Empresas Administradoras de Inmuebles
* **Perfil:** Administradores de edificios residenciales modernos o condominios en distritos de clase media/alta en Lima (ej. Miraflores, San Isidro, Surco, Lince).
* **Necesidad:** Reducir los gastos comunes del edificio (mantenimiento de cableado) y aumentar el valor/percepción de seguridad del inmueble mediante tecnología moderna.

2) **El Usuario Principal (Quién opera el sistema):** Personal de Seguridad / Conserjería
* **Perfil:** Hombres y mujeres entre 25 y 60 años, que trabajan en turnos rotativos en las recepciones de los edificios. Su nivel de habilidad tecnológica es variable (desde básico hasta intermedio).
* **Necesidad:** Una herramienta que sea rápida, a prueba de fallos y que les permita registrar visitantes sin tener que usar papel y lápiz, además de contactar al residente incluso si este no está en su departamento.

<br>

# CAPÍTULO II: REQUIREMENTS ELICITATION & ANALYSIS

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


### 2.3.3. User Journey Mapping


### 2.3.4. Empathy Mapping


## 2.4. Big Picture EventStorming


## 2.5. Ubiquitous Language

<br>

# CAPÍTULO III: REQUIREMENTS SPECIFICATION

## 3.1. User Stories


## 3.2. Impact Mapping


## 3.3. Product Backlog

<br>

# CAPÍTULO IV: SOLUTION HADWARE DESIGN

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming


#### 4.1.1.1. Candidate Context Discovery


#### 4.1.1.2. Domain Message Flows Modelling


#### 4.1.1.3. Bounded Context Canvases


### 4.1.2. Context Mapping


### 4.1.3. Software Architecture


#### 4.1.3.1. Software Architecture System Landscape Diagram


#### 4.1.3.2. Software Architecture Context Level Diagram



#### 4.1.3.3. Software Architecture Deployment Diagrams


## 4.2. Tactical-Level Domain-Driven Design


<!-- copiar por número de bcs -->

### 4.2.1. Bounded Context: [Nombre]

#### 4.2.1.1. Domain Layer

#### 4.2.1.2. Interface Layer

#### 4.2.1.3. Application Layer

#### 4.2.1.4. Infrastructure Layer

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Container Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.1.6.2. Bounded Context Database Design Diagram

<!-- copiar por número de bcs -->
