O que é o projeto?

https://pt.wikipedia.org/wiki/Jogo_da_vida

Inspirado no jogo original, a equipe tem por objetivo recria-lo utilizando a linguagem Java (17).
O Jogo da Vida é um jogo sem jogadores que simula a evolução de diversas "células", estas podendo estar em dois estados, "Viva" ou "Morta", essas celulas estão posicionadas em um Grid definido pelo usuário, e podem observar as oito unidades do Grid que estão adjacentes a ela.
O sistema segue sempre quatro regras base:

1. Qualquer célula viva com menos de dois vizinhos vivos morre de solidão.
2. Qualquer célula viva com mais de três vizinhos vivos morre de superpopulação.
3. Qualquer célula morta com exatamente três vizinhos vivos se torna uma célula viva.
4. Qualquer célula viva com dois ou três vizinhos vivos continua no mesmo estado para a próxima geração.

E uma quinta regra adicional que foi definida por nós:
5. Qualquer célula fora da grade definida pelo usuário está definida como morta.

Os resultados dessa evolução muitas vezes são imprevisíveis, podendo chegar a estagnação, morte total da população, ou um ciclo de procriação infinito.

Como executa o projeto?
* Clonar o projeto do github, entrando na pagina do projeto, aperte code baixe o arquivo ou clone o repositorio
* Instalar Jdk 17
* Compilar usando o comando no terminal ".\mvnw.cmd clean install"
* Executar o programa no terminal com o comando "java -jar .\target\game_of_life-0.0.1-SNAPSHOT.jar"
