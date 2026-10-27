# HelpdeskApp

Sistema web de suporte e gerenciamento de chamados desenvolvido em PHP.

## Sobre o Projeto

O HelpdeskApp é uma aplicação voltada para o controle e acompanhamento de chamados de suporte técnico. O sistema conta com controle de autenticação de usuários, abertura de novos chamados, consulta de solicitações registradas e painel administrativo.

## Funcionalidades

* Autenticação e validação de usuários.
* Tela principal (Home) com acesso rápido às opções do sistema.
* Formulário para abertura de novos chamados de suporte.
* Módulo de consulta e listagem de chamados cadastrados.
* Sistema de encerramento de sessão (Logoff).

## Estrutura do Projeto

* `index.php`: Página de login do sistema.
* `valida_login.php`: Script responsável por autenticar o usuário.
* `home.php`: Painel principal após o login.
* `abrir_chamado.php`: Interface para criar um novo chamado.
* `registrar_chamado.php`: Processa o salvamento do chamado.
* `consultar_chamado.php`: Exibe os chamados registrados.
* `logoff.php`: Encerra a sessão ativa do usuário.

## Como Executar

1. Certifique-se de ter um ambiente de servidor local configurado com suporte a PHP (como XAMPP, WampServer ou Docker).
2. Clone este repositório ou faça o download dos arquivos no diretório raiz do seu servidor web (ex: `htdocs` ou `www`).
3. Acesse o projeto através do seu navegador no endereço local correspondente (ex: `http://localhost/HelpdeskApp/index.php`).


