# Como solicitar atividades à IA

Use os comandos abaixo no ChatGPT. Você não precisa preencher todos os campos: informe o objetivo e anexe ou indique o material relevante. A IA deverá pedir esclarecimento somente quando uma informação essencial estiver faltando.

## 1. Registrar uma pesquisa
**Comando:** "EÓLICA-IA: pesquise [tema]. Registre a estratégia de busca, fontes realmente consultadas, síntese, limitações e referências no GitHub."

Resultado esperado: entrada em `PESQUISAS.csv`, com fontes e status de verificação. A síntese deve distinguir o que a fonte afirma da interpretação da IA.

## 2. Revisar um material
**Comando:** "EÓLICA-IA: revise este [documento/código/cálculo/projeto]. Aponte erros, lacunas, riscos, melhorias e o que precisa de validação externa. Registre o feedback no GitHub."

Resultado esperado: feedback priorizado em `FEEDBACKS.csv`, com evidências e ações sugeridas.

## 3. Registrar uma sessão de trabalho
**Comando:** "EÓLICA-IA: registre esta sessão. O que foi feito, o que foi produzido, quais decisões surgiram e quais são as próximas tarefas?"

Resultado esperado: atualização de `CONTRIBUICOES_IA.csv` e, se aplicável, dos diários pertinentes.

## 4. Atualizar o estado do projeto
**Comando:** "EÓLICA-IA: faça uma revisão do repositório e produza um relatório de andamento. Liste entregáveis, pendências, riscos, decisões em aberto e próximos passos."

Resultado esperado: análise do conteúdo disponível no GitHub e relatório datado. Não presumir atividades que não estejam documentadas.

## 5. Auditoria crítica
**Comando:** "EÓLICA-IA: faça uma auditoria crítica deste resultado. Tente encontrar erros, pressupostos frágeis, dados ausentes, referências inadequadas e explicações alternativas."

Resultado esperado: feedback adversarial, não apenas confirmação do trabalho.

## 6. Incorporar alterações ao GitHub
**Comando:** "EÓLICA-IA: aplique no repositório as alterações documentais aprovadas abaixo. Preserve o histórico e informe os arquivos e commits alterados."

A IA deve diferenciar alterações propostas das autorizadas. Para mudanças substantivas em método, requisitos ou segurança, solicitar confirmação antes de substituir o conteúdo vigente.

## 7. Preparar relatório periódico
**Comando:** "EÓLICA-IA: gere o relatório mensal do período [datas], usando apenas os registros existentes. Indique lacunas de documentação e não estime atividades ausentes."

## Modelo curto para qualquer solicitação
- Objetivo:
- Material ou link:
- Tipo de ajuda: pesquisa / revisão / cálculo / código / planejamento / documentação
- Profundidade desejada:
- Pode alterar o GitHub? sim/não
- Restrições:

## Limites operacionais
A IA só consegue analisar arquivos, mensagens e fontes às quais tenha acesso na tarefa. Para acompanhar uma atividade externa, compartilhe o arquivo, link acessível, resultado ou resumo. Não há monitoramento contínuo automático neste protocolo.
