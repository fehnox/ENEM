Função composta e Função inversa

**Função inversa**

Consideremos os conjuntos A={0,2,4,6,8} e B={1,3,5,7,9} e a função f:A![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)B definida por y=x+1. A função f está representada no diagrama abaixo:

![img](https://static.planejativo.com/uploads/novas/f49fe690ce9cac61f9289606da29a8f3.jpg)

A função f é bijetora. A cada elemento x de A está associado um único elemento y de B, de modo que y=x+1. Porém, como f é bijetora, a cada elemento y de B está associado um único elemento x de A, de modo que x=y-1; portanto temos uma outra função g:B![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)A, de modo que x=y-1 ou g(y)=y-1. Essa função está representada no diagrama abaixo:

![img](https://static.planejativo.com/uploads/novas/dd251f3eb47cd09809ae7bce145f0162.jpg)

Pelo que acabamos de ver, a função f leva x até y, enquanto a função g leva y até x. A função g:B![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)A recebe o nome de **função inversa** de f e é indicada por f-1.

O domínio de f é o conjunto imagem de g, e o conjunto imagem de f é o domínio de g. Quando queremos, a partir da sentença y=f(x), obter a sentença de f-1(x), devemos realizar os seguintes passos:

1º) Isolamos x na sentença y=f(x)
2º) Pelo fato de ser usual a letra x como símbolo da variável independente, trocamos x por y e y por x.

Por exemplo, para obter a função inversa de f:IR![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)IR definida por y=2x+1, devemos:

1º) isolar x em y=2x+1. Assim y=2x+1 ![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif) y-1=2x ![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif) x=(y-1)/2
2º) trocar x por y e y por x: y=(x-1)/2.

Portanto a função inversa de f é: f-1(x)=(x-1)/2.

Observação: Para que uma função f admita a inversa f-1 é necessário que ela seja bijetora. Se f não for bijetora, ela não possuirá inversa.

Exercício resolvido

![img](https://www.somatematica.com.br/emedio/funcoes/func22.gif)

**Função composta**

Vamos analisar um exemplo para entender o que é uma função composta. Consideremos os conjuntos:

A={-2,-1,0,1,2}
B={-2,1,4,7,10}
C={3,0,15,48,99}

E as funções:
f:A![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)B definida por f(x)=3x+4
g:B![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)C definida por g(y)=y2-1

![img](https://static.planejativo.com/uploads/novas/6930dad5dc5f773123c9b8adf5ff2881.jpg)

Como nos mostra o diagrama acima, para todo x ![img](https://www.somatematica.com.br/emedio/funcoes/pertence.gif) A temos um único y ![img](https://www.somatematica.com.br/emedio/funcoes/pertence.gif) B tal que y=3x+4, e para todo y ![img](https://www.somatematica.com.br/emedio/funcoes/pertence.gif) B existe um único z ![img](https://www.somatematica.com.br/emedio/funcoes/pertence.gif) C tal que z=y2-1. Então, concluímos que existe uma função h de A em C, definida por h(x)=z ou h(x)=9x2+24x+15, pois:
h(x)=z ![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif)  h(x)= y2-1
E sendo y=3x+4, então h(x)=(3x+4)2-1 ![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif) h(x)= 9x2+24x+15.

A função h(x) é chamada função **composta de g com f**. Podemos indicá-la por **g o f** (lemos “g composta com f”) ou **g[f(x)]** (lemos “g de f de x”). Vamos ver alguns exercícios para entender melhor a ideia de função composta.

Exercícios resolvidos

1) Dadas as funções f(x)=x2-1 e g(x)=2x, calcule f[g(x)] e g[f(x)].
Resolução:
f[g(x)] = f(2x) = (2x)2-1 = 4x2-1
g[f(x)] = g(x2-1) = 2(x2-1) = 2x2-2

2) Dadas as funções f(x)=5x e f[g(x)]=3x+2, calcule g(x).
Resolução:
Como f(x)=5x, então f[g(x)]= 5.g(x).
Porém, f[g(x)]=3x+2, logo:
5.g(x)=3x+2, e daí g(x)=(3x+2)/5

3) Dadas as funções f(x)=x2+1 e g(x)=3x-4, determine f[g(3)].
Resolução: g(3)=3.3-4=5 ![img](https://www.somatematica.com.br/emedio/funcoes/seta.gif) f[g(3)]= f(5)= 52+1 = 25+1= 26.

**Fontes:**

[Só Matemática - Função composta](https://www.somatematica.com.br/emedio/funcoes/funcoes9.php)
[Só Matemática - Função inversa](https://www.somatematica.com.br/emedio/funcoes/funcoes10.php)

Vídeos Relacionados(Prof.Ferretto):

Funções: Função Composta (Composição de Funções) 
https://www.youtube.com/watch?v=V9yhPL87lGs

Questões Comentadas: Função Composta
https://www.youtube.com/watch?v=mytzKEjGM_A

Funções: Função Inversa
https://www.youtube.com/watch?v=k-BPycvaZLA

Questões Comentadas: Função Inversa
https://www.youtube.com/watch?v=HXAdRVV_SMc&t=1s
