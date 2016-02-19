source 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? "#{ENV['PUPPET_VERSION']}" : ['>= 3.3']
gem 'puppet', puppetversion

group :test, :development do
  gem 'puppetlabs_spec_helper', '>= 0.8.2', require: false
  gem 'puppet-lint', '>= 1.0.0',            require: false
  gem 'facter', '>= 2.0.1',                 require: false
  gem 'metadata-json-lint',                 require: false
  gem 'librarian-puppet',                   require: false
end
