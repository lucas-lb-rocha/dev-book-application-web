# Dev-book-application-web

Essa aplicação web consome da API dev-book-api e é uma página similar ao twitter na qual é possível postar mensagens, seguir usuários e acompanhar as postagens dos usuários da rede. Essa aplicação é resultante do curso https://www.udemy.com/course/aprenda-golang-do-zero-desenvolva-uma-aplicacao-completa/?couponCode=KEEPLEARNING

# Pré-requisistos
- golang
- postgres
- javascript

# Rodando a aplicação
- Criar o arquivo .env com os seguintes valores
  ```
  API_URL=UrlDaAplicacaoDevBookApi ("http://localhost:5000")
  APP_PORT=portaDaAplicacao  
  HASH_KEY=HashEmFormatoHex (dá para gerar em python com uuid.uuid4.hex)
  BLOCK_KEY=HashEmFormatoHexDiferenteDaAnterior
  ```
- Na raiz do projeto rode go run main.go

O projeto vai estar rodando na porta que escolheu, por exemplo, localhost:5001

Link para o vídeo com a demonstração da aplicação: https://youtu.be/BF60wRh9cDc
