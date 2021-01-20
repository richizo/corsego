source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.2"

gem "rails", "~> 6.1.1"
# gem 'rails', github: 'rails/rails', branch: 'master'
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 4.1"
gem "sass-rails", ">= 6"
gem "webpacker", "~> 4.0"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.7"
gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "standard", group: :development
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "haml-rails", "~> 2.0" # HTML abstraction markup language
# gem 'font-awesome-sass', '~> 5.12.0' #add icons for styling #installed via yarn withot gem
gem "simple_form" # creating forms made easier
gem "faker" # fake data for seeds.rb
gem "devise" # authentication as a User
# gem 'devise', :git => "https://github.com/heartcombo/devise.git", ref: '8bb358cf80a632d3232c3f548ce7b95fd94b6eb2' # https://stackoverflow.com/questions/65702896/latest-omniauth-facebook-gem-breaks-devise
gem "friendly_id", "~> 5.2.4" # nice URLs and hide IDs
gem "ransack" # filter and sort data
gem "public_activity" # see all activity in the app
gem "rolify" # give users roles (admin, teacher, student)
gem "pundit" # authorization (different roles have different accesses)
gem "exception_notification", group: :production # email notifications if any errors in production
gem "pagy" # pagination
gem "chartkick" # charts #yarn add chartkick chart.js
gem "groupdate" # group records by day/week/year
gem "rails-erd", group: :development # sudo apt-get install graphviz; bundle exec erd
gem "ranked-model" # give serial/index numbers to items in a list
gem "aws-sdk-s3", require: false # save images and files in production
gem "active_storage_validations" # validate image and file uploads
gem "image_processing" # sudo apt install imagemagick
gem "recaptcha" # for new user registration
gem "wicked_pdf" # PDF for Ruby on Rails
gem "wkhtmltopdf-binary", group: :development
gem "wkhtmltopdf-heroku", group: :production
gem "wicked" # multistep forms
gem "omniauth", "~> 1.9.1" # Can not move to 2.0 because of devise - https://github.com/heartcombo/devise/pull/5327
gem "omniauth-google-oauth2" # sign in with google
gem "omniauth-github" # sign in with github
gem "omniauth-facebook" # sign in with facebook
gem "cocoon" # nested forms
gem "stripe" # accept payments 
gem 'sitemap_generator' # SEO and webmasters