- Executando um arquivo com Node

👉 No terminal cmd no diretório do arquivo, digite: node "nome-do-arquivo"

Site para Baixar Pacotes Npm: https://www.npmjs.com/package/package

❌ Instalando pacote Npm Global: npm i (OU npm install) -g "nome do pacote"
❌ Instalando pacote Npm Local: npm i (OU npm install) "nome do pacote" --save

👉 Pacotes baixados no primeiro projeto node:

- typescript
- ts-node
- ts-node-dev
- cors
- express

- Inicializando um projeto com Npm 

👉 No terminal cmd no diretório do projeto, digite: npm init
👉 package name: digitar o nome do projeto para renomeá-lo ou enter para considerar o nome da pasta como nome do projeto
👉 version: Enter para considerar a versão indicada no terminal ou indicar a versão desejada
👉 description: indique a descrição do projeto se desejar
👉 entry point: Enter para considerar a indicada no terminal
👉 test command: Enter para considerar essa opção em branco
👉 git repository: pode ser adicionado o repositório responsável pelo projeto
👉 keywords: Enter para considerar essa opção em branco 
👉 author: pode ser adicionado o nome do autor (email, nome)
👉 license: Enter para considerar a licença indicada no terminal

✔ (Comando tsc no terminal cmd: mostra os comandos e seus respectivos significados)
✔ (Comando tsc --version: mostra a versão do typesript instalada)
✔ (Comando tsc: limpa o terminal)

👉 Comando tsc --init:  gerar um arquivo ```tsconfig.json```
👉 Comando tsc: após configuração do arquivo ```tsconfig.json```, esse comando transforma um arquivo .ts e um arquivo .js
👉 Comando node dist/"nome-do-arquivo": executa o arquivo .js
✔ Comando ts-node "nome-do-arquivo": lê um arquivo .ts e executa sem a necessidade de compilar o arquivo para .js

- Tipagem

✅ ```let numero = 5```: pode ser modificado para outro tipo em .js
✅ ```let numero: number = 5```: NÃO pode ser modificado para outro tipo em .js
✅ ```const texto: string = 'Texto 1'```: tipo string obrigatoriamente

