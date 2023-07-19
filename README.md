# Chess Game System ☕💻♟

# Sobre o projeto
Quando a simulação é iniciada, os jogadores têm a opção de escolher seus lados: o exército das peças brancas(brancas) ou o exército das peças pretas(Amarelas). 
O tabuleiro é apresentado com todas as peças dispostas em suas posições iniciais, dando início à emoção de uma partida de xadrez real.

Cada peça se movimenta de acordo com suas regras específicas, e a aplicação garante que apenas movimentos válidos sejam permitidos, mantendo a 
integridade das regras oficiais do jogo. Os jogadores têm a oportunidade de utilizar táticas bem conhecidas do xadrez, como roque, en passant e 
promoção de peões, tornando a experiência ainda mais desafiadora e estratégica.

- A mecânica do jogo é baseada em **linhas**(_1, 2, 3, 4, 5, 6, 7, 8_) e **colunas**(_a, b, c, d, e, f, g, h_)
- Para **escolher** uma peça é necessário selecionar _primeiramente_ a **coluna** e logo em seguida(sem espaços) selecionar a **linha**, exemplo: **c2**
- Em **Captured pieces** o jogo armazena as peças capturadas.
- O **Turn** exibe o turno(rodada) em que o jogo está.
- **Waiting player** exibe qual é o jogador a jogar a próxima peça.
- **Source** é a origem, ou seja, a peça no qual o jogador irá jogar.
- **Target** é o destino, ou seja, o local no qual o jogador irá mover a peça.
- O jogo possui sistema de **Check** e **CheckMate**
- Alguns movimentos especiais:
  - Castling(Roque)
  - En Passant
  - Promotion(Promoção)

# Tecnologias utilizadas
- Java
- POO

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone git@github.com:IagoCappeletti/chess-system-java.git

# entrar na pasta do projeto 
cd chess-system-java/chess-system/src/application/Program.java

# executar o projeto
Java application/Program
```


# Diaagrama UML do Projeto
![chess-system-design](https://user-images.githubusercontent.com/11077068/195115475-23c9c172-72b3-46f5-94da-eb57e1189a5a.png)

# Autor

Iago Cappeletti

Linkedin: <i> [Iago Cappeletti](https://www.linkedin.com/in/iago-kilppe-cappeletti/) </i>  

Instrutor: <i>  [Nelio Alves](https://github.com/acenelio) </i>  
