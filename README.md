== README

```rb
gem 'haml-rails'

group :development, :test do
  gem 'rspec-rails'
end

group :test do
  gem 'capybara'
end
```

```sh
rails generate rspec:install
```