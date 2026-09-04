# FF-0007 — SCOPE

**Nome do documento:** Scope  
**ID:** FF-0007  
**Versão:** 0.2  
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
- como distinguir escopo permanente do produto, cobertura atual e escopo do MVP;
- como evitar expansão silenciosa de escopo ao longo do tempo.

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
- informação desconhecida ou não disponível publicamente pode permanecer explicitamente desconhecida;
- acesso público a uma informação não significa automaticamente que sua coleta, armazenamento ou republicação integral seja apropriada.

---

# 3. Princípio central de escopo

O Fiel Fiscaliza deve cobrir **a vida institucional do Sport Club Corinthians Paulista e relações externas que produzam consequência institucional materialmente relevante sobre o clube**.

O critério não é simplesmente se um assunto “fala do Corinthians”, gera engajamento ou aparece muito na imprensa.

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

## 3.1 O que significa “materialmente relevante”

Neste documento, materialidade é qualitativa.

Uma consequência é materialmente relevante quando pode alterar de maneira não trivial a compreensão de pelo menos um dos seguintes elementos:

- quem exerce poder ou possui competência institucional;
- qual regra, decisão, direito, obrigação ou procedimento está vigente;
- posição financeira ou patrimonial relevante do clube;
- estado jurídico, regulatório ou investigativo de questão institucional;
- capacidade de participação, representação ou controle associativo;
- interpretação histórica de ato, gestão, decisão ou relação institucional.

Materialidade **não é sinônimo de popularidade, repercussão, valor absoluto alto ou controvérsia pública**.

Um tema muito comentado pode permanecer fora de escopo; um documento pouco comentado pode ser central para o produto.

---

# 4. Teste de pertinência institucional

Antes de tratar um tema adjacente ou duvidoso como parte da cobertura, devem ser respondidas quatro perguntas.

## 4.1 Nexo

Existe relação direta e demonstrável com o SCCP em capacidade institucional, e não apenas proximidade pessoal, esportiva ou midiática?

## 4.2 Consequência

O tema altera, documenta ou ajuda a compreender alguma dimensão material descrita na seção 3.1?

## 4.3 Utilidade

Sua inclusão contribui para pelo menos um JTBD do FF-0006 ou para a memória institucional necessária a esses Jobs?

## 4.4 Base pública e proporcionalidade

Existe base pública adequada para tratamento responsável, e a informação a ser armazenada ou publicada é proporcional à finalidade institucional?

Se o nexo ou a consequência institucional não puderem ser demonstrados, o tema deve permanecer fora de escopo.

Se o tema passar pelo teste, ele se torna elegível; prioridade de cobertura continua sujeita à seção 19.

---

# 5. Três camadas que não devem ser confundidas

## 5.1 Escopo do produto

Define aquilo que o Fiel Fiscaliza pode legitimamente cobrir ao longo de sua vida.

## 5.2 Cobertura atual

Define aquilo que o projeto consegue efetivamente manter com qualidade em determinado momento.

A ausência de cobertura de um tema em escopo não significa que ele deixou de pertencer ao produto.

## 5.3 Escopo do MVP

Define o menor subconjunto de problemas e capacidades que será implementado na primeira versão publicável.

O fato de um tema estar no escopo do produto **não obriga sua presença no MVP**.

O FF-0008 deverá escolher esse subconjunto explicitamente.

Essa separação impede que “está no escopo” se transforme em compromisso de cobrir tudo desde o início.

---

# 6. Domínios institucionais em escopo

Os domínios abaixo formam o núcleo institucional legítimo do Fiel Fiscaliza, sujeitos a relevância, disponibilidade de evidência e capacidade de manutenção.

## 6.1 Governança e estrutura institucional

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

## 6.2 Estatuto, regimentos e regras institucionais

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

## 6.3 Eleições, chapas e participação associativa

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

## 6.4 Decisões, votações e atuação institucional

Inclui:

- pautas formalmente deliberadas;
- decisões de órgãos;
- resultados de votações;
- votos individuais somente quando forem publicamente conhecidos de forma adequada;
- posições públicas diretamente relacionadas a questão institucional;
- histórico de atuação em cargos e órgãos quando verificável.

Resultado coletivo não deve ser transformado em voto individual presumido.

Declarações isoladas não precisam ser catalogadas apenas por existirem; devem possuir valor para reconstrução de questão institucional relevante.

---

## 6.5 Finanças e patrimônio

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

## 6.6 Arena e estruturas relacionadas

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

## 6.7 Contratos, parcerias e operações institucionalmente relevantes

Contratos e relações comerciais podem entrar no produto quando sua importância ultrapassar a rotina esportiva ou administrativa e houver consequência institucional relevante.

Fatores que podem sustentar relevância incluem:

- obrigação material em relação à realidade financeira do clube;
- duração ou comprometimento relevante de longo prazo;
- efeito sobre patrimônio, direitos, marca ou receitas futuras;
- controvérsia jurídica ou regulatória material;
- participação em investigação ou processo;
- mudança estrutural na forma de exploração de ativo, marca ou atividade;
- necessidade de compreender decisão de governança relevante.

Valor nominal alto, isoladamente, não transforma todo contrato esportivo em item obrigatório do produto.

O Fiel Fiscaliza **não assume que todo contrato do clube deve ser catalogado**.

---

## 6.8 Investigações, processos e decisões jurídicas ou regulatórias

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

## 6.9 Transparência e documentos institucionais

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

## 6.10 Pessoas em capacidade institucional

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

# 7. Entidades externas ao SCCP

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

# 8. Torcidas organizadas, movimentos e coletivos

A atuação de torcidas organizadas, movimentos, coletivos e grupos de associados pode entrar no produto quando houver conexão direta e material com:

- governança do SCCP;
- eleição ou reforma estatutária;
- proposição ou pedido formal dirigido à instituição;
- participação documentada em processo, assembleia ou acontecimento institucional;
- mobilização cujo efeito institucional seja necessário para reconstruir determinada questão;
- posicionamento público cuja preservação seja necessária para compreender debate, decisão ou mudança institucional relevante.

A mera existência de opinião política, postagem, disputa interna ou mobilização sem consequência institucional não gera obrigação de registro.

A vida interna desses grupos, suas disputas próprias, carnaval, atividades sociais ou outros assuntos sem consequência institucional para o SCCP não pertencem automaticamente ao escopo.

O Fiel Fiscaliza deve registrar posições desses grupos como **posições atribuídas a seus emissores**, não como verdade automática sobre terceiros.

---

# 9. Critério para temas esportivos adquirirem relevância institucional

Um tema de futebol que normalmente estaria fora de escopo pode entrar quando deixar de ser apenas esportivo e passar a produzir consequência institucional documentável.

Para isso, deve existir pelo menos uma conexão material com:

1. **governança:** decisão, crise ou alteração relevante de estrutura ou poder;
2. **finanças ou patrimônio:** obrigação, receita, dívida, ativo ou impacto materialmente relevante;
3. **jurídico/regulatório:** processo, investigação, sanção, disputa ou obrigação formal relevante;
4. **administração:** mudança estrutural ou decisão administrativa relevante;
5. **transparência/integridade institucional:** necessidade de documentar ato, contrato ou procedimento cuja relevância ultrapasse a cobertura esportiva cotidiana.

Além dessa conexão, a inclusão deve contribuir para pelo menos um JTBD relevante do FF-0006 e possuir base pública suficientemente adequada para tratamento responsável.

---

# 10. Exemplos de fronteira esportivo × institucional

Os exemplos abaixo são orientativos e não substituem análise do caso concreto.

| Tema | Regra de escopo |
|---|---|
| escalação de uma partida | fora de escopo |
| desempenho individual de jogador | fora de escopo |
| análise tática | fora de escopo |
| resultado de jogo | fora de escopo, salvo quando necessário como contexto mínimo de consequência institucional |
| rumor comum de transferência | fora de escopo |
| contratação de jogador | normalmente fora; pode entrar se houver questão financeira, contratual, jurídica ou de governança materialmente relevante além da rotina esportiva |
| rescisão de atleta ou treinador | normalmente fora; pode entrar quando produzir obrigação financeira, litígio ou decisão institucional relevante |
| punição esportiva | pode entrar quando houver consequência jurídica, regulatória, financeira ou institucional relevante |
| patrocínio relevante | em escopo quando possuir efeito financeiro, contratual, patrimonial ou de governança materialmente relevante |
| conflito entre dirigente e atleta | fora por padrão; entra apenas se evoluir para questão institucional documentável |
| venda de mando / uso de estádio | pode entrar se houver impacto patrimonial, contratual, financeiro ou decisório relevante |

O Fiel Fiscaliza deve registrar somente o contexto esportivo necessário para compreender a consequência institucional.

---

# 11. Fronteira entre memória institucional e portal de notícias

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

# 12. Fronteira entre fiscalização e militância política

O Fiel Fiscaliza pode defender os princípios procedimentais já assumidos por sua Constituição, como:

- transparência;
- prestação de contas;
- memória institucional;
- verificabilidade;
- acesso público adequado à informação institucional;
- preservação de incerteza e de evidência.

Essa defesa não autoriza transformar o produto em campanha por resultados políticos ou modelos institucionais específicos.

Por padrão, o Fiel Fiscaliza não deve recomendar ou fazer campanha por:

- candidatura ou chapa;
- situação ou oposição;
- voto em eleição interna;
- manutenção ou destituição de pessoa em cargo;
- adoção ou rejeição de SAF;
- modelo estatutário específico;
- sistema eleitoral específico;
- outro resultado político substantivo do clube.

O projeto pode documentar propostas, argumentos, posições e consequências desses modelos quando forem institucionalmente relevantes, sem converter documentação em endosso.

---

# 13. Fronteira entre fiscalização e exposição pessoal

A relevância pública de um cargo não transforma toda a vida de seu ocupante em assunto do Fiel Fiscaliza.

Informação sobre uma pessoa deve satisfazer pelo menos uma das seguintes condições:

- descreve função ou mandato institucional;
- documenta ato público praticado em capacidade institucional;
- registra posição pública diretamente relacionada ao SCCP;
- é necessária para compreender relação institucional verificável;
- integra procedimento público relevante ao clube de forma documentalmente sustentada.

Mesmo quando uma informação é publicamente encontrável, sua publicação pelo Fiel Fiscaliza deve ser necessária e proporcional à finalidade institucional.

---

# 14. Rumores, denúncias e conteúdo não verificado

Rumor não constitui motivo suficiente para inclusão factual.

Denúncia ou acusação pode entrar quando sua existência for institucionalmente relevante e adequadamente documentada, desde que o produto deixe claro:

- quem apresentou a alegação;
- qual é seu status;
- se existe investigação ou processo;
- quais evidências públicas estão disponíveis;
- o que permanece desconhecido ou contestado.

O Fiel Fiscaliza não deve operar como caixa de denúncias anônimas irrestrita nem publicar acusação apenas por circulação em rede social.

---

# 15. Temas normalmente fora de escopo

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

# 16. Informação pública insuficiente

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

# 17. Público não significa automaticamente apropriado para republicação

Uma informação ser acessível publicamente é condição relevante para o projeto, mas não é autorização automática para coleta ou republicação irrestrita.

Antes de armazenar ou republicar conteúdo, devem ser considerados, conforme o caso:

- necessidade institucional;
- proporcionalidade;
- privacidade e risco de reidentificação;
- direitos autorais e limites de reprodução;
- termos e limitações legítimas da fonte;
- segurança de pessoas;
- existência de alternativa menos invasiva, como registrar metadados, resumo, hash ou link de origem.

As regras especializadas pertencerão principalmente ao FF-0010 — SOURCE_POLICY e aos documentos de segurança, privacidade e risco legal.

Esta seção estabelece somente a fronteira de produto: **o Fiel Fiscaliza não deve usar “está na internet” como justificativa suficiente para armazenar ou republicar informação.**

---

# 18. Escopo temporal

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

# 19. Critério de inclusão editorial-operacional

Um item estar em escopo não significa que deve ser imediatamente coletado ou publicado.

Antes de priorizar cobertura, deve-se avaliar pelo menos:

1. **relevância institucional:** altera ou ajuda a compreender poder, regra, decisão, patrimônio, finanças, obrigação, processo ou memória relevante?;
2. **utilidade:** atende a JTBD ou pergunta relevante do produto?;
3. **evidência:** existe base pública suficiente para tratamento responsável?;
4. **temporalidade:** preservar mudança ou histórico acrescenta valor?;
5. **risco editorial:** existe risco elevado de acusação, assédio, privacidade ou interpretação indevida?;
6. **sustentabilidade:** o custo recorrente de manter a cobertura é compatível com uma pessoa?;
7. **duplicação:** soluções existentes já resolvem suficientemente a tarefa sem ganho material do Fiel Fiscaliza?;
8. **proporcionalidade:** a quantidade e granularidade da informação são necessárias para a finalidade institucional?

Esses fatores orientam priorização; não constituem fórmula numérica, ranking automático ou autorização para automatizar julgamento editorial.

---

# 20. Critérios de não inclusão mesmo quando há interesse da torcida

Interesse, curiosidade, repercussão ou pressão pública não são suficientes quando:

- a informação é privada e sem necessidade institucional proporcional;
- a alegação não possui base pública adequada;
- o assunto exigiria especulação para preencher lacunas;
- a cobertura facilitaria assédio ou perseguição de forma desproporcional;
- o tema é essencialmente esportivo e não possui consequência institucional relevante;
- a inclusão transformaria o produto em campanha política ou veículo de ataque;
- a cobertura exigiria operação diária incompatível com a sustentabilidade do projeto sem entregar valor institucional proporcional.

---

# 21. Relação com os JTBD do FF-0006

O escopo deve permitir principalmente que o usuário consiga:

- verificar uma afirmação e chegar à fonte;
- reconstruir a história e o estado atual de uma questão;
- entender um número financeiro no tempo;
- reconstruir uma decisão institucional pública.

Casos secundários, como acompanhamento de investigação, claims conflitantes, histórico de cargos e estado conhecido em data passada, pertencem ao universo do produto, mas podem exigir política editorial e modelo de evidência mais maduros antes de receber cobertura ampla.

A inclusão de um domínio no FF-0007 não supera dependências futuras de FF-0009 a FF-0012.

---

# 22. Controle de expansão de escopo

Novos casos concretos que se enquadrem claramente nas fronteiras deste documento não exigem alteração do FF-0007.

Entretanto, deve haver revisão explícita deste documento antes de:

- incorporar um novo domínio permanente não coberto pelas categorias atuais;
- transformar atividade hoje considerada fora de escopo em função regular do produto;
- ampliar a fiscalização para organizações externas como objetivo próprio;
- adotar cobertura esportiva cotidiana;
- introduzir função de mobilização política, denúncia aberta ou avaliação reputacional de indivíduos;
- alterar materialmente a fronteira entre informação institucional e vida privada.

Expansão relevante de escopo não deve ocorrer silenciosamente por acumulação de pequenas funcionalidades.

---

# 23. Decisões deliberadamente adiadas

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

# 24. Revisão crítica de 2026-09-04

A revisão da v0.1 identificou cinco riscos principais e os tratou nesta versão.

## 24.1 Circularidade de “relevância institucional”

A v0.1 utilizava materialidade como critério correto, porém ainda amplo. A v0.2 define materialidade qualitativa e adiciona teste de pertinência institucional.

## 24.2 Escopo excessivo de atores externos e movimentos

A redação foi estreitada para impedir que posições, disputas ou atividades de organizações externas sejam cobertas apenas por proximidade temática.

## 24.3 Risco de militância substantiva

A fronteira política agora distingue defesa de princípios procedimentais já canônicos de campanha por candidaturas, modelos institucionais ou resultados políticos específicos.

## 24.4 Confusão entre acesso público e adequação para publicação

A v0.2 deixa explícito que conteúdo acessível na internet pode ainda ser inadequado para armazenamento ou republicação integral.

## 24.5 Scope creep por acumulação

Foi criada regra de controle de expansão para exigir revisão documental quando a natureza permanente do produto mudar.

A revisão não identificou conflito material bloqueante com FF-0001, FF-0002, FF-0005 ou FF-0006.

---

# 25. Critérios para canonização

Antes de promover o FF-0007 para CANONICAL, deve-se confirmar que:

- as fronteiras são compatíveis com FF-0001;
- o documento satisfaz o checklist de Escopo do FF-0002;
- o escopo deriva dos usuários e JTBD do FF-0006 sem transformar todos os casos de uso em obrigação de MVP;
- materialidade e pertinência institucional possuem critérios utilizáveis sem fórmula artificial;
- temas esportivos possuem critério claro de promoção para relevância institucional;
- memória institucional está claramente separada de portal de notícias;
- fiscalização está separada de militância eleitoral e exposição pessoal;
- assuntos jurídicos ou investigativos não presumem culpa;
- a existência de escopo conceitual não implica cobertura integral;
- ausências de informação podem permanecer desconhecidas;
- acesso público não é tratado como autorização automática de republicação;
- expansão relevante de escopo exige revisão explícita;
- não foram introduzidas decisões técnicas ou de interface prematuras;
- o documento oferece fronteira suficiente para o FF-0008 escolher um MVP pequeno e sustentável.

A revisão crítica de 2026-09-04 considera esses critérios satisfeitos no conteúdo da v0.2, sujeito à aprovação explícita de André para promoção a CANONICAL.

---

# 26. Impacto e dependências documentais

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

# 27. Vigência

Esta versão permanece **DRAFT** até aprovação explícita.

**FF-0007 — SCOPE v0.2 // DRAFT**
