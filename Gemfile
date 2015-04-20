source 'https://rubygems.org'
ruby '2.2.2'

gem 'compass-rails', '~> 2.0.0'
gem 'dalli', '~> 2.7.0'
gem 'font-awesome-sass', '~> 4.3'
gem 'jquery-cdn', '~> 2.1.1'
gem 'kaminari', '~> 0.16.0'
gem 'mongoid', '~> 4.0.0'
gem 'rails', '4.2.1'
gem 'sass-rails', '~> 5.0'
gem 'text', '~> 1.3.0'
gem 'uglifier', '~> 2.7'
gem 'unicorn', '~> 4.8.1', platforms: :ruby

group :development do
  gem 'foreman', '~> 0.60'
end

group :development, :test do
  gem 'coveralls', '~> 0.8', require: false
  gem 'rspec-rails', '~> 3.2'
end

group :production do
  gem 'airbrake', '~> 4.1.0'
  gem 'newrelic_rpm', '~> 3.10'
  gem 'rails_12factor', '~> 0.0.2'
  gem 'skylight', '~> 0.6.0'
end

group :test do
  gem 'mocha', '~> 1.1.0', require: 'mocha/api'
end
