source('https://rubygems.org')

gemspec

source 'https://github.com/93luiz/google-drive-ruby' do
    gem 'google_drive2'
end

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
