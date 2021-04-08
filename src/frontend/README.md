# party-planner-app

## Why Pug Party Planner?

It's a simple app that is intended to teach me...
 - How to setup a Front end using:
   - Vuejs
   - Pug
   - Sass
 - How to setup a Backend using:
   - Java
 - How to setup a database using:
   - postgres
 - How to handle DB calls to a Calculations service using
   - Java
 - How to containerize each part of the app listed above with the addition of:
   - Nginx
   - Testing
   - ProdBuildDemo?
 - How to set env-vars for the following:
   - Dev
   - Test
   - Prod


## What will this app consist of

Pages
 - planner (send/revoke invites to people) calculations usage
 - guest (people create/update/delete) api usage
 - events (party create/update/delete) api  usage
 - viewer (display info either tied to party or individual) api select call usage


FrontEnd
 - vuejs (js)
 - pug (html)
 - sass (css)
BackEnd / Calculations
 - java
DataBase
 - postgres (sql)

-- Testing will exist in the project but I dont expect it at all bc testing sucks --
UnitTest (optional)
 - Mocha
E2E
 - Selenide



## Project setup

Recomended tools
WSL2
Docker
VSCode
SourceTree
DBeaver
Postman or Insomnia


For windows follow this and setup WSL2 (Mac and Linux skip this)
https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10

Once installed open VsCode and in the bottom left open the remote connections and remote into WSL.
Clone the project onto your WSL instance and follow the terminal commands bellow.

```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Lints and fixes files
```
npm run lint
```

### Runs simple selenium test in root/test folder
```
npm test
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
