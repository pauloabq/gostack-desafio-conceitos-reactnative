<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio: Conceitos do React Native
</h3>


<p align="center">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/pauloabq/gostack-desafio-conceitos-reactnative">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/gostack%20bootcamp-Rocketseat-%237259c1">
  </a>

  <img alt="License" src="https://img.shields.io/github/license/pauloabq/gostack-desafio-conceitos-reactnative">

  
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instalação">Instalação</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#testes">Testes</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
  
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no React Native!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend utilizando o Node.js, e no último desafio em ReactJS.

**Atenção**: Caso você esteja emulando no iOS, na pasta do seu projeto navegue até a pasta ios executando o comando `cd ios` e depois execute `pod install` para instalar todas as dependências para o iOS.


### Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.


### Específicação dos testes

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.


Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

### Instalação 

#### 1. Obter os arquivos

```bash
$ git clone https://github.com/pauloabq/gostack-desafio-conceitos-reactnative

```
#### 2. Instalar as dependências

Executar o comando no diretório do projeto clonado para instalar as dependências

```bash
$ yarn
```
ou 

```bash
$ npm install
```
#### 3. Iniciar servidor back-end NodeJS
Instruções no repositório: https://github.com/pauloabq/gostack-desafio-conceitos-nodejs

#### 4. Iniciar o emulador do dispositivo

#### 5. Iniciar a aplicação no emulador

```bash
$ npx react-native run-android

```

### Testes

```bash
$ yarn test
```

### :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

--- 

Criado por <strong>Paulo Albuquerque</strong>

[![Twitter][twitter-shield]][twitter-url] [![LinkedIn][linkedin-shield]][linkedin-url] [![GitHub][github-profile-shield]][github-profile-url]


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/pauloabq/gostack-desafio-conceitos-reactnative
[license-url]: https://github.com/pauloabq/gostack-desafio-conceitos-reactnative/LICENSE

[twitter-shield]: https://img.shields.io/badge/-twitter-black.svg?style=flat-square&logo=twitter&colorB=555
[twitter-url]: http://twitter.com/pauloabq

[github-profile-shield]: https://img.shields.io/badge/-Github-black?style=flat-square&logo=github&colorB=555
[github-profile-url]: http://github.com/pauloabq

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/pauloabq


[github-lang-shield]: https://img.shields.io/github/languages/count/pauloabq/gostack-desafio-conceitos-reactnative
[github-lang-url]: http://github.com/pauloabq
