# ToDo List
Projeto de criação de API, bootcamp realizado pela Rocketseat.

## Tecnologias e Software utilizadas
[![My Skills](https://skillicons.dev/icons?i=postman,java,spring,maven&perline=6)](https://skillicons.dev)

## URL da aplicação no Render:
https://todolist-java-ljy7.onrender.com

## Requests desenvolvidas:

### POST:
Adição de usuários *(URL/users/)*: também com a validação de trazer uma resposta de um existente. A senha que retorna criptografada, reforçando a segurança de dados do usuário.

Adição de tarefas *(URL/tasks/)*: com a funcionalidade de validação de datas, tais como, não adicionar para iniciar no passado, e a data inicial deve ser menor que a data final. O título possui um limite de 50 caracteres, passado disso, impedirá o cadastro.

### GET:
Lista de tarefas *(URL/tasks/)*, usando a autenticação do usuário e senha, então a API retorna com a lista exclusivamente do usuário cadastrado.

### PUT:
Alteração de tarefas *(URL/tasks/id)*: permitindo solicitar edição a partir ID da tarefa existente, podemos tanto alterar um item, como todos. Este também possui validação de que nenhum outro usuário teria permissão para realizar essa requisição.
