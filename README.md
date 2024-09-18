<h1>Projeto de Engenharia e Análise de Dados</h1>
<p>A imagem abaixo representa o Pipeline dos dados.</p>

![Screenshot from 2024-09-18 07-55-44](https://github.com/user-attachments/assets/9aed1e49-c3e5-421b-952c-3c6574800aaf)

<br>
<h3>Resumo</h3>
1. Os dados foram baixados do <a href="https://www.kaggle.com/datasets/abdullah0a/retail-sales-data-with-seasonal-trends-and-marketing">Kaggle</a> e extraídos de um arquivo .csv.

2. O dataset contém informações detalhadas sobre vendas e receitas de uma empresa.
   
3. O arquivo .csv foi armazenado no **Amazon S3**.
     - Embora esse passo não fosse estritamente necessário, optei por utilizá-lo para adquirir experiência com ferramentas de nuvem.

4. A leitura dos dados foi realizada integrando o **Amazon S3** com o **Databricks**.
  
5. No **Databricks**, foram realizadas transformações e análises dos dados, utilizando **Apache Spark** e **SQL**.

6. Por fim a visualização dos dados foi feita com a biblioteca **Seaborn** utilizando **Python**.
