source 'https://rubygems.org'

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 2.7']
end

gem 'rake'
gem 'puppet-lint'
gem 'rspec-puppet'
gem 'rspec-puppet-facts'
gem 'puppetlabs_spec_helper'
gem 'metadata-json-lint'
gem 'puppet', puppetversion
