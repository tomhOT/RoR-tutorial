# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
task 'test:prepare' do
  sh "bundle exec rake db:migrate RAILS_ENV=test"
end

Rails.application.load_tasks
