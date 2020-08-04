# Quiz Infantil

## Mapa de Desenvolvimento

### Deixando página inicial funcional e com mais animais

Você está recebendo um projeto em mãos. Este projeto já foi iniciado por outro desenvolvedor e agora cabe a você terminar ele conforme os requisitos.

A tela, no que diz respeito ao visual (interface), está pronta. Ela está divivida em duas áreas horizontais sendo que a primeira apresenta duas características de um animal e a outra apresenta duas opções possível de animal.

Ao executar o projeto, você verá um jogo e se fizer a simulação de várias vezes um jogo iniciando (dando f5) irá notar que:
- Só tem dois animais, o cachorro e a coruja
- De forma equivocada, o sistema está previsivelmente sempre mostrando animal correto na primeira posição, da esquerda. E isso precisa ser aleatório.
- Em alguns momentos o cachorro repete na tela
- Ao clicar em uma opção, a tela posterior apresenta uma mensagem pela metade faltando informação

Por isso, nesta primeira etapa é desejado que:
1. Adicione a lista de animais mais 2 animais
    - Lembrando que cada animal tem duas características
    - Lembrando que cada animal tem uma imagem para ele e outras duas sendo uma para cada característica
    - Garanta que estes novos animais passem a figurar dentre as opções e no jogo
2. Corrija o código de modo que o animal correto deixe de ser sempre o primeiro e passe então esta ordem a ser aleatória.
    - Não há problemas em o animal correto ser o primeiro algumas vezes, o problema é ele ser sempre. Isso deveria ser randômico, aleatório.
3. Corrija o código de modo que o cachorro ou qualquer outro animal não apareça duas vezes como as únicas duas opções.
    - É preciso mostrar o animal correto e outro animal, qualquer um, desde que não seja o mesmo.
4. A mensagem da tela posterior deve seguir o seguinte critério caso seja mostrada a opção coruja e cachorro e a opção correta seja cachorro:
    - A mensagem será: "Você escolheu: coruja. A opção correta é: cachorro."

### Dicas

#### Por onde começar?

#### O que eu vou precisar usar para resolver o exercício?

#### Onde encontrar imagens de animais?

Basicamente uma consulta no Google resolve e em tese a imagem em si não é o foco principal.

Para quem quiser deixar bonito e padronizado, a imagem deve ser quadrada, se for possível 512x512 pixels.

Um link de busca que podem encontrar mais exemplos deixarei a seguir:
https://www.google.com/search?source=univ&tbm=isch&q=google+icon+animal+512x512&sa=X&ved=2ahUKEwih6prGx4LrAhWzErkGHa17CyAQsAR6BAgKEAE&biw=1920&bih=983

