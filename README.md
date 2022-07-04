# microfrontends com <a href="https://single-spa.js.org/">single-spa</a>

# Nomenclaturas: 
  MFE's: Micro frontends

```
	A estrutura utilizada para desenvolver os micro-frontends foi o single-spa,
  caso queira saber mais sobre como a mesma funciona é só clicar <a href="https://single-spa.js.org/">aqui</a> . 
	Para rodar o ambiente dos microfrontends no local, será necessário instalar dois micro-frontends, 
  sendo eles o root-config, react-app, angular-ap, react-nav, vue-app. 
```

Obs: A versão do node precisa ser a v16.13.2, ser for inferior ou superior irá gerar um erro de versão no terminal. 

Comandos importantes:
➜  Versão do Node
➜  node --version ou node -v
➜  v16.13.2

➜  Instalar dependências </br>
npm i

➜  Rodar o mfe </br>
npm start

#### Instalando o microfrontend root-config </br>
  <ul>
    <li> ➜  https://github.com/ccarol-freitas/root-config.git</li>
    <li> ➜  cd documents</li>
    <li> ➜  mkdir microfrontends</li>
    <li> ➜  cd microfrontends</li>
    <li> ➜  git clone https://github.com/ccarol-freitas/root-config.git</li>
    <li> ➜  cd  root-config</li>
    <li> ➜  git checkout -b develop</li>
    <li> ➜  git pull origin main</li>
    <li> ➜  npm i</li>
    <li> ➜  npm start</li>
    <li> ➜  root-config: http://localhost:9000/</li>
  </ul>

#### Instalando o microfrontend react-app </br>
  <ul>
    <li> ➜  https://github.com/ccarol-freitas/react-app.git</li>
    <li> ➜  cd documents</li>
    <li> ➜  cd microfrontends</li>
    <li> ➜  git clone https://github.com/ccarol-freitas/react-app.git</li>
    <li> ➜  cd  react-app</li>
    <li> ➜  git checkout -b develop</li>
    <li> ➜  git pull origin main</li>
    <li> ➜  npm i</li>
    <li> ➜  npm start</li>
    <li> ➜  react-app: http://localhost:8082/</li>
  </ul>
  
  #### Instalando o microfrontend react-nav </br>
  <ul>
    <li> ➜  https://github.com/ccarol-freitas/react-nav.git</li>
    <li> ➜  cd documents</li>
    <li> ➜  mkdir microfrontends</li>
    <li> ➜  cd microfrontends</li>
    <li> ➜  git clone https://github.com/ccarol-freitas/react-nav.git</li>
    <li> ➜  cd  react-nav</li>
    <li> ➜  git checkout -b develop</li>
    <li> ➜  git pull origin main</li>
    <li> ➜  npm i</li>
    <li> ➜  npm start</li>
    <li> ➜  root-config: http://localhost:8081/</li>
  </ul>
  
  #### Instalando o microfrontend angular-app </br>
  <ul>
    <li> ➜  https://github.com/ccarol-freitas/angular-app.git</li>
    <li> ➜  cd documents</li>
    <li> ➜  cd microfrontends</li>
    <li> ➜  git clone https://github.com/ccarol-freitas/angular-app.git</li>
    <li> ➜  cd  angular-app</li>
    <li> ➜  git checkout -b develop</li>
    <li> ➜  git pull origin main</li>
    <li> ➜  npm i</li>
    <li> ➜  npm start</li>
    <li> ➜  angular-app: http://localhost:4200/</li>
  </ul>
  
  #### Instalando o microfrontend vue-app </br>
  <ul>
    <li> ➜  https://github.com/ccarol-freitas/vue-app.git</li>
    <li> ➜  cd documents</li>
    <li> ➜  cd microfrontends</li>
    <li> ➜  git clone https://github.com/ccarol-freitas/vue-app.git</li>
    <li> ➜  cd  vue-app</li>
    <li> ➜  git checkout -b develop</li>
    <li> ➜  git pull origin main</li>
    <li> ➜  npm i</li>
    <li> ➜  npm run serve</li>
    <li> ➜  vue-app: http://localhost:8080/</li>
  </ul>


#### O ambiente vai estar rodando em:
http://localhost:9000
