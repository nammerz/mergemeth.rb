mergemeth.rb
============

food = {name: "sushi"}
type = {fish: "butterfish"}

puts food.merge(type)
puts food
puts type

food1 = {name1: "sashimi"}
type1 = {fish1: "fatty tuna"}

puts food1.merge!(type1)
puts food1
puts type1

# the merge without the bang does not permanently change "food"
# the merge with the bang does change it permanently
