Archivos creados por la acción `specify init` (simulación)

Este repositorio contiene una estructura mínima generada para reproducir lo que hace `specify init`:

- `.github/prompts/agent_prompt.md` — Prompt de agente para inicializar el proyecto.
- `.github/agents/sample-agent.yml` — Ejemplo de configuración de agente.
- `.specify/memory/.specify/templates/rss_memory.md` — Plantilla de memoria de ejemplo para feeds RSS.
- `.specify/scripts/powershell/init.ps1` — Script de ejemplo que imprime "Proyecto listo".
- `.vscode/settings.json` — Ajustes recomendados para editores.

Siguientes pasos recomendados:
1. Revisar los archivos creados y ajustarlos a tus necesidades.
2. Si tienes la CLI `specify` instalada, ejecuta:
   ```bash
   specify init --here --ai copilot --script ps
   ```
   o bien `npx specify init --here --ai copilot --script ps` si no está instalada globalmente.
3. Confirmar cualquier acción en proyectos brownfield (cuando el directorio ya contiene archivos).

Si quieres, puedo crear un commit con estos cambios o intentar ejecutar `specify init` desde el contenedor (si reabrimos el devcontainer).