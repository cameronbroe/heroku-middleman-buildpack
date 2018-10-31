[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcameronbroe%2Fheroku-middleman-buildpack.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcameronbroe%2Fheroku-middleman-buildpack?ref=badge_shield)

A basic buildpack for deploying a Middleman site to Heroku and serving with Caddy. It is important to note that you will need some things in your project for this to work.

A Procfile with the line

    web: caddy/caddy -root build/ -port $PORT

And this line in your Gemfile

    gem 'therubyracer'


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcameronbroe%2Fheroku-middleman-buildpack.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcameronbroe%2Fheroku-middleman-buildpack?ref=badge_large)