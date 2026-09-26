# Prompt 2 — Orientação para agentes
Ao abrir tarefas, siga o schema EXECUTAR.

Rotas: execução técnica em Sas-Executar/executar-Blog; governança do Programa e documentos canônicos em Sas-Executar/Copiloto. OPS-COPILOTO mantém procedimentos.

Leia o CLAUDE.md atual do alvo e a fonte canônica indicada em docs/FONTES.md. Título: [TIPO] <ID> — <descrição>. Preserve IDs literais. M2 foi confirmado para Executar Blog no manifest-03.json e Epic #37 do Copiloto; revalide antes de agir.

Selecione labels exclusivamente da lista canônica: type:*, approval:pendente, gate confirmado ou gate:tbd; area:* quando comprovada e prioridade conforme instruções. Registre portfolio_id no corpo; não invente label de portfólio. Use requires-human-decision para decisões humanas.

Toda tarefa precisa de Epic correto e vínculo de sub-issue verificado. Confirme a capacidade de vinculação antes de criar. Se ID ou pai forem ambíguos, pergunte. Gate desconhecido pode usar gate:tbd; não invente correspondências enquanto GAP-DEP-01 impedir o mapeamento.

Sem responsável confirmado, registre owner A_DEFINIR e não atribua assignee. Trabalhe com WIP=1. Não altere approval:pendente para approval:aprovado sem ação humana explícita. Fechar uma issue registra execução, não aprovação.

A planilha canônica prevalece sobre o GitHub. Divergências exigem type:conflict com versões e fontes, respeitando a hierarquia. Não inclua credenciais em nenhum artefato.

Project organiza o trabalho; Epic agrupa resultados; issue descreve entrega; checklist detalha passos; milestone define meta temporal; commit/PR implementa. Labels e Issue Types não são equivalentes.

Informe em pt-BR número/link dos objetos realmente criados, validações e pendências. Não declare configuração, dependência ou vínculo que não tenha sido confirmado.
