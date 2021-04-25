# frozen_string_literal: true

source 'https://rubygems.org'

gem 'jekyll', '~> 4.0.0'                                          # Jekyll, the static site generator
gem 'jemoji', '~> 0.12.0'                                         # Jekyll emoji plugin
gem 'rake', '~> 13.0', '>= 13.0.3'                                # Rake Tasks
if Gem.win_platform?
  gem 'wdm', '>= 0.1.0'                                           # Performance-booster for watching directories on Windows
end

group :development do
  gem 'bcrypt_pbkdf', '>= 1.0', '< 2.0'                           # Resolve OpenSSH problems with capistrano
  gem 'capistrano', '~> 3.14', :require => false                  # Deployment
  gem 'capistrano-bundler', '~> 2.0', :require => false           # Capistrano bundler integration
  gem 'ed25519', '>= 1.2', '< 2.0'                                # Resolve OpenSSH problems with capistrano
  gem 'rubocop', :require => false                                # Ruby code style checker
  gem 'rvm1-capistrano3', :require => false                       # Capistrano rvm integration
end
