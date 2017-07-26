# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version 5
* bootstrap 4
* font-awesome-sass

______________________________________________________________________________


Put in your Gemfile

<!-- # Use sqlite3 as the database for Active Record -->
group :production do
  gem 'pg'
end
group :development do
  gem 'sqlite3', require: false
end


______________________________________________________________________________

<!-- #font-awesome-sass -->

Font Awesome = http://fontawesome.io/get-started/

Sass Ruby Gem
Use the Official Font Awesome Sass Ruby Gem to easily get Font Awesome Sass into a Rails or Compass project. Generously maintained by @supercodepoet.

Add this line to your application's Gemfile:

gem 'font-awesome-sass'

And then execute:
$ bundle

# bootstrap

gem 'bootstrap', '~> 4.0.0.alpha6'

source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.1.0'
end


______________________________________________________________________________

If you use Rails, add this to your e.g. application.scss:

@import "bootstrap";

@import "font-awesome-sprockets";
@import "font-awesome";


______________________________________________________________________________

Add this to app/layout/application.html

head
<!-- font-awesome link -->
<link href="https://fonts.googleapis.com/css?family=Nosifer|Orbitron|Trade+Winds" rel="stylesheet">

body
<!-- jQuery first, then Tether, then Bootstrap JS. -->
    <script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha384-A7FZj7v+d/sdmMqp/nOQwliLvUsJfDHW+k9Omg/a/EheAdgtzNs3hpfag6Ed950n" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" integrity="sha384-DztdAPBWPRXSA/3eYEEUWrWCy7G5KFbe8fFjk5JAIxUYHKkDx6Qin1DkWx51bBrb" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>
# media_woman
