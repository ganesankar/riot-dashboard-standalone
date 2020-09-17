# Riot Dashboard Standalone

This is a sample project using Riot 4 which you need only browser to compile.


## Demo

[Demo Site](https://ganesankar.github.io/riot-dashboard-standalone/) - Type any username and password to login

## Stack 

1. [Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction/)  CSS Template and Design
2. [Riot 4](https://riot.js.org/) - Componet based UI Library
3. [Akita 4](https://netbasal.gitbook.io/akita/) - State Management [CDN](https://www.pika.dev/packages/@datorama/akita)
4. [Axios 0.19.0](https://github.com/axios/axios) - HTTP
5. [Navigo 6](https://github.com/krasimir/navigo) - Routing


## Running

you can use any http server on your machine. Clone this repo then

```
npm i -g hostr
```

Then open terminal from the directory

```
hostr
```

## Implementation

You can login using any credentials (type anyting in username and password). 
All dummy data files are located under `/functions/` folder. planned to have netlify lambda function as roadmap

All external libraries linked to  CDN to make simple

