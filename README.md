# Provas_2021.2
P2
Considere listas simplesmente encadeadas, não circulares e sem nós cabeça.

Escreva um programa em C que:

a) (2,0) Crie uma função para preencher L1 e L2 com N números inteiros cada. Os
elementos não precisam ser ordenados, mas não podem ser incluídos números
repetidos em uma mesma lista.
Um novo elemento deve ser sempre inserido na Lista da seguinte forma:
  - Se o elemento for par, ele deverá ser inserido ao final da lista
  - Se o elemento for ímpar, ele deverá ser inserido no início da lista
Para resolver este item, crie uma única função chamada insereElem(L,elem).
  • Não deve ser criada uma função separada para fazer a busca de elementos.
  • As duas lista L1 e L2 devem possuir a mesma quantidade de nós.


b) (3,0) Após criar L1 e L2, crie uma função chamada inverteLista(L) que deverá
inverter uma Lista passada como parâmetro.
Não devem ser criados novos nós para a criação da lista invertida. Os ponteiros devem
ser ajustados para que a lista resultante seja produzida.
Exemplo:
    L1 -> 15 -> 40 -> 20 -> 58 -> NULL
    L1inv -> 58 -> 20 -> 40 -> 15 -> NULL

c) (2,0) Após inverter L1 e L2 chame a função combina(L1,L2), que receberá como
parâmetros as duas listas invertidas e deverá retornar uma única lista resultante que será
a concatenação de L1+L2.
Exemplo:
    L1 -> 58 -> 20 -> 40 -> 15 -> NULL
    L2 -> 27 -> 31 -> 18 -> 30 -> NULL
Resultado: 
    L1 -> 58 -> 20 -> 40 -> 15 -> 27 -> 31 -> 18 -> 30 -> NULL

d) (2,0) Por último faça uma função apagaPares(L) que receberá a lista concatenada e
deverá apagar todos os elementos pares.
e) (1,0) Ao final do programa imprima a lista resultante de trás pra frente. Para isso, faça a
função imprimeReverso(L).

OBS:
  • Crie uma função imprimeLista(L) para que você possa chamar para fazer a
  conferência das suas operações durante o programa. É uma sugestão, esta função
  não vale ponto.
  • Se você estiver usando o replit, coloque o comando printf("\n\n"); antes do
  return 0 do programa principal. Isto evitará que o replit se perca ao imprimir
  algumas informações.
