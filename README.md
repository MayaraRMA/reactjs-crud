# reactjs-crud

## Funcionalidades da aplicação


- **Listar os pratos de comida da sua API:** a página Dashboard deve ser capaz de exibir uma listagem, com o campo title, value, e description e available de todos os pratos de comida que estão cadastrados na sua API.

- **Adicionar novos pratos de comida a sua API:** a página Dashboard abre um modal ao clicar no botão Novo Prato no Header. Esse modal deve ser responsável por cadastrar uma nova food passando os campos image, name, description, value.

- **Editar pratos de comida da sua API:** a Dashboard abre um modal ao clicar no botão Editar Prato. Esse modal deve ser responsável por editar uma food passando os campos image, name, description, value.
Dica: Ao editar um item, quando for envia-lo para o backend, lembre de copiar os dados anteriores como o available e o id, ou eles serão perdidos do seu arquivo server.json.

- **Remover pratos de comida da sua API:** a página Dashboard remove um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- **Alterar disponibilidade dos pratos de comida da sua API:** a página Dashboard altera a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de available.

## testes:

- **should be able to list all the food plates from your api:** a aplicação deve permitir que sejam listados, toda os pratos de comidas que são retornadas da sua fake API.

- **should be able to add a new food plate:** um prato de comida deve ser adicionado a sua api, adicionando-o também à listagem.

- **should be able to edit a food plate:** um prato de comida deve ser editado na sua api, editando-o também na listagem.

- **should be able to remove a food plate:** um prato de comida deve ser removido da sua api, removendo-o também da listagem.

- **should be able to update the availibility of a food plate:** a dashboard deve permitir que o status do prato de comida seja alterado entre Disponível e Indisponível;
