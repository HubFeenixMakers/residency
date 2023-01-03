source "https://rubygems.org"

ruby "3.0.4"

gem "rails", "~> 7.0"

gem "sprockets-rails"
gem "pg", "~> 1.1"

gem "importmap-rails"
gem "tailwindcss-rails"
gem "sassc-rails"

gem 'haml-rails'
gem 'html2haml'
gem 'devise'
gem 'carrierwave', '>= 3.0.0.beta', '< 4.0'

gem "ruby2js" , git: "https://github.com/ruby2js/ruby2js/" , branch: "haml_fix"
gem 'thredded', '~> 1.0'

gem "simple_form" , "5.1.0"
gem "simple_form_tailwind_css"

gem "merged" , git: "https://github.com/HubFeenixMakers/merged"
#gem "merged" , path: "../merged"

group :production do
  gem "passenger"
end

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "bootsnap", require: false
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "mina"
  gem 'guard-minitest'
  gem 'guard' # NOTE: this is necessary in newer versions
  gem "puma" ,  "~> 4.0"
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
