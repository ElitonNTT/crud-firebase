CRUD com Next.js, TypeScript, Tailwind CSS e Firebase

Este é um projeto de CRUD simples que utiliza as tecnologias Next.js, TypeScript, Tailwind CSS e Firebase. O aplicativo permite a criação, leitura, atualização e exclusão de clientes em um banco de dados Firebase.

Como rodar o projeto?
Clone o repositório usando o comando git clone.

Na pasta raiz do projeto, execute o comando npm install para instalar as dependências.

Em seguida, execute o comando npm run dev para iniciar o servidor de desenvolvimento.

Abra o seu navegador e navegue até http://localhost:3000 para visualizar a aplicação.

É necessário criar banco de dados Firebase e passar as informações geradas dentro do arquivo src/backend/config.ts.

  "apiKey, authDomain e projectId."


Funcionalidades:

O aplicativo de CRUD permite ao usuário:

Adicionar um novo cliente, informando o nome e a idade.

Visualizar uma lista de clientes cadastrados, mostrando o ID, nome e idade de cada um.

Editar as informações de um cliente existente.

Excluir um cliente existente.


Algumas melhorias que podem ser implementadas no projeto incluem:

Adição de validação de campos para garantir que os dados inseridos pelo usuário são válidos.

Melhorias no design da página, como a adição de animações e transições.

Adição de uma mensagem de erro ou sucesso quando o usuário cria, edita ou exclui um cliente.