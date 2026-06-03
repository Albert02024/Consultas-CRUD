# SQL Fundamentals: CRUD y JOINs

## Descripción

SQL (Structured Query Language) es el lenguaje estándar para interactuar con bases de datos relacionales. Es una habilidad fundamental para cualquier desarrollador backend, independientemente del lenguaje o framework utilizado, ya sea Node.js, Python, Golang, Java, PHP, entre otros.

En esta tarea se trabajarán los conceptos esenciales de SQL, enfocándose en las operaciones **CRUD** (Create, Read, Update, Delete) y en el uso de **JOINs** para relacionar información entre múltiples tablas.

Dominar estos conceptos permite construir aplicaciones capaces de almacenar, consultar y manipular datos de manera eficiente, constituyendo la base de cualquier sistema backend profesional.

---

## Objetivos

- Comprender la estructura básica de una base de datos relacional.
- Aprender a realizar operaciones CRUD utilizando SQL.
- Entender cómo funcionan las relaciones entre tablas.
- Utilizar JOINs para combinar información proveniente de diferentes tablas.
- Escribir consultas SQL claras, eficientes y mantenibles.

---

## Temas a Practicar

### 1. CREATE (Crear)

Insertar nuevos registros en una tabla.

```sql
INSERT INTO usuarios (nombre, correo)
VALUES ('Juan Pérez', 'juan@email.com');
