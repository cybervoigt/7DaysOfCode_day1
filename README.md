# 7DaysOfCode    _day1


Eu pensei em aproveitar esse "7 days of code" pra tentar fazer push do meu computador local para um novo repositório dentro do GITHUB e finalmente conseugi...


Eu consegui fazendo assim:

1. criei este repositório aqui no github

2. fiz clone do repositório para uma pasta local
git clone https://github.com/cybervoigt/7DaysOfCode_day1.git

3. criei o projeto React, com styled-components
npx create-next-app --example with-styled-components day1
Foi criada a nova pasta "day1"

4. fiz a quebra do problema em outros componentes, conforme proposto.
(deixei a parte de "design" e css pra depois)

5. No VSCode clicar em "Open Folder" e selecionar a pasta "day1".

6. No menu "New Terminal" este comando executa a aplicação para compilar e testar
npm run dev

8. no prompt, para adicionar a pasta "src" rodei este comando
git add src

9. rodei o comando abaixo para confirmar as alterações feitas, e inserindo uma mensagem
git commit -m "First commit..."

10. Finalmente o comando push para enviar os arquivos para o repositório dentro do github
git push -u origin main
Aqui abriu uma janela do git pedindo a autenticação, onde colei o token.

