<h1 align="center">
  <br>
  <br>
  App Weather
</h1>

<h4 align="center">
   App de consulta de clima utilizando geolocalização e consumo de API.
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

# Acesse a pasta criado com o comando; 
cd AppWeather

# Apos acessar a pasta execute o comando yarn para instalar as dependencias do projeto.  exemplo;
c:\AppWeather\yarn

# Para start do App execute dentro da pasta AppWeather o comando;
expo start
```

# Projeto

Ao abrir o aplicativo o sistema identifica por geolocalização a localização do celular   capturando as informações de latitude e longitude. Atraves destas informações (alt+lat) é consumido a API da GH Brasil para retornar informações do clima da sua cidade.

![1][tela1]

Na tela é apresentado, nome da cidade, tipo de clima (nublado, chovendo, insolarado), se é dia ou noite, graus celsius, velocida do vento, humidade, hora Sunraise, Hora Sunset. Abaixo das informações do clima é apresentado uma lista do clima nos proximos 7 dias.

![3][tela3]

No menu pricipal, guia procurar, é possivel pesquisar o clima pelo nome da cidade e estado.

![2][tela2]  .... ![4][tela4]




[tela1]: T1.PNG
[tela2]: T2.PNG
[tela3]: T3.PNG
[tela4]: T4.PNG
