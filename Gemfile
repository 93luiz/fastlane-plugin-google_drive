source('https://rubygems.org')

gemspec

gem 'google_drive2', github: '93luiz/google-drive-ruby'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
