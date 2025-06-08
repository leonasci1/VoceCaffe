La Voce Caffe ☕
Uma aplicação web completa para gestão de cardápio, desenvolvida com Java e Spring Boot. O projeto permite visualizar, adicionar, editar e apagar itens de um cardápio de café, demonstrando um fluxo CRUD completo com uma arquitetura de software profissional.

✨ Funcionalidades
Visualização de Cardápio: Lista todos os cafés disponíveis a partir de um banco de dados MySQL.

Adicionar Novo Café: Formulário para inserir novos itens no cardápio.

Editar Café Existente: Permite alterar o nome, descrição e preço de qualquer item.

Apagar Café: Remove itens do cardápio de forma permanente.

🎥 Demo em Ação
(Dica: Grave um GIF rápido da sua tela usando uma ferramenta como o ScreenToGIF ou o LICEcap e adicione-o aqui. É a melhor forma de mostrar o projeto a funcionar!)

🚀 Tecnologias Utilizadas
Backend: Java 21, Spring Boot 3, Spring Data JPA, Hibernate

Frontend: Thymeleaf, HTML5, CSS3

Banco de Dados: MySQL 8

Gestão de Dependências: Maven

Ambiente de Execução: Docker (com Docker Compose)

🛠️ Como Executar o Projeto Localmente
Pré-requisitos:

Java 21 (ou superior)

Maven 3.8+

Docker e Docker Compose

Passos:

Clone o repositório:

git clone <url-do-seu-repositorio>
cd VoceCaffe

Inicie o Banco de Dados com Docker:
O projeto inclui um ficheiro docker-compose.yml que sobe um contentor MySQL já configurado.

docker-compose up -d

Isto irá iniciar o banco de dados em segundo plano.

Execute a Aplicação Spring Boot:
Use o Maven para compilar e iniciar a aplicação.

mvn spring-boot:run

Acesse a aplicação:
Abra o seu navegador e vá para http://localhost:8080.

🏛️ Arquitetura do Software
O projeto segue uma arquitetura em camadas para separar as responsabilidades:

Controller: Recebe as requisições HTTP e direciona o fluxo.

Service: Contém a lógica de negócio da aplicação.

Repository: Camada de acesso a dados, que comunica com o banco de dados via Spring Data JPA.

Domain/Model: Representa as entidades do nosso sistema (neste caso, a classe Cafe).

Este projeto foi desenvolvido como um exercício prático para solidificar conceitos de desenvolvimento web com o ecossistema Spring.
