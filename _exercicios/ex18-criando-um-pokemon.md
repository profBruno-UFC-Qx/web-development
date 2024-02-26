---
layout: exercicio
numero: 18
nome: Criando um pokemon
topicos: javascript, objeto, funções
---

### Descrição:

Neste exercício, você irá praticar a criação de funções e objetos em JavaScript. Você vai criar uma função que recebe informações sobre um Pokémon e retorna um objeto que o representa.

Instruções:

1. Crie uma função chamada `criarPokemon` que aceita quatro argumentos: 
  - nome (string), tipo (string), nivel (number) e hp (number).
2. Dentro da função, crie um objeto vazio chamado pokemon.
3. Adicione as seguintes propriedades ao objeto pokemon com base nos argumentos recebidos:
  - `nome`: Nome do Pokémon (string).
  - `tipo`: Tipo do Pokémon (string).
  - `nivel`: Nível do Pokémon (number).
  - `hp`: Pontos de vida do Pokémon (number).
4. Retorne o objeto pokemon preenchido.
5. Fora da função, chame `criarPokemon()` passando valores fictícios como argumentos e armazene o objeto resultante.
6. Exiba o objeto resultante no console.


Exemplo de criação da função e chamada:

```javascript
...

const meuPokemon = criarPokemon("Pikachu", "Elétrico", 25, 80);
console.log(meuPokemon);
```
Dica: 

- Use os argumentos passados para a função para preencher as propriedades do Pokémon.



Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
