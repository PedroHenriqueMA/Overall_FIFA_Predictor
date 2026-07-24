# Preditor de Overall de Jogadores de Futebol - FIFA 22

O objetivo é utilizar modelos de aprendizado de máquina para prever nota geral (Overall) de atletas com base em atributos técnicos e físicos, e também avaliar qual deles obteve melhores resultados. Com base em [conjunto de dados fornecidos pela FIFA](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset).

Para realizar essa tarefa será utilizado aprendizado de máquina supervisionado por **regressão**. Haja vista que o objetivo é prever um valor inteiro.

## Integrantes
Pedro Henrique Moura Andrade - https://github.com/PedroHenriqueMA

Ian Marcel Santos Santana - https://github.com/IanMS-0803

Luis Gustavo Santos - https://github.com/luisGsts

## Organização dos Arquivos 🏗️
```
/dataset
    /female
        female_players_2016.csv
                ...
        female_players_2022.csv
/images
    /resultados
        ...
    /tutorial
        ...
LICENSE
README.md
Notebook.ipynb
```

## Como abrir o Notebook 📒

Para abrir o notebook siga o passo a passo:
1. Baixe o arquivo ***"Notebook.ipynb"***
2. Abra o Colab no navegador e acesse https://colab.research.google.com (imagem)


3. Selecione a opção "Fazer upload de notebook"
(imagem)

4. Clique no botão "Procurar"
(imagem)

5. E selecione o arquivo ***"Notebook.ipynb"*** baixado

Agora é só usar.

## Modelos utilizados ⚙️

Para fins de avaliação e comparação de resultados utilizamos três modelos: ***Random Forest***, ***Árvore de Decisão*** e ***Regressão Linear***

## Resultados 📊

Obtivemos os seguintes resultados:

(imagens)

Os erros obtidos foram:

| Modelo            | MAE       | MSE       | RMSE      |
| ---               | ---       | ---       | ---       |
|Random Forest      | 0.905806  | 1.522458  | 1.233879  |
|Árvore de Decisão  | 1.337596  | 4.017903  | 2.004471  |
|Regressão Linear   | 1.683050  | 4.524838  | 2.127167  |
|Baseline           | 4.610262  | 33.154566 | 5.758000  |

Portanto, constatou-se que o modelo com melhor resultado foi o ***Random Forest***

## Contribuições 👥

As Contribuições estão listadas abaixo com base nos membros listados e em planilha organizada pelo grupo grupos.

| Tarefa                    | Autor                         |
|   ----                    |    -----                      |
| Idetificação              | Todos                         |
| Compreensão dos dados     | Pedro Henrique Moura Andrade  |
| Análise Exploratória      | Pedro Henrique Moura Andrade  |
| Pré-Processamento         | Pedro Henrique Moura Andrade  |
| Separação                 | Pedro Henrique Moura Andrade  | 
| Modelagem                 | Ian Marcel e Pedro Henrique   |
| Código Random Forest      | Ian Marcel Santos Santana     |
| Código Árvore de Decisão  | Pedro Henrique Moura Andrade  |
| Código Regressão Linear   | Luis Gustavo Santos           |
| Resultados e Discussões   | Pedro Henrique Moura Andrade  | 
| Escrita do Readme         | Luis Gustavo e Pedro Henrique |  
| Edição do vídeo           | Pedro Henrique Moura Andrade  | 

## Link do vídeo 📽️

[Link do youtube](https://youtu.be/fcm4PDgsdTo)
[Link do drive](https://drive.google.com/file/d/1j7IEGGZM6tQkkca3WW9w0zHPu6n2q2Vn/view?usp=sharing)

## Declaração de uso de IA 📄

Em conformidade com as diretrizes acadêmicas/de conduta, declaramos o uso das seguintes ferramentas de IA durante o desenvolvimento deste trabalho:

| Ferramenta | Finalidade | Seção | Forma de Verificação|
|   ----     |    -----   | ----- |       ------        |
| Gemini | Ajuste e correção de código | Compreensão dos dados | Observação do resultado e revisão do código|
| Gemini | Construção dos gráficos | Análise Exploratória | Observação do resultado e revisão do código|
| Gemini | Compreensão dos resultados | Resultados e Discussões | Pesquisa e releitura |
| Gemini | Correção ortográfica | Todas | Revisão por releitura |

💡 *Nota: Toda a lógica do problema, validação dos resultados e interpretação das análises foram revisadas e validadas pela equipe de integrantes de maneira manual.*