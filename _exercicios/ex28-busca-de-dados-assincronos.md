---
layout: exercicio
numero: 28
nome: Temperatura atual
topicos: Promises, API externa
---

### Descrição:

Neste exercício, você irá utilizar uma API pública de informações climáticas para recuperar a temperatura atual de uma cidade brasileira qualquer.

Objetivo deste exercício, é a pratica do uso de Promises para buscar dados de uma API externa e manipulá-los.

Instruções:

1. Iremos utilizar a API do [Open Meteo](https://open-meteo.com/). Mais especificamente iremos requisitar a seguinte URL:

```
https://api.open-meteo.com/v1/forecast?latitude=${LATITUDE}&longitude=${LONGITUDE}&current_weather=true
```
  - Desta forma será necessário passar dois parâmtros para nesta URL, a latitude e a longitude da cidade que você quer verificar o tempo.
  - Exemplo, para verificar o clima atual em Fortaleza devemos fazer a seguinte requisição:
```
https://api.open-meteo.com/v1/forecast?latitude=-3.7275&longitude=-38.4767&current_weather=true
```
  - Você pode encontrar a latitude e longitude das principais cidades do país no site [simplemaps.com](https://simplemaps.com/data/br-cities)
2. Crie uma função chamada buscarDados que aceite a latitude e a longitude de uma cidade como argumento e retorne uma Promise.
3. Dentro da Promise, faça uma solicitação GET assíncrona para a API usando a função fetch().
4. Resolva a Promise com os dados retornados após a resposta da API ser convertida para JSON.
5. Manipule os dados retornados para exibir informações relevantes, como a temperatura.
6. Trate os possíveis erros, como falha na conexão com a API.

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
