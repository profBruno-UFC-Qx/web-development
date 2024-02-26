---
layout: exercicio
numero: 23
nome: Pontuação no Campeonato Brasileiro
topicos: javascript, objeto, funções
---

### Descrição:

Neste exercício, você irá criar uma função que calcule a pontuação total de um time no campeonato brasileiro.

Instruções:

1. A função deve receber um objeto que representa o desempenho do time no campeonato, com as seguintes propriedades:
time: 
  - Nome do time (string).
  - vitorias: Número de vitórias (number).
  - empates: Número de empates (number).
  - derrotas: Número de derrotas (number).
2. A pontuação total do time é calculada da seguinte forma:
  - Cada vitória vale 3 pontos.
  - Cada empate vale 1 ponto.
  - Cada derrota vale 0 pontos.
3. Crie a função chamada `calcularPontuacao` que aceita o objeto de desempenho do time como argumento.
4. Dentro da função, implemente a lógica para calcular a pontuação total do time.
5. Retorne a pontuação total calculada.
6. Teste a função chamando-a com diferentes objetos de desempenho e exiba o resultado.
7. O número de vitórias, empates e derrotas devem ser números inteiros e positivos, caso contrário uma exceção deve ser lançada.

Exemplo de uso da função:

```js
const desempenhoTime = { time: "Ceará", vitorias: 6, empates: 3, derrotas: 2 };
const pontuacaoTotal = calcularPontuacao(desempenhoTime);
console.log(`A pontuação total do time ${desempenhoTime.time} é: ${pontuacaoTotal}`);
```


Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
