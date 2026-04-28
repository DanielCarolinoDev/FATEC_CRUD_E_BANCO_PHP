# FATEC_CRUD_E_BANCO_PHP

## Descrição
Este projeto foi desenvolvido como parte da disciplina da FATEC e tem como objetivo demonstrar a implementação completa de um CRUD (Create, Read, Update, Delete) utilizando PHP com integração a banco de dados.

O diferencial do projeto é a aplicação de três formas de conexão com banco:
- Procedural (MySQLi)
- Orientado a Objetos (MySQLi OO)
- PDO (PHP Data Objects)

---

## Objetivo
Apresentar diferentes abordagens de conexão com banco de dados em PHP e aplicar operações CRUD de forma prática.

---

## Funcionalidades
- Inserção de registros (Create)
- Listagem de dados (Read)
- Atualização de registros (Update)
- Exclusão de registros (Delete)
- Conexão com banco em:
  - Procedural
  - Orientado a Objetos
  - PDO

---

## Tecnologias Utilizadas
- PHP
- MySQL
- HTML
- CSS (opcional)

---

## Estrutura do Projeto
/projeto
│── index.php              # Página principal
│── create.php             # Inserção de dados
│── read.php               # Listagem de dados
│── update.php             # Atualização
│── delete.php             # Exclusão
│── conexao_procedural.php # Conexão procedural
│── conexao_oo.php         # Conexão orientada a objetos
│── conexao_pdo.php        # Conexão com PDO

---

## Conexões com Banco

### Procedural (MySQLi)
Utiliza funções diretas como mysqli_connect para conexão simples.

### Orientado a Objetos (MySQLi OO)
Utiliza a classe mysqli com métodos e propriedades.

### PDO
Utiliza PDO para maior segurança e flexibilidade, com suporte a prepared statements.

---

## Segurança
- Uso de prepared statements (PDO)
- Validação de entrada de dados
- Evita SQL Injection

---

## Como Executar
1. Instale um servidor local (XAMPP, WAMP ou Laragon)
2. Crie um banco de dados no MySQL
3. Configure os dados de conexão nos arquivos
4. Coloque o projeto na pasta htdocs
5. Inicie Apache e MySQL
6. Acesse: http://localhost/nome-do-projeto

---

## Conceitos Aplicados
- CRUD em PHP
- Conexão com banco de dados
- Programação Orientada a Objetos
- Segurança em aplicações web

---

## Autor
Daniel Carolino
Estudante de Desenvolvimento de Software Multiplataforma – FATEC
