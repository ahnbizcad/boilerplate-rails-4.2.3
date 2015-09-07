# README

## Anatomy
### Major parts
* ruby 2.2.2
* rails 4.2.3
* database: sqlite3

### Testing
* test suite: 
* debugging: pry, byebug
* Services (job queues, cache servers, search engines, etc.):

### Config & Settings Management
* turbolinks is OFF
* application preloader: spring
* secret credentials & management: figaro

#### Preprocessors
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

### Installing

* figaro
* simpleform
* devise