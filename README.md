#Media Woman
Social media marketing is more than sharing content.


Media Woman uses web-based and mobile technologies to create highly interactive platforms through which individuals, communities and organizations can share.

Social media changes the way individuals and large organizations communicate.

Social Media presents businesses with a direct line to their current and potential customers.

______________________________________________________________________________





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


# bootstrap
-Put in your Gemfile

gem 'bootstrap', '~> 4.0.0.alpha6'

source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.1.0'
end


______________________________________________________________________________

#font-awesome-sass

Font Awesome = http://fontawesome.io/get-started/

Sass Ruby Gem
Use the Official Font Awesome Sass Ruby Gem to easily get Font Awesome Sass into a Rails or Compass project. Generously maintained by @supercodepoet.

Add this line to your application's Gemfile:

gem 'font-awesome-sass'

And then execute (Terminal):
$ bundle




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



______________________________________________________________________________


    Resources:

    https://www.lyfemarketing.com/

    https://sproutsocial.com/insights/social-media-and-business/

    https://en.wikipedia.org/wiki/Social_media#Social_media_automation
