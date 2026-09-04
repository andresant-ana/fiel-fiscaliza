# FF-0002 — PRE_CODEX_CHECKLIST

**Nome do documento:** Pre-Codex Checklist  
**ID:** FF-0002  
**Versão:** 1.1  
**Status:** CANONICAL  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define o caminho formal que o Fiel Fiscaliza deve percorrer antes de liberar o Codex para implementação relevante do produto.

Seu objetivo é impedir que a cota limitada do Codex seja consumida para descobrir requisitos, arquitetura, regras editoriais ou decisões de produto que podem ser resolvidas previamente por pesquisa, discussão, especificação e documentação.

O princípio central é:

> **Pensar, decidir e especificar antes de delegar implementação.**

O Codex deve receber problemas suficientemente compreendidos, delimitados e testáveis.

Este documento é subordinado ao **FF-0001 — PROJECT_CONSTITUTION**.

---

# 2. O que significa “liberar o Codex”

Neste documento, “liberar o Codex” significa permitir que ele seja utilizado de forma regular para implementar código de produção do MVP do Fiel Fiscaliza.

Isso não inclui tarefas meramente documentais realizadas no ChatGPT, alterações manuais pequenas no repositório ou manutenção da própria documentação.

Antes da liberação formal, qualquer exceção para uso do Codex em prova técnica, investigação ou experimento descartável deve:

1. resolver uma incerteza que não possa ser decidida razoavelmente apenas por análise;
2. possuir escopo estritamente limitado;
3. não introduzir silenciosamente código de produção;
4. ser explicitamente aprovada por André;
5. ter a decisão resultante documentada.

A exceção não substitui o cumprimento deste checklist.

Este documento regula o uso do Codex, mas não autoriza que implementação manual ou assistida pelo ChatGPT seja usada para contornar decisões ainda não resolvidas. Código de produção não deve cristalizar silenciosamente requisitos, arquitetura ou regras editoriais que ainda estejam em aberto.

---

# 3. Princípios do processo pré-Codex

## 3.1 Especificação antes de implementação

Não utilizar Codex para responder perguntas como:

- qual produto devemos construir;
- quem é o usuário;
- qual é o MVP;
- como diferenciar alegação de fato;
- qual modelo temporal utilizar;
- qual infraestrutura escolher;
- qual deve ser o comportamento esperado de uma funcionalidade.

Essas perguntas devem ser respondidas antes da implementação correspondente.

## 3.2 Documentação proporcional

O objetivo deste processo não é produzir burocracia.

Documentar em profundidade aquilo que:

- influencia múltiplas partes do sistema;
- possui risco editorial, jurídico ou arquitetural;
- precisa sobreviver aos chats;
- condiciona futuras decisões;
- será necessário para orientar agentes e colaboradores.

Não criar precisão artificial para detalhes que ainda dependem de descoberta posterior.

## 3.3 Decisões canônicas são gates

Uma fase não é considerada concluída apenas porque o tema foi discutido em chat.

Quando este checklist exigir um documento CANONICAL, a decisão correspondente deve estar formalizada e aprovada.

## 3.4 O checklist é lógico, não burocraticamente linear

É permitido trabalhar em documentos de fases posteriores quando isso ajudar a esclarecer uma fase anterior.

Entretanto, os gates devem ser cumpridos antes da liberação final do Codex.

## 3.5 Nenhuma pendência crítica escondida

Se uma decisão permanecer conscientemente em aberto, ela deve ser registrada como pendência.

Não utilizar uma implementação para decidir silenciosamente uma questão ainda não resolvida.

## 3.6 Documentos canônicos devem ser rastreáveis entre si

Quando uma decisão de um documento puder alterar materialmente outro documento, essa relação deve ser identificável por referência, seção de impacto, índice ou mecanismo equivalente.

Não é obrigatório criar dependências artificiais entre todos os documentos. O objetivo é impedir que uma alteração importante seja feita sem que seus efeitos sobre especificações relacionadas sejam percebidos.

---

# 4. Convenção de status deste checklist

- `[x]` — concluído e verificado;
- `[ ]` — pendente;
- `[~]` — em andamento;
- `[N/A]` — conscientemente não aplicável, com justificativa registrada.

Um item marcado como concluído deve possuir evidência no repositório, em documento canônico ou em decisão formal rastreável.

---

# 5. FASE 0 — Fundação e governança documental

## Objetivo

Garantir que o projeto possua identidade, autoridade documental, memória de decisões e vocabulário comum antes de especificar o produto em profundidade.

## Checklist

- [x] Nome oficial definido: **Fiel Fiscaliza**.
- [x] Projeto criado no ChatGPT.
- [x] Repositório GitHub criado: `andresant-ana/fiel-fiscaliza`.
- [x] Estrutura documental inicial criada no repositório.
- [x] Instruções permanentes do projeto definidas no ChatGPT.
- [x] FF-0001 — PROJECT_CONSTITUTION v1.0 // CANONICAL.
- [x] FF-0002 — PRE_CODEX_CHECKLIST v1.1 // CANONICAL.
- [x] FF-0003 — DECISION_LOG com o conjunto inicial de decisões já tomadas.
- [x] FF-0004 — GLOSSARY com o vocabulário inicial oficial.
- [x] Definir e aplicar convenção mínima de impacto/dependência entre documentos canônicos quando materialmente relevante.
- [x] Confirmar que nenhum documento da Fundação contradiz o FF-0001.

## Gate F0

A Fundação está concluída quando FF-0001, FF-0002, FF-0003 e FF-0004 estiverem em estado CANONICAL e consistentes entre si.

**Status do Gate F0:** APROVADO em 2026-09-04.

A auditoria de consistência confirmou que:

- FF-0001 permanece como autoridade normativa máxima;
- FF-0002 operacionaliza gates e uso do Codex sem alterar princípios constitucionais;
- FF-0003 preserva decisões em nível subordinado às fontes de autoridade superiores;
- FF-0004 padroniza vocabulário sem antecipar decisões de produto, domínio ou arquitetura;
- os estados documentais, a hierarquia de autoridade e as regras de conflito são consistentes entre os quatro documentos;
- as pendências de licenciamento, produto, domínio e arquitetura estão conscientemente alocadas a fases posteriores e não bloqueiam a Fundação.

---

# 6. FASE 1 — Produto

## Objetivo

Definir claramente qual problema o Fiel Fiscaliza resolve, para quem, quais resultados pretende produzir e qual é a menor versão capaz de entregar utilidade real.

## Documentos

- FF-0005 — PRODUCT_VISION
- FF-0006 — USERS_AND_USE_CASES
- FF-0007 — SCOPE
- FF-0008 — MVP_SPEC

## Checklist

### Problema e valor

- [ ] Formular o problema central do produto sem descrever prematuramente a solução técnica.
- [ ] Identificar quais dificuldades reais de fiscalização o sistema pretende reduzir.
- [ ] Mapear iniciativas já existentes e quais problemas elas já resolvem.
- [ ] Identificar lacunas que justifiquem a existência do Fiel Fiscaliza.
- [ ] Definir quais resultados tornam a ferramenta útil mesmo com audiência pequena.

### Usuários

- [ ] Identificar usuários primários do MVP.
- [ ] Identificar usuários secundários relevantes.
- [ ] Definir necessidades e capacidades distintas desses usuários.
- [ ] Documentar casos de uso prioritários.
- [ ] Evitar presumir acesso privilegiado ao SCCP, Gaviões ou qualquer outra instituição.

### Escopo

- [ ] Definir explicitamente o que pertence ao produto.
- [ ] Definir explicitamente o que não pertence ao produto.
- [ ] Definir critérios para temas esportivos que adquirem relevância institucional.
- [ ] Definir fronteiras entre memória institucional, fiscalização e portal de notícias.

### MVP

- [ ] Definir a proposta de valor mínima.
- [ ] Definir funcionalidades obrigatórias do MVP.
- [ ] Definir funcionalidades conscientemente adiadas.
- [ ] Definir jornada principal do usuário.
- [ ] Definir critérios objetivos de aceite do MVP.
- [ ] Definir o que significa “MVP publicável”.
- [ ] Confirmar que o MVP é sustentável por uma pessoa.
- [ ] Confirmar que o MVP não depende de acesso institucional privilegiado.

## Gate F1

A fase Produto está concluída quando FF-0005 a FF-0008 estiverem CANONICAL e o MVP puder ser descrito sem depender de decisões técnicas ainda não tomadas.

---

# 7. FASE 2 — Política editorial e evidências

## Objetivo

Definir as regras que impedem o Fiel Fiscaliza de transformar informação pública em acusação irresponsável, propaganda política, fofoca ou registro historicamente enganoso.

## Documentos

- FF-0009 — EDITORIAL_POLICY
- FF-0010 — SOURCE_POLICY
- FF-0011 — CLAIMS_AND_EVIDENCE
- FF-0012 — CORRECTIONS_POLICY

## Checklist

### Política editorial

- [ ] Definir critérios de relevância institucional.
- [ ] Definir diferença entre fato, alegação, denúncia, investigação, processo, decisão e opinião.
- [ ] Definir tratamento de versões conflitantes.
- [ ] Definir quando uma informação deve permanecer “desconhecida” ou “não confirmada”.
- [ ] Definir limites contra inferências de intenção, culpa, aliança ou voto.
- [ ] Definir regras para linguagem politicamente sensível.

### Fontes

- [ ] Definir categorias de fontes.
- [ ] Definir prioridade de fontes primárias.
- [ ] Definir uso aceitável de imprensa e fontes especializadas.
- [ ] Definir tratamento de redes sociais e declarações públicas.
- [ ] Definir tratamento de fontes indisponíveis posteriormente.
- [ ] Definir metadados mínimos de proveniência.
- [ ] Definir quando múltiplas fontes são necessárias.
- [ ] Definir como separar autoridade sobre um ato da veracidade material de alegações contidas nele.

### Claims e evidências

- [ ] Definir modelo conceitual de claim.
- [ ] Definir estados de verificação.
- [ ] Definir contestação e contraditório factual.
- [ ] Definir evolução de status ao longo do tempo.
- [ ] Definir relação entre afirmação e evidência.
- [ ] Definir como representar investigações sem presumir culpa.
- [ ] Definir como representar decisões não definitivas.

### Correções

- [ ] Definir processo para corrigir dados incorretos.
- [ ] Definir quais correções precisam de histórico público.
- [ ] Definir como registrar retratações ou fontes posteriormente invalidadas.
- [ ] Definir como corrigir sem apagar indevidamente o registro histórico.

## Gate F2

A fase Editorial está concluída quando FF-0009 a FF-0012 estiverem CANONICAL e for possível avaliar de maneira reproduzível se um dado pode ou não ser publicado.

---

# 8. FASE 3 — Modelo de domínio e temporalidade

## Objetivo

Transformar os princípios editoriais e institucionais em um modelo conceitual capaz de sobreviver às mudanças do Corinthians.

## Documentos

- FF-0013 — DOMAIN_MODEL
- FF-0014 — TEMPORAL_MODEL
- FF-0015 — EVENT_TAXONOMY

## Checklist

### Entidades e relações

- [ ] Definir entidades centrais do domínio.
- [ ] Definir identidade e ciclo de vida de pessoas.
- [ ] Definir organizações e órgãos institucionais.
- [ ] Definir cargos, mandatos e vínculos.
- [ ] Definir documentos e versões.
- [ ] Definir fontes e evidências.
- [ ] Definir eventos institucionais.
- [ ] Definir votações.
- [ ] Definir investigações, processos e decisões sem confundir seus estados.
- [ ] Definir relações institucionais verificáveis.

### Temporalidade

- [ ] Definir diferença entre estado atual e estado histórico.
- [ ] Definir data de ocorrência, publicação, coleta, validade e revisão quando aplicável.
- [ ] Definir encerramento de cargos e mandatos sem sobrescrever histórico.
- [ ] Definir evolução de investigações e processos.
- [ ] Definir como valores financeiros concorrentes são contextualizados no tempo.
- [ ] Definir como correções afetam registros históricos.
- [ ] Validar o modelo contra cenários de reforma estatutária.
- [ ] Validar o modelo contra cenário de intervenção judicial.
- [ ] Validar o modelo contra cenário de SAF ou nova estrutura societária.

### Taxonomia

- [ ] Criar taxonomia inicial de eventos institucionais.
- [ ] Evitar categorias excessivamente específicas sem necessidade.
- [ ] Permitir expansão sem migração conceitual destrutiva.
- [ ] Definir regras para eventos relacionados e eventos derivados.

## Gate F3

A fase Domínio está concluída quando FF-0013 a FF-0015 estiverem CANONICAL e o modelo conseguir representar, sem reconstrução conceitual, os principais cenários institucionais atuais e futuros já identificados.

---

# 9. FASE 4 — Arquitetura e infraestrutura

## Objetivo

Definir como implementar o MVP respeitando custo operacional obrigatório de R$ 0, manutenção por exceção, portabilidade e simplicidade.

## Documentos

- FF-0016 — SYSTEM_ARCHITECTURE
- FF-0017 — ZERO_COST_INFRASTRUCTURE
- FF-0018 — INGESTION_PIPELINE
- FF-0019 — DATA_STORAGE
- FF-0020 — AUTOMATION_STRATEGY
- FF-0021 — ADR_INDEX e ADRs relacionados

## Checklist

### Arquitetura geral

- [ ] Definir arquitetura de alto nível.
- [ ] Definir fronteiras entre domínio, coleta, validação e apresentação.
- [ ] Definir o que será static-first.
- [ ] Definir se o MVP necessita ou não de backend em runtime.
- [ ] Definir como busca será executada no MVP.
- [ ] Definir como dados públicos serão gerados e consumidos.
- [ ] Evitar componentes que não resolvam requisito concreto.

### Custo zero

- [ ] Validar cada serviço necessário contra planos gratuitos atuais.
- [ ] Registrar data em que limites gratuitos foram verificados.
- [ ] Verificar riscos de cobrança automática.
- [ ] Preferir hard limits quando disponíveis.
- [ ] Definir rota de migração caso um free tier seja encerrado.
- [ ] Confirmar que nenhum serviço pago é indispensável.
- [ ] Confirmar que IA paga não está no caminho crítico público.

### Coleta

- [ ] Definir fluxo de descoberta de alterações.
- [ ] Definir captura e normalização.
- [ ] Definir deduplicação.
- [ ] Definir snapshots e hashes quando aplicável.
- [ ] Definir tratamento de fontes que mudam ou desaparecem.
- [ ] Definir filas de revisão.
- [ ] Definir regras para publicação automática versus aprovação humana.
- [ ] Definir estratégia para documentos e PDFs.
- [ ] Definir mecanismos de coleta que não dependam de burlar autenticação, controles de acesso ou restrições técnicas.
- [ ] Definir política de taxa de acesso, retries e comportamento responsável por fonte.
- [ ] Avaliar termos de uso, regras de acesso e limitações técnicas relevantes quando uma fonte exigir coleta automatizada.

### Persistência

- [ ] Escolher formato e tecnologia de armazenamento do MVP.
- [ ] Garantir portabilidade.
- [ ] Garantir versionamento e histórico.
- [ ] Definir IDs estáveis.
- [ ] Definir estratégia de migrations quando aplicável.
- [ ] Definir exportação e restauração.
- [ ] Confirmar que o modelo preserva proveniência.

### Automação

- [ ] Definir frequência de coleta por classe de fonte.
- [ ] Definir jobs automatizados.
- [ ] Definir retries e falhas.
- [ ] Definir notificações ao mantenedor.
- [ ] Definir processo de revisão em lote.
- [ ] Definir como reduzir trabalho manual recorrente.

### ADRs

- [ ] Registrar decisões arquiteturais de impacto relevante.
- [ ] Documentar alternativas consideradas.
- [ ] Documentar consequências e riscos.
- [ ] Confirmar compatibilidade de cada ADR com FF-0001.

## Gate F4

A fase Arquitetura está concluída quando FF-0016 a FF-0021 estiverem suficientemente especificados e CANONICAL para o MVP, e todas as decisões arquiteturais bloqueantes possuírem ADR aprovado quando necessário.

---

# 10. FASE 5 — Experiência e linguagem do produto

## Objetivo

Definir como um corinthiano comum compreenderá e utilizará o Fiel Fiscaliza sem depender de conhecimento técnico, jurídico ou político especializado.

## Documentos

- FF-0022 — INFORMATION_ARCHITECTURE
- FF-0023 — USER_FLOWS
- FF-0024 — DESIGN_SYSTEM
- FF-0025 — CONTENT_STYLE_GUIDE
- FF-0026 — UI_COPY_CATALOG

## Checklist

### Informação

- [ ] Definir hierarquia de navegação.
- [ ] Definir páginas e visões necessárias para o MVP.
- [ ] Definir relações entre pessoas, eventos, documentos e fontes na interface.
- [ ] Definir mecanismos de descoberta histórica.
- [ ] Definir busca e filtros do MVP.
- [ ] Definir como incerteza e status editorial aparecem visualmente.

### Fluxos

- [ ] Definir jornada principal do usuário.
- [ ] Definir consulta de evento.
- [ ] Definir consulta de pessoa ou órgão quando aplicável.
- [ ] Definir acesso à evidência e fonte original.
- [ ] Definir navegação temporal.
- [ ] Definir estados vazios e informação indisponível.

### Design

- [ ] Definir princípios visuais.
- [ ] Definir acessibilidade mínima esperada.
- [ ] Definir componentes necessários ao MVP.
- [ ] Evitar identidade visual que sugira oficialidade do SCCP ou da Gaviões.
- [ ] Evitar estética que comprometa legibilidade documental.

### Linguagem

- [ ] Definir voz e tom.
- [ ] Definir termos sensíveis.
- [ ] Definir microcopy essencial do MVP.
- [ ] Definir nomenclaturas consistentes com FF-0004.
- [ ] Revisar textos para evitar transformar alegação em fato.

## Gate F5

A fase Experiência está concluída quando as jornadas e interfaces necessárias para o MVP puderem ser implementadas sem o Codex precisar inventar comportamento, nomenclatura ou regras editoriais.

Detalhes visuais não bloqueantes podem continuar evoluindo por versionamento posterior, desde que não deixem decisões essenciais para o agente implementar por conta própria.

---

# 11. FASE 6 — Qualidade, segurança e risco

## Objetivo

Definir como o Fiel Fiscaliza evitará regressões, exposição indevida de dados, falhas editoriais graves e riscos previsíveis de operação.

## Documentos

- FF-0027 — TEST_STRATEGY
- FF-0028 — SECURITY_AND_PRIVACY
- FF-0029 — LEGAL_AND_REPUTATIONAL_RISK
- FF-0030 — RISK_REGISTER

## Checklist

### Testes

- [ ] Definir níveis de teste do MVP.
- [ ] Definir testes prioritários do domínio temporal.
- [ ] Definir testes dos coletores.
- [ ] Definir testes de normalização e deduplicação.
- [ ] Definir testes de geração/publicação.
- [ ] Definir quais regras editoriais devem possuir validação automatizada.

### Segurança e privacidade

- [ ] Modelar ameaças relevantes para a arquitetura escolhida.
- [ ] Definir tratamento de segredos e credenciais técnicas.
- [ ] Confirmar que dados privados não fazem parte do escopo.
- [ ] Definir proteção contra injeção de conteúdo malicioso proveniente de fontes externas quando aplicável.
- [ ] Definir política para dependências e atualizações de segurança.

### Risco jurídico, propriedade intelectual e reputação

- [ ] Mapear riscos de difamação e falsa atribuição factual.
- [ ] Mapear risco de descontextualização histórica.
- [ ] Mapear risco de uso indevido de dados pessoais.
- [ ] Mapear risco de parecer iniciativa oficial.
- [ ] Avaliar uso de nomes, marcas, escudos, logos e identidade visual de terceiros.
- [ ] Distinguir informação publicamente acessível de conteúdo livremente redistribuível.
- [ ] Definir estratégia de licenciamento para código, documentação e dados estruturados antes do release público do MVP ou da aceitação de contribuições externas, o que ocorrer primeiro.
- [ ] Definir política de preservação ou referência a documentos de terceiros, priorizando metadados, hashes e links quando a redistribuição integral não for adequada.
- [ ] Definir mitigação por evidência, linguagem e correção.

### Registro de riscos

- [ ] Registrar riscos técnicos.
- [ ] Registrar riscos editoriais.
- [ ] Registrar riscos operacionais.
- [ ] Registrar riscos de sustentabilidade.
- [ ] Atribuir mitigação e prioridade aos riscos críticos.

## Gate F6

A fase Qualidade está concluída quando os riscos críticos do MVP estiverem identificados, possuírem mitigação e forem refletidos nos critérios de implementação e aceite.

---

# 12. FASE 7 — Operação e manutenção

## Objetivo

Garantir que o Fiel Fiscaliza consiga continuar funcionando com pouco tempo do mantenedor e sem depender de alimentação manual diária.

## Documentos

- FF-0031 — SOURCE_REGISTRY
- FF-0032 — MAINTENANCE
- FF-0033 — OBSERVABILITY
- FF-0034 — BACKUP_AND_RECOVERY

## Checklist

### Fontes iniciais

- [ ] Criar registro inicial das fontes necessárias ao MVP.
- [ ] Registrar responsável/publicador.
- [ ] Registrar URL ou mecanismo de acesso.
- [ ] Registrar tipo e prioridade editorial.
- [ ] Registrar formato técnico.
- [ ] Registrar frequência esperada de mudança.
- [ ] Registrar estratégia de coleta.
- [ ] Registrar limitações conhecidas.

### Manutenção

- [ ] Definir rotina editorial por exceção.
- [ ] Definir revisão em lote.
- [ ] Definir tratamento de backlog de pendências.
- [ ] Definir procedimento quando um coletor quebra.
- [ ] Definir procedimento quando uma fonte muda de formato.
- [ ] Estimar carga humana normal de manutenção.
- [ ] Confirmar que não existe obrigação de alimentação diária.

### Observabilidade

- [ ] Definir health checks.
- [ ] Definir detecção de coletor silenciosamente parado.
- [ ] Definir alertas mínimos.
- [ ] Definir visibilidade de última coleta e última revisão.
- [ ] Definir logs suficientes para diagnóstico sem infraestrutura onerosa.

### Backup e recuperação

- [ ] Definir o que precisa ser preservado.
- [ ] Definir estratégia de backup.
- [ ] Definir processo de recuperação.
- [ ] Definir como reconstruir o site a partir dos dados canônicos.
- [ ] Definir como migrar para outro provedor se necessário.

## Gate F7

A fase Operação está concluída quando houver um processo plausível de operação individual, recuperação de falhas e manutenção de baixo esforço compatível com o FF-0001.

---

# 13. FASE 8 — Preparação de entrega e execução

## Objetivo

Converter todas as decisões anteriores em tarefas pequenas, verificáveis e prontas para implementação eficiente.

## Documentos

- FF-0035 — ROADMAP
- FF-0036 — BACKLOG
- FF-0037 — DEFINITION_OF_READY
- FF-0038 — DEFINITION_OF_DONE
- FF-0039 — AGENTS

## Checklist

### Roadmap

- [ ] Definir marcos até o MVP.
- [ ] Separar MVP de pós-MVP.
- [ ] Definir dependências entre marcos.
- [ ] Evitar datas artificiais sem necessidade real.

### Backlog

- [ ] Decompor MVP em épicos/features quando útil.
- [ ] Decompor features em tarefas implementáveis.
- [ ] Identificar dependências.
- [ ] Identificar tarefas que não precisam de Codex.
- [ ] Identificar tarefas de maior risco técnico.

### Definition of Ready

- [ ] Definir informações mínimas para uma tarefa entrar em implementação.
- [ ] Exigir problema e objetivo claros.
- [ ] Exigir critérios de aceite.
- [ ] Exigir referências aos documentos canônicos relevantes.
- [ ] Exigir tratamento de casos de borda relevantes.
- [ ] Exigir identificação de restrições arquiteturais.

### Definition of Done

- [ ] Definir testes necessários.
- [ ] Definir critérios de documentação.
- [ ] Definir critérios de segurança.
- [ ] Definir critérios de revisão.
- [ ] Definir quando uma alteração está pronta para merge.

### Instruções para agentes

- [ ] Preencher FF-0039 / `AGENTS.md` a partir das regras canônicas vigentes.
- [ ] Instruir agentes a ler FF-0001 e documentos relacionados à tarefa.
- [ ] Proibir alteração silenciosa de requisitos canônicos.
- [ ] Instruir agentes a reportar conflitos de especificação.
- [ ] Instruir agentes a executar testes relevantes.
- [ ] Instruir agentes a não introduzir serviço pago sem aprovação.
- [ ] Instruir agentes a preservar temporalidade e proveniência.

## Gate F8

A fase Entrega está concluída quando o primeiro conjunto de tarefas do MVP estiver em estado Ready e o `AGENTS.md` contiver regras suficientes para impedir decisões autônomas contrárias à documentação canônica.

---

# 14. Gate final — CODEX READY

O Codex está formalmente liberado para implementação regular do MVP somente quando todos os critérios abaixo forem verdadeiros.

## Governança

- [x] Gate F0 aprovado.
- [x] FF-0001 continua vigente e sem conflito conhecido.
- [x] Nenhum conflito CANONICAL não resolvido existe.

## Produto

- [ ] Gate F1 aprovado.
- [ ] MVP possui escopo e critérios de aceite claros.

## Editorial

- [ ] Gate F2 aprovado.
- [ ] Regras de publicação factual estão definidas.

## Domínio

- [ ] Gate F3 aprovado.
- [ ] Temporalidade e proveniência estão modeladas.

## Arquitetura

- [ ] Gate F4 aprovado.
- [ ] Arquitetura respeita custo obrigatório de R$ 0.
- [ ] Decisões arquiteturais bloqueantes possuem ADR quando necessário.
- [ ] Limites, preços e condições dos serviços externos críticos foram revalidados perto da data do CODEX READY.

## Experiência

- [ ] Gate F5 aprovado.
- [ ] O agente não precisa inventar fluxos essenciais do MVP.

## Qualidade

- [ ] Gate F6 aprovado.
- [ ] Riscos críticos possuem mitigação definida.

## Operação

- [ ] Gate F7 aprovado.
- [ ] Manutenção por exceção está operacionalmente especificada.
- [ ] Acesso às fontes críticas do MVP foi revalidado perto da data do CODEX READY.

## Execução

- [ ] Gate F8 aprovado.
- [ ] `AGENTS.md` está pronto.
- [ ] A primeira tarefa do Codex atende à Definition of Ready.

### Resultado

Quando todos os itens acima forem concluídos, registrar formalmente:

> **CODEX READY — Fiel Fiscaliza MVP**

com:

- data;
- versão vigente do FF-0001;
- commit do repositório;
- versão do MVP_SPEC;
- arquitetura vigente;
- lista de pendências não bloqueantes;
- ID da primeira tarefa destinada ao Codex;
- aprovação explícita de André.

---

# 15. Política de economia de cota do Codex

Mesmo depois do estado CODEX READY, o Codex continua sendo recurso escasso.

Cada tarefa deve ser classificada antes da execução.

## Classe Verde — evitar Codex

Preferir ChatGPT + edição manual para:

- documentação;
- pequenas alterações localizadas;
- configurações simples;
- snippets pequenos;
- revisão de texto;
- análise de logs já fornecidos;
- planejamento;
- desenho de testes;
- especificação de interfaces.

## Classe Amarela — avaliar caso a caso

Pode usar Codex quando houver ganho real em:

- feature média envolvendo múltiplos arquivos;
- integração moderada;
- mudança com testes distribuídos;
- debugging que exija navegação pelo repositório.

Antes, tentar reduzir o escopo e especificar completamente a tarefa.

## Classe Vermelha — Codex prioritário

Reservar Codex principalmente para:

- implementação multiarquivo extensa;
- refatorações transversais;
- bugs complexos;
- alterações grandes de persistência;
- ciclos repetidos de implementação, execução e correção;
- tarefas que dependam fortemente de navegação autônoma pelo repositório.

## Regra

> **Nunca gastar Codex para descobrir aquilo que deveria ter sido decidido antes da tarefa.**

---

# 16. Critérios para uma tarefa ser enviada ao Codex

Uma tarefa destinada ao Codex deve conter, quando aplicável:

- ID da tarefa;
- objetivo;
- contexto mínimo necessário;
- documentos CANONICAL relevantes;
- arquivos ou módulos provavelmente envolvidos;
- comportamento esperado;
- critérios de aceite;
- casos de borda conhecidos;
- restrições arquiteturais;
- testes esperados;
- coisas que explicitamente não devem ser alteradas.

Se uma dessas informações estiver ausente porque ainda não foi decidida, a tarefa deve voltar para especificação antes de consumir cota do Codex.

---

# 17. O que pode continuar evoluindo após CODEX READY

CODEX READY não significa que todos os detalhes do Fiel Fiscaliza estão permanentemente congelados.

Podem continuar evoluindo por versionamento normal:

- detalhes visuais;
- microcopy não estrutural;
- fontes adicionais;
- taxonomias secundárias;
- funcionalidades pós-MVP;
- otimizações;
- novas integrações;
- decisões futuras motivadas por uso real.

Entretanto, mudanças que conflitem com documentação CANONICAL devem seguir o processo formal definido no FF-0001.

## 17.1 Validade do estado CODEX READY

CODEX READY é uma aprovação baseada em um conjunto específico de documentos, decisões e premissas em determinado momento. Ele não constitui autorização permanente e irrestrita.

Se, após a liberação:

- um documento CANONICAL que afete o MVP sofrer mudança material;
- uma decisão arquitetural bloqueante for substituída;
- uma fonte crítica deixar de ser acessível;
- uma condição de free tier ou custo zero deixar de ser verdadeira;
- um risco crítico novo invalidar uma premissa anterior;

as partes afetadas do estado CODEX READY devem ser marcadas como **REVIEW REQUIRED** até que uma análise de impacto confirme que a implementação pode continuar.

Não é necessário paralisar tarefas comprovadamente não relacionadas. O bloqueio deve ser proporcional ao impacto da mudança.

A revalidação deve registrar quais gates foram afetados e quais permanecem válidos.

---

# 18. Anti-patterns

Este processo deve impedir explicitamente os seguintes comportamentos:

## Coding-first

Começar a implementar porque “a ideia geral já está clara”.

## Architecture astronautics

Adicionar infraestrutura sofisticada sem requisito concreto.

## Documentation theater

Produzir documentos apenas para completar checkboxes sem resolver decisões reais.

## AI-driven requirements

Permitir que ChatGPT ou Codex inventem requisitos ausentes durante implementação.

## Current-Corinthians hardcoding

Codificar a estrutura institucional de 2026 como se fosse permanente.

## News-portal drift

Transformar o projeto progressivamente em agregador esportivo genérico.

## Manual-maintenance trap

Criar fluxos que exigem André cadastrando acontecimentos todos os dias.

## Free-tier blindness

Escolher serviço gratuito sem considerar limites, lock-in, possibilidade de cobrança e rota de migração.

## Unverified-publication automation

Permitir que automação transforme alegações sensíveis em fatos públicos sem as salvaguardas editoriais definidas.

## Public-means-republishable

Presumir que uma informação ou documento disponível publicamente pode ser copiado, redistribuído ou republicado integralmente sem análise de direitos, termos ou necessidade.

## Gate bypass

Usar implementação manual, ChatGPT, Codex, scripts ou experimentos como forma de cristalizar silenciosamente uma decisão que ainda deveria passar pelo processo de especificação e aprovação.

---

# 19. Estado atual

Na entrada em vigor desta versão:

- FF-0001 está **CANONICAL v1.0**;
- FF-0002 está **CANONICAL v1.1**;
- FF-0003 está **CANONICAL v1.0**;
- FF-0004 está **CANONICAL v1.0**;
- o **Gate F0 — Fundação está APROVADO**;
- o repositório GitHub e a estrutura documental estão criados;
- o Fiel Fiscaliza entra na **FASE 1 — Produto**;
- Codex continua **não liberado para implementação regular do produto**.

O próximo objetivo é concluir a Fase 1 por meio de FF-0005 — PRODUCT_VISION, FF-0006 — USERS_AND_USE_CASES, FF-0007 — SCOPE e FF-0008 — MVP_SPEC.

---

# 20. Vigência

Esta versão possui status **CANONICAL** e entra em vigor em **2026-09-04** por aprovação explícita de André.

**FF-0002 — PRE_CODEX_CHECKLIST v1.1 // CANONICAL**

Esta revisão registra a conclusão e aprovação do **Gate F0 — Fundação** após auditoria de consistência dos documentos FF-0001 a FF-0004.