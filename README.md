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

### **Usando Jupyter Notebook**

1. Certifique-se de ter o Python 3 instalado no seu sistema. Se ainda não o fez, você pode baixá-lo em **[python.org](https://www.python.org/downloads/)**.
2. Instale o Jupyter Notebook usando o comando pip:
    
    ```bash
    pip install jupyter
    ```
    
3. Abra o terminal e navegue até o diretório do projeto onde o arquivo **`main.ipynb`** está localizado.
4. Inicie o Jupyter Notebook executando o seguinte comando no terminal:
    
    ```bash
    jupyter notebook
    ```
    
5. Uma nova aba do navegador deverá abrir com o painel do Jupyter Notebook. Clique no arquivo **`main.ipynb`** para abrir o notebook.
6. Dentro do notebook, você pode executar as células de código para ver as análises e gráficos gerados pelo script.

### **Usando o Visual Studio Code (VSCode)**

1. Certifique-se de ter o Python 3 instalado no seu sistema. Se ainda não o fez, você pode baixá-lo em **[python.org](https://www.python.org/downloads/)**.
2. Instale o Visual Studio Code (VSCode) no seu sistema, caso ainda não tenha feito. Você pode baixá-lo em **[code.visualstudio.com](https://code.visualstudio.com/)**.
3. Abra o VSCode e instale a extensão "Python" se ainda não estiver instalada. Você pode fazer isso na seção "Extensões" do VSCode.
4. Abra o diretório do projeto no VSCode.
5. Abra o arquivo **`main.ipynb`** no VSCode.
6. Você pode executar as células de código no arquivo **`main.ipynb`** para ver as análises e gráficos gerados pelo script.
