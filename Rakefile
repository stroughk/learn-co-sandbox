require_relative './config/environment'

def reload!
  load_all './lib'
end

task :console do 
Pry.start 
end 

task :scrape_rooms do 
  RoomsScraper.new().update_rooms
end 