# Projeto - M — pacote de entrega

Material de mesa de um sistema de RPG de Jujutsu Kaisen, para um server de guilda com **5 a 7 mestres ativos** e **personagem persistente entre mesas**. Material de fã, gratuito, sem fins comerciais.

**Recorte da v0.167.** Manual do Fundamento na **v7.17**, e o Manual da Guilda em **17 capítulos**, 245 páginas.

> ## Este repositório é ARTEFATO, e não fonte
>
> **Nada aqui é editado à mão.** Tudo é cópia, recortada do repositório de trabalho quando uma versão fecha.
>
> **A fonte é [cupcake-mochi/JJK---Project](https://github.com/cupcake-mochi/JJK---Project).** Correção descoberta aqui se aplica lá, e volta na próxima leva.
>
> **Ele existe por um motivo medido:** o repositório de trabalho tem `4,9 MB`, e `732 KB` disso é o CHANGELOG — o registro de *por que* cada número é aquele. Para escrever texto de mesa isso é ruído, e ruído que gasta o contexto de quem está lendo. **Aqui são `2,0 MB`, e mais da metade é o `.pdf` do manual: nenhum byte é histórico de decisão.**

---


## O que tem aqui

| pasta | o que é |
|---|---|
| `regra/` | as **vinte e quatro peças** de mecânica, na ordem numérica |
| `desenho/` | o que **ainda não virou peça**: as Trilhas, os degraus de Caminho, as Manhas, a lista de gatilhos, o esqueleto e a regra opcional do `Bloquear` |
| `manual/` | o **Fundamento** — o subsistema de técnica e feitiço, fechado e validado. `.docx` e `.pdf` na **v7.17** |
| `ficha/` | a ficha em branco e uma ficha de exemplo preenchida, nível 2 |
| `livro/` | **o Manual da Guilda inteiro** — o texto de mesa que a v0.102 decidiu escrever direto no PDF. 18 capítulos, 238 páginas, `.pdf` e `.docx` de revisão |

> ## Um arquivo de `desenho/` não é desenho, e ele entrou na v0.98
>
> **O `arquitetura.md` é o esqueleto do sistema**, e a maior parte dele é história de decisão que não interessa para o PDF. *Ele está aqui por uma linha só:* **a seção 4.3 tem a tabela de quanto refino cada rota tem em cada marco**, do nv6 ao nv30 — e ela não existe em nenhuma peça. **Sem ela não dá para publicar progressão.**
>
> ***O rascunho do `Bloquear` saiu daqui na v0.143.*** *Ele era a regra opcional, e o `Bloquear` deixou de ser opcional:* **virou a peça 23, e ela mora em `regra/23-bloquear.md` como qualquer outra.** *O rascunho foi para o arquivo morto do projeto, e material morto não vem para a entrega.*
>
> *O nome do arquivo velho não é citado aqui de propósito: a checagem 7.2 procura ponteiro por **texto**, e não distingue "abra este arquivo" de "este arquivo deixou de existir".*
>
> **Os dois vieram porque a entrega apontava para eles e não os carregava.** *Até a v0.97 eram 19 ponteiros pendurados; agora a checagem 7 do `conferir-repositorio.py` acusa se voltar a acontecer.* **Hoje sobrou um: o `arquitetura.md`.**

> **Comece pela peça 17.** Ela é o índice das **102 entradas** que um personagem pode ganhar — 68 entregas de Trilha, 20 degraus de Caminho e as 14 Manhas — e diz, de cada uma, **como ela se chama e em qual arquivo de `desenho/` o texto dela mora.** *Ela não repete preço nem texto de mesa: para isso, ela te manda para o desenho.* **É o mapa mais curto que existe deste material.**

## O plano do livro — dezesseis capítulos em três partes

**Decisão do Mizuki. Este é o índice a seguir, e ele não é sugestão.**

*O rascunho da v0.97 inventou o próprio índice, com oito capítulos, e deixou de fora onze que o jogador precisa. O efeito está medido no PDF que ele produziu: a palavra `Perícia` aparece 35 vezes, `Descanso` 34, `Refino` 15 e `Exaustão` 4 — e nenhum capítulo diz o que qualquer uma delas é.*

**A ordem existe por um motivo só: nenhum termo aparece antes de ter capítulo.**

| # | capítulo | de onde sai |
|---|---|---|
| | **PARTE 1 — O JOGO** | |
| 1 | Atributos, acerto, defesa, `Bloquear`, vida e energia | `regra/01` · `regra/02` · `regra/23` |
| 4 | Dano, condições, cobertura e **dano de alma** | `regra/19` · `regra/24` |
| 2 | O turno, a iniciativa e as doze Ações | `regra/03` · `regra/05` |
| 3 | Perícias, ofícios e testes | `regra/04` · `regra/07` |
| 4 | Dano, condições e cobertura | `regra/19` |
| 5 | Descanso e recuperação | `regra/10` |
| | **PARTE 2 — O PERSONAGEM** | |
| 6 | Criação de personagem, em oito passos | `regra/08` |
| 7 | Origens e Legados | `regra/09` · `regra/13` |
| 8 | Caminhos | `regra/06` · `desenho/DESENHO-caminhos.md` |
| 9 | Trilhas | `desenho/DESENHO-trilhas.md` · `desenho/LISTA-gatilhos-trilhas.md` |
| 10 | Manhas | `desenho/DESENHO-manhas.md` |
| 11 | Fundamento — técnica e feitiço | `manual/` |
| 12 | Aptidões e refino | `regra/11` · `desenho/arquitetura.md` §4.3 |
| 13 | Equipamento | `regra/14` |
| 14 | Ferramenta amaldiçoada | `regra/16` |
| 15 | Invocações | `regra/15` |
| | **PARTE 3 — A CAMPANHA** | |
| 16 | Experiência e progressão | `regra/12` · `regra/18` |

**A `regra/17` não vira capítulo.** Ela é índice das 102 entradas, e o sumário do livro faz o trabalho dela. *Ela continua sendo o melhor mapa para escrever — só não é material de mesa.*

### O tamanho, medido contra o rascunho da v0.97

**A compressão real é de 14%:** as 112 mil palavras de peça e desenho que o rascunho publicou viraram 62 páginas. Os onze capítulos que faltam somam 52 mil palavras de fonte, então saem **28 a 38 páginas**.

**O livro fechou em 230 páginas** — a estimativa de 140 daqui era de antes de existir texto de
verdade. Está em `livro/Projeto-M-Manual-da-Guilda.pdf`, com quick-start, glossário e índice
remissivo, nenhum deles previstos nesta estimativa original.

> ### ⚠ Dois defeitos de pipeline do rascunho, para não repetir
>
> **1 — O sumário tem número de página errado, e a causa é `id` duplicado.** No capítulo de Trilhas, as cinco entradas de Caminho apontam para as páginas 64 a 67, que são o capítulo anterior. Mesmo defeito no capítulo de Invocações, onde *"O catálogo"* aponta para a página 84, que é o capítulo de Manhas. **O `target-counter(attr(href), page)` resolve para o primeiro elemento com aquele `id`**, e duas seções de mesmo nome em capítulos diferentes viram o mesmo `id`. *Conserto: prefixe o `id` com o capítulo.*
>
> **2 — O Fundamento precisa ser regerado, e não reaproveitado.** O rascunho transcreveu o manual na `v7.9`. Ele está na **v7.17**, e três coisas mudaram desde lá: a v0.104 mexeu em dois feitiços prontos — `Palma Trovejante` de `5d8` para `6d8`, e `Vala Comum` de `9d8` para `11d8` —, e a v0.107 devolveu o piso `Classe 3 ou mais` à regra de ouro nº 5, que estava publicado em outros três lugares do manual e faltava justamente na tabela que o checklist do mestre segue; e a v0.159 acertou a seção `Integridade` — ela publicava `Integridade = vida máxima` sem dizer para quem, e essa linha é do inimigo e não do personagem jogador — e deu à seção `Inimigos` as duas linhas que o mestre marca na ficha, Integridade e Reação. *É trabalho mecânico — transcrever o `.docx` —, mas não é copiar o capítulo antigo.*

## ⚠ A primeira coisa a entender: as peças NÃO são texto de mesa

**Elas são argumento de design.** Cada uma explica por que o número é aquele, o que foi testado, o que morreu no caminho e o que ficou pendurado. Uma peça típica tem mais parágrafo de justificativa do que de regra.

**Para o PDF, o trabalho é transpor, não copiar.** A regra está lá dentro, quase sempre num bloco de citação (`>`) ou numa tabela. O resto é registro.

**E texto riscado, bloco de citação começando com *"Corrigido na v0.NN"* e nota em itálico são história.** Eles registram o que a regra **era**. Publicar um deles como regra viva é o erro mais fácil de cometer aqui.

## ⚠⚠ Quando você achar um buraco, DECLARE — a passada anterior inventou

**Isto aconteceu de verdade, e foi medido.** O rascunho de PDF da v0.97 chegou nas três Trilhas do Evocador, não achou entrega escrita para nenhuma das três, e abriu a seção com esta frase:

> *"As três Trilhas do Evocador não seguem a tabela de 2 · 11 · 19 · 27 das outras doze."*

**Ninguém neste material diz isso.** Quatro arquivos daqui dizem o contrário, e afirmam que o calendário `2 · 11 · 19 · 27` vale para toda Trilha, sem exceção: a `regra/05`, a `regra/06`, a `regra/08` e o `desenho/DESENHO-trilhas.md`. *No repositório de trabalho ainda tem um quinto, o rascunho de Trilhas, que não vem para cá.*

*A tabela que vinha logo abaixo daquela frase era legítima — ela sai da `regra/15`, que preça o que cada uma das três concede em orçamento de corpo e em vida de corpo.* **O que era invenção era a moldura**, e é a moldura que faz o estrago: ela transforma *"isto não foi escrito"* em *"isto é assim de propósito"*. Um leitor de mesa não tem como descobrir a diferença.

**O que fazer no lugar, e o próprio rascunho já sabia:** no mesmo capítulo, o nível 27 do `Arremate` saiu escrito como *"Sem entrega publicada"*. **É essa a forma certa.** Diga que falta, diga que está parado, e siga.

> ### O buraco do Evocador, com o tamanho dele
>
> **As três Trilhas do Evocador — `Servo`, `Matilha` e `Coro` — não têm entrega escrita**, e estão paradas desde a v0.82. O que existe delas: o nome, a frase de uma linha na `regra/06`, e a tabela da `regra/15` que diz o orçamento e a vida do corpo de cada uma.
>
> **O que NÃO existe são as quatro entregas de níveis `2 · 11 · 19 · 27` das três.**
>
> **O tamanho, em número:** a Trilha se escolhe no nível 2, junto do Caminho, e é obrigatória. Uma Trilha inteira leva `5` fatias de orçamento e um Caminho leva `3`. **Um Evocador sai com `5` de `8` fatias faltando — 62,5% do orçamento da ficha.** Os quatro degraus de Caminho dele estão escritos com texto de mesa; a camada de Trilha está vazia inteira.
>
> **Publique o Evocador com o buraco declarado.** O Caminho dele é jogável — `Sintonia`, `Coleira`, `Escudo de Osso` e `Segundo Corpo` têm texto. **A Trilha não é**, e o capítulo tem de dizer isso com todas as letras, do mesmo jeito que o `Arremate` diz.

## ⚠⚠ Três coisas que estão ERRADAS nos arquivos, e você vai encontrar

Nenhuma delas é opinião — todas foram medidas. *Eram seis até a v0.87; três fecharam na v0.88.*

**1 — A linha do físico está certa, e o aviso que existia aqui morreu na v0.82.** A peça 6 §3 publica `106` de dano por rodada no nível 30 para o combatente físico, somando feitiço de Toque **mais** golpe simples. *Uma versão inteira isso ficou marcado como dívida, porque um feitiço de Toque gasta a Ação Padrão conjurando.* **O golpe vem do ataque extra do nível 7, que é um golpe SOLTO por rodada e não exige a Ação de Atacar.** Está escrito na peça 6 §3.1, com validador em cima. *Publique o `106`; ele é o número certo.*

~~**2 — O `.pdf` do manual está atrasado em relação ao `.docx`.**~~ **Resolvido na v0.93:** o `.pdf` deixou de ser exportado a mão e sai junto. *Os dois estão na* **v7.17**, *e pode usar qualquer um.*

**3 — O `Batedor` estoura o orçamento em ~20%, e é de propósito.** A ação `Mirar` foi escrita na v0.86 — *Ação Bônus, vantagem no próximo tiro, e só se você não se deslocou nem vai se deslocar* — e ela custa `4,25` fatias num degrau de `0,80`. **As três rotas vão para `5,95` a `6,09` contra um teto de `5,00`, e as três passam a dominar a `Estocada` por `1,20×`.** *Decisão do Mizuki, no mesmo molde da `Brasa`, que já está publicada estourada.* **Publique como está** — o argumento e os números estão em `desenho/DESENHO-trilhas.md`, na seção `A ação Mirar`.

> *⚠ Esta linha citava o `Punho` como segundo precedente, e ele caiu na v0.103: aquele estouro de `22%` era erro de preço — o `Derrubado` do nível 11 estava preçado como permanente, sem os dois portões que o texto da entrega escreve. Com eles a Trilha cabe em `4,94` de `5,00`. **A conta destas três rotas não muda; o que muda é qual precedente elas citam.** O maior estouro aceito do projeto passa a ser a `Brasa`, entre `41%` e `88%`.*

## Uma tensão de nome que você vai notar, e ela é decidida

**A seção 5.5 da peça 1 se chama `Inconsciente`, e ela tem dois ramos.** *No `Aguentar` você apaga; no `Insistir` você fica **de pé** a 0 de vida e age normalmente, e só desaba na quarta rodada.*

**O nome cobre o `Aguentar` e o fim dos dois, e não cobre o meio do `Insistir`.** *Decisão do Mizuki na v0.88, com a alternativa `Queda` na mesa e recusada.* **Publique `Inconsciente`** — e não invente um nome para o ramo do `Insistir`, porque ele não tem um.

> *E não confunda com `Derrubado`, que é condição de nível `Leve`: quem está `Derrubado` está no chão e continua com vida.*

> *⚠ Esta linha dizia que o `Derrubado` era `Condição Menor` do manual. **A `Condição Menor` e a `Condição Maior` deixaram de existir na v0.104** — as duas viraram uma Melhoria só, chamada `Condição`, e o preço dela é o **nível** da condição escolhida. O `Derrubado` desceu de `Média` para `Leve` na mesma versão.*

## O que existe e o que NÃO existe

**Uma ficha de nível 2 fecha inteira**, por seis das nove rotas de Origem, e roda uma missão do começo ao fim.

| existe | onde |
|---|---|
| atributos, acerto, defesa, vida, energia | `regra/01` e `regra/02` |
| o turno, a iniciativa e as Restrições | `regra/03` |
| perícias, ofícios, testes | `regra/04` e `regra/07` |
| os cinco Caminhos e as quinze Trilhas **por nome** | `regra/06` |
| **o índice das 102 entradas** — nome e onde o texto mora | `regra/17` |
| **as entregas de 12 das 15 Trilhas**, e o `Batedor` conta as três rotas | `desenho/DESENHO-trilhas.md` |
| **os 20 degraus dos cinco Caminhos** | `desenho/DESENHO-caminhos.md` |
| **as 13 Manhas** — o nível 2 da Vanguarda | `desenho/DESENHO-manhas.md` |
| **as doze Ações Padrão** — Atacar, Conjurar, Correr, Esquivar, Ajudar… | `regra/03`, seção 3.1 |
| **as duas Ações Bônus** — `Provocar` e `Ler o Ambiente` | `regra/03`, seção 3.1. *A conta de preço das duas está no fim do* `desenho/DESENHO-caminhos.md` |
| **o alcance de cada arma de projétil e arremesso** — as 19, em metros | `regra/14`, seção 5.2.2 |
| **Cobertura** — Parcial, Boa e Total | `regra/19`, seção 5 |
| **as treze condições**, com o efeito de cada uma e o nível de cada uma | `regra/19`, seção 3, e `manual/` |
| **os catorze tipos de dano**, em três grupos | `regra/19`, seção 4 |
| **quanto vale uma condição**, em dano por rodada e em fatia | `regra/19`, seção 2 |
| criação de personagem, em oito passos, com ficha de exemplo | `regra/08` |
| Origens, Legados, descanso, XP, aptidões, equipamento, invocações, ferramenta | `regra/09` a `regra/16` |
| **dano e condições** — a régua, as treze condições, os tipos de dano e a cobertura | `regra/19` |
| técnica, feitiço, Melhoria, Restrição, Expansão de Domínio | `manual/` |
| vida e dano de chefe e capanga por nível | `manual/`, tabela de inimigo |
| **o que você ganha em cada nível, do 1 ao 30** — XP, maestria, espaços de feitiço, refino, Classe, Passiva, Classe 0 e os eventos | `regra/18`, numa tabela só |
| **quanto refino você tem em cada marco** — as três rotas, do nv6 ao nv30 | `desenho/arquitetura.md`, seção 4.3 |
| **`Bloquear`** — rolar `2d10` no lugar da Defesa parada, e ele vale em toda mesa | `regra/23` |
| **Dano de alma** — a Integridade leva Essência, os quatro estágios, e o dano que atravessa o corpo | `regra/24` |

| NÃO existe | tamanho do buraco |
|---|---|
| **As três Trilhas do Evocador** — `Servo`, `Matilha` e `Coro` | **paradas desde a v0.82, e o buraco é `5` de `8` fatias da ficha.** *O `Servo` tem um rascunho pronto no repositório de trabalho, que não veio para cá.* **Leia a seção *"Quando você achar um buraco, DECLARE"* antes de escrever este capítulo** — a passada anterior inventou uma exceção aqui |
| ~~**Régua de PREÇO de condição**~~ | **existe desde a v0.103: é a `regra/19`, seção 2.** *Cada uma das treze tem valor em dano por rodada e nível — `Leve`, `Média` ou `Pesada` —, e tirar uma custa `1` ponto de energia por nível.* **A força continua sendo previsão até alguém jogar** |
| ~~Tabela de progressão consolidada~~ | **existe desde a v0.99: é a `regra/18`.** *Uma tabela, do nível 1 ao 30* |
| **Playtest** | zero sessões. **Todo número deste sistema é previsão** |
| ~~Nome do sistema~~ | **`Projeto - M`, batizado na v0.94** |

## As réguas que valem, se você precisar conferir alguma conta

*Tudo medido no nível 30, que é onde a fatia foi definida.*

- **A fatia é `5,08` de dano por rodada.** Uma Trilha inteira leva `5` fatias; um Caminho leva `3`.
- **`+1` no seu acerto vale `10,80` por rodada** — `10%` da Rotina. É por isso que quase nada que mexe no d20 cabe num degrau.
- **Dano evitado converte `1` pra `1`.** PV temporário, resistência e redução, todos. *A conversão de PONTO do manual, `3` por ponto, é a moeda de montar feitiço e não serve para preçar entrega de Caminho ou Trilha.*
- **Rerrolar e dar vantagem valem os mesmos `+25` pontos percentuais.**
- **A Rotina é `floor(3,5 × Classe)` dados**, e ela é do manual.
- **Um Classe 0 causa `27` no nível 30** — `2d8` a `6d8` por faixa, tabela do manual. *No nível 30 um Classe 0 e um Classe 2 num alvo causam os dois `27`.*
- **O vão `físico − conjurador` é `9 · 10 · 11 · 12`**, e ele é exatamente um golpe simples. *Ver o item 3 acima antes de usar.*

## ⚠ Duas regras vieram do d20, de propósito, e isso está declarado

**O alcance das armas e a Cobertura foram importados e convertidos**, em vez de derivados aqui. *`5 pés = 1,5 m`, a mesma conversão que põe o deslocamento em `9 m`.*

**O motivo é honesto: nenhuma das duas tem preço neste sistema.** *O `Longo Alcance` custa `1` ponto por existir e não por quanto, e cobertura não tem conversão em fatia.* **Então o número não sai de conta nenhuma daqui — ele só precisa ser plausível, consistente e igual em sete mesas.**

**Ao escrever o PDF, pode publicar os dois como regra normal.** *A origem está registrada na peça para quem for reler; não é ressalva de mesa.*

## O que NÃO tem régua, e por isso não se inventa preço

**Gastar PE** e **"uma aptidão a mais"**. *A última não pode ter régua: ela vale a Trilha inteira para quem nunca escolhe Refino e um sétimo para quem sempre escolhe — foi ela que matou o `Repertório`.*

> *⚠ `condição` estava nesta lista, e ela saiu na v0.103.* **A régua de preço de condição existe: é a `regra/19`, seção 2**, e a linha da tabela acima já dizia isso — este parágrafo contradizia aquela linha 27 linhas depois.

## Licença e escopo

Material de fã, sem fins comerciais, não afiliado à Shueisha, à MAPPA nem a Gege Akutami. Jujutsu Kaisen e seus personagens pertencem aos detentores originais.
