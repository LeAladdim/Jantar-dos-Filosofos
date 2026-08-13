# Jantar-dos-Filosofos
Programa para resolver o famigerado dilema do Jantar dos Filósofos em que:

° Cinco filósofos sentam-se a uma mesa redonda.
° Há um prato de macarrão para cada um e um garfo entre cada par de pratos.
° Cada filósofo alterna entre pensar e comer.
° Para comer, o filósofo precisa pegar os dois garfos adjacentes (um à esquerda e outro à direita).

Os Desafios:

° Se todos os filósofos sentirem fome ao mesmo tempo e pegarem primeiro o garfo da sua direita, cada um ficará com um garfo na mão.

° O segundo garfo necessário estará ocupado pelo vizinho.

° Nenhum deles conseguirá comer nem largar o garfo para liberar o próximo, gerando um bloqueio infinito (deadlock)


Esse problema busca elucidar conceitos como Starving e Badlock, além de estimular o uso e o aprendizado de táticas para evitar tais problemas. A linguagem escolhida foi Java, e algumas das estratégias utilizadas foram: 

° Atacar a 2° condição de Coffman através do tryAcquire, que faz com que se um filósofo não  conseguir 2 garfos de imediato ele largue o que está segurando, eliminando a Posse e Espera

° Atacar a Starvation usando ordem de tentativa aleatória dos filósofos, se todos buscassem sempre pegar os garfos na mesma ordem não tardaria a haverem problemas 

