# FF-0008 — MVP_SPEC

**Nome do documento:** MVP Specification  
**ID:** FF-0008  
**Versão:** 0.2  
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
- quais funcionalidades compatíveis com a visão ficam conscientemente adiadas;
- quais elementos permanecem fora do produto sob as regras canônicas atuais;
- qual é a jornada principal do usuário;
- quais critérios objetivos determinam se o MVP está aceitável;
- o que significa “MVP publicável” em sentido de Produto;
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
- IA paga não pode ser requisito do caminho crítico público;
- acesso público a uma informação não significa automaticamente que sua republicação integral seja apropriada.

A revisão crítica desta versão não identificou conflito canônico bloqueante com esses documentos.

---

# 3. Tese do MVP

O MVP não tentará provar que o Fiel Fiscaliza consegue cobrir toda a vida institucional do Corinthians.

Ele deve testar uma proposição menor e mais útil:

> **É possível transformar um conjunto pequeno de questões institucionais públicas do Corinthians em representações temporais, verificáveis e compreensíveis que reduzam o trabalho necessário para descobrir o que aconteceu, qual era o estado conhecido na última verificação e quais fontes sustentam essa reconstrução.**

O MVP será considerado coerente com a visão se demonstrar essa capacidade em profundidade suficiente, mesmo com corpus pequeno.

O foco inicial é **profundidade verificável, não abrangência**.

O MVP não promete conhecimento em tempo real nem cobertura exaustiva do estado institucional do clube.

---

# 4. Proposta de valor mínima

A proposta de valor mínima do MVP é:

> **Ao chegar com uma dúvida institucional relevante sobre o Corinthians, o usuário deve conseguir compreender o estado conhecido da questão na última verificação do projeto, reconstruir seus principais acontecimentos e chegar às fontes que sustentam a representação apresentada — sem depender de uma sequência extensa de buscas, notícias antigas e memória informal.**

Quando a questão envolver número financeiro, o produto deve permitir compreender o valor com seu contexto mínimo adequado.

Quando envolver decisão institucional pública, deve permitir compreender quem decidiu, quando, o resultado conhecido e os limites da informação disponível.

O MVP não precisa resolver todos os JTBD do FF-0006 em todos os casos publicados.

Ele deve, porém, demonstrar concretamente os quatro JTBD P0 no conjunto do corpus inicial:

1. verificar uma afirmação e chegar à fonte;
2. reconstruir história e estado conhecido de uma questão;
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

A unidade central de experiência do MVP será a **Questão Institucional**.

Uma Questão Institucional representa um problema, acontecimento ou assunto delimitado cuja compreensão exige relacionar fatos, mudanças, fontes e estados ao longo do tempo.

Exemplos abstratos:

- como determinada obrigação financeira evoluiu e por que valores diferentes aparecem em momentos distintos;
- como uma decisão institucional foi tomada e qual era seu estado conhecido na última verificação;
- como uma regra, estrutura ou processo de governança mudou;
- qual é a sequência documental necessária para entender uma controvérsia institucional sem transformar alegação em fato.

“Questão Institucional” é conceito de produto desta especificação.

Ela **não obriga** o FF-0013 a criar uma entidade de domínio com esse nome, não determina schema de persistência e não exige que cada questão corresponda tecnicamente a uma única página ou rota.

O modelo formal de domínio e a arquitetura de informação poderão decompor essa experiência em entidades e estruturas diferentes, desde que preservem a proposta de valor canônica.

## 6.1 Por que a Questão Institucional é a unidade do MVP

Ela conecta diretamente:

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

Deve existir explicação curta do contexto necessário para que um usuário não especializado entenda por que a questão importa institucionalmente.

## 7.3 Estado conhecido na última verificação

A questão deve indicar o estado mais recente que o projeto conseguiu sustentar documentalmente no momento de sua última verificação.

Isso não deve ser apresentado como garantia de tempo real.

Quando a questão estiver encerrada ou for estritamente histórica, o equivalente pode ser o desfecho ou estado historicamente relevante documentado, em vez de uma falsa noção de “situação atual”.

## 7.4 Referência temporal e última verificação

O usuário deve conseguir distinguir, quando aplicável:

- data do acontecimento;
- data ou período a que determinado estado se refere;
- momento em que o Fiel Fiscaliza verificou aquela representação.

A data de última verificação informa **quando o projeto conferiu o conteúdo**, não constitui promessa de que nenhuma mudança ocorreu posteriormente.

O MVP não possui SLA de atualização em tempo real.

## 7.5 Reconstrução temporal suficiente

A questão deve permitir compreender os acontecimentos materiais necessários para reconstruir sua evolução.

Não é obrigatório criar uma linha temporal artificial quando o caso não possuir múltiplos eventos materiais.

Quando houver evolução relevante, estados anteriores não devem ser apagados silenciosamente por atualizações posteriores.

O produto não deve registrar todo conteúdo publicado sobre o tema; apenas eventos que alterem, esclareçam ou documentem materialmente a questão.

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

O usuário deve conseguir descobrir quais Questões Institucionais estão publicadas e acessar cada uma sem conhecer previamente sua URL.

Não é obrigatório existir busca textual global no MVP.

A descoberta pode ser resolvida por mecanismo simples, cuja forma pertence à Fase de Experiência.

## MVP-CAP-02 — Compreensão rápida da questão

Ao acessar uma Questão Institucional, o usuário deve conseguir identificar:

- qual é a pergunta ou problema;
- por que é institucionalmente relevante;
- qual era o estado conhecido na última verificação;
- quando essa representação foi verificada.

## MVP-CAP-03 — Reconstrução temporal

O usuário deve conseguir compreender a sequência dos acontecimentos materiais quando houver evolução temporal relevante e distinguir estados anteriores do estado conhecido na última verificação.

O produto não deve fabricar cronologia apenas para preencher estrutura.

## MVP-CAP-04 — Inspeção de proveniência

O usuário deve conseguir identificar a origem das informações factuais relevantes e acessar a fonte quando ela estiver publicamente disponível e sua exposição for apropriada.

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
- possui meio acessível de apontar possível erro, pedir correção ou indicar fonte adicional.

Esse mecanismo não precisa funcionar como fórum, comentários públicos ou atendimento em tempo real, e não cria obrigação de aceitar automaticamente alegações recebidas.

A política formal de correções será definida em FF-0012.

## MVP-CAP-09 — Acesso público sem conta

A consulta ao conteúdo essencial do MVP não deve exigir cadastro, login, pagamento ou vínculo institucional.

## MVP-CAP-10 — Atualização sem obrigação de fluxo diário

O produto deve poder permanecer útil sem exigir publicação cotidiana.

A manutenção deve ocorrer em função de mudanças materiais nas questões acompanhadas e das capacidades operacionais definidas posteriormente.

A data de última verificação deve impedir que ausência de atualização seja apresentada como certeza de atualidade.

---

# 9. Corpus mínimo de lançamento

O MVP deve ser lançado com um **corpus pequeno, coerente e deliberadamente curado**, suficiente para demonstrar a tese sem simular cobertura total.

## 9.1 Quantidade mínima

O corpus inicial deve conter **pelo menos 3 Questões Institucionais completas** segundo os critérios desta especificação.

Esse número é um critério pragmático de demonstração de repetibilidade do formato, não uma alegação de que três casos validam demanda de mercado.

O objetivo é evitar tanto um protótipo de caso único quanto um catálogo amplo demais para a primeira versão.

## 9.2 Cobertura mínima dos JTBD P0

No conjunto das questões iniciais:

- todas devem demonstrar proveniência adequada e contexto temporal suficiente;
- pelo menos uma deve demonstrar evolução temporal com mais de um acontecimento material;
- pelo menos uma deve demonstrar contextualização financeira;
- pelo menos uma deve demonstrar reconstrução de decisão institucional pública.

Uma mesma questão pode satisfazer mais de um requisito.

## 9.3 Coerência do corpus

As três questões não devem ser escolhidas apenas para representar três “módulos” diferentes.

Sempre que possível, o corpus inicial deve favorecer **coerência temática, reaproveitamento de contexto e fontes e menor custo de manutenção**, desde que continue demonstrando os JTBD obrigatórios.

Um conjunto tematicamente relacionado pode ser preferível a três verticais independentes se conseguir provar a proposta de valor com menos dispersão operacional.

A escolha concreta será registrada antes do release, sem transformar essa preferência em obrigação de um único tema.

## 9.4 Critérios para selecionar as questões iniciais

As questões devem:

- estar claramente dentro do FF-0007;
- possuir relevância institucional demonstrável;
- possuir conjunto razoável de fontes públicas adequadas;
- permitir contexto temporal útil;
- ter custo de manutenção compatível com uma pessoa;
- não depender de acesso privilegiado;
- não exigir que o MVP resolva investigação de culpa ou acusação sensível para demonstrar seu valor;
- permitir testar proveniência e contexto sem exigir cobertura diária;
- evitar volatilidade tão alta que torne a primeira versão obsoleta imediatamente sem acompanhamento contínuo.

## 9.5 Composição recomendada, não obrigatória

O corpus deve cobrir, no conjunto:

- pelo menos uma questão com componente de **finanças ou Arena** suficientemente rico para contextualização de números;
- pelo menos uma questão com **governança, votação ou decisão institucional pública**;
- uma terceira questão que aprofunde o mesmo núcleo temático ou explore **regra, estrutura, estatuto, participação ou outra mudança institucional**, conforme a combinação mais coerente e sustentável.

A escolha dos acontecimentos concretos deve ser feita antes da publicação do MVP e documentada de forma rastreável, mas esta versão não canoniza casos históricos específicos como conteúdo obrigatório.

---

# 10. Jornada principal do usuário

A jornada principal do MVP é:

1. o usuário chega ao Fiel Fiscaliza por descoberta do corpus ou diretamente por uma Questão Institucional;
2. identifica claramente a pergunta tratada;
3. compreende rapidamente o contexto e o estado conhecido na última verificação;
4. percorre os acontecimentos materiais necessários para entender o que mudou, quando aplicável;
5. inspeciona as fontes associadas aos fatos ou acontecimentos que deseja verificar;
6. quando aplicável, consulta o contexto de números financeiros ou decisões institucionais;
7. identifica claramente o que permanece desconhecido, contestado, desatualizado ou não disponível;
8. consegue navegar para outras Questões Institucionais publicadas sem conhecer URLs internas;
9. sai com base suficiente para explicar ou continuar investigando a questão sem depender apenas da autoridade do Fiel Fiscaliza.

O objetivo central não é maximizar tempo de permanência.

É **reduzir custo de compreensão e verificação**.

---

# 11. Funcionalidades conscientemente adiadas, mas compatíveis com a visão

As capacidades abaixo podem ser valiosas no futuro, mas **não são requisitos do MVP** e sua eventual inclusão dependerá dos documentos responsáveis:

- busca global textual ou semântica;
- alertas e notificações;
- contas de usuário;
- favoritos;
- personalização;
- comentários limitados ou mecanismos de participação compatíveis com as políticas futuras;
- perfis institucionais mais completos de dirigentes ou conselheiros;
- visualizações de relações institucionais verificáveis;
- painel mais amplo de conselheiros;
- cobertura mais ampla de votações;
- painel financeiro mais abrangente;
- catálogo maior de contratos institucionalmente relevantes;
- arquivo mais amplo de documentos institucionais;
- cobertura mais ampla de processos e investigações;
- backfill histórico extenso;
- exportações acadêmicas avançadas;
- API pública;
- aplicativo móvel nativo;
- assistente público de IA compatível com os requisitos canônicos;
- tradução para outros idiomas.

Adiar significa apenas que essas capacidades não são necessárias para demonstrar a tese do MVP.

Não significa que sua implementação futura esteja automaticamente aprovada.

---

# 12. Elementos que não são “apenas adiados” sob o escopo canônico atual

Algumas ideias não devem ser descritas como simples backlog futuro porque conflitam com as fronteiras vigentes do produto ou exigiriam revisão canônica material antes de serem consideradas.

Sob FF-0001, FF-0005 e FF-0007 atuais, o MVP não inclui e o projeto não deve introduzir silenciosamente:

- portal ou feed geral de notícias esportivas;
- cobertura esportiva cotidiana sem consequência institucional;
- ranking automático de “bons” e “maus” atores políticos;
- sistema aberto de acusações ou denúncias irrestritas por usuários;
- campanha por chapa, candidato, situação, oposição, SAF ou outro resultado político substantivo;
- mecanismo de recomendação de voto interno;
- mobilização política eleitoral como função do produto;
- dossiê de vida privada;
- geração automática de culpa, intenção, aliança ou reputação;
- delegação de julgamento editorial substantivo à IA.

Uma futura decisão de introduzir algo materialmente equivalente exigiria primeiro revisar os documentos CANONICAL afetados, e não apenas mover um item de backlog para “feito”.

---

# 13. Cobertura jurídica, investigativa e de claims conflitantes no MVP

Processos, investigações e claims conflitantes pertencem ao escopo permanente, mas possuem risco editorial elevado no FF-0006.

Por isso, o MVP **não precisa ter cobertura ampla dessas áreas como proposta de valor principal**.

Uma Questão Institucional do corpus inicial pode conter elemento jurídico ou contestação quando necessário para compreender o assunto, desde que:

- seja indispensável ao contexto;
- exista base pública adequada;
- a representação não dependa de inferir culpa, intenção ou verdade material de acusação;
- as políticas editoriais da Fase 2 já sejam suficientes para publicação responsável.

O MVP não deve escolher como vitrine inicial um caso cujo valor dependa principalmente de transformar acusação sensível ou investigação em narrativa conclusiva.

---

# 14. Requisitos editoriais e de proveniência antes da publicação

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
- correções futuras podem ser feitas sem apagar silenciosamente histórico material;
- a representação não implica cobertura exaustiva ou atualização em tempo real que o projeto não oferece.

Os estados, regras e metadados formais serão definidos por FF-0009 a FF-0012.

---

# 15. Sustentabilidade operacional do MVP

O MVP deve ser compatível com manutenção pessoal por André.

Isso significa que o produto **não pode exigir como condição de qualidade**:

- publicação diária;
- cobertura de toda novidade institucional;
- acompanhamento manual contínuo de dezenas de fontes;
- resposta em tempo real;
- moderação de comunidade ativa;
- alimentação manual diária de grande volume;
- contratação de serviço pago indispensável.

## 15.1 Estratégia de manutenção compatível com o MVP

A primeira versão pode operar com corpus pequeno e atualização por mudança material.

O produto deve informar quando cada questão foi verificada pela última vez, sem transformar esse campo em promessa de atualidade posterior.

Automação de coleta e manutenção por exceção permanece direção constitucional, mas o nível de automação concreto será definido nas fases de arquitetura e operações.

O MVP pode começar com processos parcialmente manuais ou semiautomáticos desde que:

- não exista tarefa manual diária obrigatória para manter o produto minimamente correto;
- o corpus inicial possa permanecer publicável durante períodos sem novidade material;
- processos manuais não sejam usados para justificar expansão de cobertura incompatível com uma pessoa;
- o caminho para manutenção sustentável não dependa de serviço pago essencial.

---

# 16. Independência de acesso privilegiado

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

# 17. Critérios objetivos de aceite do MVP

Os critérios abaixo devem ser verificáveis antes de declarar a especificação implementada em nível de Produto.

## MVP-AC-01 — Corpus mínimo

Existem pelo menos 3 Questões Institucionais publicáveis e completas.

## MVP-AC-02 — Descoberta

Um usuário consegue encontrar e abrir todas as Questões Institucionais publicadas sem conhecer previamente URLs internas.

## MVP-AC-03 — Estado conhecido

Cada questão apresenta o estado conhecido na última verificação ou explicita que esse estado não pôde ser determinado com segurança.

Questões encerradas ou históricas podem apresentar desfecho ou estado histórico relevante em vez de falsa noção de atualidade.

## MVP-AC-04 — Referência temporal

Cada questão permite identificar a data ou período relevante das informações apresentadas e a última verificação feita pelo projeto.

A interface ou conteúdo não transforma a última verificação em garantia de tempo real.

## MVP-AC-05 — Histórico preservado sem cronologia artificial

Cada questão apresenta o contexto temporal necessário para compreensão.

Quando houver mais de um acontecimento material, a evolução pode ser reconstruída sem sobrescrever estados anteriores relevantes.

Quando não houver múltiplos eventos materiais, o produto não fabrica uma timeline apenas para satisfazer formato.

## MVP-AC-06 — Proveniência

Toda informação factual materialmente relevante publicada possui fonte ou proveniência suficiente segundo as políticas canônicas vigentes no momento do release.

## MVP-AC-07 — Fonte acessível ou adequadamente tratada

Quando uma fonte original estiver publicamente acessível e sua exposição for apropriada, o usuário consegue chegar a ela a partir da representação do produto.

Quando não estiver acessível ou sua republicação direta não for adequada, o produto aplica a política de proveniência vigente sem inventar disponibilidade.

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

Existe mecanismo acessível para que uma pessoa indique possível erro, fonte adicional ou pedido de correção, sem exigir comentários públicos, resposta em tempo real ou aceitação automática da alegação enviada.

## MVP-AC-14 — Sem acesso privilegiado

Nenhuma das três Questões Institucionais mínimas depende de fonte privada, credencial interna ou acesso não público para entregar sua proposta de valor.

## MVP-AC-15 — Sustentabilidade mínima verificável

Nenhuma capacidade obrigatória do MVP exige:

- publicação diária;
- moderação contínua de comunidade;
- resposta em tempo real;
- tarefa manual diária inevitável;
- serviço pago indispensável à consulta pública essencial.

O corpus inicial pode permanecer correto em seus próprios termos por meio de data de verificação e atualização baseada em mudança material, sem fingir cobertura contínua.

## MVP-AC-16 — Escopo preservado

Nenhuma capacidade implementada transforma o produto em portal esportivo geral, campanha política, sistema de denúncias irrestrito ou dossiê de vida privada.

## MVP-AC-17 — Compreensão básica independente de especialização

A representação inicial de cada questão explica contexto suficiente para que um torcedor sem conhecimento técnico especializado consiga compreender a pergunta central e o estado conhecido antes de abrir documentos de origem.

## MVP-AC-18 — Limites de cobertura explícitos

O produto não induz o usuário a concluir que o corpus representa cobertura completa da vida institucional do Corinthians nem que todas as questões estão atualizadas em tempo real.

---

# 18. O que significa “MVP publicável”

O FF-0002 exige que a Fase 1 defina o significado de “MVP publicável”.

Neste documento, **MVP publicável em sentido de Produto** significa que a futura implementação:

- contém o corpus mínimo definido;
- satisfaz as capacidades obrigatórias;
- satisfaz os critérios de aceite de Produto;
- consegue ser descrita sem depender de funcionalidade essencial ainda indefinida nesta fase.

Essa expressão **não equivale a autorização de release público**.

O release real continua dependente dos gates posteriores do FF-0002, incluindo, quando aplicáveis:

- política editorial;
- política de fontes e evidências;
- modelo de domínio e temporalidade;
- arquitetura;
- experiência;
- segurança, privacidade e risco legal;
- operações;
- critérios de Definition of Done e release.

Portanto:

> **FF-0008 define quando o produto mínimo está funcionalmente especificado; os gates posteriores determinam quando sua implementação está segura e pronta para publicação real.**

---

# 19. Critério de sucesso inicial após o lançamento

O MVP não terá meta artificial de tráfego ou crescimento como condição de sucesso.

Os primeiros sinais de valor devem procurar responder:

- usuários conseguem compreender uma questão sem recorrer imediatamente a múltiplas buscas externas?;
- conseguem identificar a fonte e auditar a representação?;
- o contexto temporal reduz confusão sobre o que aconteceu e o que mudou?;
- valores financeiros contextualizados evitam comparação enganosa?;
- decisões institucionais ficam mais claras sem inferir informação ausente?;
- a manutenção real permanece sustentável para André?;
- algum caso de uso ou segmento se mostra materialmente diferente das hipóteses atuais?

Esses sinais podem ser avaliados posteriormente por uso real, feedback, observação e pesquisa proporcional ao risco.

Eles **não constituem requisito adicional para fechar o Gate F1**, porque dependem de comportamento observável posterior ao lançamento.

A dívida de validação do FF-0006 permanece ativa.

---

# 20. Gatilhos para rever o MVP após evidência real

A especificação deve ser reavaliada se ocorrer, entre outros:

1. o formato de Questão Institucional não ajudar usuários a compreender ou verificar o problema;
2. o corpus exigir manutenção recorrente incompatível com uma pessoa;
3. usuários utilizarem principalmente um segmento ou JTBD diferente do esperado;
4. as fontes disponíveis não sustentarem reconstruções confiáveis;
5. a contextualização necessária tornar a experiência excessivamente complexa para usuários não especializados;
6. soluções existentes demonstrarem atender melhor os mesmos casos de uso;
7. um recurso adiado se mostrar claramente necessário para completar a jornada principal;
8. risco editorial, jurídico ou de privacidade tornar alguma capacidade inadequada;
9. a exigência de três questões mostrar custo desproporcional sem acrescentar demonstração real de repetibilidade.

Esses gatilhos não implicam pivot automático.

Eles exigem revisão da evidência e decisão explícita.

---

# 21. Decisões deliberadamente não tomadas pelo FF-0008

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

# 22. Revisão crítica de 2026-09-04

A revisão da v0.1 identificou riscos relevantes e os tratou nesta versão.

## 22.1 “Estado atual” poderia criar falsa promessa de atualização

A redação foi alterada para **estado conhecido na última verificação**, com separação entre data do fato, período de referência e momento de verificação.

O MVP não promete tempo real.

## 22.2 Timeline obrigatória em todo caso poderia produzir estrutura artificial

A temporalidade continua obrigatória quando necessária, mas o produto não deve fabricar múltiplos eventos para questões que não possuam evolução material.

## 22.3 Três verticais independentes poderiam aumentar escopo e manutenção

O mínimo de três questões foi preservado, mas a seleção agora privilegia coerência temática, reaproveitamento de fontes/contexto e menor dispersão operacional.

## 22.4 “Questão Institucional” poderia ser interpretada prematuramente como entidade técnica

A v0.2 deixa explícito que se trata de unidade de experiência de Produto, sem impor entidade de domínio, schema, página ou rota específica.

## 22.5 Itens incompatíveis com o escopo estavam misturados com backlog adiado

Portal esportivo geral, ranking político, denúncia irrestrita, mobilização eleitoral, dossiê privado e julgamento editorial automatizado não são descritos como simples funcionalidades futuras.

Sua introdução exigiria revisão dos documentos CANONICAL afetados.

## 22.6 Sustentabilidade estava correta, mas pouco verificável

O aceite agora proíbe explicitamente dependência de publicação diária, moderação contínua, resposta em tempo real, tarefa manual diária inevitável ou serviço pago indispensável.

## 22.7 “MVP publicável” poderia ser confundido com autorização de release

A v0.2 separa explicitamente suficiência de Produto de readiness real de publicação, que permanece dependente das fases posteriores.

## 22.8 Sucesso pós-lançamento não deve reabrir o Gate F1

Sinais de comportamento real continuam importantes para a dívida de validação, mas não são condição retroativa para fechar a especificação de Produto.

A revisão não identificou conflito canônico bloqueante com FF-0001, FF-0002, FF-0005, FF-0006 ou FF-0007 após esses ajustes.

---

# 23. Impacto e dependências documentais

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

# 24. Critérios para canonização

Antes de promover o FF-0008 para CANONICAL, deve-se confirmar que:

- a proposta de valor mínima é coerente com FF-0005;
- usuários e JTBD derivam de FF-0006;
- nenhuma capacidade viola FF-0007;
- o MVP é menor que o escopo permanente do produto;
- o corpus mínimo demonstra utilidade sem exigir cobertura ampla;
- a quantidade mínima de questões não cria obrigação desproporcional para o primeiro release;
- as capacidades obrigatórias podem ser descritas sem stack ou arquitetura;
- “Questão Institucional” não antecipa modelo de domínio ou estrutura técnica;
- a jornada principal está explícita;
- funcionalidades adiadas estão separadas de ideias incompatíveis com o escopo canônico atual;
- critérios de aceite são verificáveis;
- “MVP publicável” está separado de “pronto para release público”;
- a manutenção não exige operação diária;
- o MVP pode operar com custo mensal obrigatório de R$ 0;
- o MVP não depende de acesso institucional privilegiado;
- risco jurídico/editorial elevado não foi transformado em requisito de vitrine inicial;
- a dívida de validação permanece explícita;
- nenhuma decisão técnica futura foi canonizada prematuramente.

A revisão crítica de 2026-09-04 considera esses critérios satisfeitos no conteúdo da v0.2, sujeito à aprovação explícita de André para promoção a CANONICAL.

---

# 25. Vigência

Esta versão permanece **DRAFT** até aprovação explícita.

**FF-0008 — MVP_SPEC v0.2 // DRAFT**
