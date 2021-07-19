Leis de Kirchhoff e Ponte de Wheatstone

**Leis de Kirchhoff
**

As **Leis de Kirchhoff** são utilizadas para encontrar as intensidades das correntes em circuitos elétricos que não podem ser reduzidos a circuitos simples.

Constituídas por um conjunto de regras, elas foram concebidas em 1845 pelo físico alemão Gustav Robert Kirchhoff (1824-1887), quando ele era estudante na Universidade de Königsberg.

A 1ª Lei de Kirchhoff é chamada de **Lei dos Nós**, que se aplica aos pontos do circuito onde a corrente elétrica se divide. Ou seja, nos pontos de conexão entre três ou mais condutores (nós).

Já a 2ª Lei é chamada de **Lei das Malhas**, sendo aplicada aos caminhos fechados de um circuito, os quais são chamados de malhas.

![Circuito](https://static.planejativo.com/uploads/novas/d09a6f5d240d64d30bb107dee127fb1c.jpg)

**Lei dos Nós**

A Lei dos Nós, também chamada de primeira lei de Kirchhoff, indica que a soma das correntes que chegam em um nó é igual a soma das correntes que saem.

Esta lei é consequência da conservação da carga elétrica, cuja soma algébrica das cargas existentes em um sistema fechado permanece constante.

**Exemplo**

Na figura abaixo, representamos um trecho de um circuito percorrido pelas correntes i1, i2, i3 e i4.

Indicamos ainda o ponto onde os condutores se encontram (nó):

![Lei dos Nós](https://static.planejativo.com/uploads/novas/7cc62f67607eefbc9a21001054e803d6.jpg)

Neste exemplo, considerando que as correntes i1 e i2 estão chegando ao nó, e as correntes i3 e i4 estão saindo, temos:

i1 + i2 = i3 + i4

Em um circuito, o número de vezes que devemos aplicar a Lei dos Nós é igual ao número de nós do circuito menos 1. Por exemplo, se no circuito existir 4 nós, vamos usar a lei 3 vezes (4 - 1).

**Lei das Malhas**

A Lei das Malhas é uma consequência da conservação da energia. Ela indica que quando percorremos uma malha em um dado sentido, a soma algébrica das diferenças de potencial (ddp ou tensão) é igual a zero.

Para aplicar a Lei das Malhas, devemos convencionar o sentido que iremos percorrer o circuito.

A tensão poderá ser positiva ou negativa, de acordo com o sentido que arbitramos para a corrente e para percorrer o circuito.

Para isso, vamos considerar que o valor da ddp em um resistor é dado por R . i, sendo positivo se o sentido da corrente for o mesmo do sentido do percurso, e negativo se for no sentido contrário.

Para o gerador (fem) e receptor (fcem) utiliza-se o sinal de entrada no sentido que adotamos para a malha.

Como exemplo, considere a malha indicada na figura abaixo:

![Lei das Malhas](https://static.planejativo.com/uploads/novas/f544d37f1929bc970285163efc5943d9.jpg)

Aplicando a lei das malhas para esse trecho do circuito, teremos:

UAB + UBE + UEF + UFA = 0

Para substituir os valores de cada trecho, devemos analisar os sinais das tensões:

- **ε****1**: positivo, pois ao percorrer o circuito no sentido horário (sentido que escolhemos) chegamos pelo polo positivo;
- **R1.i1**: positivo, pois estamos percorrendo o circuito no mesmo sentido que definimos o sentido de i1;
- **R2.i2**: negativo, pois estamos percorrendo o circuito no sentido contrário que definimos para o sentido de i2;
- **ε2**: negativo, pois ao percorrer o circuito no sentido horário (sentido que escolhemos), chegamos pelo polo negativo;
- **R3.i1**: positivo, pois estamos percorrendo o circuito no mesmo sentido que definimos o sentido de i1;
- **R4.i1**: positivo, pois estamos percorrendo o circuito no mesmo sentido que definimos o sentido de i1;

Considerando o sinal da tensão em cada componente, podemos escrever a equação desta malha como:

ε1 + R1.i1 - R2.i2 - ε2 + R3.i1 + R4.i1 = 0

**
Passo a Passo**

Para aplicar as Leis de Kirchhoff devemos seguir os seguintes passos:

- **1º Passo**: Definir o sentido da corrente em cada ramo e escolher o sentido em que iremos percorrer as malhas do circuito. Essas definições são arbitrárias, contudo, devemos analisar o circuito para escolher de forma coerente esses sentidos.
- **2º Passo**: Escrever as equações relativas a Lei dos Nós e Lei das Malhas.
- **3º Passo**: Juntar as equações obtidas pela Lei dos Nós e das Malhas em um sistema de equações e calcular os valores desconhecidos. O número de equações do sistema deve ser igual ao número de incógnitas.

Ao resolver o sistema, encontraremos todas as correntes que percorrem os diferentes ramos do circuito.

Se algum dos valores encontrados for negativo, significa que a sentido da corrente escolhido para o ramo tem, na verdade, sentido contrário.

**Exemplo**

No circuito abaixo, determine as intensidades das correntes em todos os ramos.

![Lei de Kirchhoff exemplo](https://static.planejativo.com/uploads/novas/ac78be1e0337309ece2975ec0c0dbc03.jpg)

**Solução**

Primeiro, vamos definir um sentido arbitrário para as correntes e também o sentido que iremos seguir na malha.

Neste exemplo, escolhemos o sentido conforme esquema abaixo:

![Lei de Kirchhoff exemplo](https://static.planejativo.com/uploads/novas/1e1f902beb8f7bfe158429d4f8179363.jpg)

O próximo passo é escrever um sistema com as equações estabelecidas usando a Lei dos Nós e das Malhas. Sendo assim, temos:

![abre chaves atributos de tabela alinhamento de coluna left fim dos atributos linha com célula com tabela linha com célula com i com 1 subscrito igual a i com 2 subscrito mais i com 3 subscrito fim da célula linha com célula com 20 menos 4. i com 2 subscrito menos 1. i com 1 subscrito igual a 0 fim da célula linha com célula com 7 mais 1. i com 3 subscrito menos 4. i com 2 subscrito igual a 0 fim da célula fim da tabela fim da célula linha com blank fim da tabela fecha](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAKcAAABpCAYAAABf9DMoAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAABGJhU0UAAAA/dkK/owAABWZJREFUeNrtnTGIHkUUx4fjCIeEQAgiYnEQggQLsRM5gggSRA4JgRQiKUJAgljYWYhYBSxFgiBBUlgIQUKQcKQJIYRDAkGCBBE7yzQWFvIRAud73Bz58rF7uzu7b97Ml98PXpHN3c28ef+dnd1v5/+F0MynEg8DQGFsSdyUeI2hgJK4IPErwwAlcldik2GAEplJrFbc//8kVmh7OdmpuO/HJH6nbcQJ1ICBGcBXEp8vQds7FeWNOHtyVeLUiLy7wqrtsTWYsm3EacRfEq8sQds7FeWNOHuwEu9Ya2x7zKztmTfi7MmbEredBDK27TE1mLptxGnAhxJXGo6/KvGlxIPMbe8J+rHEdth93GNRg662Ne+TiNOXbyXONxz/UeJj47za2t677H4i8ZtRDfZrWzku8Tfi9OWaxPtOeXW1rcyMatDVtp4c/yBOX7QAa055dbX9tsQdh7aPSFySOIc4yauJl+Oa86hDvhpnKSJ5hZabsRtRoB4ckrgY19wUkbyemTG3okC8mVFE8ppnK94pe3NC4j5FLDefIZ+R197ufNs6Y+p2m3XECYA4AXECIE4AxAmIEwBxAuIEQJwAiBMQJ0AR4tyQ+Fni3/B078pHLT+rb+p8J3Evxvchz9s7m4n5efkQjd3/5NFv09qmilPf9NbNVgfjv9XbczseW+SWxAcLorllPGjarz8S8vP0IRqz/8mr36a1nfKyvt4wQGfC7qasRb5pEfJU6Bl8vtJlSy19Nq/t1AOx+KKrXvqbtqq+E//Pgo25s7dGH6KUmnj027y2U4rzrXhpn0c3ZB1o+Fk99shgwA7E2Xs9Mb8SfIhSauLhG2Ve26nEuRYXxBsLx5/s8zuPDQr7ddj98oXU/ErwIUqpiUe/zWs7hTgPS1xvmeKfDFgCjD2TX2+YuYfk5+mBNKYmXv5JKbXNKs6jUZht9iuPWqb+NYPL+r2GftToQzS0Jl6+Uea1HSNO3dB1WeKFjkXzew3HTxrcEI2dtab2QMpVEy/fKPPaporzpbgI7/qyg9NRwItcCbaPklLym9oDKVdNvHyjzGub2vEbof9WWL3kfBaFrJeBL4KdXUvf/Jpm06k9kCxqktJvy+emprXdGfF7fS+fesP0QyysLtz1AfnBAsXp6YEUeo5lSr8txWlaW1786IeXB9JzXWPE2Y23BxLihNYZsxQPJMQJz1CKBxLihKSbFPqOOOF54sWwROb2sDzoQ9OfJN5lKKA09COmMwwDlIh+Vtz2JjMAa04A7tYBcQIgTkCcAIgTwFicU+w8HEqN/kLz1OTnlN3zKsfMqQ/7Lxv97Rr9hfaozc8pu+eVtTh1I9zdsP82gin6U+PypCY/JxfPK+uB+UXijQz9qcVfaI/a/Jw8PK9MxXkhrgdDoeL08kXy9HMq1hcppzjX46J5tWBxevki1ejnlNvzylScd+KUb3Umj83DyxfJ28/JQpyzmsSpi+etzP3J7S+UirefU7G+SDnEqWf2nwNvgjzE2eWL9CDYvE5Yq59TTs8rM3GeCuNcMXKJcz9fJEV3XOZ6nbAGPycXz6upxalbP84VJs4Uf6GVeIfqKc7S/Jyye15NLU5dfxzOuIaz8Bc6InFp5ElmJU5PP6fsnle8+NEsiLMV9r1mPyfE2RN9meFi2P3MvhZq93NCnAOZVdLPZfBzQpwDOCFxv5K+LoOfE+Lsud7UGfNmePrZdy39rtYTCXEC4gRAnIA4ARAnAOIExAmAOAFxAiBOAMQJiBMAcQLiBECcgDgBECcA4gTECYA4AXECIE4AxAlVo3u0VxkGKBH9GpZNhgFKRM2qthkGKBX12tHvCzrOUECJ6HcGPWQYwJP/AcxFcDWhY4DYAAACz3RFWHRNYXRoTUwAPG1hdGggeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzE5OTgvTWF0aC9NYXRoTUwiPjxtZmVuY2VkIGNsb3NlPSIiIG9wZW49InsiPjxtdGFibGUgY29sdW1uYWxpZ249ImxlZnQiPjxtdHI+PG10ZD48bXRhYmxlPjxtdHI+PG10ZD48bXN1Yj48bWk+aTwvbWk+PG1uPjE8L21uPjwvbXN1Yj48bW8+PTwvbW8+PG1zdWI+PG1pPmk8L21pPjxtbj4yPC9tbj48L21zdWI+PG1vPis8L21vPjxtc3ViPjxtaT5pPC9taT48bW4+MzwvbW4+PC9tc3ViPjwvbXRkPjwvbXRyPjxtdHI+PG10ZD48bW4+MjA8L21uPjxtbz4tPC9tbz48bW4+NDwvbW4+PG1vPi48L21vPjxtc3ViPjxtaT5pPC9taT48bW4+MjwvbW4+PC9tc3ViPjxtbz4tPC9tbz48bW4+MTwvbW4+PG1vPi48L21vPjxtc3ViPjxtaT5pPC9taT48bW4+MTwvbW4+PC9tc3ViPjxtbz49PC9tbz48bW4+MDwvbW4+PC9tdGQ+PC9tdHI+PG10cj48bXRkPjxtbj43PC9tbj48bW8+KzwvbW8+PG1uPjE8L21uPjxtbz4uPC9tbz48bXN1Yj48bWk+aTwvbWk+PG1uPjM8L21uPjwvbXN1Yj48bW8+LTwvbW8+PG1uPjQ8L21uPjxtbz4uPC9tbz48bXN1Yj48bWk+aTwvbWk+PG1uPjI8L21uPjwvbXN1Yj48bW8+PTwvbW8+PG1uPjA8L21uPjwvbXRkPjwvbXRyPjwvbXRhYmxlPjwvbXRkPjwvbXRyPjxtdHI+PG10ZC8+PC9tdHI+PC9tdGFibGU+PC9tZmVuY2VkPjxtc3BhY2UgbGluZWJyZWFrPSJuZXdsaW5lIi8+PC9tYXRoPiSNF5QAAAAASUVORK5CYII=)

Por fim, vamos resolver o sistema. Começando substituindo i3 por i1 - i2 nas demais equações:

![abre chaves atributos de tabela alinhamento de coluna left fim dos atributos linha com célula com 20 menos 4. i com 2 subscrito menos espaço i com 1 subscrito igual a 0 fim da célula linha com célula com 7 mais i com 1 subscrito menos i com 2 subscrito menos 4 i com 2 subscrito igual a 0 fim da célula fim da tabela fecha](data:image/png;base64,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)

Resolvendo o sistema por soma, temos:

![Error converting from MathML to accessible text.](data:image/png;base64,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hROUr6MaQAr+BVNLJwxPqLp9AAADS3RFWHRNYXRoTUwAPG1hdGggeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzE5OTgvTWF0aC9NYXRoTUwiPjxtZmVuY2VkIGNsb3NlPSIiIG9wZW49InsiPjxtdGFibGUgY29sdW1uYWxpZ249ImxlZnQiPjxtdHI+PG10ZD48bXN0YWNrIGNoYXJhbGlnbj0iY2VudGVyIiBzdGFja2FsaWduPSJyaWdodCI+PG1zcm93Pjxtbj4yMDwvbW4+PG1vPi08L21vPjxtbj40PC9tbj48bXJvdz48bXN1Yj48bWk+aTwvbWk+PG1uPjI8L21uPjwvbXN1Yj48bW8+LTwvbW8+PG1lbmNsb3NlIG5vdGF0aW9uPSJ1cGRpYWdvbmFsc3RyaWtlIj48bXN1Yj48bWk+aTwvbWk+PG1uPjE8L21uPjwvbXN1Yj48L21lbmNsb3NlPjxtbz49PC9tbz48bW4+MDwvbW4+PC9tcm93PjwvbXNyb3c+PG1zcm93Pjxtbz4rPC9tbz48bW4+NzwvbW4+PG1vPis8L21vPjxtZW5jbG9zZSBub3RhdGlvbj0idXBkaWFnb25hbHN0cmlrZSI+PG1zdWI+PG1pPmk8L21pPjxtbj4xPC9tbj48L21zdWI+PC9tZW5jbG9zZT48bW8+LTwvbW8+PG1yb3c+PG1uPjU8L21uPjxtc3ViPjxtaT5pPC9taT48bW4+MjwvbW4+PC9tc3ViPjxtbz49PC9tbz48bW4+MDwvbW4+PC9tcm93PjwvbXNyb3c+PG1zbGluZS8+PG1zcm93Pjxtbj4yNzwvbW4+PG1vPi08L21vPjxtbj45PC9tbj48bXJvdz48bXN1Yj48bWk+aTwvbWk+PG1uPjI8L21uPjwvbXN1Yj48bW8+PTwvbW8+PG1uPjA8L21uPjxtbz4mI3hBMDs8L21vPjxtbz4mI3hBMDs8L21vPjxtbz4mI3hBMDs8L21vPjxtbz4mI3hBMDs8L21vPjxtbz4mI3hBMDs8L21vPjwvbXJvdz48L21zcm93PjwvbXN0YWNrPjwvbXRkPjwvbXRyPjxtdHI+PG10ZC8+PC9tdHI+PC9tdGFibGU+PC9tZmVuY2VkPjwvbWF0aD409VSQAAAAAElFTkSuQmCC)

![i com 2 subscrito igual a numerador menos 27 sobre denominador menos 9 fim da fração igual a 3 A](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAG8AAAAjCAYAAACaX1R3AAAACXBIWXMAAA7EAAAOxAGVKw4bAAAABGJhU0UAAAAXQ/cXWQAAAsZJREFUeNrtmzFIHEEUhodFQgiHcKQIh4ggR5AUIoQgEmQRJEUQCYFDQgoRQSSVhZBKLMQmlYiNpEgpiEiQcAgiEg4LQY4QUhwBSZ0mhYUcIuh7+C+c5+zMGPVudu998Beuc+vem503/3u7KpUOXpI2SMekU9IP0nvNuHOLhCbwnfSOlMHPz0j7OOZCgfRZwugPXaSfDuOekEqkhxIyv6g6jNki9Umo/GIAqdPENGlOQuUXnAIPYGRMaZXHtEm47pZz9f/OMEv6SnrlYHKGJNT+0I2Jyzu4y6KEyx96YPcfWcYFpIqYFH9gu7/uuH+9QcoUPOEbVp4La6SJtAbiBKklLQannr8wNY1mCPvsCerP36Ql0mPHz8/YBuQduxLCzdkjvSU9qDnG++62w2fH1GXPVsoazzi2/D6LBbWD/TqWedJHiWdDS5uKZcyqumywj5NWTAPXbbN7T4V1qzQQat3xBPa914ZxAzBj0WeOTCflk3XIgmjYxJtMCO9vh6TOmmPlOFcdwAn5ejc3WvdJFhmOe6uhYQubrTu2SPqgG9wPR9TMdNIqaTMigwmspwerrB6e6C3diXhT/BJzoWxT95W9ZyjcHN0zx5LhxtCWDMukyZg/EGC5liXWd0ovfEYtUyjeTR2iayZn0+J84u4SwQ3upxawagJ0XP6gBIjIoabLGM4zqZvcf8r8HkeopKF7GwZh+6sQ+4sRTak2YjlPh2a1Gslhz+tOWMBC7B9VOOmNBH6HW/EUd0wuYdfNT9J/kV4gTbUh5VRQ8KYenjDuhLcn8NoPY1YZ7zufWmHyisr9OZlvnBmcc0u45iQX2twHfK453qWa10kSHCnAiodYbQGcXBmFrtDkLGDLCiEseWTP2YrnZeUll+iFXCGBcGdjQcKQTBaVPLP0nl119YUfnjD+p5JRCY3/DMOscL3HL/lwN743TV/wAnL97XSSQm9YAAAA2nRFWHRNYXRoTUwAPG1hdGggeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzE5OTgvTWF0aC9NYXRoTUwiPjxtc3ViPjxtaT5pPC9taT48bW4+MjwvbW4+PC9tc3ViPjxtbz49PC9tbz48bWZyYWM+PG1yb3c+PG1vPi08L21vPjxtbj4yNzwvbW4+PC9tcm93Pjxtcm93Pjxtbz4tPC9tbz48bW4+OTwvbW4+PC9tcm93PjwvbWZyYWM+PG1vPj08L21vPjxtbj4zPC9tbj48bWk+QTwvbWk+PC9tYXRoPsWX4SkAAAAASUVORK5CYII=)

Agora vamos encontrar o valor de i1, substituindo na segunda equação o valor encontrado para i2:

![20 menos 4.3 menos i com 1 subscrito igual a 0 seta dupla para a direita 20 menos 12 menos i com 1 subscrito igual a 0 seta dupla para a direita 8 menos i com 1 subscrito igual a 0 seta dupla para a direita i com 1 subscrito igual a 8 A](data:image/png;base64,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)

Finalmente, vamos substituir esses valores encontrados na primeira equação, para encontrar o valor de i3:

![i com 3 subscrito igual a 8 menos 3 igual a 5 A](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGsAAAARCAYAAADaBlKrAAAACXBIWXMAAA7EAAAOxAGVKw4bAAAABGJhU0UAAAAMyZLetQAAAkdJREFUeNrtmUFEg2EYxz+TJBPZITMZ6TDJRJIOk12SdJgx6ZDMmHTIJDqlU3TokHTpkE6JDjskiQ6ZTpGkQzKSdOjWIclM1PPw//i8fXu/te19943vz49927s97/M+7/s8z2uG8VdfhM/Qq05ih/gkSsQ5EVJgJ06cwUe2UyS2iYACWz8SqlHOaUA/cW/o1z6xQbQR7cQmca3AziWRhA1TQ9gcKoJVq2aIMtbDdSoJzz5MVpc+XBSsbhyYCyIhG7hOrDYhWJz+/EKwXjXZ7iMeXRSsPWKWmCd2ZQOPnaJZY452ytVcr5Ysz2PEluIg9RBp1K0pBX7VEiz2+9QyvyfZ4KKiwu6kKNIeUyDeiJgiW+JC5xTaKSPFclOzLGQPUVyfbohey3u3RMRusA9dkm6FiUMiaCn8w9hVUQWn2FobEmhkxhX61wZ/1pBuI5IStCK8x03Xot3gUXRLhuY0mK8QlHid86lWfofOsxEbw9QEMoeoCE6RKN5EJ3Y/xEXtoMJE+TjfwZjqTrDaz3TNQYetK8lGsG3huchnJEY4+i8KJv+A+52oAdQuHfWyqClQgzZNQxYX80o6smuA8g5dEde0dwUOJBGwOGz48JqdWmiwLU5BKexU084z2uRGK4/uzvRpEj4lLWOCuFPJGo+MXTA5EB0VvhBAz59WtONSyNllpIlCHVcImWJojUuAa+K0Qp/4xH5jbflaNGJzVXKyH/rPyTdz55zhqSXUhTYy6y1F66jkLUFrKIYbtieXyqxX5n9MYW9Jmqdfb3i0D6s8K7gAAACmdEVYdE1hdGhNTAA8bWF0aCB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMTk5OC9NYXRoL01hdGhNTCI+PG1zdWI+PG1pPmk8L21pPjxtbj4zPC9tbj48L21zdWI+PG1vPj08L21vPjxtbj44PC9tbj48bW8+LTwvbW8+PG1uPjM8L21uPjxtbz49PC9tbz48bW4+NTwvbW4+PG1pPkE8L21pPjwvbWF0aD5XYB8IAAAAAElFTkSuQmCC)

**Assim, os valores das correntes que percorrem o circuito são: 3A, 8A e 5A.**

**
Ponte** **de** **Wheatstone****
**

**Ponte** **de** **Wheatstone** é um circuito elétrico muito útil para a realização de medidas precisas de resistência elétrica. Esse circuito é formado por **quatro resistores** e um **galvanômetro**, sendo dois desses resistores conhecidos ou predeterminados, um deles de resistência variável e, por último, um de resistência desconhecida.

A ponte de Wheatstone foi inventada por **Samuel** **Hunter** **Christie,** entretanto seu nome permaneceu como uma forma de homenagem a **Sir** **Charles** **Wheatstone,** responsável por difundir o uso dessa configuração de resistores.

**Aplicações**

Além de sua utilização mais comum (a de medir uma resistência elétrica desconhecida), a ponte de Wheatstone está presente em diversos tipos de circuitos que necessitam de **sensores** bastante precisos, como **balanças**, **termostatos**, **sensores de pressão** etc.

![A figura acima mostra uma antiga ponte de Wheatstone.](https://static.planejativo.com/uploads/novas/78281403c299db8859a9b405ce442b3c.jpg)
A figura acima mostra uma antiga ponte de Wheatstone.

**Cálculo das resistências**

Na ponte de Wheatstone, ligam-se quatro resistores, em dois diferentes ramos de um circuito, a uma bateria. Em seguida, esses ramos são conectados por um fio, que os leva a um galvanômetro. O galvanômetro serve como um indicador de corrente elétrica, dessa forma, altera-se a resistência do resistor variável até que o galvanômetro não acuse a passagem de corrente. Quando nenhuma corrente passa pelo galvanômetro, não há diferença de potencial entre os ramos do circuito. Nessa situação, dizemos que a ponte de Wheatstone encontra-se em **equilíbrio**.

A figura a seguir mostra o esquema de uma ponte de Wheatstone formado pelos resistores R1, R2, R3 e RX, observe:

![img](https://static.planejativo.com/uploads/novas/71d3df0f736fdb19009712285b80bed2.jpg)

A ponte de Wheatstone encontra-se em equilíbrio desde que ig = 0.

**i****g** — corrente no galvanômetro

**R****X** — resistência desconhecida

**R****1****, R****2****, R****3** — resistências conhecidas

Na situação de equilíbrio, o circuito mostrado na figura anterior pode ser usado para determinar com grande precisão a resistência elétrica do elemento resistivo RX. Para tanto, é necessário que a corrente a atravessar o galvanômetro seja igual a 0. No caso afirmativo, dizemos que há uma **igualdade** entre os **produtos das resistências cruzadas** que pode ser escrita pela seguinte fórmula:

![img](https://static.planejativo.com/uploads/novas/4a42d69cfad9a513c649d3de4cd7b49d.jpg)

**Demonstração**

A identidade mostrada na figura anterior, apesar de muito simples, é determinada pela lei da conservação da energia, por meio da lei de Kirchoff que se refere às malhas. Essa lei, conhecida como a **2ª lei de Kirchoff**, determina que a **soma dos potenciais elétricos** em cada malha do circuito é sempre **nula**.

Por isso, somaremos todos os potenciais elétricos nas malhas **ADC** e **DBC** e igualaremos essas somas a zero. Observe a imagem a seguir:

![img](https://static.planejativo.com/uploads/novas/5d5fabcd2e9108343fe2c17c79a2e067.jpg)

Aplicando a lei das malhas, conseguimos encontrar o resultado que diz respeito ao produto cruzado das resistências.

Para chegarmos no resultado anterior, fizemos uso da **1ª lei de Ohm**, que diz que a queda de potencial elétrico nos elementos resistivos de um circuito é dada por **U = R.i**, juntamente à **lei das malhas**, que afirma que o potencial elétrico deve ser **negativ**o, caso percorramos a malha no mesmo sentido da corrente elétrica em cada ramo (lembre-se de que o sentido da corrente elétrica pode ser arbitrado como quisermos).

**Resumo**

- A ponte de Wheatstone é um circuito formado por quatro resistores ligados em série e paralelo, conectados por um galvanômetro;
- A ponte de Wheatstone pode ser usada para determinar uma resistência elétrica desconhecida;
- Para determinar a resistência desconhecida, é necessário que a ponte de Wheatstone esteja em equilíbrio, isto é, a corrente no galvanômetro deve ser nula;
- Se a ponte de Wheatstone estiver em equilíbrio, então podemos igualar o produto cruzado das resistências.

**Fontes:**

[Toda Matéria - Leis de Kirchhoff](https://www.todamateria.com.br/leis-de-kirchhoff/)
[Mundo Educação - Ponte de Wheatstone](https://mundoeducacao.bol.uol.com.br/fisica/ponte-wheatstone.htm)

Vídeos Relacionados:

# Ponte de Wheatstone - Eletrodinâmica - Aula 18 - Prof. Marcelo Boaro

https://www.youtube.com/watch?v=tlPNRa4_0js

# Leis de Kirchhoff - Eletrodinâmica - Aula 19 - Prof. Marcelo Boaro

https://www.youtube.com/watch?v=5q0ss9G8Xlc



