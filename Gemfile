source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Ruby ODM framework for MongoDB
gem 'mongoid', '~> 7.0'
gem 'mongoid-locker'
gem 'bson_ext'
# Devise is a flexible authentication solution for Rails based on Warden
# gem 'devise'
gem 'devise_token_auth', git: 'https://github.com/lynndylanhurley/devise_token_auth.git'
gem 'omniauth'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: 'bootsnap/setup'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

# Draper adds an object-oriented layer of presentation logic to your Rails application.
gem 'draper'

group :development, :test do
  gem 'rspec-rails', '~> 3.6'
  gem 'factory_girl_rails', '~> 4.8'
  gem 'database_cleaner', '~> 1.6', '>= 1.6.1'
  gem 'email_spec', '~> 2.1'
  gem 'mongoid-rspec', git: 'https://github.com/mongoid-rspec/mongoid-rspec.git'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
