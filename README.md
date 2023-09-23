# Pipeline-ETL-AI
Pipeline ETL (Extração, Transformação e Carregamento) com OpenAI

Consumir o endpoint `GET httpssdw-2023-prd.up.railway.appusers{id}` (API da Santander Dev Week 2023) para obter os dados de cada cliente.

Obter os dados dos clientes e usar a API do ChatGPT (OpenAI) para gerar uma mensagem de marketing personalizada para cada cliente.

Uma vez que a mensagem para cada cliente esteja pronta, envia essas informações de volta para a API, atualizando a lista de news de cada usuário usando o endpoint `PUT httpssdw-2023-prd.up.railway.appusers{id}`