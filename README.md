<h1 align="center">
  <br>
  <br>
  App Weather
</h1>

<h4 align="center">
   Aplicativo de consulta de clima por geolocalização,pesquisa por cidade e consumo de API -  HG-brasil
</h4>

<h6 align="center">
  bootcamp SujeitoProgramador
</h6>

<br/>

<p align="center">
  <a href="#Pre-Requisitos">Pre-requisitos</a> |
  <a href="#Instalação">Instalação</a> |
  <a href="#Usabilidade">Usabildiade</a>
</p>

# Pre-Requisitos

* [React-Native Expo](https://reactnative.dev/)
* [Android Studio](https://developer.android.com/studio) 
* [Node.JS](https://nodejs.org/)
* [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/get-npm)
* [API Weather - HG brasil](https://hgbrasil.com/)

# Instalação
```
# Primeiro clone o repositorio do Git para seu computador. Execute o comando; 
git clone https://github.com/SandroFrazaoS/AppWeather.git

# Acesse a pasta criado atraves do comando; 
cd AppWeather

# Instale todas as dependencias do projeto, acesse a pasta AppWeather e execute o comando;
yarn

# Para start do App execute dentro da pasta AppWeather o comando;
expo start
```

# Projeto

Ao abrir o aplicativo o sistema identifica por geolocalização a localização do celular   capturando as informações de latitude e longitude. Atraves destas informações (alt+lat) é consumido a API da GH Brasil para retornar informações do clima da sua cidade.

![1][tela1]

Na tela é apresentado, nome da cidade, tipo de clima (nublado, chovendo, insolarado), se é dia ou noite, graus celsius, velocida do vento, humidade, hora Sunraise, Hora Sunset. Abaixo das informações do clima atual é apresentado uma lista de clima dos proximos 7 dias.

![2][tela2]
![3][tela3]

No menu pricipal, guia procurar, é possivel pesquisar o clima pelo nome cidade e estado.

![4][tela4]




[tela1]: T1.png
[tela2]: T2.png
[tela3]: T3.png
[tela4]: T4.png
