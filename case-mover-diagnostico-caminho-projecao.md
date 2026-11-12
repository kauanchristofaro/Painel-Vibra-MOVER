# Case MOVER — diagnóstico, caminho e projeção

Documento de trabalho para análise. A MOVER é uma rede fictícia de academias e estúdios, case do processo seletivo Trainee Vibra 2027. Este texto reúne a solução escolhida, os números do case, as contas derivadas, a projeção contra as metas e as evidências de fora usadas pelo comitê.

**Como ler.** Distinga quatro tipos de dado:

1. **Fato do case** — informado no material da banca.
2. **Conta derivada** — aritmética feita só com números do case; a premissa vai junto.
3. **Evidência externa** — dado ou referência de fora do case, com fonte.
4. **Posição do comitê** — escolha ou recusa, não um número medido na MOVER.

**O que não inventar em qualquer análise posterior.** O case não decompõe o 3,8% (plano compartilhado vs. entrada fantasma vs. cobrança contestada), não informa o NPS atual e não informa o custo interno da camada de identidade nem do check-in de sessão. A frequência do aluno de plataforma não foi medida no case, mas a média implícita se deriva do mix 33%/19%, da mensalidade direta média de R$ 129 e dos R$ 14 por visita (conta abaixo). Não trate essa média implícita como frequência observada por unidade ou por horário, nem transforme o faturamento implícito em reais — lastreado nos 410 mil — em receita auditada: os 410 mil são soma, com 12% a 20% de possíveis duplicados. O rito de a plataforma pedir que a academia reporte compartilhamento depois do fato **não está no material da banca**: é evidência externa de mercado, não fato do case. O que o case informa é que esses alunos são quase anônimos, que a plataforma fica com o relacionamento e com os dados, e que paga por visita.

---

## Recorte da banca

A solução precisa caber nesta estrutura:

### 01 Diagnóstico

O que está acontecendo de verdade no case.

### 02 O caminho

Por quê · evidências e referências · do que abre mão · consequências · primeiros passos · ponto frágil.

### Três exigências

- **Escolha um caminho.** Não existe resposta certa. Tentar agradar a todas as frentes não é escolher.
- **Diga do que abre mão.** Toda escolha tem custo. Mostrar que você enxerga o seu faz parte da resposta.
- **Vá além do case.** Busque dados e referências de fora. O case foi feito para isso.

### Cinco competências da Vibra

A solução deve estar alinhada a estas competências.

1. **Visão estratégica.** Compreende o todo, escuta de forma ativa os clientes e conecta variáveis internas e externas, tomando decisões que sustentam o negócio no curto e no longo prazo.
2. **Coragem.** É protagonista e inconformado: assume riscos com responsabilidade e decide com transparência diante da incerteza, mantendo a segurança como princípio inegociável.
3. **Gente que inspira e transforma.** Atua como agente de desenvolvimento e transformação, com respeito às pessoas, promovendo colaboração, aprendizagem e protagonismo para impulsionar projetos e resultados sustentáveis.
4. **Mentalidade empreendedora.** Identifica oportunidades e gera valor com autonomia e iniciativa, entregando soluções com simplicidade e agilidade, inovando e aprendendo continuamente.
5. **Foco em resultado.** Vai além de metas de curto prazo, entrega resultados de forma colaborativa, cumpre e cobra os combinados e integra impacto econômico, social e ambiental, sempre com o cliente no centro das decisões.

Há também um painel de cerca de sete minutos com gestores, na frente de Tecnologia e Dados, cobrindo diagnóstico, caminho e como a inteligência artificial foi usada — inclusive onde houve discordância.

---

## Fatos do case (o que o material informa)

- Rede de cerca de **180 unidades em 7 estados**, depois de comprar **4 redes** regionais.
- Opera com **5 sistemas que não conversam** entre si.
- Cerca de **410 mil «alunos ativos»**: soma dos cinco sistemas, não pessoas distintas.
- O case admite **12% a 20%** de possíveis duplicados.
- A empresa promete **treinar em qualquer unidade**, mas sem identidade única isso não se sustenta.
- **Fraude e chargeback: 3,8% da receita**, o dobro de dois anos atrás. O case nomeia três tipos de perda — plano compartilhado, entrada fantasma e cobrança contestada — mas **não decompõe** o 3,8% entre eles.
- **7 pilotos de inteligência artificial** não escalaram; os professores desconfiam deles.
- Plataformas de benefícios: **33% dos alunos e 19% da receita**; cerca de **R$ 14 por visita** contra mensalidade direta média de **R$ 129**.
- Para a MOVER, esses alunos são **quase anônimos**: a plataforma fica com o relacionamento e com os dados, e paga por visita.
- Teste de reconhecimento facial em **3 unidades**: corte de **45%** da fraude; o fornecedor tinha prometido **80%**. Houve fila no pico, liberação manual, erro maior para parte do público e alerta de LGPD / discriminação.
- Levar o facial à rede inteira custaria cerca de **1,5% da receita de um ano**.
- **Metas do case:**
  - Em **12 meses**: visão única do aluno **e** cortar a fraude pela metade (**3,8% → 1,9%**), **sem piorar** a experiência de chegada nem o NPS.
  - Em **90 dias**: um resultado mensurável para o conselho.
  - Em **4 meses**: decidir renovar, renegociar ou sair da maior plataforma.

---

## Caminho escolhido (síntese)

Identidade cadastral única e check-in de sessão (código de uso único, de curta duração, amarrado à visita). O reconhecimento facial fica **fora deste ciclo** — na rede, como plano B e nas 3 unidades de teste, que **desligam até o dia 60**, com a porta migrada para o mesmo pacote. A maior plataforma **só se renova** com identidade do beneficiário no check-in: o mesmo beneficiário reconhecível entre visitas, mesmo que tokenizado. Identificador agregado ou que muda a cada visita não passa. Preço melhor ou teto no pico não substituem identidade. Corte seco e saída no escuro estão recusados. A meta de **1,9% em 12 meses** é a meta escolhida e fecha pelo pacote das três alavancas.

Decisões travadas:

| Decisão | Posição |
|---|---|
| Via principal | Identidade cadastral e check-in de sessão |
| Facial nacional | Fora deste ciclo, inclusive como plano B |
| Meta de 1,9% | Meta escolhida para 12 meses, fechada pelo pacote das três alavancas — o dia 28 calibra o peso de cada braço, não a meta |
| Maior plataforma | Renova só com o mesmo beneficiário reconhecível no check-in |
| Aplicativo | Escala só depois de prova no pico, com alternativa equivalente sem celular |
| Teste facial em 3 unidades | Desligar até o dia 60 e migrar a porta para identidade e check-in de sessão. As 3 casas não entram automaticamente na amostra |
| QR estático | Recusado: é a mesma credencial compartilhável de hoje |
| Troca dos cinco sistemas | Fora deste ciclo de 12 meses; a visão única vem da camada de identidade |
| Pilotos de IA | Pausar os sete como estão. Depois do dia 90, um sucessor contido: alerta ao professor sobre queda de frequência real na rede. IA na catraca e IA de fraude no backoffice ficam de fora neste ciclo |

Fluxo da via principal:

1. Identidade cadastral — o mesmo aluno nos cinco sistemas.
2. Check-in de sessão — uso único e curta duração.
3. Porta no pico — fallback auditável, sem improviso na recepção.

Fork da maior plataforma:

- Se houver identidade no check-in → renovar, com identidade e pacote econômico.
- Se não houver → não renovar como está; ponte curta e alternativa real.

---

## 01 Diagnóstico

O que está acontecendo de verdade não é falta de câmera nem de inteligência artificial. Depois de comprar quatro redes, a MOVER opera cerca de 180 unidades em sete estados com cinco sistemas que não conversam. Os 410 mil «alunos ativos» são soma, não pessoas: o case admite 12% a 20% de possíveis duplicados. Sem uma identidade única, confiável e lícita, a empresa não sabe quem atravessa a catraca, não cumpre a promessa de treinar em qualquer unidade e não separa, nos 3,8% da receita perdidos em fraude e chargeback, o que é plano compartilhado, entrada fantasma ou cobrança contestada.

Um terço dos alunos chega por plataforma e gera só 19% da receita: cerca de R$ 14 por visita contra uma mensalidade direta média de R$ 129. Para a MOVER, esse aluno é quase anônimo: a plataforma fica com o relacionamento e com os dados, e paga por visita.

Fora do case — evidência de mercado, não enunciado da banca — as plataformas líderes já identificam o beneficiário do lado delas e pedem à academia que reporte compartilhamento depois do fato (Wellhub Partner Academy; suporte Gympass/Wellhub). A academia denuncia e espera: essa identidade não chega à porta. Documentação operacional de sistemas de gestão usados por academias no Brasil (Pacto) descreve a recepção virando camada de integração no primeiro check-in, e o atalho da indústria é empurrar biometria na primeira visita.

O teste facial em três unidades cortou a fraude em 45% — o fornecedor tinha prometido 80% — e trouxe fila no pico, liberação manual, erro maior para parte do público e alerta de LGPD. Levado à rede, custaria cerca de 1,5% da receita de um ano. Os sete pilotos de inteligência artificial não escalaram, e os professores desconfiam deles. A ferida é de cadastro e de contrato, não de algoritmo.

---

## Os números que importam

Contas derivadas apenas dos números do case.

| Dado | O que o case diz | Leitura |
|---|---|---|
| Alunos ativos | cerca de 410 mil | Soma dos cinco sistemas, não pessoas |
| Duplicidade possível | 12% a 20% | Sem identidade única a base não fecha |
| Unidades e estados | cerca de 180 em 7 estados | Cinco sistemas após quatro compras |
| Fraude e chargeback | 3,8% da receita | Dobrou em dois anos |
| Teste facial | −45% da fraude em 3 unidades | Fornecedor prometeu 80%; houve fila no pico |
| Custo facial na rede | cerca de 1,5% da receita de um ano | Atalho caro e ainda acima da meta |
| Plataforma | 33% dos alunos e 19% da receita | R$ 14 por visita versus R$ 129 por mês |
| Pilotos de IA | 7, sem escala | Professores desconfiam deles |

No desempenho já testado, o atalho da câmera também não fecha a meta de 1,9%.

```
3,8% × 45% = 1,71 p.p. de redução
3,8% − 1,71 p.p. = 2,09% de residual
```

| Referência | Valor |
|---|---|
| Perda atual (fraude e chargeback) | 3,8% |
| Após facial a 45% (ainda acima da meta) | 2,09% |
| Meta em 12 meses | 1,9% |

Para o aluno de plataforma igualar o ticket direto de R$ 129 a R$ 14 por visita, seriam necessárias cerca de **9,2 visitas por mês**. Esse ponto de equilíbrio sai da conta `129 ÷ 14 ≈ 9,21`. Ele diz quantas visitas equiparariam o ticket; não é a frequência implícita do mix.

A frequência média implícita do aluno de plataforma (conta derivada, não métrica medida) fecha com os próprios números do case e **não precisa** dos 410 mil nem do faturamento total. Se 33% dos alunos geram 19% da receita, os outros 67% geram 81%. O rendimento relativo do aluno-plataforma frente ao aluno direto é:

```
(19 ÷ 33) ÷ (81 ÷ 67) = (19 × 67) ÷ (33 × 81) ≈ 0,476
0,476 × 129 ≈ R$ 61,44 por aluno-plataforma por mês
61,44 ÷ 14 ≈ 4,39  →  cerca de 4,4 visitas por mês
```

Em reais redondos: cerca de **R$ 61,43/mês** e **4,4 visitas/mês**. Essa conta herda os «cerca de» do case e trata R$ 129 como a média de receita mensal do aluno direto, que o case já apresenta como média. Premissas: os 67% complementares são os alunos diretos e correspondem aos 81% da receita; toda a receita de plataforma entra como R$ 14 por visita; percentual de alunos e percentual de receita falam da mesma base. Se a taxa de duplicidade for diferente entre direto e plataforma, a frequência por pessoa — e não por registro — se desloca. O 4,4 descreve o aluno como o case o conta no mix 33%/67%, não uma frequência observada por unidade ou horário.

Duas leituras de yield, que não se confundem:

- `19 ÷ 33 ≈ 58%` — quanto o canal entrega da receita que sua fatia da base sugeriria, se a receita fosse proporcional ao número de alunos.
- `(19 ÷ 33) ÷ (81 ÷ 67) ≈ 48%` — receita por aluno de plataforma frente à receita por aluno direto.

Um corte seco desse terço furaria cerca de **19% da receita** para perseguir uma perda de 3,8%.

O faturamento total em reais **não está escrito** no case. Dá para lastreá-lo se a base de alunos for conhecida: `receita mensal = (0,67 × base × 129) ÷ 0,81`. Com os 410 mil da soma dos cinco sistemas, isso dá cerca de **R$ 43,75 milhões/mês** (cerca de **R$ 525 milhões/ano**). Essa conta é mais frágil do que o 4,4: se 12% a 20% forem duplicados e cada pessoa pagar uma vez, o total cai na mesma proporção, para cerca de **R$ 38,5 milhões** a **R$ 35,0 milhões** por mês. Por isso o custo do facial permanece melhor lido como «cerca de 1,5% da receita de um ano», e não como um valor certificado em reais.

---

## 02 O caminho

A via é uma camada de identidade que fala com os cinco sistemas e um check-in de sessão: um código de uso único, de curta duração, amarrado à visita. QR estático é a mesma credencial compartilhável de hoje. O aplicativo da MOVER, sozinho, não identifica o terço da plataforma — isso se resolve no contrato. O aplicativo só escala depois de prova no pico, com alternativa equivalente sem celular.

Sem saber quem é quem, não há visão única em doze meses nem antifraude que se sustente. Preço melhor ou teto no pico não substituem identidade. Corte seco e saída no escuro também estão recusados: um corte do terço furaria cerca de 19% da receita, buraco maior do que a perda de 3,8% que se tenta fechar. Sem mapa de ocupação e alternativa real em 90 dias, a mesa é blefe.

O pacote antifraude desta via (posição do comitê, efeito combinado **ainda não medido** na MOVER): identidade cadastral, regras de velocidade, exceção auditável, playbook de contestação e cláusula de identidade na plataforma — não a câmera.

---

## Projeção contra as metas

Contas derivadas dos números do case e da leitura do comitê. A composição do 3,8% não está no case, então a fraude **não ganha um ponto único inventado**.

O case pede três entregas no relógio: um resultado que o conselho consiga ler em 90 dias, a decisão da maior plataforma em quatro meses, e em doze meses a visão única do aluno junto com a fraude pela metade, sem piorar a chegada nem o NPS.

| Meta do case | Projeção da solução | Frente à meta |
|---|---|---|
| Visão única do aluno em 12 meses | Camada de identidade sobre os cinco sistemas, sem trocá-los neste ciclo | No prazo |
| Fraude de 3,8% para 1,9% em 12 meses | Meta de 12 meses escolhida. Fecha com três alavancas ao mesmo tempo: velocidade e token contra compartilhamento; validador e check-in de sessão contra entrada fantasma; dossiê e conciliação contra chargeback. O dia 28 calibra o peso de cada braço, não se a meta vale | Caminho escolhido |
| Não piorar a chegada nem o NPS em 12 meses | O aplicativo só escala depois de prova no pico, com alternativa sem celular. O case não informa o NPS atual | Restrição (não é um número projetado) |
| Resultado mensurável ao conselho em 90 dias | Indicadores antecedentes: corte do 3,8%, alunos únicos medidos, mapa da porta e mesa aberta — não o print de −1,9 p.p. no resultado | No prazo |
| Decidir a maior plataforma em 4 meses | Renova só com identidade do beneficiário no check-in; corte seco recusado | Decisão no prazo |

Na maior plataforma, um terço dos alunos gera 19% da receita: cerca de 58% do que corresponderia à sua fatia da base (`19 ÷ 33`). Cortar esse terço no escuro furaria cerca de 19% da receita para perseguir uma perda de 3,8%. A projeção dos quatro meses é a decisão com identidade na mesa, não um furo deliberado nem uma renovação cega.

### Alunos únicos

Se a duplicidade admitida no case se confirmar, a visão única troca a soma de 410 mil alunos por uma base menor. As contas partem dos 410 mil do case.

```
410 mil × (1 − 12%) = 360,8 mil alunos únicos
410 mil × (1 − 20%) = 328 mil alunos únicos
```

| Referência | Valor |
|---|---|
| Soma atual (cinco sistemas, não pessoas) | 410 mil |
| Únicos se a duplicidade for 12% | 360,8 mil |
| Únicos se a duplicidade for 20% | 328 mil |
| Registros a mais do que pessoas | de 49,2 mil a 82 mil |

O trabalho de 90 dias é medir onde a base cai nessa faixa, não escolher um número no meio.

### Fraude e chargeback

Para a fraude cair de 3,8% para 1,9%, o pacote precisa cortar metade da perda. O atalho da câmera, no desempenho já testado, corta 45% e deixa 2,09%. A solução escolhida não tem um residual próprio até o 3,8% ser separado; o que dá para projetar é o que cada tamanho de corte faria.

```
3,8% × 50% = 1,9 p.p.  →  o corte que a meta pede
```

| Se o pacote cortar | Residual | Distância da meta de 1,9% |
|---|---|---|
| 25% do 3,8% | 2,85% | +0,95 p.p. |
| 45% — mesmo efeito do teste facial | 2,09% | +0,19 p.p. |
| 50% — o corte que a meta pede | 1,90% | na meta |
| 80% — promessa do fornecedor facial | 0,76% | −1,14 p.p., sem evidência neste pacote |

| Referência visual | Valor |
|---|---|
| Perda atual | 3,8% |
| Se cortar 25% | 2,85% |
| Se cortar 45% (efeito do teste facial) | 2,09% |
| Meta (corte de 50%) | 1,9% |

Os cortes de 45% e 80% são o teste em três unidades e a promessa do fornecedor, trazidos **só como referência de magnitude** — não como previsão deste pacote. Se a maior fatia do 3,8% for contestação de aluno aparentemente legítimo, o residual fica mais perto do cenário de 25% do que da meta. Se for plano compartilhado e entrada fantasma, o caminho até 1,9% existe sem câmera. É por isso que separar o 3,8% em 90 dias é o primeiro número de conselho, não um detalhe.

No atalho facial, o comitê leu ainda outra conta: poupar 1,71 ponto da receita e gastar cerca de 1,5% da receita de um ano deixa um líquido de cerca de **0,21 ponto** no primeiro ano — e ainda assim acima da meta. O case não diz se esse 1,5% se repete todo ano; se se repetir, o atalho quase não se paga. O custo interno da camada de identidade e do check-in de sessão também não está no case, e **não entra nesta projeção**.

### O que o conselho lê em 90 dias

| Indicador | O que fica visível |
|---|---|
| Composição do 3,8% | Se a meta de 1,9% é alcançável com identidade e token, ou se a maior fatia pede playbook de contestação |
| Alunos únicos medidos | Onde a base cai na faixa de 328 mil a 360,8 mil, se a duplicidade do case se confirmar |
| Tempo e fallback no pico | Se o pacote está sendo pago com fila — o critério para não escalar o aplicativo |
| Identidade pedida por escrito | A decisão dos quatro meses deixa de ser blefe, com conversa aberta sob a mesma cláusula |

---

## Evidências e referências (fora do case)

Fora do case, o mercado fitness brasileiro cresce em torno de rede e conveniência. O Panorama Setorial Fitness Brasil 2024, citado pelo InvestNews em 17 de junho de 2025, aponta cerca de 15 milhões de alunos, 57 mil unidades e R$ 17 bilhões em faturamento. A BlueFit aparece ali com 176 unidades e 431 mil alunos, ordem próxima da MOVER. A Smart Fit vende treinar em qualquer unidade e declara a integração de sistemas como trabalho real.

As plataformas projetam crescer rápido e já identificam o usuário do lado delas. O Wellhub instrui o parceiro a reportar compra ou aluguel de conta, compartilhamento e familiar não elegível; o rito é posterior ao fato (bandeira no Portal do Parceiro, análise, bloqueio se confirmado). O suporte do Gympass/Wellhub descreve o mesmo canal de denúncia pelo parceiro, e os termos da TotalPass proíbem ceder, vender ou alugar o plano. Isso **não está no PDF da banca**: é prática pública do mercado, usada aqui para ir além do case. A leitura do comitê, junto com o «quase anônimo» do enunciado, é que a plataforma protege o produto dela e não entrega essa identidade à academia. Documentação do Pacto descreve a recepção como camada de integração e o atalho de cadastrar biometria na primeira visita. Uma regra prática relatada pelo Sindfit-CE fala em no máximo cerca de 30% da base em agregadores; a MOVER já está em 33% dos alunos e 19% da receita. O Cade limitou exclusividades: isso abre espaço legal para falar com outra plataforma, não constrói sozinho a alternativa comercial.

Dado biométrico é dado sensível na LGPD. A ANPD regula biometria agora e já fiscalizou reconhecimento facial até onde há lei setorial mandando cadastro. O Idec exige alternativa não biométrica para o consentimento ser livre. O NIST documenta erro desigual entre grupos e falso negativo ligado à qualidade da imagem — luz ruim, ângulo, altura — o mesmo ambiente do pico da academia.

Fora do case, frequência e dias sem treino são o sinal mais repetido de abandono. Um estudo brasileiro em duas academias associou frequência baixa (≤3×/mês e 4–6×/mês) ao dropout (RBCE/SciELO). Em um fitness center português, dias sem frequência foram a variável mais relevante para prever saída. Frequência e estabilidade no início da matrícula ajudam a prever quem continua (Psychology of Sport and Exercise, 2020). O corte desses estudos **não se copia** para a MOVER: o limiar sai com o professor, no chão. Não se inventa ganho de NPS nem taxa de retenção.

Fontes usadas pelo comitê:

- InvestNews, 17/06/2025 — [De influencers a Ozempic: o que está por trás do crescimento do mercado fitness no Brasil](https://investnews.com.br/negocios/de-influencers-a-ozempic-o-que-esta-por-tras-do-crescimento-do-mercado-fitness-no-brasil/)
- Fitness Brasil — [Panorama Setorial Fitness Brasil 2024](https://www.fitnessbrasil.com.br/newsfitbr/descubra-as-tendencias-do-mercado-fitness-em-2024-uma-analise-completa-do-panorama-setorial-fb/)
- Diário do Nordeste, 28/05/2025 — [Apps de bem-estar apertam academias e regra prática de mix do Sindfit-CE](https://diariodonordeste.verdesmares.com.br/negocios/apps-de-bem-estar-abocanham-mercado-fitness-e-apertam-academias-menores-no-ceara-1.3654100)
- Cade, 18/12/2025 — [Cade homologa novo TCC com a Wellhub](https://www.gov.br/cade/pt-br/assuntos/noticias/cade-homologa-novo-tcc-com-wellhub-gympass)
- Cade, 21/09/2022 — [Gympass celebra acordo com o Cade no mercado de academias](https://www.gov.br/cade/pt-br/assuntos/noticias/gympass-celebra-acordo-com-o-cade-no-mercado-de-academias-de-ginasticas-no-brasil)
- VEJA, 12/09/2025 — [Nunca seremos donos de academia, diz presidente do Wellhub no Brasil](https://veja.abril.com.br/economia/nunca-seremos-donos-de-academia-diz-presidente-do-wellhub-no-brasil/)
- Wellhub Partner Academy — [Reportar comportamentos suspeitos](https://wellhub.com/pt-br/partner-academy/reportar-comportamentos-suspeitos/)
- Wellhub / Gympass suporte — [Como parceiros podem reportar um visitante](https://support.gympass.com/hc/pt-br/articles/43621714617619-Como-parceiros-podem-reportar-um-visitante)
- Wellhub / Gympass suporte — [Por que é necessário o reconhecimento facial no check-in](https://support.gympass.com/hc/pt-br/articles/45639853727379-Por-que-%C3%A9-necess%C3%A1rio-o-reconhecimento-facial-no-momento-do-check-in)
- TotalPass — [Termos de uso](https://totalpass.com/br/terms/)
- Pacto — [Cadastro automático do aluno TotalPass no primeiro check-in](https://sistemapacto.zendesk.com/hc/pt-br/articles/56614209472531-Como-%C3%A9-feito-o-cadastro-autom%C3%A1tico-do-aluno-TotalPass-no-primeiro-check-in)
- Planalto — [Lei 13.709/2018 — LGPD](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)
- ANPD, 02/06/2025 — [ANPD abre tomada de subsídios sobre tratamento de dados biométricos](https://www.gov.br/anpd/pt-br/assuntos/noticias/anpd-abre-tomada-de-subsidios-sobre-tratamento-de-dados-biometricos)
- ANPD, 18/02/2025 — [ANPD fiscaliza reconhecimento facial em 23 clubes de futebol](https://www.gov.br/anpd/pt-br/assuntos/noticias/anpd-fiscaliza-uso-de-sistema-de-reconhecimento-facial-na-venda-de-ingressos-e-na-entrada-de-estadios-por-23-clubes-de-futebol)
- ANPD — [Biometria é tema do Radar Tecnológico](https://www.gov.br/anpd/pt-br/assuntos/noticias/biometria-e-tema-do-segundo-volume-da-serie-radar-tecnologico)
- Idec, 12/06/2025 — [Guia completo: sistema de reconhecimento facial](https://idec.org.br/dicas-e-direitos/guia-completo-sistema-de-reconhecimento-facial)
- NIST — [FRTE demographics — efeitos demográficos no reconhecimento facial](https://pages.nist.gov/frvt/html/frvt_demographics.html)
- NIST, 12/2019 — [NISTIR 8280 — Face Recognition Vendor Test Part 3](https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8280.pdf)
- RBCE / SciELO — [Dropout predictors at gyms: a retrospective study](https://www.scielo.br/j/rbce/a/WtzM3gBFRkcrqY7xKZsVNnm/)
- IJERPH / PMC, 2021 — [Predicting Fitness Centre Dropout](https://pmc.ncbi.nlm.nih.gov/articles/PMC8508547/)
- Psychology of Sport and Exercise, 2020 — [Why do new members stop attending health and fitness venues? The importance of developing frequent and stable attendance behaviour](https://doi.org/10.1016/j.psychsport.2020.101771)

Leitura jurídica e técnica que o comitê acoplou a essas fontes (não são métricas novas da MOVER): dado biométrico é dado sensível (LGPD art. 5º, II); arts. 6º, 9º, 11 (II; a hipótese “g” não é cheque em branco), 18, 20, 37 e 38 (RIPD); Resolução CD/ANPD nº 2/2022, critérios de alto risco; a ANPD já fiscalizou reconhecimento facial em clubes de futebol mesmo havendo lei setorial de cadastro (Lei Geral do Esporte 14.597/2023). O Idec exige alternativa não biométrica para o consentimento ser livre. O NIST documenta variação grande de falso positivo entre grupos e falso negativo ligado à qualidade da imagem.

---

## Do que se abre mão e consequências

### O que a escolha ganha

- Uma identidade que sustenta a visão única e a fraude que depende de saber quem é quem.
- Não gastar cerca de 1,5% da receita num atalho que, no teste, deixa residual de cerca de 2,09%.
- Não virar controlador biométrico nacional no meio da regulação da ANPD.
- A mesa com a plataforma deixa de ser uma renovação cega.
- Depois do dia 90, um produto simples de retenção sobre a identidade construída, com o professor como protagonista.

### Do que se abre mão

- Do atalho da câmera e da premissa dos 80% do fornecedor.
- De garantir o corte da fraude pela metade neste ciclo.
- De parecer inovador agora, de escolher um vencedor entre os sete sem evidência, de fazer da inteligência artificial a heroína do antifraude neste ciclo, e de trocar os cinco sistemas em doze meses.
- De renovar a plataforma como está, do corte seco e do QR estático.
- Da recepção como arranjo informal e de anunciar a promessa de rede antes de a porta aguentar o pico.

### Consequências

A fraude pode cair mais devagar, e 1,9% pode não fechar se a maior fatia do 3,8% for contestação de aluno aparentemente legítimo ou se a plataforma recusar a identidade. Conversão para plano direto é caminho fraco sem titular: sem dado não há relacionamento, só porta. Se precisar de ponte, ela é curta, com data para a identidade — não um contrato cheio sem cláusula.

---

## Primeiros passos

1. **Separar o 3,8%.** Fraude versus chargeback aparentemente legítimo; direto versus plataforma; por unidade. Sem esse corte, qualquer promessa de 1,9% é narrativa.
2. **Medir alunos únicos de verdade.** 410 mil é soma. Inventariar as chaves dos cinco sistemas, a taxa de falha de acesso cruzado e o dado mínimo da mesa: beneficiário identificável ou token estável, amarrado ao evento de entrada.
3. **Mapear a porta no pico.** Ocupação por unidade e canal, tempo de passagem, taxa de fallback, filas e entradas falhas de aluno já identificado — noites de semana e domingo às 18h.
4. **Abrir a mesa com o BATNA ao lado.** Identidade por escrito, conversa com outra plataforma sob a mesma cláusula mínima e pack por unidade. O Cade abre espaço legal; o mapa é o que evita o blefe.
5. **Abrir as minutas e o playbook.** Cláusula de identidade, o que circula no check-in, exclusividade, rescisão e evidência para contestação. Ficha do token: o que pode ser, o que não pode coletar, alternativa sem aplicativo.
6. **Desenhar o que se diz ao aluno.** Roteiro de recepção e oferta nos dois cenários. Não publicar o que a operação ainda não aguenta, nem transformar 1,9% em promessa de marca.

### Entrega por frente em 90 dias

| Frente | O que entrega em 90 dias |
|---|---|
| Prevenção a Fraude e Financeiro | Separar o 3,8% e montar o pack de alternativa por unidade |
| Tecnologia e Dados | Alunos únicos, falha de acesso cruzado, inventário e dado mínimo da mesa |
| Operações e Experiência | Mapa de ocupação e medição da porta no pico |
| Parcerias | Renegociação formal e conversa com outro canal sob a mesma cláusula |
| Jurídico e LGPD | Minutas, playbook e ficha jurídica do check-in |
| Marketing e Reputação | Desenhar a fala ao aluno, sem disparar o que a porta ainda não segura |

Em quatro meses, a maior plataforma só se renova com identidade no check-in. Em doze meses, a visão única vem da camada de identidade, não da troca dos cinco sistemas, e a fraude cai pelo pacote — identidade, regras de velocidade, exceção auditável, playbook de contestação e cláusula de plataforma — não pela câmera.

---

## Ponto frágil

Se em 90 dias a maior fatia do 3,8% for contestação de aluno aparentemente legítimo, se a plataforma recusar a identidade antes de existir alternativa, ou se o aplicativo falhar no pico, ficam linhas duras sem alavanca que se pague. Essa fragilidade **não serve para descongelar o facial**. Por isso o mapa de ocupação, o token de sessão e a medição do fallback no pico não são detalhe: são o que impede a posição de virar um não sem caminho.

---

## Competências da Vibra — como aparecem na escolha

| Competência | Como aparece na escolha |
|---|---|
| Coragem | Recusar o slide dos 80%, desligar o teste facial nas 3 unidades, recusar parecer inovador empilhando ferramentas e nomear o custo: o efeito local de 45% até o pacote novo morder |
| Visão estratégica | No curto prazo, identidade mensurável e mesa aberta; no longo, a visão única vira capacidade de retenção — sem construir a espinha da identidade numa biometria que a ANPD ainda regula |
| Foco em resultado | O resultado é a perda de 3,8% virar 1,9% em 12 meses pelo pacote de identidade, e o aluno que chegou para treinar passar pela catraca — não o fato de ter instalado câmeras, nem o rótulo de meta não certificada. O piloto de retenção apoia a outra metade da meta de 12 meses, sem inventar NPS |
| Mentalidade empreendedora | O identificador único sobre sistemas que já existem e, depois da higiene, um produto simples de alerta ao professor sobre essa identidade — em vez de um sexto silo, uma troca geral em doze meses ou mais uma ferramenta fragmentada |
| Gente que inspira e transforma | Pausar os sete como estão, especialmente o que substitui o professor na prescrição de treino; o professor desenha e age no sucessor único de alerta de frequência; não discriminar na porta |

---

## Convergências e divergências do comitê

Sete frentes diagnosticaram o case em separado (Tecnologia e Dados, Jurídico e LGPD, Financeiro, Marketing e Reputação, Operações e Experiência, Prevenção a Fraude, Parcerias), releram a solução à luz do recorte da banca e debateram três conflitos que ainda estavam abertos: a meta de 1,9% sem facial, a recusa de identidade pela plataforma e o check-in no aplicativo. O caminho acima é o cruzamento desse debate, **não uma média** que tenta agradar a todas as frentes.

### O que ficou convergente

- O diagnóstico: a ferida é de cadastro e de contrato, não de câmera nem de algoritmo.
- Identidade cadastral + check-in de sessão como via.
- Facial nacional fora deste ciclo, inclusive como plano B. Ninguém usa a incerteza do pacote ou a falha do check-in para descongelar o facial.
- Não inventar a composição do 3,8%.
- O atalho da câmera, no 45% testado, também não fecha 1,9% (residual ≈ 2,09%) e ainda custaria cerca de 1,5% da receita de um ano.
- A maior plataforma não se renova como está. Sem identidade do beneficiário no check-in, não há renovação cega.
- O aplicativo só escala depois de prova no pico. QR estático está recusado.
- Sem mapa de ocupação e alternativa real em 90 dias, a mesa com a plataforma é blefe. O Cade amplia espaço legal; não constrói sozinho o BATNA.

### Decisão executiva que fecha o que ainda divergia

A banca pede escolher um caminho: tentar agradar a todas as frentes é não escolher. Duas decisões que o comitê tinha deixado em aberto foram fechadas:

1. **Facial nas 3 unidades de teste: desligar até o dia 60.** A porta migra para identidade e check-in de sessão. Manter a câmera «com alternativa» na mesma catraca seria não escolher — duas classes na porta e o teste virando plano B. O teste já entregou a resposta (45%, não 80%; fila; erro desigual; alerta de LGPD). As 3 casas entram na amostra só se forem críticas pelos critérios já travados, não por terem tido câmera. Do que se abre mão: o efeito local de 45% até o pacote novo morder, e a chance de comparar câmera e token na mesma porta.

2. **Meta de 1,9% em 12 meses: é a meta do caminho, não uma hipótese.** Fecha-se combinando as três alavancas ao mesmo tempo, uma família para cada tipo de perda que o case nomeia:
   - Compartilhamento simultâneo → velocidade (a mesma identidade não mantém duas visitas abertas).
   - Compartilhamento sequencial e credencial emprestada → token de uso único e recusa de QR estático ou print.
   - Compartilhamento no canal de plataforma → check-in vivo na porta até o dia 60 e cláusula de identidade na renovação dos quatro meses.
   - Entrada fantasma → validador «este ID pode entrar?», evento de presença amarrado à identidade e token de sessão.
   - Chargeback → dossiê de presença, conciliação automatizada de cobrança e repasse, e playbook de contestação.
   
   O case não decompõe o 3,8%; por isso **não se inventa um residual hoje**. O dia 28 calibra o **peso** de cada braço, não se a meta vale. Os três braços rodam juntos. Em 90 dias não se promete −1,9 p.p. na rede; em 12 meses o Conselho lê o 3,8% da rede contra 1,9%. Do que se abre mão: do rótulo «não certificada» como fuga, de qualquer atalho de uma alavanca só (incluindo a câmera) e de fabricar o número com fila ou biometria.

3. **Pilotos de IA: pausar os sete como estão e, depois do dia 90, um sucessor único.** O case não lista cada piloto; cita exemplos (prever quem vai cancelar e montar treinos personalizados), cada um numa região e com ferramenta diferente, nenhum com resultado claro, e os professores desconfiam. Não se escolhe um «vencedor» entre os sete sem evidência. Em especial, não segue nada que substitua o professor na prescrição de treino.

   O sucessor alerta o professor de referência sobre queda de frequência real daquela pessoa na rede (nas cerca de 180 unidades, comparada com o histórico dela mesma — não uma nota opaca de churn) para acolhimento humano. A ferramenta não manda mensagem automática de cancelamento, não oferece desconto sozinha e não monta treino. Isso inverte o caso de uso que o case já nomeia («prever quem vai cancelar»), em vez de lançar um oitavo experimento fragmentado.

   O piloto nasce contido, só onde o matching for de alta confiança. Alunos diretos primeiro; o terço quase anônimo da plataforma não entra como se fosse aluno do professor. Durante os 90 dias o professor ajuda a desenhar o sinal e o roteiro — não recebe a oitava ferramenta no meio da faxina. Se o alerta errar (cadastro duplicado, férias, visita que o matching não viu) ou se o professor não usar, o piloto para.

   IA na catraca segue recusada. IA de fraude no backoffice fica de fora neste ciclo: o 3,8% para 1,9% fecha com o pacote das três alavancas, não com um modelo que pontua suspeito. Do que se abre mão: parecer inovador agora, escolher um vencedor entre os sete sem evidência, e fazer da inteligência artificial a heroína do antifraude neste ciclo. Não se inventa ganho de NPS nem taxa de retenção — o case não informa o NPS atual.

O que o comitê pensava, e que esta decisão resolve sem média:

- **Financeiro** e **Prevenção a Fraude** mantêm 1,9% como meta de negócio / P&L e recusam trocá-la por «vamos tentar» — a decisão executiva fica com eles na escolha da meta.
- **Tecnologia e Dados** e **Jurídico e LGPD** não certificam um ponto inventado nesta rodada — a decisão executiva fica com eles em não fabricar o residual de hoje.
- **Operações e Experiência** e **Marketing e Reputação** preferem furar 1,9% a fabricar o número com fila, constrangimento ou biometria em rede — a decisão executiva fica com eles em não religar o facial nem comprar o número com fila.

Sobre os sete pilotos (o comitê tinha congelado tudo; o painel de Tecnologia e Dados pedia um sucessor que não fosse só defensivo):

- O congelamento permanece nos dias 1 a 90, como Tecnologia e Financeiro pediram.
- Depois do dia 90, um sucessor redesenhado, com o professor no desenho e na ação — isso atende Marketing e Operações, que recusavam mais IA de treino ou churn sem o professor.
- IA de fraude no backoffice fica de fora neste ciclo, para não repetir base suja nem transformar o aluno em suspeito.

Sobre a ponte, se a plataforma recusar identidade (ninguém discorda do «não renovar como está»; o desenho da transição é que separa):

- **Parcerias** defende uma transição de volume em camadas, sem corte seco.
- **Jurídico e LGPD** quer ponte curta, com marco vinculante de identidade e saída automática; recusa fabricar identidade de beneficiário para vender plano direto.
- **Financeiro** aceita ponte curta com teto de volume se o mapa mostrar que repor o terço destruiria mais receita do que os 1,9 p.p. buscados — um corte do terço furaria cerca de 19% da receita.
- **Marketing e Reputação** exige aviso prévio, oferta clara e prazo digno.
- **Operações e Experiência** recusa duas classes na entrada e surpresa na catraca no pico (noites de semana e domingo às 18h).

---

## Como a inteligência artificial entra

A inteligência artificial entra no método, não na solução da catraca. As sete frentes diagnosticaram em separado, releram o recorte da banca e debateram os três conflitos restantes. O texto acima é o cruzamento, não uma média. Discordância do candidato com algum ponto do comitê também conta como parte de como a ferramenta foi usada.

O caminho acima é o recomendado pelo comitê, com cinco calibrações pedidas depois: (1) publicar a frequência implícita de ~4,4 visitas/mês do aluno de plataforma, derivada do próprio case; (2) tratar o split do 3,8% como baseline das primeiras 3 a 4 semanas, com alavanca em produção até o dia 60; (3) fechar as duas decisões que ainda estavam em aberto — desligar o facial nas 3 unidades de teste até o dia 60, e tomar a meta de 1,9% em 12 meses como a meta do caminho, fechada pelo pacote das três alavancas, sem deixá-la como «não certificada»; (4) não listar como fato do case o rito de a plataforma pedir que a academia reporte compartilhamento depois do fato — isso é evidência de mercado, não enunciado da banca; (5) pausar os sete pilotos como estão e, depois do dia 90, autorizar um sucessor único e contido — alerta ao professor sobre queda de frequência real na rede, para acolhimento humano — recusando IA na catraca e IA de fraude no backoffice neste ciclo.
