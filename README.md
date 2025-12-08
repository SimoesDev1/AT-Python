# AT-Python — IMDb Scraper & Movie Catalog

##  Visão Geral

Este projeto tem como objetivo **raspar os filmes do top do IMDb** (versão móvel) e montar um **catálogo de filmes e séries**, com dados como título, ano de lançamento e nota de avaliação. O processo envolve:

- Web scraping com BeautifulSoup + requests  
- Uso de classes em Python (POO) para representar filmes e séries  
- Armazenamento em banco de dados SQLite com SQLAlchemy  
- Exportação / análise de dados via pandas — CSV, JSON, tabelas, filtros  

O repositório está no formato de notebook Jupyter (`.ipynb`), facilitando a execução passo a passo e a visualização dos resultados.  

---

## Funcionalidades

- ✅ Raspar lista dos “top” filmes no IMDb (título, ano, nota)  
- ✅ Construir objetos `Movie` (filmes) e `Series` (séries) com POO  
- ✅ Preencher catálogo com dados de scraping + séries definidas manualmente  
- ✅ Armazenar dados em banco SQLite (tabelas `movies` e `series`)  
- ✅ Ler os dados com pandas e exibir como DataFrame  
- ✅ Ordenar / filtrar filmes (ex: por nota)  
- ✅ Exportar dados para CSV e JSON  
- ✅ Classificar filmes por categorias (“Obra-prima”, “Excelente”, etc.) com base na nota  
- ✅ Gerar análises básicas com pivot table — por exemplo, contagem por categoria e ano  

---

## 🛠️ Como usar / executar

1. Clone este repositório:

```bash
git clone https://github.com/SimoesDev1/AT-Python.git
cd AT-Python
