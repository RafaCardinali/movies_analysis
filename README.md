# Análise de Dados de Filmes de Diretores Indicado ao Oscar usando a API TMDb

Este projeto tem como objetivo coletar e analisar filmes dirigidos por diretores indicados ao Oscar desde o início da premiação, com duração superior a 50 minutos. Os dados são obtidos utilizando a [API do TMDb](https://developers.themoviedb.org/3/getting-started/introduction).

## Índice

1. [Introdução](#introdução)
2. [Coleta de Dados](#coleta-de-dados)
3. [Tecnologias Utilizadas](#tecnologias-utilizadas)
4. [Estrutura do Projeto](#estrutura-do-projeto)
5. [Como Rodar o Projeto](#como-rodar-o-projeto)
6. [Contato](#contato)

## Introdução

O projeto se concentra em realizar uma análise dos filmes dirigidos por diretores que foram indicados ao Oscar. Utilizando a API do TMDb, buscamos todos os filmes com duração superior a 50 minutos de cada um desses diretores. A análise inclui informações como título, gênero, e ano de lançamento dos filmes.

## Coleta de Dados

Os dados foram obtidos diretamente da API do TMDb para cada diretor indicado ao Oscar. A API foi consultada para buscar informações sobre o diretor e seus filmes, filtrando para filmes com mais de 50 minutos de duração.

Devido a restrições de segurança, a chave da API não está incluída no código. Você precisará configurar suas próprias variáveis de ambiente para armazenar a chave da API.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para todo o script de coleta e análise de dados.
- **Pandas**: Biblioteca utilizada para manipulação de dados.
- **Requests**: Biblioteca utilizada para fazer requisições HTTP à API do TMDb.
- **TMDb API**: Usada para obter os dados dos filmes e diretores.

## Estrutura do Projeto

    ```bash
    ├── movie.ipynb
    ├── df_sortered.csv 
    ├── README.md
    ```

## Como Rodar o Projeto

1. Clone este repositório: 
   ```bash
   git clone https://github.com/RafaCardinali/movies_analysis.git
    ```
2. Instale as dependências:
    ```bash
    pip install pandas requests
    ```
3. Crie um arquivo `.env` na raiz do seu projeto e adicione sua chave da API TMDb:
    ```bash
    TMDB_API_KEY=sua_chave_de_api_aqui
    ```
3. Execute o script Python:
    ```bash
    jupyter notebook movie.ipynb
    ```

## Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

[LinkedIn](https://www.linkedin.com/in/rafael-cardinali-213899296/)

[Email](mailto:rflcardinali@gmail.com)