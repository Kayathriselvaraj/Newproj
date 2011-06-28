# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'rake/dsl_definition'
require 'rake'

#Use correct application name that matches for you
#module ::Newp
#  class Application
#    include Rake::DSL
#  end
#end
#
#module ::RakeFileUtils
#  extend Rake::FileUtilsExt
#end


Newp::Application.load_tasks
