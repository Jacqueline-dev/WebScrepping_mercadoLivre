# Web Scraping para Extrair Dados da Página de Ofertas do Mercado Livre
Este projeto consiste em um script de web scraping desenvolvido em Python para extrair dados da página de ofertas do Mercado Livre. O web scraping é uma técnica utilizada para coletar automaticamente informações de páginas da web.

## Bibliotecas Utilizadas 
* Requests:  Utilizada para enviar solicitações HTTP para o servidor e receber as respostas.
* Pandas: Usada para manipulação e análise de dados.
* BeautifulSoup: Utilizada para fazer a raspagem do HTML e extrair os dados desejados.
* Datetime: Utilizada para manipulação de datas e horas.



## Funcionamento do Script
O script envia uma solicitação HTTP para a página de ofertas do Mercado Livre, obtém o HTML da página como resposta e, em seguida, utiliza o BeautifulSoup para analisar o HTML e extrair os dados relevantes, como título, preço, condição do produto, etc. Os dados extraídos são então organizados em um DataFrame do pandas para facilitar sua manipulação e análise posterior.

## Como Utilizar
Para utilizar o script, basta executá-lo em um ambiente Python compatível com as bibliotecas mencionadas. Certifique-se de ter as dependências estejam instaladas.

Autora: Jacqueline Ferreira 💜
