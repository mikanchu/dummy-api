
# dummy-api

A very simplistic API written in go to be deployed in Heroku

## Running Locally

Make sure you have [Go](http://golang.org/doc/install) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ go get -u github.com/mikanchu/dummy_api
$ cd $GOPATH/src/github.com/mikanchu/dummy_api
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

You should also install [Godep](https://github.com/tools/godep) if you are going to add any dependencies to the sample app.

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku open
```

or

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## Documentation

For more information about using Go on Heroku, see these Dev Center articles:

- [Go on Heroku](https://devcenter.heroku.com/categories/go)
