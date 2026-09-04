# FF-0003 — DECISION_LOG

**Nome do documento:** Decision Log  
**ID:** FF-0003  
**Versão:** 1.4  
**Status:** CANONICAL  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento preserva as decisões relevantes tomadas ao longo da vida do Fiel Fiscaliza.

Seu objetivo é impedir que decisões importantes fiquem enterradas apenas em chats, sejam esquecidas com o tempo ou sejam reinterpretadas sem rastreabilidade.

O Decision Log registra principalmente:

- decisões fundacionais;
- decisões de produto;
- decisões operacionais;
- decisões de governança do projeto;
- decisões que ainda não justificam um ADR próprio;
- aprovações ou substituições de documentos canônicos;
- decisões negativas relevantes, isto é, escolhas conscientes de **não** adotar algo naquele momento.

Este documento é subordinado ao **FF-0001 — PROJECT_CONSTITUTION**, aos demais documentos CANONICAL específicos de cada área e aos ADRs aprovados.

Se uma entrada deste log entrar em conflito com uma fonte de autoridade superior, prevalece a fonte superior.

---

# 2. O que este documento não é

O FF-0003 não substitui:

- especificações detalhadas;
- ADRs;
- políticas editoriais;
- modelo de domínio;
- arquitetura;
- backlog;
- documentação de implementação.

Uma entrada deste log deve registrar **o que foi decidido, por quê e onde essa decisão passou a morar**.

Quando uma decisão crescer a ponto de exigir especificação própria, a entrada permanece como registro histórico e passa a referenciar o documento responsável.

---

# 3. Status das decisões

Os status abaixo pertencem às **entradas** do Decision Log e não substituem os estados documentais DRAFT, CANONICAL e DEPRECATED.

### APROVADA

Decisão explicitamente aceita por André e vigente no nível de autoridade indicado.

### SUBSTITUÍDA

Decisão anteriormente aprovada que foi posteriormente substituída por outra.

A entrada original não deve ser removida.

### REVOGADA

Decisão que deixou de vigorar sem substituição direta.

### PENDENTE

Questão registrada, mas ainda não decidida.

Entradas PENDENTES não constituem regra do projeto.

---

# 4. Estrutura das entradas

Cada decisão deve, quando aplicável, registrar:

- **ID**;
- **data da decisão**;
- **data de registro**, quando diferente ou materialmente relevante;
- **status**;
- **decisão**;
- **motivação**;
- **fonte de autoridade / formalização**;
- **impacto**;
- **substitui / é substituída por**;
- **observações**.

Quando a data histórica exata de uma decisão reconstruída não puder ser determinada com segurança, ela não deve ser inventada. Nesse caso, o log deve indicar a data conhecida de formalização ou registrar explicitamente que a data original não foi determinada.

A granularidade deve ser suficiente para reconstruir a evolução do projeto sem transformar o log em duplicação integral dos documentos canônicos.

## 4.1 Identidade, preservação e correção das entradas

IDs `FF-DEC-XXXX` já utilizados não devem ser reutilizados para outra decisão.

Uma decisão substituída, revogada ou posteriormente considerada inadequada não deve ser simplesmente removida do histórico. Seu status deve evoluir e, quando aplicável, a entrada deve apontar para a decisão que a substituiu.

Correções factuais do próprio Decision Log são permitidas. Quando a correção alterar materialmente o significado histórico de uma entrada, ela deve ser rastreável pelo versionamento do documento e explicada na própria entrada ou em decisão relacionada.

O objetivo é preservar memória decisória sem transformar erro de redação em regra imutável.

---

# 5. Decisões fundacionais reconstruídas

As entradas desta seção consolidam decisões tomadas durante a concepção inicial do Fiel Fiscaliza e posteriormente formalizadas, total ou parcialmente, nos documentos canônicos do projeto.

Nas entradas fundacionais abaixo, **2026-09-04 representa a data de formalização inicial no sistema documental**, salvo indicação diferente. O log não deve atribuir artificialmente um horário ou uma data anterior quando isso não estiver preservado de forma confiável.

---

## FF-DEC-0001 — Nome oficial do projeto

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O nome oficial e definitivo do projeto é **Fiel Fiscaliza**.

### Motivação

O nome é curto, intuitivo, diretamente relacionado à torcida do Corinthians e comunica de forma simples a finalidade de fiscalização coletiva do projeto.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seção 2.1.

### Impacto

O nome deve ser utilizado consistentemente em documentação, repositório, produto e comunicações do projeto.

---

## FF-DEC-0002 — Natureza independente, comunitária e sem fins lucrativos

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O Fiel Fiscaliza é um projeto independente, comunitário e sem fins lucrativos.

O projeto não tem por objetivo gerar lucro para o mantenedor nem funcionar como extensão de grupo político, dirigente, empresa ou instituição.

### Motivação

Preservar independência editorial e alinhar o produto à finalidade de utilidade pública para a comunidade corinthiana.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 2, 5 e 44.

---

## FF-DEC-0003 — Missão do Fiel Fiscaliza

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

A missão do projeto é ajudar corinthianos a compreender, acompanhar, preservar e fiscalizar a vida institucional do Sport Club Corinthians Paulista por meio de informação pública, organizada, verificável, contextualizada e historicamente preservada.

### Motivação

O problema central identificado não é ausência absoluta de informação, mas dispersão, dificuldade de consulta, perda de contexto, baixa rastreabilidade e ausência de memória institucional acessível.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 3 e 4.

---

## FF-DEC-0004 — Independência em relação ao SCCP e à Gaviões da Fiel

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O Fiel Fiscaliza não representa oficialmente:

- o Sport Club Corinthians Paulista;
- a Gaviões da Fiel;
- qualquer grupo político do clube.

O fato de André ser associado da Gaviões da Fiel não torna o projeto institucionalmente vinculado à torcida organizada.

### Motivação

Permitir colaboração e proximidade com a comunidade sem criar falsa representação institucional ou comprometer independência editorial.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seção 5.

---

## FF-DEC-0005 — Escopo institucional, não jornalismo esportivo geral

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O Fiel Fiscaliza prioriza governança, política institucional, diretoria, conselhos, eleições, estatuto, finanças, Arena, contratos relevantes, investigações, processos, transparência, documentos, votações e memória política.

O projeto não deve evoluir para portal geral de notícias esportivas.

### Motivação

Evitar perda de foco, sobrecarga operacional e competição desnecessária com veículos cuja função é cobrir futebol cotidiano.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 14 e 15.

---

## FF-DEC-0006 — Integridade editorial acima de velocidade e engajamento

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

A credibilidade factual do Fiel Fiscaliza tem prioridade sobre velocidade de publicação, alcance, viralização ou alinhamento com percepções populares.

O sistema deve distinguir explicitamente fatos, alegações, denúncias, investigações, processos, decisões, opiniões, rumores e estados de incerteza.

### Motivação

O domínio político, financeiro e jurídico do Corinthians envolve acusações, versões conflitantes e procedimentos ainda não concluídos. Uma ferramenta de fiscalização só possui utilidade duradoura se não transformar alegação em fato.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 7, 8, 18 e 19.

---

## FF-DEC-0007 — Existência de investigação não comprova a acusação investigada

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Quando uma investigação, denúncia ou processo estiver documentalmente comprovado, o fato confirmado é a existência daquele procedimento ou alegação.

Isso não comprova automaticamente a veracidade material da acusação.

### Motivação

Evitar que o próprio ato de registrar investigações seja interpretado como atribuição de culpa.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION v1.0, seção 7.

---

## FF-DEC-0008 — Fonte primária não equivale a verdade material absoluta

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Fontes primárias têm prioridade para comprovar atos, documentos, decisões e declarações emitidas por suas respectivas instituições.

Entretanto, uma fonte primária não torna automaticamente verdadeira toda alegação material que contenha quando houver contestação, apuração pendente ou posição de parte interessada.

### Motivação

Separar corretamente autoridade documental de verdade material sobre fatos controvertidos.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION v1.0, seção 10.

---

## FF-DEC-0009 — Proveniência é parte estrutural do dado

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Informações factuais relevantes devem carregar proveniência suficiente para reconstruir sua origem, publicação, coleta, documento ou URL e contexto temporal.

### Motivação

Fiscalização sem rastreabilidade se transforma facilmente em reprodução de narrativa. A evidência deve acompanhar o dado desde sua modelagem.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seção 9.

---

## FF-DEC-0010 — Histórico não deve ser sobrescrito pelo estado atual

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O Fiel Fiscaliza deve modelar mudanças ao longo do tempo e preservar estados anteriores.

Mudanças de cargo, valores, decisões, investigações, relações e estrutura institucional devem gerar evolução histórica, não substituição destrutiva do passado.

### Motivação

O Corinthians pode passar por reforma estatutária, intervenção judicial, SAF, mudança de órgãos ou outras reestruturações. O sistema precisa sobreviver conceitualmente a essas mudanças.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 11, 12 e 13.

---

## FF-DEC-0011 — Custo operacional mensal obrigatório de R$ 0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Enquanto o projeto for mantido pessoalmente por André, sua arquitetura deve permitir operação com custo mensal obrigatório de **R$ 0**.

Custos opcionais podem existir apenas por decisão explícita e não devem se tornar silenciosamente indispensáveis.

### Motivação

O Fiel Fiscaliza não possui objetivo de lucro e não deve transformar-se em despesa recorrente pessoal para continuar existindo.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 22 e 23.

---

## FF-DEC-0012 — Preferência por static-first, portabilidade e complexidade sob demanda

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

A arquitetura deve preferir soluções static-first, portáteis, observáveis, simples de manter e baseadas em padrões abertos.

Infraestrutura dinâmica ou complexa deve ser introduzida somente quando um requisito concreto a justificar.

### Motivação

Reduzir custo, superfície de ataque, manutenção e lock-in, preservando capacidade futura de migração.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 24, 27 e 28.

---

## FF-DEC-0013 — IA paga fora do caminho crítico público

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

IA pode auxiliar desenvolvimento, pesquisa, classificação, extração e revisão, mas APIs pagas de IA não devem ser requisito para o funcionamento essencial da aplicação pública enquanto vigorar o requisito de custo zero.

### Motivação

Evitar custo variável e dependência comercial no caminho crítico do produto.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 25 e 26.

---

## FF-DEC-0014 — Manutenção por exceção

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

André não deve precisar alimentar manualmente o Fiel Fiscaliza todos os dias.

A direção operacional desejada é:

**coleta automática → detecção → normalização → fila de revisão → validação humana → publicação.**

### Motivação

O projeto precisa ser sustentável por uma pessoa e aproveitar software para trabalho repetitivo, preservando julgamento humano para significado editorial.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 20 e 21.

---

# 6. Governança documental e ambiente de trabalho

---

## FF-DEC-0015 — Documentação é memória oficial; chats são espaço de elaboração

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Chats são utilizados para pesquisar, discutir, propor e revisar.

Documentos formais são utilizados para estabelecer, preservar, comunicar e versionar decisões.

Princípio adotado:

> **Chats servem para pensar. Documentos servem para lembrar.**

### Motivação

Reduzir perda de contexto e evitar que decisões importantes dependam da memória de uma conversa ou de um modelo.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seção 35.

---

## FF-DEC-0016 — Estados documentais e hierarquia de autoridade

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Estados formais de documentos:

- DRAFT;
- CANONICAL;
- DEPRECATED.

Hierarquia de autoridade:

1. FF-0001 — PROJECT_CONSTITUTION;
2. documentos CANONICAL específicos da área;
3. ADRs aprovados;
4. FF-0003 — DECISION_LOG;
5. documentos DRAFT;
6. chats e discussões ainda não formalizadas.

### Motivação

Impedir contradições silenciosas e tornar explícito qual documento prevalece quando houver divergência.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seções 36 a 39.

---

## FF-DEC-0017 — Projeto ChatGPT como workspace intelectual e GitHub como repositório versionado

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O trabalho do Fiel Fiscaliza será dividido entre:

- **Projeto Fiel Fiscaliza no ChatGPT:** pesquisa, raciocínio, arquitetura, especificação, documentação e revisão;
- **GitHub:** preservação versionada da documentação e, futuramente, do código e dos dados do projeto;
- **Codex:** agente de implementação utilizado seletivamente quando sua atuação autônoma sobre o repositório gerar benefício real.

Documentos CANONICAL mantidos no projeto e no repositório devem representar as mesmas decisões vigentes.

A autoridade de uma decisão decorre de seu status e da hierarquia documental definida pelo FF-0001, e não simplesmente do local físico em que uma cópia do arquivo esteja armazenada.

### Motivação

Separar elaboração intelectual, memória versionada e execução de código, reduzindo dependência da memória de qualquer ferramenta individual.

### Impacto

Exige disciplina de sincronização das decisões canônicas relevantes entre as fontes utilizadas no Projeto ChatGPT e o repositório.

---

## FF-DEC-0018 — Repositório oficial criado no GitHub

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O repositório versionado do projeto foi criado como:

`andresant-ana/fiel-fiscaliza`

O repositório está público em sua configuração atual.

### Motivação

Permitir transparência, auditabilidade, histórico de mudanças e futura colaboração.

### Observação

A existência pública do repositório não determina, por si só, a licença futura de código, documentação ou dados.

---

## FF-DEC-0019 — Estrutura documental inicial numerada e modular

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

A documentação formal foi organizada em blocos funcionais e IDs estáveis `FF-XXXX`, incluindo inicialmente:

- `00-foundation`;
- `10-product`;
- `20-editorial`;
- `30-domain`;
- `40-architecture`;
- `50-experience`;
- `60-quality`;
- `70-operations`;
- `80-delivery`.

Foi criada uma estrutura inicial até **FF-0039**, com diretório separado para ADRs.

### Motivação

Facilitar navegação, referência cruzada, evolução modular e instrução de agentes.

### Impacto

A estrutura pode evoluir futuramente, mas IDs já utilizados não devem ser reutilizados silenciosamente para significados diferentes.

---

## FF-DEC-0028 — Rastreabilidade de impacto entre documentos canônicos

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Quando uma decisão de um documento puder alterar materialmente outro documento canônico, essa relação deve ser identificável por referência, seção de impacto, índice ou mecanismo equivalente.

Não é obrigatório criar dependências artificiais entre todos os documentos.

### Motivação

Impedir que mudanças relevantes sejam feitas em uma especificação sem que seus efeitos sobre documentos relacionados sejam percebidos.

### Formalização

- FF-0002 — PRE_CODEX_CHECKLIST v1.0, seção 3.6 e Gate F0.

---

# 7. Uso do Codex e preparação para implementação

---

## FF-DEC-0020 — Cota do Codex é recurso escasso

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O Fiel Fiscaliza deve utilizar ChatGPT prioritariamente para pesquisa, produto, arquitetura, especificação, documentação, revisão e decomposição de tarefas.

Codex deve ser reservado para situações em que sua capacidade de navegar e modificar o repositório de forma autônoma produza ganho significativo.

### Motivação

A cota disponível no plano de André é limitada e concorre com outros projetos pessoais.

### Formalização

- FF-0001 — PROJECT_CONSTITUTION, seção 34.
- FF-0002 — PRE_CODEX_CHECKLIST, seções 15 e 16.

---

## FF-DEC-0021 — Implementação regular só após estado CODEX READY

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O Codex não deve iniciar implementação regular do código de produção do MVP antes do cumprimento dos gates definidos no FF-0002 e da declaração formal **CODEX READY — Fiel Fiscaliza MVP**.

Exceções técnicas prévias devem ser limitadas, explicitamente aprovadas e não podem cristalizar silenciosamente requisitos ainda em aberto.

### Motivação

Evitar coding-first, desperdício de cota e retrabalho arquitetural/editorial.

### Formalização

- FF-0002 — PRE_CODEX_CHECKLIST v1.0 // CANONICAL.

---

## FF-DEC-0022 — Classificação Verde, Amarela e Vermelha para uso do Codex

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Tarefas serão classificadas antes de consumir Codex:

- **Verde:** evitar Codex;
- **Amarela:** avaliar caso a caso;
- **Vermelha:** Codex prioritário.

### Motivação

Usar a cota onde a autonomia sobre múltiplos arquivos, testes e ciclos de correção gera maior retorno.

### Formalização

- FF-0002 — PRE_CODEX_CHECKLIST, seção 15.

---

## FF-DEC-0023 — CODEX READY é revalidável, não permanente

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Após um estado CODEX READY, mudanças materiais em documentos canônicos, arquitetura, free tiers, fontes críticas ou riscos podem colocar apenas as áreas afetadas em **REVIEW REQUIRED**.

Tarefas comprovadamente não relacionadas não precisam ser bloqueadas.

### Motivação

O Corinthians, as fontes públicas e a infraestrutura gratuita mudam ao longo do tempo. A autorização de implementação precisa refletir as premissas realmente vigentes.

### Formalização

- FF-0002 — PRE_CODEX_CHECKLIST, seção 17.1.

---

# 8. Decisões conscientemente adiadas

---

## FF-DEC-0024 — Stack e provedores de infraestrutura ainda não estão definidos

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

Não há, neste momento, decisão CANONICAL sobre:

- framework de frontend;
- linguagem principal de implementação;
- banco de dados;
- formato definitivo de persistência;
- provedor de hospedagem;
- provedor de jobs;
- Cloudflare;
- Supabase;
- GitHub Actions como runtime operacional;
- JSON como armazenamento principal;
- necessidade de backend em runtime.

Essas possibilidades foram discutidas apenas como alternativas iniciais e deverão ser decididas na fase de arquitetura com base no MVP e nos requisitos canônicos.

### Motivação

Evitar transformar explorações prematuras em compromisso técnico antes de produto, editorial e domínio estarem definidos.

### Formalização

- FF-0002 — PRE_CODEX_CHECKLIST, Fase 4.

---

## FF-DEC-0025 — Licenciamento ainda não definido

**Data:** 2026-09-04  
**Status:** PENDENTE  

### Questão

Ainda não foi escolhida licença para:

- código;
- documentação;
- dados estruturados.

### Restrição já aprovada

A estratégia deve ser definida antes do release público do MVP ou da aceitação de contribuições externas, o que ocorrer primeiro.

A disponibilidade pública do repositório não deve ser interpretada como autorização irrestrita de reutilização.

### Formalização da pendência

- FF-0002 — PRE_CODEX_CHECKLIST, Fase 6.

---

# 9. Aprovação dos primeiros documentos canônicos e gates

---

## FF-DEC-0026 — FF-0001 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0001 — PROJECT_CONSTITUTION v1.0** foi explicitamente aprovado por André e tornou-se a autoridade normativa máxima do Fiel Fiscaliza.

### Commit de formalização

`eb70be12ac286a3f755d60db40d446b065f159c5`

### Impacto

Toda decisão posterior deve respeitar ou formalmente alterar o FF-0001 quando houver conflito.

---

## FF-DEC-0027 — FF-0002 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0002 — PRE_CODEX_CHECKLIST v1.0** foi explicitamente aprovado por André e tornou-se o mapa oficial de preparação do projeto até o estado CODEX READY.

### Commit de formalização

`060d2730a450969a10d26e8be60c7c3f6b889246`

### Impacto

O projeto permanece em fase pré-Codex e deve concluir os gates pertinentes antes da implementação regular do MVP.

---

## FF-DEC-0029 — FF-0003 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0003 — DECISION_LOG v1.0** foi explicitamente aprovado por André após revisão final e tornou-se o registro canônico resumido da evolução das decisões relevantes do Fiel Fiscaliza, subordinado à hierarquia definida no FF-0001.

### Impacto

A partir desta versão, novas decisões relevantes devem ser registradas incrementalmente sem apagar silenciosamente decisões históricas.

---

## FF-DEC-0030 — FF-0004 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0004 — GLOSSARY v1.0** foi explicitamente aprovado por André após revisão crítica e tornou-se a referência terminológica oficial do Fiel Fiscaliza, subordinada ao FF-0001 e às definições especializadas de documentos CANONICAL dentro de seus respectivos escopos.

### Commit de formalização

`b3b8fb0f7877e6fe401323414b4d742574a9b3ff`

### Impacto

Documentos posteriores devem utilizar o vocabulário comum do FF-0004 ou registrar explicitamente especializações relevantes sem criar conflito canônico silencioso.

---

## FF-DEC-0031 — Gate F0 — Fundação aprovado

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **Gate F0 — Fundação e governança documental** foi aprovado após auditoria de consistência dos documentos FF-0001, FF-0002, FF-0003 e FF-0004.

A auditoria não identificou conflito canônico bloqueante entre os quatro documentos.

### Escopo da auditoria

Foram verificados, entre outros pontos:

- autoridade e hierarquia documental;
- estados DRAFT, CANONICAL e DEPRECATED;
- regras de conflito e versionamento;
- papel do Decision Log e dos futuros ADRs;
- independência institucional e editorial;
- distinção entre fato, alegação, investigação, fonte e evidência;
- proveniência e preservação temporal;
- custo operacional zero, static-first e manutenção por exceção;
- política de uso do Codex e estado CODEX READY;
- consistência terminológica e não antecipação indevida de decisões de produto, domínio ou arquitetura;
- rastreabilidade de impacto entre documentos canônicos.

### Pendências não bloqueantes reconhecidas

Permanecem deliberadamente para fases posteriores:

- licenciamento de código, documentação e dados;
- definição detalhada de produto e MVP;
- política editorial especializada;
- modelo de domínio e temporalidade técnica;
- stack, persistência e provedores de infraestrutura.

Essas pendências não contradizem o FF-0001 e já possuem fase de resolução prevista no FF-0002.

### Formalização

- FF-0002 — PRE_CODEX_CHECKLIST v1.1 // CANONICAL.
- Commit de fechamento do Gate F0: `1901bd1a6c3739f6b13232e965f56b9cb7deea3c`.

### Impacto

A **FASE 0 — Fundação** está concluída.

O Fiel Fiscaliza entra formalmente na **FASE 1 — Produto**, permanecendo pré-Codex e sem autorização para implementação regular do MVP.

---

## FF-DEC-0032 — FF-0005 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0005 — PRODUCT_VISION v1.0** foi aprovado após revisão crítica de produto e tornou-se a visão canônica do Fiel Fiscaliza para a Fase 1.

A visão estabelece como tese de produto que memória institucional estruturada, temporal, verificável e auditável pode reduzir o custo de compreensão e fiscalização da vida institucional do Corinthians.

### Salvaguardas da decisão

A canonização da visão não confirma empiricamente que:

- a dor percebida possui magnitude suficiente para usuários externos;
- existe lacuna de mercado já comprovada;
- as iniciativas atuais são insuficientes;
- determinado conjunto de funcionalidades deve compor o MVP.

Esses pontos permanecem hipóteses explícitas a serem testadas antes do Gate F1 conforme a redação então vigente.

### Formalização

- FF-0005 — PRODUCT_VISION v1.0 // CANONICAL.
- Commit de formalização: `3951684f72445173899518c82074ac3348432fa0`.

### Impacto

FF-0006, FF-0007 e FF-0008 devem derivar da visão sem transformar hipóteses ainda não validadas em fatos ou requisitos silenciosos.

---

## FF-DEC-0033 — Estratégia de validação da Fase 1 ajustada no FF-0005 v1.1

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

A estratégia de validação da Fase 1 foi ajustada para impedir que pesquisa comportamental pré-MVP se torne um gate universal desproporcional para um projeto individual.

Para decisões pequenas, reversíveis e de baixo risco, a Fase 1 pode avançar com:

- desk research robusta;
- busca explícita de contraprovas;
- nível de incerteza declarado;
- dívida de validação documentada;
- gatilhos definidos para reabrir pesquisa quando a incerteza puder alterar materialmente uma decisão.

Entrevistas e testes comportamentais continuam sendo métodos válidos e podem se tornar necessários quando risco, custo, compreensão, segurança, editorial ou irreversibilidade justificarem evidência adicional.

Decisões tomadas sob essa regra não podem ser apresentadas como demanda empiricamente validada.

### Motivação

A revisão crítica do FF-0006 identificou que a redação do FF-0005 v1.0 poderia transformar discovery síncrono em gargalo antes do MVP, apesar de a incerteza poder ser absorvida por um produto inicial pequeno e reversível.

A mudança preserva rigor epistemológico e contraprova, mas torna o nível de pesquisa proporcional à decisão.

### Formalização

- FF-0005 — PRODUCT_VISION v1.1 // CANONICAL.
- Commit de formalização: `bbc34f2f80b62bac507245e9e40e08cfeb459d83`.

### Impacto

- resolve a tensão documental identificada pelo FF-0006 v0.4;
- permite canonizar usuários e casos de uso com dívida de validação explícita;
- não altera missão, visão, tese central, princípios editoriais ou requisito de custo zero;
- pesquisa comportamental pode ser reaberta posteriormente pelos gatilhos definidos nos documentos de produto.

---

## FF-DEC-0034 — FF-0006 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0006 — USERS_AND_USE_CASES v1.0** foi aprovado após desk research, revisão crítica e resolução da tensão metodológica com o FF-0005.

Para a Fase 1:

- o **torcedor institucionalmente engajado** é o usuário primário do MVP;
- torcedor com dúvida institucional pontual, jornalista/comunicador/criador de conteúdo e pesquisador histórico/acadêmico/analista externo são usuários secundários relevantes;
- associado, conselheiro ou participante institucional permanece usuário secundário hipotético;
- os JTBD P0 são verificar afirmação e fonte, reconstruir cronologia e estado atual, contextualizar números financeiros e reconstruir decisão institucional pública;
- demanda, frequência de uso, intensidade da dor e preferências de interface continuam sem validação comportamental e permanecem como dívida explícita.

### Salvaguardas

A decisão não afirma que:

- existe demanda de mercado comprovada;
- usuários retornarão com frequência determinada;
- todos os JTBD P0 precisam entrar no MVP;
- determinada interface, página, módulo ou tecnologia foi escolhida;
- usuários institucionais possuem prioridade sobre quem fiscaliza a instituição.

### Formalização

- FF-0006 — USERS_AND_USE_CASES v1.0 // CANONICAL.
- Commit de formalização: `dec0c5fdab9d1c3c250b2955c788f5eb8e2489a9`.

### Impacto

FF-0007 — SCOPE e FF-0008 — MVP_SPEC passam a poder utilizar usuários e casos de uso definidos pelo FF-0006 como base canônica, respeitando a dívida de validação e sem converter prioridades em funcionalidades automáticas.

---

## FF-DEC-0035 — FF-0007 promovido a CANONICAL v1.0

**Data:** 2026-09-04  
**Status:** APROVADA  

### Decisão

O **FF-0007 — SCOPE v1.0** foi aprovado após revisão crítica e tornou-se a fronteira canônica de produto do Fiel Fiscaliza.

O documento estabelece, entre outros pontos, que:

- o escopo permanente do produto, a cobertura atual e o escopo do MVP são camadas distintas;
- o núcleo do produto é a vida institucional do SCCP e relações externas necessárias para compreender consequências institucionais materialmente relevantes;
- temas adjacentes passam por teste de nexo, consequência institucional, utilidade e base pública/proporcionalidade;
- temas esportivos permanecem fora por padrão e só entram quando houver consequência institucional documentável além da rotina esportiva;
- memória institucional não deve se transformar em fluxo jornalístico cotidiano;
- fiscalização não deve se transformar em campanha eleitoral, militância substantiva ou exposição desproporcional da vida pessoal;
- acesso público não equivale automaticamente a autorização ou adequação para republicação integral;
- expansão material de escopo exige revisão explícita do documento.

### Motivação

Transformar o escopo constitucional amplo em fronteiras operacionais claras sem antecipar o conteúdo do MVP, reduzir risco de scope creep e preservar sustentabilidade, independência editorial e proporcionalidade.

### Formalização

- FF-0007 — SCOPE v1.0 // CANONICAL.
- Commit de formalização: `8093488b4e7514ada4957e25e2657f9eeac8a44f`.

### Impacto

- FF-0008 — MVP_SPEC deve selecionar explicitamente um subconjunto pequeno do escopo permanente;
- documentos editoriais, de domínio, experiência, arquitetura e operações posteriores devem respeitar as fronteiras de escopo vigentes;
- novos casos que já caibam nessas fronteiras não exigem alteração do FF-0007, mas expansão material da natureza do produto exige revisão formal.

---

# 10. Pendências abertas na data desta versão

As entradas abaixo não constituem decisões aprovadas; apenas consolidam questões já reconhecidas como pendentes.

- produzir, revisar e canonizar FF-0008 — MVP_SPEC;
- continuar avaliando as hipóteses do FF-0005 de forma proporcional ao risco e preservar a dívida de validação do FF-0006;
- concluir Gate F1 — Produto;
- definir arquitetura somente após requisitos, política editorial e domínio;
- definir estratégia de licenciamento antes do marco estabelecido em FF-0002;
- manter Codex fora da implementação regular até CODEX READY.

---

# 11. Regra para novas entradas

Uma nova decisão relevante tomada em chat deve provocar a pergunta:

> **Onde esta decisão deve morar?**

Se houver documento canônico específico, ele deve ser atualizado pelo processo aplicável e o Decision Log pode registrar a alteração de forma resumida.

Se não houver documento específico e a decisão for relevante o suficiente para sobreviver ao chat, ela deve receber uma entrada neste log.

Decisões arquiteturais relevantes que exigirem análise de contexto, alternativas e consequências devem preferencialmente utilizar ADR.

Ao adicionar uma nova entrada, deve-se verificar se ela:

- contradiz documento de autoridade superior;
- substitui ou revoga decisão anterior;
- altera materialmente outro documento canônico;
- exige atualização de referência ou seção de impacto relacionada.

---

# 12. Vigência

Esta versão possui status **CANONICAL** e entra em vigor em **2026-09-04** por aprovação explícita de André.

**FF-0003 — DECISION_LOG v1.4 // CANONICAL**

Esta revisão registra a canonização do FF-0007 e mantém como principal pendência de Produto a definição e canonização do FF-0008 — MVP_SPEC antes do Gate F1.
