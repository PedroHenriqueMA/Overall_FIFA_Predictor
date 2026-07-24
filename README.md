

# **TITULO:** Preditor de Overall de Jogadores FIFA 16-22 - Grupo 16

> **Objetivo:**  O objetivo é utilizar modelos de aprendizado de máquina para prever nota geral (Overall) de atletas com base em atributos técnicos e físicos, e também avaliar qual deles obteve melhores resultados.

---

##  Integrantes

**Pedro Henrique Moura Andrade**   - https://github.com/PedroHenriqueMA

**Ian Marcel Santos Santana**      - https://github.com/IanMS-0803

**Luis Gustavo Santos**            - https://github.com/luisGsts

--- 

##  Fonte dos Dados

Os dados utilizados neste projeto foram obtidos a partir de:

**Fonte       :** Kaggle datasets

**Link        :** https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset

**Descrição   :** O conjunto de dados contém métricas com base em estatísticas de jogadores de futebol.

---

##  Tipo da Tarefa

**Categoria   :** Regressão

---

##  Organização dos Arquivos


├── dataset/female                                   # Conjuntos de dados 

├── Trabalho_Final_Fundamento_IA.ipynb/              # Jupyter Notebook/Colab com código e análises

├── README.md                                        # Documentação principal do projeto



---

##  Como Abrir o Notebook no Google Colab

Você pode executar o projeto diretamente no Google Colab seguindo os passos abaixo:

1. **Acesso Direto:**
Clique no arquivo Trabalho_Final_Fundamento_IA.ipynb e depois clique no botão "Open with Colab" para abrir o notebook principal diretamente no Colab:

Ou

2. **Passo a Passo Manual:**
Baixe o arquivo `.ipynb`.

Acesse o [Google Colab](https://colab.research.google.com/).
Vá em **Arquivo** > **Fazer upload do notebook** e selecione o arquivo baixado.
Certifique-se de executar as primeiras células para instalar dependências e carregar a base de dados.



---

##  Modelos Utilizados

Durante o desenvolvimento, foram avaliados e comparados os seguintes modelos de Machine Learning:

**Regressão Linear** 

**Baseline** 

**Random Forest** 

**Arvore de decisão**

---

##  Principais Resultados

Resumo do desempenho dos modelos e das descobertas do projeto:

| Modelo            |    MAE    |    MSE    |    RMSE   |
| ---               |    ---    |    ---    |    ---    |
| Random Forest     | 0.905806  | 1.522458  | 1.233879  |
| Árvore de Decisão | 1.337596  | 4.017903  | 2.004471  |
| Regressão Linear  | 1.683050  | 4.524838  | 2.127167  |
| Baseline          | 4.610262  | 33.154566 | 5.758000  |



**Conclusões:** O Modelo escolhido como melhor foi o Random Forest, por ter obtido o menor erro absoluto (MAE), erro quadrático médio (MSE) e raiz do erro quadrático médio (RMSE) com base nos resultados apresentados nos testes.

---

##  Divisão das Contribuições

**Pedro Henrique Moura Andrade:** Compreensão dos dados, Pré-Processamento, Separação, Análise Exploratória, treinamento Baseline (Modelo de Comparação) e Árvore de Decisão para Regressão;

**Ian Marcel Santos Santana:** Treinamento do random forest e avaliação do modelo;

**Luis Gustavo Santos:** Treinamento do modelo de regressão linear e avaliação do modelo e documentação do README.
         
---

##  Demonstração em Vídeo

Assista ao nosso vídeo explicativo do projeto onde apresentamos a metodologia, o código em execução e os resultados obtidos:

**Clique aqui para assistir ao vídeo do projeto (link do video)**

---

##  Declaração de Uso de Ferramentas de Inteligência Artificial

Em conformidade com as diretrizes acadêmicas/de conduta, declaramos o uso das seguintes ferramentas de IA durante o desenvolvimento deste trabalho:

**ChatGPT/ Gemini:** Utilizada para auxílio no refinamento do código do notebook, depuração de erros de sintaxe e estruturação do texto de documentação.

*Nota:* Toda a lógica do problema, validação dos resultados e interpretação das análises foram revisadas e validadas pela equipe de integrantes de maneira manual.
