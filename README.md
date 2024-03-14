# Bootcamp #01 Qualiters Club
_Teste de API Rest do manual a CI/CD_

## O que é ?
_Este repositório foi criado para o bootcamp de Teste de API Rest._

## Tecnologias utilizadas
- **Postman versão web**
- **node version v12.22.12**
- **newman v4.6.1**
- **newman-reporter-html**

## Documentações

- Doc da API: **[Consulte Swagger](https://serverest.dev/#/)**

## Como instalar o ambiente 
- Primeiro: instale o node em seu computador **[Link de download](https://nodejs.org/en/download)**
- Segundo: realize a instalação do newman de forma global **[Link de download](https://www.npmjs.com/package/newman)**
```
- npm install -g newman
```
  
- Terceiro: realize a instalação da dependência dos relatórios (opcional)
- **[newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)**
```
 npm install -g newman-reporter-html
```

## Como rodar os testes 
### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os teste de forma manual ou automatizada

### Pelo newman

- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
``` 
  **_newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli_**
```

-  Execute a seguinte linha de comando para rodar os testes com relatório
``` 
  **_newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra_**
```

### Report
Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos testes
e para verificar as validações você abrir a pasta **newman** que foi criada no local em que os arquivos de _collection_ 
e _environment_ se encontram. 

## Entre em contato
- email: **wt.laureano@protonmail.ch**
- redes sociais: **https://www.linkedin.com/in/walber-tavares-52a97013b/**



















