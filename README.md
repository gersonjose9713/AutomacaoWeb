# 🌐 Web Scraper 🌐

Este é um projeto pessoal que eu criei para automatizar a coleta de dados de um site. O objetivo era poder obter dados atualizados sobre os preços de diversos produtos de forma rápida e eficiente, sem precisar navegar manualmente pelo site.

Para isso, criei um script em Python que usa a biblioteca Selenium para controlar o navegador e navegar pelo site. A biblioteca Selenium permite que o script execute ações como preencher formulários, clicar em botões e navegar entre páginas de forma automatizada.

Uma vez na página do site, o script usa o módulo BeautifulSoup para analisar o código HTML da página e extrair informações relevantes, como o nome do produto, o preço em diferentes lojas online e a URL da página de cada produto.

Para armazenar os dados coletados de forma organizada, o script utiliza o módulo Pandas para criar um DataFrame e exporta os dados para um arquivo CSV. Dessa forma, é possível realizar análises e tomar decisões mais informadas sobre onde comprar os produtos com os melhores preços.

Além disso, para garantir que o script possa lidar com falhas na conexão ou com alterações no layout do site, implementei verificações de erro e tratamento de exceções . Também criei um sistema de log para registrar quaisquer problemas que possam ocorrer durante a execução do script. Dessa forma, é possível identificar e corrigir qualquer falha de forma rápida e eficiente.

## 📋 Dependências 📋
Para executar este script, você precisará ter instalado os seguintes módulos Python:

Selenium: para controlar o navegador e navegar pelo site.
BeautifulSoup: para analisar o código HTML da página e extrair informações relevantes.
Pandas: para armazenar os dados coletados em um DataFrame e exportá-los para um arquivo CSV.

## 🚀 Executando o script 🚀
Executar o script, passar a lista de produtos de interesse como argumentos. O script irá abrir o navegador e começar a coletar os dados. Quando o processo estiver concluído, os dados serão armazenados em um arquivo CSV na mesma pasta do script.
