source 'https://rubygems.org'
ruby "2.0.0"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~>4.0.3'
gem 'pg', '0.15.1'


group :development, :test do
  gem 'rspec-rails', '2.13.1'
  gem 'rspec-mocks'
end

group :development do
  gem 'guard-livereload'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', '4.0.0'
  gem 'guard-spork', '1.5.0'
  gem 'childprocess', '0.3.9'
  gem 'factory_girl_rails', '4.2.1'
  gem "launchy", "~> 2.1.2"
  gem "shoulda-matchers"
end
gem 'sass-rails', '~> 4.0.0'
gem "compass-rails"
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails', '~>3.1.0'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
#gem 'honeybadger'

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'rails_12factor', '0.0.2'
end

gem 'unicorn'
gem 'spree', github: 'spree/spree', branch: '2-2-stable'
gem 'spree_gateway', :git => 'https://github.com/spree/spree_gateway.git', :branch => '2-2-stable'
gem 'spree_auth_devise', :git => 'https://github.com/spree/spree_auth_devise.git', :branch => '2-2-stable'