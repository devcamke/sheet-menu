source "https://rubygems.org"

ruby "3.3.0"

gem "bootsnap", require: false
gem "importmap-rails"
gem "jbuilder"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "rails", "~> 7.1.2"
gem 'redis', '~> 5.0', '>= 5.0.8'
gem "sassc-rails"
gem "sprockets-rails"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ windows jruby ]

group :development, :test do
  gem 'factory_bot_rails', '~> 6.4', '>= 6.4.3'
  gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'main'
  gem "pry-rails"
  gem 'rspec-rails', '~> 6.1'
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

end

group :test do
  gem 'shoulda-matchers', '~> 6.0'
  
end

# Gemfile.lock
