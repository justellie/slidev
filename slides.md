---
# YAML block. p1
# > Sección: Introducción

theme: seriph
background: images/computer.jpg
layout: cover
---
# Model Driven Developing (MDE)
Universidad de Carabobo. Ingeniería de Software. 


<div class="abs-bl ml-14 mb-12 items-center" >
<span class="font-400">Integrantes</span>

<div class="flex">
<div class="ml-3 flex flex-col text-left">
    <span class="font-300">Jesús Pelay,</span>
    <span class="font-200">C.I: 26.804.859</span>
</div>


<div class="ml-3 flex flex-col text-left">
    <span class="font-300">Gabriel Peraza,</span>
    <span class="font-200">C.I: 26.929.687</span>
</div>

<div class="ml-3 flex flex-col text-left">
    <span class="font-300">Elio Ruíz</span>
    <span class="font-200">C.I: 27.877.261</span>
</div>
</div>
</div>


<div class="abs-br mr-14 mb-12 items-center" >
<span class="font-400">Docente<br></span>

<div class="flex">
<div class="ml-3 flex flex-col text-left">
    <span class="font-300">Dinarle Ortega</span>
    <span class="font-200"><br></span>
</div>

</div>
</div>

---
# YAML block. p2
layout: image-right
image: 'images/visco.jpg'
---

# Introducción

Ideas preliminares


Codificar resuelve problemas simples.

```python
c = 1
print( c + 1 )
```

Pero los problemas complejos requieren
de estructuras flexibles, ajustadas a la
necesidades de los clientes.

```java
EngineBuilder eng = logic.engineFactoryBuilder();
eng.build( abstract_model );
// ... Y muchas cosas más ...
```

<br>
<br>
<br>

_Y si trabajamos en equipo...  **¿cómo se coordinan las tareas?**_

---
# p3
layout: statement
---

# Se emplean modelos

---
# p4
layout: image-left
image: 'images/meeting.jpg'
---

# ¿Qué es un modelo?
<br>

> _Un modelo es una abstracción de algo con el propósito de
> entenderlo antes de construirlo. - [1]_

<br>



<br>
<br>

* Dirigen la **atención** a los aspectos de interés.
* Describen el **contexto** del problema.
* Determinan los **alcances** y **detalles** del problema.
* Definen como se debe **implementar** un sistema.

<br>
<br>

Es decir, son una _**Abstracción**_ del problema.
    

---
# p5
layout: default
---

# Modelado para el desarrollo de software.
<br>

### Modelos como bosquejos
Comunicación + Vistas parciales = Vistas parciales de la especificación del sistema.

<br>

### Modelos como planos

Descripción detallada de la especificación

<br>

### Modelos como programas

Modelos en lugar de `código` <carbon-arrow-right /> Desarrollo de sistemas.

---
# p6
layout: default
---

# MDSE
Model Driven Software Engineering

<div grid="~ cols-2 gap-4">

<div>

### Principios de MDSE
Está constituído por:

* Conceptos.
* Notaciones.
* Procesos y Reglas.
* Herramientas.

<br>
<br>

```
Modelos + Transformaciones = Software
```

</div>

<div>

<div class="text-center">
MDSE
</div>

![Metodología MDSE](images/mdse-methodology.png)


</div>
</div>




---
# p7
layout: image-right
image: 'images/md-jungle3.png'
---
# Muchos acrónimos similares **MD\*s**
La diversidad de MD\*s
<br>

1. MDD: Model-Driven Development. es un **paradigma** de desarrollo.

2. MDA: Model-Driven Architecture. es un **subconjunto** propuesto por le OMG.

3. **MDE:** Model-Driven Engineering. Es el **superconjunto** de MDD.

4. MBE: Model-Based Engineering. versión más flexible de **MDE**.





---
# p8
layout: default
---


# Metodología MDSE
Visión general

<div grid="~ cols-2 gap-4">
<div>


### Objetivo de MDSE
* Dominios.
* plataformas.
* Espacios técnicos.
* Escenarios.

<br>


</div>

<div>

### Lenguajes de modelado
* DSLs: Domain-Specific Languages.
    
    por ejemplo <carbon-arrow-right /> HTML


* GPMLs: General-Purpose Modeling Languages.

    el más conocido <carbon-arrow-right /> UML

</div>

</div>




---
# p9
layout: default
---

# Metodología MDSE
Visión general

<div grid="~ cols-2 gap-4">
<div>

### Metamodelado

Resalta las propiedades del modelo. Se emplean para modelar los
lenguajes de modelado y proveen un modo para describir todas las
clases de models que pueden representarse en ése lenguaje.


</div>

<div>

### Transformaciones

MDSE provee lenguajes para definir la transformación de modelos. Las
transformaciones también se tratan como modelos.


</div>

</div>

---
# p10
layout: default
---

# Metodología MDSE
Visión general

<div grid="~ cols-2 gap-4">
<div>

### Clasificación de los modelos

* **Modelos estáticos**

    describen formas estructurales, la arquitectura del sistema y cómo se gestiona la información.

* **Modelos dinámicos**

    Muestran la secuencia de ejecución de las acciones y los algoritmos, las colaboraciones entres los componentes, cambios de los estados internos, entre otros.





</div>

<div>

### Adopción de MDSE en la industria.

![Grafico de adopcion](images/acceptance.png)

</div>

</div>

<br>

---
# p11
layout: default
---

# Metodología MDSE
Visión general

<div grid="~ cols-2 gap-4">

<div>

### Soporte de herramientas

- Herramientas de Diagramas vs Herramientas de Modelado.
- Herramientas MDSE: Model-Based vs Programming-Based.

</div>

<div>

### Críticas a MDSE

> _Los modelos son valorados por las personas que no pueden
> programar. Desafortunadamente, no se valoran poruqe los
> modelos son más expresivos que los programas (dado que expresan
> ideas complejas de un modo sencillo), sino porque los modelos
> los simplifican excesivamente. - Friedrich Steimann_



</div>

</div>

---
# p12
layout: image-left
image: 'images/robo.webp'
---

# Casos de uso de MDSE
<br>

1. Automatización del desarrollo de software.

<br>

- Generación de `código`.
- Interpretación de _modelos_.
- Combinación de ambos enfoques.

<br>

2. Interoperabilidad del sistema

---
# p13
layout: section
---

# Arquitectura Dirigida por Modelos

---
# p14
layout: default
---

# Arquitectura Dirigida por Modelos (MDA)
<br>

Propuesta creada por _The Object Magement Group_ (OMG) para aplicar
las prácticas del MDE dentro del desarrollo de sistemas.

<br>

### Definiciones y suposiciones de MDA.

|     |     |     |
| --- | --- | --- |
| Sistema | Dominio del Problema | Espacio de Solución |
| Modelo | Arquitectura | Plataforma |
| ViewPoint | Vista | Transformación |




---
# p15
layout: default
---

# Arquitectura Dirigida por Modelos (MDA)
<br>

<div grid="~ cols-2 gap-4">
<div>

### Tres niveles de modelado:
* CIM: Computation-Independent Model.
* PIM: Platform-Independent Model.
* PSM: Plataform-Specific Model.

<br>

### Mapeos
 
correspondencias entre los elementos
de dos modelos distintos.


### Lenguajes dentro del MDA
* DSLs: Domain-Specific Languages.
* GPMLs: General-Purpose Modeling Languages.

</div>

<div>

![Niveles MDA](images/html.png)

</div>

</div>

---
# p16
layout: image-left
image: images/teamwork2.jpg
### usar la imagen p57 del libro
---

# Los lenguajes de modelado
<br>

### Anatomía de los lenguajes de modelado.

* Sintaxis abstracta.
* Sintaxis Concreta.
* Semántica.

---
# p17
layout: image-right
image: 'images/uml3.png'
---

# UML
Modelado de propósito general

### Prácticas de diseño

* Diagramas de estructura

    <carbon-arrow-right /> diagramas estáticos

* Diagramas de comportamiento

    <carbon-arrow-right /> diagramas dinámicos

### Herramientas UML
<br>

### Críticas y evolución

---
# p18
layout: image-right
image: 'images/dsl2.png'
---

# Las DSL
Visión general

- Principios básicos de los DSLs.
- ejemplos
- Restricciones de Modelado (OCL)

---
# p19
layout: section
---

# Transformaciones de modelo a texto

---
# p20
layout: default
---

# Transformaciones de modelo a texto

### Fundamentos de la generación de código basada en modelos
<br>

### Generación de código mediante...

* Lenguajes de programación
* Lenguajes de transformación MT.

---
# p21
layout: section
---

# Gestión de modelos

---
# p22
layout: image-right
image: 'images/deal.jpg'
---

# Gestión de modelos
<br>

### Comparación de Modelos

* Fase 1: Model Matching.
* Fase 2: Model Differencing:

Para los modelos de Eclipse Modeling Framework (EMF), existen
herramientas para diferenciar los modelos (herramientas de
automatización).

* EMF Compare.
* SiDiff.
* Epsilon Comparison Language (ECL).

---
# p23
layout: image-right
image: 'images/deal.jpg'
---

# Gestión de modelos

### Gestión global de modelos

El problema global de manejar el ecosistema.

### Calidad de los modelos

* Verificación de modelos.
* Prueba y validación de modelos.

---
# p24
layout: quote
---

_Para un hombre con martillo, todo luce como un clavo. Para
un Cientifico de Computación, todo se asemeja a los problemas
del diseño de un lenguaje. Los lenguajes y compiladores son,
en mi opinión, la única vía para llevar una idea a la
práctica - David Parnas_

---
# p24
layout: default
---

# Referencias
<br>

[1] J. Rumbaugh, M. Blaha, W. Premerlani, F. Eddy, and W. Lorensen. Object-Oriented Modeling and Design. Prentice Hall, Englewood Cliffs, New Jersey, USA, 1991.

[2] Jordi Cabot, and Manuel Wimmer. Model-Driven Software Engineering in Practice Marco Brambilla, 2012.
