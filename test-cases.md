# TC-05 – Validar cancelación de orden en base de datos con track válido

## Objetivo
Validar que una orden se marque como **cancelada en base de datos** al enviar un **track válido** mediante el endpoint de cancelación.

## Precondiciones
- Existe una orden creada previamente con un track válido.
- El servicio de órdenes está disponible.
- Se tiene acceso de lectura a la base de datos.

## Pasos
1. Enviar una solicitud de cancelación:
2. Enviar el siguiente body:
```json
{
  "track": 751437
}
{ "ok": true }

