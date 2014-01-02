source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '4.0.0.rc1'
gem 'jquery-rails'

group :production do
	gem 'pg'
end
group :development, :test do
	gem 'sqlite3'
end

gem 'rails_12factor', group: :production


group :assets do
	gem 'sass-rails', '~> 4.0.0.rc1'
	gem 'bootstrap-sass', '~> 3.0.3.0'
	gem 'uglifier', '>= 1.3.0'
	gem 'coffee-rails', '~> 4.0.0'
end


# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
