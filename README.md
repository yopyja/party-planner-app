# party-planner-app

## Why Pug Party Planner?

It's a simple app that is intended to teach me...
 - How to setup a Front end using:
   - Vuejs
   - Pug    - npm
   - Sass
 - How to setup a Backend using:
   - Java   - Maven
 - How to setup a database using:
   - Oracle DB 18c Express Edition
 - How to containerize each part of the app like:
   - Tomcat 10 (frontend and backend)
   - Oracle DB 18c
   - Nginx
   - Testing
 - How to set env-vars for the following:
   - Dev
   - Test
   - Prod


## What will this app consist of

Pages
 - planner (send/revoke invites to people) 
 - guest (people create/update/delete) 
 - events (party create/update/delete) 
 - viewer (display info either tied to party or individual) api select call usage
 - login page is a joke


-- Testing will exist in the project but I dont expect it at all bc testing sucks --
UnitTest (optional)
 - Mocha
E2E
 - Selenium Cucumber in Js (super super cool)


## Project setup

Recomended tools
Docker
VSCode
SourceTree
DBeaver
Insomnia
Webdriver (v89)


For windows follow this and setup WSL2 (Mac and Linux skip this)
https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10

### CD into src/frontend and run these to work on the front end
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

### CD into Test and run these
```
npm install
```

```
npm test
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).