source "https://rubygems.org"

gem "rails", "~> 4.1.0"
gem "mysql2"
gem 'will_paginate', '~> 3.0'
gem 'feed_parser', :git => "https://github.com/johnl/feed_parser.git", :ref => "fe4b7095"
# requires uuid-dev package on Ubuntu
#gem 'xapian-ruby'

# Make web-page-parser faster
platforms :ruby_18 do
  # Needs libonig-dev debian/ubuntu package
  gem "oniguruma", ">=1.1.0"
end

# web-page-parser requires Debian/Ubuntu package libonig-dev (on ruby1.8)
gem "web-page-parser", :git => "git://github.com/johnl/web-page-parser.git", :ref => "26ec446", :require => "web-page-parser"

gem "diff-lcs", '~>1.2.5', :require => "diff/lcs"

# Requires xapian library, best installed on Debian/Ubuntu with t
# package "libxapian-ruby1.8"
gem "xapian-fu", "~>1.5.0"

gem "lograge"

group :development do
  gem "rdoc"
  gem "sqlite3"
  gem "rspec-core"
  gem "rspec-rails"
  gem 'thin'
  gem 'capistrano', '~> 3.2.0'
  gem 'capistrano-bundler', '~> 1.1.2'
end
