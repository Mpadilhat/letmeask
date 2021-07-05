![logo Letmeask](https://github.com/Mpadilhat/letmeask/blob/master/logo.svg)

> O [Letmeask](https://letmeask-a9540.web.app/) foi o projeto desenvolvido na trilha de React JS durante a 6ª Edição da Next Level Week (#NLWTogether), evento realizado pela [Rocketseat](https://rocketseat.com.br/).

Em suma, é uma espécie de fórum de perguntas e respostas em tempo real em que você pode ser administrador ou um simples usuário:

- Ao criar uma sala para determinado assunto, você passa a administrá-la, ou seja, pode destacar uma pergunta, marcá-la como respondida ou mesmo excluí-la;
- Ao entrar em uma sala, você pode criar uma pergunta ou marcar alguma existente como "gostei!".

## Tecnologias utilizadas

- [React JS](https://pt-br.reactjs.org/);
- [TypeScript](https://www.typescriptlang.org/);
- [Firebase](https://firebase.google.com/?hl=pt);
- [Sass](https://sass-lang.com/); 

## Pré-requisitos
Antes de pôr a mão na massa (ou no código), você deve ter instalado na sua máquina:
- [Git](https://git-scm.com/);
- [Npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/) (**recomendado**);
- Uma IDE, recomendo o [VSCode](https://code.visualstudio.com/);

## Rodando o projeto
No terminal (cmd):

- Clone o projeto em sua máquina na pasta de sua preferência;
- Acesse a pasta em que o projeto foi clonado;
- Usando **yarn** ou **npm**, instale as dependências do projeto: execute o comando **`yarn`** ou **`npm i`**;
- Por fim, execute o comando **`yarn start`** ou **`npm start`** para rodar o projeto. Abrirá em: `localhost:3000` ou numa porta semelhante.

## Importante
Este projeto utiliza [variáveis de ambiente](https://dev.to/guiselair/utilizando-variaveis-de-ambiente-com-create-react-app-5ckc), portanto, para que ele funcione, você precisa:
> - Criar o seu projeto no [Firebase Console](https://console.firebase.google.com/);
> - Dentro do seu projeto, crie o seu banco de dados no Realtime Database;
> - Copie o objeto **`firebaseConfig`** que irá aparecer no passo a passo da criação do banco;
> - No seu código, procure pelo arquivo `.env.local` e, em cada linha correspondente ao atributo do objeto copiado, cole o valores. 
> Exemplo: **`const firebaseConfig = { apiKey: "abcdefghijklmnopqrstuvwxyz", ...}`** ==> **No arquivo `.env.local`:** REACT_APP_API_KEY="abcdefghijklmnopqrstuvwxyz" ...

A configuração acima será utilizada no arquivo `firebase.ts`, portanto, se não existir o arquivo de variáveis de ambiente, crie-o seguindo os nomes de variáveis que estão definidos em `firebase.ts`.

#### Bom código! ✌😉

## Contato
- [LinkedIn](https://linkedin.com/in/marcos-padilha-6b48901b9);
- [mpadilhat@gmail.com](mpadilhat@gmail.com);
