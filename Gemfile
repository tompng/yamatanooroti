source 'https://rubygems.org'
require 'rbconfig'

unless RbConfig::CONFIG['host_os'].match?(/mswin|msys|mingw|cygwin|bccwin|wince|emc/)
  gem "vterm", github: "ruby/vterm-gem"
end

# Specify your gem's dependencies in reline.gemspec
gemspec

group :development do
  gem 'rake'
  gem 'bundler'
  gem 'reline'
end
