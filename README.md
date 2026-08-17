# RPG da Guilda — pacote de entrega

Material de mesa de um sistema de RPG de Jujutsu Kaisen, para um server de guilda com **5 a 7 mestres ativos** e **personagem persistente entre mesas**. Material de fã, gratuito, sem fins comerciais.

**Recorte da v0.88.** Manual do Fundamento na **v7.8**.

> ## Este repositório é ARTEFATO, e não fonte
>
> **Nada aqui é editado à mão.** Tudo é cópia, recortada do repositório de trabalho quando uma versão fecha.
>
> **A fonte é [cupcake-mochi/JJK---Project](https://github.com/cupcake-mochi/JJK---Project).** Correção descoberta aqui se aplica lá, e volta na próxima leva.
>
> **Ele existe por um motivo medido:** o repositório de trabalho tem `2,2 MB` de texto, e `628 KB` disso é o CHANGELOG — o registro de *por que* cada número é aquele. Para escrever texto de mesa isso é ruído, e ruído que gasta o contexto de quem está lendo. **Aqui são `816 KB`, e nenhum deles é histórico de decisão.**

---


## O que tem aqui

| pasta | o que é |
|---|---|
| `regra/` | as **dezessete peças** de mecânica, na ordem numérica |
| `desenho/` | o que **ainda não virou peça**: as Trilhas, os degraus de Caminho, as Manhas e a lista de gatilhos |
| `manual/` | o **Fundamento** — o subsistema de técnica e feitiço, fechado e validado. `.docx` na v7.8 |
| `ficha/` | a ficha em branco e uma ficha de exemplo preenchida, nível 2 |

> **Comece pela peça 17.** Ela é o índice das **89 entradas** que um personagem pode ganhar — 56 entregas de Trilha, 20 degraus de Caminho e as 13 Manhas — e diz, de cada uma, **como ela se chama e em qual arquivo de `desenho/` o texto dela mora.** *Ela não repete preço nem texto de mesa: para isso, ela te manda para o desenho.* **É o mapa mais curto que existe deste material.**

## ⚠ A primeira coisa a entender: as peças NÃO são texto de mesa

**Elas são argumento de design.** Cada uma explica por que o número é aquele, o que foi testado, o que morreu no caminho e o que ficou pendurado. Uma peça típica tem mais parágrafo de justificativa do que de regra.

**Para o PDF, o trabalho é transpor, não copiar.** A regra está lá dentro, quase sempre num bloco de citação (`>`) ou numa tabela. O resto é registro.

**E texto riscado, bloco de citação começando com *"Corrigido na v0.NN"* e nota em itálico são história.** Eles registram o que a regra **era**. Publicar um deles como regra viva é o erro mais fácil de cometer aqui.

## ⚠⚠ Três coisas que estão ERRADAS nos arquivos, e você vai encontrar

Nenhuma delas é opinião — todas foram medidas. *Eram seis até a v0.87; três fecharam na v0.88.*

**1 — A linha do físico está certa, e o aviso que existia aqui morreu na v0.82.** A peça 6 §3 publica `106` de dano por rodada no nível 30 para o combatente físico, somando feitiço de Toque **mais** golpe simples. *Uma versão inteira isso ficou marcado como dívida, porque um feitiço de Toque gasta a Ação Padrão conjurando.* **O golpe vem do ataque extra do nível 7, que é um golpe SOLTO por rodada e não exige a Ação de Atacar.** Está escrito na peça 6 §3.1, com validador em cima. *Publique o `106`; ele é o número certo.*

**2 — O `.pdf` do manual está na v7.4 e o `.docx` na v7.8.** *Ele é exportado à mão e por isso vive atrasado.* **Use o `.docx`.**

**3 — O `Batedor` estoura o orçamento em ~20%, e é de propósito.** A ação `Mirar` foi escrita na v0.86 — *Ação Bônus, vantagem no próximo tiro, e só se você não se deslocou nem vai se deslocar* — e ela custa `4,25` fatias num degrau de `0,80`. **As três rotas vão para `5,95` a `6,09` contra um teto de `5,00`, e as três passam a dominar a `Estocada` por `1,20×`.** *Decisão do Mizuki, mesmo molde do `Punho` e da `Brasa`, que já estão publicados estourados.* **Publique como está** — o argumento e os números estão em `desenho/DESENHO-trilhas.md`, na seção `A ação Mirar`.

## Uma tensão de nome que você vai notar, e ela é decidida

**A seção 5.5 da peça 1 se chama `Inconsciente`, e ela tem dois ramos.** *No `Aguentar` você apaga; no `Insistir` você fica **de pé** a 0 de vida e age normalmente, e só desaba na quarta rodada.*

**O nome cobre o `Aguentar` e o fim dos dois, e não cobre o meio do `Insistir`.** *Decisão do Mizuki na v0.88, com a alternativa `Queda` na mesa e recusada.* **Publique `Inconsciente`** — e não invente um nome para o ramo do `Insistir`, porque ele não tem um.

> *E não confunda com `Derrubado`, que é `Condição Menor` do manual: quem está `Derrubado` está no chão e continua com vida.*

## O que existe e o que NÃO existe

**Uma ficha de nível 2 fecha inteira**, por seis das nove rotas de Origem, e roda uma missão do começo ao fim.

| existe | onde |
|---|---|
| atributos, acerto, defesa, vida, energia, iniciativa | `regra/01` e `regra/02` |
| o turno e as Restrições | `regra/03` |
| perícias, ofícios, testes | `regra/04` e `regra/07` |
| os cinco Caminhos e as quinze Trilhas **por nome** | `regra/06` |
| **o índice das 89 entradas** — nome e onde o texto mora | `regra/17` |
| **as entregas de 12 das 15 Trilhas**, e o `Batedor` conta as três rotas | `desenho/DESENHO-trilhas.md` |
| **os 20 degraus dos cinco Caminhos** | `desenho/DESENHO-caminhos.md` |
| **as 13 Manhas** — o nível 2 da Vanguarda | `desenho/DESENHO-manhas.md` |
| **as doze Ações Padrão** — Atacar, Conjurar, Correr, Esquivar, Ajudar… | `regra/03`, seção 3.1 |
| **as duas Ações Bônus** — `Provocar` e `Ler o Ambiente` | **no FIM do** `desenho/DESENHO-caminhos.md` |
| criação de personagem, em oito passos, com ficha de exemplo | `regra/08` |
| Origens, Legados, descanso, XP, aptidões, equipamento, invocações, ferramenta | `regra/09` a `regra/16` |
| técnica, feitiço, Melhoria, Restrição, Expansão de Domínio | `manual/` |
| vida e dano de chefe e capanga por nível | `manual/`, tabela de inimigo |

| NÃO existe | tamanho do buraco |
|---|---|
| **As três Trilhas do Evocador** — `Servo`, `Matilha` e `Coro` | cortadas de propósito: ninguém vai jogar de Evocador no primeiro teste. *O `Servo` tem um rascunho pronto no `RASCUNHO-trilhas.md` §6.10, que não veio para cá* |
| **Régua de condição** | não existe conversão de condição em preço. O `Abalo` das Manhas aplica `Derrubado` — que é `Condição Menor` do manual — com o efeito escrito por extenso |
| **Tabela de progressão consolidada** | o que se ganha em cada nível está espalhado por cinco documentos |
| **Playtest** | zero sessões. **Todo número deste sistema é previsão** |
| **Nome do sistema** | aberto desde a v0.1 |

## As réguas que valem, se você precisar conferir alguma conta

*Tudo medido no nível 30, que é onde a fatia foi definida.*

- **A fatia é `5,08` de dano por rodada.** Uma Trilha inteira leva `5` fatias; um Caminho leva `3`.
- **`+1` no seu acerto vale `10,80` por rodada** — `10%` da Rotina. É por isso que quase nada que mexe no d20 cabe num degrau.
- **Dano evitado converte `1` pra `1`.** PV temporário, resistência e redução, todos. *A conversão de PONTO do manual, `3` por ponto, é a moeda de montar feitiço e não serve para preçar entrega de Caminho ou Trilha.*
- **Rerrolar e dar vantagem valem os mesmos `+25` pontos percentuais.**
- **A Rotina é `floor(3,5 × Classe)` dados**, e ela é do manual.
- **Um Classe 0 causa `27` no nível 30** — `2d8` a `6d8` por faixa, tabela do manual. *No nível 30 um Classe 0 e um Classe 2 num alvo causam os dois `27`.*
- **O vão `físico − conjurador` é `9 · 10 · 11 · 12`**, e ele é exatamente um golpe simples. *Ver o item 3 acima antes de usar.*

## O que NÃO tem régua, e por isso não se inventa preço

**Gastar PE**, **condição**, e **"uma aptidão a mais"**. *A última não pode ter régua: ela vale a Trilha inteira para quem nunca escolhe Refino e um sétimo para quem sempre escolhe — foi ela que matou o `Repertório`.*

## Licença e escopo

Material de fã, sem fins comerciais, não afiliado à Shueisha, à MAPPA nem a Gege Akutami. Jujutsu Kaisen e seus personagens pertencem aos detentores originais.
