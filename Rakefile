require "rake/testtask"
require "bundler/gem_tasks"
require "bundler/setup"

desc "Default: run unit tests."
task default: :test

Rake::TestTask.new(:test) do |t|
  t.libs << "test"
  t.pattern = "test/**/*_test.rb"
end
