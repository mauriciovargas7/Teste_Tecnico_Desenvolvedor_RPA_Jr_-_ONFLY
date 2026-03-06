# Teste Técnico Desenvolvedor RPA Jr - ONFLY
Desenvolver uma automação que realize coleta, integração e consolidação de dados a partir de uma página web e de uma API pública.

📌 Desafio
A automação deve executar as seguintes etapas:

1️⃣ Scraping
Acesse o site abaixo:

Worldometers population page
https://www.worldometers.info/world-population/population-by-country/
Identifique os 10 países com maior média de idade (coluna “Median Age”) e capture:


Nome do país


Quantidade de habitantes (Population)


Média de idade (Median Age)

O processo deve ser automatizado.

2️⃣ Consumo de API
Utilize a API pública abaixo:

REST Countries
https://restcountries.com/
Para cada país obtido na etapa anterior, consulte a API e capture:


Capital


Linguagens faladas


Nome das moedas

3️⃣ Consolidação
Mescle as informações das duas etapas e gere um arquivo .xlsx com a seguinte estrutura:

País | Qtd habitantes | Média idade | Capital | Linguagens | Moedas

Exemplo:

Brazil | 213562666 | 35.3 | Brasília | Portuguese | Brazilian real

O arquivo deve ter o seu nome completo. Ex:
Teste RPA - Felipe Campos Junior.xlsx
4️⃣ Envio
Envie o arquivo gerado para o seguinte webhook via requisição HTTP POST:

https://sua-url

Autenticação:

Usuário: seu-user

Senha: sua-senha

⚙️ Requisitos

Linguagem: Python ou JavaScript


O processo deve ser totalmente automatizado


O código deve estar versionado em repositório GitHub/GitLab

📦 Entrega
Enviar:


Link do repositório



Evidência de envio ao webhook
