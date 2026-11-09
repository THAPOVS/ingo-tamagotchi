# Repos guardados para Jarvis

Registro de repos open-source a tener en cuenta. Antes de recomendar o pagar una herramienta,
revisar si alguno de estos la reemplaza.

## Fuente: @sergioprompts — "10 repos de GitHub gratis" (5 nov 2026)

Post: https://www.instagram.com/p/DfYb9FHkWox/ · Guardado: 9 nov 2026 · Estrellas al 9 nov 2026.

| # | Repo | Reemplaza a | Qué hace | Licencia | ★ | Relevancia |
|---|------|-------------|----------|----------|---|------------|
| 1 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | CapCut | Editor de video web, escritorio y móvil | MIT | 98k | Baja: referencia |
| 2 | [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) | ElevenLabs | Clonar voces, doblaje, TTS y transcripción 100% local | AGPL-3.0 | 106k | Media: contenido |
| 3 | [AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | Notion | Workspace con IA, wikis y proyectos; datos propios | AGPL-3.0 | 79k | Baja: ya usamos Notion |
| 4 | [makeplane/plane](https://github.com/makeplane/plane) | ClickUp / Jira / Linear | Tareas, sprints, docs; tiene MCP oficial (`makeplane/plane-mcp-server`) | AGPL-3.0 | 62k | Baja: ya usamos ClickUp |
| 5 | [calcom/cal.diy](https://github.com/calcom/cal.diy) | Calendly | Agenda de reuniones (ex Cal.com) | MIT | 50k | Media |
| 6 | [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) | Intercom / Zendesk | Bandeja omnicanal: chat web, email, WhatsApp | Mixta (ver LICENSE) | 39k | Media: inbox de ops/leads |
| 7 | [every-app/open-seo](https://github.com/every-app/open-seo) | Semrush / Ahrefs | Keywords, rank tracking, backlinks, auditorías; MCP + Agent Skills para Claude Code | MIT | 27k | **Alta: usable desde Claude** |
| 8 | [CapSoftware/Cap](https://github.com/CapSoftware/Cap) | Loom | Grabar pantalla y compartir por link | Mixta (ver LICENSE) | 25k | Media: walkthroughs a clientes |
| 9 | [dyad-sh/dyad](https://github.com/dyad-sh/dyad) | Lovable / v0 / Bolt | Constructor de apps con IA, local | Mixta (ver LICENSE) | 22k | Baja: Claude Code ya lo cubre |
| 10 | [OpenWhispr/openwhispr](https://github.com/OpenWhispr/openwhispr) | Wispr Flow | Dictado voz→texto (Whisper/Parakeet local o API propia, incl. Anthropic) | MIT | 11k | Media: dictado personal |

### Notas de uso

- **OpenSEO**: está en el directorio oficial de conectores de Claude (claude.ai → Settings → Connectors → OpenSEO; MCP `https://app.openseo.so/mcp`, login con OAuth, sin API key).
  Hosteado: USD 10/mes + 28% de recargo sobre DataForSEO (se puede probar gratis). Autohospedado (Docker o Cloudflare): necesita API key de DataForSEO, pago por uso.
- **AGPL-3.0** (VoiceStudio, AppFlowy, Plane): uso interno sin problema; si se modifica y se ofrece como servicio a clientes, hay que publicar el código.
- Licencia "Mixta" (Chatwoot, Cap, Dyad): núcleo abierto + partes comerciales; revisar el LICENSE antes de usarlo para clientes.
- Todos son "gratis si los ejecutás vos": el costo real es hosting + mantenimiento.
