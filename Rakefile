#!/usr/bin/env rake
require 'rake/testtask'
require "bundler/gem_tasks"

task :default => :test
Rake::TestTask.new do |t|
  t.libs << 'test'
  t.pattern = 'test/**/*_test.rb'
  t.warning = true
  t.verbose = true
end
