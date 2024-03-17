# Dev-book-application-web

Essa API é um CRUD de usuários e publicações para um banco de dados postgres. Essa aplicação é resultante do curso https://www.udemy.com/course/aprenda-golang-do-zero-desenvolva-uma-aplicacao-completa/?couponCode=KEEPLEARNING

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
