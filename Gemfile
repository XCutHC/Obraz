source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.6'
gem 'sqlite3'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-turbolinks'
gem 'masonry-rails', '~> 0.2.4'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'devise', '~> 4.4', '>= 4.4.3'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5.0.0'
gem 'jbuilder', '~> 2.5'
gem 'paperclip', '~> 6.0'
gem 'will_paginate', '~> 3.1', '>= 3.1.6'
gem 'will_paginate-bootstrap', '~> 1.0', '>= 1.0.1'

group :development, :test do
  gem 'sqlite3'
end

group :production do
  gem 'pg', '0.18.2'
  gem 'rails_12factor', '0.0.3'
end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
