# EBAC-PVL-Análise-Tesouro

# 📊 Análise de Solicitações de Projetos de Lei (PVL) - Tesouro Nacional 🇧🇷

Este é um projeto de análise exploratória dos dados de solicitações de Projetos de Lei (PVL) de estados e municípios do Brasil, utilizando a API do Tesouro Nacional 💰. Desenvolvido como parte do meu aprendizado na EBAC 📚.

## 📂 Conteúdo

* `seu_notebook.ipynb` 💻: Notebook Jupyter com o código Python para acessar a API, realizar as análises e gerar o arquivo CSV.
* `solicitacoes_bahia_estados.csv` 💾: Arquivo CSV contendo os dados das solicitações do estado da Bahia (interessado 'Estado'), resultado da nossa análise.
* `README.md` 📝: Este arquivo que você está lendo agora, com a descrição do projeto e como utilizá-lo.

## 🚀 Como Utilizar

1.  **Pré-requisitos:**
    * Python 🐍 instalado na sua máquina.
    * Bibliotecas `requests` e `pandas` instaladas. Se não tiver, rode no terminal: `pip install requests pandas`
    * Jupyter Notebook instalado. Se não tiver, rode: `pip install notebook`

2.  **Execução:**
    * Clone este repositório para o seu computador: `git clone https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content`
    * Navegue até a pasta do projeto no terminal: `cd [nome-do-repositorio]`
    * Inicie o Jupyter Notebook: `jupyter notebook`
    * Abra o arquivo `seu_notebook.ipynb` e execute as células para rodar a análise e gerar o arquivo CSV.

## 🔍 Análises Realizadas

Neste notebook, realizamos as seguintes explorações nos dados:

1.  🛠️ Criamos uma função Python esperta para consultar a API do Tesouro Nacional, permitindo filtrar por Unidade Federativa (UF) e tipo de interessado ('Estado' ou 'Município').
2.  🇧🇷 Investigamos quantas solicitações do estado de Minas Gerais com o status de 'Arquivado por decurso de prazo' encontramos 🤔.
3.  🌴 Descobrimos qual município da Bahia se destaca com o maior número de solicitações que foram deferidas ✅.
4.  💾 Salvamos os dados das solicitações do estado da Bahia (apenas para o tipo 'Estado') em um arquivo CSV chamado `solicitacoes_bahia_estados.csv`.

