# 7DaysOfCode    _day1


Eu pensei em aproveitar esse "7 days of code" pra tentar fazer push do meu computador local para um novo repositório dentro do GITHUB e finalmente conseugi...

Eu já tinha instalado o NPM e GIT, e segui os seguintes passos:

1. criei este repositório aqui no GITHUB.

2. Defini nome e email nas configurações locais do GIT:

git config --global user.name "cybervoigt"

git config --global user.email "cybervoigt@gmail.com"

OBS: este comando apenas lista as configurações "git config -l"


3. fiz clone do repositório para uma pasta local

git clone https://github.com/cybervoigt/7DaysOfCode_day1.git


4. criei o projeto REACT com styled-components, rodando este comando no prompt

npx create-next-app --example with-styled-components day1

OBS: Foi criada a nova pasta "day1".


5. No VSCode clicar em "Open Folder" e selecionar a pasta "day1".


6. Mão na massa, implementei a quebra do problema em outros 2 componentes, conforme proposto.

OBS: foi criada a pasta "src", e deixei a parte de "design" e css pra depois.


7. No menu "New Terminal" e rodei este comando para compilar e testar a aplicação:

npm run dev

OBS: rodei em modo web, abrindo neste caminho: http://localhost:3000/


8. De volta ao GIT, para adicionar a pasta "src" rodei este comando no prompt:

git add src


9. rodei o comando abaixo para confirmar as alterações feitas, e inserindo uma mensagem:

git commit -m "First commit..."


10. Finalmente o comando push para enviar os arquivos para o repositório dentro do github

git push -u origin main

OBS: Aqui abriu uma janela do git pedindo a autenticação, onde colei o PAT (Personal access token).

