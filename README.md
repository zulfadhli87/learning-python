# learning-python
basic python 
Currently doing the course "Introduction to Python: Fundamental" by Microsoft. Most of python flow and mini project in this repo are based from the course.



# [ ] assign a string 5 or more letters long to the variable: street_name
# [ ] print the 1st, 3rd and 5th characters

street_name = "hello"
print (street_name[0])
print (street_name[2])
print (street_name[4])


# [ ] Create an input variable: team_name - ask that second letter = "i", "o", or "u"
# [ ] Test if team_name 2nd character = "i", "o", or "u" and print a message
# note: use if, elif and else

team_name = input("type your team name")
if team_name[1].lower == "i":
  print ("your second letter is i")
elif team_name[1].lower == "o":
  print ("your second letter is o")
elif team_name[1].lower == "u":
  print ("your second letter is u")
else:
  print (" you second letter is " + team_name[1] )
  
 
