---
layout: exercicio
numero: 26
nome: Programa de milhas
topicos: JavaScript, funcional
---

### Descrição:

Uma empresa de aviação tem um programa de fidelidade que premia seus clientes com milhas por cada voo que eles realizam. O cálculo de milhas é baseado na distância dos voos, e apenas voos de empresas parceiras são aceitos. Os voos nacionais rendem 1 milha para cada quilometro percorrida, enquanto os voos internacionais rendem o dobro de milhas para a mesma distância percorrida.

## Instruções:

Uma empresa de aviação tem um programa de fidelidade que premia seus clientes com milhas por cada voo que eles realizam. O cálculo de milhas é baseado na distância dos voos, e apenas voos de empresas parceiras são aceitos. 

Os voos nacionais rendem 1 milha para cada quilometro percorrida, enquanto os voos internacionais rendem o dobro de milhas para a mesma distância percorrida.

Escreva um programa que calcule o total de milhas ganhos por um cliente com base em uma lista de voos. Para isso siga as seguintes instruções:

1. Cria uma função chamada `calcularTotalDeMilhas` que deve receber um vetor contendo a lista de voos.
  - Cada voo possui os seguintes atributos
    - origem
    - destino
    - distância.
    - tipo (nacional ou internacional)
    - operadora
   - Veja o exemplo abaixo:

| Origem | Destino | Distância | Tipo | Operadora
|---|---|---|---|---|
| Rio de Janeiro | São Paulo| 400 | Nacional | AeroLink |
| São Paulo | Miami | 8000 | Internacional | SkyWings |
| São Paulo | Paris | 10000 | Internacional | Oceanic Airways |
| Belo Horizonte | Rio de Janeiro | 300 | Nacional | AeroLink |
| Miami | Nova York | 1200 | Nacional | JetStream |
| São Paulo | Belo Horizonte | 500 | Nacional | StarFly |
| Porto Alegre | Rio de janeiro | 800 | Nacional | AeroLink |
| Rio de Janeiro | Fortaleza | 2800 | Nacional | StarFly |
| Fortaleza | Lisboa | 6500 | Internacional | Oceanic Airways |
| Belo Horizonte | Salvador | 900 | Nacional | StarFly |
| Paris | Londres | 300 | Internacional | AeroLink |
| Londres | Nova York | 3500 | Internacional | Pacific Air |
| São Paulo | Lisboa | 7000 | Internacional | SkyWings |
| Belo Horizonte | São Paulo | 500 | Nacional | AeroLink |
| Rio de Janeiro | Recife | 2600 | Nacional | Oceanic Airways |
| Recife | Madri | 5900 | Internacional | SkyWings |
| São Paulo | Rio de Janeiro | 400 | Nacional | StarFly |
| Rio de Janeiro | Brasília | 400 | Nacional | StarFly |
| Brasília | Nova York | 5500 | Internacional | StarFly |
| São Paulo | Brasília | 900 | Nacional | SkyWings |

2. A função deve retornar um objeto com as seguintes informações:
```js
  {
    nacionais: // Número de voos nacionais realizados
    internacionais: // Número de voos internacionais realizados
    invalidos: // Número de voos realizados por empresas não parceiras
    milhasAcumuladas: //Total de milhas acumuladas
  }
```
3. Considere que as operadoreas **JetStream** e **Pacific Air** <mark>NÃO</mark> são parceiras do programa de fidelidade.



Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
