source 'https://rubygems.org'

gemspec

gem 'onesky-ruby', :git => 'https://github.com/niteshvijay1995/onesky-ruby.git', :branch => 'ruby2.4_support'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
