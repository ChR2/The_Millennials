source 'https://rubygems.org'
gem 'rails', '4.1.6'
gem 'pg'
gem 'bcrypt-ruby', '~> 3.1.2'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'

gem 'spring',        group: :development

group :test, :development do
  gem 'dotenv-rails'
  gem 'rspec-rails', '~> 3.0.0'
  gem 'faker'
end

group :test do
  gem 'factory_girl_rails', '~> 4.0'
  gem 'shoulda-matchers'
end

group :production do
  gem 'thin'
  gem 'rails_12factor'
end
