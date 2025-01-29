# LH_CD_MiriamOASobral
Repositório do Programa Lighthouse Indicium_Cientista de Dados_ 2025

https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExZTBkcHF0dngzb2QwODY1bnFhd2RqeWptdjkwMnhnOHN0YTJyeXVwcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/mIzxHJogusIqN5esAY/giphy.gif

# Desafio Ciência de Dados - Lighthouse 2025

![indicium (1)](https://github.com/user-attachments/assets/fd6834e0-8b0f-45b2-a739-16daead80523)


# Sobre o projeto: Tranformando dados para alcançar vantagens competitivas

Olá! Seja bem vindo a este repositório do desafio de ciência de dados da Indicium. Nele você vai encontrar uma solução para te ajudar na tomada de decisões no ramo de aluguéis de temporada.
Foi objeto de estudo um conjunto de dados de imóveis disponíveis para locação de temporada do principal concorrente do cliente.


# Objetivo do Projeto

Explorar analiticamente o mercado de imóveis de temporada e a partir disso construir uma estratégia de precificação dos imóveis disponíveis para locaçaõ em NYC.

## Metodologia Crisp DM Model

Utilizou-se a metodologia Crisp DM - Cross Industry Standard Process for Data Mining, que em português significa algo como “Processo Padrão Inter-Indústrias para Mineração de Dados”. O objetivo é desenvolver modelos a partir da análise de informações e dados de um negócio para prever futuras falhas e soluções. 

Composta por 6 etapas, ela inclui descrições das fases típicas de um projeto, as tarefas envolvidas em cada fase e uma explicação dos relacionamentos entre essas tarefas. Como um modelo de processo, o CRISP-DM fornece uma visão geral do ciclo de vida da mineração de dados.

## O problema do Negócio


## Dicionário

* 01 id – Atua como uma chave exclusiva para cada anúncio nos dados do aplicativo
* 02 nome - Representa o nome do anúncio
* 03 host_id - Representa o id do usuário que hospedou o anúncio
* 05 host_name – Contém o nome do usuário que hospedou o anúncio
* 05 bairro_group - Contém o nome do bairro onde o anúncio está localizado
* 06 bairro - Contém o nome da área onde o anúncio está localizado
* 07 latitude - Contém a latitude do local
* 08 longitude - Contém a longitude do local
* 09 room_type – Contém o tipo de espaço de cada anúncio
* 10 price - Contém o preço por noite em dólares listado pelo anfitrião
* 11 minimo_noites - Contém o número mínimo de noites que o usuário deve reservar
* 12 numero_de_reviews - Contém o número de comentários dados a cada listagem
* 13 ultima_review - Contém a data da última revisão dada à listagem
* 14 reviews_por_mes - Contém o número de avaliações fornecidas por mês
* 15 calculado_host_listings_count - Contém a quantidade de listagem por host
* 16 disponibilidade_365 - Contém o número de dias em que o anúncio está disponível para reserva


## Entregas do projeto

* Produto A: Análise exploratória de dados (EDA)
* Produto B: Achados e insights
* Produto C: Modelagem Preditiva
* Produto D: Arquivo salvo.pkl
* Produto E: Repositório GITHUB
* Produto F: Apresentação em vídeo


# Tecnologias utilizadas

## Código
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## Instruções de Execução
Para este em desafio questão utilizei o ambiente GoogleColab, segue abaixo como executar o mesmo.
Você pode abrir diretamente no [Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/drive/1HltbtqTZrbNjZ7cC2vGoNdjkIzjPBJyO#scrollTo=GdvReh0gXD5w

# Carregando Dados de um Arquivo CSV em Outro Drive

Se você estiver usando um ambiente diferente do Google Colab e deseja carregar um arquivo CSV de outro drive, siga as instruções abaixo:

1. **Monte o Drive (se necessário):**
   - Em alguns ambientes, como Jupyter Notebook local, você pode precisar montar o seu Google Drive manualmente.
   - No Google Colab, essa etapa não é necessária, pois já possui integração direta.

2. **Especifique o Caminho Completo:**
   - Forneça o caminho completo até o arquivo CSV no seu drive. Se o arquivo estiver em uma pasta, inclua o caminho até essa pasta.
   - Lembre-se de usar barras invertidas ou barras normais, dependendo do sistema operacional que você está usando.

   Exemplo para um ambiente local:

   ```python
   # Importe a biblioteca pandas
   import pandas as pd

   # Especifique o caminho completo até o arquivo CSV no seu drive
   caminho_arquivo = "C:/Caminho/Para/Seu/Arquivo/teste_indicium_precificacao.csv"

   # Carregue os dados do arquivo CSV
   dados = pd.read_csv(caminho_arquivo)

```
# Relatório

- Relatório Canva https://www.canva.com/design/DAGLVuQC59s/pxiw7R0T4bMHJ_XAOLiTcQ/edit
  
# Autor

Miriam O. A . Sobral

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miriamaguiarsobral/)

[![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:eumoas@gmail.com)
