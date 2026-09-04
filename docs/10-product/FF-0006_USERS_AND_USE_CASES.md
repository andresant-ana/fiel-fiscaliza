# FF-0006 — USERS_AND_USE_CASES

**Nome do documento:** Users and Use Cases  
**ID:** FF-0006  
**Versão:** 0.3  
**Status:** DRAFT  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento identifica os usuários que podem obter maior valor do Fiel Fiscaliza, descreve os principais Jobs to Be Done (JTBD) e registra a evidência utilizada para orientar FF-0007 — SCOPE e FF-0008 — MVP_SPEC.

Seu objetivo não é provar demanda de mercado nem produzir personas artificiais.

O documento deve permitir responder:

- para quem o produto será inicialmente desenhado;
- quais tarefas institucionais pretende tornar menos custosas;
- quais usuários são primários e secundários;
- quais casos de uso possuem prioridade de produto;
- quais incertezas permanecem abertas;
- quais usos não devem orientar o produto.

O FF-0006 é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

A Product Vision estabelece que a unidade básica de valor do Fiel Fiscaliza é **uma questão institucional que se torna mais fácil de compreender, verificar e reconstruir**, e não uma notícia publicada.

---

# 2. Mudança metodológica da versão 0.3

A versão 0.2 previa entrevistas semiestruturadas e testes de tarefa como condição para promover segmentos e casos de uso a `VALIDADO PARA F1`.

Essa exigência foi reavaliada em 2026-09-04.

Para evitar que discovery síncrono se transforme em gargalo desproporcional para um projeto individual, a pesquisa comportamental pré-MVP deixa de ser requisito obrigatório para o Gate F1.

A decisão **não** significa que entrevistas ou testes de usuários sejam inúteis.

Significa que, neste estágio, o projeto aceita avançar com:

1. pesquisa documental pública já realizada;
2. análise explícita de alternativas e contraprovas;
3. decisões de produto com nível de confiança declarado;
4. MVP deliberadamente pequeno e reversível;
5. validação posterior por uso real, feedback público ou pesquisa direcionada quando uma incerteza material justificar o custo.

A consequência é uma **dívida de validação de produto conscientemente aceita**, registrada neste documento.

---

# 3. Regra epistemológica

As seguintes classificações são utilizadas no FF-0006.

## HIPÓTESE

Proposição plausível ainda sem evidência significativa suficiente.

## EVIDÊNCIA DOCUMENTAL

Proposição observada de modo consistente em fontes públicas, documentos, cobertura jornalística, discussões ou iniciativas do ecossistema.

Demonstra que a tarefa ou necessidade existe publicamente, mas não prova frequência individual, intensidade da dor ou recorrência de uso de um produto dedicado.

## DECIDIDO PARA F1

Decisão de produto adotada com base na melhor evidência disponível para permitir avanço de escopo e MVP.

`DECIDIDO PARA F1` **não significa validação empírica de demanda**.

A decisão pode ser revista se uso real, feedback ou nova pesquisa produzir contraprova relevante.

## REFUTADO / DEPRIORIZADO

Hipótese ou caso de uso conscientemente afastado por baixo valor, boa solução alternativa, baixa viabilidade, risco incompatível, escopo excessivo ou conflito com documentos CANONICAL.

O projeto não deve utilizar a palavra “validado” para descrever demanda ou comportamento de usuários sem evidência comportamental apropriada.

---

# 4. Base de evidência disponível

A versão 0.3 utiliza como principal evidência de discovery uma pesquisa documental pública aprofundada realizada em 2026-09-04 sobre o ecossistema de informação, transparência, governança, fiscalização e memória institucional do Corinthians.

A pesquisa examinou, entre outros:

- portal oficial de Transparência do SCCP;
- demonstrações financeiras, eleições, conselhos, atas e regimentos publicados pelo clube;
- Gaviões da Fiel;
- Meu Timão e Fórum Meu Timão;
- ge;
- UOL;
- Central do Timão;
- Alambrado Alvinegro;
- SAFiel;
- Coletivo Voz Corinthiana;
- Projeto Time do Povo;
- Reddit r/Corinthians;
- produção acadêmica;
- MPSP;
- TJSP;
- CVM / Fundos.NET;
- Receita Federal e dados públicos de CNPJ;
- Diários Oficiais e outras bases públicas auxiliares.

A pesquisa procurou evidências favoráveis e contraprovas para a tese do FF-0005.

---

# 5. Síntese do problema observado

A pesquisa não encontrou ausência absoluta de informação institucional sobre o Corinthians.

Existe um ecossistema relevante de documentos oficiais, imprensa, comunidades, torcidas, movimentos, registros judiciais, bases governamentais e pesquisas independentes.

A fricção observada está principalmente em:

- fragmentação entre fontes;
- informação consumida como fluxo e difícil de reencontrar;
- contexto temporal disperso;
- documentos e notícias que precisam ser correlacionados manualmente;
- números financeiros com datas-base ou conceitos diferentes;
- dificuldade de distinguir estágio atual de investigações e processos;
- decisões coletivas sem voto individual público;
- versões conflitantes e alegações que exigem rastreamento até a origem;
- conhecimento necessário para interpretar documentos jurídicos, financeiros e estatutários.

A oportunidade de produto permanece **plausível, não comprovada como demanda de mercado**.

---

# 6. Contraprovas e alternativas atuais

O Fiel Fiscaliza não parte da premissa de que usuários estejam sem solução.

Hoje muitas perguntas podem ser respondidas utilizando uma combinação de:

- Google e outros mecanismos de busca;
- portal oficial do SCCP;
- veículos de imprensa;
- portais especializados;
- fóruns e redes sociais;
- registros do Judiciário e Ministério Público;
- CVM e outras bases públicas;
- arquivos pessoais, contatos e conhecimento prévio de usuários especializados.

Portanto, o produto só se justifica se reduzir materialmente algum dos seguintes custos:

- tempo de reconstrução;
- quantidade de fontes que precisam ser correlacionadas;
- risco de usar informação desatualizada;
- dificuldade de chegar à fonte original;
- dificuldade de compreender status, vigência ou incerteza;
- perda de memória histórica.

A existência dessas alternativas é contraprova permanente contra qualquer tentativa de construir apenas “mais um lugar com as mesmas notícias”.

---

# 7. Usuário, stakeholder e objeto de fiscalização

## Usuário

Pessoa que utiliza o Fiel Fiscaliza para compreender, verificar, pesquisar, reconstruir ou acompanhar informação institucional.

## Stakeholder

Pessoa ou organização afetada pelo projeto, interessada em seus resultados ou capaz de fornecer contexto, crítica, dados públicos ou colaboração.

## Objeto de fiscalização

Pessoa, órgão, organização, decisão, documento, contrato, processo, votação ou outro elemento institucional documentado pelo Fiel Fiscaliza.

Ser objeto de fiscalização não torna alguém usuário do produto.

O produto deve ser desenhado prioritariamente para quem precisa compreender a instituição, não para agradar as pessoas fiscalizadas.

---

# 8. Usuário primário do MVP

## 8.1 Torcedor institucionalmente engajado

**Status:** DECIDIDO PARA F1  
**Nível de confiança:** moderado  
**Papel:** usuário primário do MVP

É o corinthiano que acompanha com alguma recorrência temas como:

- governança;
- finanças;
- eleições;
- conselhos;
- estatuto;
- Arena;
- investigações;
- processos;
- decisões institucionais.

Pode ou não participar de organizada, associação, movimento, fórum ou grupo político.

A escolha não presume qualquer alinhamento partidário interno.

### Por que foi escolhido

A pesquisa documental encontrou os sinais mais consistentes de necessidade recorrente nesse grupo:

- debates públicos frequentes;
- mobilização de torcidas e coletivos;
- necessidade de reconstruir fatos e documentos;
- interesse em votações, finanças, estatuto e responsabilização;
- uso repetido de fontes distintas para sustentar discussões.

### Necessidades principais

- verificar afirmações;
- reencontrar documentos e fontes;
- reconstruir cronologias;
- saber o estado atual de questões antigas;
- contextualizar números;
- compreender decisões sem inferir informação ausente;
- usar histórico em vez de memória informal.

### Limitação da decisão

Não foi demonstrado por entrevista ou analytics que esse usuário utilizará o produto com determinada frequência.

A decisão é suficiente para orientar um MVP pequeno, mas deverá ser reavaliada após evidência de uso real.

---

# 9. Usuários secundários

## 9.1 Torcedor com dúvida institucional pontual

**Status:** DECIDIDO PARA F1  
**Nível de confiança:** moderado  
**Papel:** usuário secundário relevante

Não acompanha política diariamente, mas procura contexto quando uma crise, eleição, investigação, dívida ou decisão ganha relevância.

Este usuário exige baixa barreira cognitiva e ajuda a impedir que o produto seja compreensível apenas por especialistas.

## 9.2 Jornalista, comunicador ou criador de conteúdo

**Status:** DECIDIDO PARA F1  
**Nível de confiança:** moderado  
**Papel:** usuário secundário / power user

Pode obter valor ao localizar fonte original, datas, cronologias e registros públicos.

O produto não deve se tornar serviço de pauta, clipping ou substituto de apuração jornalística.

## 9.3 Pesquisador histórico, acadêmico ou analista externo

**Status:** DECIDIDO PARA F1  
**Nível de confiança:** moderado/baixo para o MVP; alto para visão de longo prazo  
**Papel:** usuário secundário

Pode obter alto valor do patrimônio acumulado, mas não deve comandar o escopo inicial.

## 9.4 Associado, conselheiro ou participante institucional

**Status:** HIPÓTESE COM EVIDÊNCIA DOCUMENTAL PARCIAL  
**Papel:** usuário secundário possível

Pode se beneficiar de memória pública, mas o produto não dependerá de acesso interno, credenciais privilegiadas, documentos confidenciais ou relacionamento político.

---

# 10. Jobs to Be Done prioritários

## P0 — orientar escopo e MVP

### JTBD-01 — Verificar uma afirmação e chegar à fonte

**Quando** encontro uma afirmação institucional relevante,  
**quero** identificar quem afirmou, a origem, o status e a evidência disponível,  
**para** distinguir o documentado do alegado, inferido, contestado ou desconhecido.

**Status:** DECIDIDO PARA F1

Este JTBD incorpora a necessidade de chegar ao documento, decisão, declaração ou registro de origem quando disponível.

---

### JTBD-02 — Reconstruir a história e o estado atual de uma questão

**Quando** um assunto se desenvolve durante meses ou anos,  
**quero** reconstruir sua evolução e identificar seu estado conhecido atual,  
**para** entender o que mudou sem depender da última notícia que lembro ter visto.

**Status:** DECIDIDO PARA F1

---

### JTBD-03 — Entender um número financeiro no tempo

**Quando** encontro um valor sobre dívida, Arena, receita, despesa ou outro indicador financeiro,  
**quero** saber valor, data-base, conceito, método e fonte,  
**para** evitar comparar números diferentes como se fossem equivalentes.

**Status:** DECIDIDO PARA F1

---

### JTBD-04 — Reconstruir uma decisão institucional pública

**Quando** um órgão do clube toma uma decisão,  
**quero** saber qual órgão decidiu, quando, qual era a pauta, qual foi o resultado e quais informações individuais estão publicamente disponíveis,  
**para** compreender a decisão sem inferir votos, alianças ou posições não documentadas.

**Status:** DECIDIDO PARA F1

Voto individual não publicado deve permanecer **desconhecido / não disponível publicamente**.

---

# 11. Jobs to Be Done secundários

## P1

### JTBD-05 — Entender o estágio real de investigação ou processo

Identificar o que está em investigação, o que foi decidido, o que ainda pode mudar e qual é o estado processual conhecido.

**Status:** DECIDIDO PARA F1  
**Risco editorial:** alto

A presença no conjunto de casos de uso não significa cobertura ampla obrigatória no MVP.

### JTBD-06 — Comparar versões ou claims conflitantes

Identificar quem afirmou cada versão, quais evidências estão associadas e o que permanece contestado.

**Status:** DECIDIDO PARA F1  
**Risco editorial:** alto

### JTBD-07 — Recuperar atuação institucional publicamente documentada

Encontrar cargos, mandatos, decisões, posições e votações publicamente verificáveis relacionados a pessoa ou órgão.

**Status:** DECIDIDO PARA F1

Não autoriza inferir voto secreto, aliança, intenção ou culpa.

### JTBD-08 — Descobrir o que era conhecido em determinada data

Reconstruir o estado documental disponível em um momento passado para reduzir anacronismo.

**Status:** DECIDIDO PARA F1

---

## P2 / ADIADO

### JTBD-09 — Alertas de mudança

**Status:** DEPRIORIZADO PARA O MVP

A dispersão de fontes torna a ideia plausível, mas não existe evidência suficiente de que alertas devam orientar a primeira versão.

### JTBD-10 — Pesquisa acadêmica avançada / exportações especializadas

**Status:** DEPRIORIZADO PARA O MVP

Compatível com visão de longo prazo, mas não necessário para provar utilidade inicial.

---

# 12. Matriz de prioridade

| Caso de uso | Prioridade F1 | Evidência | Risco | Observação |
|---|---|---|---|---|
| Verificar afirmação + fonte original | P0 | documental forte | médio | capacidade transversal central |
| Cronologia + estado atual | P0 | documental forte | médio | núcleo da memória institucional |
| Contextualizar números financeiros | P0 | documental forte | médio/alto | exige precisão conceitual |
| Reconstruir decisão institucional pública | P0 | documental forte | alto | nunca inferir voto ausente |
| Processo/investigação | P1 | documental forte | alto | depende de política editorial robusta |
| Claims conflitantes | P1 | documental | alto | depende de FF-0011 |
| Histórico de cargos/mandatos | P1 | documental | médio | forte valor acumulativo |
| Estado conhecido em data passada | P1 | documental | médio | valor histórico alto |
| Alertas | P2 | parcial | médio | adiado |
| Pesquisa acadêmica avançada | P2 | documental | baixo | não orienta MVP |

As prioridades P0/P1/P2 orientam FF-0007 e FF-0008, mas o FF-0008 continua responsável por decidir quais capacidades efetivamente entram no MVP.

---

# 13. Não usuários prioritários e anti-use-cases

O Fiel Fiscaliza não deve otimizar sua experiência para:

- cobertura esportiva cotidiana sem consequência institucional;
- campanha eleitoral interna;
- listas para assédio, intimidação ou perseguição;
- pesquisa de dados pessoais privados;
- conclusões de culpa sem evidência;
- rumor rápido;
- manipulação editorial pró-situação ou pró-oposição;
- ranking simplista de “bons” e “maus” dirigentes ou conselheiros;
- gamificação de pessoas fiscalizadas.

O projeto fiscaliza atos, decisões, recursos e relações institucionais publicamente documentadas.

---

# 14. O que a pesquisa já permite decidir

Com confiança suficiente para avançar na Fase 1:

- o MVP deve ser desenhado prioritariamente para o torcedor institucionalmente engajado;
- precisa continuar compreensível para o torcedor que chega com uma dúvida pontual;
- jornalistas/comunicadores e pesquisadores são usuários secundários relevantes;
- fonte original/proveniência, temporalidade, contexto financeiro e decisões institucionais são casos de uso fortes;
- o produto não deve competir por velocidade de notícia;
- informação ausente deve poder permanecer desconhecida;
- soluções atuais já resolvem partes do problema e devem ser tratadas como concorrência funcional;
- um MVP pequeno pode ser utilizado como instrumento adicional de validação da própria tese de produto.

---

# 15. O que continua desconhecido

A decisão de avançar sem entrevistas preserva explicitamente as seguintes incertezas:

- frequência real de uso por pessoa;
- intensidade subjetiva da dor;
- taxa de retorno a uma ferramenta dedicada;
- preferência de interface;
- quantidade de contexto que usuários não especializados toleram;
- quanto tempo o Fiel Fiscaliza efetivamente economiza;
- quais segmentos gerarão maior uso real;
- se determinados recursos aparentemente valiosos serão pouco utilizados.

Nenhuma dessas incertezas deve ser convertida em alegação de demanda comprovada.

---

# 16. Dívida de validação aceita

A ausência de entrevistas pré-MVP gera uma dívida consciente de validação.

Ela deve ser paga de forma proporcional, sem se transformar em novo gate automático.

Formas aceitáveis incluem:

- feedback espontâneo após protótipo ou MVP;
- formulário curto no produto;
- issues/discussões públicas;
- análise agregada de uso quando compatível com privacidade;
- conversas assíncronas com usuários;
- entrevistas direcionadas somente quando uma decisão material continuar incerta;
- testes de tarefa quando uma interface concreta existir e houver algo real a observar.

Pesquisa adicional deve ser realizada **quando puder alterar uma decisão**, não apenas para cumprir ritual de discovery.

---

# 17. Gatilhos para reabrir pesquisa de usuários

Nova pesquisa passa a ser recomendada quando ocorrer pelo menos uma das condições:

1. dois caminhos de produto relevantes possuírem evidência documental semelhante e a escolha depender de comportamento de usuário;
2. o MVP não demonstrar uso suficiente para seus casos de uso centrais;
3. usuários apresentarem dificuldade recorrente de compreensão;
4. um recurso de alto custo operacional depender de demanda ainda desconhecida;
5. surgir contraprova relevante de que solução existente atende melhor o problema;
6. o produto começar a atrair principalmente um segmento diferente do usuário primário definido neste documento.

Esses gatilhos permitem pesquisa sob demanda em vez de pesquisa como etapa burocrática obrigatória.

---

# 18. Relação com o FF-0005

O FF-0005 exige que hipóteses de produto sejam testadas e que contraprovas sejam procuradas antes do Gate F1.

A pesquisa documental realizada em 2026-09-04 cumpriu parte material dessa obrigação e produziu evidências favoráveis e contrárias.

O FF-0005 **não exige entrevistas como método específico**.

Portanto, adiar pesquisa comportamental não cria conflito com a Product Vision, desde que:

- a incerteza permaneça explícita;
- decisões não sejam apresentadas como demanda empiricamente validada;
- o MVP permaneça pequeno e reversível;
- nova evidência possa provocar revisão posterior.

---

# 19. Critérios para promoção a CANONICAL

Antes de promover FF-0006 para CANONICAL, deve-se confirmar que:

- o usuário primário está explicitamente definido;
- usuários secundários estão diferenciados;
- os JTBD P0/P1 são compatíveis com FF-0001 e FF-0005;
- a escolha é apresentada como decisão de produto, não como prova científica de comportamento;
- alternativas existentes e contraprovas foram consideradas;
- anti-use-cases permanecem explícitos;
- nenhuma necessidade presume acesso privilegiado, voto secreto, aliança, culpa ou dado privado;
- a dívida de validação e seus gatilhos estão registrados;
- as decisões são suficientes para orientar FF-0007 e FF-0008 sem escolher tecnologia ou interface prematuramente.

Entrevistas ou testes de tarefa **não são requisito obrigatório de canonização desta versão**.

---

# 20. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

## Impacta

- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- futuros documentos de Experiência;
- priorização posterior de backlog e roadmap.

As prioridades deste documento não selecionam automaticamente funcionalidades do MVP.

---

# 21. Vigência

Esta versão permanece **DRAFT** até revisão crítica e aprovação explícita.

**FF-0006 — USERS_AND_USE_CASES v0.3 // DRAFT**

A versão 0.3 registra a decisão de **adiar pesquisa comportamental obrigatória pré-MVP**, define usuários e JTBD com base na melhor evidência documental disponível e preserva explicitamente a dívida de validação para revisão posterior orientada por necessidade.