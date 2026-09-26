# Protocolo operacional
## Entrada
Identifique objetivo, modo (transform/execução), repositório alvo, fontes e critérios de aceite. Leia instruções locais e consulte estado real. Execute uma tarefa por vez.

## Decisões deste bootstrap
- OPS-COPILOTO recebe documentação e os dois prompts.
- executar-Blog continua sendo o alvo do Prompt 1; Copiloto continua sendo a fonte do schema.
- M2 foi confirmado em manifest e Epic; revalidar antes de execução futura.
- gate:tbd é permitido sem inventar mapeamento.
- Labels sugeridas como area:deploy, cloudflare, security e component:studio não pertencem automaticamente ao conjunto canônico.
- Issue Type e label type:* são conceitos diferentes. Tipos técnicos exigem compatibilização explícita; não ampliar o schema silenciosamente.
- Milestones são releases/metas temporais. A proposta de milestones por gate depende de decisão explícita; não criar doze checkpoints automaticamente.
- Relações entre tarefas de deploy #2–#7 fornecidas pelo usuário são propostas a verificar no Blog; números e dependências não foram auditados neste bootstrap.

## Execução
Reutilize objetos existentes. Confirme ID, pai, labels e capacidade de vinculação antes de criar. Falta de ferramenta deve gerar alternativa versionada e pendência explícita, nunca alegação de sucesso.

## Saída
Informe status, arquivos alterados, commit, links, validações, limitações e próxima ação única. Separe execução concluída de aprovação humana.
