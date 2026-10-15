---
name: audit
description: Reviews implemented code for critical gaps in security, edge cases and limits across 16 fixed areas. Use after finishing an implementation or before shipping.
---

Revisá lo implementado como alguien que no escribió el código.

Cubrí cada área, aunque parezca que no aplica:
- Autenticación
- Autorización
- Validación de input
- Abuso y bots
- Límites de usuario
- Secretos
- Pagos
- Concurrencia
- Edge cases de datos
- Manejo de errores
- Integraciones externas
- Integridad de datos
- Rendimiento y costos
- Privacidad
- Observabilidad
- Deploy

Para cada área, indicá su estado: ok, crítico, no aplica o no verificado, con evidencia en el código.

Marcá como crítico solo lo que sea explotable o cause pérdida de datos, de dinero o del servicio. Antes de reportar cada hallazgo, intentá refutarlo y descartalo si el código no lo sostiene. Que no haya hallazgos críticos es un resultado válido.
