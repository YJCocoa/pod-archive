source "https://rubygems.org"
ruby '2.7.5'

gem 'cocoapods'
gem 'fastlane'
gem 'fastlane-plugin-versioning'
gem 'fastlane-plugin-pgyer'
gem 'cocoapods-hmap-prebuilt'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
