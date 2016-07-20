source "https://rubygems.org"

ruby "2.3.1"

gem "rails", "~> 5.0.0"

gem "coffee-rails", "~> 4.2"
gem "dotenv-rails"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "pg"
gem "puma", "~> 3.0"
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "byebug", platform: :mri
  gem "coffeelint"
  gem "jasmine", "> 2.0"
  gem "listen", "~> 3.0.5"
  gem "rspec-rails"
  gem "rubocop", require: false
  gem "rubocop-rspec", require: false
  gem "scss_lint", require: false
  gem "slim_lint", require: false
end

group :development do
  gem "foreman", require: false
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console"
end

group :test do
  gem "codeclimate-test-reporter", require: false
end

gem "tzinfo-data", platforms: %i(mingw mswin x64_mingw jruby)

group :staging, :production do
  gem "rails_12factor"
end
