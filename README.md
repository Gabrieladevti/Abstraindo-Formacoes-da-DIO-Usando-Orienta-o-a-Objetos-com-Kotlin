# Abstraindo Formações da DIO com Kotlin

Este projeto tem como objetivo demonstrar como utilizar os conceitos de Orientação a Objetos (OO) em Kotlin para abstrair formações oferecidas pela plataforma DIO (Digital Innovation One). O foco é a aplicação prática de classes, objetos, herança, polimorfismo e encapsulamento para organizar e representar os dados das formações de maneira eficiente.

## Funcionalidades

- **Criação de classes** para representar cursos, usuários e outras entidades relacionadas às formações.
- **Utilização de herança** para estender funcionalidades de cursos e usuários.
- **Aplicação de polimorfismo** para personalizar comportamentos de diferentes tipos de cursos.
- **Encapsulamento** para garantir o acesso controlado aos dados dos cursos e usuários.
- **Estrutura de dados** para armazenar as formações e possibilitar o filtro, atualização e exibição de informações.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem de programação utilizada para implementar a solução.
- **Orientação a Objetos**: Paradigma de programação utilizado para organizar o código e promover reutilização e manutenção.

## Estrutura do Projeto

O projeto é composto por:

- **Classe Curso**: Representa um curso, com atributos como título, descrição e carga horária.
- **Classe Usuário**: Representa um usuário da plataforma, com atributos como nome, email e lista de cursos matriculados.
- **Classe Formação**: Abstração de uma formação que pode ser composta por um ou mais cursos.
- **Classe Principal**: Realiza a interação com o usuário e executa as ações de manipulação dos cursos e formações.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/Abstraindo-Formacoes-DIO-Kotlin.git
   2. Abra o projeto em sua IDE preferida (exemplo: IntelliJ IDEA, Android Studio).


3. Compile e execute o projeto.


4. No terminal ou na interface, você poderá visualizar os cursos e usuários cadastrados, além de realizar manipulações como adicionar novos cursos e usuários.



Exemplos de Uso

Criar um novo curso:

val curso = Curso("Kotlin Básico", "Introdução ao Kotlin", 40)

Criar um novo usuário e matricular em um curso:

val usuario = Usuario("João", "joao@dominio.com")
usuario.matricularCurso(curso)

Listar cursos de um usuário:

usuario.listarCursos()


Contribuições

Se você deseja contribuir com este projeto, siga os seguintes passos:

1. Faça um fork deste repositório.


2. Crie uma branch para sua feature (git checkout -b minha-feature).


3. Realize as alterações desejadas.


4. Commit suas mudanças (git commit -am 'Adicionando nova feature').


5. Envie para o repositório remoto (git push origin minha-feature).


6. Abra um pull request.
