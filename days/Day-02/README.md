# Day 02 – Daily Calendar Events Reminder

## Objetivo
Recibir un email automático todos los días con los eventos programados para **mañana**.

---

## Qué hace esta automatización
- Se ejecuta diariamente en un horario definido
- Obtiene los eventos de mañana desde Google Calendar
- Los formatea en una lista simple y fácil de leer
- Envía el resumen por email usando Gmail

---

## Por qué es útil
Una fricción pequeña pero muy común:
revisar el calendario varias veces al día o olvidarse de reuniones.

Esta automatización elimina ese paso y permite arrancar el día con mayor claridad.

---

## Servicios utilizados
- n8n
- Google Calendar
- Gmail

---

## Configuración
1. Importar el archivo `workflow.json` en n8n
2. Conectar las credenciales de Google Calendar
3. Conectar las credenciales de Gmail
4. Ajustar el horario de ejecución si es necesario
5. Activar el workflow
