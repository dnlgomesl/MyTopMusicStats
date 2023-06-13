# MyTopMusicStats
O My Top Music Stats é um projeto de Trabalho de Conclusão de Curso que visa mostrar para você que usa o Spotify um pequeno dashboard com informações referente ao que você vem escutando.

## Backend
O backend foi desenvolvido em Python, utilizando o framework Flask. A escolha dessa tecnologia foi baseada na facilidade de manipulação de dados e também porque Python é a mesma linguagem utilizada nos experimentos realizados no Google Colab. A API construída em Flask se comunica com a API do Spotify, permitindo a obtenção dos dados necessários para a criação das estatísticas musicais. A API é responsável pela manipulação dos dados vindo do Spotify, ou seja todos os cruzamentos de dados, cálculos de médias, moda e mediana serão feitos por essa API. Para garantir um ambiente de desenvolvimento consistente e facilitar a implantação, o Docker foi utilizado durante a construção da API, permitindo a criação de contêineres para executar a aplicação de forma independente do ambiente local. A API possui três endpoints principais, sendo um para o status atual da API e os outros dois para obtenção dos itens mais ouvidos, sendo um específico para músicas e outro para artistas. Esses endpoints oferecem uma experiência personalizada aos usuários, permitindo a configuração de parâmetros adicionais. Para os endpoints de músicas e artistas, é possível definir o tipo de ordenação, que pode ser padrão, popularidade ou, no caso das músicas, duração. Além disso, é possível especificar o intervalo de tempo desejado, que pode ser as últimas 4 semanas, os últimos 6 meses ou todos os tempos. Por fim, é possível limitar a quantidade de itens retornados, variando de 1 a 50. Esses parâmetros configuráveis proporcionam aos usuários maior controle sobre as informações obtidas, adaptando a API às suas necessidades específicas de análise e descoberta musical. Para maisinformações sobre a api acesse o módulo backend.
