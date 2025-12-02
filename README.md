# Sistema de Agendamento para Salão de Beleza

![Badge Status](https://img.shields.io/badge/Status-Finalizado%20(Projeto%20Legado)-orange)

## ⚠️ Nota sobre o Contexto do Projeto

**Este foi um dos primeiros projetos que desenvolvi no início da minha jornada como programador.**

Ele foi criado originalmente para um **processo seletivo**, representando o conhecimento técnico que eu possuía na época (iniciante). Mantenho este repositório público para demonstrar minha evolução técnica e transparência sobre meu aprendizado.

> 💡 **Para ver meus projetos mais atuais, com arquiteturas mais robustas e melhores práticas (Clean Code, Patterns, etc.), convido você a visitar a página principal do meu perfil.**

---

## 💻 Sobre o Projeto

Este é uma aplicação web desenvolvida em **PHP Puro (Vanilla)** para gerenciar agendamentos de um salão de beleza. O sistema permite que clientes se cadastrem, façam login e agendem horários, enquanto administradores podem gerenciar esses agendamentos.

### Funcionalidades Principais

* **Autenticação:** Sistema de Login e Cadastro de usuários.
* **Agendamento:** Formulário para seleção de data, horário e serviço.
* **Gestão do Usuário:** O cliente pode visualizar seus agendamentos ("Meus Agendamentos"), editar ou cancelar.
* **Painel Administrativo:** Área restrita para visualização, edição e exclusão de todos os agendamentos do sistema.

## 📸 Screenshots

| Tela Inicial | Tela de Agendamento |
|:---:|:---:|
| <img src="/fotos/inicio.jpg" width="400"> | <img src="agendar.jpg" width="400"> |

| Tela de Login | Tela de Cadastro |
|:---:|:---:|
| <img src="login.jpg" width="400"> | <img src="cadastro.jpg" width="400"> |

## 🛠️ Tecnologias Utilizadas

Na época, o foco era entender os fundamentos da web sem o uso de frameworks complexos no back-end:

* **Back-end:** PHP (Estrutural/Procedural)
* **Banco de Dados:** MySQL
* **Front-end:** HTML5, CSS3, JavaScript
* **Estilização:** Bootstrap 5 (para responsividade e componentes visuais)

## 🚀 Como Executar o Projeto

Como este é um projeto legado em PHP simples, você precisará de um servidor local como XAMPP, WAMP ou Docker com PHP/Apache.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/agendamento-salao.git](https://github.com/seu-usuario/agendamento-salao.git)
    ```
2.  **Banco de Dados:**
    * Crie um banco de dados no MySQL (ex: `salao_db`).
    * Importe o arquivo `database/users.sql` para criar as tabelas necessárias.
3.  **Configuração:**
    * Verifique o arquivo `database/conexao.php` e ajuste as credenciais (usuário/senha) do seu banco de dados local, se necessário.
4.  **Execução:**
    * Coloque a pasta do projeto no diretório do seu servidor (ex: `htdocs` no XAMPP).
    * Acesse via navegador: `http://localhost/agendamento-salao/views/index.php`

---

Desenvolvido por [Seu Nome] - [Link para seu LinkedIn]
