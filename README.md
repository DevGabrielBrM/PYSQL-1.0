# PYSQL 1.0 - Aplicação CRUD de Clientes

Bem-vindo ao PYSQL 1.0, uma aplicação de gerenciamento de clientes desenvolvida em Python. Esta aplicação permite a você criar, ler, atualizar e deletar (CRUD) registros de clientes utilizando uma interface gráfica simples e um banco de dados SQLite.

## 📋 Visão Geral

O PYSQL 1.0 é um projeto que demonstra como construir uma aplicação CRUD usando Python com a biblioteca Tkinter para a interface gráfica e SQLite para o banco de dados. O projeto é dividido em quatro etapas principais:

1. **Modelagem na Prática**
2. **Backend**
3. **Integração Backend e Frontend**
4. **Compilação para Distribuição**

## 🚀 Funcionalidades

- **Criar**: Adicionar novos clientes ao banco de dados.
- **Ler**: Visualizar todos os clientes ou buscar por critérios específicos.
- **Atualizar**: Modificar informações de clientes existentes.
- **Deletar**: Remover clientes do banco de dados.

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Tkinter**: Biblioteca para criar a interface gráfica do usuário.
- **SQLite**: Banco de dados usado para armazenar os dados dos clientes.

## 📁 Estrutura do Projeto

1. **`gui.py`**: Contém a definição da interface gráfica utilizando Tkinter.
2. **`backend.py`**: Responsável pelas operações de banco de dados.
3. **`Aplicacao.py`**: Integra a interface gráfica com o backend e controla a aplicação.

## 🔧 Instalação

### Pré-requisitos

- Python 3.x
- Pip (gerenciador de pacotes do Python)

### Passos de Instalação

1. **Clone o repositório**

    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. **Instale as dependências**

    ```bash
    pip install pyinstaller
    ```

3. **Execute a aplicação**

    ```bash
    python Aplicacao.py
    ```

## 📦 Compilação

Para compilar a aplicação para distribuição em Windows ou macOS, use o `pyinstaller`:

```bash
pyinstaller --onefile --windowed Aplicacao.py
```

## 📚 Uso
Visualizar todos os clientes: Clique no botão "Ver todos".
Buscar clientes: Insira critérios de busca e clique em "Buscar".
Adicionar um novo cliente: Preencha os campos e clique em "Inserir".
Atualizar cliente selecionado: Selecione um cliente na lista e clique em "Atualizar Selecionados".
Deletar cliente selecionado: Selecione um cliente na lista e clique em "Deletar Selecionados".
Fechar a aplicação: Clique em "Fechar".

## 📜 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.

## 📞 Contato
Se você tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

Email: gabriel.briotto@aluno.faculdadeimpacta.com.br

## Obrigado por usar o PYSQL 1.0! 🚀

