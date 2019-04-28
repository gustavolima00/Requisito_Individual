# flop
### C3092 {#id=3092}

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    flop   |
|  **Objetivo** |    Acumular apostas no [pote](lexicos10xf6da0.md#id=12678) com 5 cartas possíveis para a [mão](lexicos10xf6da0.md#id=12686) de cada jogador   |
|  **Contexto** |    Fim do PRÉ-FLOP   |
|  **Atores**   |    [dealer](lexicos10xf6da0.md#id=12688)   |
|  **Recursos** |    Jogadores, [pote](lexicos10xf6da0.md#id=12678), baralho, mesa.   |
|  **Excecão**  |    Jogadores deram [fold](lexicos10xf6da0.md#id=12677), restando apenas 1 jogador no PRÉ-FLOP   |
|  **Episódio** |    [dealer](lexicos10xf6da0.md#id=12688) vira 3 cartas na mesa, visíveis para todos os jogadores.</br>Jogador a esquerda do [jogador com o botão](lexicos10xf6da0.md#id=12687) inicia as apostas ou realiza o [check](lexicos10xf6da0.md#id=12679).</br>Outros jogadores fazem o mesmo terminando no [jogador com o botão](lexicos10xf6da0.md#id=12687).</br>Caso os jogadores derem [fold](lexicos10xf6da0.md#id=12677) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos10xf6da0.md#id=12678).</br>Caso as apostas se igualem o [dealer](lexicos10xf6da0.md#id=12688) junta todas as fichas e coloca no [pote](lexicos10xf6da0.md#id=12678).</br>[dealer](lexicos10xf6da0.md#id=12688) realiza o  [turn](cenarios10xf6da0.md#id=3093).   |


# pré-flop
### C3091 {#id=3091}

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    pré-flop   |
|  **Objetivo** |    Acumular apostas no [pote](lexicos10xf6da0.md#id=12678) sem cartas na mesa   |
|  **Contexto** |    Inicio da  [rodada](cenarios10xf6da0.md#id=3096).   |
|  **Atores**   |    [dealer](lexicos10xf6da0.md#id=12688)   |
|  **Recursos** |    Jogadores, baralho, mesa.   |
|  **Excecão**  |    Na mesa possuem menos que 2 jogadores apenas.   |
|  **Episódio** |    Jogador uma posição a esquerda do [jogador com o botão](lexicos10xf6da0.md#id=12687) aposta o [small blind](lexicos10xf6da0.md#id=12682).</br>Jogador duas posições a esquerda do [jogador com o botão](lexicos10xf6da0.md#id=12687) aposta o [big blind](lexicos10xf6da0.md#id=12681).</br>Caso os jogadores derem [fold](lexicos10xf6da0.md#id=12677) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos10xf6da0.md#id=12678).</br>Caso as apostas se igualem o [dealer](lexicos10xf6da0.md#id=12688) reúne as apostas no [pote](lexicos10xf6da0.md#id=12678) e realiza o  [flop](cenarios10xf6da0.md#id=3092).   |


# river
### C3094 {#id=3094}

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    river   |
|  **Objetivo** |    Declarar o vencedor com [mão](lexicos10xf6da0.md#id=12686) mais forte.   |
|  **Contexto** |    Fim do  [turn](cenarios10xf6da0.md#id=3093)   |
|  **Atores**   |    [dealer](lexicos10xf6da0.md#id=12688)   |
|  **Recursos** |    Jogadores, [mão](lexicos10xf6da0.md#id=12686) dos jogadores,[pote](lexicos10xf6da0.md#id=12678), baralho, mesa.   |
|  **Excecão**  |    Jogadores deram [fold](lexicos10xf6da0.md#id=12677), restando apenas 1 jogador no  [turn](cenarios10xf6da0.md#id=3093).   |
|  **Episódio** |    [dealer](lexicos10xf6da0.md#id=12688) vira mais 1 cartas na mesa, visível para todos os jogadores.</br>Jogador a esquerda do [jogador com o botão](lexicos10xf6da0.md#id=12687) inicia as apostas ou realiza o [check](lexicos10xf6da0.md#id=12679).</br>Outros jogadores fazem o mesmo terminando no [jogador com o botão](lexicos10xf6da0.md#id=12687).</br>Caso os jogadores derem [fold](lexicos10xf6da0.md#id=12677) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos10xf6da0.md#id=12678).</br>Caso as apostas se igualem na mesa os jogadores restantes mostram suas [mãos](lexicos10xf6da0.md#id=12686) e a melhor [mão](lexicos10xf6da0.md#id=12686) vence o jogo e o jogador ganha o [pote](lexicos10xf6da0.md#id=12678).   |


# rodada
### C3096 {#id=3096}

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    rodada   |
|  **Objetivo** |    Juntar apostas no [pote](lexicos10xf6da0.md#id=12678) e entregar ao jogador vencedor.   |
|  **Contexto** |    Inicio do jogo ou fim de outra rodada   |
|  **Atores**   |    [dealer](lexicos10xf6da0.md#id=12688)   |
|  **Recursos** |    Jogadores, baralho, mesa.   |
|  **Excecão**  |    Na mesa possuem menos que 2 jogadores apenas.   |
|  **Episódio** |    [dealer](lexicos10xf6da0.md#id=12688) embaralha as cartas.</br>[dealer](lexicos10xf6da0.md#id=12688) dá inicio a rodada com o  [pré-flop](cenarios10xf6da0.md#id=3091)   |


# turn
### C3093 {#id=3093}

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    turn   |
|  **Objetivo** |    Acumular apostas no [pote](lexicos10xf6da0.md#id=12678) com 6 cartas possíveis para a [mão](lexicos10xf6da0.md#id=12686) de cada jogador   |
|  **Contexto** |    fim do  [flop](cenarios10xf6da0.md#id=3092)   |
|  **Atores**   |    [dealer](lexicos10xf6da0.md#id=12688)   |
|  **Recursos** |    Jogadores, [pote](lexicos10xf6da0.md#id=12678), baralho, mesa.   |
|  **Excecão**  |    Jogadores deram [fold](lexicos10xf6da0.md#id=12677), restando apenas 1 jogador no  [flop](cenarios10xf6da0.md#id=3092)   |
|  **Episódio** |    [dealer](lexicos10xf6da0.md#id=12688) vira mais 1 cartas na mesa, visível para todos os jogadores.</br>Jogador a esquerda do [jogador com o botão](lexicos10xf6da0.md#id=12687) inicia as apostas ou realiza o [check](lexicos10xf6da0.md#id=12679).</br>Outros jogadores fazem o mesmo terminando no [jogador com o botão](lexicos10xf6da0.md#id=12687).</br>Caso os jogadores derem [fold](lexicos10xf6da0.md#id=12677) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos10xf6da0.md#id=12678).</br>Caso as apostas se igualem o [dealer](lexicos10xf6da0.md#id=12688) junta todas as fichas e coloca no [pote](lexicos10xf6da0.md#id=12678).</br>[dealer](lexicos10xf6da0.md#id=12688) realiza o  [river](cenarios10xf6da0.md#id=3094).   |


