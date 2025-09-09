# 📊 Análise de Dados com SQL e Python

Este projeto demonstra como integrar **SQL e Python (Pandas, Matplotlib e Seaborn)** para análise de dados.
A base utilizada contém informações de **pedidos, produtos, vendedores e itens de pedidos**, permitindo a criação de consultas e visualizações para explorar os principais insights de negócio.

---

## 🚀 Tecnologias utilizadas
- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [SQLAlchemy](https://www.sqlalchemy.org/)

---

## 📂 Estrutura dos dados
As tabelas utilizadas foram importadas em formato CSV a partir de [dados disponibilizados no GitHub](https://github.com/alura-cursos/SQL-python-integracao):

- **Vendedores**
  - `vendedor_id` → Identificador do vendedor  
  - `nome_vendedor` → Nome do vendedor  

- **Itens Pedidos**
  - `pedido_id` → Identificador do pedido  
  - `produto_id` → Identificador do produto  
  - `quantidade` → Quantidade de itens  
  - `valor_unitario` → Valor unitário  
  - `valor_total` → Valor total  
  - `frete` → Valor do frete  
  - `estado` → Estado de destino  

- **Produtos**
  - `produto_id` → Identificador do produto  
  - `produto` → Nome do produto  
  - `marca` → Marca do produto  
  - `preco` → Preço  
  - `condicao` → Condição do produto  

- **Pedidos**
  - `pedido_id` → Identificador do pedido  
  - `data_compra` → Data da compra  
  - `vendedor_id` → Identificador do vendedor  

---

## 📊 Análises realizadas
- Consultas SQL integradas ao Python.  
- Identificação de produtos mais vendidos.  
- Agrupamentos e rankings.
- Visualizações gráficas para facilitar a interpretação dos dados.  

---

## 🛠️ Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/seuprojeto.git
   cd seuprojeto

2. Crie um ambiente virtual e instale as dependências:

  python -m venv venv
  
  source venv/bin/activate   # Linux/Mac
  
  venv\Scripts\activate      # Windows
  
  pip install -r requirements.txt

4. Abra o Jupyter Notebook:
   
  jupyter notebook

6. Execute o arquivo dados_python_sql.ipynb.

## ✨ Autor
Luís Ferreira

Projeto desenvolvido como estudo de integração Python + SQL para análise de dados.
