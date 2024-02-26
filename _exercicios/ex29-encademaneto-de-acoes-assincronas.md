---
layout: exercicio
numero: 29
nome: Encadeamento de Ações Assíncronas
topicos: promises, API externa
---

### Descrição:

Neste exercício, você irá criar um script que dado o nome de um pokemon, ele recupera as informções de como ele pode ser encontrado.

O objetivo desse exercício é praticar o uso de Promises encadedas, ou seja, promises que dependem de outras promises.

Instruções:

1. Crie uma função chamada `acharPokemon` que deve receber o nome do pokemon como argumento
2. A função deve consultar a [PokeApi](http://pokeapi.co), mais especficamente, o endpoint *Pokemon*, por meio da seguinte URL:

```
https://pokeapi.co/api/v2/pokemon/{id or name}/
```
  - Utilize o nome do pokemon para customizar a URL
3. Ao recuperar a resposta, você receberá um JSON com diversas informações, dentre elas a *location_area_enconters*
  - Esta propriedade do JSON tem como valor uma segunda URL da que leva ao endpoint *Encouters* da PokeAPI
  - Usando outra promise, você deve consultar essa URL e deve trazer todos os `name` localizados dentro de cada objeto contindo no vetor `names` da resposta.
4. A função `acharPokemon` deve retorna o nome do pokemon e a lista de locais onde ele pode ser encontrado.
5. Para mais informações sobre os endpoints necessários acesse:
  - [https://pokeapi.co/docs/v2#pokemon](https://pokeapi.co/docs/v2#pokemon)
  - [https://pokeapi.co/docs/v2#encounters-section](https://pokeapi.co/docs/v2#encounters-section)

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
