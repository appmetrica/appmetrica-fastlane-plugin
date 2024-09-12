source('https://rubygems.org')

gem 'racc'
gem 'rake'
gem 'rubocop'
gem 'rubocop-performance'
gem 'rubocop-rake'
gem 'rubocop-rspec'
gemspec

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
