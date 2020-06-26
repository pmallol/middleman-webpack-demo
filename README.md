# Middleman app using Webpack

Plus, it's dockerized and configured to be continuously deployed to GitHub Pages as a bonus!

![](/screenshots/screenshot.png)

Make your Middleman app's deployment run smoothly with [GitHub Actions](https://github.com/features/actions).
Check out it's [workflow file](https://github.com/pmallol/middleman-webpack-demo/blob/master/.github/workflows/deploy.yml) to see what's happening under the hood.

## Project setup

1. [Download Docker](https://www.docker.com/get-started) (if you haven't already)
1. Clone this repository
1. Open a terminal session in the root of your project and run:

```
$ docker-compose up
```

That's it! You're good to go.


## Useful commands

### Builds a new docker image
```
$ docker-compose build
```

### Builds Middleman framework
```
$ docker-compose run --rm web bundle exec middleman build
```
