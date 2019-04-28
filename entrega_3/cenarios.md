# Flop

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    flop   |
|  **Objetivo** |    Acumular apostas no [pote](lexicos.md#Pote) com 5 cartas possíveis para a [mão](lexicos.md#Mão) de cada jogador   |
|  **Contexto** |    Fim do PRÉ-FLOP   |
|  **Atores**   |    [dealer](lexicos.md#Dealer)   |
|  **Recursos** |    Jogadores, [pote](lexicos.md#Pote), baralho, mesa.   |
|  **Excecão**  |    Jogadores deram [fold](lexicos.md#Fold), restando apenas 1 jogador no PRÉ-FLOP   |
|  **Episódio** |    [dealer](lexicos.md#Dealer) vira 3 cartas na mesa, visíveis para todos os jogadores.</br>Jogador a esquerda do [jogador com o botão](lexicos.md#Jogador-está-com-o-botão) inicia as apostas ou realiza o [check](lexicos.md#Check).</br>Outros jogadores fazem o mesmo terminando no [jogador com o botão](lexicos.md#Jogador-está-com-o-botão).</br>Caso os jogadores derem [fold](lexicos.md#Fold) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos.md#Pote).</br>Caso as apostas se igualem o [dealer](lexicos.md#Dealer) junta todas as fichas e coloca no [pote](lexicos.md#Pote).</br>[dealer](lexicos.md#Dealer) realiza o  [TURN](#Turn).   |


# Pré-flop

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    pré-flop   |
|  **Objetivo** |    Acumular apostas no [pote](lexicos.md#Pote) sem cartas na mesa   |
|  **Contexto** |    Inicio da  [RODADA](#Rodada).   |
|  **Atores**   |    [dealer](lexicos.md#Dealer)   |
|  **Recursos** |    Jogadores, baralho, mesa.   |
|  **Excecão**  |    Na mesa possuem menos que 2 jogadores apenas.   |
|  **Episódio** |    Jogador uma posição a esquerda do [jogador com o botão](lexicos.md#Jogador-está-com-o-botão) aposta o [small blind](#Small-blind).</br>Jogador duas posições a esquerda do [jogador com o botão](lexicos.md#Jogador-está-com-o-botão) aposta o [big blind](lexicos.md#Big-Blind).</br>Caso os jogadores derem [fold](lexicos.md#Fold) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos.md#Pote).</br>Caso as apostas se igualem o [dealer](lexicos.md#Dealer) reúne as apostas no [pote](lexicos.md#Pote) e realiza o  [FLOP](#Flop).   |


# River

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    river   |
|  **Objetivo** |    Declarar o vencedor com [mão](lexicos.md#Mão) mais forte.   |
|  **Contexto** |    Fim do  [TURN](#Turn)   |
|  **Atores**   |    [dealer](lexicos.md#Dealer)   |
|  **Recursos** |    Jogadores, [mão](lexicos.md#Mão) dos jogadores,[pote](lexicos.md#Pote), baralho, mesa.   |
|  **Excecão**  |    Jogadores deram [fold](lexicos.md#Fold), restando apenas 1 jogador no  [TURN](#Turn).   |
|  **Episódio** |    [dealer](lexicos.md#Dealer) vira mais 1 cartas na mesa, visível para todos os jogadores.</br>Jogador a esquerda do [jogador com o botão](lexicos.md#Jogador-está-com-o-botão) inicia as apostas ou realiza o [check](lexicos.md#Check).</br>Outros jogadores fazem o mesmo terminando no [jogador com o botão](lexicos.md#Jogador-está-com-o-botão).</br>Caso os jogadores derem [fold](lexicos.md#Fold) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos.md#Pote).</br>Caso as apostas se igualem na mesa os jogadores restantes mostram suas [mãos](lexicos.md#Mão) e a melhor [mão](lexicos.md#Mão) vence o jogo e o jogador ganha o [pote](lexicos.md#Pote).   |


# Rodada

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    rodada   |
|  **Objetivo** |    Juntar apostas no [pote](lexicos.md#Pote) e entregar ao jogador vencedor.   |
|  **Contexto** |    Inicio do jogo ou fim de outra rodada   |
|  **Atores**   |    [dealer](lexicos.md#Dealer)   |
|  **Recursos** |    Jogadores, baralho, mesa.   |
|  **Excecão**  |    Na mesa possuem menos que 2 jogadores apenas.   |
|  **Episódio** |    [dealer](lexicos.md#Dealer) embaralha as cartas.</br>[dealer](lexicos.md#Dealer) dá inicio a rodada com o  [PRÉ-FLOP](#Pré-flop)   |


# Turn

|  Informações  | Cenário |
|:-------------:|:-------:|
|  **Título**   |    turn   |
|  **Objetivo** |    Acumular apostas no [pote](lexicos.md#Pote) com 6 cartas possíveis para a [mão](lexicos.md#Mão) de cada jogador   |
|  **Contexto** |    fim do  [FLOP](#Flop)   |
|  **Atores**   |    [dealer](lexicos.md#Dealer)   |
|  **Recursos** |    Jogadores, [pote](lexicos.md#Pote), baralho, mesa.   |
|  **Excecão**  |    Jogadores deram [fold](lexicos.md#Fold), restando apenas 1 jogador no  [FLOP](#Flop)   |
|  **Episódio** |    [dealer](lexicos.md#Dealer) vira mais 1 cartas na mesa, visível para todos os jogadores.</br>Jogador a esquerda do [jogador com o botão](lexicos.md#Jogador-está-com-o-botão) inicia as apostas ou realiza o [check](lexicos.md#Check).</br>Outros jogadores fazem o mesmo terminando no [jogador com o botão](lexicos.md#Jogador-está-com-o-botão).</br>Caso os jogadores derem [fold](lexicos.md#Fold) restando apenas 1 jogador ele é o vencedor ganhando o [pote](lexicos.md#Pote).</br>Caso as apostas se igualem o [dealer](lexicos.md#Dealer) junta todas as fichas e coloca no [pote](lexicos.md#Pote).</br>[dealer](lexicos.md#Dealer) realiza o  [RIVER](#River).   |


