source :rubygems

# Server requirements
# gem 'thin' # or mongrel
# gem 'trinidad', :platform => 'jruby'

# Project requirements
gem 'rake'
gem 'sinatra-flash', :require => 'sinatra/flash'

gem 'pg'

# Component requirements
gem 'bcrypt-ruby', :require => "bcrypt"
gem 'compass'
gem 'haml'
gem 'activerecord', :require => "active_record"

group :development do
  gem 'sqlite3'
end

group :test do
  gem 'sqlite3'
end

# Test requirements
gem 'shoulda', :group => "test"
gem 'rack-test', :require => "rack/test", :group => "test"

# Padrino Stable Gem
gem 'padrino', '0.10.7'

# Or Padrino Edge
# gem 'padrino', :git => 'git://github.com/padrino/padrino-framework.git'

# Or Individual Gems
# %w(core gen helpers cache mailer admin).each do |g|
#   gem 'padrino-' + g, '0.10.7'
# end
