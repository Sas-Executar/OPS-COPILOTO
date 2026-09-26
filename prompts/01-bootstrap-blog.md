# Prompt 1 — Bootstrap do schema de Issues
## Objetivo
Configurar Sas-Executar/executar-Blog conforme o schema de Sas-Executar/Copiloto e documentar seu uso, preservando README.md, CLAUDE.md e ADRs existentes.

## Fontes e regras
Leia o CLAUDE.md atual dos dois repositórios, instruções locais e manifest-*.json do Copiloto. M2 e Epic #37 foram confirmados em 2026-09-26; revalide. Não trate o exemplo Blog/M2 como prova isolada.
Use somente labels canônicas. WIP=1; nenhuma issue nasce aprovada; aprovação exige ação humana explícita. Não invente IDs ou relações; gate desconhecido usa gate:tbd. Sem owner, A_DEFINIR e sem assignee. Nenhum segredo.

## Execução
1. Consulte estado real, branch e regras de push. Verifique a fonte primária quando exigido pelo protocolo do Copiloto.
2. Confirme portfolio_id, Epic, lacunas e gates. Se ID ou pai forem ambíguos, pergunte antes de criar.
3. Descubra ferramentas reais para listar/criar labels, milestones, sub-issues e dependências. Busque label/milestone no catálogo ou ToolSearch, quando disponível.
4. Compare labels existentes com a lista canônica. Crie somente faltantes, preservando semântica e verificando nomes, cores e descrições retornados. Sem ferramenta, gere configuração versionada com proveniência e instruções manuais; não invente metadados canônicos.
5. Milestones representam releases. Não converta G00–G11 automaticamente: resolva explicitamente a divergência entre milestones por gate e milestones temporais. Nunca atribua datas inventadas.
6. Reutilize o Epic correto; só crie Epic local se necessário e com hierarquia confirmada. Aplique type:portfolio-epic, approval:pendente e gate confirmado ou gate:tbd. Não duplique o Epic canônico sem necessidade documentada.
7. Acrescente Governança de Issues ao CLAUDE.md: título, labels obrigatórias, hierarquia, aprovação e WIP. Referencie a lista canônica, sem duplicá-la.
8. Acrescente Como abrir uma tarefa ao README.md. Preserve integralmente instruções anteriores.
9. Valide e faça commit/push conforme autorização do repositório alvo. Não altere aprovação.
10. Só reorganize #2–#7 após confirmar títulos, escopo, pai e dependências reais; nunca deduza dependência apenas da numeração.

## Validação e saída
Reporte labels criadas/existentes/pendentes, milestones e seu propósito, Epic com número/link, portfolio_id, gates, arquivos, commit e bloqueios.
Confira labels exatas, aprovação pendente, vínculos reais, preservação de conteúdo e ausência de segredos.
Se faltar capacidade de vinculação, não crie tarefas órfãs: deixe proposta versionada.
Conclua quando ações autorizadas e verificáveis estiverem entregues; registre claramente o que não pôde ser executado.
