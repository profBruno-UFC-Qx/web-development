---
layout: exercicio
numero: 25
nome: Aquele desconto que todo mundo gosta
topicos: javascript, funções, vetor
---

### Descrição:

Neste exercício, considere que você foi contratado para criar um sistema que calcula o total de desconto com base na categoria de itens comprados.

Instruções:

1. Crie uma função chamada `calcularDesconto` que aceita um vetor `itensComprados` como argumento. Cada item no vetor é representado por um objeto com as seguintes propriedades:
  - nome: Nome do item (string).
  - valor: Valor do item (number).
  - categoria: Categoria do item (string).
2. Dentro da função, faça o seguinte:
  - Crie um objeto chamado `categoriasDescont` que mapeia as categorias para as porcentagens de desconto correspondentes. Considere as seguintes categorias:

```javascript
const categoriasDesconto = {
  "eletronicos": 0.1,   // 10% de desconto
  "vestuario": 0.2,     // 20% de desconto
  "alimentos": 0.15,    // 15% de desconto
  "livros": 0.12,       // 12% de desconto
}
```

  - Inicialize uma variável chamada totalDesconto como 0.
  - Percorra o vetor `itensComprados` usando um loop e, para cada item, adicione o desconto apropriado com base na categoria.
  - Some os valores de desconto a `totalDesconto`.
3. Retorne o valor total de desconto calculado.
4. Teste a função chamando-a com diferentes vetores de itens comprados e exiba o total de desconto.

Exemplo de uso da função:

```javascript
const itensComprados = [
  { nome: "Smartphone", valor: 1000, categoria: "eletronicos" },
  { nome: "Camiseta", valor: 50, categoria: "vestuario" },
  { nome: "Fones de Ouvido", valor: 150, categoria: "eletronicos" },
  { nome: "Chocolate", valor: 5, categoria: "alimentos" },
  { nome: "Livro", valor: 30, categoria: "livros" }
];
const totalDesconto = calcularDescontoPorCategoria(itensComprados);
console.log(`Total de desconto: R$${totalDesconto.toFixed(2)}`);
```

Dica: Use o objeto `categoriasDesconto` para acessar a porcentagem de desconto com base na categoria de cada item.

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
