ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'


desc 'it starts the console'
rake do 'console'
  Pry.start
end

# Type `rake -T` on your command line to see the available rake tasks.