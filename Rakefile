require 'rubygems'
require 'hoe'

Hoe.plugin :git
Hoe.plugin :minitest
Hoe.plugin :travis

Hoe.spec 'ruby-growl' do
  developer 'Eric Hodel', 'drbrain@segment7.net'

  spec_extras['required_ruby_version'] = '>= 1.9.2'

  extra_deps << ['uuid', '~> 2.3', '>= 2.3.5']
end

