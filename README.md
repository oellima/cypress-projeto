# cypress

Site ultilizado para automação: http://automationpractice.com/index.php

Sobre o cypress:
 
Testes end-to-end são excelentes pois refletem as ações dos usuários. Essa categoria de testes se comportam como um humano real, validando várias partes da aplicação ao mesmo tempo. O Cypress, é um novo test runner com a premissa de testes rápidos, fáceis e confiáveis para qualquer coisa que seja executada em um navegador.

OBS: O ideal é sempre fazer um teste falhar, após fazer ele passar e por fim a refatoração. Mas afim de estudos do Cypress, a maioria dos exemplos não seguiram essa ordem.

Mais sobre : https://tableless.com.br/testando-aplicacoes-com-cypress/
Site do cypress: https://www.cypress.io/

Iniciando um projeto em cypress

1. crie um diretório 
2. abra o vs code 
3. de npm init -y para criar seu package.json
4. depois de npm install cypress@3 
5. npx cypress open
6. veja os exemplos que o cypress ja trás pronto para você

Com todos as dependências instaladas, clone o projeto e execute esse comando:
npx cypress run --browser chrome --no-exit

Executando o projeto:

npm install
Execução em Chrome -- Sempre executar o arquivo .feature
npx cypress open
Execução via SH
npx cypress run

Video:
https://user-images.githubusercontent.com/19351435/111055874-dd511880-8458-11eb-94e0-be73cd04c54a.gif

