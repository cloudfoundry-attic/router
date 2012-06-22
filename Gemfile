source "http://rubygems.org"

gem 'bundler', '>= 1.0.10'
gem 'rake'
gem 'nats', :require => 'nats/client'
gem 'eventmachine', :git => 'https://github.com/cloudfoundry/eventmachine.git', :branch => 'release-0.12.11-cf'

gem "http_parser.rb", :require => "http/parser"
gem "yajl-ruby", :require => ["yajl", "yajl/json_gem"]
gem "sinatra"

gem 'vcap_common', '~> 1.0.9', :git => 'https://github.com/cloudfoundry/vcap-common.git', :ref => 'c91898e1'
gem 'vcap_logging', :require => ['vcap/logging'], :git => 'https://github.com/cloudfoundry/common.git'

group :test do
  gem "rspec"
  gem "rcov"
  gem "ci_reporter"
end
