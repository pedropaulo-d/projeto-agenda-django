# Agenda de Contatos com Django

Este é um projeto simples de uma agenda de contatos desenvolvido em Python 3.11.0 e Django 4.2.6. O objetivo deste projeto é demonstrar minhas habilidades em desenvolvimento web com o Django e fornecer uma amostra do meu trabalho para o meu portfólio.

## Funcionalidades

- Registro e autenticação de usuários.
- Criação, visualização, edição e exclusão de contatos.
- Cada contato possui os seguintes campos:
  - Nome
  - Sobrenome
  - Email
  - Número de telefone
  - Endereço
  - Data de criação
  - Foto de perfil
- Pesquisa de contatos por nome.
- Paginação de contatos na lista.
- Interface amigável e responsiva.

## Pré-requisitos
- Certifique-se de ter o Python 3.11.0 instalado em seu sistema. Você também pode usar um ambiente virtual para isolar as dependências do projeto.
```
pip install virtualenv
python -m venv venv
source venv/bin/activate  # No Windows, use 'venv\Scripts\activate'
```
- Eu utilizei um script usando a biblioteca Faker para gerar contatos aleátorios para poder desenvolver o projeto.

## Configuração

1. Clone este repositório para o seu ambiente de desenvolvimento:

`git clone https://github.com/seu-usuario/nome-do-repositorio.git`

2. Acesse o diretório do projeto:

`cd nome-do-repositorio`

3. Configure o banco de dados e aplique as migrações:

`python manage.py migrate`

4. Crie um superusuário para acessar o painel de administração:

`python manage.py createsuperuser`

5. Inicie o servidor de desenvolvimento:

`python manage.py runserver`

- Agora você pode acessar a aplicação em http://localhost:8000/ e fazer login com o superusuário que você criou.

## Uso
Após a configuração, você pode acessar a aplicação e começar a usar a agenda de contatos. Você pode criar, visualizar, editar e excluir contatos, bem como realizar pesquisas por nome. O painel de administração está disponível em http://localhost:8000/admin/ para gerenciar os dados de forma mais avançada.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter mais detalhes.


