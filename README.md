# Apunts_UF1_1

# Elementos del desarrollo de software
---

# Introducción

## Tipos de Software

  - **De sistema** (Sistema operativo, drivers)
  - **De aplicacion** (Suite ofimática, Navegador, Edición de imagen, ...)
  - **De desarrollo** (Editores, Compiladores, Interpretes, ...)

## Relación Hardware-Software

  - **Disco duro**: Almacena de forma permanente los datos.
  - **Memoria RAM**: Almacena de forma temporal el código binario de los archivos.
  - **CPU**: Lee y ejecuta instrucciones almacenadas en memoria RAM.
  - **E/S**: Recoge datos desde la entrada(*Ejemplo: Un raton*), se muestran los resultados,se leen/guardan en el disco,...

## Códigos fuente, objeto y ejecutable
 
 - **Código fuente**: Archivo de texto legible escrito en un lenguaje de programación.
 - **Código objeto**: Archivo binario no ejecutable.
 - **Código ejecutable**: Archivo binario ejecutable

# Ciclo de vida del software
---

## Desarrollo de software
\
Fases Principales
 - [**Analisis**](https://github.com/MrWanArab/Apunts_UF1_1/blob/main/README.md#analisis)
 - [**Diseño**](https://github.com/MrWanArab/Apunts_UF1_1/blob/main/README.md#dise%C3%B1o)
 - [**Codificación**](https://github.com/MrWanArab/Apunts_UF1_1/blob/main/README.md#codificaci%C3%B3n)
 - [**Pruebas**](https://github.com/MrWanArab/Apunts_UF1_1/blob/main/README.md#pruebas)
 - [**Mantenimiento**](https://github.com/MrWanArab/Apunts_UF1_1/blob/main/README.md#mantenimiento)

### Analisis

 - Se determina las necesidades de los clientes i los requisitos que debe cumplir.
 - La especificación de requisitos debe:
    - Ser completa y sin omisiones
    - Ser concisa y sin trivialidades
    - Evitar ambigüedades
    - Evitar detalles de diseño o implementación
    - Ser entendible por el cliente
    - Separar requisitos funcionales y no funcionales
    - Dividir y jerarquizar el modelo
    - Fijar criterios de validación

### Diseño

 - Se organiza el sistema en elementos que pueden ser desarrollados por separado.
 - Las actividades habituales son las siguientes:
    - Diseño arquitectónico
    - Diseño detallado
    - Diseño de datos
    - Diseño de interfaz

### Codificación

 - Se escribe el código fuente de cada componente.
 - Pueden utilizarse distintos lenguajes informáticos:
    -  **Lenguajes de programación**: C, C++, Java, Javascript, ...
    -  **Lenguajes de otro tipo**: HTML, XML, JSON, ...

### Pruebas

 - El principal objetivo de las pruebas debe ser conseguir que el programa funcione incorrectamente y que se descubran defectos.
 - Deberemos someter al programa al máximo número de situaciones diferentes.
 
### Mantenimiento

 - Se realizan cambios (fallos encontrados en las pruebas, mejoras, etc).
 - Tipos de mantenimiento:
    - **Correctivo**: se corrigen defectos.
    - **Perfectivo**: se mejora la funcionalidad.
    - **Evolutivo**: se añade funcionalidades nuevas.
    - **Adaptativo**: se adapta a nuevos entornos.

### Resultado tras cada fase (I)

 - Ingeniería de sistemas: **Especificación del sistema**
 - Análisis: **Especificación de requisitos del software**
 - Diseño arquitectónico: **Documento de arquitectura del software**
 - Diseño detallado: **Especificación de módulos y funciones**
 - Codificación: **Código fuente**

 ### Resultado tras cada fase (II)

 - Pruebas de unidades: **Módulos utilizables**
 - Pruebas de integración: **Sistema utilizable**
 - Pruebas del sistema: **Sistema aceptado**
 - Documentación: **Documentación técnica y de usuario**
 - Mantenimiento: **Informes de errores y control de cambios**
 
 ## MODELOS DE DESARROLLO DE SOFTWARE

### MODELOS CLÁSICOS (PREDICTIVOS)

#### MODELO EN CASCADA

  - Modelo más antiguo.
  - Identifica las dases principales del desarrollo software.
  - Las fases han de realizarse en el orden indicado.
  - El resultado de una face de entrada a la siguiente fase.
  - Modelo bastante rígido que no se adapta bien a futuros cambios/actualizaciones.
  - Existen diferentes variantes.  

#### MODELO EN V

  - Modelo parecido al modelo de cascada
  - Visión jerarquizada en distintos niveles.
  - Mas abstraccion en niveles superiores
  - Niveles interiores mas detallados.
  - El resultado de una fase es la entrada de otra.
  - Existen diferentes variantes.  

### Modelo de construcción de prototipos

  - Los requisitos no están especificados claramente(a menudo):
    - Existencia previa nula.
    - Omisión o falta de concreción de usuario/cliente.
    
  - Proceso:
    - Se crea el prototipo durante la fase de análisis y es probado por el usuario/cliente.
    - El paso anterior se repite las veces necesarias.
  
  - Tipos de prototipos:
    - **Prototipos rápidos**: puede estar desarrollado usando otro lenguaje y/o herramientas i el prototipo al final se desecha.
    - **Prototipos evolutivos**: está diseñado en el mismo lenguaje y herramientas y se usa como base para desarrollar el proyecto.
    
### Modelos evolutivos o incrementales

#### Modelo en espiral (iterativos)
  
  - La actividad de ingeniería corresponde con las fases del modelo.
  - Se da gran importáncia a la reutilización de código.

#### Metodologías ágiles (adaptativos)

  - Métodos de ingeniería del software basados en el desarrollo iterativo e incremental.
  - Los requisitos y soluciones van evolucionando con el tiempo según las necesidades en el proyecto.
  - El trabajo se hace colaborativo mediante los equipos de trabajo.
  - Metdologías más conocidas:
    - Kanban
    - Scrum
    - XP (Programación Extrema)

#### XP (PROGRAMACIÓN EXTREMA): VALORES UTILIZADOS 
  - Simplicidad
  - Comunicación
  - Retroalimentación (comunicacion mútua)
  - Valentía o coraje ()/
  - Respeto o humildad (respetar trabajo entre mútuos)
 

## LENGUAJES DE PROGRAMACIÓN 

### Otención de código ejecutable

Para obtener un código binario ejecutable, tenemos 2 opciones:
  - Compilar
  - Interpretar
 
#### Compilar

  Compilar significa que el código que escribimos, lo transformamos a un código
  que entienden las máquinas y de esta forma, obtener un programa ejecutable
  que se pueda leer fácilmente entre ordenadores y máquinas
  
#### Ejemplos lenguajes compilados
  - C, C++
  - Principal ventaja: La ejecución de estos, es muy eficiente.
  - Principal desventaja: Es necesaria la compilación cada vez que modifiquemos el código fuente

#### Interpretar

  En programación, interpretar, és analizar y ejecutar otros programas mediante
  a un programa informático (intérprete).
  
#### Ejemplos lenguajes compilados

  - PHP, Javascript
  - Principal ventaja: El código guente se interpreta de forma directa
  - Principal desventaja: Su ejecución es menos eficiente.
  
### ¿Cual es el proceso de compilación / interpretación?

  - La compilación/interpretación del código se lleva a cabo en 2 tipos de fases:
    - Análisis léxico
    - Análisis sintáctico
  - Si no hay ninguna existencia de errores, se genera el código objeto correspondiente.
  - Un código fuente correctamente escrito no quiere significar que funcione según lo deseado.
  - No se realiza un análisis semántico.
  
### JAVA

  - Lenguajes compilado e interpretado
  - El código fuente Java se compila y se obtiene un código binario intermedio que se denomina **bytecode.
  - Se puede considerar como un código objeto pero destinado a la máquina virtual de Java en lugar de código objeto nativo.
  - Después, el **Bytecode** se interpreta para ejecutarlo.
  - Ventajas:
    - Estructurado y orientado a objetos.
    - Relativamente su aprendizaje es fácil.
    - Buena documentación y base de usuarios
  - Desventajas:
    - Menos eficiente que los lenguajes compilados

### Tipos
  - Según la forma en la que operan:
    - **Declarativos**: indicamos el resultado sin especificar préviamente los pasos a realizar.
    - **Imperativos**: indicamos los pasos a seguir para obtener un resultado a cabo.
  
  - Tipos de lenguajes **declaratvos**:
    - Lógicos: Utilizan reglas
    - Funcionales: Utilizan funciones
    - Algebráicos: Utilizan sentencias
  - Normalmente son lenguajes interpretados.<br>

<br>

  - Tipos de lenguajes **imperativos**:
    - Son estructurados
    - Están orientados a objetos
    - Son multiparadigma
  - Los lenguajes orientados  a objetos son también lenguajes estructurados.
  - Muchos de estos lenguajes son compilados.

<br>

  - Tipos de lenguajes según su nivel de **abstracción**:
    - Bajo nivel: ensamblador
    - Medio nivel: C
    - Alto nivel: C++, Java
    
### Criterios para la selección de un lenguaje de programación

  A la hora de elegir un lenguaje de programación para hacer desarrollo de software, hemos de tener en cuenta unos criterios básicos, estos són:

  - En que campo aplicación se encuentra.
  - Tener experiéncia previa.
  - Que herramienta de desarrollo se utilitza.
  - Mirar si hay una documentación disponible.
  - Tener una base de usuarios.
  - Si el lenguaje es reusable i portable.
  - Iposición de nuestro cliente.
