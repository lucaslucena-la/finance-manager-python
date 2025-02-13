# Finance Manager - Python Puro

Um projeto simples para gerenciamento de contas bancárias em Python puro, utilizando **SQLModel** para banco de dados e **Matplotlib** para visualização financeira.


## 🚀 Funcionalidades

- 📌 **Gerenciamento de Contas**: Criar, listar e desativar contas bancárias.
- 🔄 **Transferências**: Realizar transferências entre contas.
- 💰 **Movimentações Financeiras**: Registrar entradas e saídas de dinheiro.
- 📊 **Análises e Relatórios**: Filtrar movimentações e gerar gráficos do saldo por conta.

## 🛠️ Tecnologias Utilizadas

- **Python 3** 🐍
- **SQLModel** (para banco de dados SQLite)
- **Matplotlib** (para gráficos financeiros)

## 📂 Estrutura do Projeto

📦 finance-manager-python
 ┣ 📜 models.py         # Definição das tabelas do banco de dados
 ┣ 📜 view.py           # Funções para manipulação de contas e movimentações
 ┣ 📜 interface.py      # Interface via terminal para interação do usuário
 ┣ 📜 README.md         # Documentação do projeto
 ┗ 📜 requirements.txt  # Dependências do projeto

## ⚙️ Como Executar o Projeto

### 1️⃣ Criar ambiente virtual

# Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\Activate

### 2️⃣ Instalar dependências

pip install -r requirements.txt

### 3️⃣ Criar o banco de dados

python models.py

### 4️⃣ Iniciar a aplicação

python templates.py

## 📈 Exemplo de Uso

Após rodar o **interface.py**, escolha as opções disponíveis:

1️⃣ Criar conta
2️⃣ Desativar conta
3️⃣ Transferir dinheiro
4️⃣ Movimentar dinheiro
5️⃣ Ver total de contas
6️⃣ Filtrar histórico
7️⃣ Gerar gráfico

