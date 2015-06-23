source 'https://rubygems.org'

# Specify your gem's dependencies in travis-sidekiq.gemspec
gemspec

gem 'sprockets', '~> 2.2.1'
gem 'travis-core',     github: 'final-ci/travis-core'
#gem 'travis-core',      path: '../travis-core'
gem 'travis-support',   github: 'final-ci/travis-support'
#gem 'travis-support',   path: '../travis-support'

gem "sentry-raven",     github: "getsentry/raven-ruby"
gem 'multi_json'

group :test do
  gem 'rspec'
  gem 'guard'
  gem 'guard-rspec'
  gem 'rb-fsevent'
  gem 'mocha'
end
