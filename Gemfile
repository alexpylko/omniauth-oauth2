source "http://rubygems.org"

gem "rake"

group :test do
  gem "coveralls"
  gem "json", :platforms => %i[jruby ruby_18 ruby_19]
  gem "mime-types", "~> 1.25", :platforms => %i[jruby ruby_18]
  gem "rack-test"
  gem "rest-client", "~> 1.7.3", :platforms => %i[jruby ruby_18]
  gem "rspec", "~> 3.2"
  gem "rubocop", ">= 0.51", :platforms => %i[ruby_19 ruby_20 ruby_21 ruby_22]
  gem "simplecov", ">= 0.9"
  gem "webmock"
end

# Specify your gem's dependencies in omniauth-oauth2.gemspec
gemspec
