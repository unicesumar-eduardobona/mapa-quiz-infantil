## Funcionalidade: Persistindo Votos

### Problema

O script votar.php precisa de algumas melhorias e dentre elas podemos destacar a persistência do voto, a pontuação acumulada 

Ao executar o script votar.php?apresentado=x&escolhido=y o jogo precisa persistir (armazenar) este voto para uso posterior.
- A persistência inicialmente, neste estágio, será por meio de registro em arquivo (filesystem).
- O arquivo se chamará votos.csv e estará dentro da pasta dados (dados/votos.csv)
- Cada voto ficará em uma linha do arquivo com o respectivo código
- Um arquivo de exemplo chamado dados/votos.modelo.csv foi criado para você ter uma ideia de como deveria ficar.


