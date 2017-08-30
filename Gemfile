source 'https://rubygems.org'

gemspec

gem 'onesky-ruby', '1.0.1'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
