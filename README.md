# Ruby-Rails-React-social-app

This is a Rails 6 web application setup with React 17 and Typescript 4.

Created for you is an API for 3 resources; User, Post, Comment, and Image.

Your challenge is to create a kind-of social media platform in React using this API. You could create an instagram clone, but it's encouraged you come up with your own design.

Feel free to expand the API and add more functionality, but it's not required.

API
API Documentation

Getting started
Fork this repo and run the following commands from inside the directory to get setup.

Setup rails
Install ruby (using rbenv)
brew install rbenv
rbenv install
Install gems
gem install bundler
bundle install
Setup database
rails db:setup
Setup npm
Install node (using nvm)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
nvm install
Install packages
nvm use
npm install -g yarn
yarn install
Starting the server
This will start rails and the webpack-dev-server. Webpack is setup with hot reloading.

foreman start
