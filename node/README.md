# Stocks-Project
Um projeto para gerenciar ações que permite: 

   - Cotar uma ação;
   - Determinar seu Preço histórico;
   - Preço atual em comparação a outras ações;
   - Projeção de ganhos com compra em data específica.

# Documentação da API 

- https://documenter.getpostman.com/view/11935242/UV5dctZE

# Utilização: 

- Gere sua chave gratuitamente em : 
- https://www.alphavantage.co/ 
- Preencha o arquivo api/.env com a informação da chave: 
- ALPHA_API_KEY= "Sua Chave"

## Inicialização do Front-End

Há um problema de versão na utilização do JEST com o create-react-app. 
Para rodar o front e os testes faça: 

Renomeie o arquivo .env.development.local para .env

### Instalação dos Pacotes do Front-End: 

Na raiz do projeto:

```
 npm install
 npm run start
```

## Inicialização do Back-End : 

Raiz do projeto de api:

```
- cd /api
- npm install
- npm run dev 
```


## Testes Automatizados

Há um problema de versão na utilização do JEST com o create-react-app. Para contorná-lo:  

- Renomeie o arquivo .env.development.local para .env
- SKIP_PREFLIGHT_CHECK=true
Após este passo basta rodar os testes de Back-End: 

```
- cd /api
- npm run test
```

## Construção: 

- npm run build 