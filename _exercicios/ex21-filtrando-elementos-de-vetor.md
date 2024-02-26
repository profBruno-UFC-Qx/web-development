---
layout: exercicio
numero: 21
nome: Filtrando elementos de um vetor
topicos: javascript, funções, objetos, vetores
---

### Descrição:

Neste exercício, você irá uma função que filtra um vetor com base em um critério qualquer de filtragem. 

Considere que uma tarefa é representada por objeto que possui as seguintes propriedades como mostra o exemplo abaixo: título, concluida e prioridade.

Exemplos de tarefas:

```js
const tarefas = [
  { titulo: "Estudar JavaScript", concluida: false, prioridade: 2 };
  { titulo: "Estudar HTML e CSS", concluida: true, prioridade: 1 }
]
```

Instruções:

1. Crie uma função chamada `filtrarTarefas` que aceita três argumentos: o vetor de tarefas, o critério de filtragem e o valor para aplicar o filtro.
2. Implemente a lógica para filtrar o vetor com base no critério e valor fornecidos. 
  * Por exemplo, se o critério for "concluidas" e o valor for true, filtre as tarefas concluídas.
3. A função deve retornar um novo vetor contendo apenas as tarefas que atendem ao critério de filtragem.


Exemplo:

```js
const tarefas = [
  { titulo: "Estudar JavaScript", concluida: false },
  { titulo: "Fazer compras", concluida: true },
  // ...
];

const tarefasConcluidas = filtrarTarefas(tarefas, "concluidas", true);
console.log(tarefasConcluidas); // [{ titulo: "Fazer compras", concluida: true }]
```

Desafio extra:

* Altere a função de forma que seja possível filtrar por mais de um critério combinado, de forma que somente as tarefas que atendam todos critérios sejam retornadas.

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
