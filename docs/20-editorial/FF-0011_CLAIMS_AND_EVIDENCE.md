# FF-0011 — CLAIMS_AND_EVIDENCE

**Nome do documento:** Claims and Evidence  
**ID:** FF-0011  
**Versão:** 0.1  
**Status:** DRAFT  
**Última revisão:** 2026-09-06  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define o modelo conceitual editorial de **Claims e evidências** do Fiel Fiscaliza.

Seu objetivo é tornar reproduzível a avaliação de afirmações factuais sem transformar:

- existência de fonte em confirmação automática;
- quantidade de links em robustez evidencial;
- alegação em fato;
- investigação em culpa;
- decisão não definitiva em encerramento definitivo;
- ausência de resultado em prova de inexistência;
- correlação em causalidade;
- mudança posterior em falsificação do estado histórico anterior.

O FF-0011 deve permitir responder, para cada afirmação material:

1. **qual proposição exata está sendo avaliada?**;
2. **a qual período ou momento ela se refere?**;
3. **quais evidências a sustentam, contradizem, limitam ou contextualizam?**;
4. **essas evidências são adequadas para essa proposição específica?**;
5. **existe contestação material?**;
6. **qual é o estado de verificação compatível com o conjunto evidencial atual?**;
7. **o que pode ser publicado e em qual linguagem?**;
8. **como o estado deve evoluir quando surge nova evidência sem apagar o histórico?**

Este documento estabelece um **modelo conceitual**, não um schema físico de banco de dados.

---

# 2. Autoridade e dependências

Este documento é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION v1.0 // CANONICAL;
- FF-0002 — PRE_CODEX_CHECKLIST v1.2 // CANONICAL;
- FF-0004 — GLOSSARY v1.0 // CANONICAL;
- FF-0007 — SCOPE v1.0 // CANONICAL;
- FF-0008 — MVP_SPEC v1.0 // CANONICAL;
- FF-0009 — EDITORIAL_POLICY v1.0 // CANONICAL;
- FF-0010 — SOURCE_POLICY v1.0 // CANONICAL.

Em particular, o FF-0011 deve preservar que:

- linguagem publicada não pode expressar certeza, abrangência, causalidade ou efeito jurídico maiores que a evidência;
- a classificação de uma fonte depende do Claim específico que ela pretende sustentar;
- fonte primária comprova com especial força o ato correspondente, não necessariamente a verdade material de toda narrativa nela contida;
- afirmações graves exigem diligência proporcionalmente maior;
- versões conflitantes não devem receber peso artificialmente igual nem ser resolvidas por preferência política;
- ausência de evidência não equivale automaticamente a evidência de ausência;
- conhecimento pessoal ou não público do mantenedor não substitui evidência pública auditável no núcleo factual do produto;
- estado atual conhecido não deve apagar o histórico;
- julgamento editorial substantivo permanece humano.

---

# 3. Princípio central

A unidade básica de verificação do Fiel Fiscaliza é uma **proposição suficientemente precisa para ser avaliada separadamente**.

> **Não se verifica uma pessoa, um veículo, uma gestão ou uma narrativa inteira. Verifica-se um Claim específico, no escopo e no tempo em que foi formulado.**

Consequentemente:

- uma mesma fonte pode sustentar um Claim e ser insuficiente para outro;
- uma mesma pessoa pode ter afirmações sustentadas, refutadas e indeterminadas em contextos diferentes;
- uma alegação pode estar documentalmente confirmada **como alegação** sem que seu conteúdo material esteja confirmado;
- um fato histórico pode permanecer sustentado mesmo depois de deixar de representar o estado atual;
- uma parte de uma frase estar correta não autoriza considerar toda a frase confirmada.

---

# 4. Definição conceitual de Claim

## 4.1 Claim

**Claim** é uma proposição declarativa cuja sustentação pode ser avaliada a partir de evidências identificáveis.

Exemplos conceituais:

- “O Conselho Deliberativo aprovou a proposta X em determinada data.”
- “O Ministério Público instaurou o procedimento Y.”
- “A demonstração financeira informa dívida de valor Z na data-base W sob determinado conceito.”
- “A pessoa A declarou apoio à chapa B em determinada ocasião.”
- “Não foi localizado registro público de voto individual no conjunto de fontes consultado até determinada data.”

O Claim deve ser formulado de forma suficientemente específica para que seja possível dizer **o que exatamente seria necessário para sustentá-lo ou contradizê-lo**.

## 4.2 Claim não é texto editorial completo

Uma Questão Institucional, parágrafo, título ou linha do tempo pode conter vários Claims.

O modelo não exige que cada frase corresponda a exatamente um Claim, mas afirmações materialmente independentes devem poder ser avaliadas separadamente.

## 4.3 Atomicidade proporcional

O Claim deve ser **atômico o suficiente para verificação independente**, sem exigir fragmentação artificial de cada detalhe linguístico.

Exemplo a evitar:

> “O dirigente X, aliado de Y, ocultou o documento para favorecer Z e causou prejuízo de R$ N.”

Essa frase contém múltiplas proposições distintas sobre:

- relação política;
- existência ou indisponibilidade do documento;
- intenção de ocultação;
- favorecimento;
- causalidade;
- valor financeiro.

Essas proposições não podem receber um único estado de verificação agregado.

---

# 5. Elementos conceituais mínimos de um Claim

Sem antecipar schema técnico, todo Claim material deve permitir identificar, quando aplicável:

- **proposição** — o que está sendo afirmado;
- **sujeito ou objeto institucional relevante**;
- **escopo** — limites necessários para não ampliar a afirmação;
- **referência temporal** — data, período ou estado a que se refere;
- **natureza editorial** — fato observável, declaração atribuída, alegação, estado processual, número, relação, interpretação ou outra classe relevante;
- **estado de verificação**;
- **estado de contestação**, quando houver;
- **evidências relacionadas**;
- **última avaliação** pelo Fiel Fiscaliza;
- **incertezas ou limitações materiais**;
- **histórico de mudança de estado**, quando aplicável.

Metadados técnicos, IDs, estruturas físicas e cardinalidades serão definidos na Fase 3.

---

# 6. Natureza editorial do Claim

A natureza do Claim e seu estado de verificação são dimensões diferentes.

Um Claim pode estar bem sustentado e ainda ser, por exemplo, um Claim **sobre uma alegação feita por terceiro**.

## 6.1 Claim factual descritivo

Descreve ato, evento, atributo ou estado observável/documentável.

Exemplo:

> “A ata registra aprovação por X votos a Y.”

## 6.2 Claim de declaração ou posição atribuída

Descreve que uma pessoa ou organização fez determinada manifestação.

Exemplo:

> “A chapa A declarou apoio à proposta B.”

A sustentação desse Claim não confirma automaticamente fatos externos narrados dentro da declaração.

## 6.3 Claim de alegação ou acusação atribuída

Descreve a existência e o conteúdo de alegação identificável.

Exemplo:

> “A parte X alegou que Y ocorreu.”

O Claim “X alegou Y” pode estar sustentado enquanto o Claim material “Y ocorreu” permanece insuficiente.

## 6.4 Claim procedimental, jurídico ou administrativo

Descreve estágio ou ato de investigação, processo, procedimento, decisão ou sanção.

Exemplo:

> “O juízo concedeu a liminar X em determinada data.”

O significado deve permanecer limitado ao efeito jurídico ou administrativo efetivamente documentado.

## 6.5 Claim numérico ou financeiro

Descreve valor, indicador ou cálculo com conceito, período, moeda, perímetro e método necessários à interpretação.

## 6.6 Claim relacional

Descreve relação verificável entre pessoas, órgãos ou organizações.

Exemplos:

- integrou determinada chapa;
- ocupou determinado cargo;
- declarou apoio em determinado contexto;
- foi nomeado por determinado ato.

Relação documentada não deve ser automaticamente ampliada para aliança permanente, intenção, coordenação ou pertencimento informal.

## 6.7 Claim derivado ou analítico

Resulta de cálculo, comparação, interpretação ou inferência realizada pelo próprio projeto.

Sua base, método e premissas devem ser identificáveis.

Quando a conclusão depender de interpretação, ela deve permanecer editorialmente distinguível de dado bruto.

## 6.8 Claim negativo ou de ausência

Afirma inexistência ou ausência de determinado registro, ato ou ocorrência.

É uma classe de risco especial porque normalmente exige demonstrar que o universo consultado é suficientemente completo para sustentar a negativa.

Quando isso não for possível, deve-se preferir um Claim mais restrito de **não localização**.

---

# 7. Evidência

Em continuidade ao FF-0004 e ao FF-0010, **evidência** é material verificável utilizado em relação a um Claim para:

- sustentar;
- contradizer;
- limitar;
- qualificar;
- contextualizar;
- estabelecer autoria ou atribuição;
- estabelecer referência temporal;
- demonstrar transformação ou cálculo.

A existência de uma fonte no sistema não cria automaticamente uma relação evidencial com todos os Claims relacionados ao mesmo assunto.

---

# 8. Relações entre evidência e Claim

Uma evidência pode desempenhar um ou mais papéis, desde que a relação seja explícita.

## 8.1 SUSTENTA

A evidência oferece suporte positivo à proposição formulada.

## 8.2 CONTRADIZ

A evidência oferece suporte material a proposição incompatível com o Claim.

Contradição não significa automaticamente que o Claim está refutado.

## 8.3 LIMITA OU QUALIFICA

A evidência mostra que o Claim precisa de escopo, ressalva, data, condição ou formulação mais restrita.

## 8.4 CONTEXTUALIZA

A evidência é relevante para compreensão, mas não é por si só prova direta da proposição.

## 8.5 ESTABELECE ATRIBUIÇÃO

A evidência comprova que determinada pessoa ou instituição realizou declaração, alegação ou ato comunicacional.

## 8.6 ESTABELECE MÉTODO OU DERIVAÇÃO

A evidência documenta dados de entrada, transformação, cálculo ou metodologia utilizada para produzir Claim derivado.

A implementação futura pode representar essas relações com nomes diferentes, desde que preserve semanticamente essas funções.

---

# 9. O que torna evidência suficiente

**Suficiência de evidência é uma avaliação do conjunto evidencial em relação ao Claim exato.**

Não existe número universal de fontes que garanta confirmação.

A avaliação deve considerar, conforme aplicável:

- especificidade da evidência para a proposição;
- autenticidade;
- competência ou proximidade da origem;
- adequação temporal;
- independência na raiz evidencial;
- interesse das fontes envolvidas;
- completude e contexto;
- qualidade de transformações intermediárias;
- existência de evidência contraditória relevante;
- metodologia quando houver cálculo ou análise;
- exaustividade quando o Claim for negativo;
- gravidade e risco da afirmação;
- capacidade de auditoria por terceiro.

## 9.1 Quantidade não substitui qualidade

Várias fontes que derivam da mesma raiz não devem ser contadas como confirmações independentes apenas por possuírem URLs diferentes.

## 9.2 Uma fonte pode bastar

Uma fonte única pode ser suficiente quando for diretamente competente para o ato afirmado e o Claim não extrapolar seu conteúdo.

Exemplo:

> uma decisão judicial pode bastar para sustentar o Claim de que aquele juízo proferiu determinada decisão naquela data.

Ela não basta automaticamente para sustentar toda alegação factual contida nos autos.

## 9.3 Evidência parcial deve restringir o Claim

Se a evidência sustenta apenas parte material da proposição, o correto é:

- reduzir a formulação;
- decompor o Claim;
- ou manter a parte não sustentada como insuficiente.

O sistema não deve utilizar “parcialmente confirmado” como atalho para preservar uma frase excessivamente ampla.

---

# 10. Estados formais de verificação

O estado de verificação responde apenas à pergunta:

> **“Qual é a relação atual entre este Claim específico e o conjunto de evidências adequadas disponível ao Fiel Fiscaliza?”**

Ele não é nota moral, reputacional ou política.

## 10.1 PENDENTE_DE_AVALIACAO

O Claim foi identificado, mas ainda não recebeu avaliação editorial suficiente.

Características:

- estado interno de trabalho;
- não deve ser apresentado ao público como fato;
- pode resultar de coleta automática, descoberta ou nova evidência ainda não revisada.

## 10.2 INSUFICIENTE

O conjunto de evidências disponível não é suficiente para sustentar nem para refutar adequadamente a proposição no nível de certeza formulado.

Pode ocorrer por:

- ausência de evidência localizada;
- evidência parcial;
- autenticidade incerta;
- fonte inadequada para o Claim;
- conflito material não resolvido;
- falta de exaustividade para Claim negativo;
- informação desatualizada para o estado pretendido;
- impossibilidade de distinguir adequadamente pessoas, valores ou eventos.

**INSUFICIENTE não significa falso.**

Na linguagem pública, conforme o caso, pode corresponder a:

- não confirmado;
- não determinado;
- desconhecido;
- não localizado;
- evidência insuficiente.

## 10.3 SUSTENTADO

O conjunto de evidências adequadas é suficiente para sustentar a proposição **nos limites exatos em que ela foi formulada**.

SUSTENTADO não significa:

- verdade metafísica absoluta;
- impossibilidade de correção futura;
- ausência de contestação;
- aprovação moral;
- validade eterna fora do período do Claim.

Um Claim sustentado pode ser posteriormente reavaliado se surgirem novas evidências relevantes.

## 10.4 REFUTADO

O conjunto de evidências adequadas é suficiente para sustentar a incompatibilidade da proposição exata com o que está documentado.

REFUTADO exige mais do que:

- alguém negar o Claim;
- existir fonte contraditória isolada;
- haver arquivamento, absolvição ou improcedência cujo fundamento não estabeleça a falsidade específica do Claim;
- a informação ter deixado de ser atual.

**Mudança temporal não é refutação.**

Exemplo:

> “X ocupava o cargo Y em 2024” pode permanecer sustentado mesmo que X não ocupe o cargo em 2026.

## 10.5 Não existe estado “PARCIALMENTE_SUSTENTADO” por padrão

Quando um Claim contém partes com estados diferentes, ele deve ser decomposto ou reformulado.

Isso evita que um rótulo intermediário esconda qual parte está realmente documentada.

---

# 11. Estado de contestação é dimensão separada

**Contestação não deve ser confundida com estado de verificação.**

Um Claim pode estar sustentado e ainda possuir contestação pública relevante.

Exemplo:

- o fato de uma decisão ter sido proferida pode estar SUSTENTADO;
- uma das partes pode contestar juridicamente seu fundamento ou recorrer dela.

## 11.1 SEM_CONTESTACAO_MATERIAL_CONHECIDA

Até a última avaliação, não foi identificada contestação material capaz de alterar a compreensão do Claim.

Isso não prova inexistência absoluta de contestação.

## 11.2 CONTESTADO

Existe manifestação identificável que nega, disputa, limita ou oferece versão materialmente incompatível com o Claim ou sua interpretação.

A mera existência de contestação não reduz automaticamente o estado de SUSTENTADO.

## 11.3 EVIDENCIA_CONFLITANTE

Existem evidências materialmente incompatíveis cuja tensão ainda não foi resolvida de maneira suficiente.

Quando o conflito impedir conclusão segura, o estado de verificação deve ser INSUFICIENTE.

Quando o conflito não atingir a proposição exata — por exemplo, contestar mérito sem negar que um ato ocorreu — o Claim pode continuar SUSTENTADO, com contestação visível.

---

# 12. Razão de insuficiência deve ser identificável

Sempre que material, um Claim INSUFICIENTE deve permitir indicar por que não foi confirmado.

Razões conceituais possíveis incluem:

- `SEM_EVIDENCIA_LOCALIZADA`;
- `EVIDENCIA_PARCIAL`;
- `AUTENTICIDADE_NAO_ESTABELECIDA`;
- `FONTE_INADEQUADA_PARA_O_CLAIM`;
- `EVIDENCIA_CONFLITANTE`;
- `EXAUSTIVIDADE_NAO_DEMONSTRADA`;
- `REFERENCIA_TEMPORAL_INSUFICIENTE`;
- `IDENTIDADE_AMBIGUA`;
- `METODO_NAO_REPRODUZIVEL`;
- `OUTRA_LIMITACAO_DOCUMENTADA`.

Esses nomes são conceituais e não obrigam enums técnicos idênticos na implementação.

---

# 13. De Claim atribuído para Claim material

Uma das separações mais importantes do projeto é entre:

1. **o Claim de que alguém afirmou algo**;
2. **o Claim de que o conteúdo afirmado aconteceu materialmente**.

Exemplo:

### Claim A

> “O Ministério Público alegou que houve irregularidade X.”

Pode estar **SUSTENTADO** pela manifestação do próprio MP.

### Claim B

> “Houve irregularidade X.”

Pode permanecer **INSUFICIENTE**, **SUSTENTADO** ou **REFUTADO** conforme evidências próprias.

O sistema nunca deve herdar automaticamente o estado do Claim A para o Claim B.

---

# 14. Investigações, processos e acusações

## 14.1 A existência do procedimento é um Claim próprio

Exemplo:

> “Existe investigação formal sobre X.”

Pode ser SUSTENTADO por fonte competente sobre o procedimento.

## 14.2 A conduta investigada é outro Claim

Exemplo:

> “X praticou a conduta investigada.”

Não herda confirmação pela mera existência da investigação.

## 14.3 Mudança de fase processual não reescreve estados anteriores

Se uma investigação evolui para denúncia, processo, decisão ou arquivamento:

- cada estado histórico continua verdadeiro no período correspondente;
- o estado atual deve ser atualizado;
- o histórico não deve ser sobrescrito como se as fases anteriores nunca tivessem existido.

## 14.4 Desfecho não refuta automaticamente o Claim material mais amplo

Arquivamento, absolvição, prescrição, nulidade, improcedência ou extinção devem ser modelados pelo conteúdo e fundamento exatos.

Eles só REFUTAM um Claim quando efetivamente sustentarem sua incompatibilidade factual ou jurídica no escopo formulado.

---

# 15. Decisões não definitivas

Um Claim sobre decisão deve separar, quando material:

- existência da decisão;
- conteúdo da decisão;
- efeitos vigentes;
- possibilidade ou existência de recurso;
- suspensão, reforma, anulação ou substituição posterior;
- definitividade, quando efetivamente estabelecida.

Exemplo:

> “A decisão X determinou Y em [data]”

pode estar SUSTENTADO mesmo que:

- exista recurso;
- a decisão não seja definitiva;
- ela venha a ser reformada posteriormente.

A reforma posterior cria novo estado temporal; não transforma automaticamente em falso o Claim histórico de que a decisão existiu e determinou Y naquele momento.

---

# 16. Claims financeiros e numéricos

Um valor só pode ser avaliado corretamente se o Claim preservar os qualificadores necessários.

Conforme o caso, deve conter:

- valor;
- moeda;
- data-base ou período;
- conceito;
- perímetro;
- natureza do valor;
- fonte;
- método quando derivado.

## 16.1 Números diferentes podem ser Claims diferentes

“Dívida de R$ X” e “dívida de R$ Y” não são necessariamente contraditórios se utilizarem:

- datas diferentes;
- conceitos diferentes;
- perímetros diferentes;
- critérios de atualização diferentes.

Antes de marcar CONTRADIZ, o projeto deve verificar se os Claims realmente possuem o mesmo significado.

## 16.2 Claim calculado pelo projeto

Quando o Fiel Fiscaliza produzir cálculo próprio:

- dados de entrada devem ser identificáveis;
- método deve ser reproduzível em nível proporcional;
- resultado deve ser distinguido de número oficialmente publicado por terceiro;
- premissas relevantes devem ser preservadas.

---

# 17. Claims sobre votos e relações políticas

## 17.1 Voto individual

Claim de voto individual só pode ser SUSTENTADO com evidência pública compatível com a precisão afirmada, como registro nominal adequado ou manifestação pública inequívoca quando aplicável.

Resultado coletivo não sustenta Claim de voto individual.

## 17.2 Apoio, aliança e pertencimento

Claims devem preferir a relação documentável específica:

- “integrou a chapa X”;
- “declarou apoio a Y em [data]”;
- “foi nomeado para o cargo Z por ato W”.

Esses Claims não autorizam automaticamente:

- “é aliado permanente”;
- “pertence ao grupo”;
- “vota com o grupo”;
- “age a mando de”.

Cada ampliação exige evidência própria.

---

# 18. Claims causais e de responsabilidade

Claims de causalidade ou responsabilidade exigem evidência adicional à mera sequência temporal.

Exemplo:

> “Após a decisão X, a dívida aumentou.”

é diferente de:

> “A decisão X causou o aumento da dívida.”

Para sustentar causalidade, deve existir base documental, metodológica ou analítica capaz de estabelecer a relação proposta e tratar explicações concorrentes materialmente plausíveis.

Responsabilidade institucional ou pessoal também deve ser formulada no nível exato que a evidência permite.

---

# 19. Claims negativos e ausência de evidência

## 19.1 “Não localizamos” é diferente de “não existe”

Quando a busca não possui exaustividade demonstrada, o Claim adequado é normalmente sobre o resultado da pesquisa do projeto.

Exemplo:

> “Até [data], o Fiel Fiscaliza não localizou registro público de voto individual nas fontes consultadas.”

Isso pode ser SUSTENTADO pela própria trilha de pesquisa e proveniência das consultas.

Não autoriza automaticamente:

> “Não existe registro de voto individual.”

## 19.2 Claim negativo forte exige universo adequado

Para sustentar inexistência, deve haver fundamento proporcional para considerar que:

- a base ou conjunto consultado é exaustivo naquele escopo;
- o período está coberto;
- os identificadores e filtros são adequados;
- sigilo, atraso ou lacuna de indexação não invalidam a conclusão.

---

# 20. Evidência contraditória e versões incompatíveis

Quando surge evidência contraditória, o sistema deve primeiro perguntar:

1. os Claims são realmente sobre a mesma proposição?;
2. utilizam o mesmo período e conceito?;
3. uma fonte apenas atribui alegação enquanto outra trata do fato material?;
4. existe diferença de competência, autenticidade ou proximidade?;
5. uma evidência é derivada da outra?;
6. o conflito pode ser resolvido restringindo o Claim?;

## 20.1 O sistema não faz média de versões

Versões conflitantes não devem ser conciliadas artificialmente por meio de frase intermediária sem suporte próprio.

## 20.2 Contraditório factual deve ser representado

Quando a contestação for material para interpretação, ela deve permanecer associada ao Claim ou à Questão Institucional de forma visível e atribuída.

## 20.3 Fonte contraditória relevante não pode ser omitida por conveniência

Evidência materialmente desfavorável à conclusão preferida deve ser considerada com o mesmo padrão metodológico das demais.

---

# 21. Publicabilidade por estado

O estado de verificação não substitui a Política Editorial, mas estabelece limites mínimos.

## 21.1 PENDENTE_DE_AVALIACAO

Não pode ser publicado como afirmação factual do Fiel Fiscaliza.

Pode existir apenas na fila interna de revisão.

## 21.2 INSUFICIENTE

Não pode ser publicado como fato confirmado.

Pode aparecer quando a própria incerteza for institucionalmente relevante, usando linguagem compatível como:

- não confirmado;
- não determinado;
- desconhecido;
- não localizado;
- segundo X, sem confirmação independente suficiente.

## 21.3 SUSTENTADO

Pode ser utilizado como base factual, desde que:

- a natureza editorial esteja corretamente representada;
- os qualificadores temporais e de escopo permaneçam;
- contestação material seja mostrada quando necessária;
- FF-0009 e FF-0010 sejam atendidos.

## 21.4 REFUTADO

Pode ser publicado como Claim refutado apenas quando sua relevância histórica ou editorial justificar e a formulação explicar **o que exatamente foi refutado e por qual evidência**.

Não deve ser usado para rotular permanentemente pessoa, grupo ou fonte como “refutado”.

---

# 22. “Fato confirmado” e estado SUSTENTADO não são sinônimos mecânicos

O FF-0009 utiliza “fato confirmado” como categoria de linguagem pública.

O FF-0011 utiliza **SUSTENTADO** como estado formal da relação entre Claim e evidência.

A passagem de um Claim SUSTENTADO para linguagem pública depende também de sua natureza.

Exemplo:

> Claim: “X declarou que Y ocorreu.” — SUSTENTADO.

O fato confirmado é **a declaração de X**.

Isso não autoriza publicar:

> “Y ocorreu.”

sem um Claim material próprio também SUSTENTADO.

---

# 23. Evolução temporal do estado de um Claim

Estados de verificação devem possuir histórico.

Exemplo conceitual:

`PENDENTE_DE_AVALIACAO → INSUFICIENTE → SUSTENTADO`

ou:

`SUSTENTADO → INSUFICIENTE`

se a única evidência central se tornar materialmente inválida e nenhuma outra sustentar adequadamente o Claim.

## 23.1 Mudança de estado não apaga estado anterior

Deve ser possível reconstruir:

- qual era o estado;
- em que momento;
- com base em quais evidências;
- qual nova evidência ou correção motivou a mudança.

O modelo temporal técnico será detalhado no FF-0014.

## 23.2 Novo fato não significa necessariamente novo estado do mesmo Claim

Quando a realidade muda, muitas vezes o correto é criar Claim temporalmente diferente, não refutar o anterior.

Exemplo:

- “X ocupa o cargo Y em 2025.”
- “Z ocupa o cargo Y em 2026.”

Os dois podem estar SUSTENTADOS em seus respectivos períodos.

---

# 24. Revisão, reformulação e identidade do Claim

## 24.1 Ajuste editorial sem mudança semântica material

Correções de ortografia ou clareza que não alterem a proposição podem preservar a identidade conceitual do Claim.

## 24.2 Mudança material de proposição

Se uma revisão altera sujeito, objeto, período, causalidade, abrangência ou significado verificável, o sistema deve preservar rastreabilidade da formulação anterior e tratar a mudança como nova versão ou novo Claim relacionado.

A implementação técnica será definida posteriormente.

## 24.3 Não reescrever silenciosamente Claim para fazê-lo caber na evidência

Quando a evidência não sustenta a formulação original, a revisão deve ser rastreável em vez de fingir que o Claim sempre teve formulação mais restrita.

FF-0012 definirá o fluxo de correção pública aplicável.

---

# 25. Evidência derivada, OCR, transcrição e IA

Conteúdo derivado pode auxiliar verificação, mas não deve apagar sua origem.

## 25.1 OCR e transcrição

Podem servir como índice ou camada de trabalho.

Quando palavra, número, negação, nome ou termo jurídico for material, a avaliação deve retornar ao original sempre que razoavelmente possível.

## 25.2 Tradução

Claim baseado em tradução deve preservar relação com o texto original e evitar excesso de certeza quando houver ambiguidade relevante.

## 25.3 IA

IA pode:

- sugerir Claims;
- extrair potenciais evidências;
- identificar conflitos;
- propor decomposição;
- resumir materiais;
- sugerir estado preliminar.

IA não pode, sozinha:

- promover Claim sensível a SUSTENTADO;
- marcar Claim como REFUTADO;
- resolver conflito evidencial material;
- inferir culpa, intenção, aliança, voto ou causalidade;
- transformar ausência de busca em inexistência.

A decisão substantiva final permanece humana.

---

# 26. Evidência mínima para Claims de maior risco

Sem criar regra fixa de quantidade de fontes, Claims de alto potencial de dano exigem salvaguardas reforçadas.

Por padrão, Claim material sobre crime, fraude, corrupção, desvio, favorecimento ilícito, conflito de interesse, culpa pessoal ou irregularidade grave **não deve ser marcado como SUSTENTADO exclusivamente com base em**:

- alegação da parte interessada;
- mera existência de denúncia, investigação ou processo;
- reportagem baseada apenas em fonte anônima de terceiro;
- screenshot sem origem verificável;
- rumor ou postagem sem documentação adequada;
- inferência por associação política;
- correlação temporal.

A avaliação precisa de evidência própria adequada ao **fato material afirmado**, proporcional à gravidade da conclusão.

---

# 27. Evidência de ausência em bases exaustivas

O FF-0010 admite que ausência possa sustentar Claim negativo quando a base for comprovadamente exaustiva no universo correspondente.

Para isso, o projeto deve conseguir justificar, conforme o caso:

- universo coberto;
- período;
- regra de inclusão;
- atualização;
- filtros e parâmetros;
- limitações conhecidas;
- ausência de sigilo ou lacuna capaz de invalidar a conclusão.

Se essa justificativa não for possível, o estado deve permanecer INSUFICIENTE para o Claim forte de inexistência, ainda que um Claim de não localização possa estar SUSTENTADO.

---

# 28. Claim e Questão Institucional

A **Questão Institucional** do FF-0008 é unidade de experiência do MVP.

Ela pode agrupar:

- Claims sustentados;
- alegações atribuídas;
- Claims insuficientes materialmente relevantes;
- Claims contestados;
- Claims históricos;
- evidências;
- eventos e mudanças de estado.

A Questão Institucional não deve receber um único rótulo global de “verdadeira”, “falsa”, “confirmada” ou “refutada”.

A verificação ocorre Claim a Claim.

---

# 29. Checklist mínimo de avaliação de Claim

Antes de atribuir ou alterar estado de verificação de Claim material, deve ser possível responder, conforme aplicável:

- [ ] A proposição está formulada de modo específico e verificável?
- [ ] O Claim mistura fatos, alegações, causalidade ou relações que deveriam ser separados?
- [ ] A referência temporal está clara?
- [ ] A natureza editorial do Claim está identificada?
- [ ] As fontes usadas são adequadas a esse Claim segundo FF-0010?
- [ ] Cada evidência possui relação identificável com o Claim?
- [ ] A evidência sustenta a proposição inteira ou apenas parte dela?
- [ ] Existem evidências contraditórias ou qualificadoras relevantes?
- [ ] As fontes realmente independentes foram distinguidas de republicações?
- [ ] Alegação atribuída foi separada do fato material alegado?
- [ ] Investigação/processo foi separado da conduta investigada?
- [ ] Decisão não definitiva foi separada de definitividade?
- [ ] Claim financeiro preserva conceito, período e perímetro?
- [ ] Claim político não extrapola vínculo documentado?
- [ ] Claim causal possui base adicional à sequência temporal?
- [ ] Claim negativo possui exaustividade suficiente ou deveria ser “não localizado”?
- [ ] Transformações automáticas foram conferidas quando materialmente sensíveis?
- [ ] A gravidade do Claim recebeu diligência proporcional?
- [ ] O estado escolhido descreve evidência, não preferência editorial ou reputação da pessoa?
- [ ] Contestação foi registrada separadamente do estado de verificação?
- [ ] A mudança de estado preservará histórico?

---

# 30. Exemplos conceituais

Os exemplos abaixo são fictícios e servem apenas para demonstrar o modelo.

| Claim | Evidência | Estado possível | Observação |
|---|---|---|---|
| “A ata registra aprovação por 120 a 80.” | Ata oficial autêntica | SUSTENTADO | Sustenta o resultado coletivo, não votos individuais. |
| “Conselheiro A votou a favor.” | Apenas resultado coletivo | INSUFICIENTE | Não inferir voto individual. |
| “O MP alegou irregularidade X.” | Manifestação oficial do MP | SUSTENTADO | Confirma a alegação atribuída. |
| “A irregularidade X ocorreu.” | Apenas a manifestação acusatória | INSUFICIENTE | A acusação não confirma o fato material. |
| “O juízo concedeu liminar Y.” | Decisão correspondente | SUSTENTADO | Não implica decisão definitiva. |
| “A decisão Y é definitiva.” | Decisão recorrível sem prova de trânsito | INSUFICIENTE | Definitividade exige evidência própria. |
| “A dívida era R$ X em 31/12, no conceito Z.” | Demonstração financeira correspondente | SUSTENTADO | Preservar conceito e data-base. |
| “A decisão A causou o aumento da dívida.” | Apenas sequência temporal | INSUFICIENTE | Causalidade exige base adicional. |
| “Não localizamos voto nominal nas fontes A/B/C até data D.” | Trilha de consulta preservada | SUSTENTADO | Claim é sobre a busca do projeto. |
| “Não existe voto nominal.” | Mesmas fontes sem prova de exaustividade | INSUFICIENTE | Ausência de busca não prova inexistência. |

---

# 31. Decisões reservadas aos documentos seguintes

## FF-0012 — CORRECTIONS_POLICY

Este documento não define:

- severidade de erro;
- fluxo de pedido de correção;
- quando uma mudança de estado exige nota pública;
- quando há retratação;
- formato de changelog público;
- tratamento operacional de contestação externa.

## FF-0013 — DOMAIN_MODEL

Este documento não define:

- entidade técnica `Claim`;
- IDs;
- campos físicos;
- cardinalidades;
- agregados;
- estrutura de objetos.

O FF-0013 poderá decidir que o modelo técnico represente os conceitos deste documento de outra forma, desde que preserve sua semântica canônica quando este documento for aprovado.

## FF-0014 — TEMPORAL_MODEL

Este documento não define tecnicamente:

- valid time;
- transaction time;
- versionamento físico;
- intervalos temporais;
- estratégia de histórico.

## FF-0019 — DATA_STORAGE

Este documento não define:

- JSON;
- banco relacional;
- arquivos;
- schema de persistência;
- estratégia de índices.

---

# 32. Critérios para revisão crítica e canonização

Antes de promover o FF-0011 para CANONICAL, deve-se confirmar que:

- não contradiz FF-0001;
- respeita FF-0009 e FF-0010;
- atende aos itens de Claims e evidências exigidos pelo Gate F2 do FF-0002;
- define Claim em nível conceitual sem antecipar schema técnico;
- separa natureza editorial de estado de verificação;
- define estados de verificação reproduzíveis;
- trata contestação como dimensão separada;
- separa alegação atribuída de verdade material;
- impede que investigação ou processo herde confirmação para a acusação;
- representa decisões não definitivas sem apagar sua existência histórica;
- trata Claims financeiros, políticos, causais e negativos com salvaguardas específicas;
- diferencia INSUFICIENTE de REFUTADO;
- não trata mudança temporal como refutação;
- evita estado genérico de “parcialmente sustentado” que esconda decomposição necessária;
- define evolução de estado sem sobrescrever histórico;
- preserva revisão humana em julgamentos substantivos;
- não transforma número de fontes ou score de confiança em regra mecânica de verdade;
- permite ao FF-0012 definir correções sem conflito;
- permite ao FF-0013 e FF-0014 escolher implementação técnica sem perder a semântica editorial.

---

# 33. Impacto documental

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- FF-0009 — EDITORIAL_POLICY;
- FF-0010 — SOURCE_POLICY.

## Impacta

- FF-0012 — CORRECTIONS_POLICY;
- FF-0013 — DOMAIN_MODEL;
- FF-0014 — TEMPORAL_MODEL;
- FF-0015 — EVENT_TAXONOMY;
- FF-0018 — INGESTION_PIPELINE;
- FF-0019 — DATA_STORAGE;
- FF-0020 — AUTOMATION_STRATEGY;
- FF-0023 — USER_FLOWS;
- FF-0025 — CONTENT_STYLE_GUIDE;
- FF-0026 — UI_COPY_CATALOG;
- FF-0027 — TEST_STRATEGY;
- FF-0029 — LEGAL_AND_REPUTATIONAL_RISK;
- FF-0032 — MAINTENANCE;
- FF-0038 — DEFINITION_OF_DONE.

---

# 34. Vigência

Esta versão permanece **DRAFT** até revisão crítica e aprovação explícita.

**FF-0011 — CLAIMS_AND_EVIDENCE v0.1 // DRAFT**
