# FF-0007 — SCOPE

**Nome do documento:** Scope  
**ID:** FF-0007  
**Versão:** 0.1  
**Status:** DRAFT  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define as fronteiras de produto do Fiel Fiscaliza.

Seu objetivo é responder, sem escolher ainda arquitetura, interface ou funcionalidades específicas:

- quais tipos de assunto pertencem ao produto;
- quais tipos de assunto normalmente não pertencem;
- quando um tema esportivo passa a possuir relevância institucional;
- quais limites separam memória institucional, fiscalização, jornalismo cotidiano, militância política e exposição pessoal;
- como tratar assuntos parcialmente públicos, incompletos ou difíceis de documentar;
- como distinguir escopo permanente do produto de cobertura atual e de escopo do MVP.

O FF-0007 não define quais páginas existirão, quais módulos serão implementados, quais fontes serão automatizadas nem quais capacidades entrarão no MVP.

Essas decisões pertencem principalmente ao **FF-0008 — MVP_SPEC** e às fases posteriores.

---

# 2. Autoridade e dependências

Este documento é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION;
- FF-0006 — USERS_AND_USE_CASES.

Em particular, o escopo deve respeitar que:

- o projeto é institucional, não um portal esportivo geral;
- proveniência e temporalidade são parte central do valor;
- o usuário primário da Fase 1 é o torcedor institucionalmente engajado;
- os JTBD centrais envolvem verificação de afirmações e fontes, reconstrução temporal, contextualização financeira e reconstrução de decisões institucionais públicas;
- assuntos de alto risco editorial não devem ser ampliados apenas porque geram atenção;
- informação desconhecida ou não disponível publicamente pode permanecer explicitamente desconhecida.

---

# 3. Princípio central de escopo

O Fiel Fiscaliza deve cobrir **a vida institucional do Sport Club Corinthians Paulista e relações externas que produzam efeito institucional materialmente relevante sobre o clube**.

O critério não é simplesmente se um assunto “fala do Corinthians”.

Um assunto pertence ao produto quando sua compreensão ajuda materialmente a reconstruir, verificar, preservar ou fiscalizar pelo menos uma das seguintes dimensões:

1. governança e exercício de poder institucional;
2. regras, órgãos, cargos, mandatos e processos decisórios;
3. patrimônio, finanças, obrigações, receitas, dívidas e compromissos relevantes;
4. atos jurídicos, regulatórios ou investigativos com consequência institucional;
5. documentos, decisões, votações e posições públicas institucionalmente relevantes;
6. mudanças estruturais ou históricas do clube;
7. participação associativa e mecanismos formais de representação;
8. relações institucionais verificáveis com organizações ou pessoas externas quando necessárias para compreender o SCCP.

A presença em uma dessas dimensões torna o tema **elegível** ao produto, não automaticamente prioritário para cobertura atual ou MVP.

---

# 4. Três camadas que não devem ser confundidas

## 4.1 Escopo do produto

Define aquilo que o Fiel Fiscaliza pode legitimamente cobrir ao longo de sua vida.

## 4.2 Cobertura atual

Define aquilo que o projeto consegue efetivamente manter com qualidade em determinado momento.

A ausência de cobertura de um tema em escopo não significa que ele deixou de pertencer ao produto.

## 4.3 Escopo do MVP

Define o menor subconjunto de problemas e capacidades que será implementado na primeira versão publicável.

O fato de um tema estar no escopo do produto **não obriga sua presença no MVP**.

O FF-0008 deverá escolher esse subconjunto explicitamente.

Essa separação impede que “está no escopo” se transforme em compromisso de cobrir tudo desde o início.

---

# 5. Domínios institucionais em escopo

Os domínios abaixo pertencem ao universo legítimo do Fiel Fiscaliza, sujeitos a relevância, disponibilidade de evidência e capacidade de manutenção.

## 5.1 Governança e estrutura institucional

Inclui, quando publicamente documentável:

- Presidência;
- vice-presidências;
- diretorias;
- Conselho Deliberativo;
- Conselho de Orientação;
- Conselho Fiscal;
- comissões e demais órgãos estatutários;
- competências formais dos órgãos;
- criação, extinção ou reorganização de cargos e estruturas;
- mandatos, substituições, afastamentos e vacâncias;
- processos formais de decisão.

---

## 5.2 Estatuto, regimentos e regras institucionais

Inclui:

- Estatuto Social;
- reformas estatutárias;
- regimentos;
- regras eleitorais;
- regras de funcionamento dos órgãos;
- direitos e deveres associativos institucionalmente relevantes;
- alterações formais que mudem governança ou participação.

O produto deve preservar versões e vigências quando essas diferenças forem relevantes para compreender o histórico.

---

## 5.3 Eleições, chapas e participação associativa

Inclui:

- eleições internas;
- candidaturas e chapas formalmente registradas;
- regras de elegibilidade;
- resultados;
- impugnações e procedimentos formais;
- assembleias e consultas associativas relevantes;
- propostas ou compromissos públicos quando documentalmente atribuíveis;
- alterações nos mecanismos de participação e representação.

A cobertura não autoriza inferir alinhamento político, apoio, voto ou pertencimento informal sem evidência pública adequada.

---

## 5.4 Decisões, votações e atuação institucional

Inclui:

- pautas formalmente deliberadas;
- decisões de órgãos;
- resultados de votações;
- votos individuais somente quando forem publicamente conhecidos de forma adequada;
- posições públicas diretamente relacionadas a questão institucional;
- histórico de atuação em cargos e órgãos quando verificável.

Resultado coletivo não deve ser transformado em voto individual presumido.

---

## 5.5 Finanças e patrimônio

Inclui, quando institucionalmente relevante:

- demonstrações financeiras;
- balanços e balancetes;
- endividamento;
- receitas e despesas;
- fluxo e evolução de indicadores financeiros relevantes;
- ativos e passivos;
- patrimônio;
- obrigações financeiras relevantes;
- operações que alterem materialmente a posição financeira ou patrimonial do clube.

Valores devem ser compreendidos com data-base, conceito, método e fonte quando essas distinções forem necessárias para evitar comparação enganosa.

O FF-0007 não estabelece limiar numérico universal de materialidade financeira. Critérios operacionais poderão ser definidos posteriormente se necessários.

---

## 5.6 Arena e estruturas relacionadas

A Neo Química Arena e relações jurídicas, financeiras e administrativas diretamente associadas a ela pertencem ao escopo quando forem relevantes para compreender:

- dívida;
- financiamento;
- propriedade e direitos;
- fundos ou estruturas financeiras relacionadas;
- contratos relevantes;
- receitas e obrigações;
- decisões judiciais ou administrativas;
- alterações na governança ou exploração econômica do ativo.

O projeto não precisa cobrir operação cotidiana do estádio sem consequência institucional relevante.

---

## 5.7 Contratos, parcerias e operações institucionalmente relevantes

Contratos e relações comerciais podem entrar no produto quando sua importância ultrapassar a rotina esportiva ou administrativa e houver consequência institucional relevante.

Exemplos de fatores de relevância:

- impacto financeiro material;
- duração ou obrigação de longo prazo;
- efeito relevante sobre patrimônio ou direitos do clube;
- controvérsia jurídica ou regulatória relevante;
- participação em investigação ou processo;
- mudança estrutural na forma de exploração de ativo, marca ou atividade;
- necessidade de compreender decisão de governança relevante.

O produto **não assume que todo contrato do clube deve ser catalogado**.

---

## 5.8 Investigações, processos e decisões jurídicas ou regulatórias

Inclui procedimentos que tenham conexão institucional relevante com o SCCP, sua governança, patrimônio, administração ou atos praticados em capacidade institucional.

Podem incluir, quando adequadamente públicos:

- investigações;
- inquéritos;
- ações judiciais;
- decisões judiciais;
- procedimentos administrativos;
- atuações de Ministério Público ou órgãos reguladores;
- sanções ou determinações de entidades competentes.

A inclusão de um procedimento documenta sua existência e evolução.

**Não transforma a acusação investigada em fato nem presume culpa.**

Assuntos estritamente pessoais de indivíduos ligados ao clube permanecem fora do escopo quando não houver relação institucional materialmente relevante.

---

## 5.9 Transparência e documentos institucionais

Inclui:

- documentos oficiais do SCCP;
- atas;
- estatutos e regimentos;
- demonstrações financeiras;
- comunicados;
- documentos eleitorais;
- decisões públicas;
- documentos de órgãos públicos relacionados ao clube;
- versões e alterações de documentos relevantes;
- disponibilidade, indisponibilidade ou substituição de documentos quando isso for importante para a memória institucional.

O Fiel Fiscaliza pode registrar metadados, contexto, origem, versão e relação entre documentos.

Isso **não implica obrigação de republicar integralmente todo documento acessível na internet**.

---

## 5.10 Pessoas em capacidade institucional

Pessoas podem ser documentadas na medida necessária para compreender sua atuação pública no ecossistema institucional do Corinthians.

Podem entrar:

- cargos e mandatos;
- candidaturas e participação formal em chapa;
- nomeações;
- votos nominais publicados;
- decisões formalmente tomadas;
- declarações públicas institucionalmente relevantes;
- vínculos administrativos ou institucionais verificáveis.

Não entram por padrão:

- vida familiar;
- endereço residencial;
- telefone privado;
- hábitos pessoais;
- relações pessoais sem relevância institucional comprovada;
- opinião sobre caráter;
- especulação sobre intenção;
- suposta aliança baseada apenas em proximidade percebida.

O objetivo de um eventual perfil é reconstruir atuação institucional, não produzir dossiê pessoal.

---

# 6. Entidades externas ao SCCP

Organizações e pessoas externas podem aparecer quando forem necessárias para compreender uma questão institucional do Corinthians.

Exemplos possíveis:

- Poder Judiciário;
- Ministério Público;
- órgãos públicos;
- entidades esportivas;
- instituições financeiras;
- patrocinadores e parceiros;
- empresas relacionadas a operações relevantes;
- movimentos, coletivos ou torcidas organizadas;
- outras associações ou pessoas que pratiquem atos públicos com consequência institucional relevante para o SCCP.

A inclusão deve se limitar à relação pertinente com o Corinthians.

O Fiel Fiscaliza não deve ampliar silenciosamente seu escopo para fiscalizar integralmente organizações externas.

---

# 7. Torcidas organizadas, movimentos e coletivos

A atuação de torcidas organizadas, movimentos, coletivos e grupos de associados pode entrar no produto quando houver conexão direta com:

- governança do SCCP;
- eleição ou reforma estatutária;
- mobilização sobre decisão institucional;
- proposição formal;
- posicionamento público relevante para questão institucional;
- participação documentada em processo ou acontecimento institucional.

A vida interna desses grupos, suas disputas próprias, carnaval, atividades sociais ou outros assuntos sem consequência institucional para o SCCP não pertencem automaticamente ao escopo.

O Fiel Fiscaliza deve registrar posições desses grupos como **posições atribuídas a seus emissores**, não como verdade automática sobre terceiros.

---

# 8. Critério para temas esportivos adquirirem relevância institucional

Um tema de futebol que normalmente estaria fora de escopo pode entrar quando deixar de ser apenas esportivo e passar a produzir consequência institucional documentável.

Para isso, deve existir pelo menos uma conexão material com:

1. **governança:** decisão, crise ou alteração relevante de estrutura ou poder;
2. **finanças ou patrimônio:** obrigação, receita, dívida, ativo ou impacto materialmente relevante;
3. **jurídico/regulatório:** processo, investigação, sanção, disputa ou obrigação formal relevante;
4. **administração:** mudança estrutural ou decisão administrativa relevante;
5. **transparência/integridade institucional:** necessidade de documentar ato, contrato ou procedimento cuja relevância ultrapasse a cobertura esportiva cotidiana.

Além dessa conexão, a inclusão deve contribuir para pelo menos um JTBD relevante do FF-0006 e possuir base pública suficientemente adequada para tratamento responsável.

---

# 9. Exemplos de fronteira esportivo × institucional

Os exemplos abaixo são orientativos e não substituem análise do caso concreto.

| Tema | Regra de escopo |
|---|---|
| escalação de uma partida | fora de escopo |
| desempenho individual de jogador | fora de escopo |
| análise tática | fora de escopo |
| resultado de jogo | fora de escopo, salvo quando necessário como contexto mínimo de consequência institucional |
| rumor comum de transferência | fora de escopo |
| contratação de jogador | normalmente fora; pode entrar se houver questão financeira, contratual, jurídica ou de governança materialmente relevante |
| rescisão de atleta ou treinador | normalmente fora; pode entrar quando produzir obrigação financeira, litígio ou decisão institucional relevante |
| punição esportiva | pode entrar quando houver consequência jurídica, regulatória, financeira ou institucional relevante |
| patrocínio relevante | em escopo quando possuir efeito financeiro, contratual ou de governança materialmente relevante |
| conflito entre dirigente e atleta | fora por padrão; entra apenas se evoluir para questão institucional documentável |
| venda de mando / uso de estádio | pode entrar se houver impacto patrimonial, contratual, financeiro ou decisório relevante |

O Fiel Fiscaliza deve registrar somente o contexto esportivo necessário para compreender a consequência institucional.

---

# 10. Fronteira entre memória institucional e portal de notícias

O Fiel Fiscaliza não deve competir com a imprensa pela cobertura de tudo que acontece no Corinthians.

Uma notícia pode servir como:

- fonte secundária;
- mecanismo de descoberta;
- evidência de declaração pública;
- contexto para localizar documentação primária.

Mas a unidade de publicação ou organização do produto não deve ser determinada pela existência de uma manchete nova.

O produto deve perguntar:

> **Esse acontecimento altera, esclarece ou documenta uma questão institucional que vale preservar e reconstruir?**

Se a resposta for não, o acontecimento não precisa entrar apenas porque é recente ou popular.

O objetivo é preservar **estado, mudança, decisão, evidência e contexto**, não replicar fluxo jornalístico.

---

# 11. Fronteira entre fiscalização e militância política

O Fiel Fiscaliza pode defender institucionalmente princípios compatíveis com sua Constituição, como:

- transparência;
- prestação de contas;
- memória institucional;
- verificabilidade;
- governança responsável;
- acesso público adequado à informação institucional.

Isso não autoriza o projeto a funcionar como:

- campanha de chapa;
- veículo de situação ou oposição;
- plataforma de mobilização eleitoral;
- instrumento de ataque pessoal;
- sistema de recomendação de voto;
- mecanismo de classificação automática de atores em “bons” e “maus”.

O produto pode documentar posições políticas e disputas institucionais quando forem relevantes, preservando atribuição, evidência e contexto.

---

# 12. Fronteira entre fiscalização e exposição pessoal

A relevância pública de um cargo não transforma toda a vida de seu ocupante em assunto do Fiel Fiscaliza.

Informação sobre uma pessoa deve satisfazer pelo menos uma das seguintes condições:

- descreve função ou mandato institucional;
- documenta ato público praticado em capacidade institucional;
- registra posição pública diretamente relacionada ao SCCP;
- é necessária para compreender relação institucional verificável;
- integra procedimento público relevante ao clube de forma documentalmente sustentada.

Mesmo quando uma informação é publicamente encontrável, sua publicação pelo Fiel Fiscaliza deve ser necessária e proporcional à finalidade institucional.

---

# 13. Rumores, denúncias e conteúdo não verificado

Rumor não constitui motivo suficiente para inclusão factual.

Denúncia ou acusação pode entrar quando sua existência for institucionalmente relevante e adequadamente documentada, desde que o produto deixe claro:

- quem apresentou a alegação;
- qual é seu status;
- se existe investigação ou processo;
- quais evidências públicas estão disponíveis;
- o que permanece desconhecido ou contestado.

O Fiel Fiscaliza não deve operar como caixa de denúncias anônimas irrestrita nem publicar acusação apenas por circulação em rede social.

---

# 14. Temas normalmente fora de escopo

Permanecem normalmente fora do produto:

- escalações;
- treino;
- análise tática;
- desempenho esportivo individual;
- resultados e tabelas de campeonatos;
- mercado da bola cotidiano;
- rumores de contratação;
- entretenimento esportivo;
- memes e cultura de torcida sem consequência institucional;
- cobertura de categorias de base puramente esportiva;
- história esportiva sem relação institucional relevante;
- vida privada de dirigentes, conselheiros, atletas ou terceiros;
- fofoca;
- boato político sem base documental adequada;
- política partidária nacional, estadual ou municipal sem conexão institucional material com o SCCP;
- fiscalização ampla de empresas, torcidas, federações ou órgãos externos além da relação necessária com o Corinthians;
- produção de opinião eleitoral interna em nome do projeto;
- rankings automáticos de reputação política;
- sistema aberto de acusações por usuários.

---

# 15. Informação pública insuficiente

Um assunto pode pertencer ao escopo conceitual e ainda assim não ser publicável com o nível de detalhe desejado.

Quando faltarem evidências adequadas, o produto pode registrar, conforme o caso:

- informação desconhecida;
- informação não confirmada;
- documento não localizado;
- voto individual não disponível publicamente;
- contrato não acessível publicamente;
- status não determinado com segurança.

A ausência de dados **não autoriza preencher lacunas por inferência**.

Também não cria obrigação de abandonar definitivamente o assunto quando ele pertence ao escopo institucional.

---

# 16. Escopo temporal

O Fiel Fiscaliza é um projeto de memória acumulativa e não deve possuir, como regra permanente, um corte histórico que impeça representar acontecimentos antigos relevantes.

Entretanto, cobertura retrospectiva integral não é requisito inicial.

A incorporação de histórico pode ocorrer progressivamente, priorizando:

- temas necessários para compreender questões atuais;
- acontecimentos de alta relevância institucional;
- registros que sustentem os JTBD prioritários;
- períodos cuja documentação pública permita reconstrução responsável;
- trabalho compatível com manutenção individual.

O FF-0008 poderá estabelecer um recorte temporal específico para o MVP sem alterar o escopo permanente do produto.

---

# 17. Critério de inclusão editorial-operacional

Um item estar em escopo não significa que deve ser imediatamente coletado ou publicado.

Antes de priorizar cobertura, deve-se avaliar pelo menos:

1. **relevância institucional:** ajuda a compreender poder, regra, decisão, patrimônio, finanças, obrigação, processo ou memória relevante?;
2. **utilidade:** atende a JTBD ou pergunta relevante do produto?;
3. **evidência:** existe base pública suficiente para tratamento responsável?;
4. **temporalidade:** preservar mudança ou histórico acrescenta valor?;
5. **risco editorial:** existe risco elevado de acusação, assédio, privacidade ou interpretação indevida?;
6. **sustentabilidade:** o custo recorrente de manter a cobertura é compatível com uma pessoa?;
7. **duplicação:** soluções existentes já resolvem suficientemente a tarefa sem ganho material do Fiel Fiscaliza?

Esses fatores orientam priorização; não constituem ainda uma fórmula numérica ou algoritmo automático.

---

# 18. Critérios de não inclusão mesmo quando há interesse público

O interesse ou curiosidade da torcida não é suficiente quando:

- a informação é privada e sem necessidade institucional proporcional;
- a alegação não possui base pública adequada;
- o assunto exigiria especulação para preencher lacunas;
- a cobertura facilitaria assédio ou perseguição de forma desproporcional;
- o tema é essencialmente esportivo e não possui consequência institucional relevante;
- a inclusão transformaria o produto em campanha política ou veículo de ataque;
- a cobertura exigiria operação diária incompatível com a sustentabilidade do projeto sem entregar valor institucional proporcional.

---

# 19. Relação com os JTBD do FF-0006

O escopo deve permitir principalmente que o usuário consiga:

- verificar uma afirmação e chegar à fonte;
- reconstruir a história e o estado atual de uma questão;
- entender um número financeiro no tempo;
- reconstruir uma decisão institucional pública.

Casos secundários, como acompanhamento de investigação, claims conflitantes, histórico de cargos e estado conhecido em data passada, pertencem ao universo do produto, mas podem exigir política editorial e modelo de evidência mais maduros antes de receber cobertura ampla.

A inclusão de um domínio no FF-0007 não supera dependências futuras de FF-0009 a FF-0012.

---

# 20. Decisões deliberadamente adiadas

Este documento não decide:

- qual domínio será o primeiro do MVP;
- se o MVP começará por finanças, governança, votações, documentos ou outra combinação;
- quais páginas existirão;
- se haverá perfil individual de pessoas no MVP;
- se haverá busca global;
- se haverá timeline geral;
- quais fontes serão monitoradas automaticamente;
- periodicidade de atualização;
- limiar numérico definitivo de materialidade financeira;
- schema de dados;
- modelo formal de Claim;
- tecnologia, banco, hospedagem ou infraestrutura;
- regras editoriais especializadas ainda pertencentes à Fase 2.

Essas questões devem permanecer abertas até os documentos responsáveis por elas.

---

# 21. Critérios para revisão crítica e canonização

Antes de promover o FF-0007 para CANONICAL, deve-se confirmar que:

- as fronteiras são compatíveis com FF-0001;
- o documento satisfaz o checklist de Escopo do FF-0002;
- o escopo deriva dos usuários e JTBD do FF-0006 sem transformar todos os casos de uso em obrigação de MVP;
- temas esportivos possuem critério claro de promoção para relevância institucional;
- memória institucional está claramente separada de portal de notícias;
- fiscalização está separada de militância eleitoral e exposição pessoal;
- assuntos jurídicos ou investigativos não presumem culpa;
- a existência de escopo conceitual não implica cobertura integral;
- ausências de informação podem permanecer desconhecidas;
- não foram introduzidas decisões técnicas ou de interface prematuras;
- o documento oferece fronteira suficiente para o FF-0008 escolher um MVP pequeno e sustentável.

---

# 22. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION;
- FF-0006 — USERS_AND_USE_CASES.

## Impacta

- FF-0008 — MVP_SPEC;
- FF-0009 — EDITORIAL_POLICY;
- FF-0010 — SOURCE_POLICY;
- FF-0011 — CLAIMS_AND_EVIDENCE;
- FF-0013 — DOMAIN_MODEL;
- FF-0014 — TEMPORAL_MODEL;
- futuros documentos de experiência, arquitetura e operações.

---

# 23. Vigência

Esta versão permanece **DRAFT** até revisão crítica e aprovação explícita.

**FF-0007 — SCOPE v0.1 // DRAFT**
