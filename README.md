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
          * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problem%C3%A1tica)
          * [1.2.2. Lean UX Process](#122-lean-ux-process)
              * [1.2.2.1. Lean UX Problem Statements](#12221-lean-ux-problem-statements)
              * [1.2.2.2. Lean UX Assumptions](#12222-lean-ux-assumptions)
              * [1.2.2.3. Lean UX Hypothesis Statements](#12223-lean-ux-hypothesis-statements)
              * [1.2.2.4. Lean UX Canvas](#12224-lean-ux-canvas)
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



# CAPÍTULO I: INTRODUCCIÓN

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


### 1.1.2. Perfiles de los integrantes del equipo


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements


#### 1.2.2.2. Lean UX Assumptions


#### 1.2.2.3. Lean UX Hypothesis Statements


#### 1.2.2.4. Lean UX Canvas


## 1.3. Segmentos objetivo


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


# CAPÍTULO III: REQUIREMENTS SPECIFICATION

## 3.1. User Stories


## 3.2. Impact Mapping


## 3.3. Product Backlog


# CAPÍTULO IV: SOLUTION HADWARE DESIGN

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming


#### 4.1.1.1. Candidate Context Discovery


#### 4.1.1.2. Domain Message Flows Modelling


#### 4.1.1.3. Bounded Context Canvases


### 4.1.2. Context Mapping


### 4.1.3. Software Architecture


#### 4.1.3.1. Software Architecture System Langscape Diagram


#### 4.1.3.2. Software Architecture Context Level Diagram



### 4.1.3.3. Software Architecture Deployment Diagrams


## 4.2. Tactical-Level Domain-Driven Design


<!-- copiar por número de bcs -->

### 4.2.1. Bounded Context: <!-- nombre -->

#### 4.2.1.1. Domain Layer

#### 4.2.1.2. Interface Layer

#### 4.2.1.3. Application Layer

#### 4.2.1.4. Infrastructure Layer

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Container Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.1.6.2. Bounded Context Database Design Diagram

<!-- copiar por número de bcs -->
