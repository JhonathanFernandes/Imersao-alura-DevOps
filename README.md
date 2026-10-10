# API de Gestão Escolar

API desenvolvida durante uma atividade de imersão, com foco na organização de informações de uma instituição de ensino.

## Funcionalidades identificadas

- Rotas para gerenciamento de alunos.
- Rotas para gerenciamento de cursos.
- Rotas para gerenciamento de matrículas.
- Documentação de API gerada pelo FastAPI.

## Tecnologias

- Python
- FastAPI
- SQLAlchemy
- Banco de dados configurado pelo projeto

## Como executar

Os comandos exatos dependem das dependências e das variáveis de ambiente configuradas no projeto. Em um ambiente Python, crie e ative um ambiente virtual e instale as dependências declaradas pelo repositório, caso exista um arquivo `requirements.txt`.

Exemplo de criação de ambiente virtual:

```bash
python -m venv .venv
```

Ative o ambiente virtual e instale as dependências do projeto antes de iniciar a aplicação.

O ponto de entrada identificado é `app.py`. Com as dependências e a configuração do banco prontas, a API pode ser iniciada com:

```bash
uvicorn app:app --reload
```

A documentação interativa do FastAPI normalmente fica disponível em `/docs` enquanto o servidor está em execução.

## Observação

Este README descreve a estrutura identificada no código. Os detalhes de instalação e configuração do banco devem ser confirmados com os arquivos de dependências e configuração do projeto.

## Autor

Jhonathan Fernandes — [GitHub](https://github.com/JhonathanFernandes)
