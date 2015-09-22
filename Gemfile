source 'https://rubygems.org'

ruby '2.3.0'

gem 'dotenv-rails', groups: [:development, :test]

gem 'rails', github: 'rails/rails'
gem 'sprockets-rails', '2.3.3'
gem 'devise', github: 'twalpole/devise', branch: 'rails5'
gem 'pundit'
gem 'puma'
gem 'jquery-rails'
gem 'nested_form'
gem 'active_hash'
gem 'sanitize'
gem 'gmaps4rails'
gem 'geocoder'
gem 'omniauth-google-oauth2'
gem 'omniauth-meetup'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-github'
gem 'gravatar_image_tag'
gem 'simple_form', github: 'plataformatec/simple_form', branch: 'lm-test-rails-5'
# TODO: find replacement, not compatible with rails 5
# gem 'rack-canonical-host'
gem 'icalendar'
gem 'pg' if ENV['FORCE_POSTGRES']
gem 'rack-mini-profiler'
gem 'bower-rails'
gem 'rack', github: 'rack/rack'
gem 'arel', github: 'rails/arel'

group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'heroku_rails_deflate'
  gem 'newrelic_rpm'
  gem 'sentry-raven'
  gem 'rack-timeout'
end

gem 'handlebars_assets'
gem 'sass-rails', '5.0.4'
gem 'coffee-rails'
gem 'uglifier'
gem 'bootstrap-sass'
gem 'font-awesome-rails'
gem 'jquery-ui-rails'
gem 'backbone-on-rails'
gem 'masonry-rails'

group :development do
  gem 'quiet_assets'
  gem 'rb-fsevent'
  gem "bullet"
  gem "heroku_san"
  gem "better_errors"
  gem "binding_of_caller"
  gem "byebug"
end

group :test, :development do
  gem 'jasmine'
  gem 'jasmine-jquery-rails'
  gem 'sqlite3'
  gem 'rspec-rails', github: 'rspec/rspec-rails'
  gem 'rspec-mocks', github: 'rspec/rspec-mocks'
  gem 'rspec-support', github: 'rspec/rspec-support'
  gem 'rspec-core', github: 'rspec/rspec-core'
  gem 'rspec-expectations', github: 'rspec/rspec-expectations'
  gem 'rspec-collection_matchers'
  gem 'awesome_print'
  gem 'rails-controller-testing'
end

group :test do
  gem 'webmock'
  gem "factory_girl_rails"
  gem 'capybara', github: 'tjgrathwell/capybara', branch: 'rails5'
  gem "poltergeist"
  gem "launchy"
  gem 'shoulda-matchers'
  gem "faker"
  gem 'capybara-screenshot'
  gem 'database_cleaner'
end
