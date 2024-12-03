# Angular Estudos

## Projetos inciados:
- [Repertorio](./resource/Repertorio)

## Recursos utilizados nas aplicações

### Requisições de APIs:
- [Observable](https://rxjs.dev/guide/observable)
- [HttpClient](https://angular.dev/guide/http)

### API para testes:
- [Json-Server](https://www.npmjs.com/package/json-server)

### Scripts para inicialziação de multiplos aplicativos:
- [Concurrently](https://www.npmjs.com/package/concurrently)

### Base de dados criada com:
- [Claude](https://claude.ai/chat/0e7e0274-8b86-4ea0-b2e1-7ac093aaff00)

## Estilização
- [Tailwind](https://tailwindcss.com/docs/guides/angular)
- [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## Pacotes
- [Angular Material](https://www.npmjs.com/package/@angular/material)


## Scripts:
```json
  "json-server": "npx json-server --watch db/musica.json",
  ...
  "stack": "concurrently \"npm run json-server\" \"ng serve -o\"",
  
```
