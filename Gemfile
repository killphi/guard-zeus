source 'http://rubygems.org'

# Specify your gem's dependencies in guard-spin.gemspec
gemspec

gem "guard-bundler", "~> 1.0.0"
gem 'guard-rspec'

if RbConfig::CONFIG['target_os'] =~ /darwin/i
  gem 'growl', :require => false
end
if RbConfig::CONFIG['target_os'] =~ /linux/i
  gem 'libnotify', '~> 0.7.1', :require => false
end
