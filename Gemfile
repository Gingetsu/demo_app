source 'https://rubygems.org'
# -*- encoding: utf-8 -*-
$:.push File.expand_path("../lib", __FILE__)
require 'image_suckr/version'
Gem::Specification.new do |s|
s.name = 'image_suckr'
s.version = ImageSuckr::VERSION
s.platform = Gem::Platform::RUBY
s.author = 'Mauricio Miranda'
s.email = 'maurimiranda@gmail.com'
s.homepage = 'https://github.com/maurimiranda/image_suckr'
s.summary = %q{Gets images randomly from the web}
s.description = %q{ImageSuckr is a ruby gem that allows you to get random images from Google for seeding purposes.}
s.license = 'GPL-3.0'
s.rubyforge_project = "image_suckr"
s.files = `git ls-files`.split("\n")
s.test_files = `git ls-files -- {test,spec,features}/*`.split("\n")
s.executables = `git ls-files -- bin/*`.split("\n").map{ |f| File.basename(f) }
s.require_paths = ['lib']
s.add_development_dependency 'rspec', '~> 3'
end
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
