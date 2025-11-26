# trilha_databricks 🚀

Este repositório reúne conteúdos, notebooks e exemplos práticos para quem deseja aprender sobre engenharia de dados, Databricks, Delta Lake, ETL, e arquitetura de dados moderna.

## 📚 Estrutura do Projeto

- **aula_02/**: Primeiros notebooks de introdução.
	- `primeiro notebook.ipynb`
	- `segundo notebook.ipynb`
- **aula_03/**: Catálogo de dados.
	- `aula_03_catalago_de_dados.ipynb`
- **aula_04/**: Criação de catálogos, schemas e ingestão de dados.
	- `data/`: Dados brutos (`claims.csv`, `customers.csv`, `policies.csv`)
	- `notebooks/`: Notebooks de criação de catálogo, volumes e tabelas.
- **aula_05/**: Pipeline de dados do bronze ao gold.
	- `bronze_to_silver/`: Deduplicação e joins.
	- `silver_to_gold/`: Métricas finais.
	- `source_to_bronze/`: Ingestão inicial.
	- `data/`: Dados de apoio.
	- `analises.ipynb`: Análises exploratórias.
- **aula_06/**: Pipeline LakeFlow e explorações.
	- `data/`: Dados brutos.
	- `pipeline_lakeflow/`
		- `explorations/`: Notebooks exploratórios.
		- `transformations/`: Transformações bronze, silver e gold.

## 🛠️ Tecnologias Utilizadas

- **Databricks**: Plataforma unificada de análise de dados.
- **Delta Lake**: Storage layer para transações ACID em Data Lakes.
- **Python** e **PySpark**: Linguagens para manipulação e processamento de dados.
- **Jupyter Notebooks**: Documentação e execução interativa de código.

## 📈 Objetivos

- Demonstrar boas práticas de ingestão, transformação e análise de dados.
- Explorar conceitos de Data Lakehouse, tabelas bronze/silver/gold e streaming.
- Prover exemplos práticos para uso em ambientes Databricks.

## 🔗 Referências

- [Databricks Documentation](https://docs.databricks.com/)
- [Delta Lake Documentation](https://docs.delta.io/latest/index.html)
- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)

## 👩‍💻 Como Contribuir

1. Faça um fork do projeto.
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m 'feat: minha nova feature'`
4. Faça um push para a branch: `git push origin minha-feature`
5. Abra um Pull Request.