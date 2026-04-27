# Custom Copilot Agents

Questa cartella contiene i profili dei custom agent di GitHub Copilot per questo repository.

## Agenti disponibili

- **[web-developer.md](./web-developer.md)** — Spatialcorp Web Developer: sviluppatore dedicato al sito-vetrina, con conoscenza dell'ecosistema Spatialcorp.

## Come usarli

Gli agenti definiti qui appaiono automaticamente tra gli agenti disponibili in GitHub Copilot per chi ha accesso al repository. Possono essere richiamati da:
- github.com (interfaccia Copilot)
- Copilot CLI
- Editor con estensione Copilot

Ogni file `.md` in questa cartella definisce un agente tramite front-matter YAML (nome, descrizione, tool) seguito dal prompt di sistema in Markdown.
