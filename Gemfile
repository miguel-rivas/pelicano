source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# ----- apps:begin
gem 'bucaro', path: 'gems/bucaro'
gem 'guinea', path: 'gems/guinea'
gem 'colibri', path: 'gems/colibri'
gem 'paloma', path: 'gems/paloma'
gem 'pavo', path: 'gems/pavo'
# ----- apps:end

gem 'sprockets-rails', '2.3.3'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0' 
gem 'bootsnap', '>= 1.4.2', require: false
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'

group :development do
	gem 'listen', '~> 3.2'
#   gem 'web-console', '>= 3.3.0'
#   gem 'spring'
#   gem 'spring-watcher-listen', '~> 2.0.0'
end

# group :development, :test do
#   gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
# end

group :test do
	gem 'capybara', '>= 2.15'
	gem 'cucumber'
	gem 'selenium-webdriver'
	gem 'webdrivers'
end

# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]