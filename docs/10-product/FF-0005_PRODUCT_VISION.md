# FF-0005 — PRODUCT_VISION

**Nome do documento:** Product Vision  
**ID:** FF-0005  
**Versão:** 1.1  
**Status:** CANONICAL  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define a visão de produto do Fiel Fiscaliza.

Seu objetivo é responder, em nível de produto e sem antecipar arquitetura ou implementação:

- qual problema concreto justifica a existência do Fiel Fiscaliza;
- qual transformação o produto pretende produzir para seus usuários;
- qual é sua tese de valor;
- quais resultados caracterizam sucesso;
- quais princípios devem orientar futuras escolhas de escopo e experiência;
- quais hipóteses ainda precisam ser investigadas e validadas ao longo da evolução do produto.

Este documento não define ainda:

- usuários e personas em detalhe;
- casos de uso priorizados;
- escopo fechado do MVP;
- funcionalidades obrigatórias;
- arquitetura de informação;
- stack técnica;
- persistência;
- provedores;
- interface visual.

Essas decisões pertencem aos documentos posteriores da Fase 1 e às fases subsequentes do FF-0002.

O FF-0005 é subordinado ao **FF-0001 — PROJECT_CONSTITUTION** e deve utilizar o vocabulário do **FF-0004 — GLOSSARY**.

---

# 2. Base constitucional da visão

A visão de produto deriva diretamente de princípios já CANONICAL.

O Fiel Fiscaliza existe para ajudar corinthianos a:

- compreender;
- acompanhar;
- preservar;
- fiscalizar;

a vida institucional do Sport Club Corinthians Paulista por meio de informação pública, organizada, verificável, contextualizada e historicamente preservada.

A Constituição também estabelece que:

- informação institucional dispersa deve ser transformada em conhecimento acessível;
- o projeto deve preservar memória, não apenas retratar o presente;
- proveniência é parte estrutural do dado;
- o estado atual não pode apagar o histórico;
- credibilidade factual é mais importante que velocidade ou engajamento;
- utilidade é mais importante que abrangência;
- tecnologia é instrumento, não objetivo;
- o produto deve permanecer sustentável para manutenção individual;
- o projeto não deve se transformar em portal esportivo geral.

A Product Vision não pode contradizer esses limites.

---

# 3. Problema de produto

## 3.1 Problema central

A vida institucional do Corinthians produz continuamente informação relevante sobre:

- governança;
- eleições;
- conselhos;
- votações;
- dirigentes;
- finanças;
- documentos;
- contratos relevantes;
- investigações;
- processos;
- decisões;
- reformas estatutárias;
- mudanças administrativas;
- posicionamentos públicos;
- Arena;
- demais acontecimentos institucionais.

O problema não é simplesmente que essas informações não existam.

O problema que esta visão pretende atacar é que, em muitos casos, elas chegam ao torcedor de forma:

- fragmentada;
- efêmera;
- descontextualizada;
- difícil de verificar;
- difícil de reencontrar;
- dependente de memória individual;
- misturada a opinião ou disputa política;
- distribuída entre documentos extensos, notícias, comunicados, redes sociais e registros públicos;
- pouco conectada ao histórico que permite compreender sua importância.

A hipótese de produto é que, para parte relevante das questões institucionais, acompanhar um acontecimento no momento em que ocorre é menos custoso do que reconstruí-lo com precisão meses ou anos depois.

Essa hipótese deve receber evidência suficiente para orientar decisões de Fase 1 e permanecer explicitamente revisável enquanto não houver validação comportamental adequada. Ela não deve ser tratada como verdade universal sobre todo tipo de informação do clube.

---

## 3.2 Problema de continuidade

Informação institucional costuma ser consumida como fluxo do presente.

Entretanto, fiscalização institucional frequentemente exige continuidade.

Para avaliar uma gestão, uma decisão, uma promessa, uma votação, uma dívida, uma investigação ou uma mudança estatutária, não basta necessariamente conhecer apenas o último acontecimento isolado.

Pode ser necessário reconstruir:

- o que existia antes;
- o que mudou;
- quando mudou;
- quem participou;
- qual documento sustenta cada etapa;
- quais versões ou contestações existiam;
- qual era o estado conhecido em determinado momento;
- qual é o estado conhecido agora.

A visão parte da hipótese de que a ausência dessa continuidade aumenta o custo de fiscalização para torcedores interessados e favorece perda de memória institucional.

---

## 3.3 Problema de confiança e verificabilidade

Em ambiente político e institucional, a mesma questão pode ser apresentada de formas incompatíveis por diferentes grupos.

O torcedor pode precisar responder perguntas como:

- isso aconteceu ou alguém apenas afirmou que aconteceu?
- existe documento?
- a fonte está reproduzindo outra fonte?
- a decisão é definitiva?
- a investigação ainda está aberta?
- este valor financeiro corresponde a qual data e metodologia?
- esta informação foi posteriormente corrigida?
- essa pessoa realmente votou assim ou isso está sendo inferido?

O Fiel Fiscaliza pretende reduzir o custo de verificação dessas perguntas sem substituir incerteza por falsa certeza e sem exigir que o usuário confie no projeto apenas por autoridade declarada.

A confiança pretendida deve ser consequência de rastreabilidade, consistência editorial, correções e acesso às evidências — não de autoproclamação.

---

# 4. Oportunidade de produto

A oportunidade que esta visão propõe explorar é a criação de um produto cujo valor principal não seja produzir mais volume de informação, mas **aumentar a capacidade de compreender e reutilizar informação institucional ao longo do tempo**.

Essa oportunidade ainda é uma hipótese de produto. Antes do fechamento do Gate F1, sua plausibilidade e relevância devem ter sido investigadas por evidência suficiente e contraprova proporcional ao risco e à reversibilidade das decisões tomadas. Pesquisa comportamental pré-MVP pode ser adiada quando sua ausência não impedir uma decisão responsável, pequena e reversível, desde que a incerteza permaneça documentada.

Se sustentada pela evidência disponível, o Fiel Fiscaliza poderá transformar informação pública dispersa em um patrimônio informacional:

- consultável;
- contextualizado;
- temporal;
- rastreável;
- verificável;
- conectado;
- compreensível para quem não acompanha diariamente a política do clube.

O Fiel Fiscaliza não precisa substituir imprensa, portais, instituições ou movimentos de fiscalização existentes.

Seu valor proposto está em ocupar uma função diferente:

> **preservar e organizar aquilo que normalmente pode se perder no fluxo cotidiano de notícias, documentos, declarações e disputas institucionais.**

A pesquisa da Fase 1 deve procurar tanto evidências favoráveis quanto contraprovas para essa hipótese.

---

# 5. Visão de produto

## 5.1 Declaração de visão

> **O Fiel Fiscaliza deve se tornar uma referência pública e independente para compreender a vida institucional do Corinthians — um lugar em que atos, decisões, documentos, posições e mudanças possam ser reconstruídos no tempo com contexto, proveniência e evidência verificável.**

A confiabilidade do produto deve ser demonstrável por sua rastreabilidade e comportamento editorial, não presumida pelo próprio projeto.

A visão não depende de o usuário acompanhar política do clube diariamente.

O produto deve permitir que alguém chegue depois de um acontecimento e ainda consiga reconstruir sua história com o nível de certeza que as evidências realmente permitem.

---

## 5.2 Transformação desejada

### Antes

Para compreender determinadas questões institucionais, o torcedor pode precisar:

- lembrar onde viu determinada informação;
- procurar notícias antigas;
- buscar posts ou comunicados;
- comparar datas manualmente;
- interpretar documentos extensos;
- distinguir fato de alegação sem apoio estrutural;
- reconstruir sozinho a sequência dos acontecimentos.

### Depois

O Fiel Fiscaliza deve reduzir esse trabalho, permitindo que o usuário encontre uma representação organizada da questão e consiga compreender rapidamente:

- o que é conhecido;
- o que não é conhecido;
- o que está sendo alegado;
- quais fontes sustentam cada afirmação;
- como a situação evoluiu;
- quais documentos são relevantes;
- o que mudou desde o estado anterior.

O produto não elimina a necessidade de análise crítica.

Ele pretende diminuir o custo de reunir a base factual e documental necessária para exercê-la.

---

# 6. Tese de produto

A tese central do Fiel Fiscaliza é:

> **A fiscalização institucional pode se tornar mais efetiva quando informação pública deixa de ser consumida apenas como fluxo e passa a existir como memória estruturada, temporal e verificável.**

Esta é uma **tese de produto a ser testada**, não uma conclusão empírica já demonstrada.

A tese possui cinco partes.

## 6.1 Estrutura reduz dispersão

Informações relacionadas devem poder ser encontradas e compreendidas como partes de uma mesma história institucional, e não apenas como páginas isoladas publicadas em lugares diferentes.

## 6.2 Temporalidade reduz risco de distorção histórica

A plataforma deve preservar o que era conhecido em cada momento e permitir acompanhar evolução sem reescrever o passado a partir do estado atual.

## 6.3 Proveniência aumenta auditabilidade

O usuário deve poder chegar à origem da informação e compreender quem publicou, quando publicou e qual evidência sustenta determinada afirmação.

## 6.4 Linguagem de incerteza protege a integridade da consulta

Dizer “desconhecido”, “não confirmado”, “alegado” ou “em investigação” quando apropriado é parte da utilidade do produto, não uma fraqueza.

## 6.5 Memória sustenta fiscalização retrospectiva

Atos institucionais se tornam mais recuperáveis e comparáveis quando permanecem associados a documentos, contexto, posições e estados anteriores de forma documentalmente sustentada.

Isso pode ampliar a capacidade de fiscalização posterior sem implicar que memória, por si só, produza responsabilização institucional.

---

# 7. Valor fundamental entregue ao usuário

A unidade básica de valor do Fiel Fiscaliza não deve ser “uma notícia publicada”.

A unidade de valor é **uma questão institucional que se torna mais fácil de compreender, verificar e reconstruir**.

Exemplos abstratos de perguntas que o produto deve ajudar a responder ao longo de sua evolução:

- O que aconteceu?
- Quando aconteceu?
- Quem tomou ou participou da decisão?
- Qual documento registra isso?
- Quem afirmou determinada informação?
- Essa afirmação foi contestada?
- Qual era o estado da questão naquela data?
- O que mudou posteriormente?
- Essa decisão ainda está vigente?
- O processo terminou ou continua em andamento?
- O voto individual é conhecido ou desconhecido?
- De onde vem determinado valor financeiro?

Esses exemplos descrevem resultados desejados, não funcionalidades já aprovadas para o MVP.

---

# 8. Pilares de valor

## 8.1 Compreensão

Reduzir a quantidade de contexto prévio necessária para que um corinthiano consiga entender um assunto institucional.

## 8.2 Verificabilidade

Tornar simples identificar a origem e a adequação da evidência que sustenta uma informação.

## 8.3 Memória

Evitar que decisões e acontecimentos relevantes desapareçam apenas porque deixaram de ser notícia.

## 8.4 Contexto temporal

Mostrar evolução e vigência em vez de apresentar apenas o último estado conhecido.

## 8.5 Independência

Permitir uso e avaliação da estrutura factual do produto sem exigir alinhamento com situação, oposição, torcida organizada, dirigente ou grupo político.

## 8.6 Acessibilidade informacional

Reduzir a barreira de entrada para quem não domina linguagem jurídica, contábil, política ou estatutária, sem sacrificar precisão.

## 8.7 Sustentabilidade

Entregar valor de uma forma que possa continuar sendo mantida por uma pessoa com baixo esforço operacional recorrente.

---

# 9. Princípios de produto

Decisões futuras de produto devem respeitar os seguintes princípios.

## 9.1 Pergunta antes da feature

Nenhuma funcionalidade deve existir apenas porque parece interessante tecnicamente.

Ela deve responder a uma dificuldade concreta de compreensão, preservação ou fiscalização.

## 9.2 Fonte próxima do conteúdo

A evidência não deve ser tratada como detalhe periférico ou rodapé ornamental.

A experiência deve facilitar a passagem entre informação apresentada e sua proveniência.

## 9.3 Histórico antes de novidade

O produto não deve privilegiar exclusivamente conteúdo recente a ponto de destruir seu valor de memória.

## 9.4 Incerteza visível

Informações contestadas, incompletas ou não confirmadas devem permanecer reconhecíveis como tais.

## 9.5 Profundidade antes de cobertura total

É preferível representar bem um conjunto menor de problemas institucionais do que possuir cobertura superficial de tudo.

## 9.6 Utilidade independente de audiência

O produto deve possuir valor mesmo que não tenha grande número de acessos.

Uma consulta histórica precisa, uma fonte reencontrada ou uma decisão reconstruída corretamente já podem constituir valor real.

## 9.7 Baixo custo cognitivo

O usuário não deve precisar compreender a arquitetura interna, o modelo de dados ou a terminologia técnica do projeto para utilizar o produto.

## 9.8 Sem falsa neutralização dos fatos

Independência editorial não exige tratar evidências desiguais como equivalentes.

O produto deve representar fatos, contestações e incertezas de forma proporcional ao suporte disponível, sem propaganda e sem fabricar falsa simetria.

## 9.9 Confiabilidade deve ser auditável

O produto não deve pedir confiança cega do usuário.

Sempre que materialmente possível, afirmações relevantes devem permitir inspeção de origem, contexto, status e histórico suficiente para que o usuário avalie a base da informação apresentada.

---

# 10. O que o Fiel Fiscaliza não pretende ser

A visão de produto exclui deliberadamente a transformação do Fiel Fiscaliza em:

- portal geral de notícias do Corinthians;
- agregador de manchetes;
- fórum de torcida;
- rede social;
- veículo de campanha eleitoral interna;
- instrumento de ataque pessoal a dirigentes ou conselheiros;
- ranking automático de “bons” e “maus” atores políticos;
- substituto de órgãos oficiais ou da imprensa;
- sistema de denúncia anônima irrestrita;
- arquivo de dados privados;
- produto cuja principal função seja gerar conteúdo por IA;
- demonstração tecnológica ou projeto de portfólio disfarçado de fiscalização.

Isso não impede funcionalidades futuras relacionadas a participação, pesquisa ou análise, desde que sejam compatíveis com a Constituição e justificadas por problema real.

---

# 11. Resultados desejados para o usuário

Sem ainda definir usuários específicos, a visão considera desejável que uma pessoa consiga:

1. encontrar informação institucional relevante sem conhecer previamente a fonte exata;
2. compreender o contexto mínimo necessário de um acontecimento;
3. identificar claramente o que é fato, alegação, investigação, decisão, opinião ou estado desconhecido;
4. acessar ou identificar a evidência de origem;
5. reconstruir a evolução temporal de uma questão;
6. diferenciar estado histórico de estado atual;
7. retornar meses ou anos depois e reencontrar a informação sem depender de memória pessoal ou redes sociais;
8. compreender melhor o funcionamento e as decisões institucionais do Corinthians.

A priorização e tradução desses resultados em casos de uso concretos pertencem ao **FF-0006 — USERS_AND_USE_CASES**.

---

# 12. Critério de sucesso do produto

O sucesso do Fiel Fiscaliza deve ser avaliado prioritariamente pela utilidade institucional entregue, e não por métricas de atenção isoladas.

Indicadores de audiência podem ser úteis, mas não devem ser confundidos com missão cumprida.

Um produto bem-sucedido deve demonstrar, ao longo do tempo, capacidade de:

- responder melhor a perguntas institucionais relevantes;
- reduzir esforço de pesquisa para reconstruir acontecimentos;
- manter fontes e contexto associados às informações;
- preservar histórico sem sobrescrita destrutiva;
- tornar incerteza e contestação compreensíveis;
- continuar operacionalmente sustentável;
- permanecer útil mesmo quando a conjuntura política do clube mudar.

Não constitui sucesso, por si só:

- obter tráfego elevado com baixa rastreabilidade;
- publicar grande volume com baixa utilidade;
- cobrir muitas áreas superficialmente;
- depender de esforço manual incompatível com manutenção individual;
- gerar percepção de autoridade sem permitir auditoria das evidências.

Métricas quantitativas específicas serão definidas somente quando houver MVP e comportamento observável suficientes para justificar metas concretas.

Não devem ser inventadas metas numéricas nesta fase apenas para dar aparência de precisão.

---

# 13. Visão de longo prazo

No longo prazo, o Fiel Fiscaliza deve funcionar como um patrimônio informacional público sobre a vida institucional do Corinthians.

Seu valor acumulado deve crescer com o tempo porque cada novo registro poderá se beneficiar do contexto histórico anterior.

A plataforma deve permanecer conceitualmente útil através de:

- diferentes gestões;
- diferentes composições de conselhos;
- eleições;
- reformas estatutárias;
- investigações e encerramentos de investigações;
- crises;
- períodos de estabilidade;
- mudanças jurídicas;
- reorganizações administrativas;
- eventual mudança profunda de estrutura institucional.

A visão de longo prazo não exige que todas essas dimensões estejam presentes no MVP.

Ela exige apenas que o MVP não seja concebido de maneira incompatível com esse futuro.

---

# 14. Direção do MVP sem antecipar seu escopo

A Product Vision impõe algumas condições ao futuro MVP, mas não escolhe ainda suas funcionalidades.

O MVP deverá:

- entregar utilidade institucional perceptível desde sua primeira versão pública;
- resolver profundamente pelo menos um conjunto coerente de problemas, em vez de simular cobertura total;
- demonstrar proveniência e contexto como elementos centrais da experiência;
- preservar temporalidade quando o tipo de informação exigir;
- ser compreensível para usuários sem conhecimento especializado;
- ser sustentável por uma pessoa;
- não depender de acesso privilegiado a SCCP, Gaviões ou qualquer grupo político;
- não depender de serviço pago como requisito operacional essencial;
- não depender de IA paga no caminho crítico público;
- evitar decisões técnicas que tornem a visão de longo prazo inviável.

Quais problemas específicos serão escolhidos para o MVP será definido no FF-0008 após análise de usuários, casos de uso e escopo.

---

# 15. Hipóteses de produto e dívida de validação

A visão atual contém hipóteses que não devem ser tratadas como fatos enquanto não houver evidência apropriada.

Nem toda hipótese precisa ser empiricamente encerrada antes do Gate F1. Para decisões pequenas, reversíveis e de baixo custo, a Fase 1 pode adotar uma direção provisória com base em evidência documental robusta, contraprovas e incerteza explicitamente registrada.

Hipóteses cuja incerteza possa alterar materialmente escopo, custo operacional, risco editorial, segurança, compreensão ou viabilidade devem receber investigação adicional antes de cristalizar decisões difíceis de reverter.

## 15.1 Hipótese de dor

Torcedores interessados em vida institucional enfrentam esforço materialmente relevante para reencontrar, verificar e contextualizar determinadas informações históricas.

## 15.2 Hipótese de valor

Organização temporal e proveniência explícita reduzem materialmente esse esforço e tornam a base da consulta mais auditável.

## 15.3 Hipótese de usuário

Existe um grupo de usuários além do próprio mantenedor que obterá utilidade recorrente de uma ferramenta desse tipo.

## 15.4 Hipótese de lacuna

As iniciativas já existentes de transparência, imprensa, mobilização ou acompanhamento institucional deixam uma lacuna relevante e contínua no problema de memória institucional estruturada que o Fiel Fiscaliza pretende atacar.

Essa hipótese deve ser investigada por mapeamento do ecossistema, não presumida.

## 15.5 Hipótese de disponibilidade

Há volume suficiente de informação pública e legitimamente acessível para produzir valor sem depender de dados privados ou acesso institucional privilegiado.

## 15.6 Hipótese de manutenção

É possível entregar utilidade relevante sem criar uma operação editorial diária incompatível com manutenção individual.

## 15.7 Hipótese de compreensão

É possível apresentar contexto, proveniência, temporalidade e incerteza com rigor sem tornar a experiência excessivamente complexa para usuários não especializados.

---

# 16. Pesquisa necessária antes do Gate F1

Para transformar esta visão em especificação de produto, a Fase 1 deve reunir **evidência suficiente para a decisão**, proporcional ao risco, ao custo e à reversibilidade do que está sendo decidido.

A pesquisa deve examinar, conforme materialmente relevante:

- quem são os usuários primários e secundários;
- quais perguntas institucionais aparecem no ecossistema;
- quais dessas perguntas parecem exigir maior esforço, reconstrução ou verificação;
- como essas perguntas são resolvidas atualmente;
- quais iniciativas, sites, veículos ou ferramentas já atendem parte dessas necessidades;
- quais lacunas plausíveis permanecem;
- quais casos de uso possuem melhores sinais de utilidade recorrente;
- qual subconjunto de problemas possui melhor relação entre valor e custo de manutenção para um MVP;
- quais funções parecem interessantes, mas não essenciais;
- quais evidências contradizem ou enfraquecem as hipóteses desta visão.

A pesquisa não deve ser conduzida apenas para confirmar a ideia existente. Contraprovas são parte do processo de produto.

Pesquisa comportamental, entrevistas ou testes de tarefa são meios válidos, mas **não constituem requisito universal obrigatório antes do MVP**. Podem ser adiados quando:

- a decisão é pequena e reversível;
- a desk research e outras evidências já permitem uma escolha responsável;
- a incerteza é declarada explicitamente;
- o custo de pesquisa adicional é desproporcional ao risco da decisão;
- existe mecanismo futuro razoável para reabrir a questão diante de uso real, feedback ou contraprova.

Quando pesquisa comportamental for adiada, o documento responsável deve registrar a **dívida de validação**, o que permanece desconhecido e os gatilhos que exigem reabertura da pesquisa.

Decisões tomadas sob essa regra não devem ser descritas como demanda empiricamente validada.

O **FF-0006 — USERS_AND_USE_CASES** deve aprofundar usuários, tarefas, força de evidência e eventual dívida de validação.

O **FF-0007 — SCOPE** deve transformar a visão em fronteiras claras.

O **FF-0008 — MVP_SPEC** deve escolher a menor combinação de capacidades capaz de testar a tese de produto com utilidade real e risco controlado.

## 16.1 Critérios de reavaliação da visão

A Product Vision deve ser reavaliada antes do Gate F1 se a pesquisa indicar materialmente que:

- o problema percebido não gera esforço relevante para usuários além do mantenedor;
- soluções já existentes resolvem de maneira suficiente os casos de uso prioritários;
- a informação pública disponível é insuficiente para entregar valor consistente;
- a estrutura necessária para produzir valor exige manutenção incompatível com o FF-0001;
- o rigor editorial necessário torna a experiência inviável para os usuários-alvo;
- o melhor problema a resolver está fora da tese central de memória institucional estruturada.

Nesses casos, o resultado correto pode ser reduzir escopo, reposicionar a tese, substituir parte da visão ou até concluir que determinada proposta de produto não se justifica.

Preservar uma ideia por apego não é objetivo do Fiel Fiscaliza.

## 16.2 Gatilhos para pesquisa adicional

Pesquisa adicional deve ser realizada ou fortemente considerada quando a incerteza puder alterar materialmente uma decisão, incluindo situações em que:

- duas alternativas de produto relevantes possuam evidência semelhante e a escolha dependa de comportamento de usuário;
- um recurso de custo operacional elevado dependa de demanda ainda desconhecida;
- haja sinais de incompreensão recorrente por usuários não especializados;
- uso real contradiga o usuário primário ou os casos de uso escolhidos;
- uma solução existente passe a atender melhor o problema;
- um risco editorial, jurídico, de privacidade ou segurança dependa de pressuposto ainda não testado.

A existência de dívida de validação não deve ser usada para impedir indefinidamente o avanço do projeto, mas também não autoriza converter incerteza em fato.

---

# 17. Perguntas deliberadamente não respondidas por este documento

Permanecem abertas neste nível de visão, entre outras:

- quem exatamente será o usuário primário do MVP;
- qual será a primeira área institucional coberta profundamente;
- quais páginas existirão;
- se haverá perfis de pessoas no MVP;
- se haverá acompanhamento de votações no MVP;
- se haverá linha do tempo geral ou apenas contextual;
- como será executada a busca;
- quais fontes serão monitoradas inicialmente;
- qual frequência de atualização será necessária;
- quais dados serão coletados automaticamente;
- qual será o modelo formal de Claim;
- qual será o schema de dados;
- qual será a stack;
- onde o produto será hospedado.

Essas perguntas podem ser respondidas por documentos posteriores e não devem ser respondidas silenciosamente por implementação.

---

# 18. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0003 — DECISION_LOG;
- FF-0004 — GLOSSARY.

## Impacta

Este documento condiciona principalmente:

- FF-0006 — USERS_AND_USE_CASES;
- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- futuros documentos de Experiência;
- critérios de priorização de backlog e roadmap.

Documentos posteriores podem especializar esta visão e tomar decisões provisórias sob incerteza quando seguirem as regras de proporcionalidade e dívida de validação desta versão.

---

# 19. Critérios para canonização

Antes de promover este documento para CANONICAL, deve-se confirmar que:

- a visão é compatível com FF-0001;
- o problema está formulado sem depender de uma solução técnica específica;
- a visão diferencia claramente valor institucional de cobertura jornalística;
- nenhuma funcionalidade de MVP foi canonizada prematuramente;
- hipóteses relevantes estão identificadas como hipóteses;
- a oportunidade proposta não é apresentada como lacuna de mercado já comprovada;
- decisões sobre usuários distinguem evidência disponível de validação comportamental;
- os critérios de sucesso não dependem apenas de audiência;
- a visão é compatível com manutenção individual e custo zero;
- existem critérios explícitos para reavaliar ou pivotar a tese diante de contraprovas;
- eventual dívida de validação possui incertezas e gatilhos de reabertura explícitos;
- as questões ainda abertas estão encaminhadas aos documentos adequados.

A revisão de 2026-09-04 confirmou esses critérios e aprovou a alteração metodológica estreita que permite evidência proporcional ao risco e à reversibilidade, sem dispensar contraprova nem transformar hipótese em fato.

---

# 20. Vigência

Esta versão possui status **CANONICAL** e entra em vigor em **2026-09-04** por aprovação explícita de André.

**FF-0005 — PRODUCT_VISION v1.1 // CANONICAL**

A versão 1.1 preserva integralmente a visão, a tese e os princípios da versão 1.0 e altera apenas a estratégia de validação da Fase 1: pesquisa comportamental pré-MVP deixa de ser requisito universal, desde que decisões sob incerteza sejam proporcionais, reversíveis, explicitamente qualificadas e acompanhadas de dívida de validação quando aplicável.

A canonização deste documento não encerra a Fase 1. O Gate F1 exige também FF-0006, FF-0007 e FF-0008 em estado CANONICAL e consistentes entre si.
