GRUPO:
PEDRO HENRIQUE BEZERRA CAVALCANTE
YÁN SÁVIO ALVES DA COSTA


O que foi desenvolvido foi o básico do programa, que é a entrada do usuário, a geração da matriz com números aleatórios e a inundação, 
acompanhado dos critérios de parada. Além disso, o grupo implementou a escolha do tamanho da matriz em três diferentes dificuldades, 
cada uma com sua respectiva quantidade de jogadas possíveis, como um elemento extra proposto. Não foi concluída a coloração da matriz, 
como no jogo original, porque, primeiramente, bibliotecas gráficas é uma parte de programação que exige um período de tempo considerável 
para o aprendizado e sua utilização; e, também, tivemos problemas em instalar bibliotecas que seriam essenciais para a implementação de 
alteração de cor ( como a conio2.h e a conio.c) em nosso compilador. Dessa forma, como o projeto se tornou um pouco mais trabalhoso ao 
longo do tempo, não tivemos tempo suficiente para aprendermos esses recursos.

De certa forma, pensamos que deveríamos ter planejado melhor nosso tempo para otimizarmos o progresso do trabalho. 
Entretanto, vejo que com o andar do processo, o trabalho teve poucos problemas que atrapalharam um progresso maior 
(com exceção do tempo gasto nas pesquisas sobre bibliotecas gráficas e na lógica final para tratamento de erros).

O nosso código foi feito através do DevC++ e do Geany, ambos não apresentam bibliotecas gráficas. 
A única diferença entre eles é que a função de limpar a tela deve ser adaptada para cada compilador.

Nossa dupla é formada por Pedro Henrique e Yan Sávio. De maneira geral, todos os dois contribuíram 
igualmente para o projeto. Em alguns dias, algum dos dois ficou com a responsabilidade de pesquisa de 
bibliotecas gráficas e elementos extras possíveis e o outro com a construção do código.Mas, ao longo do 
trabalho e em todo o código, houve a cooperação mútua.

==========================================================================================================================================

Nesse projeto, foram atendidos os seguintes requisitos: 
==> Tipos de dados necessários;
==> Modularização do programa em arquivos;
==> Geração aleatória do tabuleiro;
==> Apresentaçaõ da interface do jogo;
==> Leitura da entrada do usuário e atualização da matriz de forma recursiva;
==> Implementação da condição de parada do jogo;
==> Salvamento e carregamento de um estado do jogo;
==> Possibilitada a criação de níveis de jogos, como o Fácil (4X4) Médio (10X10) e Difícil (14X14) com números máximos de jogadas diferentes;

Não foram atendidas as seguintes funcionalidades:
==> Distribuição uniforme dos números aleatórios;
==> Possibilidade de Salvar/Carregar vários jogos;
==> Suporte a cores;
==> Uso de biblioteca gráfica;
==> Possibilidade de "Undo"

==========================================================================================================================================

COMO COMPILAR O PROJETO.

Existe uma pequena mudança no código ao compilar usando o Windows ou Linux. 

Ao usar o Windows, é possível utilizar normalmente a biblioteca <conio.h> e usar o comando 'system("cls"). Ao compilar no Linux, deve-se colocar
em forma de comentário a inclusão da biblioteca supracitada e desse comando, devendo substituir pelo 'system("clear");
