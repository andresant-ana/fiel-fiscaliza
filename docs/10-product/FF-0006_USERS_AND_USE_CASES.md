# FF-0006 — USERS_AND_USE_CASES

**Nome do documento:** Users and Use Cases  
**ID:** FF-0006  
**Versão:** 0.1  
**Status:** DRAFT  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento identifica os grupos de usuários candidatos do Fiel Fiscaliza, descreve as tarefas institucionais que o produto pretende ajudar a realizar e define como essas hipóteses deverão ser validadas antes do Gate F1.

Seu objetivo não é inventar personas detalhadas sem evidência.

O documento deve responder progressivamente:

- quem pode obter valor real do Fiel Fiscaliza;
- quais problemas essas pessoas tentam resolver;
- em quais situações esses problemas aparecem;
- como essas tarefas são realizadas atualmente;
- onde existe atrito, perda de contexto ou custo de verificação;
- quais casos de uso possuem melhor combinação entre utilidade, frequência, relevância institucional e sustentabilidade operacional;
- quais grupos não devem orientar o produto mesmo que consigam utilizá-lo.

O FF-0006 é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

---

# 2. Regra epistemológica desta versão

A Fase 1 ainda não possui pesquisa suficiente para declarar empiricamente quais segmentos são usuários primários, qual a frequência real de suas dores ou quais casos de uso possuem maior valor recorrente.

Portanto, esta versão utiliza três classificações:

## HIPÓTESE

Proposição plausível ainda não validada por evidência suficiente de usuários.

## EVIDÊNCIA PARCIAL

Proposição sustentada por sinais reais, mas ainda insuficiente para decisão definitiva de produto.

## VALIDADO PARA F1

Proposição com evidência suficiente, dentro das limitações desta fase, para orientar FF-0007 e FF-0008.

Nenhum segmento ou caso de uso deve ser promovido a prioridade de MVP apenas porque parece intuitivo ao mantenedor.

A experiência pessoal de André é evidência válida de uma necessidade individual, mas não prova, sozinha, que a mesma necessidade possua relevância suficiente para um público externo.

---

# 3. Usuário, stakeholder e objeto de fiscalização

Esses conceitos não devem ser confundidos.

## Usuário

Pessoa que utiliza o Fiel Fiscaliza para compreender, verificar, pesquisar, reconstruir ou acompanhar informação institucional.

## Stakeholder

Pessoa ou organização afetada pelo projeto, interessada em seus resultados ou capaz de fornecer contexto, crítica, dados públicos ou colaboração.

Um stakeholder pode nunca utilizar a aplicação pública.

## Objeto de fiscalização

Pessoa, órgão, organização, decisão, documento, contrato, processo, votação ou outro elemento institucional documentado pelo Fiel Fiscaliza.

Ser objeto de fiscalização não torna alguém usuário do produto.

Essa distinção é importante para impedir que a experiência seja desenhada principalmente para as pessoas fiscalizadas em vez de para quem precisa compreender a instituição.

---

# 4. Critérios para considerar um segmento prioritário

Um grupo de usuários deve ganhar prioridade somente quando houver evidência de que reúne parte relevante dos seguintes fatores:

1. possui perguntas institucionais compatíveis com a missão do projeto;
2. enfrenta esforço materialmente relevante para respondê-las hoje;
3. consegue obter valor de informação pública sem depender de acesso privilegiado;
4. valoriza contexto, fonte, histórico ou verificabilidade;
5. pode utilizar o produto sem exigir cobertura jornalística em tempo real;
6. não exige operação incompatível com manutenção individual;
7. seu atendimento beneficia a capacidade de fiscalização institucional e memória;
8. suas necessidades podem ser atendidas sem violar independência editorial, privacidade ou segurança.

Tamanho do público, sozinho, não determina prioridade.

---

# 5. Segmentos candidatos

Os segmentos abaixo são **hipóteses de produto** nesta versão.

A nomenclatura descreve comportamento e necessidade, não identidade política, faixa etária, profissão ou pertencimento a grupos específicos.

---

## 5.1 Torcedor interessado em compreender uma questão institucional

**Status:** HIPÓTESE  
**Candidato a:** usuário primário

### Situação

É um corinthiano que não acompanha necessariamente a política do clube todos os dias, mas encontra uma questão que deseja compreender melhor.

Pode chegar ao tema após:

- notícia relevante;
- crise institucional;
- eleição;
- votação;
- investigação;
- mudança financeira;
- debate em redes sociais;
- declaração de dirigente;
- alteração estatutária;
- outro acontecimento de consequência institucional.

### Necessidades candidatas

- entender rapidamente o contexto mínimo;
- saber o que efetivamente aconteceu;
- separar fato, alegação e opinião;
- localizar documento ou fonte;
- identificar o estado atual da questão;
- descobrir o que aconteceu anteriormente.

### Risco de produto

Se o Fiel Fiscaliza exigir conhecimento prévio de direito, contabilidade, estatuto ou política interna, esse usuário pode não conseguir extrair valor mesmo quando os dados forem corretos.

---

## 5.2 Torcedor institucionalmente engajado

**Status:** HIPÓTESE  
**Candidato a:** usuário primário

### Situação

Acompanha governança, finanças, eleições, conselhos, estatuto ou crises institucionais com frequência maior que o torcedor comum.

Pode participar ou não de associações, movimentos, torcidas organizadas, grupos de discussão ou espaços políticos do clube.

O Fiel Fiscaliza não deve presumir filiação institucional nem alinhamento político desse usuário.

### Necessidades candidatas

- reencontrar fatos e documentos antigos;
- reconstruir cronologias;
- verificar afirmações que circulam em debates;
- comparar estado atual com estados anteriores;
- consultar histórico institucional de pessoas, órgãos ou decisões quando publicamente documentado;
- sustentar discussões com fontes verificáveis em vez de memória informal.

### Risco de produto

Esse usuário pode possuir opiniões políticas fortes. O produto não deve adaptar fatos para confirmar situação, oposição ou qualquer grupo com o qual ele se identifique.

---

## 5.3 Pesquisador eventual de uma questão histórica

**Status:** HIPÓTESE  
**Candidato a:** usuário primário ou secundário

### Situação

Chega ao produto com uma pergunta específica sobre algo que aconteceu meses ou anos antes.

Não precisa ser pesquisador profissional.

Pode ser um torcedor tentando responder, por exemplo:

- quando determinada decisão ocorreu;
- qual era a composição de um órgão;
- como um processo evoluiu;
- qual documento sustentava determinada informação;
- qual valor financeiro era divulgado em determinada época;
- se uma afirmação atual corresponde ao registro histórico disponível.

### Necessidades candidatas

- busca e descoberta sem conhecer a fonte original;
- recuperação temporal;
- acesso a documentos e proveniência;
- distinção entre estado histórico e estado atual;
- contexto suficiente para não interpretar um registro antigo com informação que só surgiu depois.

### Risco de produto

Uma plataforma otimizada apenas para acontecimentos recentes pode falhar completamente para esse segmento, mesmo mantendo grande volume de conteúdo.

---

## 5.4 Jornalista, comunicador ou criador de conteúdo

**Status:** HIPÓTESE  
**Candidato a:** usuário secundário

### Situação

Precisa verificar ou reconstruir rapidamente informação institucional antes de produzir conteúdo próprio.

O Fiel Fiscaliza não existe para substituir apuração jornalística, mas pode reduzir o custo de localizar material público já documentado.

### Necessidades candidatas

- localizar fonte original;
- verificar datas;
- reconstruir cronologias;
- identificar estado processual ou institucional conhecido;
- encontrar documentos históricos;
- evitar reproduzir alegações antigas como fatos atuais.

### Risco de produto

Uso jornalístico não deve transformar o Fiel Fiscaliza em serviço de pauta, clipping ou produção de manchetes em tempo real.

---

## 5.5 Associado do SCCP, conselheiro ou participante da vida institucional

**Status:** HIPÓTESE  
**Candidato a:** usuário secundário

### Situação

Possui relação formal com estruturas do clube e pode utilizar o produto para recuperar registros públicos, contexto ou memória institucional.

### Necessidades candidatas

- localizar decisões e documentos públicos anteriores;
- reconstruir histórico de votações quando publicamente disponível;
- acompanhar alterações institucionais;
- consultar contexto de temas em deliberação.

### Restrições

O produto público não deve depender de:

- acesso interno;
- credenciais privilegiadas;
- documentos confidenciais;
- favores institucionais;
- vazamentos ilegais.

### Risco de produto

A proximidade de determinados usuários com o poder institucional não lhes concede autoridade editorial sobre o projeto.

---

## 5.6 Pesquisador acadêmico, historiador ou analista externo

**Status:** HIPÓTESE  
**Candidato a:** usuário secundário de longo prazo

### Situação

Busca dados, documentos ou reconstrução histórica sobre governança esportiva, futebol, associativismo, finanças ou política institucional.

### Necessidades candidatas

- histórico preservado;
- proveniência;
- datas e vigências claras;
- documentação rastreável;
- dados estruturados quando futuramente disponíveis.

### Observação

Esse segmento pode obter alto valor do patrimônio acumulado do projeto, mas não deve necessariamente determinar o escopo inicial do MVP.

---

# 6. Não usuários prioritários e anti-use-cases

O fato de alguém conseguir acessar o produto não significa que suas necessidades devam orientar o roadmap.

O Fiel Fiscaliza não deve otimizar sua experiência para:

- usuários que buscam escalações, transferências ou cobertura esportiva cotidiana sem consequência institucional;
- grupos que desejem apenas material para campanha eleitoral interna;
- pessoas buscando listas para assédio, intimidação ou perseguição;
- usuários interessados em dados pessoais privados;
- pessoas que esperem conclusões de culpa sem evidência suficiente;
- usuários que desejem rumores rápidos em vez de informação verificável;
- grupos que exijam manipulação editorial favorável a situação ou oposição;
- pessoas cuja principal necessidade seja entretenimento esportivo.

Esses usos podem ocorrer apesar das intenções do projeto, mas não devem ser tratados como valor de produto a maximizar.

---

# 7. Jobs to Be Done candidatos

Os casos abaixo representam tarefas do usuário, não funcionalidades específicas.

Uma mesma tarefa pode futuramente ser atendida por diferentes soluções de interface ou arquitetura.

---

## JTBD-01 — Entender uma questão institucional que apareceu agora

**Quando** encontro uma notícia, debate ou crise sobre o Corinthians,  
**quero** compreender rapidamente o que aconteceu, qual é o contexto e quais informações são confirmadas,  
**para** formar uma visão informada sem depender apenas da narrativa de quem publicou primeiro.

**Status:** HIPÓTESE

---

## JTBD-02 — Reconstruir a história de uma questão

**Quando** preciso entender um assunto que se desenvolveu durante meses ou anos,  
**quero** visualizar ou consultar sua evolução em ordem temporal,  
**para** saber o que mudou e evitar interpretar o passado somente pelo estado atual.

**Status:** HIPÓTESE

---

## JTBD-03 — Verificar uma afirmação

**Quando** vejo uma afirmação sobre dirigente, conselheiro, votação, dívida, documento, investigação ou decisão,  
**quero** identificar a origem, o status e a evidência disponível,  
**para** distinguir o que é documentado do que é alegado, inferido ou desconhecido.

**Status:** HIPÓTESE

---

## JTBD-04 — Encontrar a fonte original

**Quando** encontro uma informação reproduzida em notícia, rede social ou debate,  
**quero** chegar ao documento, decisão, declaração ou registro de origem quando disponível,  
**para** verificar o conteúdo com menos intermediação.

**Status:** HIPÓTESE

---

## JTBD-05 — Saber o estado atual de algo que acompanhei no passado

**Quando** volto a uma investigação, processo, mandato, dívida, promessa ou decisão que acompanhei anteriormente,  
**quero** descobrir o que aconteceu desde então,  
**para** não depender da última informação que lembro ter visto.

**Status:** HIPÓTESE

---

## JTBD-06 — Descobrir o que era conhecido em determinada data

**Quando** preciso avaliar uma decisão ou declaração passada,  
**quero** saber quais informações e estados estavam documentados naquele momento,  
**para** evitar anacronismo e reconstrução histórica incorreta.

**Status:** HIPÓTESE

---

## JTBD-07 — Recuperar atuação institucional publicamente documentada

**Quando** preciso compreender a trajetória institucional de uma pessoa ou órgão,  
**quero** encontrar cargos, mandatos, decisões, posições, votações ou acontecimentos publicamente verificáveis relacionados,  
**para** avaliar atuação institucional com memória documental em vez de impressão pessoal.

**Status:** HIPÓTESE

### Restrição

Esse Job não autoriza inferir voto secreto, aliança política, intenção, culpa ou posição não documentada.

---

## JTBD-08 — Explicar uma questão para outra pessoa sem perder a fonte

**Quando** preciso compartilhar ou discutir um tema institucional,  
**quero** conseguir apontar para uma representação clara e rastreável da questão,  
**para** que a outra pessoa possa verificar a base factual sem depender apenas da minha interpretação.

**Status:** HIPÓTESE

---

# 8. Dimensões de valor dos casos de uso

Antes de priorizar casos de uso para o MVP, cada um deverá ser avaliado pelo menos pelas seguintes dimensões:

## Relevância institucional

Quanto a tarefa contribui para compreensão, memória ou fiscalização do SCCP?

## Intensidade da dor

Quanto esforço, incerteza ou retrabalho existe hoje para realizar a tarefa?

## Frequência

Com que frequência a necessidade aparece para o segmento correspondente?

Baixa frequência não elimina valor quando o impacto da tarefa for alto.

## Adequação às fontes públicas

A tarefa pode ser atendida de maneira útil utilizando apenas informação legitimamente acessível?

## Diferenciação

O Fiel Fiscaliza acrescenta valor além do que já é facilmente obtido por busca comum, imprensa, site oficial ou iniciativas existentes?

## Sustentabilidade

O caso de uso pode ser mantido sem exigir operação manual diária incompatível com o projeto?

## Risco editorial

Qual o potencial de erro, falsa atribuição, descontextualização ou dano reputacional caso o caso de uso seja mal implementado?

## Complexidade cognitiva

É possível oferecer o valor sem exigir que o usuário compreenda internamente o modelo de domínio, a política editorial ou linguagem especializada?

---

# 9. Fluxos de tarefa conceituais

Esta seção descreve comportamentos desejados em nível abstrato e não determina páginas ou componentes.

## Fluxo A — partir de uma pergunta atual

1. usuário encontra uma questão institucional;
2. identifica no Fiel Fiscaliza uma representação relacionada;
3. compreende resumo factual e status;
4. consulta contexto anterior quando necessário;
5. inspeciona fontes e evidências;
6. entende o estado atual e as lacunas conhecidas.

## Fluxo B — partir de uma informação antiga

1. usuário lembra parcialmente de um acontecimento;
2. procura por tema, pessoa, órgão, documento ou período;
3. encontra registros relacionados;
4. reconstrói a sequência temporal;
5. identifica o que mudou desde aquele momento.

## Fluxo C — partir de uma afirmação contestada

1. usuário encontra uma afirmação;
2. procura evidência ou registro correspondente;
3. identifica autoria e fonte;
4. verifica status editorial e eventuais contestações;
5. acessa a origem quando disponível;
6. conclui apenas até o nível permitido pelas evidências.

---

# 10. Barreiras de uso a investigar

Mesmo que a tese do FF-0005 esteja correta, o produto pode falhar se o usuário não conseguir interpretar sua estrutura.

A pesquisa deve investigar especialmente:

- excesso de linguagem jurídica;
- excesso de linguagem técnica;
- diferença entre fonte, evidência e claim;
- compreensão de datas e vigências;
- compreensão de status como “alegado”, “não confirmado” e “em andamento”;
- dificuldade de navegar histórias longas;
- sobrecarga de detalhes documentais;
- dificuldade de distinguir resumo editorial de fonte original;
- expectativa de atualização em tempo real;
- expectativa de que o projeto emita julgamento político ou moral sobre pessoas.

A solução futura deve reduzir essas barreiras sem esconder incerteza ou simplificar a ponto de distorcer fatos.

---

# 11. Hipóteses prioritárias a validar

Antes de considerar este documento pronto para canonização, a pesquisa deve produzir evidência sobre pelo menos as seguintes perguntas.

## U-H01 — Existe usuário externo?

Há pessoas além de André que enfrentam problemas compatíveis com os Jobs identificados?

## U-H02 — Qual Job dói mais?

Entre compreensão atual, reconstrução histórica, verificação de afirmações, busca de documentos e acompanhamento de evolução, quais tarefas possuem maior valor percebido?

## U-H03 — Qual segmento sente a dor com maior intensidade?

O maior valor está no torcedor interessado eventual, no institucionalmente engajado, em comunicadores, associados ou em outro grupo ainda não identificado?

## U-H04 — Busca comum já resolve?

Em quais casos Google, imprensa, redes sociais, sites oficiais ou arquivos existentes já resolvem suficientemente a tarefa?

## U-H05 — O histórico realmente gera valor adicional?

Usuários precisam apenas da informação atual ou valorizam conseguir reconstruir sua evolução?

## U-H06 — Proveniência é utilizada?

Usuários realmente querem abrir e verificar fontes ou apenas valorizam saber que a informação possui origem rastreável?

## U-H07 — O rigor é compreensível?

É possível expor status, incerteza e evidência sem tornar o produto difícil de entender?

## U-H08 — Existe valor recorrente?

Os usuários voltariam ao produto para novas questões ou o utilizariam apenas em crises excepcionais?

Valor não recorrente não invalida automaticamente o projeto, mas muda as decisões de MVP e sucesso.

---

# 12. Estratégia de pesquisa de usuários para a Fase 1

A validação deve ser proporcional ao tamanho e natureza do projeto.

Não é necessário executar uma pesquisa de mercado corporativa extensa.

É necessário obter evidência suficiente para evitar construir apenas para a intuição do mantenedor.

## 12.1 Pesquisa documental e comportamental pública

Mapear:

- perguntas recorrentes em discussões públicas sobre política institucional do Corinthians;
- tipos de conteúdo de fiscalização que recebem uso ou circulação relevante;
- iniciativas existentes e tarefas que já resolvem;
- dificuldades visíveis para localizar documentos, votos, cronologias ou informações históricas.

Essa etapa pode gerar hipóteses, mas não substitui contato com usuários.

## 12.2 Entrevistas semiestruturadas

Meta inicial sugerida para F1:

**5 a 8 entrevistas** distribuídas entre pelo menos dois segmentos candidatos.

O número não é meta estatística. O objetivo é descobrir padrões de tarefa, linguagem e frustração suficientes para orientar o MVP.

As entrevistas devem privilegiar comportamento passado, por exemplo:

- “Me conte a última vez em que você tentou entender uma questão política do Corinthians.”
- “O que você procurou?”
- “Onde procurou?”
- “O que foi difícil?”
- “Você conseguiu chegar à fonte original?”
- “Como soube em qual versão confiar?”
- “Você precisou voltar ao assunto depois?”

Evitar perguntas como:

- “Você usaria um site que organiza tudo?”
- “Você acha essa ideia boa?”

Essas perguntas tendem a produzir aprovação educada sem demonstrar comportamento real.

## 12.3 Testes de tarefa sem produto implementado

Antes do MVP, é possível selecionar questões institucionais reais e pedir que participantes tentem responder perguntas utilizando os meios atuais.

Observar:

- tempo aproximado;
- número de fontes consultadas;
- pontos de abandono;
- dificuldade de encontrar origem;
- contradições encontradas;
- informações que permaneceram desconhecidas.

O objetivo é medir o problema, não testar ainda uma interface inexistente.

## 12.4 Validação complementar

Enquetes ou formulários públicos podem ajudar a coletar sinais, mas não devem ser usados isoladamente para provar demanda.

Preferir perguntas sobre comportamento passado a preferência hipotética.

---

# 13. Registro mínimo de evidências

Para cada entrevista ou observação utilizada na Fase 1, preservar de forma proporcional:

- data;
- segmento candidato;
- método;
- pergunta ou tarefa investigada;
- síntese anonimizada quando aplicável;
- problemas observados;
- Jobs relacionados;
- evidências favoráveis;
- contraprovas;
- limitações da observação.

Não armazenar dados pessoais desnecessários dos participantes.

Se trechos de entrevistas forem utilizados publicamente, obter autorização adequada ou anonimizar de forma suficiente.

---

# 14. Critério provisório para usuário primário do MVP

O usuário primário do MVP ainda está **NÃO DEFINIDO**.

Para que um segmento seja escolhido no FF-0008, deverá existir evidência suficiente de que:

- possui pelo menos um Job relevante e claramente observado;
- o Job é compatível com a Product Vision;
- o problema atual não é trivialmente resolvido por alternativas existentes;
- há informação pública suficiente para gerar valor;
- atender o Job é operacionalmente sustentável;
- o segmento não exige privilégio institucional;
- o produto consegue servir esse grupo sem prejudicar integridade editorial.

A escolha deve considerar força da evidência, não apenas proximidade pessoal do mantenedor com o segmento.

---

# 15. Casos de uso candidatos para priorização posterior

Sem definir ainda o MVP, os casos abaixo devem entrar na pesquisa e comparação:

- compreender uma crise ou decisão institucional atual;
- reconstruir cronologia de uma questão;
- verificar uma afirmação pública;
- localizar documento ou fonte original;
- descobrir estado atual de processo ou investigação anteriormente acompanhado;
- recuperar composição, cargo ou mandato em determinado período;
- consultar atuação institucional publicamente documentada de pessoa ou órgão;
- identificar se um voto individual é público, desconhecido ou não verificável;
- contextualizar um valor financeiro historicamente;
- comparar promessa, declaração ou posição pública com registros posteriores quando houver evidência adequada;
- compartilhar uma questão com contexto e fontes preservados.

Esses itens são **candidatos de pesquisa**, não escopo aprovado.

---

# 16. Critérios de descarte ou rebaixamento

Um segmento ou caso de uso deve ser rebaixado de prioridade se a pesquisa indicar que:

- a dor é rara e de baixo impacto;
- alternativas atuais resolvem bem a tarefa;
- depende de informação que normalmente não é pública;
- exige interpretação humana diária desproporcional;
- gera risco editorial alto sem benefício equivalente;
- empurra o produto para jornalismo esportivo geral;
- depende de opinião ou ranking político como valor central;
- atende principalmente ao mantenedor sem evidência externa suficiente;
- entra em conflito com custo zero, privacidade ou independência.

Descartar uma hipótese não constitui falha do projeto.

É resultado válido de pesquisa.

---

# 17. Relação com o FF-0007 e FF-0008

O FF-0006 não define sozinho o escopo.

Após a pesquisa:

## FF-0007 — SCOPE

deve estabelecer quais classes de problema e informação pertencem ou não ao produto.

## FF-0008 — MVP_SPEC

deve escolher quais segmentos e Jobs serão atendidos primeiro e quais capacidades mínimas serão necessárias para fazê-lo.

Nenhum caso de uso listado neste documento entra automaticamente no MVP.

---

# 18. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

## Impacta

- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- FF-0022 — INFORMATION_ARCHITECTURE;
- FF-0023 — USER_FLOWS;
- FF-0025 — CONTENT_STYLE_GUIDE;
- priorização futura de backlog e roadmap.

Se a pesquisa de usuários produzir evidência materialmente incompatível com a tese do FF-0005, a Product Vision deve ser reavaliada antes do Gate F1 em vez de adaptar silenciosamente este documento para contornar o conflito.

---

# 19. Critérios para canonização

Antes de promover o FF-0006 para CANONICAL, deve-se confirmar que:

- segmentos prioritários possuem evidência além da intuição do mantenedor;
- pelo menos os principais Jobs foram observados em comportamento ou necessidade real;
- alternativas atuais foram consideradas;
- contraprovas foram registradas;
- usuário primário do MVP pode ser escolhido ou conscientemente adiado ao FF-0008 com evidência suficiente;
- nenhum segmento pressupõe acesso institucional privilegiado;
- anti-use-cases estão coerentes com FF-0001;
- os casos de uso não antecipam silenciosamente funcionalidades específicas;
- o documento continua compatível com manutenção individual;
- eventuais impactos sobre FF-0005 foram avaliados.

---

# 20. Estado desta versão

Esta versão é deliberadamente **DRAFT**.

Ela organiza as hipóteses de usuários, Jobs e estratégia de validação, mas ainda não possui evidência suficiente para declarar os segmentos candidatos como prioridades canônicas de produto.

O próximo passo para o próprio FF-0006 não é simplesmente “revisar a redação”.

É executar a pesquisa mínima prevista nesta especificação, incorporar seus resultados e somente então avaliar promoção para:

**FF-0006 — USERS_AND_USE_CASES v1.0 // CANONICAL**

O Gate F1 permanece aberto.