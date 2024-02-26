---
layout: exercicio
numero: 24
nome: Calculando o faturamento
topicos: javascript, funções, argumentos variáveis
---

### Descrição:

Neste exercício, você terá que escrever uma função para calcular o faturamento de um dia de vendas de uma loja. 


Objetivo: Praticar o uso de funções que aceitam um número variável de compras, cada uma contendo itens com nome e valor, em JavaScript.

Instruções:

1. Você vai criar uma função que calcula o faturamento gerado por um conjunto de compras, onde cada compra possui vários `itens` com `nome` e `valor`.
2. Crie uma função chamada `calcularFaturamento` que aceita **qualquer quantidade de argumentos**, cada um representando uma compra.
3. Cada argumento (compra) deve ser um objeto contendo:
  - itens: Um array de objetos, onde cada objeto representa um item da compra e contém propriedades `nome` (string) e `valor` (number).
4. Dentro da função, faça o seguinte:
  - Para cada compra no array, calcule o gasto total somando os valores dos itens.
 - Retorne o gasto total calculado.
5. Teste a função chamando-a com diferentes compras e quantidades de argumentos e exiba o resultado.

Exemplo de uso da função:

```javascript
const compra1 = { itens: [
{ nome: "Camiseta", valor: 30 },
{ nome: "Calça", valor: 50 }
]}

const compra2 = { itens: [
{ nome: "Tênis", valor: 80 }
]}

const compra3 = { itens: [
{ nome: "Livro", valor: 20 },
{ nome: "Caneta", valor: 5 }
]}

const compra4 = { itens: [
{ nome: "Caderno", valor: 15 }
]}

const compra5 =   { itens: [
{ nome: "Lápis", valor: 2 }, 
{ nome: "Borracha", valor: 3 }
]}


const faturamento1 = calcularFaturamento(compra1, compra2)

const faturamento2 = calcularFaturamento(compra3, compra4, compra5)

console.log(`Faturamento 1: R$${gasto1}`);
console.log(`Faturamento 2: R$${gasto2}`);
```
Dica: 
- Existe mais de uma maneira de resolver esse problema. Que tal testar as duas?

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
