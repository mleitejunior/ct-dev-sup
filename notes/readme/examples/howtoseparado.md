<h1 align="center">
  <img alt="be the Hero" src="./frontend/src/assets/logo.svg" width="400px" />
    <br>
</h1>

<h1 align="center">
   Application Be the Hero 
</h1>

<h4 align="center">
  Be the Hero, application connects people who are willing to help and often do not have time, and can help some monetary forms for non-profit applications that are often needed for a specific amount to handle a specific case.
</h4>

<p align="center">
<img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/joaomenna1/be_the_hero?color=E02041">
<img alt="Made by Joao nogueira" src="https://img.shields.io/badge/made%20by-joaomenna1-%20?color=E02041">
<img alt="Project top programing language" src="https://img.shields.io/github/languages/top/joaomenna1/be_the_hero?color=E02041">
<img alt="GitHub license" src="https://img.shields.io/github/license/joaomenna1/be_the_hero?color=7159C1">
</p> 

<p align="center">
  <a href="#rocket-built-with">Built with</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#page_facing_up-license">Licence</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#mailbox_with_mail-get-in-touch">Get in touch</a>
</p>
<br><br>

## :rocket: Built with

This project was developed with the following technologies:

-  [Node.js](https://nodejs.org/)
-  [Express](https://expressjs.com/)
-  [knex](http://knexjs.org/)
-  [sqlite3](https://sqlitebrowser.org/)
-  [axios](https://github.com/axios/axios)
-  [React Native](https://facebook.github.io/react-native/)
-  [Expo](https://expo.io/learn)
-  [Expo-Mail-Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
-  [React Navigation](https://reactnavigation.org/)
-  [react-native-gesture-handler](https://software-mansion.github.io/react-native-gesture-handler/docs/getting-started.html)
-  [Celebrate](https://www.npmjs.com/package/celebrate)
-  [Jest](https://jestjs.io/)
-  [VS Code](https://code.visualstudio.com/)

## :information_source: How to run
### Requirements
To run the app, you will need [Git](https://git-scm.com), [Node.js](https://nodejs.org/) v12.13.1 or higher, [Yarn](https://yarnpkg.com/), [SQLite3](https://sqlitebrowser.org/).
<br>

### Backend
Now clone the repository and install the dependencies.
```bash
# to clone the repository
git clone https://github.com/joaomenna1/be_the_hero.git

# go into the backend folder
cd be_the_hero/backend

#install the backend dependencies
yarn or npm install

```
In order to connect to the database, you will need to enter the access informations into a .env file, based on a .env.example file that is provided in the backend folder, change the variables according to your environment.
```bash
# run migrations
yarn knex migrate:latest
  &
npm knex migrate:latest


# run api
yarn dev & npm run dev
```
### Frontend

```bash
# in another tab of the terminal install the frontend dependencies and run it 
cd frontend
yarn
yarn start & npm install
```
Use this credentials to access the web application

### Mobile

The Application was developed using Expo. It is a free and open source toolchain built around React Native to facilitate the process of running and testing applications. [Click here](https://expo.io/learn) to get start with Expo.

```bash
# install the dependencies
cd mobile
yarn
```

In order to run the application on your device, you need to change the ip config.

[api.js](https://github.com/joaomenna1/be_the_hero)
```javascript
  baseURL: 'http://192.168.0.235:3333',
```
replace 192.168.0.235 with your machine's ip.

Now with everything on place, run the application.

```bash

# to run the app
yarn start

```
Expo will open a page in your browser, scan the QRcode on the page and wait for the app to load.

> The Application was developed and tested on android 9.0 moto g6

---

## :page_facing_up: License

This project is under the MIT license. See the [LICENSE](https://github.com/joaomenna1/be_the_hero/blob/master/LICENSE) for more information


## :mailbox_with_mail: Get in touch!

[LinkedIn](https://linkedin.com/in/nogueira-menna-barreto)

---

Made with :coffee: and ♥ by Jamelão.
