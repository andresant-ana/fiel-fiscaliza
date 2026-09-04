# FF-0006 — USERS_AND_USE_CASES

**Nome do documento:** Users and Use Cases  
**ID:** FF-0006  
**Versão:** 0.2  
**Status:** DRAFT  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento identifica os grupos de usuários candidatos do Fiel Fiscaliza, descreve as tarefas institucionais que o produto pretende ajudar a realizar e registra a evidência disponível para decidir quais usuários e casos de uso poderão orientar o MVP.

Seu objetivo não é inventar personas detalhadas nem transformar interesse aparente em demanda comprovada.

O documento deve responder progressivamente:

- quem pode obter valor real do Fiel Fiscaliza;
- quais problemas essas pessoas tentam resolver;
- em quais situações esses problemas aparecem;
- como essas tarefas são realizadas atualmente;
- onde existe atrito, perda de contexto ou custo de verificação;
- quais alternativas já resolvem parte do problema;
- quais casos de uso possuem melhor combinação entre utilidade, frequência, relevância institucional e sustentabilidade operacional;
- quais grupos não devem orientar o produto mesmo que consigam utilizá-lo;
- quais hipóteses já possuem evidência documental e quais ainda dependem de evidência comportamental.

O FF-0006 é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

A Product Vision estabelece que a unidade básica de valor do Fiel Fiscaliza é uma questão institucional que se torna mais fácil de compreender, verificar e reconstruir, e não uma notícia publicada.

---

# 2. Estado da pesquisa nesta versão

A versão 0.2 incorpora uma pesquisa documental pública realizada em **2026-09-04** sobre o ecossistema de informação, transparência, governança, fiscalização e memória institucional relacionado ao Corinthians.

A pesquisa incluiu, entre outros:

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
- pesquisa acadêmica;
- MPSP;
- TJSP;
- CVM / Fundos.NET;
- Receita Federal e dados de CNPJ;
- Diários Oficiais e outras bases públicas auxiliares.

A pesquisa documental encontrou evidência forte de que determinadas tarefas existem publicamente e se repetem no ecossistema, mas **não é suficiente para declarar qual segmento deve ser o usuário primário do MVP, qual é a frequência real dessas tarefas por pessoa ou quão forte é a disposição de usar uma ferramenta dedicada para resolvê-las**.

Portanto, esta versão permanece **DRAFT**.

---

# 3. Regra epistemológica

A partir desta versão, hipóteses de usuário e de caso de uso devem utilizar os seguintes estados.

## HIPÓTESE

Proposição plausível ainda sem evidência significativa suficiente.

## EVIDÊNCIA DOCUMENTAL

Proposição observada de modo consistente em fontes públicas, documentos, cobertura jornalística, discussões ou iniciativas do ecossistema.

Esse estado demonstra que a tarefa ou necessidade existe publicamente, mas não demonstra por si só frequência individual, intensidade da dor ou prioridade de produto.

## EVIDÊNCIA COMPORTAMENTAL

Proposição sustentada por episódios reais relatados por participantes ou pela observação direta de uma pessoa executando a tarefa.

## VALIDADO PARA F1

Proposição com evidência documental e comportamental suficiente, dentro das limitações desta fase, para orientar FF-0007 e FF-0008.

## REFUTADO / DEPRIORIZADO

Hipótese que a pesquisa mostrou possuir baixa frequência, baixo valor, boa solução alternativa, baixa viabilidade, risco incompatível com o projeto ou conflito com os documentos CANONICAL.

Nenhum segmento ou caso de uso deve ser promovido a prioridade de MVP apenas porque parece intuitivo ao mantenedor.

A experiência pessoal de André é evidência válida de uma necessidade individual, mas não prova, sozinha, que a mesma necessidade possua relevância suficiente para um público externo.

---

# 4. Usuário, stakeholder e objeto de fiscalização

Esses conceitos não devem ser confundidos.

## Usuário

Pessoa que utiliza o Fiel Fiscaliza para compreender, verificar, pesquisar, reconstruir ou acompanhar informação institucional.

## Stakeholder

Pessoa ou organização afetada pelo projeto, interessada em seus resultados ou capaz de fornecer contexto, crítica, dados públicos ou colaboração.

Um stakeholder pode nunca utilizar a aplicação pública.

## Objeto de fiscalização

Pessoa, órgão, organização, decisão, documento, contrato, processo, votação ou outro elemento institucional documentado pelo Fiel Fiscaliza.

Ser objeto de fiscalização não torna alguém usuário do produto.

Essa distinção impede que a experiência seja desenhada principalmente para as pessoas fiscalizadas em vez de para quem precisa compreender a instituição.

---

# 5. Síntese da pesquisa documental

## 5.1 Evidência observada

A pesquisa não encontrou falta absoluta de informação institucional sobre o Corinthians.

Ao contrário, existe um ecossistema significativo de:

- documentos oficiais;
- cobertura jornalística;
- fóruns e comunidades;
- torcidas organizadas;
- coletivos de governança;
- propostas de reforma institucional;
- registros judiciais e administrativos;
- bases públicas governamentais.

A fricção observada está principalmente em **fragmentação, heterogeneidade, perda de contexto temporal, dificuldade de reencontrar fontes, divergência de conceitos e custo de reconstrução**.

O portal oficial do SCCP publica materiais relevantes, mas sua organização é predominantemente documental. Notícias oferecem contexto e atualização, mas são consumidas como fluxo. Fóruns e redes ajudam a revelar perguntas e controvérsias, mas misturam opinião, rumor e informação não confirmada. Bases públicas podem oferecer evidência primária, porém exigem conhecimento para consulta e interpretação.

## 5.2 Interpretação de produto

A pesquisa torna mais plausível a tese de que existe espaço para uma camada independente orientada a reconstrução de questões institucionais.

Essa é uma **interpretação da pesquisa**, não uma prova de que o Fiel Fiscaliza possui demanda suficiente ou de que nenhuma solução equivalente existe.

A diferenciação candidata mais defensável não é competir com imprensa por velocidade nem reproduzir o portal oficial, mas reduzir o esforço necessário para conectar:

**fonte → afirmação/fato → evento → entidade → estado temporal → histórico.**

Essa formulação permanece uma hipótese de produto a ser testada com usuários.

---

# 6. Inventário resumido do ecossistema atual

## 6.1 SCCP — Transparência

**Tipo:** fonte oficial / primária para atos e publicações do clube.  
**Referências públicas:**

- https://www.corinthians.com.br/clube/transparencia
- https://www.corinthians.com.br/clube/transparencia/demonstracoes-financeiras-e-balancetes-patrimoniais
- https://www.corinthians.com.br/clube/transparencia/eleicoes
- https://www.corinthians.com.br/clube/transparencia/atas-do-conselho
- https://www.corinthians.com.br/clube/transparencia/conselho-deliberativo
- https://www.corinthians.com.br/clube/transparencia/presidencia-e-diretoria
- https://www.corinthians.com.br/clube/transparencia/regimentos

**Valor observado:** documentos oficiais relevantes para governança, eleições, demonstrações financeiras, conselhos, atas e regras institucionais.

**Fricção observada:** o acervo responde bem à pergunta “o que o clube publicou?”, mas não necessariamente à pergunta “como esta questão evoluiu?” ou “quais documentos de períodos diferentes preciso correlacionar para entender isto?”.

**Observação técnica:** durante a pesquisa, algumas páginas indexadas retornaram bloqueios a acesso automatizado. Isso é sinal de risco operacional para futura coleta, não prova de proibição de automação.

---

## 6.2 Imprensa e portais especializados

### Meu Timão

Referências:

- https://www.meutimao.com.br/
- https://www.meutimao.com.br/forum-do-corinthians/

Valor observado:

- cobertura histórica extensa;
- páginas e notícias sobre política, diretoria, Arena, estatuto e finanças;
- fórum público muito ativo;
- corpus útil para descobrir perguntas espontâneas da torcida.

Limite:

- notícia e fórum não constituem base canônica de fatos;
- conteúdo comunitário mistura opinião, hipótese, rumor e informação verificável.

### ge

Referência:

- https://ge.globo.com/futebol/times/corinthians/

Valor observado:

- cobertura profissional de finanças, política, processos e investigações;
- útil para descoberta, contexto e triangulação.

### UOL Esporte

Referência:

- https://www.uol.com.br/esporte/

Valor observado:

- cobertura frequente de política, Arena, investigação e Judiciário;
- útil para identificar divergências entre versões, documentos e cálculos.

### Central do Timão e Alambrado Alvinegro

Referências:

- https://centraldotimao.com.br/
- https://alambradoalvinegro.com.br/

Valor observado:

- ampliam diversidade de cobertura especializada e de atores institucionais ou comunitários.

---

## 6.3 Torcidas, movimentos e advocacy

### Gaviões da Fiel

Referência:

- https://gavioes.com.br/

A entidade declara publicamente entre seus objetivos acompanhar e fiscalizar o Corinthians e publica posicionamentos sobre temas institucionais.

É fonte primária para **suas próprias posições e atos**, mas não deve ser tratada como árbitro neutro sobre fatos controvertidos envolvendo terceiros.

### SAFiel

Referência:

- https://safiel.com.br/

É uma proposta de transformação societária e de governança. Sua existência demonstra demanda por discussões profundas sobre estrutura institucional, mas seu conteúdo possui natureza propositiva e interessada.

### Coletivo Voz Corinthiana

Referências documentais localizadas:

- https://www.meutimao.com.br/noticias-do-corinthians/509649/democratizar-para-profissionalizar-coletivo-convoca-torcida-para-reformar-estatuto-do-corinthians
- https://www.meutimao.com.br/noticias-do-corinthians/513979/coletivo-conclui-documento-sugestivo-a-reforma-do-estatuto-do-corinthians-confira-os-detalhes
- https://www.meutimao.com.br/noticias-do-corinthians/528526/coletivo-protocola-pedido-exigindo-votacao-aberta-e-nominal-na-reforma-do-estatuto-do-corinthians
- https://www.meutimao.com.br/noticias-do-corinthians/535465/coletivo-voz-corinthiana-anuncia-suspensao-das-atividades-no-dia-a-dia-do-corinthians

A pesquisa encontrou evidência de mobilização em torno de reforma estatutária, governança e voto nominal. Também encontrou relato de suspensão de atividades regulares em 2026 associado a desgaste, polarização, ataques e ameaças.

Esse caso reforça simultaneamente duas hipóteses:

1. existe interesse intenso por governança em parte da torcida;
2. produto de fiscalização deve evitar mecanismos que personalizem, gamifiquem ou facilitem perseguição de pessoas.

### Projeto Time do Povo

Referência:

- https://x.com/proj_timedopovo

Foi localizado como iniciativa pública ligada a debate e pressão institucional. Alcance, cadência e cobertura atual não foram medidos de forma suficiente para caracterização mais forte nesta versão.

---

## 6.4 Comunidades públicas

### Fórum Meu Timão

O fórum possui grande volume de discussões e recorrência de temas políticos, financeiros e de governança.

Isso demonstra atividade pública relevante, mas não permite inferir a proporção de toda a torcida que possui essas necessidades.

### Reddit r/Corinthians

Referência:

- https://www.reddit.com/r/Corinthians/

Foram encontrados debates sobre reforma estatutária, impeachment, SAF, finanças, conselhos e votações.

É um bom campo de discovery qualitativo e recrutamento de usuários digitais, mas não é amostra representativa da torcida.

---

## 6.5 Fontes primárias externas ao clube

Fontes potencialmente críticas para casos específicos:

- MPSP — https://www.mpsp.mp.br/
- TJSP — https://www.tjsp.jus.br/Processos
- CVM / Fundos.NET — https://cvmweb.cvm.gov.br/
- Dados Abertos CVM — https://dados.cvm.gov.br/
- Receita Federal / Dados Abertos — https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/dados-abertos/cadastros
- JUCESP — https://vre.jucesp.sp.gov.br/
- Diário Oficial do Estado de São Paulo — https://www.doe.sp.gov.br/
- Diário Oficial da Cidade de São Paulo — https://diariooficial.prefeitura.sp.gov.br/
- Diário Oficial da União — https://www.gov.br/pt-br/servicos/acessar-o-diario-oficial-da-uniao
- Portal da Transparência — https://portaldatransparencia.gov.br/

A existência dessas fontes fortalece a hipótese de disponibilidade pública para alguns domínios, mas não garante que todo contrato, processo, voto ou documento institucional esteja acessível.

---

# 7. Limitações e contraprovas da pesquisa documental

A pesquisa encontrou evidências favoráveis à tese do Fiel Fiscaliza, mas também limites importantes.

## 7.1 Alternativas atuais já resolvem parte relevante do problema

Google, imprensa, portal oficial, fóruns, redes sociais e bases públicas permitem responder muitas perguntas sem uma ferramenta nova.

O Fiel Fiscaliza somente se justifica se reduzir materialmente o esforço ou aumentar qualidade, contexto, auditabilidade ou recuperação histórica em tarefas relevantes.

## 7.2 O público observado é enviesado para usuários mais engajados

Fóruns, Reddit, organizadas e coletivos super-representam quem já discute política e governança.

A pesquisa documental não mostra se um torcedor menos especializado terá valor recorrente suficiente.

## 7.3 Informação pública é incompleta

Votos podem não ser nominais. Contratos podem ser privados. Processos podem ter restrições. Documentos podem não estar publicados. Algumas decisões podem ser conhecidas apenas por cobertura jornalística.

O produto precisa aceitar **desconhecido / não disponível publicamente** como resposta legítima.

## 7.4 Acesso público não equivale a reutilização irrestrita

A disponibilidade de uma página ou documento não significa licença para republicação integral.

Direitos autorais, regras de acesso, LGPD, dados pessoais e direitos de personalidade deverão ser aprofundados em documentos posteriores.

## 7.5 Automação perfeita não está demonstrada

As fontes possuem formatos e barreiras técnicas diferentes. A pesquisa encontrou páginas oficiais que não responderam de forma uniforme a acesso automatizado.

Isso enfraquece qualquer hipótese de que o MVP possa depender de coleta integral totalmente automática desde o primeiro dia.

## 7.6 Iniciativas específicas ainda precisam de caracterização primária

Discussões anteriores do projeto mencionaram iniciativas como **Expulsão Já** e **Painel dos Conselheiros**. A pesquisa documental desta rodada não obteve material primário suficiente para caracterizá-las com o mesmo rigor das iniciativas acima.

Elas não devem ser tratadas como inexistentes nem ter escopo atribuído por memória. Se forem relevantes ao fechamento do FF-0006/FF-0007, devem receber verificação específica adicional.

---

# 8. Segmentos candidatos após desk research

Nenhum segmento é declarado usuário primário nesta versão.

## 8.1 Torcedor interessado em compreender uma questão institucional

**Status:** EVIDÊNCIA DOCUMENTAL  
**Candidato a:** usuário primário

A pesquisa observou grande circulação de dúvidas e debates sobre dívida, Arena, estatuto, processos, eleições, conselhos e decisões.

O que ainda falta saber:

- com que frequência esse torcedor realiza pesquisa ativa;
- se aceita depender de imprensa como solução suficiente;
- qual profundidade tolera;
- se valoriza fonte/proveniência ou apenas uma explicação resumida;
- se retornaria a uma ferramenta dedicada.

---

## 8.2 Torcedor institucionalmente engajado

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Candidato a:** usuário primário

Organizadas, coletivos, fóruns e debates públicos demonstram existência clara de usuários que acompanham governança e precisam verificar ou reconstruir informação com maior frequência.

O que ainda falta saber:

- se as soluções atuais já são suficientes para power users;
- quais tarefas são repetitivas e dolorosas em vez de apenas intelectualmente interessantes;
- se desejam memória estruturada ou preferem pesquisa livre em notícias/documentos.

---

## 8.3 Pesquisador eventual de uma questão histórica

**Status:** EVIDÊNCIA DOCUMENTAL  
**Candidato a:** usuário primário ou secundário

A própria dispersão temporal de notícias, documentos e séries financeiras torna a tarefa plausível e recorrente no ecossistema.

Ainda falta evidência comportamental sobre frequência e intensidade.

---

## 8.4 Jornalista, comunicador ou criador de conteúdo

**Status:** EVIDÊNCIA DOCUMENTAL  
**Candidato a:** usuário secundário / power user

A cobertura observada demonstra trabalho frequente de reconstrução documental, financeira, processual e histórica.

Ainda precisa ser validado se uma ferramenta externa realmente reduziria o processo de apuração ou se jornalistas preferem seus próprios arquivos, contatos e rotinas.

---

## 8.5 Associado do SCCP, conselheiro ou participante institucional

**Status:** HIPÓTESE COM EVIDÊNCIA DOCUMENTAL PARCIAL  
**Candidato a:** usuário secundário

A pesquisa mostra intensa atividade institucional, audiências, assembleias e discussões de estatuto, mas não demonstra como esses participantes atualmente pesquisam informação nem se usariam uma ferramenta pública externa.

O produto não poderá depender de acesso interno ou privilegiado.

---

## 8.6 Pesquisador acadêmico, historiador ou analista externo

**Status:** EVIDÊNCIA DOCUMENTAL  
**Candidato a:** usuário secundário de longo prazo

A existência de estudos acadêmicos sobre governança corinthiana mostra uso real do clube como objeto de pesquisa.

Este segmento pode obter valor alto do acervo histórico acumulado, mas ainda não há justificativa para fazê-lo comandar o MVP.

---

# 9. Perguntas institucionais observadas

A pesquisa encontrou recorrência qualitativa das seguintes perguntas:

- Quanto o Corinthians deve e de onde saiu esse número?
- Qual é o estado real desta investigação ou processo?
- Essa decisão já vale ou ainda pode mudar?
- Como funciona a estrutura política do clube?
- Quem ou qual órgão tomou esta decisão?
- Existe registro de votação? O voto foi nominal?
- Qual documento original confirma esta notícia?
- Quem ocupava determinado cargo em uma data específica?
- Como um valor financeiro mudou ao longo do tempo?
- O que era conhecido quando uma decisão foi tomada?
- Quais fatos estão confirmados e quais continuam alegados ou contestados?
- O que não está disponível publicamente?

Essas perguntas constituem evidência de tarefas existentes, não prova de prioridade de MVP.

---

# 10. Jobs to Be Done após desk research

## JTBD-01 — Entender uma questão institucional que apareceu agora

**Quando** encontro uma notícia, debate ou crise sobre o Corinthians,  
**quero** compreender rapidamente o que aconteceu, qual é o contexto e quais informações são confirmadas,  
**para** formar uma visão informada sem depender apenas da narrativa de quem publicou primeiro.

**Status:** EVIDÊNCIA DOCUMENTAL  
**Prioridade candidata:** P0/P1

---

## JTBD-02 — Reconstruir a história e o estado atual de uma questão

**Quando** um assunto se desenvolve durante meses ou anos,  
**quero** consultar sua evolução temporal e seu estado atual,  
**para** saber o que mudou sem reler todo o fluxo de notícias.

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Prioridade candidata:** P0

Casos públicos que sustentam a hipótese incluem Arena, reforma estatutária, investigações e processos.

---

## JTBD-03 — Verificar uma afirmação

**Quando** vejo uma afirmação sobre dirigente, conselheiro, votação, dívida, documento, investigação ou decisão,  
**quero** identificar sua origem, status e evidência disponível,  
**para** distinguir o documentado do alegado, inferido ou desconhecido.

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Prioridade candidata:** P0

---

## JTBD-04 — Encontrar a fonte original

**Quando** encontro uma informação reproduzida em notícia, rede social ou debate,  
**quero** chegar ao documento, decisão, declaração ou registro de origem quando disponível,  
**para** verificar o conteúdo com menos intermediação.

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Prioridade candidata:** P0

---

## JTBD-05 — Entender um número financeiro no tempo

**Quando** encontro um valor sobre dívida, Arena, receita, despesa ou outro indicador financeiro,  
**quero** saber valor, data-base, conceito, método e fonte,  
**para** não comparar números diferentes como se representassem a mesma coisa.

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Prioridade candidata:** P0

A divergência pública entre cálculos relacionados à Arena em 2026 é um caso-teste especialmente forte para esta tarefa.

---

## JTBD-06 — Saber o estágio real de uma investigação ou processo

**Quando** existe uma investigação, processo ou decisão judicial relevante,  
**quero** saber qual é o estágio atual, o que já foi decidido e o que ainda pode mudar,  
**para** não confundir existência do procedimento com culpa nem decisão não definitiva com resultado encerrado.

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Prioridade candidata:** P0/P1  
**Risco editorial:** alto

---

## JTBD-07 — Reconstruir uma decisão institucional pública

**Quando** um órgão do clube toma uma decisão,  
**quero** saber qual órgão decidiu, quando, qual era a pauta, qual foi o resultado e, se publicamente nominal, como cada pessoa votou,  
**para** compreender a governança sem inferir informação que não foi publicada.

**Status:** EVIDÊNCIA DOCUMENTAL FORTE  
**Prioridade candidata:** P0/P1

### Restrição

Voto individual desconhecido deve permanecer desconhecido.

---

## JTBD-08 — Comparar versões ou claims conflitantes

**Quando** duas partes apresentam versões incompatíveis,  
**quero** identificar quem afirmou cada coisa, qual evidência acompanha cada versão e o que permanece contestado,  
**para** compreender a divergência sem exigir falsa equivalência nem falsa certeza.

**Status:** EVIDÊNCIA DOCUMENTAL  
**Prioridade candidata:** P1

---

## JTBD-09 — Recuperar atuação institucional publicamente documentada

**Quando** preciso compreender a trajetória institucional de uma pessoa ou órgão,  
**quero** encontrar cargos, mandatos, decisões, posições ou votações publicamente verificáveis relacionadas,  
**para** avaliar atuação institucional com memória documental em vez de impressão pessoal.

**Status:** EVIDÊNCIA DOCUMENTAL  
**Prioridade candidata:** P1

### Restrição

Esse Job não autoriza inferir voto secreto, aliança política, intenção, culpa ou posição não documentada.

---

## JTBD-10 — Descobrir o que era conhecido em determinada data

**Quando** preciso avaliar uma decisão ou declaração passada,  
**quero** saber quais informações e estados estavam publicamente documentados naquele momento,  
**para** evitar anacronismo e reconstrução histórica incorreta.

**Status:** EVIDÊNCIA DOCUMENTAL  
**Prioridade candidata:** P1/P2

---

## JTBD-11 — Perceber que uma questão mudou

**Quando** uma questão institucional que acompanho sofre mudança relevante,  
**quero** perceber a mudança e chegar à nova evidência,  
**para** não precisar monitorar manualmente dezenas de fontes.

**Status:** HIPÓTESE COM EVIDÊNCIA DOCUMENTAL PARCIAL  
**Prioridade candidata:** P2

A dispersão de fontes sustenta a plausibilidade, mas a necessidade real de alertas ou monitoramento pessoal ainda não foi demonstrada.

---

## JTBD-12 — Explicar uma questão para outra pessoa sem perder a fonte

**Quando** preciso compartilhar ou discutir um tema institucional,  
**quero** apontar para uma representação clara e rastreável da questão,  
**para** que outra pessoa consiga verificar a base factual sem depender apenas da minha interpretação.

**Status:** HIPÓTESE COM EVIDÊNCIA DOCUMENTAL PARCIAL  
**Prioridade candidata:** P1/P2

---

# 11. Matriz provisória de casos de uso

As prioridades abaixo são **candidatas** e não constituem decisão de MVP.

| Caso de uso | Evidência documental | Impacto institucional | Viabilidade aparente | Risco | Próximo passo |
|---|---|---|---|---|---|
| Encontrar fonte original | forte | muito alto | alta | baixo/médio | teste comportamental |
| Reconstruir cronologia + estado atual | forte | muito alto | média/alta | médio | teste comportamental |
| Contextualizar números financeiros | forte | muito alto | média/alta | médio/alto | teste comportamental |
| Reconstruir decisão/votação pública | forte | muito alto | média | alto | teste comportamental |
| Acompanhar processo/investigação | forte | muito alto | média | alto | teste comportamental |
| Comparar claims conflitantes | forte | alto | média/alta | alto | entrevistas + Fase 2 editorial |
| Histórico de cargos/mandatos | média | alto | alta | médio | entrevistas |
| Contratos relevantes | média | alto | baixa/média | alto | de-priorizar até validar disponibilidade |
| Alertas de mudança | parcial | médio/alto | média | médio | validar frequência real |
| Pesquisa acadêmica avançada | média | médio | média | baixo | não orientar MVP inicialmente |

---

# 12. Implicações candidatas para o futuro MVP

A pesquisa sugere que o MVP pode obter melhor relação valor/custo se começar por **capacidades transversais**, e não por tentar construir vários grandes módulos independentes.

Capacidades candidatas:

1. chegar à fonte original e à proveniência;
2. reconstruir cronologia e estado atual;
3. contextualizar valores financeiros no tempo;
4. reconstruir decisões institucionais públicas.

Esta seção registra **sugestões derivadas da pesquisa**, não requisitos aprovados.

A escolha formal do MVP pertence ao **FF-0008 — MVP_SPEC** após conclusão da pesquisa comportamental, definição de usuários prioritários e FF-0007.

Contratos completos, inferência de alianças políticas, rankings de atores e cobertura indiscriminada de todos os processos não possuem justificativa suficiente para o MVP nesta versão.

---

# 13. Não usuários prioritários e anti-use-cases

O Fiel Fiscaliza não deve otimizar sua experiência para:

- usuários que buscam escalações, transferências ou cobertura esportiva cotidiana sem consequência institucional;
- grupos que desejem apenas material para campanha eleitoral interna;
- pessoas buscando listas para assédio, intimidação ou perseguição;
- usuários interessados em dados pessoais privados;
- pessoas que esperem conclusões de culpa sem evidência suficiente;
- usuários que desejem rumores rápidos em vez de informação verificável;
- grupos que exijam manipulação editorial favorável a situação ou oposição;
- pessoas cuja principal necessidade seja entretenimento esportivo;
- usuários que desejem ranking simplista de “bons” ou “maus” dirigentes/conselheiros.

A pesquisa sobre o ambiente político online reforçou que histórico de pessoas, votos e posições pode possuir valor de fiscalização, mas também aumentar risco de personalização e assédio se mal projetado.

O produto deve fiscalizar **atos públicos e institucionais**, não gamificar indivíduos.

---

# 14. O que a pesquisa documental já permite afirmar

Com o grau de segurança adequado a esta fase:

- existem fontes públicas relevantes suficientes para justificar exploração de produto em vários domínios;
- informação institucional sobre o SCCP está distribuída entre fontes oficiais, imprensa, registros públicos e comunidades;
- tarefas de verificação de fonte, reconstrução temporal, compreensão financeira e acompanhamento de decisões/processos aparecem de forma recorrente no ecossistema público;
- há grupos de torcedores com interesse intenso em governança e transparência;
- soluções atuais resolvem partes importantes dessas tarefas, portanto o Fiel Fiscaliza precisa demonstrar ganho real e não apenas duplicar conteúdo;
- fontes críticas possuem limitações técnicas e documentais que impedem presumir automação total ou cobertura completa;
- votos, contratos, documentos ou estados podem legitimamente permanecer desconhecidos ou indisponíveis publicamente;
- nenhum segmento está validado ainda como usuário primário do MVP.

---

# 15. O que ainda NÃO pode ser afirmado

A pesquisa documental não permite afirmar que:

- a maioria dos corinthianos possui interesse recorrente por governança;
- o torcedor comum sente a mesma dor que jornalistas, pesquisadores ou usuários engajados;
- qualquer segmento utilizaria o produto repetidamente;
- os JTBD P0 propostos são necessariamente os mais importantes para o MVP;
- usuários preferem cronologia, tabela, perfil, busca ou qualquer interface específica;
- alertas são necessários;
- perfis de pessoas devem estar no MVP;
- existe demanda suficiente para cobertura ampla de contratos;
- todas as fontes críticas podem ser coletadas automaticamente;
- a lacuna de mercado está comprovada;
- as iniciativas atuais são insuficientes para todos os usuários.

Esses pontos permanecem perguntas de pesquisa.

---

# 16. Matriz das hipóteses do FF-0005

| Hipótese do FF-0005 | Estado após desk research | Leitura atual |
|---|---|---|
| Dor | fortalecida, não validada | há fricção observável de reconstrução/verificação, mas intensidade individual precisa de entrevistas |
| Valor de temporalidade e proveniência | fortalecida | múltiplos casos mostram perda de contexto, versões e números dependentes de data/fonte |
| Existência de usuários externos | fortalecida | há grupos públicos engajados e produção recorrente de pesquisa/conteúdo; recorrência de uso do produto ainda desconhecida |
| Lacuna frente a soluções atuais | plausível, não comprovada | nenhuma solução encontrada reuniu claramente todas as capacidades propostas, mas alternativas atuais resolvem partes importantes |
| Disponibilidade pública | parcialmente fortalecida | há muitas fontes úteis, porém lacunas, restrições e formatos heterogêneos são relevantes |
| Manutenção individual | desconhecida/parcial | ingestão híbrida parece possível; custo humano real só poderá ser estimado após recorte de MVP e protótipo operacional |
| Compreensão por não especialistas | desconhecida | pesquisa documental não substitui teste de compreensão com usuários |

---

# 17. Pesquisa comportamental necessária

Antes de promover segmentos ou JTBD para `VALIDADO PARA F1`, devem ser realizadas entrevistas semiestruturadas acompanhadas de pequenos testes de tarefa.

Objetivos:

- identificar episódios reais de busca institucional;
- medir esforço percebido e passos executados;
- descobrir fontes e atalhos atuais;
- identificar casos em que a solução atual já é boa o suficiente;
- compreender tolerância a incerteza e profundidade;
- descobrir diferenças entre usuário casual e power user;
- testar se proveniência e temporalidade realmente reduzem esforço;
- levantar contraprovas para as prioridades candidatas.

Não deve ser perguntado apenas se a pessoa “usaria um site de transparência”.

O foco deve ser comportamento passado e tarefa demonstrada.

---

# 18. Pacote de campo — critérios de recrutamento

## 18.1 Princípio

A amostra não pretende representar estatisticamente toda a torcida.

O objetivo é maximizar **diversidade de comportamento e contexto de uso**.

## 18.2 Tamanho recomendado

**5 a 8 participantes** para a primeira rodada.

## 18.3 Composição desejada para 8 participantes

- 2 torcedores comuns ou moderadamente engajados, incluindo ao menos 1 que não acompanhe política diariamente;
- 1 torcedor institucionalmente muito engajado;
- 1 associado do SCCP ou participante de espaços institucionais;
- 1 integrante de torcida organizada com interesse/atuação em fiscalização;
- 1 jornalista ou setorista;
- 1 comunicador/criador que trate de política, finanças ou governança;
- 1 pesquisador, advogado, contador, analista ou ator institucional com experiência real em documentação do SCCP.

A composição pode ser adaptada conforme disponibilidade, mas não deve ficar restrita a pessoas já politicamente hiperengajadas.

## 18.4 Critérios de inclusão

O participante deve conseguir relatar pelo menos um episódio real, recente ou histórico, em que tentou compreender ou verificar uma questão institucional relacionada ao Corinthians.

## 18.5 Critérios de diversidade

Buscar variedade em:

- intensidade de acompanhamento político;
- familiaridade com documentos oficiais;
- relação ou não com clube social/organizada;
- dependência de redes sociais versus pesquisa ativa;
- capacidade técnica de interpretar temas jurídicos/financeiros.

## 18.6 Critérios de exclusão metodológica

Evitar:

- amostra composta apenas por amigos próximos que já conhecem a proposta;
- participantes recrutados somente de uma corrente política;
- entrevistas exclusivamente com especialistas;
- selecionar pessoas porque já disseram gostar da ideia.

---

# 19. Pacote de campo — roteiro de entrevista

O roteiro é semiestruturado. A ordem pode variar, mas não se deve conduzir a pessoa para confirmar a tese do Fiel Fiscaliza.

## Bloco A — episódio real

1. Me conte a última vez em que você quis entender algo sobre política, administração, finanças, Justiça ou governança envolvendo o Corinthians.
2. O que fez você começar a procurar?
3. Qual era exatamente a pergunta que queria responder?
4. Como você saberia que a resposta estava boa o suficiente?

## Bloco B — caminho atual

5. Onde você começou a procurar?
6. Qual foi o segundo lugar?
7. Você usou Google, notícia, rede social, fórum, documento oficial ou perguntou para alguém?
8. Quais fontes costuma confiar mais? Quais costuma confirmar em outro lugar?
9. Você chegou à fonte/documento original?

## Bloco C — fricção

10. O que demorou mais?
11. Teve algo que você não conseguiu descobrir?
12. Precisou juntar informação de várias páginas?
13. Já desistiu de pesquisar alguma questão do Corinthians? Qual?
14. Alguma vez encontrou números ou versões incompatíveis e não soube qual estava correta?

## Bloco D — temporalidade

15. Foi fácil saber se a informação ainda estava atual?
16. Já descobriu depois que um status, valor ou decisão que usou estava desatualizado?
17. Quando um caso se prolonga por meses, como você descobre o que aconteceu desde a última vez que acompanhou?

## Bloco E — incerteza e confiança

18. Como prefere que uma ferramenta mostre que algo ainda é alegação, contestado, desconhecido ou está em investigação?
19. É melhor mostrar resposta incompleta explicitamente ou não mostrar nada?
20. O que faria você confiar em uma síntese feita por uma ferramenta independente?

## Bloco F — governança e pessoas

21. Você já tentou saber quem decidiu ou votou alguma coisa?
22. O que fez quando o voto individual não estava disponível?
23. Já pesquisou histórico institucional de um dirigente, conselheiro ou órgão?
24. Que informação seria útil e que informação seria invasiva ou desnecessária?

## Bloco G — formato, somente após reconstruir comportamento

25. Na situação que você contou, o que teria ajudado mais: cronologia, tabela, resumo, documento, busca, perfil, comparação ou outro formato?
26. O que uma ferramenta teria de fazer para realmente substituir parte do seu processo atual?

---

# 20. Pacote de campo — três testes de tarefa

Os testes devem observar **como a pessoa pesquisa hoje**, antes de apresentar qualquer solução futura do Fiel Fiscaliza.

Registrar tempo aproximado, número de fontes, erros, abandono, nível de confiança e resultado.

## TESTE T1 — Financeiro / Arena

### Pergunta

> “Há valores diferentes circulando sobre a dívida relacionada à Arena. Descubra por que esses valores podem ser diferentes e em qual fonte você confiaria para explicar isso para outra pessoa.”

### O que observar

- onde começa a pesquisa;
- se procura data-base e conceito;
- se identifica fontes oficiais ou apenas manchetes;
- se percebe que valores diferentes podem medir coisas diferentes;
- se chega a documentos do SCCP/CVM ou triangula imprensa;
- quanto tempo leva até considerar a resposta suficiente.

### Hipóteses testadas

- JTBD-03;
- JTBD-04;
- JTBD-05;
- valor de proveniência;
- valor de contextualização temporal.

---

## TESTE T2 — Processo / decisão não definitiva

### Pergunta

> “Você encontra uma notícia dizendo que uma decisão judicial mudou uma estrutura institucional do Corinthians. Descubra se essa mudança já está definitivamente valendo ou se ainda pode mudar.”

### O que observar

- se diferencia decisão de trânsito em julgado/definitividade;
- se busca tribunal ou apenas notícia;
- se identifica possibilidade de recurso quando documentada;
- se transforma manchete em certeza maior do que a fonte permite;
- dificuldade de entender linguagem processual.

### Hipóteses testadas

- JTBD-02;
- JTBD-03;
- JTBD-06;
- hipótese de compreensão por não especialistas.

---

## TESTE T3 — Governança / votação

### Pergunta

> “Escolha uma decisão relevante do Conselho ou de uma assembleia do Corinthians. Descubra qual órgão decidiu, qual foi o resultado e se existe registro público de como cada pessoa votou.”

### O que observar

- se encontra o órgão correto;
- se localiza ata, eleição, comunicado ou cobertura;
- se diferencia resultado coletivo de voto individual;
- se aceita ‘voto individual não disponível publicamente’ como resposta;
- se tenta inferir alinhamento ou voto sem evidência.

### Hipóteses testadas

- JTBD-04;
- JTBD-07;
- JTBD-09;
- valor de representar lacunas explicitamente.

---

# 21. Pacote de campo — template de Evidence Log

Uma linha por evidência documental ou comportamental relevante.

```text
evidence_id:
tipo: documental | entrevista | teste_tarefa
data_coleta:
fonte_ou_participante:
url_se_publica:
tema:
pergunta_observada:
jtbd_relacionado:
segmento_candidato:

evidencia_resumida:
evidencia_literal_se_necessaria:
forca_do_sinal: fraca | media | forte

contraevidencia:
solucao_atual_utilizada:
risco_de_vies:
implicacao_provisoria:
observacoes:
```

O campo `contraevidencia` é obrigatório sempre que houver evidência material contrária ou alternativa já suficiente.

---

# 22. Pacote de campo — template por participante

```text
participant_id: P01
perfil_hipotetico:
data:
canal:
consentimento: sim | nao
gravacao_autorizada: sim | nao | nao_gravado

episodio_real_descrito:
gatilho:
pergunta_original:
passos_executados:
fontes_utilizadas:
tempo_aproximado:
frustracoes:
resultado:
nivel_de_confianca:
incertezas_percebidas:
solucao_atual_foi_suficiente: sim | parcial | nao

teste_tarefa:
resultado:
tempo:
fontes_visitadas:
erros:
pontos_de_atrito:
resultado_corretamente_qualificado: sim | parcial | nao

jtbd_correlacionados:
evidencia_a_favor:
evidencia_contra:
novas_hipoteses:
observacoes:
```

---

# 23. Consentimento, privacidade e retenção da pesquisa

Formulação mínima sugerida antes da entrevista:

> “Estou pesquisando como pessoas buscam e verificam informações institucionais sobre o Corinthians para o projeto independente Fiel Fiscaliza. A participação é voluntária. Vou usar suas respostas para síntese de pesquisa; nenhuma fala será atribuída publicamente a você sem autorização específica. Você pode pular qualquer pergunta ou encerrar a conversa.”

Gravação deve possuir consentimento separado e explícito.

Participantes devem ser identificados na análise como `P01`, `P02` etc.

Dados de contato devem ficar separados das notas de análise quando possível.

Não publicar frases facilmente pesquisáveis que possam reidentificar participante sem autorização.

Áudio bruto, se existir, deve ter retenção limitada ao período necessário para conferência/transcrição e não deve ser preservado indefinidamente sem justificativa.

---

# 24. Critérios para concluir a pesquisa de FF-0006

A primeira rodada de pesquisa comportamental pode ser considerada suficiente para revisão de canonização quando:

- houver entrevistas com diversidade mínima de comportamento;
- existirem episódios reais, não apenas opiniões sobre a ideia;
- os principais JTBD candidatos tiverem evidência a favor e tentativa explícita de encontrar contraprova;
- alternativas atuais estiverem registradas;
- pelo menos os três testes de tarefa tiverem sido aplicados ou houver justificativa documentada para não aplicá-los;
- usuários primários e secundários puderem ser escolhidos com base em evidência;
- casos de uso prioritários puderem ser definidos sem depender de solução técnica específica;
- casos refutados ou depriorizados estiverem preservados;
- a pesquisa não exigir acesso privado ou privilegiado ao SCCP/Gaviões;
- os resultados forem compatíveis com manutenção individual e princípios do FF-0001.

Não existe obrigação de validar todas as hipóteses.

Um resultado válido da pesquisa pode ser reduzir significativamente o escopo inicialmente imaginado.

---

# 25. Critérios para promoção a CANONICAL

Antes de promover FF-0006 para CANONICAL, deve-se confirmar que:

- o usuário primário do MVP foi identificado com evidência suficiente para F1;
- usuários secundários relevantes foram distinguidos do usuário primário;
- necessidades são baseadas em tarefas e episódios observados, não em personas inventadas;
- casos de uso prioritários possuem evidência documental e comportamental adequada;
- soluções alternativas existentes foram consideradas;
- pelo menos algumas hipóteses foram ativamente desafiadas;
- não foram convertidas preferências de interface em necessidades sem validação;
- anti-use-cases e riscos de assédio/politização estão explícitos;
- nenhum caso de uso presume voto, culpa, aliança ou informação privada;
- a versão é compatível com FF-0001 e FF-0005;
- as decisões resultantes podem orientar FF-0007 e FF-0008.

A pesquisa documental de 2026-09-04 **não satisfaz sozinha esses critérios**.

---

# 26. Impacto e dependências documentais

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0005 — PRODUCT_VISION.

## Impacta

- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- futuros FF-0022/FF-0023 relacionados a arquitetura de informação e fluxos;
- priorização posterior de backlog e roadmap.

As sugestões de MVP desta versão não devem ser tratadas como requisitos canônicos antes do FF-0008.

---

# 27. Vigência

Esta versão permanece **DRAFT**.

**FF-0006 — USERS_AND_USE_CASES v0.2 // DRAFT**

A pesquisa documental foi incorporada, mas a etapa de evidência comportamental permanece pendente antes de qualquer proposta de canonização.
