
# PicPay Simplificado - Teste Técnico

Este projeto é uma aplicação Django que implementa funcionalidades simplificadas de um sistema de pagamento, similar ao PicPay. O objetivo é fornecer uma solução técnica para gerenciar transações e usuários.

## Funcionalidades

- Registro e autenticação de usuários.
- Processamento de pagamentos e transações.
- API para realizar operações de pagamento.

## Requisitos

- Python 3.9+
- Django 3.2+
- Banco de dados SQLite (ou outro configurável no `settings.py`)

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/picpay-simplificado.git
   cd picpay-simplificado
   ```

2. Crie um ambiente virtual e ative-o:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute as migrações do banco de dados:

   ```bash
   python manage.py migrate
   ```

5. Inicie o servidor:

   ```bash
   python manage.py runserver
   ```

## Estrutura do Projeto

- `core/`: Configurações principais do Django (settings, urls, etc.).
- `payments/`: Lógica da aplicação de pagamentos (modelos, APIs, e tarefas).

## Testes

Para rodar os testes automatizados:

```bash
python manage.py test
```
