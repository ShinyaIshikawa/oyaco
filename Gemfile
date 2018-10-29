source 'https://rubygems.org'
group :production, :staging do
  gem 'rails_12factor'
end
ruby '2.5.1'
gem 'rakuten_web_service'
gem 'autoprefixer-rails'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'google_custom_search_api'
gem 'jp_prefecture'
gem 'devise'
gem 'activeadmin'#, '~> 1.0.0.pre1'
gem 'font-awesome-sass'
gem 'wicked'
gem 'active_hash'
gem 'newrelic_rpm'
gem 'redis'
gem 'redis-rails'
gem 'month'
gem 'momentjs-rails', '~> 2.9',  :github => 'derekprior/momentjs-rails'
gem 'datetimepicker-rails', github: 'zpaulovics/datetimepicker-rails', branch: 'master', submodules: true
gem 'simple_form'
gem 'twitter-bootstrap-rails-confirm'
gem 'carrierwave'
gem 'cloudinary'
gem 'lightbox2-rails'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.1.0'
gem 'railties', '5.1.0'
# Use postgresql as the database for Active Record
gem 'pg', '0.21.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'#, '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
#gem 'therubyracer', platforms: :ruby
gem 'mini_racer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'rails-controller-testing'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
#  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'meta_request'
end
group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end
group :development do
  gem 'rails_best_practices'
end

group :test do
  gem "minitest", "5.10.1"
  gem "minitest-rails", "~> 3.0.0"
  gem "minitest-rails-capybara", "~> 3.0.0"
end
