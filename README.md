
# Micro Tarea: API para Procesar Mensajes de AWS SQS u otro provedor de colas de mensajes en la nube
## Objetivo

 Desarrollar una API que interactúe con una cola de mensajes de AWS SQS u otro provedor de colas de mensajes en la nube, realizando las siguientes funciones:

1. Leer y eliminar mensajes de una cola de AWS SQS.
2. Proceso que escuche de la cola y guarde los mensajes leídos en una base de datos o en un archivo de texto.
3. Proveer dos endpoints:
    - Uno para encolar mensajes en AWS SQS.
    - Otro para devolver el contenido almacenado (de la base de datos o archivo de texto).

### NOTA: los mensajes deben ser objetos con el siguiente formato:

```
{
    "message": "un mensaje",
    "timestamp": "2021-09-01T12:00:00",// Puede ser cualquier formato de fecha
    "author": "autor del mensaje"
}
```

## Requisitos
Lenguaje de programación: Libre elección.
Servicios AWS: Uso obligatorio de AWS SQS u otro provedor de colas de mensajes en la nube.
Almacenamiento: Opcional entre una base de datos (puede ser SQL o NoSQL) o un archivo de texto.

## Entrega

 1. Subir el repo a classroom.
 2. Evidencia en video de que funciona.
