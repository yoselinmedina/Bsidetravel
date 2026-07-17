---
layout: post
title: "Cómo resolvimos una restricción inesperada en Meta Business Portfolio"
date: 2026-07-14
---

## Contexto

B Side Travel Chile es una agencia de viajes boutique especializada en experiencias en Atacama, Patagonia y el Valle Central. Como parte de la estrategia de marketing digital del proyecto, estábamos preparando el lanzamiento de una campaña de Meta Ads: un video con llamada a la acción ("Cotizar") vía WhatsApp, con ubicaciones en Reels y Feed, segmentado para audiencia en Chile.

Antes de lanzar cualquier campaña paga, hicimos una auditoría previa con un checklist de prioridades para asegurar que la cuenta, el pixel, el catálogo y los permisos estuvieran en orden. Fue justo en esta etapa de revisión donde apareció el problema.

## Problema

Al revisar el Business Portfolio de Meta asociado a la cuenta de Instagram **@bsidetravelchile**, detectamos que la cuenta tenía una **restricción activa** que impedía avanzar con la configuración de la campaña. Esto bloqueaba directamente:

- La vinculación correcta de la cuenta de Instagram al Business Manager.
- La posibilidad de publicar anuncios desde esa cuenta.
- El cronograma de lanzamiento que ya estaba comprometido con el cliente.

El desafío no era solo técnico (entender *por qué* Meta había aplicado la restricción), sino también de comunicación: había que explicarle al cliente que el lanzamiento podía atrasarse sin generar alarma innecesaria.

## Acciones

1. **Diagnóstico inicial**: revisamos el estado de la cuenta en Meta Business Suite y el Centro de Cuentas, identificando el tipo de restricción y el mensaje de política asociado.
2. **Revisión de causas posibles**: verificamos configuración de roles y permisos, si la cuenta de Instagram estaba correctamente reclamada por el Business Portfolio correcto, y si había señales de actividad que Meta pudiera interpretar como no conforme a sus políticas.
3. **Solicitud de revisión**: iniciamos el proceso formal de apelación/revisión con Meta, documentando el caso de uso legítimo del negocio.
4. **Plan de contingencia**: mientras se resolvía, ajustamos el cronograma de la campaña y preparamos configuraciones alternativas para no perder la ventana de lanzamiento.
5. **Post-mortem constructivo**: una vez resuelta la restricción, hicimos un análisis en equipo de qué pudo haberla originado y qué pasos de verificación deberíamos incorporar *antes* de futuras campañas, en lugar de descubrir estos problemas a último momento.

## Aprendizajes

- **Verificar el estado del Business Portfolio y la cuenta de Instagram debe ser parte del checklist pre-lanzamiento**, no algo que se revisa cuando ya se quiere activar la campaña.
- Las restricciones de Meta no siempre tienen una causa clara o inmediata; hay que tener **tiempo de margen** en el cronograma para procesos de apelación.
- Comunicar el problema al cliente de forma transparente y con un plan de acción ayuda a mantener la confianza durante el imprevisto.
- Documentar el incidente en el momento (capturas, mensajes de error, fechas) facilita mucho tanto la apelación con Meta como el post-mortem posterior.

## Documentación y control de versiones

Este mismo blog está versionado con Git como evidencia del proceso de documentación:

- Repositorio: https://github.com/yoselinmedina/Bsidetravel
- Commit de creación de la entrada: https://github.com/yoselinmedina/Bsidetravel/commit/9095bd3ee68054abac73ecffc16795dc0d58101e
- Commit con ajustes y correcciones a la entrada: https://github.com/yoselinmedina/Bsidetravel/commit/b6b7895423d248d88c8cbfaf967ae584745d13e0

## Reflexión sobre feedback radicalmente sincero

Durante este proceso, el feedback más honesto fue el que me di a mí misma en el post-mortem: reconocer que la verificación del estado de la cuenta debió hacerse *antes*, como parte del checklist, y no reaccionar solo cuando ya era urgente. Ser directa conmigo misma sobre ese vacío en el proceso fue lo que permitió convertirlo en una mejora concreta en vez de solo un contratiempo que se olvida.

También fue clave comunicar con el cliente de forma clara y directa sobre el atraso, en vez de suavizar demasiado la situación.

**Checklist de entrega:**
- [x] URL pública del blog/entrada: https://yoselinmedina.github.io/Bsidetravel/2026/07/14/restriccion-meta-bside-travel.html
- [x] Enlace al repositorio o snapshot de commits: https://github.com/yoselinmedina/Bsidetravel/commits/main
- [x] Reflexión sobre feedback aplicado: incluida arriba ✅
