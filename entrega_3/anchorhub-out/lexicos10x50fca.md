# big blind
### L12681

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    big blind   |
|  **Noção**      |    Quantia apostada obrigatoriamente pelo jogador 2 posições a esquerda do [dealer](lexicos10x50fca.md#l12688) antes de serem distribuídas quaisquer cartas. O valor da aposta varia dependendo do jogo.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogadores apostam obrigatoriamente big blind e [small blind](lexicos10x50fca.md#l12682) para o jogo sempre possuir um [pote](lexicos10x50fca.md#l12678). Caso contrário seria possível tem vários jogos com [pote](lexicos10x50fca.md#l12678) 0.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) | [small blind](lexicos10x50fca.md#l12682) |



# blefar
### L12674

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    blefar   |
|  **Noção**      |    Acontece quando o jogador tem uma pior [mão](lexicos10x50fca.md#l12686) que o adversário</br>Jogador faz uma aposta como se tivesse uma boa [mão](lexicos10x50fca.md#l12686)</br>Adversário da [fold](lexicos10x50fca.md#l12677)   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Caso o adversário der [fold](lexicos10x50fca.md#l12677) o Jogador ganha o [pote](lexicos10x50fca.md#l12678)</br>Caso o adversário der [call](lexicos10x50fca.md#l12676) o Jogador irá perder dinheiro pois ele possui uma [mão](lexicos10x50fca.md#l12686) pior   |
|  **Sinônimos**  |    blefe .   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# botão
### L12689

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    botão   |
|  **Noção**      |    Botão que roda entre os jogadores no sentido horário ao fim de cada rodada.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    O jogador que recebe com o botão se torna o [jogador com o botão](lexicos10x50fca.md#l12687)   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) | [jogador está com o botão](lexicos10x50fca.md#l12687) |
| [flop](cenarios10x50fca.md#c3092) |   |
| [turn](cenarios10x50fca.md#c3093) |   |
| [river](cenarios10x50fca.md#c3094) |   |



# call
### L12676

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    call   |
|  **Noção**      |    Adversário faz uma aposta.</br>Jogador faz uma aposta igualando a aposta adversária.   |
|**Classificação**|    verbo   |
|  **Impacto**    |    O jogador só continua no jogo se der call em todas as apostas.</br>Jogador que não da call possuindo fichas é obrigado a [dar fold](lexicos10x50fca.md#l12677).   |
|  **Sinônimos**  |    deu call, dar call .   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
|   | [blefar](lexicos10x50fca.md#l12674) |
|   | [semi-blefar](lexicos10x50fca.md#l12675) |
|   | [check](lexicos10x50fca.md#l12679) |
|   | [check-raise](lexicos10x50fca.md#l12680) |
|   | [jogador está com o botão](lexicos10x50fca.md#l12687) |



# check
### L12679

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    check   |
|  **Noção**      |    Em uma rodada de apostas ninguém apostou nada.</br>A maior aposta do jogo é 0, portanto o jogador não precisa apostar para continuar no jogo.</br>Se o jogador não apostar nada ele realiza um check   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Jogador não precisa wzzxkkxy0pois não possui aposta na mesa para isso, portanto o jogador pode simplesmente dar check e continuar o jogo.   |
|  **Sinônimos**  |    dar ceck, deu check.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [flop](cenarios10x50fca.md#c3092) | [check-raise](lexicos10x50fca.md#l12680) |
| [turn](cenarios10x50fca.md#c3093) |   |
| [river](cenarios10x50fca.md#c3094) |   |



# check-raise
### L12680

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    check-raise   |
|  **Noção**      |    Jogador escolheu dar [check](lexicos10x50fca.md#l12679) como se não tivesse um bom jogo.</br>A rodada de apostas continua e algum adversário aposta.</br>Ao invés de [dar fold](lexicos10x50fca.md#l12677) ou [call](lexicos10x50fca.md#l12676) o jogador da raise forçando o adversário a apostar mais.   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Jogador que da [check](lexicos10x50fca.md#l12679)-raise coloca o apostador em uma situação delicada, pois se ele der [fold](lexicos10x50fca.md#l12677), ele perde as fichas que já apostou, se ele der [call](lexicos10x50fca.md#l12676), ele vai apostar mais do que planejado, que geralmente é o que o jogador que [deu check](lexicos10x50fca.md#l12679)-raise quer.   |
|  **Sinônimos**  |    dar check-raise, deu check-raise.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# dealer
### L12688

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    dealer   |
|  **Noção**      |    Pessoa que controla o baralho, entrega as cartas e controla o [pote](lexicos10x50fca.md#l12678).   |
|**Classificação**|    sujeito   |
|  **Impacto**    |    Ele é responsável por dirigir todo o jogo.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) | [big blind](lexicos10x50fca.md#l12681) |
| [flop](cenarios10x50fca.md#c3092) | [small blind](lexicos10x50fca.md#l12682) |
| [turn](cenarios10x50fca.md#c3093) |   |
| [river](cenarios10x50fca.md#c3094) |   |
| [rodada](cenarios10x50fca.md#c3096) |   |



# flush
### L12685

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    flush   |
|  **Noção**      |    [mão](lexicos10x50fca.md#l12686) com 5 cartas do mesmo nipe.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogador que possui um flush tem boas chances de vitória dependendo das cartas da mesa.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
|   | [flush-draw](lexicos10x50fca.md#l12684) |



# flush-draw
### L12684

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    flush-draw   |
|  **Noção**      |    Jogador tem 2 cartas do mesmo nipe na [mão](lexicos10x50fca.md#l12686).   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogador possui grandes chances de formar um [flush](lexicos10x50fca.md#l12685) com as cartas da mesa.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# fold
### L12677

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    fold   |
|  **Noção**      |    Adversário realiza uma aposta.</br>Jogador ainda possui fichas.</br>Jogador não iguala sua aposta a aposta adversária.</br>Jogador é obrigado a desistir do jogo.   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Quando um jogador da fold ele perde a chance de ganhar o [pote](lexicos10x50fca.md#l12678), e perde todas as apostas realizadas na rodada.   |
|  **Sinônimos**  |    dar fold, deu fold.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) | [call](lexicos10x50fca.md#l12676) |
| [flop](cenarios10x50fca.md#c3092) | [blefar](lexicos10x50fca.md#l12674) |
| [turn](cenarios10x50fca.md#c3093) | [semi-blefar](lexicos10x50fca.md#l12675) |
| [river](cenarios10x50fca.md#c3094) | [check-raise](lexicos10x50fca.md#l12680) |
|   | [jogador está com o botão](lexicos10x50fca.md#l12687) |



# jogador está com o botão
### L12687

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    jogador está com o botão   |
|  **Noção**      |    O [botão](lexicos10x50fca.md#l12689) se encontra com o jogador.   |
|**Classificação**|    estado   |
|  **Impacto**    |    O jogador com o [botão](lexicos10x50fca.md#l12689) tem a vantagem de ser o último a apostar podendo ter a chance de [dar fold](lexicos10x50fca.md#l12677) em uma aposta muito alta ou wzzxkkxy0em uma aposta acessível.   |
|  **Sinônimos**  |    jogador com o botão.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) |   |
| [flop](cenarios10x50fca.md#c3092) |   |
| [turn](cenarios10x50fca.md#c3093) |   |
| [river](cenarios10x50fca.md#c3094) |   |



# mão
### L12686

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    mão   |
|  **Noção**      |    Jogo formado por 5 de 7 cartas possíveis, sendo que 2 estão na sua mão e até 5 estão na mesa.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Ao final do river jogador com a melhor mão vence o jogo.   |
|  **Sinônimos**  |    mão de poker, mãos.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [flop](cenarios10x50fca.md#c3092) | [blefar](lexicos10x50fca.md#l12674) |
| [turn](cenarios10x50fca.md#c3093) | [semi-blefar](lexicos10x50fca.md#l12675) |
| [river](cenarios10x50fca.md#c3094) | [outs](lexicos10x50fca.md#l12683) |
|   | [flush-draw](lexicos10x50fca.md#l12684) |
|   | [flush](lexicos10x50fca.md#l12685) |



# outs
### L12683

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    outs   |
|  **Noção**      |    Jogador possui a chance de fazer um bom jogo com as cartas de sua [mão](lexicos10x50fca.md#l12686), caso o flop, turn ou river virem cartas específicas.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogador que possui outs tem grandes chances de virar o jogo no flop, turn ou river.   |
|  **Sinônimos**  |    out.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
|   | [semi-blefar](lexicos10x50fca.md#l12675) |



# pote
### L12678

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    pote   |
|  **Noção**      |    A rodada se inicia.</br>Jogadores apostam suas fichas.</br>Fichas apostadas ficam separadas e são chamadas de pote.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Ao final da rodada o jogador vencedor ganha o pote   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) | [blefar](lexicos10x50fca.md#l12674) |
| [flop](cenarios10x50fca.md#c3092) | [fold](lexicos10x50fca.md#l12677) |
| [turn](cenarios10x50fca.md#c3093) | [big blind](lexicos10x50fca.md#l12681) |
| [river](cenarios10x50fca.md#c3094) | [small blind](lexicos10x50fca.md#l12682) |
| [rodada](cenarios10x50fca.md#c3096) | [dealer](lexicos10x50fca.md#l12688) |



# semi-blefar
### L12675

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    semi-blefar   |
|  **Noção**      |    Adversário tem um melhor jogo.</br>Jogador faz aposta para o adversário [dar fold](lexicos10x50fca.md#l12677).</br>Mesmo se o adversário der [call](lexicos10x50fca.md#l12676) Jogador possui vários [outs](lexicos10x50fca.md#l12683).   |
|**Classificação**|    verbo   |
|  **Impacto**    |    Caso adversário der [fold](lexicos10x50fca.md#l12677) Jogador ganha com uma [mão](lexicos10x50fca.md#l12686) pior.</br>Caso o adversário der [call](lexicos10x50fca.md#l12676) Jogador ainda tem chance de virar o jogo com algum de seus [outs](lexicos10x50fca.md#l12683).   |
|  **Sinônimos**  |    semi-blefe.   |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| - | - |



# small blind
### L12682

|  Informações    | Símbolo |
|:---------------:|:-------:|
|  **Nome**       |    small blind   |
|  **Noção**      |    Quantia apostada obrigatoriamente pelo jogador 1 posição a esquerda do [dealer](lexicos10x50fca.md#l12688) antes de serem distribuídas quaisquer cartas. O valor da aposta varia dependendo do jogo.   |
|**Classificação**|    objeto   |
|  **Impacto**    |    Jogadores apostam obrigatoriamente [big blind](lexicos10x50fca.md#l12681) e small blind para o jogo sempre possuir um [pote](lexicos10x50fca.md#l12678). Caso contrário seria possível tem vários jogos com [pote](lexicos10x50fca.md#l12678) 0.   |
|  **Sinônimos**  |       |


|  **Cenários** |**Lexicos**|
|:-------------:|:---------:|
| [pré-flop](cenarios10x50fca.md#c3091) | [big blind](lexicos10x50fca.md#l12681) |



