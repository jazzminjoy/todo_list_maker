source 'https://rubygems.org'


gem 'rails', '4.0.5'

gem 'devise'
gem 'simple_form'
gem 'sass-rails', '~> 4.0.2'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  gem 'sdoc', require: false
end

# Add capybara to test version only
# Add gem shoulda-matches for writing tests 
group :test do
	gem 'capybara', '~> 2.1.0'
	gem 'shoulda-matchers', '~> 2.6.1'
end

# Add rspec to development and test environments
# Cannot use sqlite3 when deploying to Heroku
group :development, :test do
	gem 'rspec-rails', '~> 2.0'
	gem 'sqlite3'
end

# Must use postgresql database 12factor for deployment to Heroku
group :production do
	gem 'pg'
	gem 'rails_12factor'
end 
