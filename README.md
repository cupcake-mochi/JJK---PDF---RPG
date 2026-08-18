# Projeto - M — pacote de entrega

Material de mesa de um sistema de RPG de Jujutsu Kaisen, para um server de guilda com **5 a 7 mestres ativos** e **personagem persistente entre mesas**. Material de fã, gratuito, sem fins comerciais.

**Recorte da v0.103.** Manual do Fundamento na **v7.9**.

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
| `regra/` | as **dezenove peças** de mecânica, na ordem numérica |
| `desenho/` | o que **ainda não virou peça**: as Trilhas, os degraus de Caminho, as Manhas, a lista de gatilhos, o esqueleto e a regra opcional do `Bloquear` |
| `manual/` | o **Fundamento** — o subsistema de técnica e feitiço, fechado e validado. `.docx` e `.pdf` na **v7.9** |
| `ficha/` | a ficha em branco e uma ficha de exemplo preenchida, nível 2 |

> ## Dois arquivos de `desenho/` não são desenho, e entraram na v0.98
>
> **O `arquitetura.md` é o esqueleto do sistema**, e a maior parte dele é história de decisão que não interessa para o PDF. *Ele está aqui por uma linha só:* **a seção 4.3 tem a tabela de quanto refino cada rota tem em cada marco**, do nv6 ao nv30 — e ela não existe em nenhuma peça. **Sem ela não dá para publicar progressão.**
>
> **O `RASCUNHO-bloqueio.md` é a regra opcional do `Bloquear`** — rolar `2d10` no lugar da Defesa estática. *Metade da condição `Incapacitado` depende dela*, e a peça 1 mandava o leitor abrir um arquivo que não estava aqui.
>
> **Os dois vieram porque a entrega apontava para eles e não os carregava.** *Até a v0.97 eram 19 ponteiros pendurados; agora a checagem 7 do `conferir-repositorio.py` acusa se voltar a acontecer.*

> **Comece pela peça 17.** Ela é o índice das **89 entradas** que um personagem pode ganhar — 56 entregas de Trilha, 20 degraus de Caminho e as 13 Manhas — e diz, de cada uma, **como ela se chama e em qual arquivo de `desenho/` o texto dela mora.** *Ela não repete preço nem texto de mesa: para isso, ela te manda para o desenho.* **É o mapa mais curto que existe deste material.**

## ⚠ A primeira coisa a entender: as peças NÃO são texto de mesa

**Elas são argumento de design.** Cada uma explica por que o número é aquele, o que foi testado, o que morreu no caminho e o que ficou pendurado. Uma peça típica tem mais parágrafo de justificativa do que de regra.

**Para o PDF, o trabalho é transpor, não copiar.** A regra está lá dentro, quase sempre num bloco de citação (`>`) ou numa tabela. O resto é registro.

**E texto riscado, bloco de citação começando com *"Corrigido na v0.NN"* e nota em itálico são história.** Eles registram o que a regra **era**. Publicar um deles como regra viva é o erro mais fácil de cometer aqui.

## ⚠⚠ Três coisas que estão ERRADAS nos arquivos, e você vai encontrar

Nenhuma delas é opinião — todas foram medidas. *Eram seis até a v0.87; três fecharam na v0.88.*

**1 — A linha do físico está certa, e o aviso que existia aqui morreu na v0.82.** A peça 6 §3 publica `106` de dano por rodada no nível 30 para o combatente físico, somando feitiço de Toque **mais** golpe simples. *Uma versão inteira isso ficou marcado como dívida, porque um feitiço de Toque gasta a Ação Padrão conjurando.* **O golpe vem do ataque extra do nível 7, que é um golpe SOLTO por rodada e não exige a Ação de Atacar.** Está escrito na peça 6 §3.1, com validador em cima. *Publique o `106`; ele é o número certo.*

~~**2 — O `.pdf` do manual está atrasado em relação ao `.docx`.**~~ **Resolvido na v0.93:** o `.pdf` deixou de ser exportado a mão e sai junto. *Os dois estão na* **v7.9**, *e pode usar qualquer um.*

**3 — O `Batedor` estoura o orçamento em ~20%, e é de propósito.** A ação `Mirar` foi escrita na v0.86 — *Ação Bônus, vantagem no próximo tiro, e só se você não se deslocou nem vai se deslocar* — e ela custa `4,25` fatias num degrau de `0,80`. **As três rotas vão para `5,95` a `6,09` contra um teto de `5,00`, e as três passam a dominar a `Estocada` por `1,20×`.** *Decisão do Mizuki, mesmo molde do `Punho` e da `Brasa`, que já estão publicados estourados.* **Publique como está** — o argumento e os números estão em `desenho/DESENHO-trilhas.md`, na seção `A ação Mirar`.

## Uma tensão de nome que você vai notar, e ela é decidida

**A seção 5.5 da peça 1 se chama `Inconsciente`, e ela tem dois ramos.** *No `Aguentar` você apaga; no `Insistir` você fica **de pé** a 0 de vida e age normalmente, e só desaba na quarta rodada.*

**O nome cobre o `Aguentar` e o fim dos dois, e não cobre o meio do `Insistir`.** *Decisão do Mizuki na v0.88, com a alternativa `Queda` na mesa e recusada.* **Publique `Inconsciente`** — e não invente um nome para o ramo do `Insistir`, porque ele não tem um.

> *E não confunda com `Derrubado`, que é `Condição Menor` do manual: quem está `Derrubado` está no chão e continua com vida.*

## O que existe e o que NÃO existe

**Uma ficha de nível 2 fecha inteira**, por seis das nove rotas de Origem, e roda uma missão do começo ao fim.

| existe | onde |
|---|---|
| atributos, acerto, defesa, vida, energia | `regra/01` e `regra/02` |
| o turno, a iniciativa e as Restrições | `regra/03` |
| perícias, ofícios, testes | `regra/04` e `regra/07` |
| os cinco Caminhos e as quinze Trilhas **por nome** | `regra/06` |
| **o índice das 89 entradas** — nome e onde o texto mora | `regra/17` |
| **as entregas de 12 das 15 Trilhas**, e o `Batedor` conta as três rotas | `desenho/DESENHO-trilhas.md` |
| **os 20 degraus dos cinco Caminhos** | `desenho/DESENHO-caminhos.md` |
| **as 13 Manhas** — o nível 2 da Vanguarda | `desenho/DESENHO-manhas.md` |
| **as doze Ações Padrão** — Atacar, Conjurar, Correr, Esquivar, Ajudar… | `regra/03`, seção 3.1 |
| **as duas Ações Bônus** — `Provocar` e `Ler o Ambiente` | `regra/03`, seção 3.1. *A conta de preço das duas está no fim do* `desenho/DESENHO-caminhos.md` |
| **o alcance de cada arma de projétil e arremesso** — as 19, em metros | `regra/14`, seção 5.2.2 |
| **Cobertura** — Parcial, Boa e Total | `regra/19`, seção 5 |
| **as catorze condições**, com o efeito de cada uma e o nível de cada uma | `regra/19`, seção 3, e `manual/` |
| **os catorze tipos de dano**, em três grupos | `regra/19`, seção 4 |
| **quanto vale uma condição**, em dano por rodada e em fatia | `regra/19`, seção 2 |
| criação de personagem, em oito passos, com ficha de exemplo | `regra/08` |
| Origens, Legados, descanso, XP, aptidões, equipamento, invocações, ferramenta | `regra/09` a `regra/16` |
| **dano e condições** — a régua, as catorze condições, os tipos de dano e a cobertura | `regra/19` |
| técnica, feitiço, Melhoria, Restrição, Expansão de Domínio | `manual/` |
| vida e dano de chefe e capanga por nível | `manual/`, tabela de inimigo |
| **o que você ganha em cada nível, do 1 ao 30** — XP, maestria, espaços de feitiço, refino, Classe, Passiva, Classe 0 e os eventos | `regra/18`, numa tabela só |
| **quanto refino você tem em cada marco** — as três rotas, do nv6 ao nv30 | `desenho/arquitetura.md`, seção 4.3 |
| **`Bloquear`** — a regra opcional de rolar `2d10` no lugar da Defesa estática | `desenho/RASCUNHO-bloqueio.md` |

| NÃO existe | tamanho do buraco |
|---|---|
| **As três Trilhas do Evocador** — `Servo`, `Matilha` e `Coro` | cortadas de propósito: ninguém vai jogar de Evocador no primeiro teste. *O `Servo` tem um rascunho pronto no `RASCUNHO-trilhas.md` §6.10, que não veio para cá* |
| ~~**Régua de PREÇO de condição**~~ | **existe desde a v0.103: é a `regra/19`, seção 2.** *Cada uma das catorze tem valor em dano por rodada e nível — `Leve`, `Média` ou `Pesada` —, e tirar uma custa `1` ponto de energia por nível.* **A força continua sendo previsão até alguém jogar** |
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

**Gastar PE**, **condição**, e **"uma aptidão a mais"**. *A última não pode ter régua: ela vale a Trilha inteira para quem nunca escolhe Refino e um sétimo para quem sempre escolhe — foi ela que matou o `Repertório`.*

## Licença e escopo

Material de fã, sem fins comerciais, não afiliado à Shueisha, à MAPPA nem a Gege Akutami. Jujutsu Kaisen e seus personagens pertencem aos detentores originais.
