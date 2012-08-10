source 'https://rubygems.org'

gem 'rails',        '~> 3.2.8'
gem 'heroku',       '~> 2.21.0'
gem 'simple_form',  '~> 2.0.0'
gem 'pry',          '~> 0.9.9.0'

# ------------ DB ------------ #

gem 'pg', '~> 0.13.0'

# group :development, :test do
#   gem 'sqlite3'
# end

# ------------ ASSETS ------------ #

gem 'haml-rails',     '~> 0.3.0'
gem 'bootstrap-sass', '~> 2.0.1'
gem 'jquery-rails',   '~> 2.0.0'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

# ------------ REFINERYCMS ------------ #

gem 'refinerycms', '~> 2.0.0'

# Specify additional Refinery CMS Extensions here (all optional):
gem 'refinerycms-i18n', '~> 2.0.0'
#  gem 'refinerycms-blog', '~> 2.0.0'
#  gem 'refinerycms-inquiries', '~> 2.0.0'
#  gem 'refinerycms-search', '~> 2.0.0'
#  gem 'refinerycms-page-images', '~> 2.0.0'

# ------------ TEST SUITE ------------ #
group :test do
  gem 'cucumber-rails',    '~> 1.3.0'
  gem 'capybara',          '~> 1.1.0'
  gem 'rr',                '~> 1.0.4'
  gem 'turn', :require => false
  gem 'database_cleaner',   '~> 0.7.2'
  gem 'factory_girl_rails', '~> 3.0'
  gem 'shoulda',            '~> 3.1.1'
end

group :development, :test do
  gem 'rspec-rails',   '~> 2.9.0'
  gem 'jasminerice',   '~> 0.0.9'
  gem 'guard-jasmine', '~> 1.5.0'
end