# Game Brief: Vitrine Doce

**Frase de venda:** Arraste docinhos pelas prateleiras de uma confeitaria, complete fileiras para atender os pedidos dos clientes e veja tudo virar confete antes que a vitrine transborde.

## Ciclo de jogo
- Arrastar um doce (de 1 a 4 casas) para a esquerda ou para a direita: uma jogada.
- Os doces sem apoio caem e as fileiras completas viram confete. Uma cadeia de fileiras multiplica os pontos.
- Uma fileira nova sobe do forno, e a próxima aparece como prévia.
- Cada fileira que some conta para os pedidos da fase. Ao cumprir todos, a fase é vencida, ganha estrelas e libera a próxima.

## Objetivo e derrota
- **Vencer:** cumprir todos os pedidos da fase.
- **Perder:** um doce encosta no topo da vitrine.
- **Estrelas:** de 1 a 3, conforme a pontuação.

## Versão mínima (o que precisa existir)
1. Tabuleiro de 9×10 e arrastar doces de 1 a 4 casas na horizontal, encaixando na grade.
2. Gravidade, limpar fileira e reação em cadeia.
3. Fileira nova a cada jogada, com prévia; transbordar é derrota.
4. Pedidos por fase, de 1 a 3 por fase. Exemplos: "limpe 3 fileiras com morango", "faça um combo de 2".
5. 10 fases definidas em arquivo de dados, com dificuldade crescente; progresso e estrelas ficam salvos.
6. Acabamento das animações: esticar e amassar, explosão de confete, tremida na tela, som que sobe de tom no combo, vibração e doces com carinhas que reagem.
7. Telas: seleção de fases, pausa, vitória e derrota. Layout em retrato, funcionando no celular e no navegador.

## Fica de fora
- Modo infinito com recorde.
- Power-ups (como martelo ou eliminar uma cor).
- Anúncios e compras dentro do jogo.
- Ranking online.
- Mapa de fases ilustrado (por enquanto é só uma grade de fases).
- Mais de 10 fases, editor de fases.
- Temas e visuais alternativos, multiplayer.

## Ordem de construção
1. Lógica do tabuleiro com quadrados coloridos: deslizar, gravidade, limpar fileira e cadeia, com testes. Serve para provar que é divertido antes de qualquer arte.
2. Fileira nova e derrota.
3. Pedidos e uma fase lida do arquivo de dados.
4. Acabamento das animações.
5. Arte dos doces e telas.
6. As 10 fases e o balanceamento.
7. Exportar para Web e Android.

---
**Para quem e o que sente:** jogadores casuais de celular, em partidas de 2 a 5 minutos, com a satisfação de ver tudo se encaixar e a vontade de "só mais uma fase".

**Arte e áudio:** 2D vetorial fofo, em tons pastel vivos, com doces brilhantes de carinhas expressivas. Música alegre e leve de confeitaria, com sons crocantes e estalos.

**Jogo de referência:** os jogos de deslizar blocos do tipo *Slidey: Block Puzzle*. A versão mínima mantém o ciclo de deslizar e fileira subindo; os pedidos por fase são o nosso diferencial.
