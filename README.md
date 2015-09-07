# README

## Anatomy

Built on Mac

### Major parts
* ruby 2.2.2
* rails 4.2.3
* database: mongoDB with mongoid

### Testing
* test suite: 
* debugging: pry, byebug
* Services (job queues, cache servers, search engines, etc.):

### Config & Settings Management
* turbolinks is OFF
* application preloader: spring
* secret credentials & management: figaro

### Preprocessors
* html preprocessor: slim
* css preprocessor: stylus
* js preprocessor: opal

### Main Gems
* authentication: devise
* omniauth
* simpleform


## Configuring

### Renaming the App

Search the app for "YourAppName" and rename to desired app name. Change names in the following three locations:

* /config/application.rb
* /config/initializers/session_store.rb
* /app/views/layouts/application.html.slim

* /config/mongoid.yml

### Configure Gems

###### Mongoid
See:
[Official MongoDB ruby guide](http://docs.mongodb.org/ecosystem/tutorial/ruby-mongoid-tutorial/#ruby-mongoid-tutorial)
[Ademar Tutor Blog - Setup MongoDB with Rails](http://www.ademartutor.com/setup-mongodb-with-rails/)

###### Figaro
[Figaro](https://github.com/laserlemon/figaro)

###### Simpleform
[Simple_form](https://github.com/plataformatec/simple_form)

###### Devise

