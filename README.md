# crowdfunder

This is a bootstrap of a personal crowd funding site built with Node.js using [Express 4](http://expressjs.com/), [Twitter Bootstrap](https://github.com/twbs/bootstrap), [Font Awesome](https://github.com/FortAwesome/Font-Awesome), [Bootstrap Social Buttons](https://github.com/noizwaves/bootstrap-social-buttons/)

Originally forked from [heroku/node-js-sample](https://github.com/heroku/node-js-sample).<br>
Started from the [Startup Engineering Course on Coursera](https://class.coursera.org/startup-001).

## Live example on Heroku
I currently have it hosted on Heroku. <br>
You can refer to http://mysterious-coast-9222.herokuapp.com/ for the live example.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
git clone git@github.com:jian-wei/crowdfunder.git # or clone your own fork
cd crowdfunder
npm install
npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
heroku create
git push heroku master
heroku open
```

Alternatively, you can deploy your own copy of the app using this experimental
web-based flow:

[![Deploy on Heroku](https://s3.amazonaws.com/f.cl.ly/items/12030r0c0J3z123k442i/deploy-button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [10 Habits of a Happy Node Hacker](https://blog.heroku.com/archives/2014/3/11/node-habits)
- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
