source 'https://rubygems.org'

group :lint do
  gem 'foodcritic', '~> 4.0'
  gem 'rubocop', '~> 0.27.0'
  gem 'rainbow', '< 2.0'
  gem 'rake'
end

group :unit do
  gem 'berkshelf',  '~> 3.2.0'
  gem 'chefspec',   '~> 3.1'
end

group :kitchen_common do
  gem 'test-kitchen', '~> 1.2.1'
end

group :kitchen_vagrant do
  gem 'kitchen-vagrant', '~> 0.15'
end

group :kitchen_cloud do
  gem 'kitchen-digitalocean'
  gem 'kitchen-ec2'
end

group :development do
  gem 'ruby_gntp'
  gem 'growl'
  gem 'rb-fsevent'
  gem 'guard', '~> 2.4'
  gem 'guard-kitchen'
  gem 'guard-foodcritic'
  gem 'guard-rspec'
  gem 'guard-rubocop'
end
