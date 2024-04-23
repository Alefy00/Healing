# Sistema de Agendamento de Consultas

Este é um sistema de agendamento de consultas desenvolvido em Python utilizando o framework Django.

## Propósito

O sistema tem como objetivo facilitar o agendamento de consultas médicas, permitindo que pacientes façam agendamentos online e que os profissionais de saúde gerenciem suas agendas de forma eficiente.

## Funcionalidades

- Cadastro de pacientes, médicos e consultas.
- Agendamento de consultas por pacientes.
- Visualização e gerenciamento de agendas por parte dos médicos.
- Notificações de lembrete de consulta para pacientes e médicos.

## Requisitos

- Python 3.x
- Django
- Banco de dados suportado pelo Django (por exemplo, SQLite, PostgreSQL)

## Instalação e Configuração

1. Clone este repositório:

git clone https://github.com/Alefy00/Healing.git

2. Instale as dependências:

Django
Pillow


3. Execute as migrações do banco de dados:

python manage.py migrate

4. Inicie o servidor:

python manage.py runserver


5. Acesse o sistema em `http://localhost:8000`.

## Uso

1. Faça login como paciente ou médico.
2. Para pacientes: agende sua consulta escolhendo um médico disponível e um horário conveniente.
3. Para médicos: gerencie sua agenda, visualize os agendamentos e confirme as consultas.


## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues relatando problemas ou sugestões de melhorias.

