# FF-0004 — GLOSSARY

**Nome do documento:** Glossary  
**ID:** FF-0004  
**Versão:** 1.0  
**Status:** CANONICAL  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define o vocabulário comum do Fiel Fiscaliza.

Seu objetivo é impedir que palavras importantes adquiram significados diferentes entre:

- chats;
- documentação;
- pesquisa;
- política editorial;
- modelo de domínio;
- arquitetura;
- código;
- interface pública;
- agentes de IA;
- colaboradores futuros.

O glossário não substitui especificações detalhadas. Ele estabelece o significado mínimo compartilhado dos termos utilizados no projeto.

Quando um documento CANONICAL específico definir um conceito com maior precisão dentro de seu próprio escopo, essa definição especializada prevalece naquele contexto, desde que não contradiga o FF-0001 — PROJECT_CONSTITUTION.

---

# 2. Regras de uso do glossário

## 2.1 Consistência

Termos definidos neste documento devem ser utilizados de forma consistente quando tiverem o mesmo significado conceitual.

Não utilizar duas palavras diferentes para representar silenciosamente o mesmo conceito quando essa diferença puder causar ambiguidade.

## 2.2 Precisão acima de simplificação

Quando um termo possuir significado jurídico, institucional ou editorial sensível, a interface poderá utilizar linguagem mais acessível, mas não deve alterar materialmente o sentido do conceito.

## 2.3 Termos especializados futuros

Este glossário contém apenas o vocabulário necessário para a Fundação e conceitos já estabelecidos pelos documentos canônicos atuais.

Termos de domínio ainda não completamente modelados poderão ser refinados posteriormente por:

- FF-0011 — CLAIMS_AND_EVIDENCE;
- FF-0013 — DOMAIN_MODEL;
- FF-0014 — TEMPORAL_MODEL;
- FF-0015 — EVENT_TAXONOMY;
- demais documentos CANONICAL específicos.

A existência de uma definição preliminar neste glossário não deve ser interpretada como decisão antecipada de implementação ou schema de dados.

## 2.4 Incerteza terminológica

Quando não houver termo suficientemente preciso para representar uma situação, o projeto deve preferir linguagem descritiva a utilizar uma classificação inadequada.

## 2.5 Especialização não autoriza conflito silencioso

Um documento especializado pode tornar uma definição mais precisa dentro de seu escopo.

Se essa especialização alterar materialmente o significado compartilhado de um termo deste glossário, o FF-0004 deve ser reavaliado e, quando necessário, versionado. Uma definição especializada não pode ser utilizada para contradizer silenciosamente o FF-0001 ou tornar incompatíveis documentos canônicos relacionados.

---

# 3. Projeto e identidade

## Fiel Fiscaliza

Projeto independente, comunitário e sem fins lucrativos dedicado a ajudar corinthianos a compreender, acompanhar, preservar e fiscalizar a vida institucional do Sport Club Corinthians Paulista por meio de informação pública, verificável, contextualizada e historicamente preservada.

Não representa oficialmente o SCCP, a Gaviões da Fiel ou qualquer grupo político do clube.

## André

Criador e mantenedor original do Fiel Fiscaliza e autoridade final do projeto enquanto vigorar o modelo de governança individual definido no FF-0001.

## SCCP

Abreviação de **Sport Club Corinthians Paulista**.

Quando o termo “Corinthians” for utilizado em contexto institucional neste projeto, normalmente refere-se ao SCCP como instituição, e não exclusivamente à equipe profissional de futebol.

## Gaviões da Fiel

Entidade independente do SCCP e do Fiel Fiscaliza.

O fato de André ser associado da Gaviões da Fiel não concede ao projeto autorização para falar em nome da entidade.

## Independência editorial

Capacidade do Fiel Fiscaliza de registrar, organizar, corrigir e apresentar informação sem subordinação automática a dirigentes, grupos políticos, movimentos, patrocinadores, torcidas organizadas, financiadores ou outras partes interessadas.

Independência editorial não significa ausência de princípios. O projeto pode defender transparência, memória, prestação de contas e governança sem funcionar como instrumento eleitoral de um grupo.

## Não oficial

Qualificação que indica ausência de representação ou chancela institucional formal.

O Fiel Fiscaliza é um projeto não oficial em relação ao SCCP e à Gaviões da Fiel.

---

# 4. Governança documental

## Documento formal

Documento identificado, versionado e reconhecido dentro da estrutura documental oficial do Fiel Fiscaliza.

Todo documento formal deve possuir, no mínimo:

- ID;
- nome;
- versão;
- status;
- data da última revisão.

O local físico em que uma cópia esteja armazenada não determina sozinho sua autoridade.

## DRAFT

Estado documental de conteúdo ainda em discussão ou revisão.

Um documento DRAFT não constitui fonte canônica de verdade e pode mudar antes de aprovação.

## CANONICAL

Estado documental de conteúdo explicitamente aprovado e obrigatório dentro de seu escopo.

Um documento CANONICAL integra a fonte oficial de verdade do projeto conforme a hierarquia estabelecida pelo FF-0001.

## DEPRECATED

Estado documental de conteúdo anteriormente válido, mas posteriormente substituído.

Um documento DEPRECATED permanece preservado para memória histórica e não deve ser tratado como regra vigente.

## Fonte de verdade

Conjunto de documentos e decisões formalmente autorizados que determinam o estado vigente das regras do Fiel Fiscaliza.

Sua autoridade decorre da hierarquia documental definida pelo FF-0001, e não apenas do local em que uma cópia do conteúdo está armazenada.

## Hierarquia documental

Ordem usada para resolver autoridade entre fontes internas do projeto:

1. FF-0001 — PROJECT_CONSTITUTION;
2. documentos CANONICAL específicos da área;
3. ADRs aprovados;
4. FF-0003 — DECISION_LOG;
5. documentos DRAFT;
6. discussões e decisões ainda não formalizadas em chats.

## Decision Log

Registro resumido e histórico das decisões relevantes do Fiel Fiscaliza.

O FF-0003 não substitui documentos especializados nem ADRs. Ele preserva o que foi decidido, por quê e onde a decisão passou a ser formalizada.

## Decisão APROVADA

Entrada do Decision Log explicitamente aceita por André e vigente no nível de autoridade indicado.

## Decisão SUBSTITUÍDA

Decisão anteriormente aprovada que foi substituída por outra decisão posterior.

A entrada original permanece preservada.

## Decisão REVOGADA

Decisão que deixou de vigorar sem possuir substituição direta.

## Decisão PENDENTE

Questão registrada no Decision Log, mas ainda não decidida.

Uma decisão PENDENTE não constitui regra do projeto.

## ADR

**Architecture Decision Record.**

Documento utilizado para registrar uma decisão arquitetural relevante, incluindo normalmente:

- contexto;
- decisão;
- alternativas consideradas;
- consequências;
- status.

ADRs são preferíveis ao Decision Log quando uma decisão arquitetural exige justificativa e análise próprias.

## Impacto documental

Efeito material que uma decisão ou alteração em um documento pode produzir sobre outros documentos canônicos.

Quando relevante, esse impacto deve ser rastreável por referência, seção específica, índice ou mecanismo equivalente.

## Conflito canônico

Situação em que uma proposta, decisão, implementação ou documento contradiz regra vigente de autoridade igual ou superior.

Conflitos canônicos não podem ser resolvidos silenciosamente. Devem ser identificados, avaliados e aprovados formalmente conforme o FF-0001.

---

# 5. Processo de desenvolvimento

## Pré-Codex

Período de definição e especificação do projeto anterior à liberação regular do Codex para implementar código de produção do MVP.

O estado pré-Codex não impede pesquisa, documentação, decisões de produto, desenho arquitetural ou pequenas alterações manuais no repositório.

## Codex

Agente de implementação utilizado seletivamente para tarefas em que sua capacidade de navegar, modificar e testar o repositório de forma autônoma gere benefício relevante.

A utilização do Codex é regulada principalmente pelo FF-0002.

## CODEX READY

Estado formal que indica que os gates necessários do FF-0002 foram satisfeitos e que o Codex está liberado para implementação regular do MVP dentro das premissas aprovadas naquele momento.

CODEX READY não é autorização permanente e irrestrita.

## REVIEW REQUIRED

Estado aplicado às partes afetadas de um CODEX READY quando uma premissa material deixa de ser confiável ou vigente.

Exemplos incluem mudança relevante em:

- documento CANONICAL;
- arquitetura bloqueante;
- free tier;
- fonte crítica;
- risco crítico.

A revisão deve ser proporcional ao impacto e não precisa bloquear tarefas comprovadamente não relacionadas.

## Gate

Conjunto explícito de condições que precisa ser satisfeito antes de uma fase ser considerada concluída ou antes de uma autorização posterior ser concedida.

## MVP

**Minimum Viable Product.**

Menor versão publicável do Fiel Fiscaliza capaz de entregar utilidade real aos usuários e atender aos critérios de aceite que serão definidos no FF-0008 — MVP_SPEC.

MVP não significa produto descuidado, editorialmente inseguro ou conceitualmente descartável.

## Definition of Ready

Conjunto futuro de critérios mínimos que uma tarefa deverá atender antes de entrar em implementação.

Será formalizado no FF-0037.

## Definition of Done

Conjunto futuro de critérios que determinará quando uma alteração pode ser considerada concluída e pronta para integração.

Será formalizado no FF-0038.

---

# 6. Princípios técnicos e operacionais

## Custo operacional zero

Requisito de que, enquanto o Fiel Fiscaliza for mantido pessoalmente por André, exista uma forma de operação com custo mensal obrigatório de **R$ 0**.

Custos opcionais não podem tornar-se silenciosamente requisitos indispensáveis.

## Static-first

Princípio arquitetural segundo o qual o projeto deve preferir conteúdo e funcionalidades que possam ser gerados e servidos estaticamente quando isso não prejudicar requisitos essenciais.

Static-first não significa proibição de backend ou comportamento dinâmico. Significa que complexidade dinâmica precisa ser justificada por necessidade concreta.

## Caminho crítico público

Conjunto de componentes e serviços indispensáveis para que um usuário consiga utilizar as funções essenciais da aplicação pública.

Uma dependência fora do caminho crítico pode falhar ou ficar indisponível sem impedir o uso essencial do Fiel Fiscaliza.

## IA paga no caminho crítico

Dependência de uma API ou serviço comercial de inteligência artificial cuja disponibilidade ou consumo pago seja necessário para o funcionamento essencial da aplicação pública.

Enquanto vigorar o requisito de custo zero, esse padrão não é permitido.

## Free tier

Faixa gratuita de um serviço externo, sujeita a limites, condições, políticas e alterações definidas pelo respectivo fornecedor.

A existência de um free tier não garante permanência, ausência de cobrança automática, portabilidade ou adequação ao Fiel Fiscaliza. Serviços críticos baseados em free tier devem ser avaliados e revalidados conforme o FF-0002.

## Fonte crítica

Fonte cuja indisponibilidade, perda de acesso ou mudança material comprometa requisito relevante do MVP, um coletor indispensável ou uma premissa operacional aprovada.

A classificação de uma fonte como crítica será definida nas fases de arquitetura e operação e pode mudar ao longo do tempo.

## Portabilidade

Capacidade de mover dados, lógica e operação do projeto entre ferramentas ou provedores sem reconstrução desproporcional e sem perda do patrimônio informacional.

## Lock-in

Dependência excessiva de tecnologia, formato ou provedor que torne migração tecnicamente difícil, operacionalmente inviável ou financeiramente onerosa.

## Complexidade sob demanda

Princípio segundo o qual novos componentes, serviços e abstrações devem ser introduzidos quando um problema real os justificar, e não apenas por sofisticação técnica antecipada.

## Manutenção por exceção

Modelo operacional em que o sistema executa automaticamente o trabalho repetitivo e solicita intervenção humana principalmente quando algo exige julgamento, correção ou ação especial.

Fluxo de referência atual:

**coleta automática → detecção → normalização → fila de revisão → validação humana → publicação.**

## Observabilidade

Capacidade de perceber e diagnosticar o estado dos processos automatizados do projeto, incluindo falhas, atrasos, coletores interrompidos e fontes indisponíveis.

---

# 7. Informação, evidência e proveniência

## Informação factual

Afirmação sobre algo que pode, em princípio, ser sustentado ou contestado por evidência verificável.

Informação factual não deve ser confundida com opinião ou interpretação.

## Informação publicamente acessível

Informação que pode ser acessada legitimamente por integrantes do público a partir de fonte disponível sem obtenção ilícita ou burla de controle de acesso.

Ser publicamente acessível não significa, por si só, que o conteúdo deva ser armazenado, republicado integralmente ou exposto pelo Fiel Fiscaliza. Privacidade, relevância institucional, propriedade intelectual, termos aplicáveis e riscos de exposição continuam devendo ser avaliados quando pertinentes.

## Fato confirmado

Informação factual sustentada por evidência suficiente para o nível de certeza afirmado pelo Fiel Fiscaliza.

O fato confirmado deve ser formulado com precisão proporcional à evidência disponível.

Exemplo conceitual: se um órgão publica formalmente a abertura de uma investigação, pode estar confirmado que **a investigação foi aberta**. Isso não confirma automaticamente a acusação investigada.

## Alegação

Afirmação de que determinado fato, conduta ou situação ocorreu, cuja veracidade material ainda não foi estabelecida com segurança suficiente pelo projeto.

Uma alegação pode possuir fonte identificável e ainda assim continuar sendo uma alegação.

## Denúncia

Comunicação ou imputação de possível irregularidade feita por pessoa, instituição ou procedimento identificável.

O termo deve ser qualificado quando necessário para evitar ambiguidade entre uma denúncia em sentido genérico e uma peça ou ato formal com significado jurídico específico.

Quando o tipo jurídico do ato for conhecido e materialmente relevante — por exemplo, denúncia criminal, representação, notícia de fato ou outra categoria formal — o projeto deve preferir a denominação precisa em vez de reduzir todos esses atos ao termo genérico “denúncia”.

A existência de uma denúncia não confirma sua procedência.

## Investigação

Procedimento ou atividade destinada a apurar fatos, responsabilidades ou possíveis irregularidades.

Quando se tratar de procedimento formal, o projeto deve identificar, quando relevante, o órgão responsável e a natureza do procedimento. Apuração jornalística ou pesquisa própria não deve ser apresentada como investigação oficial.

A existência de investigação comprova que algo está sendo apurado, não que a hipótese investigada é verdadeira.

## Processo em andamento

Procedimento formal ainda não concluído de maneira definitiva dentro do âmbito relevante.

O projeto deve registrar seu estado e evolução sem antecipar resultado e, quando necessário, qualificar sua natureza — judicial, administrativa, disciplinar ou outra.

## Decisão administrativa

Decisão emitida por órgão ou autoridade administrativa dentro de sua competência.

Seu alcance, possibilidade de revisão e definitividade dependem do contexto específico e devem ser informados quando materialmente relevantes.

## Decisão judicial não definitiva

Decisão judicial ainda sujeita a recurso, revisão ou outra forma relevante de modificação dentro do processo correspondente.

Não deve ser apresentada como desfecho judicial definitivo.

## Decisão definitiva

Decisão cujo estado, dentro do procedimento e do alcance especificamente considerados, permite tratá-la como encerramento definitivo da questão analisada.

O termo não deve ser usado de forma genérica quando houver condição processual mais precisa disponível. Em contexto judicial, quando a definitividade depender de trânsito em julgado ou de outra condição processual específica, essa condição deve ser verificada e descrita adequadamente antes de o projeto afirmar que a questão está definitivamente encerrada.

Quando houver dúvida, o projeto deve preferir a descrição objetiva do estado processual conhecido.

## Declaração pública

Manifestação atribuível a uma pessoa ou instituição e tornada publicamente acessível por meio verificável.

Uma declaração comprova que determinada posição foi expressa; não comprova automaticamente a verdade material de todos os fatos afirmados nela.

## Opinião

Juízo subjetivo, avaliação ou posicionamento que não deve ser apresentado como fato verificável apenas por ter sido publicado por pessoa ou instituição relevante.

## Interpretação

Conclusão analítica derivada de fatos, documentos ou contexto.

Uma interpretação deve ser distinguida dos fatos que a sustentam.

## Rumor

Informação circulante cuja origem, evidência ou confirmação são insuficientes para tratamento factual seguro.

Rumor não deve ser promovido a fato por repetição ou popularidade.

## Informação contestada

Informação ou alegação relevante cuja veracidade, interpretação ou alcance é publicamente contestado por fonte materialmente relacionada ao caso.

O sistema deve ser capaz de representar a contestação sem escolher automaticamente uma versão por preferência editorial.

## Informação não confirmada

Informação para a qual não existe evidência suficiente para o nível de certeza necessário à publicação factual pretendida.

## Desconhecido

Estado usado quando o Fiel Fiscaliza não possui informação suficiente para determinar uma resposta com segurança.

“Desconhecido” é um resultado válido e preferível a preencher lacunas com inferência.

## Claim

Termo técnico provisório para uma afirmação factual ou factualizável cuja relação com evidência, contestação, status e temporalidade precisa ser representada pelo sistema.

O modelo formal de Claim será definido no FF-0011 — CLAIMS_AND_EVIDENCE e poderá refinar esta definição.

## Evidência

Material verificável utilizado para sustentar, limitar, contestar ou contextualizar uma afirmação.

Evidência não é sinônimo automático de prova conclusiva. Sua força depende da afirmação, da fonte, do contexto e das demais evidências disponíveis.

Exemplos podem incluir documentos, registros oficiais, declarações verificáveis ou outras fontes adequadas conforme a política editorial futura.

## Fonte

Origem identificável a partir da qual o projeto obtém informação ou evidência.

Uma fonte pode possuir diferentes níveis de autoridade e adequação dependendo da afirmação que está sendo sustentada.

## Fonte primária

Fonte diretamente ligada ao ato, documento, decisão, declaração ou evidência específica que está sendo registrada.

A classificação como primária é relativa à afirmação que a fonte pretende sustentar. Uma mesma publicação pode ser fonte primária para provar que determinada declaração foi feita e não ser fonte suficiente para comprovar materialmente todos os fatos alegados nessa declaração.

Exemplos possíveis incluem documentos oficiais, decisões, atas, estatutos e comunicados emitidos pela instituição responsável.

Fonte primária não significa verdade material absoluta de todas as alegações que o documento eventualmente contenha.

## Fonte secundária

Fonte que relata, contextualiza, analisa ou reproduz informação originada em outro lugar.

A classificação também depende da afirmação considerada. Veículos jornalísticos e publicações especializadas frequentemente atuam como fontes secundárias, embora possam ser fonte primária para suas próprias entrevistas, documentos obtidos, apurações originais ou declarações publicadas diretamente por eles.

## Fonte oficial

Fonte publicada ou emitida por uma instituição, órgão, autoridade ou representante autorizado em nome da entidade correspondente.

“Oficial” descreve a autoria ou chancela institucional da fonte; não significa neutralidade, independência editorial nem verdade material automática sobre fatos controvertidos.

Uma fonte oficial pode ser fonte primária para determinado ato ou declaração e não ser suficiente, isoladamente, para comprovar outra afirmação material.

## Documento oficial

Documento emitido, aprovado, assinado ou publicado por instituição ou autoridade competente dentro do contexto correspondente.

Seu caráter oficial comprova sua origem institucional quando autenticidade e contexto forem adequadamente estabelecidos; não torna automaticamente verdadeiras todas as alegações ou interpretações nele contidas.

## Proveniência

Conjunto de informações que permite rastrear a origem e o contexto de um dado.

Quando aplicável, deve responder a perguntas como:

- de onde veio;
- quem publicou;
- quando foi publicado;
- quando foi coletado;
- qual documento ou URL o sustenta;
- qual versão foi utilizada;
- qual era o estado da informação naquele momento.

A proveniência faz parte estrutural do dado.

## Contraditório factual

Representação de versões, contestações ou respostas materialmente relevantes a uma afirmação ou acontecimento.

Não significa equivalência automática entre todas as versões, nem constitui por si só um conceito de contraditório processual jurídico. Seu objetivo editorial é preservar de forma verificável respostas e divergências relevantes sem fabricar simetria artificial entre evidências de força diferente.

## Correção

Alteração destinada a reparar informação incorreta ou inadequadamente apresentada pelo próprio Fiel Fiscaliza.

Correções materialmente relevantes devem preservar rastreabilidade conforme a política futura do FF-0012 — CORRECTIONS_POLICY.

---

# 8. Temporalidade e memória

## Estado atual

Representação mais recente considerada válida para determinado aspecto do domínio.

O estado atual não apaga estados históricos anteriores.

## Estado histórico

Representação de uma situação que foi válida ou registrada em momento anterior e permanece preservada para reconstrução temporal.

## Data de ocorrência

Data em que um acontecimento ocorreu, quando conhecida e aplicável.

## Data de publicação

Data em que uma fonte, documento, declaração ou informação foi tornada pública pela origem correspondente.

## Data de coleta

Data em que o Fiel Fiscaliza capturou ou registrou determinada informação a partir de uma fonte.

## Data de revisão

Data em que determinado conteúdo, dado ou decisão foi revisado editorialmente ou documentalmente pelo projeto.

## Vigência

Período em que uma regra, documento, mandato, estado ou decisão é considerado válido dentro do contexto correspondente.

## Histórico

Conjunto preservado das mudanças e estados anteriores de uma informação ou entidade ao longo do tempo.

## Snapshot

Registro de um estado observado de uma fonte ou conteúdo em determinado momento, utilizado para comparação, detecção de mudanças ou preservação de contexto.

A estratégia técnica de snapshots será definida posteriormente.

## Versão

Identificação de uma determinada revisão de documento, conteúdo ou artefato.

Uma nova versão não deve apagar silenciosamente versões anteriores quando sua preservação for relevante à memória ou auditoria.

---

# 9. Conceitos institucionais e de domínio — definições preliminares

As definições desta seção são conceituais e poderão ser refinadas pelo FF-0013, FF-0014 e FF-0015. Elas **não determinam ainda classes, tabelas, schemas ou formatos de persistência**.

## Pessoa

Indivíduo cuja atuação ou relação institucional é relevante ao escopo do Fiel Fiscaliza.

A presença de uma pessoa no sistema deve se limitar à informação pública e institucionalmente relevante.

## Organização

Entidade coletiva relevante ao contexto institucional analisado, como clube, empresa, órgão público, associação, movimento ou outra estrutura identificável.

## Órgão institucional

Estrutura formal pertencente ou relacionada a uma organização e dotada de função, competência ou composição próprias.

## Cargo

Função institucional identificável ocupada por uma pessoa dentro de determinada estrutura.

Cargo não é sinônimo de pessoa. Diferentes pessoas podem ocupar o mesmo cargo em períodos diferentes.

## Mandato

Período ou vínculo durante o qual uma pessoa exerce determinada função institucional, quando o conceito de mandato for aplicável.

O modelo temporal formal será definido posteriormente.

## Evento institucional

Acontecimento relevante para governança, administração, política, finanças, transparência, estrutura ou memória institucional do SCCP.

Sua taxonomia será definida pelo FF-0015 — EVENT_TAXONOMY.

## Documento

Artefato identificável que registra informação relevante, como estatuto, ata, balanço, decisão, comunicado, contrato publicamente acessível ou outro material dentro do escopo editorial.

A existência pública de um documento não significa automaticamente que sua redistribuição integral seja permitida.

## Relação institucional

Vínculo verificável entre pessoas, organizações, órgãos, cargos, eventos ou outras entidades no contexto institucional.

Relações não devem ser inferidas apenas por percepção de proximidade política.

## Votação

Processo formal de deliberação em que votos ou posições são registrados segundo regras da instituição correspondente.

Quando votos individuais não forem públicos, o Fiel Fiscaliza não deve inferi-los.

---

# 10. Coleta e manutenção — definições preliminares

## Fonte monitorada

Fonte pública incluída no processo operacional do Fiel Fiscaliza para verificação periódica ou automatizada de mudanças relevantes.

## Coletor

Componente ou processo responsável por acessar uma fonte permitida e capturar informação ou mudanças de forma automatizada ou semiautomatizada.

Um coletor não deve depender de burlar autenticação, controles de acesso ou restrições técnicas.

## Coleta

Ato de obter informação de uma fonte para processamento pelo Fiel Fiscaliza.

Coletar não equivale a publicar.

## Detecção

Etapa em que o sistema identifica que algo novo, removido ou alterado pode exigir processamento ou revisão.

## Normalização

Transformação de informação coletada para uma representação consistente que facilite validação, comparação e uso pelo sistema.

## Deduplicação

Processo de identificar registros ou descobertas que representam essencialmente o mesmo conteúdo ou acontecimento, evitando multiplicação artificial de itens.

## Fila de revisão

Conjunto de itens detectados ou processados que aguardam julgamento humano antes de determinada ação editorial ou publicação.

## Validação humana

Revisão realizada por pessoa autorizada para decidir significado, adequação editorial, classificação ou publicação de informação quando a automação não deve tomar essa decisão sozinha.

## Publicação

Ato de tornar determinado conteúdo ou dado acessível na aplicação pública do Fiel Fiscaliza.

Publicação é uma etapa distinta de coleta, processamento e armazenamento interno.

## Source Registry

Registro futuro das fontes utilizadas ou monitoradas pelo Fiel Fiscaliza, incluindo atributos editoriais e operacionais relevantes.

Será formalizado no FF-0031 — SOURCE_REGISTRY.

---

# 11. Termos que não devem ser usados como sinônimos

Para reduzir ambiguidade, as seguintes distinções devem ser preservadas:

- **investigação** não é **culpa comprovada**;
- **investigação oficial** não é **apuração jornalística ou pesquisa própria**;
- **denúncia** não é **fato confirmado**;
- **alegação** não é **fato confirmado**;
- **evidência** não é automaticamente **prova conclusiva**;
- **fonte primária** não é **verdade absoluta**;
- **fonte oficial** não é **fonte neutra nem verdade material automática**;
- **fonte oficial** não é necessariamente **fonte primária para toda afirmação**;
- **declaração pública** não é **comprovação material de tudo que foi declarado**;
- **decisão judicial** não é automaticamente **decisão judicial definitiva**;
- **decisão judicial definitiva** não deve ser presumida sem verificar o estado processual aplicável;
- **estado atual** não substitui **histórico**;
- **coleta** não é **publicação**;
- **informação publicamente acessível** não é necessariamente **conteúdo apropriado para republicação ou armazenamento integral**;
- **documento público** não é necessariamente **conteúdo livremente redistribuível**;
- **repositório público** não é automaticamente **projeto com licença aberta**;
- **associado da Gaviões da Fiel** não significa **representante oficial da Gaviões da Fiel**;
- **DRAFT** não é **CANONICAL**;
- **Decision Log** não é **ADR**;
- **CODEX READY** não significa **autorização permanente para qualquer implementação**;
- **static-first** não significa **proibição de backend**;
- **free tier** não significa **serviço gratuito garantido para sempre**;
- **sem fins lucrativos** não significa necessariamente **proibição de qualquer apoio financeiro futuro**.

---

# 12. Termos deliberadamente ainda não definidos

Os seguintes temas não devem receber definição técnica definitiva neste momento:

- schema de entidades;
- IDs de domínio;
- arquitetura de frontend;
- banco de dados;
- persistência;
- API pública;
- backend em runtime;
- mecanismo definitivo de busca;
- classificação final de fontes;
- estados finais de Claim;
- taxonomia final de eventos;
- modelo temporal técnico;
- stack de implementação;
- provedores de infraestrutura.

Essas decisões pertencem às fases posteriores definidas pelo FF-0002.

---

# 13. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0003 — DECISION_LOG;
- futuros documentos CANONICAL que especializem conceitos aqui definidos.

## Impacta

Este glossário será referência terminológica para todos os documentos posteriores, especialmente:

- FF-0005 a FF-0008 — Produto;
- FF-0009 a FF-0012 — Editorial;
- FF-0013 a FF-0015 — Domínio;
- FF-0016 a FF-0021 — Arquitetura;
- FF-0022 a FF-0026 — Experiência e linguagem;
- FF-0039 — AGENTS.

Quando um documento especializado alterar materialmente o significado de termo definido aqui, o impacto sobre o FF-0004 deve ser revisado.

---

# 14. Manutenção do glossário

Novos termos devem ser adicionados quando:

- forem relevantes para múltiplos documentos;
- possuírem risco de ambiguidade;
- tiverem significado específico dentro do Fiel Fiscaliza;
- forem necessários para orientar agentes ou colaboradores.

Não é necessário adicionar todo termo técnico utilizado pelo projeto.

Alterações que mudem materialmente o significado de um termo CANONICAL devem:

1. avaliar impacto em documentos relacionados;
2. atualizar referências quando necessário;
3. gerar nova versão do FF-0004;
4. registrar decisão no FF-0003 quando materialmente relevante.

---

# 15. Vigência

Esta versão possui status **CANONICAL** e entra em vigor em **2026-09-04** por aprovação explícita de André.

**FF-0004 — GLOSSARY v1.0 // CANONICAL**

A partir desta promoção, o FF-0004 constitui a referência terminológica oficial do Fiel Fiscaliza, subordinada ao FF-0001 e às definições especializadas de documentos CANONICAL dentro de seus respectivos escopos.