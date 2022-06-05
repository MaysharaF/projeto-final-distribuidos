# projeto-final-distribuidos
Como sugestão e mostrado em aula, pode-se desenvolver dois nós: nó sink e nó sensor.

O primeiro nó descrito como nó sink ou Estação Base terá como objetivo criar uma rota até todos os nós da rede (como mostrado no exemplo de rotas do Sinalgo) e, posteriormente, receber indefinidamente pacotes dos nós sensores que estiverem mais próximos.

O segundo nó descrito como nó sensor terá como objetivo receber pacotes de rotas de quaisquer nós sinks e, após, ser capaz de enviar pacotes indefinidamente para o nó sink  mais próximo.

Como cenário proposto para teste sugere-se uma área bidimensional de 600x600; com 100 nós sensores e 4 nós sinks. Para distribuir os nós sensores na área sugere-se primeiramente um modelo de distribuição em grade (Grid2D) com os 4 sinks localizados em cada extremidade da área. Após, sugere-se o mesmo cenário mas com modelo de distribuição randômica (Random) dos nós sensores.
