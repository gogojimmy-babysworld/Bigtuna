source 'http://rubygems.org'

gem "rails", "~> 3.0.11"
gem "mysql2", "0.2.6"
gem "delayed_job", "~> 2.1.4"
gem "haml"
gem "stringex"
gem "open4"
gem "json"
gem "jquery-rails"
gem "thin"

# ruby 1.9 compatible version
gem "scashin133-xmpp4r-simple", '0.8.9', :require => 'xmpp4r-simple'

# irc notification
gem "shout-bot"

# notifo notifications
gem "notifo"

# campfire notifications
gem "tinder"

gem 'capistrano'
gem 'capistrano-ext'
gem 'capistrano_colors'
gem 'rvm-capistrano'

group :development, :test do
  gem "capybara"
  gem "launchy"
  gem "faker"
  gem "machinist"
  gem "nokogiri"
  gem "mocha"
  gem "database_cleaner"
  gem "crack"

  platforms :mri_18 do
    gem "ruby-debug"
  end

  platforms :mri_19 do
    gem "ruby-debug19"
  end
end

group :test do
  gem "webmock"
end
