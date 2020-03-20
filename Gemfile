source "https://rubygems.org"

group :test do
  gem "rake"
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.7.0'
  gem "puppet-lint"
  gem "puppet-lint-unquoted_string-check"
  gem "rspec-puppet", :git => 'https://github.com/rodjek/rspec-puppet.git'
  gem "puppet-syntax"
  gem "puppetlabs_spec_helper"
  gem "metadata-json-lint", ">= 0.0.6"
end

group :development do
  gem "travis", ">= 1.7.5"
  gem "travis-lint", ">= 2.0.0"
  gem "beaker", :git => 'https://github.com/puppetlabs/beaker.git'
  gem "beaker-rspec"
  gem "puppet-blacksmith"
  gem "guard-rake"
end
