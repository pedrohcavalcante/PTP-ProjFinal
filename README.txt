GRUPO:
PEDRO HENRIQUE BEZERRA CAVALCANTE
Y�N S�VIO ALVES DA COSTA


O que foi desenvolvido foi o b�sico do programa, que � a entrada do usu�rio, a gera��o da matriz com n�meros aleat�rios e a inunda��o, 
acompanhado dos crit�rios de parada. Al�m disso, o grupo implementou a escolha do tamanho da matriz em tr�s diferentes dificuldades, 
cada uma com sua respectiva quantidade de jogadas poss�veis, como um elemento extra proposto. N�o foi conclu�da a colora��o da matriz, 
como no jogo original, porque, primeiramente, bibliotecas gr�ficas � uma parte de programa��o que exige um per�odo de tempo consider�vel 
para o aprendizado e sua utiliza��o; e, tamb�m, tivemos problemas em instalar bibliotecas que seriam essenciais para a implementa��o de 
altera��o de cor ( como a conio2.h e a conio.c) em nosso compilador. Dessa forma, como o projeto se tornou um pouco mais trabalhoso ao 
longo do tempo, n�o tivemos tempo suficiente para aprendermos esses recursos.

De certa forma, pensamos que dever�amos ter planejado melhor nosso tempo para otimizarmos o progresso do trabalho. 
Entretanto, vejo que com o andar do processo, o trabalho teve poucos problemas que atrapalharam um progresso maior 
(com exce��o do tempo gasto nas pesquisas sobre bibliotecas gr�ficas e na l�gica final para tratamento de erros).

O nosso c�digo foi feito atrav�s do DevC++ e do Geany, ambos n�o apresentam bibliotecas gr�ficas. 
A �nica diferen�a entre eles � que a fun��o de limpar a tela deve ser adaptada para cada compilador.

Nossa dupla � formada por Pedro Henrique e Yan S�vio. De maneira geral, todos os dois contribu�ram 
igualmente para o projeto. Em alguns dias, algum dos dois ficou com a responsabilidade de pesquisa de 
bibliotecas gr�ficas e elementos extras poss�veis e o outro com a constru��o do c�digo.Mas, ao longo do 
trabalho e em todo o c�digo, houve a coopera��o m�tua.

==========================================================================================================================================

Nesse projeto, foram atendidos os seguintes requisitos: 
==> Tipos de dados necess�rios;
==> Modulariza��o do programa em arquivos;
==> Gera��o aleat�ria do tabuleiro;
==> Apresenta�a� da interface do jogo;
==> Leitura da entrada do usu�rio e atualiza��o da matriz de forma recursiva;
==> Implementa��o da condi��o de parada do jogo;
==> Salvamento e carregamento de um estado do jogo;
==> Possibilitada a cria��o de n�veis de jogos, como o F�cil (4X4) M�dio (10X10) e Dif�cil (14X14) com n�meros m�ximos de jogadas diferentes;

N�o foram atendidas as seguintes funcionalidades:
==> Distribui��o uniforme dos n�meros aleat�rios;
==> Possibilidade de Salvar/Carregar v�rios jogos;
==> Suporte a cores;
==> Uso de biblioteca gr�fica;
==> Possibilidade de "Undo"

==========================================================================================================================================

COMO COMPILAR O PROJETO.

Existe uma pequena mudan�a no c�digo ao compilar usando o Windows ou Linux. 

Ao usar o Windows, � poss�vel utilizar normalmente a biblioteca <conio.h> e usar o comando 'system("cls"). Ao compilar no Linux, deve-se colocar
em forma de coment�rio a inclus�o da biblioteca supracitada e desse comando, devendo substituir pelo 'system("clear");
