source 'https://rubygems.org'
 
 git_source(:github) do |repo_name|
   repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
   "https://github.com/#{repo_name}.git"
 end
 
 ruby '3.0.1'
 # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
 gem 'rails'
 
 # #1
 group :production do
   # Use pg as the production database for Active Record
   gem 'pg'
   gem 'rails_12factor'
 end
 
 # #2
 group :development do
   # Use sqlite3 as the development database for Active Record
   gem 'sqlite3'
 end
 
 # Use Puma as the app server
 gem 'puma'
 # Use SCSS for stylesheets
 gem 'sass-rails'
 # Use Uglifier as compressor for JavaScript assets
 gem 'uglifier'
 
 # Use jquery as the JavaScript library
 gem 'jquery-rails'
 # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
 gem 'turbolinks'
 # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
 gem 'jbuilder'
 
 gem 'thor'
 
 group :development do
   gem 'listen'
   gem 'pry-rails'
 end
 
 group :development, :test do
   gem 'rspec-rails'
   gem 'rails-controller-testing'
   gem 'shoulda'
 end
 
 gem 'bootstrap'
 gem 'bcrypt'
 gem 'figaro'
