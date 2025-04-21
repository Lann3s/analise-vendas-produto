
# 📊 Análise de Vendas por Linha de Produto

## 📌 Sobre o Projeto
Esse projeto foi criado para analisar as vendas por linha de produto usando um dataset do [Kaggle](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data). O objetivo é aprender mais sobre análise de dados com Python, especialmente utilizando **pandas** e **plotly**, enquanto exploro o comportamento de vendas por categoria de produtos.

## 🧠 O Que Eu Aprendi
- Manipulação e limpeza de dados com **pandas**.
- Criação de visualizações interativas com **plotly**.
- Como lidar com datas e agregação de dados.
- Como comunicar insights de forma visual e objetiva.

## 🔍 O Passo a Passo
1. **Carregando os Dados:** O primeiro passo foi importar o dataset e dar uma olhada geral nele.
2. **Tratamento de Dados:** Aqui, transformei os tipos de dados e criei uma nova coluna de "receita" para cada venda.
3. **Análise:** Calculei a receita total por linha de produto, para entender melhor quais categorias se destacam.
4. **Visualização:** Usei o **plotly** para criar um gráfico interativo que facilita a visualização das vendas por linha de produto.

## 📈 Resultados

As três linhas de produto que mais geraram receita foram:

- 🥇 **Classic Cars** — \$2.968.546,40
- 🥈 **Vintage Cars** — \$1.644.212,05
- 🥉 **Motorcycles** — \$971.086,29

Já a linha com a menor receita foi:

- 🚂 **Trains** — \$203.804,26

## 💡 O Que Eu Descobri
- **Classic Cars** é disparada a linha mais lucrativa. Isso mostra que o mercado de carros clássicos tem uma boa demanda.
- **Trains** foi a linha que não teve o desempenho esperado. Isso pode ser um sinal de que as vendas precisam de mais atenção ou melhorias na estratégia.

## 🛠️ Próximos Passos
- **Análise por Região:** Explorar como as vendas variam em diferentes regiões pode trazer novas oportunidades.
- **Explorar Sazonalidades:** Investigar se há variações sazonais nas vendas pode ajudar a entender tendências ao longo do ano.
- **Análise por Tipo de Cliente:** Verificar quais segmentos de clientes compram mais cada categoria de produto.

## 🧾 Dataset
- [Sales Data Sample](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- O dataset é fictício e foi usado apenas para fins de aprendizado.

## 🚀 Como Executar
Esse projeto foi feito em um **Jupyter Notebook**, então para rodar ele na sua máquina, basta seguir os passos abaixo:
1. Clone este repositório.
2. Instale as dependências com:
   ```bash
   pip install pandas plotly
   ```
3. Abra e execute o notebook `AnaliseVendasProduto.ipynb`.

