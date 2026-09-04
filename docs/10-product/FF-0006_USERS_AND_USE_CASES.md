# FF-0006 — USERS_AND_USE_CASES

**Nome do documento:** Users and Use Cases  
**ID:** FF-0006  
**Versão:** 1.0  
**Status:** CANONICAL  
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
- quais usos não devem orientar o produto;
- qual nível de evidência sustenta cada decisão.

O FF-0006 é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

A Product Vision estabelece que a unidade básica de valor do Fiel Fiscaliza é **uma questão institucional que se torna mais fácil de compreender, verificar e reconstruir**, e não uma notícia publicada.

---

# 2. Estado desta versão

A versão 1.0 resulta da revisão crítica da v0.4 e da resolução formal da tensão metodológica identificada com o FF-0005.

O **FF-0005 — PRODUCT_VISION v1.1 // CANONICAL** passou a permitir que decisões pequenas, reversíveis e de baixo risco avancem com evidência documental robusta, contraprovas e incerteza declarada, sem tornar pesquisa comportamental pré-MVP um requisito universal.

Essa alteração não transforma desk research em validação empírica. Ela permite uma decisão de produto proporcional ao risco, acompanhada de dívida de validação explícita.

Com essa condição resolvida, esta versão:

- define usuário primário e usuários secundários para a Fase 1;
- prioriza Jobs to Be Done sem transformá-los automaticamente em funcionalidades de MVP;
- diferencia força de evidência de status formal do projeto;
- registra alternativas e contraprovas;
- preserva incertezas comportamentais;
- mantém FF-0008 responsável por selecionar o conteúdo efetivo do MVP;
- estabelece gatilhos para reabrir pesquisa quando ela puder alterar uma decisão material.

---

# 3. Classificações locais de evidência e decisão

As classificações abaixo existem apenas dentro do FF-0006 para expressar força de evidência e grau de decisão de produto.

Elas **não substituem**:

- os estados documentais `DRAFT`, `CANONICAL` e `DEPRECATED`;
- os status de entradas do FF-0003 — DECISION_LOG;
- qualquer taxonomia editorial futura de claims ou evidências.

## HIPÓTESE

Proposição plausível ainda sem evidência significativa suficiente.

## HIPÓTESE COM EVIDÊNCIA DOCUMENTAL PARCIAL

Proposição ainda insuficiente para decisão de F1, mas que possui sinais documentais reais a seu favor.

## EVIDÊNCIA DOCUMENTAL

Proposição observada de modo consistente em fontes públicas, documentos, cobertura jornalística, discussões ou iniciativas do ecossistema.

Demonstra que a tarefa ou necessidade existe publicamente, mas não prova frequência individual, intensidade da dor ou recorrência de uso de um produto dedicado.

## DECIDIDO PARA F1

Decisão de produto adotada com base na melhor evidência disponível para orientar escopo e MVP.

`DECIDIDO PARA F1` **não significa validação empírica de demanda ou comportamento**.

A decisão deve permanecer revisável diante de uso real, feedback, nova pesquisa ou contraprova relevante.

## REFUTADO / DEPRIORIZADO

Hipótese ou caso de uso conscientemente afastado por baixo valor, boa solução alternativa, baixa viabilidade, risco incompatível, escopo excessivo ou conflito com documentos CANONICAL.

O projeto não deve utilizar a palavra “validado” para descrever demanda ou comportamento de usuários sem evidência comportamental apropriada.

---

# 4. Escala local de confiança

A indicação de confiança deste documento é qualitativa e serve apenas para tornar a incerteza explícita.

## ALTA

Há evidência consistente em múltiplos tipos de fonte e pouca contraprova material conhecida para a decisão em questão.

## MODERADA

Há sinais documentais consistentes, mas permanecem incertezas relevantes sobre comportamento, frequência, intensidade ou adoção.

## BAIXA

A proposição é plausível, porém sustentada por evidência limitada, indireta ou excessivamente concentrada em um segmento.

A escala não deve ser convertida em porcentagens artificiais.

---

# 5. Base e proveniência da pesquisa documental

A principal evidência de discovery disponível é uma pesquisa documental pública aprofundada realizada em **2026-09-04** sobre informação, transparência, governança, fiscalização e memória institucional do Corinthians.

A pesquisa buscou evidências favoráveis e contraprovas para a tese do FF-0005.

## 5.1 Fontes e ecossistemas examinados

Entre as fontes e iniciativas examinadas estão:

- SCCP — Transparência: https://www.corinthians.com.br/clube/transparencia
- SCCP — demonstrações financeiras: https://www.corinthians.com.br/clube/transparencia/demonstracoes-financeiras-e-balancetes-patrimoniais
- SCCP — eleições: https://www.corinthians.com.br/clube/transparencia/eleicoes
- SCCP — atas do Conselho: https://www.corinthians.com.br/clube/transparencia/atas-do-conselho
- SCCP — Conselho Deliberativo: https://www.corinthians.com.br/clube/transparencia/conselho-deliberativo
- SCCP — presidência e diretoria: https://www.corinthians.com.br/clube/transparencia/presidencia-e-diretoria
- SCCP — regimentos: https://www.corinthians.com.br/clube/transparencia/regimentos
- Gaviões da Fiel: https://gavioes.com.br/
- Meu Timão: https://www.meutimao.com.br/
- Fórum Meu Timão: https://www.meutimao.com.br/forum-do-corinthians/
- ge Corinthians: https://ge.globo.com/futebol/times/corinthians/
- UOL Esporte: https://www.uol.com.br/esporte/
- Central do Timão: https://centraldotimao.com.br/
- Alambrado Alvinegro: https://alambradoalvinegro.com.br/
- SAFiel: https://safiel.com.br/
- Reddit r/Corinthians: https://www.reddit.com/r/Corinthians/
- MPSP: https://www.mpsp.mp.br/
- TJSP — Processos: https://www.tjsp.jus.br/Processos
- CVM: https://cvmweb.cvm.gov.br/
- Dados Abertos CVM: https://dados.cvm.gov.br/
- Receita Federal — dados abertos: https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/dados-abertos/cadastros
- JUCESP: https://vre.jucesp.sp.gov.br/
- Diário Oficial do Estado de São Paulo: https://www.doe.sp.gov.br/
- Diário Oficial da Cidade de São Paulo: https://diariooficial.prefeitura.sp.gov.br/
- Diário Oficial da União: https://www.gov.br/pt-br/servicos/acessar-o-diario-oficial-da-uniao
- Portal da Transparência: https://portaldatransparencia.gov.br/

Também foram examinados materiais públicos relacionados a coletivos, movimentos, debates institucionais e produção acadêmica.

## 5.2 Limite de proveniência desta versão

Esta lista preserva as principais origens consultadas, mas não substitui futuros FF-0010 — SOURCE_POLICY e FF-0031 — SOURCE_REGISTRY.

Quando uma afirmação factual específica do produto depender de uma fonte determinada, sua proveniência deverá ser preservada em granularidade maior que este inventário de discovery.

---

# 6. Síntese do problema observado

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

# 7. Contraprovas e alternativas atuais

O Fiel Fiscaliza não parte da premissa de que usuários estejam sem solução.

Hoje muitas perguntas podem ser respondidas utilizando uma combinação de:

- mecanismos de busca;
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

A existência dessas alternativas é contraprova permanente contra construir apenas “mais um lugar com as mesmas notícias”.

A desk research também possui viés de observação: fóruns, Reddit, torcidas e coletivos tendem a super-representar pessoas já engajadas em política e governança.

---

# 8. Usuário, stakeholder e objeto de fiscalização

## Usuário

Pessoa que utiliza o Fiel Fiscaliza para compreender, verificar, pesquisar, reconstruir ou acompanhar informação institucional.

## Stakeholder

Pessoa ou organização afetada pelo projeto, interessada em seus resultados ou capaz de fornecer contexto, crítica, dados públicos ou colaboração.

## Objeto de fiscalização

Pessoa, órgão, organização, decisão, documento, contrato, processo, votação ou outro elemento institucional documentado pelo Fiel Fiscaliza.

Ser objeto de fiscalização não torna alguém usuário do produto.

O produto deve ser desenhado prioritariamente para quem precisa compreender a instituição, não para satisfazer interesses das pessoas fiscalizadas.

---

# 9. Usuário primário para F1

## 9.1 Torcedor institucionalmente engajado

**Classificação:** DECIDIDO PARA F1  
**Confiança:** MODERADA  
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

A escolha não presume alinhamento político interno.

### Justificativa

A pesquisa documental encontrou os sinais mais consistentes de interesse e necessidade de reconstrução documental nesse grupo, incluindo debates públicos recorrentes, mobilização em torno de governança, consulta a múltiplos tipos de fonte e interesse por finanças, estatuto, decisões e memória institucional.

Sob incerteza, esse segmento também reduz risco de MVP: é onde a intensidade aparente do problema é maior, sem impedir que a experiência permaneça acessível a usuários menos especializados.

### Necessidades principais

- verificar afirmações;
- reencontrar documentos e fontes;
- reconstruir cronologias;
- saber o estado atual de questões antigas;
- contextualizar números;
- compreender decisões sem inferir informação ausente;
- usar histórico em vez de memória informal.

### Limitação da decisão

Não foi demonstrado por pesquisa comportamental que esse segmento utilizará uma ferramenta dedicada com determinada frequência.

A escolha é uma decisão estratégica reversível, não uma alegação de demanda comprovada.

---

# 10. Usuários secundários

## 10.1 Torcedor com dúvida institucional pontual

**Classificação:** DECIDIDO PARA F1  
**Confiança:** MODERADA

Não acompanha política diariamente, mas procura contexto quando uma crise, eleição, investigação, dívida ou decisão ganha relevância.

Sua inclusão como usuário secundário protege o requisito de acessibilidade informacional e evita uma experiência compreensível apenas para especialistas.

## 10.2 Jornalista, comunicador ou criador de conteúdo

**Classificação:** DECIDIDO PARA F1  
**Confiança:** MODERADA

Pode obter valor ao localizar fonte original, datas, cronologias e registros públicos.

O produto não deve se tornar serviço de pauta, clipping ou substituto de apuração jornalística.

## 10.3 Pesquisador histórico, acadêmico ou analista externo

**Classificação:** DECIDIDO PARA F1  
**Confiança:** BAIXA para o MVP; MODERADA para a visão de longo prazo

Pode obter valor do patrimônio acumulado, mas não deve comandar o escopo inicial.

## 10.4 Associado, conselheiro ou participante institucional

**Classificação:** HIPÓTESE COM EVIDÊNCIA DOCUMENTAL PARCIAL  
**Confiança:** BAIXA

Pode se beneficiar de memória pública, mas o produto não dependerá de acesso interno, credenciais privilegiadas, documentos confidenciais ou relacionamento político.

---

# 11. Jobs to Be Done prioritários

As prioridades abaixo orientam escopo e discussão do MVP. Elas **não obrigam** o FF-0008 a implementar todos os P0.

## P0 — candidatos centrais

### JTBD-01 — Verificar uma afirmação e chegar à fonte

**Quando** encontro uma afirmação institucional relevante,  
**quero** identificar quem afirmou, a origem, o status e a evidência disponível,  
**para** distinguir o documentado do alegado, inferido, contestado ou desconhecido.

**Classificação:** DECIDIDO PARA F1

---

### JTBD-02 — Reconstruir a história e o estado atual de uma questão

**Quando** um assunto se desenvolve durante meses ou anos,  
**quero** reconstruir sua evolução e identificar seu estado conhecido atual,  
**para** entender o que mudou sem depender da última notícia que lembro ter visto.

**Classificação:** DECIDIDO PARA F1

---

### JTBD-03 — Entender um número financeiro no tempo

**Quando** encontro um valor sobre dívida, Arena, receita, despesa ou outro indicador financeiro,  
**quero** saber valor, data-base, conceito, método e fonte,  
**para** evitar comparar números diferentes como se fossem equivalentes.

**Classificação:** DECIDIDO PARA F1

---

### JTBD-04 — Reconstruir uma decisão institucional pública

**Quando** um órgão do clube toma uma decisão,  
**quero** saber qual órgão decidiu, quando, qual era a pauta, qual foi o resultado e quais informações individuais estão publicamente disponíveis,  
**para** compreender a decisão sem inferir votos, alianças ou posições não documentadas.

**Classificação:** DECIDIDO PARA F1

Voto individual não publicado deve permanecer **desconhecido / não disponível publicamente**.

---

## P1 — relevantes, não obrigatórios para o MVP

### JTBD-05 — Entender o estágio real de investigação ou processo

Identificar o que está em investigação, o que foi decidido, o que ainda pode mudar e qual é o estado processual conhecido.

**Classificação:** DECIDIDO PARA F1  
**Risco editorial:** ALTO

### JTBD-06 — Comparar versões ou claims conflitantes

Identificar quem afirmou cada versão, quais evidências estão associadas e o que permanece contestado.

**Classificação:** DECIDIDO PARA F1  
**Risco editorial:** ALTO

### JTBD-07 — Recuperar atuação institucional publicamente documentada

Encontrar cargos, mandatos, decisões, posições e votações publicamente verificáveis relacionados a pessoa ou órgão.

**Classificação:** DECIDIDO PARA F1

Não autoriza inferir voto secreto, aliança, intenção ou culpa.

### JTBD-08 — Descobrir o que era conhecido em determinada data

Reconstruir o estado documental disponível em um momento passado para reduzir anacronismo.

**Classificação:** DECIDIDO PARA F1

---

## P2 — adiados

### JTBD-09 — Alertas de mudança

**Classificação:** DEPRIORIZADO PARA O MVP

A dispersão de fontes torna a ideia plausível, mas não existe evidência suficiente de que alertas devam orientar a primeira versão.

### JTBD-10 — Pesquisa acadêmica avançada / exportações especializadas

**Classificação:** DEPRIORIZADO PARA O MVP

Compatível com a visão de longo prazo, mas não necessário para provar utilidade inicial.

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

O FF-0008 permanece responsável por selecionar quais capacidades efetivamente entram no MVP.

---

# 13. Anti-use-cases

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

O projeto fiscaliza atos e estruturas institucionais publicamente documentáveis, sem transformar pessoas em alvos de perseguição.

---

# 14. Dívida de validação e gatilhos de reabertura

Ao avançar sem pesquisa comportamental pré-MVP, permanecem explicitamente desconhecidos:

- frequência real de uso por pessoa;
- intensidade subjetiva da dor;
- taxa de retorno a uma ferramenta dedicada;
- preferência de interface;
- quantidade de contexto tolerada por usuários não especializados;
- economia efetiva de tempo;
- segmentos que gerarão maior uso real;
- recursos aparentemente valiosos que podem ser pouco utilizados.

Essa dívida pode ser reduzida por:

- feedback espontâneo após protótipo ou MVP;
- formulário curto no produto;
- issues ou discussões públicas;
- análise agregada de uso quando compatível com privacidade;
- conversas assíncronas;
- entrevistas direcionadas quando uma decisão material continuar incerta;
- testes de tarefa quando existir interface concreta a observar.

Nova pesquisa deve ser fortemente considerada quando:

1. dois caminhos relevantes possuírem evidência semelhante e a escolha depender de comportamento do usuário;
2. o MVP não demonstrar utilidade suficiente nos casos centrais;
3. houver dificuldade recorrente de compreensão;
4. um recurso de alto custo operacional depender de demanda ainda desconhecida;
5. surgir contraprova relevante de que uma solução existente atende melhor o problema;
6. o produto atrair principalmente um segmento diferente do usuário primário definido neste documento.

A dívida de validação não bloqueia automaticamente o projeto, mas deve permanecer visível e revisável.

---

# 15. Revisão de consistência canônica

## 15.1 FF-0001 — PROJECT_CONSTITUTION

A revisão não identificou conflito material com o FF-0001.

A estratégia de limitar discovery obrigatório é coerente com manutenção individual, utilidade antes de abrangência, especificação antes de implementação e sustentabilidade operacional.

## 15.2 FF-0002 — PRE_CODEX_CHECKLIST

O FF-0002 exige na Fase 1:

- identificação de usuários primários e secundários;
- definição de necessidades distintas;
- documentação de casos de uso prioritários;
- consideração das iniciativas existentes e das lacunas do produto.

Ele não prescreve entrevistas ou testes comportamentais como método obrigatório.

Esta versão satisfaz esses requisitos no nível de decisão necessário para prosseguir a Fase 1, sem alegar validação empírica inexistente.

## 15.3 FF-0005 — PRODUCT_VISION v1.1

A tensão identificada na revisão v0.4 foi formalmente resolvida pela **FF-0005 v1.1 // CANONICAL**, formalizada no commit:

`bbc34f2f80b62bac507245e9e40e08cfeb459d83`

A versão 1.1 preserva a tese e os princípios da Product Vision e estabelece que:

- a evidência exigida para F1 é proporcional ao risco, custo e reversibilidade da decisão;
- pesquisa comportamental pré-MVP não é requisito universal;
- decisões sob incerteza devem permanecer pequenas, reversíveis e explicitamente qualificadas;
- dívida de validação deve ser registrada quando aplicável;
- pesquisa deve ser reaberta quando puder alterar materialmente escopo, custo, risco, compreensão ou viabilidade;
- decisão provisória não pode ser apresentada como demanda empiricamente validada.

O FF-0006 v1.0 é compatível com essa regra.

---

# 16. Decisões de produto estabelecidas por este documento

Para fins da Fase 1, ficam estabelecidas as seguintes decisões, sujeitas aos limites e à dívida de validação já registrados:

1. **usuário primário:** torcedor institucionalmente engajado;
2. **usuários secundários relevantes:** torcedor com dúvida institucional pontual; jornalista/comunicador/criador de conteúdo; pesquisador histórico, acadêmico ou analista externo;
3. **usuário secundário ainda hipotético:** associado, conselheiro ou participante institucional;
4. **JTBD P0:** verificar afirmação e fonte; reconstruir cronologia e estado atual; contextualizar número financeiro; reconstruir decisão institucional pública;
5. **JTBD P1:** estágio de investigação/processo; claims conflitantes; atuação institucional documentada; estado conhecido em data passada;
6. **JTBD P2/depriorizados para MVP:** alertas de mudança; pesquisa acadêmica avançada/exportações especializadas.

Essas decisões orientam FF-0007 e FF-0008, mas não escolhem automaticamente páginas, funcionalidades, arquitetura, fontes iniciais ou modelo de dados.

---

# 17. Critérios de canonização e resultado da revisão

A revisão confirmou que:

- o usuário primário está explicitamente definido;
- usuários secundários estão diferenciados;
- JTBD P0/P1 são compatíveis com FF-0001 e FF-0005 v1.1;
- escolhas são apresentadas como decisões de produto, não como prova científica de comportamento;
- alternativas existentes e contraprovas foram consideradas;
- anti-use-cases permanecem explícitos;
- nenhuma necessidade presume acesso privilegiado, voto secreto, aliança, culpa ou dado privado;
- dívida de validação e gatilhos estão registrados;
- as decisões são suficientes para orientar FF-0007 e FF-0008 sem escolher tecnologia ou interface prematuramente.

Não foi identificado conflito canônico bloqueante após a atualização do FF-0005.

---

# 18. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION v1.1.

## Impacta

- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- futuros documentos de Experiência;
- priorização posterior de backlog e roadmap.

As prioridades deste documento não selecionam automaticamente funcionalidades do MVP.

---

# 19. Vigência

Esta versão possui status **CANONICAL** e entra em vigor em **2026-09-04** por aprovação explícita de André após revisão crítica e resolução da tensão com o FF-0005.

**FF-0006 — USERS_AND_USE_CASES v1.0 // CANONICAL**

A canonização estabelece usuários e casos de uso suficientes para orientar a continuidade da Fase 1, preservando explicitamente que demanda, frequência e comportamento ainda não foram empiricamente validados por pesquisa comportamental.
