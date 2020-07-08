# Quiz Infantil

## Mapa de Desenvolvimento

### Adicionando nova funcionalidade de persistência de votos e atualização da pontuação

O script votar.php precisa de algumas melhorias e dentre elas podemos destacar a persistência do voto, a pontuação acumulada 

Ao executar o script votar.php?apresentado=x&escolhido=y o jogo precisa persistir (armazenar) este voto para uso posterior.
- A persistência inicialmente, neste estágio, será por meio de registro em arquivo (escrita em arquivo / filesystem).
- O arquivo se chamará votos.csv e estará dentro da pasta dados (dados/votos.csv)
- Cada voto ficará em uma linha do arquivo com o respectivo código
- Um arquivo de exemplo chamado dados/votos.modelo.csv foi criado para você ter uma ideia de como deveria ficar.
- Um outro arquivo chamado dados/pontos.csv armazenará um ponto a mais (incrementará) sempre que você acertar a resposta

Ao executar o script reiniciar.php:
- A votação deverá retornar ao estágio inicial (vazia), excluindo deste modo votos anteriores
- A pontuação deverá retornar ao estágio inicial (valor vazio ou 0), excluindo deste modo pontuação anterior
- O usuário deverá ser redirecionado para a página inicial index.php
