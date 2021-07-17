Teoria geral de funções
O que é uma função?

O conceito de função é um dos mais importantes em toda a matemática. O conceito básico é o seguinte: toda vez que temos dois conjuntos e algum tipo de associação entre eles, que faça corresponder a todo elemento do primeiro conjunto um único elemento do segundo, ocorre uma função.

O uso de funções pode ser encontrado em diversos assuntos. Por exemplo, na tabela de preços de uma loja, a cada produto corresponde um determinado preço. Outro exemplo seria o preço a ser pago numa conta de luz, que depende da quantidade de energia consumida. Observe, por exemplo, o diagrama das relações abaixo:


A relação acima não é uma função, pois existe o elemento 1 no conjunto A, que não está associado a nenhum elemento do conjunto B. Vamos ver outro caso:


A relação acima também não é uma função, pois existe o elemento 4 no conjunto A, que está associado a mais de um elemento do conjunto B. Agora preste atenção no próximo exemplo:



A relação acima é uma função, pois todo elemento do conjunto A está associado a somente um elemento do conjunto B.

De um modo geral, dados dois conjuntos A e B, e uma relação entre eles, dizemos que essa relação é uma função de A em B se e somente se, para todo x  A existe um único y  B de modo que x se relacione com y.    

Domínio e imagem de uma função

O domínio de uma função de A em B é sempre o próprio conjunto de partida, ou seja, D=A. Se um elemento x  A estiver associado a um elemento y  B, dizemos que y é a imagem de x (indica-se y=f(x) e lê-se “y é igual a f de x”).

Observe o domínio e a imagem na função abaixo.



Outro exemplo: se f é uma função de IN em IN (isto significa que o domínio e o contradomínio são os números naturais) definida por y=x+2, então temos que:

A imagem de 1 através de f é 3, ou seja, f(1)=1+2=3;
A imagem de 2 através de f é 4, ou seja, f(2)=2+2=4;
De modo geral, a imagem de x através de f é x+2, ou seja: f(x)=x+2.

Em uma função f de A em B, os elementos de B que são imagens dos elementos de A através da aplicação de f formam o conjunto imagem de f. Segundo o conceito de função, existem duas condições para que uma relação f seja uma função:

1ª) O domínio deve sempre coincidir com o conjunto de partida, ou seja, todo elemento de A é ponto de partida de flecha. Se tivermos um elemento de A do qual não parta flecha, a relação não é função.2ª) De cada elemento de A deve partir uma única flecha. Se de um elemento de A partir mais de uma flecha, a relação não é função.

Observações:

Como x e y têm seus valores variando nos conjuntos A e B, recebem o nome de variáveis.
A variável x é chamada variável independente e a variável y, variável dependente, pois para obter o valor de y dependemos de um valor de x.
Uma função f fica definida quando são dados seu domínio (conjunto A), seu contradomínio (conjunto B) e a lei de associação y=f(x).
Obtenção do domínio de uma função

O domínio é o subconjunto de IR no qual todas as operações indicadas em y=f(x) são possíveis. Vamos ver alguns exemplos:



Agora o denominador: como 3-x está dentro da raiz, devemos ter 3-x0, mas além disso ele também está no denominador, portanto devemos ter 3-x0. Juntando as duas condições devemos ter: 3-x > 0, ou seja, x < 3 (condição 2). Resolvendo o sistema formado pelas condições 1 e 2 temos:

Devemos considerar o intervalo que satisfaz as duas condições ao mesmo tempo. Portanto, D={x  IR | 2  x < 3}.

Construção do gráfico cartesiano de uma função

Para construir o gráfico de uma função f, basta atribuir valores do domínio à variável x e, usando a sentença matemática que define a função, calcular os correspondentes valores da variável y.

Vamos construir o gráfico da função definida por y=x/2. Escolhemos alguns valores para o domínio, como por exemplo D={2,4,6,8}. Agora calculamos os respectivos valores de y. Assim temos:

x=2  y=2/2 = 1
x=4  y=4/2 = 2
x=6  y=6/2 = 3
x=8  y=8/2 = 4

Então, montamos a seguinte tabela:



Identificamos os pontos encontrados no plano cartesiano:



O gráfico da função será uma reta que passará pelos quatro pontos encontrados. Basta traçar a reta, e o gráfico estará construído.



Obs: para desenhar o gráfico de uma reta são necessários apenas dois pontos. No exemplo acima escolhemos 4 pontos, mas bastaria escolher dois elementos do domínio, encontrar suas imagens, e logo após traçar a reta que passa por esses 2 pontos.

Raízes de uma função

Dada uma função y=f(x), os valores de x para os quais f(x)=0 são chamados raízes da função. No gráfico cartesiano, as raízes são abscissas dos pontos onde o gráfico corta o eixo horizontal. Observe o gráfico abaixo:



Neste gráfico, temos:

f(x1)=0

f(x2)=0

f(x3)=0

Portanto x1, x2 e x3 são raízes da função.

Propriedades de uma função

Estas são algumas propriedades que caracterizam uma função f:AB.

Função sobrejetora

Dizemos que uma função é sobrejetora se, e somente se, o seu conjunto imagem for igual ao contradomínio, isto é, se Im=B. Em outras palavras, não pode sobrar elementos no conjunto B sem receber flechas. Exemplo:



Função injetora

A função é injetora se elementos distintos do domínio tiverem imagens distintas, ou seja, dois elementos não podem ter a mesma imagem. Portanto, não pode haver nenhum elemento no conjunto B que receba duas flechas. Exemplo:



Por exemplo, a função f:IRIR definida por f(x)=3x é injetora, pois se x1x2 então 3x13x2, portanto f(x1)f(x2).

Função bijetora

Uma função é bijetora quando ela é sobrejetora e injetora ao mesmo tempo. Por exemplo, a função f: IRIR definida por y=3x é injetora, como vimos no exemplo anterior. Ela também é sobrejetora, pois Im=B=IR. Logo, esta função é bijetora.

Já a função f: ININ definida por y=x+5 não é sobrejetora, pois Im={5,6,7,8,...} e o contradomínio CD=IN, mas é injetora, já que valores diferentes de x têm imagens distintas. Então essa função não é bijetora.

Resumindo, observe os diagramas abaixo:



Essa função é sobrejetora, pois não sobra elemento em B.
Essa função não é injetora, pois existem dois elementos com mesma imagem.
Essa função não é bijetora, pois não é injetora.


Essa função é injetora, pois elementos de B são “flechados” só uma vez.
Essa função não é sobrejetora, pois existem elementos sobrando em B.
Essa função não é bijetora, pois não é sobrejetora.


função é injetora, pois elementos de B são “flechados” só uma vez.
Essa função é sobrejetora, pois não existem elementos sobrando em B.
A função é bijetora, pois é injetora e sobrejetora.


Função par e função ímpar

Dada uma função f: AB, dizemos que f é par se, e somente se, f(x)=f(-x) para todo x  A. Ou seja: os valores simétricos devem possuir a mesma imagem. O diagrama a seguir mostra um exemplo de função par:



Por exemplo, a função f: IRIR definida por f(x)=x2 é uma função par, pois f(x)=x2=(-x)2=f(-x). Podemos notar a paridade dessa função observando o seu gráfico:



Notamos no gráfico que existe uma simetria em relação ao eixo vertical. Elementos simétricos têm a mesma imagem. Os elementos 2 e –2, por exemplo, são simétricos e possuem a imagem 4.

Por outro lado, dada uma função f: AB, dizemos que f é ímpar se, e somente se, f(-x)=-f(x) para todo x  A. Ou seja: valores simétricos possuem imagens simétricas. O diagrama a seguir mostra um exemplo de função ímpar:



Por exemplo, a função f: IRIR definida por f(x)=x3 é uma função ímpar, pois f(-x)=(-x)3=-x3=-f(x). Podemos notar que a função é ímpar observando o seu gráfico:



Notamos no gráfico que existe uma simetria em relação a origem 0. Elementos simétricos têm imagens simétricas. Os elementos 1 e –1, por exemplo, são simétricos e possuem imagens 1 e –1 (que também são simétricas).

Obs: Uma função que não é par nem ímpar é chamada função sem paridade.

Exercício resolvido:

Classifique as funções abaixo em pares, ímpares ou sem paridade:

a) f(x)=2x
f(-x)= 2(-x) = -2x  f(-x) = -f(x), portanto f é ímpar.

b) f(x)=x2-1
f(-x)= (-x)2-1 = x2-1  f(x)=f(-x), portanto f é par.

c) f(x)=x2-5x+6
f(-x)= (-x)2-5(-x)+6 = x2+5x+6
Como f(x)f(-x), então f não é par.
Temos também que –f(x)f(-x), logo f não é ímpar.
Por não ser par nem ímpar, concluímos que f é função sem paridade.

Função crescente e função decrescente

Dada uma função f: AB, dizemos que f é crescente em algum conjunto A’A, se, e somente se, para quaisquer x1  A’ e x2  A’, com x12, tivermos f(x1)2).

Por exemplo, a função f: IRIR definida por f(x)=x+1 é crescente em IR, pois:
x12 => x1+12+1 => f(x1)2)

Ou seja: quando os valores do domínio crescem, suas imagens também crescem.

Por outro lado, dada uma função f: AB, dizemos que f é decrescente em algum conjunto A’  A, se, e somente se, para quaisquer x1  A’ e x2  A’, com x12, tivermos f(x1)>f(x2).

Por exemplo, a função f: IRIR definida por f(x)=-x+1 é decrescente em IR, pois:
x12 => -x1>-x2 => -x1+1>-x2+1 => f(x1)>f(x2).

Ou seja: quando os valores do domínio crescem, suas correspondentes imagens decrescem. Exemplos:


Este é um exemplo de função crescente. Podemos notar no gráfico que à medida que os valores de x vão aumentando, suas imagens também vão aumentando.


Este é um exemplo de função decrescente. Podemos notar no gráfico que à medida que os valores de x vão aumentando, suas imagens vão diminuindo.



Fontes:

Só Matemática - O que é uma função?
Só Matemática - Domínio e imagem de uma função
Só Matemática - Obtenção do domínio de uma função
Só Matemática - Construção do gráfico cartesiano de uma função
Só Matemática - Raízes de uma função
Só Matemática - Propriedades de uma função
Só Matemática - Função par e função ímpar
Só Matemática - Função crescente e função decrescente

Conteúdo relacionado
(Prof. Ferretto Matemática):
Funções: Noções Básicas (Aula 1 de 15)
https://www.youtube.com/watch?v=SPZqQ5qn3P0&t=1s
Funções: Domínio, Contradominío e Conjunto de Imagem (Aula 2 de 15):
https://www.youtube.com/watch?v=G3zjNRYbDv8
Funções: Estudo do Domínio das Funções Reais (Aula 3 de 15):
https://www.youtube.com/watch?v=Y1urlgE0lBU
Funções: Noções Básicas de Plano Cartesiano (Aula 4 de 15):
https://www.youtube.com/watch?v=iC4q1AGeN5A
Funções: Construção de Gráficos (Aula 5 de 15):
https://www.youtube.com/watch?v=K7wtLRXGLJw&t=1s
Funções: Domínio e Imagem Através do Gráfico (Aula 6 de 15):
https://www.youtube.com/watch?v=w13aeOGO3ZI
Funções: Reconhcendo uma Função (Aula 7 de 15):
https://www.youtube.com/watch?v=xsIMsYRl46M
Funções: Analisando o Gráfico de Funções (Aula 8 de 15):
https://www.youtube.com/watch?v=5aLsdGSxCM4&t=1s
Questões Comentadas: Análise de Gráficos (Aula 9 de 15):
https://www.youtube.com/watch?v=8sXnloWAU8s&t=1s
Funções:Função Par e Função ímpar (Aula 10 de 15):
https://www.youtube.com/watch?v=HYvlmUiRpGc
Funções: Função Injetora (Função injetiva)(Aula 11 de 15):
https://www.youtube.com/watch?v=OMvGmAB96do
Funções: Função Sobrejetora(Função Sobrejetiva)(Aula 12 de 15):
https://www.youtube.com/watch?v=057CkKna7kM&t=1s
Funções: Função Bijetora(Funlção Bijetiva)(Aula 13 de 15):
https://www.youtube.com/watch?v=B8TtvV_vKQc&t=1s
