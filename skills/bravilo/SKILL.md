---
name: bravilo
description: Consultar la cuenta de Bravilo del usuario (inbox, conversaciones, contactos, leads, pipeline, pronóstico, tareas y métricas). Usar cuando pregunte por sus ventas, sus clientes, sus conversaciones de WhatsApp/Instagram/Messenger, sus agentes o "cómo viene mi día".
---

# Bravilo

El conector de Bravilo da acceso de **solo lectura** a la cuenta del usuario. Todos los datos ya vienen acotados a su organización.

## Qué herramienta usar

- **Resumen del día**: `get_my_day`.
- **Inbox**: buscar con `search_conversations`, leer con `get_conversation` y `get_messages`.
- **Personas**: `search_contacts` para encontrar, `get_contact` para el perfil comercial completo.
- **Leads**: `get_leads` para listar, `get_lead_details` para uno, `get_leads_at_risk` para los que se están enfriando.
- **Negocio**: `get_pipeline`, `get_forecast` y `get_account_metrics`. Para preguntas agregadas usar estas, no contar conversaciones a mano.
- **Tareas**: `get_tasks`.
- **Agentes de IA de la cuenta**: `list_agents`.

## Reglas

- Nunca inventar números. Si una herramienta no devuelve un dato, decir que no está disponible.
- No se puede escribir, responder mensajes ni mover leads desde acá: para eso, mandar al usuario a app.braviloai.com.
- Responder en el idioma del usuario y citar de qué conversación o contacto sale cada dato.
