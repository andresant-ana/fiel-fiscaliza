# FF-0010 — SOURCE_POLICY

**Nome do documento:** Source Policy  
**ID:** FF-0010  
**Versão:** 0.2  
**Status:** DRAFT  
**Última revisão:** 2026-09-04  
**Responsável:** André  
**Projeto:** Fiel Fiscaliza  

---

# 1. Propósito

Este documento define a política de fontes do Fiel Fiscaliza.

Seu objetivo é estabelecer regras reproduzíveis para decidir:

- que tipos de fonte podem sustentar informação publicada;
- como classificar a relação entre uma fonte e a afirmação que ela sustenta;
- quando uma fonte primária deve ter prioridade;
- quando uma fonte secundária pode ser suficiente;
- quando múltiplas fontes são necessárias;
- como avaliar independência entre fontes;
- como utilizar imprensa, veículos especializados, estudos e produção acadêmica;
- como tratar documentos oficiais, registros públicos e manifestações de partes interessadas;
- como tratar redes sociais e declarações públicas;
- como lidar com fontes removidas, alteradas ou posteriormente indisponíveis;
- quais metadados mínimos de proveniência devem ser preservados;
- como separar autoridade sobre um ato da verdade material de alegações contidas na própria fonte;
- como tratar bases estruturadas, consultas e datasets;
- como avaliar afirmações negativas baseadas na ausência de registro;
- como preservar a cadeia entre fonte original, reprodução, transcrição, tradução e dado derivado;
- como evitar que quantidade de links seja confundida com qualidade de evidência.

O FF-0010 trata de **adequação, classificação, prioridade, proveniência e uso editorial de fontes**.

Ele não substitui:

- FF-0009 — EDITORIAL_POLICY, responsável pelas regras gerais de redação, prudência, atribuição e julgamento editorial;
- FF-0011 — CLAIMS_AND_EVIDENCE, responsável pelo modelo conceitual de Claims, estados de verificação e suficiência de evidência para cada afirmação;
- FF-0012 — CORRECTIONS_POLICY, responsável pelo tratamento formal de correções, retratações e fontes posteriormente invalidadas;
- FF-0031 — SOURCE_REGISTRY, responsável pelo inventário operacional de fontes utilizadas pelo projeto.

---

# 2. Autoridade e dependências

Este documento é subordinado ao:

- FF-0001 — PROJECT_CONSTITUTION v1.0 // CANONICAL;
- FF-0002 — PRE_CODEX_CHECKLIST v1.2 // CANONICAL;
- FF-0004 — GLOSSARY v1.0 // CANONICAL;
- FF-0007 — SCOPE v1.0 // CANONICAL;
- FF-0008 — MVP_SPEC v1.0 // CANONICAL;
- FF-0009 — EDITORIAL_POLICY v1.0 // CANONICAL.

Em particular, esta política deve preservar que:

- proveniência faz parte estrutural do dado;
- fontes primárias devem ser priorizadas quando adequadas e disponíveis;
- uma fonte primária é autoridade sobre o ato, documento ou declaração que emitiu, não necessariamente sobre a verdade material de todas as alegações contidas nela;
- alegações devem permanecer atribuídas enquanto não houver evidência suficiente para tratá-las como fato independente;
- afirmações mais graves exigem diligência proporcionalmente maior;
- acesso público não equivale automaticamente a adequação para armazenamento ou republicação integral;
- o MVP não pode depender de acesso institucional privilegiado;
- conhecimento pessoal ou não público do mantenedor não substitui evidência pública auditável no núcleo factual do produto;
- o estado conhecido na última verificação não deve ser apresentado como garantia de tempo real.

A revisão crítica desta versão não identificou conflito canônico bloqueante com esses documentos.

---

# 3. Princípio central

A regra central desta política é:

> **A adequação de uma fonte depende da afirmação específica que ela pretende sustentar, do período a que essa afirmação se refere e da cadeia de evidência disponível — não de um rótulo global de confiança atribuído ao emissor.**

Consequentemente:

- uma fonte pode ser primária para uma afirmação e insuficiente para outra;
- uma fonte oficial pode comprovar que um órgão publicou ou decidiu algo sem comprovar materialmente toda acusação existente no documento;
- uma reportagem pode ser secundária para um acontecimento e primária para uma entrevista realizada pelo próprio veículo;
- uma postagem em rede social pode comprovar que determinada pessoa publicou uma declaração sem comprovar o fato narrado nessa declaração;
- uma fonte correta para um estado histórico pode ser inadequada para descrever o estado conhecido mais recente;
- várias publicações diferentes podem representar apenas uma única cadeia de evidência se todas reproduzirem a mesma origem.

O Fiel Fiscaliza não deve manter um ranking absoluto de veículos, instituições ou pessoas como “fontes confiáveis” ou “fontes não confiáveis” que substitua análise caso a caso.

Também não deve utilizar pontuação numérica global de “confiabilidade da fonte” como atalho para decidir se um Claim está suficientemente sustentado.

---

# 4. Fonte, evidência e afirmação não são a mesma coisa

## 4.1 Fonte

É a origem identificável de informação consultada ou preservada pelo projeto.

Pode ser, entre outros:

- documento;
- página institucional;
- base pública;
- decisão;
- ata;
- demonstração financeira;
- publicação jornalística;
- artigo acadêmico;
- entrevista;
- vídeo;
- áudio;
- postagem pública;
- dataset;
- resultado de consulta estruturada;
- registro arquivado.

## 4.2 Evidência

É a relação pela qual determinado conteúdo de uma fonte sustenta, contradiz, qualifica ou contextualiza uma afirmação.

Uma fonte não é automaticamente evidência adequada para qualquer afirmação relacionada ao mesmo assunto.

## 4.3 Afirmação ou Claim

É a proposição específica cuja sustentação está sendo avaliada.

A modelagem formal de Claim será definida em FF-0011.

## 4.4 Consequência prática

A pergunta editorial correta não é apenas:

> “Esta fonte é boa?”

É:

> **“Esta fonte é adequada para sustentar esta afirmação, neste nível de certeza, neste contexto temporal e para este significado específico?”**

---

# 5. Classificação principal por relação com a afirmação

A classificação como primária, secundária ou de descoberta é relativa ao Claim considerado.

## 5.1 Fonte primária

Fonte diretamente ligada ao ato, documento, decisão, declaração, registro ou evidência específica que está sendo descrita.

Exemplos possíveis:

- ata para comprovar conteúdo registrado na própria ata;
- estatuto para comprovar regra estatutária;
- decisão judicial para comprovar o que o juízo decidiu;
- manifestação do Ministério Público para comprovar o que o órgão alegou ou requereu;
- demonstração financeira para comprovar os valores apresentados naquele documento e sob seus conceitos;
- comunicado oficial para comprovar que a instituição comunicou determinada posição;
- postagem autenticada de uma pessoa para comprovar que ela publicou aquela declaração;
- resultado oficial de votação para comprovar o resultado formal registrado.

Uma fonte primária **não é automaticamente prova da verdade material de todas as afirmações nela contidas**.

## 5.2 Fonte secundária

Fonte que descreve, interpreta, resume, contextualiza ou investiga informação cuja origem material está em outro ato, documento, evento ou conjunto de evidências.

Exemplos frequentes:

- reportagem que resume uma decisão judicial;
- matéria que contextualiza demonstração financeira;
- artigo analítico sobre governança;
- cobertura jornalística de reunião ou eleição;
- estudo que consolida dados provenientes de fontes anteriores.

Uma fonte secundária pode possuir alta qualidade e grande valor editorial.

“Secundária” não significa “ruim”.

## 5.3 Fonte de descoberta ou orientação

Fonte útil para localizar documentos, identificar nomes, datas, hipóteses de pesquisa ou caminhos de investigação, mas que não deve ser tratada automaticamente como base suficiente para afirmação factual material.

Exemplos possíveis:

- mecanismos de busca;
- agregadores;
- fóruns;
- wikis;
- posts sem documentação;
- comentários;
- compilações sem proveniência adequada.

Sempre que possível, o projeto deve seguir a cadeia até uma fonte mais adequada antes de publicar o fato material.

## 5.4 Uma mesma fonte pode ocupar papéis diferentes

Uma reportagem que contém uma entrevista exclusiva pode ser:

- fonte primária para provar o que o entrevistado declarou ao veículo;
- fonte secundária para um fato externo narrado pelo entrevistado;
- fonte de descoberta para um documento mencionado mas não disponibilizado.

A classificação deve acompanhar a afirmação, não apenas o URL.

---

# 6. Classificações complementares por natureza do emissor

As categorias abaixo não formam uma hierarquia automática de confiança.

## 6.1 Fonte oficial ou institucional

Publicada ou emitida por instituição, órgão, autoridade ou representante autorizado em nome da entidade correspondente.

Exemplos:

- SCCP;
- Conselho Deliberativo;
- órgão estatutário;
- Judiciário;
- Ministério Público;
- CVM;
- Receita Federal;
- Diário Oficial;
- entidade reguladora;
- empresa em comunicação formal própria.

Fonte oficial é especialmente adequada para comprovar **o ato da própria instituição**, mas deve ser analisada como fonte de parte interessada quando faz alegações sobre fatos controvertidos que ultrapassam esse ato.

A condição de “oficial” não torna o emissor competente para afirmar qualquer coisa fora de sua atribuição.

## 6.2 Fonte de parte interessada

Fonte emitida por pessoa ou organização que possui interesse direto na controvérsia, decisão ou resultado descrito.

Exemplos possíveis:

- dirigente defendendo sua gestão;
- chapa eleitoral descrevendo adversário;
- empresa explicando contrato do qual participa;
- autor de ação judicial;
- réu ou parte apresentando sua defesa;
- torcida ou movimento defendendo determinada interpretação institucional.

Essas fontes podem ser primárias e indispensáveis para registrar posição, alegação, defesa ou ato da parte.

Entretanto, não devem ser tratadas automaticamente como corroboradores independentes da verdade material de sua própria narrativa.

## 6.3 Fonte jornalística

Veículo ou profissional que realiza cobertura, apuração, entrevista, análise ou contextualização jornalística.

Seu valor depende de fatores como:

- proximidade com o fato;
- transparência sobre origem da informação;
- acesso a documentos;
- apuração própria;
- correções;
- especialização;
- independência em relação a outras publicações.

## 6.4 Fonte especializada ou acadêmica

Produção que acrescenta conhecimento técnico, histórico, jurídico, contábil, econômico, estatístico ou institucional relevante.

Pode incluir:

- artigos acadêmicos;
- livros;
- pesquisas;
- pareceres públicos;
- análises técnicas assinadas;
- bases especializadas;
- profissionais ou entidades com expertise demonstrável.

Especialização aumenta pertinência para certas perguntas, mas não elimina necessidade de avaliar método, data, conflito de interesse e base documental.

## 6.5 Fonte comunitária ou social

Conteúdo produzido em fóruns, redes sociais, comunidades, torcidas, movimentos ou por indivíduos fora de publicação institucional formal.

Pode ser útil para:

- descobrir questões;
- localizar documentos;
- identificar manifestações públicas;
- registrar mobilização ou posicionamento quando isso for o próprio objeto da afirmação.

Não deve ser promovida automaticamente a prova independente de fatos materiais apenas por repercussão ou volume de compartilhamentos.

## 6.6 Fonte arquivística ou reprodução preservada

Cópia, snapshot, mirror ou registro preservado de conteúdo anteriormente disponível.

Pode ser útil para provar o estado histórico de uma página ou documento quando a origem, data e integridade forem suficientemente identificáveis.

Não deve ocultar que o material consultado é uma reprodução ou captura, e não necessariamente o endereço original ainda disponível.

## 6.7 Fonte estruturada ou base consultável

Base de dados, API, sistema de consulta, exportação oficial ou dataset que permite recuperar registros a partir de filtros, parâmetros ou identificadores.

Seu uso exige atenção adicional ao escopo da base, cobertura, atualização, filtros aplicados, possibilidade de lacunas e data de extração.

O fato de uma consulta retornar zero resultados não permite, por si só, concluir inexistência do objeto procurado.

---

# 7. Critérios de avaliação de uma fonte

A adequação deve considerar, conforme o caso:

## 7.1 Proximidade

Quão diretamente a fonte está ligada ao ato ou informação afirmada?

## 7.2 Autenticidade

Há segurança razoável de que o documento, conta, publicação ou registro é genuíno e corresponde ao emissor indicado?

## 7.3 Especificidade

A fonte sustenta exatamente a afirmação publicada ou apenas algo parecido, mais amplo ou mais restrito?

## 7.4 Competência ou autoridade

O emissor possui competência institucional ou técnica para praticar o ato ou produzir a informação correspondente?

## 7.5 Independência

A fonte deriva de apuração própria ou apenas reproduz outra origem?

## 7.6 Interesse

O emissor possui interesse material, político, jurídico, comercial ou reputacional no resultado da questão?

Interesse não invalida automaticamente a fonte, mas altera o tipo de conclusão que ela pode sustentar sozinha.

## 7.7 Adequação temporal

A fonte corresponde ao período ou estado histórico que está sendo representado?

## 7.8 Completude e contexto

O conteúdo consultado possui informação suficiente para evitar distorção por fragmento, corte ou resumo excessivo?

## 7.9 Estabilidade e auditabilidade

A origem pode ser reencontrada, versionada, localizada internamente ou preservada de forma rastreável?

## 7.10 Metodologia

Quando a fonte apresenta cálculo, estimativa, estudo, ranking ou consolidação, o método necessário para interpretar o resultado é identificável?

## 7.11 Cadeia de transformação

O conteúdo consultado é original ou passou por:

- reprodução;
- recorte;
- transcrição;
- tradução;
- resumo;
- OCR;
- cálculo derivado;
- agregação;
- outra transformação?

Transformações podem ser legítimas, mas precisam ser identificadas quando forem capazes de alterar significado ou auditabilidade.

## 7.12 Cobertura e exaustividade

Quando a conclusão depende de saber se uma base ou conjunto contém **todos** os registros relevantes, existe fundamento para considerar a fonte exaustiva naquele escopo?

Uma fonte excelente para localizar ocorrências não é automaticamente adequada para provar ausência.

---

# 8. Prioridade de fontes primárias

Quando uma fonte primária adequada estiver disponível, o Fiel Fiscaliza deve preferi-la para sustentar afirmações objetivas sobre o ato, documento ou registro correspondente.

Exemplos:

- para afirmar qual regra consta do Estatuto, preferir o texto estatutário vigente à notícia que o resume;
- para afirmar o teor de decisão judicial, preferir a decisão à reportagem sobre ela;
- para afirmar resultado formal de votação, preferir ata ou registro oficial adequado;
- para afirmar valor publicado em demonstração financeira, preferir a própria demonstração;
- para afirmar o que uma pessoa declarou, preferir a gravação, publicação original ou entrevista direta quando disponível.

## 8.1 Prioridade não significa exclusividade

Fonte secundária pode ser necessária para:

- contexto;
- descoberta;
- interpretação técnica;
- identificação de contradições;
- explicação de impacto;
- apuração de fatos não documentados na fonte oficial;
- reconstrução de eventos cujo registro primário seja incompleto.

## 8.2 Prioridade não significa deferência à narrativa oficial

O projeto deve preferir fonte oficial para comprovar o ato oficial correspondente.

Isso não obriga o Fiel Fiscaliza a aceitar como verdade material alegações favoráveis à própria instituição apenas porque foram publicadas oficialmente.

## 8.3 Documento normativo ou declaratório não prova automaticamente prática efetiva

Um estatuto pode provar qual regra estava formalmente prevista.

Ele não prova, sozinho, que a regra foi efetivamente cumprida em determinado caso.

Da mesma forma, um comunicado pode provar que uma instituição declarou ter feito algo, mas a execução material da ação pode exigir evidência adicional.

---

# 9. Quando uma única fonte pode ser suficiente

Não existe regra geral de “duas fontes para todo fato”.

Uma única fonte pode ser suficiente quando:

- é primária, autêntica e diretamente competente para o ato afirmado;
- a afirmação está limitada ao que a fonte realmente estabelece;
- não existe contestação material conhecida que altere a compreensão;
- não existe fonte materialmente incompatível ignorada pelo projeto;
- a gravidade e o risco não exigem diligência adicional;
- a informação é verificável de forma auditável.

Exemplos conceituais:

- um estatuto oficial pode bastar para afirmar que determinada regra consta daquela versão;
- uma ata oficial pode bastar para afirmar que determinado resultado coletivo foi registrado;
- uma decisão judicial pode bastar para afirmar que aquele juízo decidiu determinada coisa naquela data;
- uma postagem autenticada pode bastar para afirmar que a pessoa publicou aquela declaração.

Isso não significa que a mesma fonte baste para conclusões mais amplas derivadas desses atos.

---

# 10. Quando múltiplas fontes ou diligência adicional são necessárias

A exigência aumenta quando:

- a afirmação é grave ou potencialmente danosa;
- a verdade material é contestada;
- a principal fonte é parte interessada;
- a fonte disponível apenas relata informação de terceiro não acessível;
- existem versões materialmente conflitantes;
- um número depende de método, perímetro ou cálculo não evidente;
- uma afirmação causal está sendo formulada;
- há risco relevante de erro de identidade;
- a informação pode ter mudado e a fonte é antiga;
- a fonte original está indisponível e só existem reproduções;
- a afirmação deriva de material incompleto, editado ou fora de contexto;
- a conclusão ultrapassa o ato formal documentado;
- a conclusão depende da **ausência** de registro;
- uma transcrição, tradução, OCR ou resumo automático contém termo materialmente sensível;
- uma fonte contraditória relevante existe e pode alterar a formulação.

O FF-0011 definirá como a suficiência da evidência se relaciona aos estados formais dos Claims.

---

# 11. Independência entre fontes

Quantidade de publicações não equivale a quantidade de evidências independentes.

## 11.1 Cadeia comum de origem

Se dez matérias reproduzem o mesmo comunicado, documento ou relato inicial, elas podem representar apenas **uma raiz evidencial** para o fato material correspondente.

O projeto deve procurar identificar, quando relevante:

- quem publicou primeiro;
- qual é a fonte original;
- se houve apuração adicional independente;
- se os veículos apenas reescreveram a mesma informação.

## 11.2 Circularidade

O Fiel Fiscaliza deve evitar confirmar uma afirmação utilizando fontes que, na prática, citam umas às outras de forma circular.

Exemplo:

- veículo A cita B;
- B cita C;
- C cita A.

A multiplicação de URLs não cria corroboração independente.

## 11.3 Independência não exige ausência total de relação

Duas fontes podem compartilhar parte do contexto e ainda possuir evidência independente se cada uma tiver acesso próprio a documentos, observação, dados ou apuração distintos.

## 11.4 Independência deve ser avaliada na raiz evidencial

Dois veículos diferentes que tiveram acesso independente ao mesmo documento podem oferecer confirmação de autenticidade ou contexto, mas continuam compartilhando o mesmo documento como raiz para o conteúdo material daquele documento.

A análise deve distinguir independência de publicação de independência de evidência.

## 11.5 Seleção de fontes não pode ser orientada pelo resultado desejado

Quando existirem fontes relevantes que sustentem, contradigam ou qualifiquem materialmente uma afirmação, o projeto não deve selecionar apenas aquelas compatíveis com uma narrativa preferida.

O dever editorial é representar a evidência materialmente relevante, não montar um conjunto de citações que apenas confirme a conclusão desejada.

---

# 12. Uso aceitável de imprensa

Imprensa pode ser fonte legítima e importante do Fiel Fiscaliza.

Ela pode:

- revelar acontecimentos;
- localizar documentos;
- registrar declarações;
- obter entrevistas;
- fornecer contexto histórico;
- realizar apuração original;
- comparar versões;
- identificar consequências práticas;
- cobrir eventos sem registro institucional completo.

## 12.1 Quando uma fonte jornalística secundária pode ser suficiente

Uma reportagem secundária pode ser suficiente para sustentar uma afirmação factual limitada quando, em conjunto:

- não há fonte primária razoavelmente acessível ou o fato não gera naturalmente documento primário público;
- a reportagem é específica sobre o que afirma;
- autoria, data e veículo são identificáveis;
- há indicação suficiente da base da apuração;
- não existe contradição material conhecida ignorada;
- a formulação do Fiel Fiscaliza não é mais forte que a reportagem permite;
- a gravidade e o risco não exigem corroboração adicional.

Quando esses critérios não forem atendidos, a reportagem pode continuar servindo como contexto, pista ou informação atribuída ao veículo sem ser promovida a fato confirmado próprio.

## 12.2 Quando a imprensa sustenta fato material por apuração original

Uma reportagem pode ter força evidencial maior quando contém, por exemplo:

- documentos obtidos e descritos de forma verificável;
- entrevista direta;
- observação própria de evento;
- dados originais;
- múltiplas fontes independentes;
- metodologia de apuração suficientemente transparente.

A publicação jornalística continua devendo ser avaliada Claim a Claim.

## 12.3 Informação atribuída a fontes anônimas da imprensa

Reportagens baseadas em fontes anônimas podem ser editorialmente relevantes, mas o Fiel Fiscaliza não deve converter automaticamente o conteúdo anônimo em fato confirmado próprio.

Por padrão, quando material para a questão, deve ser representado como:

- informação reportada pelo veículo;
- alegação atribuída à reportagem;
- pista para buscar confirmação adicional.

Afirmações graves não devem depender exclusivamente de fonte anônima de terceiro para serem apresentadas pelo Fiel Fiscaliza como fato material confirmado.

## 12.4 Republicação em cadeia

Veículos que apenas reproduzem notícia de outro veículo não constituem nova confirmação independente.

Quando possível, citar a apuração original.

---

# 13. Fontes especializadas, técnicas e acadêmicas

Fontes especializadas podem ser especialmente úteis para:

- interpretação contábil;
- análise jurídica;
- contexto histórico;
- estatística;
- governança;
- estrutura societária;
- finanças;
- avaliação de metodologia.

O projeto deve avaliar:

- autoria e qualificação;
- método;
- dados utilizados;
- data da análise;
- possibilidade de reprodução ou conferência;
- conflitos de interesse;
- distinção entre dado observado e opinião técnica.

Parecer técnico não transforma automaticamente interpretação em fato quando houver leituras profissionais razoavelmente concorrentes.

Uma opinião especializada também não substitui o ato oficial correspondente quando o Claim é sobre o conteúdo ou estado jurídico daquele ato.

---

# 14. Documentos e canais oficiais do SCCP

Canais e documentos do SCCP possuem alta relevância para comprovar atos institucionais praticados ou comunicados pelo próprio clube.

Podem ser fonte primária para, entre outros:

- estatuto e regimentos publicados;
- composição institucional oficialmente divulgada;
- atas;
- demonstrações financeiras;
- comunicados;
- resultados oficialmente divulgados;
- decisões e atos dos órgãos quando publicados pelo canal competente.

## 14.1 Canal oficial não equivale a verdade universal

Quando um comunicado do SCCP faz afirmação controvertida sobre terceiro, investigação, contrato, responsabilidade ou fato externo, a publicação comprova que **o SCCP afirmou aquilo**.

Sua verdade material deve ser avaliada separadamente quando relevante.

## 14.2 Órgão específico deve ser identificado

Sempre que possível, registrar qual órgão, departamento ou representante emitiu o documento, evitando atribuir genericamente “ao Corinthians” posição que pertença apenas a parte da estrutura institucional.

## 14.3 Página atual não substitui documento histórico

Quando uma página institucional atual descreve composição, regra ou estrutura, ela não deve ser usada automaticamente para reconstruir período histórico anterior.

A fonte deve corresponder ao momento que está sendo representado.

---

# 15. Judiciário, Ministério Público e órgãos públicos

Documentos emitidos por autoridades públicas são fontes primárias especialmente relevantes para comprovar seus próprios atos processuais, administrativos ou regulatórios.

Exemplos:

- decisão judicial para o conteúdo da decisão;
- andamento processual para o estado registrado no sistema;
- manifestação do Ministério Público para a existência e conteúdo da manifestação;
- Diário Oficial para ato publicado;
- registro da CVM para documento ou ato arquivado na plataforma correspondente.

## 15.1 Procedimento não comprova acusação

Uma petição, denúncia, manifestação, inquérito ou ação de órgão público pode ser fonte primária para comprovar que a acusação ou procedimento existe.

Ela não é automaticamente fonte suficiente para o Fiel Fiscaliza afirmar como fato a conduta material acusada.

## 15.2 Sistemas de consulta possuem escopo próprio

Ausência de resultado em busca pública não autoriza concluir inexistência de procedimento sem saber se:

- a base é exaustiva;
- há sigilo;
- há atraso de indexação;
- a consulta utilizou identificadores corretos;
- o tipo de procedimento aparece naquele sistema.

## 15.3 Metadado processual não substitui necessariamente a peça

Uma movimentação, resumo de andamento ou campo estruturado pode ser suficiente para comprovar o estado exibido pelo sistema.

Quando a afirmação depender do fundamento, alcance ou teor de uma decisão, deve-se preferir a peça correspondente quando acessível.

---

# 16. Redes sociais e declarações públicas

Postagem pública pode ser fonte primária para provar **a própria manifestação**, desde que haja segurança razoável sobre autoria e integridade.

## 16.1 Verificação mínima de autoria

Conforme a relevância e o risco, considerar:

- conta oficial ou publicamente associada à pessoa/instituição;
- contexto consistente;
- URL original;
- data e horário quando disponíveis;
- confirmação por canal relacionado;
- ausência de sinais de montagem, adulteração, paródia, impersonação ou comprometimento da conta.

Selo de verificação de plataforma, quando existir, é apenas um sinal e não substitui análise de contexto.

## 16.2 Conteúdo da postagem

O projeto deve distinguir:

> “X afirmou em rede social que Y ocorreu”

 de:

> “Y ocorreu”.

A primeira afirmação pode ser sustentada pela postagem; a segunda pode exigir evidência adicional.

## 16.3 Prints

Screenshot isolado possui menor auditabilidade que publicação original.

Pode ser útil quando o conteúdo foi removido, mas deve ser tratado com cautela e, quando possível, acompanhado de:

- URL original;
- data da captura;
- arquivo ou snapshot preservado;
- corroboradores independentes;
- contexto necessário para verificar autoria.

Print sem origem verificável não deve sustentar sozinho afirmação material grave.

## 16.4 Conteúdo privado ou de grupo fechado

Conteúdo obtido de conta privada, grupo fechado ou ambiente restrito não deve ser tratado como fonte pública apenas porque alguém enviou uma captura ao projeto.

O MVP não depende desse tipo de acesso.

## 16.5 Conteúdo sintético, manipulado ou de autenticidade duvidosa

Áudio, vídeo, imagem ou texto com sinais razoáveis de manipulação, edição enganosa, geração sintética ou atribuição falsa deve permanecer não autenticado até verificação adequada.

O Fiel Fiscaliza não deve usar material de autenticidade materialmente duvidosa como base exclusiva de afirmação grave.

---

# 17. Entrevistas, vídeos, áudios e declarações ao vivo

Gravação original, vídeo, áudio ou entrevista pode ser fonte primária para comprovar o que foi declarado.

O projeto deve preservar, quando relevante:

- quem falou;
- onde;
- quando;
- em qual contexto;
- trecho ou localização suficiente para conferência;
- link ou referência à gravação original.

Transcrição automática ou legenda não deve ser presumida perfeita quando uma palavra puder alterar materialmente o significado.

Em caso de dúvida relevante, deve-se conferir o áudio ou vídeo original.

## 17.1 Transcrição, OCR e tradução são camadas derivadas

Transcrição, OCR e tradução podem tornar uma fonte mais acessível, mas não substituem silenciosamente o original.

Quando uma palavra, número, nome, negação, qualificador ou termo jurídico puder alterar materialmente a conclusão, a conferência deve voltar ao conteúdo original sempre que razoavelmente possível.

Tradução própria ou automática deve ser identificável como tradução quando a formulação exata for material.

---

# 18. Fontes fornecidas por usuários ou terceiros

Pessoas podem indicar links, documentos e pistas ao Fiel Fiscaliza.

## 18.1 Indicação não é validação

O envio de uma fonte por usuário, conselheiro, dirigente, integrante de torcida, jornalista ou qualquer terceiro não altera seu padrão editorial.

Ela deve ser avaliada pelas mesmas regras aplicáveis às demais fontes.

## 18.2 Material não público

Por padrão, material privado, confidencial ou não publicamente acessível não deve se tornar base factual indispensável do MVP.

Pode servir como pista de pesquisa apenas quando seu uso for legítimo e não contrariar segurança, privacidade, direitos ou o requisito de independência de acesso privilegiado.

## 18.3 Vazamentos e obtenção ilícita

O Fiel Fiscaliza não deve solicitar, incentivar, adquirir por invasão nem publicar conteúdo obtido por acesso não autorizado ou vazamento ilegal.

A simples chegada espontânea de material ao projeto não elimina a necessidade de avaliar legalidade, autenticidade, proporcionalidade e risco antes de qualquer uso.

Casos excepcionais não cobertos por esta política exigem revisão dos documentos de segurança/legal aplicáveis antes de publicação.

## 18.4 Exposição acidental não transforma informação privada em fonte pública adequada

Credenciais expostas, diretórios mal configurados, arquivos deixados acidentalmente acessíveis, endpoints sem proteção ou outros erros de segurança não devem ser tratados como autorização pública de acesso apenas porque uma URL responde tecnicamente.

O projeto não deve explorar falha de acesso para obter conteúdo fora de sua finalidade pública legítima.

---

# 19. Fontes removidas, alteradas ou posteriormente indisponíveis

A indisponibilidade posterior de uma fonte não apaga automaticamente o fato de que ela existiu nem invalida todo uso histórico feito enquanto estava disponível.

Entretanto, o projeto deve tornar a mudança de disponibilidade rastreável.

## 19.1 Estados relevantes

Conforme o caso, uma fonte pode ser descrita como:

- disponível no endereço original;
- substituída por nova versão;
- alterada desde a coleta;
- removida;
- indisponível temporariamente;
- disponível apenas em arquivo ou reprodução preservada;
- acesso posteriormente restrito;
- origem não mais verificável com segurança.

A modelagem formal desses estados pertence às fases posteriores.

## 19.2 Não substituir silenciosamente

Se um URL original desaparecer e outro material for utilizado em seu lugar, o projeto deve preservar a distinção entre:

- a fonte originalmente usada;
- a evidência atualmente acessível;
- eventual snapshot ou reprodução.

## 19.3 Continuidade da afirmação

Quando uma fonte central se torna impossível de verificar, a afirmação correspondente deve ser reavaliada conforme sua gravidade, redundância evidencial e material preservado.

Uma afirmação grave sustentada apenas por fonte que se tornou não verificável pode exigir redução de certeza ou retirada até nova evidência.

O FF-0011 e FF-0012 definirão os efeitos formais sobre Claim e correção.

## 19.4 Versões divergentes da mesma origem

Se duas versões do mesmo documento ou página divergirem materialmente, o projeto não deve presumir automaticamente que a mais recente torna a anterior “errada”.

Deve determinar, quando possível, se houve:

- correção;
- substituição normativa;
- atualização de estado;
- edição sem explicação;
- erro anterior;
- simples mudança temporal.

A relação entre versões deve permanecer rastreável.

---

# 20. Versionamento, snapshots e integridade

Fontes institucionais podem mudar sem manter histórico público claro.

Quando o conteúdo for material para reconstrução temporal, o projeto deve avaliar preservação de elementos que permitam demonstrar qual versão foi consultada.

Podem ser utilizados, conforme arquitetura e legalidade:

- data de coleta;
- hash criptográfico;
- identificador de versão;
- título e data do documento;
- número do processo ou ato;
- snapshot;
- arquivo local quando redistribuição ou preservação forem apropriadas;
- referência a serviço de arquivamento público.

## 20.1 Hash não prova verdade

Hash demonstra integridade de uma cópia em relação àquela versão preservada.

Não comprova autoria, autenticidade jurídica ou verdade material do conteúdo por si só.

## 20.2 Snapshot não transforma reprodução em original

Quando uma versão arquivada for usada, isso deve permanecer identificável na proveniência.

## 20.3 Assinatura, selo ou metadado técnico são sinais, não atalhos absolutos

Assinatura digital, certificado, protocolo, identificador oficial ou metadado técnico podem fortalecer autenticidade.

Seu significado deve ser interpretado conforme o sistema que os emitiu e não transforma automaticamente todo conteúdo em verdade material.

---

# 21. Metadados mínimos de proveniência

Toda fonte utilizada para sustentar informação factual material deve permitir preservar, quando aplicável e disponível:

- **emissor ou publicador**;
- **título, identificação ou descrição suficiente da fonte**;
- **tipo ou natureza da fonte**;
- **URL, identificador público ou referência documental**;
- **data de publicação, emissão ou ocorrência documental**;
- **data de coleta ou verificação pelo Fiel Fiscaliza**;
- **data de vigência, competência ou período coberto**, quando distinta da publicação e material para a interpretação;
- **relação temporal ou versão relevante**;
- **localizador interno**, quando necessário, como página, seção, item, timestamp ou trecho identificável;
- **status de acessibilidade**, quando material;
- **origem original e eventual reprodução/arquivo**, quando diferentes;
- **transformações relevantes**, como transcrição, OCR, tradução, cálculo ou agregação;
- **informação suficiente para distinguir fonte primária, secundária ou de descoberta no contexto da afirmação**, ainda que a implementação futura utilize estrutura diferente.

Quando algum metadado não existir ou não puder ser determinado, isso não deve ser inventado.

## 21.1 Proveniência mínima não é schema físico

Esta seção define informação conceitualmente necessária.

FF-0013, FF-0014 e FF-0019 decidirão como esses elementos serão modelados e armazenados tecnicamente.

---

# 22. Localização precisa dentro de documentos extensos

Um link para documento de centenas de páginas pode ser tecnicamente uma fonte e ainda oferecer baixa auditabilidade prática.

Quando uma afirmação depender de trecho específico de documento extenso, o Fiel Fiscaliza deve preservar, quando possível:

- página;
- seção;
- cláusula;
- item;
- artigo;
- timestamp;
- identificador equivalente.

O objetivo é reduzir o custo de o usuário reencontrar a evidência sem retirar o trecho de seu contexto material.

Quando o trecho isolado puder induzir leitura enganosa, o localizador deve permitir acessar contexto suficiente da seção correspondente.

---

# 23. Acesso público, preservação e republicação

Uma fonte ser acessível publicamente não significa automaticamente que o Fiel Fiscaliza deve copiá-la ou republicá-la integralmente.

A estratégia preferencial deve utilizar a menor exposição necessária para entregar auditabilidade, considerando:

- link para origem;
- metadados;
- hash;
- referência de página ou seção;
- citação curta quando apropriada;
- resumo próprio;
- preservação técnica quando legítima e necessária.

Direitos autorais, termos de uso, privacidade e risco jurídico serão aprofundados em FF-0028 e FF-0029.

---

# 24. Fontes de acesso restrito, paywall ou cadastro

Uma fonte pode ser legitimamente consultável e ainda não ser livremente acessível a todo usuário.

Quando conteúdo material depender de fonte com paywall, cadastro, autenticação legítima ou outra restrição de acesso:

- a restrição deve ser considerada na auditabilidade;
- deve-se buscar fonte pública equivalente quando existir;
- o projeto não deve burlar controle de acesso;
- não deve redistribuir integralmente conteúdo apenas para contornar a restrição;
- a fonte restrita não deve ser apresentada como se fosse livremente auditável por todos.

Por padrão, o núcleo mínimo do MVP deve evitar depender exclusivamente de fonte restrita para uma afirmação central quando houver alternativa pública adequada.

Uma fonte legitimamente restrita pode ainda ser usada de forma atribuída e proporcional quando não houver alternativa melhor, desde que sua restrição seja transparente e o Claim não dependa de acesso privilegiado incompatível com o MVP.

---

# 25. Fontes corrigidas, retratadas ou invalidadas

O Fiel Fiscaliza deve acompanhar, quando materialmente relevante, se uma fonte:

- publicou correção;
- alterou conteúdo;
- retirou alegação;
- substituiu documento;
- teve sua autenticidade questionada;
- foi invalidada por fonte de autoridade superior para o ponto correspondente.

O histórico da existência da fonte pode continuar relevante, mas sua capacidade de sustentar afirmações atuais deve ser reavaliada.

“Invalidação” deve ser entendida em relação ao Claim específico: uma fonte pode deixar de sustentar uma afirmação e continuar válida para comprovar que determinada declaração ou versão existiu historicamente.

O fluxo formal de correção pertence ao FF-0012.

---

# 26. Adequação temporal e atualidade da fonte

Uma fonte correta em determinado momento pode estar desatualizada para representar estado posterior.

Antes de usar uma fonte para descrever estado conhecido mais recente, o projeto deve considerar:

- data da fonte;
- frequência com que a informação pode mudar;
- existência de versão posterior;
- eventos conhecidos que possam ter alterado o estado;
- data da última verificação.

Fonte antiga pode continuar sendo a fonte correta para um fato histórico.

“Antiga” não significa “errada”; significa que seu escopo temporal precisa ser explicitado.

---

# 27. Fontes financeiras

Para valores financeiros, a fonte deve ser avaliada não apenas pelo valor publicado, mas pelo conceito representado.

Sempre que materialmente necessário, o projeto deve buscar identificar:

- data-base ou período;
- moeda;
- entidade ou perímetro contábil;
- natureza do valor;
- critério de reconhecimento;
- se é realizado, estimado, provisionado, nominal, atualizado ou consolidado;
- método de cálculo quando derivado.

## 27.1 Preferência

Demonstrações financeiras, notas explicativas, documentos de auditoria, documentos regulatórios e instrumentos contratuais adequados devem ter preferência para os conceitos que efetivamente documentam.

Reportagens e análises especializadas podem contextualizar, explicar e comparar, mas não devem apagar diferenças conceituais existentes na fonte financeira original.

## 27.2 Cálculo próprio

Quando o Fiel Fiscaliza produzir cálculo derivado, as fontes de entrada e o método devem ser identificáveis.

O cálculo próprio não deve ser apresentado como número oficialmente publicado por terceiro.

## 27.3 Auditoria externa não transforma toda afirmação contábil em verdade absoluta

Relatório de auditoria deve ser interpretado conforme seu escopo, opinião, ressalvas, materialidade e período.

A existência de auditoria não autoriza atribuir ao auditor afirmações que não constem de sua opinião nem elimina a necessidade de compreender notas e critérios contábeis relevantes.

---

# 28. Fontes sobre eleições, votos e relações políticas

Afirmações sobre voto individual, composição de chapa, candidatura, apoio formal ou vínculo político exigem fonte compatível com a precisão da relação afirmada.

## 28.1 Voto individual

Preferir registro nominal público, ata, documento eleitoral ou manifestação pública inequívoca do próprio votante quando aplicável.

Resultado coletivo não sustenta inferência de voto individual.

## 28.2 Apoio e aliança

Autodeclaração, documento de chapa, declaração pública de apoio, nomeação ou vínculo formal podem comprovar relações específicas.

Nenhuma dessas evidências autoriza automaticamente concluir aliança permanente, coordenação ampla ou concordância total além do vínculo documentado.

## 28.3 Lista produzida por terceiro não substitui prova da relação

Compilações de “aliados”, “oposição”, “grupo” ou “base” devem ser tratadas como análise ou classificação do emissor, salvo quando cada vínculo puder ser reconstruído por evidência própria adequada.

---

# 29. Fontes sobre investigações, processos e acusações

A fonte deve ser escolhida conforme **qual Claim está sendo feito**.

Exemplos:

| Claim | Fonte adequada preferencial |
|---|---|
| “O Ministério Público instaurou procedimento X.” | registro ou documento oficial do órgão, quando disponível |
| “A parte X alegou Y.” | peça processual, manifestação original ou registro oficial correspondente |
| “O juízo decidiu Z.” | decisão judicial correspondente |
| “A imprensa publicou acusação X.” | publicação jornalística original |
| “A pessoa praticou a conduta acusada.” | exige evidência própria suficiente para esse fato; a existência da acusação não basta |

A mesma peça pode comprovar perfeitamente a existência de uma acusação e ser insuficiente para comprovar a conduta acusada.

---

# 30. Fontes de conhecimento enciclopédico e compilações

Wikis, enciclopédias abertas, compilações, bancos colaborativos e páginas de resumo podem ser úteis para orientação.

Por padrão, fatos materialmente relevantes do Fiel Fiscaliza devem ser rastreados até fonte mais direta ou especializada quando isso for razoavelmente possível.

Essas fontes não devem ser utilizadas como atalho para evitar reconstrução de proveniência.

---

# 31. Bases estruturadas, APIs, consultas e datasets

Quando um Claim depender de resultado obtido por consulta a base estruturada, o projeto deve preservar informação suficiente para tornar a consulta reproduzível ou auditável quando razoavelmente possível.

Isso pode incluir:

- nome da base ou sistema;
- publicador;
- data e horário de extração quando material;
- filtros aplicados;
- termos ou identificadores pesquisados;
- parâmetros da consulta;
- período coberto;
- versão do dataset ou endpoint quando houver;
- campos utilizados;
- paginação ou limite de resultados quando capaz de afetar a conclusão;
- transformações ou cálculos feitos após a extração.

## 31.1 Resultado de consulta não é automaticamente retrato completo da realidade

Uma base pode possuir atraso, recorte, erro, sigilo, cobertura parcial ou regra de indexação própria.

O Claim deve respeitar o que a base realmente permite concluir.

## 31.2 Dado derivado precisa preservar sua linhagem

Quando o Fiel Fiscaliza combinar, limpar, agregar ou calcular dados provenientes de uma ou mais fontes, deve ser possível identificar:

- dados de entrada;
- transformações relevantes;
- método;
- momento da extração;
- diferença entre valor original e resultado produzido pelo projeto.

---

# 32. Afirmações negativas baseadas na ausência de registro

Claims como:

- “não existe documento”;
- “não houve publicação”;
- “não consta processo”;
- “não houve voto registrado”;
- “ninguém declarou apoio”;

exigem padrão mais rigoroso do que simplesmente não encontrar resultado em uma busca.

Antes de transformar ausência de resultado em afirmação negativa, o projeto deve considerar:

- se a fonte consultada é exaustiva para aquele universo;
- se o período pesquisado está completo;
- se podem existir sigilo, atraso, indexação incompleta ou alteração de nomenclatura;
- se os termos e identificadores utilizados são suficientes;
- se foram consultadas fontes alternativas proporcionais ao risco;
- se a formulação correta deve ser “não localizamos” em vez de “não existe”.

Por padrão, quando a exaustividade não puder ser demonstrada, o Fiel Fiscaliza deve preferir formulações de **não localização** ou **não confirmação**, em consonância com o FF-0009.

---

# 33. Automação de coleta e avaliação de fonte

Automação pode:

- descobrir novas publicações;
- detectar alterações;
- baixar ou indexar documentos quando permitido;
- extrair metadados;
- sugerir classificação preliminar;
- comparar versões;
- identificar links quebrados;
- calcular hashes.

Automação não deve, sem controles posteriores aprovados:

- declarar uma fonte autêntica apenas por aparência;
- transformar fonte secundária em confirmação independente;
- decidir sozinha que uma acusação está comprovada;
- ignorar conflito de interesse;
- preencher metadado desconhecido por inferência;
- concluir que ausência em busca significa inexistência;
- elevar automaticamente o status editorial de um Claim;
- tratar transformação automática, como OCR ou tradução, como se fosse o original sem marcar sua derivação.

A publicação automática de mudanças mecânicas dependerá de FF-0011, FF-0018, FF-0020 e dos controles de qualidade aplicáveis.

---

# 34. Relação com o SOURCE_REGISTRY

FF-0010 define **as regras editoriais gerais de uso de fontes**.

FF-0031 — SOURCE_REGISTRY deverá registrar as fontes concretas utilizadas operacionalmente pelo projeto, incluindo, quando pertinente:

- publicador;
- mecanismo de acesso;
- formato;
- frequência esperada de mudança;
- estratégia de coleta;
- limitações conhecidas;
- criticidade operacional.

Uma fonte estar cadastrada no SOURCE_REGISTRY não significa que qualquer conteúdo vindo dela possa ser publicado automaticamente.

A adequação continua sendo avaliada em relação ao Claim e às políticas editoriais vigentes.

---

# 35. Checklist mínimo de uso de fonte

Antes de utilizar uma fonte para sustentar afirmação material, deve ser possível responder, conforme aplicável:

- [ ] Qual afirmação específica esta fonte pretende sustentar?
- [ ] Ela é primária, secundária ou apenas de descoberta para essa afirmação?
- [ ] Quem é o emissor ou publicador?
- [ ] A autoria ou origem possui autenticidade razoável?
- [ ] O emissor possui competência ou proximidade adequada para o ponto afirmado?
- [ ] A fonte é parte interessada?
- [ ] O conteúdo sustenta exatamente a formulação publicada?
- [ ] A data, vigência e versão correspondem ao estado temporal representado?
- [ ] Existe fonte primária melhor e razoavelmente acessível?
- [ ] A fonte primária comprova o ato ou também a verdade material do Claim específico?
- [ ] Se múltiplas fontes forem usadas, elas são realmente independentes na raiz evidencial?
- [ ] Há cadeia de republicação ou circularidade?
- [ ] Existe fonte materialmente contraditória ou qualificadora que não pode ser ignorada?
- [ ] Existe contestação material ou correção posterior?
- [ ] O conteúdo passou por transcrição, OCR, tradução, resumo, cálculo ou outra transformação relevante?
- [ ] O local exato da evidência dentro da fonte pode ser reencontrado?
- [ ] Os metadados mínimos de proveniência foram preservados?
- [ ] Se o Claim deriva de consulta estruturada, os filtros e parâmetros relevantes estão registrados?
- [ ] Se o Claim é negativo, a ausência de registro realmente permite concluir ausência?
- [ ] A fonte está disponível ao usuário ou sua restrição/indisponibilidade foi corretamente representada?
- [ ] A forma de armazenamento, citação ou referência é proporcional e adequada?
- [ ] A gravidade da afirmação exige diligência adicional?

Esse checklist não substitui o julgamento de suficiência de evidência do FF-0011.

---

# 36. Decisões reservadas aos documentos seguintes

## FF-0011 — CLAIMS_AND_EVIDENCE

Este documento não define:

- schema ou entidade formal de Claim;
- estados formais de verificação;
- quantidade ou combinação mínima de evidências por classe de Claim;
- lógica formal de confirmação, contestação, refutação ou desconhecimento;
- evolução temporal do estado de um Claim.

## FF-0012 — CORRECTIONS_POLICY

Este documento não define:

- severidade de correções;
- quando uma fonte invalidada exige retratação pública;
- formato de changelog;
- SLA ou fluxo de pedidos externos de correção.

## FF-0013 / FF-0019

Este documento não define:

- schema físico de Source;
- formato de armazenamento;
- IDs técnicos;
- banco de dados;
- estrutura de arquivos.

## FF-0018 / FF-0020 / FF-0031

Este documento não define:

- frequência concreta de coleta;
- scraping por fonte;
- jobs;
- retries;
- mecanismos operacionais de snapshot;
- criticidade técnica específica de cada fonte.

---

# 37. Critérios para canonização

Antes de promover o FF-0010 para CANONICAL, deve-se confirmar que:

- não contradiz FF-0001;
- respeita FF-0009;
- atende a todos os itens de Fontes exigidos pelo Gate F2 do FF-0002;
- define categorias de fonte sem criar ranking absoluto de confiança;
- estabelece prioridade adequada para fontes primárias;
- explica quando fonte secundária pode ser legítima e suficiente;
- define uso aceitável de imprensa e fontes especializadas;
- define tratamento de redes sociais e declarações públicas;
- define tratamento de fontes removidas, alteradas e indisponíveis;
- estabelece metadados mínimos de proveniência;
- diferencia múltiplos links de evidência realmente independente;
- separa autoridade sobre ato da verdade material de alegação;
- não presume que fonte oficial seja imparcial ou competente para toda afirmação;
- não trata quantidade fixa de fontes como substituto de julgamento;
- trata cadeia de transformação, incluindo transcrição, OCR, tradução e dados derivados;
- estabelece cautela específica para afirmações negativas baseadas em ausência;
- trata bases estruturadas e consultas de forma reproduzível;
- impede seleção enviesada de fontes materialmente relevantes;
- preserva temporalidade e versão das fontes;
- não torna material privado, vazado ou privilegiado requisito do MVP;
- preserva sustentabilidade operacional e possibilidade de automação responsável;
- não antecipa indevidamente o modelo formal de Claims, schema técnico ou processo de correção.

A revisão crítica de 2026-09-04 considera esses critérios satisfeitos no conteúdo da v0.2, sujeito à aprovação explícita de André para promoção a CANONICAL.

---

# 38. Revisão crítica de 2026-09-04

A revisão da v0.1 identificou pontos que poderiam gerar falsa robustez evidencial ou ambiguidade operacional e foram tratados nesta versão.

## 38.1 “Fonte boa” ainda poderia ser interpretada como qualidade global do emissor

O princípio central foi refinado para tornar explícitos o Claim, o período e a cadeia evidencial, além de proibir score global de confiabilidade como substituto de análise.

## 38.2 A prioridade de fonte primária podia ser confundida com deferência à narrativa oficial

Foi reforçado que documento oficial prova com especial força o ato da instituição dentro de sua competência, mas não prova automaticamente prática efetiva, causalidade ou verdade material de alegações externas ao ato.

## 38.3 Faltava dizer com clareza quando uma fonte jornalística secundária pode bastar

A v0.2 estabelece critérios para uso suficiente de reportagem secundária em Claims limitados, sem criar regra fixa de quantidade de fontes e sem permitir que afirmações graves dependam de apuração opaca inadequada.

## 38.4 Independência entre fontes precisava ser avaliada na raiz, não apenas no veículo

Diferenciou-se independência de publicação de independência evidencial e foi explicitado que múltiplos veículos podem continuar dependentes de uma única raiz documental ou informacional.

## 38.5 Faltava uma proteção explícita contra cherry-picking

A seleção de fontes não pode omitir evidência materialmente contraditória ou qualificadora apenas porque ela enfraquece uma narrativa desejada.

## 38.6 Ausência de resultado precisava de regra geral própria

A v0.1 tratava esse risco principalmente em sistemas públicos. A v0.2 cria regra transversal para Claims negativos e exige cautela com exaustividade, sigilo, indexação, filtros e período.

## 38.7 Bases estruturadas e consultas não tinham proveniência reproduzível suficiente

Foram acrescentadas regras para parâmetros, filtros, data de extração, versão, paginação, escopo e linhagem de dados derivados.

## 38.8 Transformações intermediárias estavam subespecificadas

Transcrição, OCR, tradução, resumo, cálculo e agregação passaram a ser tratados como camadas derivadas que devem preservar relação com a fonte original.

## 38.9 Fontes digitais exigiam salvaguardas adicionais de autenticidade

A v0.2 acrescenta atenção a impersonação, conta comprometida, material sintético/manipulado e exposição acidental de conteúdo privado.

## 38.10 Versões diferentes da mesma fonte não devem ser tratadas como simples correção

Foi criada distinção entre correção, atualização de estado, substituição normativa, edição sem explicação e mudança temporal, preservando a memória da versão anteriormente válida.

Após os ajustes, não foi identificado conflito canônico bloqueante com FF-0001, FF-0002, FF-0004, FF-0007, FF-0008 ou FF-0009.

---

# 39. Impacto documental

## É impactado por

- FF-0001 — PROJECT_CONSTITUTION;
- FF-0002 — PRE_CODEX_CHECKLIST;
- FF-0004 — GLOSSARY;
- FF-0007 — SCOPE;
- FF-0008 — MVP_SPEC;
- FF-0009 — EDITORIAL_POLICY.

## Impacta

- FF-0011 — CLAIMS_AND_EVIDENCE;
- FF-0012 — CORRECTIONS_POLICY;
- FF-0013 — DOMAIN_MODEL;
- FF-0014 — TEMPORAL_MODEL;
- FF-0018 — INGESTION_PIPELINE;
- FF-0019 — DATA_STORAGE;
- FF-0020 — AUTOMATION_STRATEGY;
- FF-0027 — TEST_STRATEGY;
- FF-0028 — SECURITY_AND_PRIVACY;
- FF-0029 — LEGAL_AND_REPUTATIONAL_RISK;
- FF-0031 — SOURCE_REGISTRY;
- FF-0032 — MAINTENANCE;
- FF-0033 — OBSERVABILITY;
- FF-0034 — BACKUP_AND_RECOVERY.

---

# 40. Vigência

Esta versão permanece **DRAFT** até aprovação explícita.

**FF-0010 — SOURCE_POLICY v0.2 // DRAFT**
