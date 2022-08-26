# arrays

friends = ["derek", "jusin", "zach", "issa"]

ticket_cost = [15, 16, 19, 34]

decibel_level = [3.5, 6.7, 34.5, 64.4]

enjoyment = [true, false, true, false]

#Removes the last element from self and returns it.

#removes "issa" and returns it.
friends.pop
#removes 34 and returns it
ticket_cost.pop
#removes 64.4 and returns it
decibel_level.pop
#removes false and returns it
enjoyment.pop



# Pushes the given object(s) on to the end of this array. This expression returns the array itself, so several appends may be chained together.

#returns ["derek", "justin", "zach", "issa", "periun", "tyler"]
friends.push("periun", "tyler")
#returns [15, 16, 19, 34, 45]
ticket_cost.push(45)
#returns [3.5, 6.7, 34.5, 64.4, 22.3]
decibel_level.push(22.3)
#returns [true, false, true, false, false]
enjoyment.push(false)



#Removes the first element of self and returns it (shifting all other elements down by one)

#removes "derek" and returns it
friends.shift
#removes 15 and returns it
ticket_cost.shift
#removes 3.5 and returns it
decibel_level.shift
#removes true and returns it
enjoyment.shift



#repends objects to the front of self, moving other elements upwards

#returns ["periun", "tyler", "derek", "justin", "zach", "issa", ]
friends.unshift ("periun", "tyler")
#returns [45, 15, 16, 19, 34]
ticket_cost.unshift(45)
#returns [3.4, 3.5, 6.7, 34.5, 64.4]
decibel_level.unshift(3.4)
#returns [true, true, false, true, false]
enjoyment.unshift(true)






#index positions are the positions of the list of arrays you made. You start with 0 and count up. an example of this would be in the variable "friends" derek would be 0, justin would be 1, and zach would be 2.




#a new method is the replace method it "Replaces the contents of self with the contents of other_ary, truncating or expanding if necessary."
