source :rubygems

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
 else
  puppetversion = ['>= 3.2']
end

gem 'rake'
gem 'puppet-lint'
gem 'puppet-syntax'
gem 'rspec-puppet'
gem 'puppetlabs_spec_helper'
gem 'puppet', puppetversion
