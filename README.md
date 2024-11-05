# Estudo de Caso: Sistema de Gerenciamento de Conteúdo Digital - BookStream

## Descrição do Problema

A **BookStream** é uma empresa inovadora que deseja criar um sistema para gerenciar empréstimos de livros digitais (e-books) e audiolivros. O objetivo é permitir que os usuários acessem e façam streaming de conteúdo após realizarem cadastro e adquirirem uma assinatura. Inspirada em plataformas de streaming de vídeo, a BookStream busca mudar a maneira de acessar os livros.

## Objetivos de Aprendizagem

Com este estudo de caso, os alunos deverão ser capazes de:

1. **Analisar Requisitos**  
   - Realizar uma entrevista com o cliente utilizando um questionário preexistente para identificar as funcionalidades esperadas pela BookStream.

2. **Modelar Banco de Dados**  
   - Desenvolver as modelagens de banco de dados nas etapas:
     - **Modelo Conceitual:** Identificar as entidades, atributos e relacionamentos fundamentais.
     - **Modelo Lógico:** Estruturar o modelo com as relações e chaves.
     - **Modelo Físico:** Implementar o banco de dados, considerando as tecnologias e otimizações necessárias para o BookStream.

---

## Solução

- Perguntas para o levantamento de Requisitos
1. Quais informações precisam ser armazenadas sobre os usuários?
   
   Resposta: Precisamos armazenar o nome, e-mail, senha, data de nascimento, endereço e o status da assinatura (ativa ou inativa).

2. Como funcionará o sistema de assinatura dos usuários?

   Resposta: Os usuários precisarão adquirir uma assinatura mensal ou anual para ter acesso ao conteúdo. A assinatura será renovada automaticamente, e o sistema deve controlar a validade da assinatura.

3. Quantos dispositivos podem acessar o conteúdo ao mesmo tempo com uma única assinatura?

   Resposta: No momento, cada usuário pode acessar o conteúdo em apenas um único dispositivo ao mesmo tempo.

4. Há alguma limitação quanto ao número de conteúdos que um usuário pode acessar por vez?

   Resposta: Não há limite para o número de conteúdos, desde que seja dentro dos dispositivos permitidos e que o usuário possua uma assinatura ativa.


#### Autor

[![LinkedIn](https://img.shields.io/badge/LinkedIn-fernandoleonid-blue?logo=linkedin)](https://www.linkedin.com/in/fernandoleonid)
