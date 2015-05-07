# Ruby on Rails Tutorial: sample application

This is the sample application for
the [*Ruby on Rails Tutorial*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

### How to install this project
Clone the repository to your local machine
```sh
cd apps
git clone https://github.com/jacobtarr/sample_app.git
cd sample_app
```
Install the necessary dependencies for Rails
```sh
bundle install --without production
bundle exec rake db:migrate
```
Start the server
```sh
rails s
```
