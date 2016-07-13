source 'https://rubygems.org'

gem 'sqlite3', :platforms => [:ruby]
gem 'activerecord-jdbcsqlite3-adapter', :platforms => [:jruby]

platforms :rbx do
  gem 'rubysl'
  gem 'rubysl-test-unit'
  gem 'rubinius-developer_tools'
end

rails = ENV['RAILS'] || '4.2.7'

gem 'rails', rails

# Specify your gem's dependencies in paranoia.gemspec
gemspec
