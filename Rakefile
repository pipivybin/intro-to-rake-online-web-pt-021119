namespacing :greeting do

  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  task :hola do
    puts "hola de Rake!"
  end

end

namespacing :db do

  task :migrate => :environment do
    task :environment do
      require_relative './config/environment'
    end
    students.create_table
    end

    task :seed do
      require_relative './db/seeds'
    end


  end
