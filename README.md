<h1 align="center">Welcome to Forkify 👋</h1>

<p align="center" markdown="1">
  <img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/Slashflex/Forkify?style=flat-square">
  <img alt="Netlify" src="https://img.shields.io/netlify/99e9ec54-e3aa-4d05-b6b2-c3fc6eeb0088?style=flat-square">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Slashflex/Forkify?style=flat-square">
</p>

> Recipe finder app created using ES6 JS, NodeJS, NPM, WebPack, Babel, Node-SASS(scss synthax), 7-1 pattern and BEM methodology.

## Install

```sh
npm install 
# This will install Dev Dependencies locally based on package.json
```
Some dependencies are required to be able to run the project, to install them run:
```sh
npm install --save @babel/polyfill axios fractional uniqid
```

## Usage (If you want to make any modifications to files)

```sh
npm run start
# This will run webpack-dev-server --mode development --open --watch
# This command will open a new tab on your default web browser and watch for any changes on JS, HTML or SCSS files and reload the page once webpack has done it's job of bundling :D 
```

## This project is powered by an API
Originally the API used to build this project was [food2fork](https://www.food2fork.com/) but this website will close on 30th November 2019, therefore i had to use a part of this API which i found [here](https://forkify-api.herokuapp.com/), thanks to [Jonas Schmedtmann](https://github.com/jonasschmedtmann).

## How does the application work
Therefore instead of being able to search over 1.000.000 recipes using the Food2fork API, you can now only search with ```pizza```, ```broccoli``` or ```bacon``` words in the app's search bar.

If you type in one of the above three words inside the search bar and hit ```search``` or type ```enter``` on keyboard, the datas from the API will be parsed and be returned in the left part of the app:
![Parsed results](https://i.imgur.com/uI2lOpt.png)
There is 30 results displayed for each of the three recipe type (```pizza```, ```broccoli``` or ```bacon```), 10 results are displayed per page, so a pagination system is displayed on the bottom to be able to show the differents pages:
![Pagination](https://i.imgur.com/erR6Wkd.png)

Once you click on a recipe on the left, it is then displayed in the middle of the screen like so:
![Recipe](https://i.imgur.com/1cXTL76.png)

Once displayed, you can then update the servings by hovering on ```+``` or ```-```, this will update the ingredients accordingly:
![Update servings](https://i.imgur.com/FEW128t.png)

You can also ```like``` or ```unlike``` recipe(s) by clicking the ```heart button```:
![Liked](https://i.imgur.com/dq7uuDo.png)
![Unliked](https://i.imgur.com/522ie7Y.png)

The liked recipe(s) will then be displayed in the top right corner of the app by hovering on the ```heart shapped icon```:
![Liked recipe(s)](https://i.imgur.com/pO7EPIf.png)


Have fun :D



## Author

👤 **Slashflex (David)**

* Twitter: [@saoud_david](https://twitter.com/saoud_david)
* Github: [@Slashflex](https://github.com/Slashflex)

## Result can be seen here
[Forkify](https://forkify-native-es6.netlify.com/)
## Show your support

Give a ⭐️ if you liked this project !