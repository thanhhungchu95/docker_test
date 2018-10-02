source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap"
gem "config"
gem "dotenv-rails"
gem "i18n-js"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "mysql2"
gem "paranoia"
gem "puma", "~> 3.11"
gem "rails", "~> 5.2.1"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "factory_bot_rails"
  gem "ffaker"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails"
  gem "rubocop", "~> 0.54.0", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "scss_lint", require: false
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "rails-controller-testing"
  gem "rspec-json_expectations"
  gem "rspec_junit_formatter"
  gem "shoulda-matchers"
end
