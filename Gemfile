source "http://rubygems.org"

gemspec

group :development do
  gem 'rack'
  gem 'rake'
  gem 'rdoc'
end

group :test do
  gem 'shoulda', '~> 2.0'
  gem 'jruby-openssl' if RUBY_PLATFORM[/java/]
end
