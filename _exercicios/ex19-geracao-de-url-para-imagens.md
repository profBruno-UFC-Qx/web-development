---
layout: exercicio
numero: 19
nome: Geração de URL para Imagens de Notícias
topicos: javascript, string, funções
---

### Descrição:

Neste exercício, você está desenvolvendo um sistema de gerenciamento de notícias e precisa criar uma função para gerar URLs amigáveis para as imagens relacionadas às notícias.

Instruções:

1. Crie uma função chamada gerarURLImagem que aceita um argumento `gerarURLImagem `(string) representando o título da notícia.
2. Dentro da função, realize as seguintes etapas para gerar a URL:
  - Remova espaços em branco extras, do início e do final do título.
  - Remova os caracteres especiais (à, á, â, ã, é, ê, è, e ó, õ) do título da notícia.
  - Converta o título da notícia para letras minúsculas.
  - Substitua os espaços restantes por hífens (-) para criar uma URL amigável.
3. Adicione a extensão ".jpg" ao final da URL.
4. Retorne a URL gerada.
5. Teste a função chamando-a com diferentes títulos de notícias e exiba o resultado.

Exemplo de uso da função:

```js
const titulo = "Grande Vitória na Final do Campeonato";
const urlImagem = gerarURLImagem(titulo);
console.log(`URL da imagem: ${urlImagem}`);

```

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
