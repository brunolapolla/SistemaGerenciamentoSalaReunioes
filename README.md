# SistemaGerenciamentoSalaReunioes
Live Coding Desenvolvimento de um Sistema de Gerenciamento de Sala de Reuniões

Códigos desenvolvidos em treinamento da plataforma de ensino da Digital Innovation One, ministrado por [Kamila Santos](https://www.linkedin.com/in/kamila-santos-oliveira/ "Kamila Santos") desenvolvedora backend em [Ame Digital](https://www.linkedin.com/company/ame-digital/ "Ame Digital").
Esse repositório é dividido em duas pastas compactadas, uma contém o backend da aplicação e a outra o frontend.

Baixar as pastas backend e frontend compactadas ou clonar o projeto no link/:
https://github.com/brunolapolla/SistemaGerenciamentoSalaReunioes.git


------------



**Orientações para o Backend:**

localhost:8080

Stacks utilizada:
Spring Web
Spring Data JPA
H2 Database
Java 8
Maven


Endpoints criados na API
Criar sala de reuniao POST - /api/v1/rooms

Listar todas as salas GET - /api/v1/rooms

Buscar uma sala pelo Id GET - /api/v1/rooms/{id}

Atualizar uma sala pelo Id PUT - /api/v1/rooms/{id}

Excluir uma sala pelo id DELETE - /api/v1/rooms/{Id}


------------



**Orientações para o Frontend:**

Instalar NodeJS a partir da versão 12

Instalar Gerenciador de Dependências NPM na pasta client-room
npm init

Instalar as dependencias na pasta client-room com os comandos
npm install -g @angular/cli@9.0.0-rc.7

npm install bootstrap jquery --save

Criar projeto na pasta Angular
ng new client-room

Execute o frontend:
com o comando ng serve

Porta -> localhost:4200

**Listar salas de reuniões**
![Listar salas de reuniões](https://github.com/brunolapolla/SistemaGerenciamentoSalaReunioes/blob/master/Listar%20salas%20de%20reuni%C3%B5es.jpg)

**Cadastrar salas de reuniões**
![Cadastrar salas de reuniões](https://github.com/brunolapolla/SistemaGerenciamentoSalaReunioes/blob/master/Cadastrar%20salas%20de%20reuni%C3%B5es.jpg)

**Atualizar salas de reuniões**
![Atualizar salas de reuniões](https://github.com/brunolapolla/SistemaGerenciamentoSalaReunioes/blob/master/Atualizar%20salas%20de%20reuni%C3%B5es.jpg)

**Detalhes das salas de reuniões**
![Detalhes salas de reuniões](https://github.com/brunolapolla/SistemaGerenciamentoSalaReunioes/blob/master/Detalhes%20salas%20de%20reuni%C3%B5es.jpg)
