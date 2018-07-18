namespace :greeting do
  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
  end
end

namespace :db do
  desc 'might the changes to your database'
  task :environment do
    require_relative './config.environment.rb'
  end
  task :migrate => :environment do
    Student.create_table
  end
end
