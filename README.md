# Guía de Scrum

## Introducción

Scrum es un marco de trabajo ágil utilizado para la gestión de proyectos, especialmente en el desarrollo de software. Se centra en la colaboración, la adaptación y la entrega continua de productos de alta calidad. Scrum se basa en principios de transparencia, inspección y adaptación.

## Roles en Scrum

### 1. **Product Owner**

El Product Owner es el encargado de definir y priorizar los elementos del producto. Su responsabilidad principal es garantizar que el equipo trabaje en las tareas más valiosas para el cliente.

### 2. **Scrum Master**

El Scrum Master es el facilitador del equipo. Su rol es asegurarse de que el equipo siga las prácticas de Scrum y elimine obstáculos que puedan afectar su productividad.

### 3. **Equipo de Desarrollo**

El Equipo de Desarrollo es responsable de entregar incrementos del producto en cada Sprint. Son autoorganizados y multidisciplinarios, lo que significa que tienen todas las habilidades necesarias para completar las tareas.

## Artefactos en Scrum

### 1. **Product Backlog**

El Product Backlog es una lista priorizada de todos los elementos que se deben realizar en el proyecto. Los elementos pueden ser características, errores, mejoras, etc.

### 2. **Sprint Backlog**

El Sprint Backlog es una selección de elementos del Product Backlog que el equipo ha comprometido completar en el próximo Sprint.

### 3. **Incremento**

El Incremento es el resultado del trabajo del equipo al final de cada Sprint. Debe ser una versión potencialmente entregable del producto.

## Eventos en Scrum

### 1. **Sprint**

Un Sprint es un periodo de tiempo fijo, típicamente de 2 a 4 semanas, durante el cual el equipo trabaja en la entrega de un Incremento. Al final de cada Sprint, se debe tener una versión funcional del producto.

### 2. **Reunión de Planificación del Sprint**

En esta reunión, el equipo selecciona elementos del Product Backlog para incluir en el Sprint Backlog y define cómo se implementarán.

### 3. **Daily Scrum**

Esta es una reunión diaria de 15 minutos en la que el equipo se sincroniza, discute el progreso y aborda cualquier problema que pueda surgir.

### 4. **Revisión del Sprint**

Al final de cada Sprint, se lleva a cabo una reunión de revisión para demostrar el Incremento a los stakeholders y recibir retroalimentación.

### 5. **Retrospectiva del Sprint**

La Retrospectiva es una reunión al final del Sprint donde el equipo reflexiona sobre su desempeño y busca formas de mejorar.

## Ejemplo de uso de Scrum

Imagina que estás desarrollando una aplicación de gestión de tareas. Tu Product Backlog podría incluir elementos como "Agregar función de asignación de tareas", "Crear interfaz de usuario de lista de tareas" y "Implementar notificaciones por correo electrónico". Al comienzo de un Sprint, seleccionas algunos de estos elementos para trabajar durante el Sprint y planificas cómo los implementarás.

Durante el Sprint, el equipo trabaja en estas tareas y se reúne diariamente para asegurarse de que todo esté en marcha. Al final del Sprint, has completado la asignación de tareas y mejorado la interfaz de usuario. En la Revisión del Sprint, muestras estas mejoras a tus stakeholders y obtienes su retroalimentación. Luego, en la Retrospectiva, el equipo discute cómo pueden trabajar de manera más eficiente en el próximo Sprint.

Esta es una visión general de Scrum, pero es importante recordar que Scrum es altamente adaptable y puede ajustarse según las necesidades específicas de tu proyecto. Para obtener más detalles y profundizar en Scrum, te recomiendo consultar la [Guía Scrum oficial](https://www.scrum.org/resources/scrum-guide).

## Ejemplo practico con JavaScript para entender SCRUM

Este ejemplo ilustra cómo se pueden aplicar los conceptos de Scrum en el desarrollo de software, desde la planificación del Sprint y el trabajo en las tareas hasta las reuniones de revisión y retrospectiva.
La práctica de Scrum se centra en la entrega iterativa y continua de valor al cliente, y este código refleja un ciclo de desarrollo simplificado.

```Javascript
// Iniciemos con un Product Backlog ficticio (elementos pendientes).
const productBacklog = [
  "Implementar autenticación de usuarios",
  "Desarrollar una interfaz de usuario atractiva",
  "Agregar funcionalidad de notificaciones",
];

// Creamos un Sprint Backlog para el Sprint actual.
const sprintBacklog = productBacklog.slice(0, 2); // Tomamos los 2 primeros elementos.

// Ahora trabajemos en el Sprint actual.
for (const tarea of sprintBacklog) {
  // El equipo de desarrollo trabaja en la tarea.
  console.log(`Trabajando en: ${tarea}`);

  // Cuando se completa la tarea, la movemos al "Done" (hecho).
  console.log(`Tarea completada: ${tarea}`);
}

// En la reunión de revisión del Sprint, mostramos lo que se ha completado.
console.log("Reunión de Revisión del Sprint:");
for (const tarea of sprintBacklog) {
  console.log(`- ${tarea}`);
}

// En la reunión de retrospectiva del Sprint, reflexionamos y discutimos mejoras.
console.log("Reunión de Retrospectiva del Sprint:");
console.log("¿Cómo podemos mejorar para el próximo Sprint?");
```

El código proporcionado es un ejemplo simple en JavaScript y simula el proceso de desarrollo de software aplicando algunos conceptos de Scrum.

1. **Product Backlog** (`productBacklog`):
   - En Scrum, el Product Backlog es una lista priorizada de todas las tareas, características o elementos pendientes que deben abordarse en un proyecto. En este ejemplo, `productBacklog` representa una lista ficticia de elementos pendientes.

2. **Sprint Backlog** (`sprintBacklog`):
   - El Sprint Backlog es una selección de elementos del Product Backlog que se comprometen a completar durante un Sprint en Scrum. En este ejemplo, `sprintBacklog` toma los dos primeros elementos del Product Backlog, lo que simboliza la selección de tareas para el Sprint actual.

3. **Trabajo en el Sprint** (`for (const tarea of sprintBacklog)`):
   - En Scrum, durante un Sprint, el equipo de desarrollo trabaja en los elementos del Sprint Backlog. En el código, el bucle `for` representa el trabajo en las tareas seleccionadas para el Sprint.

4. **Reunión de Revisión del Sprint**:
   - Al final de un Sprint en Scrum, se lleva a cabo una reunión de revisión para demostrar el trabajo completado a los stakeholders. En el código, se simula esta reunión mostrando las tareas completadas del Sprint Backlog.

5. **Reunión de Retrospectiva del Sprint**:
   - La Retrospectiva del Sprint es una reunión donde el equipo reflexiona sobre su desempeño y busca mejoras para el próximo Sprint. En el código, se simula esta reunión planteando la pregunta de cómo mejorar para el próximo Sprint.

Para terminar, SCRUM es una metodología ágil que enfatiza la entrega continua de valor al cliente. El ejemplo en JavaScript demuestra cómo se aplica Scrum en el desarrollo de software, mejorando la eficiencia y la calidad de los proyectos. Comprender y aplicar Scrum permite a los equipos trabajar de manera más efectiva y consistente.

## Agradecimientos

Hecho con ❤️ por Matias Ignacio - https://github.com/Matignaciom
