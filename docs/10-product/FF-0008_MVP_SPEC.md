# FF-0008 — MVP_SPEC

**Nome do documento:** MVP Specification  
**ID:** FF-0008  
**Versão:** 0.1  
**Status:** DRAFT  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define a menor versão do Fiel Fiscaliza capaz de entregar utilidade institucional real e demonstrar a tese de produto sem exigir cobertura ampla, operação editorial diária ou decisões técnicas prematuras.

Seu objetivo é responder:

- qual valor mínimo o MVP precisa entregar;
- para quem a primeira versão será desenhada prioritariamente;
- qual é a unidade principal de experiência do MVP;
- quais capacidades são obrigatórias;
- qual conteúdo mínimo precisa existir no lançamento;
- quais funcionalidades ficam conscientemente adiadas;
- qual é a jornada principal do usuário;
- quais critérios objetivos determinam se o MVP está aceitável;
- o que significa “MVP publicável” em sentido de produto;
- como o MVP permanece sustentável para uma pessoa;
- quais incertezas de produto continuam abertas após a Fase 1.

O FF-0008 não define stack, banco de dados, hospedagem, schema físico, framework, provedor, pipeline definitivo de ingestão, arquitetura visual detalhada ou implementação concreta de interface.

Essas decisões pertencem às fases posteriores do FF-0002.

---

# 2. Autoridade e dependências

Este documento é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION v1.1 // CANONICAL;
- FF-0006 — USERS_AND_USE_CASES v1.0 // CANONICAL;
- FF-0007 — SCOPE v1.0 // CANONICAL.

Em particular, o MVP deve respeitar que:

- sua unidade de valor é uma questão institucional que se torna mais fácil de compreender, verificar e reconstruir;
- o usuário primário da Fase 1 é o torcedor institucionalmente engajado;
- fonte, proveniência, temporalidade e incerteza são partes centrais do valor;
- o produto não deve competir com portais de notícia por velocidade ou volume;
- o escopo institucional permanente é maior que o escopo do MVP;
- informação desconhecida não deve ser preenchida por inferência;
- o MVP deve ser sustentável por uma pessoa;
- a aplicação pública não pode depender de acesso privilegiado ao SCCP, Gaviões da Fiel ou qualquer grupo político;
- custo operacional mensal obrigatório deve poder permanecer em R$ 0 enquanto André mantiver pessoalmente o projeto;
- IA paga não pode ser requisito do caminho crítico público.

---

# 3. Tese do MVP

O MVP não tentará provar que o Fiel Fiscaliza consegue cobrir toda a vida institucional do Corinthians.

Ele deve testar uma proposição menor e mais útil:

> **É possível transformar um conjunto pequeno de questões institucionais públicas do Corinthians em registros temporais, verificáveis e compreensíveis que reduzam o trabalho necessário para descobrir o que aconteceu, qual é o estado conhecido atual e quais fontes sustentam essa reconstrução.**

O MVP será considerado coerente com a visão se demonstrar essa capacidade em profundidade suficiente, mesmo com corpus pequeno.

O foco inicial é **profundidade verificável, não abrangência**.

---

# 4. Proposta de valor mínima

A proposta de valor mínima do MVP é:

> **Ao chegar com uma dúvida institucional relevante sobre o Corinthians, o usuário deve conseguir compreender o estado conhecido da questão, reconstruir seus principais acontecimentos no tempo e chegar às fontes que sustentam a representação apresentada — sem depender de uma sequência extensa de buscas, notícias antigas e memória informal.**

Quando a questão envolver número financeiro, o produto deve permitir compreender o valor com seu contexto mínimo adequado.

Quando envolver decisão institucional pública, deve permitir compreender quem decidiu, quando, o resultado conhecido e os limites da informação disponível.

O MVP não precisa resolver todos os JTBD do FF-0006 em todos os casos publicados.

Ele deve, porém, demonstrar concretamente os quatro JTBD P0 no conjunto do corpus inicial:

1. verificar uma afirmação e chegar à fonte;
2. reconstruir história e estado atual de uma questão;
3. entender um número financeiro no tempo;
4. reconstruir uma decisão institucional pública.

---

# 5. Usuários do MVP

## 5.1 Usuário primário

O MVP será desenhado prioritariamente para o **torcedor institucionalmente engajado**, conforme FF-0006.

Esse usuário deve conseguir aprofundar uma questão sem precisar confiar cegamente no Fiel Fiscaliza e sem conhecer previamente a fonte correta.

## 5.2 Usuários secundários

A experiência também deve permanecer útil e compreensível para:

- torcedor com dúvida institucional pontual;
- jornalista, comunicador ou criador de conteúdo;
- pesquisador histórico, acadêmico ou analista externo.

O MVP não deve exigir linguagem técnica, conhecimento jurídico, contábil ou estatutário prévio para sua compreensão básica.

Especialistas podem aprofundar pela proveniência; não especialistas devem conseguir entender o núcleo da questão antes de aprofundar.

---

# 6. Unidade principal de experiência: Questão Institucional

A unidade central do MVP será a **Questão Institucional**.

Uma Questão Institucional representa um problema, acontecimento ou assunto delimitado cuja compreensão exige relacionar fatos, eventos, fontes e estados ao longo do tempo.

Exemplos abstratos:

- como determinada obrigação financeira evoluiu e por que valores diferentes aparecem em momentos distintos;
- como uma decisão institucional foi tomada e qual é seu estado atual;
- como uma regra, estrutura ou processo de governança mudou;
- qual é a sequência documental necessária para entender uma controvérsia institucional sem transformar alegação em fato.

“Questão Institucional” é conceito de produto desta especificação.

O modelo formal de domínio que representará tecnicamente esse conceito pertence ao FF-0013 — DOMAIN_MODEL e não deve ser antecipado aqui.

## 6.1 Por que a Questão Institucional é a unidade do MVP

Ela conecta diretamente os principais valores definidos anteriormente:

- contexto;
- temporalidade;
- proveniência;
- incerteza;
- reconstrução histórica;
- compreensão sem cobertura jornalística contínua.

Também permite lançar um corpus pequeno sem criar a expectativa de que o produto já seja um banco universal de toda informação do Corinthians.

---

# 7. Estrutura mínima de uma Questão Institucional

Toda Questão Institucional publicável no MVP deve oferecer, em nível conceitual, pelo menos:

## 7.1 Pergunta ou problema delimitado

O usuário deve conseguir identificar claramente qual questão aquela unidade pretende ajudá-lo a compreender.

## 7.2 Resumo contextual

Deve existir uma explicação curta do contexto necessário para que um usuário não especializado entenda por que a questão importa institucionalmente.

## 7.3 Estado conhecido atual

A questão deve indicar o estado conhecido mais recente que o projeto consegue sustentar documentalmente.

Esse estado deve possuir data de referência ou indicação equivalente de atualidade.

## 7.4 Data de última verificação

O usuário deve conseguir distinguir:

- data do acontecimento;
- data ou período a que o estado se refere;
- momento em que o Fiel Fiscaliza verificou aquela representação.

A implementação exata pertence às fases posteriores.

## 7.5 Linha temporal dos acontecimentos materiais

A questão deve permitir reconstruir os principais acontecimentos relevantes em ordem temporal.

A linha temporal não deve registrar todo conteúdo publicado sobre o tema.

Deve registrar eventos que alterem, esclareçam ou documentem materialmente o estado da questão.

## 7.6 Proveniência e fontes

Informações factuais materialmente relevantes devem permitir chegar à fonte que as sustenta ou, quando a fonte não estiver mais acessível, aos metadados de proveniência preservados pelo projeto conforme políticas posteriores.

## 7.7 Incerteza e ausência de informação

Quando algo não puder ser determinado com segurança, a representação deve permitir estados como:

- desconhecido;
- não confirmado;
- não disponível publicamente;
- contestado;
- documento não localizado;
- status não determinado.

A taxonomia editorial formal será definida na Fase 2.

## 7.8 Elementos especializados quando aplicáveis

Questões podem incluir elementos adicionais exigidos pelo tipo de assunto, como número financeiro contextualizado ou decisão institucional pública.

Esses elementos não são obrigatórios em toda Questão Institucional.

---

# 8. Capacidades obrigatórias do MVP

As capacidades abaixo são requisitos de produto. Elas não determinam tecnologia ou layout.

## MVP-CAP-01 — Descoberta do corpus publicado

O usuário deve conseguir visualizar quais Questões Institucionais estão publicadas e acessar cada uma sem conhecer previamente sua URL.

Não é obrigatório existir busca textual global no MVP.

## MVP-CAP-02 — Compreensão rápida da questão

Ao acessar uma Questão Institucional, o usuário deve conseguir identificar:

- qual é a pergunta ou problema;
- por que é institucionalmente relevante;
- qual é o estado conhecido atual;
- quando essa representação foi verificada.

## MVP-CAP-03 — Reconstrução temporal

O usuário deve conseguir percorrer os acontecimentos materiais da questão em ordem temporal e distinguir estados anteriores do estado atual.

Atualizações futuras não devem apagar silenciosamente eventos históricos materiais.

## MVP-CAP-04 — Inspeção de proveniência

O usuário deve conseguir identificar a origem das informações factuais relevantes e acessar a fonte quando ela estiver publicamente disponível.

A evidência deve permanecer próxima o suficiente da informação para permitir auditoria razoável da representação.

## MVP-CAP-05 — Distinção de certeza e incerteza

O produto deve permitir distinguir informação documentada de alegação, contestação ou desconhecimento quando isso for necessário para não induzir conclusão indevida.

A taxonomia detalhada depende de FF-0009 a FF-0011.

## MVP-CAP-06 — Contextualização financeira

Para pelo menos uma questão financeira do corpus inicial, o usuário deve conseguir compreender cada valor material com, quando aplicável:

- valor;
- moeda;
- data-base ou período;
- conceito do número;
- método ou natureza do cálculo quando necessário;
- fonte.

Valores conceitualmente diferentes não devem ser apresentados como equivalentes sem explicação.

## MVP-CAP-07 — Reconstrução de decisão institucional pública

Para pelo menos uma questão de decisão institucional do corpus inicial, o usuário deve conseguir identificar, quando publicamente documentado:

- órgão ou instância decisória;
- data;
- objeto ou pauta relevante;
- resultado conhecido;
- fonte documental;
- voto individual somente quando houver registro público adequado.

Informação individual não publicada deve permanecer desconhecida.

## MVP-CAP-08 — Transparência mínima sobre o próprio projeto

O usuário deve conseguir identificar que o Fiel Fiscaliza:

- é independente;
- não representa oficialmente SCCP, Gaviões ou grupo político;
- trabalha com informação pública e proveniência;
- admite incerteza;
- possui meio público ou acessível de apontar erro, correção ou fonte adicional.

A política formal de correções será definida em FF-0012.

## MVP-CAP-09 — Acesso público sem conta

A consulta ao conteúdo essencial do MVP não deve exigir cadastro, login, pagamento ou vínculo institucional.

## MVP-CAP-10 — Atualização sem obrigação de fluxo diário

O produto deve poder permanecer correto e útil sem exigir publicação cotidiana.

A manutenção deve ocorrer em função de mudanças materiais nas questões acompanhadas e das capacidades operacionais definidas posteriormente.

---

# 9. Corpus mínimo de lançamento

O MVP deve ser lançado com um **corpus pequeno e deliberadamente curado**, suficiente para demonstrar a tese sem simular cobertura total.

## 9.1 Quantidade mínima

O corpus inicial deve conter **pelo menos 3 Questões Institucionais completas** segundo os critérios desta especificação.

Esse número é um critério de demonstração do produto, não uma alegação de que três casos validam demanda de mercado.

## 9.2 Cobertura mínima dos JTBD P0

No conjunto das questões iniciais:

- todas devem demonstrar verificação de fontes e reconstrução temporal;
- pelo menos uma deve demonstrar contextualização financeira;
- pelo menos uma deve demonstrar reconstrução de decisão institucional pública.

Uma mesma questão pode satisfazer mais de um requisito.

## 9.3 Critérios para selecionar as questões iniciais

As questões devem:

- estar claramente dentro do FF-0007;
- possuir relevância institucional demonstrável;
- possuir conjunto razoável de fontes públicas adequadas;
- permitir reconstrução temporal útil;
- ter custo de manutenção compatível com uma pessoa;
- não depender de acesso privilegiado;
- não exigir que o MVP resolva investigação de culpa ou acusação sensível para demonstrar seu valor;
- permitir testar o valor de proveniência e contexto sem exigir cobertura diária.

## 9.4 Tipos recomendados para o corpus inicial

Como direção de produto, o conjunto inicial deve preferencialmente conter:

1. uma questão de **finanças ou Arena** com valores em momentos ou conceitos distintos;
2. uma questão de **governança, votação ou decisão institucional pública**;
3. uma questão de **regra, estrutura, estatuto, participação ou outra mudança institucional temporalmente reconstruível**.

A escolha dos casos concretos deve ser feita antes da publicação do MVP e documentada de forma rastreável, mas esta versão não canoniza acontecimentos específicos como conteúdo obrigatório.

---

# 10. Jornada principal do usuário

A jornada principal do MVP é:

1. o usuário chega ao Fiel Fiscaliza com uma dúvida institucional ou interesse em compreender uma questão;
2. visualiza o conjunto de Questões Institucionais publicadas;
3. seleciona uma questão relevante;
4. compreende rapidamente o problema, o contexto e o estado conhecido atual;
5. percorre a evolução temporal para entender o que mudou;
6. inspeciona as fontes associadas aos fatos ou acontecimentos que deseja verificar;
7. quando aplicável, consulta o contexto de números financeiros ou decisões institucionais;
8. identifica claramente o que permanece desconhecido, contestado ou não disponível;
9. sai com base suficiente para explicar ou continuar investigando a questão sem depender apenas da autoridade do Fiel Fiscaliza.

O objetivo central não é maximizar tempo de permanência.

É **reduzir custo de compreensão e verificação**.

---

# 11. Funcionalidades conscientemente adiadas

As funcionalidades abaixo podem ser valiosas no futuro, mas **não são requisitos do MVP**.

- busca global textual ou semântica;
- alertas e notificações;
- contas de usuário;
- favoritos;
- personalização;
- comentários e comunidade;
- fórum;
- feed de notícias;
- cobertura esportiva;
- perfis completos de dirigentes ou conselheiros;
- grafo político ou visualização avançada de relações;
- ranking de atores políticos;
- painel completo de todos os conselheiros;
- cobertura ampla de todas as votações;
- painel financeiro universal;
- catálogo completo de contratos;
- arquivo integral de todos os documentos institucionais;
- cobertura ampla de processos e investigações;
- backfill histórico completo;
- exportações acadêmicas avançadas;
- API pública;
- aplicativo móvel nativo;
- assistente público de IA;
- geração automática de conclusões ou julgamento editorial por IA;
- tradução para outros idiomas;
- participação política, votação ou mobilização interna pelo produto.

Adiar não significa proibir permanentemente.

Qualquer inclusão futura deve respeitar FF-0001 e FF-0007 e passar pelos documentos responsáveis.

---

# 12. Cobertura jurídica, investigativa e de claims conflitantes no MVP

Processos, investigações e claims conflitantes pertencem ao escopo permanente, mas possuem risco editorial elevado no FF-0006.

Por isso, o MVP **não precisa ter cobertura ampla dessas áreas como proposta de valor principal**.

Uma Questão Institucional do corpus inicial pode conter elemento jurídico ou contestação quando necessário para compreender o assunto, desde que:

- seja indispensável ao contexto;
- exista base pública adequada;
- a representação não dependa de inferir culpa, intenção ou verdade material de acusação;
- as políticas editoriais da Fase 2 já sejam suficientes para publicação responsável.

O MVP não deve escolher como vitrine inicial um caso cujo valor dependa principalmente de transformar acusação sensível ou investigação em narrativa conclusiva.

---

# 13. Requisitos editoriais e de proveniência antes da publicação

O FF-0008 define requisitos de produto, mas a publicação real do MVP dependerá das regras posteriores de editorial, fonte, claims e correções.

Antes de uma Questão Institucional ser publicável, deve ser possível demonstrar que:

- suas informações factuais relevantes possuem proveniência adequada;
- fontes primárias são priorizadas quando apropriadas e disponíveis;
- alegação não está apresentada como fato;
- investigação não está apresentada como comprovação de culpa;
- decisão não definitiva não está apresentada como definitiva;
- voto individual desconhecido não foi inferido;
- relações políticas não documentadas não foram inventadas;
- informação privada desnecessária não foi incorporada;
- divergências de números ou versões relevantes receberam contexto suficiente;
- correções futuras podem ser feitas sem apagar silenciosamente histórico material.

Os estados, regras e metadados formais serão definidos por FF-0009 a FF-0012.

---

# 14. Sustentabilidade operacional do MVP

O MVP deve ser compatível com manutenção pessoal por André.

Isso significa que o produto **não pode exigir como condição de qualidade**:

- publicação diária;
- cobertura de toda novidade institucional;
- acompanhamento manual contínuo de dezenas de fontes;
- resposta em tempo real;
- moderação de comunidade ativa;
- alimentação manual diária de grande volume;
- contratação de serviço pago indispensável.

## 14.1 Estratégia de manutenção compatível com o MVP

A primeira versão pode operar com corpus pequeno e atualização por mudança material.

O produto deve permitir indicar quando uma questão foi verificada pela última vez, reduzindo a necessidade de fingir atualização contínua.

Automação de coleta e manutenção por exceção permanece direção constitucional, mas o nível de automação concreto será definido nas fases de arquitetura e operações.

O MVP pode começar com processos parcialmente manuais ou semiautomáticos desde que isso não crie obrigação recorrente incompatível com uma pessoa e que o caminho para manutenção sustentável não dependa de serviço pago essencial.

---

# 15. Independência de acesso privilegiado

Nenhum requisito do MVP pode depender de:

- acesso interno ao SCCP;
- credencial de associado não pública como requisito do produto;
- grupo fechado de Gaviões ou outra torcida organizada;
- documento confidencial;
- vazamento;
- fonte obtida por acesso não autorizado;
- amizade, contato político ou relação pessoal do mantenedor;
- autorização de dirigente, conselheiro ou grupo interno.

Informação fornecida legitimamente por terceiros pode ser avaliada futuramente pelas políticas de fontes, mas **o funcionamento essencial do MVP deve ser possível utilizando informação pública e adequadamente acessível**.

---

# 16. Critérios objetivos de aceite do MVP

Os critérios abaixo devem ser verificáveis antes de declarar a especificação implementada em nível de produto.

## MVP-AC-01 — Corpus mínimo

Existem pelo menos 3 Questões Institucionais publicáveis e completas.

## MVP-AC-02 — Descoberta

Um usuário consegue encontrar e abrir todas as Questões Institucionais publicadas sem conhecer previamente URLs internas.

## MVP-AC-03 — Estado atual

Cada questão apresenta um estado conhecido atual ou explicita que esse estado não pôde ser determinado com segurança.

## MVP-AC-04 — Referência temporal

Cada questão permite identificar a data ou período relevante do estado atual e a última verificação feita pelo projeto.

## MVP-AC-05 — Histórico preservado

Cada questão possui reconstrução temporal dos acontecimentos materiais necessários para compreender sua evolução, sem sobrescrever estados anteriores relevantes.

## MVP-AC-06 — Proveniência

Toda informação factual materialmente relevante publicada possui fonte ou proveniência suficiente segundo as políticas canônicas vigentes no momento do release.

## MVP-AC-07 — Fonte acessível ou explicada

Quando uma fonte original estiver publicamente acessível, o usuário consegue chegar a ela a partir da representação do produto.

Quando não estiver mais acessível, o produto não inventa sua disponibilidade e aplica a política de proveniência definida posteriormente.

## MVP-AC-08 — Incerteza visível

Questões com informação contestada, incompleta ou não confirmada não apresentam falsa certeza.

## MVP-AC-09 — Caso financeiro

Pelo menos uma questão demonstra número financeiro com contexto suficiente de valor, data-base/período, conceito e fonte, além de método quando necessário.

## MVP-AC-10 — Caso decisório

Pelo menos uma questão demonstra decisão institucional com órgão, data, objeto/resultados conhecidos e fonte; votos individuais só aparecem quando publicamente sustentados.

## MVP-AC-11 — Independência explícita

O produto deixa claro que não representa oficialmente SCCP, Gaviões ou grupo político.

## MVP-AC-12 — Consulta pública

O conteúdo essencial pode ser consultado sem cadastro ou pagamento.

## MVP-AC-13 — Correção acessível

Existe mecanismo acessível para que uma pessoa indique possível erro, fonte adicional ou pedido de correção, sem exigir que o Fiel Fiscaliza aceite automaticamente a alegação enviada.

## MVP-AC-14 — Sem acesso privilegiado

Nenhuma das três Questões Institucionais mínimas depende de fonte privada, credencial interna ou acesso não público para entregar sua proposta de valor.

## MVP-AC-15 — Sustentabilidade

O corpus inicial pode ser mantido sem obrigação editorial diária e sem serviço pago indispensável.

## MVP-AC-16 — Escopo preservado

Nenhuma capacidade implementada transforma o produto em portal esportivo, campanha política, sistema de denúncias irrestrito ou dossiê de vida privada.

## MVP-AC-17 — Compreensão básica independente de especialização

A representação inicial de cada questão explica contexto suficiente para que um torcedor sem conhecimento técnico especializado consiga compreender a pergunta central e o estado conhecido antes de abrir documentos de origem.

---

# 17. O que significa “MVP publicável”

Neste documento, **MVP publicável** significa que a especificação de produto está completa e que a implementação futura satisfaz os critérios de aceite acima.

Isso **não autoriza publicação imediata ao final da Fase 1**.

O release público real continua dependente das fases posteriores do FF-0002, incluindo, quando aplicáveis:

- política editorial;
- política de fontes e evidências;
- modelo de domínio e temporalidade;
- arquitetura;
- experiência;
- segurança, privacidade e risco legal;
- operações;
- critérios de Definition of Done e release.

Portanto:

> **FF-0008 define o produto que poderá ser publicado; os gates posteriores determinam se ele está pronto para ser publicado com segurança e qualidade.**

---

# 18. Critério de sucesso inicial após o lançamento

O MVP não terá meta artificial de tráfego ou crescimento como condição de sucesso.

Os primeiros sinais de valor devem procurar responder:

- usuários conseguem compreender uma questão sem recorrer imediatamente a múltiplas buscas externas?;
- conseguem identificar a fonte e auditar a representação?;
- a cronologia reduz confusão sobre o que aconteceu e o que mudou?;
- valores financeiros contextualizados evitam comparação enganosa?;
- decisões institucionais ficam mais claras sem inferir informação ausente?;
- a manutenção real permanece sustentável para André?;
- algum caso de uso ou segmento se mostra materialmente diferente das hipóteses atuais?

Esses sinais podem ser avaliados posteriormente por uso real, feedback, observação e pesquisa proporcional ao risco.

A dívida de validação do FF-0006 permanece ativa.

---

# 19. Gatilhos para rever o MVP após evidência real

A especificação deve ser reavaliada se ocorrer, entre outros:

1. o formato de Questão Institucional não ajudar usuários a compreender ou verificar o problema;
2. o corpus exigir manutenção recorrente incompatível com uma pessoa;
3. usuários utilizarem principalmente um segmento ou JTBD diferente do esperado;
4. as fontes disponíveis não sustentarem reconstruções confiáveis;
5. a contextualização necessária tornar a experiência excessivamente complexa para usuários não especializados;
6. soluções existentes demonstrarem atender melhor os mesmos casos de uso;
7. um recurso adiado se mostrar claramente necessário para completar a jornada principal;
8. risco editorial, jurídico ou de privacidade tornar alguma capacidade inadequada.

Esses gatilhos não implicam pivot automático.

Eles exigem revisão da evidência e decisão explícita.

---

# 20. Decisões deliberadamente não tomadas pelo FF-0008

Permanecem para fases posteriores:

- stack de frontend ou backend;
- banco de dados;
- formato de arquivos ou persistência;
- CMS;
- geração estática ou dinâmica concreta;
- provedor de hospedagem;
- GitHub Actions ou outro mecanismo de automação;
- Cloudflare, Supabase ou outro provedor;
- estrutura de URLs;
- design visual;
- navegação detalhada;
- mecanismo concreto de busca futura;
- schema de Questão, Evento, Fonte, Claim ou Entidade;
- taxonomia editorial formal;
- pipeline de ingestão;
- regras de scraping;
- política de retenção;
- implementação do mecanismo de correção;
- analytics e métricas concretas;
- nomes e acontecimentos exatos das primeiras 3 Questões Institucionais.

Essas decisões não devem ser inferidas silenciosamente por implementação.

---

# 21. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION;
- FF-0006 — USERS_AND_USE_CASES;
- FF-0007 — SCOPE.

## Impacta

O FF-0008 condicionará principalmente:

- FF-0009 a FF-0012 — políticas editoriais, fontes, claims e correções;
- FF-0013 a FF-0015 — domínio, temporalidade e eventos;
- FF-0016 a FF-0021 — arquitetura e decisões relacionadas;
- FF-0022 a FF-0026 — experiência e conteúdo;
- FF-0027 a FF-0030 — qualidade, segurança, privacidade e risco;
- FF-0031 a FF-0034 — operações e manutenção;
- FF-0035 a FF-0038 — roadmap, backlog, readiness e done.

O FF-0008 não autoriza implementação regular antes do cumprimento dos gates definidos pelo FF-0002.

---

# 22. Critérios para revisão crítica e canonização

Antes de promover o FF-0008 para CANONICAL, deve-se confirmar que:

- a proposta de valor mínima é coerente com FF-0005;
- usuários e JTBD derivam de FF-0006;
- nenhuma capacidade viola FF-0007;
- o MVP é menor que o escopo permanente do produto;
- o corpus mínimo demonstra utilidade real sem exigir cobertura ampla;
- as capacidades obrigatórias podem ser descritas sem stack ou arquitetura;
- a jornada principal está explícita;
- funcionalidades adiadas estão registradas;
- critérios de aceite são verificáveis;
- “MVP publicável” está separado de “pronto para release público”;
- a manutenção não exige operação diária;
- o MVP pode operar com custo mensal obrigatório de R$ 0;
- o MVP não depende de acesso institucional privilegiado;
- risco jurídico/editorial elevado não foi transformado em requisito de vitrine inicial;
- a dívida de validação permanece explícita;
- nenhuma decisão técnica futura foi canonizada prematuramente.

---

# 23. Vigência

Esta versão permanece **DRAFT** até revisão crítica e aprovação explícita.

**FF-0008 — MVP_SPEC v0.1 // DRAFT**
