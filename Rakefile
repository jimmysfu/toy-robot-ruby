require 'rake'
require 'rspec/core/rake_task'

task default: [ :specs]

RSpec::Core::RakeTask.new(:specs) do |spec|
  spec.pattern = 'spec/*_spec.rb'
  spec.rspec_opts = ['--backtrace']
end