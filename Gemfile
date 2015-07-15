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

#TODO should be in travis-core.gemspec?
gem 'stash-client',       github: 'final-ci/stash-client'
gem 'sidekiq-status',     github: 'utgarda/sidekiq-status', ref: 'e77d5dc2ea0a249ccbbafead21ece59d6b8caf73', require: nil
