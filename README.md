Heroku buildpack: Headless Chrome
=================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for retrieving a headless Chrome build.

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/minted/heroku-buildpack-chrome-headless

# or if your app is already created:
$ heroku buildpacks:add https://github.com/minted/heroku-buildpack-chrome-headless

$ git push heroku master
```
