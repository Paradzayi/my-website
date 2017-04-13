# My website

To keep transparency I have decided to open source my website. Feel free to clone it modify and use it as you wish to your own gain. If you like it don't forget to star it.

## Contibuting

I really apreciate contributions to the site. Feel free to create pull requests for any features you like me to implement. You can also create issues reporting bugs like typos.

## Licence

This website is licenced under the [MIT](LICENCE.md) licence which basicaly means that you can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of this website. You can read more in the LICENCE.md file.

## Running Locally

Make sure you have [Git](http://git-scm.com), [Node.js](http://nodejs.org/) installed. The [Heroku Toolbelt](https://toolbelt.heroku.com/) is optional if you want to host your version of this website on heroku.

```sh
$ git clone git@github.com:paradzayi/my-website.git # or clone your own fork
$ cd my-website
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying

You can deploy this web app to any host that supports nodejs. I am using the free tier at heroku so you can check it out.

### Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Credit

The site makes use of the following open source projects
* [nodejs](https://nodejs.org)
* [semantic ui](https://semantic-ui.com)
* [express](http://www.expressjs.com)
* [ejs](https://github.com/mde/ejs)
