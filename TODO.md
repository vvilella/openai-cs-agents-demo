# TODO – Customizações no openai-cs-agents-demo

Organização estilo Kanban para acompanhar ideias e melhorias no fork.

## Feito

- [x] Clonagem e execução local do projeto
- [x] Atualização de README personalizado no fork
- [x] PR enviado para log de guardrail ativado (https://github.com/openai/openai-cs-agents-demo/pull/19)

## Em andamento

- [ ] Criar TelcoAgentContext com campos como: número da linha, plano, franquia, CPF, protocolo
- [ ] Criar agente com RAG simples: busca simulada em base de conhecimento (ex: FAQ telco, contrato, planos)
- [ ] Adicionar etapa de feedback humano no final da interação ("Isso ajudou? [sim/não]")

## Ideias futuras (UI / Devtools)

- [ ] Human Feedback Panel: painel lateral com histórico de feedbacks do usuário
- [ ] Agent Memory Viewer: mostrar contexto armazenado pelo agente durante execução
- [ ] Intent Recognizer Debug: exibir intenção detectada pelo Triage Agent com score
- [ ] Agent Switch History: linha do tempo visual das trocas de agente
- [ ] Prompt Playground: modo dev com edição dinâmica dos prompts no frontend

## Ideias para PR futuro

- [ ] Nova seção de UI: painel lateral de depuração de agentes
- [ ] Melhoria na visualização do contexto: edição inline dos campos
- [ ] Log estruturado para eventos de tool calls e atualizações de contexto

## Anotações

- Customizações visam demonstrar casos reais (telco, RAG, feedback humano)
- Evitar alterações destrutivas na estrutura do repositório original
- README do fork manterá separação clara entre uso original e extensões
