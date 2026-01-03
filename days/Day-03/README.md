# Asistente de IA para responder emails – n8n

Workflow desarrollado en n8n que genera Emails de respuesta utilizando inteligencia artificial.

## Qué hace
- Detecta nuevos emails en Gmail
- Analiza el contenido del mensaje
- Genera una respuesta profesional con IA
- Devuelve la respuesta y la envia automaticamente.

## Por qué es útil
Responder emails consume tiempo y energía.
Este workflow automatiza el envio de mensaje, manteniendo siempre control humano.

## Tecnologías usadas
- n8n
- Gmail
- OpenAI
- Agente de IA (LangChain)
- Google Docs (contexto opcional)

## Configuración
1. Importar `workflow.json` en n8n
2. Configurar las credenciales:
   - Gmail (OAuth)
   - OpenAI (API Key)
   - Google Docs (opcional)
3. Activar el workflow

⚠️ Las credenciales no están incluidas en este repositorio.

## Notas
- El workflow **no envía emails automáticamente**
- Pensado para productividad diaria y automatización segura
