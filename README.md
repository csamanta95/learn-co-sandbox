input = ""
while input != "Mommmm!!"
  puts "Stop hitting yourself!"
  input = gets.chomp
end

basket = ["apple 1","apple 2","apple 3","apple 4","apple 5","apple 6","apple 7","apple 8","apple 9","apple 10"]
basket.each do |apple|
  puts "Taking out #{apple}"
end