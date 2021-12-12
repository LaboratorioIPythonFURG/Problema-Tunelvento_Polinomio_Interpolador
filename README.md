# Problema 3
_(Fonte: Linear Algebra and Its Applications. Addison-Wesley Longman, 1997)_

Suponha que um conjunto de dados experimentais seja representado por um conjunto de pontos do plano.
Um polinômio interpolador para esse conjunto de dados é um polinômio cujo gráfico passa por cada ponto.
Em trabalhos científicos, esse polinômio pode ser usado, por exemplo, para obter estimativas de valores
entre pontos conhecidos.

Em uma experiência num túnel de vento, a força sobre um projétil devido à resistência do ar foi medida
para velocidades diferentes:

| Velocidade | Força |
| -- | --  | 
| 0 | 0 |
| 2 | 2.9 |
| 4 | 14.8 |
| 6 | 39.6 |
| 8 | 74.3 |
| 10 | 119 | 

1. Determine um polinômio interpolador para esse conjunto de dados e obtenha uma estimativa para a força
sobre o projétil quando ele está se deslocando a uma velocidade de 228,6 m/s. Use $p(t) = a_0 + a_1t + a_2t^2 + a_3t^3 + a_4t^4 $

2. O que acontece se tentarmos obter a resposta empregando um polinômio cúbico, por exemplo?
