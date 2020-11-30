## Sobre o desafio

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no React Native!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend utilizando o Node.js, e no último desafio em ReactJS.

## Template da aplicação

Para te ajudar nesse desafio, criamos para você um modelo que você deve utilizar como um template do Github.

O template está disponível na seguinte url: <b>[Acessar Template](https://github.com/rocketseat-education/gostack-template-conceitos-react-native)</b>

Agora navegue até a pasta criada e abra no Visual Studio Code, execute o comando `yarn` no seu terminal para instalar todas as dependências e já estará pronto para iniciar.

<b>Atenção</b>: Caso você esteja emulando no iOS, na pasta do seu projeto navegue até a pasta ios executando o comando `cd ios` e depois execute `pod install` para instalar todas as dependências para o iOS.

## Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo <b>src/App.js</b>, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

- <b>`Listar os repositórios da sua API:`</b> Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos <b>title, techs</b> e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- <b>`Curtir um repositório listado da API:`</b> Deve ser capaz de curtir um item na sua API através de um botão com o texto <b>Curtir</b> e deve atualizar o número de likes na listagem no mobile.

## Específicação dos testes

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Para esse desafio temos os seguintes testes:

- <b>`should add a like to the like counter of the repository:`</b> Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.
