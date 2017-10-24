A basic buildpack for deploying a Middleman site to Heroku and serving with Caddy. It is important to note that you will need some things in your project for this to work.

A Procfile with the line

    web: caddy/caddy -root build/ -port $PORT

And this line in your Gemfile

    gem 'therubyracer'
