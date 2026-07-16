---
creada: 2026-07-16
etiquetas: [referencia, api, ecommerce]
---

# API de tickets - GoPDQ2

## Idea principal

- Endpoints REST propuestos para el módulo de soporte.

## Detalles

- `POST /tickets` — crear ticket (cliente).
- `GET /tickets/:id` — detalle del ticket.
- `PATCH /tickets/:id/estado` — cambiar estado (agente).
- `POST /tickets/:id/mensajes` — agregar mensaje al hilo.
- Auth: JWT de sesión de cliente o agente, sin credenciales hardcodeadas.

## Relacionado

- [[GoPDQ2 - App de soporte ecommerce]]
- [[Flujo de tickets de soporte]]
