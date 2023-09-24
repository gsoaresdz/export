Eu tenho esse README.md no GitHub, gostaria de complementar adicionando como instalar o Jupyter Notebook e vscode para rodar o projeto:

# **Exportações entre Brasil e França**

Este repositório contém um script em Python que analisa as exportações entre o Brasil e a França.

## **Descrição do Código**

O código utiliza a biblioteca Pandas para ler um arquivo CSV chamado **`exportacoes_franca.csv`** e realiza uma série de análises e manipulações nos dados. A base de dados contém informações sobre exportações entre Brasil e França de 2016 a 2020.

### **Estrutura dos Dados**

Os dados estão estruturados nas seguintes colunas:

- Year
- Month
- Country
- City
- SH4 Code
- SH4 Description
- SH2 Code
- SH2 Description
- Economic Block
- US$ FOB
- Net Weight

### **Análises Realizadas**

O script realiza as seguintes análises nos dados:

1. Evolução das exportações para a França ao longo dos anos (US$)
2. Os produtos mais exportados ao longo de todo o período em (US$)
3. Em 2020, qual cidade mais exportou para a França?
4. O que as 2 maiores cidades exportaram?

## **Como executar**

Para executar o script, é necessário ter Python 3 instalado e as seguintes bibliotecas: Pandas e Plotly.

Para instalar as dependências, execute o comando:

```bash

pip install pandas plotly
```

Para executar o script e visualizar as análises, você pode escolher entre o Jupyter Notebook ou o Visual Studio Code. Abaixo estão as instruções para ambos os ambientes.

Usando Jupyter Notebook
Certifique-se de ter o Python 3 instalado no seu sistema. Se ainda não o fez, você pode baixá-lo em python.org.

Instale o Jupyter Notebook usando o comando pip:

bash
pip install jupyter
Abra o terminal e navegue até o diretório do projeto onde o arquivo main.ipynb está localizado.

Inicie o Jupyter Notebook executando o seguinte comando no terminal:

bash
jupyter notebook
Uma nova aba do navegador deverá abrir com o painel do Jupyter Notebook. Clique no arquivo main.ipynb para abrir o notebook.

Dentro do notebook, você pode executar as células de código para ver as análises e gráficos gerados pelo script.

Usando o Visual Studio Code (VSCode)
Certifique-se de ter o Python 3 instalado no seu sistema. Se ainda não o fez, você pode baixá-lo em python.org.

Instale o Visual Studio Code (VSCode) no seu sistema, caso ainda não tenha feito. Você pode baixá-lo em code.visualstudio.com.

Abra o VSCode e instale a extensão "Python" se ainda não estiver instalada. Você pode fazer isso na seção "Extensões" do VSCode.

Abra o diretório do projeto no VSCode.

Abra o arquivo main.ipynb no VSCode.

Você pode executar as células de código no arquivo main.ipynb para ver as análises e gráficos gerados pelo script.

Agora, os usuários do seu repositório no GitHub terão instruções claras sobre como executar o projeto tanto no Jupyter Notebook quanto no Visual Studio Code. Certifique-se de incluir essas instruções no seu README.md no GitHub.
