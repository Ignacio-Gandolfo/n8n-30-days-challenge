# Day 01 — Resumen diario de emails (Gmail)

## Objetivo
Automatizar la lectura de los correos recibidos durante el día y generar un
resumen simple con el remitente y el asunto de cada mensaje.

---

## Qué hace este workflow
Una vez por día, el workflow se ejecuta automáticamente y revisa la bandeja de
entrada de Gmail. Toma los correos recibidos en las últimas 24 horas y extrae la
información más relevante de cada uno.

Con esos datos, arma un resumen claro que permite ver de un vistazo qué emails
llegaron durante el día, sin necesidad de abrir cada mensaje.

---

## Flujo del proceso
1. El workflow se inicia mediante un **trigger de programación**.
2. Se consultan los correos recibidos en Gmail durante las últimas 24 horas.
3. Se procesan los mensajes para obtener remitente y asunto.
4. Se envía un email con el resumen generado.

---

## Requisitos
- Cuenta de Gmail conectada en n8n y sus credenciales, si no saben como hacerlo en breve subo un video explicando, es muy sencillo! .
- Permisos para leer y enviar correos.

---

## Cómo probarlo
1. Importar el archivo `workflow.json` en n8n.
2. Configurar las credenciales de Gmail.
3. Ajustar el horario del trigger si es necesario.
4. Ejecutar el workflow manualmente o esperar la ejecución programada.

---

## Nota
El workflow se publica sin credenciales ni datos sensibles.
Cada usuario debe configurar su propia cuenta de Gmail.
