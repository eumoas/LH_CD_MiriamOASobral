

# Desafio Ciência de Dados - Lighthouse 2025

![indicium (1)](https://github.com/eumoas/LH_CD_MiriamOASobral/blob/main/Outros/64944e552f9b281987535da9_Logo-indicium-09.svg)


# "Do Check-in ao Check-out: Estratégias Data Driven para Aluguéis de Temporada"

Olá! Seja bem vindo a este repositório do desafio de ciência de dados da Indicium. Nele você vai encontrar uma solução para te ajudar na tomada de decisões no ramo de aluguéis de temporada.
Foi objeto de estudo um conjunto de dados de imóveis disponíveis para locação de temporada do principal concorrente do cliente.

# Objetivo do Projeto

Construir um modelo preditivo eficiente, avaliá-lo com métricas adequadas e justificar as escolhas feitas ao longo do processo, incluindo análise exploratória, engenharia de features e validação do modelo.

## O problema do Negócio

Previsão de preços para uma plataforma de aluguéis temporários em Nova York, utilizando dados do maior concorrente.

## Contexto do Negócio

O cliente da Indicium deseja criar uma plataforma de aluguéis temporários na cidade de Nova York e sugeriu como passo inicial compreender o perfil de vendas de seu maior cliente (Análise Exploratória), bem como o teste para validação de um modelo de predição com base nessa experiência.

![](https://i.gifer.com/Hguj.gif)

A cidade de Nova York compreende 5 distritos situados no encontro do rio Hudson com o Oceano Atlântico. No centro da cidade fica Manhattan, um distrito com alta densidade demográfica que está entre os principais centros comerciais, financeiros e culturais do mundo. 

O mercado de aluguéis de temporada em Nova York enfrenta transformações significativas devido à implementação da Lei Local 18, que entrou em vigor em setembro de 2023. Essa legislação impõe restrições rigorosas aos aluguéis de curto prazo, exigindo que os anfitriões estejam presentes durante a estadia dos hóspedes, limitando o número de visitantes a dois por vez e proibindo o trancamento das portas dos quartos. Além disso, os anfitriões devem se registrar junto à prefeitura e pagar uma taxa bienal de US$ 145. Essas medidas visam combater práticas ilegais que, segundo as autoridades, geram barulho, lixo e problemas de segurança tanto para visitantes quanto para residentes.
g1.globo.com

Em resposta a essas restrições, surgiram alternativas no mercado. Startups como a Ohana estão se destacando ao focar em aluguéis com duração superior a 30 dias, modelo que não se enquadra nas limitações da nova lei. A Ohana já atraiu mais de 1.200 anfitriões provenientes do Airbnb e gerenciou US$ 2 milhões em pagamentos de aluguel. Paralelamente, plataformas como a Furnished Finder também registraram crescimento, oferecendo opções de estadias mais longas. No entanto, o mercado de aluguéis de temporada em Nova York permanece desafiador, exigindo que novas plataformas se adaptem às regulamentações em constante evolução e às demandas dos consumidores. 
Fontes: 

https://g1.globo.com/google/amp/mundo/noticia/2023/09/07/cidade-de-nova-york-proibe-alugueis-por-curto-prazo-como-os-do-airbnb.ghtml?utm_source=chatgpt.com

https://nypost.com/2024/10/07/business/nycs-airbnb-crackdown-has-sparked-an-underground-market-for-home-shares/?utm_source=chatgpt.com
   

## Perguntas a serem respondidas

* 01 Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?

* 02 O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?

* 03 Existe algum padrão no texto do nome do local para lugares de mais alto valor?

* 04 Qual seria o preço sugerido para um apartamento com as seguintes características?
   {'id': 2595,
      'nome': 'Skylit Midtown Castle',
      'host_id': 2845,
      'host_name': 'Jennifer',
      'bairro_group': 'Manhattan',
      'bairro': 'Midtown',
      'latitude': 40.75362,
      'longitude': -73.98377,
      'room_type': 'Entire home/apt',
      'minimo_noites': 1,
      'numero_de_reviews': 45,
      'ultima_review': '2019-05-21',
      'reviews_por_mes': 0.38,
      'calculado_host_listings_count': 2,
      'disponibilidade_365': 355}

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
* Produto B: Relatório de Hipóteses para o negócio
* Produto C: Modelagem Preditiva
* Produto D: Implantação (Arquivo salvo.pkl)
* Produto E: Apresentação em vídeo
* Produto F: Repositório GITHUB 


# Tecnologias utilizadas

## Código
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## Instruções de Execução
Para este em desafio questão utilizei o ambiente GoogleColab, segue abaixo como executar o mesmo.
Você pode abrir diretamente no [Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/drive/1HltbtqTZrbNjZ7cC2vGoNdjkIzjPBJyO#scrollTo=GdvReh0gXD5w

## Carregando Dados de um Arquivo CSV em Outro Drive

Se você estiver usando um ambiente diferente do Google Colab e deseja carregar um arquivo CSV de outro drive, siga as instruções abaixo:

1. **Monte o Drive (se necessário):**
   - Em alguns ambientes, como Jupyter Notebook local, você pode precisar montar o seu Google Drive manualmente.
   - No Google Colab:
     
            from google.colab import drive
            drive.mount('/content/drive')

Você pode acessar os arquivos no Drive pelo caminho /content/drive/MyDrive/.

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

# Recomendações para a plataforma do cliente: 

Diversidade: É importante considerar a diversidade de perfis potenciais a serem atendidos na plataforma. Embora a alta demanda por imóveis inteiros, pode ser vantajoso investir inicialmente nesse tipo de propriedade, mas também considerar a inclusão de quartos privados para diversificar a oferta.

Precificação: Os preços devem considerar que os imóveis inteiros podem ter preços mais elevados, uma vez que são os mais procurados. Já os quartos compartilhados podem ser oferecidos a preços mais baixos para atrair um público específico.

Otimização algoritmica: Algoritmos de otimização que possam sugerir melhores ofertas para apartamentos desocupados, maximizando a ocupação.

Reviews: Importante desenhar estratégias para que os hóspedes deixem avaliações, seja por algum tipo de programa de fidelidade como milhas, ou mesmo bônus e desconto para a próxima locação. Garantir padrões de qualidade para que os hóspedes se sintam motivados a deixar sua opinião. Inicie, entendendo como foi a experiência do cliente e como pode ser melhor nas próximas vezes.

Hackear a legislação: Business voltado para locações com mais de 30 diárias, opção que não se enquadra nas limitações da nova lei.

Tráfego da plataforma: Monitorar e traçar planos específicos de tráfego para os imóveis com poucas avaliações, aumentando as suas chances de ocupação.

Custo benefício: Dê enfoque para imóveis que combinam preços acessíveis e um alto número de reviews positivos. Identifique os bairros onde os imóveis têm preços mais baixos e alta taxa de ocupação (baixa disponibilidade) e focalize nas ações de marketing e expansão nesses locais.

Melhoria dos espaços: Incentive os anfitriões a melhorarem a qualidade dos seus espaços, de modo que imóveis com preços mais baixos mantenham padrões de qualidade, uma vez que isso levará a reviews positivos e aumentará sua popularidade.

Gestão: Considere criar ferramentas que facilite a gestão dos anfitriões com muitos imóveis listados, por outro lado, considere oferecer benefícios ou recursos para que os menores também consigam prosperar tanto quanto os mais expansivos.

Promoções: Incentive anfitriões com alta disponibilidade a listar pacotes promocionais ou descontos.

Avaliação reversa: Crie mecanismos para que os hóspedes também sejam avaliados pelos anfitriões, sendo justo com os dois lados. Dê espaço para os hóspedes ganhe bonificação ao postar vídeos curtos sobre sua experiência na locação, assim como acontece nessas plataformas de vendas de proutos: shoppee, aliexpress e etc.


# Relatório

- Relatório Canva https://www.canva.com/design/DAGdmQDFCn8/rC98e8TeZYcZijJ_FnHx0g/edit?utm_content=DAGdmQDFCn8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

# Vídeo

https://www.canva.com/design/DAGdmQDFCn8/OVNXG3bCbovQOGCatJugLg/view?utm_content=DAGdmQDFCn8&utm_campaign=designshare&utm_medium=link&utm_source=recording_view
  
# Autor

Miriam O. A . Sobral

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miriamaguiarsobral/)

[![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:eumoas@gmail.com)
