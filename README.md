﻿# Hangar Challenge

Este é um projeto desenvolvido para o desafio proposto pela Hangar Digital. Consiste em uma página web que lista todos os pedidos em um formato de tabela, como um relatório, com cores de fundo alternadas para facilitar a leitura. Além disso, inclui um botão de impressão para gerar uma versão em papel do relatório.

## Funcionalidades

- Lista todos os pedidos em uma tabela.
- Alternância de cores de fundo para facilitar a leitura.
- Botão de impressão para gerar uma versão impressa do relatório.

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter os seguintes requisitos instalados:

- Servidor web (por exemplo, Apache, Nginx) configurado.
- PHP instalado.
- Banco de dados MySQL.

## Instalação

1. Clone o repositório para o diretório do seu servidor web:

2. Importe o banco de dados incluído (`database.sql`) para o seu servidor MySQL.

3. Configure as credenciais do banco de dados em `db_connection.php`.

4. Inicie o servidor web.

## Uso

1. Acesse a página do projeto através do navegador web.

2. A tabela listará automaticamente todos os pedidos disponíveis.

3. Clique no botão "Imprimir" para gerar uma versão impressa do relatório.

## Estrutura do Projeto

- `index.php`: Página principal que exibe a tabela de pedidos.
- `fetch_data.php`: Script PHP para buscar dados do banco de dados e preencher a tabela.
- `db_connection.php`: Arquivo de configuração para conexão com o banco de dados.
- `styles.css`: Folha de estilos para estilizar a página.
- `print-icon.png`: Ícone do botão de impressão.
- `database.sql`: Arquivo SQL para importar a estrutura do banco de dados.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).

