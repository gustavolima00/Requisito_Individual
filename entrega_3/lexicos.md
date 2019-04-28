# Big blind

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    big blind   |
|  **Noção**      |    Quantia apostada obrigatoriamente pelo jogador 2 posições a esquerda do [dealer](#Dealer) antes de serem distribuídas quaisquer cartas. O valor da aposta varia dependendo do jogo.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogadores apostam obrigatoriamente big blind e [small blind](#Small-blind)  para o jogo sempre possuir um [pote](#Pote). Caso contrário seria possível tem vários jogos com [pote](#Pote) 0.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) | [small blind](#Small-blind)  |



# Blefar

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    blefar   |
|  **Noção**      |    Acontece quando o jogador tem uma pior [mão](#Mão) que o adversário</br>Jogador faz uma aposta como se tivesse uma boa [mão](#Mão)</br>Adversário da [fold](#Fold)   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Caso o adversário der [fold](#Fold) o Jogador ganha o [pote](#Pote)</br>Caso o adversário der [call](#Call) o Jogador irá perder dinheiro pois ele possui uma [mão](#Mão) pior   |
|  **Sinônimos**  |    blefe .   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# Botão

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    botão   |
|  **Noção**      |    Botão que roda entre os jogadores no sentido horário ao fim de cada rodada.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    O jogador que recebe com o botão se torna o [jogador com o botão](#Jogador-está-com-o-botão)   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) | [jogador está com o botão](#Jogador-está-com-o-botão) |
| [flop](cenarios.md#Flop) |   |
| [turn](cenarios.md#Turn) |   |
| [river](cenarios.md#River) |   |



# Call

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    call   |
|  **Noção**      |    Adversário faz uma aposta.</br>Jogador faz uma aposta igualando a aposta adversária.   |
|**Classificação**|    verbo   |
|  **Impacto**    |    O jogador só continua no jogo se der call em todas as apostas.</br>Jogador que não da call possuindo fichas é obrigado a [dar fold](#Fold).   |
|  **Sinônimos**  |    deu call, dar call .   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
|   | [blefar](#Blefar) |
|   | [semi-blefar](#Semi-blefar) |
|   | [check](#Check) |
|   | [check-raise](#Check-raise) |
|   | [jogador está com o botão](#Jogador-está-com-o-botão) |



# Check

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    check   |
|  **Noção**      |    Em uma rodada de apostas ninguém apostou nada.</br>A maior aposta do jogo é 0, portanto o jogador não precisa apostar para continuar no jogo.</br>Se o jogador não apostar nada ele realiza um check   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Jogador não precisa wzzxkkxy0pois não possui aposta na mesa para isso, portanto o jogador pode simplesmente dar check e continuar o jogo.   |
|  **Sinônimos**  |    dar ceck, deu check.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [flop](cenarios.md#Flop) | [check-raise](#Check-raise) |
| [turn](cenarios.md#Turn) |   |
| [river](cenarios.md#River) |   |



# Check-raise

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    check-raise   |
|  **Noção**      |    Jogador escolheu dar [check](#Check) como se não tivesse um bom jogo.</br>A rodada de apostas continua e algum adversário aposta.</br>Ao invés de [dar fold](#Fold) ou [call](#Call) o jogador da raise forçando o adversário a apostar mais.   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Jogador que da [check](#Check)-raise coloca o apostador em uma situação delicada, pois se ele der [fold](#Fold), ele perde as fichas que já apostou, se ele der [call](#Call), ele vai apostar mais do que planejado, que geralmente é o que o jogador que [deu check](#Check)-raise quer.   |
|  **Sinônimos**  |    dar check-raise, deu check-raise.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# Dealer

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    dealer   |
|  **Noção**      |    Pessoa que controla o baralho, entrega as cartas e controla o [pote](#Pote).   |
|**Classificação**|    sujeito   |
|  **Impacto**    |    Ele é responsável por dirigir todo o jogo.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) | [big blind](#Big-blind) |
| [flop](cenarios.md#Flop) | [small blind](#Small-blind)  |
| [turn](cenarios.md#Turn) |   |
| [river](cenarios.md#River) |   |
| [rodada](cenarios10x50fca.md#id=3096) |   |



# Flush

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    flush   |
|  **Noção**      |    [mão](#Mão) com 5 cartas do mesmo nipe.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogador que possui um flush tem boas chances de vitória dependendo das cartas da mesa.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
|   | [flush-draw](#Flush-draw) |



# Flush-draw

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    flush-draw   |
|  **Noção**      |    Jogador tem 2 cartas do mesmo nipe na [mão](#Mão).   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogador possui grandes chances de formar um [flush](#Flush) com as cartas da mesa.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# Fold

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    fold   |
|  **Noção**      |    Adversário realiza uma aposta.</br>Jogador ainda possui fichas.</br>Jogador não iguala sua aposta a aposta adversária.</br>Jogador é obrigado a desistir do jogo.   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Quando um jogador da fold ele perde a chance de ganhar o [pote](#Pote), e perde todas as apostas realizadas na rodada.   |
|  **Sinônimos**  |    dar fold, deu fold.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) | [call](#Call) |
| [flop](cenarios.md#Flop) | [blefar](#Blefar) |
| [turn](cenarios.md#Turn) | [semi-blefar](#Semi-blefar) |
| [river](cenarios.md#River) | [check-raise](#Check-raise) |
|   | [jogador está com o botão](#Jogador-está-com-o-botão) |



# Jogador está com o botão

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    jogador está com o botão   |
|  **Noção**      |    O [botão](#Botão) se encontra com o jogador.   |
|**Classificação**|    estado   |
|  **Impacto**    |    O jogador com o [botão](#Botão) tem a vantagem de ser o último a apostar podendo ter a chance de [dar fold](#Fold) em uma aposta muito alta ou wzzxkkxy0em uma aposta acessível.   |
|  **Sinônimos**  |    jogador com o botão.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) |   |
| [flop](cenarios.md#Flop) |   |
| [turn](cenarios.md#Turn) |   |
| [river](cenarios.md#River) |   |



# Mão

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    mão   |
|  **Noção**      |    Jogo formado por 5 de 7 cartas possíveis, sendo que 2 estão na sua mão e até 5 estão na mesa.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Ao final do river jogador com a melhor mão vence o jogo.   |
|  **Sinônimos**  |    mão de poker, mãos.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [flop](cenarios.md#Flop) | [blefar](#Blefar) |
| [turn](cenarios.md#Turn) | [semi-blefar](#Semi-blefar) |
| [river](cenarios.md#River) | [outs](#Outs) |
|   | [flush-draw](#Flush-draw) |
|   | [flush](#Flush) |



# Outs

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    outs   |
|  **Noção**      |    Jogador possui a chance de fazer um bom jogo com as cartas de sua [mão](#Mão), caso o flop, turn ou river virem cartas específicas.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogador que possui outs tem grandes chances de virar o jogo no flop, turn ou river.   |
|  **Sinônimos**  |    out.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
|   | [semi-blefar](#Semi-blefar) |



# Pote

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    pote   |
|  **Noção**      |    A rodada se inicia.</br>Jogadores apostam suas fichas.</br>Fichas apostadas ficam separadas e são chamadas de pote.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Ao final da rodada o jogador vencedor ganha o pote   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) | [blefar](#Blefar) |
| [flop](cenarios.md#Flop) | [fold](#Fold) |
| [turn](cenarios.md#Turn) | [big blind](#Big-blind) |
| [river](cenarios.md#River) | [small blind](#Small-blind)  |
| [rodada](cenarios10x50fca.md#id=3096) | [dealer](#Dealer) |



# Semi-blefar

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    semi-blefar   |
|  **Noção**      |    Adversário tem um melhor jogo.</br>Jogador faz aposta para o adversário [dar fold](#Fold).</br>Mesmo se o adversário der [call](#Call) Jogador possui vários [outs](#Outs).   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Caso adversário der [fold](#Fold) Jogador ganha com uma [mão](#Mão) pior.</br>Caso o adversário der [call](#Call) Jogador ainda tem chance de virar o jogo com algum de seus [outs](#Outs).   |
|  **Sinônimos**  |    semi-blefe.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# Small blind

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    small blind   |
|  **Noção**      |    Quantia apostada obrigatoriamente pelo jogador 1 posição a esquerda do [dealer](#Dealer) antes de serem distribuídas quaisquer cartas. O valor da aposta varia dependendo do jogo.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogadores apostam obrigatoriamente [big blind](#Big-blind) e small blind para o jogo sempre possuir um [pote](#Pote). Caso contrário seria possível tem vários jogos com [pote](#Pote) 0.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios.md#Pré-flop) | [big blind](#Big-blind) |



