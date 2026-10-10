# API de Gestão Escolar

API desenvolvida em Python durante uma **imersão de DevOps promovida pela Alura**, com foco na organização de informações de uma instituição de ensino.

O projeto utiliza FastAPI para disponibilizar endpoints de gerenciamento escolar e SQLAlchemy para interação com o banco de dados configurado na aplicação.

## Funcionalidades

- Rotas para gerenciamento de alunos.
- Rotas para gerenciamento de cursos.
- Rotas para gerenciamento de matrículas.
- Documentação interativa da API gerada pelo FastAPI.

## Tecnologias

- **Python**
- **FastAPI** — criação dos endpoints e documentação da API.
- **SQLAlchemy** — camada de acesso a dados.
- **Banco de dados** — conforme configuração do projeto.

## Como executar localmente

Os passos abaixo são uma orientação geral. Confira os arquivos do repositório para identificar as dependências e as variáveis de ambiente exigidas pela versão atual.

### 1. Criar um ambiente virtual

```bash
python -m venv .venv
```

Ative o ambiente virtual:

**Linux/macOS**
```bash
source .venv/bin/activate
```

**Windows (PowerShell)**
```powershell
.venv\Scripts\Activate.ps1
```

### 2. Instalar as dependências

Se o repositório possuir um arquivo `requirements.txt`, execute:

```bash
python -m pip install -r requirements.txt
```

Caso as dependências sejam gerenciadas de outra forma, siga as instruções correspondentes do projeto.

### 3. Iniciar a API

O ponto de entrada identificado é `app.py`. Depois de instalar as dependências e configurar o banco de dados, inicie o servidor com:

```bash
uvicorn app:app --reload
```

Se necessário, instale o Uvicorn conforme as dependências do projeto.

### 4. Acessar a documentação

Com o servidor em execução, abra:

- **Documentação Swagger:** [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
- **Documentação alternativa:** [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

Esses endereços são locais e só ficam disponíveis enquanto a aplicação estiver em execução.

## Contexto acadêmico

Projeto realizado como atividade prática durante uma **imersão de DevOps da Alura**. A proposta permitiu trabalhar com uma API em Python, organização de endpoints e integração com uma camada de persistência.

## Autor

**Jhonathan Fernandes** — [GitHub](https://github.com/JhonathanFernandes)

---

> Este README resume a estrutura identificada no projeto. Para confirmar os detalhes de banco de dados, dependências e configuração, consulte os arquivos de código e configuração do repositório.