# AI-AGENTS

Agentes reutilizables para Codex.

## Agente programador

El archivo [programador.toml](./programador.toml) define un agente generalista para tareas de programación. Se adapta al lenguaje, framework y convenciones que encuentre en cada proyecto. Está pensado para trabajos universitarios y profesionales.

## Agente QA Engineer

El archivo [qa-engineer.toml](./qa-engineer.toml) define un agente de aseguramiento de calidad para revisar código implementado, comprobar requisitos y casos límite, priorizar defectos con evidencia y corregir problemas verificables dentro del alcance. Está pensado para usarse después de la implementación, junto al agente programador.

### Instalar en Codex

Descarga el TOML del agente que quieras usar y guárdalo en la carpeta personal de agentes de Codex:

- **Windows:** `%USERPROFILE%\\.codex\\agents\\<nombre-del-agente>.toml`
- **macOS/Linux:** `~/.codex/agents/<nombre-del-agente>.toml`

Por ejemplo, guarda `qa-engineer.toml` como `%USERPROFILE%\\.codex\\agents\\qa-engineer.toml`. Crea la carpeta `agents` si todavía no existe y reinicia Codex para cargar el agente.

Documentación oficial: [Agentes personalizados de Codex](https://developers.openai.com/codex/subagents/).
