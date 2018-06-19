# ReplGame
def welcome_screen 
    puts "Welcome!"
def
    puts "What do you want to do?"
def
    puts "Options: play game, quit, score"
option = gets.chomp
case option
when "play game"
    puts "Let's start"
when "quit"
    puts "Sorry that you're leaving"
when "score"
    puts "Score +100"
end
