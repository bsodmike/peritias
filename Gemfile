source 'https://rubygems.org'

ruby "1.9.3"
gem 'rails', '3.2.8'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
  gem 'yui-compressor'
  #gem 'jquery-fileupload-rails'
end

# infrastructure
gem 'unicorn'
gem 'sqlite3', :group => [:development, :test]
#gem 'mysql2'
#gem 'devise'
#gem 'cancan', :git => "git://github.com/ryanb/cancan.git", :branch => "2.0"
#gem 'state_machine'
#gem 'paperclip'
#gem 'curb'
#gem "delocalize"
#gem 'tire'

# base objects
gem 'attribute_normalizer'
gem 'strong_parameters'
gem 'acts_as_list'
gem 'squeel'
gem 'paranoia'

# views
gem 'jquery-rails'

gem 'rspec-rails', :group => [:development, :test]

group :development do
  gem 'thin'
  gem 'pry'
  gem 'debugger'
  gem 'foreman'
  gem 'awesome_print'
  gem 'rails-erd'
end

group :test do
  gem 'fuubar'
  gem 'guard-rspec'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'rb-fsevent'
  gem "spork", "> 0.9.0.rc"
  gem "guard-spork"
  gem 'guard'
end
