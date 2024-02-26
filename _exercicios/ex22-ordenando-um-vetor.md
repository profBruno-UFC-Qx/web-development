---
layout: exercicio
numero: 22
nome: Ordenando um vetor
topicos: javascript, funções, objetos, vetores
---

### Descrição:

Neste exercício, você irá criar uma função que ordena um vetor de objetos com base em um critério específico.


## Instruções:

Considere que uma tarefa é representada por objeto que possui as seguintes propriedades como mostra o exemplo abaixo: título, concluida, prioridade e data.

```js
const tarefas = [
  { titulo: "Estudar JavaScript", concluida: false, prioridade: 2, data: "2023-08-15" };
  { titulo: "Estudar HTML e CSS", concluida: true, prioridade: 1, data: "2023-08-10" }
]
```

1. Crie uma função chamada ordenarTarefas que aceita dois argumentos: o array de tarefas e um critério de ordenação (por exemplo, "prioridade" ou "titulo") e ordem (crescente ou decrescente).
2. Implemente a lógica para ordenar o array de tarefas com base no critério fornecido.
  -  Se o critério for "prioridade", as tarefas devem ser ordenadas pela propriedade prioridade.
3. A função deve retornar o vetor ordenado.
Exemplo:

```js
const tarefas = [
  { titulo: "Estudar JavaScript", data: "2023-08-15" },
  { titulo: "Fazer compras", data: "2023-08-10" },
  // ...
];

const tarefasOrdenadasPorData = ordenarTarefas(tarefas, "data", "crescente");
console.log(tarefasOrdenadasPorData);
```

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
