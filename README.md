# Jantar-dos-Filosofos
° Programa para resolver o famigerado dilema do Jantar dos Filósofos


Esse problema busca elucidar conceitos como Starving e Badlock, além de estimular o uso e o aprendizado de táticas para evitar tais problemas. A linguagem escolhida foi Java, e algumas das estratégias utilizadas foram: 

° Atacar a 2° condição de Coffman através do tryAcquire, que faz com que se um filósofo não  conseguir 2 garfos de imediato ele largue o que está segurando, eliminando a Posse e Espera

° Atacar a Starvation usando ordem de tentativa aleatória dos filósofos, se todos buscassem sempre pegar os garfos na mesma ordem não tardaria a haverem problemas 

