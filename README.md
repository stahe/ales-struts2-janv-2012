# Introducción al marco Struts 2 a través de ejemplos (2012)

🔗 **Curso en línea:**
[https://stahe.github.io/ales-struts2-janv-2012/](https://stahe.github.io/ales-struts2-janv-2012/)

---

## Resumen

Este documento ofrece una **introducción al marco Struts 2** mediante un enfoque paso a paso basado en ejemplos.

Struts 2 es un marco web de Java que ofrece lo siguiente:

* un conjunto de bibliotecas que se distribuyen en forma de archivos **JAR**
* un marco de desarrollo que brinda estructura al diseñar una aplicación web

El objetivo es comprender los conceptos básicos de Struts 2 en la práctica.

---

## Requisitos

Para poder seguir los ejemplos, se requiere lo siguiente:

* conocimientos básicos de **Java**
* conocimientos básicos de **desarrollo web**, especialmente **HTML**

Hay recursos adicionales disponibles en:

* [http://developpez.com](http://developpez.com)

---

## Referencias para profundizar más

Para más información:

* **[ref1]** Documentación oficial de Struts 2 (sitio web oficial del proyecto)
* **[ref2]** *Struts 2 in Action*
  Donald Brown – Chad Michael Davis – Scott Stanlick
  Manning Publishing

En este documento se hace referencia ocasionalmente a *Struts 2 in Action* para explicar con mayor detalle ciertos aspectos técnicos.

---

## Objetivo de aprendizaje

El documento está redactado de tal manera que se puede leer sin necesidad de una computadora.
Se han incluido numerosas capturas de pantalla para facilitar la comprensión.

---

## El papel de Struts 2 en una aplicación web

Struts 2 se encuentra **exclusivamente en la capa web** de una arquitectura típica de múltiples capas.

### Arquitectura general

Una aplicación web clásica puede estructurarse de la siguiente manera:

### 1️⃣ Capa web

* Interfaz con el usuario (navegador)
* Procesamiento de solicitudes HTTP
* Generación de respuestas
* **Struts 2 se encuentra exclusivamente en esta capa**

### 2️⃣ Capa de negocio

* Implementa las reglas de negocio
* Ejemplo: cálculo de un salario, generación de una factura
* Utiliza:

  * datos de la capa web
  * datos de la base de datos a través de la capa DAO

### 3️⃣ Capa DAO/JPA/JDBC

* Administración del acceso a los datos
* DAO: Objetos de Acceso a Datos
* JPA: API de persistencia de Java
* JDBC: acceso de bajo nivel a la base de datos
* JPA funciona como ORM (mapeador objeto-relacional)

### 4️⃣ Integración de las capas

Puede ser proporcionada por:

* **Spring**
* **EJB3 (Enterprise Java Bean)**

---

## Estructura de los ejemplos

La mayoría de los ejemplos de este documento **utilizan exclusivamente la capa web** para enfocar la atención en Struts 2.

Al final del documento se construye una **aplicación web completa de múltiples capas**:

* Capa web
* Capa de negocio
* Capa DAO
* Capa JPA/Hibernate
* Acceso a la base de datos mediante JDBC

Las capas de negocio y de persistencia se proporcionan en forma de archivo JAR, para que el lector pueda concentrarse principalmente en la capa web.

---

## Público objetivo

* Desarrolladores de Java que deseen descubrir Struts 2
* Estudiantes de desarrollo web en Java
* Cualquier persona que desee comprender la integración de Struts 2 en una arquitectura de múltiples capas

---

## Autor

Serge Tahé, Versión 2012

---
