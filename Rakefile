# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'rake/dsl_definition'
require 'rake'

Spyapp::Application.load_tasks

task :web do
    sh 'cp -r ../../iphone/skyapp/www/* public/'
end
