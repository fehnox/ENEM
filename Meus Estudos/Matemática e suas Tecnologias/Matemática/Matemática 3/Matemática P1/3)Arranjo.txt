Arranjo

**1. Tipos de Combinatória**

O princípio fundamental da contagem pode ser usado em grande parte dos problemas relacionados com contagem. Entretanto, em algumas situações seu uso torna a resolução muito trabalhosa.

Desta maneira, usamos algumas técnicas para resolver problemas com determinadas características. Basicamente há três tipos de agrupamentos: arranjos, combinações e permutações.

Antes de conhecermos melhor esses procedimentos de cálculo, precisamos definir uma ferramenta muito utilizada em problemas de contagem, que é o fatorial.

O fatorial de um número natural é definido como o produto deste número por todos os seus antecessores. Utilizamos o símbolo **!** para indicar o fatorial de um número.

Define-se ainda que o fatorial de zero é igual a 1.

**Exemplo**

O! = 1
1! = 1
3! = 3.2.1 = 6
7! = 7.6.5.4.3.2.1 = 5 040
10! = 10.9.8.7.6.5.4.3.2.1 = 3 628 800

Note que o valor do fatorial cresce rapidamente, conforme cresce o número. Então, frequentemente usamos simplificações para efetuar os cálculos de análise combinatória.

**2. Arranjos**

Nos **arranjos**, os agrupamentos dos elementos dependem da ordem e da natureza dos mesmos.

O arranjo pode ser de dois tipos:

- Arranjo Simples
- Arranjo com repetição

**Arranjo Simples**

Utilizamos o **arranjo simples** para obter a quantidade de agrupamentos possíveis de serem realizados com os elementos de um conjunto finito. No arranjo os elementos trocam de posição, ou seja, ordem. Com isso os agrupamentos tornam-se distintos, por possuírem seus elementos organizados em uma ordem diferente. Veja a seguir um exemplo de arranjo simples.

**Exemplo:** Mostre os agrupamentos possíveis de serem realizados com o conjunto A ={5,6,7,8}; cada agrupamento deve possuir 3 elementos distintos.

**Resposta:**

(5,6,7) (5,6,8) (5,7,8) (6,7,8)

(5,7,6) (5,8,6) (5,8,7) (6,8,7)

(6,5,7) (6,5,8) (7,5,8) (7,6,8)

(6,7,5) (6,8,5) (7,8,5) (7,8,6)

(7,6,5) (8,5,6) (8,5,7) (8,7,6)

(7,6,5) (8,6,5) (8,7,5) (8,6,7)

Observe que as sequências formadas com 3 elementos são diferentes entre si, em alguns casos o conjunto possui os mesmo termos que outro conjunto, o que muda é a posição dos elementos. Como é o caso de (5,6,7) e (5,7,6); observe que os elementos 6 e 7 trocaram de posição, as sequências obtidos com três elementos referentes ao conjunto A ={5,6,7,8}; são chamadas de arranjo simples.

Do exemplo acima obtemos que de um conjunto com 4 elementos distintos, podemos obter 24 arranjos simples. Podendo ser representar da seguinte forma:

A4,3=24

Para encontramos a quantidade de arranjos possíveis sem precisarmos expressas cada arranjo individualmente, podemos utilizar o Princípio Fundamental da Contagem.

Definição: Dado um com A = {a1, a2, a3, ..., an} com *n* elementos distintos, chamaremos de arranjo simples toda a sequência formada por uma quantidade delimitada de elementos, sendo todos esses elementos pertencentes ao conjunto A.

**Formula Geral para calcular o Arranjo Simples**

![img](https://static.planejativo.com/uploads/novas/dae60e63473a2ccdef95b58ddafa88e8.png)

- n = Quantidade total de elementos no conjunto.
- P =Quantidade de elementos por arranjo

**Exemplos:**

Dado o conjunto B = {d,e,f,g}, responda:

**a) Quantos são os arranjos simples dos elementos de B tomados de 2 a 2?**

Para calcular a quantidade de arranjos, basta aplicar a fórmula:

An,p=n!/(n−p)!

Nessa questão temos que:

n = 4 (Quantidade total de elementos do conjunto B)

p = 2 (Quantidade de elementos por arranjo)

Substitua na equação *n* por 4 e *p* por 2

A4,2=4!/(4−2)!

A4,2=4!/2!

A4,2=4⋅3⋅2/!2!

A4,2=4⋅3

A4,2=12

Tomando os elementos do conjunto B de 2 a 2, será possível formar 12 arranjos.

**b) Quantos são os arranjos simples dos elementos de B tomados de 3 a 3?**

Aplicaremos a fórmula para arranjo simples:

An,p=n!/(n−p)!

Nessa questão temos que:

n = 4 (Quantidade total de elementos do conjunto B)

p = 3 (Quantidade de elementos por arranjo)

Substitua na equação *n* por 4 e *p* por 3

A4,3=4!/(4−3)!

A4,3=4!/1!

A4,3=4⋅3⋅2⋅1/!1

A4,3=4⋅3⋅2

A4,3=24

Tomando os elementos do conjunto B de 3 a 3, será possível formar 24 arranjos.

**Arranjo com repetição**

Os elementos que compõem o conjunto podem aparecer repetidos em um agrupamento, ou seja, ocorre a repetição de um mesmo elemento em um agrupamento.

**A fórmula geral para o arranjo com repetição é representada por:**

![img](https://static.planejativo.com/uploads/novas/f47d7dce8963f75b35b0b466210cc0b6.png)

- n = Número de elementos do conjunto.
- p = Quantidade de elementos por agrupamento.

Exemplo: Seja P um conjunto com elementos: P = {A,B,C,D}, tomando os agrupamentos de dois em dois, considerando o arranjo com repetição quantos agrupamentos podemos obter em relação ao conjunto P.

- P = {A, B, C, D}
- n = 4
- p = 2

A(n,p)=np



A(4,2)=42=16

**Representação por extenso dos agrupamentos do arranjo com repetição:**

A= {AA, AB, AC, AD, BB, BA, BC, BD, CC, CA, CB, CD, DD, DA, DB, DC}

Observe que os agrupamentos com repetição de elementos do conjunto P são: AA, BB, CC e DD. A existência desses elementos referente ao agrupamento faz com que o arranjo seja do tipo com repetição.

**Fontes:**

[Info Escola - Arranjo com repetição](https://www.infoescola.com/matematica/arranjo-com-repeticao/)
[Info Escola - Arranjo simples](https://www.infoescola.com/combinatoria/arranjo-simples/)
[Toda Matéria - Análise Combinatória](https://www.todamateria.com.br/analise-combinatoria/)



Vídeos Relacionados:

# Arranjo - Análise Combinatória #09 - Professor Rafa Jesus

https://www.youtube.com/watch?v=UaTPoG0WDEM