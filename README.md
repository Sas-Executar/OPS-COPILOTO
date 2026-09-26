# OPS-COPILOTO
Central de instruções operacionais do Programa EXECUTAR e GTM-Blog.

## Entrada
Leia [AGENTS.md](AGENTS.md), [INSTRUCOES.md](INSTRUCOES.md) e [fontes](docs/FONTES.md).
Claude: [CLAUDE.md](CLAUDE.md).

## Procedimentos
- [Prompt 1: bootstrap do Blog](prompts/01-bootstrap-blog.md).
- [Prompt 2: orientação para agentes](prompts/02-agentes.md).
- [Modelo de tarefa](templates/tarefa.md).
- [Estado e pendências](docs/ESTADO.md).

## Como abrir uma tarefa
Confirme ID e Epic na fonte canônica. Use `[TIPO] <ID> — <descrição>`, aprovação pendente e labels da [lista canônica](https://github.com/Sas-Executar/Copiloto/blob/claude/gifted-brown-7u1e5d/CLAUDE.md#labels-use-somente-estas).
Informe objetivo, escopo, critérios de aceite, owner, fonte e dependências. Vincule ao Epic e confirme o vínculo. Sem owner, registre A_DEFINIR e deixe assignee vazio.
Gate desconhecido: gate:tbd; ID ou Epic ambíguo: pergunte antes de criar.

## Responsabilidades
| Local | Responsabilidade |
|---|---|
| Notion | Conhecimento, estratégia, Foundation Docs, PRDs e ADRs |
| Copiloto | Schema de governança e espelho da planilha canônica |
| executar-Blog | Código, deploy e execução técnica |
| OPS-COPILOTO | Instruções, procedimentos e referências |

Project organiza; Epic agrupa resultados; issue define entrega; sub-issue divide execução; checklist registra passos; PR/commit implementa.
Milestone representa objetivo temporal/release. Gate representa governança: não equiparar automaticamente.
