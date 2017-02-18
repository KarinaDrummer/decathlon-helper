source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'
gem 'unicode'
gem 'listen'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'haml'
gem 'sass-rails', '~> 5.0'
gem 'uglifier'
gem 'coffee-rails'
gem 'therubyracer', platforms: :ruby
# gem 'therubyrhino', platforms: :jruby
gem 'jquery-rails'
gem 'jquery-turbolinks'
gem 'scrollbar-rails'
gem 'material_icons'
gem 'turbolinks'
gem 'jbuilder', '~> 2.5'
gem 'nokogiri'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'

group :development do
  gem 'web-console'
end
