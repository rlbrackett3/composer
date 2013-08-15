source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0'

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'

gem 'turbolinks'

gem 'jbuilder', '~> 1.2'

gem 'devise'

gem 'figaro'

gem 'haml-rails'

gem 'sendgrid'

gem 'simple_form', '>= 3.0.0.rc'

gem 'unicorn'
gem 'foreman'

group :assets do
  gem 'therubyracer', :platform=>:ruby
end

group :development do
  gem 'sqlite3'
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :rbx]
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'html2haml'
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
end

group :development, :test do
  gem 'fabrication'
end

group :test do
  gem 'capybara'
  gem 'minitest-spec-rails'
  gem 'minitest-wscolor'
end

group :production do
  gem 'rails_12factor'
  gem 'pg'
end
