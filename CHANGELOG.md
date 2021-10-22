# Change Log

## Versões dos Commits

### 1.0 (21/09/2021)

- Cria-se o repositório afim de iniciar a codificação e documentação.
<br/><br/>
- Primeiro commit;
- Commit: [c1d187cc76fe4e91f8c0fb095e35b25a1cc1d887](https://github.com/deeplearningunb/PoemGenerator/commit/c1d187cc76fe4e91f8c0fb095e35b25a1cc1d887);
- Autor: Ítalo Vinícius. 
<br/><br/>
- Criação das pastas;
- Commit: [27c470939a33bfa7b82e24e6ea49a8aa221326dd](https://github.com/deeplearningunb/PoemGenerator/commit/27c470939a33bfa7b82e24e6ea49a8aa221326dd);
- Autor: Ítalo Vinícius. 
<br/><br/>
- Pegando dados de um site de poemas;
- Commit: [2b381508e7804110428fee919eabbc43799fc9ba](https://github.com/deeplearningunb/PoemGenerator/commit/2b381508e7804110428fee919eabbc43799fc9ba);
- Autor: Ítalo Vinícius. 

### 1.1 (22/09/2021)

- Removendo informações e criação de dataset;
- Commit: [d954c229cee84c93257c670b73ae1c01fb108b0f](https://github.com/deeplearningunb/PoemGenerator/commit/d954c229cee84c93257c670b73ae1c01fb108b0f);
- Autor: Ian Fillipe. 
<br/><br/>
- Removendo linhas de código redundantes;
- Commit: [bf5932ae260494019cb27429d9d5154001ea39c3](https://github.com/deeplearningunb/PoemGenerator/commit/bf5932ae260494019cb27429d9d5154001ea39c3);
- Autor: Ítalo Vinícius. 

### 1.2 (25/09/2021)

- Rastreabilidade de dados;
- Commit: [f83fff3f3e3e8444444352c088428412ae1f7845](https://github.com/deeplearningunb/PoemGenerator/commit/f83fff3f3e3e8444444352c088428412ae1f7845);
- Autor: Ítalo Vinícius. 

### 2.0 (18/10/2021)

- Remoção de alguns títulos de poemas;
- Commit: [353fc183975384d7a94cbb9abec7860973a97a6e](https://github.com/deeplearningunb/PoemGenerator/commit/353fc183975384d7a94cbb9abec7860973a97a6e);
- Autor: Ítalo Vinícius. 
<br/><br/>
- Criação do modelo de treinamento.
- Commit: [f2a9bcc31f013670c7fee7cf80b9c483b0aeb2ff](https://github.com/deeplearningunb/PoemGenerator/commit/f2a9bcc31f013670c7fee7cf80b9c483b0aeb2ff);
- Autor: Álvaro Leles.

### 2.1 (19/10/2021)

- Inicia-se o processo de remoção de palavras consecutivas repetidas;
- Commit: [38ef41cd8ae390bb62cea1366cef41e147679e88](https://github.com/deeplearningunb/PoemGenerator/commit/38ef41cd8ae390bb62cea1366cef41e147679e88);
- Autor: Guilherme Richter;

## Versões das Releases

### 1.0.0 - alpha

- [Web Scraping e criação do dataset](https://github.com/deeplearningunb/PoemGenerator/releases/tag/v1.0.0-alpha):
    - Projeto está dividido em pastas para cada tarefa que será feita;
    - Foi feito na página ["O Pensador"](https://www.pensador.com/poemas/) a partir das bibliotecas Requests e BS4;
    - Foi criado um dataset por meio da biblioteca [Pandas](https://pandas.pydata.org/) sendo salvo estes dados em um arquivo CSV;
    - Não se sabe ainda se os dados serão limpos, pois, pode ser que os ruídos que existam sejam importantes para o treinamento do modelo.

### 1.1.0 - alpha

- [Pre-trained Model](https://github.com/deeplearningunb/PoemGenerator/releases/tag/v1.1.0-alpha):
    - Referente ao treinamento do modelo;
    - Os poemas estão pré-processos para entrar no modelo;
    - Modelo foi salvo como uma pasta ou HDF5 para facilitar o treinamento.