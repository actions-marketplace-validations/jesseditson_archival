# frozen_string_literal: true

require 'bundler/gem_tasks'
require 'rspec/core/rake_task'
require 'rubocop/rake_task'

RSpec::Core::RakeTask.new(:spec)

RuboCop::RakeTask.new

task default: :spec
task lint: :rubocop
task 'lint:fix': 'rubocop:auto_correct'
