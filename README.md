# PoemGenerator

**Código da Disciplina**: FGA0134<br>

## Alunos
| Matrícula | Aluno |
| -- | -- |
| 18/0096991 | Álvaro Leles Guimarães |
| 18/0145088 | Gabriel Bonifácio Perez Nunes |
| 18/0101617 | Guilherme de Morais Richter |
| 18/0102087 | Ian Fillipe Pontes Ferreira |
| 18/0102656 | Ítalo Vinícius Pereira Guimarães |

## Sobre 

&emsp;&emsp;Esse é um repositório focado no trabalho de Tópicos Especiais de Engenharia de Software - Deep Learning. Desenvolvido pelos integrantes acima, o PoemGenerator utilizará Machine e Deep Learning com o objetivo de gerar poemas. Para isso, serão usados alguns dados públicos armazenados em arquivos contendo poemas e o nome de seus autores. Na 1ª reunião, foram definidas as bibliotecas e a equipe começou a fazer a codificação dando, então, início ao projeto. O grupo retirou e coletou os dados da página [pensador](https://www.pensador.com/poemas/) que possui muitos poemas de diversos autores. Com o objetivo de implementar um método já validado, utilizamos um utilizado pelo engenheiro de inteligência artificial [Laurence Moroney](https://laurencemoroney.com/), tendo como principal base o vídeo: [Training an AI to create poetry (NLP Zero to Hero - Part 6)](https://www.youtube.com/watch?v=ZMudJXhsUpY). 

## Bibliotecas e ferramentas

&emsp;&emsp;Foram utilizadas as seguintes bibliotecas e ferramentas:

- [BeautifulSoup](https://pypi.org/project/beautifulsoup4/), para realizar o Web Scrapping do site [pensador](https://www.pensador.com/poemas/)

- [Keras](https://www.tensorflow.org/guide/keras?hl=pt) (API de alto nível do [Tensorflow](https://www.tensorflow.org/overview));

- Com o objetivo de trabalhar com expressões regulares e fazer uma "limpa" no dataset, utilizamos o [RegEX](https://docs.python.org/pt-br/3/library/re.html);

- [Numpy](https://numpy.org/), para trabalharmos com arrays, principalmente;

- [Pandas](https://pandas.pydata.org/). Utilizado para análise de dados, leitura de arquivos, entre outros.
