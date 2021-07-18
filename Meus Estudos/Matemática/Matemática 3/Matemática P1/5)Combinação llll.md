Combinação

**Combinações**

As **combinações** são subconjuntos em que a ordem dos elementos não é importante, entretanto, são caracterizadas pela natureza dos mesmos.

Assim, para calcular uma combinação simples de *n* elementos tomados p a p (p ≤ n), utiliza-se a seguinte expressão:

![img](https://static.planejativo.com/uploads/novas/1535034fab688bbd3f807846ed680af9.png)

**Combinação Simples**

A **combinação simples** pode ser definida como sendo um agrupamento dos elementos de um conjunto em subconjuntos. Na combinação a ordem dos elementos não é considerada na formação dos subconjuntos, ou seja, o subconjunto {A, B} e {B, A} são iguais, devendo ser considerado uma única vez na contagem da quantidade de combinações. A fórmula geral para encontrar as quantidades de combinações simples de um conjunto é representada por:

![img](https://static.planejativo.com/uploads/novas/8eb44a124876e8f44deb1526cb87a4b7.png)



- n = Número de elementos do conjunto.
- P = Quantidade de elementos por subconjunto.

**Exemplo 1:** Utilizando a combinação simples e considerando o conjunto J ={A, B, C, D} encontre quantos subconjuntos e possível formar tomando os elementos de 2 em 2.

- Conjunto: J = {A, B, C, D}
- n = 4
- p = 2

![img](https://static.planejativo.com/uploads/novas/2fc12b5ee628befd4d6c2ae8590c1423.png)

Tomando os elementos do conjunto J ={A, B, C, D} de 2 em 2 é possível formar 6 subconjuntos.

**Representação dos subconjuntos por extenso:**

J = { AB, AC, AD, BC, BD, CD}

Exemplo 2: Seja I um conjunto formado por {a, b, c, d}, tomando os elementos de 3 em 3, encontre quantos combinações simples podemos obter.

- Conjunto: I = {a, b, c, d}
- n = 4
- p = 3

![img](https://static.planejativo.com/uploads/novas/5d6544972568787986a36c41b648fcc9.png)
  ![img](https://static.planejativo.com/uploads/novas/918433013d1be3d9fd9c88859f86b155.png)

Tomando os elementos do conjunto I ={a, b, c, d} de 3 em 3 é possível formar 4 subconjuntos.

Representação dos subconjuntos por extenso:

J = { (abc), (abd), (acd), (bcd) }

**Combinação com Repetição**

Para introduzirmos o conceito de **combinação com repetição**, é importante relembrar a definição formal de combinação simples.

Considere *n* objetos diferentes. Se tratarmos da contagem do número de maneiras de escolher *k* dentre esses *n* objetos sem considerarmos a ordem, então criamos uma combinação destes elementos sem repetição. A fórmula para obter esta combinação é dada por:

![img](https://static.planejativo.com/uploads/novas/cff481d30f5c694c098493b23f813c96.png)

Por exemplo, imagine o seguinte cenário: Estamos organizando um campeonato de xadrez com 12 participantes. De quantas maneiras possíveis podemos criar as duplas para disputar a primeira partida? Este problema pode ser solucionado calculando a combinação de 12 jogadores organizados de 2 em 2. Que nos traz:

![img](https://static.planejativo.com/uploads/novas/1c206a1b474342c9a98a305aa743f765.png)

Temos então 66 formas diferentes de organizar as duplas a partir dos 12 primeiros participantes. Há uma outra notação para a operação de combinação, ou coeficiente binomial, que é dada por:

![img](https://static.planejativo.com/uploads/novas/b1b20ab098a94141e8090669fb87126d.png)

Agora, quando a ordem dos elementos *pode ser repetida*, então tratamos de uma **combinação com repetição**. A fórmula será dada, neste caso, por:

![img](https://static.planejativo.com/uploads/novas/7aa202ba4db77492f9f8940467dc9980.png)
Ou seja:

![img](https://static.planejativo.com/uploads/novas/c8a652360f803384965a7fb8c721aace.png)



Vejamos agora um exemplo aplicado:

**Exemplo 1)** Supondo que você queira comprar um sorvete com 4 bolas em uma sorveteria que possui 3 sabores disponíveis: chocolate, baunilha e morango. De quantos modos diferentes você pode fazer esta compra?

Note que nesta combinação, é possível repetir a ordem de dois ou mais sabores, assim tratando de uma combinação com repetição. Se temos 3 sabores disponíveis e queremos uma combinação para 4 bolas, pela fórmula obtemos:

![img](https://static.planejativo.com/uploads/novas/4b456ab52a520d7d0994dc37692fc573.png)

![img](https://static.planejativo.com/uploads/novas/9cd67597239d9ce73bedb6664d368df8.png)
Logo, temos 15 combinações possíveis para esta compra!

**ENEM 2017)** Um brinquedo infantil caminhão-cegonha é formado por uma carreta e dez carrinhos nela transportados, conforme a figura.





![img](https://static.planejativo.com/uploads/novas/caac003b17e78277cbf1d7b862ec1042.png)



No setor de produção da empresa que fabrica esse brinquedo, é feita a pintura de todos os carrinhos para que o aspecto do brinquedo fique mais atraente. São utilizadas as cores: **amarelo, branco, laranja e verde**, e cada carrinho é **pintado apenas com uma cor**. O caminhão-cegonha **deve haver pelo menos um carrinho de cada uma das quatro cores disponíveis**. Mudança de posição dos carrinhos no caminhão-cegonha **não gera um novo modelo do brinquedo**. Com base nessas informações, quantos são os modelos distintos do brinquedo que essa empresa poderá produzir?

Note as palavras em negrito no texto. Pela interpretação da questão percebe-se que ela se trata de uma combinação com repetição. Então, se temos 4 cores disponíveis e 10 carrinhos a ser colocados no brinquedo a questão pode ser solucionada da seguinte maneira:

Pelo exercício, teremos pelo menos um carrinho de cada cor. Então podemos supor que existe uma quantidade (amarelo), (branco), (laranja) e (verde) e mais um de cada, no mínimo. Então podemos dizer:

- Carrinho amarelo: a+1
- Carrinho branco: b+1
- Carrinho laranja: L+1
- Carrinho verde: v+1

Somando então estas quantidades, sabemos que o total deve ser igual a 10 carrinhos, o que nos leva a:

![img](https://static.planejativo.com/uploads/novas/ffe6dc2576d7719480a0b5fdbc5f1b0f.png)
Isolando as variáveis temos que:

![img](https://static.planejativo.com/uploads/novas/c204f63844b50771a65479b3cd64e172.png)

Ora, perceba que agora temos um cenário onde já sabemos que ao mínimo teremos um carrinho de cada cor, que já ocupa 4 posições no caminhão-cegonha restando apenas 6 posições. Então é necessário pensar que devemos organizar agora 4 carrinhos em 6 posições considerando a repetição. O que nos leva a formula:

![img](https://static.planejativo.com/uploads/novas/4fb82d13c5898af151a1f3e50b6af42d.png)

**Fontes:**

[Info Escola - Combinação com repetição](https://www.infoescola.com/matematica/combinacao-com-repeticao/)
[Info Escola - Combinação simples](https://www.infoescola.com/matematica/combinacao-simples/)
[Toda Matéria - Análise combinatória](https://www.todamateria.com.br/analise-combinatoria/)

##### Conteúdo relacionado

(Equaciona com Paulo Pereira):

# COMBINAÇÃO SIMPLES

https://www.youtube.com/watch?v=fvPIb7Vtez4

# COMBINAÇÃO SIMPLES - EXERCÍCIOS #1

https://www.youtube.com/watch?v=sd9-uIlKA80

