# source :gemcutter  # DEPRICATED
source 'https://rubygems.org'

gem 'rails', '~> 2.3.18'

# bundler requires these gems in all environments
# gem 'nokogiri', '1.4.2'
# gem 'geokit'

group :production do
  # bundler requires these gems in production 
  gem 'pg'
end

group :development do
  # bundler requires these gems in development
  # gem 'rails-footnotes'
  gem 'sqlite3-ruby', :require => 'sqlite3'
  gem 'heroku'
end

group :test do
  # bundler requires these gems while running tests
  # gem 'rspec'
  # gem 'faker'
end

