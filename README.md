# 📚 Processamento de Jurisprudências

Este repositório contém a lógica para o processamento das jurisprudências geradas no repositório [jonas-elias/jurisprudencia-sc-scraping](https://github.com/jonas-elias/jurisprudencia-sc-scraping).

## 📋 Requisitos e Observações

- No arquivo "requirements.txt" estão listadas as dependências necessárias para o processamento das jurisprudências.
- Recomenda-se realizar o processamento em uma máquina com bom desempenho de VRAM, pois a sumarização requer o uso de um modelo transformers para geração de texto.

## 🔢 Embeddings

- Este processo é responsável por gerar embeddings em arquivos mesclados. A quantidade de arquivos gerados depende da escolha do utilizador. Os embeddings são gerados a partir de um texto recebido, que será processado por um modelo de linguagem específico.

## 📂 Conjunto de Dados Original

- Este processo gera arquivos originais do conjunto de dados, de forma mesclada. Novamente, a quantidade de arquivos gerados depende da escolha do utilizador.

## 📑 Conjunto de Dados Resumido

- Este processo realiza a sumarização da jurisprudência em questão, com o objetivo de reduzir a quantidade de caracteres no modelo de linguagem (devido a limitações).
