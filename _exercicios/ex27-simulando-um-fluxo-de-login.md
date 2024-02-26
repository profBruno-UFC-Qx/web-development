---
layout: exercicio
numero: 27
nome: Simulando um fluxo de login com promises
topicos: javascript, promises, assícronicidade
---

### Descrição:

Neste exercício, você irá praticar o uso de `promises` no contexto de um fluxo de autenticação de usuário.

Instruções:

1. Crie uma função chamada `verificarUsuario` que retorna uma Promise que simula a verificação de um nome de usuário.
  - Para simplificar a implementação a função deve resolver a `promise` quando o o nume de usuário informando for `sucesso@mail.com`, caso contrário a `promise` deve ser rejeitada.
2. Crie outra função chamada `verificarSenha` que retorna uma Promise que simula a verificação da senha.
  - Considere que a senha correta é 123456
3. Encadeie as Promises usando .then() para simular um fluxo de autenticação, onde a primeira Promise representa a verificação do nome de usuário e a segunda Promise representa a verificação da senha.
4. Use `.then()` e `.catch()`para lidar com o resultado do fluxo de autenticação.
5. Caso o usuário informe usuário e senha corretamente, imprima uma mensagem de sucesso no console.

Gostou? Não esqueça de avaliar o exercício:

<a class="btn" href="https://forms.gle/scs1VxDDFSiMqAhe8" target="_blank"> Abra o formulário de avaliação</a>
