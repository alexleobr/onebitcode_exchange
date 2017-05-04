**Conversor de moeda**

![ruby](https://img.shields.io/badge/Ruby-2.4.1-red.svg)
![rails](https://img.shields.io/badge/Rails-5.1.0-red.svg)
![rails](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)

##Sintetização da ideia

Um site onde você pode ver o valor de conversão de uma moeda em outra.
(ex.: 10 reais para pesos uruguaios)

##Sintetização de funções do projeto

Conversão de X quantidades de uma moeda em Y quantidades de outra.

## [Clique e veja online](https://bc2-exchange.herokuapp.com/)

<!-- ![One Exchange](https://raw.githubusercontent.com/cheesepaulo/OneExchange/master/app/assets/images/screenshot.png) -->

# Stack
```
  * Application
```

# Dependencies
```
  * Fixer.io to consult currency rates
```

# Getting Started
```
  * docker-compose build
  * docker-compose run --rm website rake db:create db:migrate
  * docker-compose up
```

# Test
```
  * docker-compose run --rm website rspec
```
