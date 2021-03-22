
namespace :greeting do
  
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  
  task :hola do 
    puts "hola de Rake!"
  end 
  
  desc 'Make sure you have a 'console' rake task'
  task :console => :environment do 
    Pry.start
  end 
  
end 
