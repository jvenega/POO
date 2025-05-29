
# 🧠 Proyecto de Gestión de Asistencia - Niveles de Desarrollo POO

Este repositorio aborda progresivamente la implementación de un sistema de gestión de asistencia usando Programación Orientada a Objetos (POO) en Python.

---

## 🧩 Nivel 1: Clases Base

### Objetivo

Crear la estructura base del sistema:

- `Usuario`
- `Marca`
- `Turno`

### Conceptos:

- Atributos y métodos simples
- Listas de objetos dentro de una clase (composición)
- Lectura y escritura básica de archivos

---

## 🧩 Nivel 2: Herencia y Tipos de Turno

### Objetivo

Implementar clases hijas:

- `TurnoDia` (permite minutos de atraso)
- `TurnoTarde` (permite retiro anticipado)

### Conceptos:

- Herencia (`class TurnoDia(Turno):`)
- Métodos sobrescritos
- Control de reglas personalizadas según el tipo de turno

---

## 🧩 Nivel 3: Planificación y Evaluación

### Objetivo

Implementar la clase `Planificacion` que contiene:

- Referencia a `Turno`
- Fecha
- Estado (presente/ausente)
- Minutos trabajados
- Minutos de atraso/retiro

### Conceptos:

- Asociación entre objetos
- Control de validaciones por día
- Cálculo de asistencia con condiciones

---

## 🧩 Nivel 4: Administrador

### Objetivo

Implementar un rol con mayores permisos:

- Clase `Administrador` que hereda de `Usuario`
- Capacidad de asignar planificaciones a otros usuarios

### Conceptos:

- Herencia con nuevas responsabilidades
- Métodos de administración del sistema

---

## 🧩 Nivel 5: Integración y Archivo de Salida

### Objetivo

Procesar archivos de entrada y generar reportes `rut.txt` por cada usuario.

### Conceptos:

- Manejo de archivos `.txt` estructurados
- Escritura de informes por usuario
- Comparación entre marcas y turnos para definir presencia

---

Cada nivel debe ser implementado y testeado individualmente para asegurar el correcto funcionamiento del sistema.
