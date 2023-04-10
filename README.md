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

Em seguida, execute o script **`main.py`**:

```bash

python main.ipynb
```

Após a execução, você verá as análises e gráficos gerados pelo script.
