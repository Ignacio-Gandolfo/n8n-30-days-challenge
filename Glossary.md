# Diccionario de términos — n8n

Este diccionario explica de forma simple los términos utilizados en los workflows
para personas que recién comienzan a usar n8n.

---

## Workflow
Conjunto completo de pasos que automatizan una tarea.
Incluye triggers, nodos y conexiones.

---

## Trigger
Nodo que inicia un workflow.
Define **cuándo** se ejecuta la automatización.

---

## Trigger de programación (Schedule Trigger)
Trigger que ejecuta el workflow en un horario definido
(diario, semanal o cada cierto intervalo).

---

## Nodo (Node)
Bloque que realiza una acción dentro del workflow.
Puede leer datos, transformarlos o enviarlos a otro servicio.

---

## Nodo de entrada
Nodo que obtiene información desde un sistema externo.

**Ejemplo:** leer correos desde Gmail.

---

## Nodo de procesamiento
Nodo que transforma o prepara los datos.

**Ejemplo:** generar un resumen a partir de varios emails.

---

## Nodo de salida
Nodo que envía o guarda el resultado final.

**Ejemplo:** enviar un email con el resumen diario.

---

## Sticky Note
Elemento visual usado para documentar y explicar partes del workflow.
No ejecuta ninguna acción.

---

## Credenciales
Datos de autenticación que permiten a n8n conectarse a servicios externos.
No se incluyen en los exports públicos.

---

## Export (workflow.json)
Archivo que contiene la definición del workflow y puede ser importado en otra instancia de n8n.

