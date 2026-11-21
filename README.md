# EÓLICA-IA — UTFPR Londrina

**Projeto de pesquisa e desenvolvimento tecnológico assistido por inteligência artificial**  
Versão documental: 0.2.0 (estrutura inicial; não constitui aprovação institucional ou orientação técnica).

## Objetivo

Investigar, de forma documentada e crítica, como a IA generativa pode apoiar a aprendizagem autodirigida e o desenvolvimento, por uma pessoa sem formação prévia em engenharia eólica, de soluções experimentais de aproveitamento eólico de baixo custo com potencial de aplicação na UTFPR Londrina.

O projeto combina:

1. **Estudo longitudinal de caso único:** acompanhamento da evolução de competências de um participante ao longo do tempo.
2. **Design Science Research (DSR):** identificação de problema, definição de objetivos, projeto e desenvolvimento de artefato, demonstração, avaliação e comunicação.
3. **Pesquisa experimental aplicada:** somente após definição de requisitos, análise de riscos, instrumentação e validação por pessoas tecnicamente habilitadas.

> Importante: um estudo de caso único documenta uma trajetória e não permite generalizar automaticamente os resultados para todas as pessoas. A IA é ferramenta de apoio, não autoridade técnica nem substituta de orientação profissional.

## Comece por aqui — lista única de preenchimento

Abra [`00_GESTAO/LISTA_DE_PREENCHIMENTO.md`](00_GESTAO/LISTA_DE_PREENCHIMENTO.md). Ela organiza tudo o que o participante precisa informar, em ordem, sem exigir que todos os documentos sejam preenchidos de uma vez.

**Não estude engenharia eólica antes de concluir a linha de base inicial**, descrita em `01_LINHA_DE_BASE/`. O diagnóstico inclui questões de desempenho; não consulte IA, internet, livros ou terceiros durante a aplicação inicial, salvo se a instrução de uma questão permitir.

## Acompanhamento da IA

O diretório [`11_ACOMPANHAMENTO_IA/`](11_ACOMPANHAMENTO_IA/README.md) formaliza a participação da IA. Nele serão registrados pesquisas e fontes consultadas, feedbacks sobre materiais, contribuições, entregáveis e verificações. Consulte [Como solicitar atividades à IA](11_ACOMPANHAMENTO_IA/COMO_SOLICITAR.md) para os comandos operacionais.

A IA registra somente atividades que realizou ou que consegue comprovar a partir de materiais acessíveis. Não monitora automaticamente atividades externas ao ChatGPT. Sugestões da IA não equivalem a validação científica ou aprovação técnica.

## Estrutura

- `00_GESTAO/` — governança, protocolo, cronograma e decisões.
- `01_LINHA_DE_BASE/` — perfil inicial e avaliação diagnóstica.
- `02_DIARIO_DE_APRENDIZAGEM/` — registros de aprendizagem e matriz de competências.
- `03_INTERACOES_IA/` — registro de modelos, prompts, respostas e auditorias.
- `04_FUNDAMENTACAO/` — plano de revisão e referências.
- `05_PESQUISA_LOCAL/` — caracterização do local e dados meteorológicos.
- `06_DESENVOLVIMENTO/` — requisitos, cálculos, riscos, projeto e software.
- `07_EXPERIMENTOS/` — protocolos, registros, dados e desvios.
- `08_RESULTADOS/` — análise e indicadores.
- `09_PRODUCAO_ACADEMICA/` — relatórios e manuscritos.
- `10_EVIDENCIAS/` — índice de evidências e documentação visual.
- `11_ACOMPANHAMENTO_IA/` — pesquisas, feedbacks e contribuições rastreáveis da IA.
- `templates/` — modelos reutilizáveis.
- `data/` — arquivos tabulares-modelo e dicionários de dados.

## Regras essenciais de integridade

1. Não inventar dados, medições, fontes, resultados, credenciais ou aprovações.
2. Distinguir claramente dado observado, estimativa, simulação, hipótese e opinião.
3. Preservar dados brutos sem edição; trabalhar em cópias derivadas.
4. Registrar data, unidade, instrumento, resolução, calibração e condições de medição.
5. Registrar ferramenta/modelo de IA, data, prompt, resposta relevante e verificação.
6. Não considerar uma segunda resposta da mesma IA como validação independente.
7. Toda afirmação técnica crítica precisa de fonte confiável e, quando necessário, revisão de especialista.
8. Não construir, instalar ou conectar equipamentos à rede elétrica sem avaliação de risco, autorização institucional e supervisão técnica apropriada.
9. Não coletar dados pessoais de terceiros sem avaliar previamente requisitos éticos, legais e institucionais.
10. Manter histórico de mudanças no Git; não reescrever registros antigos para ocultar erros.

## Status científico

Este repositório é um **protocolo em preparação**. Antes de ser tratado como pesquisa institucional, deverá ser discutido com orientador(a) e adequar-se às normas, editais, comitês e procedimentos aplicáveis da UTFPR. O protocolo e os instrumentos poderão ser revisados após avaliação do orientador; alterações devem ser registradas em `00_GESTAO/REGISTRO_DE_EMENDAS.md`.

## Como registrar

- Datas: `AAAA-MM-DD`.
- Horários: ISO 8601 com fuso, quando relevante.
- Identificadores: `APR-AAAA-MM-DD-001`, `IA-AAAA-MM-DD-001`, `EXP-001`, `DEC-001`.
- Unidades: SI, salvo justificativa.
- Arquivos brutos: não sobrescrever.
- Commits: mensagens objetivas, por exemplo `docs: adiciona diagnóstico inicial`.

## Referências metodológicas iniciais

Consultar `04_FUNDAMENTACAO/REFERENCIAS_INICIAIS.md`. As referências devem ser conferidas e completadas pelo pesquisador antes de serem citadas em trabalho acadêmico.
