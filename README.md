# Video Game Sales & Metacritic — Análise Exploratória de Dados

> Projeto de prática em Python e Pandas, desenvolvido como parte dos meus estudos em Engenharia de Dados.

---

## Sobre o projeto

Este projeto é uma análise exploratória de dados (EDA) aplicada a um dataset de vendas e avaliações de jogos entre 1980 e 2026. O objetivo principal é praticar técnicas de limpeza, transformação e análise de dados com Python e Pandas.

---

## Dataset

- **Fonte:** [Kaggle — Video Game Sales & Metacritic Intelligence 1980–2026](https://www.kaggle.com/)
- **Registros:** ~50.000 jogos
- **Colunas principais:** título, plataforma, gênero, ano, publisher, developer, vendas por região, receita estimada, nota Metacritic e nota dos usuários

---

## O que foi analisado

- Identificação e remoção de registros inválidos (jogos cadastrados incorretamente na plataforma Game Boy)
- Gêneros mais populares por região (América do Norte, Europa e Japão)
- Publishers com maior receita estimada

---

## Limpeza realizada

- Remoção de colunas desnecessárias para a análise
- Exclusão de registros com plataforma inválida (Game Boy com títulos e datas incompatíveis)
- Conversão e padronização da coluna `year`

---

## Tecnologias utilizadas

- Python 3.14
- Pandas
- Jupyter Notebook

---

## Próximos passos

- Integração com PostgreSQL — carregar os dados tratados em um banco de dados relacional
- Criação de queries SQL para análises complementares

---

## 👨‍💻 Autor

**Vitor Emanuel**
[github.com/vitor-emanueldev](https://github.com/vitor-emanueldev)

> 📌 Este é um projeto de aprendizado, desenvolvido durante meus estudos em Engenharia de Dados.
